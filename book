Перевод на русский язык
--- 
Yii2 Разработка Приложений 
---
Книга рецептов
---
Третье издание 
---



Что охватывает эта книга
===
**Глава 1**, Основы, описывает, как установить Yii Framework и различные способы его установки. Мы познакомим вас с шаблонами приложений: базовыми и продвинутыми, и в чем разница между ними. Затем вы узнаете о контейнере внедрения зависимостей. В этой главе содержится информация о событиях модели, которые запускаются после некоторых простых действий, таких как сохранение и обновление модели и другое. Мы научимся использовать внешний код, который будет включать ZendFramework, Laravel и Sympony в примерах. Мы также узнаем, как обновить приложения на основе yii-1.x.x  к yii2 шаг за шагом. Еще несколько рецептов доступны по адресу <https://www.packtpub.com/sites/default/files/downloads/4270OS Chapter1.pdf>

**Глава 2**, маршрутизация, контроллеры и представления, учит некоторым удобным вещам о маршрутизаторе URL Yii, контроллерах и представлениях. Вы сможете сделать ваши контроллеры и представления более гибкими.

**В главе 3**, ActiveRecord, Model и Database, рассматриваются три основных метода работы с базами данных в Yii: Active Record, query builder и прямые SQL-запросы через DAO. Все они различаются по синтаксису, функциям и производительности. В этой главе мы узнаем, как эффективно работать с базой данных, когда использовать модели, а когда нет, как работать с несколькими базами данных, как автоматически предварительно обрабатывать поля активных записей и как использовать мощные критерии базы данных.

**Глава 4**, формы, охватывает, как Yii делает работу с формами a breeze и документация по нему почти завершена. Тем не менее, есть некоторые области, которые нуждаются в разъяснениях и примерах.

**Глава 5**, безопасность, описывает, как обеспечить безопасность приложения в соответствии с общим принципом безопасности веб-приложения " вход фильтруем вход, escape на выходе."Мы рассмотрим такие темы, как создание собственных фильтров контроллера, предотвращение инъекций XSS, CSRF и SQL, экранирование выходных данных и использование управления доступом на основе ролей.

**Глава 6**, веб-службы RESTful, описывает, как писать веб-службы RESTful с помощью Yii2 и встроенных функций.

**Глава 7**, официальные расширения, объясняет нам, как установить и использовать официальные расширения в вашем проекте. Вы узнаете, как написать собственное расширение и поделиться им с другими разработчиками.

**Глава 8**, расширение Yii, охватывает не только то, как реализовать собственное расширение Yii, но и как сделать ваше расширение многоразовым и полезным для сообщества. Кроме того, мы сосредоточимся на многих вещах, которые вы должны сделать, чтобы сделать ваше расширение максимально эффективным.

**Глава 9**, Настройка производительности, учит некоторым лучшим практикам разработки приложения, которое будет работать гладко, пока у вас не будет очень высоких нагрузок. Yii является одним из самых быстрых фреймворков. Тем не менее, при разработке и развертывании приложения хорошо иметь дополнительную производительность бесплатно, а также следовать рекомендациям для самого приложения. В этой главе мы увидим, как настроить yii для получения дополнительной производительности. Кроме того, мы изучим некоторые лучшие практики для разработки приложения, которое будет работать гладко, пока у нас не будет очень высоких нагрузок.

**Глава 10**, развертывание, содержит различные советы, которые особенно полезны при развертывании приложений и при разработке приложения в команде, или когда вы просто хотите сделать свою среду разработки более удобной.

**Глава 11**, тестирование, учит нас, как использовать лучшие технологии для тестирования, такие как Codeception, PhpUnit, Atoum и Behat. Вы узнаете, как писать простые тесты и как избежать ошибок регрессии в приложении.

**В главе 12** Отладка, ведение журнала и обработка ошибок" рассматриваются ведение журнала проверок, анализ трассировки стека исключений и реализация собственного обработчика ошибок. Невозможно создать приложение без ошибок, если оно относительно сложное, поэтому разработчикам приходится обнаруживать ошибки и работать с ними как можно быстрее. Yii имеет хороший набор функций утилиты для обработки регистрации и обработки ошибок. Кроме того, в режиме отладки Yii дает вам трассировку стека, если есть ошибка. Используя его, вы можете исправить ошибки быстрее.



Установка фреймворка
===
Yii2-это современный PHP фреймворк представлен в виде пакета Composer. В этом рецепте мы установим фреймворк через менеджер пакетов Composer и настроим подключение к базе данных для нашего приложения.

Подготовка
---
Прежде всего, установите Composer в вашей системе.

**Замечание**
Если вы используете Openserver на Windows, команда Composer уже существует в Openserver терминальной консоли.
В Mac или Linux загрузите установщик с <https://getcomposer.org/download/> и установить его глобально с помощью следующей команды:

**sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer**

В Windows без Openserver запустить 

**Composer-Setup.exe** 

cо страницы <https://getcomposer.org/doc/00-intro.md>.

Если у вас нет административных прав в системе, то в качестве альтернативы вы можете просто скачать <https://getcomposer.org/composer.phar>  файл и использовать команду
 
**php composer. phar** 

вместо команды Composer

После установки запустить в терминале:
 
**Composer** 

Или (если вы просто скачиваете архив) его альтернатива:
 
**PHP composer.phar**

После успешной установки вы увидите следующий ответ:

![](img/038_1.jpg)

Прямо сейчас вы можете установить любой пакет из https://packagist.org репозитория.

Как это сделать...
---
Можно установить базовые или расширенные шаблоны приложений. Чтобы узнать о различиях между шаблонами, см. рецепт шаблонов приложений.

**Замечание**

Обратите внимание, что во время установки менеджера пакетов Composer получает много информации с сайта GitHub. GitHub может ограничить запросы анонимных пользователей. В этом случае Composer просит Вас ввести маркер доступа. Вы просто должны  зарегистрироваться на <https://github.com> и генерировать новый маркер через с помошью руководства <https://github.com/blog/1509-personal-api-tokens>

### Установка базового шаблона проекта

Выполните следующие действия для установки базового шаблона проекта:

1  В качестве первого шага откройте ваш терминал и установите Bower-to-Composer  адаптер:
 
**composer global require "fxp/composer-asset-plugin:^1.2.0"**

Он обеспечивает простой способ загрузки, не связанных с созданием пакетов для PHP (JavaScript и CSS) из репозитория Bower.
(замечание переводчика: Если вы работаете под Windows то имя пользователя должно состоять только из латинских букв. С именем на русском это все нормально работать не будет)

2  Создание нового приложения в новом базовом каталоге:
(замечание переводчика: если вы работаете с Openserver то сначала в консоле перейдите в каталог domains 

**cd domains**

а затем создавайте каталог с приложением)

**composer create-project --prefer-dist yiisoft/yii2-app-basic basic**

3  Убедитесь, что ваш PHP содержит необходимые расширения:
 
**cd basic**

**php requirements.php**

**Замечание**
PHP в командном режиме и в режиме web-интерфейса может использовать разные php.ini файлы с различными конфигурациями и различными расширениями.

4  Создайте новую базу данных (если она нужна для вашего проекта) и настройте ее в config/db.php -файле.

5  Попробуйте запустить приложение с помощью следующей команды консоли:
**php yii serve**

6  Проверьте в браузере, что приложение работает по адресу http://localhost:8080:
(замечание переводчика: при работе с OpenServer необходимо настроить имя сайта что бы вы могли по нему обращаться к этому приложению. Это делается пункете меню Настройки->закладка Домены)

![](img/040_1.jpg)

Для постоянной работы создайте новый хост на вашем сервере (Apache, Nginx и так далее) и установите веб-каталог в качестве корневого документа хоста.

### Установка расширенного шаблона проекта

Выполните следующие действия для установки расширенного шаблона проекта:

1  В качестве первого шага откройте ваш терминал и установите Bower-to-Composer  адаптер 

**composer global require "fxp/composer-asset-plugin:^1.2.0"**

Он обеспечивает простой способ загрузки, не связанных с созданием пакетов для PHP (JavaScript и CSS) из репозитория Bower.
(замечание переводчика: Если вы работаете под Windows то имя пользователя должно состоять только из латинских букв. С именем на русском это все нормально работать не будет)

2  Создание нового приложения в новом advaced каталоге:

**composer create-project --prefer-dist yiisoft/yii2-app-advanced advanced**

3  Новое приложение не содержит локальных файлов конфигурации и index.php. Для создания файлов необходимо инициализировать рабочую среду:
**cd advanced** 
**php init**

Во время инициализации выберите среду разработки Development.

4  Убедитесь, что ваш PHP содержит необходимые расширения:

**php requirements.php**  

**Примечание:** 
PHP в режиме командной строки и в режиме веб-интерфейса может использовать другие .ini файлы с различной конфигурацией и различными расширениями.

5  Создайте новую базу данных и настройте ее в сгенерированном common/config/main-local.php файле .

6  Примените миграции приложения:

**php yii migrate**

Эта команда автоматически создаст пользовательскую таблицу в базе данных.

7  Попробуйте запустить приложение frontend с помощью следующей команды консоли:

**php yii serve --docroot=@frontend/web --port=8080**

Затем запустите серверную часть в другом окне терминала:
 
**php yii serve --docroot=@backend/web --port=8090**

8  Проверьте в браузере, что приложение работает по адресу  http: //localhost: 8080 и  http://localhost:8090 
![](img/041_1.jpg)
Создайте два домена  для backend и frontend приложения на своем сервере (Apache, nginx и т. д.) и настройки серверной части веб-и frontend/веб-каталогах, как корневые каталоги.

Как это работает...
----
Прежде всего, мы установили менеджер пакетов Composer и плагин Bower asset.
После установки приложения с помощью команды composer create-project команда создает новый пустой каталог, клонирует исходный код шаблона приложения и загружает все его внутренние зависимости (фреймворк и другие компоненты) в подкаталог vendor.

При необходимости мы инициализируем конфигурацию приложения и создадим новую базу данных.
Мы можем проверить требования к системе через запуск requirements.php -скрипт в консоли или в режиме браузера.
А после клонирования кода мы можем сконфигурировать свой PHP сервер для работы с веб-каталогами как корневыми документами сервера.

Смотрите также
---
* Для получения дополнительной информации об установке yii2-app-basic обратитесь к, <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
* Ссылка , <https://github.com/yiisoft/yii2-app-advanced/blob/mastpr/docs/guide/start-installation.md>  для  yii2-app-advanced.
* Ссылка, <https://getcomposer.org> для Composer package manager.
* Для создания маркера доступа GitHub для Composer обратитесь к  <https://github.com/blog/1509-personal-api-tokens>.



Шаблон приложения
===
Yii2 имеет два шаблона приложений для разработки: базовый и расширенный. В чем разница между базовыми и продвинутыми шаблонами?
Имена сбивают с толку. Некоторые люди в конце концов выбирают basic, потому что расширенный может показаться отталкивающим. В этой главе мы рассмотрим различия.

Как это сделать...
---
Пожалуйста см. Рецепт Установка фреймворка Как это сделать ... раздел для понимания и изучения установки различных шаблонов.

Как это работает.
---
Расширенный шаблон имеет пользовательскую систему конфигураций. Он разработан таким образом, что команда может работать вместе над проектом, но каждый разработчик может настроить свои собственные конфигурации для разработки, тестирования и другого окружения.
Конфигурации окружения могут быть сложными и обычно не используются при разработке в одиночку.
Расширенный шаблон соотвествует frontend и backend папки frontend и backend части Web-приложения  Так что вы можете настроить отдельный хост для каждой папки и тем самым изолировать frontend и backend части.
Это простой способ организовать файлы в директории и настроить веб-сервер. Вы можете легко сделать то же самое в базовом шаблоне.
Ни front/back-end  разделение, ни управление пользователями сами по себе не являются веским основанием для выбора расширенного шаблона. Лучше адаптировать эти функции к вашему приложению—вы узнаете больше и не получите трудную проблему конфигурации.
Если вы будете работать над проектом с командой, и вам может понадобиться гибкость конфигурации, используйте различные среды для разработки, и в этом случае лучшим выбором будет расширенный шаблон приложения. Если вы будете работать в одиночку и ваш проект прост выбирайте базовый шаблон приложения.


Контейнер внедрения зависимостей
===
***Dependency Inversion Principle (DIP)*** предположим, что мы создаем модульный код с низкой связью с помощью извлечения четких подсистем абстракции.
Например, если вы хотите упростить большой класс, вы можете разделить его на несколько кусков рутинного кода и извлечь каждый кусок в новый простой разделенный класс.
Принцип говорит о том, что низкоуровневые фрагменты должны реализовывать достаточную и четкую абстракцию, а высокоуровневый код должен работать только с этой абстракцией, а не с низкоуровневой реализацией.
Когда мы разделяем большой многозадачный класс на небольшие специализированные классы, мы сталкиваемся с проблемой создания зависимых объектов и внедрения их друг в друга.
Если раньше  мы могли создать один экземпляр:
```php
$service = new MyGiantSuperService();
```
А после разделения мы создадим и получим все зависимые предметы и построим наш сервис:
```php
$service = new MyService(
    new Repository(new PDO('dsn', 'username', 'password')), new Session(),
    new Mailer(new SmtpMailerTransport('username', 'password', host')), 
    new Cache(new FileSystem('/tmp/cache')),
);
```
Контейнер для инъекций зависимостей-это фабрика, которая позволяет нам не заботиться о создании наших объектов. В Yii2 мы можем настроить контейнер только один раз и использовать его для получения нашего сервиса, как это:
```php
$service = Yii::$container->get('app\services\MyService')
```
Мы можем также использовать это:

```php
$service = Yii::createObject('app\services\MyService')
```
Или мы просим контейнер внедрить его как зависимость в конструкторе другой службы:

```php
use app\services\MyService; 
class OtherService {
      public function construct(MyService $myService) { ... }
}
```
Когда мы получим экземпляр OtherService:

```php
$otherService = Yii::createObject('app\services\OtherService')
```

Во всех случаях контейнер будет разрешать все зависимости и внедрять зависимые объекты друг в друга.
В рецепте мы создаем корзину с подсистемой хранения и автоматически вставляем корзину в контроллер.

### Подготовка

Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>

### Как это сделать...

Выполните следующие действия:

1 Создание класса корзины покупок:
```php

<?php

namespace app\cart;

use app\cart\storage\StorageInterface;

class ShoppingCart
{
    /**
     * @var StorageInterface
     */
    private $storage;
    private $_items = [];

    public function __construct(StorageInterface $storage)
    {
        $this->storage = $storage;
    }

    public function add($id, $amount)
    {
        $this->loadItems();
        if (array_key_exists($id, $this->_items)) {
            $this->_items[$id]['amount'] += $amount;
        } else {
            $this->_items[$id] = [
                'id' => $id,
                'amount' => $amount,
            ];
        }
        $this->saveItems();
    }

    public function remove($id)
    {
        $this->loadItems();
        $this->_items = array_diff_key($this->_items, [$id => []]);
        $this->saveItems();
    }

    public function clear()
    {
        $this->_items = [];
        $this->saveItems();
    }

    public function getItems()
    {
        $this->loadItems();
        return $this->_items;
    }

    private function loadItems()
    {
        $this->_items = $this->storage->load();
    }

    private function saveItems()
    {
        $this->storage->save($this->_items);
    }
}
```

2  Он будет работать только с собственными предметами. Вместо встроенного хранения элементов в сеансе он делегирует эту ответственность любому внешнему классу хранения, который будет реализовывать Интерфейс Storageinterface.

3  Класс cart просто получает объект хранения в собственный конструктор, сохраняет его экземпляр в закрытый $storage поле и вызывает  load() и save() методы.

4  Определите общий интерфейс хранения корзины с необходимыми методами:
```php
<?php

namespace app\cart\storage;

interface StorageInterface
{
    /**
     * @return array of cart items
     */
    public function load();

    /**
     * @param array $items from cart
     */
    public function save(array $items);
}
```

5  Создайте простую реализацию хранилища. Он будет хранить выбранные элементы в сеансе сервера:
```php
<?php

namespace app\cart\storage;

use yii\web\Session;

class SessionStorage implements StorageInterface
{
    /**
     * @var Session
     */
    private $session;
    private $key;

    public function __construct(Session $session, $key)
    {
        $this->key = $key;
        $this->session = $session;
    }

    public function load()
    {
        return $this->session->get($this->key, []);
    }

    public function save(array $items)
    {
        $this->session->set($this->key, $items);
    }
}
```
6  Хранилище получает любой экземпляр framework session  в constructor и использует его позже для получения и хранение предметов.

7  Настройте класс shoppingCart и его зависимости в файле config/web.php:
```php
<?php
use app\cart\storage\SessionStorage;
Yii::$container->setSingleton('app\cart\ShoppingCart');
Yii::$container->set('app\cart\storage\StorageInterface', function() { 
        return new SessionStorage(Yii::$app->session, 'primary-cart');
        });
$params = require(  __DIR__  . '/params.php');
//...
```
8  Создайте контроллер cart с расширенным конструктором:
```php
<?php

namespace app\controllers;

use app\cart\ShoppingCart;
use app\models\CartAddForm;
use Yii;
use yii\data\ArrayDataProvider;
use yii\filters\VerbFilter;
use yii\web\Controller;

class CartController extends Controller
{
    /**
     * @var ShoppingCart
     */
    private $cart;

    public function __construct($id, $module, ShoppingCart $cart, $config = [])
    {
        $this->cart = $cart;
        parent::__construct($id, $module, $config);
    }

    public function behaviors()
    {
        return [
            'verbs' => [
                'class' => VerbFilter::className(),
                'actions' => [
                    'delete' => ['post'],
                ],
            ],
        ];
    }

    public function actionIndex()
    {
        $dataProvider = new ArrayDataProvider([
            'allModels' => $this->cart->getItems(),
        ]);

        return $this->render('index', [
            'dataProvider' => $dataProvider,
        ]);
    }

    public function actionAdd()
    {
        $form = new CartAddForm();

        if ($form->load(Yii::$app->request->post()) && $form->validate()) {
            $this->cart->add($form->productId, $form->amount);
            return $this->redirect(['index']);
        }

        return $this->render('add', [
            'model' => $form,
        ]);
    }

    public function actionDelete($id)
    {
        $this->cart->remove($id);

        return $this->redirect(['index']);
    }
}
```
9  Создание формы:
```php
<?php
namespace app\models;
use yii\base\Model;
class CartAddForm extends Model {
    public $productId; 
    public $amount;
    public function rules()
    {
       return [
          [['productId', 'amount'], 'required'],
          [['amount'], 'integer', 'min' => 1],
       ];
    }
}

```
10  Создания вида views/cart/index.php :
```php
<?php
use yii\grid\ActionColumn; 
use yii\grid\GridView; 
use yii\grid\SerialColumn; 
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $dataProvider yii\data\ArrayDataProvider */
$this->title = 'Cart';
$this->params['breadcrumbs'][] = $this->title;
?>
<div class="cart-index">
   <h1><?= Html::encode($this->title) ?></h1>
   <p><?= Html::a('Add Item', ['add'], ['class' => 'btn btn-success']) ?></p>
   <?= GridView::widget([
        'dataProvider' => $dataProvider,
        'columns' => [
            ['class' => SerialColumn::className()], 'id:text:Product ID','amount:text:Amount',
            ['class' => ActionColumn::className(),  'template' => '{delete}',]
        ],
    ])?>
</div>
```
11 Cоздаем представление views/cart/add.php:
```php
<?php
use yii\helpers\Html;
use yii\bootstrap\ActiveForm;
/* @var $this yii\web\View */
/* @var $form yii\bootstrap\ActiveForm */
/* @var $model app\models\CartAddForm */
$this->title = 'Add item';
$this->params['breadcrumbs'][] = ['label' => 'Cart', 'url' => ['index']]; $this->params['breadcrumbs'][] = $this->title;
?>
<div class="cart-add">
<h1><?= Html::encode($this->title) ?></h1>
<?php $form = ActiveForm::begin(['id' => 'contact-form']); ?>
<?= $form->field($model, 'productId') ?>
<?= $form->field($model, 'amount') ?>
<div class="form-group">
<?= Html::submitButton('Add', ['class' => 'btn btn-primary']) ?> </div>
<?php ActiveForm::end(); ?>
</div>
```
12  Добавление элементов в Главное меню:
```html
['label' => 'Home', 'url' => ['/site/index']],
['label' => 'Cart', 'url' => ['/cart/index']],
['label' => 'About', 'url' => ['/site/about']],
// ...
```
13  Откройте страницу корзины и попробуйте добавить строки:
![](img/050_1.jpg)


Как это работает..
---

В этом случае у нас есть основной класс shoppingCart с низкоуровневой зависимостью, определяемой интерфейсом абстракции:

```php
class ShoppingCart 
{
   public function __construct(StorageInterface $storage) { ... }
}

interface StorageInterface 
{
public function load();
public function save(array $items);
}
```
И у нас есть некоторая реализация абстракции:
```php
class SessionStorage implements StorageInterface
{
       public function  construct(Session $session, $key) { ... }
}
Right now we can create an instance of the cart manually like this:
$storage = new SessionStorage(Yii::$app->session, 'primary-cart');
$cart = new ShoppingCart($storage)
```
Это позволяет нам создавать множество различных реализаций, таких как SessionStorage, CookieStorage или DbStorage. И мы можем повторно использовать независимый от фреймворка класс ShoppingCart с StorageInterface в разных проектах и разных фреймворках. Мы должны только реализовать класс хранения с методами интерфейса для необходимой платформы.

Но вместо того, чтобы вручную создавать экземпляр со всеми зависимостями, мы можем использовать контейнер внедрения зависимостей.

По умолчанию контейнер анализирует конструкторы всех классов и рекурсивно создает все необходимые экземпляры. Например, если у нас четыре класса:
```php
class A 
{
    public function __construct(B $b, C $c) { ... }
}

class B 
{
    {...}

class C 
{
public function __construct(D $d) { ... }
}

class D 
{
    ...
}
```
Мы можем получить экземпляр класса двумя способами:
```php
$a = Yii::$container->get('app\services\A')
```
// или
```php
$a = Yii::createObject('app\services\A')
```
Контейнер автоматически создает экземпляры классов B, D, C и A и внедряет их друг в друга.
В нашем случае мы отмечаем корзину как синглтон: 
```php
Yii::$container->setSingleton('app\cart\ShoppingCart');
```
Это означает, что контейнер будет возвращать один экземпляр для каждого повторного вызова вместо создания корзины снова и снова.
Кроме того, наш ShoppingCart имеет Тип StorageInterface в своем собственном конструкторе, и контейнер знает, какой класс он должен создать для этого типа. Мы должны вручную привязать класс к интерфейсу, как это:
```php
Yii::$container->set('app\cart\storage\StorageInterface', 'app\cart\storage\CustomStorage', );
```
Но наш класс SessionStorage имеет нестандартный конструктор:
```php
class SessionStorage implements StorageInterface {
        public function __construct(Session $session, $key) { ... }
}
```
Поэтому мы используем анонимную функцию для создания экземпляра вручную:
```php
Yii::$container->set('app\cart\storage\StorageInterface', function() {
         return new SessionStorage(Yii::$app->session, 'primary-cart');
});
```
И в конце концов мы можем получить объект cart из контейнера вручную в наших собственных контроллерах, виджетах и других местах:
```php
$cart = Yii::createObject('app\cart\ShoppingCart')
```
Каждый контроллер и другие объекты будут созданы с помощью метода createObject внутри фреймворка. И мы можем использовать инжекцию  через конструктор контроллера:
```php
class CartController extends Controller {
    private $cart;
    public function  __construct($id, $module, ShoppingCart $cart, $config = [])
    {
        $this->cart = $cart;
        parent::    construct($id, $module, $config);
     }
     // ...
}
```
Используйте этот впрыснутый объект :
```php
public function actionDelete($id)
{
    $this->cart->remove($id);
    return $this->redirect(['index']);
}
```

Смотрите также
---
*   Дополнительные сведения о DIP см <https://en.wikipedia.org/wiki/Dependencv inversion principle>
*   Чтобы узнать больше о контейнере внедрения зависимостей, обратитесь к <http://www.yiiframework.com/doc-2.0/gurde-concept-di-container.html>      на русском <http://yiiframework.domain-na.me/doc/guide/2.0/ru/concept-di-container> 



Service locator
===
Вместо того чтобы вручную создавать экземпляры различных общих служб (компонентов приложения), мы можем получить их из специального глобального объекта, который содержит конфигурации и экземпляры всех компонентов.
Локатор служб-это глобальный объект, который содержит список компонентов или определений, однозначно идентифицируемых по идентификатору, и позволяет получить любой необходимый экземпляр по его идентификатору. Локатор создает один экземпляр компонента "на лету" при первом вызове и возвращает предыдущий экземпляр при последующих вызовах.
В этом рецепте мы создадим компонент корзины и напишем контроллер корзины для работы с ним.

Подготовка
----
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу http://www.viiframework.com/doc-2.0/guide-start-installation.html. 
(от переводчика на русском http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation)

Как это сделать...
---
Для создания компонента корзины выполните следующие действия:

1 Создайте компонент корзины покупок. Он будет хранить выбранные элементы в сеансе пользователя:
```php
<?php

namespace app\components;

use Yii;
use yii\base\Component;

class ShoppingCart extends Component
{
    public $sessionKey = 'cart';
    private $_items = [];

    public function add($id, $amount)
    {
        $this->loadItems();
        if (array_key_exists($id, $this->_items)) {
            $this->_items[$id]['amount'] += $amount;
        } else {
            $this->_items[$id] = [
                'id' => $id,
                'amount' => $amount,
            ];
        }
        $this->saveItems();
    }

    public function remove($id)
    {
        $this->loadItems();
        $this->_items = array_diff_key($this->_items, [$id => []]);
        $this->saveItems();
    }

    public function clear()
    {
        $this->_items = [];
        $this->saveItems();
    }

    public function getItems()
    {
        $this->loadItems();
        return $this->_items;
    }

    private function loadItems()
    {
        $this->_items = Yii::$app->session->get($this->sessionKey, []);
    }

    private function saveItems()
    {
        Yii::$app->session->set($this->sessionKey, $this->_items);
    }
}
```
2 Создайте контроллер корзины:
```php
<?php

namespace app\controllers;

use app\models\CartAddForm;
use Yii;
use yii\data\ArrayDataProvider;
use yii\filters\VerbFilter;
use yii\web\Controller;

class CartController extends Controller
{
    public function behaviors()
    {
        return [
            'verbs' => [
                'class' => VerbFilter::className(),
                'actions' => [
                    'delete' => ['post'],
                ],
            ],
        ];
    }

    public function actionIndex()
    {
        $dataProvider = new ArrayDataProvider([
            'allModels' => Yii::$app->cart->getItems(),
        ]);

        return $this->render('index', [
            'dataProvider' => $dataProvider,
        ]);
    }

    public function actionAdd()
    {
        $form = new CartAddForm();

        if ($form->load(Yii::$app->request->post()) && $form->validate()) {
            Yii::$app->cart->add($form->productId, $form->amount);
            return $this->redirect(['index']);
        }

        return $this->render('add', [
            'model' => $form,
        ]);
    }

    public function actionDelete($id)
    {
        Yii::$app->cart->remove($id);

        return $this->redirect(['index']);
    }
}
```
4 Создаем форму:
```php
<?php
namespace app\models;
use yii\base\Model;
class CartAddForm extends Model {
public $productId; public $amount;
public function rules()
{
    return [
       [['productId', 'amount'], 'required'],
       [['amount'], 'integer', 'min' => 1],
    ];
}
}
```
5 Создаем представление  views/cart/index.php :
```php
<?php
use yii\grid\ActionColumn; 
use yii\grid\GridView; 
use yii\grid\SerialColumn; 
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $dataProvider yii\data\ArrayDataProvider */
$this->title = 'Cart';
$this->params['breadcrumbs'][] = $this->title;
?>
<div class="site-contact">
<h1><?= Html::encode($this->title) ?></h1>
<p><?= Html::a('Add Item', ['add'], ['class' => 'btn btn-success']) ?></p>
<?= GridView::widget([
    'dataProvider' => $dataProvider,
    'columns' => [
         ['class' => SerialColumn::className()],
         'id:text:Product ID',
         'amount:text:Amount',
         [
          'class' => ActionColumn::className(),
          'template' => '{delete}',
         ]
     ],
]) ?>
</div>
```
6 Создаем представление views/cart/add.php:
```php
<?php
use yii\helpers\Html;
use yii\bootstrap\ActiveForm;
/* @var $this yii\web\View */
/* @var $form yii\bootstrap\ActiveForm */
/* @var $model app\models\CartAddForm */
$this->title = 'Add item';
$this->params['breadcrumbs'][] = ['label' => 'Cart', 'url' => ['index']]; 
$this->params['breadcrumbs'][] = $this->title;
?>
<div class="site-contact">
<h1><?= Html::encode($this->title) ?></h1>
<?php $form = ActiveForm::begin(['id' => 'contact-form']); ?>
<?= $form->field($model, 'productId') ?>
<?= $form->field($model, 'amount') ?>
<div class="form-group">
     <?= Html::submitButton('Add', ['class' => 'btn btn-primary']) ?> </div>
<?php ActiveForm::end(); ?>
</div>
```
7 Добавляем пункты в меню:
```php
['label' => 'Home', 'url' => ['/site/index']],
['label' => 'Cart', 'url' => ['/cart/index']],
['label' => 'About', 'url' => ['/site/about']],
// ...
```
8 Откройте страницу корзина и попробуйте добавить строки:
![](img/057_1.jpg)

Как это работает
---
Прежде всего, мы создали собственный класс с опцией public sessionKey:
```php
<?php
namespace app\components; 
use yii\base\Component;
class ShoppingCart extends Component {
    public $sessionKey = 'cart';
    // ...
}
```
Во-вторых, мы добавили определение компонента в раздел components файла конфигурации: 
```php
'components' => [
   'cart => [
      'class' => 'app\components\ShoppingCart', 
      'sessionKey' => 'primary-cart',
   ],
]
```
Сейчас мы можем получить экземпляр компонента двумя способами:
```php
$cart = Yii::$app->cart;
$cart = Yii::$app->get('cart');
```
И мы можем использовать этот объект в наших собственных контроллерах, виджетах и других местах.
Когда мы вызываем любой компонент как корзина:
```php
Yii::$app->cart
```
Мы вызываем виртуальное свойство экземпляра класса Application в статической переменной Yii:: $app. Класс yii\base\Application расширяет в yii\base\Module, который расширяет
 yii\di\ServiceLocator с волшебным методом __get. Этот волшебный метод просто вызывает метод get()
из класса  yii\di\ServiceLocator :
```php
namespace yii\di;
class ServiceLocator extends Component {
    private $_components = []; 
    private $_definitions = [];

    public function __get($name)
    {
        if ($this->has($name)) {
           return $this->get($name);
        } else {
           return parent::get($name);
        }
    }
    // ...
}
```
В результате это альтернатива непосредственному вызову сервиса через get метод:
```php
Yii::$app->get('cart);
```
Когда мы получаем компонент из метода Get сервис локатора, локатор находит необходимое определение в своем списке _definitions и в случае успеха создает новый объект по определению на лету, регистрирует его в своем собственном списке экземпляров _ Components и возвращает объект.
Если мы получим какой-то компонент, множественный запуск локатора всегда будет возвращать предыдущий сохраненный экземпляр снова и снова:
```php
$cart1 = Yii::$app->cart;
$cart2 = Yii::$app->cart;
var_dump($cart1 === $cart2); // bool(true)
```
Это позволяет нам использовать общий экземпляр одной корзины Yii::$app->cart или одно соединение с базой  Yii::$app->db вместо того чтобы создавать один большой набор с нуля снова и снова.

Смотреть также
---
* Дополнительные сведения о локаторе служб и основных компонентах платформы см. в разделе <http://www.yiiframework.eom/doc-2.0/guide-concept-service-locator.html>
на русском <http://yiiframework.domain-na.me/doc/guide/2.0/ru/concept-service-locator> 
* Рецепт Конфигурация компонентов 
* Рецепт Создание компонентов в главе 8, Расширение Yii



Генерация кода
===
Yii2 обеспечивает мощный модуль Gii для генерации моделей, контроллеров и представлений, которые вы можете легко изменять и настраивать. Это действительно полезный инструмент для быстрого  развития.
В этом разделе мы рассмотрим, как использовать Gii и генерировать код. Например, у вас есть база данных с одной таблицей film, и вы хотели бы создать приложение с операциями CRUD для этой таблицы. Это просто.

Подготовка
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html.> по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation >

2 Скачать база данных "sakila" c <http://dev.mysql.com/doc/indey-other.html>.

3 Выполните загрузку SQL: сначала схема, затем данные.

4 Настройте подключение к базе данных в config/main.php для использования базы данных Sakila.

5 Запустите веб-сервер с помощью./yii serve. (от переводчика: или другим способом)

Как это сделать...
---
1 Перейдите по адресу http: //localhost :8080/index. php?r=gii и выберите Model Generator.

2 Заполните Table Name как actor и Model Class как Actor и нажмите кнопку Generate внизу страницы

![](img/060_1.JPG)

3  Вернуться к главному меню GII, нажав на логотип в заголовке и выбрав  CRUD Generator.
![](img/061_1.JPG)

4 Заполнит поле Model Class как  app\models\Actor и Controller Class как app\controllers\ActorController.

5  Нажмите кнопку Preview в нижней части страницы, а затем нажмите зеленую кнопку Generate.

6 Проверьте результат по адресу http://localhost:8080/index.php?actor/create.
![](img/062_1.JPG)

Как это работает…
---
Если вы проверите структуру проекта, вы увидите автоматически созданный код:
![](img/063_1.JPG)


Сначала мы создали модель Actor. Gii автоматически создает все модельные правила, которые зависят от типов полей mysql. Например, если в Вашей таблице MySQL actor поля first_name и last_name имеют флаг NOT NULL, то Yii автоматически создает правило для него required и устанавливает максимальную длину 45 символов, потому что в нашей базе данных Максимальная длина этого поля установлена как 45
 ```php
public function rules()
{
   return [
    [['first_name', 'last_name'], 'required'],
    [['last_update'], 'safe'],
    [['first_name', 'last_name'], 'string', 'max' => 45],
}
```
Кроме того, yii автоматически создает отношения между моделями на основе внешних ключей, добавленных в базу данных. В нашем случае два отношения были созданы автоматически .

```php
public function getFilmActors()
{
     return $this->hasMany(FilmActor::className(), ['actor_id' => 'actor_id']);
}
public function getFilms()
{
     return $this->hasMany(Film::className(), ['film_id' => 'film_id'])->viaTable('film_actor', ['actor_id' => 'actor_id']);
}
```
Это отношение было создано, потому что у нас есть два внешних ключа в нашей базе данных. Таблица film_actor имеет внешний ключ fk_film_actor_actor, который указывает на поля таблицы Actor actor_id и fk_film_actor_film что указывает на таблицу  Film поле film_id.
Обратите внимание, что модель FilmActor еще не создана. Поэтому, если вы будете разрабатывать полное приложение , вы должны будете генерировать также модели Film, FilmActor . 
Для остальных частей обратитесь к <http://www.yiiframework.com/doc-2.0/guide-start-gii.html>.  по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-gii>



Настройка компонентов
===
Yii-это очень настраиваемый фреймворк. Кроме того, как и во всем настраиваемом коде, должен быть удобный способ настройки различных частей приложения. В Yii это обеспечивается через файлы конфигурации, расположенные в config.

Подготовка
---
Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation> 

Как это работает
---
Если вы работали с Yii раньше, то вы, вероятно, настроили подключение к базе данных: 
```php
return [
    'components' => [
        'db' => [
            'class' => 'system.db.CDbConnection',
            'dsn' => 'mysql:host=localhost;dbname=database_name',
            'username' => 'root',
            ' password' => '',
            'charset' => ' utf8',
        ],
    ],
];
```
Этот способ настройки компонентов используется, когда требуется использовать компонент во всех частях приложения. С помощью предыдущей конфигурации можно получить доступ к компоненту по его имени, например Yii::$app->db.

Как это работает.
---
При первом использовании компонента БД Yii::$app->непосредственно или через активную модель записи Yii создает компонент и инициализирует его открытые свойства соответствующими значениями, указанными в массиве БД в разделе компоненты файла конфигурации приложения. В предыдущем примере, значение dsn будет назначен в yii\db\Connection::dsn имя источника данных, имя пользователя будет присвоено Connection::username, и так далее.
Если вы хотите узнать, что означает Кодировка или хотите знать, что еще вы можете настроить в компоненте БД, то вам нужно знать его класс. В случае компонента db классом является yii\db\Connection. Можно просто открыть класс и найти его открытые свойства, которые можно задать в config.
В предыдущем коде свойство class является немного специальным, поскольку оно используется для указания имени класса компонента. Он не существует в классе Yii\db\Connection. Поэтому его можно использовать для переопределения класса следующим образом:
```php
return [
    'components' => [
        'db' => [
            'class' => app\components\MyConnection',
        ],
    ],
);
```
Таким образом, Вы можете переопределить каждый компонент приложения; это очень полезно, когда стандартный компонент не подходит для вашего приложения.

Встроенные компоненты
---
Теперь давайте выясним, какие стандартные компоненты приложения Yii вы можете настроить. Есть два типа приложений в комплекте с Yii:
* Web приложение (yii\webApplication)
* Console приложение (yii\console\Application)

Смотрите также
---
* Компоненты консоли и веб-приложения перечислены в списке по адресу http://www.viiframework.com/doc-2.0/guide-structure-application-components.html
* по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-application-components>
* Дополнительные сведения о создании собственных компонентов см. в разделе:
Рецепт Service locator 
Рецепт Создание компонентов в главе 8, Расширенный Yii



Работа с событиями
===

События Yii обеспечивают простую реализацию, которая позволяет прослушивать и подписываться на различные события, происходящие в вашем веб-приложении. Например, вы можете отправить уведомление о новой статье подписчикам при каждой публикации нового материала.

Подготовка
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве по http://www.yiiframework.com/doc-2.0/guide-start-installation.html. (от переводчика по русски http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation )

2 Выполните следующий код SQL на сервере, чтобы создать таблицу статей:
```php
CREATE TABLE 'article' (
'id' int(11) NOT NULL AUTO_INCREMENT,
'name' varchar(255) DEFAULT NULL,
'description' text,
PRIMARY KEY ('id')
) ENGINE=InnoDB AUTO_INCREMENT=29 DEFAULT CHARSET=utf8;
```

3  Создайте модель Article с помощью Gii.

4 Запустите ваш webserver командой ./yii serve.

Как это работает
---
1 Добавить тест действия в \controllers\SiteController:

```php
public function actionTest()
{
    $article = new Article();

    $article->name = ‘День Святого Валентина приближается? Вот дерьмо! Я забыл снова завести девушку!';
    $article->description = ‘Бендер злится на Фрая за то, что он встречается с роботом. Держись подальше от наших женщин. У тебя металлическая лихорадка, парень. Лихорадка металла';

    // $event - объект класса yii\base\Event или дочернего класса 
    $article->on(ActiveRecord::EVENT_AFTER_INSERT, function($event) {
        $followers = ['john2@teleworm.us', 
                      'shivawhite@cuvox.de', 
                      'kate@dayrep.com'
                     ];
        
        foreach($followers as $follower) {
            Yii::$app->mailer->compose()
            ->setFrom('techblog@teleworm.us')
            ->setTo($follower)
            ->setSubject($event->sender ->name)
            ->setTextBody($event->sender->description)
            ->send();
        }
        echo 'Emails has been sent';
    });
    if (!$article->save()) {
        echo VarDumper::dumpAsString($article->getErrors());
    };
}
```

2 Обновите config/web.php, компонент mailer использует следующий код.
```php
'mailer' => [
    'class' => 'yii\swiftmailer\Mailer', 'useFileTransport' => false,
],
```

3 Запустите это URL в вашем браузере: http: //localhost: 8080/index . php?r=site/test. 

4 Проверьте  <http://www.fakemailgenerator.com/inbox/teleworm.us/john2/>.
![](img/068_1.jpg)

Как это работает…
---
Мы создали модель статьи и добавили обработчик для события ActiveRecord: : EVENT_AFTER_INSERT в нашу модель статьи. Это означает, что каждый раз, когда мы сохраняем новую статью, событие инициируется, и наш прикрепленный обработчик будет вызван.
В реальном мире, мы хотели бы уведомить наших подписчиков блога каждый раз, когда мы публикуем новую статью. В реальном приложении у нас будет Таблица подписчиков или пользователей и с различными разделами блога, а не только один блог. В этом примере после сохранения нашей модели мы уведомляем наших последователей john2@teleworm. us, shivawhite@cuvox. de, and kate@dayrep. com. На последнем шаге мы просто доказываем, что пользователи получили наши уведомления, особенно john2. Вы можете создать собственное мероприятие с любым именем. В этом примере мы используем встроенное событие ActiveRecord:: EVENT_AFTER_INSERT, которое вызывается после каждой вставки в базу данных.
Например, мы можем создать ваше собственное событие. Просто добавьте новое событие TestNew со следующим кодом:
```php
public function actionTestNew()
{
    $article = new Article();
    $article->name = 'Valentine\'s Day\'s coming? Aw crap! I forgot to get a girlfriend again!';
    $article->description = 'Bender is angry at Fry for dating a robot. Stay away from our women. You've got metal fever, boy. Metal fever';
    // $event is an object of yii\base\Event or a child class 
    $article->on(Article::EVENT_OUR_CUSTOM_EVENT, function($event) {
    $followers = ['john2@teleworm.us', 
                 'shivawhite@cuvox.de', 
                 'kate@dayrep.com' ]; 
    foreach($followers as $follower) {
        Yii::$app->mailer->compose()
        ->setFrom('techblog@teleworm.us')
        ->setTo($follower)
        ->setSubject($event->sender->name)
        ->setTextBody($event->sender->description)
        ->send();
    }
     echo 'Emails have been sent';
    });
     if ($article->save()) {
$article->trigger(Article::EVENT_OUR_CUSTOM_EVENT);
}
}
```
Также добавьте константу  EVENT_OUR_CUSTOM_EVENT  В models/Article :
```php
class Article extends \yii\db\ActiveRecord {
CONST EVENT_OUR_CUSTOM_EVENT = 'eventOurCustomEvent';
}
```
Запустите http: //localhost:8080/index.php?r=site/test-new.
Вы должны увидеть тот же результат, и все уведомления последователям будут отправлены снова. Главное отличие в том, что мы использовали наше пользовательское имя события.
После сохранения мы запустили наше событие. События могут быть вызваны вызовом триггером yii\base\Component::trigger(). Метод требует имя события и при необходимости объект события, описывающий параметры, которые должны быть переданы обработчикам событий.

Смотрите также
---
Для получения дополнительной информации о событиях обратитесь к   <http://www.yiiframework.com/doc-2.0/guide-concept-events.html> 
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/concept-events> 



Èñïîëüçîâàíèå âíåøíåãî êîäà
==
Ðåïîçèòîðèè ïàêåòîâ, ñòàíäàðòû PSR è ñîöèàëüíîå êîäèðîâàíèå ïðåäîñòàâëÿþò íàì ìíîæåñòâî âûñîêîêà÷åñòâåííûõ ìíîãîêðàòíî èñïîëüçóåìûõ áèáëèîòåê è äðóãèõ êîìïîíåíòîâ ñ áåñïëàòíûìè ëèöåíçèÿìè. Ìû ìîæåì ïðîñòî óñòàíîâèòü êàêèå-ëèáî âíåøíèå êîìïîíåíòû â ïðîåêò âìåñòî ðåèíæèíèðèíãà èõ ñ íóëÿ. Ýòî ïîâûøàåò ïðîèçâîäèòåëüíîñòü ðàçðàáîòêè è äåëàåò êîä áîëåå âûñîêîãî êà÷åñòâà.

Ïîäãîòîâêà 
---
Ñîçäàéòå íîâîå ïðèëîæåíèå ñ ïîìîùüþ composer, êàê îïèñàíî â îôèöèàëüíîì ðóêîâîäñòâå ïî <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. ïî ðóññêè <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Êàê ýòî ðàáîòàåò
---
Â ýòîì ðåöåïòå ìû ïîïûòàåìñÿ ïðèêðåïèòü íåêîòîðûå áèáëèîòåêè âðó÷íóþ è ÷åðåç Composer.

### Óñòàíîâêà áèáëèîòåêè ñ ïîìîùüþ Composer
Ïðè èñïîëüçîâàíèè NoSQL èëè äðóãèõ áàç äàííûõ áåç ïåðâè÷íûõ êëþ÷åé autoincrement íåîáõîäèìî ñîçäàòü óíèêàëüíûå èäåíòèôèêàòîðû âðó÷íóþ. Íàïðèìåð, âìåñòî ÷èñëîâîãî èäåíòèôèêàòîðà ìîæíî èñïîëüçîâàòü Óíèâåðñàëüíûé óíèêàëüíûé èäåíòèôèêàòîð (UUID). Äàâàéòå ñäåëàåì ýòî:

1 Óñòàíîâèì  êîìïîíåíò <https://github.com/ramsey/uuid> èñïîëüçóÿ Composer:

**composer require ramsey/uuid**

2 Ñîçäàíèå äåìîíñòðàöèîííîãî êîíòðîëëåðà êîíñîëè:
```php
<?php
namespace app\commands;
use Ramsey\Uuid\Uuid; 
use íii\console\Controller;
class UuidController extends Controller {
public function actionGenerate()
{
$this->stdout(Uuid::uuid4()->toString(). PHP_EOL);
$this->stdout(uuid::uuid4()->toString(). PHP_EOL);
$this->stdout(uuid::uuid4()->toString(). PHP_EOL);
$this->stdout(uuid::uuid4()->toString(). PHP_EOL);
$this->stdout(uuid::uuid4()->toString(). PHP_EOL);
}
}
```
3 È ïðîñòî çàïóñòèòå åãî:

***./yii uuid/generate***

4 Â ñëó÷àå óñïåõà, âû óâèäèòå ñëåäóþùèé ðåçóëüòàò:

25841e6c-6060-4a81-8368-4d99aa3617dd
fcac910a-a9dc-4760-8528-491c17591a26
4d745da3-0a6c-47df-aee7-993a42ed915c 
0f3e6da5-88f1-4385-9334-b47d1801ca0f 
21a28940-c749-430d-908e-1893c52f1fe0

Âîò è âñå! Òåïåðü âû ìîæåòå èñïîëüçîâàòü êëàññ Ramsey\uuid\uuid â ñâîåì ïðîåêòå.

### Óñòàíîâêà áèáëèîòåê âðó÷íóþ 
Ìû ìîæåì óñòàíîâèòü áèáëèîòåêó àâòîìàòè÷åñêè,êîãäà îíà ïðåäîñòàâëÿåòñÿ â âèäå ïàêåòà Composer. Â äðóãèõ ñëó÷àÿõ ìû äîëæíû óñòàíîâèòü åãî âðó÷íóþ.
Íàïðèìåð, ñîçäàéòå íåñêîëüêî ïðèìåðîâ áèáëèîòåê:

1 Ñîçäàéòå  ôàéë awesome/namespaced/Library.php ñî ñëåäóþùèì êîäîì:
```php
<?php
namespace awesome\namespaced;
class Library {
    public function method()
    {
        return 'I am an awesome library with namespace.';
    }
}
```
2 Ñîçäàéòå ôàéë old/OldLibrary.php:
```php
<?php
class OldLibrary {
    function method()
    {
        return 'I am an old library without namespace.';
    }
}
```

3 Ñîçäàéòå íàáîð ôóíêöèé â ôàéëå old/functions.php:
```php
<?php
function simpleFunction()
{
    return 'I am a simple function.';
}
```
À òåïåðü íàñòðîéòå ýòîò ôàéë â íàøåì ïðèëîæåíèè:

4 Îïðåäåëèòå íîâûé ïñåâäîíèì äëÿ êîðíÿ ïðîñòðàíñòâà èìåí â ôàéëå config/web.php (â ðàçäåëå ïñåâäîíèìû):
```php
$config = [
    'id' => 'basic',
    'basePath' => dirname(__DIR__),
    'bootstrap' => ['log'],
    'aliases' => [
       '@awesome' => '@app/awesome',
    ],
    'components' => [
        // ...
    ],
    'params' =>  // ...
];
```
èëè ÷åðåç ìåòîä setAlias:
```php
Yii::setAlias('@awesome','@app/awesome');
```

5 Îïðåäåëèòå ïðîñòîé ïóòü ê ôàéëó êëàññà â âåðõíåé ÷àñòè config/web.php -ôàéëà: 
```php
Yii::$classMap['OldLibrary'] = '@old/OldLibrary.php';
```

6 Íàñòðîéòå àâòîìàòè÷åñêóþ çàãðóçêó functions.php ôàéë â composer.json: 
```php
"require-dev": {
   ...
    },
"autoload": {
    "files": ["old/functions.php"]
    },
"config": {
     ...
    },
```
È ïðèìåíèòå èçìåíåíèÿ:

***composer update***

7 À òåïåðü ñîçäàäèì ïðèìåð êîíòðîëëåðà:
```php
<?php
namespace app\controllers; 
use yii\base\Controller;

class LibraryController extends Controller {
    public function actionIndex()
    {
        $awesome = new \awesome\namespaced\Library(); 
        echo '<pre>' . $awesome->method() .	'</pre>';
        $old = new \OldLibrary();
        echo '<pre>' . $old->method() .	'</pre>';
        echo '<pre>' . simpleFunction() .	'</pre>';
    }
}
```
è îòêðîéòå ñòðàíèöó:

![](img/072_1.jpg)



Использование кода Yii2 в других фреймворках
===
 Если вы хотите использовать код  Yii2 с другими фреймвоками, просто добавьте параметры yii2 в composer.json:
```php
{
    "extra": {
        "asset-installer-paths": {
            "npm-asset-library": "vendor/npm",
            "bower-asset-library": "vendor/bower"
        }
     }
}
```
И установите фреймворк: 

***composer require yiisoft/yii2***

Теперь откройте сценарий входа вашего приложения (на ZendFramework, Laravel, Symfony и многих других), требуйте автозапуска Yii2 и создайте экземпляр приложения Yii:

```php
require( __DIR__  . '/../vendor/autoload.php');
require( __DIR__  . '/../vendor/yiisoft/yii2/Yii.php');
$config = require(__DIR__ . '/../config/yii/web.php');
new yii\web\Application($config);
```
Вот и все! Теперь вы можете использовать экземпляры yii::$app, модели, виджеты и другие компоненты из Yii2.

Как это работает…
---
В первом случае мы просто устанавливаем новый пакет Composer в наш проект и используем его, потому что это composer.json файл определяет все аспекты автоматической загрузки файлов библиотеки.
Но во втором случае у нас не было пакетов Composer и файлы регистрировались в механизме автозапуска вручную. В Yii2 мы можем использовать псевдонимы и yii::$classMap для регистрации корней пространств имен PSR-4 и для отдельных файлов.
Но в качестве альтернативы мы можем использовать Composer autoloader для всех случаев. Просто определите расширенный раздел автозапуска в composer.файл json, как это:
```php

"autoload": {
    "psr-0": { "": "old/" },
    "psr-4": {"awesome\\": "awesome/"},
    "files": ["old/functions.php"]
}
```
Примените изменения с помощью этой команды: 

***composer update***

Прямо сейчас вы можете удалить псевдонимы и определения $classMap из файлов конфигурации и убедиться, что страница примера все еще работает правильно:
![](img/074_1.jpg)

Этот пример полностью использует autoloader Composer вместо autoloader фреймворка.

Смотрите так же
---

Дополнительные сведения об интеграции внешнего кода в Yii2 и кода платформы в наши проекты см. в руководстве по адресу <http://www.yiiframework.com/doc-2.0/gurde-tutorial-yii-intpgration.html>   по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/tutorial-yii-integration> 
* Подробнее об псевдонимах см. <http://www.yiiframework.com/doc-2.0/guide-concept-aliases.html>
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/concept-aliases> 
*  Подробнее о разделе autoload композитора.json обратитесь к <https://getcomposer.org/doc/04-schema.md#autoload> 
* А также вы можете просматривать любые пакеты Composer по адресу  <https://packagist.org>




Ãëàâà 2. Ìàðøðóòèçàöèÿ, êîíòðîëëåðû è ïðåäñòàâëåíèÿ
======== 

Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:

*	Íàñòðîéêà ïðàâèë URL 
*	Ñîçäàíèå Url-Àäðåñîâ
*	Èñïîëüçîâàíèå ðåãóëÿðíûõ âûðàæåíèé â ïðàâèëàõ URL
*	Èñïîëüçîâàíèå áàçîâîãî êîíòðîëëåðà
*	Èñïîëüçîâàíèå àâòîíîìíûõ äåéñòâèé
*	Ñîçäàíèå ïîëüçîâàòåëüñêîãî ôèëüòðà
*	Îòîáðàæåíèå ñòàòè÷åñêèõ ñòðàíèö
*	Èñïîëüçîâàíèå flash-Ñîîáùåíèé
*	Èñïîëüçîâàíèå êîíòåêñòà êîíòðîëëåðà â ïðåäñòàâëåíèè
*	Ïîâòîðíîå èñïîëüçîâàíèå ïðåäñòàâëåíèé ñ ÷àñòÿìè
*	Áëîê using
*	Èñïîëüçîâàíèå äåêîðàòîðîâ
*	Îïðåäåëåíèå íåñêîëüêèõ ìàêåòîâ
*	Ðàçáèâêà íà ñòðàíèöû è ñîðòèðîâêà äàííûõ

Ââåäåíèå
======
Ýòà ãëàâà ïîìîæåò âàì óçíàòü íåêîòîðûå ïîëåçíûå âåùè î yii URL ìàðøðóòèçàòîð, êîíòðîëëåðû è 
ïðåäñòàâëåíèÿ. Âû ñìîæåòå ñäåëàòü âàøè êîíòðîëëåðû è ïðåäñòàâëåíèÿ áîëåå ãèáêèìè.


Настройка правил URL
===
В этом рецепте мы узнаем, как настроить правила URL. 
Прежде чем мы начнем позволяет настроить приложение.

Подготовка
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation> .

2 Создайте контроллер @app/controllers/TestController.php со следующим кодом внутри:
```php
<?php

namespace app\controllers;

use yii\helpers\Html;
use yii\web\Controller;

class TestController extends Controller
{
    public function actionIndex()
    {
        return $this->renderContent(Html::tag('h2',
            'Index action'
        ));
    }

    public function actionPage($alias)
    {
        return $this->renderContent(Html::tag('h2',
            'Page is '. Html::encode($alias)
        ));
    }
}
```
Это контроллер приложений, в котором который мы собираемся настроить URL-адреса.

3 Настройте сервер приложений на использование чистых URL-адресов. Если вы используете Apache с включеными mod_rewrite и allowoverride , то вы должны добавить следующие строки в файл .htaccess в каталоге @web:
```php
Options +FollowSymLinks IndexIgnore */*
RewriteEngine on
# if a directory or a file exists, use it directly RewriteCond %{REQUEST_FILENAME} !-f 
RewriteCond %{REQUEST_FILENAME} !-d
# otherwise forward it to index.php 
RewriteRule . index.php
```

Как это работает
---

Наш веб-сайт должен отображать индексную страницу в /home и все другие страницы в /page/<alias_ here>. Кроме того, параметр /about должен приводить к странице с псевдонимом about:

1 Добавьте следующую конфигурацию компонента urlManager в @app/config/web.php:

```php

'components' => [
// . .
    'urlManager' => [
         'enablePrettyUrl' => true,
         'rules' => [
             'home' => 'test/index',
             '<alias:about>' => 'test/page',
             'page/<alias>' => 'test/page',
         ]
    ],
// ..
],
```
После сохранения изменений вы сможете просматривать следующие URL-адреса:

fe/home

fe/about

fe/page/about

/page/test

2  Попробуйте запустить /home URL, и вы получите следующее: 
![](img/077_1.jpg)

Давайте рассмотрим, что было сделано и почему это работает. Начнем с правой части первого правила

3 Затем попробуйте запустить страницу /about:
![](img/077_2.jpg)

Как это работает
---
```php
'home' => 'test/index',
```
Что такое test/index? В приложении, каждый контроллер и его действия имеют соответствующие внутренние маршруты. Формат для внутреннего маршрута-moduleiD/controlleriD /actioniD. Например, метод actionPage Testcontroller соответствует маршруту test/page. Таким образом, чтобы получить идентификатор контроллера, вы должны взять его имя без постфикса контроллера и сделать его первую букву строчной. Чтобы получить идентификатор действия, следует взять имя метода действия без префикса действия и снова сделать его первую букву строчной.
Итак, что такое home? Чтобы лучше понять это, нам нужно знать, по крайней мере, поверхностно, что происходит, когда мы получаем доступ к нашему приложению, используя различные URL-адреса.
Когда мы используем /home, маршрутизатор URL проверяет наши правила один за другим, начиная с вершины, пытаясь соответствовать URL, введенному с правилом. Если соответствие найдено, то маршрутизатор получает контроллер и его действие от внутреннего маршрута, назначенного правилу, и выполняет его. Итак, /home-это шаблон URL, который определяет, какие URL будут обрабатываться правилом, которому он принадлежит.

Это еще не все...
---
Можно также создать параметризованные правила, используя специальный синтаксис. Рассмотрим третье правило: 
```php
'page/<alias>' => test/page',
```
Здесь мы определяем параметр alias, который должен быть указан в URL после /page/. Это может быть практически что угодно и он будет передан в качестве параметра $alias следующим:
```php
TestController::actionPage($alias) .
```
Для такого параметра можно определить шаблон. Мы сделали это по второму правилу, а именно:

```php
'<alias:about>' => test/page',
```

Псевдоним здесь должен совпадать, иначе правило не будет применяться.

Смотрите так же
---
См. следующие ссылки для дальнейшего чтения:
* <http://www.yiiframework.com/doc-2.0/guide-runtime-routing.html>
* По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/runtime-routing>
* <http://www.Yiiframework.com/doc-2.0/guide-runtime-url-handling.html> (ссылка не рабочая)
* <http://www.yiiframework.com/doc-2.0/yii-web-urlmanager.html>
* Рецепт Использование регулярных выражений в URL правилах



Создание Url-Адресов
==
Yii позволяет не только маршрутизировать URL-адреса к различным действиям контроллера, но и генерировать 
URL-адрес, указав правильный внутренний маршрут и его параметры. Это действительно полезно, потому что вы 
можете сосредоточиться на внутренних маршрутах при разработке приложения, и только беспокоиться о реальных 
URL-адресов, прежде чем идти в прямом эфире. Никогда не указывайте URL напрямую и убедитесь, что вы 
используете группу инструментов YII URL. Это позволит вам изменить URL-адреса без перезаписи большого 
количества кода приложения.

Подготовка 
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве по 
<http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. по русски <http://yiiframework.domain-
na.me/doc/guide/2.0/ru/start-installation>

2	Найдите @app/config/web.php файл и заменить массив правил следующим образом:
```php
'urlManager' => array(
'enablePrettyUrl' => true,
'showScriptName' => false,
),
```
3	Настройте сервер приложений на использование чистых URL-адресов. Если вы используете Apache с 
mod_rewrite и allowoverride включен, то вы должны добавить следующие строки в  файл .htaccess в 
папке @app/web:
```php
Options +FollowSymLinks 
IndexIgnore */*
RewriteEngine on
#	if a directory or a file exists, use it directly 
RewriteCond %{REQUEST_FILENAME} !-f 
RewriteCond %{REQUEST_FILENAME} !-d
#	otherwise forward it to index.php 
#	RewriteRule . index.php
```

Как это сделать...
---
1.	В каталоге @app/controllers создайте BlogController со следующим кодом:
```php
<?php
namespace app\controllers; use yii\web\Controller;
class BlogController extends Controller {
    public function actionIndex()
    {
        return $this->render('index');
    }
    public function actionRssFeed($param)
    {
        return $this->renderContent('This is RSS feed for our blog and '	. $param);
    }
    public function actionArticle($alias)
    {
        return $this->renderContent('This is an article with alias ' . $alias);
    }
    public function actionList()
    {
         return $this->renderContent('Blog\'s articles here');
    }
    public function actionHiTech()
    {
          return $this->renderContent('Just a test of action which contains more than one words in the name') ;
    }
}
```
Это наш контроллер блога, что мы собираемся генерировать пользовательские URL-адреса для.

2.	В каталоге @app/controllers создайте TestController со следующим кодом:
```php
<?php
namespace app\controllers; use Yii;
use yii\web\Controller;
class TestController extends Controller {
    public function actionUrls()
    {
        return $this->render('urls');
    }
}
```

3.	В каталоге @app/views создайте тестовый каталог и url.php  файл, и поместите следующий код 
внутри:
```php
<?php
use yii\helpers\Url; use 
yii\helpers\Html;
?>
<h1>Generating URLs</h1>
<h3>Generating a link with URL to <i>blog</i> controller and <i>article</i> action with alias as param</h3>
<?= Html::a('Link Name', ['blog/article', 'alias' => 'someAlias']); ?>
<h3>Current url</h3>
<?=Url::to(' ')?>
<h3>Current Controller, but you can specify an action</h3>
<?=Url::toRoute(['view', 'id' => 'contact']);?>
<h3>Current module, but you can specify controller and action</h3>
<?= Url::toRoute('blog/article')?>
<h3>An absolute route to blog/list </h3>
<?= Url::toRoute('/blog/list')?>
<h3> URL for <i>blog</i> controller and action <i>HiTech</i> </h3>
<?= Url::toRoute('blog/hi-tech')?>
<h3>Canonical URL for current page</h3>
<?= Url::canonical()?>
<h3>Getting a home URL</h3>
<?= Url::home()?>
<h3>Saving a URL of the current page and getting it for re-use</h3>
<?php Url::remember()?>
<?=Url::previous()?>
<h3>Creating URL to <i>blog</i> controller and <i>rss-feed</i> action while 
URL helper isn't available</h3>
<?=Yii::$app->urlManager->createUrl(['blog/rss-feed', 'param' => 'someParam'])?>
<h3>Creating an absolute URL to <i>blog</i> controller and <i>rss-
feed</i></h3> <p>It's very useful for emails and console applications</p>
<?=Yii::$app->urlManager->createAbsoluteUrl(['blog/rss-feed', 'param' =>
' someParam'])?>
```
4 Перейдите по URL http: //yii-book.app/test/urls, и вы увидите вывод. (См. полный список методов 
в предыдущем коде.):
![](img/081_1.jpg)
 
Как это работает
---
Нам нужно генерировать URL-адреса, указывающие на действия контроллера (RssFeed, Article, List, HiTech) в BlogController.
В зависимости от того, где нам это нужно, есть разные способы сделать это, но основы одинаковы. Перечислим некоторые 
методы, которые генерируют адреса.
Что такое внутренний маршрут? Каждый контроллер и его действия имеют соответствующие маршруты. Формат для 
маршрута-moduleID/controllerID/actionID. Например, метод actionHitech BlogController соответствует маршруту blog/hi-
tech.
Чтобы получить идентификатор контроллера, вы должны взять его имя без постфикса контроллера и сделать его первую 
букву строчной. Чтобы получить идентификатор действия, необходимо взять имя метода действия без префикса 
действия и сделать первую букву в каждом слове строчной, и отделить их знаком тире ( - ) (например, actionHiTech будет 
hi-tech).
Переменные $_GET-это параметры, которые будут переданы действию с указанным внутренним маршрутом. Например, 
если мы хотим создать URL-адрес статьи BlogController::action, которая передает ему параметр $_GET[ 'name'], это 
можно сделать следующим образом:
```php
<?= HTML::a('Link Name', ['blog/article', 'alias' => 'someAlias']); ?>
```

Относительные URL-адреса могут использоваться внутри вашего приложения, в то время как абсолютные должны 
использоваться для указания на места за пределами вашего веб-сайта (например, другие веб-сайты) или для ссылки на 
ресурсы, предназначенные для доступа извне (RSS-каналы, электронные письма и так далее).
Вы можете сделать это легко с менеджером адрес. Диспетчер URL-адресов-это встроенный компонент приложения с 
именем urlManager. Вы должны использовать этот компонент, который доступен из веб-и консольных приложений через

```php
Yii::$app->urlManager.
```

Если не удается получить экземпляр контроллера, например при реализации консольного приложения, 
можно использовать два следующих метода создания urlManager:

```php
<?=Yii::$app->urlManager->createUrl(['blog/rss-feed', 'param' => 'someParam'])?> 
<?=Yii::$app->urlManager->createAbsoluteUrl(['blog/rss-feed', 'param' => 'someParam'])?>
```

Есть еще.
---

Дополнительные сведения см. по следующим URL-адресам:
*	<https://en.wikipedia.org/wiki/Canonical link element>
*	<http://www.yiiframework.com/doc-2.0/guide-structure-controllers.html>
	по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-controllers>
*	<http://www.yiiframework.com/doc-2.0/guide-runtime-routing.html>
	по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/runtime-routing>
*	<http://www.viiframework.com/doc-2.0/guide-helper-url.html>
	по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/helper-url> 
*	<http://www.yiiframework.com/doc-2.0/yii-web-urlmanager.html>
	
Смотрите так же
---
Рецепт Конфигурирование URL правил


Использование регулярных выражений в правилах URL
==
Одной из скрытых особенностей YII URL router является то, что вы можете использовать регулярные выражения, которые являются довольно мощными средством для обработки строк.

Подготовка 
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве по http://www.yiiframework.com/doc-2.0/guide-start-installation.html.
 по русски http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation 

2 В каталоге @app/controllers создайте Postcontroller.php использует следующее:
```php
<?php
namespace app\controllers;
use yii\helpers\Html; 
use yii\web\Controller;
class PostController extends Controller {
    public function actionView($alias)
    {
        return $this->renderContent(Html::tag('h2','Showing post with alias '. Html::encode($alias)));
    }
    public function actionIndex($type = 'posts', $order = 'DESC')
    {
        return $this->renderContent(Html::tag('h2','Showing ' . Html::encode($type) . ' ordered ' . Html::encode($order)));
    }
    public function actionHello($name)
    {
         return $this->renderContent(Html::tag('h2','Hello, ' . Html::encode($name) . '!'));
    }
}
```
Это наш контроллер приложений, к которому мы собираемся получить доступ, используя наши пользовательские URL-адреса.

3 Настройте сервер приложений на использование чистых URL-адресов. Если вы используете Apache с mod_rewrite и allowoverride включен, то вы должны добавить следующие строки в  файл .htaccess в папке @web:
```php
Options +FollowSymLinks IndexIgnore */*
RewriteEngine on
# if a directory or a file exists, use it directly 
RewriteCond %{REQUEST_FILENAME} !-f 
RewriteCond %{REQUEST_FILENAME} !-d
# otherwise forward it to index.php 
RewriteRule . index.php
```

Как это сделать...
---
Мы хотим, чтобы наше действие Postcontroller принимало параметры в соответствии с некоторыми заданными правилами и давало 404 не найденных ответа HTTP для всех параметров, которые не совпадают. Кроме того, post/index должен иметь архив URL-адресов псевдонимов.
Добавьте следующую конфигурацию компонента urlManager в @app/config/web.РНР:
```php
'components' => [
    // ..
    'urlManager' => [
        'enablePrettyUrl' => true,
        'rules' => [
                   'post/<alias:[-a-z]+>' => 'post/view',
                   '<type:(archive|posts)>' => 'post/index',
                   '<type:(archive|posts)>/<order:(DESC|ASC)>' => 'post/index',
                   'sayhello/<name>' => 'post/hello',
                   ]
    ],
    // ..
],
```
Следующие URL-адреса будут успешными:
* http://yii-book.app/post/test
* http://yii-book.app/posts
* http://yii-book.app/archive
* http://yii-book.app/posts/ASC
* http://yii-book.app/sayhello

Не удастся выполнить следующие URL-адреса:

* http: //yii-book.app/archive/test
* http: //yii-book.app/post/another_post

На следующем снимке экрана показано, что URL http: //yii-book.app/post/test успешно запущен:
(от переводчика: забавная картинка с другим адресом)
![](img/085_1.jpg)

На следующем снимке экрана показано, что URL http: //yii-book. app/archive тоже успешно работает:
![](img/086_1.jpg)

На следующем снимке экрана показано, что URL http: //yii-book.app/archive/test не был успешно запущен и произошла ошибка:
![](img/086_2.jpg)

Как это работает…
---
Регулярные выражения можно использовать как в определении параметра, так и в остальной части правила. Давайте читать наши правила одно за другим:
```php
'post/<alias:[-a-z]+>' => 'post/view',
```
Параметр alias должен содержать одну или несколько английских букв или дефис. Никакие другие символы не допускаются
```php
'(posts|archive)' => 'post/index',
'(posts|archive)/<order:(DESC|ASC)>' => 'post/index',
```
КАК СООБЩЕНИЯ, ТАК И АРХИВ ВЕДУТ К POST/INDEX. ПАРАМЕТР ORDER МОЖЕТ ПРИНИМАТЬ ТОЛЬКО ДВА ЗНАЧЕНИЯ – DESC И ASC:
```php
'sayhello/<name>' => 'post/hello',
```
Вы должны указать часть имени, но нет никаких ограничений на то, какие символы разрешены. Обратите внимание, что независимо от используемого правила, Разработчик никогда не должен предполагать, что входные данные безопасны.
![](img/087_1.jpg)


Это еще не все...
---
Чтобы узнать больше о регулярных выражениях, можно использовать следующие источники:
* <http://www.php.net/manual/en/reference.pcre.pattern.syntax.php>
* Mastering Regular Expressions, Jeffrey Fried! доступна по адресу <http://regex.info/>.

Смотрите так же
---
* Рецепт Конфигурация URLправил


Использование базового контроллера
===

Во многих фреймворках концепция базового контроллера, расширяемая другими, описана прямо в 
руководстве. В Yii это не в руководстве, так как вы можете достичь гибкости многими другими способами. 
Тем не менее, использование базового контроллера возможно и может быть полезно.
Допустим, мы хотим добавить некоторые контроллеры, которые будут доступны только при входе 
пользователя в систему. Мы, конечно, можем установить это ограничение для каждого контроллера 
отдельно, но мы сделаем это лучше.

Подготовка
---

Создайте новое приложение с помощью composer, как описано в официальном руководстве по 
<http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. по русски <http://yiiframework.domain-
na.me/doc/guide/2.0/ru/start-installation> 

Как это сделать...
---

1 Во-первых, нам понадобится базовый контроллер, который будут использовать наши пользовательские 
контроллеры. Давайте создадим @app/components/BaseController.php со следующим кодом:
```php
<?php
namespace app\components; 
use Yii;
use yii\web\Controller;
use yii\filters\AccessControl;
class BaseController extends Controller 
{
	public function actions()
		{
			return [
			'error' => ['class' => 'yii\web\ErrorAction'],
		];
	}
	public function behaviors()
	{
		return [
			'access' => [
				'class' => AccessControl::className(),
				'rules' => [
					[
						'allow' => true,
						'actions' => 'error'
					],
					[
						'allow' => true,
						'roles' => ['@'],
					],
				],
			]
		];
	}
}
```
Этот контроллер имеет схему действий с действием ошибка.


2 Теперь создайте Testcontroller с помощью Gii, но задайте значение поля базового класса как 
app/components/BaseController:
![](img/089_1.jpg)

Вы получите что-то похожее на следующее:
```php
<?php
namespace app\controllers;
class Testcontroller extends \app\components\BaseController {
	public function actionIndex()
	{
		return $this->render('index');
	}
}
```

3 Теперь Ваш TestController будет доступен только в том случае, если пользователь вошел в 
систему, даже если мы не объявили его явно в классе TestController. Вы можете проверить это, 
зайдя <http://yii-book.app/index.php?r=test/index> не зарегестрировавшись  в системе.

Как это работает...
---

Хитрость заключается не более чем в наследовании базового класса. Если фильтры или правила управления 
доступом не найдены в TestController, то они будут вызваны из SecureController.

Это еще не все...
---
Если необходимо расширить метод базового контроллера, имейте в виду, что он не должен быть 
переопределен. Например, нам нужно добавить действие страницы в Карту действий контроллера:
```php
<?php
namespace app\controllers;
use yii\helpers\ArrayHelper; use app\components\BaseController;
class TestController extends BaseController {
	public function actions()
	{
		return ArrayHelper::merge(parent::actions(), [
			'page' => [
				'class' => 'yii\web\ViewAction',
			],
		]);
	}
	public function behaviors()
	{
		$behaviors = parent::behaviors();
		$rules = $behaviors['access']['rules'];
		$rules = ArrayHelper::merge(
			$rules,
			[
				[
					'allow' => true,
					'actions' => ['page']
				]
			]
		);
		$behaviors['access']['rules'] = $rules; return 
		$behaviors;
	}
	public function actionIndex()
	{
		return $this->render('index');
	}
}
```
Для получения дополнительной информации обратитесь к <https://www.yiiframework.com/doc/api/2.0/yii-base-controller>.


Использование автономных действий
==

В Yii можно определить действия контроллера как отдельные классы, а затем подключить их к контроллерам.
Это поможет вам повторно использовать некоторые общие функциональные возможности.
Например, можно переместить серверную часть для полей автозаполнения в действие и сэкономить некоторое время, не записывая ее снова и снова.
Другим примером является то, что мы можем создавать все операции CRUD как отдельные автономные действия. Мы будем писать, создавать, просматривать и удалять операции модели и просматривать список операций моделей.

Подготовка
---

1 Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Давайте создадим таблицу post. Создайте миграцию для этого с помощью следующей команды:
**./yii migrate/create create_post_table**

3 Обновите только что созданные методы миграции и список импортированных классов следующим образом:
```php
<?php
use yii\db\Schema; 
use yii\db\Migration;
class m150719_152435_create_post_table extends Migration {const TABLE_NAME = '{{%post}}';
	public function up()
	{
		$tableOptions = null;
		if ($this->db->driverName === 'mysql') {
			$tableOptions = 'CHARACTER SET utf8 COLLATE utf8_general_ci ENGINE=InnoDB';
		}
		$this->createTable(self::TABLE_NAME, [
			'id' => Schema::TYPE_PK,
			'title' => Schema::TYPE_STRING.'(255) NOT NULL',
			'content' => Schema::TYPE_TEXT.' NOT NULL',
		], $tableOptions);
		for ($i = 1; $i < 7; $i++) {
				 $this->insert(self::TABLE_NAME, [
					'title' => 'Test article #'.$i,
					'content' => 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. '
					.'Sed sit amet mauris est. Sed at dignissim dui. '
					.'Phasellus arcu massa, facilisis a fringilla sit amet, '
					. ' rhoncus ut enim.',
				 ]);
		}
	}

	public function down()
	{
		$this->dropTable(self::TABLE_NAME);
	}
}
```
4 Установите все миграции с помощью следующей команды:

**./yii migrate up**

5 Создайте модель Post с помощью Gii.

Как это сделать...
---

1 Создайте автономное действие @app/actions/CreateAction.php следующим образом:
```php
<?php
namespace app\actions; 
use Yii;
use yii\base\Action;
class CreateAction extends Action {
	public $modelClass;
	public function run()
	{
		$model = new $this->modelClass();
		if ($model->load(Yii::$app->request->post()) && $model->save()) {
			$this->controller->redirect(['view', 'id' => $model->getPrimaryKey()]); 
		} else {
			return $this->controller->render('//crud/create', ['model' => $model]);
		}
	}
}
```

2 Создайте автономное действие @app/actions/DeleteAction.php следующим образом:
```php
<?php
namespace app\actions;
use yii\base\Action;
use yii\web\NotFoundHttpException;
class DeleteAction extends Action {
	public $modelClass;
	public function run($id)
	{
		$class = $this->modelClass;
		if (($model = $class::findOne($id)) === null) {
			throw new NotFoundHttpException('The requested page does not exist.');
		}
		$model->delete();
		return $this->controller->redirect(['index']);
	}
}
```

3 Создайте автономное действие @app/actions/IndexAction.php следующим образом:
```php
<?php
namespace app\actions;
use yii\base\Action; 
use yii\data\Pagination;
class IndexAction extends Action {
	public $modelClass; 
	public $pageSize = 3;
	public function run()
	{
		$class = $this->modelClass;
		$query = $class::find();
		$countQuery = clone $query;
		$pages = new Pagination([
			'totalCount' => $countQuery->count(),
		]);
		$pages->setPageSize($this->pageSize);
		$models = $query->offset($pages->offset)->limit($pages->limit)->all();
		return $this->controller->render('//crud/index', [
			'pages' => $pages,
			'models' => $models
		]);
	}
}
```

4 Создайте автономное действие @app/actions/ViewAction.php следующим образом:
```php
<?php
namespace app\actions;
use yii\base\Action;
use yii\web\NotFoundHttpException;
class ViewAction extends Action {
	public $modelClass;
	public function run($id)
	{
		$class = $this->modelClass;
		if (($model = $class::findOne($id)) === null) {
			throw new NotFoundHttpException('The requested page does not exist.');
		}
		return $this->controller->render('//crud/view', [
			'model' => $model
		]);
	}
}
```

5 Создайте файл представления @app/views/crud/create.php следующим образом:
```php
<?php
use yii\helpers\Html; 
use yii\widgets\ActiveForm;
/*
* @var yii\web\View $this 
* */
?>
<h1><?= Yii::t('app', 'Create post'); ?></h1>
<?php $form = ActiveForm::begin();?>
<?php $form->errorSummary($model); ?>
<?= $form->field($model, 'title')->textInput() ?>
<?= $form->field($model, 'content')->textarea() ?>
<?= Html::submitButton(Yii::t('app', 'Create'), ['class' => 'btn btn-primary']) ?> 
<?php ActiveForm::end(); ?>
```php

6 Создайте файл представления @app/views/crud/index.php следующим образом:
```php
<?php
use yii\widgets\LinkPager; 
use yii\helpers\Html; 
use yii\helpers\Url;
/*
* @var yii\web\View $this
* @var yii\data\Pagination $pages
* @var array $models 
* */
?>
<h1>Posts</h1>
<?= Html::a('+ Create a post', Url::toRoute('post/create')); ?>
<?php foreach ($models as $model):?>
<h3><?= Html::encode($model->title);?></h3>
<p><?= Html::encode($model->content);?></p>
<p>
<?= Html::a('view', Url::toRoute(['post/view', 'id' => $model->id]));?> | <?= Html::a('delete', Url::toRoute(['post/delete', 'id' => $model->id]));?>
</p>
<?php endforeach; ?>
<?= LinkPager::widget(['pagination' => $pages,]); ?>
```

7 Создайте файл представления @app/views/crud/view.php следующим образом:
```php
<?php
use yii\helpers\Html; 
use yii\helpers\Url;
/*
* @var yii\web\View $this
* @var app\models\Post $model 
* */
?>
<p><?= Html::a('< back to posts', Url::toRoute('post/index')); ?></p>
<h2><?= Html::encode($model->title);?></h2>
<p><?= Html::encode($model->content);?></p>
```
   Чтобы использовать автономные действия, мы объявили его в карте действий, переопределив метод actions. 
   
   8 Запустите post/index:
   ![](img/095_1.jpg)

Как это работает…
---
Каждый контроллер может быть построен из отдельных действий, как пазл из кусочков. Разница в том, что вы можете сделать автономные действия очень гибкими и использовать их во многих местах.
В наших действиях мы определили публичное свойство Model class, которое помогает настроить определенный класс модели в методе actions PostController.

Смотрите так же
---
 Для получения дополнительной информации обратитесь к  <http://www.yiiframework.com/doc-2.0/guide-structure- controllers.html#standalone-actions>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-controllers>



Создание пользовательского фильтра
==
Фильтры-это объекты, которые выполняются до и / или после действий контроллера. Например, фильтр управления доступом может выполняться перед действиями, чтобы гарантировать, что к ним разрешен доступ определенным конечным пользователям; фильтр сжатия содержимого может выполняться после действий по сжатию содержимого ответа перед его отправкой конечным пользователям.
Фильтр может состоять из предфильтра (логика фильтрации, применяемая перед действиями) и / или постфильтра (логика, применяемая после действий). Фильтры-это, по сути, особый вид поведения. Таким образом, использование фильтров аналогично использованию поведения.
Допустим, у нас есть веб-приложение, которое предоставляет пользовательский интерфейс для работы только в указанные часы, например, с 10 утра до 6 вечера.

Подготовка
---
Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
(по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---

1 Создайте контроллер @app/controllers/TestController. php, следующим образом:
```php
<?php
namespace app\controllers;
use app\components\CustomFilter; 
use yii\helpers\Html; 
use yii\web\Controller;
class TestController extends Controller {
	public function behaviors()
	{
		return [
			'access' => [
				'class' => CustomFilter::className(),
			],
		];
	}
	public function actionIndex()
	{
		return $this->renderContent(Html::tag('h1','This is a test content'));
	}
}
```

2 Создайте новый фильтр @app/components/CustomFilter.php, следующим образом:
```php
<?php
namespace app\components;
use Yii;
use yii\base\ActionFilter; 
use yii\web\HttpException;
class CustomFilter extends ActionFilter {
	const WORK_TIME_BEGIN = 10; 
	const WORK_TIME_END = 18;
	protected function canBeDisplayed()
	{
		$hours = date('G');
		return $hours >= self::WORK_TIME_BEGIN && $hours <= self::WORK_TIME_END;
	}
	public function beforeAction($action)
	{
		if (!$this->canBeDisplayed())
			{
				$error = 'This part of website works from '
				. self::WORK_TIME_BEGIN .	' to '
				. self::WORK_TIME_END .	' hours.';
				throw new HttpException(403, $error);
			}
		return parent::beforeAction($action);
	}
	public function afterAction($action, $result)
	{
		if (Yii::$app->request->url == '/test/index') {
			Yii::trace("This is the index action");
		}
		return parent::afterAction($action, $result);
	}
}
```
![](img/098_1.jpg)

3 Если вы посетите эту страницу за пределами указанного периода времени, вы получите следующее:

Как это работает...
---
Сначала мы добавили часть кода в наш контроллер, который реализует наш пользовательский фильтр:
```php
public function behaviors()
{
	return [
		'access' => [
			'class' => CustomFilter::className(),
		],
	];
}
```
По умолчанию фильтр применяется ко всем действиям контроллера, но мы можем указать действия, для которых он будет применяться, или даже исключить действия из нашего фильтра.
У вас есть два действия внутри него—beforeAction и afterActions. Первый запускается перед действиями контроллера, а следующий-после.
В нашем простом примере мы определили условие, которое не разрешает доступ к веб-сайту, если время раньше 10 утра, а в методе after мы просто запускаем метод трассировки, если текущий путь-test/index.
Результат можно увидеть в отладчике, в разделе журнал:
![](img/099_1.jpg)

В реальных приложениях фильтры более сложны, а также Yii2 предоставляет множество встроенных фильтров, таких как core, authentication, content negotiator, http cache end и т. д.

Смотрите так же
---
Для получения дополнительной информации обратитесь к <http://www.yiiframework.com/doc-2.0/guidestructure-filters.html>
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-filters> 



Отображение статических страниц
===
Если у вас есть несколько статических страниц и Вы не собираетесь менять их очень часто, то не стоит запрашивать базу данных и внедрять для них управление страницами.

Подготовка
---
Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это работает
---

1 Создайте файл контроллера тестирования @app/controllers/TestController.php, следующим образом:
```php
<?php
namespace app\controllers;
use yii\web\Controller;
class TestController extends Controller {
    public function actions()
    {
        return [
                'page' => [
                            'class' => 'yii\web\ViewAction',
                          ]
                ];
    }
}
```

2 Теперь поместите свои страницы в views/test/ pages и назовите их index.php и contact.php. Содержание index.php выглядит следующим образом:
```php
<h1>Index</h1> content of index file
Contact.php content is:
<h2>Contacts</h2>
<p>Our contact: contact@localhost</p>
```

3 Теперь вы можете проверить свои страницы, введя URL,
<http://yii-book.app/index.php?r=test/page&view=contact>:
![](img/101_1.jpg)

4 Кроме того, вы можете ввести URL-адрес http: //yii-book. app/test/page/view/about, если Вы настроили чистые URL-адреса с форматом пути.

Как это работает...
---
Мы подключаем внешнее действие с именем \yii\web\viewAction, которое просто пытается найти представление с именем, совпадающим с предоставленным параметром $_GET. Если оно там, то оно показывает его. Если нет, то это даст вам 404 "не найдена страница". Если viewParam не задан, будет использоваться значение defaultview.

Есть еще.
---
О ViewAction
Есть некоторые полезные параметры \yii\web\ViewAction, которые мы можем использовать. Они перечислены в следующей таблице:

Имя параметра|Описание
-------------|----------------------
defaultView  |Имя представления по умолчанию, если параметр YII\web\ViewAction::$viewParam GET не указан пользователем. По умолчанию 'index'. Это должно быть в формате path/to/view, аналогичном тому, который указан в параметре GET.
layout       |Имя макета, применяемого к запрошенному представлению. Это будет присвоено yii\base\Controller::$layout перед отображением представления. Значения по умолчанию null, если  будут использованы. Если false, макет не будет применен.
viewParam    |Имя параметра GET, содержащего запрошенное имя представления.
viewPrefix   |Строка с префиксом к указанному пользователем имени представления для формирования полного имени представления. Например, если пользователь запрашивает tutorial/chap1, соответствующее имя представления будет pages/tutorial/chap1, при условии, что префикс pages. Фактический вид файла определяется в yii\base\View::findViewFile().

Настройка правил URL
---
Действие viewAction позволяет минимизировать контроллер, но URL-адреса выглядят как http://yii-book.app/index.php?r=test/page&page=about. Чтобы сделать URL короткими и удобочитаемыми, добавьте правило URL в компонент urlManager:
```php
'<view:about>' => 'test/page'
```
Если компонент urlManager настроен правильно, вы получите следующее:
![](img/102_1.jpg)

Чтобы настроить компонент urlManager, см. рецепт в разделе Настройка правил URL.

Смотрите так же
---
Дополнительные сведения см. по следующим URL-адресам:
* <http://www.yiiframework.com/doc-2.0/yir-web-v'ewaction.html>
* <http://www.yiiframework.com/doc-2.0/guide-structure-views.html#rendering-static-pages>
* По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-views#rendering-static-pages> 
* Рецепт Конфигурирование URL




Использование flash-cообщений
===
Когда вы редактируете модель с помощью формы, удаляете модель или выполняете любую другую операцию, хорошо сообщить пользователям, прошла ли она хорошо или произошла ошибка. Как правило, после какого-то действия, такого как редактирование формы, произойдет перенаправление, и нам нужно отобразить сообщение на странице, на которую мы хотим перейти. Однако, как мы передаем его от текущей страницы к цели перенаправления и очищаем впоследствии? Флэш-сообщения помогут нам сделать это.

Подготовка
---
Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
1 Давайте создадим @app/controllers/TestController.php контроллер следующим образом:
```php
<?php
namespace app\controllers; use Yii;
use yii\web\Controller;
use yii\filters\AccessControl;
class TestController extends Controller {
    public function behaviors()
    {
        return [
            'access' => [
                'class' => AccessControl::className(),
                'rules' => [
                    [
                    'allow' => true,
                    'roles ' => ['@'],
                    'actions' => ['user']
                    ],
                    [
                    'allow' => true,
                    'roles' => ['?'],
                    'actions' => ['index', 'success', 'error']
                    ],
                ],
                'denyCallback' => function ($rule, $action) {
                    Yii::$app->session->setFlash('error', 'This section is only for registered users.');
                    $this->redirect(['index']);
                },
            ],
        ];
    }
    public function actionUser()
    {
        return $this->renderContent('user')
    }

    public function actionSuccess()
    {
        Yii::$app->session->setFlash('success', 'Everything went fine!'); 
        $this->redirect(['index']);
    }

    public function actionError()
    {
        Yii::$app->session->setFlash('error', 'Everything went wrong!'); 
        $this->redirect(['index']);
    }
    public function actionIndex()
    {
        return $this->render('index');
    }
}
```
2 Кроме того, создайте @app/views/common/alert. php посмотреть следующим образом:
```php
<?php
use yii\bootstrap\Alert;
?>
<?php if (Yii::$app->session->hasFlash('success')):?>
    <?= Alert::widget([
        'options' => ['class' => 'alert-success'],
        'body' => Yii::$app->session->getFlash('success'),]);
    ?>
<?php endif ?>
<?php if (Yii::$app->session->hasFlash('error')) :?>
    <?= Alert::widget([
        'options' => ['class' => 'alert-danger'],
        'body' => Yii::$app->session->getFlash('error'),
    ]);?>
<?php endif; ?>
```

3 Создайте @app/views/test/index.php файл представления  следующим образом:
```php
<?php
/* @var $this yii\web\View */
?>
<?= $this->render('//common/alert') ?>
<h2>Guest page</h2>
<p>There's a content of guest page</p>
```

4 Создайте @app/views/test/user.php  файла представления следующим образом:
```php
<?php
/* @var $this yii\web\View */
?>
<?= $this->render('//common/alert') ?>
<h2>User page</h2>
<p>There's a content of user page</p>
```

5 Теперь, если вы перейдете на <http://yii-book.app/index.php?r=test/success>, вы будете перенаправлены на <http://yii-book.app/index.php?r=test/index> и сообщение об успешном выполнении будет отображаться как
![](img/105_1.jpg)

6 Более того, если вы заходите на http://yii-book.app/index. php?r=test/error, вы будете перенаправлены на ту же страницу, но с сообщением об ошибке. Обновление страницы индекса скроет сообщение
![](img/105_2.jpg)

7 Затем попробуйте запустить <http://yii-book.app/index.php?r=test/user>. Вы будете перенаправлены на <http://yii-book.app/index.php?r=test/index> и сообщение об ошибке, выполненные в функции denyCallback:

Как это работает…
---
Мы установили флэш-сообщение с Yii::$app->session->("sucess", " Все прошло хорошо!'). Внутренне, он сохраняет сообщение в состояние сеанса, поэтому на самом низком уровне наше сообщение хранится в $_SESSION до тех пор, пока Yii::$app->session->getFlash( 'success') не будет вызван и ключ $_SESSION не будет удален.
Флэш-сообщение будет автоматически удалено после получения запроса.

Есть еще.
---
**Метод getAllFlashes()**
Иногда нужно справиться со всеми вспышками. Вы можете сделать это простым способом, следующим образом:
```php
$flashes = Yii::$app->session->getAllFlashes();
<?php foreach ($flashes as $key => $message): ?>
    <?= Alert::widget([
        'options' => ['class' => 'alert-info'],
        'body' => $message,
        ]);
    ?>
<?php endforeach; ?>
```
**Метод removeAllFlashes()**
Когда вам нужно очистить все ваши вспышки, используйте следующее:
```php
Yii::$app->session->removeAllFlashes();
```
**Метод removeFlash()**
Если необходимо удалить метод flash с указанным ключом, используйте следующее:
```php
Yii::$app->session->removeFlash('success');
```
В этом примере мы добавили очень полезную функцию обратного вызова, которая устанавливает сообщение об ошибке и выполняет перенаправление на страницу test/index.

Смотрите так же
---
Для получения дополнительной информации обратитесь к:
* <http://www.viiframework.com/doc-2.0/vii-web-session.html>
* <http://www.yiiframework.com/doc-2.0/yii-bootstrap-alert.html>




Использование контекста контроллера в представлении
===
Виды Yii довольно мощные и имеют множество функций. Одним из них является то, что вы можете использовать контекст контроллера в представлении. Итак, давайте попробуем.

Подготовка
---
Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
     по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>
     
Как это сделать...
---

1 Создайте controllers/ViewController.php следующим образом:
```php
<?php
namespace app\controllers;
use yii\web\Controller;
class ViewController extends Controller {
	public $pageTitle;
	public function actionIndex()
		{
			$this->pageTitle = 'Controller context test'; return $this->render('index');
		}
	public function hello()
		{
			if (!empty($_GET['name'])) {
			echo 'Hello, '	. $_GET['name'] . '!';
		}
	}
}
```

2 Сейчас мы будем создавать views/view.php. Он показывает, что мы можем сделать:
```php
<h1><?= $this->context->pageTitle ?></h1>
<p>Hello call. <?php $this->context->hello() ?></p>
```

3 Для того чтобы испытать его, вы можете следовать /index.php?r=view/index&name=Alex:
![](img/108_1.jpg)

Как это работает...
---
Мы используем $this в представлении для ссылки на текущий контроллер. При этом мы можем вызвать метод контроллера и доступ к его свойствам. Наиболее полезным свойством является pageTitle, который ссылается на Заголовок текущей страницы. Существует множество встроенных методов, которые чрезвычайно полезны в представлениях, таких как renderPartials и widget.

Есть еще.
---
<http://www.yiiframework.com/doc-2.0/guide-structure-views.html#accessing-data-in-views> 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-views#accessing-data-in-views> 
URL содержит документацию API для controller, где вы можете получить хороший список методов, которые вы можете использовать в своем представлении





Повторное использование представлений с частями
===
Yii поддерживает partials, поэтому, если у вас есть блок без особой логики, который вы хотите 
повторно использовать или хотите реализовать шаблоны электронной почты, partials являются 
правильным способом, чтобы сделать это.
Представьте, что у нас есть две учетные записи Twitter, одна для нашего блога, а другая для 
деятельности компании, и наша цель-вывод графиков Twitter на указанных страницах.

Подготовка
---
1	Создайте новое приложение с помощью composer, как описано в официальном 
руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

 2	Создайте виджет Twitter на https://twitter.com/settings/widgets/ для пользователей php_net и 
yii framework и найдите значение data-widget-id для каждого созданного виджета.

Как это сделать...
---

1	Создайте контроллер @app/controllers/BlogController.php, следующим образом:
```php
<?php
namespace app\controllers;
use yii\web\Controller;
class BlogController extends Controller 
{
	public function actionIndex()
	{
	$posts = [
				[
				'title' => 'First post',
				'content' => 'There\'s an example of reusing views with 
				partials.',
				],
				[
				'title' => 'Second post',
				'content' => 'We use twitter widget.'
				],
			];
	return $this->render('index', ['posts' => $posts]);
	}
}
```

2	Создайте файл представления с именем @app/views/common/twitter.php и вставить код из Twitter. Вы получите что-то вроде следующего:
```php
<?php
/* @var $this \yii\web\View */
/* @var $widget_id integer */
/* @var $screen_name string */
?>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s) 
[0],p=/Ahttp:/.test(d.location)?'http':'https';if(!d.getElementById(id))
{js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js
";fjs.p 
arentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>
<?php if ($widget_id && $screen_name): ?>
<a class="twitter-timeline"
data-widget-id="<?= $widget_id?>" 
href="https://twitter.com/<?= 
$screen_name?>" 
height="300">
Tweets by @<?= $screen_name?>
</a>
<?php endif;?>
```

3	Создайте файл представления @app/views/blog/index. php   следующим образом:
```php
<?php
/* @var $category string */
/* @var $posts array */
/* @var $this \yii\web\View */
?>
<div class="row">
	<div class="col-xs-7">
		<h1>Posts</h1>
		<hr>
		<?php foreach ($posts as $post): ?>
			<h3><?= $post['title']?></h3>
			<p><?= $post['content']?></p>
		<?php endforeach;?>
	</div>
	<div class="col-xs-5">
		<?= $this->render('//common/twitter', [
			'widget_id' = > '620531418213576704',
			'screen_name' => 'php_net',
		]);?>
	</div>
</div>
```

4	Замените @app/views/site/about.php  следующим содержанием:
```php
<?php
use yii\helpers\Html;
/* @var $this yii\web\View */
$this->title = 'About';
?>
<div class="col-xs-7">
	<h1><?= Html::encode($this->title) ?></h1>
	<p>This is the About page. You may modify this page.</p>
</div>
<div class="col-xs-5">
	<?= $this->render('//common/twitter', [
		'widget_id' => '620526086343012352',
		'screen_name' => 'yiiframework'
	]);?>
</div>
```

5	Запустите  index.php?r=blog/index:
![](img/111_1.jpg)

6 Запустите index.php?r=site/about:
![](img/111_2.jpg)

Как это работает...
---
В текущем примере два представления отображают @app/views/common/twitter.php с дополнительными параметрами для формирования виджетов Twitter внутри себя. Обратите внимание, что представления 
можно отображать в контроллерах, виджетах или в любом другом месте, вызывая методы визуализации 
представления. 
В каждом файле представления мы можем получить доступ к двум экземплярам класса View с помощью $this, поэтому любой файл представления можно отобразить в другом представлении, вызвав метод render 

Есть еще...
---
Для получения дополнительной информации обратитесь к
<http://www.yiiframework.com/doc-2.0/guidestructureviews.html#rendering-views>.
По русски  http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-views#rendering-in-views






Использование блоков
===
Одной из функций Yii, которую вы можете использовать в своих представлениях, являются блоки. Основная идея заключается в том, что вы можете записать некоторые Выходные данные, а затем использовать их позже в представлении. Хорошим примером может быть определение дополнительных областей содержимого для макета и их заполнение в другом месте.
В предыдущей версии, Yii 1.1, блоки назывались клипами.

Подготовка
---
Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---

1 В нашем примере нам нужно определить две области в макете-beforeContent и footer.

2 Откройте @app/views/layouts/main.php и вставьте следующий код строки просто до выхода содержания:
```php
<?php if(!empty($this->blocks['beforeContent'])) 
	echo $this->blocks['beforeContent']; 
?>
```

3 Затем замените код футера на следующий код:
```php
<footer class="footer">
	<div class="container">
		<?php if (!empty($this->blocks['footer'])): 
			echo $this->blocks['footer'] ?>
		<?php else: ?>
			<p class="pull-left">&copy; My Company <?= date('Y') ?></p>
			<p class="pull-right"><?= Yii::powered() ?></p>
		<?php endif; ?>
	</div>
</footer>
```
4 Вот и все! Затем добавьте новое действие в controllers/SiteController.php, именованные блоки:
```php
public function actionBlocks()
{
	return $this->render('blocks');
}
```

5 Теперь создайте файл представления, views/site/blocks.php, со следующим содержанием:
```php
<?php
use \yii\Helpers\Html;
/* @var $this \yii\web\View */
?>
<?php $this->beginBlock('beforeContent');
echo Html::tag('pre', 'Your IP is '	. Yii::$app->request->userIP);
$this->endBlock(); ?>
<?php $this->beginBlock('footer');
echo Html::tag('h3', 'My custom footer block');
$this->endBlock(); ?>
<h1>Blocks usage example</h1>
```

6 Теперь, когда вы открываете /index. php?r=site/blocks , вы должны узнать свой IP до содержимого страницы и заметки в футере
![](img/114_1.jpg)

Как это работает...
---

Мы помечаем регионы кодом, который просто проверяет наличие определенного блока,и если блок существует, код выводит его. Затем мы записываем содержимое блоков, определенных с помощью специальных методов контроллера beginBlock и endBlock.
Из контроллера, вы можете легко достигнуть переменных нашего блока через 
```php
$this->view->blocks[' blockID' ].
```

Есть еще.
---
* Рецепт Использования контекста контроллера в представлении
* <http://www.yiiframework.com/doc-2.0/guide-structure-views.html#using-blocks>
* <По русски http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-views#using-blocks>




Использование декоратора
===
В Yii мы можем вложить Контент в декоратора. Общее использование декораторов - layout. При рендеринге вида с помощью метода рендеринга контроллера Yii автоматически украшает его основным макетом. Давайте создадим простой декоратор, который будет правильно форматировать цитаты.

Подготовка
---
Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---

1 Во-первых, мы создадим файл декоратора, @app/views/decorators/quote.РНР:
```php
<div class="quote">
	<h2>&ldquo;<?= $content?>&rdquo;, <?= $author?></h2>
</div>
```

2 Теперь замените содержимое @app/views/site/index.php со следующим кодом:
```php
<?php
use yii\widgets\ContentDecorator;
/* @var */
?>
<?php ContentDecorator::begin([
	'viewFile' => '@app/views/decorators/quote.php',
	'view' => $this,
	'params' => ['author' => 'S. Freud']
]);?>
Time spent with cats is never wasted.
<?php ContentDecorator::end();?>
```

3 Теперь ваша Домашняя страница должна выглядеть следующим образом:
![](img/115_1.jpg)

Как это работает…
---
Декораторы довольно просты. Все между contentDecorator::begin() и contentDecorator::end() оказывается в переменной $content и передается в шаблон "декоратор". Затем шаблон декоратора визуализируется и вставляется в то место, где был вызван ContentDecorator::end.
Мы можем передать дополнительные переменные в шаблон декоратора, используя второй параметр ContentDecorator::begin (), такой как тот, который мы сделали для автора.
Обратите внимание, что мы использовали @app/views/decorators/quote.php как путь представления.

Смотрите так же
---
* < http://www.yiiframework.com/doc-2.0/yii-widgets-contentdecorator.html> URL предоставит больше информации о декораторах:
* Рецепт  Использование контекста контроллера в представлении





Определение нескольких макетов
===
Большинство приложений используют один макет для всех своих представлений. Однако бывают ситуации, когда требуется несколько макетов. Например, приложение может использовать разные макеты на разных страницах: два дополнительных столбца для блогов, один дополнительный столбец для статей и никаких дополнительных столбцов для портфолио.

Подготовка
---
Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>
 
Как это сделать...
---
1 Создайте два макета в views/layouts: блог и статьи. Блог будет содержать следующий код:
```php
<?php $this->beginContent('//layouts/main')?>
<div>
	<?= $content ?>
</div>
<div class="sidebar tags">
	<ul>
		<li><a href="#php">PHP</a></li>
		<li><a href="#yii">Yii</a></li>
	</ul>
</div>
<div class="sidebar links">
	<ul>
		<li><a href="http://yiiframework.com/">Yiiframework</a></li>
		<li><a href="http://php.net/">PHP</a></li>
	</ul>
</div>
<?php $this->endContent()?>
```

2 Статьи будут содержать следующий код:
```php
<?php
/* @var $this yii\web\View */
?>
<?php $this->beginContent('@app/views/layouts/main.php'); ?>
<div class="container">
	<div class="col-xs-8">
		<?= $content ?>
	</div>
	<div class="col-xs-4">
		<h4>Table of contents</h4>
		<ol>
			<li><a href="#intro">Introduction</a></li>
			<li><a href="#quick-start">Quick start</a></li>
			<li>..</li>
		</ol>
	</div>
</div>
<?php $this->endContent() ?>
```

3 Создайте файл представления, views/site/content.php, следующим образом:
```php
<h1>Title</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
```

4 Создайте три контроллера с именем BlogController, ArticleController и PortfolioController, с действиями индекса во всех трех. Содержание controllers/BlogController.php выглядит следующим образом:
```php
<?php
namespace app\controllers;
use yii\web\Controller;
class BlogController extends Controller {
	public $layout = 'blog';
	public function actionIndex()
	{
		return $this->render('//site/content');
	}
}
```

5 Содержание controllers/ArticleController. php выглядит следующим образом:
```php
<?php
namespace app\controllers; 
use yii\web\Controller;
class ArticleController extends Controller {
	public $layout = 'articles';
	public function actionIndex()
	{
		return $this->render('//site/content');
	}
}
```

6 Содержание controllers/PortfolioController.php выглядит следующим образом:
```
<?php
namespace app\controllers; use yii\web\Controller;
class PortfolioController extends Controller {
	public function actionIndex()
	{
		return $this->render('//site/content');
	}
}
```

7 Теперь попробуйте запустить **http://yii-book.app/?r=blog/index:**
![](img/119_1.jpg)


8 Затем попробуйте запустить http://yii-book.app/?r=article/index:
![](img/119_2.jpg)

9 Наконец, попробуйте запустить http: //yii-book.app/?r=portfolio/index:
![](img/119_3.jpg)

Как это работает...
---
Мы определили два дополнительных макета для блога и статей. Поскольку мы не хотим копировать и вставлять общие части из основного макета, мы применяем дополнительные декораторы макета, используя $this->beginContent и $this-> endContent.

Смотрите так же
---
* <http://www.yiiframework.com/doc-2.0/guide-structure-views.html#nested-layouts>  URL предоставляет дополнительные сведения о макетах.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-views#nested-layouts> 
* Рецепт Использования контекста контроллера в представлении
* Рецепт Использование декоратора






Разбивка на страницы и сортировка данных
===
В последних выпусках Yii фокус был перенесен с использования Active Record напрямую на таблицы, списки и поставщики данных. Тем не менее, иногда лучше использовать Active Record напрямую. Давайте посмотрим, как перечислить разбитые на страницы записи AR с возможностью их сортировки. В этом разделе мы хотели бы создать список фильмов и отсортировать их по некоторым атрибутам из базы данных. В нашем примере мы отсортируем наши фильмы по названию фильма и атрибутам арендной ставки.

Подготовка
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Скачать база данных "sakila" <http://dev.mysql.com/doc/index-other.html>.

3 Выполните загруженные SQLs; сначала схема, затем данные.

4 Настройте подключение к БД в config/main.php для использования базы данных Sakila.

5 Используйте Gii для создания модели Film.

Как это сделать...
---

1 Во-первых, необходимо создать @app/controllers/FilmController.php:
```php
<?php
namespace app\controllers;
use app\models\Film; 
use yii\web\Controller; 
use yii\data\Pagination; 
use yii\data\Sort;
class FilmController extends Controller {
    public function actionIndex()
    {
        $query = Film::find();
        $countQuery = clone $query;
        $pages = new Pagination(['totalCount' => $countQuery->count()]); 
            $pages->pageSize = 5;
            $sort = new Sort([
                'attributes' => [
                'title',
                'rental_rate'
            ]
        ]);
        $models = $query->offset($pages->offset)
            ->limit($pages->limit)
            ->orderBy($sort->orders)
            ->all();
        return $this->render('index', [
            'models' => $models,
            'sort' => $sort,
            'pages' => $pages
            ]);
    }
}
```

2 Теперь давайте реализуем @app/views/film/index.php, следующим образом:
```php
<?php
use yii\widgets\LinkPager;
/**
* @var \app\models\Film $models
* @var \yii\web\View $this
* @var \yii\data\Pagination $pages
* @var yii\data\Sort $sort */
?>
<h1>Films List</h1>
<p><?=$sort ->link('title')?> | <?=$sort->link('rental_rate')?></p>
<?php foreach ($models as $model): ?>
    <div class="list-group">
        <h4 class="list-group-item-heading"> <?=$model->title ?>
            <label class="label label-default"> <?=$model->rental_rate ?></label>
        </h4>
        <p class="list-group-item-text"><?=$model->description ?></p>
    </div>
<?php endforeach ?>
<?=LinkPager::widget([
    'pagination' => $pages ]); ?>
```
    
3 Попробуйте загрузить http://yii-book.app/index.php?r=film/index. Вы должны получить рабочую пагинацию и ссылки, которые позволяют сортировать список по названию фильма или по арендной ставке:
![](img/123_1.jpg)

Как это работает...
---
Во-первых, мы получили общее количество моделей и инициализировали новый экземпляр компонента разбиения на страницы, передав переменную totalcount нашему экземпляру разбиения на страницы. 
Затем мы использовали поле $pages->pageSize, чтобы настроить Размер страницы для нашей пагинации. 
После этого мы создали экземпляр сортировщика для модели, указав атрибуты модели, которые мы хотели отсортировать, и применив условия заказа К запросу, вызвав orderBy и передав $ sort->orders в качестве параметра. 
Затем мы вызвали all (), чтобы получить записи из БД.
На этом этапе у нас есть список моделей, страницы и данные, используемые для пейджера ссылок, и сортировщик, который мы используем для создания ссылок сортировки.
В представлении мы используем собранные данные. Во-первых, мы генерируем ссылки с помощью метода Sort::link. Затем мы перечислим модели. Наконец, используя LinkPager виджеты, то вывести постраничную навигацию.

Смотрите так же
---
Дополнительные сведения о разбиении на страницы и сортировке см. по следующим ссылкам:
*<http://www.yiiframework.com/doc-2.0/yii-data-pagination.html>
*<http://www.yiiframework.com/doc-2.0/yii-data-sort.html>
* <http://www.yiiframework.com/doc-2.0/guide-output-pagination.html> 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/output-pagination>
* <http://www.yiiframework.com/doc-2.0/guide-output-sorting.html>
 <по русски http://yiiframework.domain-na.me/doc/guide/2.0/ru/output-sorting>






Ãëàâà 3. ActiveRecord, ìîäåëè è áàçû äàííûõ
=====
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:
* Ïîëó÷åíèå äàííûõ èç áàçû äàííûõ
* Îïðåäåëåíèå è èñïîëüçîâàíèå íåñêîëüêèõ ñîåäèíåíèé ÁÄ
* Íàñòðîéêà êëàññà ActiveQuery
* Îáðàáîòêà ïîëåé ìîäåëè ñ ïîìîùüþ ñîáûòèéíûõ ìåòîäîâ AR
* Àâòîìàòèçàöèÿ âðåìåííûõ ìåòîê
* Àâòîìàòè÷åñêàÿ íàñòðîéêà àâòîðà
* Íàñòðîéêà slug àâòîìàòè÷åñêè
* Òðàíçàêöèè
* Ðåïëèêàöèÿ è ðàçäåëåíèå ÷òåíèÿ è çàïèñè
* Ðåàëèçàöèÿ íàñëåäîâàíèÿ îäíîé òàáëèöû

Ââåäåíèå
===
Â ýòîé ãëàâå âû óçíàåòå, êàê ýôôåêòèâíî ðàáîòàòü ñ áàçîé äàííûõ, êîãäà èñïîëüçîâàòü ìîäåëè, à êîãäà íåò, êàê ðàáîòàòü ñ íåñêîëüêèìè áàçàìè äàííûõ, êàê àâòîìàòè÷åñêè ïðåäâàðèòåëüíî îáðàáàòûâàòü ïîëÿ àêòèâíûõ çàïèñåé, êàê èñïîëüçîâàòü òðàíçàêöèè è ò. ä



Получение данных из базы данных
===
Сегодня большинство приложений используют базы данных. Будь то небольшой сайт или социальная сеть, по крайней мере, некоторые части питаются от баз данных.
Yii предлагает три способа работы с базами данных. Они заключаются в следующем:
* Active Record
* Query Builder
* SQL использующий DAO

Мы будем использовать все эти методы, чтобы получить данные из таблиц film, film_actor и actor и показать их в списке. Кроме того, мы сравним время выполнения и использование памяти, чтобы определить, в каких случаях мы должны использовать эти методы.

Подготовка
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Скачать база данных "sakila" <http://dev.mysql.com/doc/index-other.html>.

3 Выполните загруженные SQLs; сначала схема, затем данные.

4 Настройте подключение к БД в config/main.php для использования базы данных Sakila.

5 Используйте Gii для создания модели Film.

Как это сделать...
---
1 Cоздайте app/controllers/DbController.php как здесь описано:
```php
<?php

namespace app\controllers;

use app\models\Actor;
use Yii;
use yii\db\Query;
use yii\helpers\ArrayHelper;
use yii\helpers\Html;
use yii\web\Controller;

/**
 * Class DbController.
 */
class DbController extends Controller
{
    /**
     * Example of Active Record usage.
     *
     * @return string
     */
    public function actionAr()
    {
        $records = Actor::find()
                        ->joinWith('films')
                        ->orderBy('actor.first_name, actor.last_name, film.title')
                        ->all();

        return $this->renderRecords($records);
    }

    /**
     * Example of Query class usage.
     *
     * @return string
     */
    public function actionQuery()
    {
        $rows = (new Query())
            ->from('actor')
            ->innerJoin('film_actor', 'actor.actor_id=film_actor.actor_id')
            ->leftJoin('film', 'film.film_id=film_actor.film_id')
            ->orderBy('actor.first_name, actor.last_name, actor.actor_id, film.title')
            ->all();
        return $this->renderRows($rows);
    }

    /**
     * Example of SQL execution usage.
     *
     * @return string
     */
    public function actionSql()
    {
        $sql = 'SELECT *
           FROM actor a
             JOIN film_actor fa ON fa.actor_id = a.actor_id
             JOIN film f ON fa.film_id = f.film_id
             ORDER BY a.first_name, a.last_name, a.actor_id, f.title';

        $rows = Yii::$app->db->createCommand($sql)->queryAll();

        return $this->renderRows($rows);
    }

    /**
     * Render records for Active Record array.
     *
     * @param array $records
     *
     * @return string
     */
    protected function renderRecords(array $records = [])
    {
        if (!$records) {
            return $this->renderContent('Actor list is empty.');
        }

        $items = [];

        foreach ($records as $record) {
            $actorFilms = $record->films
                ? Html::ol(ArrayHelper::getColumn($record->films, 'title'))
                : null;
            $actorName = $record->first_name . ' ' . $record->last_name;
            $items[] = $actorName . $actorFilms;
        }

        return $this->renderContent(Html::ol($items, [
            'encode' => false,
        ]));
    }

    /**
     * Render rows for result of query.
     *
     * @param array $rows
     *
     * @return string
     */
    protected function renderRows(array $rows = [])
    {
        if (!$rows) {
            return $this->renderContent('Actor list is empty.');
        }

        $items = [];
        $films = [];

        $actorId = null;
        $actorName = null;
        $actorFilms = null;

        $lastActorId = $rows[0]['actor_id'];

        foreach ($rows as $row) {
            $actorId = $row['actor_id'];
            $films[] = $row['title'];

            if ($actorId != $lastActorId) {
                $actorName = $row['first_name'] . ' ' . $row['last_name'];
                $actorFilms = $films ? Html::ol($films) : null;

                $items[] = $actorName.$actorFilms;
                $films = [];
                $lastActorId = $actorId;
            }
        }

        if ($actorId == $lastActorId) {
            $actorFilms = $films ? Html::ol($films) : null;
            $items[] = $actorName . $actorFilms;
        }

        return $this->renderContent(Html::ol($items, [
            'encode' => false,
        ]));
    }
}
```
2 Здесь, у нас есть три действия, соответствующие трем различным методам получения данных из базы данных.

3 После выполнения предыдущих действий db/ar, db/query и db/sql вы должны получить дерево, показывающее 200 актеров и 1000 фильмов, в которых они действовали, как показано на следующем снимке экрана:

![](img/128_1.jpg)

4 Внизу есть статистика, которая дает информацию об использовании памяти и времени выполнения. Абсолютные числа могут отличаться при выполнении этого кода, но разница между используемыми методами должна быть примерно одинаковой:

Метод            |Использование памяти (megabytes)|Время выполнения (seconds)
-----------------|------------------------------------------------|---------------------------
Active Record|21.4|2.398
Query Builder|28.3|0.477
SQL (DAO)    |27.6|0.481


Как это работает...
---
Метод actionAr получает экземпляры модели с использованием подхода Active Record.
Мы начинаем с модели Actor, сгенерированной с Gii, чтобы получить всех актеров, и указываем joinwith = > 'films', чтобы получить соответствующие фильмы, используя один запрос или нетерпеливую загрузку через отношение, которое gii строит для нас из внешних ключей таблицы innoDB. Затем мы просто переберем всех актеров и каждого актера, каждый фильм. Затем для каждого элемента, мы печатаем его имя.
Функция actionQuery использует Построитель запросов. Сначала мы создадим запрос для текущего соединения с базой данных с помощью \yii\db\Query. Затем мы добавляем части запросов по одному from, joininner, и leftJoin. Эти методы автоматически экранируют значения, таблицы и имена полей. Функция all () функции \yii\db\Query возвращает массив необработанных строк базы данных. Каждая строка также является массивом, индексированным с именами полей результатов. Мы передаем результат renderRows, который выводит его.
С actionSql мы делаем то же самое, за исключением того, что мы передаем SQL напрямую вместо добавления его частей по одному. Стоит отметить, что мы должны экранировать значения параметров вручную, используя Yii::app()->db->quotevalue, прежде чем использовать их в строке запроса:
Метод renderRows отображает Построитель запросов.
Метод renderRecords отображает активные записи.

Method |Active Record |Query Builder |SQL (DAO)
-------|--------------|--------------|---------
|Синтаксис |Это сделает SQL для вас. Gii будет генерировать модели и отношения для вас. Работает с моделями, полностью ОО-стиль, и очень чистый API. В результате создается массив правильно вложенных моделей. |Чистый API, подходит для построения запроса на лету. Создает необработанные массивы данных в результате. |Хорошо для сложного SQL. Ручные значения и цитирование ключевых слов. Не очень подходит для построения запроса на лету. Создает необработанные массивы данных в результате.
|Производительность |Более высокое использование памяти и время выполнения по сравнению с SQL и Построителем запросов. |Okay. |Okay.
|Дополнительные особенности |Кавычки значения и имена автоматически. Поведения. До / после крючков. Утверждение. Прототипирование выбирает. |Кавычки значения и имена автоматически.|None.
|Лучшее для |Обновление, удаление и создание действий для отдельных моделей (модель дает огромное преимущество при работе с формами).|Работа с большим объемом данных и построение запросов на лету. |Сложные запросы, которые вы хотите завершить с помощью чистого SQL и иметь максимальную возможную производительность.

Есть еще...
---
Чтобы узнать больше о работе с базами данных в Yii, обратитесь к следующим ресурсам:
* <http://www.yiiframework.eom/doc-2.0/guide-db-dao.html>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-dao>
* <http://www.yiiframework.com/doc-2.0/guide-db-query-builder.html>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-query-builder>
* <http://www.yiiframework.com/doc-2.0/guide-db-active-rerord.html>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-active-record>





Определение и использование нескольких подключений к БД
===
Несколько подключений к базам данных не используются очень часто для новых автономных веб-приложений. Однако при создании дополнительного приложения для существующей системы, скорее всего, потребуется другое подключение к базе данных.
Из этого рецепта вы узнаете, как определить несколько подключений к БД и использовать их с DAO, Построителем запросов и моделями активных записей.

Подготовка
---

1 Создайте новое приложение с помощью composer, как описано в официальном руководстве  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Создайте две базы данных MySQL с именами dbi и db2.

3 Создайте таблицу с именем post в dbi следующим образом:
```php
DROP TABLE IF EXISTS 'post';
CREATE TABLE IF NOT EXISTS 'post' (
'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
'title' VARCHAR(255) NOT NULL,
'text' TEXT NOT NULL,
PRIMARY KEY ('id')
);
```

4 Создайте таблицу с именем comment в db2 следующим образом:
```php
DROP TABLE IF EXISTS 'comment';
CREATE TABLE IF NOT EXISTS 'comment' (
'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
'text' TEXT NOT NULL,
'post_id' INT(10) UNSIGNED NOT NULL,
PRIMARY KEY ('id')
);
```

Как это сделать...
---

1 Начнем с настройки соединений с БД. Откройте config/main.php и определить первичное соединение, как описано в официальном руководстве:
```php
'db' => ['connectionString' =>'mysql:host=localhost;dbname=db1',
         'username' => 'root',
         'password' => '',
         'charset' => 'utf8',
        ],
```

2 Скопируйте его, переименуйте компонент db в db2 и измените строку подключения соответствующим образом. Кроме того, необходимо добавить имя класса следующим образом:
```php
'db2' => [
		'class'=>'yii\db\Connection ',
		'connectionString' => 'mysql:host=localhost;dbname=db2',
		'username' => 'root',
		'password' => '',
		'charset' => 'utf8',
		],
```

3 Вот и все. Теперь у вас есть два подключения к базе данных, и вы можете использовать их с DAO и Построителем запросов следующим образом:
```php
$rows1 = Yii::$app->db->createCommand($sql)->queryAll();
$rows2 = Yii::$app->db2->createCommand($sql)->queryAll();
```

4 Теперь, если нам нужно использовать Активные модели записей, нам сначала нужно создать модели Post и Comment с помощью Gii. Можно выбрать соответствующее соединение для каждой модели. Задайте ID соединения с базой данных db2  при создании модели Comments, как показано на следующем снимке экрана:
![](img/132_1.jpg)

5 Теперь Вы можете использовать модель Comment как обычно и создавать controllers/ DbController.php, следующим образом:
```php
<?php

namespace app\controllers;

use app\models\Post;
use app\models\Comment;
use Yii;
use yii\helpers\ArrayHelper;
use yii\helpers\Html;
use yii\web\Controller;

/**
 * Class DbController
 * @package app\controllers
 */
class DbController extends Controller
{
    public function actionIndex()
    {
        $post        = new Post();
        $post->title = "Post #" . rand(1, 1000);
        $post->text  = "text";
        $post->save();

        $posts = Post::find()->all();

        echo Html::tag('h1', 'Posts');
        echo Html::ul(ArrayHelper::getColumn($posts, 'title'));

        $comment         = new Comment();
        $comment->post_id = $post->id;
        $comment->text   = "comment #" . rand(1, 1000);
        $comment->save();

        $comments = Comment::find()->all();

        echo Html::tag('h1', 'Comments');
        echo Html::ul(ArrayHelper::getColumn($comments, 'text'));
    }
}
```

5 Запустите db/index несколько раз, и вы увидите записи, добавленные в обе базы данных, как показано на следующем снимке экрана:

![](img/133_1.jpg)

Как это работает...
---
В Yii можно добавлять и настраивать собственные компоненты с помощью файла конфигурации. Для нестандартных компонентов, таких как db2, необходимо указать класс компонента. Аналогичным образом можно добавить db3, db4 или любой другой компонент, например facebookApi. Остальные пары ключ/значение массива назначаются открытым свойствам компонента соответственно.

Есть еще.
---
В зависимости от используемой РСУБД, есть дополнительные вещи, которые мы можем сделать, чтобы упростить использование нескольких баз данных.

**Перекрестные отношения между базами**

Если Вы используете MySQL, можно создать отношения между базами данных для ваших моделей. Чтобы сделать это, вы должны вставить префикс  с именем базы данных в имя таблицы модели Comment, следующим образом:
```php
class Comment extends\yii\db\ActiveRecord {
	//...
	public function tableName()
	{
		return 'db2.comment';
	}
	//...
}
```
Теперь, если связь комментариев определена  модели Post  в связывающем методе , можно использовать следующий код:
```
$posts = Post::find()->joinWith('comments')->all();
```

Смотрите так же
---

Для получения дополнительной информации обратитесь к   <http://www.yiiframework.com/doc-2.0/guide-db-dao.html#creating-db- connections>. По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-dao> 




Настройка класса ActiveQuery
===
По умолчанию все активные запросы записей поддерживаются yii\db\ActiveQuery. Использование настраиваемого запроса класс в активном классе записей следует переопределить метод yii\db\ActiveRecord::find() и возврат экземпляра настраиваемого класса запросов.

Подготовка
---

1 Создайте новое приложение с помощью composer, как описано в официальном руководстве  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Настройте подключение к базе данных и создайте таблицу с именем post, как показано ниже:
```php
DROP TABLE IF EXISTS 'post';
CREATE TABLE IF NOT EXISTS 'post' (
'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
'lang' VARCHAR(5) NOT NULL DEFAULT 'en',
'title' VARCHAR(255) NOT NULL,
'text' TEXT NOT NULL,
PRIMARY KEY ('id')
);
INSERT INTO 'post'('id','lang','title','text')
VALUES (1,'en_us','Yii news','Text in English'),
(2,'de','Yii Nachrichten','Text in Deutsch');
```

3 Создания модели Post с помощью GII с возможностью генерировать ActiveQuery, что создает класс PostQuery.

Как это сделать...
---

1 Добавьте следующий метод в models/PostQuery.php:
```php
<?php
namespace app\models;
/**
* This is the ActiveQuery class for [[Post]].
*
* @see Post
*/
class PostQuery extends \yii\db\ActiveQuery
{
/**
* @param $lang
*
* @return $this
*/
    public function lang($lang)
    {
        return $this->where([ 'lang' => $lang ]);
    }
}
```

2 Вот и все. Теперь мы можем использовать нашу модель. Создавая controllers/DbController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\Post;
use yii\helpers\Html;
use yii\web\Controller;
/**
* Class DbController.
* @package app\controllers
*/
class DbController extends Controller
{
    public function actionIndex()
    {
        // Get posts written in default application language
        $posts = Post::find()->all();
        echo Html::tag('h1', 'Default language');
        foreach ($posts as $post) {
            echo Html::tag('h2', $post->title);
            echo $post->text;
        }
        // Get posts written in German
        $posts = Post::find()->lang('de')->all();
        echo Html::tag('h1', 'German');
        foreach ($posts as $post) {
            echo Html::tag('h2', $post->title);
            echo $post->text;
            }
    }
}
```

3 Теперь запустите db/index, и вы получите результат, аналогичный показанному ниже
screenshot:
![](img/138_1.jpg)

Как это работает...
---
Мы переписали метод find в модели Post и расширили класс ActiveQuery. Метод lang возвращает ActiveQuery с указанным значением языка. Для поддержки цепных вызовов lang возвращает экземпляр модели самостоятельно.

Есть еще.
---
Согласно руководству Yii2, в Yii 1.1 было понятие, называемое областью. Область больше не поддерживается напрямую в Yii 2.0, и для достижения той же цели следует использовать настраиваемые классы запросов и методы запросов.

Смотрите так же
---
Дополнительные сведения см. по следующим URL-адресам:
* <http://www.yiiframework.com/doc-2.0/guide-db-active-record.html#customizing-query-classes>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-active-record#customizing-query-classes> 
* <http://www.yiiframework.com/doc-2.0/guide-intro-upgrade-from-v1.html#active-record>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/intro-upgrade-from-v1#active-record> 





Обработка полей модели с помощью событийных методов AR
===
Активная реализация записи в Yii очень мощна и имеет много особенностей. Одной из таких функций являются событийные методы, которые можно использовать для предварительной обработки полей модели перед их помещением в базу данных или получением из базы данных, а также для удаления данных, связанных с моделью, и т. д.
В этом рецепте мы свяжем все URL-адреса в тексте сообщения и перечислим все существующие активные записи, похожие на события.

Подготовка
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Настройте подключение к базе данных и создайте таблицу с именем post, как показано ниже:
```php
DROP TABLE IF EXISTS 'post';
CREATE TABLE IF NOT EXISTS 'post' (
'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
'title' VARCHAR(255) NOT NULL,
'text' TEXT NOT NULL,
PRIMARY KEY ('id')
);
```

3 Создайте модель post с помощью Gii.

Как это сделать...
---
1 Добавьте следующий метод в models/Post.php:
```php
/**
* @param bool $insert
*
* @return bool
*/
    public function beforeSave($insert)
    {
        $this->text = preg_replace('~((?:https?|ftps?)://.*?)( |$)~iu',
            '<a href="\1">\1</a>\2', $this->text);
        return parent::beforeSave($insert);
    }
```

2 Вот и все. Теперь попробуйте сохранить сообщение, содержащее ссылку. Создание controllers/TestController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\Post; 
use yii\helpers\Html; 
use yii\helpers\VarDumper; 
use yii\web\Controller;
/**
* Class TestController.
* @package app\controllers
*/
class TestController extends Controller {
	public function actionIndex()
	{
		$post = new Post();
		$post->title = 'links test';
		$post->text = 'before http://www.yiiframework.com/ after'; $post->save();
		return $this->renderContent(Html::tag('pre', VarDumper::dumpAsString( $post->attributes)));
	}
}
```

3 Вот и все. Теперь запустите test/index. Вы должны получить следующий результат:
![](img/141_1.jpg)

Как это работает...
---
Метод beforeSave реализуется в классе ActiveRecord и выполняется непосредственно перед сохранением модели. Используя регулярное выражение, мы заменяем все, что выглядит как URL-адрес, ссылкой, которая использует этот URL-адрес, и вызываем родительскую реализацию, чтобы реальные события вызывались правильно. Чтобы предотвратить сохранение, вы можете вернуть false.

Смотрите так же
---
* Для получения дополнительной информации обратитесь к 
<http://www.yiiframework.com/doc-2.0/guide-db-active-record.html#active-record-life-cycles>
по русски http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-active-record#ar-life-cycles 
* Рецепт Работа с событиями в главе 1, Основы
* Рецепт Автоматизации временных меток
* Рецепт Настройка автора  автоматически
* Рецепт Настройка slug автоматически




Автоматизация временных меток
===
Например, у нас есть простое приложение. Как и в любом блоге, в нем есть посты, комментарии и так далее. Мы хотели бы, чтобы заполнить время во время создания/обновления событий для сообщений. Предположим, что наша модель записи называется моделью Blogpost.

Подготовка
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Настройте подключение к базе данных и создайте таблицу с именем blog_post следующим образом:
```php
DROP TABLE IF EXISTS 'blog_post';
CREATE TABLE IF NOT EXISTS 'blog_post' (
'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
'title' VARCHAR(255) NOT NULL,
'text' TEXT NOT NULL,
'created_date' INTEGER,
' modified_date'INTEGER,
PRIMARY KEY ('id')
);
```

3 Используйте Gii для создания модели для таблицы blog_post.

Как это сделать...
---
1 Добавьте следующий метод в models/BlogPost.php:
```php
/**
* @return array 
* */
public function behaviors()
{
	return [
		'timestamp'=> [
			'class' => 'yii\behaviors\TimestampBehavior', 'createdAtAttribute' => 'creation_date', 'updatedAtAttribute' => 'modified_date'
		]
	];
}
```

2 Создание controllers/TestController.php следующим образом:
```php
 <?php
 
 namespace app\controllers;
 
 use app\models\BlogPost;
 use yii\helpers\Html;
 use yii\helpers\VarDumper;
 use yii\web\Controller;
 
 /**
  * Class TestController.
  */
 class TestController extends Controller
 {
     public function actionIndex()
     {
         $blogPost = new BlogPost();
         $blogPost->title = 'Gotcha!';
         $blogPost->text = 'We need some laughter to ease the tension of holiday shopping.';
         $blogPost->save();
         return $this->renderContent(Html::tag('pre',VarDumper::dumpAsString($blogPost->attributes)));
     }
 }
 ```
 
3 Вот и все. Теперь запустите test/index. Вы должны получить следующий результат:
![](img/143_1.jpg)

Как это работает...
---
По умолчанию поведение Метки времени заполняет created_at (метка времени, указывающая на время создания модели) и updated_at (время обновления модели). Это стандартная практика, чтобы назвать эти поля, но если мы хотели бы внести изменения, мы можем указать поля, которые будут обновлены, и события модели.

Есть еще.
---
Например, наши поля называются creation_date и modified_date.
Давайте настроим нашу модель поведения в соответствии с этими полями. Кроме того, мы должны добавить код нашего поведения в нашу почтовую модель:
```php
<?php
namespace app\models; 
use Yii;
use yii\db\BaseActiveRecord;
class Post extends \yii\db\ActiveRecord {
	// . .
	public function behaviors()
		{
			return [
					[
						'class' => 'yii\behaviors\TimestampBehavior',
						'attributes' => [BaseActiveRecord::EVENT_BEFORE_INSERT => 'creation_date', BaseActiveRecord::EVENT_BEFORE_UPDATE => 'modified_date',]
					]
					];
		}
	// ..
}
```
В этом примере мы указали на атрибуты creation_date и modified_date перед созданием и обновлением нашей модели соответствующим образом с помощью специальных событий ActiveRecord: EVENT_BEFORE_INSERT и EVENT_BEFORE_UPDATE.

Кроме того...
---
Можно сохранить метку времени для пользовательских сценариев. Допустим, вы хотите обновить поле last_login, например, для определенного действия контроллера. В этом случае можно вызвать обновление метки времени для конкретного атрибута с помощью следующих:
```php
$model->touch('last_login');
```
Имейте в виду, что touch() нельзя использовать для новых моделей. В этом случае Вы получите InvalidCallException:
```php
$model = new Post();
$model->touch('creation_date ' );
```
Метод touch() вызывает сохранение модели внутри себя, поэтому вам не нужно сохранять модель после ее вызова.

Смотрите так же
---
Для получения дополнительной информации обратитесь к
<http://www.yiiframework.com/doc-2.0/guide-concept-behaviors.html#using-timestamp-behavior> 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/concept-behaviors#using-timestamp-behavior> 




Автоматическая настройка автора
===
Поведение Blameable позволяет автоматически обновлять одно или несколько полей авторов. Это в основном используется для заполнения данных в поля created_by и updated_by. Подобно поведению Метки времени, можно легко задать некоторые специальные параметры и важные события для этого поведения.
Вернемся к примеру из предыдущего раздела. У нас также есть посты нашего блога. Например, предположим, что наша модель блога называется Blogpost. Модель имеет author_id, поле, которое указывает на то, кто создал этот пост, и updater_id, поле, которое указывает на то, кто обновил. Мы хотели бы заполнить эти атрибуты автоматически во время событий создания / обновления модели. Сейчас вы можете узнать, как это сделать.

Подготовка
---

1 Создайте новое приложение с помощью composer, как описано в официальном руководстве  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Настройте подключение к базе данных и создайте таблицу с именем blog_post следующим образом:
```php
DROP TABLE IF EXISTS 'blog_post';
CREATE TABLE IF NOT EXISTS 'blog_post' (
'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
'author_id' INT(10) UNSIGNED DEFAULT NULL,
'updater_id' INT(10) UNSIGNED DEFAULT NULL,
'title' VARCHAR(255) NOT NULL,
'text' TEXT NOT NULL,
PRIMARY KEY ('id')
);
```

3 Используйте Gii для создания модели BlogPost для таблицы blost_post.

Как это сделать...
---

1 Добавьте следующий метод поведения в models/BlogPost.php: 
```php
<?php
namespace app\models; 
use Yii;
use yii\db\BaseActiveRecord;
/**
* This is the model class for table "blog_post".
*
* @property integer $id
* @property integer $author_id
* @property integer $updater_id
* @property string $title
* @property string $text */
class BlogPost extends \yii\db\ActiveRecord {
/**
* @return array 
*/
    public function behaviors()
    {
        return [
                [
                    'class' => 'yii\behaviors\BlameableBehavior',
                    'attributes' => [BaseActiveRecord::EVENT_BEFORE_INSERT => 'author_id', BaseActiveRecord::EVENT_BEFORE_UPDATE => 'updater_id']
                ]
                ];
    }
}
```

2 Создание controllers/TestController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\BlogPost; 
use app\models\User; 
use Yii;
use yii\helpers\Html; 
use yii\helpers\VarDumper; 
use yii\web\Controller;
/**
* Class TestController.
* @package app\controllers */
class TestController extends Controller {
	public function actionIndex()
	{
		$users = new User();
		$identity = $users->findIdentity(100);
		Yii::$app->user->setIdentity($identity);
		$blogPost = new BlogPost();
		$blogPost->title = 'Very pretty title';
		$blogPost->text = 'Success is not final, failure is not fatal...'; 
		$blogPost->save();
		return $this->renderContent(Html::tag('pre', VarDumper::dumpAsString( $blogPost->attributes)));
	}
}
```

3 Вот и все. Теперь запустите test/index. Вы получите следующий результат
![](img/147_1.jpg)

Как это работает...
---
По умолчанию поведение Blameable заполняет атрибуты created_by и updated_by, но мы внесем изменения и настроим наше поведение в соответствии с нашими собственными полями.
Мы также указали события и поля модели в модели, поэтому при создании модели будет заполнен author_id. Аналогично, при обновлении модели, мы заполним updater_id.
Что Blameable не вставить текущее значение идентификатора пользователя в created_by и поля updated_by в создать/обновить модель событий. Это супер-удобный способ делать вещи. Каждый раз, когда модель создается или обновляется, мы автоматически заполняем необходимые поля.
Это очень хорошо работает для небольших проектов, таких как для больших систем, где несколько пользователей являются администраторами, и вам нужно отслеживать, кто что делает. Вы также можете использовать это для реализации веб-интерфейса, например, если у вас была Таблица blog_comment и вы хотели использовать этот метод для отслеживания автора комментария. Кроме того, можно задать поля автора в контроллере, но поведение помогает избежать написания ненужного и дополнительного кода. Это очень эффективный и простой способ реализовать эту вещь.

Есть еще.
---
Иногда нам нужно заполнить author_id и updater_id идентификатором, отличным от идентификатора текущего пользователя. В таком случае, мы можем отделить наше поведение следующим образом:
```php
$model->detachBehavior('blammable ' );
```
Мы можем отделить любое поведение которое понравится в этом случае.

Смотрите так же
---
Для получения дополнительной информации обратитесь к <http://www.yiiframework.com/doc-2.0/yii-behaviors-blameablebehavior.html> 




Настройка slug автоматически
==
В интернете slug-это короткий текст, используемый в URL-адресе для идентификации и описания ресурса. Slug - это часть URL, которая идентифицирует страницу с помощью удобочитаемых ключевых слов. Sluggable поведение-это поведение модели Yii2, которое позволяет нам генерировать уникальные slug.
В этом разделе мы будем направлять вас через изменение маршрутов URL представления Yii по умолчанию для объектов модели, чтобы быть более удобным для пользователя и поисковой системы. Yii обеспечивает встроенную поддержку для этого через своё sluggable поведение.

Подготовка
---
1 Создайте новое приложение с помощью composer, как описано в официальном руководстве  <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Настройте подключение к базе данных и создайте таблицу с именем blog_post следующим образом:
```php
DROP TABLE IF EXISTS 'blog_post';
CREATE TABLE IF NOT EXISTS 'blog_post' (
	'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
	'title' VARCHAR(255) NOT NULL,
	'slug' VARCHAR(255) NOT NULL,
	'text' TEXT NOT NULL,
	PRIMARY KEY ('id')
);
```

3 Используйте Gii для создания модели для таблицы post.

Как это сделать...
---

1 Добавьте следующий метод поведения в models/BlogPost.php:
```php
<?php
namespace app\models; 
use Yii;
use yii\db\BaseActiveRecord;
class BlogPost extends \yii\db\ActiveRecord {
// ..
	public function behaviors()
	{
		return [
			[
			'class' => 'yii\behaviors\SluggableBehavior', 'attribute' => 'title',
			'slugAttribute' => 'slug',
			'immutable'=> false,
			'ensureUnique' => true
			]
		];
	}
// ..
}
```

2 Создайте controllers/TestController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\BlogPost;
use Yii;
use yii\helpers\Html;
use yii\helpers\VarDumper;
use yii\web\Controller;
/**
* Class TestController
* @package app\controllers 
* */
class TestController extends Controller {
	public function actionIndex()
	{
		$blogPostA	=	new BlogPost();
		$blogPostA->title = 'Super Quote title 1';
		$blogPostA->text = 'The price of success is hard work, dedication to the job at hand';
		$blogPostA->save();
		$blogPostB	=	new BlogPost();
		$blogPostB->title = 'Super Quote title 2';
		$blogPostB->text = 'Happiness lies in the joy of achievement...'; 
		$blogPostB->save();
		return $this->renderContent( '<pre>'. VarDumper::dumpAsString( $blogPostA->attributes ). VarDumper::dumpAsString($blogPostB->attributes ) . '</pre>');
	}
}
```

2 Результат будет следующим:
![](img/150_1.jpg)

Как это работает...
---
Yii предлагает некоторые приятные усовершенствования sluggableBehavior для полезных сценариев.
Например, как только поисковая система записывает пули, вы, вероятно, не хотите, чтобы URL-Адрес страницы изменение.
Неизменяемый атрибут говорит Yii сохранить пули же после его первого создания-даже если Заголовок будет обновляться.
Если пользователи вводят сообщения, которые перекрываются в содержимом, свойство ensureunique будет автоматически 
 добавьте уникальный суффикс к дубликатам. Это гарантирует, что каждое сообщение имеет уникальный URL-адрес, даже если сообщение идентично.
Если вы создадите еще один пост с точно таким же названием, вы увидите, что его slug увеличено до hot-update-for-ios-devices-2.
 
**Примечание: **Если возникает ошибка, связанная с неизменяемым свойством, может потребоваться запустить обновление Composer, чтобы получить последнюю версию Yii.

Есть еще.
---
1 Используйте Gii для создания CRUD для класса модели app\models\Post и класса контроллера app\controllers\BlogPostController.

2 Добавьте следующее действие в controllers/BlogPostController.php:
```php
/**
* @param $slug
*
* @return string
* @throws NotFoundHttpException
*/
	public function actionSlug($slug)
	{
		$model = BlogPost::findOne(['slug'=>$slug]);
		if ($model === null) {
			throw new NotFoundHttpException('The requested page does not exist.');
		}
		return $this->render('view', ['model' => $model,]);
	}

3 Так и есть. Если вы запустите blogpost/slug со значением slug как sluggablebehavior-test, вы получите следующий результат:
![](img/151_1.jpg)

4 Предлагается, чтобы предыдущий рецепт slug был успешно завершен с созданным экземпляром  модели Post.

5 Чтобы украсить URL, добавьте следующий компонент urlManager в config\web.РНР:
```php
//..
'urlManager' => [
	'enablePrettyUrl' => true,
	'rules' => [
		'blog-post' => 'blog-post/index',
		'blog-post/index' => 'blog-post/index',
		'blog-post/create' => 'blog-post/create',
		'blog-post/view/<id:\d+>' => 'blog-post/view',
		'blog-post/update/<id:\d+>' => 'blog-post/update',
		'blog-post/delete/<id:\d+>' => 'blog-post/delete',
		'blog-post/<slug>' => 'blog-post/slug',
		'defaultRoute' => '/site/index',
	],
]
//..
```

6 Важно, что 'blog-post/<slug>' => 'blog-post/slug' - это последнее в списке URL. 

7 Теперь, если вы идете на страницу, используя ваш slug URL, например, index.php/blog-post/super-quote-title-i/, вы получите результат, подобный тому, что в шаге 3:

![](img/152_1.jpg)

Смотрите так же
---

Для получения дополнительной информации обратитесь к:
<http://www.yiiframework.com/doc-2.0/vii-behaviors-sluggablebehavior.hrml>
<http://www.yiiframework.com/doc-2.0/guide-runtime-routing.html#url-rules> 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/runtime-routing#url-rules>




Транзакции 
===
В современных базах данных транзакции также делают некоторые другие вещи, такие как обеспечение того, что Вы не можете получить доступ к данным, которые другой человек написал наполовину. Однако основная идея все та же—сделки там, чтобы обеспечить, что бы ни случилось, данные работы будут в здравое состояние. Они гарантируют
что не будет ситуации, когда деньги снимаются с одного счета, но не зачисляются на другой.
Yii2 поддерживает мощный механизм транзакций с точками сохранения. Классический пример-перевод денег с одного банковского счета на другой. Для этого необходимо сначала вывести сумму с исходного счета, а затем внести ее на целевой счет. Операция должна быть выполнена в полном объеме. Если вы остановитесь на полпути, деньги будут потеряны, и это очень плохо. Например, у нас есть счет получателя и счет отправителя. Мы хотели бы перевести деньги от отправителя
получателю. Предположим, что у нас есть модель счета. Наша модель счета будет очень простой и будет содержать только поля id и баланс.

Подготовка...
---
1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation> 

2 Создайте миграцию, которая добавляет таблицу учетных записей, с помощью следующей команды:

**./yii migrate/create create_account_table**

3 Кроме того, обновите только что созданный перенос, используя следующий код:
```php
<?php
use yii\db\Schema;
use yii\db\Migration;
class m150620_062034_create_account_table extends Migration
{
    const TABLE_NAME = '{{%account}}';
    public function up()
    {
        $tableOptions = null;
        if ($this->db->driverName === 'mysql') {
            $tableOptions = 'CHARACTER SET utf8 COLLATE utf8_general_ci ENGINE=InnoDB';
        }
        $this->createTable(self::TABLE_NAME, [
            'id' => Schema::TYPE_PK,
            'balance' => ' NUMERIC(15,2) DEFAULT NULL',
        ], $tableOptions);
    }
    public function down()
    {
        $this->dropTable(self::TABLE_NAME);
    }
}
```

4 Затем установите миграцию с помощью следующей команды:

***./yii migrate up***

5 Используйте Gii для создания модели для таблицы Account.

6 Создайте миграцию, которая добавит несколько тестовых моделей счетов с балансом для нашей таблицы:

***./yii migrate/create add_account_records***

7 Кроме того, обновите только что созданный перенос, используя следующий код:
```php
<?php
use yii\db\Migration;
use app\models\Account;
class m150620_063252_add_account_records extends Migration
{
    public function up()
    {
        $accountFirst = new Account();
        $accountFirst->balance = 1110;
        $accountFirst->save();
        $accountSecond = new Account();
        $accountSecond->balance = 779;
        $accountSecond->save();
        $accountThird = new Account();
        $accountThird->balance = 568;
        $accountThird->save();
        return true;
    }
    public function down()
    {
        $this->truncateTable('{{%account}}');
        return false;
    }
}
```

Как это сделать...
---

1 Добавьте следующее правило в метод rules, в models/Account.php:
```php
public function rules()
{
    return [
        //..
        [['balance'], 'number', 'min' => 0],
        //..
    ];
}
```

2 Предположим, что наш баланс может быть только положительным и не может быть отрицательным.

3 Создайте TestController с действиями успеха и ошибки:

```php
<?php
namespace app\controllers;
use app\models\Account;
use Yii;
use yii\db\Exception;
use yii\helpers\Html;
use yii\helpers\VarDumper;
use yii\web\Controller;
class TestController extends Controller
{
    public function actionSuccess()
    {
        $transaction = Yii::$app->db->beginTransaction();
        try {
            $recipient = Account::findOne(1);
            $sender = Account::findOne(2);
            $transferAmount = 177;
            $recipient->balance += $transferAmount;
            $sender->balance -= $transferAmount;
            if ($sender->save() && $recipient->save()) {
                $transaction->commit();
                return $this->renderContent(Html::tag('h1', 'Money transfer was successfully'));
            } else {
                $transaction->rollBack();
                throw new Exception('Money transfer failed:' .
                    VarDumper::dumpAsString($sender->getErrors()) .
                    VarDumper::dumpAsString($recipient->getErrors())
                );
            }
        } catch ( Exception $e ) {
            $transaction->rollBack();
            throw $e;
        }
    }
    public function actionError()
    {
        $transaction = Yii::$app->db->beginTransaction();
        try {
            $recipient = Account::findOne(1);
            $sender = Account::findOne(3);
            $transferAmount = 1000;
            $recipient->balance += $transferAmount;
            $sender->balance -= $transferAmount;
            if ($sender->save() && $recipient->save()) {
                $transaction->commit();
                return $this->renderContent(
                Html::tag('h1', 'Money transfer was successfully'));
            } else {
                $transaction->rollBack();
                throw new Exception('Money transfer failed: ' .
                    VarDumper::dumpAsString($sender->getErrors()) .
                    VarDumper::dumpAsString($recipient->getErrors())
                    );
            }
        } catch ( Exception $e ) {
            $transaction->rollBack();
            throw $e;
        }
    }
```
Выполните test/success, и вы должны получить Выходные данные, показанные на следующем снимке экрана:
![](img/156_1.jpg)

5. В этом случае механизм транзакций не обновит баланс получателя и отправителя, если произошла ошибка.

6. Выполните test/error, и вы должны получить Выходные данные, показанные на следующем снимке экрана:

![](img/156_2.jpg)

Как вы помните, мы добавили правило в Модель счета, поэтому баланс нашего счета может быть только положительным.
Транзакция будет откатываться в этом случае, и это предотвращает ситуацию, когда деньги снимаются со счета отправителя, но не зачисляются на счет получателя.

Смотрите так же
---
Для получения дополнительной информации обратитесь к:
* <http://www.yiiframework.com/doc-2.0/guide-db-dao.html#performing-transactions>
по русски  <http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-dao#performing-transactions> 
* <http://www.yiiframework.com/doc-2.0/guide-db-dao.html#nesting-transactions>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-dao#nesting-transactions> 





Репликация и разделение операций чтения и записи
===
В этом рецепте мы рассмотрим, как сделать репликацию и разделение чтения и записи. Мы увидим, как ведомые и главные серверы помогают нам в том, чтобы сделать это.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу
<http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Настройте подключение к базе данных и создайте таблицу с именем post, как показано ниже:
```php
DROP TABLE IF EXISTS 'blog_post';
CREATE TABLE IF NOT EXISTS 'blog_post' (
'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
'title' VARCHAR(255) NOT NULL,
'text' TEXT NOT NULL,
'created_at' INTEGER,
' modified_at'INTEGER,
PRIMARY KEY ('id')
);
```

3 Создание модели BlogPost для таблицы blog_post.


4 Настройте репликацию Master-slave между серверами баз данных, например, как в статье
<https://www.digitalocean.com/community/tutorials/how-to-set-up-mastpr-slave-replication-in-mysql/>.


5 Настройте компонент БД в config/main.php; вот пример конфигурации:
```php
'components' =>[
	// ..
	'db' => [
		'class' => 'yii\db\Connection',
		'dsn' => 'mysql:host=4.4.4.4;dbname=masterdb',
		'username' => 'master',
		'password' => 'pass',
		'charset' => 'utf8 ',
		'slaveConfig' => [
			'username' => 'slave',
			'password' => 'pass',
		],
		// list of slave configurations
		'slaves' => [
			['dsn' => 'mysql:host=5.5.5.5;dbname=slavedb']
		]
	],
	// ..
]
```

Как это сделать...
---

1 Создать TestController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\BlogPost;
use Yii;
use yii\helpers\Html;
use yii\helpers\VarDumper;
use yii\web\Controller;
/**
* Class TestController
* @package app\controllers
*/
class TestController extends Controller
{
	public function actionIndex(){
		$masterModel = new BlogPost();
		$masterModel->title = 'Awesome';
		$masterModel->text = 'Something is going on..';
		$masterModel->save();
		$postId = $masterModel->id;
		$replModel = BlogPost::findOne($postId);
		return $this->renderContent(
		Html::tag('h2', 'Master') .
		Html::tag('pre', VarDumper::dumpAsString(
			$masterModel
			? $masterModel->attributes
			: null
		)) .
		Html::tag('h2', 'Slave') .
			Html::tag('pre', VarDumper::dumpAsString(
				$replModel
				? $replModel->attributes
				: null
			))
		);
	}
}
```

2 Запустите test/index, и вы должны получить Выходные данные, показанные на следующем снимке экрана:
![](img/160_1.jpg)

Как это работает...
---
Ведомые серверы используются для чтения данных, в то время как главный сервер используется для записи. После сохранения модели ActiveRecord на главном сервере новые записи реплицируются на подчиненный сервер, а затем $replModel находит записи на нем.

Есть еще.
---
Компонент\yii\db\connection поддерживает балансировку нагрузки и отработку отказа между ведомыми устройствами. При выполнении запроса на чтение в первый раз компонент \yii\db\connection случайным образом выберет ведомое устройство и попытается подключиться к нему. Если раб найден мертвым, он попробует еще один. Если ни один из ведомых устройств не доступен, это соединится с ведущим устройством. Настроив кэш состояния сервера, можно запомнить мертвый сервер, чтобы он не повторялся в течение определенного периода времени.

Смотрите так же
---
Дополнительные сведения см. по следующим URL-адресам:
* <http://www.yiiframework.com/doc-2.0/guide-db-dao.html#replication-and-read-write-splitting>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/db-dao#read-write-splitting>
* <http://dev.mysql.com/doc/refman/5.G/en/replication.html>
* <http://docs.mongodb.org/manual/tutorial/deploy-replica-set/>
* <http://docs.mongodb.org/manual/tutorial/deploy-replica-set-for-testing/>




Реализация наследования одной таблицы
===
Реляционные базы данных не поддерживают наследование. Если нам нужно сохранить наследование в базе данных, мы должны каким-то образом поддерживать его с помощью кода. Этот код должен быть эффективным, чтобы генерировать как можно меньше соединений. Общее решение этой проблемы было описано Мартином Фаулером и называется наследованием одной таблицы.
Когда мы используем этот шаблон, мы храним все данные дерева классов в одной таблице и используем поле type для определения модели для каждой строки.
В качестве примера мы реализуем наследование одной таблицы для следующего дерева классов:

Car

  |- SportCar

  |- FamilyCar

Подготовка
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу
<http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Создание и настройка базы данных. Добавить следующую таблицу:
```php
DROP TABLE IF EXISTS 'car';
CREATE TABLE 'car' (
'id' int(10) UNSIGNED NOT NULL AUTO_INCREMENT,
'name' varchar(255) NOT NULL,
'type' varchar(100) NOT NULL,
PRIMARY KEY ('id')
);
INSERT INTO 'car' ('name', 'type')
VALUES ('Ford Focus', 'family'),
('Opel Astra', 'family'),
('Kia Ceed', 'family'),
('Porsche Boxster', 'sport'),
('Ferrari 550','sport');
```

3 Используйте Gii для создания модели автомобиля для таблицы car и создания ActiveQuery для модели автомобиля.

Как это сделать...
---
1 Добавьте следующий метод и свойство в models/CarQuery.php:
```php
/**
* @var
*/
public $type;
/**
* @param \yii\db\QueryBuilder $builder
*
* @return \yii\db\Query
*/
public function prepare($builder)
{
    if ($this->type !== null) {
        $this->andWhere(['type' => $this->type]);
    }
    return parent::prepare($builder);
}
```

2 Создание models/sportcar.php следующим образом:
```php
<?php
namespace app\models;
use Yii;
/**
* Class SportCar
* @package app\models
*/
class SportCar extends Car
{
    const TYPE = 'sport';
    /**
    * @return CarQuery
    */
    public static function find()
    {
        return new CarQuery(get_called_class(), ['where' => ['type' =>self::TYPE]]);
    }
    /**
    * @param bool $insert
    *
    * @return bool
    */
    public function beforeSave($insert)
    {
        $this->type = self::TYPE;
        return parent::beforeSave($insert);
    }
}
```

3 Создание models/FamilyCar.php следующим образом:
```php
<?php
namespace app\models;
use Yii;
/**
* Class FamilyCar
* @package app\models
*/
class FamilyCar extends Car
{
    const TYPE = 'family';
    /**
    * @return CarQuery
    */
    public static function find()
    {
        return new CarQuery(get_called_class(), ['where' => ['type' =>self::TYPE]]);
    }
    /**
    * @param bool $insert
    *
    * @return bool
    */
    public function beforeSave($insert)
    {
        $this->type = self::TYPE;
        return parent::beforeSave($insert);
    }
}
````
4 Добавьте следующий метод к models/Car.php:
```php
/**
* @param array $row
*
* @return Car|FamilyCar|SportCar
*/
public static function instantiate($row)
{
    switch ($row['type']) {
    case SportCar::TYPE:
        return new SportCar();
    case FamilyCar::TYPE:
        return new FamilyCar();
    default:
        return new self;
    }
}
```

5 Add TestController with the following code:
```php
<?php
namespace app\controllers;
use app\models\Car;
use app\models\FamilyCar;
use Yii;
use yii\helpers\Html;
use yii\web\Controller;
/**
* Class TestController
* @package app\controllers
*/
class TestController extends Controller
{
    public function actionIndex()
    {
        echo Html::tag('h1', 'All cars');
        $cars = Car::find()->all();
        foreach ($cars as $car) {
            // Each car can be of class Car, SportCar or FamilyCar
            echo get_class($car).' '.$car->name."<br />";
       }
        echo Html::tag('h1', 'Family cars');
        $familyCars = FamilyCar::find()->all();
        foreach($familyCars as $car)
        {
            // Each car should be FamilyCar
            echo get_class($car).' '.$car->name."<br />";
        }
    }
}
```

6 Запустите test/index, и вы должны получить выходные данные, показанные на следующем снимке экрана:
![](img/165_1.jpg)

Как это работает...
---
Автомобиль базовой модели типичная -используемая модель YII AR за исключением того, что он имеет 2 добавленных метода. Метод tableName явно объявляет имя таблицы, которое будет использоваться для модели. Для одной только модели автомобиля это не имеет смысла, но для дочерних моделей он вернет ту же таблицу автомобилей, что и мы хотим —одну таблицу для всего дерева классов. Метод instantiate используется AR внутренне для создания экземпляра модели из необработанных данных при вызове таких методов, как Car::find()->all(). Мы используем оператор switch для создания различных классов на основе атрибута type и используем один и тот же класс, если значение атрибута не указано или указывает на несуществующий класс.
Модели Sportcar и FamilyCar просто устанавливают область AR по умолчанию, поэтому при поиске моделей с помощью методов SportCar:: model () - > мы получим только модель SportCar.

Смотрите так же
---
Используйте следующие ссылки, чтобы узнать больше о шаблоне наследования одной таблицы и реализации Active Record Yii:
* <http://martinfowler.com/eaaCatalog/singleTableInheritance.html>
* <https://blog.liip.ch/archive/2012/03/27/table-inheritance-with-doctrine.html>
* <http://www.yiiframework.com/doc/api/CActiveRecord>/




Ãëàâà 4. Ôîðìû
===
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:
* Íàïèñàíèå ñîáñòâåííûõ âàëèäàòîðîâ
* Çàãðóçêà ôàéëîâ
* Äîáàâëåíèå è íàñòðîéêà CaptchaWidget
* Íàñòðîéêà êàï÷è
* Ñîçäàíèå ïîëüçîâàòåëüñêîãî âèäæåòà ââîäà
* Òàáëè÷íûé ââîä
* Óñëîâíàÿ âàëèäàöèÿ
* Ñëîæíûå ôîðìû ñ ìíîæåñòâåííûìè ìîäåëÿìè
* Ðàñêðûâàþùèéñÿ ñïèñîê, çàâèñÿùèé îò AJAX
* Ïðîâåðêà AJAX
* Ñîçäàíèå ïîëüçîâàòåëüñêîé ïðîâåðêè íà ñòîðîíå êëèåíòà

Ââåäåíèå
===
Yii äåëàåò ðàáîòó ñ ôîðìàìè ëåãêîé è äîêóìåíòàöèÿ íà ýòó òåìó ïî÷òè çàêîí÷åíà. Òåì íå ìåíåå, åñòü íåêîòîðûå îáëàñòè, êîòîðûå íóæäàþòñÿ â ðàçúÿñíåíèÿõ è ïðèìåðàõ. Ìû îïèøåì èõ â ýòîé ãëàâå.






Написание собственных валидаторов
===
Yii обеспечивает хороший набор встроенных валидаторов форм, которые охватывают наиболее типичные потребности разработчиков и легко настраиваются. Однако, в некоторых случаях разработчику может потребоваться создать пользовательский валидатор.
Этот рецепт является хорошим примером создания автономного валидатора, который проверяет количество слов.

Подготовка
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу
<http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---

1 Создайте автономный валидатор в @app/components/WordsValidator.php следующим образом:
```php
<?php
namespace app\components;
use yii\validators\Validator;
class WordsValidator extends Validator
    {
    public $size = 50;
    public function validateValue($value){
        if (str_word_count($value) > $this->size) {
            return ['The number of words must be less than {size}', ['size' =>$this->size]];
        }
        return false;
    }
}
```

2 Создайте модель статьи в @app/models/Article.php следующим образом:
```php
<?php
namespace app\models;
use app\components\WordsValidator;
use yii\base\Model;
class Article extends Model
{
    public $title;
    public function rules()
    {
        return [
        ['title ',	'string'],
        ['title', WordsValidator::className(), 'size' => 10],
        ];
    }
}
```

3 Создайте @app/controllers/ModelValidationController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\Article;
use yii\helpers\Html;
use yii\web\Controller;
class ModelValidationController extends Controller
{
    private function getLongTitle()
    {
        return 'There is a very long content for current article, '.'it should be less then ten words';
    }
    private function getShortTitle()
    {
        return 'There is a shot title';
    }
    private function renderContentByModel($title)
    {
        $model = new Article();
        $model->title = $title;
        if ($model->validate()) {
            $content = Html::tag('div', 'Model is valid.',[
                'class' => 'alert alert-success',
                ]);
        } else {
            $content = Html::errorSummary($model, [
                'class' => 'alert alert-danger',
            ]);
        }
        return $this->renderContent($content);
    }
    public function actionSuccess()
    {
        $title = $this->getShortTitle();
        return $this->renderContentByModel($title);
    }
    public function actionFailure()
    {
        $title = $this->getLongTitle();
        return $this->renderContentByModel($title);
    }
}
```

4 Запустите действие success контроллера modelValidation, открыв index.php?r=model-validation/success, и вы получите следующее:
![](img/169_1.jpg)

5 Запустите действие failure контроллера modelValidation, открыв index.php?r=model-validation/failure, и вы получите следующее: 
![](img/170_1.jpg)

6 Создайте @app/controllers/AdhocValidationController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\components\WordsValidator;
use app\models\Article;
use yii\helpers\Html;
use yii\web\Controller;
class AdhocValidationController extends Controller
{
    private function getLongTitle()
    {
        return 'There is a very long content for current article, '.'it should be less then ten words';
    }

    private function getShortTitle()
    {
        return 'There is a shot title';
    }

    private function renderContentByTitle($title)
    {
        $validator = new WordsValidator(['size' => 10,]);
        if ($validator->validate($title, $error)) {
            $content = Html::tag('div', 'Value is valid.',[
                'class' => 'alert alert-success',
            ]);
        } else {
            $content = Html::tag('div', $error, [
                'class' => 'alert alert-danger',
            ]);
        }
        return $this->renderContent($content);
    }

    public function actionSuccess()
    {
        $title = $this->getShortTitle();
        return $this->renderContentByTitle($title);
    }

    public function actionFailure()
    {
        $title = $this->getLongTitle();
        return $this->renderContentByTitle($title);
    }
}
```
Запустите успешное действие AdhocValidationController, открыв index.php?r=adhoc-validation/success, и вы получите следующее:
![](img/171_1.jpg)

Запустите действие failure контроллера adhocvalidation, открыв index.php?r=adhoc-validation/failure URL-адрес, и вы получите следующее:
![](img/171_2.jpg)

Как это работает...
---
Сначала мы создали автономный валидатор, который проверяет количество слов с помощью стандартной функции STR_WORD_COUNT PHP, а затем продемонстрировали два варианта использования валидатора:
* Использование средства проверки в качестве правила проверки в модели статьи
* Использование валидатора в качестве специального валидатора
Валидатор имеет атрибут size, который устанавливает максимальное значение для количества слов.

Смотрите так же
---
Дополнительные сведения см. по следующим URL-адресам:
* <http://www.yiiframework.com/doc-2.0/guide-input-validation.html>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-validation>
* <http://www.yiiframework.com/doc-2.0/guide-tutorial-corevalidators.html>





Загрузка файлов
===
Обработка загрузки файлов является довольно распространенной задачей для веб-приложения. Yii имеет некоторые полезные классы, встроенные для этого. Давайте создадим простую форму, которая позволит загружать ZIP архивы и хранить их в /uploads.

Подготовка
---

1 Создайте новое приложение с помощью composer, как описано в официальном руководстве по <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Создайте каталог @app/web/uploads

Как это сделать...
---

1 Мы начнем с модели, поэтому создайте модель @app/models/Upload.php следующим образом:
```php
<?php
namespace app\models;
use yii\base\Model;
use yii\web\UploadedFile;
class UploadForm extends Model
{
    /**
    * @var UploadedFile
    */
    public $file;
    public function rules()
    {
        return [
            ['file', 'file', 'skipOnEmpty' => false, 'extensions' => 'zip'],
        ];
    }
    public function upload()
    {
        if ($this->validate()) {
            $this->file->saveAs('uploads/' . $this->file->baseName . '.'	. $this->file->extension);
            return true;
        } else {
            return false;
        }
    }
}
```

2 Теперь перейдем к контроллеру, поэтому создадим @app/controllers/UploadController.php как:
```php
<?php
namespace app\controllers;
use Yii;
use yii\web\Controller;
use app\models\UploadForm;
use yii\web\UploadedFile;
class UploadController extends Controller
{
    public function actionUpload()
    {
        $model = new UploadForm();
        if (Yii::$app->request->isPost) {
            $model->file = UploadedFile::getInstance($model, 'file');
            if ($model->upload()) {
                return $this->renderContent("File {$model->file->name} is uploaded successfully");
            }
        }
        return $this->render('index', ['model' => $model]);
    }
}
```

3 Наконец, Вы можете просмотреть @app/views/upload/index.php следующим образом:
![](img/173_1.jpg)

```php
<?php
use yii\widgets\ActiveForm;
use yii\helpers\Html;
?>
<?php $form = ActiveForm::begin(['options' => ['enctype' => 'multipart/form-data']]) ?>
<?= $form->field($model, 'file')->fileInput() ?>
<?= Html::submitButton('Upload', ['class' => 'btn-success'])?>
<?php ActiveForm::end() ?>
```

4 Вот и все. Теперь запустите контроллер загрузки и попробуйте загрузить как ZIP-архивы, так и другие файлы, как показано на следующем снимке экрана:

Как это работает...
---
Модель, которую мы используем, довольно проста. Мы определяем только одно поле с именем $file и правило проверки, которое использует файловый валидатор FileValidator, который читает только ZIP-файлы.
Мы создаем экземпляр модели и заполняем его данными из $_POST, если форма отправлена:
```php
$model->file = UploadedFile::getInstance($model, 'file');
if ($model->upload()) {
     return $this->renderContent("File {$model->file->name} is uploaded successfully");
}
```
Затем мы используем UploadedFile:: getInstance, что дает нам доступ к использованию экземпляра UploadedFile. Этот класс является оболочкой вокруг массива $_FILE, который PHP заполняет при загрузке файла. Мы удостоверяемся, что файл является ZIP-архивом, вызвав метод validate модели, затем мы сохраняем файл, используя UploadedFile:: saveAs.
Для загрузки файла HTML-форма должна соответствовать следующим двум важным требованиям:
* Метод должен быть установлен в POST
* Атрибут enctype должен иметь значение multipart / form-data
Важно помнить, что вы добавляете опцию enctype в форму, чтобы файл можно было правильно загрузить.
Мы можем создать этот HTML с помощью помощника Html или ActiveForm с набором htmlOptions. Здесь использовался HTML:
```php
<?= Html::beginForm('', 'post', ['enctype'=>'multipart/form-data'])?>
```
В конце концов, мы отобразим ошибку и поле для атрибута файла модели, а также отобразим кнопку Отправить.

Есть еще...
---
Для загрузки нескольких файлов Yii2 реализует два специальных метода.
Например, вы определили $imageFiles в вашей модели в файле представления в общем все будет то же самое с небольшой разницей:
```php
<?= $form->field($model, 'imageFiles[]')->fileInput(['multiple' => true, 'accept' =>'image/*']) ?>
```
Чтобы получить dсе экземпляры файлов, необходимо вызвать Cuploadedfile::getInstances() вместо UploadedFile::getInstance():
```php
$model->imageFiles = UploadedFile::getInstances($model, 'imageFiles');
```
Обработка и сохранение нескольких файлов может быть сделано с помощью простого фрагмента кода:
```php
foreach ($this->imageFiles as $file) {
    $file->saveAs('uploads/' . $file->baseName .	'.' . $file->extension);
}
```

Смотрите так же
---
Для получения дополнительной информации обратитесь к:
* <http://www.yiiframework.com/doc-2.0/guide-input-file-upload.html> по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-file-upload>
* <http://www.yiiframework.com/doc-2.0/guide-input-file-upload.html#uploadjng-multiple-files> по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-file-upload#uploading-multiple-files>





Добавление и настройка CaptchaWidget
===
В настоящее время, в Интернете, если вы оставите форму без защиты от спама, вы получите массу спам-данных, введенных в течение короткого времени. Yii включает компонент Captcha который делает добавлять такое предохранение легким.
Единственная проблема заключается в том, что нет систематического руководства о том, как его использовать. В следующем примере мы добавим защиту Captcha в простую форму.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.  По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Создайте модель формы @app/models/EmailForm.php, следующим образом:
```php
<?php
namespace app\models;
use yii\base\Model;
class EmailForm extends Model
{
    public $email;
    public function rules()
    {
        return [
            ['email',	'email']
        ];
    }
}
```

3 Создайте контроллер @app/controllers/EmailController.php, следующим образом:
```php
<?php
namespace app\controllers;
use Yii;
use yii\web\Controller;
use app\models\EmailForm;
class EmailController extends Controller
{
    public function actionIndex(){
        $success = false;
        $model = new EmailForm();
        if ($model->load(Yii::$app->request->post()) && $model->validate()) {
            Yii::$app->session->setFlash('success', 'Success!');
        }
        return $this->render('index', [
            'model' => $model,
            'success' => $success,
        ]);
    }
}
```

4 Создайте представление @app/views/email/index.php, следующим образом:
```php
<?php
use yii\helpers\Html;
use yii\captcha\Captcha;
use yii\widgets\ActiveForm;
?>
<?php if (Yii::$app->session->hasFlash('success')): ?>
    <div class="alert alert-success"><?=Yii::$app->session->getFlash('success')?></div>
<?php else: ?>
    <?php $form = ActiveForm::begin()?>
        <div class="control-group">
            <div class="controls">
                <?= $form->field($model, 'email')->textInput(['class' => 'form-control ']); ?>
                <?php echo Html::error($model, 'email', ['class' => 'help-block'])?>
            </div>
        </div>
        <?php if (Captcha::checkRequirements() && Yii::$app->user->isGuest): ?>
            <div class="control-group">
                <?= $form->field($model, 'verifyCode')->widget(\yii\captcha\Captcha::classname(), ['captchaAction' => 'email/captcha']) ?>
            </div>
        <?php endif; ?>
        <div class="control-group">
            <label class="control-label" for=""></label>
            <div class="controls">
                <?=Html::submitButton('Submit', ['class' => 'btn btn-success'])?>
            </div>
        </div>
    <?php ActiveForm::end()?>
<?php endif;?>
```
5 Теперь у нас есть форма отправки электронной почты, как показано на следующем снимке экрана, которая проверяет поле электронной почты. Давайте добавим капчу:
![](img/176_1.jpg)

Как это сделать...
---

1 Во-первых, нам нужно настроить модель формы. Нам нужно добавить $verifyCode, который будет содержать введенный код проверки и добавить для него правило проверки:
```php
<?php
namespace app\models;
use yii\base\Model;
use yii\captcha\Captcha;
class EmailForm extends Model
{
    public $email;
    public $verifyCode;
    public function rules()
    {
        return [
            ['email',	'email' ],
            ['verifyCode', 'captcha', 'skipOnEmpty' =>  !Captcha::checkRequirements(), 'captchaAction' => 'email/captcha']
        ];
    }
}
```

2 Затем нам нужно добавить внешнее действие к контроллеру. Добавьте в него следующий код:
```php
public function actions()
{
    return [
        'captcha' => [
            'class' => 'yii\captcha\CaptchaAction',
        ],
    ];
}
```

3 В виде нам нужно показать дополнительное поле и изображение капчи. Следующий код сделает это за нас:
```php
<?php if (Captcha::checkRequirements() && Yii::$app->user->isGuest): ?>
    <div class="control-group">
        <?=Captcha::widget([
            'model' => $model,
            'attribute' => 'verifyCode',
            ]);?>
        <?php echo Html::error($model, 'verifyCode')?>
    </div>
<?php endif; ?>
```

4 Кроме того, не забудьте добавить Импорт Captcha в разделе заголовка представления:
```php
<?php
use yii\helpers\Html;
use yii\captcha\Captcha;
?>
```

5 Вот и все. Теперь вы можете запустить контроллер электронной почты и увидеть Captcha в действии, как показано на следующем снимке экрана:
![](img/178_1.jpg)

Если на экране нет ошибок и нет поля Captcha в форме, скорее всего, у вас нет установленных и настроенных расширений GD PHP или Imagick. Imagick или GD требуется для Captcha, потому что он генерирует изображения. Мы добавили несколько проверок Captcha::checkRequirements (), поэтому приложение не будет использовать Captcha, если изображение не может быть отображено, но оно все равно будет работать.

Как это работает...
---
В представлении мы вызываем виджет Captcha, который отображает тег img с атрибутом src, указывающим на действие Captcha, которое мы добавили к контроллеру. В этом действии генерируется изображение со случайным словом. Сгенерированное слово-это код, который пользователь должен ввести в форму. Он хранится в пользовательском сеансе, и изображение отображается пользователю. Когда пользователь вводит в форму адрес электронной почты и код подтверждения, мы присваиваем эти значения модели формы, а затем проверяем ее. Для верификации поля кода мы используем Captchavalidator. Он получает код из сеанса пользователя и сравнивает его с введенным кодом. Если они не совпадают, данные модели считаются недопустимыми.

Кое что еще...
---
Если вы ограничиваете доступ к действиям контроллера с помощью метода контроллера accessRules, не забудьте предоставить каждому доступ к ним:

```php
public function behaviors()
{
    return [
        'access' => [
            'class' => AccessControl::className(),
            'rules' => [
                [
                    'actions' => ['index', 'captcha'],
                    'allow' => true,
                ]
            ],
        ],
    ];
}
```





Настройка капчи
==
Стандартная капча Yii достаточно хороша, чтобы защитить вас от спама, но есть ситуации, когда вы можете захотеть настроить ее, такие как:
* Вы сталкиваетесь со спам-ботом, который может читать текст изображения, и вам нужно добавить больше безопасности
* Вы хотите, чтобы сделать его более интересным или легче ввести текст капчи
В нашем примере мы изменим капчу Yii, чтобы она потребовала от пользователя решить действительно простую арифметическую головоломку вместо того, чтобы просто повторять текст на изображении.

Подготовка 
---
В качестве отправной точки для этого примера мы возьмем результат добавления и настройки рецепта CaptchaWidget. В качестве альтернативы, Вы можете принять любую форму, которая использует Captcha, так как мы не сильно много изменяем существующий код .

Как это сделать...
---
Нам нужно настроить captchaAction, который генерирует код и отображает его изображение.
Код должен быть случайным числом и представление должно быть арифметическим выражением, которое дает тот же результат:

1 Создайте @app/components/MathCaptchaAction.php следующим образом:
```php
<?php
namespace app\components;
use \Yii;
use yii\captcha\CaptchaAction;
class MathCaptchaAction extends CaptchaAction
{
    protected function renderImage($code)
    {
        return parent::renderImage($this->getText($code));
    }
    protected function generateVerifyCode()
    {
        return mt_rand((int)$this->minLength,(int)$this->maxLength);
    }
    protected function getText($code)
    {
        $code = (int) $code;
        $rand = mt_rand(1, $code-1);
        $op = mt_rand(0, 1);
        if ($op) {
            return $code - $rand . " + "	. $rand;
        } else {
            return $code + $rand . " - " . " " . $rand;
        }
    }
}
```

2 Теперь, в методе действий нашего контроллера, нам нужно заменить captchaAction нашим собственным действием Captcha, следующим образом:
```php
public function actions()
{
    return [
        'captcha' => [
            'class' => 'app\components\MathCaptchaAction',
            'minLength' => 1,
            'maxLength' => 10,
        ],
    ];
}
```

3 Теперь, запустите форму и попробуйте новую капчу. Он покажет арифметические выражения с числами от 1 до 10 и потребует ввода ответа, как показано на следующем снимке экрана:
![](img/181_1.jpg)

Мы переопределяем два метода CaptchaAction. В generateVerifyCode(), мы генерируем случайное число, а не текст. Затем, поскольку нам нужно отобразить выражение, а не просто показать текст, мы переопределяем renderImage. Само выражение создается в то gettext () метод.
Свойства $minLength и $maxLenght уже определены в CaptchaAction, поэтому нам не нужно добавлять их в наш класс Math CaptchaAction.

Смотрите так же
---
Для получения дополнительной информации обратитесь к следующему:
* <http://www.yiiframework.eom/doc-2.0/yii-captcha-captcha.html>
* <http://www.yiiframework.com/doc-2.0/vii-captcha-captchaartion.html>
* Рецепт Использование базового контроллера Глава  2, Маршрутизация, контроллеры и представления.





Создание пользовательского виджета ввода
===
Yii имеет очень хороший набор виджетов формы, но, как и в каждом фреймворке, Yii не имеет их всех. В этом рецепте мы узнаем, как создать свой собственный виджет ввода. Для нашего примера, мы создадим виджет ввода диапазона.

Подготовка
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
1 Создайте файл виджета @app/components/RangeInputWidget.php, следующим образом:
```php
<?php
namespace app\components;
use yii\base\Exception;
use yii\base\Model;
use yii\base\Widget;
use yii\helpers\Html;
class RangeInputWidget extends Widget
{
    public $model;
    public $attributeFrom;
    public $attributeTo;
    public $htmlOptions = [];

    protected function hasModel()
    {
        return $this->model instanceof Model&& $this->attributeFrom !== null&& $this->attributeTo !== null;
    }
    public function run()
    {
        if (!$this->hasModel()) {
            throw new Exception('Model must be set');
        }
        return Html::activeTextInput($this->model, $this->attributeFrom, $this->htmlOptions) .' &rarr; ' .Html::activeTextInput($this->model, $this->attributeTo, $this->htmlOptions);
    }
}
```

2 Создайте файл контроллера @app/controllers/RangeController.php, следующим образом:
```php
<?php
namespace app\controllers;
use Yii;
use yii\web\Controller;
use app\models\RangeForm;
class RangeController extends Controller
{
    public function actionIndex()
    {
        $model = new RangeForm();
        if ($model->load(Yii::$app->request->post()) && $model->validate()) {
            Yii::$app->session->setFlash('rangeFormSubmitted','The form was successfully processed!');
        }
        return $this->render('index', array(
            'model' => $model,
        ));
    }
}
```

3 Создайте файл формы @app/models/RangeForm.php, следующим образом:
```php
<?php
namespace app\models;
use yii\base\Model;
class RangeForm extends Model
{
    public $from;
    public $to;
    public function rules()
    {
        return [
            [['from',	'to'], 'number', 'integerOnly' => true],
            ['from', 'compare', 'compareAttribute' => 'to', 'operator' => '<='],
        ];
    }
}
```

4 Создайте файл представления @app/views/range/index.php, следующим образом:
```php
<?php
use yii\helpers\Html;
use yii\bootstrap\ActiveForm;
use app\components\RangeInputWidget;
?>
<h1>Range form</h1>
<?php if (Yii::$app->session->hasFlash('rangeFormSubmitted')): ?>
    <div class="alert alert-success">
        <?= Yii::$app->session->getFlash('rangeFormSubmitted'); ?>
    </div>
<?php endif?>
<?= Html::errorSummary($model, ['class'=>'alert alert-danger'])?>
<?php $form = ActiveForm::begin([
    'options' => ['class' => 'form-inline']
    ]); ?>
    <div class="form-group">
        <?= RangeInputWidget::widget([
            'model' => $model,
            'attributeFrom' => 'from',
            'attributeTo' => 'to',
            'htmlOptions' => [
                'class' =>'form-control'
            ]
        ]) ?>
    </div>
    <?= Html::submitButton('Submit', ['class' => 'btn btn-primary', 'name' =>'contact-button']) ?>
<?php ActiveForm::end(); ?>
```
5 Запустите контроллер диапазона, открыв index.php?r=range и вы получите следующее:
![](img/185_1.jpg)

6 Введите 200 в первом поле ввода текста и 300 во втором, и вы получите следующее:
![](img/185_2.jpg)

7 Виджет выдает ошибку, если первое значение больше второго; то есть оно. Попробуйте ввести правильные значения, 100 и 200, для первого и второго входов соответственно:
![](img/186_1.jpg)

Как это работает...
---
Пишем виджет ввода диапазона, который требует четыре параметра:
* model: если она не задана, будет выдано исключение
* attributeFrom: это используется, чтобы установить минимальный диапазон значений
* attributeTo: это используется, чтобы установить максимальный диапазон значений
* htmloptions: передается на каждый вход
Этот виджет используется при проверке формы и настроен на проверку того, что первое значение меньше или равно второму значению.

Кое что еще.
---
Yii2 framework имеет официальное расширение Twitter Bootstrap, которое предоставляет Вам пакет PHP-оболочек над виджетами Twitter Bootstrap. Перед тем, как написать свой собственный виджет, проверьте, существует ли виджет Bootstrap в http://www.yiiframework.com/doc-2.0/extbootstrap-index.html.

Смотрите так же
---
Чтобы узнать больше о виджетах, вы можете использовать следующие ресурсы:
* <http://www.viiframework.com/doc-2.0/yii-base-wirlget.html>
* <https://github.com/viisoft/yii2-bootstrap/blob/master/docs/guide/usage-widgets.md>
* статья про виджеты <https://github.com/yiisoft/yii2-bootstrap/blob/master/docs/guide/README.md>






Табличный ввод
===
В этом разделе мы покажем вам, как использовать модель, чтобы сохранить и проверить связанные модели. Иногда вам нужно будет обрабатывать несколько моделей одного и того же вида в одной форме.
Например, у нас есть конкурсы и призы для конкурсов. Любой конкурс может содержать неограниченное количество призов. Таким образом, нам нужна возможность создать конкурс с призами, проверить их, отобразить все ошибки и сохранить основную модель (модель конкурса) и все связанные модели (модели призов) в базу данных.

Подготовка
---
1  Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>  По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Создавайте миграции для конкурсных и призовых таблиц с помощью следующих команд:

**./yii migrate/create create_table_contest_and_prize_table**

Обновите только что созданные методы миграции up () и down () следующим кодом
```php
public function up()
{
    $tableOptions = null;
    if ($this->db->driverName === 'mysql') {
        $tableOptions = 'CHARACTER SET utf8 COLLATE utf8_general_ci ENGINE=InnoDB';
    }
    $this->createTable('{{%contest}}',	[
        'id' => Schema::TYPE_PK,
        'name' => Schema::TYPE_STRING .	' NOT NULL',
        ], $tableOptions);
    $this->createTable('{{%prize}}', [
        'id' => Schema::TYPE_PK,
        'name' => Schema::TYPE_STRING,
        'amount' => Schema::TYPE_INTEGER,
    ], $tableOptions);
    $this->createTable('{{%contest_prize_assn}}',	[
        'contest_id' => Schema::TYPE_INTEGER,
        'prize_id' => Schema::TYPE_INTEGER,
    ], $tableOptions);
    $this-addForeignKey('fk_contest_prize_assn_contest_id',
        '{{%contest_prize_assn}}', 'contest_id', {{%contest}}', 'id');
    $this->addForeignKey('fk_contest_prize_assn_prize_id',
        '{{%contest_prize_assn}}', 'prize_id', '{{%prize}}',	'id');
}
public function down()
{
    $this-dropForeignKey('fk_contest_prize_assn_contest_id','{{%contest_prize_assn}}');
    $this->dropForeignKey('fk_contest_prize_assn_prize_id','{{%contest_prize_assn}}');
    $this->dropTable('{{%contest_prize_assn}}');
    $this->dropTable('{{%prize}}');
    $this->dropTable('{{%contest}}');
}
```

3 Затем установите миграцию с помощью следующей команды:

**./yii migrate/up**

4 С помощью GII, создайте модели Contest, Priz, и  ContestPrizeAssn.

Как это сделать...
---

1 Давайте создадим @app/controllers/ContestController.php со следующим кодом:
```php
<?php
namespace app\controllers;
use app\models\Contest;
use app\models\ContestPrizeAssn;
use app\models\Prize;
use Yii;
use yii\base\Model;
use yii\helpers\VarDumper;
use yii\web\Controller;
class ContestController extends Controller
{
    public function actionCreate()
    {
        $contestName = 'Happy New Year';
        $firstPrize = new Prize();
        $firstPrize->name = 'Iphone 6s';
        $firstPrize->amount = 4;
        $secondPrize = new Prize();
        $secondPrize->name = 'Sony Playstation 4';
        $secondPrize->amount = 2;
        $contest = new Contest();
        $contest->name = $contestName;
        $prizes = [$firstPrize, $secondPrize];
        if ($contest->validate() && Model::validateMultiple($prizes)) {
            $contest->save(false);
            foreach ($prizes as $prize) {
                $prize->save(false);
                $contestPrizeAssn = new ContestPrizeAssn();
                $contestPrizeAssn->prize_id = $prize->id;
                $contestPrizeAssn->contest_id = $contest>id;
                $contestPrizeAssn->save(false);
            }
            return $this->renderContent('All prizes have been successfully saved!');
        } else {
            return $this->renderContent(VarDumper::dumpAsString($contest->getErrors()));
        }
    }

    public function actionUpdate()
    {
        $prizes = Prize::find()->all();
        if (Model::loadMultiple($prizes, Yii::$app->request->post()) &&Model::validateMultiple($prizes)){
            foreach ($prizes as $prize) {
                $prize->save(false);
            }
            return $this->renderContent('All prizes have been successfully saved!');
        }
        return $this->render('update', ['prizes' => $prizes]);
    }
}
```

2 Создать @app/views/contest/update.php и поместите в него следующий код:
```php
<?php
use yii\helpers\Html;
use yii\widgets\ActiveForm;
$form = ActiveForm::begin();
foreach ($prizes as $i => $prize) {
    echo $form->field($prize, "[$i]amount")->label($prize->name);
}
echo Html::submitButton('submit' , ['class' => 'btn btn-success']);

ActiveForm::end();
?>
Как это работает...
---
Следующая информация показывает, как реализовать табличный ввод с помощью Yii.
В действии contest/update , мы сможем отобразить все призы с их креплениями и редактировать их все сразу. Мы использовали два специальных метода Yii:
* Model: : loadMultiple (): ***This method populates a set of models with data from the end user***
* Model: : validateMultiple(): ***This methods takes a set of models and validates them all at once***
Поскольку мы уже проверяли наши модели с помощью validateMultiple(), мы передаем false в качестве параметра save(), чтобы избежать выполнения проверки дважды.
Во-первых, визит на страницу /index. php?r=contest/create . После посещения, вы увидите страницу, которая будет проверять и создавать "С Новым Годом" с двумя призами, и передаст призы текущей модели конкурса. Обратите внимание, что модель конкурса и призы будут сохранены в базе данных только в том случае, если они действительны:
![](img/189_1.jpg)

Это обеспечивается следующим условием:
```php
if ($contest->validate() && Model::validateMultiple($prizes)) { ...}
```
Перейдите в /index.php?r=contest/update, и вы увидите эту форму:
![](img/190_1.jpg)

В @app/views/contest/update.php для каждого приза мы выводим имя и ввод с суммой.
Мы должны добавить индекс к каждому входному имени, чтобы Model:: loadMultiple() мог определить, какую модель заполнить какими значениями.
В заключение, этот подход используется для сбора табличных входных данных при обработке всех атрибутов из формы представления и заполнении родительских и связанных моделей из формы.

Смотрите так же
---
Для получения дополнительной информации, обратитесь к следующему адресу:
<http://www.yiiframework.com/doc-2.0/guide-input-tabular-input.html#collecting-tabular-input>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-tabular-input> 





Условная проверка
===
Бывают случаи, когда необходимо включить или отключить определенные правила валидации в модели. Yii2 обеспечивает механизм для этого.

Подготовка
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
1 Создайте файл формы @app/models/DeliveryForm.php, следующим образом:
```php
<?php
namespace app\models;
use app\components\WordsValidator;
use yii\base\Model;
class DeliveryForm extends Model
{
    const TYPE_PICKUP = 1;
    const TYPE_COURIER = 2;
    public $type;
    public $address;
    public function rules()
    {
        return [
            ['type',	'required'],
            ['type', 'in', 'range'=>[self::TYPE_PICKUP, self::TYPE_COURIER]],
            ['address', 'required', 'when' => function ($model) {
                return $model->type == self::TYPE_COURIER;
                }, 'whenClient' => "function (attribute, value) {
                return $('#deliveryform-type').val() == '".self::TYPE_COURIER."';}
                "]
        ];
    }
    public function typeList()
    {
        return [
            self::TYPE_PICKUP => 'Pickup',
            self::TYPE_COURIER => 'Courier delivery',
        ];
    }
}
```

2 Создайте файл контроллера @app/controllers/ValidationController.php, следующим образом:
```php
<?php
namespace app\controllers;
use Yii;
use yii\web\Controller;
use app\models\DeliveryForm;
class ValidationController extends Controller
{
    public function actionIndex()
    {
        $model = new DeliveryForm();
        if ($model->load(Yii::$app->request->post()) && $model->validate()) {
            Yii::$app->session->setFlash('success',
            'The form was successfully processed!'
            );
        }
        return $this->render('index', array(
            'model' => $model,
        ));
    }
}
```

3 Создайте файл представления @app/views/validation/index. php, следующим образом:
```php
<?php
use yii\bootstrap\ActiveForm;
use yii\helpers\Html;
?>
    <h1>Delivery form</h1>
    <?php if (Yii::$app->session->hasFlash('success')): ?>
    <div class="alert alert-success"><?= Yii::$app->session->getFlash('success'); ?></div>
    <?php endif; ?>
    <?php $form = ActiveForm::begin(); ?>
        <?= $form->field($model, 'type')->dropDownList($model->typeList(), ['prompt'=>'Select delivery type']) ?>
        <?= $form->field($model, 'address') ?>
        <div class="form-group"><?= Html::submitButton('Submit', ['class' => 'btn btn-primary']) ?></div>
    <?php ActiveForm::end(); ?>
```

4 Запустите контроллер проверки, открыв index. php?r=validation и выберите значение доставки курьера для ввода типа; затем вы получите следующее:
![](img/192_1.jpg)

Как это работает...
---
Атрибут адрес DeliveryForm требуется, если атрибут Type имеет значение
DeliveryForm::TYPE_COURIER; в противном случае, мы выбираем опцию курьерской доставки в типе select.
Кроме того, для поддержки условной проверки на стороне клиента мы настраиваем свойство whenClient, которое принимает строку, представляющую функцию JavaScript, возвращаемое значение которой определяет, применять правило или нет.

Смотрите так же
---
Для получения дополнительной информации обратитесь к  <http://www.yiiframework.com/doc-2.0/guide-input-validation.html#conditional-validation>
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-validation#conditional-validation>





Сложные формы с несколькими моделями
===
При работе с некоторыми сложными данными, возможно, потребуется использовать несколько различных моделей для сбора входных данных пользователя. Например, у вас есть бланк заказа с информацией о пользователе, такие как имя, фамилия и номер телефона; у вас также есть адрес доставки и какой-то продукт.
Вы хотели бы сохранить все эти данные в одной форме. С моделями Yii и формами поддержки, вы можете легко сделать это.
Предполагая, что информация о пользователе будет храниться в пользовательской таблице и в форме заказа, мы сохраним информацию о продукте и user_id пользователя, который заказал продукт. У нас также есть таблица продуктов с некоторой информацией в ней.

Подготовка
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Создавайте миграции для конкурсных и призовых таблиц с помощью следующих команд:
***./yii migrate/create create_order_tables***

3 Обновите созданные методы миграции up() и down () следующим кодом:
```php
<?php
use yii\db\Schema;
use yii\db\Migration;
use app\models\Product;
class m150813_161817_create_order_form_tables extends Migration
{
    public function up()
    {
        $tableOptions = null;
        if ($this->db->driverName === 'mysql') {
            $tableOptions = 'CHARACTER SET utf8 COLLATE utf8_general_ci ENGINE=InnoDB';
        }
        $this->createTable('user', [
            'id' => Schema::TYPE_PK,
            'first_name' => Schema::TYPE_STRING .	' NOT NULL',
            'last_name' => Schema::TYPE_STRING .	' NOT NULL',
            'phone' => Schema::TYPE_STRING .	' NOT NULL',
            ], $tableOptions);
        $this->createTable('product', [
            'id' => Schema::TYPE_PK,
            'title' => Schema::TYPE_STRING .	' NOT NULL',
            'price' => Schema::TYPE_FLOAT .	'(6,2) ',
            ], $tableOptions);
        $this->createTable('order', [
            'id' => Schema::TYPE_PK,
            'user_id' => Schema::TYPE_INTEGER .	' NULL',
            'address' => Schema::TYPE_STRING .	' NOT NULL',
            'product_id' => Schema::TYPE_INTEGER .	' NOT NULL',
            ], $tableOptions);
        $product1 = new Product();
        $product1->title = 'Iphone 6';
        $product1->price = 400.5;
        $product1->save();
        $product3 = new Product();
        $product3->title = 'Samsung Galaxy Note 5';
        $product3->price = 900;
        $product3->save();
        $this->addForeignKey('fk_order_product_id', 'order', 'product_id',' product',	'id');
    }
    public function down()
    {
        $this->dropTable('order');
        $this->dropTable('user');
        $this->dropTable('product');
    }
}
```

4 Затем установите миграцию с помощью следующей команды:

***./yii migrate/up***

5 С помощью Gii создайте модели пользователей, заказов и продуктов.

Как это сделать...
---
1 Создайте @app/controllers/TestController со следующим кодом:
```php
<?php
namespace app\controllers;
use app\models\Order;
use app\models\User;
use Yii;
use yii\web\Controller;
class TestController extends Controller
{
    public function actionOrder()
    {
        $user = new User();
        $order = new Order();
        if ($user->load(Yii::$app->request->post()) && $order->load(Yii::$app->request->post())) {
        if ($user->validate() && $order->validate()) {
            $user->save(false);
            $order->user_id = $user->id;
            $order->save(false);
            $this->redirect(['/test/result', 'id' => $order->id]);
        }
    }
        return $this->render('order', ['user' => $user, 'order' => $order]);
    }
    public function actionResult($id)
    {
        $order = Order::find($id)->with('product', 'user')->one();
        return $this->renderContent(
            'Product: ' . $order->product->title . '</br>' .
            'Price: ' . $order->product->price . '</br>' .
            'Customer: '. $order->user->first_name .''. $order->user->last_name.</br>'.
            'Address: '. $order->address
        );
    }
}
```

2 Затем создайте файл представления с именем @app/views/test/order.php и добавьте следующий код:
```php
<?php
    use yii\helpers\Html;
    use yii\widgets\ActiveForm;
    use app\models\Product;
    use yii\helpers\ArrayHelper;
    /**
    * @var $user \app\models\User
    * @var $order \app\models\Order
    */
    $form = ActiveForm::begin([
        'id' => 'order-form',
        'options' => ['class' => 'form-horizontal'],
    ]) 
?>
<?= $form->field($user, 'first_name')->textInput(); ?>
<?= $form->field($user, 'last_name')->textInput(); ?>
<?= $form->field($user, 'phone')->textInput(); ?>
<?= $form->field($order, 'product_id')->dropDownList(ArrayHelper::map(Product::find()->all(), 'id', 'title')); ?>
<?= $form->field($order, 'address')->textInput(); ?>
<?= Html::submitButton('Save', ['class' => 'btn btn-primary']) ?>
<?php ActiveForm::end() ?>
```

Как это работает...
---
Вы можете увидеть форму по адресу http: //yii-book.app/index.php?r=test/order. Наша форма собирает информацию от пользователя и моделей заказа.
Давайте заполним нашу форму:
![](img/197_1.jpg)

После сохранения, вы увидите следующий результат:
![](img/198_1.jpg)

В контроллере мы проверяем и храним его. Конечно, этот пример очень прост. В реальных проектах у вас может быть более одной модели, и вы сможете использовать этот подход для них. Этот подход очень полезен, если требуется создать или обновить несколько экземпляров в одной форме.

Смотрите так же
---
Для получения дополнительной информации обратитесь к <http://www.yiiframework.com/doc-2.0/guide-inpnt-mnltiple-models.html> 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-multiple-models> 





Раскрывающийся список, зависящий от AJAX
===
Часто вам понадобится форма с двумя раскрывающимися списками, и одно раскрывающееся значение будет зависеть от значения другого раскрывающегося списка. Используя встроенные функции AJAX Yii, вы можете создать такое выпадающее меню.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски  <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Создайте @app/model/Product.php следующим образом:
```php
<?php
namespace app\models;
use yii\db\ActiveRecord;
class Product extends ActiveRecord
{
    public function rules()
    {
        return [
            ['title ',	'string'],
            [['title', 'category_id', 'sub_category_id'], 'required'],
                ['category_id', 'exist', 'targetAttribute' => 'id', 'targetClass' =>'app\models\Category ' ],
                ['sub_category_id', 'exist', 'targetAttribute' => 'id', 'targetClass'=> 'app\models\Category'],
        ];
    }
    public function attributeLabels()
    {
        return [
            'category_id' => 'Category',
            'sub_category_id' => 'Sub category',
        ]; 
    }
}
```

3 Создайте модель @app/models/Category.php следующим образом:
```php
<?php
namespace app\models;
use yii\db\ActiveRecord;
class Category extends ActiveRecord
{
    public function rules()
    {
        return [['title ',	'string'],];
    }
    /**
    * @return array
    */
    public static function getSubCategories($categoryId)
    {
        $subCategories = [];
        if ($categoryId) {
            $subCategories = self::find()
                ->where(['category_id' => $categoryId])
                ->asArray()
                ->all();
        }
        return $subCategories;
    }
}
```

4 Создайте миграцию create_category_and_product_tables с помощью следующей команды:

***./yii migrate/create create_category_and_product_tables***

5 Обновите только что созданные методы миграции и список импортированных классов следующим образом:
```php
<?php
use yii\db\Schema;
use yii\db\Migration;
class m150813_005030_create_categories extends Migration
{
    public function up()
    {
        $tableOptions = null;
        $this->createTable('{{%product}}',[
            'id' => Schema::TYPE_PK,
            'category_id' => Schema::TYPE_INTEGER .' NOT NULL',
            'sub_category_id' => Schema::TYPE_INTEGER .' NOT NULL',
            'title' => Schema::TYPE_STRING .' NOT NULL',
        ], $tableOptions);
        $this->createTable('{{%category}} ',	[
            'id' => Schema::TYPE_PK,
            'category_id' => Schema::TYPE_INTEGER,
            'title' => Schema::TYPE_STRING .' NOT NULL',
        ], $tableOptions);
        $this->addForeignKey('fk_product_category_id','{{%product}}',
            'category_id', '{{%category}}', 'id');
        $this->addForeignKey('fk_product_sub_category_id',	'{{%product}}',
            'category_id', '{{%category}}', 'id');
        $this->batchInsert('{{%category}}', ['id', 'title'], [
            [1, 'TV, Audio/Video'],
            [2,	' Photo'],
            [3, 'Video']
        ]);
        $this->batchInsert('{{%category}}', ['category_id', 'title'], [
            [1, 'TV'],
            [1, 'Acoustic System'],
            [2, 'Cameras'],
            [2, 'Flashes and Lenses '],
            [3, 'Video Cams'],
            [3, 'Action Cams'],
            [3, 'Accessories']
        ]);
    }
    public function down()
    {
        $this->dropTable('{{%product}}');
        $this->dropTable('{{%category}}');
    }
}
```

Как это сделать...
---

1 Создайте файл контроллера @app/controllers/DropdownController.php, следующим образом:
```php
<?php
namespace app\controllers;
use app\models\Product;
use app\models\Category;
use app\models\SubCategory;
use Yii;
use yii\helpers\ArrayHelper;
use yii\helpers\Json;
use yii\web\Controller;
use yii\web\HttpException;
class DropdownController extends Controller
{
    public function actionGetSubCategories($id)
    {
        if (!Yii::$app->request->isAjax) {
            throw new HttpException(400, 'Only ajax request is allowed.');
        }
        return Json: :encode(Category::getSubCategories($id));
    }
    public function actionIndex()
    {
        $model = new Product();
        if ($model->load(Yii::$app->request->post()) && $model->validate()) {
            Yii::$app->session->setFlash('success','Model was successfully saved');
        }
        return $this->render('index', [
            'model' => $model,
        ]);
    }
}
```

2 Создайте файл представления @app/views/dropdown/index.php, следующим образом:
```php
<?php
use yii\bootstrap\ActiveForm;
use yii\helpers\Html;
use yii\helpers\Url;
use app\models\Category;
use yii\helpers\ArrayHelper;
use yii\web\View;
$url = Url::toRoute(['dropdown/get-sub-categories']);
$this->registerJs("
(function() {
    var select = $('#product-sub_category_id');
    var buildOptions = function(options) {
        if (typeof options === 'object') {
            select. children('option' ).remove();
            $('<option />')
                .appendTo(select)
                .html('Select a sub category')
            $.each(options, function(index, option) {
                $('<option />', {value:option.id})
                .appendTo(select)
                .html(option.title);
            });
        }
    };
    var categoryOnChange = function(category_id){
        $.ajax({
            dataType : ' j son',
            url: '" . $url . "&id=' + category_id ,
            success: buildOptions
        });
    };
    window.buildOptions = buildOptions;
    window.categoryOnChange = categoryOnChange;
})();
", View::POS_READY);
?>
<h1>Product</h1>
<?php if (Yii::$app->session->hasFlash('success')): ?>
    <div class="alert alert-success"><?= Yii::$app->session->getFlash('success'); ?
></div>
<?php endif; ?>
<?php $form = ActiveForm::begin(); ?>
    <?= $form->field($model, 'title')->textInput() ?>
    <?= $form->field($model, 'category_id')->dropDownList(ArrayHelper::map(
        Category::find()->where('category_id IS NULL')->asArray()->all(),'id','title'), [
        'prompt' => 'Select a category',
        'onChange' => 'categoryOnChange($(this).val());',
    ]) ?>
    <?= $form->field($model, 'sub_category_id')->dropDownList(
        ArrayHelper::map(Category::getSubCategories($model->sub_category_id), 'id' , 'title'),	[
        'prompt' => 'Select a sub category',
    ]) ?>
    <div class="form-group">
        <?= Html::submitButton('Submit', ['class' => 'btn btn-primary']) ?>
    </div>
<?php ActiveForm::end(); ?>
```
3 Запустите контроллер раскрывающегося списка, открыв  index.php?r=dropdown, затем добавьте новый продукт со значением Canon-EOS Rebel T6i DSLR для поля заголовка:
![](img/202_1.jpg)

4 Как вы можете видеть, Категория ввода имеет три варианта. Давайте выберем опцию фото и после этого, второй выбор ввода будет иметь еще два варианта:
![](img/203_1.jpg)

5 Вот и все. Если вы выберете другую категорию, вы получите подкатегории этой категории.

Как это работает...
---
В этом примере у нас есть два зависимых списка с категориями и подкатегориями и одна модель, Category. Основная идея проста: мы просто привязали событие JQuery onChange к полю category_id в нашей форме. Каждый раз, когда пользователь изменяет это поле, наше приложение отправляет запрос AJAX в действие get-sub-categories. Это действие возвращает список подкатегорий в формате JSON, а затем на стороне клиента мы строим список параметров для нашего списка подкатегорий.





AJAX валидация
===
Некоторые проверки могут выполняться только на стороне сервера, поскольку только сервер имеет необходимую информацию. Например, чтобы проверить уникальность имени компании или электронной почты пользователя, мы должны проверить соответствующие таблицы на стороне сервера. В этом случае следует использовать встроенную проверку AJAX. Yii2 поддерживает проверку формы AJAX, которая по существу отправляет значения формы на сервер, проверяет их и отправляет обратно ошибки проверки, все, не выходя из страницы. Он делает это каждый раз, когда вы выходите из (измененного) поля.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---

1 В базовом шаблоне приложения у нас есть простая контактная форма. Вы можете увидеть эту страницу на http://yii-book.app/index.php?r=site/contact. Откройте и измените связанную форму представления @app/views/site/contact.php. Чтобы включить проверку AJAX для всей формы, настройте параметр enableAjaxValidation как true в конфигурации формы:
```php
$form = ActiveForm::begin([
      'id' => 'contact-form',
      'enableAjaxValidation' => true,
]);
```

2 Кроме того, следует добавить обработку для проверки AJAX на стороне сервера. Этот фрагмент кода просто проверяет, является ли текущий запрос AJAX и если это запрос POST. Если это так, мы получим ошибки в формате JSON:
```php
if (Yii::$app->request->isAjax && $model->load(Yii::$app->request->post())) {
    Yii::$app->response->format = Response::FORMAT_JSON;
    return ActiveForm::validate($model);
}
```

3 Давайте изменим наш actionContact() в siteController следующим кодом:
```php
public function actionContact()
{
    $model = new ContactForm();
    if (Yii::$app->request->isAjax && $model->load(Yii::$app->request->post())) {
        Yii::$app->response->format = Response::FORMAT_JSON;
        return ActiveForm::validate($model);
    }
    if ($model->load(Yii::$app->request->post()) && $model->contact(Yii::$app->params['adminEmail'])) {
        Yii::$app->session->setFlash('contactFormSubmitted');
        return $this->refresh();
    } else {
        return $this->render('contact', [
        'model' => $model,
        ]);
    }
}
```

Как это работает...
---
Предыдущий код проверит, является ли текущий запрос AJAX. Если это так, он ответит на этот запрос, запустив проверку и вернув ошибки в формате JSON.
Вы можете проверить ответ сервера в панели отладки в браузере. Попробуйте отправить пустую форму и вы увидите ответ.
Например, в браузере Google Chrome, нажмите F12 и выберите вкладку "Сеть" в панели инструментов развития. Вы увидите массив JSON с ошибками и сообщениями:
![](img/205_1.jpg)

Смотрите так же
---
<http://www.yiiframework.com/doc-2.0/guide-input-validation.html#ajaxvalidation>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-validation>







Создание пользовательской проверки на стороне клиента
===
При написании собственного рецепта валидаторов мы создали автономный валидатор. В этом рецепте мы изменим валидатор, чтобы создать дополнительную валидацию на стороне клиента, которая также проверяет количество слов.

Подготовка
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation

Как это сделать...
---

1 Создайте @app/components/WordsValidator.php следующим образом:
```php
<?php
namespace app\components;
use yii\validators\Validator;
class WordsValidator extends Validator
{
    public $size = 50;
    public $message = 'The number of words must be less than {size}';
    public function validateValue($value)
    {
        preg_match_all('/(\w+)/i', $value, $matches);
        if (count($matches[0]) > $this->size) {
            return [$this->message, ['size' => $this->size]];
        }
    }
    public function clientValidateAttribute($model, $attribute, $view)
    {
        $message = strtr($this->message, ['{size}' => $this->size]);
        return <<<JS
            if (value.split(/\w+/gi).length > $this->size ) {
                messages.push("$message");
            }
        JS;
    }
}
```

2 Создать @app/models/Article.php следующим образом:
```php
<?php
namespace app\models;
use app\components\WordsValidator;
use yii\base\Model;
class Article extends Model
{
    public $title;
    public function rules()
    {
        return [
            ['title ',	'string'],
            ['title', WordsValidator::className(), 'size' => 10],
        ];
    }
}
```

3 Создайте @app/controllers/ValidationController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\Article;
use Yii;
use yii\web\Controller;
class ValidationController extends Controller
{
    public function actionIndex()
    {
        $model = new Article();
        if ($model->load(Yii::$app->request->post()) && $model->validate()) {
            Yii::$app->session->setFlash('success', 'Model is valid');
        }
        return $this->render('index', [
            'model' => $model,
        ]);
    }
}
```

4 Создайте @app/views/validation/index.php следующим образом:
```php
<?php
use yii\bootstrap\ActiveForm;
use yii\helpers\Html;
?>
<h1>Article form</h1>
<?php if (Yii::$app->session->hasFlash('success')): ?>
      <div class="alert alert-success">
          <?= Yii::$app->session->getFlash('success'); ?>
      </div>
<?php endif; ?>
<?php $form = ActiveForm::begin(); ?>
      <?= $form->field($model, 'title') ?>
      <div class="form-group">
            <?= Html::submitButton('Submit', ['class' => 'btn btn-primary']) ?>
      </div>
<?php ActiveForm::end(); ?>
```

Как это работает...
---
Запустите контроллер проверки, открыв index. php?r=validation. Вы увидите пример неправильного значения, если введете более десяти слов:
![](img/208_1.jpg)

Если ввести менее десяти слов, проверка на стороне клиента будет успешной:
![](img/208_2.jpg)

Во-первых, мы создали @app/components/wordsvalidator.php, который расширяет класс @yii\validators\validator и добавляет вновь созданный класс validator в атрибут title
Модель статьи:
```php
    ['title', WordsValidator::className(), 'size' => 10],
```
Внутри нашего валидатора мы определили два специальных метода: validatevalue () и  clientValidateAttribute().
Наш класс validator реализует метод validatevalue () для поддержки проверки данных вне контекста модели данных. Второй метод просто возвращает JavaScript, необходимый для выполнения проверки на стороне клиента.

Есть еще...
---
Если мы хотим скрыть реализацию валидатора или хотим контролировать все процессы валидации только на стороне сервера, мы можем создать Отложенный объект.
Во-первых, измените валидатор Wordsvalidator следующим образом:
```php
<?php
namespace app\components;
use yii\validators\Validator;
use yii\helpers\Url;
class WordsValidator extends Validator
{
    public $size = 50;
    public $message = 'The number of words must be less than {size}';
    public function validateValue($value)
    {
        if (str_word_count($value) > $this->size) {
            return ['The number of words must be less than {size}', ['size' => $this->size]];
        }
        return false;
    }
    public function clientValidateAttribute($model, $attribute, $view)
    {
        $url = Url::toRoute(['validation/check-words']);
        return <<<JS
            deferred.push($.get("$url", {words: value}).done(function(data) {
                if (!data.result) {
                    messages.push(data.error);
                }
            }));
        JS;
    }
}
```
В предыдущем коде переменная deferred предоставляемая Yii, который является массивом отложенных объектов.  Метод $get ()jQuery создает Отложенный объект, который передается в отложенный массив.
Во-вторых, добавьте это действие checkWords в контроллер проверки:
```php
public function actionCheckWords()
{
    \Yii::$app->response->format = \yii\web\Response::FORMAT_JSON;
    $value = Yii::$app->getRequest()->get('words');
    $validator = new WordsValidator([
        'size' => 10,
    ]);
    $result = $validator->validate($value, $error);
    return ['result' => $result,'error' => $error];
}
```

Смотрите еще
---
Дополнительные сведения см. по следующим URL-адресам:
* <https://www.yiiframework.com/doc/guide/2.0/en/input-validation#implementing-client-side-validation>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-validation#implementing-client-side-validation> 
* <https://www.yiiframework.com/doc/guide/2.0/en/input-validation#deferred-validation>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/input-validation#deferred-validation> 





Ãëàâà 5. Áåçîïàñíîñòü
===
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:
* Èäåíòèôèêàöèÿ
* Èñïîëüçîâàíèå ôèëüòðîâ êîíòðîëëåðà
* Ïðåäîòâðàùåíèå XSS
* Äëÿ ïðåäîòâðàùåíèÿ SQL-èíúåêöèé 
* Ïðåäîòâðàùåíèÿ csrf àòàê
* Èñïîëüçîâàíèå RBAC
* Øèôðîâàíèå / ðàñøèôðîâêà äàííûõ

Ââåäåíèå
===
Áåçîïàñíîñòü ÿâëÿåòñÿ âàæíîé ÷àñòüþ ëþáîãî âåá-ïðèëîæåíèÿ.
Â ýòîé ãëàâå âû óçíàåòå, êàê îáåñïå÷èòü áåçîïàñíîñòü ïðèëîæåíèÿ â ñîîòâåòñòâèè ñ îáùèì ïðèíöèïîì áåçîïàñíîñòè âåá-ïðèëîæåíèÿ "filter input, escape output". Ìû ðàññìîòðèì òàêèå òåìû, êàê ñîçäàíèå ñîáñòâåííûõ ôèëüòðîâ êîíòðîëëåðà, ïðåäîòâðàùåíèå èíúåêöèé XSS, CSRF è SQL, ýêðàíèðîâàíèå âûõîäíûõ äàííûõ è èñïîëüçîâàíèå óïðàâëåíèÿ äîñòóïîì íà îñíîâå ðîëåé.
Ðåêîìåíäàöèè ïî îáåñïå÷åíèþ áåçîïàñíîñòè ñì. 
<http://www.yiiframework.com/doc-2.0/guide-security-best-practices.html#avoiding-debug-info-and-tools-at-production>

Íà ðóññêîì 
<http://yiiframework.domain-na.me/doc/guide/2.0/ru/security-best-practices>





Идентификация
==
Большинство веб-приложений предоставляют пользователям возможность входа в систему или сброса забытых паролей. В Yii2 у нас нет такой возможности по умолчанию. Для базового шаблона приложения Yii по умолчанию предоставляет только двух тестовых пользователей, которые статически описаны в пользовательской модели. Таким образом, мы должны реализовать специальный код, чтобы иметь возможность включить вход пользователя из базы данных.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 В разделе компонента конфигурации добавьте:
```php
'user' => [
    'identityClass' => 'app\models\User',
    'enableAutoLogin' => true,
],
```

3 Создайте таблицу User. Создайте миграцию, введя следующую команду:

***./yii migrate/create create_user_table***

4 Измените созданую миграции следующим кодом:
```php
<?php
use yii\db\Schema;
use yii\db\Migration;
class m150626_112049_create_user_table extends Migration
{
    public function up()
    {
        $tableOptions = null;
        if ($this->db->driverName === 'mysql') {
            $tableOptions = 'CHARACTER SET utf8 COLLATE utf8_general_ci ENGINE=InnoDB';
        }
        $this->createTable('{{%user}}', [
            'id' => Schema::TYPE_PK,
            'username' => Schema::TYPE_STRING .	' NOT NULL',
            'auth_key' => Schema::TYPE_STRING .	'(32) NOT NULL',
            'password_hash' => Schema::TYPE_STRING .	' NOT NULL',
            'password_reset_token' => Schema::TYPE_STRING,
        ], $tableOptions);
    }
    public function down()
    {
        $this->dropTable('{{%user}}');
    }
}
```

5 Обновите существующую модель models/User следующим кодом:
```php
<?php
namespace app\models;
use yii\db\ActiveRecord;
use yii\web\IdentityInterface;
use yii\base\NotSupportedException;
use Yii;
class User extends ActiveRecord implements IdentityInterface
{
    /* *
    * @inheritdoc
    */
    public function rules()
    {
          return [
               ['username', 'required'],
               ['username', 'unique'],
               ['username', 'string', 'min' => 3],
               ['username', 'match', 'pattern' => '~A[A-Za-z][A-Za-z0-9]+$~', 'message' => 'Username can contain only alphanumeric characters.'],
               [['username', 'password_hash', 'password_reset_token'],'string', 'max' => 255],
               ['auth_key', 'string', 'max' => 32],
          ];
    }
    /**
    * @inheritdoc
    */
    public static function findIdentity($id)
    {
        return static::findOne($id);
    }
    public static function findIdentityByAccessToken($token, $type = null)
    {
        throw new NotSupportedException('"findIdentityByAccessToken" is not implemented .');
    }
    /**
    * Finds user by username
    *
    * @param string	$username
    * @return User
    */
    public static function findByUsername($username)
    {
        return static::findOne(['username' => $username]);
    }
    /**
    * @inheritdoc
    */
    public function getId()
    {
        return $this->getPrimaryKey();
    }
    /**
    * @inheritdoc
    */
    public function getAuthKey()
    {
        return $this->auth_key;
    }
    /* *
    * @inheritdoc
    */
    public function validateAuthKey($authKey)
    {
        return $this->getAuthKey() === $authKey;
    }
    /**
    * Validates password
    *
    * @param string $password password to validate
    * @return boolean if password provided is valid for current user
    */
    public function validatePassword($password)
    {
        return Yii::$app->getSecurity()->validatePassword($password, $this->password_hash);
    }
    /**
    * Generates password hash from password and sets it to the model
    *
    * @param string $password
    */
    public function setPassword($password)
    {
        $this->password_hash = Yii::$app->getSecurity()->generatePasswordHash($password);
    }
    /**
    * Generates "remember me" authentication key
    */
    public function generateAuthKey()
    {
        $this->auth_key = Yii::$app->getSecurity()->generateRandomString();
    }
    /**
    * Generates new password reset token
    */
    public function generatePasswordResetToken()
    {
        $this->password_reset_token = Yii::$app->getSecurity()->generateRandomString() . '_' . time();
    }
    /**
    * Finds user by password reset token
    *
    * @param string	$token password reset token
    * @return static|null
    */
    public static function findByPasswordResetToken($token)
    {
        $expire = Yii::$app->params['user.passwordResetTokenExpire'];
        $parts = explode('_', $token);
        $timestamp = (int) end($parts);
        if ($timestamp + $expire < time()) {
            return null;
        }
        return static::findOne([
            'password_reset_token' => $token
        ]);
    }
}
```

6 Создайте миграцию, которая добавит тестового пользователя. Используйте следующую команду:

***./yii migrate/create create_test_user***

7 Измените  миграции следующим кодом:
```php
<?php
use yii\db\Migration;
use app\models\User;
class m150626_120355_create_test_user extends Migration
{
    public function up()
    {
        $testUser = new User();
        $testUser->username = 'admin';
        $testUser->setPassword('admin');
        $testUser->generateAuthKey();
        $testUser->save();
    }
    public function down()
    {
        User: : findByUsername('turbulence')->delete();
        return false;
    }
}
```

8 Установите все миграции с помощью следующей команды:

***./yii migrate up***

Как это сделать...

1 Теперь, введите  URL-адрес site/login действие и введите admin/admin в качестве учетных данных:
![](img/216_1.jpg)

2 Поздравляю! Если вы завершили эти шаги, вы должны иметь возможность войти.

Как это работает...
---

1 Сначала мы создали миграцию для пользовательской таблицы. Помимо ID и имя пользователя, наша Таблица содержит специальные поля, такие как auth_key (главным образом использовать это для проверки подлинности пользователя с помощью куки), функция password_hash (по соображениям безопасности мы не храним пароли и хранит только хэш пароля), и password_reset_token (используется, когда нужно сбросить пароль пользователя).

2 Результат после установки и миграции create_test_user должен выглядеть следующим образом
screenshot:
![](img/216_2.jpg)

Мы также добавили специальные методы в пользовательскую модель и изменили наследование на класс User extends. ActiveRecord реализует Identityinterface, поэтому мы должны быть в состоянии найти пользователей в базе данных.
 Вы также можете скопировать модель пользователя из расширенного приложения по адресу  
<https://github.com/yiisoft/yii2-app-advanced/blob/master/common/models/User.php> .

Смотриет так же
---
Для получения дополнительной информации обратитесь к <http://www.yiiframework.com/doc-2.0/guide-security-authentiration.html>
По русски  <http://yiiframework.domain-na.me/doc/guide/2.0/ru/security-authentication> 





Использование фильтров контроллера
===
Во многих случаях нам нужно отфильтровать входящие данные или выполнить некоторые действия на основе данных. Например, с помощью пользовательских фильтров мы можем фильтровать посетителей по IP-адресу, заставлять пользователей использовать HTTPS или перенаправлять пользователя на страницу установки перед использованием приложения. 
В Yii2 фильтры по существу являются особым видом поведения, поэтому использование фильтров аналогично использованию поведений.
Yii имеет много встроенных полезных фильтров, которые включают:
* Core
* Custom
* Authentication
* Content Negotiator
* HttpCache
* PageCache
* RateLimiter
* Verb
* Cors

В этом рецепте мы реализуем следующее:
* Ограничение доступа к действию контроллера только авторизованными пользователями
* Ограничение доступа к действию контроллера указанными IP-адресами
* Ограничение доступа к определенным ролям пользователей

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html> . По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation..

2 Создайте app/components/AccessRule.php:
```php
<?php
namespace app\components;
use app\models\User;
class AccessRule extends \yii\filters\AccessRule {
    /* *
    * @inheritdoc
    */
    protected function matchRole($user)
    {
        if (empty($this->roles)) {
            return true;
        }
        $isGuest = $user->getIsGuest();
        foreach ($this->roles as $role) {
            switch($role) {
                case '?':
                    return ($isGuest) ? true : false;
                case User::ROLE_USER:
                    return (!$isGuest) ? true : false;
                case $user->identity->role: 
                    // Check if the user is logged in, and the roles match
                    return (!$isGuest) ? true : false;
                default:
                    return false;
            }
        }
        return false;
    }
}
```

3 Создайте app/controllers/AccessController.php:
```php
<?php
namespace app\controllers;
use app\models\User;
use Yii;
use yii\filters\AccessControl;
use app\components\AccessRule;
use yii\web\Controller;
class AccessController extends Controller
{
    public function behaviors()
    {
        return [
            'access' => [
                'class' => AccessControl::className(),
                // We will override the default rule config with the new AccessRule class
                'ruleConfig' => [
                    'class' => AccessRule::className(),
                ],
                'rules ' => [
                    [
                        'allow' => true,
                        'actions' => ['auth-only'],
                        'roles' => [User::ROLE_USER]
                    ],
                    [
                        'allow' => true,
                        'actions' => ['ip'],
                        'ips' => ['127.0.0.1'],
                    ],
                    [
                        'allow' => true,
                        'actions' => ['user'],
                        'roles' => [ User::ROLE_ADMIN],
                    ],
                    ['allow' => false,]
                ],
            ]
        ];
    }
    public function actionAuthOnly()
    {
        echo "Looks like you are authorized to run me.";
    }
    public function actionIp()
    {
        echo "Your IP is in our list. Lucky you!";
    }
    public function actionUser()
    {
        echo "You're the right man. Welcome!";
    }
}
```

4 Измените  User как здесь показано:
```php
<?php
namespace app\models;
class User extends \yii\base\Object implements \yii\web\IdentityInterface
{
    // add roles contstants
    CONST ROLE_USER = 200;
    CONST ROLE_ADMIN = 100;
    public $id;
    public $username;
    public $password;
    public $authKey;
    public $accessToken;
    public $role;
    private static $users = [
        '100' => [
            'id' => '100',
            'username' => 'admin',
            'password' => 'admin',
            'authKey' => 'test100key',
            'accessToken' => '100-token',
            'role' => USER::ROLE_ADMIN // add admin role for admin user
        ],
        '101' => [
            'id' => '101',
            'username' => 'demo',
            'password' => 'demo',
            'authKey' => 'test101key',
            'accessToken' => '101-token',
            'role' => USER::ROLE_USER // add user role for admin user
        ],
    ];
}
```

Как это сделать...
---

1 Чтобы использовать AccessControl, объявите его в методе behaviors() класса контроллера. Мы делаем это следующим образом:
```php
public function behaviors()
{
    return [
        'access' => [
            'class' => AccessControl::className(),
            'rules' => [
                [
                    'allow' => true,
                    'actions' => ['auth-only'],
                    ' roles' => ['@'],
                ],
                [
                    'allow' => true,
                    'actions' => ['ip'],
                    'ips' => ['127.0.0.1'],
                ],
                [
                    'allow' => true,
                    'actions' => ['user'],
                    ' roles ' => ['admin'],
                ],
                [
                    'allow' => true,
                    'actions' => ['user'],
                    'matchCallback' => function ($rule, $action) {
                        return preg_match('/MSIE 9/',$_SERVER['HTTP_USER_AGENT'])!== false;
                    }
                ],
                ['allow' => false]
            ],
        ]
    ];
}
```

2 Теперь попробуйте выполнить действия контроллера с помощью Internet Explorer и других браузерах с помощью имен пользователей admin и demo.

Как это работает...
---
Мы начнем с ограничения доступа к действию только авторизованным пользователям. См. следующий код в массив правил:
```php
[
    'allow' => true,
    'actions' => ['auth-only'],
    'roles' => [User::ROLE_USER]
],
```
Каждый массив здесь является правилом доступа. Для запрещающего правила можно использовать allow=true или allow=false. Для каждого правила существует несколько параметров.
По умолчанию Yii не запрещает все, поэтому рассмотрите возможность добавления ['allow' = > false] в конец списка правил, если вам нужна максимальная безопасность.
В нашем правиле мы используем два параметра. Первый параметр действия, который принимает массив действий, к которым будет применяться правило. Второй-параметр roles, который принимает массив ролей пользователей для определения пользователей, к которым применяется это правило.
Встроенный контроль доступа Yii2 поддерживает только две роли по умолчанию: guest (не вошедший в систему), представленный ? и авторизованный , представленный @.
С помощью простых элементов управления доступом мы можем просто ограничить доступ к определенным страницам или действиям контроллера на основе состояния входа. Если пользователи не вошли в систему при посещении этих страниц, Yii перенаправит их на страницу входа.
Правила выполняются один за другим, начиная сверху, пока не совпадет один. Если ничего не совпадает, то действие рассматривается как разрешенное.
Следующая задача-ограничить доступ к определенным IP-адресам. В этом случае используются следующие два правила доступа:
```php
[
    'allow' => true,
    'actions' => ['ip'],
    'ips' => ['127.0.0.1'],
],
```
Первое правило разрешает доступ к действию IP из списка указанных IP-адресов. В нашем случае мы используем адрес обратной связи, который всегда указывает на наш собственный компьютер. Попробуйте изменить его на 127.0.0.2, например, чтобы увидеть, как он работает, когда адрес не совпадает. Второе правило отрицает все, включая все остальные IP.
Далее мы ограничиваем доступ одной определенной ролью пользователя следующим образом:
```php
[
    'allow' => true,
    'actions' => ['user'],
    'roles' => [ User::ROLE_ADMIN],
],
```
Предыдущее правило позволяет пользователю с ролью, равной admin, запускать действие пользователя. Поэтому, если Вы войдете как администратор, он впустит вас, но если Вы войдете как демо, он не будет ничего делать.
![](img/222_1.jpg)

Мы сами переопределили стандартный класс AccessRule, который находится в файле components/AccessRule.php. Внутри нашего класса AccessRule мы сами переопределили метод matchRole, где получаем и проверяем текущую роль пользователя и сопоставляем ее с ролями из наших правил.
Наконец, нам нужно запретить доступ к определенному браузеру. Для этого рецепта мы отрицаем только Internet Explorer 9. Само правило ставится сверху, поэтому оно выполняется первым, следующим образом:
```php
[
    'allow' => true,
    'actions' => ['user'],
    'matchCallback' => function ($rule, $action) {
        return preg_match('/MSIE 9/',$_SERVER['HTTP_USER_AGENT'])!== false;
    }
],
```
Метод обнаружения, который мы используем, не очень надежен, поскольку MSIE содержится во многих других строках агента пользователя. Для получения списка возможных строк агента пользователя можно обратиться к <http://www.useragentstring.com/>
В предыдущем коде мы использовали другое свойство правила фильтра с именем 'matchCallback'. Это свойство применяется только в том случае, если функции, описанные в данном свойстве, возвращают значение true.
Наша функция проверяет, содержит ли строка агента пользователя msie 9.0 sting. В зависимости от Ваших требований, вы можете указать любой PHP код.

Смотрите так же
---
Для получения дополнительной информации об управлении доступом и фильтрах обратитесь к следующему:
* <http://www.viiframework.com/doc-2.0/guide-structure-filters.html>
 по русски  <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-filters#using-filters>
* <http://www.yiiframework.com/doc-2.0/yii-filters-accesscontrol.html>
* <http://www.yiiframework.com/doc-2.0/yii-filters-accessrnle.html>
* <https://github.com/yiisoft/yii2/hloh/master/docs/guide/structure-filters.md>
 по русски <https://github.com/yiisoft/yii2/blob/master/docs/guide-ru/structure-filters.md>
* <http://www.yiiframework.com/doc-2.0/guide-security-authorization.html#access-control-filter>
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/security-authorization#filtry-kontrola-dostupa>
8 Рецепт Использование RBAC




Предотвращение XSS
===
XSS означает межсайтовый скриптинг и представляет собой Тип уязвимости, которая позволяет внедрить клиентский скрипт (обычно JavaScript) на страницу, просматриваемую другими пользователями. Учитывая возможности клиентских сценариев, это может привести к очень серьезным последствиям, таким как обход проверок безопасности, получение учетных данных других Пользователей или утечка данных.
В этом рецепте мы увидим, как предотвратить xss, экранируя Выходные данные с помощью \yii\helpers\Html и \yii\helpers\HtmlPurifier.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Создайте controllers/XssController.php:
```php
<?php
namespace app\controllers;
use Yii;
use yii\helpers\Html;
use yii\web\Controller;
/**
* Class SiteController.
* @package app\controllers
*/
class XssController extends Controller
{
    /**
    * @return string
    */
    public function actionIndex()
    {
        $username = Yii::$app->request->get('username', 'nobody');
        return $this->renderContent(Html::tag('h1',
            'Hello, ' . $username .	'!'));
    }
}
```

3 Обычно он будет использоваться как  /xss/simple?username=Administrator. Однако, поскольку основной принцип безопасности фильтра ввода escape output не учитывался, злоумышленники смогут использовать его следующим образом:

```php
/xss/simple?username=<script>alert('XSS');</script>
```

4 Предыдущий код приведет к выполнению сценария, как показано на следующем снимке экрана:
![](img/225_1.jpg)

Как это сделать...
---
Выполните следующие действия:

1 Чтобы предотвратить предупреждение XSS, показанное на предыдущем снимке экрана, нам нужно экранировать данные escape, прежде чем передавать их в браузер. Мы делаем это следующим образом:
```php
<?php
namespace app\controllers;
use Yii;
use yii\helpers\Html;
use yii\web\Controller;
/**
* Class SiteController.
* @package app\controllers
*/
class XssController extends Controller
{
    /**
    * @return string
    */
    public function actionIndex()
    {
        $username = Yii::$app->request->get('username', 'nobody');
        return $this->renderContent(Html::tag('h1',
            Html::encode('Hello, '	. $username .	'!')
            ));
    }
}
```

2 Теперь вместо предупреждения мы получим правильно экранированный HTML, как показано на следующем снимке экрана:
![](img/226_1.jpg)

3 Поэтому основное правило-всегда экранировать все динамические данные. Например, мы должны сделать то же самое для имени ссылки :
```php
use \yii\helpers\Html;
echo Html::a(Html::encode($_GET['username']), array());
```
Вот и все. У вас есть страница, которая свободна от XSS. Теперь, что если мы хотим, чтобы некоторые HTML, чтобы пройти? Мы больше не можем использовать \yii\helpers\Html: : encode, потому что он будет отображать HTML как просто код, и нам нужно фактическое представление. К счастью, есть инструмент в комплекте с Yii, который позволяет фильтровать вредоносный HTML. Он называется HTML-Очиститель и может быть использован следующим образом:
```php
<?php
namespace app\controllers;
use Yii;
use yii\helpers\Html;
use yii\helpers\HtmlPurifier;
use yii\web\Controller;
/**
* Class SiteController.
* @package app\controllers
*/
class XssController extends Controller
{
    /**
    * @return string
    */
    public function actionIndex()
    {
        $username = Yii::$app->request->get('username', 'nobody');
        $content = Html::tag('h1', 'Hello, '. $username .'!');
        return $this->renderContent(HtmlPurifier::process($content));
    }
}
```
Теперь, если мы получаем доступ к действию HTML, используя URL-адрес ,такой как /xss/index?username=<i>username</i> < script>alert ('XSS') < / script>, HTML Очиститель удалит вредоносную часть, и мы получим следующий результат:
![](img/227_1.jpg)

Как это работает...
---

1 Внутренне, \yii\helpers\Html::encode выглядит следующим образом:
```php
public static function encode($content, $doubleEncode = true)
{
     return htmlspecialchars($content, ENT_QUOTES | ENT_SUBSTITUTE, 
     Yii::$app 
     ? Yii::$app->charset 
     : 'UTF-8'
     , $doubleEncode);
}
```

2 Таким образом, в основном, мы используем внутреннюю функцию htmlspecialchars PHP, которая довольно безопасна, если не забыть передать правильную кодировку в третьем аргументе. \yii\helpers\HtmlPurifier использует библиотеку HTML-очистителя, которая является самым передовым решением для предотвращения XSS внутри HTML. Мы использовали его конфигурацию по умолчанию, которая подходит для большинства введенного пользователем контента.

Кое что еще.
---

Есть несколько вещей, чтобы знать о xss и HTML-Очиститель; они обсуждаются в следующем разделе. Типа межсайтового скриптинга  
Существует два основных вида инъекций или xss, которые заключаются в следующем:
* Непостоянный
* Настойчивый

Первый тип-это тот, который мы использовали в рецепте и является наиболее распространенным типом XSS; его можно найти в большинстве небезопасных веб-приложений. Данные, передаваемые пользователем или через URL, нигде не хранятся, поэтому вводимый скрипт будет выполняться только один раз и только для пользователя, который его ввел. Тем не менее, это не так безопасно, как кажется. Злонамеренные пользователи могут включить XSS в ссылку на другой веб-сайт, и их ядро будет выполняться, когда другой пользователь следует по ссылке.

Второй тип гораздо серьезнее, так как данные, введенные злоумышленником, хранятся в базе данных и показываются многим, если не всем, пользователям сайта. Используя этот тип XSS, вредоносные пользователи могут буквально уничтожить ваш сайт, приказав всем пользователям удалить все данные, к которым они имеют доступ.

Смотрите так же
---

Чтобы узнать больше о XSS и о том, как с ним работать, обратитесь к следующим ресурсам:
* <http://htmlpurifier.org/docs>
* <http://ha.ckers.org/xss.html>
* <http://shiflett.org/blog/2nn7/may/character-encoding-and-xss>




Предотвращение SQL-инъекций
===
SQL injection-это тип внедрения кода, который использует уязвимость на уровне базы данных и позволяет выполнять произвольный SQL, позволяя злоумышленникам выполнять такие действия, как удаление данных или привилегии.
В этом рецепте, мы увидим примеры уязвимого кода и исправим их.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.  По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Выполните следующий SQL:
```php
DROP TABLE IF EXISTS 'user';
CREATE TABLE 'user' (
    'id' int(11) unsigned NOT NULL AUTO_INCREMENT,
    'username' varchar(100) NOT NULL,
    'password' varchar(32) NOT NULL,
    PRIMARY KEY ('id')
);

INSERT INTO 'user'('id','username','password') VALUES ('1','Alex','202cb962ac59075b964b07152d234b70');
INSERT INTO 'user'('id','username','password') VALUES ('2','Qiang','202cb962ac59075b964b07152d234b70');
```

3 Создайте пользовательскую модель с помощью Gii.

Как это сделать...
---

1 Во-первых, мы реализуем простое действие, которое проверяет правильность имени пользователя и пароля, которые пришли из URL. Создайте app/controllers/Sqlcontroller.php:
```php
<?php
namespace app\controllers;
use app\models\User;
use Yii;
use yii\base\Controller;
use yii\base\Exception;
use yii\helpers\ArrayHelper;
use yii\helpers\Html;
/**
* Class SqlController.
* @package app\controllers
*/
class SqlController extends Controller
{
    protected function renderContentByResult($result)
    {
        if ($result) {
            $content = "Success";
        } else {
            $content = "Failure";
        }
        return $this->renderContent($content);
    }
    public function actionSimple()
    {
        $userName = Yii::$app->request->get('username');
        $password = Yii::$app->request->get('password');
        $passwordHash = md5($password);
        $sql = "SELECT * FROM 'user'"
            ." WHERE 'username' = '".$userName."'"
            ." AND password = '".$passwordHash."' LIMIT |1";
        $result = Yii::$app->db->createCommand($sql)->queryOne();
        return $this->renderContentByResult($result);
    }
}
```

2 Давайте попробуем получить к нему доступ  URL /sql/simple?username=test&password=test. Поскольку мы не знаем имя пользователя, так и пароль, это будет, как и ожидалось, сбой.

3 Теперь попробуйте /sql/simple?username=%27+or+%271%27%3D%271%27%3B+--&password=whatever. На этот раз он позволяет нам войти, хотя мы все еще ничего не знаем о фактических полномочиях. Расшифрованная часть usernamevalue выглядит следующим образом:
' or '1'='1'; --

4 Закройте цитату, чтобы синтаксис оставался правильным. Добавьте или ' I ' = 'I', что делает условие всегда истинным. Используйте;--, чтобы завершить запрос и прокомментировать остальные.

5 Поскольку экранирование не было выполнено, был выполнен весь запрос:
```php
    SELECT * FROM user WHERE username = '' or '1'='1'; --' AND password ='008c5926ca861023c1d2a36653fd88e2' LIMIT 1;
```

6 Лучший способ исправить это - использовать подготовленный оператор следующим образом:
```php
public function actionPrepared()
{
    $userName = Yii::$app->request->get('username');
    $password = Yii::$app->request->get('password');
    $passwordHash = md5($password);
    $sql = "SELECT * FROM 'user'"
        ." WHERE 'username' = :username"
        ." AND password = :password LIMIT 1";
    $command = Yii::$app->db->createCommand($sql);
    $command->bindValue(':username', $userName);
    $command->bindValue(':password', $passwordHash);
    $result = $command->queryOne();
    return $this->renderContentByResult($result);
    }
```

7 Теперь проверьте /sql/prepared с теми же вредоносными параметрами. На этот раз все было хорошо, и мы получили сообщение об ошибке. Тот же принцип применяется и к ActiveRecord. Единственное отличие здесь в том, что AR использует другой синтаксис:
```php
public function actionAr()
{
    $userName = Yii::$app->request->get('username');
    $password = Yii::$app->request->get('password');
    $passwordHash = md5($password);
    $result = User::findOne([
        'username' => $userName,
        'password' => $passwordHash
        ]);
    return $this->renderContentByResult($result);
}
```

8 В предыдущем коде мы использовали параметры username и password как ключ массива со стилем значения. Если бы мы написали предыдущий код, используя только первый аргумент, он был бы уязвим:
```php
public function actionWrongAr()
{
    $userName = Yii::$app->request->get('username');
    $password = Yii::$app->request->get('password');
    $passwordHash = md5($password);
    $condition = "'username' = '".$userName." AND 'password' = '".$passwordHash."'";
    $result = User::find()->where($condition)->one();
    return $this->renderContentByResult($result);
}
```

9 При правильном использовании подготовленные операторы могут избавить вас от всех типов SQL-инъекций. Тем не менее, есть некоторые общие проблемы:
* Вы можете привязать только одно значение к одному параметру, поэтому, если вы хотите(1, 2, 3, 4), вам придется создать и привязать четыре параметра.
* Подготовленные операторы нельзя использовать для имен таблиц, столбцов и других ключевых слов.

10 При использовании ActiveRecord, первая проблема может быть решена путем добавления, где, как следует:
```php
public function actionIn()
{
    $names = ['Alex', 'Qiang'];
    $users = User::find()->where(['username' => $names])->all();
    return $this->renderContent(Html::ul(
        ArrayHelper::getColumn($users, 'username')
        ));
}
```

11 Вторая проблема может быть решена несколькими способами. Первый способ-полагаться на активную запись и PDO quoting:
```php
public function actionColumn()
{
    $attr = Yii::$app->request->get('attr');
    $value = Yii::$app->request->get('value');
    $users = User::find()->where([$attr => $value])->all();
    return $this->renderContent(Html::ul(
        ArrayHelper::getColumn($users, 'username')
        ));
}
```

12 Но самый безопасный способ - использовать подход белого списка следующим образом:
```php
public function actionWhiteList()
{
    $attr = Yii::$app->request->get('attr');
    $value = Yii::$app->request->get('value');
    $allowedAttr = ['username', 'id'];
    if (!in_array($attr, $allowedAttr)) {
        throw new Exception("Attribute specified is not allowed.");
    }
    $users = User::find()->where([$attr => $value])->all();
    return $this->renderContent(Html::ul(
        ArrayHelper::getColumn($users, 'username')
        ));
}
```

Как это работает...
---
Главная цель для предотвращения SQL-инъекции-это правильный фильтр на входе. Во всех случаях, кроме имен таблиц, мы использовали подготовленные операторы—функцию, поддерживаемую большинством серверов реляционных баз данных.
Они позволяют создавать операторы один раз, а затем использовать их несколько раз, и они обеспечивают безопасный способ привязки значений параметров.
В Yii можно использовать подготовленные операторы как для Active Record, так и для DAO. При использовании DAO, это может быть достигнуто с помощью bindValue или bindParam. Последнее полезно, когда мы хотим выполнить несколько запросов одного типа при изменении значений параметров:
```php
public function actionBind()
{
    $userName = 'Alex';
    $passwordHash = md5('password1');
    $sql = "INSERT INTO 'user' ('username', 'password') VALUES (:username, :password);";
    // insert first user
    $command = Yii::$app->db->createCommand($sql);
    $command->bindParam('username', $userName);
    $command->bindParam('password', $passwordHash);
    $command->execute();
    // insert second user
    $userName = 'Qiang';
    $passwordHash = md5('password2');
    $command->execute();
    return $this->renderContent(Html::ul(
        ArrayHelper::getColumn(User::find()->all(),	'username')
```




Предотвращения csrf атак
===
CSRF-это аббревиатура для подделки межсайтовых запросов, где злонамеренный пользователь обманывает браузер пользователя, чтобы он молча выполнял HTTP-запрос на веб-сайт, когда пользователь вошел в систему.
Примером такой атаки является вставка невидимого тега изображения с src, указывающим на пример http://example.com/site/logout. Даже если тег изображения вставлен в другой веб-сайт, вы сразу же выйдете из example.com. Последствия CSRF могут быть очень серьезными: уничтожение данных сайта, предотвращение всех пользователей сайта от входа в систему, подвергая частные данные, и так далее.

Некоторые факты о CSRF:

• Поскольку CSRF должен выполняться браузером пользователя-жертвы, злоумышленник обычно не может изменить отправленные заголовки HTTP. Тем не менее, существуют уязвимости как браузера, так и плагина Flash, которые позволяют пользователям подделывать заголовки, поэтому мы не должны полагаться на них.

• Злоумышленник должен передать те же параметры и значения, что и обычно пользователь.
Учитывая это, хорошим методом работы с CSRF является передача и проверка уникального маркера во время отправки формы и, кроме того, использование GET в соответствии со спецификацией HTTP.
Yii включает в себя встроенную генерацию токенов и проверку токенов. Кроме того, он может автоматизировать вставку маркера в HTML-формы.
Во избежание CSRF, вы должны всегда:

•  Следуйте cпецификаци HTTP, то есть GET не должен изменять  состояние приложения

• Держать в Yii защиту от csrf включеной

В этом рецепте мы увидим, как убедиться, что наше приложение устойчиво к CSRF.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать...
---

1 Для того, чтобы включить анти-CSRF защиту, мы должны добавить в config/main.php следующее:
```php
'components' => [
    request => [
        'enableCsrfValidation => true,
    ].
],
```

2 Параметр enableCsrfvalidation по умолчанию равен true. Когда проверка CSRF включена, формы, отправленные в веб-приложение Yii, должны исходить из одного и того же приложения. В противном случае возникнет исключение 400 HTTP.
Обратите внимание, что эта функция требует, чтобы пользователь клиент принимал куки

3 После настройки приложения следует использовать ActiveForm::beginForm и ActiveForm::endForm вместо тегов HTML-форм в представлении ActiveForm:
```php
<?php $form = ActiveForm::begin(['id' => 'login-form']); ?>
    <input type='text' name='name'
<?php ActiveForm::end(); ?>
```

4 Или вручную:
```php
<form action='#' method='POST'>
    <input type="hidden" name="<?= Yii::$app->request->csrfParam ?>" value="<?
    =Yii::$app->request->getCsrfToken()?>" />
</form>
```

5 В первом случае Yii автоматически добавляет скрытое поле маркера следующим образом:
```php
<form action="/csrf/create" method="post">
<div style="display:none"><input type="hidden" value="e4d1021e79ac269e8d6289043a7a8bc154d7115a" name="YII_CSRF_TOKEN" />
```

6 Если вы сохраните эту форму как HTML и попытаетесь отправить ее, Вы получите сообщение, подобное показанному на следующем снимке экрана, вместо обычной обработки данных:

Как это работает...
---
Внутренне, во время рендеринга формы, у нас есть такой код:
```php
if ($request->enableCsrfValidation && !strcasecmp($method, 'post')) {
    $hiddenInputs[] = static::hiddenInput($request->csrfParam, $request->getCsrfToken());
}
if (!empty($hiddenInputs)) {
    $form .= "\n" . implode("\n", $hiddenInputs);
}
```

В предыдущем коде getcsrfToken() создает уникальное значение токена и записывает его в файл cookie. Затем при последующих запросах сравниваются значения cookie и POST. Если они не совпадают, вместо обычной обработки данных отображается сообщение об ошибке.
Если Вам необходимо выполнить Post запрос, но не хотите создать форму, используя метод CHtml, то вы можете передать параметр с именем из Yii::app()->request->csrfParam и значение из Yii::$app->request->getCsrfToken().

Кое что еще.
---
Давайте посмотрим на некоторые дополнительные функции.

***Отключение csrf-токенов для всех действий***

1 Если у вас возникли проблемы с enableCsrfvalidation вы можете отключить его.

2 Чтобы отключить CSRF, добавьте этот код в контроллер:

```php
public function beforeAction($action) {
    $this->enableCsrfValidation = false;
    return parent::beforeAction($action);
}
```

***Отключение csrf-токенов для определенного действия***
```php
public function beforeAction($action) {
    $this->enableCsrfValidation = ($action->id !== "actionId");
    return parent::beforeAction($action);
}
```

***Проверка CSRF для Ajax-вызовов***

Когда опция enableCsrfValidation включена в основном макете, добавьте csrfMetaTags:
```php
<head>
<?= Html::csrfMetaTags() ?>
</head>
Now you will be able to simply add it to ajax-call
var csrfToken = $('meta[name="csrf-token"]').attr("content");
$.ajax({
    url: 'request'
    type: ' post',
    dataType:	' j son',
    data: {paraml: paraml, _csrf : csrfToken},
});
```

***Дополнительно [переименовать]***

Если ваше приложение требует очень высокого уровня безопасности, например, системы управления банковскими счетами, могут быть приняты дополнительные меры.
Во-первых, вы можете отключить функцию Запомнить меня с помощью config/main.php, следующим образом:
```php
'components' => [
     'user' => [
         'enableAutoLogin' => false,
     ].
],
```
Обратите внимание, что это не будет работать, если параметр enabledSession имеет значение true.
Затем можно уменьшить время ожидания сеанса следующим образом:
```php
'components' => [
    'session' => [
       'timeout' => 200,
    ],..
],
```

Устанавливает количество секунд, после которой данные будут рассматриваться как мусор и очищены.
Конечно, эти меры сделают пользовательский опыт хуже, но они добавят дополнительный уровень безопасности.

***Использование GET и POST правильно***
HTTP настаивает на том, чтобы не использовать операции GET, которые изменяют данные или состояние. Придерживаться этого правила-хорошая практика. Оно не предотвратит Все типы CSRF, но оно хотя бы снабдит некоторые впрыски, как <img src=,pointless>

Смотрите так же
---
Чтобы узнать больше о SQL-инъекциях и работе с базами данных через Yii, обратитесь к следующим URL:
* <http://en.wikipedia.org/wiki/Cross-site request forgery>
* <http://www.viiframework.com/doc-2.0/guide-securitv-best-practices.html#avoiding-csrf>
* <http://www.yiiframework.com/doc-2.0/yiL-web-rpqupst.html#$enableCsrfValidation-detail>
* Рецепт Предотвращение XSS .





Использование RBAC
===

***Role-Based Access Control (RBAC)*** обеспечивает простое, но мощное централизованное управление доступом. Самый мощный метод контроля допуска имеющийся в Yii. Это описано в руководстве, но поскольку оно довольно сложное и мощное, его не так легко понять, не попав под капот немного. 
В этом рецепте мы возьмем иерархию ролей из окончательного руководства, импортируем ее и объясним, что происходит внутри.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html> . По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Создайте базу данных MySQL и настройте ее.

3 Настройте компонент authManager в config/main.php и config/console.php следующим образом:
```php
return [
    // ...
    'components' => [
        'authManager' => [
            'class' => 'yii\rbac\DbManager',
        ],
        // ...
    ],
];
```

4 Запусти миграции:
***yii migrate --migrationPath=@yii/rbac/migrations***

Как это сделать...
---
Выполните следующие действия:

1 Создайте правило доступа rbac/AuthorRule.РНР:
```php
<?php
namespace app\rbac;
use yii\rbac\Rule;
/**
* Class AuthorRule.
* @package app\rbac
*/
class AuthorRule extends Rule
{
    public $name = 'isAuthor';
    /**
    * @param int|string $user
    * @param \yii\rbac\Item $item
    * @param array $params
    *
    * @return bool
    */
    public function execute($user, $item, $params)
    {
        return isset($params['post']) ? $params['post']->createdBy == $user : false;
    }
}
```

2 Создайте консольную команду command/RbacController.php, для инициализации команды RBAC rules:
```php
<?php
namespace app\commands;
use app\models\User;
use Yii;
use yii\console\Controller;
/**
* Class RbacController.
* @package app\commands
*/
class RbacController extends Controller
{
    public function actionInit()
    {
        $auth = Yii::$app->authManager;
        $createPost = $auth->createPermission('createPost');
        $createPost->description = 'Create a post';
        $updatePost = $auth->createPermission('updatePost');
        $updatePost->description = 'Update a post';
        $updatePost = $auth->createPermission('updatePost');
        $updatePost->description = 'Update a post';
        $deletePost = $auth->createPermission('deletePost');
        $deletePost->description = 'Delete a post';
        $readPost = $auth->createPermission('readPost');
        $readPost->description = 'Read a post';
        $authorRule = new \app\rbac\AuthorRule();
        // add permissions
        $auth->add($createPost);
        $auth->add($updatePost);
        $auth->add($deletePost);
        $auth->add($readPost);
        $auth->add($authorRule);
        // add the "updateOwnPost" permission and associate the rule with it.
        $updateOwnPost = $auth->createPermission('updateOwnPost');
        $updateOwnPost->description = 'Update own post';
        $updateOwnPost->ruleName = $authorRule->name;
        $auth->add($updateOwnPost);
        $auth->addChild($updateOwnPost, $updatePost);
        // create Author role
        $author = $auth->createRole('author');
        $auth->add($author);
        $auth->addChild($author, $createPost);
        $auth->addChild($author, $updateOwnPost);
        $auth->addChild($author, $readPost);
        // create Admin role
        $admin = $auth->createRole('admin');
        $auth->add($admin);
        $auth->addChild($admin, $updatePost);
        $auth->addChild($admin, $deletePost);
        $auth->addChild($admin, $author);
        // assign roles
        $auth->assign($admin, User::findByUsername('admin')->id);
        $auth->assign($author, User: : findByUsername('demo')->id);
        echo "Done!\n";
    }
}
```

3 Вот и все. Запустите его в консоли:

***yii rbac/init***

4 Создание controllers/RbacController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\User;
use stdClass;
use Yii;
use yii\filters\AccessControl;
use yii\helpers\Html;
use yii\web\Controller;
/**
* Class RbacController.
*/
class RbacController extends Controller
{
    public function behaviors()
    {
    return [
        'access' => [
            'class' => AccessControl::className(),
            'rules' => [
                [
                    'allow' => true,
                    'actions' => ['delete'],
                    'roles' => ['deletePost'],
                ],
                [
                    'allow' => true,
                    'actions' => ['test'],
                ],
            ],
        ],
    ];
}

    public function actionDelete()
    {
        return $this->renderContent(Html::tag('h1', 'Post deleted.'));
    }
    /**
    * @param $description
    * @param $rule
    * @param array $params
    *
    * @return string
    */
    protected function renderAccess($description, $rule, $params = [])
    {
        $access = Yii::$app->user->can($rule, $params);
        return $description.': '.($access ? 'yes' :	'no');
    }
    public function actionTest()
    {
        $post = new stdClass();
        $post->createdBy = User::findByUsername('demo')->id;
        return $this->renderContent(
            Html::tag('h1', 'Current permissions').
            Html::ul([
                $this->renderAccess('Use can create post', 'createPost'),
                $this->renderAccess('Use can read post', 'readPost'),
                $this->renderAccess('Use can update post', 'updatePost'),
                $this->renderAccess('Use can own update post', 'updateOwnPost', [
                    'post' => $post,
                ]),
                $this->renderAccess('Use can delete post', 'deletePost'),
            ])
        );
    }
}
```

5 Теперь запустите rbac/test один раз, чтобы проверить доступ ко всем созданным разрешениям иерархии RBAC: 
![](img/242_1.jpg)

6 Затем попробуйте войти как demo (пароль demo) и снова запустите rbac/test:
![](img/243_1.jpg)

7 Затем попробуйте войти как admin (пароль admin) и снова запустить rbac/test:
![](img/243_2.jpg)

8. Войдите как демо-пользователь и запустите rbac/delete:
![](img/244_1.jpg)

9. Войдите как администратор и запустите rbac/delete:
![](img/244_2.jpg)

Как это работает...
---
Yii реализует иерархию ролей в соответствии с ролей NIST RBAC. Она обеспечивает управление доступом на основе ролей функциональность через компонент authManagerapplication.
Иерархия RBAC представляет собой ориентированный ациклический граф, то есть набор узлов и их направленных соединений или ребер. Доступны три типа узлов: роли, разрешения и правила.
Роль представляет собой набор разрешений (например, создание и обновление записей). Роль может быть назначена одному или нескольким пользователям. Чтобы проверить, имеет ли пользователь указанное разрешение, мы можем проверить, назначена ли ему роль, содержащая это разрешение.
Роли и разрешения могут быть организованы в иерархию. В частности, роль может состоять из других ролей или разрешений, а разрешение может состоять из других разрешений. Yii реализует иерархию частичного порядка, которая включает в себя более специальную иерархию дерева. Хотя роль может содержать разрешение,она не соответствует действительности.
Для тестирования разрешений мы создали два действия. Первое действие test содержит средства проверки созданных разрешений и ролей. Второе действие-удалить, которое ограничено через фильтр доступа. Правило для фильтра доступа содержит следующий код:
```php
[
    'allow' => true,
    'actions' => ['delete'],
    'roles' => ['deletePost'],
],
```
Это означает, что мы разрешаем всем пользователям, имеющим разрешение deletePost, запускать действие deletePost. Yii начинает проверку с разрешения deletePost. Помимо того, что элемент правила доступа называется ролями, можно указать узел иерархии RBAC, будь то роль, правило или разрешение. Проверка updatePost является сложной:
```php
Yii::$app->user->can('updatePost', ['post' => $post]);
```
Мы используем второй параметр для передачи сообщения (в нашем случае мы смоделировали его с помощью stdclass). Если пользователь вошел в систему как demo, то для получения доступа нам нужно перейти от updatePost к author. Если вам повезет, вам нужно только пройти updatePost, updateOwnPost и author.
Поскольку updateOwnPost имеет определенное правило, он будет запущен с параметром, переданным checkAccess. Если результат равен true, то доступ будет предоставлен. Поскольку Yii не знает, что такое самый короткий путь, он пытается проверить все возможности, пока он не будет успешным, или не останется никаких альтернатив.

Кое что еще...
---
Есть несколько полезных трюков, которые помогут вам эффективно использовать RBAC, которые обсуждаются в следующих подразделах.

***Простая и эффективная иерархия***

Следуйте этим рекомендациям, где это возможно, чтобы максимизировать производительность и уменьшить сложность иерархии:
* Избегайте использования нескольких ролей одному пользователю
* Не подключайте узлы одного типа; например, избегайте подключения одной задачи к другой

***Именование ролей узлов***

Сложная иерархия становится трудной для понимания без использования какого-либо соглашения об именах. Одна из возможных конвенций, которая помогает ограничить путаницу, заключается в следующем:
[group_][own_]entity_action
Где own используется, когда правило определяет возможность изменения элемента только в том случае, если текущий пользователь является владельцем элемента, а группа-просто пространством имен. В сущности имя сущности, мы работаем  и действие, которые мы совершаем.
Например, если нам нужно создать правило, которое определяет, может ли пользователь удалить запись в блоге, мы назовем его blog_post_delete. Если правило определяет, может ли пользователь редактировать свой собственный комментарий блога, имя будет blog_own_comment_edit.

Смотрите так же
---
Чтобы узнать больше о SQL-инъекциях и работе с базами данных через Yii, обратитесь к следующему:
* <http://csrc.nist.gov/rbac/sandhu-ferraiolo-kuhn-00.pdf>
* <http://en.wikipedia.org/wiki/Role-based access control>
* <http://en.wikipedia.org/wiki/Directed acyclic graph>
* <https://www.yiiframework.com/doc/guide/2.0/en/security-authorization#rbac>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/security-authorization#kontrol-dostupa-na-osnove-rolej-rbac> 
* Рецепт Использование пользовательского фильтра





Шифрование / расшифровка данных
===
Платформа Yii2 содержит специальный компонент безопасности, который предоставляет набор методов для обработки общих задач, связанных с безопасностью. В \yii\base\security требует расширение openssl PHP вместо mcrypt.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Настройте подключение к базе данных и создайте таблицу с именем order следующим образом:
```php
DROP TABLE IF EXISTS 'order';
CREATE TABLE IF NOT EXISTS 'order' (
    'id' INT(10) UNSIGNED NOT NULL AUTO_INCREMENT,
    'client' VARCHAR(255) NOT NULL,
    'total' FLOAT NOT NULL,
    'encrypted_field' BLOB NOT NULL,
    PRIMARY KEY ('id')
);
```

3 Создайте модель Order с помощью Gii.

Как это сделать...
---
1 Добавьте дополнительный параметр ключа в config/params.php, следующим образом:
```php
<?php
return [
    'adminEmail' => 'admin@example.com',
    'key' => 'mysecretkey'
];
```

2 Добавьте поведения и вспомогательные свойства в модель Order следующим образом:
```php
public $encrypted_field_temp;
public function behaviors()
{
    return [
        [
            'class' => AttributeBehavior::className(),
            'attributes' => [
                ActiveRecord::EVENT_BEFORE_INSERT => 'encrypted_field',
                ActiveRecord::EVENT_BEFORE_UPDATE => 'encrypted_field',
            ],
            'value' => function ($event) {
                $event->sender->encrypted_field_temp = $event->sender->encrypted_field;
                return Yii::$app->security->encryptByKey( $event->sender->encrypted_field,Yii::$app->params['key']);
            },
        ],
        [
            'class' => AttributeBehavior::className(),
            'attributes' => [
            ActiveRecord::EVENT_AFTER_INSERT => 'encrypted_field',
            ActiveRecord::EVENT_AFTER_UPDATE => 'encrypted_field',
        ],
        'value' => function ($event) {
                return $event->sender->encrypted_field_temp;
            },
        ],
        [
            'class' => AttributeBehavior::className(),
            'attributes' => [
            ActiveRecord::EVENT_AFTER_FIND => 'encrypted_field',
        ],
        'value' => function ($event) {
            return Yii::$app
            ->security
            ->decryptByKey($event
                ->sender
                ->encrypted_field, Yii::$app->params['key']
                );
            },
        ],
    ];
}
```

3 Добавить controllers/CryptoController.php:
```php
<?php
namespace app\controllers;
use app\models\Order;
use Yii;
use yii\db\Query;
use yii\helpers\ArrayHelper;
use yii\helpers\Html;
use yii\helpers\VarDumper;
use yii\web\Controller;
/**
* Class CryptoController.
* @package app\controllers
*/
class CryptoController extends Controller
{
    public function actionTest()
    {
        $newOrder = new Order();
        $newOrder->client = "Alex";
        $newOrder->total = 100;
        $newOrder->encrypted_field = 'very-secret-info';
        $newOrder->save();
        $findOrder = Order::findOne($newOrder->id);
            return $this->renderContent(Html::ul([
                'New model: '. VarDumper::dumpAsString($newOrder->attributes),
                'Find model: '. VarDumper::dumpAsString($findOrder->attributes)
                ]));
    }
    public function actionRaw()
    {
        $row = (new Query())->from('order')
            ->where(['client' => 'Alex'])
            ->one();
            return $this->renderContent(Html::ul($row));
    }
}
```

4. Запустите crypto/test и вы получите следующее:
![](img/249_1.jpg)

 5. Для просмотра необработанных данных запустите crypto/raw:
![](img/249_2.jpg)

Как это работает...
---
Во-первых, мы добавили AttributeBehavior, который автоматически обрабатывает наши данные, когда происходят определенные события. Наши определенные события ActiveRecord: : EVENT_AFTER_INSERT,
ActiveRecord::EVENT_AFTER_UPDATE and ActiveRecord::EVENT_AFTER_FIND.
Во время событий вставки и обновления мы расшифровываем наши данные специальным методом: Yii:: $app ->security ->encryptByKey();. Этот метод использует HKDF и случайную соль для расшифровки наших данных перед их сохранением в базе данных. После получения данных из базы данных мы можем также использовать ActiveRecord:: EVENT_AFTER_FIND метод расшифровки наших данных. В этом случае мы также используем специальный метод Yii2 Yii:: $app ->security ->encryptByKey(); .Этот метод принимает два параметра: зашифрованные данные и ключ. 

Это еще не все... 
---
Помимо шифрования данных и расшифровки данных, безопасный компонент также обеспечивает вывод ключей с использованием стандартных алгоритмов, предотвращение подделки данных и проверку пароля.

***Работа с паролями***

Проверка пароля:
```php
if (Yii::$app->getSecurity()->validatePassword($password, $hash)) {
 // all good, logging user in
} else {
 // wrong password
}
```
Смотрите так же
---
Чтобы узнать больше о, обратитесь к <http://www.yiiframework.com/doc-2.0/guide-security-passwords.html>
По русски  <http://yiiframework.domain-na.me/doc/guide/2.0/ru/security-passwords>





Ãëàâà 6. Âåá-Ñëóæáû RESTful
===
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:

* Ñîçäàíèå ñåðâåðà îñòàëüíûå 
* Èäåíòèôèêàöèÿ
* Îãðàíè÷åíèå ñêîðîñòè
* Óïðàâëåíèå âåðñèÿìè
* Îáðàáîòêà îøèáîê

Ââåäåíèå
===
Ýòà ãëàâà ïîìîæåò âàì óçíàòü íåêîòîðûå ïîëåçíûå âåùè î yii URL ìàðøðóòèçàòîð, êîíòðîëëåðû è ïðåäñòàâëåíèÿ. Âû ñìîæåòå ñäåëàòü âàøè êîíòðîëëåðû è ïðåäñòàâëåíèÿ áîëåå ãèáêèìè.




Создание REST server
===
В следующем рецепте мы используем пример, который иллюстрирует, как можно создать и настроить RESTful API с минимальными усилиями по кодированию. Этот рецепт будет повторно использован в других рецептах в этой главе.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>.  По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Создайте миграцию для создания таблицы статей с помощью следующей команды:

***./yii migrate/create create_film_table***

3 Затем обновите только что созданный метод миграции с помощью следующего кода:
```php
public function up()
{
    $tableOptions = null;
    if ($this->db->driverName === 'mysql') {
        $tableOptions = 'CHARACTER SET utf8 COLLATE
        utf8_general_ci ENGINE=InnoDB';
    }
    $this->createTable('{{%film}}',
        [
            'id' => $this->primaryKey(),
            'title' => $this->string(64)->notNull(),
            'release_year' => $this->integer(4)->notNull(),
        ], $tableOptions);
    $this->batchInsert('{{%film}}',
        ['id','title','release_year'],
        [
            [1, 'Interstellar', 2014],
            [2, "Harry Potter and the Philosopher's Stone",2001],
            [3, 'Back to the Future', 1985],
            [4, 'Blade Runner', 1982],
            [5, 'Dallas Buyers Club', 2013],
        ]);
}
```
Обновление метод со следующим кодом:
```php
public function down()
{
    $this->dropTable('film');
}
```

4 Запустите созданную миграцию create_film_table.

5 Создать модель Film модулем GII.

6 Настройте сервер приложений на использование чистых URL-адресов. Если вы используете Apache с mod_rewrite и allowoverride включен, то вы должны добавить следующие строки в  файл .htaccess в каталоге @web:
```php
Options +FollowSymLinks
IndexIgnore */*
RewriteEngine on
# if a directory or a file exists, use it directly
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
# otherwise forward it to index.php
RewriteRule . index.php
```

Как это сделать...
---

1 Создать контроллер, @app/controller/FilmController.php, со следующим кодом:
```php
<?php
namespace app\controllers;
use yii\rest\ActiveController;
class FilmController extends ActiveController
{
    public $modelClass = 'app\models\Film';
}
```

2 Обновите @app/config/web.php. Добавьте следующую конфигурацию компонента urlManager:
```php
'urlManager' => [
    'enablePrettyUrl' => true,
    'enableStrictParsing' => true,
    'showScriptName' => false,
    'rules' => [
        ['class' => 'yii\rest\UrlRule', 'controller' => 'films'],
    ],
],
```

3 Перенастройте компонент запроса в @app/config/web.php:
```php
'request' => [
    'cookieValidationKey' => 'mySecretKey',
    'parsers' => [
        'application/json' => 'yii\web\JsonParser',
    ],
]
```

Как это работает…
---
Мы раширяем \yii\rest\ActiveController, чтобы создать наш собственный контроллер, затем для созданных контроллер, свойства modelClass был установлен. Класс \yii\rest\ActiveController реализует общий набор действий для поддержки RESTful-доступа к ActiveRecord.
С вышеуказанным минимальным количеством усилий вы уже закончили создание RESTful API для доступа к данным Film.
Созданные API включают:

* GET /films: В этом списке все фильмы страница за страницей
* HEAD /films: Это показывает обзорную информацию о списке фильмов
* POST /films: Это создает новый фильм
* GET /films/5: Это возвращает детали фильма 5
* HEAD /films/5: Это показывает обзорную информацию фильма 5
* PATCH /films/5 and PUT /films/5: Это обновление фильм 5
* DELETE /films/5: Это удаляет фильм 5
* OPTIONS /films: Это показывает Поддерживаемые команды относительно конечной точки /films
* OPTIONS /films/5: Это показывает Поддерживаемые команды относительно конечной точки /films/5

Это работает так, потому что \yii\rest\ActiveController поддерживает следующие действия:

* index: Здесь перечислены модели
* view: Возвращает сведения о модели
* create: Это создает новую модель
* update: Это обновляет существующую модель
* delete: Это приведет к удалению существующей модели
* options: Возвращает методы HTTP

И есть также метод verbs (), который определяет разрешенные методы запроса для каждого действия.
Чтобы убедиться, что наш RESTful API работает корректно, отправим несколько запросов.
Начнем с запроса GET. Запустите это в консоли:

***curl -i -H "Accept:application/json" "http://yii-book.app/films"**

Вы получите следующий вывод:
```php
HTTP/1.1 200 OK
Date: Wed, 23 Sep 2015 17:46:35 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
X-Pagination-Total-Count: 5
X-Pagination-Page-Count: 1
X-Pagination-Current-Page: 1
X-Pagination-Per-Page: 20
Link: <http://yii-book.app/films?page=1>; rel=self
Content-Length: 301
Content-Type: application/json; charset=UTF-8
[{"id":1,"title":"Interstellar","release_year":2014},{"id":2,"title":"Harry Potter and
the Philosopher's Stone","release_year":2001},{"id":3,"title":"Back to the
Future","release_year":1985},{"id":4,"title":"Blade Runner","release_year":1982},
{"id":5,"title":"Dallas Buyers Club","release_year":2013}]
```
Давайте отправим запрос POST. Запустите это в консоли:

***curl -i -H "Accept:application/json" -X POST -d title="New film" -d release_year=2015 "http://yii-book.app/films"***

```php
Вы получите следующий вывод:
HTTP/1.1 201 Created
Date: Wed, 23 Sep 2015 17:48:06 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Location: http://yii-book.app/films/6
Content-Length: 49
Content-Type: application/json; charset=UTF-8
{"title":"New film","release_year":"2015", "id":6}
```
Давайте создадим фильм. Запустите в консоли:

***curl -i -H "Accept:application/json" "http://yii-book.app/films/6"***

```php
Вы получите следующий вывод:
HTTP/1.1 200 OK
Date: Wed, 23 Sep 2015 17:48:36 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Content-Length: 47
Content-Type: application/json; charset=UTF-8
{"id":6, "title":"New film", "release_year":2015}
```
Давайте отправим запрос на удаление. Запустите это в консоли:

***curl -i -H "Accept:application/json" -X DELETE "http://yii-book.app/films/6"***

И вы получите следующий результат:
```php
HTTP/1.1 204 No Content
Date: Wed, 23 Sep 2015 17:48:55 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Content-Length: 0
Content-Type: application/json; charset=UTF-8
```

Кое что еще...
---
Теперь мы рассмотрим согласование контента и настройку правила rest URL:

***Согласование содержания***

Вы также можете легко отформатировать  ответ поведением согласования Контента.
Например, можно поместить этот код в контроллер, и все данные будут возвращены в формате XML.
Ознакомьтесь с полным списком форматов в документации.
```php
use yii\web\Response;
public function behaviors()
{
    $behaviors = parent::behaviors();
    $behaviors['contentNegotiator']['formats']['application/xml']= Response::FORMAT_XML;
    return $behaviors;
}
```
Запустите это в консоли:

***curl -i -H "Accept:application/xml" "http://yii-book.app/films"***


Вы получите следующий вывод:
```php
HTTP/1.1 200 OK
Date: Wed, 23 Sep 2015 18:02:47 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
X-Pagination-Total-Count: 5
X-Pagination-Page-Count: 1
X-Pagination-Current-Page: 1
X-Pagination-Per-Page: 20
Link: <http://yii-book.app/films?page=1>; rel=self
Content-Length: 516
Content-Type: application/xml; charset=UTF-8
<?xml version="1.0" encoding="UTF-8"?>
<response>
<item>
    <id>1</id>
    <title>Interstellar</title>
    <release_year>2014
    </release_year>
</item>
<item>
    <id>2</id>
    <title>Harry Potter and the Philosopher's Stone</title>
    <release_year>2001
    </release_year>
</item>
<item>
    <id>3</id>
    <title>Back to the Future</title>
    <release_year>1985
    </release_year>
</item>
<item>
    <id>4</id>
    <title>Blade Runner</title>
    <release_year>1982
    </release_year>
</item>
<item>
    <id>5</id>
    <title>Dallas Buyers Club</title>
    <release_year>2013
    </release_year>
</item>
</response>
```

***Настройка остальных правил***

Вы должны помнить, что идентификатор контроллера, по умолчанию, определяется во множественном числе. Это происходит потому, что в yii\rest\UrlRule автоматически в форму множественного идентификаторов контроллера. Вы можете просто отключить это, установив yii\rest\UrlRule::$pluralize в false:
```php
'urlManager' => [
    //..
    'rules' => [
        [
            'class' => 'yii\rest\UrlRule',
            'controller' => 'film'
            'pluralize' => false
        ],
    ],
    //..
]
```
Если вы хотите указать как ID контроллера должен присутствовать в модели, вы можете добавить Пользовательское имя массива как значение ключа пары, где массив ключ-ID контроллера и массив значений-это фактический контроллер ID. Например:
```php
'urlManager' => [
    //. .
    'rules' => [
        [
            'class' => 'yii\rest\UrlRule',
            'controller' => ['super-films' => 'film']
        ],
    ],
    //..
]
```

Смотрите так же
---
Для получения дополнительной информации, обратитесь к следующему адресу:
* <http://www.viiframework.com/doc-2.0/guide-rest-quick-starr.hrml>
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/rest-quick-start>
* <http://www.yiiframework.com/doc-2.0/yii-rest-urlrule.html>
* <http://www.yiiframework.com/doc-2.0/guide-rest-response-formatting.html>
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/rest-response-formatting>
* <http://budiirawan.com/setup-restful-api-yii2/>





Идентификация
===
В этом рецепте будет настроена модель аутентификации.

Подготовка
---
Повторите все шаги из раздела создание рецепта сервера REST в разделе Подготовка и как это сделать.

Как это сделать...
---

1 Изменить @app/controllers/FilmController следующим образом:
```php
<?php
namespace app\controllers;
use app\models\User;
use Yii;
use yii\helpers\ArrayHelper;
use yii\rest\ActiveController;
use yii\filters\auth\HttpBasicAuth;
class FilmController extends ActiveController
{
    public $modelClass = 'app\models\Film';
    public function behaviors()
    {
        return ArrayHelper::merge(parent::behaviors(),[
            'authenticator' => [
                'authMethods' => [
                    'basicAuth' => [
                        'class' =>HttpBasicAuth::className(),
                        'auth' => function ($username,$password) {
                                 $user =User::findByUsername($username);
                                 if ($user !== null && $user->validatePassword($password)){
                                    return $user;
                                 }
                                 return null;
                        },
                    ]
                ]
            ]
        ]);
    }
}
```
Откройте http://yii-book.app/films в браузере и убедитесь, что мы настраиваем обычную аутентификацию HTTP:
![](img/259_1.jpg)

Давайте попробуем аутентифицироваться. Запустите это в консоли:


***curl -i -H "Accept:application/json" "http://yii-book.app/films"***

И вы получите следующее:
```php
HTTP/1.1 401 Unauthorized
Date: Thu, 24 Sep 2015 01:01:24 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Www-Authenticate: Basic realm="api"
Content-Length: 149
Content-Type: application/json; charset=UTF-8
{"name":"Unauthorized","message":"You are requesting with an invalid
credential.","code":0,"status":401,"type":"yii\\web\\UnauthorizedHttpException"}
```
1 А ТЕПЕРЬ ПОПРОБУЙТЕ AUTH С CURL:

***curl -i -H "Accept:application/json" -u admin:admin "http://yii-book.app/films"***

2 Затем вы должны получить ответ, который выглядит так:
```php
HTTP/1.1 200 OK
Date: Thu, 24 Sep 2015 01:01:40 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Set-Cookie: PHPSESSID=8b3726040bf8850ebd07209090333103; path=/; HttpOnly
Expires: Thu, 19 Nov 1981 08:52:00 GMT
Cache-Control: no-store, no-cache, must-revalidate, post-check=0, pre-check=0
Pragma: no-cache
X-Pagination-Total-Count: 5
X-Pagination-Page-Count: 1
X-Pagination-Current-Page: 1
X-Pagination-Per-Page: 20
Link: <http://yii-book.app/films?page=1>; rel=self
Content-Length: 301
Content-Type: application/json; charset=UTF-8
[{"id":1,"title":"Interstellar","release_year":2014},{"id":2,"title":"Harry Potter
and the Philosopher's Stone","release_year":2001},{"id":3,"title":"Back to the
Future","release_year":1985},{"id":4,"title":"Blade Runner","release_year":1982},
{"id":5,"title":"Dallas Buyers Club","release_year":2013}]
```

Как это работает...
---
Мы также добавили поведение authenticator к классу HttpBasicAuth, так мы сможем проверить подлинность только логин и пароль. Можно реализовать любой метод проверки подлинности, описанный в официальном руководстве в разделе веб-службы RESTful.

Есть еще.
---
Существует несколько способов отправки маркера доступа:
* HTTP Basic Auth
* Параметр запроса
* Протокол oauth
Yii поддерживает все эти методы аутентификации.

Смотрите так же
---
Для получения дополнительной информации обратитесь к <http://www.yiiframework.com/doc-2.0/guide-rest-ratp-limiting.html>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/rest-rate-limiting> 





Ограничение скорости
==
Чтобы предотвратить злоупотребления, следует рассмотреть возможность добавления ограничения скорости к API. Например, можно ограничить использование API каждым пользователем максимум пятью вызовами API в течение одной минуты. Если в течение указанного периода времени От пользователя получено слишком много запросов, необходимо вернуть ответ с кодом состояния 429 (слишком много запросов).

Подготовка
--
Повторите все шаги, описанные в рецепте Создание рецепта REST-сервера подготовка и как это сделать... .

1 Создайте миграцию для создания таблицы разрешений пользователя с помощью следующей команды:

***./yii migrate/create create_user_allowance_table***

2 Затем обновите только что созданный метод миграции с помощью следующего кода:
```php
public function up()
{
    $tableOptions = null;
    if ($this->db->driverName === 'mysql') {
        $tableOptions = 'CHARACTER SET utf8 COLLATEutf8_general_ci ENGINE=InnoDB';
    }
    $this->createTable('{{%user_allowance}}',	[
        'user_id' => $this->primaryKey(),
        'allowed_number_requests' => $this->integer(10)->notNull(), 'last_check_time' => $this->integer(10)->notNull()
    ], $tableOptions);
}
```

3 Обновление метод Down() следующим кодом:
```php
public function down()
{
    $this->dropTable('{{%user_allowance}}');
}
```

4 Запустите созданную миграцию create_film_table.

5 Создайте  модель UserAllowance модулем GII.

Как это сделать...
---
Во-первых, вы должны обновить @app/controllers/FilmController.php следующим кодом:
```php
<?php
namespace app\controllers;
use yii\rest\ActiveController;
use yii\filters\RateLimiter;
use yii\filters\auth\QueryParamAuth;
class FilmController extends ActiveController
{
    public $modelClass = 'app\models\Film';
    public function behaviors()
    {
        $behaviors = parent::behaviors();
        $behaviors['authenticator'] = [
            'class' => QueryParamAuth::className(),
        ];
        $behaviors['rateLimiter'] = [
            'class' => RateLimiter::className(),
            'enableRateLimitHeaders' => true
        ];
        return $behaviors;
    }
}
```
Чтобы включить ограничение скорости, класс пользовательской модели должен реализовать Yii\filters\RateLimitInterface и требует реализации трех методов: getRateLimit (), loadAllowance () и saveAllowance(). Необходимо добавить их с константами RATE_LIMIT_NUMBER и RATE_LIMIT_RESET:
```php
<?php
namespace app\models;
class User extends \yii\base\Object implements \yii\web\IdentityInterface, \yii\filters\RateLimitInterface
{
    public $id;
    public $username;
    public $password;
    public $authKey;
    public $accessToken;
    const RATE_LIMIT_NUMBER = 5;
    const RATE_LIMIT_RESET = 60;
    // it means that user allowed only 5 requests per one minute
    public function getRateLimit($request, $action)
    {
        return [self::RATE_LIMIT_NUMBER,self::RATE_LIMIT_RESET];
    }
    public function loadAllowance($request, $action)
    {
        $userAllowance = UserAllowance::findOne($this->id);
        return $userAllowance 
            ? [$userAllowance->allowed_number_requests,$userAllowance->last_check_time] 
            : $this->getRateLimit($request, $action);
    }
    public function saveAllowance($request, $action,$allowance, $timestamp)
    {
         $userAllowance = ($allowanceModel =UserAllowance::findOne($this->id)) 
            ? $allowanceModel 
            : new UserAllowance();
            $userAllowance->user_id = $this->id;
            $userAllowance->last_check_time = $timestamp;
            $userAllowance->allowed_number_requests =$allowance;
            $userAllowance->save();
    }
    // other User model methods
}
```

Как это работает...
---
Как только класс identity реализует требуемый интерфейс, Yii автоматически использует [ [yii\filters\RateLimiter]], настроенный как фильтр действий для [[yii\rest\controller]] для выполнения проверки ограничения скорости. Мы также добавили поведение 'authenticator' с классом QueryParamAuth. Таким образом, теперь мы можем аутентифицироваться только с помощью маркера доступа, переданного через параметр запроса. Можно добавить любой метод проверки подлинности, описанный в официальном руководстве в разделе веб-службы RESTful.
Давайте объясним наши методы. Их довольно легко понять.

***getRateLimit()***: возвращает максимальное количество разрешенных запросов и период времени (например, [100, 600] означает, что может быть не более 100 вызовов API в течение 600 секунд)

***loadAllowance()***: возвращает количество разрешенных оставшихся запросов и соответствующую метку времени UNIX при последней проверке ограничения скорости

***saveAllowance()***: сохраняет как количество оставшихся запросов, так и текущую метку времени UNIX

Мы храним наши данные в базе данных MySQL. Для повышения производительности можно использовать базу данных NoSQL или другую систему хранения с большим временем получения и загрузки данных.
Теперь давайте попробуем проверить функцию ограничения скорости. Запустите это в консоли:

***curl -i "http://yii-book.app/films?access-token=100-token"***

Вы получите следующий вывод:
```php
HTTP/1.1 200 OK
Date: Thu, 24 Sep 2015 01:35:51 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Set-Cookie: PHPSESSID=495a928978cc732bee853b83f521eba2; path=/; HttpOnly
Expires: Thu, 19 Nov 1981 08:52:00 GMT
Cache-Control: no-store, no-cache, must-revalidate, post-check=0, pre-check=0
Pragma: no-cache
X-Rate-Limit-Limit: 5
X-Rate-Limit-Remaining: 4
X-Rate-Limit-Reset: 0
X-Pagination-Total-Count: 5
X-Pagination-Page-Count: 1
X-Pagination-Current-Page: 1
X-Pagination-Per-Page: 20
Link: <http: //yii-book.app/films?access-token=100-token&page=1>; rel=self
Content-Length: 301
Content-Type: application/json; charset=UTF-8
[{"id":1,"title":"Interstellar","release_year":2014},{"id":2,"title":"Harry Potter and
the Philosopher's Stone","release_year":2001},{"id":3,"title":"Back to the
Future","release_year":1985},{"id":4,"title":"Blade Runner","release_year":1982},
{"id":5,"title":"Dallas Buyers Club","release_year":2013}]
```
Давайте узнаем о возвращаемых заголовках. Когда ограничение частоты запросов включено, по умолчанию каждый ответ будет возващаться со следующими http-заголовками, содержащими информацию о текущих ограничениях:

***X-Rate-Limit-Limit***: Это Максимальное число запросов, разрешенных в течение определенного периода времени

***X-Rate-Limit-Remaining***: Это количество оставшихся запросов в текущем периоде времени

***X-Rate-Limit-Reset***: Это количество секунд ожидания для получения максимального количества разрешенных запросов

Таким образом, теперь попробуйте превысить предел, запросить следующий URL-адрес более пяти раз в минуту, и вы увидите TooManyRequestsHttpExeption:
```php
HTTP/1.1 429 Too Many Requests
Date: Thu, 24 Sep 2015 01:37:24 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Set-Cookie: PHPSESSID=bb630ca8a641ef92bd210c0a936e3149; path=/; HttpOnly
Expires: Thu, 19 Nov 1981 08:52:00 GMT
Cache-Control: no-store, no-cache, must-revalidate, post-check=0, pre-check=0
Pragma: no-cache
X-Rate-Limit-Limit: 5
X-Rate-Limit-Remaining: 0
X-Rate-Limit-Reset: 60
Content-Length: 131
Content-Type: application/json; charset=UTF-8
{"name":"Too Many Requests","message":"Rate limit
exceeded.","code":0,"status":429,"type":"yii\\web\\TooManyRequestsHttpException"}
```
Смотрите так же
---
Дополнительные сведения см. по следующим URL-адресам:
* <https://en.wikipedia.org/wiki/Leaky bucket>
* <http://www.yiiframework.com/doc-2.0/guide-rest-rate-limiting.html>
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/rest-rate-limiting>
* <http://www.yiiframework.com/doc-2.0/yii-filters-ratelimiter.html>




Управление версиями
===
Если вы строите свой API без версии, это ужасно. Давайте представим, что вы выталкиваете критическое изменение-в основном любое изменение, которое противоречит тому, что разработчики клиентов запланировали, например, переименование или удаление параметра или изменение формата ответа - вы рискуете сбить многие, если не все, системы Ваших клиентов, что приводит к сердитым вызовам поддержки или, что еще хуже, массовому оттоку. Вот почему вы должны поддерживать свою версию API. В Yii2 управление версиями может быть легко выполнено с помощью модулей, поэтому версии будут представлены как изолированный блок кода.

Подготовка
---
Повторите все шаги, описанные в разделе создание рецепта REST-сервера подготовка и как это сделать...

Как это сделать...
---

1 Создайте следующую структуру в папке приложения. В общей сложности, вы должны создать папку @app/modules с папками v1 и v2 внутри него. В папке каждого модуля необходимо создать папки контроллеров и модели:
```php
app/
modules/
v1/
controllers/
    FilmController.php
Module.php
v2/
controllers/
    FilmController.php
Module.php
```

2 Добавьте модули импорта в @app/config/web.php:

```php
'modules' => [
    'v1' => [
        'class' => 'app\modules\v1\Module',
    ],
    ' v2' => [
        'class' => 'app\modules\v2\Module'
    ]
],
```

3 Создайте @app/modules/v1/controllers/FilmController.php и @app/modules/v2/controllers/FilmController.php со следующим кодом:
```php
<?php
namespace app\modules\v1\controllers;
use yii\rest\ActiveController;
class FilmController extends ActiveController
{
    public $modelClass = 'app\models\Film';
}

<?php
namespace app\modules\v1\controllers;
use yii\rest\ActiveController;
class FilmController extends ActiveController
{
    public $modelClass = 'app\models\Film';
}
<?php
namespace app\modules\v1;
class Module extends \yii\base\Module
{
    public function init()
    {
        parent::init();
    }
}
<?php
namespace app\modules\v2;
class Module extends \yii\base\Module
{
    public function init()
    {
        parent::init();
    }
}
```
Создайте @app/modules/v1/Module.php и @app/modules/v2/Module.php со следующим кодом:

Как это работает...
---
Каждый модуль представляет собой независимую версию нашего API.
Теперь вы сможете указать версию API двумя способами:

1 По URL API. Можно указать версии v1 или v2. В результате http://yii-book.app/v1/film вернет список фильмов для версии 1 и http://yii-book.app/v2/film сделает это для версии 2.

2 Можно также поместить номер версии через заголовки запроса HTTP. Как обычно, это можно сделать через заголовок Accept:

```php

// as a vendor content type
Accept: application/vnd.company.myproject-v1+j son // via a parameter
Accept: application/json; version=v1
```
Итак, теперь у нас есть две версии нашего API, и мы можем легко изменить версию v2 без каких-либо головных болей. Наши старые клиенты продолжают работать с версией v1, а новые клиенты или те, кто хотел бы обновить будет использовать версию v2.

Кое что еще...
---
Для получения дополнительной информации обратитесь к:
* <http://www.yiiframework.com/doc-2.0/guide-rest-versioning.html>
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/rest-versioning>
* <http://budiirawan.com/setup-restful-api-yii2/>




Обработка ошибок
===
Иногда может потребоваться настроить Формат ответа об ошибке по умолчанию. Например, нам нужно знать метку времени ответа и успешность ответа. Фреймворки предоставляют простой способ сделать это.

Подготовка 
---
Повторите все шаги из создания рецепта сервера REST в разделе Подготовка и Как это сделать....

Как это сделать...
---
Для достижения этой цели можно ответить на событие beforeSend компонента response в @app/config/web.php, следующим образом:
```php
' response' => [
    'class' => 'yii\web\Response',
    'on beforeSend' => function ($event) {
        $response = $event->sender;
        if ($response->data !== null) {
            $response->data = [
                'success' => $response->isSuccessful,
                'timestamp' => time(),
                'path' => Yii::$app->request->getPathInfo(),
                'data' => $response->data,
            ];
        }
    },
],
```
Как это работает.
---
Чтобы узнать, что происходит в этом коде, давайте поиграем с ним. Сначала запустите это в консоли:

***curl -i "http://yii-book.app/films/1"***

Вы получите следующий вывод:
```php
HTTP/1.1 200 OK
Date: Thu, 24 Sep 2015 04:24:52 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Content-Length: 115
Content-Type: application/json; charset=UTF-8
{"success":true, "timestamp":1443068692, "path":"films/1", "data":
{"id":1,"title":"Interstellar","release_year":2014}}
```
Во-вторых, запустите это в консоли:

***curl -i "http://yii-book.app/films/1000"***

И вы получите следующее:
```php
HTTP/1.1 404 Not Found
Date: Thu, 24 Sep 2015 04:24:26 GMT
Server: Apache
X-Powered-By: PHP/5.5.23
Content-Length: 186
Content-Type: application/json; charset=UTF-8
{"success"false, "timestamp":1443068666, "path":"films/1000","data":{"name":"Not
Found","message":"Object not found:
1000","code":0,"status":404,"type":"yii\\web\\NotFoundHttpException"}}
```
Мы изменили содержимое ответа перед отправкой. Таким образом, легко определить, является ли ответ успешным или нет.

Смотрите так же
---
Для получения дополнительной информации обратитесь к <http://www.yiiframework.com/doc-2.0/guide-rest-error-handling.html>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/rest-error-handling>




Ãëàâà 7. Îôèöèàëüíûå Ðàñøèðåíèÿ
===
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:
* Ïðîâåðêà ïîäëèííîñòè êëèåíòà 
* Áèáëèîòåêà ýëåêòðîííîé ïî÷òû SwiftMailer
* Ãåíåðàòîð äàííûõ ïðèñïîñîáëåíèÿ ôàêåðà
* Ïðåäñòàâüòå áèáëèîòåêó
* Äðàéâåð MongoDB
* Àäàïòåð elasticsearch â äâèãàòåëü 
* Ãåíåðàòîð êîäà Gii
* Pjax ïëàãèí jQuery 
* Äðàéâåð áàçû äàííûõ Redis

Ââåäåíèå 
===
Îôèöèàëüíûé ðåïîçèòîðèé Yii2 ïðåäîñòàâëÿåò àäàïòåðû äëÿ íåêîòîðûõ ïîïóëÿðíûõ áèáëèîòåê, áàç äàííûõ è ïîèñêîâûõ ñèñòåì. Â ýòîé ãëàâå ìû ïîêàæåì âàì, êàê óñòàíîâèòü è èñïîëüçîâàòü îôèöèàëüíûå ðàñøèðåíèÿ â âàøåì ïðîåêòå. Âû òàêæå óçíàåòå, êàê íàïèñàòü ñîáñòâåííîå ðàñøèðåíèå è ïîäåëèòüñÿ èì ñ äðóãèìè ðàçðàáîò÷èêàìè.



Проверка подлинности клиента
===
Это расширение добавляет потребителей OpenID, OAuth и OAuth2 для платформы yii 2.0.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Установите расширение с помощью следующей команды:

***composer require yiisoft/yii2-authclient***

Как это сделать...
---
1 Откройте страницу приложения GitHub https://github.com/settings/applications и добавить свое новое приложение:
![](img/271_1.jpg)

2 Получить Client ID и Client Secret:
![](img/272_1.jpg)

3 Настройте веб-конфигурацию и задайте соответствующие параметры для компонента authClientCollection:
```php
'components' => [
    // ...
    'authClientCollection' => [
        'class' => 'yii\authclient\Collection',
        'clients' => [
            'google' => [
                'class' =>'yii\authclient\clients\GoogleOpenId'
            ],
            'github' => [
                'class' => 'yii\authclient\clients\GitHub',
                'clientId' => '87f0784aae2ac48f78a',
                'clientSecret' =>'fb5953a54dea4640f3a70d8abd96fbd25592ff18',
            ],
        // etc.
        ],
    ],
],
```

4 Откройте SiteController и добавьте автономное действие auth и метод обратного вызова успеха:
```php
use yii\authclient\ClientInterface;
public function actions()
{
    return [
        // ...
        'auth' => [
            'class' => 'yii\authclient\AuthAction',
            'successCallback' => [$this, 'onAuthSuccess'],
        ],
    ];
}
public function onAuthSuccess(ClientInterface $client)
{
    $attributes = $client->getUserAttributes(); \yii\helpers\VarDumper::dump($attributes, 10, true); exit;
}
```

5 Откройте views/site/login.php файл и вставьте виджет Authchoice:
```php
<div class="site-login">
    <h1><?= Html::encode($this->title) ?></h1>
    <div class="panel panel-default">
        <div class="panel-body">
            <?= yii\authclient\widgets\AuthChoice::widget(['baseAuthUrl' =>
                ['site/auth ' ],
                'popupMode' => false,
            ]) ?>
        </div>
    </div>
    <p>Please fill out the following fields to login:</p>
</div>
```

6 Вы увидите значки для настроенных поставщиков:
![](img/273_1.jpg)

7 Попробуйте авторизоваться у поставщика GitHub:
![](img/274_1.jpg)

8 В случае успеха ваш обратный вызов покажет атрибуты авторизованного пользователя:
```php
[
    'login' => 'Name'
    'id' => 0000000
    'avatar_url' =>'https://avatars.githubusercontent.com/u/0000000?v=3'
    'gravatar_id' => ''
    'url' => 'https://api.github.com/users/Name'
    'html_url' => 'https://github.com/Name'
    'name' => 'YourName'
    'blog' =>site.com'
    'email => mail@site.com'
]
```

9 Создайте собственный код авторизации в методе onAuthSuccess, как в примере <https://github.com/yiisoft/yii2-authclient/blob/master/docs/guide/quick-start.md>.
По русски <https://github.com/yiisoft/yii2-authclient/blob/master/docs/guide-ru/quick-start.md> 

Как это работает...
---
Расширение предоставляет клиентов OpenID, OAuth и oauth2 auth для приложения.
Виджет AuthChoice открывает страницу аутентификации на сайте выбранной службы, сохраняя действие auth
URL-адрес. После аутентификации текущая служба перенаправляет пользователей обратно при отправке данных аутентификации 
POST запрос. AuthAction получает запрос и вызывает соответствующий обратный вызов.
Вы можете использовать любой существующий клиент или создать свой собственный.

Смотрите так же
---
Для получения дополнительной информации об использовании расширений см.:
* <https://github.com/yiisoft/yii2-authclient/tree/master/docs/guide>
по русски <https://github.com/yiisoft/yii2-authclient/tree/master/docs/guide-ru>
* <http://www.yiiframework.com/doc-2.0/ext-authclient-index.html>

 Дополнительные сведения о технологиях аутентификации OpenID, OAuth и OAuth2 см. в разделе:
* <http://openid.net>
* <http://oauth.net>




Библиотека электронной почты SwiftMailer
===
Многие веб-приложения должны отправлять уведомления и подтверждать действия клиента по электронной почте по соображениям безопасности. Yii2 предоставляет обертку  yiisoft/yii2 - swiftmailer, для  библиотеки SwiftMailer.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>
Как basic, так и advances приложение содержат это расширение из коробки.

Как это сделать...
---
Теперь мы попробуем отправить любой вид электронной почты из нашего собственного приложения.
***Послание текстового сообщения***

1 Установите конфигурацию почтовой программы в файле config/console.php:
```php
'components' => [
    // ...
    'mailer' => [
        'class' => 'yii\swiftmailer\Mailer',
        'useFileTransport' => true,
    ],
    // ...
],
```

2 Создайте контроллер консольного теста, MailController, с помощью следующего кода:
```php
<?php
namespace app\commands;
use yii\console\Controller;
use Yii;
class MailController extends Controller
{
    public function actionSend()
    {
        Yii::$app->mailer->compose()
            ->setTo('to@yii-book.app')
            ->setFrom(['from@yii-book.app' => Yii::$app->name])
            ->setSubject('My Test Message')
            ->setTextBody('My Text Body')
            ->send();
    }
}
```

3 Выполните следующую команду консоли:

***php yii mail/send***

4 Проверьте каталог runtime/mail. Он должен содержать файлы с вашими письмами.

***Примечание***: файлы почты содержат сообщения в специальном   формате электронной почты , совместимый с любыми почтовым программное обеспечение. Это сообщение также можно открыть в виде обычного текста.

5 Задайте для параметра useFileTransport значение false или удалите эту строку из конфигурации:
```php
'mailer' => [
    'class' => 'yii\swiftmailer\Mailer',
],
```
Затем поместите свой реальный идентификатор электронной почты в метод setTo ():
```php
->setTo('my@real-email.com')
```

6 Снова выполните команду консоли:

***php yii mail/send***

7 Проверьте папку входящие.

***Примечание***: SwiftMailer использует стандартную функцию PHP mail () для отправки почты по умолчанию. Пожалуйста, проверьте это
Как ваш сервер настроен для отправки почты через функцию mail().
Многие почтовые системы отклоняют письма без DKIM and SPF подписей (отправленные функцией mail() например) или помещают их в папку спама.

***Отправка содержимого HTML***

1 Убедитесь, что приложение содержит сообщение mail/layouts/html.php файл и добавить в mail/layouts/text.php файл со следующим содержанием:
```php
<?php
/* @var $this \yii\web\View */
/* @var $message \yii\mail\MessageInterface */
/* @var $content string */
?>
<?php $this->beginPage() ?>
<?php $this->beginBody() ?>
<?= $content ?>
<?php $this->endBody() ?>
<?php $this->endPage() ?>
```

2 Создайте свой собственный вид в файле mail/message-html.php:
```php
<?php
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $name string */
?>
<p>Hello, <?= Html::encode($name) ?>!</p>
```
Создать mail/message-text.php файл с тем же содержимым, но без HTML тегов:
```php
<?php
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $name string */
?>
Hello, <?= Html::encode($name) ?>!
```

3 Создать контроллер консоли, Mailcontroller, с помощью следующего кода:
```php
<?php
namespace app\commands;
use yii\console\Controller;
use Yii;
class MailController extends Controller
{
    public function actionSendHtml()
    {
        $name = 'John';
        Yii::$app->mailer->compose('message-html',['name' => $name])
            ->setTo('to@yii-book.app')
            ->setFrom(['from@yii-book.app' => Yii::$app->name])
            ->setSubject('My Test Message')
            ->send();
    }
    public function actionSendCombine()
    {
        $name = 'John';
        Yii::$app->mailer->compose(
            ['html' =>'message-html', 
             'text' => 'message-text'], 
             ['name' => $name,])
            ->setTo('to@yii-book.app')
            ->setFrom(['from@yii-book.app' => Yii::$app->name])
            ->setSubject('My Test Message')
            ->send();
    }
}
```

4 Выполните следующие команды консоли:
```php
php yii mail/send-html
php yii mail/se
nd-combine
```

***Работа с транспортом SMTP***

1 Задайте параметр transport для компонента mailer следующим образом:
```php
'mailer' => [
    'class' => 'yii\swiftmailer\Mailer',
    'transport' => [
        'class' => 'Swift_SmtpTransport',
        'host' => 'smtp.gmail.com',
        'username' => 'username@gmail.com',
        'password' => 'password',
        'port' => '587',
        'encryption' => 'tls',
    ],
],
```

2 Напишите и запустите следующий код:
```php
Yii::$app->mailer->compose()
    ->setTo('to@yii-book.app')
    ->setFrom('username@gmail.com')
    ->setSubject('My Test Message')
    ->setTextBody('My Text Body')
    ->send();
````

3 Проверьте свой почтовый ящик Gmail.

***Примечание.*** Gmail автоматически переписывает поле " От " в ваш идентификатор электронной почты профиля по умолчанию, но другие системы электронной почты не делают то же самое. Всегда используйте идентичный идентификатор электронной почты в конфигурации транспорта и в методе setFrom () для передачи политик защиты от спама для других систем электронной почты.

***Прикрепление файлов и встраивание изображений***

Добавьте соответствующий метод, чтобы прикрепить любой файл к вашей почте:
```php
class MailController extends Controller
{
    public function actionSendAttach()
    {
        Yii::$app->mailer->compose()
            ->setTo('to@yii-book.app' )
            ->setFrom(['from@yii-book.app' => Yii::$app->name])
            ->setSubject('My Test Message')
            ->setTextBody('My Text Body')
            ->attach(Yii::getAlias('@app/README.md'))
            ->send();
    }
}
```
Или используйте метод embed () в файле представления электронной почты, чтобы вставить изображение в содержимое электронной почты:
```php
<img src="<?= $message->embed($imageFile); ?>">
```
Он автоматически прикрепляет файл изображения и вставляет его уникальный идентификатор.

Как это работает...
---
Обертка реализует базовый \yii\mail\MailerInterface. Его compose () метод возвращает объект сообщения (реализация \yii\mail\MessageInterface).
Вы можете вручную задать простой текст и содержимое HTML с помощью методов setTextBody () и setHtmlBody (), или вы можете передать параметры представления и представления в метод compose (). В этом случае почтовая программа вызывает метод \yii\web\view::render() для отрисовки соответствующего содержимого.
Параметр useFileTransport хранит письма в файлах вместо реальной отправки. Это полезно для локальной разработки и тестирования приложений.

Смотрите так же
----
Для получения дополнительной информации о коде расширения yii2 - swiftmailer, посетите следующие руководства:
* <http://www.yiiframework.com/doc-2.0/guide-tutorial-mailing.ht.ml>
 По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/tutorial-mailing>
* <http://www.yiiframework.com/doc-2.0/ext-swiftmailer-index.html>
 Чтобы узнать больше об исходной библиотеке swiftMailer, обратитесь к следующим URL:
* <http://swiftmailer.org/docs/introduction.html>
* <https ://github.com/swiftma iler/swiftmailer>




Faker – генератор фальшивых данных
===
Fzaninotto/faker-это библиотека PHP, которая генерирует поддельные данные многих видов: имена, телефоны, адреса, случайные строки и числа и так далее. Это может помочь Вам создать много рандомизированных записей для тестирования производительности и логики. Вы можете расширить свою коллекцию поддерживаемых типов, написав собственные модули форматирования и генераторы.
В скелетах приложения Yii2 оболочка yiisoft / yii2-faker включена в раздел require-dev файла composer.json, который используется для тестирования кода (Глава 11, тестирование). Эта оболочка предоставляет консоль FixtureController для использования в консольном приложении и тестовой среде.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать...
----

1 Откройте каталог tests/codeception/templates и добавьте файл шаблона fixture, users.txt:
```php
<?php
/**
* @var $faker \Faker\Generator
* @var $index integer
*/
return [
    'name' => $faker->firstName,
    'phone' => $faker->phoneNumber,
    'city' => $faker->city,
    'about' => $faker->sentence(7, true),
    'password' => Yii::$app->getSecurity() ->generatePasswordHash('password_' . $index),
    'auth_key' => Yii::$app->getSecurity() ->generateRandomString(),
];
```

2 В консоли  yii выполните команду test:

***php tests/codeception/bin/yii fixture/generate users --count=2***

3 Подтвердите  создания миграции.

4 Убедитесь, что каталог tests/codeception/fixtures содержит новый users.php, с созданными автоматически данными:
```php
return [
    [
        'name' => 'Isadore ',
        'phone' => '952.877.8545x190',
        'city' => 'New Marvinburgh',
        'about' => 'Ut quidem voluptatem itaque veniam voluptas dolores.',
        'password' =>'$2y$13$Fi3LOl/sKlomUH.DLgqBkOB/uCLmgCoPPL1KXiW0hffnkrdkjCzAC',
        'auth_key' => '1m05hlgaAG8zfm0cyDyoRGMkbQ9W6hj1',
    ],
    [
        'name' => 'Raleigh',
        'phone' => '1-655-488-3585x699',
        'city' => 'Reedstad',
        'about' => 'Dolorem quae impedit tempore libero doloribus nobis dicta tempora facere.',
        'password' =>'$2y$13$U7Qte5Y1jVLrx/pnhwdwt.1uXDegGXuNVzEQyUsb65WkBtjyjUuYm',
        'auth_key' => 'uWWJDgy5jNRk6KjqpxS5JuPv0OHearqE',
    ],
],
```

***Работа с собственными типами данных***

1 Создайте собственного поставщика с логикой создания настраиваемых значений:
```php
<?php
namespace tests\codeception\faker\providers;
use Faker\Provider\Base;
class UserStatus extends Base
{
    public function userStatus()
    {
        return $this->randomElement([0, 10, 20, 30]);
    }
}
```

2 Добавить поставщика в список поставщиков услуг в интернет /tests/codeception/config/config.php:
```php
return [
    'controllerMap' => [
        'fixture' => [
            'class' => 'yii\faker\FixtureController',
            'fixtureDataPath' => '@tests/codeception/fixtures',
            'templatePath' => '@tests/codeception/templates',
            'namespace' => 'tests\codeception\fixtures',
            'providers' => [
                'tests\codeception\faker\providers\UserStatus',
            ],
        ],
    ],
    // ...
];
```

3 Добавьте поле статус в файл шаблона fixture:
```php
<?php
/**
* @var $faker \Faker\Generator
* @var $index integer
*/
return [
    'name' => $faker->firstName,
    'status' => $faker->userStatus,
];
```

4 Регенерация fixtures с помощью команды консоли:

***php tests/codeception/bin/yii fixture/generate users --count=2***

5 Проверьте, что сгенерированный код в fixtures/users.php файл содержит ваши пользовательские значения:
```php
return [
    [
        'name' => 'Christelle',
        'status' => 30,
    ],
    [
        'name' => 'Theo',
        'status' => 10,
    ],
];
```

Как это работает...
---

Расширение yii2-faker содержит консольный генератор (который использует ваши шаблоны для создания файлов данных fixture) и дает вам подготовленный экземпляр исходного объекта Faker. Можно создать все или определенные fixture и передать пользовательские счетчики или язык в аргументах консоли.

***Примечание***: будьте осторожны с существующими тестовыми файлами, если ваши тесты используют эти приспособления, потому что автогенерация полностью переписывает старые данные.

Смотрите так же
* Исходный код и дополнительные сведения о расширении см. в разделе:
 <https://github.com/yiisoft/yii2-faker/tree/master/docs/guide>
 <http://www.viiframework.com/doc-2.0/ext-faker-index.html>
* И чтобы узнать больше об оригинальной библиотеке, обратитесь к:
<https ://github. com/fzaninotto/Faker>
* Глава 11, Тестирование




Библиотека Imagine 
===
Imagine, библиотека ООП для обработки изображений. Он позволяет обрезать, изменять размер и выполнять другие манипуляции с различными изображениями с помощью расширений GD, Imagic и Gmagic PHP. Yii2-Imagine-это легкая статическая оболочка для библиотеки.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Установите расширение с помощью следующей команды:

***composer require yiisoft/yii2-imagine***

Как это сделать...
---
В своих проектах вы можете использовать расширение двумя способами:

* Используя его как фабрика
* Используя внутренние методы

***Используя его как фабрика***

Можно использовать экземпляр исходного класса библиотеки Imagine:
```php
$imagine = new Imagine\Gd\Imagine();
// or
$imagine = new Imagine\Imagick\Imagine();
// or
$imagine = new Imagine\Gmagick\Imagine();
```
Однако это зависит от существующих соответствующих расширений PHP в вашей системе. Вы можете использовать getImagine() метод:
```php
$imagine = \yii\imagine\Image::getImagine();
```

***Использование внутренних методов***
Вы можете использовать методы crop(), thumbnail(), watermark(), text () и frame() для обычных высокоуровневых манипуляций, подобных этому:
```php
<?php
use yii\imagine\Image;
Image::crop('path/to/image.jpg', 100, 100, ManipulatorInterface::THUMBNAIL_OUTBOUND)
->save('path/to/destination/image.jpg', ['quality' => 90]);
```
Смотрите сигнатуры всех поддерживаемых методов  в исходном коде класса \yii\imagine\BaseIm.

Как это работает...
---
Расширение подготавливает пользовательские данные, создает исходный объект Imagine и вызывает на нем соответствующий метод. Все методы возвращают этот исходный объект image. Вы можете продолжать управлять изображением или сохранить результат на диск.

Смотрите так же
---
 Дополнительные сведения о расширении см. по следующим URL-адресам:
* <http://www.yiiframework.com/doc-2.0/ext-imagine-index.html>
* <https ://git.hub.com/yiisoft/yii2-ima gine>
* Для получения информации об исходной библиотеке см. <http://imagine.readthedocs.org/en/latest/>





MongoDB driver
===
Это расширение обеспечивает интеграцию MongoDB для фреймворка Yii2 и позволяет работать с записями коллекции MongoDB через модель ActiveRecord.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Установите MongoDB, используя правильный процесс установки из <https ://docs.mongodb. org/ma nual/installation/> для вашей системы.

3 Установите раширение php php5-mongo .

4 Установите компонент с помощью следующей команды:

***composer require yiisoft/yii2-mongodb***

Как это сделать...
---

1 Прежде всего, создайте новую базу данных MongoDB. Запустите его в оболочке mongo-client и введите имя базы данных:
```php
mongo
> use mydatabase
```

2 Добавьте эту информацию о соединении в раздел конфигурации компонентов:
```php
return [
    // ...
    'components' => [
        // ...
        'mongodb' => [
            'class' => '\yii\mongodb\Connection',
            'dsn' =>  'mongodb://localhost:27017/mydatabase',
        ],
    ],
];
```

3 Добавьте новый контроллер консоли в файл конфигурации консоли:
```php
return [
    // ...
    'controllerMap' => [
        'mongodb-migrate' => 'yii\mongodb\console\controllers\MigrateController'
    ],
];
```

4 Создайте новую миграцию с помощью команды shell:

***php yii mongodb-migrate/create create_customer_collection***

5 Введите следующий код в методы up() и down ():
```php
<?php
use yii\mongodb\Migration;
class m160201_102003_create_customer_collection extends Migration
{
    public function up()
    {
        $this->createCollection('customer');
    }
    public function down()
    {
        $this->dropCollection('customer');
    }
}
```

6 Примениете миграцию:

***php yii mongodb-migrate/up***

7 Поместите панель отладки MongoDB и генератор моделей в свою конфигурацию:
```php
if (YII_ENV_DEV) {
    // configuration adjustments for 'dev' environment
    $config['bootstrap'][] = 'debug';
    $config['modules']['debug'] = [
        'class' => 'yii\debug\Module',
        'panels' => [
            'mongodb' => [
                'class' => 'yii\mongodb\debug\MongoDbPanel',
            ],
        ],
    ];
    $config['bootstrap'][] = 'gii';
    $config['modules']['gii'] = [
        'class' => 'yii\gii\Module',
        'generators' => [
            'mongoDbModel' => [
                'class' => 'yii\mongodb\gii\model\Generator'
            ]
        ],
    ];
}
```

8. Запустите генератор Gii:
![](img/288_1.jpg)

9. Запуск новой модели генератора mongodb для создания новой модели для своей коллекции:
![](img/289_1.jpg)

10 Нажмите кнопки Preview и Generate.

11 Убедитесь, что у вас есть новая модель, app\models\customer:
```php
<?php
namespace app\models;
use Yii;
use yii\mongodb\ActiveRecord;
/**
* This is the model class for collection "customer".
*
* @property \MongoId|string $_id
* @property mixed $name
* @property mixed $email
* @property mixed $address
* @property mixed $status
*/
class Customer extends ActiveRecord
{
    public static function collectionName()
    {
        return ' customer ' ;
    }
    public function attributes()
    {
        return [
            '_id',
            'name',
            'email',
            'address',
            'status',
        ];
    }
    public function rules()
    {
        return [
            [['name', 'email', 'address', 'status'], 'safe']
        ];
    }
    public function attributeLabels()
    {
        return [
            '_id' => 'ID',
            'name' => ' Name',
            'email' => 'Email',
            'address' => 'Address',
            'status' => 'Status',
        ];
    }
}
```

12 Запустите Gii снова и сгенерируйте CRUD:
![](img/291_1.jpg)

13 Убедитесь, что создан класс Customercontroller, и запустите новую страницу Customer manager
![](img/292_1.jpg)

14 Вы можете создавать, обновлять и удалять данные Ваших клиентов прямо сейчас

15 Найдите панель отладки в Нижнем колонтитуле страницы
![](img/292_2.jpg)

16 Вы можете увидеть общее количество запросов MongoDB и общее время выполнения. Нажмите на значок count и проверьте запросы:
![](img/293_1.jpg)

Основное использование
Доступ к базам данных и коллекциям можно получить через экземпляр  \yii\mongodb\collection:
```php
$collection = Yii::$app->mongodb->getCollection('customer');$collection->insert(['name'=> 'John Smith', 'status' => 1]);
```
Для выполнения запросов поиска следует использовать \yii\mongodb\Query:
```php
use yii\mongodb\Query;
$query = new Query;
// compose the query
$query->select(['name', 'status'])
    ->from('customer')
    ->limit(10);
// execute the query
$rows = $query->all();
```
***Примечание***. идентификатор документа MongoDB (поле "_id") не является скалярным, а является экземпляром класса \MongoId.
Преобразование значений integer или string $id в \MongoId не должно волновать, так как построитель запросов преобразует их автоматически:
```php
$query = new \yii\mongodb\Query;
$row = $query->from('item')
    ->where(['_id' => $id]) // implicit typecast to \MongoId
    ->one();
```
Чтобы получить фактическую строку идентификатора Mongo, необходимо типизировать экземпляр \Mongoid в строку:
```php
$query = new Query;
$row = $query->from('customer')->one();
var_dump($row['_id']); // outputs: "object(MongoId)"var_dump((string)$row['_id']);
```

Как это работает...
---
Классы Query, ActiveQuery, и ActiveRecord расширяют  расширение распространяемое в yii\db\QueryInterface and yii\db\BaseActiveRecord, и поэтому они совместимы со встроенными  Query, ActiveQuery и ActiveRecord.
Вы можете использовать класс yii\mongodb\ActiveRecord, установленным для моделей, а в yii\mongodb\ActiveQuery Builder для извлечения моделей и использовать их в поставщике данных:
```php
use yii\data\ActiveDataProvider;
use app\models\Customer;
$provider = new ActiveDataProvider([
    'query' => Customer::find(),
    'pagination' => [
        'pageSize' => 10,
    ]
]);
```
Для получения общей информации о том, как использовать ActiveRecord Yii, пожалуйста, обратитесь к главе 3, ActiveRecord, Model, and Database.

Смотрите так же
---

 Дополнительные сведения о расширении см. по следующим URL-адресам:
* <https://github.com/yiisoft/yii2-mongodb/hloh/master/docs/gnide/RFADME.md>
По русски <https://github.com/yiisoft/yii2-mongodb/tree/master/docs/guide-ru>
* <http://www.yiiframework.com/doc-2.0/ext-mongodb-index.html>

 А также сведения о исходной библиотеки, см.:
* <https://docs.mongodb.org/manual/>
* Для использования ActivRecord  см. в главе 3, ActiveRecord, Model, and Database




Адаптер к движку ElasticSearch 
===
Это расширение является activerecord как обертка для интеграции ElasticSearch полнотекстового поиска в рамках yii2. Он позволяет работать с любыми данными модели и использовать шаблон ActiveRecord для извлечения и хранения записей в коллекциях ElasticSearch.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Установите службы elasticsearch найденные на https://www.elastic.co/downloads/elasticsearch.

3 Установите расширение с помощью следующей команды:

***Composer require yiisoft/yii2-elasticsearch***

Как это сделать...
---

Установите новое соединение ElasticSearch в конфигурации приложения:
```php
    return [
        //....
        'components' => [
        'elasticsearch' => [
            'class' => 'yii\elasticsearch\Connection',
            'nodes' => [
                ['http_address' => '127.0.0.1:9200'],
                // configure more hosts if you have a cluster
            ],
        ],
    ]
];
```

***Используем класс запроса***

Класс Query можно использовать для низкоуровневого запроса записей из любой коллекции:
```php
use \yii\elasticsearch\Query;
$query = new Query;
$query->fields('id, name')
    ->from('myindex', 'users')
    ->limit(10);
$query->search();
```
Можно также создать команду и запустить ее напрямую:
```php
$command = $query->createCommand();
$rows = $command->search();
```

***Используя ActiveRecord***

Использование ActiveRecord является распространенным способом доступа к записям. Просто расширьте класс yii\elasticsearch\ActiveRecord и реализуйте метод attributes () для определения атрибутов ваших документов.
Например, можно написать модель клиента:
```php
class Buyer extends \yii\elasticsearch\ActiveRecord
{
    public function attributes()
    {
        return ['id', 'name', 'address', 'registration_date'];
    }
    public function getOrders()
    {
        return $this->hasMany(Order::className(), ['buyer_id' => 'id'])->orderBy('id');
    }
}
```
Затем напишите модель заказа:
```php
class Order extends \yii\elasticsearch\ActiveRecord
{
    public function attributes()
    {
        return ['id', 'user_id', 'date'];
    }
    public function getBuyer()
    {
        return $this->hasOne(Customer::className(), ['id' => 'buyer_id']);
    }
}
```
Можно переопределить index () и type (), чтобы определить индекс и тип, который представляет эта запись.
Ниже приведен пример использования:
```php
$buyer = new Buyer();
$buyer>primaryKey = 1; // it equivalent to $customer->id = 1;
$buyer>name = 'test';
$buyer>save();
$buyer = Buyer::get(1);
$buyer = Buyer::mget([1,2,3]);
$buyer = Buyer::find()->where(['name' => 'test'])->one();
```
Можно использовать запрос DSL для определенных запросов:
```php
$result = Article::find()->query(["match" => ["title" => "yii"]])->all();
$query = Article::find()->query([
    "fuzzy_like_this" => [
        "fields" => ["title", "description"],
        "like_text" => "Some search text",
        "max_query_terms" => 12
    ]
]);
$query->all();
```
Вы можете добавить фасеты в поиск:
```php
$query->addStatisticalFacet('click_stats', ['field' => 'visit_count']);
$query->search();
```

***Использование ElasticSearch DebugPanel***

Данное расширение содержит специальную панель для модуля yii2-debug. Это позволяет просматривать все выполненные  запросы. Эту панель можно включить в файл конфигурации:
```php
if (YII_ENV_DEV) {
    // configuration adjustments for 'dev' environment
    $config['bootstrap'][] = 'debug';
    $config['modules']['debug'] = [
        'class' => 'yii\debug\Module',
        'panels' => [
            'elasticsearch' => [
                'class' => 'yii\elasticsearch\DebugPanel',
            ],
        ],
    ];
    $config['bootstrap'][] = 'gii';
    $config['modules']['gii'] = 'yii\gii\Module';
}
```

Как это работает...
---
Расширение предоставляет низкоуровневый конструктор команд и высокоуровневую реализацию ActiveRecord для запроса записей из индекса ElasticSearch.
Использование модели расширения, очень похожа на базу данных и activerecord, как описано в главе 3, ActiveRecord, Model, and Database, кроме  операторов join(), groupBy(), having(), and union() ActiveQuery.

***Примечание***. ElasticSearch по умолчанию ограничивает число возвращаемых записей десятью элементами. Будьте осторожны с ограничениями если вы используете отношения с опцией via().

Смотрите так же
---
 Дополнительные сведения о расширении см. в разделе:
* <https://github.com/yiisoft/yii2-elasticsearch/hlob/master/docs/guide/RFADMF.md>
* <http://www.viiframework.com/doc-2.0/ext-elasticsearch-index.html>

Вы также можете посетить официальный сайт расширения по адресу  <https://www.elastic.co/products/elasticsearch>.

Для получения дополнительной информации о запросе DSL, вы можете посетить:
* <http://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-match-query.html>
* <http://www.elastic.co/guide/en/elasticsearch/reference/current/query-dsl-flt-quervhtml>

Для использования ActivRecord см. в главе 3, ActiveRecord, Model, and Database





Генератор кода Gii
==
Это расширение предоставляет веб-генератор кода под названием Gii для приложений Yii 2. Вы можете использовать Gii для быстрого создания моделей, форм, модулей, CRUD и многих других.

Подготовка 
--

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Создайте новую миграцию с помощью команды shell:

***php yii migrate/create create_customer_table***

3 Поместите следующий код в методы up() и down ():
```php
use yii\db\Schema;
use yii\db\Migration;
class m160201_154207_create_customer_table extends Migration
{
    public function up()
    {
        $tableOptions = null;
        if ($this->db->driverName === 'mysql') {
            $tableOptions = 'CHARACTER SET utf8 COLLATE utf8_unicode_ci ENGINE=InnoDB';
        }
        $this->createTable('{{%customer}}',	[
            'id' => Schema::TYPE_PK,
            'name' => Schema::TYPE_STRING .	' NOT NULL',
            'email' => Schema::TYPE_STRING .	' NOT NULL',
            'address' => Schema::TYPE_STRING,
        ], $tableOptions);
    }
    public function down()
    {
        $this->dropTable('{{%customer}}');
    }
}
```

4 Запустите миграцию:

***php yii migrate/up***

Как это сделать...
---
В своих проектах вы можете использовать это расширение двумя способами:
* Работа с GUI
* Работа с CLI

***Работа с GUI***

1 Убедитесь, что файл веб-конфигурации содержит следующий код:
```php
if (YII_ENV_DEV) {
    $config['bootstrap'][] = 'gii';
    $config['modules']['gii'] = [
        'class' => 'yii\gii\Module',
    ];
}
```

2 Ваш  файл web/index.php будет определять среду разработки:
```php
defined('YII_ENV') or define('YII_ENV', 'dev');
```
Предыдущая конфигурация гласит, что в среде разработки приложение должно включать модуль с именем gii, который относится к классу yii\gii\Module.
По умолчанию модуль разрешает доступ с IP-адреса 127.0.0.1. Если вы работаете от другого местоположение, добавьте свой адрес в свойстве allowedIP:
```php
$config['modules']['gii'] = [
    'class' => 'yii\gii\Module',
    allowedIPs = ['127.0.0.1',	'::1',	'192.168.0.*'],
];
```

3 Перейдите к gii вашего приложения: http://localhost/index.php?r=gii.
![](img/300_1.jpg)

4 Нажмите на кнопку Model Generator и введите имя таблицы и название модели в форме:
![](img/301_1.jpg)

5 Нажмите кнопку Preview. Необходимо просмотреть список рекомендуемых файлов:
![](img/302_1.jpg)

6 Если вы хотите восстановить существующие файлы, Gii пометит их желтым цветом:
![](img/302_1.jpg)

7 В этом случае вы можете посмотреть разницу между существующими и новыми файлами и замените, если необходимо.

8 После всего этого нажмите кнопку Generate:
![](img/303_1.jpg)

9 Убедитесь, что новый класс \app\models\customer существует.

10  CRUD-это аббревиатура для четырех общих задач, использующих данные на большинстве веб-сайтов: создание, чтение, обновление и удаление. Чтобы создать CRUD с помощью Gii, выберите раздел генератор CRUD. Укажите класс модели и введите другие поля:
![](img/304_1.jpg)

11  Создание новых элементов:
![](img/305_1.jpg)

12 После этого попробуйте открыть новый контроллер:
![](img/306_1.jpg)

Вы увидите таблицу, показывающую клиентов в таблице базы данных. Попробуйте создать новый элемент. Сетку можно отсортировать или отфильтровать, введя условия фильтра в заголовках столбцов.

***Работа с  CLI***

GII также предоставляет контроллер консоли для генерации кода.

1 Убедитесь, что конфигурация консоли содержит параметры модуля Gii:
```php
return [
    // ...
    'modules' => [
        'gii' => 'yii\gii\Module',
    ],
    // ...
];
```

2 Выполните любую команду оболочки для справки:
```php
php yii help gii
php yii help gii/model
```

3 Введите следующую команду, чтобы запустить процесс создания модели:

***php yii gii/model --tableName=customer --modelClass=Customer --useTablePrefix=1***

4 Убедитесь, что новый класс \app\models\customer существует.

5 Создание CRUD для Вашей модели:

***php yii gii/crud --modelClass=app\\models\\Customer\ --searchModelClass=app\\models\\CustomerSearch\ --controllerClass=app\\controllers\\CustomerController***

Как это работает...
---
GII  позволяет создавать некоторые стандартные элементы кода, вместо ручного набора. Он предоставляет веб-интерфейсы и консольные интерфейсы для работы с каждым генератором.

Смотрите так же
---

Дополнительные сведения об использовании расширения см. в разделе:
*<http://www.yiiframework.com/doc-2.0/gurde-start-gii.html>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-gii>
* <http://www.viiframework.com/doc-2.0/ext-gii-indpx.hrml>
* <https://github.com/yiisoft/yEZ-gii/tree/master/docs/guide>
по русски <https://github.com/yiisoft/yii2-gii/tree/master/docs/guide-ru>

Для интеграции MongoDB обратитесь к  рецепта созданию виджета в главе 8, расширение Yii




Pjax jQuery plugin
==
Pjax-это виджет, который интегрирует плагин pjax jQuery. Все содержимое, обернутое этим виджетом, будет перезагружено AJAX без обновления текущей страницы. Виджет также использует API истории HTML5 для изменения текущего URL в адресной строке браузера.

Подготовка 
--
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать...
---
В следующем примере показано, как использовать pjax с виджетом yii\grid\Gridview:
```php
<?php
use yii\widgets\Pjax;
?>
<?php Pjax::begin(); ?>
    <?= GridView::widget([...]); ?>
<?php Pjax::end(); ?>
```
Просто оберните любой фрагмент кода в вызов Pjax::begin() и Pjax::end().
Это отобразит следующий HTML-код:
```php
<div id="w1">
    <div id="w2" class="grid-view">...</div>
</div>
<script type="text/javascript">jQuery(document).ready(function () {
    jQuery(document).pjax("#w1 a", "#w1", {...});
});</script>
```
Весь завернутый контент со ссылками разбиения на страницы и сортировки будет перезагружен AJAX.

***Указание пользовательского идентификатора***

Pjax получает содержимое страницы из запросов AJAX, а затем извлекает собственный элемент DOM с тем же идентификатором. Производительность отрисовки страниц можно оптимизировать путем отрисовки содержимого без макета, особенно для запросов Pjax:
```php
public function actionIndex()
{
    $dataProvider = ...;
    if (Yii::$app->request->isPjax) {
        return $this->renderPartial('_items', [
            'dataProvider' => $dataProvider,
        ]);
    } else {
        return $this->render('index', [
            'dataProvider' => $dataProvider,
        ]);
    }
}
```
По умолчанию метод yii\base\widget::getid увеличивает идентификаторы и, следовательно, виджеты на любой странице с увеличенными атрибутами:
```php
<nav id="w0">...</nav> // Main navigation
<ul id="w1">...</ul> // Breadcrumbs widget
<div id="w2">...</div> // Pjax widget
```
Для рендеринга с использованием методов renderPartial() или renderAjax() без рендеринга макета на вашей странице будет только один виджет с номером 0:
```php
<div id="w0">...</div> // Pjax widget
```
В результате ваш собственный виджет не найдет свой блок с селектором w2 при следующем запросе.
Однако Pjax найдет тот же блок с селектором w2 в ответе Ajax. В результате ваш собственный виджет не найдет блок с селектором w2 при следующем запросе.
Поэтому необходимо вручную указать уникальный идентификатор для всех виджетов Pjax, чтобы избежать различных конфликтов:
```php
<?php Pjax::begin(['id' => 'countries']) ?>
    <?= GridView::widget([...]); ?>
<?php Pjax::end() ?>
```

***Использование ActiveForm***

По умолчанию Pjax работает только со ссылками в блоке wrapped. Если вы хотите использовать его с виджетом ActiveForm, необходимо использовать параметр data-pjax формы:
```php
<?php
use \yii\widgets\Pjax
use \yii\widgets\ActiveForm;
<?php yii\widgets\Pjax::begin(['id' => 'my-block']) ?>
    <?php $form = ActiveForm::begin(['options' => ['data-pjax' => true,]]); ?>
        <?= $form->field($model, 'name') ?>
    <?php ActiveForm::end(); ?>
<?php Pjax::end(); ?>
```
Он добавляет соответствующих слушателей на форму отправки события.
Можно также использовать параметр $formSelector виджета Pjax, чтобы указать, какая отправка формы может вызвать pjax.

***Работа со сценарием на стороне клиента***

Вы можете подписаться на события контейнера:
```php
<?php $this->registerJs('
    $("#my-block").on("pjax:complete", function() {
        alert('Pjax is completed');
    });
'); ?>
```
Или можно перезагрузить контейнер вручную с помощью его селектора:
```php
<?php $this->registerJs('
    $("#my-button").on("click", function() {
        $.pjax.reload({container:"#my-block"});
    });
'); ?>
```

Как это работает...
---
Pjax-это простая оболочка для любого фрагмента кода. Он подписывается на события кликов всех ссылок в фрагменте и заменяет всю страницу, перезагружая ее в Ajax-вызовы. Мы можем использовать атрибут data-pjax для завернутых форм, и любые представления форм вызовут запрос Ajax.
Виджет будет загружать и обновлять содержимое тела виджета "на лету" без загрузки ресурсов макета (JS,CSS).
Вы можете настроить $linkSelector виджета, чтобы указать, какие ссылки должны вызвать Pjax, и настроить $formSelector, чтобы указать, что форма подачи может вызвать Pjax.
Вы можете отключить Pjax для определенной ссылки внутри контейнера, добавив атрибут data-pjax="0" к этой ссылке.

Смотрите так же
---

Дополнительные сведения об использовании расширения см. в разделе:
* <http://www.viiframework.com/doc-2.0/vii-widgets-piax.html>
* <https://github.com/yiisoft/jquery-pjax>

 Дополнительные сведения о параметрах и методах на стороне клиента см. в разделе
* <https://github.com/yiisoft/jquery-pjax#usage> 





Redis database driver
==
Это расширение позволяет использовать хранилище ключей и значений Redis в любом проекте на платформе Yii2. Он содержит обработчики кэша и хранилища сеансов, а также расширение, реализующее шаблон ActiveRecord для доступа к записям базы данных Redis.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Установите хранилище: <http://redis.io>.

3 Установите все миграции с помощью следующей команды:

***composer require yiisoft/yii2-redis***

Как это сделать...
---
Прежде всего, настройте класс соединения в файле конфигурации:
```php
return [
    //....
    'components' => [
        'redis' => [
            'class' => 'yii\redis\Connection',
            'hostname' => 'localhost',
            'port' => 6379,
            'database' => 0,
        ],
    ]
];
```

***Прямое использование***

Для низкоуровневой работы с командами Redis можно использовать метод executeCommand компонента connection:
```php
Yii::$app->redis->executeCommand('hmset', ['test_collection', 'keyl', 'vall', 'key2', 'val2']);
```

Можно также использовать упрощенные сочетания вместо вызовов executeCommand:
```php
Yii::$app->redis->hmset('test_collection', 'key1','val1','key2','val2')
```

***Использование ActiveRecord***

Для доступа к записям Redis через шаблон ActiveRecord класс record должен быть расширен из базового класса yii\redis\ActiveRecord и реализовать метод attributes:
```php
class Customer extends \yii\redis\ActiveRecord
{
    public function attributes()
    {
        return ['id', 'name', 'address', 'registration_date'];
    }
    public function getOrders()
    {
        return $this->hasMany(Order::className(), ['customer_id' => 'id']);
    }
}
```
Первичный ключ любой модели может быть определен с помощью метода primaryKey (), который по умолчанию имеет значение id, если не указан. Первичный ключ необходимо поместить в список атрибутов, если он не указан вручную в методе primaryKey.
Ниже приведен пример использования:
```php
$customer = new Customer();
$customer->name = 'test';
$customer->save();
echo $customer->id; 
// id will automatically be incremented if not set explicitly
// find by query
$customer = Customer::find()->where(['name' => 'test'])->one();
```

Как это работает...
---
Расширение предоставляет компонент подключения для низкоуровневого доступа к записям хранения Redis.
Вы также можете использовать и ActiveRecord-похожие модели с ограниченным набором методов (where(), limit(), offset(), и indexBy()). Другие методы не существуют, поскольку Redis не поддерживает запросы SQL.
В Redis нет таблиц, поэтому Вы не можете определить отношения через имя таблицы соединений. Вы можете определить отношения "многие ко многим" только через другие отношения hasMany.
Для общей информации о том, как использовать Yii’s ActiveRecord, пожалуйста см. Глава 3, ActiveRecord, Model, and Database.

Смотрите так же
---

Дополнительные сведения об использовании расширения см. в разделе:
* <https ://github.com/yiisoft/yii2-redis/blob/ma stpr/docs/guide/RF ADMF.md>
По русски <https://github.com/yiisoft/yii2-redis/tree/master/docs/guide-ru>
* <http://www.viiframework.com/doc-2.0/ext-redis-index.html>

Сведения о "ключ-значение" redis для хранения, см.: <http://redis.io/documentation>

Глава 3, ActiveRecord, Model, and Database для использования ActiveRecord 




Ãëàâà 8. Ðàñøèðåíèå Yii
==
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:
* Ñîçäàíèå ïîìîùíèêîâ
* Ñîçäàíèå ìîäåëåé ïîâåäåíèÿ
* Ñîçäàíèå êîìïîíåíòîâ
* Ñîçäàíèå ìíîãîêðàòíî èñïîëüçóåìûõ äåéñòâèé êîíòðîëëåðà
* Ñîçäàíèå ìíîãîðàçîâûõ êîíòðîëëåðîâ
* Ñîçäàíèå âèäæåòà
* Ñîçäàíèå êîìàíä CLI
* Ñîçäàíèå ôèëüòðîâ
* Ñîçäàíèå ìîäóëåé
* Ñîçäàíèå ïîëüçîâàòåëüñêîãî ñðåäñòâà âèçóàëèçàöèè âèäà
* Ñîçäàíèå ìíîãîÿçû÷íîãî ïðèëîæåíèÿ
* Äåëàòü ðàñøèðåíèå ãîòîâûì ê ðàçäà÷å

Ââåäåíèå
==
Â ýòîé ãëàâå ìû ïîêàæåì âàì íå òîëüêî, êàê ðåàëèçîâàòü ñîáñòâåííîå ðàñøèðåíèå Yii, íî è êàê ñäåëàòü âàøå ðàñøèðåíèå ìíîãîðàçîâûì è ïîëåçíûì äëÿ ñîîáùåñòâà. Êðîìå òîãî, ìû ñîñðåäîòî÷èìñÿ íà ìíîãèõ âåùàõ, êîòîðûå âû äîëæíû ñäåëàòü, ÷òîáû ñäåëàòü âàøå ðàñøèðåíèå ìàêñèìàëüíî ýôôåêòèâíûì




Создание помощников
===
В пространстве имен yii\helpers много встроенных помощников платформы, таких как stringHelper. Они содержат наборы полезных статических методов для работы со строками, файлами, массивами и другими объектами.
Во многих случаях для дополнительного поведения можно создать собственный помощник и поместить в него любую статическую функцию.Например, мы реализуем номер помощника в этом рецепте.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать...
---

1 Создайте в проекте каталог helpers и запишите класс NumberHelper:
```php
<?php
namespace app\helpers;
class NumberHelper
{
    public static function format($value, $decimal = 2)
    {
        return number_format($value, $decimal, '.',	',');
    }
}
```

2 Добавьте метод actionNumbers в SiteController:
```php
<?php...
class SiteController extends Controller
{
    public function actionNumbers()
    {
        return $this->render('numbers', ['value' => 18878334526.3]);
    }
}
```

3 Добавить в представление views/site/numbers.php:
```php
<?php
use app\helpers\NumberHelper;
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $value float */
$this->title = 'Numbers';
$this->params['breadcrumbs'][] = $this->title;
?>
<div class="site-numbers">
    <h1><?= Html::encode($this->title) ?></h1>
    <p>
        Raw number:<br />
        <b><?= $value ?></b>
    </p>
    <p>
        Formatted number:<br />
        <b><?= NumberHelper::format($value) ?></b>
    </p>
</div>
```

4. Откройте действие. Вы должны увидеть следующий результат:
![](img/315_1.jpg)

В других случаях можно указать другое количество десятичных чисел. Рассмотрим следующий пример:
NumberHelper::format($value, 3)

Как это работает...
---
Любой помощник в Yii2 - это просто набор функций, реализованных в виде статических методов в соответствующих классах.
Можно использовать помощник для реализации любых различных форматов вывода, для манипуляций со значениями любых переменных и для других случаев.

***Замечание***: Обычно статические помощники-это легкие чистые функции с небольшим количеством аргументов. Избегайте использования бизнес-логики и других сложных манипуляций в помощниках. Используйте виджеты или другие компоненты вместо помощников в других случаях.

Смотитре так же
---
Для получения дополнительной информации о помощниках, обратитесь к: <http://www.yijframework.eom/doc-2.0/guide-helper-overview.html>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/helper-overview>
 
Примеры встроенных помощников см. в разделе источники в каталоге помощников framework. Для структуры обратитесь к:<https://github.rom/yiisoft/yii2/tree/mastpr/framework/helpers>.





Создание моделей поведения
===
Есть много подобных решений в современных веб-приложениях. Ведущие продукты, такие как Google Gmail, определяют хорошие шаблоны пользовательского интерфейса. Один из них-мягкое удаление. Вместо постоянного удаления с тоннами подтверждений, Gmail позволяет нам сразу пометить сообщения как удаленные, а затем легко отменить его. Такое же поведение можно применить к любому объекту, например к записям в блоге, комментариям и т. д.
Давайте создадим поведение, которое позволит отмечать модели как удаленные, восстанавливать модели, выбирать еще не удаленные модели, удаленные модели и все модели. В этом рецепте мы будем следовать тестовому подходу к разработке для планирования поведения и тестирования, если реализация верна.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Создание двух баз данных для работы и тестирования.

3 Настройте Yii для использования первой базы данных в основном приложении в config/db.php. Убедитесь, что тестовое приложение использует вторую базу данных в tests/codeception/config/config.php.

4 Создание новой миграции:

```php
<?php
use yii\db\Migration;
class m160427_103115_create_post_table extends Migration
{
    public function up()
    {
        $this->createTable('{{%post}}',	[
            'id' => $this->primaryKey(),
            'title' => $this->string()->notNull(),
            'content_markdown' => $this->text(),
            'content_html' => $this->text(),
        ]);
    }
    public function down()
    {
        $this->dropTable('{{%post}}');
    }
}
```
5 Применить миграции рабочей и тестовой базы данных:

***./yii migrate***

***tests/codeception/bin/yii migrate***

6 Создание модели Post :
```php
<?php
namespace app\models;
use app\behaviors\MarkdownBehavior;
use yii\db\ActiveRecord;
/**
* @property integer $id
* @property string $title
* @property string $content_markdown
* @property string $content_html
*/
class Post extends ActiveRecord
{
    public static function tableName()
    {
        return '{{%post}}';
    }
    public function rules()
    {
        return [
            [['title'], 'required'],
            [['content_markdown'], 'string'],
            [['title'], 'string', 'max' => 255],
        ];
    }
}
```
Как это сделать...
---
Давайте сначала подготовим тестовую среду, начиная с определения креплений для модели Post. Создать файл tests/codeception/unit/fixtures/PostFixture.php:
```php
<?php
namespace app\tests\codeception\unit\fixtures;
use yii\test\ActiveFixture;
class PostFixture extends ActiveFixture
{
    public $modelClass = 'app\models\Post';
    public $dataFile = '@tests/codeception/unit/fixtures/data/post.php';
}
```

1 Файл добавить данные фикстуры для tests/codeception/unit/fixtures/data/post.php:
```php
<?php
return [
    [
        'id' => 1,
        'title' => 'Post 1',
        'content_markdown' => 'Stored *markdown* text 1',
        'content_html' => "<p>Stored <em>markdown</em> text 1</p>\n",
    ],
];
```

2 Затем, нам нужно создать тест, tests/codeception/unit/MarkdownBehaviorTest.php:
```php
<?php
namespace app\tests\codeception\unit;
use app\models\Post;
use app\tests\codeception\unit\fixtures\PostFixture;
use yii\codeception\DbTestCase;
class MarkdownBehaviorTest extends DbTestCase
{
    public function testNewModelSave()
    {
        $post = new Post();
        $post->title = 'Title';
        $post->content_markdown = 'New *markdown* text';
        $this->assertTrue($post->save());
        $this->assertEquals("<p>New <em>markdown</em> text</p>\n", $post->content_html);
    }
    public function testExistingModelSave()
    {
        $post = Post::findOne(1);
        $post->content_markdown = 'Other *markdown* text';
        $this->assertTrue($post->save());
        $this->assertEquals("<p>Other <em>markdown</em> text</p>\n", $post->content_html);
    }
    public function fixtures()
    {
        return [
            'posts' => [
                'class' => PostFixture::className(),
            ]
        ];
    }
}
```

3 Запустите  unit тесты:

***codecept run unit MarkdownBehaviorTest***

```php
Ensure that tests has not passed:
Codeception PHP Testing Framework v2.0.9
Powered by PHPUnit 4.8.27 by Sebastian Bergmann and contributors.
Unit Tests (2) 
Trying to test... MarkdownBehaviorTest::testNewModelSave	Error
Trying to test. MarkdownBehaviorTest::testExistingModelSave	Error
Time: 289 ms, Memory: 16.75MB
```

4 Теперь нам нужно реализовать поведение, присоединить его к модели и убедиться, что тест пройден. Создайте новый каталог, поведение. В этом каталоге создайте класс MarkdownBehavior:
```php
<?php
namespace app\behaviors;
use yii\base\Behavior;
use yii\base\Event;
use yii\base\InvalidConfigException;
use yii\db\ActiveRecord;
use yii\helpers\Markdown;
class MarkdownBehavior extends Behavior
{
    public $sourceAttribute;
    public $targetAttribute;
    public function init()
    {
        if (empty($this->sourceAttribute) || empty($this->targetAttribute)) {
            throw new InvalidConfigException('Source and target must be set.');
        }
        parent::init();
    }
    public function events()
    {
        return [
            ActiveRecord::EVENT_BEFORE_INSERT => 'onBeforeSave',
            ActiveRecord::EVENT_BEFORE_UPDATE => 'onBeforeSave',
        ];
    }
    public function onBeforeSave(Event $event)
    {
        if ($this->owner->isAttributeChanged($this->sourceAttribute)) {
            $this->processContent();
        }
    }
    private function processContent()
    {
        $model = $this->owner;
        $source = $model->{$this->sourceAttribute};
        $model->{$this->targetAttribute} = Markdown::process($source);
    }
}
```

5 Давайте прикрепим поведение к модели Post:
```php
class Post extends ActiveRecord
{
    public function behaviors()
    {
        return [
            'markdown' => [
                'class' => MarkdownBehavior::className(),
                'sourceAttribute' => 'content_markdown',
                'targetAttribute' => 'content_html',
            ],
        ];
    }
}
```

6 Запустите тест и убедитесь, что он проходит:
```php
Codeception PHP Testing Framework v2.0.9
Powered by PHPUnit 4.8.27 by Sebastian Bergmann and contributors.
Unit Tests (2) 
Trying to test... MarkdownBehaviorTest::testNewModelSave	Ok
Trying to test. MarkdownBehaviorTest::testExistingModelSave	Ok
Time: 329 ms, Memory: 17.00MB
```

7 Вот и все. Мы создали многоразовое поведение и можем использовать его для всех будущих проектов, просто подключив его к модели.

Как это работает...
---
Начнем с теста. Поскольку мы хотим использовать набор моделей, мы определяем fixtures. Набор fixtures помещается в “базу данных " при каждом выполнении метода тестирования.
Мы готовим модульные тесты для определения того, как должно работать поведение:

* Во-первых, мы тестируем обработку контента новой модели. Поведение должно преобразовать текст Markdown из исходного атрибута в HTML и сохранить второй в целевой атрибут.
* Во-вторых, мы проводим тестирование для обновления содержания существующей модели. После изменения содержимого Markdown и сохранения модели мы должны получить обновленное содержимое HTML.
Теперь перейдем к интересным деталям реализации. В behavior мы можем добавить собственные методы, которые будут смешаны с моделью, к которой прикреплено поведение. Кроме того, мы можем подписаться на события компонента владельца. Мы используем его, чтобы добавить свой слушатель:
```php
public function events()
{
    return [
        ActiveRecord::EVENT_BEFORE_INSERT => 'onBeforeSave',
        ActiveRecord::EVENT_BEFORE_UPDATE => 'onBeforeSave',
    ];
}
```
Теперь мы можем реализовать этот слушатель:
```php
public function onBeforeSave(Event $event)
{
    if ($this->owner->isAttributeChanged($this->sourceAttribute))
    {
        $this->processContent();
    }
}
```
Во всех методах мы можем использовать свойство owner для получения объекта, к которому прикреплено поведение. В общем, мы можем присоединить любое поведение к нашим моделям, контроллерам, приложениям и другим компонентам, которые расширяют класс yii\base\Component. Кроме того, мы можем многократно присоединять одно поведение к модели для обработки различных атрибутов:
```php
class Post extends ActiveRecord
{
    public function behaviors()
    {
        return [
            [
                'class' => MarkdownBehavior::className(),
                'sourceAttribute' => 'description_markdown',
                'targetAttribute' => 'description_html',
            ],
            [
                'class' => MarkdownBehavior::className(),
                'sourceAttribute' => 'content_markdown',
                'targetAttribute' => 'content_html',
            ],
        ];
    }
}
```
Кроме того, мы можем расширить класс yii\base\AttributeBehavior как yii\behaviors\TimestampBehavior для обновления заданных атрибутов для любых событий.

Смотрите так же
---

Дополнительные сведения о поведении и событиях см. на следующих страницах:
* <http://www.yiiframework.com/doc-2.0/guide-concept-behaviors.html>
 по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/concept-behaviors> 
* <http://www.yiiframework.com/doc-2.0/guide-concept-events.html>
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/concept-events>
 
Дополнительные сведения о синтаксисе Markdown см. в разделе <http://daringfireball.net/projects/markdown/>.

Кроме того, обратитесь к рецепту Созданию расширений распределения  этой главы.





Создание компонентов
==
Если у вас есть какой-то код, который выглядит так, будто его можно использовать повторно, но Вы не знаете, является ли это поведением, виджетом или чем-то еще, скорее всего, это компонент. Компонент должен быть унаследован от класса yii\base\component. Позже компонент может быть присоединен к приложению и настроен с помощью раздела components файла конфигурации. Это основное преимущество по сравнению с использованием простого класса PHP. Кроме того, мы получаем поддержку поведения, событий, геттеров и сеттеров.
В нашем примере мы реализуем простой компонент приложения Exchange, который сможет получать курсы валют из http://fixer.io сайт, прикрепите его к приложению и используйте.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать ...
---
Для получения курсов валют наш компонент должен отправить запрос HTTP GET на URL-адрес службы, например <http://api.fixer.io/2016-05-14?base=USD>.
Сервис должен вернуть все Поддерживаемые тарифы в ближайший рабочий день:
```php
{
    "base":"USD",
    "date":"2016-05-13",
    "rates": {
        "AUD":1.3728,
        "BGN":1.7235,
        "ZAR":15.168,
        "EUR":0.88121
    }
}
```
Компонент должен извлечь валюту из ответа в формате JSON и вернуть целевой курс:

1 Создайте каталог компонентов в структуре приложения.

2 Создайте пример класса компонента со следующим интерфейсом:
```php
<?php
namespace app\components;
use yii\base\Component;
class Exchange extends Component
{
    public function getRate($source, $destination, $date = null)
    {
    }
}
```

3 Реализуйте функционал компонента:
```php
<?php
namespace app\components;
use yii\base\Component;
use yii\base\InvalidConfigException;
use yii\base\InvalidParamException;
use yii\caching\Cache;
use yii\di\Instance;
use yii\helpers\Json;
class Exchange extends Component
{
    /**
    * @var string remote host
    */
    public $host = 'http://api.fixer.io';
    /**
    * @var bool cache results or not
    */
    public $enableCaching = false;
    /**
    * @var string|Cache component ID
    */
    public $cache = 'cache';
    public function init()
    {
        if (empty($this->host)) {
            throw new InvalidConfigException('Host must be set.');
        }
        if ($this->enableCaching) {
            $this->cache = Instance::ensure($this->cache, Cache::className());
        }
        parent::init();
    }
    public function getRate($source, $destination, $date = null)
    {
        $this->validateCurrency($source);
        $this->validateCurrency($destination);
        $date = $this->validateDate($date);
        $cacheKey = $this->generateCacheKey($source, $destination, $date);
        if (!$this->enableCaching || ($result = $this->cache->get($cacheKey)) === false) {
            $result = $this->getRemoteRate($source, $destination, $date);
            if ($this->enableCaching) {
                $this->cache->set($cacheKey, $result);
            }
        }
        return $result;
    }
    private function getRemoteRate($source, $destination, $date)
    {
        $url = $this->host . '/'	. $date . '?base=' . $source;
        $response = Json::decode(file_get_contents($url));
        if (!isset($response['rates'][$destination])) {
            throw new \RuntimeException('Rate not found.');
        }
        return $response['rates'][$destination];
    }
    private function validateCurrency($source)
    {
        if (!preg_match('#A[A-Z]{3}$#s', $source)) {
            throw new InvalidParamException('Invalid currency format.');
        }
    }
    private function validateDate($date)
    {
        if (!empty($date) && !preg_match('#\d{4}\-\d{2}-\d{2}#s', $date)) {
            throw new InvalidParamException('Invalid date format.');
        }
        if (empty($date)) {
            $date = date('Y-m-d');
        }
        return $date;
    }
    private function generateCacheKey($source, $destination, $date)
    {
        return [__CLASS__, $source, $destination, $date];
    }
}
```

4 Подключите компонент к конфигурации  config/console.php или config/web.php:
```php
'components' => [
    'cache' => [
        'class' => 'yii\caching\FileCache',
    ],
    'exchange' => [
        'class' => 'app\components\Exchange',
        'enableCaching' => true,
    ],
    // ...
    db' => $db,
],
```

5 Прямо сейчас мы можем использовать новый компонент напрямую или с помощью метода get:
```php
echo \Yii::$app->exchange->getRate('USD', 'EUR');
echo \Yii::$app->get('exchange')->getRate('USD', 'EUR', '2014-04-12');
```

6 Создание демонстрационного контроллера консоли:
```php
<?php
namespace app\commands;
use yii\console\Controller;
class ExchangeController extends Controller
{
    public function actionTest($currency, $date = null)
    {
        echo \Yii::$app->exchange->getRate('USD', $currency, $date) . PHP_EOL;
    }
}
```

7 Теперь попробуйте выполнить любую команду:

$ ***./yii exchange/test EUR***
> 0.90196

$ ***./yii exchange/test EUR 2015-11-24***
> 0.93888
> 
$ ***./yii exchange/test OTHER***
> Exception 'yii\base\InvalidParamException' with message 'Invalid currency
format.'

$ ***./yii exchange/test EUR 2015/24/11***
>Exception 'yii\base\InvalidParamException' with message 'Invalid date format.'

$ ***./yii exchange/test ASD***
> Exception 'RuntimeException' with message 'Rate not found.'

В результате вы должны увидеть значения курса в успешных случаях или конкретные исключения в ошибках. Помимо создания собственных компонентов, вы можете сделать больше.

***Переопределение существующих компонентов приложения***

В большинстве случаев нет необходимости создавать собственные компоненты приложения, так как другие типы расширений, такие как виджеты или поведения, охватывают почти все типы многократно используемых кодов. Тем не менее, переопределение основных компонентов платформы является обычной практикой и может использоваться для настройки поведения платформы для ваших конкретных потребностей без взлома ядра.
Например, чтобы иметь возможность форматировать числа с помощью метода Yii::app()->formatter->asNumber($value) вместо нашего метода NumberHelper:: format из рецепта создания помощников, вы можете выполнить следующие шаги:

1 Расширьте компонент Yii\i18n\Formatter следующим образом:
```php
<?php
namespace app\components;
class Formatter extends \yii\i18n\Formatter
{
    public function asNumber($value, $decimal = 2)
    {
        return number_format($value, $decimal, '.',	',');
    }
}
```


2 Переопределить в классе встроенный форматер компонент:
```php
'components' => [
    // ...
    formatter => [
        'class' => 'app\components\Formatter,
    ],
    // ...
],
```

3 Сейчас мы можем использовать этот метод напрямую:
```php
echo Yii::app()->formatter->asNumber(1534635.2, 3);
```
Кроме того, его можно использовать в качестве нового формата для виджетов GridView и DetailView:
```php
<?= \yii\grid\GridView::widget([
    'dataProvider' => $dataProvider,
    'columns' => [
        'id',
        'created_at:datetime',
        'title',
        'value:number',
    ],
]) ?>
```

4. Кроме того, можно расширить каждый существующий компонент, не перезаписывая его исходный код.

Как это работает...
---
Чтобы иметь возможность присоединить компонент к приложению,его можно расширить из класса yii\base\component. Прикрепление так же просто, как добавление нового массива в раздел компонентов конфигурации. Там значение класса указывает класс компонента, а все остальные значения устанавливаются для компонента через соответствующие открытые свойства компонента и методы setter.
Сама реализация очень проста; мы завершаем http://api.fixer.io вызывает удобный API с валидаторами и кэшированием. Мы можем получить доступ к нашему классу по его имени компонента с помощью Yii:: $app. В нашем случае это будет Yii:: $app- > exchange.

Смотрите так же
---

Для официальной информации о компонентах, см. <http://www.yiiframework.com/doc-2.0/guide-concept-components.html>.
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-application-components> 

Для источников класса NumberHelper см. рецепт создания помощников.





Создание многократно используемых действий контроллера
===
Общие действия, такие как удаление модели AR первичным ключом или получение данных для автозаполнения AJAX, могут быть перемещены в многократно используемые действия контроллера, а затем присоединены к контроллерам по мере необходимости.
В этом рецепте мы создадим повторно используемое действие удаления, которое удалит указанную модель AR по ее первичному ключу.

Подготовка 
---

1 Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

2 Создайте новую базу данных и настройте ее.

3 Создайте и примените следующую миграцию:
```php
<?php
use yii\db\Migration;
class m160308_093233_create_post_table extends Migration
{
    public function up()
    {
        $this->createTable('{{%post}}',	[
            'id' => $this->primaryKey(),
            'title' => $this->string()->notNull(),
            'text' => $this->text()->notNull(),
        ]);
    }
    public function down()
    {
        $this->dropTable('{{%post}}');
    }
}
```

4 Создайте модели для Post и Comment с помощью Gii.

5 Сгенерируйте стандартный crud для контроллера app\controllers\PostController в GII.

6 Убедитесь, что CRUD нормально работает:
![](img/329_1.jpg)

7 В случае успеха добавьте набор примеров записей.

Как это сделать...
---
Выполните следующие действия:

1 Создайте каталог действий и добавьте автономное действие DeleteAction:
```php
<?php
namespace app\actions;
use yii\base\Action;
use yii\base\InvalidConfigException;
use yii\web\MethodNotAllowedHttpException;
use yii\web\NotFoundHttpException;
class DeleteAction extends Action
{
    public $modelClass;
    public $redirectTo = ['index'];
    
    public function init()
    {
        if (empty($this->modelClass)) {
            throw new InvalidConfigException('Empty model class.');
        }
        parent::init();
    }

    public function run($id)
    {
        if (!\Yii::$app->getRequest()->getIsPost()) {
            throw new MethodNotAllowedHttpException('Method not allowed.');
        }
        $model = $this->findModel($id);
        $model->delete();
        return $this->controller->redirect($this->redirectTo);
    }
    /**
    * @param $id
    * @return \yii\db\ActiveRecord
    * @throws NotFoundHttpException
    */
    private function findModel($id)
    {
        $class = $this->modelClass;
        if (($model = $class::findOne($id)) !== null) {
            return $model;
        } else {
            throw new NotFoundHttpException('Page does not exist.');
        }
    }
}
```

2 Теперь нам нужно подключить его к контроллерам controllers/PostController.php. Удалите метод actionDelete и поведения контроллера и присоедините собственное действие в методе действия:
```php
<?php
namespace app\controllers;
use app\actions\DeleteAction;
use Yii;
use app\models\Post;
use app\models\PostSearch;
use yii\web\Controller;
use yii\web\NotFoundHttpException;
class PostController extends Controller
{
    public function actions()
    {
        return [
            'delete' => [
                'class' => DeleteAction::className(),
                'modelClass' => Post::className(),
            ],
        ];
    }
    public function actionIndex() {	...	}
    public function actionView($id) {	...	}
    public function actionCreate() {	...	}
    public function actionUpdate($id) {	...	}
    protected function findModel($id)
    {
        if (($model = Post::findOne($id)) !== null) {
            return $model;
        } else {
            throw new NotFoundHttpException('The requested page does not exist.');
        }
    }
}
```

3 Вот и все. Убедитесь, что операция удаления по-прежнему работает правильно, и после удаления вы будете перенаправлены на соответствующее действие индекса.

Как это работает...
---
Чтобы создать действие внешнего контроллера, необходимо расширить класс из yii\base\Action. Единственный обязательный метод для реализации выполняется. В нашем случае он принимает параметр $id из $_GET с помощью функции автоматической привязки параметров Yii и пытается удалить соответствующую модель.
Чтобы сделать его настраиваемым, мы создали два общедоступных свойства, настраиваемых из контроллера. Это modelName, который содержит имя модели, с которой мы работаем, и redirectTo, который задает маршрут, на который пользователь будет перенаправлен.
Сама конфигурация выполняется путем реализации метода действий в контроллере. Там можно присоединить действие один или несколько раз и настроить его общие свойства.
Вы можете получить доступ к исходному объекту контроллера через свойство controller, если это необходимо для перенаправления на другое действие или визуализации определенного представления.

Смотрите так же
---
Дополнительные сведения о контроллерах и действиях см. в разделе 
<https://www.yiiframework.com/doc/guide/2.0/en/structure-controllers> 
по русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-controllers>





Создание повторно используемых контроллеров
===
В Yii можно создавать повторно используемые контроллеры. Если вы создаете много приложений или контроллеров одного типа, перемещение всего общего кода в повторно используемый контроллер сэкономит вам много времени.
В этом рецепте мы попытаемся создать общий cleanController, который очистит временные каталоги и очистит кэшированные данные.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать...
---
Для создания повторно используемых контроллеров выполните следующие действия:

1 Создайте каталог cleaner и добавьте автономный контроллер CleanController:
```php
<?php
namespace app\cleaner;
use Yii;
use yii\filters\VerbFilter;
use yii\helpers\FileHelper;
use yii\web\Controller;
class CleanController extends Controller
{
    public $assetPaths = ['@app/web/assets'];
    public $runtimePaths = ['©runtime'];
    public $caches = ['cache'];
    public function behaviors()
    {
        return [
            'verbs' => [
                'class' => VerbFilter::className(),
                'actions' => [
                    ' assets ' => [' post' ],
                    'runtime' => ['post'],
                    ' cache' => [' post' ],
                ],
            ],
        ];
    }
    public function actionIndex()
    {
        return $this->render('@app/cleaner/views/index');
    }
    public function actionAssets()
    {
        foreach ((array)$this->assetPaths as $path) {
            $this->cleanDir($path);
            Yii::$app->session->addFlash(' cleaner','Assets path "'	. $path .	'" is cleaned.');
        }
        return $this->redirect(['index']);
    }
    public function actionRuntime()
    {
        foreach ((array)$this->runtimePaths as $path) {
            $this->cleanDir($path);
            Yii::$app->session->addFlash('cleaner','Runtime path "'	. $path .	'" is cleaned.');
        }
        return $this->redirect(['index']);
    }
    public function actionCache()
    {
        foreach ((array)$this->caches as $cache) {
            Yii::$app->get($cache)->flush();
            Yii::$app->session->addFlash('cleaner','Cache "'	. $cache . '" is cleaned.');
        }
        return $this->redirect(['index']);
    }
    private function cleanDir($dir)
    {
        $iterator = new \DirectoryIterator(Yii::getAlias($dir));
        foreach($iterator as $sub) {
            if(!$sub->isDot() && $sub->isDir()) {
                FileHelper::removeDirectory($sub->getPathname());
            }
        }
    }
}
```

2 Создание представления cleaner/views/index.php для метода actionIndex:
```php
<?php
    use yii\helpers\Html;
    /* @var $this yii\web\View */
    $this->title = 'Cleaner';
    $this->params['breadcrumbs'][] = $this->title;
?>
<div class="clean-index">
    <h1><?= Html::encode($this->title) ?></h1>
    <?php if (Yii::$app->session->hasFlash('cleaner' )): ?>
        <?php foreach ((array)Yii::$app->session->getFlash('cleaner', []) as $message):?>
            <div class="alert alert-success">
                <?= $message ?>
            </div>
        <?php endforeach; ?>
    <?php endif; ?>
    <p>
        <?= Html::a('Clear Caches', ['cache'], [
            'class' => 'btn btn-primary',
            'data' => [
                'confirm' => 'Are you sure you want to clear all cache data?', 'method ' => 'post',
            ],
        ]) ?>
        <?= Html::a('Clear Assets', ['assets'],
            ['class' => 'btn btn-primary',
            'data' => [
                'confirm' => 'Are you sure you want to clear all temporary assets?',
                'method ' => 'post',
            ],
        ]) ?>
        <?= Html::a('Clear Runtime', ['runtime'],
            ['class' => 'btn btn-primary',
            'data' => [
                'confirm' => 'Are you sure you want to clear all runtime files?',
                'method ' => 'post',
            ],
        ]) ?>
    </p>
</div>
```

3 Подключите контроллер к приложению через раздел controllerMap config/web.php:
```php
$config = [
    'id' => 'basic',
    'basePath' => dirname(__DIR__),
    'bootstrap' => ['log'],
    'controllerMap' => [
        'clean' => 'app\cleaner\CleanController',
    ],
    'components' => [
    ]...
];
```

4 Добавить новый пункт в Главное меню:
```php
echo Nav::widget([
    'options' => ['class' => 'navbar-nav navbar-right'],
    'items' => [
        ['label' => 'Home', 'url' => ['/site/index']],
        ['label' => 'Cleaner', 'url' => ['/clean/index']],
        ['label' => 'About', 'url' => ['/site/about']],
    ],
]);
```

5 Откройте контроллер и очистите активы:
![](img/335_1.jpg)

6 Если вы используете шаблон приложения yii2-app-advanced, просто укажите правильные пути в конфигурации:
```php
'controllerMap' => [
    'clean' => 'app\cleaner\CleanController',
    'assetPaths' => [
        '@backend/web/assets',
        '@frontend/web/assets',
    ],
    'runtimePaths' => [
        '@backend/runtime',
        '@frontend/runtime',
        '@console/runtime',
    ],
],
```
Теперь мы можем прикрепить контроллер к любому приложению.

Как это работает...
---
При запуске приложения и передаче маршрута, такого как clean/index, перед выполнением cleanController::actionIndex Yii проверяет, определен ли controllerMap. Поскольку у нас есть чистый контроллер, определенный там, Yii выполняет его вместо того, чтобы идти обычным путем.
В самом контроллере мы определили свойства assetPaths, runtimePaths и caches, чтобы иметь возможность подключать контроллер к приложениям с различными структурами каталогов и кэша. Мы устанавливаем его прикрепляя регулятор.

Смотрите так же
---
Чтобы узнать больше о контроллерах и о карте контроллеров, обратитесь к <http://www.yiiframework.com/doc-2.0/guide-structure-controllers.html>
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/structure-controllers> 





Создание виджета
===
Виджет-это многократно используемая часть представления, которая не только отображает некоторые данные, но и делает это в соответствии с некоторой логикой. Он может даже получать данные из моделей и использовать свои собственные представления, поэтому он похож на уменьшенную многоразовую версию модуля.
Давайте создадим виджет, который будет рисовать круговую диаграмму с помощью Google API.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать...
---

1 Создайте каталог виджетов и добавьте класс Chartwidget:
```php
<?php
namespace app\widgets;
use yii\base\Widget;
class Chartwidget extends Widget
{
    public $title;
    public $width = 300;
    public $height = 200;
    public $data = [];
    public $labels = [];
    public function run()
    {
        $path = 'http://chart.apis.google.com/chart';
        $query = http_build_query([
            'chtt' => $this->title,
            ' cht' => 'pc',
            'chs' => $this->width .	'x'	. $this->height,
            'chd' => 't:'	. implode(',', $this->data),
            ' chds ' => 'a',
            'chl' => implode('|', $this->labels),
            ' chxt' => 'y',
            'chxl' => '0:|0|' . max($this->data)
        ]);
        $url = $path .	'?'	. $query;
        return $this->render('chart', [
            'url' => $url,
        ]);
    }
}
```

2 Создать вид widgets/views/chart.php:
```php
<?php
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $url string */
?>
<div class="chart">
    <?= Html::img($url) ?>
</div>
```

3 Теперь создайте контроллер Chartcontroller:
```php
<?php
namespace app\controllers;
use yii\base\Controller;
class Chartcontroller extends Controller
{
    public function actionIndex()
    {
        return $this->render('index');
    }
}
```

4 Добавить представление views/chart/index.php:
```php
<?php
use app\widgets\ChartWidget;
use yii\helpers\Html;
/* @var $this yii\web\View */
$this->title = 'Chart';
$this->params['breadcrumbs'][] = $this->title;
?>
<div class="site-about">
    <h1><?= Html::encode($this->title) ?></h1>
    <?= ChartWidget::widget([
        'title' => 'My Chart Diagram',
        'data' => [100 - 32,32,],
        'labels' => [
            'Big',
            'Small',
        ],
    ]) ?>
</div>
```

5 Теперь попробуйте запустить действие index контроллера. Вы должны увидеть круговую диаграмму, как показано ниже:
![](img/339_1.jpg)

6 Вы можете показать любую диаграмму с различными размерами и наборами данных.

Как это работает...
---
Как и в любом другом типе расширения, мы создаем некоторые общие свойства, которые можно настроить при вызове виджета с помощью его метода widget. В этом случае мы настраиваем Заголовок, набор данных и метки данных.
Основным методом виджета является run(). В нашем виджете мы генерируем URL и визуализируем представление виджета, которое использует Google charting API для печати тега <img>.

Смотрите так же
---
Чтобы узнать больше о виджетах, обратитесь к <https://www.yiiframework.com/doc/guide/2.0/en/structure-widgets> 
 по русски  https://www.yiiframework.com/doc/guide/2.0/ru/structure-widgets 

Изготовление расширений дистрибутив - готовый рецепт в этой главе





Создание команд CLI
===
Yii имеет хорошую поддержку командной строки и позволяет создавать повторно используемые консольные команды. Консольные команды создаются быстрее, чем веб-GUI. Если вам нужно создать какую-то утилиту для вашего приложения, которая будет использоваться разработчиками или администраторами, консольные команды являются правильным инструментом.
Чтобы показать, как создать консольную команду, мы создадим простую команду, которая будет очищать различные вещи, такие как активы и временные каталоги.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать...
---
Выполните следующие шаги для создания команд CLI:

1 Создайте commands/cleanController.php файл со следующим кодом:
```php
<?php
namespace app\commands;
use yii\console\Controller;
use yii\helpers\FileHelper;
/**
* Removes content of assets and runtime directories.
*/
class CleanController extends Controller
{
    public $assetPaths = ['@app/web/assets'];
    public $runtimePaths = ['©runtime'];
    /**
    * Removes temporary assets.
    */
    public function actionAssets()
    {
        foreach ((array)$this->assetPaths as $path) {
            $this->cleanDir($path);
        }
        $this->stdout('Done' . PHP_EOL);
    }
    /**
    * Removes runtime content.
    */
    public function actionRuntime()
    {
        foreach ((array)$this->runtimePaths as $path) {
            $this->cleanDir($path);
        }
        $this->stdout('Done' . PHP_EOL);
    }
    private function cleanDir($dir)
    {
        $iterator = new \DirectoryIterator(\Yii::getAlias($dir));
        foreach($iterator as $sub) {
            if(!$sub->isDot() && $sub->isDir()) {
                $this->stdout('Removed '	. $sub->getPathname() . PHP_EOL);
                FileHelper::removeDirectory($sub->getPathname());
            }
        }
    }
}
```

2 Теперь мы можем использовать наш собственный контроллер консоли с настройками по умолчанию. Просто запустите сценарий оболочки yii:

***./yii***

3 Ищите собственные чистые команды:
```php
This is Yii version 2.0.7.
The following commands are available:
- asset	Allows you to combine...
asset/compress	Combines and compresses the asset.
asset/template	Creates	template of configuration file.
- clean	Removes	content of assets and runtime directories.
clean/assets	Removes	temporary assets.
clean/runtime	Removes	runtime content.
- fixture	Manages	fixture data loading and unloading.
fixture/load (default) Loads the specified fixture data.
fixture/unload	Unloads the specified fixtures.
```
4 Прямо сейчас запустите asset cleaning:

***.yii clean/assets***

5 Смотрите отчет о процессе:
```php
Removed /yii-book.app/web/assets/25f82b8a
Removed /yii-book.app/web/assets/9b3b2888
Removed /yii-book.app/web/assets/f4307424
Done
```

6 Если вы хотите использовать этот контроллер в приложении yii2-app-advanced, просто укажите пользовательские рабочие пути:
```php
return [
    'id' => 'app-console',
    'basePath' => dirname(__DIR__),
    'bootstrap' => ['log'],
    'controllerNamespace' => 'console\controllers',
    'controllerMap' => [
        'clean' => [
            'class' => 'console\controllers\CleanController',
            'assetPaths' => [
                '@backend/web/assets',
                '@frontend/web/assets',
            ],
            'runtimePaths' => [
                '@backend/runtime',
                '@frontend/runtime',
                '@console/runtime',
            ],
        ],
    ],
    // ...
];
```
Как это работает...
---
Все консольные команды должны быть расширены из класса yii\console\controller. Поскольку все консольные команды выполняются в yii\console\Application вместо yii\web\Application, у нас нет способа определить значение псевдонима @webroot. Кроме того, в шаблоне yii2-app-advanced по умолчанию есть подкаталоги backend, frontend и console. Для этого мы создаем настраиваемые общедоступные свойства assetPaths и runtimePaths.
Сама структура консольных команд похожа на типичный контроллер. Мы определяем несколько действий, которые мы можем выполнить через yii < консольная команда> / <командное действие>.
Как вы можете видеть, представления не используются, поэтому мы можем сосредоточиться на задачах программирования, а не на дизайне, разметке и так далее. Тем не менее, вам нужно предоставить некоторые полезные результаты, чтобы пользователи знали, что происходит. Это делается с помощью простых операторов PHP echo.
Если ваша команда относительно сложна, например message или migrate в комплекте с Yii, рекомендуется предоставить дополнительное описание доступных опций и действий. Это можно сделать, переопределив метод getHelp:
```php
public function getHelp()
{
    $out = "Clean command allows you to clean up various temporary data Yii and an application are generating.\n\n";
    return $out . parent::getHelp();
}
```
Выполните следующую команду:

***./yii help clean***

Вы можете увидеть полный вывод следующим образом:
```php
DESCRIPTION
Clean command allows you to clean up various temporary data Yii and an application are generating.
Removes content of assets and runtime directories.
SUB-COMMANDS
- clean/assets Removes temporary assets.
- clean/runtime Removes runtime content.
- ```
По умолчанию при выполнении команды оболочки:

***. /yii***

Мы видели упрощенное описание всех команд в списке вывода:
```php
- clean	Removes content of assets and runtime directories.
clean/assets	Removes temporary assets.
clean/runtime	Removes runtime content.
```
Это описание будет взято из комментариев перед классом и действия:
```php
/**
* Removes content of assets and runtime directories.
*/
class CleanController extends Controller
{
    /**
    * Removes temporary assets.
    */
    public function actionAssets() { ... }
    * Removes runtime content.
    */
    public function actionRuntime() { ... }
}
```
Он является обязательным для добавления описаний для ваших классов. Вы не должны делать это для своих собственных команд CLI.

Смотрите так же
---
* Рецепт создания многоразовых контроллеров в этой главе
* Изготовление расширений дистрибутив - готовый рецепт в этой главе




Создание фильтров
===
Фильтр-это класс, который может выполняться до / после выполнения действия. Его можно использовать для изменения контекста выполнения или оформления выходных данных. В нашем примере мы реализуем простой фильтр доступа, которая позволит пользователю видеть содержимое только после принятия пользовательского соглашения.

Подготовка 
---
Создайте новое приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>.

Как это сделать...
---

1 Создание модели формы соглашения:
```php
<?php
namespace app\models;
use yii\base\Model;
class AgreementForm extends Model
{
    public $accept;
    public function rules()
    {
        return [
            ['accept', 'required'],
            ['accept', 'compare', 'compareValue' => 1, 'message' => 'You must agree the rules.'],
        ];
    }
    public function attributeLabels()
    {
        return [
             'accept' => 'I completely accept the rules.'
        ];
    }
}
```

2 Создание службы проверки соглашений:
```php
<?php
namespace app\services;
use Yii;
use yii\web\Cookie;
class AgreementChecker
{
    public function isAllowed()
    {
        return Yii::$app->request->cookies->has('agree');
    }
    public function allowAccess()
    {
        Yii::$app->response->cookies->add(new Cookie([
            'name' => 'agree',
            'value' => 'on',
            'expire' => time() + 3600 * 24 * 90, // 90 days
        ]));
    }
}
```

 Он инкапсулирует работу с cookies соглашения.

 3 Создание класса фильтра:
```php
<?php
namespace app\filters;
use app\services\AgreementChecker;
use Yii;
use yii\base\ActionFilter;
class AgreementFilter extends ActionFilter
{
    public function beforeAction($action)
    {
        $checker = new AgreementChecker();
        if (!$checker->isAllowed()) {
            Yii::$app->response->redirect(['/content/agreement'])->send();
            return false;
        }
        return true;
    }
}
```

4 Создайте контроллер контента и присоедините фильтр к его поведениям:
```php
<?php
namespace app\controllers;
use app\filters\AgreementFilter;
use app\models\AgreementForm;
use app\services\AgreementChecker;
use Yii;
use yii\web\Controller;
class ContentController extends Controller
{
    public function behaviors()
    {
        return [
            [
            'class' => AgreementFilter::className(),
            'only' => ['index'],
            ],
        ];
    }
    public function actionIndex()
    {
        return $this->render('index');
    }
    public function actionAgreement()
    {
        $model = new AgreementForm();
        if ($model->load(Yii::$app->request->post()) && $model->validate()) {
            $checker = new AgreementChecker();
            $checker->allowAccess();
            return $this->redirect(['index']);
        } else {
            return $this->render('agreement', [
                'model' => $model,
            ]);
        }
    }
}
```

5 Добавьте views/content/index.php с личным контентом:
```php
<?php
    use yii\helpers\Html;
    /* 
       @var $this yii\web\View 
    */
    $this->title = 'Content';
    $this->params['breadcrumbs'][] = $this->title;
?>
<div class="site-about">
    <h1><?= Html::encode($this->title) ?></h1>
    <div class="well">This is our private page.</div>
</div>
```

6 Добавьте views/content/agreement.php на форму:
```php
<?php
    use yii\helpers\Html;
    use yii\bootstrap\ActiveForm;
    /* @var $this yii\web\View */
    /* @var $form yii\bootstrap\ActiveForm */
    /* @var $model app\models\AgreementForm */
    $this->title = 'User agreement';
    $this->params['breadcrumbs'][] = $this->title;
?>
<div class="site-login">
    <h1><?= Html::encode($this->title) ?></h1>
    <p>Please agree with our rules:</p>
    <?php $form = ActiveForm::begin(); ?>
        <?= $form->field($model, 'accept')->checkbox() ?>
        <div class="form-group">
            <?= Html::submitButton('Accept', ['class' => 'btn btn-success']) ?>
            <?= Html::a('Cancel', ['/site/index'], ['class' => 'btn btn-danger']) ?>
        </div>
    <?php ActiveForm::end(); ?>
</div>
```

7 Добавьте пункт главного меню в файл views/layouts/main.php:
```php
echo Nav::widget([
    'options' => ['class' => 'navbar-nav navbar-right'],
    'items' => [
        ['label' => 'Home', 'url' => ['/site/index']],
        ['label' => 'Content', 'url' => ['/content/index']],
        ['label' => 'About', 'url' => ['/site/about']],
    ];
]);
```

8 Попробуйте открыть страницу содержимого. Фильтр должен перенаправить вас на страницу соглашения:
![](img/347_1.jpg)

9 Только после принятия правил, вы можете увидеть содержимое:
![](img/347_2.jpg)

10 Также, вы можете прикрепить фильтр к другим контроллерам или модулям.

Как это работает...
---
Фильтр должен расширить в  класс yii\base\ActionFilter , который расширяет базовый метод yii\base\Behavior. Мы можем переопределить метод beforeAction или afterAction, если мы хотим сделать пост - и предфильтрацию.
Например, мы можем проверить доступ пользователей и выдать соответствующие HTTP-исключения в случае сбоя. В этом рецепте мы перенаправляем пользователя на страницу соглашения, если определенное значение cookie не существует:
```php
class AgreementFilter extends ActionFilter
{
    public function beforeAction($action)
    {
        $checker = new AgreementChecker();
        if (!$checker->isAllowed()) {
            Yii::$app->response->redirect(['/content/agreement'])->send();
            return false;
        }
        return true;
    }
}
```
Вы можете прикрепить фильтры к любому контроллеру или модулю. Чтобы указать список необходимых маршрутов, просто используйте опции only или except. Например, мы применяем наш фильтр только для индексного действия контроллера:
```php
public function behaviors()
{
    return [
        [
        'class' => AgreementFilter::className(),
        ' only' => ['index'],
        ],
    ];
}
```

***Замечание***:Не забудьте вернуть значение true в случае успеха из метода beforeAction. В противном случае действие контроллера не будет выполнено.

Смотрите так же
---
Дополнительные сведения о фильтрах см. в разделе  <http://www.yiiframework. com/doc -2.0/guide-structure -filters.html>. 
По русски https://www.yiiframework.com/doc/guide/2.0/ru/structure-filters

Для встроенного кэша и фильтров управления доступом обратитесь к:
http://www.yiiframework.com/doc-2.0/guide-caching-http.html
по русски https://www.yiiframework.com/doc/guide/2.0/ru/caching-http

Рецепт создания моделей поведения




Создание модулей
===
Если вы создали сложную часть приложения и хотите использовать ее с некоторой степенью настройки в следующем проекте, скорее всего, вам нужно создать модуль. В этом рецепте мы увидим, как создать модуль просмотра журнала приложений.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
Давайте сначала немного спланируем.
В yii2-app-basic с конфигурацией по умолчанию все записи журнала хранятся в runtime/logs/app.log. Мы можем извлечь все сообщения из этого файла с помощью регулярных выражений и отобразить их в виджете GridView. Кроме того, мы должны позволить пользователю настроить путь к пользовательскому файлу журнала.
Выполните следующие действия:

1 Создайте каталог modules/log и создайте класс Module с опцией new file:
```php
<?php
namespace app\modules\log;
class Module extends \yii\base\Module
{
    public $file = '@runtime/logs/app.log';
}
```

2 Создайте простую модель для переноса строк из файла журнала:
```php
<?php
namespace app\modules\log\models;
use yii\base\Object;
class LogRow extends Object
{
    public $time;
    public $ip;
    public $userId;
    public $sessionId;
    public $level;
    public $category;
    public $text;
}
```

3 Напишите класс чтения файла журнала, который будет анализировать строки файла, изменять их порядок и возвращать массив экземпляров моделей LogRow:
```php
<?php
namespace app\modules\log\services;
use app\modules\log\models\LogRow;
class LogReader
{
    public function getRows($file)
    {
        $result = [];
        $handle = @fopen($file, "r");
        if ($handle) {
            while (($row = fgets($handle)) !== false) {
                $pattern = '#A'	.
                    '(?P<time>\d{4}\-\d{2}\-\d{2} \d{2}:\d{2}:\d{2}) ' .
                    '\[(?P<ip>[A\]]+)\]' .
                    '\[(?P<userId>[A\]]+)\]' .
                    '\[(?P<sessionId>[A\]]+)\]' .
                    '\[(?P<level>[A\]]+)\]'	.
                    '\[(?P<category>[A\]]+)\]'	.
                    ' (?P<text>.*?)' .
                    '(\$\_(GET|POST|REQUEST|COOKIE|SERVER) = \[)?' .
                    '$#i';
                    if (preg_match($pattern, $row, $matches)) {
                        if ($matches['text']) {
                            $result[] = new LogRow([
                                'time' => $matches['time'],
                                'ip' => $matches['ip'],
                                'userid' => $matches['userId'],
                                'sessionid' => $matches['sessionId'],
                                'level' => $matches['level'],
                                'category' => $matches['category'],
                                'text' => $matches['text'],
                            ]);
                        }
                    }
            }
            fclose($handle);
        }
            return array_reverse($result);
    }
}
```

4 Добавьте помощника для отображения симпатичных HTML-бейджиков для уровней логов:
```php
<?php
namespace app\modules\log\helpers;
use yii\helpers\ArrayHelper;
use yii\helpers\Html;
class LogHelper
{
    public static function levelLabel($level)
    {
        $classes = [
            ' error ' => 'danger',
            'warning' => 'warning',
            ' info ' => 'primary',
            'trace' => 'default',
            'profile' => 'success',
            'profile begin' => 'info',
            'profile end' => 'info',
        ];
        $class = ArrayHelper::getValue($classes, $level, 'default');
        return Html::tag('span', Html::encode($level), ['class' => 'label-' . $class]);
    }
}
```

5 Создайте контроллер модуля, который получит массив строк от читателя и передаст их в ArrayDataProvider:
```php
<?php
namespace app\modules\log\controllers;
use app\modules\log\services\LogReader;
use yii\data\ArrayDataProvider;
use yii\web\Controller;
class DefaultController extends Controller
{
    public function actionIndex()
    {
        $reader = new LogReader();
        $dataProvider = new ArrayDataProvider([
            'allModels' => $reader->getRows($this->getFile()),
        ]);
        return $this->render('index', [
            'dataProvider' => $dataProvider,
        ]);
    }
    private function getFile()
    {
            return \Yii::getAlias($this->module->file);
    }
}
```

6 Теперь создайте файл представления modules/log/default/index.php:
```php
<?php
use app\modules\log\helpers\LogHelper;
use app\modules\log\models\LogRow;
use yii\grid\GridView;
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $dataProvider yii\data\ArrayDataProvider */
$this->title = 'Application log';
$this->params['breadcrumbs'][] = $this->title;
?>
<div class="log-index">
    <h1><?= Html::encode($this->title) ?></h1>
    <?= GridView::widget([
        'dataProvider' => $dataProvider,
        'columns' => [
            [
                'attribute' => 'time',
                'format' => 'datetime',
                'contentOptions' => [
                    'style' => 'white-space: nowrap',
                ],
            ],
            ' ip:text :IP',
            'userid:text:User ',
            [
                'attribute' => 'level',
                'value' => function (LogRow $row) {
                    return LogHelper::levelLabel($row->level);
                },
                'format' => 'raw',
            ],
            'category',
            ' text',
        ],
    ]) ?>
</div>
```

7 Подключите модуль к приложению в config/web.php:
```php
$config = [
    'id' => 'basic',
    'basePath' => dirname(__DIR__),
    'bootstrap' => ['log'],
    'modules' => [
        'log' => 'app\modules\log\Module',
    ],
    'components' => [
    
    ],
    ...
];
```

8 Добавьте ссылку на контроллер в файл views/layouts/main.php:
```php
echo Nav::widget([
    'options' => ['class' => 'navbar-nav navbar-right'],
    'items' => [
        ['label' => 'Home', 'url' => ['/site/index']],
        ['label' => 'Log', 'url' => ['/log/default/index']],
        ['label' => 'About', 'url' => ['/site/about']],
        ['label' => 'Contact', 'url' => ['/site/contact']],
    ],
]);
NavBar::end();
```

9 Перейти к url/index.php?r=log и убедиться, что модуль работает:
![](img/352_1.jpg)

Как это работает...
---
Можно группировать контроллеры, модели, представления и другие компоненты по отдельным модулям и присоединять их к приложению. Вы можете сгенерировать шаблон модуля с помощью Gii или сделать это вручную.
Каждый модуль содержит основной класс модуля, где мы можем определить настраиваемые свойства, определить пути изменения, присоединить контроллеры и так далее. По умолчанию модуль, сгенерированный с помощью Gii, выполняет index action контроллера по умолчанию.

Смотрите так же
---

* Дополнительные сведения о модулях и рекомендациях см. в разделе
<http://www.yiiframework.com/doc-2.0/guide-structure-modules.html>
По русски <https://www.yiiframework.com/doc/guide/2.0/ru/structure-modules>
* Делая расширения распределени-готовый рецепт




Создание пользовательского средства визуализации представлений
===
Есть много PHP шаблонов двигателей . Yii2 предлагает только собственные шаблоны PHP. Если вы хотите использовать один из существующих движков шаблонов или создать свой собственный, вы должны реализовать его-конечно, если он еще не реализован сообществом Yii.
В этом рецепте мы повторно реализуем поддержку шаблонов Smarty.

Подготовка 
---

1 Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Установите  Smarty library:

***composer require smarty/smarty***

Как это сделать...
---
Выполните следующие действия для создания пользовательского средства визуализации представлений:

1 Создайте файл smarty/ViewRenderer.php:
```php
<?php
namespace app\smarty;
use Smarty;
use Yii;
class ViewRenderer extends \yii\base\ViewRenderer
{
    public $cachePath = '@runtime/smarty/cache';
    public $compilePath = '@runtime/smarty/compile';
    /**
    * @var Smarty
    */
    private $smarty;
    public function init()
    {
        $this->smarty = new Smarty();
        $this->smarty->setCompileDir(Yii::getAlias($this->compilePath));
        $this->smarty->setCacheDir(Yii::getAlias($this->cachePath));
        $this->smarty->setTemplateDir([
            dirname(Yii::$app->getView()->getViewFile()),
            Yii::$app->getViewPath(),
        ]);
    }
    public function render($view, $file, $params)
    {
        $templateParams = empty($params) ? null : $params;
        $template = $this->smarty->createTemplate($file, null, null,$templateParams, false);
        $template->assign('app', \Yii::$app);
        $template->assign('this', $view);
        return $template->fetch();
    }
}
```

2 Теперь нам нужно соединить представление renderers к приложению. В config/web.php нужно добавить представление компонента renderers:
```php
'components' => [
    'view' => [
        'renderers ' => [
            'tpl' => [
                'class' => 'app\smarty\ViewRenderer',
            ],
        ],
    ].
];
```

3 Теперь давайте проверим это. Создание нового SmartyController:
```php
<?php
namespace app\controllers;
use yii\web\Controller;
class SmartyController extends Controller
{
    public function actionIndex()
    {
        return $this->render('index.tpl', [
            'name' => 'Bond ',
        ]);
    }
}
```

4 Далее нам нужно создать views/smarty/index.tpl:
```php
<div class="smarty-index">
    <h1>Smarty Example</h1>
    <p>Hello, {$name}!</p>
</div>
```

5  Теперь попробуйте запустить контроллер. В случае успеха вы должны получить следующие выходные данные:
![](img/355_1.jpg)

Как это работает...
---
Средство визуализации представления является дочерним для абстрактного класса yii\base\viewRenderer, реализующего только один метод, называемый render:
```php
<?php
namespace yii\base;
abstract class ViewRenderer extends Component
{
    /**
    * Renders a view file.
    *
    * This method is invoked by [[View]] whenever it tries to render a view.
    * Child classes must implement this method to render the given view file.
    *
    * @param View $view the view object used for rendering the file.
    * @param string $file the view file.
    * @param array $params the parameters to be passed to the view file.
    * @return string the rendering result
    */
    abstract public function render($view, $file, $params);
}
```
Поэтому мы получаем компонент представления, путь к файлу и переменные визуализации. Нужно обработать файл и возвраnbnm готовый результат. В нашем случае сама обработка осуществляется шаблонным движком Smarty, поэтому нам нужно правильно инициализировать его и вызвать его методы обработки:
```php
class ViewRenderer extends \yii\base\ViewRenderer
{
    public $cachePath = '@runtime/smarty/cache';
    public $compilePath = '@runtime/smarty/compile';
    private $smarty;
    public function init()
    {
        $this->smarty = new Smarty();
        $this->smarty->setCompileDir(Yii::getAlias($this->compilePath));
        $this->smarty->setCacheDir(Yii::getAlias($this->cachePath));
        $this->smarty->setTemplateDir([
            dirname(Yii::$app->getView()->getViewFile()),
            Yii::$app->getViewPath(),
        ]);
    }
}
```
Рекомендуется хранить временные файлы Yii в каталоге среды выполнения приложения. Вот почему мы устанавливаем каталог компиляции, где Smarty хранит свои шаблоны, скомпилированные в PHP, в runtime/smarty/compile.
Сам рендеринг немного проще:
```php
public function render($view, $file, $params)
{
    $templateParams = empty($params) ? null : $params;
    $template = $this->smarty->createTemplate($file, null, null, $templateParams, false);
    $template->assign('app', \Yii::$app);
    $template->assign('this', $view);
    return $template->fetch();
}
```
Весь набор данных через $this ->render передается шаблону Smarty как есть. Кроме того, мы создаем специальные переменные шаблона Smarty с именем app, и это указывает на Yii: :$app и Yii: :$app->view и позволяет нам получить свойства приложения внутри шаблона.
Затем мы визуализируем шаблоны.

Смотрите так же
---
Вы можете подготовиться к использованию smarty view renderer с плагинами и поддержкой конфигурации по адресу <https ://githnb.com/yiisoft/yii2-smarty>.

Дополнительные сведения о средствах визуализации Smarty и view в целом см. по следующим URL-адресам:<http://www. smarty.net>
* <http://www.viiframework.com/doc-2.0/guide-tutorial-templateengines.html>
* <http://www.yiiframework.com/doc-2.0/guide-structure-views.html>
по русски  <https://www.yiiframework.com/doc/guide/2.0/ru/structure-views>




Создание многоязычного приложения
===
С каждым днем мы встречаем все больше международных компаний, программных продуктов и информационных ресурсов, публикующих контент на нескольких языках. Yii2 обеспечивает встроенную поддержку i18n для создания многоязычных приложений.
В этом рецепте мы переводим интерфейс приложения на разные языки.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---

1 Изменение основной надписи в меню views/layouts/main.php в файле для использования метода Yii: : t(' app/nav','...'):
```php
echo Nav::widget([
    'options' => ['class' => 'navbar-nav navbar-right'],
    'items' => [
        ['label' => Yii::t('app/nav', 'Home'), 'url' => ['/site/index']],
        ['label' => Yii::t('app/nav', 'About'), 'url' => ['/site/about']],
        ['label' => Yii::t('app/nav', 'Contact'), 'url' => ['/site/contact']],
        ...
    ], 
]);
```

2 Измените все заголовки и хлебные крошки, чтобы использовать метод Yii ::t(' app, '...'):
```php
$this->title = Yii::t('app', 'Contact');
$this->params['breadcrumbs'][] = $this->title;
```

3 Кроме того, измените все метки кнопок:
```php
<div class="form-group">
    <?= Html::submitButton(Yii::t('app', 'Submit'), ['class' => 'btn btn-primary']) ?>
</div>
```
Изменение других жестко закодированных сообщений, а также:
```php
<p>
    <?= Yii::t('app', 'The above error occurred while the Web server was processing your request.') ?>
</p>
```

4 Изменение меток атрибутов модели ContactForm:
```php
class LoginForm extends Model
{
    public function attributeLabels()
    {
        return [
            'username' => Yii::t('app/user', 'Username'),
            'password' => Yii::t('app/user', 'Password'),
            'rememberMe' => Yii::t('app/user', 'Remember Me'),
        ];
    }
}
```
Кроме того, измените метки атрибутов модели LoginForm:
```php
class ContactForm extends Model
{
    public function attributeLabels()
    {
        return [
            'name' => Yii::t('app/contact', 'Name'),
            'email' => Yii::t('app/contact', 'Email'),
            'subject' => Yii::t('app/contact', 'Subject'),
            'body' => Yii::t('app/contact', 'Body'),
            'verifyCode' => Yii::t('app', 'Verification Code'),
        ];
    }
}
```
Он будет выводить переведенные метки для текущего языка вместо оригиналов.


5 Для подготовки переводов создайте каталог Сообщений. Прямо сейчас мы можем создать файлы перевода для всех необходимых языков. Мы можем сделать это вручную, но есть полезный искатель, который может сканировать все файлы проекта и извлекать все сообщения из конструкций Yii ::t (). Давайте использовать его.

6 Создайте файл конфигурации для сканера Сообщений:

***./yii message/config-template config/messages.php***

7 Откройте файл конфигурации и задайте следующие значения:
```php
<?php
return [
    'sourcePath' => '@app',
    'languages' => ['de',	'fr'],
    'translator' => 'Yii::t',
    'sort' => false,
    'removeUnused' => false,
    'markUnused' => true,
    'only' => ['*.php'],
    'except' => [
        '.svn',
        '.git',
        '.gitignore',
        '.gitkeep',
        '.hgignore',
        '.hgkeep',
        '/messages',
        '/vendor',
    ],
    'format' => 'php',
    'messagePath' => '@app/messages',
    'overwrite' => true,
    'ignoreCategories' => [
        'yii',
    ],
];
```

8 Запустите искатель, передавая ему этот файл конфигурации:

***./yii message config/messages.php***

9 После завершения процесса, мы должны получить следующую структуру каталогов:
![](img/360_1.jpg)

10 Например, файл messages/de/app/contact содержит следующее содержимое:
```php
<?php...
return [
    'Body' => '',
    'Email' => '',
    'Name' => '',
    'Subject' => '',
];
```
11 Это простой массив PHP с оригинальными предложениями в ключах и переведенными сообщениями в значениях.

12 Просто введите значения, необходимые для перевода сообщений из немецкого:
```php
<?php.
return [
    'Password' => 'Passwort',
    'Remember Me' => 'Erinnere dich an mich',
    'Username' => 'Benutzername',
];
```

13 Прикрепите эти переводы к компоненту ii8n приложения в файле config/web.php:
```php
$config = [
    'id' => 'basic',
    'basePath' => dirname(__DIR__),
    'bootstrap' => ['log'],
    'components' => [
        'i18n' => [
            'translations' => [
                'app*' => [
                    'class' => 'yii\i18n\PhpMessageSource',
                    'sourceLanguage' => 'en-US',
                ],
            ],
        ],
        'db' => require(	DIR	 .	'/db.php'),
    ],
    'params' => $params,
];
```

14 Откройте страницу входа с языком по умолчанию:
![](img/361_1.jpg)

15 Переключить язык приложения на de:
```php
$config = [
    'id' => 'basic',
    'language' => 'de',
    'basePath' => dirname(__DIR__),
    'bootstrap' => ['log'],
];
```
Затем обновите страницу входа
![](img/362_1.jpg)

16 Встроенные в фреймворк сообщения и ошибки проверки по умолчанию будут переведены автоматически.

Как это работает...
---
Yii2 предоставляет метод yii::t() для перевода сообщений интерфейса через компонент ii8n, который поддерживает различные типы источников. В этом рецепте мы используем yii\ii8n\hpMessageSource, который хранит переведенные сообщения в простых файлах PHP.
Фреймворк не имеет искусственного интеллекта и не переводит сообщения сам по себе. Подготовленные переводы необходимо поместить в файлы или в базу данных и фреймворк, чтобы получить необходимое сообщение из этого источника.
Текущий язык можно задать вручную:
```php
$config = [
    'id' => ' basic',
    ' language' => 'de',
];
```
Вместо настройки языка в файле конфигурации можно переключить язык приложения во время выполнения
```php
Yii::$app->language = 'fr';
```
Например, если язык пользователя хранится в поле lang модели пользователя, можно создать загрузчик языка:
```php
<?php
namespace app\bootstrap;
use yii\base\BootstrapInterface;
class LanguageBootstrap implements BootstrapInterface
{
    public function bootstrap($app)
    {
        if (!$app->user->isGuest) {
            $app->language = $app->user->identity->lang;
        }
    }
}
```
Зарегистрировать этот класс в списке загрузки:
```php
$config = [
    'id' => ' basic',
    'basePath' => dirname(__DIR__),
    'bootstrap' => ['log', 'app'bootstrap\LanguageBoostrap'],
];
```
Теперь каждый аутентифицированный пользователь увидит интерфейс на своем языке.
Кроме того, можно переопределить класс yii\web\UrlManager для передачи текущего языка в качестве параметра GET или префикса URL-адреса. Кроме того, в качестве альтернативы вы можете хранить выбранные языки в файлах cookie браузера.
При создании моделей и другого кода с помощью Gii можно выбрать следующий параметр:
![](img/363_1.jpg)

Все метки в сгенерированном коде будут включены в вызовы Yii::t().
***Замечание*** Мы не рассматривали перевод содержания модели в этом рецепте. Однако, например, можно хранить переведенные тексты в отдельных таблицах (например, в таблице post_lang для таблицы post model) в базе данных и использовать значение свойства Yii:: $app - >language для получения текущего языка и извлечения необходимого содержимого для моделей по значению.

Смотрите так же
---
 Для получения дополнительной информации об интернационализации в Yii2, обратитесь к 
<https://www.yiiframework.com/doc/guide/2.0/en/tutorial-i18n>
по русски <https://www.yiiframework.com/doc/guide/2.0/ru/tutorial-i18n> 




Подготовка расширений к распространению
===
В этой главе вы узнали, как создавать различные типы расширений Yii. Сейчас мы поговорим о том, как поделиться своими результатами с людьми, и почему это важно.

Подготовка
---
Давайте сначала сформируем контрольный список для хорошего расширения. Хороший продукт программирования должен следовать этим пунктам:
* Хороший стиль кодирования
* Люди должны быть в состоянии найти его
* Последовательный, легкий для чтения, и легкий для использования API
* Хорошая документация
* Расширение должно применяться к наиболее распространенным случаям использования
* Следует сохранить
* Хорошо протестированный код, в идеале с модульными тестами
* Вы должны обеспечить поддержку для него
Конечно, все это требует много работы, но она необходима для создания хорошего продукта.

Как это сделать...
---
1 В каждом современном продукте  PHP должен соответствовать стандартам PSR4 автозагрузки и PSR1 и PSR2 стандарты стиля кодирования от http://www.php-fig.org/psr/.

2 Давайте рассмотрим наш список более подробно, начиная с API. API должен быть последовательным, легким для чтения и простой в использовании. Непротиворечивость означает, что общий стиль не должен изменяться, поэтому не должно быть других имен переменных, несогласованных имен, таких как isFlagi() и isNotFlag2 (), и так далее. Все должно подчиняться правилам, определенным для кода. Это позволяет меньше проверять документацию и позволяет сосредоточиться на кодировании.

3 Код без документации практически бесполезен. Исключением является сравнительно простой код, но даже если это всего несколько строк, это не правильно, если нет ни одного слова о том, как установить и использовать его. Что делает хорошую документацию? Цель кода и его плюсы должны быть как можно более заметны и должны быть написаны громко и ясно.

4 Код бесполезен, если разработчики не знают, куда ее девать и что должно быть в конфигурации приложения. Не ожидайте, что люди знают, как делать специфичные для фреймворка вещи. Руководство по установке должно быть подробным. Большинство разработчиков предпочитают пошаговую форму. Если для работы кода требуется схема SQL, предоставьте ее.

5 Даже если ваши методы и свойства API названы правильно, вам все равно нужно документировать их комментариями PHPDoc с указанием типов аргументов и возвращаемых типов, предоставляя краткое описание для каждого метода. Не забывайте о защищенных и закрытых методах и свойствах, так как иногда необходимо прочитать их, чтобы понять детали того, как работает код. Кроме того, рассмотрите возможность перечисления открытых методов и свойств в документации, чтобы ее можно было использовать в качестве ссылки.

6 Предоставьте примеры вариантов использования с хорошо прокомментированным кодом. Попробуйте охватить наиболее распространенные способы использования расширения.

7 В примере не пытайтесь решить несколько проблем одновременно, так как это может сбить с толку.

8 Важно сделать код гибким, чтобы он применялся ко многим случаям использования. Однако, поскольку невозможно создать код для всех возможных вариантов использования, попробуйте охватить наиболее распространенные.

9 Важно, чтобы люди чувствовали себя комфортно. Предоставление хорошей документации-это первый шаг. Второй-это доказательство того, что ваш код работает должным образом и будет работать с дальнейшими обновлениями. Лучший способ сделать это-набор модульных тестов.

10 Расширение должно поддерживаться, по крайней мере, до тех пор, пока оно не станет стабильным, и больше не будет запросов функций и сообщений об ошибках. Поэтому ждите вопросов и отчетов, и оставляйте некоторое время для дальнейшей работы над кодом. Если Вы не можете посвятить больше времени поддержке расширений, но это очень инновационно, и никто не делал этого раньше, все равно стоит поделиться. Если сообществу это нравится, кто-то обязательно предложит свою помощь.

11 Наконец, необходимо сделать расширения доступными. Создайте пакет Composer из своего расширения, вставьте его в GitHub или другое общее хранилище репозитория и опубликуйте на сайте https://packagist.org.

12 Каждое расширение должно иметь номер версии и журнал изменений. Это позволит сообществу проверить, если у них есть последняя версия и проверить, что изменилось перед обновлением. Мы рекомендуем следовать семантическим правилам управления версиями с сайта http://semver.org.

13 Даже если ваше расширение относительно простое и документация хорошая, могут возникнуть вопросы, и в первый раз единственный человек, который может ответить на них, - это вы. Обычно вопросы задают на официальных форумах, поэтому лучше создать тему, где люди смогут обсудить ваш код и предоставить ссылку на странице расширения.

Как это работает...
---
Если вы хотите поделиться расширением с сообществом и быть уверены, что оно будет полезным и популярным, вам нужно сделать больше, чем просто написать код. Сделать распространение расширений готовым гораздо больше работы. Он может быть даже больше, чем создание самого расширения. Итак, почему хорошо делиться расширениями с сообществом в первую очередь?
Создание кода, который вы используете в своих собственных проектах с открытым исходным кодом, имеет свои плюсы. Вы получаете людей, намного больше людей, чем вы можете получить, чтобы проверить свой проект с закрытым исходным кодом. Люди, которые используют ваше расширение, тестируют его, дают ценные отзывы и сообщают об ошибках. Если ваш код популярен, будут страстные разработчики, которые попытаются улучшить ваш код, сделать его более обширным, более стабильным и многоразовым. Кроме того, вы просто чувствует себя хорошо, потому что вы делаете доброе дело.
Мы рассмотрели самые важные вещи. Тем не менее, есть больше вещей, чтобы проверить. Попробуйте существующие расширения, прежде чем писать свои собственные. Если расширение почти подходит, попробуйте связаться с автором расширения и внести свои идеи. Просмотр существующего кода поможет вам найти полезные трюки, dos и Don'TS. Кроме того, время от времени проверяйте Вики-статьи и официальный форум; есть много полезной информации о создании расширений и разработке с использованием Yii в целом.

Смотрите так же
---
* Для современной информации о стандарты кодирования PHP, см. <http://www.php-fig. org/psr/>
* Дополнительные сведения о семантическом управлении версиями см. в разделе <http://semver.org>




Следуя передовой практике
===
В этом рецепте вы увидите, как настроить Yii2 для лучшей производительности и некоторые дополнительные принципы построения адаптивных приложений. Эти принципы являются как общими, так и связанными с Yii. Поэтому, мы будем таблицей для того чтобы приложить некоторые из этих даже без использования Yii2.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---

1 Обновить PHP до последней стабильной версии. Основные выпуски PHP могут принести значительные улучшения производительности. Выключите режим отладки и установите среду prod. Это можно сделать путем редактирования web/index.php следующим образом:
```php
defined('YII_DEBUG') or define('YII_DEBUG', false);
defined('YII_ENV') or define('YII_ENV', 'prod');
```

***Замечание***: В скелете приложения yii2-app-advanced можно использовать команду оболочки php init и производственную среду opt для загрузки оптимизированного index.php и конфигурационных файлов.

2 Включить компонент кэша:
```php
'components' => [
    'cache' => [
        'class' => 'yii\caching\FileCache',
    ],
],
```
Вы можете использовать любой кэш-памяти вместо FileCache. Кроме того, вы можете зарегистрировать несколько компонентов приложения кэша и использовать Yii::$app ->cache и Yii::$app ->cache2 для различных типов данных:
```php
'components' => [
    'cache' => [
        'class' => 'yii\caching\MemCache',
        'useMemcached' => true,
    ],
    'cache2' => [
        'class' => 'yii\caching\FileCache',
    ],
],
```
Фреймворк использует компонент кэша по умолчанию в своих собственных классах.

3 Включить кэширование схемы таблицы для компонента БД следующим образом:
```
return [
    // ...
    'components' => [
        // ...
        'cache' => [
            'class' => 'yii\caching\FileCache',
        ],
        'db' => [
            'class' => 'yii\db\Connection',
            'dsn' => 'mysql:host=localhost;dbname=mydatabase',
            'username' => 'root',
            'password' => '',
            'enableSchemaCache' => true,
            // Optional. Default value is 3600 seconds
            schemaCacheDuration' => 3600,
            // Optional. Default value is 'cache'
            'schemaCache' => 'cache',
        ],
    ],
];
```

4 Используйте простые массивы вместо активных объектов записей для перечисления наборов элементов:
```php
$categoriesArray = Categories::find()->asArray()->all();
```

5 Используйте each () вместо all () в foreach для большого количества результатов:
```php
foreach (Post::find()->each() as $post) {
    // ...
}
```

6 Поскольку autoloader Composer используется для включения большинства файлов сторонних классов, рекомендуется оптимизировать его, выполнив следующую команду:

***composer dump-autoload –o***

Как это работает...
---
Если YII_DEBUG имеет значение false, Yii отключает ведение журнала на уровне трассировки и использует меньше кода обработки ошибок. Кроме того, при установке YII_ENV в prod приложение не загружает модули панели Yii и отладки.
Установка schemaCachingDuration в несколько секунд позволяет кэшировать схему базы данных, используемую активной записью Yii. Это настоятельно рекомендуется для рабочих серверов и значительно повышает производительность активных записей. Чтобы он работал, необходимо правильно настроить компонент кэша следующим образом:
```php
'cache' => [
    'class' => 'yii\cache\FileCache',
],
```
Включение кэша также положительно влияет на другие компоненты Yii. Например, маршрутизатор Yii или urlManager начинает кэшировать маршруты.
Конечно, можно попасть в ситуацию, когда предыдущие настройки не помогут достичь достаточного уровня производительности. В большинстве случаев это означает, что либо само приложение является узким местом, либо вам нужно больше оборудования.
* ***Производительность на стороне сервера-это только часть общей картины***: производительность на стороне сервера-это только одна из вещей, которые влияют на общую производительность. Благодаря оптимизации клиентской части, такой как обслуживание CSS, изображений и файлов JavaScript, правильное кэширование и минимизация количества HTTP-запросов может дать хороший визуальный прирост производительности даже без оптимизации кода PHP.
* ***Вещи, которые нужно сделать без использования Yii***: некоторые вещи лучше всего делать без Yii. Например, изменение размера изображения на лету лучше в отдельном PHP-скрипте, чтобы избежать дополнительных затрат.
* ***Active Record versus Query Builder и SQL***: использование Построителя запросов или SQL в критически важных для производительности частях приложения. Как правило, AR наиболее полезен при добавлении и редактировании записей, поскольку он добавляет удобный слой проверки и менее полезен при выборе записей.
* ***Всегда сначала проверяйте медленные запросы***: база данных может стать узким местом за секунду, если Разработчик случайно забудет добавить индекс в таблицу, которая читается часто или наоборот, или добавит слишком много индексов в таблицу, в которую мы пишем очень часто. То же самое касается выбора ненужных данных и ненужных объединений.
* ***Кэширование или сохранение результатов тяжелых процессов***: если вы можете избежать запуска тяжелого процесса при каждой загрузке страницы, лучше сделать это. Например, рекомендуется сохранить или кэшировать результаты разбора текста markdown, очистить его (это очень ресурсоемкий процесс) один раз, а затем использовать готовый к отображению HTML.
* ***Обработка слишком много обработки***: иногда слишком много обработки, чтобы быть обработаны немедленно. Это может быть построение сложных отчетов или просто отправка электронной почты (если ваш проект сильно загружен). В этом случае лучше поставить его в очередь и обработать позже с помощью cron или других специализированных инструментов.

Смотрите так же
---
Дополнительные сведения о настройке производительности и кэшировании см. по следующим URL-адресам:
* <http://www.yiiframework.eom/doc-2.0/guide-tutorial-performance-tnning.html>
 по русски ,https://www.yiiframework.com/doc/guide/2.0/ru/tutorial-performance-tuning>
* <http://www.yiiframework.com/doc-2.0/guide-cachjng-overv'ew.html>
 по русски <https://www.yiiframework.com/doc/guide/2.0/ru/caching-overview>




Ãëàâà 9. Íàñòðîéêà ïðîèçâîäèòåëüíîñòè
===
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:
* Ëó÷øèå ïðàêòèêè
* Óñêîðåíèå îáðàáîòêè ñåññèè
* Èñïîëüçîâàíèå çàâèñèìîñòåé êåøà è öåïî÷åê
* Ïðîôèëèðîâàíèå ïðèëîæåíèÿ ñ ïîìîùüþ Yii
* Èñïîëüçîâàíèå êýøèðîâàíèÿ HTTP
* Îáúåäèíåíèå è ìèíèìèçàöèÿ àêòèâîâ
* Çàïóñê Yii2 íà HHVM

Yii ÿâëÿåòñÿ îäíèì èç ñàìûõ áûñòðûõ äîñòóïíûõ ôðåéìâîðêîâ. Òåì íå ìåíåå ïðè ðàçðàáîòêå è ðàçâåðòûâàíèè ïðèëîæåíèÿ ðåêîìåíäóåòñÿ èìåòü äîïîëíèòåëüíóþ ïðîèçâîäèòåëüíîñòü áåñïëàòíî è ñëåäîâàòü ðåêîìåíäàöèÿì äëÿ ñàìîãî ïðèëîæåíèÿ. Â ýòîé ãëàâå âû óâèäèòå, êàê íàñòðîèòü yii äëÿ ïîëó÷åíèÿ äîïîëíèòåëüíîé ïðîèçâîäèòåëüíîñòè. Êðîìå òîãî, âû óçíàåòå íåêîòîðûå ðåêîìåíäàöèè ïî ðàçðàáîòêå ïðèëîæåíèÿ, êîòîðîå áóäåò ðàáîòàòü ãëàäêî, ïîêà ó âàñ íå áóäåò î÷åíü âûñîêèõ íàãðóçîê.



Ускорение обработки сеансов
===
Обработка собственных сеансов в PHP в большинстве случаев прекрасна. Существует по крайней мере две возможные причины, по которым вы захотите изменить способ обработки сеансов:
* При использовании нескольких серверов необходимо иметь общее хранилище сеансов для обоих серверов.
* Сеансы PHP по умолчанию используют файлы, поэтому максимальная возможная производительность ограничена дисковым вводом-выводом.
* Сеансы PHP по умолчанию блокируют параллельные хранилища сеансов. В этом рецепте мы увидим, как использовать эффективное хранение для сеансов Yii.
 
Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>
и установить сервер Memcache и расширение MEMCACHE PHP.

Как это сделать...
---
Мы будем стресс-тестировать веб-сайт с помощью инструмента Apache ab. Он распространяется с двоичными файлами Apache, поэтому, если Вы используете Apache, вы найдете его в каталоге bin.

1 Выполните следующую команду, заменив ваш сайт фактическим именем хоста, который вы используете:

***ab -n 1000 -c 5 http://yii-book.app/index.php?r=site/contact***

Это будет посылать 1000 запросов, пять одновременно, и будет выводить статистику следующим образом:
```php
This is ApacheBench, Version 2.3 <$Revision: 1528965 $>
Copyright 1996 Adam Twiss, Zeus Technology Ltd, http://www.zeustech.net/
Licensed to The Apache Software Foundation, http://www.apache.org/
Server	Software:	nginx
Server	Hostname:	yii-book.app
Server	Port:	80
Document	Path:	/index.php?r=site/contact
Document	Length:	14866 bytes
Concurrency Level:	5
Time taken for tests:	10.961 seconds
Complete requests:	1000
Failed	requests:	0
Total transferred:	15442000 bytes
HTML transferred:	14866000 bytes
Requests	per second:	91.24 [#/sec] (mean)
Time per	request:	54.803 [ms] (mean)
Time per	request:	10.961 [ms] (mean, across all concurrent requests)
Transfer rate:	1375.84 [Kbytes/sec] received
Connection Times (ms)
                   min	 mean[+/-sd] median max
Connect:	0	0	0.0	0	0
Processing:	18	55	324.9	29	4702
Waiting:	15	41	255.1	24	4695
Total:	18	55	324.9	29	4702
```
Нас интересует показатель запросов в секунду. Это число означает, что веб-сайт может обрабатывать 91,24 запросов в секунду, если одновременно имеется пять запросов.

***Замечание***: Обратите внимание, что отладка не отключена, так как нас интересуют изменения скорости обработки сеанса.

2 Теперь добавьте следующее в /config/web.php раздел компоненты:
```php
'session' => array(
    'class' => 'yii\web\CacheSession',
    'cache' => 'sessionCache',
),
'sessionCache' => array(
    'class' => 'yii\caching\MemCache',
),
```

3 Запустите ab снова с теми же настройками. На этот раз, вы должны получить лучшие результаты. В моем случае это было 139.07 запросов в секунду. Это означает, что Memcache, как обработчик сеанса, выполнил 52% лучше, чем файловый обработчик сеанса по умолчанию.

**Замечание**: Не полагайтесь на точные результаты, приведенные здесь. Все зависит от версий программного обеспечения, настроек и используемого оборудования. Всегда выполняйте все тесты самостоятельно в среде, в которой планируется развертывание приложения.

4 Вы можете получить значительный прирост производительности, выбрав правильный серверной обработки сеанса. Yii поддерживает больше кэширования серверных частей из коробки, включая wincache, xcache и кэш данных Zend, который поставляется с сервером Zend. Кроме того, вы можете реализовать собственную серверную часть кэша для использования быстрого хранения noSQL, например Redis.

Как это работает...
---
По умолчанию Yii использует собственные сеансы PHP; это означает, что файловая система используется в большинстве случаев. Файловая система не может эффективно работать с высоким параллелизмом.
Memcache или другие платформы отлично работают в следующей ситуации:
```php
'session' => array(
    'class' => 'yii\web\CacheSession',
    'cache' => 'sessionCache',
),
'sessionCache' => array(
    'class' => 'yii\caching\MemCache',
),
```
В предыдущем разделе config мы указываем Yii использовать CacheSession в качестве обработчика сеанса. С помощью этого компонента мы можем делегировать обработку сеанса компоненту кэша, указанному в кэше. На этот раз мы используем MemCache.
При использовании серверной части memcached следует учитывать тот факт, что при использовании этих решений пользователь приложения может потерять сеанс при достижении максимальной емкости кэша.

***Замечание***:Обратите внимание, что при использовании серверной части кэша для сеанса Вы не можете полагаться на сеанс как на временное хранилище данных, так как тогда не будет памяти для хранения большего количества данных в memcached. В таком случае, это будет просто удалить все данные или удалить некоторые из них.
Если вы используете несколько серверов, Вы не можете использовать файловое хранилище. Не существует способа совместного использования данных сеанса между серверами. В случае memcached, это легко, потому что к нему можно легко получить доступ от стольких серверов, как вы хотите.
Кроме того, для обмена данных можно использовать DbSession:
```php
return [
    // ...
    'components' => [
        'session' => [
            'class' => 'yii\web\DbSession',
        ],
    ],
];
```
Теперь создайте новую таблицу в базе данных:
```php
CREATE TABLE session (
    id CHAR(40) NOT NULL PRIMARY KEY,
    expire INTEGER,
    data BLOB
)
```

Кое что еще...
---
Рекомендуется как можно скорее закрыть сессию. Если Вы не собираетесь хранить что-либо в сеансе во время текущего запроса, вы можете даже закрыть его в самом начале действия контроллера. Таким образом, даже при использовании файлов в качестве хранилища ваше приложение должно быть в порядке.
Используйте следующую команду:
```php
Yii:$app->session->close();
```

Смотрите так же
---
Дополнительные сведения о производительности и кэшировании см. по следующим URL-адресам:
* <http://www.yiiframework.com/doc-2.0/guide-tutorial-performance-tnning.html>
 по русски <https://www.yiiframework.com/doc/guide/2.0/ru/tutorial-performance-tuning>
* <http://www.yiiframework.com/doc-2.0/guide-caching-overview.html>
 по русски <https://www.yiiframework.com/doc/guide/2.0/ru/caching-overview>





Использование зависимостей кеша и цепочек
===
Yii поддерживает множество серверных частей кэша, но что действительно делает кэш yii гибким, так это поддержка цепочек зависимостей и зависимостей. Существуют ситуации, когда вы не можете просто кэшировать данные в течение часа, потому что кэшированная информация может быть изменена в любое время.
В этом рецепте мы увидим, как кэшировать целую страницу и при этом всегда получать свежие данные при ее обновлении. Страница будет иметь Тип dashboard и покажет пять последних добавленных статей и общее количество, рассчитанное для учетной записи.

***Замечание*** Обратите внимание, что операция не может быть изменена по мере добавления, но статья может быть.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>


1 Активируйте компонент кэширования в config/web.php следующим образом:
```php
return [
    // ...
    'components' => [
        cache => ['class' => 'yii\caching\FileCache,],
    ],
];
```

2 Настройте новую базу данных и настройте ее в config/db.php.

3 Выполните следующую миграцию:

```php
<?php
use yii\db\Schema;
use yii\db\Migration;
class m160308_093233_create_example_tables extends Migration
{
    public function up()
    {
        $tableOptions = null;
        if ($this->db->driverName === 'mysql') {
            $tableOptions = 'CHARACTER SET utf8 COLLATE utf8_general_ci ENGINE=InnoDB';
        }
        $this->createTable('{{%account}}',[
            'id' => Schema::TYPE_PK,
            'amount' => Schema::TYPE_DECIMAL . '(10,2) NOT NULL',
        ], $tableOptions);
        $this->createTable('{{%article}}',[
            'id' => Schema::TYPE_PK,
            'title' => Schema::TYPE_STRING . ' NOT NULL',
            'text' => Schema::TYPE_TEXT . ' NOT NULL',
        ], $tableOptions);
    }
    public function down()
    {
        $this->dropTable('{{%article}}');
        $this->dropTable('{{%account}}');
    }
}
```

4 Создание моделей для таблиц счетов и статей с помощью Yii.

5 Создайте protected/controllers/DashboardController.php следующим образом:

```php
<?php
namespace app\controllers;
use app\models\Account;
use app\models\Article;
use yii\web\Controller;
class DashboardController extends Controller
{
    public function actionIndex()
    {
        $total = Account::find()->sum('amount');
        $articles = Article::find()->orderBy('id DESC')->limit(5)->all();
        return $this->render('index', array(
            'total' => $total,
            'articles' => $articles,
        ));
    }
    public function actionRandomOperation()
    {
        $rec = new Account();
        $rec->amount = rand(-1000, 1000);
        $rec->save();
        echo 'OK';
    }
    public function actionRandomArticle()
    {
        $n = rand(0, 1000);
        $article = new Article();
        $article->title = "Title #".$n;
        $article->text = "Text #".$n;
        $article->save();
        echo 'OK';
    }
}
```

6 Создание views/dashboard/index.php следующим образом:
```php
<?php
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $total int */
/* @var $articles app\models\Article[] */
?>
<h1>Total: <?= $total ?></h1>
<h2>5 latest articles:</h2>
<?php foreach($articles as $article): ?>
    <h3><?= Html::encode($article->title) ?></h3>
    <div><?= Html::encode($article->text) ?></div>
<?php endforeach ?>
```

7 Запустите dashboard/random-operation и dashboard/random-article несколько раз. Потом бежать dashboard/index, и вы должны увидеть экран, подобный показанному на следующем снимке экрана:
![](img/376_1.jpg)

8 Нажмите на количество запросов к базе данных в панели отладки в нижней части страницы:
![](img/377_1.jpg)

Список запросов :
![](img/377_2.jpg)

Как это работает...
---
Для достижения максимальной производительности при минимальном изменении кода мы используем полностраничный кэш с использованием фильтра следующим образом:
```php
public function behaviors()
{
return [
    'pageCache' => [
        'class' => 'yii\filters\PageCache',
        'only' => ['index'],
        'duration' => 24 * 3600 * 365, // 1 year
        'dependency' => [
            'class' => 'yii\caching\ChainedDependency',
            'dependencies' => [
                new TagDependency(['tags' => ['articles']]),
                new DbDependency(['sql' => 'SELECT MAX(id) FROM account'])
            ]
        ],
    ],
];
}
```
Предыдущий код означает, что мы применяем к действию индекса кэш полной страницы. Страница будет кэшироваться в течение года, и кэш будет обновляться при изменении одного из данных зависимостей. Поэтому, в целом, зависимость работает следующим образом:
* Первый запуск получает новые данные, как описано в зависимости, сохраняет их для дальнейшего использования и обновляет кэш
* Он получает свежие данные, как описано в разделе зависимость, получает сохраненные данные, а затем сравнивает их
* Если они равны, он использует кэшированные данные
* В противном случае он обновляет кэш, использует новые данные и сохраняет новые данные зависимостей для дальнейшего использования

В нашем случае используются два типа зависимостей—tag и DB. Зависимость тега помечает данные пользовательским строковым тегом и проверяет его, чтобы решить, нужно ли аннулировать кэш, в то время как зависимость БД использует результат запроса SQL для той же цели.
Вопрос, который у вас сейчас, вероятно,: "почему мы использовали БД для одного случая и теги для другого?” Это хороший вопрос!
Цель использования зависимости БД-заменить тяжелые вычисления и выбрать легкий запрос, который получает как можно меньше данных. Самое лучшее в этом типе зависимостей то, что нам не нужно встраивать какую-либо дополнительную логику в существующий код. В нашем случае мы можем использовать этот тип зависимости для операций с учетной записью, но не можем использовать его для статей, так как содержимое статьи может быть изменено. Поэтому для статей мы устанавливаем глобальный тег с именем article, что в основном означает, что мы можем вручную вызвать следующее, когда мы хотим сделать недействительным общий кэш статей:
```php
TagDependency::invalidate(\Yii::$app->cache, 'articles');
```

Смотрите так же
---
Чтобы узнать больше о кэшировании и использовании зависимостей кэша, обратитесь к
<http://www.yiiframework.com/doc-2.0/guide-caching-overview.html>
По русски <https://www.yiiframework.com/doc/guide/2.0/ru/caching-overview>





Профилирование приложения с помощью Yii
===
Если все рекомендации по развертыванию приложения Yii применены, а требуемая Производительность по-прежнему отсутствует, то, скорее всего, существуют некоторые узкие места в самом приложении. Основной принцип при работе с этими узкими местами заключается в том, что вы никогда не должны ничего предполагать и всегда тестировать и профилировать код, прежде чем пытаться оптимизировать его.
В этом рецепте мы постараемся найти узкие места в приложении yii2 mini.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

1 Настройте подключение к базе данных и примените следующую миграцию:
```php
<?php
use yii\db\Migration;
class m160308_093233_create_example_tables extends Migration
{
    public function up()
    {
        $tableOptions = null;
        if ($this->db->driverName === 'mysql') {
             $tableOptions = 'CHARACTER SET utf8 COLLATE utf8_general_ci ENGINE=InnoDB';
        }
        $this->createTable('{{%category}} ',[
            'id' => $this->primaryKey(),
            'name' => $this->string()->notNull(),
        ], $tableOptions);
        $this->createTable('{{%article}}',[
            'id' => $this->primaryKey(),
            'category_id' => $this->integer()->notNull(),
            'title' => $this->string()->notNull(),
            'text' => $this->text()->notNull(),
        ], $tableOptions);
        $this->createIndex('idx-article-category_id','{{%article}}', ' category_id');
        $this->addForeignKey('fk-article-category_id','{{%article}}', 'category_id', '{{%category}}', 'id');
    }
    public function down()
    {
        $this->dropTable('{{%article}}');
        $this->dropTable('{{%category}}');
    }
}
```

2 Создание моделей для каждой таблицы в Yii.

3 Напишите следующую консольную команду:

```php
<?php
namespace app\commands;
use app\models\Article;
use app\models\Category;
use Faker\Factory;
use yii\console\Controller;
class DataController extends Controller
{
    public function actionInit()
    {
        $db = \Yii::$app->db;
        $faker = Factory::create();
        $transaction = $db->beginTransaction();
        try {
            $categories = [];
            for ($id = 1; $id <= 100; $id++) {
                $categories[] = [
                    'id' => $id,
                    'name' => $faker->name,
                ];
            }
            $db->createCommand()->batchInsert(Category::tableName(), ['id', 'name'], $categories)->execute();
            $articles = [];
            for ($id = 1; $id <= 100; $id++) {
                $articles[] = [
                    'id' => $id,
                    'category_id' => $faker->numberBetween(1, 100),
                    'title' => $faker->text($maxNbChars = 100),
                    'text' => $faker->text($maxNbChars = 200),
                ];
            }
            $db->createCommand()
                ->batchInsert(Article::tableName(), ['id', 'category_id', 'title', 'text'], $articles)->execute();
            $transaction->commit();
        } catch (\Exception $e) {
            $transaction->rollBack();
            throw $e;
        }
    }
}
```
И выполнить её:

***./yii data/init***

4 Добавьте класс ArticleController следующим образом:
```php
<?php
namespace app\controllers;
use Yii;
use app\models\Article;
use yii\data\ActiveDataProvider;
use yii\web\Controller;
class ArticleController extends Controller
{
    public function actionIndex()
    {
        $query = Article::find();
        $dataProvider = new ActiveDataProvider([
            'query' => $query,
        ]);
        return $this->render('index', [
            'dataProvider' => $dataProvider,
        ]);
    }
}
```

5 Добавить вид views/article/index.php посмотреть следующим образом:
```php
<?php
use yii\helpers\Html;
use yii\widgets\ListView;
/* @var $this yii\web\View */
/* @var $dataProvider yii\data\ActiveDataProvider */
$this->title = 'Articles';
$this->params['breadcrumbs'][] = $this->title;
?>
<div class="article-index">
    <h1><?= Html::encode($this->title) ?></h1>
    <?= ListView::widget([
        'dataProvider' => $dataProvider,
        'itemOptions' => ['class' => 'item'],
        'itemView' => '_item',
    ]) ?>
/div>
```
Добавьте  views/article/_item.php:
```php
<?php
use yii\helpers\Html;
/* @var $this yii\web\View */
/* @var $model app\models\Article */
?>
<div class="panel panel-default">
    <div class="panel-heading"><?= Html::encode($model->title); ?></div>
    <div class="panel-body">
        Category: <?= Html::encode($model->category->name) ?>
    </div>
</div>
```

Как это сделать...
---
Выполните следующие действия для профилирования приложения с помощью Yii:
1 Откройте страницу статьи:
![](img/385_1.jpg)

2 Откройте views/article/index.php  файл и добавьте вызовов профилировщика до и после виджета Listview:
```php
<div class="article-index">
    <h1><?= Html::encode($this->title) ?></h1>
    <?php Yii::beginProfile('articles') ?>
    <?= ListView::widget([
        'dataProvider' => $dataProvider,
        'itemOptions' => ['class' => 'item'],
        'itemView' => '_item',
    ]) ?>
    <?php Yii::endProfile('articles') ?>
</div>
```
Теперь обновите страницу.
![](img/385_2.jpg)

3 Разверните панель отладки в нижней части страницы и нажмите на значок синхронизации (73 мс в нашем случае):
![](img/386_1.jpg)
Теперь изучите отчет профилирования
 Мы видим, что наш блок статей занял около 40 миллисекунд.

4 Откройте наш контроллер и добавьте нетерпеливую загрузку для отношения категории статьи следующим образом:
```php
class ArticleController extends Controller
{
    public function actionIndex()
    {
        $query = Article::find()->with('category');
        $dataProvider = new ActiveDataProvider([
            'query' => $query,
        ]);
        return $this->render('index', [
            'dataProvider' => $dataProvider,
        ]);
    }
}
```

5 Вернитесь на сайт, обновите страницу и снова откройте отчет профилирования
![](img/387_1.jpg)

Сейчас список статей занимает около 25 миллисекунд, так как приложение делает меньше запросов SQL с нетерпеливой загрузкой связанных моделей.

Как это работает...
---
Любой фрагмент исходного кода можно заключить в вызовы Yii::beginProfile и Yii::endProfile:
```php
Yii::beginProfile('articles');
// ...
Yii::endProfile('articles' );
```
После выполнения страницы Вы можете увидеть отчет со всеми таймингами на странице профилирование модуля отладка.
Кроме того, можно использовать вложенные вызовы профилирования следующим образом:
```php
Yii::beginProfile('outer');
Yii::beginProfile('inner');
// ...
Yii::endProfile('inner');
Yii::endProfile('outer');
```
***Замечания***: Позаботьтесь о правильном открытии и закрытии вызовов в этом случае и правильном именовании блоков. Если вы пропустите метод yii::endProfile звонок или переключить порядок в yii::endProfile( 'inner' ) и yii::endProfile ("outer"), профилирования производительности не получится.

Смотрите так же
---
* Дополнительные сведения о ведении журнала см. в следующей  URL 
<https://www.yiiframework.com/doc/guide/2.0/en/runtime-logging#performance-profiling> 
По русски <https://www.yiiframework.com/doc/guide/2.0/ru/runtime-logging#performance-profiling>
* О настройке производительности приложения см. следующий URL-адрес:
<http://www.yiiframework.com/doc-2.0/guide-tutorial-performance-tuning.html>
по русски <https://www.yiiframework.com/doc/guide/2.0/ru/tutorial-performance-tuning> 




Использование кэширования HTTP
===
Вместо реализации кэширования на стороне сервера можно использовать кэширование на стороне клиента через определенные http-заголовки.
В этом рецепте мы рассмотрим полностраничное кэширование на основе заголовков Last-Modified и ETag.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

1 Создайте и запустите миграцию следующим образом:
```php
<?php
use yii\db\Migration;
class m160308_093233_create_example_tables extends Migration
{
    public function up()
    {
        $this->createTable('{{%article}}',[
            'id' => $this->primaryKey(),
            'created_at' => $this->integer()->unsigned()->notNull(),
            'updated_at' => $this->integer()->unsigned()->notNull(),
            'title' => $this->string()->notNull(),
            'text' => $this->text()->notNull(),
        ]);
    }
    public function down()
    {
        $this->dropTable('{{%article}}');
    }
}
```

2 Создайте модель Article следующим образом:
```php
<?php
namespace app\models;
use Yii;
use yii\behaviors\TimestampBehavior;
use yii\db\ActiveRecord;
class Article extends ActiveRecord
{
    public static function tableName()
    {
        return '{{%article}}';
    }
    public function behaviors()
    {
        return [
            TimestampBehavior::className(),
        ];
    }
}
```

3 Создайте контроллер блога со следующими действиями:
```php
<?php
namespace app\controllers;
use app\models\Article;
use yii\web\Controller;
use yii\web\NotFoundHttpException;
class BlogController extends Controller
{
    public function actionIndex()
    {
        $articles = Article::find()->orderBy(['id' => SORT_DESC])->all();
        return $this->render('index', array(
            'articles' => $articles,
        ));
    }
    public function actionView($id)
    {
        $article = $this->findModel($id);
        return $this->render('view', array(
            'article' => $article,
        ));
    }
    public function actionCreate()
    {
        $n = rand(0, 1000);
        $article = new Article();
        $article->title = 'Title #'	. $n;
        $article->text = 'Text #'	. $n;
        $article->save();
        echo 'OK';
    }
    public function actionUpdate($id)
    {
        $article = $this->findModel($id);
        $n = rand(0, 1000);
        $article->title = 'Title #'	. $n;
        $article->text = 'Text #'	. $n;
        $article->save();
        echo 'OK';
    }
    private function findModel($id)
    {
        if (($model = Article::findOne($id)) !== null) {
            return $model;
        } else {
            throw new NotFoundHttpException('The requested page does not exist.');
        }
    }
}
```

4 Добавьте представления views/blog/index.php:
```php
<?php
use yii\helpers\Html;
$this->title = 'Articles';;
$this->params['breadcrumbs'][] = $this->title;
?>
<?php foreach($articles as $article): ?>
    <h3><?= Html::a(Html::encode($article->title), ['view', 'id' => $article->id])?></h3>
    <div>Created <?= Yii::$app->formatter->asDatetime($article->created_at) ?></div>
    <div>Updated <?= Yii::$app->formatter->asDatetime($article->updated_at) ?></div>
<?php endforeach ?>
```

5 Добавить файл представления views/blog/view.php:
```php
<?php
use yii\helpers\Html;
$this->title = $article->title;
$this->params['breadcrumbs'][] = ['label' => 'Articles', 'url' => ['index']];
$this->params['breadcrumbs'][] = $this->title;
?>
<h1><?= Html::encode($article->title) ?></h1>
<div>Created <?= Yii::$app->formatter->asDatetime($article->created_at) ?></div>
<div>Updated <?= Yii::$app->formatter->asDatetime($article->updated_at) ?></div>
<hr />
<p><?= Yii::$app->formatter->asNtext($article->text) ?></p>
```

Как это сделать...
---
Выполните следующие действия, чтобы использовать кэширование HTTP:

1 Доступ к этому URL http://yii-book.app/index.РНР?р=blog/create три раза, чтобы создать три статьи.

2 Откройте следующую страницу блога:
![](img/392_1.jpg)

3 Откройте консоль разработчика в браузере и просмотрите состояние ответа 200 OK для каждой перезагрузки страницы блога:
![](img/393_1.jpg)

4 Откройте BlogController и присоедините следующие поведения:
```php
class BlogController extends Controller
{
    public function behaviors()
    {
        return [
            [
                'class' => 'yii\filters\HttpCache',
                'only' => ['index'],
                'lastModified' => function ($action, $params) {
                    return Article::find()->max('updated_at');
                },
            ],
            [
                'class' => 'yii\filters\HttpCache',
                'only' => ['view'],
                'etagSeed' => function ($action, $params) {
                    $article = $this->findModel(\Yii::$app->request->get('id'));
                    return serialize([$article->title, $article->text]);
                },
            ],
        ];
    }
    // ...
}
```

5 Затем перезагрузите страницу несколько раз и убедитесь, что сервер возвращает состояние 304 Not Modified вместо 200 OK:
![](img/394_1.jpg)

6 Откройте соответствующую страницу, используя следующий URL-Адрес для обновления случайных статей: http://yii-book.app/index.php?r=blog/update.

7 После обновления страницы блога, убедитесь, что сервер возвращает 200 OK в первый раз и 304 не изменяется после этого, и убедитесь, что вы видите новое обновленное время на странице:
![](img/395_1.jpg)

8 Откройте любую страницу из нашей статьи следующим образом:
![](img/396_1.jpg)

Убедитесь, что сервер возвращает 200 OK в первый раз и 304 не изменяется при последующих запросах.

Как это работает...
---
Есть время и содержание подходов для проверки наличия кэшируемого Контента ответ на Ваш браузер с помощью http-заголовки.

***Последнее Изменение***

Этот подход предполагает, что сервер должен возвращать дату последнего изменения каждого документа. После сохранения даты, наш браузер может прикрепить ее в заголовке If-Modified-Since для каждого последующего запроса.
Мы должны прикрепить фильтр действий к нашему контроллеру и указать lastModified обратный вызов следующим образом:
```php
class BlogController extends Controller
{
    public function behaviors()
    {
        return [
            [
                'class' => 'yii\filters\HttpCache',
                'only' => ['index'],
                'lastModified' => function ($action, $params) {
                    return Article::find()->max('updated_at');
                },
                // ...
            ];
    }
    // ...
}
```
Класс \yii\filters\HttpCache вызывает обратный вызов и сравнивает возвращаемое значение с системной переменной $_SERVER ['HTTP_IF_MODIFIED_SINCE']. Если документ все еще не изменен, HttpCache отправит облегченный Заголовок ответа 304 без выполнения действия.
Однако, если документ был обновлен, кэш будет проигнорирован, и сервер вернет полный ответ.

![](img/397_1.jpg)

В качестве альтернативы или дополнения к последней измененной переменной заголовка можно использовать ETag.

***Метка объекта***

В случаях, когда мы не храним дату последнего изменения в наших документах или страницах, мы можем использовать пользовательские хэши, которые могут быть созданы на основе содержимого документа.
Например, мы можем использовать Контент Заголовок документа, чтобы хэш-тэгом:
```php
class BlogController extends Controller
{
    public function behaviors()
    {
        return [
            [
                'class' => 'yii\filters\HttpCache',
                'only' => ['view'],
                'etagSeed' => function ($action, $params) {
                    $article = $this->findModel(\Yii::$app->request->get('id'));
                    return serialize([$article->title, $article->text]);
                },
            ],
        ];
    }
    // ...
}
```
Фильтр HttpCache присоединит этот тег к ответу сервера в качестве переменной заголовка ETag.
После сохранения ETag наш браузер может присоединять его в заголовке If-None-Match для каждого последующего запроса.
Если документ все еще не изменился, HttpCache отправит облегченный Заголовок ответа 304 без выполнения действия.
![](img/398_1.jpg)

Когда кэш является допустимым, наше приложение будет отправлять 304 не измененные HTTP-заголовки ответа вместо содержимого страницы и не будет запускать контроллеры и действия повторно.

Смотрите так же
---
* Для получения дополнительной информации о кэшировании HTTP обратитесь к
<https://developers.google.com/web/fundamentals/performanre/optimi7ing-content-efficiency/http-caching>
* По HTTP-caching в Yii2 смотрите инфу по ссылке <http://www.yiiframework.com/doc-2.0/guide-caching-http.html>
 по русски <https://www.yiiframework.com/doc/guide/2.0/ru/caching-http> 




Объединение и минимизация asset
===
Если Веб-страница содержит много файлов CSS и/или JavaScript, страница будет открываться очень медленно, так как браузер отправляет большое количество HTTP-запросов на загрузку каждого файла в отдельных потоках. Чтобы уменьшить количество запросов и подключений, мы можем объединить и сжать несколько файлов CSS / JavaScript в один или очень мало файлов в рабочем режиме, а затем включить эти сжатые файлы на странице вместо исходных.

Подготовка 
---
* Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>
* Скачать компилятор  jar файлов из <https://developers.google.com/closure/compiler/>
* Скачать yuicompressor.файл jar из <https://githiih.rom/yni/ynirompressor/releases>
* Загрузите и установите среду выполнения Java (JRE) из  <http://www.java.com>

Как это сделать...
---
Выполните следующие действия, чтобы объединить и минимизировать активы:

1 Откройте исходный HTML-код страницы индекса приложения. Проверьте, похож ли он на следующую структуру:
```html 
< ! DOCTYPE html>
<html lang="en-US">
    <head>
        <title>My Yii Application</title>
        <link href="/assets/9b3b2888/css/bootstrap.css" rel="stylesheet">
        <link href="/css/site.css" rel="stylesheet">
    </head>
    <body>
        <script src="/assets/25f82b8a/jquery.js"></script>
        <script src="/assets/f4307424/yii.js"></script>
        <script src="/assets/9b3b2888/js/bootstrap.js"></script>
    </body>
</html>
```
Страница содержит три файла JavaScript.

2 Откройте config/console.php файл и добавить @webroot и @web определения псевдонимов:
```
<?php
Yii::setAlias('@webroot', 	DIR	 .	'/../web');
Yii::setAlias('@web', '/');
```

3 Откройте консоль и выполните следующую команду:

***yii asset/template assets.php***

4 Откройте сгенерированные assets.php файл и настроить его следующим образом:
```php
<?php
return [
    'jsCompressor' => 'java -jar compiler.jar --js {from} --js_output_file {to}',
    'cssCompressor' => 'java -jar yuicompressor.jar --type css {from} -o {to}',
    'bundles' => [
        'app\assets\AppAsset',
        'yii\bootstrap\BootstrapPluginAsset',
    ],
    'targets' => [
        'all' => [
            'class' => 'yii\web\AssetBundle',
            'basePath' => '@webroot/assets',
            'baseUrl' => '@web/assets',
            'js' => 'all-{hash}.js',
            'css' => 'all-{hash}.css',
        ],
    ],
    'assetManager' => [
        'basePath' => '@webroot/assets',
        'baseUrl' => '@web/assets',
    ],
];
```

5 Выполните команду объединения

***yii asset assets.php config/assets-prod.php ***

Если это успешно, вы должны получить config/assets-prod.php файл со следующей конфигурацией:
```php
<?php
return [
    'all' => [
        'class' => 'yii\\web\\AssetBundle',
        'basePath' => '@webroot/assets',
        'baseUrl' => '@web/assets',
        'js' => [
            ' all-fe792d4766bead53e7a9d851adfc6ec2.js',
        ],
        'css' => [
            'all-37cfb42649f74eb0a4bfe0d0e715c420.css',
        ],
    ],
    'yii\\web\\JqueryAsset' => [
        'sourcePath' => null,
        'js' => [],
        ' css ' => [],
        'depends' => [
            'all',
        ],
    ],
    'yii\\web\\YiiAsset' => [
        'sourcePath' => null,
        'js' => [],
        'css' => [],
        'depends' => [
            'yii\\web\\JqueryAsset',
            'all',
        ],
    ],
    'yii\\bootstrap\\BootstrapAsset' => [
        'sourcePath' => null,
        'js' => [],
        ' css ' => [],
        'depends' => [
            'all',
        ],
    ],
    'app\\assets\\AppAsset' => [
        'sourcePath' => null,
        'js' => [],
        'css' => [],
        'depends' => [
            'yii\\web\\YiiAsset',
            'yii\\bootstrap\\BootstrapAsset',
            'all',
        ],
    ],
    'yii\\bootstrap\\BootstrapPluginAsset' => [
        'sourcePath' => null,
        'js' => [],
        ' css ' => [],
        'depends' => [
            'yii\\web\\JqueryAsset',
            'yii\\bootstrap\\BootstrapAsset',
            'all',
        ],
    ],
];
```

6 Добавьте конфигурацию для компонента assetManager в config/web.php-файл:
```php
'components' => [
    // ...
    'assetManager' => [
        'bundles' => YII_ENV_PROD ? require(__DIR__ . '/assets-prod.php') : [],
    ],
],
```

7 Включите производственный режим в web/index.php:
```php
defined('YII_ENV') or define('YII_ENV', 'prod');
```

8 Перезагрузите страницу в браузере и снова увидите HTML-код. Теперь он должен содержать одиночные строки для включения наших сжатых файлов:
```php
< ! DOCTYPE html>
<html lang="en-US">
<head>
<title>My Yii Application</title>
         <link href="/assets/all-37cfb42649f74eb0a4bfe0d0e715c420.css"
rel="stylesheet">
</head>
<body>
    <script src="/assets/all-fe792d4766bead53e7a9d851adfc6ec2.js"></script>
</body>
</html>
```

Как это работает...
---
Прежде всего, на нашей странице был набор включенных файлов:
```php
<link href="/assets/9b3b2888/css/bootstrap.css" rel="stylesheet">
<link href="/css/site.css" rel="stylesheet">
<script src="/assets/25f82b8a/jquery.js"></script>
<script src="/assets/f4307424/yii.js"></script>
<script src="/assets/9b3b2888/js/bootstrap.js"></script>
```
Затем мы создали asset.php конфигурационный файл и указанные пакеты для сжатия:

'bundles' => [
    'app\assets\AppAsset',
    'yii\bootstrap\BootstrapPluginAsset',
],
```

***Замечание***: Мы могли бы определить все промежуточные пакеты ассетов, таких как веб-фреймворка yii\\jqueryAsset и yii\web\YiiAsset, но эти активы уже указаны как зависимости от AppAsset и BootstrapPluginAsset, и сжатие команда автоматически решает все эти зависимости.
AssetManager публикует все активы в классические подкаталоги в web/assets и после публикации запускает компрессоры, чтобы объединить все CSS и JS файлы в all-{hash}.js and all-{hash}.css.
Проверьте, включает ли файл CSS другие ресурсы относительными путями, такими как bootstrap.css:
```php
@font-face {
    font-family: 'Glyphicons Halflings';
    src: url('../fonts/glyphicons-halflings-regular.eot');
}
```
Если это так, то в комбинированном файле наш компрессор изменяет все относительные пути для хранения всех отношений следующим образом:
```php
@font-face{
    font-family: 'Glyphicons Halflings';
    src: url('9b3b2888/fonts/glyphicons-halflings-regular.eot');
}
```
После обработки мы получаем assets-prod.php файл с конфигурацией пакетов компонента assetManager. Он определяет новый виртуальный ресурс как зависимость чистых копий исходных пакетов:
```php
return [
    'all' => [
        'class' => 'yii\\web\\AssetBundle',
        'basePath' => '@webroot/assets',
        'baseUrl' => '@web/assets',
        'js' => [
            'all-fe792d4766bead53e7a9d851adfc6ec2 .js',
        ],
        'css' => [
            ' all-37cfb42649f74eb0a4bfe0d0e715c420.css',
        ],
    ],
    'yii\\web\\JqueryAsset' => [
        'sourcePath' => null,
        'js' => [],
        'css' => [],
        'depends' => [
            'all',
        ],
    ],
    // ...
]
```
Теперь мы можем потребовать эту конфигурацию в config/web.php:
```php
'components' => [
    // ...
    'assetManager' => [
        'bundles' => require(	DIR	 . '/assets-prod.php'),
    ],
],
```
Кроме того, файл может потребоваться только для рабочей среды:
```php
'components' => [
    // ...
    'assetManager' => [
        'bundles' => YII_ENV_PROD ? require(	DIR	 . '/assets-prod.php') : [],
    ],
],
```

***Замечание*** Не забывайте восстанавливать все сжатые и комбинированные файлы после любых обновлений исходных ресурсов.

Смотрите так же
---
* Дополнительные сведения об активах см. по следующему URL-адресу  <https://www.yiiframework.com/doc/guide/2.0/en/structure-assets> 
 по русски <https://www.yiiframework.com/doc/guide/2.0/ru/structure-assets>
* Для компилятора обратитесь к следующему URL-адресу: <https://developers.google.com/closure/compiler/>
* Для компрессора YUI обратитесь к следующему URL: <https://github.com/vmyvnirompressor/>





Реализация и выполнение заданий cron
===
Иногда приложению требуются некоторые фоновые задачи, такие как восстановление карты сайта или обновление статистики. Распространенный способ реализовать это с помощью задач cron . При использовании Yii есть способ использовать команду для запуска в качестве задания.
В этом рецепте, мы увидим, как реализовать оба. Для нашего рецепта мы реализуем написание текущей метки времени в Timestamp.txt файл в защищенном каталоге.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
***Выполнение команды Hello***

Давайте попробуем для выполнения команд app\commands\HelloController::actionIndex использовать коммандную оболочку:
```php
<?php
namespace app\commands;
use yii\console\Controller;
/**
* This command echoes the first argument that you have entered.
*/
class HelloController extends Controller
{
    /**
    * This command echoes what you have entered as the message.
    * @param string $message the message to be echoed.
    */
    public function actionIndex($message = 'hello world')
    {
        echo $message . "\n";
    }
}
```

1 Откройте командную консоль в каталоге приложения и выполните следующую команду:

***php yii***

Кроме того, можно вызвать следующее и убедиться, что оболочка работает:

***. /yii***

2 Введите следующую команду для отображения приветствия:

***./yii help hello***

3 Фреймворк должен отображать некоторую информацию:
```php
DESCRIPTION
This command echoes what you have entered as the message.
USAGE
yii hello [message] [...options...]
- message: string (defaults to 'hello world')
the message to be echoed.
```

4 Выполните команду по умолчанию:

***./yii hello***

Кроме того, выполните действие конкретного index:

***./yii hello/index***


5 Теперь вы должны увидеть фразу по умолчанию:
```php
Hello world
```

6 Выполните команду с любым параметром и посмотрите ответ:

***./yii hello 'Bond, James Bond'***

***Создание собственной команды***

Можно также создать собственные контроллеры консоли. Например, создайте commands/cronController.php файл с примером кода:
```php
<?php
namespace app\commands;
use yii\console\Controller;
use yii\helpers\Console;
use Yii;
/**
* Console crontab actions
*/
class CronController extends Controller
{
    /**
    * Regenerates timestamp
    */
    public function actionTimestamp()
    {
        file_put_contents(Yii::getAlias('@app/timestamp.txt'), time());
        $this->stdout('Done!', Console::FG_GREEN, Console::BOLD);
        $this->stdout(PHP_EOL);
    }
}
```
После того как все будет сделано, выполните команду в консоли:

***./yii cron/timestamp***

Затем проверьте текст ответа и наличие нового файла, а именно timestamp.txt.

***Настройка расписания cron***

Создать /etc/cron.d/myapp на вашем сервере Linux и добавить следующую строку, чтобы запустить нашу команду в каждую полночь:
```php
0 0
* * * www-data /path/to/yii cron/timestamp >/dev/null
```

Как это работает...
---
Консольная команда определяется как класс контроллера, который простирается от yii\console\controller. В классе controller определяется одно или несколько действий, соответствующих подкомандам контроллера. В каждом действии вы пишете код, реализующий соответствующие задачи для данной подкоманды.
При выполнении команды необходимо указать маршрут к действию. Например, маршрут migrate/create вызывает подкоманду, соответствующую методу действия MigrateController::actionCreate(). Если маршрут, предложенный во время выполнения, не содержит идентификатор действия, будет выполнено действие по умолчанию (как с веб-контроллером).
Убедитесь, что контроллеры консоли размещены в каталоге, определенном параметром controllerNamespace в конфиге web/console.php.

Смотрите так же
---
* Дополнительные сведения о консольных командах Yii2 см. в разделе
<http://www.yiiframework.com/doc-2.0/guide-tutorial-console.html>
По русски <https://www.yiiframework.com/doc/guide/2.0/ru/tutorial-console>
* Чтобы узнать больше о демоне Cron, обратитесь к <https://en.wikipedia.org/wiki/Cron>
* Смотрите  рецепта Изменение макета каталога Yii для controllerNamespace




Режим обслуживания
==
Иногда возникает необходимость тонкой настройки некоторых параметров приложения или восстановления базы данных из резервной копии.
При работе над такими задачами нежелательно разрешать всем использовать приложение, поскольку это может привести к потере последних сообщений пользователя или отображению сведений о реализации приложения.
В этом рецепте мы увидим, как показать всем, кроме разработчика сообщение об  обслуживании.

Подготовка 
--
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
Выполните следующие действия:

1 Во-первых, нам нужно создать protected/controllers/MaintenanceController.php. Мы делаем это следующим образом:
```php
class MaintenanceController extends Controller
{
    public function actionIndex()
    {
        $this->renderPartial("index");
    }
}
```

2 Затем мы создаем представление с именем views/maintenance/index.php, следующим образом:
```php
<?php
use yii\helpers\Html;
?>
<!doctype html>
    <head>
        <meta charset="utf-8" />
        <title><?php echo Html::encode(Yii::$app->name)?>is under maintenance</title>
    </head>
    <body>
        <h1><?php echo CHtml::encode(Yii::$app->name)?>is under maintenance</h1>
        <p>We'll be back soon. If we aren't back for too long,please drop a message to
        <?php echo Yii::$app->params['adminEmail']?>.</p>
        <p>Meanwhile, it's a good time to get a cup of coffee,to read a book or to check email.</p>
    </body>
```

3 Теперь нам нужно добавить одну строку кода в config/web.php, следующим образом:
```php
$config = [
    'catchAll' => file_exists(dirname(__DIR__) .'/.maintenance')
    && !(isset($_COOKIE['secret']) && $_COOKIE['secret']=="password") 
        ? ['maintenance/index'] 
        : null,
    // ...
]
```

4 Теперь для перехода в режим обслуживания необходимо создать файл с именем .maintenance в каталоге сайтов. После этого вы должны увидеть эту страницу.
Для того, чтобы вернуть его в нормальное состояние, вам просто нужно удалить его. Для просмотра веб-сайта в режиме обслуживания можно создать файл cookie secret со значением, равным password.

Как это работает...
---
Веб-приложение Yii предлагает способ перехватить все возможные запросы и направить их в одно действие контроллера. Это можно сделать, установив yii\web\Application::catchAll в массив, содержащий маршрут приложения следующим образом:
```php
'catchAll' => ['maintenance/index'],
```
Сам контроллер ремонт ничего особенного, он просто выводит в виде текста.
Нам нужен простой способ включения и выключения режима обслуживания. Поскольку конфигурация приложения является обычным файлом PHP, мы можем достичь этого с помощью простой проверки, чтобы подтвердить, что файл существует, следующим образом:
```php
file_exists(dirname(__DIR__) . '/.maintenance')
```
Кроме того, мы проверяем значение cookie, чтобы иметь возможность переопределить режим обслуживания. Мы делаем это следующим образом:
```php
(isset($_COOKIE['secret']) && $_COOKIE['secret']=="password")
```

Смотрите так же
---
Чтобы узнать больше о том, как поймать все запросы в приложении Yii и проверить производство готовое решение для обслуживания, см.
 <https://www.yiiframework.com/doc/api/2.0/yii-web-application#$catchAll-detail> .




Средства развертывания
==
Если вы используете систему управления версиями, такую как Git, для кода вашего проекта и отправки релизов в удаленный репозиторий, Вы можете использовать Git для развертывания кода на рабочем сервере с помощью команды git pull shell вместо загрузки файлов вручную. Кроме того, вы можете написать свой собственный сценарий оболочки, чтобы вытащить новые фиксации репозитория, обновить поставщиков, применить миграции и сделать больше вещей.
Однако существует множество инструментов для автоматизации процесса развертывания. В этом рецепте мы рассмотрим инструмент Deployer.

Подготовка 
--
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
При наличии общего удаленного хранилища его можно использовать для источника развертывания.

***Шаг 1-Подготовка удаленного хоста***

1 Перейдите на удаленный хост и установите Composer и asset-plugin:

***global require 'fxp/composer-asset-plugin:~1.1.1'***

2 Сгенерируйте ключ SSH через ssh-keygen.

3 Добавить содержимое ~/.ssh/id_rsa.pub  pub-файла в развертывание страница SSH-ключей настроек репозитория на github, Bitbucket или другом хранилище репозиториев.

4 Попробуйте клонировать репозиторий вручную:

***git clone git@github.com:user/repo.git***

5 Добавьте адрес Github в список известных хостов, если система попросит вас сделать это.

***Шаг 2-Подготовка localhost***

1 Установите deploy.phar глобально на локальном компьютере:
```php
sudo wget http://deployer.org/deployer.phar
sudo mv deployer.phar /usr/local/bin/dep
sudo chmod +x /usr/local/bin/dep
```

2 Добавьте deploy.php файл с конфигурацией развертывания:
```php
<?php
require 'recipe/yii2-app-basic.php';
set('shared_files', [
    ' config/db.php',
    'config/params.php',
    'web/index.php ',
    ' yii',
]);
server('prod', 'site.com', 22) // SSH access to remote server
    ->user( ' user' )
    // ->password(password) // uncomment for authentication by password
    // ->identityFile()	// uncomment for authentication by SSH key
    ->stage('production')
    ->env('deploy_path',	'/var/www/project');
set('repository', 'git@github.com:user/repo.git');
```

3 Попробуйте подготовить структуру каталогов удаленных проектов:

***dep deploy:prepare prod***

***Шаг 3-Добавление удаленной конфигурации***

1 Откройте каталог сервера /var/www/project. Он имеет два подкаталога после инициализации:
![](img/431_1.jpg)

2 Создание исходных файлов с частными конфигурациями в общем каталоге, как здесь:
![](img/431_2.jpg)

Инструмент Deployer будет включать эти файлы в каждый подкаталог release через символические ссылки. Укажите свою личную конфигурацию в файле share/config/db.php:
```php
<?php
return [
    'class' => 'yii\db\Connection',
    dsn' => 'mysql:host=localhost;dbname=catalog',
    'username' => 'root',
    'password' => 'root',
    ' charset' => 'utf8',
];
```
Кроме того, укажите его в share/config/params.php:
```php
<?php
return [
    'adminEmail' => 'admin@example.com',
];
```
Установите содержимое share/web/index.php:
```php
<?php
defined('YII_DEBUG') or define('YII_DEBUG', false);
defined('YII_ENV') or define('YII_ENV', 'prod');
$dir = dirname($_SERVER['SCRIPT_FILENAME']);
require($dir . '/../vendor/autoload.php');
require($dir . '/../vendor/yiisoft/yii2/Yii.php');
$config = require($dir . '/../config/web.php');
(new yii\web\Application($config))->run();
```
Кроме того, установите содержимое файла share/yii:
```php
#!/usr/bin/env php
<?php
defined('YII_DEBUG') or define('YII_DEBUG', false);
defined('YII_ENV') or define('YII_ENV', 'prod');
$dir = dirname($_SERVER['SCRIPT_FILENAME']);
require($dir . '/vendor/autoload.php');
require($dir . '/vendor/yiisoft/yii2/Yii.php');
$config = require($dir. '/config/console.php');
$application = new yii\console\Application($config);
$exitCode = $application->run();
exit($exitCode);
```
***Замечание*** Мы намеренно используем код dirname($_SERVER [' SCRIPT_FILENAME ' ]) вместо исходной константы__ DIR__, потому что _ _ DIR _ _ вернет неверное значение, когда файл будет включен через символьную ссылку.

***Замечание:*** При использовании шаблона yii2-app-advanced можно повторно объявить только config/main-local.php и config/params-local.php файлы каждого (backend, frontend, console и common), потому что web/index.php и yii файлы будут созданы автоматически командой init.

***Шаг 4-попытка развертывания***

1 Вернуться к localhost с deploy.php файл и выполнить команду deploy:

***dep deploy prod***

2 В случае успеха, вы увидите отчет о развертывании:
![](img/433_1.jpg)

3 Deployer создал новый подкаталог release на удаленном сервере и добавил символические ссылки из проекта на общие элементы и из текущего каталога в текущий выпуск:
![](img/433_2.jpg)

4 После того, как все будет сделано, вы должны настроить DocumentRoot директорию  вашего сервера в project/current/web.

5 Если в процессе развертывания что-то пойдет не так, можно выполнить откат к предыдущему рабочему выпуску:

***dep rollback prod***

Текущий каталог приведет к предыдущим файлам выпуска.

Как это работает...
---
Большинство средств развертывания выполняют те же задачи:
* Создать новый подкаталог релиза 
* Клонирование файлов репозитория
* Создание символических ссылок из проекта на общие каталоги и локальные файлы конфигурации
* Установка пакетов Composer
* Применение миграции проектов
* Переключите символическую ссылку из каталога DocumentRoot сервера в каталог текущего выпуска
Инструмент Deployer содержит предопределенные рецепты популярных фреймворков. Вы можете расширить любой существующий рецепт или написать новый для вашего конкретного случая.

Смотрите так же
---
* Дополнительные сведения о Deployer см. в разделе <http://deployer.org/docs>
* И о создании ключей SSH см. <https://git-scm.com/book/en/v2/Git-on-the-Server-Generating-Your-SSH-Public-Key> 





Ãëàâà 11. Òåñòèðîâàíèå
===
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:
* Ïðèìåíåíèå òåñòèðîâàíèÿ Codeception
* Ìîäóëüíîå òåñòèðîâàíèå ñ PHPUnit
* Þíèò-òåñòèðîâàíèå ñ Atoum
* Ìîäóëüíîå òåñòèðîâàíèå ñ Behat

Ââåäåíèå
===
Â ýòîé ãëàâå âû óçíàåòå, êàê èñïîëüçîâàòü ëó÷øèå òåõíîëîãèè äëÿ òåñòèðîâàíèÿ, òàêèå êàê Codeception, PhpUnit, Atoum è Behat. Âû ïîçíàêîìèòåñü ñ òåì, êàê ïèñàòü ïðîñòûå òåñòû è êàê èçáåæàòü îøèáîê ðåãðåññèè â âàøåì ïðèëîæåíèè


Тестирование приложения с Codeception
===
По умолчанию базовые и расширенные скелеты приложений Yii2 используют Codeception в качестве платформы тестирования. Codeception поддерживает написание модульных, функциональных и приемочных тестов из коробки. Для модульных тестов используется Платформа тестирования PHPUnit, которая будет описана в следующем рецепте.

Подготовка 
---

1 Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation

***Замечание***: Если вы используете версию 2.0.9 (или более раннюю) базового приложения, просто обновите вручную каталог тестов, а также добавьте config/test.php.в , config/test_db.php и web/index-тест.php-файл. Кроме того, вы должны скопировать разделы require и require-dev composer.json-файл и запустить

***composer update.***

2 Создайте и примените следующую миграцию:
```php
<?php
use yii\db\Migration;
class m160309_070856_create_post extends Migration
{
    public function up()
    {
        $this->createTable('{{%post}}',	[
            'id' => $this->primaryKey(),
            'title' => $this->string()->notNull(),
            'text' => $this->text()->notNull(),
            'status' => $this->smallInteger()->notNull()-
            >defaultValue(0),
        ]);
    }
    public function down()
    {
        $this->dropTable('{{%post}}');
    }
}
```

3 Создать модель Post:
```php
namespace app\models;
use Yii;
use yii\db\ActiveRecord;
/**
* @property integer $id
* @property string $title
* @property string $text
* @property integer $status
* @property integer $created_at
* @property integer $updated_at
*/
class Post extends ActiveRecord
{
    const STATUS_DRAFT = 0;
    const STATUS_ACTIVE = 1;
    public static function tableName()
    {
        return '{{%post}}';
    }
    public function rules()
    {
        return [
            [['title', 'text'], 'required'],
            [[' text'],	'string'],
            ['status', 'in', 'range' => [self::STATUS_DRAFT, self::STATUS_ACTIVE]],
            ['status', 'default', 'value' => self::STATUS_DRAFT],
            [['title'], 'string', 'max' => 255],
        ];
    }
    public function behaviors()
    {
        return [
            TimestampBehavior::className(),
        ];
    }
    public static function getStatusList()
    {
        return [
            self::STATUS_DRAFT => 'Draft',
            self::STATUS_ACTIVE => 'Active',
        ];
    }
    public function publish()
    {
        if ($this->status == self::STATUS_ACTIVE) {
            throw new \DomainException('Post is already published.');
        }
        $this->status = self::STATUS_ACTIVE;
    }
    public function draft()
    {
        if ($this->status == self::STATUS_DRAFT) {
        throw new \DomainException('Post is already drafted.');
        }
        $this->status = self::STATUS_DRAFT;
    }
}
```

4 Сгенерируйте CRUD:
![](img/437_1.jpg)

5 Кроме того, добавьте раскрывающийся список состояние для поля состояние и имя для кнопки Отправить в  views/admin/posts/_form.php:
```php
<div class="post-form">
    <?php $form = ActiveForm::begin(); ?>
        <?= $form->field($model, 'title')->textInput(['maxlength' => true]) ?>
        <?= $form->field($model, 'text')->textarea(['rows' => 6]) ?>
        <?= $form->field($model, 'status')->dropDownList(Post::getStatusList()) ?>
        <div class="form-group">
            <?= Html::submitButton($model->isNewRecord ? 'Create' : 'Update', [
                'class' => $model->isNewRecord ? 'btn btn-success' : 'btn btn-primary',
                'name' => 'submit-button',
            ]) ?>
        </div>
    <?php ActiveForm::end(); ?>
</div>
```

6 Теперь проверьте, что контроллер работает:
![](img/439_1.jpg)

Создайте демо-записи.

Как это сделать...
---
***Подготовка к испытаниям***

Выполните следующие действия, чтобы подготовиться к тестам:

1 Создайте yii2_basic_tests или другую тестовую базу данных и обновите ее, применив миграции:

***tests/bin/yii migrate***

Команда должна быть запущена в каталоге тестов. Параметры тестовой базы данных можно указать в файле конфигурации  /config/test_db.php.

2 Codeception использует автогенерируемые классы актеров для собственных тестов. Создайте их с помощью этой команды:

***composer exec codecept build***

***Выполнение модульных и функциональных тестов***

Мы можем запускать любые типы тестов приложения прямо сейчас:
```php
# run all available tests
composer exec codecept run
# run functional tests
composer exec codecept run functional
# run unit tests
composer exec codecept run unit
```
В результате, вы можете осмотреть, отчет по испытаниям как этот:
![](img/441_1.jpg)

***Получение отчетов о покрытии***

Можно получить отчеты о покрытии кода для кода. По умолчанию покрытие кода отключено в конфигурации tests/codeception.yml; вы должны раскомментировать необходимые строки, чтобы иметь возможность собирать покрытие кода:
```php
coverage:
    enabled: true
    whitelist:
        include:
            - models/*
            - controllers/*
            - commands/*
            - mail/*
    blacklist:
        include:
            - assets/*
            - config/*
            - runtime/*
            - vendor/*
            - views/*
            - web/*
            - tests/*
```
Необходимо установить расширение PHP Xdebug с https://xdebug.org. Например, в Ubuntu или Debian вы можете ввести в терминал следующее:

***sudo apt-get install php5-xdebug***

В Windows необходимо открыть php.ini-файл и добавьте пользовательский код с путем к каталогу установки PHP:
```php
[xdebug]
zend_extension_ts=C:/php/ext/php_xdebug.dll
```
Кроме того, если вы используете не потокобезопасный выпуск, введите следующую команду:
```php
[xdebug]
zend_extension=C:/php/ext/php_xdebug.dll
```
Наконец, можно выполнить тесты и собрать отчет о покрытии с помощью следующей команды:
```php
#collect coverage for all tests
composer exec codecept run --coverage-html

#collect coverage only for unit tests
composer exec codecept run unit --coverage-html

#collect coverage for unit and functional tests
composer exec codecept run functional,unit --coverage-html
```
Вы можете увидеть выход покрытия текстового кода в терминале:
```php
Code Coverage Report:
2016-03-31 08:13:05
Summary:
Classes: 20.00% (1/5)
Methods: 40.91% (9/22)
Lines:	30.65% (38/124)
\app\models::ContactForm
Methods:	33.33% ( 1/ 3) Lines: 80.00% ( 12/ 15)
\app\models::LoginForm
Methods: 100.00% ( 4/ 4) Lines: 100.00% ( 18/ 18)
\app\models::User
Methods:	57.14% ( 4/ 7) Lines: 53.33% (	8/ 15)
Remote CodeCoverage reports are not printed to console
HTML report generated in coverage
```
Кроме того, вы можете видеть HTML-отчет в каталоге /tests/codeception/_output/coverage:
![](img/443_1.jpg)


Вы можете нажать на любой класс и проанализировать, какие строки кода не были выполнены в процессе тестирования.

***Выполнение приемочных испытаний***

В приемочных тестах можно использовать PhpBrowser для запроса сервера через Curl. Это помогает проверить контроллеры сайта и проанализировать коды ответов HTTP и HTML. Но если вы хотите проверить поведение CSS или JavaScript, вы должны использовать реальный браузер.
Selenium Server-это интерактивный инструмент, который интегрируется в Firefox и другие браузеры и позволяет открывать страницы сайта и эмулировать действия человека.
Для работы с реальным браузером необходимо установить Selenium Server:

1 Требуется полный пакет Codeception вместо базового:
```php
composer require --dev codeception/codeception
composer remove --dev codeception/base
```

2 Скачать следующее программное обеспечение:
* Установите браузер Mozilla Firefox с https://www.mozilla.org
* Установка среды выполнения Java из https://www.java.com/en/download/
* Скачать Selenium Standalone Server с http://www.seleniumhq.org/download/
* Скачать Geckodriver с https://github.com/mozilla/geckodriver/releases

3 Запустить сервер с драйвером в новом окне терминала:
```php
java -jar -Dwebdriver.gecko.driver=~/geckodriver ~/selenium-server-standalone-x.xx.x.jar
```

4 Скопировать tests/acceptance.suite.yml.example в tests/acceptance.suite.yml -файл и настроить как здесь описано:
```php
class_name: AcceptanceTester
modules:
    enabled:
        - WebDriver:
            url: http://127.0.0.1:8080/
            browser: firefox
        - Yii2:
            part: orm
            entryScript: index-test.php
            cleanup: false
```
5 Открыть новый окно терминала и запустите веб-сервер:

***tests/bin/yii serve***

6 Выполнение приемочных тестов:

***composer exec codecept run acceptance***

И вы должны увидеть, как Selenium запускает браузер и проверить все страницы сайта.

***Создание базы данных fixtures***

Перед выполнением собственных тестов необходимо очистить собственную тестовую базу данных и загрузить в нее определенные тестовые данные. Расширение yii2-codeception предоставляет базовый класс ActiveFixture для создания наборов тестовых данных для собственных моделей. Выполните следующие действия для создания креплений базы данных:

1 Создание класса fixture для модели Post:
```php
<?php
namespace tests\fixtures;
use yii\test\ActiveFixture;
class PostFixture extends ActiveFixture
{
public $modelClass = 'app\modules\Post';
public $dataFile = '@tests/_data/post.php';
}
```
2 Добавьте демонстрационный набор данных в файл test/_data/post.php:
```php
<?php
return [
    [
        'id' => 1,
        'title' => 'First Post',
        'text' => 'First Post Text',
        'status' => 1,
        'created_at' => 1457211600,
        'updated_at' => 1457211600,
    ],
    [
        'id' => 2,
        'title' => 'Old Title For Updating',
        'text' => 'Old Text For Updating',
        'status' => 1,
        'created_at' => 1457211600,
        'updated_at' => 1457211600,
    ],
    [
        'id' => 3,
        'title' => 'Title For Deleting',
        'text' => 'Text For Deleting',
        'status' => 1,
        'created_at' => 1457211600,
        'updated_at' => 1457211600,
    ],
];
```

3 Активируйте поддержку fixtures для модульных и приемочных испытаний. Просто добавить fixtures в файл unit.suite.yml:
```php
class_name: UnitTester
    modules:
        enabled:
            - Asserts
            - Yii2:
        part: [orm, fixtures, email]
```
Также, добавьте часть fixtures в acceptance.suite.yml:
```php
class_name: AcceptanceTester
    modules:
        enabled:
            - WebDriver:
                url: http://127.0.0.1:8080/
                browser: firefox
            - Yii2:
                part: [orm, fixtures]
                entryScript: index-test.php
                cleanup: false
```
4 Повторно создайте классы тестера для применения этих изменений с помощью следующей команды:

***composer exec codecept build***

***Написание юнит и интеграционные тесты***

Модульные и интеграционные тесты проверяют исходный код нашего проекта.
Модульные тесты проверяют только текущий класс или его метод в изоляции от других классов и ресурсов, таких как базы данных, файлы и многое другое.
Интеграционные тесты проверяют работу ваших классов в интеграции с другими классами и ресурсами.
Модели ActiveRecord в Yii2 всегда используют базы данных для загрузки схемы таблицы, так как мы должны создать реальную тестовую базу данных, и наши тесты будут интеграционными.

1 Написать тесты для проверки валидации модели, сохранения и изменения ее статуса:
```php
<?php
namespace tests\unit\models;
use app\models\Post;
use Codeception\Test\Unit;
use tests\fixtures\PostFixture;
class PostTest extends Unit
{
    /**
    * @var \UnitTester
    */
    protected $tester;
    public function _before()
    {
        $this->tester->haveFixtures([
            'post' => [
                'class' => PostFixture::className(),
                'dataFile' => codecept_data_dir() . 'post.php'
            ]
        ]);
    }
    public function testValidateEmpty()
    {
        $model = new Post();
        expect('model should not validate', $model->validate())->false();
        expect('title has error', $model->errors)->hasKey('title');
        expect('title has error', $model->errors)->hasKey('text');
    }
    public function testValidateCorrect()
    {
        $model = new Post([
            'title' => 'Other Post',
            'text' => 'Other Post Text',
        ]);
        expect('model should validate', $model->validate())->true();
    }
    public function testSave()
    {
        $model = new Post([
            'title' => 'Test Post',
            'text' => 'Test Post Text',
        ]);
        expect('model should save', $model->save())->true();
        expect('title is correct', $model->title)->equals('Test Post');
        expect('text is correct', $model->text)->equals('Test Post Text');
        expect('status is draft', $model->status)->equals(Post::STATUS_DRAFT);
        expect('created_at is generated', $model->created_at)->notEmpty();
        expect('updated_at is generated', $model->updated_at)->notEmpty();
    }
    public function testPublish()
    {
        $model = new Post(['status' => Post::STATUS_DRAFT]);
        expect('post is drafted', $model->status)->equals(Post::STATUS_DRAFT);
        $model->publish();
        expect('post is published', $model->status)->equals(Post::STATUS_ACTIVE);
    }
    public function testAlreadyPublished()
    {
        $model = new Post(['status' => Post::STATUS_ACTIVE]);
        $this->setExpectedException('\LogicException');
        $model->publish();
    }
    public function testDraft()
    {
        $model = new Post(['status' => Post::STATUS_ACTIVE]);
        expect('post is published', $model->status)->equals(Post::STATUS_ACTIVE);
        $model->draft();
        expect('post is drafted', $model->status)->equals(Post::STATUS_DRAFT);
    }
    public function testAlreadyDrafted()
    {
        $model = new Post(['status' => Post::STATUS_ACTIVE]);
        $this->setExpectedException('\LogicException');
        $model->publish();
    }
}
```

2 Запуск тестов:

***composer exec codecept run unit***

3 Теперь увидим результат:
![](img/448_1.jpg)

Вот и все. Если вы намеренно или случайно нарушите метод любой модели, вы увидите сломанный тест.

***Написание функционального теста***

Функциональный тест проверяет правильность работы приложения. Этот пакет подготавливает переменные $_GET, $ _POST и другие запросы и вызывает метод Application::handleRequest. Это помогает проверить ваши контроллеры и их ответы без запуска реального сервера.
Теперь мы можем писать тесты для нашего админа CRUD:

1 Создание нового тестового класса:

***codecept generate:cest functional admin/Posts***

2 Исправьте пространство имен в созданном файле и напишите собственные тесты:
```php
<?php
namespace tests\functional\admin;
use app\models\Post;
use FunctionalTester;
use tests\fixtures\PostFixture;
use yii\helpers\Url;
class PostsCest
{
    function _before(FunctionalTester $I)
    {
        $I->haveFixtures([
            'user' => [
                'class' => PostFixture::className(),
                'dataFile' => codecept_data_dir() . 'post.php'
            ]
        ]);
    }
    public function testIndex(FunctionalTester $I)
    {
        $I->amOnPage(['admin/posts/index']);
        $I->see('Posts',	'h1');
    }
    public function testView(FunctionalTester $I)
    {
        $I->amOnPage(['admin/posts/view', 'id' => 1]);
        $I->see('First Post', 'h1');
    }
    public function testCreateInvalid(FunctionalTester $I)
    {
        $I->amOnPage(['admin/posts/create']);
        $I->see('Create',	'h1');
        $I->submitForm('#post-form', [
            'Post[title]' => '',
            ' Post[text]' => '',
        ]);
        $I->expectTo('see validation errors');
        $I->see('Title cannot be blank.', '.help-block');
        $I->see('Text cannot be blank.', '.help-block');
    }
    public function testCreateValid(FunctionalTester $I)
    {
        $I->amOnPage(['admin/posts/create']);
        $I->see('Create',	'h1');
        $I->submitForm('#post-form', [
            'Post[title]' => 'Post Create Title',
            'Post[text]' => 'Post Create Text',
            'Post[status]' => 'Active',
        ]);
        $I->expectTo('see view page');
        $I->see('Post Create Title', 'hi');
    }
    public function testUpdate(FunctionalTester $I)
    {
    // ...
    }
    public function testDelete(FunctionalTester $I)
    {
        $I->amOnPage(['/admin/posts/view', 'id' => 3]);
        $I->see('Title For Deleting', 'h1');
        $I->amGoingTo('delete item');
        $I->sendAjaxPostRequest(Url::to(['/admin/posts/delete', 'id' => 3]));
            $I->expectTo('see that post is deleted');
            $I->dontSeeRecord(Post::className(), [
            'title' => 'Title For Deleting',
        ]);
    }
}
```

3 Запустите тесты с помощью команды:

***composer exec codecept run functional***


4 Теперь смотрите результаты:
![](img/451_1.jpg)

Все тесты прошли. В другом случае вы можете увидеть снимки тестируемых страниц в каталоге tests/_output для неудачных тестов.

***Написание приемочных испытаний***

1 Тестер приемки попал на реальный сайт с тестового сервера вместо вызова метода Application::handleRequest. Высокоуровневые приемочные тесты выглядят как функциональные тесты среднего уровня, но в случае Selenium это позволяет проверить поведение JavaScript в реальном браузере.

2 В каталоге tests/acceptance необходимо получить следующий класс:
```php
<?php
namespace tests\acceptance\admin;
use AcceptanceTester;
use tests\fixtures\PostFixture;
use yii\helpers\Url;
class PostsCest
{
    function _before(AcceptanceTester $I)
    {
        $I->haveFixtures([
            'post' => [
                'class' => PostFixture::className(),
                'dataFile' => codecept_data_dir() . 'post.php'
            ]
        ]);
    }
    public function testIndex(AcceptanceTester $I)
    {
        $I->wantTo('ensure that post index page works');
        $I->amOnPage(Url::to(['/admin/posts/index']));
        $I->see('Posts',	'h1');
    }
    public function testView(AcceptanceTester $I)
    {
        $I->wantTo('ensure that post view page works');
        $I->amOnPage(Url::to(['/admin/posts/view', 'id' => 1]));
        $I->see('First Post', 'h1');
    }
    public function testCreate(AcceptanceTester $I)
    {
        $I->wantTo('ensure that post create page works');
        $I->amOnPage(Url::to(['/admin/posts/create']));
        $I->see('Create',	'h1');
        $I->fillField('#post-title', 'Post Create Title');
        $I->fillField('#post-text', 'Post Create Text');
        $I->selectOption('#post-status',	'Active');
        $I->click( 'submit-button');
        $I->wait(3);
        $I->expectTo('see view page');
        $I->see('Post Create Title', 'h1');
    }
    public function testDelete(AcceptanceTester $I)
    {
        $I->amOnPage(Url::to(['/admin/posts/view', 'id' => 3]));
        $I->see('Title For Deleting', 'h1');
        $I->click('Delete');
        $I->acceptPopup();
        $I->wait(3);
        $I->see('Posts',	'h1');
    }
}
```
Не забудьте вызвать метод wait для ожидания открытия или перезагрузки страницы.

3 Запустите тестовый сервер PHP в новом терминальном окне:

***tests/bin/yii serve***

4 Выполнение приемочных тестов:

***composer exec codecept run acceptance***

5 Смотрите результат:
![](img/453_1.jpg)

Selenium запустит веб-браузер Firefox и выполнит наши команды тестирования.

***Создание набора тестов API***

Помимо единичных, функциональных и приемочных комплектов, Codeception позволяет создавать специальные наборы тестов. Например, мы можем создать его для тестирования API с поддержкой синтаксического анализа XML и JSON.

1 Создайте контроллеры rest API controllers/api/PostsController.php для модели Post:
```php
<?php
namespace app\controllers\api;
use yii\rest\ActiveController;
class PostsController extends ActiveController
{
public $modelClass = '\app\models\Post';
}
```

2 Добавьте маршруты REST для компонента UrlManager в config/web.php:
```php
'components' => [
    // ...
    'urlManager' => [
        'enablePrettyUrl' => true,
        'showScriptName' => false,
        'rules' => [
            ['class' => 'yii\rest\UrlRule', 'controller' => 'api/posts'],
        ],
    ],
],
```
и некоторая конфигурация (но с включенной опцией showScriptName) в config/test.php:
```php
'components' => [
    // ...
    'urlManager' => [
        'enablePrettyUrl' => true,
        'showScriptName' => true,
        'rules' => [
            ['class' => 'yii\rest\UrlRule', 'controller' => 'api/posts'],
        ],
    ],
],
```

3 Добавьте в файл web/.htaccess следующим содержимым:
```php
RewriteEngine On
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule . index.php
```
4 Убедитесь, что контроллер api/posts работает:
![](img/454_1.jpg)

5 Создайте конфигурации набора тестов API tests/api.suite.yml    с модулем REST:
```php
class_name: ApiTester
modules:
enabled:
- REST:
depends: PhpBrowser
url:	'http://127.0.0.1:8080/index-test.php'
part: [json]
- Yii2:
part: [orm, fixtures]
entryScript: index-test.php
```
Теперь перестройте тесты:

***composer exec codecept build***

6 Создайте каталог tests/api и создайте новый тестовый класс:

***composer exec codecept generate:cest api Posts***

7 Напишите тесты для вашего rest-API:
```php
<?php
namespace tests\api;
use ApiTester;
use tests\fixtures\PostFixture;
use yii\helpers\Url;
class PostsCest
{
    function _before(ApiTester $I)
    {
    $I->haveFixtures([
        'post' => [
            'class' => PostFixture::className(),
            'dataFile' => codecept_data_dir() . 'post.php'
        ]
    ]);
    }
    public function testGetAll(ApiTester $I)
    {
        $I->sendGET('/api/posts');
        $I->seeResponseCodeIs(200);
        $I->seeResponseIsJson();
        $I->seeResponseContainsJson([0 => ['title' => 'First Post']]);
    }
    public function testGetOne(ApiTester $I)
    {
        $I->sendGET('/api/posts/1');
        $I->seeResponseCodeIs(200);
        $I->seeResponseIsJson();
        $I->seeResponseContainsJson(['title' => 'First Post']);
    }
    public function testGetNotFound(ApiTester $I)
    {
        $I->sendGET( '/api/posts/100');
        $I->seeResponseCodeIs(404);
        $I->seeResponseIsJson();
        $I->seeResponseContainsJson(['name' => 'Not Found']);
    }
    public function testCreate(ApiTester $I)
    {
        $I->sendPOST('/api/posts', [
            'title' => 'Test Title',
            'text' => 'Test Text',
        ]);
        $I->seeResponseCodeIs(201);
        $I->seeResponseIsJson();
        $I->seeResponseContainsJson(['title' => 'Test Title']);
    }
    public function testUpdate(ApiTester $I)
    {
        $I->sendPUT('/api/posts/2', [
            'title' => 'New Title',
        ]);
        $I->seeResponseCodeIs(200);
        $I->seeResponseIsJson();
        $I->seeResponseContainsJson([
            'title' => 'New Title',
            'text' => 'Old Text For Updating',
        ]);
    }
    public function testDelete(ApiTester $I)
    {
        $I->sendDELETE('/api/posts/3');
        $I->seeResponseCodeIs(204);
    }
}
```

8 Запустить сервер приложений:

***tests/bin yii serve***


9 Тесты по API:

***composer exec codecept run api***

Теперь смотрите результат:
![](img/456_1.jpg)
 Все тесты пройдены и наш API работает корректно.

Как это работает...
---
Codeception-это высокоуровневая фреймворк тестирования, основанный на пакете PHPUnit для обеспечения инфраструктуры для написания модульных, интеграционных, функциональных и приемочных тестов.
Мы можем использовать встроенный модуль Yii2 Codeception, который позволяет загружать fixtures, работать с моделями и многое другое из фреймворка Yii.

Смотрите так же
---
* Для получения дополнительной информации обратитесь к:
 <http://codeception.com/docs/01-Introduction>
 <https://phpunit.de/manual/5.2/en/installation.html>
<https://github.com/kopyrin/doc-codeception> 
* The tests/README. md file of your basic or advanced application:
<https://github.com/yiisoft/yii2-app-basic/blob/master/tests/RFADMF.md>
<https://github.com/yiisoft/yri2-app-advanced/blob/mastpr/tpsts/RFADME.md>
8 Рецепт  Тестирование с PHPUnit




Тестирование с PHPUnit
===
PHPUnit является самой популярной платформой тестирования PHP. Он прост для конфигурации и использования. Кроме того, Платформа поддерживает отчеты о покрытии кода и имеет множество дополнительных плагинов. Codeception из предыдущего рецепта использует PHPUnit для собственной работы и написания модульных тестов. В этом рецепте мы создадим демонстрационное расширение корзины покупок с тестами PHPUnit.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
Во-первых, мы должны создать новый пустой каталог для собственного расширения.

***Подготовка структуры расширения***

1 Сначала создайте структуру каталогов для расширения:

![](img/458_1.jpg)

 Для работы с расширением в качестве пакета Composer подготовьте файл book/cart/composer.json, как этот:
```php
{
    "name": "book/cart",
    "type": "yii2-extension",
    "require": {
        "yiisoft/yii2": "~2.0"
    },
    "require-dev": {
        "phpunit/phpunit": "4.*"
    },
    "autoload": {
        "psr -4": {
        "book\\cart\\": "src/",
        "book\\cart\\tests\\": "tests/"
    }
    },
    "extra": {
        "asset-installer-paths": {
            "npm-asset-library": "vendor/npm",
            "bower-asset-library": "vendor/bower"
        }
    }
}
```

2 Добавить в файл book/cart/.gitignore следующие строки:
```php
/vendor
/composer.lock
```

3 Добавьте следующие строки в файл конфигурации PHPUnit по умолчанию book/cart/phpunit.xml.dist:
```php
<?xml version="1.0" encoding="utf-8"?>
<phpunit bootstrap="./tests/bootstrap.php"
    colors="true"
    convertErrorsToExceptions="true"
    convertNoticesToExceptions="true"
    convertWarningsToExceptions="true"
    stopOnFailure="false">
    <testsuites>
        <testsuite name="Test Suite">
            <directory>./tests</directory>
        </testsuite>
    </testsuites>
    <filter>
        <whitelist>
            <directory suffix=".php">./src/</directory>
        </whitelist>
    </filter>
</phpunit>
```
4 Установите все зависимости расширения:

***composer install***

5 Теперь мы должны получить следующую структуру:
![](img/459_1.jpg)

***Написание кода расширения***

Чтобы написать код расширения, выполните следующие действия:

1 Создайте класс book\cart\cart в каталоге src:
```
<?php
namespace book\cart;
use book\cart\storage\StorageInterface;
use yii\base\Component;
use yii\base\InvalidConfigException;
class Cart extends Component
{
    /**
    * @var StorageInterface
    */
    private $_storage;
    /**
    * @var array
    */
    private $_items;
    public function setStorage($storage)
    {
        if (is_array($storage)) {
            $this->_storage = \Yii::createObject($storage);
        } else {
            $this->_storage = $storage;
        }
    }
    public function add($id, $amount = 1)
    {
        $this->loadItems();
        if (isset($this->_items[$id])) {
            $this->_items[$id] += $amount;
        } else {
            $this->_items[$id] = $amount;
        }
        $this->saveItems();
    }
    public function set($id, $amount)
    {
        $this->loadItems();
        $this->_items[$id] = $amount;
        $this->saveItems();
    }
    public function remove($id)
    {
        $this->loadItems();
        if (isset($this->_items[$id])) {
            unset($this->_items[$id]);
        }
        $this->saveItems();
    }
    public function clear()
    {
        $this->loadItems();
        $this->_items = [];
        $this->saveItems();
    }
    public function getItems()
    {
        $this->loadItems();
        return $this->_items;
    }
    public function getCount()
    {
        $this->loadItems();
        return count($this->_items);
    }
    public function getAmount()
    {
        $this->loadItems();
        return array_sum($this->_items);
    }
    private function loadItems()
    {
        if ($this->_storage === null) {
            throw new InvalidConfigException('Storage must be set');
        }
        if ($this->_items === null) {
            $this->_items = $this->_storage->load();
        }
    }
    private function saveItems()
    {
        $this->_storage->save($this->_items);
    }
}
```

2 Создайте интерфейс Storageinterface в подкаталоге src/storage:
```php
<?php
namespace book\cart\storage;
interface StorageInterface
{
/**
* @return array
*/
public function load();
/**
* @param array $items
*/
public function save(array $items);
}
```
И класс SessionStorage:
```php
namespace book\cart\storage;
use Yii;
class SessionStorage implements StorageInterface
{
    public $sessionKey = 'cart';
    public function load()
    {
        return Yii::$app->session->get($this->sessionKey, []);
    }
    public function save(array $items)
    {
        Yii::$app->session->set($this->sessionKey, $items);
    }
}
```

3 Теперь мы должны получить следующую структуру:
![](img/461_1.jpg)

***Написание тестов расширений***

Чтобы провести тест расширения, выполните следующие действия:

1 Добавьте book/cart/tests/bootstrap.php как скрипт при входе для PHPUnit:
```php
<?php
defined('YII_DEBUG') or define('YII_DEBUG', true);
defined('YII_ENV') or define('YII_ENV', 'test');
require( DIR  . '/../vendor/autoload.php');
require( DIR  . '/../vendor/yiisoft/yii2/Yii.php');
```

2 Создайте тестовый базовый класс, инициализируя приложение Yii перед каждым тестом и уничтожая приложение впоследствии:
```php
<?php
namespace book\cart\tests;
use yii\di\Container;
use yii\web\Application;
abstract class TestCase extends \PHPUnit_Framework_TestCase
{
    protected function setUp()
    {
        parent::setUp();
        $this->mockApplication();
    }
    protected function tearDown()
    {
        $this->destroyApplication();
        parent::tearDown();
    }
    protected function mockApplication()
    {
        new Application([
            'id' => 'testapp',
            'basePath' => 	DIR	,
            'vendorPath' => dirname(	DIR	) . '/vendor',
        ]);
    }
    protected function destroyApplication()
    {
        \Yii::$app = null;
        \Yii::$container = new Container();
    }
}
```

3 Добавьте класс FakeStorage , реализующий интерфейс StorageInterface:
```php
<?php
namespace book\cart\tests\storage;
use book\cart\storage\StorageInterface;
class FakeStorage implements StorageInterface
{
    private $items = [];
    public function load()
    {
        return $this->items;
    }
    public function save(array $items)
    {
        $this->items = $items;
    }
}
```
Он будет хранить элементы в частной переменной вместо работы с реальным сеансом. Это позволяет выполнять тесты независимо (без реального драйвера хранилища), а также повышает производительность тестирования.

4 Добавьте класс cartTest:
```php
<?php
namespace book\cart\tests;
use book\cart\Cart;
use book\cart\tests\storage\FakeStorage;
class CartTest extends TestCase
{
    /**
    * @var Cart
    */
    private $cart;
    public function setUp()
    {
        parent::setUp();
        $this->cart = new Cart(['storage' => new FakeStorage()]);
    }
    public function testEmpty()
    {
        $this->assertEquals([], $this->cart->getItems());
        $this->assertEquals(0, $this->cart->getCount());
        $this->assertEquals(0, $this->cart->getAmount());
    }
    public function testAdd()
    {
        $this->cart->add(5, 3);
        $this->assertEquals([5 => 3], $this->cart->getItems());
        $this->cart->add(7, 14);
        $this->assertEquals([5 => 3, 7 => 14], $this->cart->getItems());
        $this->cart->add(5, 10);
        $this->assertEquals([5 => 13, 7 => 14], $this->cart->getItems());
    }
    public function testSet()
    {
        $this->cart->add(5, 3);
        $this->cart->add(7, 14);
        $this->cart->set(5, 12);
        $this->assertEquals([5 => 12, 7 => 14], $this->cart->getItems());
    }
    public function testRemove()
    {
        $this->cart->add(5, 3);
        $this->cart->remove(5);
        $this->assertEquals([], $this->cart->getItems());
    }
    public function testClear()
    {
        $this->cart->add(5, 3);
        $this->cart->add(7, 14);
        $this->cart->clear();
        $this->assertEquals([], $this->cart->getItems());
    }
    public function testCount()
    {
        $this->cart->add(5, 3);
        $this->assertEquals(1, $this->cart->getCount());
        $this->cart->add(7, 14);
        $this->assertEquals(2, $this->cart->getCount());
    }
    public function testAmount()
    {
        $this->cart->add(5, 3);
        $this->assertEquals(3, $this->cart->getAmount());
        $this->cart->add(7, 14);
        $this->assertEquals(17, $this->cart->getAmount());
    }
    public function testEmptyStorage()
    {
        $cart = new Cart();
        $this->setExpectedException('yii\base\InvalidConfigException');
        $cart->getItems();
    }
}
```

5 	Добавьте отдельный тест для проверки класса SessionStorage:
```php
<?php
namespace book\cart\tests\storage;
use book\cart\storage\SessionStorage;
use book\cart\tests\TestCase;
class SessionStorageTest extends TestCase
{
    /**
    * @var SessionStorage
    */
    private $storage;
    public function setUp()
    {
        parent::setUp();
        $this->storage = new SessionStorage(['key' => 'test']);
    }
    public function testEmpty()
    {
        $this->assertEquals([], $this->storage->load());
    }
    public function testStore()
    {
        $this->storage->save($items = [1 => 5, 6 => 12]);
        $this->assertEquals($items, $this->storage->load());
    }
}
```

6 Сейчас мы должны получить следующую структуру:
![](img/465_1.jpg)

Запуск тестов

Во время установки всех зависимостей с помощью команды composer install менеджер пакетов Composer устанавливает пакет PHPUnit в каталог vendor и помещает исполняемый файл phpunit в подкаталог vendor/bin.
Теперь мы можем запустить следующий скрипт:
```php
cd book/cart
vendor/bin/phpunit
```
Мы должны увидеть следующий отчет по испытаниям:
```php
PHPUnit 4.8.26 by Sebastian Bergmann and contributors.
Time: 906 ms, Memory: 11.50MB
OK (10 tests, 16 assertions)
```
Каждая точка показывает успешный результат соответствующего теста.
Попробуйте намеренно сломать собственную корзину, комментируя операцию unset:
```php
class Cart extends Component
{
    public function remove($id)
    {
        $this->loadItems();
        if (isset($this->_items[$id])) {
            // unset($this->_items[$id]);
        }
        $this->saveItems();
    }
}
```
Запустите тесты еще раз:
```php
PHPUnit 4.8.26 by Sebastian Bergmann and contributors.
. . . F	
Time: 862 ms, Memory: 11.75MB
There was 1 failure:
1) book\cart\tests\CartTest::testRemove
Failed asserting that two arrays are equal.
	 Expected
+++ Actual
@@ @@
Array (
+	5 => 3
)
/book/cart/tests/CartTest.php:52
FAILURES!
Tests: 10, Assertions: 16, Failures: 1
```
В этом случае мы видели один сбой (помеченный как F вместо точки) и отчет об ошибке.

***Анализ покрытия кода***

Необходимо установить расширение XDebug PHP с https://xdebug.org. Например, в Ubuntu или Debian в терминале можно ввести следующее:

***sudo apt-get install php5-xdebug***

В Windows необходимо открыть php.ini-файл и добавить пользовательский код с путем к каталогу установки PHP:
```php
[xdebug]
zend_extension_ts=C:/php/ext/php_xdebug.dll

```
Кроме того, если вы используете не потокобезопасный выпуск, введите следующую команду:
```php
[xdebug]
zend_extension=C:/php/ext/php_xdebug.dll
```
После установки XDebug снова запустите тесты с флагом -- coverage-html и укажите каталог отчетов:

***vendor/bin/phpunit --coverage-html tests/_output***

После запуска откройте tests/_output/index.html-файл в вашем браузере вы увидите отчет о явном покрытии для каждого каталога и класса:
![](img/467_1.jpg)

Вы можете нажать на любой класс и проанализировать, какие строки кода не были выполнены во время тестирования  процесс. Например, откройте наш отчет класс корзины:
![](img/467_2.jpg)

В нашем случае мы забыли протестировать создание хранилища из конфигурации массива.

***Использование компонента***

После публикации расширения в Packagist мы можем установить проект один-в-один к любому проекту:
```php
composer require book/cart
```
Кроме того, включите компонент в файле конфигурации приложения:
```php
'components' => [
    // ...
    'cart' => [
        'class' => 'book\cart\Cart',
        'storage' => [
            'class' => 'book\cart\storage\SessionStorage',
        ],
    ],
],
```
В качестве альтернативного способа без публикации расширения в Packagist мы должны настроить псевдоним @book для включения правильной автоматической загрузки классов:
```php
$config = [
    'id' => ' basic',
    'basePath' => dirname(__DIR__),
    'bootstrap' => ['log'],
    'aliases' => [
        '@book' => dirname(__DIR__) . '/book',
    ],
    'components' => [
        'cart' => [
            'class' => 'book\cart\Cart',
            'storage' => [
                'class' => 'book\cart\storage\SessionStorage',
            ],
        ],
    // ...
    ],
]
```
В любом случае, мы можем использовать его как компонент yii::$app->cart в нашем проекте:
```php
Yii::$app->cart->add($product->id, $amount);
```

Как это работает...
---
Перед созданием собственных тестов необходимо просто создать любой подкаталог и добавить phpunit.xml или phpunit.xml.dist-файл в корневом каталоге проекта:
```php
<?xml version="1.0" encoding="utf-8"?>
<phpunit bootstrap="./tests/bootstrap.php"
    colors="true"
    convertErrorsToExceptions="true"
    convertNoticesToExceptions="true"
    convertWarningsToExceptions="true"
    stopOnFailure="false">
    <testsuites>
        <testsuite name="Test Suite">
            <directory>./tests</directory>
        </testsuite>
    </testsuites>
    <filter>
        <whitelist>
            <directory suffix=".php">./src/</directory>
        </whitelist>
    </filter>
</phpunit>
```
PHPUnit загружает конфигурацию из второго файла, если первый не существует в рабочем каталоге. Кроме того, вы можете создать bootstrap.php файл путем инициализации autoloader и среды вашего фреймворка:
```php
<?php
defined('YII_DEBUG') or define('YII_DEBUG', true);
defined('YII_ENV') or define('YII_ENV', 'test');
require( DIR  . '/../vendor/autoload.php');
require( DIR  . '/../vendor/yiisoft/yii2/Yii.php');
```
Наконец, можно установить PHPUnit с помощью Composer (локально или глобально) и использовать команду консоли phpunit в каталоге с файлом конфигурации XML.
PHPUnit сканирует каталог тестирования и находит файлы с суффиксом *Test.php . Все тестовые классы должны расширять класс PHPUnit_Framework_Testcase и содержать открытые методы с префиксом test*:
```php
class MyTest extends TestCase
{
    public function testSomeFunction()
    {
        $this->assertTrue(true);
    }
}
```
В теле тестов можно использовать любой из существующих методов assert*:
```php
$this->assertEqual('Alex', $model->name);
$this->assertTrue($model->validate());
$this->assertFalse($model->save());
$this->assertCount(3, $items);
$this->assertArrayHasKey('username', $model->getErrors());
$this->assertNotNull($model->author);
$this->assertInstanceOf('app\models\User', $model->author);
```
Кроме того, можно переопределить методы setUp() или tearDown() для добавления выражений, которые будут выполняться до и после каждого метода теста.
Например, можно определить собственный базовый класс TestCase путем повторной инициализации приложения Yii:
```php
<?php
namespace book\cart\tests;
use yii\di\Container;
use yii\web\Application;
abstract class TestCase extends \PHPUnit_Framework_TestCase
{
    protected function setUp()
    {
        parent::setUp();
        $this->mockApplication();
    }
    protected function tearDown()
    {
        $this->destroyApplication();
        parent::tearDown();
    }
    protected function mockApplication()
    {
        new Application([
            'id' => 'testapp',
            'basePath' => __DIR__,
            'vendorPath' => dirname(__DIR__) . '/vendor',
        ]);
    }
    protected function destroyApplication()
    {
        \Yii::$app = null;
        \Yii::$container = new Container();
    }
}
```
Теперь вы можете расширить этот класс на подклассы. Даже ваш метод тестирования будет работать с собственным экземпляром приложения. Это помогает избежать побочных эффектов и создать независимые тесты.

***Замечание***: Yii 2.0.* использует старый PHPUnit 4.* Версия для совместимости с PHP 5.4.

Смотрите так же
---
* Всю информацию об использовании PHPUnit см. в официальной документации по адресу
<https://phpunit.de/manual/current/en/index.html>
* Рецепт  Тестирование приложения с Codeception




Unit тестирование с Atoum
===
Кроме того phpunit и Codeception, Atoum фреймворк простой модульного тестирования. Эту платформу можно использовать для тестирования расширений или кода приложения.

Подготовка 
---
Создайте пустой каталог для нового проекта.

Как это сделать...
---
В этом рецепте мы создадим демонстрационное расширение корзины покупок с тестами Atoum.

***Подготовка структуры расширения***

1 Сначала создайте структуру каталогов для расширения:
![](img/471_1.jpg)

2 Для работы с расширением в качестве пакета composer подготовьте файл book/cart/composer.json следующим образом:
```php
{
    "name": "book/cart",
    "type": "yii2-extension",
    "require": {
        "yiisoft/yii2": "~2.0"
    },
    "require-dev": {
        "atoum/atoum": "A2.7"
    },
    "autoload": {
        "psr -4": {
        "book\\cart\\": "src/",
        "book\\cart\\tests\\": "tests/"
    }
    },
    "extra": {
        "asset-installer-paths": {
            "npm-asset-library": "vendor/npm",
            "bower-asset-library": "vendor/bower"
        }
    }
}
```

3 Добавьте следующие строки в файл book/cart/, .gitignore:
```php
/vendor
/composer.lock
```
4 Установите все зависимости расширения:

***composer install***

5 Теперь мы получим следующую структуру:
![](img/472_1.jpg)

***Написание кода расширения***

Скопируйте классы Cart, Storageinterface и Sessionstorage из модульного тестирования с помощью рецепта PHPUnit.
Наконец, мы должны получить следующую структуру:

![](img/472_2.jpg)

***Написание тестов расширений***

1 Добавьте book/cart/tests/bootstrap.php:
```php
<?php
defined('YII_DEBUG') or define('YII_DEBUG', true);
defined('YII_ENV') or define('YII_ENV', 'test');
require( DIR  . '/../vendor/autoload.php');
require( DIR  . '/../vendor/yiisoft/yii2/Yii.php');
```

2 Создайте тестовый базовый класс, инициализируя приложение Yii перед каждым тестом и уничтожая приложение после них:
```php
<?php
namespace book\cart\tests;
use yii\di\Container;
use yii\console\Application;
use mageekguy\atoum\test;
abstract class TestCase extends test
{
    public function beforeTestMethod($method)
    {
        parent::beforeTestMethod($method);
        $this->mockApplication();
    }
    public function afterTestMethod($method)
    {
        $this->destroyApplication();
        parent::afterTestMethod($method);
    }
    protected function mockApplication()
    {
        new Application([
            'id' => 'testapp',
            'basePath' => __DIR__,
            'vendorPath' => dirname(__DIR__) . '/vendor',
            'components' => [
                'session' => [
                    'class' => 'yii\web\Session',
                ],
            ]
        ]);
    }
    protected function destroyApplication()
    {
        \Yii::$app = null;
        \Yii::$container = new Container();
    }
}
```

3 Добавьте класс FakeStorage , реализующий интерфейс StorageInterface:
```php
<?php
namespace book\cart\tests;
use book\cart\storage\StorageInterface;
class FakeStorage implements StorageInterface
{
    private $items = [];
    public function load()
    {
        return $this->items;
    }
    public function save(array $items)
    {
        $this->items = $items;
    }
}
```
Это позволит хранить элементы в частной переменной вместо работы с реальным сеансом. Это позволяет нам запускать тесты независимо (без реального драйвера хранилища), а также улучшает производительность тестирования.

4 Добавьте класс теста Корзина:
```php
<?php
namespace book\cart\tests\units;
use book\cart\tests\FakeStorage;
use book\cart\Cart as TestedCart;
use book\cart\tests\TestCase;
class Cart extends TestCase
{
    /**
    * @var TestedCart
    */
    private $cart;
    public function beforeTestMethod($method)
    {
        parent::beforeTestMethod($method );
        $this->cart = new TestedCart(['storage' => new FakeStorage()]);
    }
    public function testEmpty()
    {
        $this->array($this->cart->getItems())->isEqualTo([]);
        $this->integer($this->cart->getCount())->isEqualTo(0);
        $this->integer($this->cart->getAmount())->isEqualTo(0);
    }
    public function testAdd()
    {
        $this->cart->add(5, 3);
        $this->array($this->cart->getItems())->isEqualTo([5 => 3]);
        $this->cart->add(7, 14);
        $this->array($this->cart->getItems())->isEqualTo([5 => 3, 7 => 14]);
        $this->cart->add(5, 10);
        $this->array($this->cart->getItems())->isEqualTo([5 => 13, 7 => 14]);
    }
    public function testSet()
    {
        $this->cart->add(5, 3);
        $this->cart->add(7, 14);
        $this->cart->set(5, 12);
        $this->array($this->cart->getItems())->isEqualTo([5 => 12, 7 => 14]);
    }
    public function testRemove()
    {
        $this->cart->add(5, 3);
        $this->cart->remove(5);
        $this->array($this->cart->getItems())->isEqualTo([]);
    }
    public function testClear()
    {
        $this->cart->add(5, 3);
        $this->cart->add(7, 14);
        $this->cart->clear();
        $this->array($this->cart->getItems())->isEqualTo([]);
    }
    public function testCount()
    {
        $this->cart->add(5, 3);
        $this->integer($this->cart->getCount())->isEqualTo(1);
        $this->cart->add(7, 14);
        $this->integer($this->cart->getCount())->isEqualTo(2);
    }
    public function testAmount()
    {
        $this->cart->add(5, 3);
        $this->integer($this->cart->getAmount())->isEqualTo(3);
        $this->cart->add(7, 14);
        $this->integer($this->cart->getAmount())->isEqualTo(17);
    }
    public function testEmptyStorage()
    {
        $cart = new TestedCart();
        $this->exception(function () use ($cart) {
            $cart->getItems();
        })->hasMessage('Storage must be set');
    }
}
```

5 Добавьте отдельный тест для проверки класса SessionStorage:
```php
<?php
namespace book\cart\tests\units\storage;
use book\cart\storage\SessionStorage as TestedStorage;
use book\cart\tests\TestCase;
class SessionStorage extends TestCase
{
    /**
    * @var TestedStorage
    */
    private $storage;
    public function beforeTestMethod($method)
    {
        parent::beforeTestMethod($method);
        $this->storage = new TestedStorage(['key' => 'test']);
    }
    public function testEmpty()
    {
        $this
        ->given($storage = $this->storage)
        ->then
        ->array($storage->load())
        ->isEqualTo([]);
    }
    public function testStore()
    {
        $this
        ->given($storage = $this->storage)
        ->and($storage->save($items = [1 => 5, 6 => 12]))
        ->then
        ->array($this->storage->load())
        ->isEqualTo($items)
    ;
    }
}
```
6 Теперь мы получим следующую структуру:
![](img/475_1.jpg)

***Запуск тестов***

Во время установки всех зависимостей с помощью команды composer install менеджер пакетов Composer устанавливает пакет Atounm в каталог vendor и помещает исполняемый файл atoum в подкаталог vendor/bin.
Теперь мы можем запустить следующий скрипт:
```php
cd book/cart
vendor/bin/atoum -d tests/units -bf tests/bootstrap.php
```
Также, мы должны увидеть следующий отчет по испытаниям:
```php
> atoum path: /book/cart/vendor/atoum/atoum/vendor/bin/atoum
> atoum version: 2.7.0
> atoum path: /book/cart/vendor/atoum/atoum/vendor/bin/atoum
> atoum version: 2.7.0
> PHP path: /usr/bin/php5
> PHP version:
=> PHP 5.5.9-1ubuntu4.16 (cli)
> book\cart\tests\units\Cart...
[SSSSSSSS	] [8/8]
=> Test duration: 1.13 seconds.
=> Memory usage: 3.75 Mb.
> book\cart\tests\units\storage\SessionStorage...
[SS	] [2/2]
=> Test duration: 0.03 second.
=> Memory usage: 1.00 Mb.
> Total tests duration: 1.15 seconds.
> Total tests memory usage: 4.75 Mb.
> Code coverage value: 16.16%
```
Каждый символ S показывает успешный результат соответствующего теста.
Попробуйте намеренно сломать корзину, комментируя операцию unset:
```php
class Cart extends Component
{
    public function remove($id)
    {
    $this->loadItems();
    if (isset($this->_items[$id])) {
        // unset($this->_items[$id]);
    }
    $this->saveItems();
    }
}
```
Запустите тесты еще раз:
```php
> atoum version: 2.7.0
> PHP path: /usr/bin/php5
> PHP version:
=> PHP 5.5.9-1ubuntu4.16 (cli)
book\cart\tests\units\Cart...
[SSFSSSSS	] [8/8]
=> Test duration: 1.09 seconds.
=> Memory usage: 3.25 Mb.
> book\cart\tests\units\storage\SessionStorage...
[SS	] [2/2]
=> Test duration: 0.02 second.
=> Memory usage: 1.00 Mb.
Failure (2 tests, 10/10 methods, 0 void method, 0 skipped method, 0 uncompleted method, 1
failure, 0 error, 0 exception)!
> There is 1 failure:
=> book\cart\tests\units\Cart::testRemove():
In file /book/cart/tests/units/Cart.php on line 53, mageekguy\atoum\asserters\phpArray()
failed: array(1) is not equal to array(0)
-Expected
+Actual
@@ -1 +1,3 @@
-array(0) {
+array(1) {
+	[5] =>
+ int(3)
```
В этом случае мы видели один сбой (помеченный как F вместо точки) и отчет об ошибке.

***Анализ покрытия кода***

Необходимо установить расширение XDebug PHP с https://xdebug.org. Например, в Ubuntu или Debian вы можете ввести в терминал следующее:

***sudo apt-get install php5-xdebug***

В Windows необходимо открыть php.ini-файл и добавьте пользовательский код с путем к каталогу установки PHP:
```php
[xdebug]
zend_extension_ts=C:/php/ext/php_xdebug.dll
```
Кроме того, если вы используете не потокобезопасный выпуск, введите следующую команду:
```php
[xdebug]
zend_extension=C:/php/ext/php_xdebug.dll
```
После установки XDebug создайте book/cart/coverage.php с параметрами отчета о покрытии:
```php
<?php
use \mageekguy\atoum;
/** @var atoum\scripts\runner $script */
$report = $script->addDefaultReport();
$coverageField = new atoum\report\fields\runner\coverage\html('Cart', 	DIR	 .
' /tests/coverage');
$report->addField($coverageField);
```
Теперь выполните тесты снова с опцией -c для использования этой конфигурации:

***vendor/bin/atoum -d tests/units -bf tests/bootstrap.php -c coverage.php***

После выполнения тестов откройтеtests/coverage/index.html файл в вашем браузере. Вы увидите отчет о явном покрытии для каждого каталога и класса:
![](img/478_1.jpg)

Вы можете нажать на любой класс и проанализировать, какие строки кода не были выполнены в процессе тестирования.

Как это работает...
---
Платформа тестирования Atoum поддерживает синтаксический поток поведенческого проектирования (BDD) следующим образом:
```php
public function testSome()
{
$this
    ->given($cart = new TestedCart())
    ->and($cart->add(5, 13))
    ->then
    ->sizeof($cart->getItems())
    ->isEqualTo(1)
    ->array($cart->getItems())
    ->isEqualTo([5 => 3])
    ->integer($cart->getCount())
    ->isEqualTo(1)
    ->integer($cart->getAmount())
    ->isEqualTo(3);
}
```
Однако для написания модульных тестов можно использовать обычный phpunit-подобный синтаксис:
```php
public function testSome()
{
    $cart = new TestedCart();
    $cart->add(5, 3);
    $this
        ->array($cart->getItems())->isEqualTo([5 => 3])
        ->integer($cart->getCount())->isEqualTo(1)
        ->integer($cart->getAmount())->isEqualTo(3);
}
```
Atoum также поддерживает отчеты о покрытии кода для анализа качества тестирования.

Смотрите так же
---
* Для получения дополнительной информации об Atoum, обратитесь к <http://docs.atoum.org/en/latest/>
* Для источников и примеров, см. <https ://github.com/atoum/atoum>
* Рецепт Модульное тестирование с PHPUnit




Unit тестирование с Behat
===
Behat-это bdd-фреймворк для тестирования кода с помощью удобочитаемых предложений, которая описывает поведение кода в различных случаях использования.

Подготовка
---
Создание пустого каталога для нового проекта.

Как это сделать...
---
В этом рецепте мы создадим демонстрационное расширение корзины покупок с тестами Behat.

***Подготовка структуры расширения***

1 Сначала создайте структуру каталогов для расширения:
![](img/480_1.jpg)

2 Для работы с расширением в качестве пакета Composer подготовьте файл book/cart/composer.json следующим образом:
```php
{
    "name": "book/cart",
    "type": "yii2-extension",
    "require": {
        "yiisoft/yii2": "~2.0"
    },
    "require-dev": {
        "phpunit/phpunit": "4.*",
        "behat/behat": "A3.1"
    },
    "autoload": {
        "psr -4": {
            "book\\cart\\": "src/",
            "book\\cart\\features\\": "features/"
        }
    },
    "extra": {
        "asset-installer-paths": {
            "npm-asset-library": "vendor/npm",
            "bower-asset-library": "vendor/bower"
        }
    }
}
```

3 Добавьте следующие строки в файл book/cart/.gitignore:
```php
/vendor
/composer.lock
```

4 Установите все зависимости расширения:

***composer install***

5. Теперь мы получаем следующую структуру:
![](img/481_1.jpg)

***Написание кода расширения***

Скопируйте классы Cart, Storageinterface и Sessionstorage из рецепта  Модульное тестирования с помощью PHPUnit.
Наконец, мы получаем следующую структуру:

![](img/481_2.jpg)

***Написание тестов расширений***

1 Добавьте book/cart/features/bootstrap/bootstrap.php как начальный  скрипт:
```php
<?php
defined('YII_DEBUG') or define('YII_DEBUG', true);
defined('YII_ENV') or define('YII_ENV', 'test');
require_once __DIR__ . '/../../vendor/yiisoft/yii2/Yii.php';
```

2 Создайте features/cart.feature и сценарии тестирования корзины:
```php
Feature: Shopping cart
In order to buy products
As a customer
I need to be able to put interesting products into a cart
Scenario: Checking empty cart
Given there is a clean cart
Then I should have 0 products
Then I should have 0 product
And the overall cart amount should be 0
Scenario: Adding products to the cart
Given there is a clean cart
When I add 3 pieces of 5 product
Then I should have 3 pieces of 5 product
And I should have 1 product
And the overall cart amount should be 3
When I add 14 pieces of 7 product
Then I should have 3 pieces of 5 product
And I should have 14 pieces of 7 product
And I should have 2 products
And the overall cart amount should be 17
When I add 10 pieces of 5 product
Then I should have 13 pieces of 5 product
And I should have 14 pieces of 7 product
And I should have 2 products
And the overall cart amount should be 27
Scenario: Change product count in the cart
Given there is a cart with 5 pieces of 7 product
When I set 3 pieces for 7 product
Then I should have 3 pieces of 7 product
Scenario: Remove products from the cart
Given there is a cart with 5 pieces of 7 product
When I add 14 pieces of 7 product
And I clear cart
Then I should have empty cart
```

3 Добавьте функции тестирования компонента features/storage.feature:
```php
Feature: Shopping cart storage
I need to be able to put items into a storage
Scenario: Checking empty storage
Given there is a clean storage
Then I should have empty storage
Scenario: Save items into storage
Given there is a clean storage
When I save 3 pieces of 7 product to the storage
Then I should have 3 pieces of 7 product in the storage
```

4 Добавьте реализацию для всех шагов в файл features/bootstrap/CartContext.php:
```php
<?php
use Behat\Behat\Context\SnippetAcceptingContext;
use book\cart\Cart;
use book\cart\features\bootstrap\storage\FakeStorage;
use yii\di\Container;
use yii\web\Application;
require_once __DIR__ . '/bootstrap.php';
class CartContext implements SnippetAcceptingContext
{
    /**
    * @var Cart
    * */
    private $cart;
    /**
    * @Given there is a clean cart
    */
    public function thereIsACleanCart()
    {
        $this->resetCart();
    }
    /**
    * @Given there is a cart with :pieces of :product product
    */
    public function thereIsAWhichCostsPs($product, $amount)
    {
        $this->resetCart();
        $this->cart->set($product, floatval($amount));
    }
    /**
    * @When I add :pieces of :product
    */
    public function iAddTheToTheCart($product, $pieces)
    {
        $this->cart->add($product, $pieces);
    }
    /**
    * @When I set :pieces for :arg2 product
    */
    public function iSetPiecesForProduct($pieces, $product)
    {
        $this->cart->set($product, $pieces);
    }
    /**
    * @When I clear cart
    */
    public function iClearCart()
    {
        $this->cart->clear();
    }
    /**
    * @Then I should have empty cart
    */
    public function iShouldHaveEmptyCart()
    {
        PHPUnit_Framework_Assert::assertEquals(
            0,
            $this->cart->getCount()
        );
    }
    /**
    * @Then I should have :count product(s)
    */
    public function iShouldHaveProductInTheCart($count)
    {
        PHPUnit_Framework_Assert::assertEquals(
            intval($count),
            $this->cart->getCount()
        );
    }
    /**
    * @Then the overall cart amount should be :amount
    */
    public function theOverallCartPriceShouldBePs($amount)
    {
        PHPUnit_Framework_Assert::assertSame(
        intval($amount),
        $this->cart->getAmount()
        );
    }
    /**
    * @Then I should have :pieces of :product
    */
    public function iShouldHavePiecesOfProduct($pieces, $product)
    {
        PHPUnit_Framework_Assert::assertArraySubset(
            [intval($product) => intval($pieces)],
            $this->cart->getItems()
        );
    }
    private function resetCart()
    {
    $this->cart = new Cart(['storage' => new FakeStorage()]);
    }
}
```

5 Кроме того, в features/bootstrap/StorageContext.php файл, добавьте следующее:
```php
<?php
use Behat\Behat\Context\SnippetAcceptingContext;
use book\cart\Cart;
use book\cart\features\bootstrap\storage\FakeStorage;
use book\cart\storage\SessionStorage;
use yii\di\Container;
use yii\web\Application;
require_once __DIR__ . '/bootstrap.php';
class StorageContext implements SnippetAcceptingContext
{
    /**
    * @var SessionStorage
    * */
    private $storage;
    /**
    * @Given there is a clean storage
    */
    public function thereIsACleanStorage()
    {
        $this->mockApplication();
        $this->storage = new SessionStorage(['key' => 'test']);
    }
    /**
    * @When I save :pieces of :product to the storage
    */
    public function iSavePiecesOfProductToTheStorage($pieces, $product)
    {
        $this->storage->save([$product => $pieces]);
    }
    /**
    * @Then I should have empty storage
    */
    public function iShouldHaveEmptyStorage()
    {
        PHPUnit_Framework_Assert::assertCount(
        0,
        $this->storage->load()
    );
    }
    /**
    * @Then I should have :pieces of :product in the storage
    */
    public function iShouldHavePiecesOfProductInTheStorage($pieces, $product)
    {
        PHPUnit_Framework_Assert::assertArraySubset(
            [intval($product) => intval($pieces)],
            $this->storage->load()
        );
    }
    private function mockApplication()
    {
        Yii::$container = new Container();
        new Application([
            'id' => 'testapp',
            'basePath' => __DIR__,
            'vendorPath' => __DIR__ . '/../../vendor',
        ]);
    }
}
```
6 Добавить features/bootstrap/CartContext/FakeStorage.php файл с поддельным классом хранения:
```php
<?php
namespace book\cart\features\bootstrap\storage;
use book\cart\storage\StorageInterface;
class FakeStorage implements StorageInterface
{
    private $items = [];
    public function load()
    {
        return $this->items;
    }
    public function save(array $items)
    {
        $this->items = $items;
    }
}
```

7 Добавить в book/cart/behat.yml определения контекста:
```php
default:
    suites:
        default:
            contexts:
                - CartContext
                - StorageContext
```


8 Теперь мы получим следующую структуру:
![](img/485_1.jpg)

Теперь мы можем запустить наши тесты.

***Запуск тестов***

Во время установки всех зависимостей с помощью команды composer install менеджер пакетов Composer устанавливает пакет Behat в каталог vendor и помещает исполняемый файл behat в подкаталог vendor/bin.
Теперь мы можем запустить следующий скрипт:
```php
cd book/cart
vendor/bin/behat
```
Также, мы должны увидеть следующий отчет по испытаниям:
```php
Feature: Shopping cart
In order to buy products
As a customer
I need to be able to put interesting products into a cart
Scenario: Checking empty cart   #   features/cart.feature:6
Given there is a clean cart     #   thereIsACleanCart()
Then I should have 0 products   #   iShouldHaveProductInTheCart()
Then I should have 0 product    #   iShouldHaveProductInTheCart()
And the overall cart amount should be 0 # theOverallCartPriceShouldBePs()
Feature: Shopping cart storage
I need to be able to put items into a storage
Scenario: Checking empty storage    # features/storage.feature:4
Given there is a clean storage      # thereIsACleanStorage()
Then I should have empty storage    # iShouldHaveEmptyStorage()
6 scenarios (6 passed)
31 steps (31 passed)
0m0.23s (13.76Mb)
```
Попробуйте намеренно сломать корзину, комментируя операцию unset:
```php
class Cart extends Component
{
    public function set($id, $amount)
    {
        $this->loadItems();
        // $this->_items[$id] = $amount;
        $this->saveItems();
    }
}
```
Теперь запустите тесты снова:
```php
Feature: Shopping cart
In order to buy products
As a customer
Feature: Shopping cart
In order to buy products
As a customer
I need to be able to put interesting products into a cart
Scenario: Change product count in the cart     # features/cart.feature:31
Given there is  a cart with 5 pieces of 7 prod # thereIsAWhichCostsPs()
When I set 3 pieces for 7 product              # iSetPiecesForProduct()
Then I should have 3 pieces of 7 product       # iShouldHavePiecesOf()
Failed asserting that an array has the subset Array &0 ( 
7 => 3
).
Scenario: Remove products from the cart                # features/cart.feature:36
Given there is  a cart with 5  pieces  of  7   prod    # thereIsAWhichCostsPs()
When I add 14 pieces of 7 product                      # iAddTheToTheCart()
And I clear cart                                       # iClearCart()
Then I should have empty cart                          # iShouldHaveEmptyCart()
— Failed scenarios:
features/cart.feature:31
6 scenarios (5 passed, 1 failed)
31 steps (30 passed, 1 failed)
0m0.22s (13.85Mb)
```
В этом случае мы видели один сбой и отчет об ошибке.

Как это работает...
---
Behat-это Платформа тестирования BDD. Это облегчает написание предыдущих удобочитаемых сценариев тестирования для низкоуровневой технической реализации.
Когда мы пишем Сценарии для каждой функции, мы можем использовать набор операторов:
```php
Scenario: Adding products to the cart
Given there is a clean cart
When I add 3 pieces of 5 product
Then I should have 3 pieces of 5 product
And I should have 1 product
And the overall cart amount should be 3
```
Behat анализирует наши предложения и находит соответствующую реализацию предложения в классе context:
```php
class FeatureContext implements SnippetAcceptingContext
{
    /**
    * @When I add :pieces of :product
    */
    public function iAddTheToTheCart($product, $pieces)
    {
        $this->cart->add($product, $pieces);
    }
}
```
Можно создать один класс FeatureContex t (по умолчанию) или набор определенных контекстов для групп объектов и сценариев.

Смотрите так же
---
Для получения дополнительной информации о Behat обратитесь к следующим URL:
* <http://docs.behat.org/en/v3.0/>
* <https://github.com/Behat/Behat>
И чтобы получить больше информации об альтернативных тестовых фреймворках, смотрите другие рецепты в этой главе.





Ãëàâà 12. Îòëàäêà, âåäåíèå æóðíàëà è îáðàáîòêà îøèáîê
===
Â ýòîé ãëàâå ìû ðàññìîòðèì ñëåäóþùèå òåìû:
* Èñïîëüçîâàíèå ðàçëè÷íûõ ìàðøðóòîâ æóðíàëà
* Àíàëèç òðàññèðîâêè ñòåêà îøèáîê Yii
* Âåäåíèå æóðíàëà è èñïîëüçîâàíèå êîíòåêñòíîé èíôîðìàöèè
* Îòîáðàæåíèå ïîëüçîâàòåëüñêèõ îøèáîê
* Íàñòðàèâàåìàÿ ïàíåëü äëÿ ðàñøèðåíèÿ îòëàäêè

Ââåäåíèå
===
Íåâîçìîæíî ñîçäàòü ïðèëîæåíèå áåç îøèáîê, åñëè îíî îòíîñèòåëüíî ñëîæíîå, ïîýòîìó ðàçðàáîò÷èêàì ïðèõîäèòñÿ îáíàðóæèâàòü îøèáêè è ðàáîòàòü ñ íèìè êàê ìîæíî áûñòðåå. Yii èìååò õîðîøèé íàáîð ôóíêöèé óòèëèòû äëÿ îáðàáîòêè ðåãèñòðàöèè è îáðàáîòêè îøèáîê. Êðîìå òîãî, â ðåæèìå îòëàäêè Yii äàåò âàì òðàññèðîâêó ñòåêà, åñëè åñòü îøèáêà. Èñïîëüçóÿ åãî, âû ìîæåòå èñïðàâèòü îøèáêè áûñòðåå.
Â ýòîé ãëàâå ìû ðàññìîòðèì âåäåíèå æóðíàëà, àíàëèç òðàññèðîâêè ñòåêà èñêëþ÷åíèé è ðåàëèçàöèþ ñîáñòâåííîãî îáðàáîò÷èêà îøèáîê.



Использование различных журналов и маршрутов
===
Ведение журнала-это ключ к пониманию того, что на самом деле делает приложение, когда у вас нет возможности отладить его. Верьте или нет, даже если вы на 100% уверены, что приложение будет вести себя так, как ожидается, в производство, он может сделать много вещей, которые Вы не знали. Это нормально, так как никто не может знать обо всем. Поэтому, если мы ожидаем необычного поведения, мы должны знать об этом как можно скорее и иметь достаточно деталей, чтобы воспроизвести его. Это где логирование пригодится.
Yii позволяет разработчику не только регистрировать сообщения, но и обрабатывать их по-разному в зависимости от уровня и категории сообщения. Вы можете, например, написать сообщение в базу данных, отправить электронное письмо или просто показать его в браузере.
В этом рецепте мы будем обрабатывать сообщения журнала мудро: самое важное сообщение будет отправлено по электронной почте, менее важные сообщения будут сохранены в файлах A и B, а профилирование будет направлено в Firebug. Кроме того, в режиме разработки на экране будут отображаться все сообщения и сведения о профилировании.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
Выполните следующие действия:

1 Настройте ведение журнала с помощью config/web.php:
```php
'components' => [
    'log' => [
        'traceLevel' => 0,
        'targets' => [
            [
                'class' => 'yii\log\EmailTarget',
                'categories' => ['example'],
                'levels' => ['error'],
                'message' => [
                    'from' => ['log@example.com'],
                    'to' => ['developer1@example.com', 'developer2@example.com'],
                    'subject' => 'Log message',
                ],
            ],
            [
                'class' => 'yii\log\FileTarget',
                'levels' => ['error'],
                'logFile' => '@runtime/logs/error.log',
            ],
            [
                'class' => 'yii\log\FileTarget',
                'levels' => ['warning'],
                'logFile' => '@runtime/logs/warning.log',
            ],
            [
                'class' => 'yii\log\FileTarget',
                'levels' => ['info'],
                'logFile' => '@runtime/logs/info.log',
            ],
        ],
    ],
    'db' => require(	DIR	 . '/db.php'),
],
```

2 Теперь, мы выигрываем производя немного сообщений журнала в protected/controllers/LogController.php следующим образом:
```php
<?php
namespace app\controllers;
use yii\web\Controller;
use Yii;
class LogController extends Controller
{
    public function actionIndex()
    {
        Yii::trace('example trace message', 'example');
        Yii::info('info', 'example');
        Yii::error('error', 'example');
        Yii::trace('trace', 'example');
        Yii::warning('warning','example');
        Yii::beginProfile('preg_replace',	'example');
        for($i=0;$i<10000;$i++){
            preg_replace('~A[ a-z]+~',	'', 'test it');
        }
        Yii:: endProfile('preg_replace',	'example');
        return $this->render('index');
    }
}
```
и просматривать views/log/index.php:
```php
<div class="log-index">
    <h1>Log</h1>
</div>
```

3 Теперь выполните предыдущее действие несколько раз. На экране должен появиться заголовок журнала и панель отладки с номером сообщения журнала:
![](img/492_1.jpg)

4  Если Вы кликните  на 17, Вы увидите веб-журнал, подобный показанному на следующем снимке экрана:

![](img/492_2.jpg)

5 Журнал содержит все сообщения, которые мы зарегистрировали вместе со следами стека, метками времени, уровнями и категориями

6 Теперь откройте страницу профиля. Вы должны увидеть сообщения профилировщика, как показано на следующем снимке экрана:
![](img/493_1.jpg)

Информация профилирования отображает общую Продолжительность выполнения собственного блока кода.

7 Поскольку мы только что изменили имена файлов журнала, а не пути, вы должны искать в runtime/logs, чтобы найти файлы журнала с именем named error.log, warning.log, и info.log

8 Внутри вы найдете следующие сообщения:
```php
2016-03-06 07:28:35 [127.0.0.1][-][-][error][example] error
2016-03-06 07:28:35 [127.0.0.1][-][-][warning][example] warning
2016-03-06 07:28:35 [127.0.0.1][-][-][info][example] info
```

Как это работает...
---
Когда один записывает сообщение черезYii::error, Yii::warning, Yii::info, or Yii::trace, Yii передает его на роутер.
В зависимости от того, как он настроен, он передает сообщения одному или нескольким целевым объектам, например, ошибки электронной почты, запись отладочной информации в файл A и запись предупреждающей информации в файл B.
Объект класса yii\log\Dispatcher обычно присоединяется к компоненту приложения с именем log. Поэтому, чтобы настроить его, мы должны установить его свойства в разделе компонентов файла конфигурации. Единственным настраиваемым свойством являются целевые объекты, содержащие массив маршрутов журналов и их конфигурации.
Мы определили четыре маршрута журнала. Рассмотрим их следующим образом:
```php
[
    'class' => 'yii\log\EmailTarget',
    'categories' => ['example'],
    'levels' => ['error'],
    // 'mailer' => 'mailer',
    'message' => [
        'from' => ['log@example.com'],
        'to' => ['developer1@example.com', 'developer2@example.com'],
        'subject' => 'Log error,
    ],
],
```
EmailTarget отправляет сообщения журнала по электронной почте через компонент yii:: $app->mailer по умолчанию. Мы ограничиваем категорию примером и уровень ошибкой. Электронное письмо будет отправлено из log@example.com для двух разработчиков и тема будет ошибка журнала:
```php
[
    'class' => 'yii\log\FileTarget',
    'levels' => [warning],
    'logFile' => '@runtime/logs/warning.log',
],
```
FileTarget добавляет сообщения об ошибках в указанный файл. Мы ограничиваем уровень сообщения предупреждением и используем файл с именем warning.log. Мы делаем то же самое для сообщений информационного уровня с помощью файла с именем Info.log.
Кроме того, мы можем использовать yii\log\SyslogTargett писать сообщения в Unix в файле /var/log/syslog и yii\log\DbTarget писать логи в базу данных. Для второго необходимо применить их миграции:

***./yii migrate --migrationPath=@yii/log/migrations/***

Есть еще...
---
Есть более интересные вещи о yii logging, которые рассматриваются в следующих подразделах.

***Yii::trace проитив Yii::getLogger()->log***

Yii::trace является простой оберткой Yii::log:
```php
public static function trace($message, $category = 'application')
{
    if (YII_DEBUG) {
        static::getLogger()->log($message, Logger::LEVEL_TRACE, $category);
    }
}
```
Таким образом yii:: trace регистрирует сообщение с уровнем трассировки, если Yii находится в режиме отладки.

***Yii::beginProfile и Yii::endProfile***

Эти методы используются для измерения времени выполнения некоторой части кода приложения. В нашем LogController мы измерили 10 000 выполнений preg_replace следующим образом:
```php
Yii::beginProfile('preg_replace',' example');
for($i=0;$i<10000;$i++){
    preg_replace('~A[ a-z]+~','', 'test it');
}
Yii::endProfile('preg_replace',' example');
```
Yii::beginProfile обозначает начало блока кода для профилирования. Мы должны установить уникальный маркер для каждого блока кода и дополнительно указать категорию:
```php
public static function beginProfile($token, $category = 'application') { ... }
```
Yii: :endProfile должен быть сопоставлен с предыдущим вызовом beginProfile с тем же именем категории: 
public static function endProfile($token, $category = 'application') { ... }
Вызовы begin и end также должны быть правильно вложенными.

***Немедленно регистрировать сообщения***

По умолчанию Yii сохраняет все сообщения журнала в памяти до завершения работы приложения. Это сделано по соображениям производительности и обычно работает нормально.
Однако при наличии консольного приложения с длительным временем работы сообщения журнала будут записываться не сразу. Чтобы убедиться, что Ваши сообщения будут зарегистрированы в любой момент, вы можете очистить их явно с помощью Yii:: $app - >getLogger () >flush (true) или изменить flushInterval и exportInterval для конфигурации консольного приложения:
```php
'components' => [
    'log' => ['flushInterval' => 1,
                'targets' => [
                    ['class' => 'yii\log\FileTarget','exportInterval' => 1,]
                ,]
    ,]
,]
],
```

Смотрите так же
---
* Чтобы узнать больше о регистрации, обратитесь к
<https://www.yiiframework.com/doc/guide/2.0/en/runtime-logging> 
 по русски https://www.yiiframework.com/doc/guide/2.0/ru/runtime-logging
* Рецепт Журналирование и использование контекстной информации




Анализ трассировки стека ошибок Yii
===
При возникновении ошибки yii может отображать трассировку стека ошибок вместе с ошибкой. Трассировка стека особенно полезна, когда нам нужно знать, что действительно вызвало ошибку, а не только тот факт, что произошла ошибка.

Подготовка 
---

1 Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Настройте базу данных и импортируйте следующую миграцию:

```php
<?php
use yii\db\Migration;
class m160308_093234_create_article_table extends Migration
{
    public function up()
    {
        $this->createTable('{{%article}}',	[
            'id' => $this->primaryKey(),
            'alias' => $this->string()->notNull(),
            'title' => $this->string()->notNull(),
            'text' => $this->text()->notNull(),
        ]);
    }
    public function down()
    {
        $this->dropTable('{{%article}}');
    }
}
```

3 Создать модель Article на yii.

Как это сделать...
---
Выполните следующие действия:

1 Теперь нам нужно будет создать код для работы. Создайте protected/controllers/ErrorController.php следующим образом:
```php
<?php
namespace app\controllers;
use app\models\Article;
use yii\web\Controller;
class ErrorController extends Controller
{
    public function actionIndex()
    {
        $article = $this->findModel('php');
        return $article->title;
    }
    private function findModel($alias)
    {
        return Article::findOne(['allas' => $alias]);
    }
}
```

2 После выполнения предыдущего действия, мы должны получить следующую ошибку:
![](img/497_1.jpg)

3 Кроме того, трассировка стека показывает следующую ошибку:
![](img/498_1.jpg)

Как это работает...
---
Из сообщения об ошибке, мы знаем, что у нас нет псевдонима столбца в базе данных, но мы использовали его где-то в коде. В нашем случае очень просто найти его, просто выполнив поиск во всех файлах проекта, но в большом проекте столбец может храниться в переменной. Кроме того, у нас есть все, чтобы исправить ошибку, не выходя из экрана, где отображается трассировка стека. Нам просто нужно внимательно прочитать его.
Трассировка стека отображает цепочку вызовов в обратном порядке, начиная с того, который вызвал ошибку. Как правило, нам не нужно читать весь след, чтобы получить то, что происходит. Сам фреймворк хорошо тестируется, поэтому вероятность ошибки меньше. Именно поэтому Yii отображает развернутые записи трассировки приложения и свернутые записи трассировки платформы.
Поэтому берем первый развернутый раздел и ищем псевдоним. Найдя его, можно сразу сказать, что он используется в ErrorController.php в строке 19.

Смотрите так же
---
* Чтобы узнать больше об обработке ошибок, обратитесь к
 <https://www.yiiframework.com/doc/guide/2.0/en/runtime-handling-errors>
 по русски <https://www.yiiframework.com/doc/guide/2.0/ru/runtime-handling-errors>
* Рецепт Журналирование и использование контекстной информации





Ведение журнала и использование информации контекста
===
Иногда сообщения журнала недостаточно для исправления ошибки. Например, если вы следуете рекомендациям и разрабатываете и тестируете приложение со всеми возможными ошибками, вы можете получить сообщение об ошибке. Однако без контекста выполнения это только говорит вам, что была ошибка, и не ясно, что на самом деле вызвало ее.
ДЛЯ НАШЕГО ПРИМЕРА МЫ БУДЕМ ИСПОЛЬЗОВАТЬ ОЧЕНЬ ПРОСТОЕ И ПЛОХО ЗАКОДИРОВАННОЕ ДЕЙСТВИЕ, КОТОРОЕ ПРОСТО ПЕРЕКЛИКАЕТСЯ С HELLO, <USERNAME>! ЕСЛИ ИМЯ ПОЛЬЗОВАТЕЛЯ БЕРЕТСЯ НЕПОСРЕДСТВЕННО ИЗ $_GET.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html.. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

Как это сделать...
---
Выполните следующие действия:

1 Во-первых, нам понадобится контроллер для работы. Таким образом, создайте protected/controllers/LogController.php следующим образом:
```php
<?php
namespace app\controllers;
use yii\web\Controller;
class LogController extends Controller
{
    public function actionIndex()
    {
        return 'Hello, '. $_GET['username'];
    }
}
```

2 Теперь, если мы запустим действие index, мы получим сообщение об ошибке, Undefined index: username. Давайте сконфигурируем регистратор для записи такого рода ошибок в файл:
```php
config/web.php:
'components'=>array(
    'log' => [
        'targets' => [
            [
                'class' => 'yii\log\FileTarget',
                'levels' => ['error'],
                'logFile' => '@runtime/logs/errors.log',
            ],
        ],
    ],
],
```

3 Снова запустите действие index и проверьте runtime/logs/errors.log. В журнале должна быть следующая информация:
```php
2016-03-06 09:27:09 [127.0.0.1][-][-][error][yii\base\ErrorException:8] exception
'yii\base\ErrorException' with message 'Undefined index: username' in
/controllers/LogController.php:11
Stack trace:
#0 /yii2/base/InlineAction.php(55): ::call_user_func_array()
#1 /yii2/base/Controller.php(151): yii\base\InlineAction->runWithParams()
#2 /yii2/base/Module.php(455): yii\base\Controller->runAction()
#3 /yii2/web/Application.php(84): yii\base\Module->runAction()
#4 /yii2/base/Application.php(375): yii\web\Application->handleRequest()
#5 /web/index.php(12): yii\base\Application->run()
#6 {main}
2016-03-06 09:27:09 [127.0.0.1][-][-][info][application] $_GET = [
'r' => 'log/index'
]
$_COOKIE = [
'_csrf' => 'ca689043348e...a69ea:2:{i:0;s:...\"DSS...KJ\";}'
' PHPSESSID' => '30584oqhat4ek8b0hrqsapsbf4'
]
$_SERVER = [
'USER' => 'www-data'
'HOME' => '/var/www'
'FCGI_ROLE' => 'RESPONDER'
'QUERY_STRING' => 'r=log/index'
'PHP_SELF' => '/index.php'
'REQUEST_TIME_FLOAT' => 1459934829.3067
'REQUEST_TIME' => 1459934829
]
```

4 Теперь мы можем передать наше приложение команде тестирования и время от времени проверять журнал ошибок. По умолчанию, отчет об ошибках журнала содержат значения из всего массива $_get, $_post, где, переменную $_files, $их помощью $_SESSION и $_server для переменных. Если не требуется отображать все значения, можно указать список настраиваемых переменных:
```php
'log' => [
    'targets' => [
        [
            'class' => 'yii\log\FileTarget',
            'levels' => ['error'],
            'logVars' => ['_GET',	'_POST'],
            'logFile' => '@runtime/logs/errors.log',
        ],
    ],
],
```

5 В этом случае отчет будет содержать только массивы $_GET и $_POST:
```php
2016-04-06 09:49:08 [127.0.0.1][-][-][info][application] $_GET = [ 'r' =>
'log/index'
]
```


Как это работает...
---
Yii добавляет полную информацию о контексте выполнения и среде в случае регистрации сообщений об ошибках. Если мы регистрируем сообщение вручную, то мы, вероятно, знаем, какая информация нам нужна, поэтому мы можем установить некоторые целевые параметры, чтобы писать только то, что нам действительно нужно:
```php
'log' => [
    'targets' => [
        [
            'class' => 'yii\log\FileTarget',
            'levels' => ['error'],
            'logVars' => ['_GET',	'_POST'],
            'logFile' => '@runtime/logs/errors.log',
        ],
    ],
],
```
В предыдущем коде ошибки записываются в файл с именем errors. В дополнение к самому сообщению, оно будет регистрировать содержимое переменных $_GET или $_POST, если они не пусты.

Смотрите так же
---
* Чтобы узнать больше о фильтрах журнала и информации о контексте, обратитесь к
<https://www.yiiframework.com/doc/guide/2.0/en/runtime-logging>
По русски <https://www.yiiframework.com/doc/guide/2.0/ru/runtime-logging> 
* Рецепт использования различных маршрутов журнала




Отображение пользовательских ошибок
===
В Yii обработка ошибок очень гибкая, поэтому вы можете создать свой собственный обработчик ошибок для ошибок определенного типа. В этом рецепте, мы будем обрабатывать 404 ошибку «не нашли» . Мы покажем пользовательскую страницу 404, которая будет предлагать контент на основе того, что было введено в адресной строке.

Подготовка 
---

1 Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation>

2 Добавьте действие fail в siteController:

```php
class SiteController extends Controller
{
    // ...
    public function actionFail()
    {
        throw new ServerErrorHttpException('Error message example.');
    }
}
```

3 Добавьте файл web/.htaccess со следующим содержимым:
```php
RewriteEngine on
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule . index.php
```

4 Настройте красивые URL для компонента urlManager в config/web.php файл:
```php
'components' => [
    // .
    'urlManager' => [
        'enablePrettyUrl' => true,
        'showScriptName' => false,
    ],
],
```

5 Убедитесь, что фреймворк отображает "Не найдено" исключение для URL-адресов, которые не существуют:
![](img/504_1.jpg)

6 Кроме того, убедитесь, что фреймворк отображает исключение внутренней ошибки сервера для нашего actionFail:
![](img/504_2.jpg)

7 Теперь мы хотим создать пользовательскую страницу для не найденной страницы. Давайте начнем с этого.

Как это сделать...
---
Теперь нам нужно изменить не найденное содержимое страницы, но оставить его как есть для других типов ошибок. Для этого выполните следующие действия:

1 Откройте класс siteController и найдите метод actions():
```php
class SiteController extends Controller
{
    // ...
    public function actions()
    {
        return [
            'error' => [
                'class' => 'yii\web\ErrorAction',
            ],
            'captcha' => [
                'class' => 'yii\captcha\CaptchaAction',
                'fixedVerifyCode' => YII_ENV_TEST ? 'testme' : null,
            ],
        ];
    }
    // ...
}
```

2 Удалите раздел ошибок по умолчанию и оставьте actions() следующим образом:
```php
class SiteController extends Controller
{
    // ...
    public function actions()
    {
        return [
            'captcha' => [
                'class' => 'yii\captcha\CaptchaAction',
                'fixedVerifyCode' => YII_ENV_TEST ? 'testme' : null,
            ],
        ];
    }
    // ...
}
```

3 Добавьте собственный метод actionError():
```php
class SiteController extends Controller
{
    // ...
    public function actionError()
    {
    }
}
```

4 Откройте исходный класс \yii\web\ErrorAction и скопируйте его содержимое действия в наш actionError () и настройте его для представления render custom error-404 для не найденной ошибки с кодом 404:
```php
// ...
use yii\base\Exception;
use yii\base\UserException;
class SiteController extends Controller
{
    // ...
    public function actionError()
    {
        if (($exception = Yii::$app->getErrorHandler()->exception)== null) {
            $exception = new HttpException(404, Yii::t('yii', 'Page not found.'));
        }
        if ($exception instanceof HttpException) {
            $code = $exception->statusCode;
        } else {
            $code = $exception->getCode();
        }
        if ($exception instanceof Exception) {
            $name = $exception->getName();
        } else {
            $name = Yii::t('yii', 'Error');
        }
        if ($code) {
            $name .= " (#$code)";
        }
        if ($exception instanceof UserException) {
            $message = $exception->getMessage();
        } else {
            $message = Yii::t('yii', 'An internal server error occurred.');
        }
        if (Yii::$app->getRequest()->getIsAjax()) {
            return "$name: $message";
        } else {
            if ($code == 404) {
                return $this->render('error-404');
            } else {
                return $this->render('error', [
                    'name' => $name,
                    'message' => $message,
                    'exception' => $exception,
                ]);
            }
        }
    }
}
```

5 Добавьте views/site/error-404.php просмотр файла с пользовательским сообщением:
```php
<?php
use yii\helpers\Html;
/* @var $this yii\web\View */
$this->title = 'Not Found!'
?>
<div class="site-error-404">
    <h1>Oops!</h1>
    <p>Sorry, but requested page not found.</p>
    <p>
        Please follow to <?= Html::a('index page', ['site/index'])?>
        to continue reading. Thank you.
    </p>
</div>
```

6 Вот и все. Теперь попробуйте перейти по несуществующему URL и посмотреть наш контент из error-404.php : ![](img/507_1.jpg)

7 Однако, на неудачу, мы должны увидеть содержимое по умолчанию от error.php:

![](img/507_2.jpg)

Как это работает...
---
По умолчанию в приложении yii2-app-basic мы настраиваем errorAction для компонента errorHandler в конфигурационном файле  config/web .php как site/error Это означает, что фреймворк будет использовать этот маршрут для отображения каждого обработанного исключения:
```php
'components' => [
    'errorHandler' => [
        'errorAction' => 'site/error',
    ],
],
```
В классе SiteController мы используем встроенный автономный класс yii\web\ErrorAction, который отображает  error.php:
```php
class SiteController extends Controller
{
    // ...
    public function actions()
    {
        return [
            'error' => [
                'class' => 'yii\web\ErrorAction',
            ],
            'captcha' => [
                'class' => 'yii\captcha\CaptchaAction',
                'fixedVerifyCode' => YII_ENV_TEST ? 'testme' : null,
            ],
        ];
    }
    // ...
}
```
Если мы хотим переопределить его реализацию, мы можем заменить его во встроенном методе actionError() нашим собственным пользовательским содержимым.
В этом рецепте мы добавляем собственный оператор if для отображения определенного представления на основе кода ошибки:
```php
if ($code == 404) {
    return $this->render('error-404');
} else {
    return $this->render('error', [
        'name' => $name,
        'message' => $message,
        'exception' => $exception,
    ]);
}
```
Также, мы можем использовать нестандартную конструкцию для не найденной страницы.

Смотрите так же
---
Чтобы узнать больше об обработке ошибок в Yii, обратитесь к
<https://www.yiiframework.com/doc/guide/2.0/en/runtime-handling-errors>
По русски <https://www.yiiframework.com/doc/guide/2.0/ru/runtime-handling-errors>.




Настраиваемая панель для расширеной отладки
==
Расширение yii2-debug-это мощный инструмент для отладки собственного кода, анализа информации о запросах или запросов к базе данных и так далее. Таким образом, можно добавить собственную панель для любого пользовательского отчета.

Подготовка 
---
Создайте новое yii2-app-basic приложение с помощью диспетчера пакетов Composer, как описано в официальном руководстве по адресу <http://www.yiiframework.com/doc-2.0/guide-start-installation.html>. 
По русски <http://yiiframework.domain-na.me/doc/guide/2.0/ru/start-installation.

Как это сделать...

1 Создайте каталог панелей на корневом пути вашего сайта.

2 Добавление нового класса userPanel:

```php
<?php
namespace app\panels;
use yii\debug\Panel;
use Yii;
class UserPanel extends Panel
{
    public function getName()
    {
        return ' User ' ;
    }
    public function getSummary()
    {
        return Yii::$app->view->render('@app/panels/views/summary', ['panel' =>$this]);
    }
    public function getDetail()
    {
        return Yii::$app->view->render('@app/panels/views/detail', ['panel' =>$this]);
    }
    public function save()
    {
        $user = Yii::$app->user;
        return !$user->isGuest ? [
            'id' => $user->id,
            'username' => $user->identity->username,
        ] : null;
    }
}
```

3 Создайте panels/view/summary.php со следующим кодом:
```php
<?php
/* @var $panel app\panels\UserPanel */
use yii\helpers\Html;
?>
<div class="yii-debug-toolbar	block">
    <?php if (!empty($panel->data)): ?>
        <a href="<?= $panel->getUrl() ?>">
            User
            <span class="yii-debug-toolbarlabel yii-debug- toolbarlabel_info">
                <?= Html::encode($panel->data['username']) ?>
            </span>
        </a>
    <?php else: ?>
        <a href="<?= $panel->getUrl() ?>">Guest session</a>
    <?php endif; ?>
</div>
```

4 Добавьте panels/view/detail.php со следующим кодом:
```php
<?php
/* @var $panel app\panels\UserPanel */
use yii\widgets\DetailView;
?>
<h1>User profile</h1>
<?php if (!empty($panel->data)): ?>
    <?= DetailView::widget([
        'model' => $panel->data,
        'attributes' => [
            'id',
            'username',
        ]
    ]) ?>
<?php else: ?>
    <p>Guest session.</p>
<?php endif;?>
```

5 Включите панель инструментов в файл config/web.php:
```php
if (YII_ENV_DEV) {
    $config['bootstrap'][] = 'debug';
    $config['modules']['debug'] = [
        'class' => 'yii\debug\Module',
        'panels' => [
            'views' => ['class' => 'app\panels\UserPanel'],
        ],
    ];
    $config['bootstrap'][] = 'gii';
    $config['modules']['gii'] = 'yii\gii\Module';
}
```

6 Перезагрузите страницу index и найдите ячейку Guest Session в конце панели отладки:

![](img/510_1.jpg)

7 Войдите на свой сайт с именем администратора и паролем администратора. В случае успеха вы должны увидеть свое имя пользователя в главном меню:

![](img/510_2.jpg)

8 Снова наблюдайте за панелью отладки. Прямо сейчас, вы увидите имя пользователя admin : 

![](img/511_1.jpg)

9 Вы можете нажать на имя пользователя на панели отладки и увидеть подробную информацию о пользователе:

![](img/511_2.jpg)

Как это работает...
---
Чтобы создать собственную панель для модуля yii2-debug, необходимо расширить класс yii\debug\Panel и переопределить его шаблонные методы:

* getName ():Метка для пункта меню на странице сведений об отладке
* getsummary():Код ячейки панели отладки
* getDetail():Код представления страницы сведений
* save ():Ваша информация, которая будет сохранена в отладочном хранилище и загружена обратно в поле $panel ->data

Объект может хранить любые отладочные данные и отображать их в блоке сводка панели и на странице сведений.В нашем примере мы храним информацию о пользователях:
```php
public function save()
{
    $user = Yii::$app->user;
    return !$user->isGuest ? [
        'id' => $user->id,
        'username' => $user->identity->username,
    ] : null;
}
```
Отобразите его на страницах сводки и сведений из поля $panel - >data.

***Обработка событий***

Вы можете подписаться на любые события приложения или любого компонента в методе init (). Например, встроенная панель yii\debug\panels\MailPanel собирает и хранит все отправленные сообщения:
```php
class MailPanel extends Panel
{
    private $_messages = [];
    public function init()
    {
        parent::init();
        Event::on(
            BaseMailer::className(),
            BaseMailer::EVENT_AFTER_SEND,
            function ($event) {
                $message = $event->message;
                $messageData = [
                    // ...
                ];
            $this->_messages[] = $messageData;
            }
        );
    }
    // ...
    public function save()
    {
        return $this->_messages;
    }
}
```
Кроме того, он отображает сетку со списком сохраненных сообщений на нашей собственной странице деталей.

Смотрите так же
---
* Чтобы узнать больше о расширении yii2-debug, обратитесь к
 <https://www.yiiframework.com/doc-2.0/ext-debug-index.html> 
* Дополнительные сведения о создании панели счетчиков представлений см. в разделе
* <https://github.com/yiisoft/yii2-debug/blob/master/docs/guide/topics-creating-your-own-panels.md>



