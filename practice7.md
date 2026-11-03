## 50 Смешанных заданий по обработке данных

### Блок 1: Числа, финансы и расчеты корзины (1–10)

1. ### Калькулятор скидки с промокодом:** Рассчитайте итоговую стоимость заказа при условии: скидка 15%, но не более 500 рублей. <img width="1877" height="432" alt="image" src="https://github.com/user-attachments/assets/0a0a6338-d383-426a-9fd0-1826fec266ff" />

2. ### Форматирование цены по стандарту валют:** Преобразуйте число `15400900.5` в строку `"15 400 900.50 ₽"`.<img width="1820" height="576" alt="image" src="https://github.com/user-attachments/assets/2e3078fa-bfe0-481f-882d-10c659f801c2" />

3. ### Расчет кешбэка баллами:** Начислите 1 балл за каждые полные 100 рублей чека, используя оператор целочисленного деления `~/`.<img width="1871" height="557" alt="image" src="https://github.com/user-attachments/assets/5ffa37c4-26f9-402a-81b7-a11351198ff6" />

4. ### Ограничитель диапазона (Clamp):** Напишите функцию, ограничивающую уровень громкости динамика в диапазоне от `0.0` до `1.0`.<img width="1869" height="413" alt="image" src="https://github.com/user-attachments/assets/bf9ff7d3-dc78-47c0-b590-517e9fbc645b" />

5. ### Конвертер байтов в мегабайты:** Преобразуйте размер файла из байтов в МБ с округлением до одного знака после запятой.<img width="1829" height="549" alt="image" src="https://github.com/user-attachments/assets/34765a45-6ded-462b-b946-e49c1d25887d" />

6. ### Вычисление процентного прогресса:** По текущему шагу `current` и общему числу шагов `total` верните `double` от `0.0` до `1.0`.<img width="1883" height="544" alt="image" src="https://github.com/user-attachments/assets/c355a018-c0f4-4985-b8c2-1cc830b86d74" />

7. ### Округление до ближайшего десятка:** Округлите переданное число вверх до ближайшего числа, кратного 10 (например, `43` -> `50`).<img width="1887" height="552" alt="image" src="https://github.com/user-attachments/assets/d73f3750-3fa2-4645-932a-785e4cc2a6a5" />


8. ### Калькулятор стоимости доставки:** Базовая ставка 200 руб. + 30 руб. за каждый километр свыше 5 км.<img width="1568" height="737" alt="image" src="https://github.com/user-attachments/assets/0b30f49c-2309-4dea-a7f8-af67982ecf11" />

9. ###  Проверка делимости без остатка:** Определите, делится ли размер скачиваемого пакета ровно на блоки по 1024 байта.<img width="1882" height="833" alt="image" src="https://github.com/user-attachments/assets/fb02ebc0-8fe8-43ea-ad6e-b99c829e81c7" />

10. ### Парсер диапазона цен:** Извлеките минимальную и максимальную цену из строки `"1500 - 4500 руб"`.<img width="1869" height="696" alt="image" src="https://github.com/user-attachments/assets/e1412926-083f-4c9d-a411-f3a543af37ee" />


### Блок 2: Строки, валидация полей и парсинг текста (11–20)

11. ### Валидатор пароля на регулярных выражениях:** Проверьте пароль на наличие минимум 8 символов, одной цифры и одной заглавной буквы.<img width="1878" height="536" alt="image" src="https://github.com/user-attachments/assets/d651b635-3668-461b-8f57-6bb974224d49" />


12. ### Очистка поискового ввода:** Удалите из поискового запроса двойные пробелы, спецсимволы `#`, `$`, `%` и приведите к нижнему регистру.<img width="1874" height="543" alt="image" src="https://github.com/user-attachments/assets/58783160-7600-4b5d-bf1d-524160182b97" />

13. ### Генератор сокращенного имени автора:** Преобразуйте `"Иванов Иван Иванович"` в `"Иванов И. И."`.<img width="1868" height="519" alt="image" src="https://github.com/user-attachments/assets/0c5e4351-62e9-4a0e-9922-d840f5c02f1b" />

