Чертоги фрилансера версия для РФ 3.0

//------------------------------------------------------------------------------
Документация до шаблону: https://start-template.ru 
//------------------------------------------------------------------------------

Спецсимволы
// --------------------------
   <   &lt;
   >   &gt;
   =   &#x3D;
   "   &quot;
   /   &#x2F;
   tab &nbsp;
   троетточие    &#8230;
   длинное тире  &#8212;
   кавычки       &#187;
   апостроф      &#8216;
   собака        &#64; 
   &rang;&rang;&rang;&rang;  стрелки-ссылки
   &UpArrow;                 стрелка вверх
   &DownArrow;               стрелка вниз 
// --------------------------

<i class="fa-solid fa-up-right-from-square"></i>    ссылка
<i class="fa-solid fa-video"></i>                   видео
<i class="fa-solid fa-file-zipper"></i>             zip-архив 
<i class="fas fa-fw text-info fa-briefcase"></i>    портфель
<i class="fas fa-fw text-info fa-book"></i>         книга  PDF






Шаблон страницы
//------------------------------------------------------------------------------
div class="page__container">

   <h1 class="page__title" id="top">Горячие сочетания клавиш</h1>

 <!-- Оглавление  -->

   <div data-spollers class="spollers">
      <details class="spollers__item">
         <summary class="spollers__title spollers__title--bg">Оглавление</summary>
         <div class="spollers__body spollers__body--menu">
            <a href="#h-items_1" class="con-menu">Медиа</a>
            <a href="#h-items_2" class="con-menu">Адаптация</a>
            <a href="#h-items_3" class="con-menu">видео</a>
            <a href="#h-items_4" class="con-menu">меню</a>
            <a href="#h-items_5" class="con-menu">таблиц</a>
         </div>
      </details>
   </div>

   <!-- Контейнер  со статьями -->
   <div class="page__content">


      <!--! Статья 1 -->
<h2 class="page__subtitle" id="h-items_1">Медиа</h2>
      <div class="page__content--items">

      </div>

       <!--! Статья 2 -->
      <h2 class="page__subtitle" id="h-items_2">Медиа</h2>
      <div class="page__content--items">
      
      </div>
       <!--! Статья 3 -->
      <h2 class="page__subtitle" id="h-items_3">запросы</h2>
      <div class="page__content--items">
      
      </div>

   </div>

</div>

Блок с увеличением изображения при наведении
//----------------------------------
<div class="page__block--pic">
   <img src="@img/h/links/links_1.png" class="img-links" alt="Варианты ссылок">

   <img src="@img/h/links/links_2.png" class="img-links" alt="Варианты ссылок">
</div>
//----------------------------------

Проблемы
//----------------------------------
html - адаптация видео. Не удалось запустить видео, надо пробовать после перехода в обычный режим.
html - видео, аудио. как и предыдущий материал не работают, или пути или чертоги не пропускают.
html - прогрессБар  Подключить скрипт  9 строка кода.
html - Font Awesome - Установка и подключение. подключить архив
                      173 строка таблица и ее подключение
                      проверка вывода иконок
                      Проверка работы скриптов при подключенных иконках
html - Формы.  кнопка-рисунок в таблице - не выводит рисунок
wp - создание темы . ссылки на архив
wp - кнопка вверх . ссыла на txt файл 

grid - Строки и столбцы.... строка 83 ссылки на статьи с ID

js - основные скрипты  проверить работу всего при подключениии библиотек из интернета 
      и не только на этой страницу
js - Фиксированный Header при скролле работа Демо, возможно нужно подключать библиотеку








== css - bg+color   Адрес рисунка в css 
//----------------------------------




 <div data-spollers class="spollers">
      <details class="spollers__item">
         <summary class="spollers__title spollers__title--bg">Оглавление</summary>
         <div class="spollers__body spollers__body--menu">
            <a href="#h-items_1" class="con-menu">Ссылки</a>
            <a href="#h-items_2" class="con-menu">Выравнивание блока по центру</a>
            <a href="#h-items_3" class="con-menu">Выравнивание по горизонтали</a>
            <a href="#h-items_4" class="con-menu">Выравнивание по вертикали</a>
            <a href="#h-items_5" class="con-menu">Позиционирование</a>
            <a href="#h-items_6" class="con-menu">Видимость элементов</a>
         </div>
      </details>
   </div>




   	<!-- Ссылки  -->

				<div data-spollers class="spollers">
					<details class="spollers__item">
						<summary class="spollers__title spollers__title--bg">Основные помощники</summary>
						<div class="spollers__body spollers__body--menu">

							<div class="page__block--list">
								<ul class="page__block--list-arhive">
                        
									<li><i class="fa-solid fa-up-right-from-square"></i><a class="link" href="" target="_blank" title=""></a></li>

								   <li><i class="fa-solid fa-up-right-from-square"></i><a class="link" href="" target="_blank" title=""></a></li>

									<li><i class="fa-solid fa-up-right-from-square"></i><a class="link" href="" target="_blank" title=""></a></li>

                           <li><i class="fa-solid fa-up-right-from-square"></i><a class="link" href="" target="_blank" title=""></a></li>

								</ul>
							</div>

						</div>
					</details>
				</div>




            // Вставка видео 

                  <figure>
							<div class="">
								<iframe loading="lazy"
									title="GULP 2022"
									width="500" height="281" src="https:/"
									frameborder="0"
									allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
									allowfullscreen></iframe>
							</div>
						</figure>

						<p>При отсутствии интернета можно просмотреть видео из архива</p>

						<div class="page__block-video">
							<video width="500" height="281" src="../../video/fls/gulp2022.mp4" controls="" preload="metadata"
								poster="../../video/html/poster.jpg" width="100%">

							</video>
						</div>




      // свернутое изображение

      <details>
         <summary>Соотношение размеров шрифта</summary>
         <picture>
            <img src="../../img/c/font_size.png"
               alt="image" class="details-img">
         </picture>
      </details>




