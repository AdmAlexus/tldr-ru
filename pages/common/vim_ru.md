# vim

> VIM (Vi IMproved, улучшенный Vi) - консольный текстовый редактор, имеющий несколько режимов для различных способов редактирования текста.
> Нажатие `i` переводит программу в режим редактирования (edit mode).
> `<Esc>` возращает программу обратно в обычный режим (normal mode), в котором не допускается простая вставка текста.

- Открыть файл:

`vim {{файл}}`

- Перейти в режим редактирования (режим вставки):

`<Esc>i`

- Копировать ("yank") или вырезать ("delete") текущую строку (вставить её можно с помощью `P`):

`<Esc>{{yy|dd}}`

- Отменить предыдущее действие:

`<Esc>u`

- Искать по шаблону в файле (нажмите `n`/`N` для перехода к следующему/предыдущему совпадению):

`<Esc>/{{поисковой_шаблон}}<Enter>`

- Выполнить поиск и замену с использованием регулярных выражений во всём файле (с начала, `1`, до конца, `$`):

`<Esc>:1,$s/{{поисковой_шаблон}}/{{замена}}/g<Enter>`

- Сохранить ("write") файл и выйти из программы ("quit"):

`<Esc>:wq<Enter>`

- Выйти из программы без сохранения:

`<Esc>:q!<Enter>`