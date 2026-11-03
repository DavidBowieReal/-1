# 50 Смешанных заданий по ООП
## Задания моделируют архитектурные сценарии коммерческих Flutter-приложений (State Management, Networking, UI Layouts, Analytics, Security).

# Блок 1: Модели данных, DTO и конструкторы
### Неизменяемая карточка товара (Immutable Product): Создайте константную модель товара с обязательными полями, расчетом цены со скидкой и валидацией неотрицательной стоимости в списке инициализации.
<img width="1856" height="697" alt="image" src="https://github.com/user-attachments/assets/4a0790ec-8950-4ab7-8af8-cc9d28aeb7a5" />

### Парсер профиля пользователя с безопасными дефолтами: Реализуйте конструктор User.fromJson(Map<String, dynamic> json) с обработкой отсутствующих полей и защитой от TypeError.
<img width="1899" height="743" alt="image" src="https://github.com/user-attachments/assets/64f94624-c136-4cc9-a9a8-1ebb27426e67" />

### Multiton локалей приложения: Спроектируйте класс AppLocale с фабричным конструктором, возвращающим единственный экземпляр для каждого языка: AppLocale("ru"), AppLocale("en").
<img width="1902" height="751" alt="image" src="https://github.com/user-attachments/assets/52372b9d-f8ed-42bd-b579-4cdecafb5ce6" />

### Модель геоточки с парсингом строки: Класс GeoPoint с именованным конструктором GeoPoint.fromString("55.751244, 37.618423").
<img width="1892" height="733" alt="image" src="https://github.com/user-attachments/assets/6eafe785-7386-4b82-96b7-62a5190bd25a" />

### Конструктор визитки из сущности БД: Напишите фабричный конструктор ContactCard.fromDatabaseRecord(Map<String, Object?> row).
<img width="1887" height="743" alt="image" src="https://github.com/user-attachments/assets/cbcd8f3e-f55f-4004-8a9c-413b7cd7b02b" />

### Клонирование с изменением полей (copyWith): Добавьте метод UserModel copyWith({String? name, String? avatarUrl}) для неизменяемой модели.
<img width="1912" height="745" alt="image" src="https://github.com/user-attachments/assets/ea7ec05b-a2d9-43eb-8a4c-e89438ace121" />

### Конструктор диапазона дат: Класс DateRange(this.start, this.end) со списком инициализации, выбрасывающим AssertionError, если дата окончания раньше даты начала.
<img width="1899" height="709" alt="image" src="https://github.com/user-attachments/assets/3c082bf4-a2e0-4ef4-9d54-371a4a5d50b3" />

### DTO банковской транзакции: Класс TransactionDto с именованными конструкторами для пополнения (TransactionDto.deposit), списания (TransactionDto.withdrawal) и перевода (TransactionDto.transfer).
<img width="1857" height="705" alt="image" src="https://github.com/user-attachments/assets/9cd0059e-66e1-41e1-9196-476d0ba772a3" />

### Парсер конфигурации окружения (Environment): Фабричный конструктор EnvConfig.fromEnvironment(), читающий флаги через const String.fromEnvironment().
<img width="1904" height="737" alt="image" src="https://github.com/user-attachments/assets/b72e7ac7-c2c8-4cf7-83ed-18e725b1be0d" />

### Кастомный оператор эквивалентности: Переопределите оператор == и метод hashCode для класса CartItem на основе совпадения полей productId и selectedSize.
<img width="1904" height="734" alt="image" src="https://github.com/user-attachments/assets/9c4b40ba-b36b-4984-89ca-1277a3239bcc" />

# Блок 2: Наследование и иерархия UI-компонентов

### Иерархия системных уведомлений: Базовый класс InAppNotification (таймаут, заголовок) и наследники SuccessNotification, WarningNotification, CriticalAlertNotification с разным цветом и иконкой.
<img width="1851" height="700" alt="image" src="https://github.com/user-attachments/assets/f2a7076c-e662-4845-b982-fa7e63073c70" />