14. ### Парсинг HEX-цвета для Flutter:** Преобразуйте строку вида `"#FF5722"` в целочисленное значение цвета `int` (`0xFFFF5722`).<img width="1894" height="762" alt="image" src="https://github.com/user-attachments/assets/1d14f5f6-e5c7-45cf-8d70-1a6db1f8d071" />

15. ### Форматирование таймера звонка:** Переведите количество секунд `int seconds = 125` в строку вида `"02:05"`.<img width="1800" height="482" alt="image" src="https://github.com/user-attachments/assets/a4bc32df-95d4-4183-ad18-01b7fe0c77af" />

16. ### Скрытие номера телефона:** Преобразуйте `"+79991234567"` в `"+7 (999) ***-**-67"`.<img width="1895" height="550" alt="image" src="https://github.com/user-attachments/assets/5d997eea-61e5-42d5-bfb8-3a9b90844257" />

17. ### Определитель языка текста (Кириллица/Латиница):** Определите, содержит ли строка символы русского алфавита с помощью проверки диапазонов кодовых точек.<img width="1855" height="876" alt="image" src="https://github.com/user-attachments/assets/d6617ba7-7814-4dea-8975-a07b13c1b5e7" />

18. ### Генератор слага (Slugify):** Преобразуйте заголовок статьи `"Быстрый старт во Flutter!"` в `"bystryi-start-vo-flutter"`.<img width="1835" height="771" alt="image" src="https://github.com/user-attachments/assets/a6270790-3be4-4bbb-b79c-5241ae9465d1" />

19. ### Подсчет слов в заметке:** Подсчитайте количество слов в тексте заметки, разделенных пробелами и переносами строк.<img width="1876" height="641" alt="image" src="https://github.com/user-attachments/assets/43462071-7e52-4d17-abc5-92c2f4238df6" />


20. ### Выделение тегов из текста:** Извлеките все хештеги из сообщения блога (слова, начинающиеся с `#`).<img width="1872" height="744" alt="image" src="https://github.com/user-attachments/assets/b9111bc6-ce7a-4a0e-83ea-bb25e93aee84" />


### Блок 3: Списки, пагинация и фильтрация каталога (21–30)

21. ### Фильтр каталога по диапазону цен:** Из списка карточек товаров отберите только те, у которых цена находится в заданном диапазоне.<img width="1879" height="881" alt="image" src="https://github.com/user-attachments/assets/f4cf5a94-e835-474e-a992-21589cbc223e" />

22. ### Удаление завершенных задач из To-Do списка:** Отфильтруйте список задач, оставив только элементы со статусом `isCompleted == false`.<img width="1099" height="449" alt="image" src="https://github.com/user-attachments/assets/bf431669-0f15-43a1-8011-575a43039160" />

23. ### Инверсия порядка чатов:** Разверните список сообщений без создания промежуточных копий в памяти.<img width="1089" height="517" alt="image" src="https://github.com/user-attachments/assets/266b3e78-f5a9-4167-8ea8-289a2a6205a1" />

24. ### Склейка двух списков баннеров:** Объедините системные промо-акции и персональные предложения с помощью spread-оператора `...`.<img width="1103" height="493" alt="image" src="https://github.com/user-attachments/assets/75ae785f-839f-4313-a747-93b890cf6341" />

25. ### Поиск максимального элемента без библиотек:** Найдите товар с наивысшим рейтингом в списке с помощью метода `.reduce()`.<img width="1892" height="612" alt="image" src="https://github.com/user-attachments/assets/795c4751-9a8c-4b7e-8d86-6cb5ad43a080" />

26. ### Чередование элементов списка:** Вставьте рекламный баннер после каждого 5-го элемента ленты новостей.<img width="1850" height="656" alt="image" src="https://github.com/user-attachments/assets/e93b5395-29cb-4b8b-9c36-b4bbfd38f5ce" />

