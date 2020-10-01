# git push

> Отправка коммитов в удаленный репозиторий.

- Отправить локальные изменения в текущей ветке удаленному аналогу:

`git push`

- Отправить локальные изменения в данной ветке удаленному аналогу:

`git push {{remote_name}} {{local_branch}}`

- Опубликовать текущую ветку в удаленном репозитории, задав имя удаленной ветки:

`git push {{remote_name}} -u {{remote_branch}}`

- Отправить изменения во всех локальных ветвях их аналогам в данном удаленном репозитории:

`git push --all {{remote_name}}`

- Удалить ветку в удаленном репозитории:

`git push {{remote_name}} --delete {{remote_branch}}`

- Удалить удаленные ветки, у которых нет локального аналога:

`git push --prune {{remote_name}}`

- Опубликовать теги, которых еще нет в удаленном репозитории:

`git push --tags`