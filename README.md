Дипломный проект курса "Инженер по тестированию: от новичка до автоматизатора"
Задания по теме "Автотесты для API"
Тестирование эндпоинтов API для Stellar Burgers. 
Это космический фастфуд: можно собрать и заказать бургер из необычных ингредиентов.
Файлы
- tests/  -  каталог с тестами 
- tests/test_create_ordeer.py  -  проверки создания заказа
- tests/test_create_user.py  -  проверки создания пользователя
- tests/test_get_order.py  -  проверки получения заказа
- tests/test_login_user.py  -  проверки авторизации пользователя
- tests/test_update_user.py  -   проверки изменения данных пользователя
- tests/conftest.py  -  файл с фикстурами
- data.py  -  файл с постоянными использукемыми в проверках
- help.py  -  вспомогательные методы используемые в проверках

Команды
Установить в зависимости — pip freeze > requirements.txt
Установить pytest — pip install pytest
Установить библиотеку allure-pytest — pip install allure-pytest
Запустить тесты — pytest tests --alluredir=allure_results
Посмотреть веб отчет — allure serve allure_results
Посмотреть степень покрытия — pytest --cov  