27. ### Проверка идентичности двух списков:** Напишите функцию, проверяющую, содержат ли два списка одинаковые элементы на тех же позициях.<img width="1872" height="645" alt="image" src="https://github.com/user-attachments/assets/a328f7c1-6402-4111-a2de-69076791553b" />

28. ### Извлечение уникальных категорий:** Из списка всех товаров магазина сформируйте `List<String>` уникальных названий категорий.<img width="1852" height="507" alt="image" src="https://github.com/user-attachments/assets/0e7e2232-6401-4fc3-bdcd-ae1bb4ab2e10" />

29. ### Сортировка списка по нескольким полям:** Отсортируйте список товаров сначала по доступности на складе, а затем по возрастанию цены.<img width="1818" height="602" alt="image" src="https://github.com/user-attachments/assets/8fba1659-5fc7-4259-a583-c95e7968ccdb" />

30. ### Постраничная группировка (Chunking):** Разбейте длинный список из 100 элементов на пачки (страницы) по 10 элементов.<img width="1867" height="758" alt="image" src="https://github.com/user-attachments/assets/7008d819-257b-4745-b466-dc04e49d8458" />


### Блок 4: Map, JSON-сериализация и кэширование (31–40)

31. ### Десериализация профиля:** Напишите парсер словаря `Map<String, dynamic>` в безопасные локальные переменные с дефолтными значениями.<img width="1868" height="594" alt="image" src="https://github.com/user-attachments/assets/05006a8d-79be-44ce-89c3-ffb73d750803" />

32. ### Конвертация списка в ассоциативную карту:** Преобразуйте `List<User>` в `Map<int, User>`, где ключом выступает уникальный `id`.<img width="1875" height="658" alt="image" src="https://github.com/user-attachments/assets/35ab4df8-c532-491d-bc90-870d7c6eab5f" />

33. ### Слияние локального и серверного профиля:** Объедините настройки приложения из кэша и свежие настройки с бэкенда с приоритетом сервера.<img width="1920" height="865" alt="image" src="https://github.com/user-attachments/assets/97697ede-db51-460b-9f1e-e3bb72c528fc" />

34. ### Удаление ключей с null-значениями:** Очистите словарь от всех пар, где значение равно `null`, перед отправкой POST-запроса.<img width="1873" height="823" alt="image" src="https://github.com/user-attachments/assets/2b2de0f5-7e10-4197-ae45-8a2440061807" />

35. ### Кэш экранов (LRU-концепт):** Реализуйте простейшую карту последних 5 открытых страниц, удаляя самый старый элемент при переполнении.<img width="1667" height="865" alt="image" src="https://github.com/user-attachments/assets/494df945-cdbe-4b06-b7f9-5ba80c70e4b9" />

36. ### Инверсия карты (Значения становятся ключами):** Поменяйте местами ключи и значения в словаре `Map<String, String>` (гарантируя уникальность).<img width="1898" height="677" alt="image" src="https://github.com/user-attachments/assets/6bea777a-7ada-4150-a2ab-66acd53dec78" />

37. ### Подсчет суммы товаров по категориям:** На основе списка покупок верните `Map<String, double>`, где ключ — категория, а значение — общая сумма затрат.<img width="1803" height="648" alt="image" src="https://github.com/user-attachments/assets/e029aa8b-7932-4829-8504-de0c5798b4a2" />

38. ### Валидация обязательных JSON-полей:** Проверьте, содержит ли карта ответа сервера ключи `"status"`, `"data"` и `"timestamp"`.<img width="1662" height="428" alt="image" src="https://github.com/user-attachments/assets/be71cf76-3928-4761-9b5f-72eaae6da422" />

39. ### Построение дерева категорий:** Преобразуйте плоский список категорий с `parentId` в иерархическую карту подкатегорий.<img width="1880" height="778" alt="image" src="https://github.com/user-attachments/assets/322d0b9c-338c-4a22-af39-0d0b87d60504" />

