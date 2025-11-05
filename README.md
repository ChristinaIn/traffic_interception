# Перехват и изменение трафика

Для работы с сетевым трафиком интернет-магазина https://intern.demoshopping.ru/ на Windows я использовала приложение Charles Proxy:

<a href="https://drive.google.com/file/d/1MPprBrVc70ve_8qm24m7dREc1FW9piFM/view?usp=sharing">Запись экрана</a>, на которой можно увидеть

<ul>
<li>изменение количества товаров в корзине</li>
<li>сервер возвращает статус-код 403 при обращении к тестируемому сайту</li>
<li>перенаправление запроса с Prod окружения на Stage</li>
</ul>

Перехват трафика интернет-магазина https://intern.demoshopping.ru/, используя сниффер Proxyman, на IOS:

<ul>
<li>  <a href="https://drive.google.com/file/d/1rDLNFD7Z5HUgBUPn01GrmySpJDlaD8DZ/view?usp=sharing">Удаление невыбранного товара из корзины</a>Имеется ввиду, выбирая один товар для удаления, удаляется другой</li>
<li>  <a href="https://drive.google.com/file/d/11XDMttc0E06yuEFsuWL5CMOo6obXQ394/view?usp=drive_link">Пользователь видит картинку в браузере при обращении к тестируемому сайту</a></li>
</ul>

