# GITHUB_Comands
Инициализация репозитория

git init
Клонирование репозитория


git clone <url>
Проверка статуса репозитория


git status
Добавление файлов к коммиту


git add <file>
# или чтобы добавить все изменения
git add .
Создание коммита


git commit -m "Сообщение коммита"
Просмотр истории коммитов


git log
Просмотр изменений в файлах


git diff
Переключение между ветками

git checkout <branch>
Создание новой ветки


git branch <new-branch>
Слияние веток


git merge <branch>
Удаление ветки


git branch -d <branch>
Отправка изменений в удалённый репозиторий


git push origin <branch>
Получение изменений из удалённого репозитория


git pull
Просмотр различий между локальной и удалённой версией


git fetch
git diff origin/<branch>
Отмена изменений


git checkout -- <file> # отмена изменений в рабочем каталоге
git reset --hard HEAD # отмена всех изменений и коммитов


git remote add origin <url>
Замените <url> на URL вашего репозитория на GitHub, который выглядит примерно так: https://github.com/ваш-пользователь/ваш-репозиторий.git.

Отправьте изменения на GitHub:

git push -u origin main
Здесь main — это имя ветки, в которую вы хотите отправить изменения. Если ваша ветка называется иначе (например, master), замените main на название вашей ветки.

Если вы работаете с несколькими ветками, убедитесь, что вы отправили все нужные ветки:
git push origin <branch>
