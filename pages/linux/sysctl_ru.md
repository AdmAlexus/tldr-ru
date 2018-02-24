# sysctl

> Чтение или редактирование на лету параметров ядра.

- Вывести все параметры и их значения:

`sysctl -a`

- Установить значение изменяемого параметра ядра:

`sysctl -w {{секция.параметр}}={{значение}}`

- Вывести число открытых файловых дескрипторов:

`sysctl fs.file-nr`

- Вывести максимально допустимое число одновременно открытых файлов.

`sysctl fs.file-max`

- Применить изменения из файла /etc/sysctl.conf:

`sysctl -p`