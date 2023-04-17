# RosTelecom_avtotests
Объект тестирования: новый интерфейс авторизации в личном кабинете от заказчика Ростелеком
Сайт:https://b2c.passport.rt.ru
Для запуска необходимо:
1)Клонировать репозиторий
2)Удалить файл "тест-кейсы и баг-репорты RosTelecom.xlsx"
3)Установить зависимости в новое виртуальное окружение >>> pip install -r requirements.txt
NB! тесты настроены для запуска с помощью RUN;
    прохождение некоторых тестов невозможно изза отсутствия валидных данных;
    прохождение некоторых тестов невозможно изза возникновения капчи на странице
    
В корне проекта находятся следующие файлы:
requirements.txt - список используемых библиотек
comfirm.py - файл с фикстурами
locators.py - список локаторов проекта
settings.py - список используемых переменных
тест-кейсы и баг-репорты RosTelecom.xlsx - файл, содержащий тест-кейсы и баг-репорты

в папке tests находятся следующие файлы:
test_base_page.py - тестирует функционал страницы авторизации
test_auto_page.py - тестирует разные способы авторизации на сайте
test_pass_recovery_page.py - тестирует функционал страницы смены пароля
test_reg_page.py - тестирует разные способы регистрации на сайте
