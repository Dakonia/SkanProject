***Добро пожаловать в проект "Силант"***

<h1>Для начало активуриуйте вирутульное окружение</h1>


Установите все зависимости командой
 >pip install -r requirements.txt

После запустите сервер
>python manage.py runserver

<h3>Проект готов к открытию</h3>

<h4>В проекте для не зарегстированого доступен ограниченый</br>
функционал только просмотр машин и поиск по номеру машины</h4>

<h4>Документация по API есть по ссылке:

>http://localhost:8000/api/docs/</br>
>http://localhost:8000/api/redoc/

<h2>В проекте реализованы группы пользователей:</h2>
<h3>
Клиент</br>
<h4>1. Возможность просмотра всех своих машин (машины других пользоватлей не буду видны),</br>
2. Что бы посмотреть детальную информацию машины преходим по ее номеру.</br>
3. (Реализовывать длинную таблицу не стал)</br>
4. Так же Клиент может добавлять ТО для своей машины и редактировать их</br> 
<h3>Сервис</br>
<h4>1. Возможность просмотра всех своих машин (другиемашины не буду видны),</br>
2. Что бы посмотреть детальную информацию машины преходим по ее номеру.</br>
3. Сервис может добавлять ТО и так же добавлять Рекламации и редактировать их </br>
<h3>
Менеджер</br>
<h4>1. Возможность просмотра всех машин </br>
2. Возмжность добавлять машины, ТО, рекламации, справочники и их редактировать</br>
3. У менеджера есть доступ ко всему, кроме регистарции новых пользователей и их редактирванию</br>
<h3>
Администратор</br>
<h4> 1. У администартора все те же права что и у менеджера, но есть возможность создать новых пользователей</br>
2. Привязывать их к соответствуюшим группам</br>

<h3>У всех пользоватлей есть так же доступ в Admin панель, с ограничеными правами, которые им достпуны 


<h4>Админстартор:</h4>

>login: Admin </br>pass: admin


<h4>Менеджер:</h4>

>login: Manager </br>pass: admin12345


<h4>Сервис:</h4>

>ООО "Промышленая техника" </br> login: service1 </br> pass: admin12345



>ООО "Силант" </br> login: service2 </br> pass: admin12345


>ООО "ФНС"  </br> login: service3 </br> pass: admin12345

<h4>Клиент</h4>

>ИП Трудников С.В. </br> login: client1</br> pass: admin12345


>ООО "ФПК21" </br> login: client2 </br> pass: admin12345


>ООО "МНС77" </br> login: client3 </br> pass: admin12345


>ООО "Ранский ЛПХ" </br> login: client4 </br> pass: admin12345


>ООО "Комплект-Поставка" </br> login: client5 </br> pass: admin12345


>ООО "РМК" <br> login: client6 </br> pass: admin12345


>АО "Зандер" </br> login: client7 </br> pass: admin12345


<h3>Надеюсь что проект получился и все ТЗ выполнено в полном объеме</br></br>
Было проверено несколько раз!!!)))