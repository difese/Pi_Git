# Синхронизация с удалённым (внешним) репозиторием

Посмотреть список текущих онлайн-репозиториев можно командой `$ git remote`, добавить другие - с помощью команды `$ git remote add [имя] [URL]` (например `$ git remote add yandex https://github.com/difese/уandex`).

Команда `$ git remote show [имя]` показывает информацию о репозитории.

Команда `$ git remote remove [имя]` удаляет удалённый (внешний) репозиторий с заданным именем.

Команда `$ git push [удалённый репозиторий] [ветка]` загружает все изменения локальной ветки в удалённый репозиторий.

Команда `$ git fetch [удалённый репозиторий]` скачивает всю историю из удалённого репозитория.

Команда `$ git merge [удалённый репозиторий]/[ветка]` вносит изменения из ветки удалённого репозитория в текущую ветку локального репозитория.

Команда `$ git pull [удалённый репозиторий]` загружает историю из удалённого репозитория и объединяет её с локальной (pull = fetch + merge).

[<< Вернуться к содержанию](../../readme.md)