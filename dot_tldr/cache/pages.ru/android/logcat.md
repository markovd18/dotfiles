# logcat

> Дамп лог (журнал) системных сообщений, включая трассировку стека при возникновении ошибки и информационные сообщения, регистрируемые приложениями.
> Больше информации: <https://developer.android.com/studio/command-line/logcat>.

- Показать системные логи:

`logcat`

- Записать системные логи в файл:

`logcat -f {{путь/до/файла}}`

- Показать строки, соответствующие регулярному выражению:

`logcat --regex {{регулярное_выражение}}`