// список  


 <div class="page__block--list">
    <ol>
        <li>Просматривать</li>
        <li>Управление:
            <ul class="page__block--ul">
                <li></li>
                <li></li>
                <li></li>
            </ul>
        </li>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ol>
</div>


      <script src="https://code.jquery.com/jquery-3.7.1.js"></script>




      ==================================================================================================


      <!DOCTYPE html>
<html lang="en">

<head>
  <title>Модуль "Popup"</title>
  <meta charset="UTF-8">
  <meta name="format-detection" content="telephone=no">
  <!-- <style>body{opacity: 0;}</style> -->
  <link rel="stylesheet" href="../../css/style.min.css?_v=20241026231742">
  <link rel="shortcut icon" href="favicon.ico">
  <!-- <meta name="robots" content="noindex, nofollow"> -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<style>
  .pre code {
    font-size: 12px;
  }
</style>

<body>
  <div class="wrapper">

    <main class="page">
      <div class="page__container">

        <h1 class="page__title"> Молуль "Popup"</h1>


        <!-- Контейнер  со статьями -->
        <div class="page__content">

          <!--! Статья 1 -->

          <div class="page__content--items">
          </div>


          <div class="page__footer">

            <div class="page__footer_left">

              <p>Burger на jQuvery<br>
                <a href="../modules/burger_Q.html" class="link">&lt;= Burger на jQuvery</a>
              </p>
            </div>

            <div class="page__footer_right">

              <p>Burger из ЧФ<br>
                <a class="link" href="../fls/fls-page_7.html">Модуль меню «бургер» =></a>
              </p>
            </div>
          </div>

          <hr class="page__hr">

        </div>

        <div class="return">
          <div class="return__container">

            <p><a href="../ready/ready-menu.html" class="link">К меню "Готовые решения"</a></p>
            <p><a href="../../index.html" class="link">К меню " Справочник по всем вопросам "</a></p>


          </div>
        </div>

        <footer class="footer">
          <div class="footer__container">

            <!-- Кнопка вверх -->
            <!-- https://itchief.ru/javascript/btn-up -->
            <div class="btn-up btn-up_hide"></div>


          </div>

        </footer>

    </main>
  </div>
  <script src="../../js/app.min.js?_v=20241026231742"></script>

  <!-- ! Кнопка "Вверх" -->
  <script>
    const btnUp = {
      el: document.querySelector('.btn-up'),
      scrolling: false,
      show() {
        if (this.el.classList.contains('btn-up_hide') && !this.el.classList.contains('btn-up_hiding')) {
          this.el.classList.remove('btn-up_hide');
          this.el.classList.add('btn-up_hiding');
          window.setTimeout(() => {
            this.el.classList.remove('btn-up_hiding');
          }, 300);
        }
      },
      hide() {
        if (!this.el.classList.contains('btn-up_hide') && !this.el.classList.contains('btn-up_hiding')) {
          this.el.classList.add('btn-up_hiding');
          window.setTimeout(() => {
            this.el.classList.add('btn-up_hide');
            this.el.classList.remove('btn-up_hiding');
          }, 300);
        }
      },
      addEventListener() {
        // при прокрутке окна (window)
        window.addEventListener('scroll', () => {
          const scrollY = window.scrollY || document.documentElement.scrollTop;
          if (this.scrolling && scrollY > 0) {
            return;
          }
          this.scrolling = false;
          // если пользователь прокрутил страницу более чем на 150px
          if (scrollY > 150) {
            // сделаем кнопку .btn-up видимой
            this.show();
          } else {
            // иначе скроем кнопку .btn-up
            this.hide();
          }
        });
        // при нажатии на кнопку .btn-up
        document.querySelector('.btn-up').onclick = () => {
          this.scrolling = true;
          this.hide();
          // переместиться в верхнюю часть страницы
          window.scrollTo({
            top: 0,
            left: 0,
            behavior: 'smooth'
          });
        }
      }
    }

    btnUp.addEventListener();
  </script>
</body>

</html>



// Заготовка для модулей

<div class="modules__container ">

    <h1 class="modules__title">Модуль "Before - After" </h1>

    <div class="modules__content">


      <h2 class="modules__content--title">Пример</h2>

      <div class="modules__content--item">
  ....
      </div>

      <h2 class="modules__content--title">Описание</h2>

      <div class="modules__content--item">

  ....
      <hr class="modules__hr">
        
        <p><a href="..../sborka/fls/fls-page_37.html" class="modules__link">Документация</a></p>
      
      </div