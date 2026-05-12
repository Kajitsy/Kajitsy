# Инструкция по подключению к локальной сети [@Net_Secure_Bot](https://t.me/net_secure_bot)
Лучший VPN: [@Net_Secure_Bot](https://t.me/net_secure_bot)

Для подключения к локальной сети используется протокол AmneziaWG 2.0 и программа AmneziaWG:

Windows: https://github.com/amnezia-vpn/amneziawg-windows-client

Linux: https://github.com/amnezia-vpn/amneziawg-linux-kernel-module

Android: [Google Play Market](https://play.google.com/store/apps/details?id=org.amnezia.awg&hl=ru), [GitHub](https://github.com/amnezia-vpn/amneziawg-android)

iOS, iPadOS, MacOS: [App Store](https://github.com/amnezia-vpn/amneziawg-android)

Данные подключения не являются способом обхода блокировок и не должны конфликтовать с основным VPN-ом. В случае возникновения проблем пишите [@ystijak](https://github.com/amnezia-vpn/amneziawg-windows-client)

## Как подключиться:
### Windows:
0. Установите [AmneziaWG с GitHub](https://github.com/amnezia-vpn/amneziawg-windows-client)

1. Создаёте подключение к локальной сети в боте [@Net_Secure_Bot](https://t.me/net_secure_bot)

![g-1.png](img/g-1.png)

2. Получите Ваш файл и Ваш IP в локальной сети

![g-2.png](img/g-2.png)

#Красная стрелка - файл; Синяя стрелка - IP

3. Для удобства переименуйте файл в local.conf

![w-3.png](img/w-3.png)

4. Добавьте local.conf в AmneziaWG

![w-4.png](img/w-4.png)

#1. Добавьте туннель; 2. Выберите local.conf; 3. Нажмите Открыть

5. Подключитесь к туннелю local

![w-5.png](img/w-5.png)

#Красная стрелка - Ваш IP внутри локальной сети

### Linux (на примере CachyOS):

0. Установите [amneziawg-linux-kernel-module](https://github.com/amnezia-vpn/amneziawg-linux-kernel-module) по [инструкции с GitHub](https://github.com/amnezia-vpn/amneziawg-linux-kernel-module)

1. Создаёте подключение к локальной сети в боте [@Net_Secure_Bot](https://t.me/net_secure_bot)

![g-1.png](img/g-1.png)

2. Получите Ваш файл и Ваш IP в локальной сети

![g-2.png](img/g-2.png)

#Красная стрелка - файл; Синяя стрелка - IP

3. Для удобства переименуйте файл в local.conf

![l-3.png](img/l-3.png)


4. Переходите в каталог с файлом и копируйте его в /etc/amnezia/amneziawg (необходим доступ к sudo)

![l-4.png](img/l-4.png)

5. Запустите службу awg-quick с local.conf

![l-5.png](img/l-5.png)
