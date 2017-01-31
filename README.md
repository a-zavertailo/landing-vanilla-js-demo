## Demo landing page application with vanilla js logic


##Задача 
* Создание сайта-портфолио веб-студии по предоставленному psd макету. 

##Общие требования к сайту 
* Корректное отображение сайта на следующих разрешениях экрана: 320px, 687px, 992px, 1200 px 
* Поддержка браузеров: последние версии Chrome, Firefox, Safarі, Opera, MS Edge.

##Структура сайта: 
###Header 
![](./task/images/template_01.png)

* При нажатии на каждый элемент меню, страница плавно прокручивается до соответствующего блока на странице.
* Меню дожно быть зафиксировано в верхней части экрана, чтобы пользователь мог им всегда воспользоватся.
 
###Слайдер изображений 
![](./task/images/template_02.png)
   
* Создайте три слайда с произвольным изображением и текстом.
* Смена слайдов должна присходить с интервалом в 3с. 
* По нажатию стелок навигации, автоматическая смена слайдов должна приостанавливатся, 
  пока пользователь листает слайды в ручную. Если в течении 5с пользователь не нажимал на элементы навигации, 
  должна возобновиться автоматическая смена слайдов.
* Кнопка "BUY THIS THEME" не содержит обработчиков событий и является лишь элементом разметки.

###Блок с описанием сервисов 
![](./task/images/template_03.png)
![](./task/images/template_04.png)

* При наведении курсора мыши на иконки сервисов, они плавно увеличиваются в размере на 10% и уменьшаются обратно, 
  когда курсор уходит с элемента (для решения данной задачи используйте JavaScript).

###Блок портфолио
![](./task/images/template_05.png)
![](./task/images/template_06.png)

* Добавьте произвольные изображения в портфолио.
* При наведении курсора мыши на изображение над ним появляется желтый полупрозрачный слой с информацией о том к какой категории относится данное изображение. 
  Всего дожно быть пять категорий: all, web design, graphic design, phtography, illustration. 
* Создайте фильтр для каждой категории с возможностью выбирать нужные изображения. 
  
###Блок с кнопкой contact us
![](./task/images/template_07.png) 

* Блок с кнопкой contact us, при нажатии на которую страница прокручивается до блока контактов. 
 
###Блок со статистикой достижений.  
![](./task/images/template_08.png)

* Когда блок только появился в видимой области страницы, течении 3 секунд происходит отсчет от 0 до значений, указанных в макете.
  Например: 1600 Happy Clients  

###Блок about us 
![](./task/images/template_09.png) 

* Краткое описание команды сайта. 
* При наведении курсора мыши на иконки описания работы команды, они плавно увеличиваются в размере на 10% и уменьшаются обратно, когда курсор мыши уходит с элемента. 

###Блок the team
![](./task/images/template_10.png)

* Добавьте произвольное фото для трех членов команды.
* При клике по изображению члена команды, под ним отображается блок с описанием его навыков. По умолчанию этот блок отображается для первого в списке человека. 
* Когда блок впервые появляется не экране, числа, что показывают уровень владения каждой технологией, а так же круговые диаграммы, плавно увеличиватся от 0 до значений в макете.
 
###Блок Our clients 
![](./task/images/template_11.png) 

* Краткое описание партнеров компании. 
* Слайдер с изображениями логотипов партнеров компании. Прокрутка изображений происходит циклически, элементы управления отсутствуют. 

###Блок отзывов
![](./task/images/template_12.png)

* Слайдер с отзыами клиентов. Навигация с помощью точек. Количество точек соответствует количеству отзывов.  

###Блок SEND US A MESSAGE 
![](./task/images/template_13.png)
![](./task/images/template_14.png)

* Форма с полями Name, Email, Subject, Message. Валидация формы происходит при нажатии на клавиши. При вводе пользователем некорректных данных в поле ввода под этим полем сразу отображается сообщение об ошибке. Сообщение об ошибке сразу же скрывается, если пользователь ввел корректные данные. 
* В поле Name допускаются только буквы английского алфавита.
* В поле Email допускаются толко буквы английского алфавита, цифры, знак подчеркивание и симвом @.
* В поле Subject допускаются только буквы английского алфавита и цифры.
* В поле Message допускаются любые символы.

###Footer 
![](./task/images/template_15.png)

* Копирайт и ссылки на социальные сети.
* Кнопка со стрелкой вверх при нажатии на которую страница прокручивается в начало. 



