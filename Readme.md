1.Поганять по тегам!

2.GIT!

git version - показує поточну встановлену версію гіта.

Для ініціалізації репозиторію - пишемо git init.

Щоб зрозуміти поточний стан репозиторію - пишемо git status

Щоб додати файл до staging area - пишемо git add <ім'я файлу>

Щоб зробити коміт - пишемо git commit -m "Опис комміту"

Щоб переглянути історію коммітів - пишемо git log. Ця команда покаже список коммітів та їх хешів.

Щоб перейти до конкретного комміту – пишемо git checkout <hash>

Щоб зв'язати віддалений репозиторій з локальним – один раз пишемо git remote add origin <адреса репозиторію>

Щоб глянути список віддалених репозиторіїв - пишемо git remote --v

Щоб залити код на віддалений репозиторій.

Щоб підтягнути код із віддаленого репозиторію - пишемо git pull origin master

ЯК ПРАЦЮВАТИ З ГІЛКАМИ
git branch - показує, на якій ви зараз гілки
git checkout -b <branch_name> - створює нову гілку з ім'ям <branch_name> і перемикається на цю гілку
git checkout <branch_name> - перемикається на існуючу гілку з ім'ям <branch_name>

Ідентифікація(один раз)

git config -global user.name "John Doe"
git config --global user.email johndoe@example.com

Налаштування щоб при ініціалізації репозиторію створювалась гілка main а не master

git config --global init.defaultBranch main