### Компоненты диалоговых окон: Базовый класс BaseDialog с шаблоном отрисовки шапки и подвала, и наследник ConfirmActionDialog с кнопками «Подтвердить» и «Отмена».
<img width="1845" height="688" alt="image" src="https://github.com/user-attachments/assets/b0ce9f60-eead-4134-b148-26174275dd26" />

### Иерархия медиаплееров: Базовый класс MediaPlayer (методы play(), pause(), seek()) и специализированные наследники AudioPlayer и HlsVideoPlayer.
<img width="1847" height="699" alt="image" src="https://github.com/user-attachments/assets/4ee0e17b-7095-42ec-870a-49ca028ce6af" />

### Модели сенсоров смартфона: Базовый класс HardwareSensor и подклассы AccelerometerSensor (оси X, Y, Z) и BarometerSensor (давление в гПа).
<img width="1857" height="690" alt="image" src="https://github.com/user-attachments/assets/072d8dd3-d546-4e59-849d-097cff0336f3" />

### Система тарифов подписки: Базовый класс SubscriptionPlan и наследники MonthlyPlan, AnnualDiscountPlan (скидка 20%) и FamilyPlan (множитель цены за участников).
<img width="1860" height="695" alt="image" src="https://github.com/user-attachments/assets/3d74c1c4-9e7a-46d3-8980-235247121ab2" />

### Слои графического редактора: Базовый класс CanvasLayer (прозрачность, видимость, z-index) и подклассы VectorLayer, RasterBitmapLayer, TextLayer.
<img width="1842" height="690" alt="image" src="https://github.com/user-attachments/assets/4562a1e1-b0f3-4201-a3a3-cc98780ad657" />

### Иерархия платежных шлюзов: Базовый класс PaymentGateway с защищенным методом логирования и наследники SbpGateway (Система быстрых платежей) и BankCardGateway.
<img width="1904" height="730" alt="image" src="https://github.com/user-attachments/assets/a777de92-b7c6-4c92-9cc5-ad3c6e9a0df4" />

### Экраны онбординга: Базовый экран обучающего тура с кнопкой пропуска и конкретные шаги с уникальными иллюстрациями.
<img width="1833" height="687" alt="image" src="https://github.com/user-attachments/assets/3e3117d3-4570-4045-946f-a4e51bf5a28e" />

### Кастомная кнопка с состояниями: Базовый класс WidgetButton и подкласс AsyncLoadingButton, отображающий индикатор загрузки при активном асинхронном действии.
<img width="1911" height="748" alt="image" src="https://github.com/user-attachments/assets/2d9fdd9a-4a96-4d27-b115-893ffa1d35ee" />

### Иерархия логгеров приложения: Базовый класс AppLogger и подклассы ConsoleLogger (форматированный вывод в терминал) и FileCrashLogger (запись на диск).
<img width="1896" height="743" alt="image" src="https://github.com/user-attachments/assets/81c17992-109b-4ac1-adee-1c6a77511b13" />

# Блок 3: Абстрактные контракты, интерфейсы и репозитории

### Репозиторий каталога товаров (Repository Pattern): Объявите интерфейс ProductRepository с методами Future<List<Product>> getAll(), Future<Product> getById(int id) и создайте две реализации: NetworkProductRepository и MockProductRepository.
<img width="1907" height="741" alt="image" src="https://github.com/user-attachments/assets/24d50a56-f320-470a-97dd-7d711ccf9b77" />

### Интерфейс биометрической аутентификации: Спроектируйте интерфейс BiometricAuthService с методами canAuthenticate() и authenticate(). Напишите реализацию-заглушку для тестов.
<img width="1864" height="682" alt="image" src="https://github.com/user-attachments/assets/275ea563-410d-486f-b49b-abc4ad1ce8b4" />

### Шифрование пользовательских данных: Интерфейс CryptoService с методами encrypt(String plainText) и decrypt(String cipherText). Реализуйте класс AesCryptoService.
<img width="1864" height="698" alt="image" src="https://github.com/user-attachments/assets/7862bfa9-50cc-4387-835a-b12f4a81fd0e" />

### Контракт аналитического провайдера: Интерфейс AnalyticsProvider с методом logEvent(String name, Map<String, Object> params). Реализуйте множественную отправку через класс CompositeAnalyticsProvider.
<img width="1853" height="703" alt="image" src="https://github.com/user-attachments/assets/fe7f4c15-4857-4b11-8e08-802a42f66afb" />