40. ### Сериализация параметров фильтра в URL:** Соберите из словаря `{"brand": "Apple", "minPrice": 50000}` строку параметров `brand=Apple&minPrice=50000`.<img width="1895" height="808" alt="image" src="https://github.com/user-attachments/assets/eb4bd6cc-6cd6-4874-a0b6-e23c84b16017" />


### Блок 5: Sound Null Safety, Records и архитектурные пайплайны (41–50)

41. ### Парсер геолокации через Record:** Напишите функцию, принимающую строку `"54.01, 38.29"` и возвращающую кортеж `(double lat, double lon)?`.<img width="1082" height="559" alt="image" src="https://github.com/user-attachments/assets/5df1ced4-33b7-4bfb-bffd-6c8a0c27f8ba" />
42. **Резолвер состояний загрузки (Pattern Matching):** С помощью `switch` верните текст сообщения для состояний `(isLoading: true, hasError: false)`, `(isLoading: false, hasError: true)` и `(isLoading: false, hasError: false)`.<img width="1847" height="702" alt="image" src="https://github.com/user-attachments/assets/f793b3e5-e26a-4008-9eed-b3f1186b03dd" />

43. ### Безопасная цепочка вызовов (Deep Null Traversal):** Считайте улицу из вложенного объекта компании: `user?.company?.address?.street ?? "Адрес не указан"`.<img width="1864" height="474" alt="image" src="https://github.com/user-attachments/assets/01d00c63-9045-4835-a3d9-79c7fe87420e" />

44. ### Сопоставление типа ответа API:** Напишите функцию обработки ответа через сопоставление типов: `case int code`, `case String error`, `case Map data`.<img width="1869" height="566" alt="image" src="https://github.com/user-attachments/assets/4c4f7b84-7cdb-4d1c-95e6-367bb1268a24" />

45. ### Деструктуризация координат точки в цикле:** Пройдитесь по списку кортежей `List<(int x, int y)>` с прямой деструктуризацией `for (var (x, y) in points)`.<img width="1917" height="855" alt="image" src="https://github.com/user-attachments/assets/d1ad0a10-03ac-4488-a7e5-ec899a59debc" />

46. ### Обмен значений двух переменных без третьей:** Поменяйте местами значения переменных `a` и `b` с помощью синтаксиса кортежей: `(a, b) = (b, a)`.<img width="1249" height="288" alt="image" src="https://github.com/user-attachments/assets/2f73dfd4-5566-4005-bc79-ee7ea146eabf" />

47. ### Валидатор комплексной формы регистрации:** Функция возвращает Record `({bool isValid, List<String> errors})` с перечнем всех найденных ошибок формы.<img width="1889" height="791" alt="image" src="https://github.com/user-attachments/assets/653d77bb-85d5-44fb-bac2-a3581c431944" />

48. ### Обработка диапазона громкости через Switch Guard:** Используйте паттерн с условием `when`: `case int v when v > 80 => "Слишком громко!"`.<img width="1841" height="485" alt="image" src="https://github.com/user-attachments/assets/7c039326-62d9-4536-a894-eeab273fd189" />

49. ### Пайплайн очистки телефонной книги:** Дан список `List<String?>` с поврежденными записями. Очистите его от `null`, пустых строк и верните `Set<String>` уникальных нормализованных номеров.<img width="1857" height="571" alt="image" src="https://github.com/user-attachments/assets/75680e92-2842-4a20-9545-ef13b59d8912" />

50. ### Итоговый аналитический модуль корзины:**<img width="1280" height="580" alt="50" src="https://github.com/user-attachments/assets/af84ab31-bb27-44d9-b0f7-f84d48e34e52" />

    - Примите корзину покупок в виде `List<Map<String, dynamic>>`.
    - Рассчитайте общую стоимость позиций с учетом индивидуальных скидок.
    - Выделите категории товаров и проверьте бесплатность доставки (от 2000 руб.).
    - Верните результат в виде именованного кортежа `({double total, double discountAmount, bool isFreeDelivery})`.

---
