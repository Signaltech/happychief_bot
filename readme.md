# HappyChief_bot
## Бот для отправки на почту сообщений вашему шефу

### Команды
**/reg** _имя_ - Регистрация у бота под именем
**/reg**
_имя_ см. выше.

**/xyi** _сообщение_ - Сообщение, которое будет отправлено в теле письма
**/xyi**
_сообщение_ см. выше.

**/help** - Подсказка по боту.

### Настройка
Для настройки, нужно поправить файл конфигурации **/config.json**:
* _token_ - токен в телеграфе
* _mail.to_ - куда отправлять мыло
* _mail.from_ - валидное(существующее) мыло. Иначе на некоторые(mail.ru)
    почтовые сервисы приходить не будет.