### Интерфейс геолокатора: Спроектируйте контракт получения координат устройства с поддержкой стрима обновлений позиции Stream<GeoPoint> get positionStream.
<img width="1906" height="729" alt="image" src="https://github.com/user-attachments/assets/3e1e3c8c-f3d1-4af6-baff-634678372da6" />

### Служба локальных уведомлений: Интерфейс NotificationSender с методами отправки мгновенных и отложенных системных пушей.
<img width="1860" height="688" alt="image" src="https://github.com/user-attachments/assets/e8e19fde-f8a3-4dfe-bc02-9fe4482a926a" />

### Контракт синхронизатора баз данных: Абстрактный класс DataSyncEngine с абстрактными методами fetchRemoteDelta() и applyLocalChanges().
<img width="1891" height="740" alt="image" src="https://github.com/user-attachments/assets/5e9466df-82c2-44f7-a669-8998e1bcd3f1" />

### Провайдер сетевого статуса: Интерфейс ConnectivityService с геттером bool isOnline и стримом событий потери интернета.
<img width="1894" height="735" alt="image" src="https://github.com/user-attachments/assets/02f624d9-9277-4e38-ab74-b1ee8fbeca19" />

### Хранилище ключ-значение (KeyValueStorage): Спроектируйте интерфейс с обобщенными методами T? read<T>(String key) и Future<void> write<T>(String key, T value).
<img width="1902" height="746" alt="image" src="https://github.com/user-attachments/assets/67257f7b-fae8-4781-b83a-252871645834" />

### Интерфейс экспортера отчетов: Контракт ReportExporter с реализациями PdfReportExporter и ExcelReportExporter.
<img width="1909" height="752" alt="image" src="https://github.com/user-attachments/assets/3da48033-b07a-4416-9051-c776527a9b50" />

# Блок 4: Миксины и повторное использование функционала

### Миксин дебаунса событий (Anti-Spam Click): Миксин DebounceMixin, предотвращающий повторный вызов одного и того же действия чаще чем раз в 500 мс.
<img width="1903" height="744" alt="image" src="https://github.com/user-attachments/assets/0820be6d-a555-41bf-a3ce-1b5e62bde070" />

### Миксин восстановления состояния экрана (RestorationMixin): Миксин, автоматически сохраняющий текстовые поля ввода при сворачивании приложения.
<img width="1866" height="688" alt="image" src="https://github.com/user-attachments/assets/2d090641-011c-460d-ab7a-9f797fc8a346" />

### Миксин проверки сетевого соединения: Миксин NetworkAwareMixin, внедряющий в презентер экрана проверку доступности интернета перед выполнением любого запроса.
<img width="1909" height="760" alt="image" src="https://github.com/user-attachments/assets/4f7cfb92-9367-4b3d-837c-5b22555295fc" />

### Миксин форматирования цен и валют: Миксин CurrencyFormatterMixin, предоставляющий готовый метод преобразования чисел в красивый денежный формат.
<img width="1911" height="747" alt="image" src="https://github.com/user-attachments/assets/2a2a3303-2d00-48fa-95c8-267454a94752" />

### Миксин таймера автообновления: Миксин PeriodicRefreshMixin, запускающий периодический опрос сервера каждые 30 секунд при активном экране.
<img width="1858" height="703" alt="image" src="https://github.com/user-attachments/assets/ad056635-8d39-40de-8a73-a6aa8a00ae31" />

### Миксин валидации паспортных данных: Миксин PassportValidationMixin с методами строгой проверки серии, номера и кода подразделения.
<img width="1904" height="735" alt="image" src="https://github.com/user-attachments/assets/b930b138-20da-4654-91f2-97b7d5d37855" />

### Миксин анимации затухания (FadeAnimationController): Подмешиваемый контроллер управления прозрачностью элемента от 0.0 до 1.0.
<img width="1904" height="741" alt="image" src="https://github.com/user-attachments/assets/5e789f28-025a-47a1-869f-59c742f170aa" />

