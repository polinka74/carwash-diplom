# carwash-diplom
Дипломный проект - мойка самообслуживания "Мой САМ"

---------------------------------------------------------------------------------------
Для входа на сайт необходимо перейти по ссылке http://polinawz.beget.tech/. 

После чего откроется главная страница и можно будет авторизоваться как Администратор с помощью логина и пароля:
-	логин: polina-polina-1991@list.tu;
-	пароль: bqW6sMqnXR5GMT6.

---------------------------------------------------------------------------------------------------------------------------
Все файлы с кодом находятся в папке resources/view/
- Админ-панель admin/
- Страница контакты - contact.blade.php
- Страница главная - home.blade.php
- Страница с header+footer+подключение стилей и js -layout.blade.php
- Страница вход - login.blade.php
- Страница регистрации - register.blade.php
- Страница продукты - отдельная страница - PageProduct.blade.php
- Страница отзывы - reviews.blade.php
- Страница мойсам - wash.blade.php
- СТраница прайса и товаров - price.blade.php
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Контроллеры находятся в app\Http\Controllers
Модели в app\Models
---------------------------------------------------------------------------------------
!!!!
в файле env указан логин, пароль и название базы данных, хост:

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=carwash
DB_USERNAME=root
DB_PASSWORD=root

----------------------------------------------------------------
в файле route находится ваил web с путями для перехода на страницы
---------------------------------------------------------------------------------------
