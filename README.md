Финальное тестовое задание для студентов курса. Написание автоматизированных тестов с использованием PyTest и Selenium для интернет-магазина, в котором есть большое количество товаров, а также функционал поиска и сортировки / фильтрации товаров.

https://chromedriver.chromium.org/downloads - скачать версию Selenium WebDriver, совместимую с вашим браузером (тесты проводились в браузере Chrome)

Команда для запуска тестов

python3 -m pytest -v --driver Chrome --driver-path ${PATH_TO_DRIVER} tests_labirint/tests_labirint.py

Где ${PATH_TO_DRIVER} находится путь к драйверу Selenium для текущей ОС