### Миксин переключения темы: Миксин, предоставляющий экрану быстрый доступ к текущей цветовой палитре (темная/светлая).
<img width="1909" height="747" alt="image" src="https://github.com/user-attachments/assets/a9b9a99b-f077-4e1b-b57b-5bfef5da8c7c" />

### Миксин глубоких ссылок (DeepLinkHandlerMixin): Миксин, парсящий входящие URI-схемы приложения и открывающий целевые экраны.
<img width="1866" height="702" alt="image" src="https://github.com/user-attachments/assets/63e6e59e-13e4-4aa7-9673-82e4eedf50c5" />

### Миксин аудита действий администратора: Подмешиваемый модуль, отправляющий критические действия модератора на выделенный сервер безопасности.
<img width="1913" height="740" alt="image" src="https://github.com/user-attachments/assets/d2b1dbe9-a482-4d68-a7bc-ca3b195748c2" />

# Блок 5: Современные модификаторы классов и архитектурные стейты

### Sealed-состояние корзины интернет-магазина: Создайте sealed class CartState с состояниями: CartEmpty, CartLoading, CartLoaded(List<Item> items, double total), CartCheckoutError(String error). Напишите функцию обработки состояний через исчерпывающий switch.
<img width="1902" height="732" alt="image" src="https://github.com/user-attachments/assets/04f830c5-03aa-4ae0-bafa-5960416ca10f" />

### Sealed-иерархия сетевого ответа (Result Pattern): Реализуйте sealed class Result<T> с подтипами Success<T>(final T data) и Failure<T>(final Exception exception).
<img width="1900" height="730" alt="image" src="https://github.com/user-attachments/assets/8289c678-9cf1-4f82-a75a-f80107137515" />

### Архитектура UI-событий экрана логина: Создайте sealed class LoginEvent с событиями LoginEmailChanged(String email), LoginPasswordChanged(String pass), LoginSubmitted.
<img width="1907" height="745" alt="image" src="https://github.com/user-attachments/assets/d8e9f064-0d12-49a4-94e6-d93e05d31e06" />

### Модификатор final class для безопасности криптоключа: Объявите класс final class EncryptionKey, запретив любое его расширение или реализацию вне текущей библиотеки.
<img width="1866" height="663" alt="image" src="https://github.com/user-attachments/assets/b3c2afb2-e09c-4e75-8b10-fcb90693a054" />

### Модификатор interface class для публичного API SDK: Разработайте интерфейсный класс платежного терминала, запретив прямое наследование логики клиентами библиотеки.
<img width="1870" height="691" alt="image" src="https://github.com/user-attachments/assets/fecc7cc2-4d4b-4ade-bb94-78e3f8e16387" />

### Исчерпывающий роутинг экрана через Sealed Route: Спроектируйте sealed class AppRoute для типобезопасной навигации во Flutter.
<img width="1913" height="736" alt="image" src="https://github.com/user-attachments/assets/ca7cb119-9010-447d-a9ea-d5db5a3a32c6" />

### Паттерн «Команда» (Command Pattern): Создайте абстрактный класс Command с методом execute() и undo() для реализации функции отмены действий в редакторе текста.
<img width="1908" height="730" alt="image" src="https://github.com/user-attachments/assets/1008076a-3d16-48f0-b3b2-e4484366e06b" />

### Паттерн «Строитель» (Builder): Реализуйте NotificationBuilder с цепочечными вызовами .setTitle().setBody().setIcon().build().
<img width="1907" height="743" alt="image" src="https://github.com/user-attachments/assets/bf5960e0-41e9-4fde-928f-f2b9c49d39fe" />

### Паттерн «Наблюдатель» (Observer / EventBus): Создайте легковесную шину событий с классами событий и методами подписки/отписки.
<img width="1908" height="741" alt="image" src="https://github.com/user-attachments/assets/d431b301-a5fe-4008-a3d4-d440ef18bf9f" />

### Комплексный архитектурный модуль заказа такси (Production Case)
<img width="1911" height="737" alt="image" src="https://github.com/user-attachments/assets/2a37a3bd-9565-4c06-a3d0-0690320b582d" />
