# SnakeGuardBot
Обновленная версия SnakeGuard, которая работает через Telegram и поддерживает прочие протоколы

## Поддерживаемые протоколы:
- XTLS
- MTProto
- Wireguard
- ShadowSocks
- AdGuard
- Прокси

## Инструкция по установке:

1.Скопируйте и вставьте в вашу консоль данную команду:
```bash
wget -O- https://raw.githubusercontent.com/JoricJim/SnakeGuardBot/main/scripts/init.sh | sh -s TG
```
> Обязательно замените `TG` на токен от вашего Telegram бота

2. После установки импортируйте конфигурацию и обновите SSL сертификат
3. Скачайте файлы из GitHub и в папке `/root/vpnbot/app` замените эти файлы
