# Telegram
Кроссплатформенная система мгновенного обмена сообщениями (мессенджер) с функциями обмена текстовыми, голосовыми и видеосообщениями, а также стикерами, фотографиями и файлами многих форматов.
## Установка из репозитория <Badge type="warning" text="sysphus" />
**Telegram** можно установить любым привычным и удобным способом

**Установка через терминал**
::: code-group

```bash[apt-get]
su -
apt-get update
apt-get install telegram-desktop
```
```bash[epm]
epm -i telegram-desktop
```
:::

## Установка c помощью единой комманды управления пакетами 

При наличии пакета eepm, можно установить **Telegram** одной командой:

**Установка через терминал**

```bash
epm play telegram
```

## Установка c помощью Flatpak

При наличии пакета [Flatpak](/flatpak), можно установить **Telegram** одной командой:

```bash
flatpak install flathub org.telegram.desktop
```

## Проблема отображения уведомлений в Telegram

Если вместо уведомления с текстом пришедшего сообщения вы видите нечто подобное:

![telegram_1](/telegram_1.png)

1. Переходим в: *Настройки -> Уведомления* и отключаем пункт: **подсветка окна**

![telegram_2](/telegram_2.png)

2. Затем переходим в:* Настройки -> Продвинутые настройки -> Экспериментальные настройки* и включаем пункт **GNotification**

![telegram_3](/telegram_3.png)

3. Перезагружаем клиент

Теперь уведомления должны отображаться правильно!

![telegram_4](/telegram_4.png)

