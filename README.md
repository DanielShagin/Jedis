Тестовое задание для БАРС
Необходимо настроить эл.почту в Settings.py, либо закомментить указанные строки в views.py

перед тем как пользоваться приложением необходимо выполнить создание и синхр. базы с помощью команд
makemigrations;
migrate --run-syncdb
зетем проверить настройки базы, и с помощью админки добавить вопросы (Questions), планеты (Planets) и джедаев (Jedi)

в коде введено ограничение на добавление падаванов  padavanLimit = 3 в def card
