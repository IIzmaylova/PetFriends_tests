**Автотест Selenium для сайта PetFriends**

Тест, который проверяет, что на странице сайта: https://petfriends.skillfactory.ru/ , со списком питомцев пользователя:

- Присутствуют все питомцы.
- Хотя бы у половины питомцев есть фото.
- У всех питомцев есть имя, возраст и порода.
- У всех питомцев разные имена.
- В списке нет повторяющихся питомцев. (Сложное задание).
- В написанном тесте (проверка карточек питомцев) добавить неявные ожидания всех элементов (фото, имя питомца, его возраст).
- В написанном тесте (проверка таблицы питомцев) добавить явные ожидания элементов страницы.


**Как запустить:**
1) Скачать driver для браузера Chrome: 
   https://chromedriver.chromium.org/downloads 
2) Установить зависимости командой в терминале: 
   pip install -r requirements.txt
3) Запустить тест командой в терминале: 
   python -m pytest -v --driver Chrome --driver-path </путь к драйверу/chromedriver.exe> tests/tests_my_pets.py



