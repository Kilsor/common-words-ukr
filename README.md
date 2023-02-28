# Слова, які часто використовуються в CSS-класах

## Зображення

`image`, `img`, `picture`, `pic` - картинка

`icon` - іконка

`logo` - логотип

`userpic`, `avatar` - юзерпік, маленька картинка користувача

`thumbnail`, `thumb` — мініатюра, зменшене зображення

## Текст

`title`, `subject`, `heading`, `headline`, `caption` - заголовок

`subtitle` - підзаголовок

`slogan` - слоган

`lead`, `tagline` - лід-абзац у тексті

`text` - текстовий контент

`desc` - опис, варіант текстового контенту

`excerpt` — уривок тексту, який зазвичай використовується перед посиланням «Читати далі...»

`quote`, `blockquote` - цитата

`snippet` - приклад коду

`link` - посилання

`copyright`, `copy` — копірайт

## Списки

`list`, `items` — список

`item` - елемент списку

## Блоки

`page` - кореневий елемент сторінки

`header` - шапка (сторінки або елемента)

`footer` - підвал (сторінки або елемента)

`section` — розділ контенту (один із кількох)

`main`, `body` - основна частина (сторінки або елемента)

`content` - вміст елемента

`sidebar` - бічна колонка (сторінки або елемента)

`aside` - блок з додатковою інформацією

`widget` - віджет, наприклад, у бічній колонці

## Розкладка

`wrapper`, `wrap` - обгортка, зазвичай зовнішня

`inner` - внутрішня обгортка

`container`, `holder`, `box` - контейнер

`grid` - розкладка (сторінки або елемента) у вигляді сітки (зазвичай містить у собі `row` та `col`)

`row` - контейнер у вигляді рядка

`col`, `column` - контейнер у вигляді стовпця

## Елементи управління

`button`, `btn` - кнопка, наприклад, для відправлення форми

`control` - елемент управління, наприклад, стрілки "Вперед/назад" у фотогалереї, кнопки управління слайдером

`dropdown` - випадаючий список

## Медіавирази

`phone`, `mobile` - мобільні пристрої

`phablet` - телефони з великим екраном (6-7")

`tablet` - планшети

`notebook`, `laptop` - ноутбуки

`desktop` - настільні комп'ютери

## Розміри

`tiny`, `xs` - маленький, крихітний

`small`, `sm` - невеликий

`medium`, `base` - середній

`big`, `large`, `lg` - великий

`huge`, `xl` - величезний

`narrow` - вузький

`wide` - широкий

## Різне

`search` — пошук

`socials` - блок іконок соцмереж

`advertisement`, `adv`, `commercial`, `promo` - рекламний блок (ріжуться Адблоком, не рекомендується використовувати такі класи для блоків з внутрішньою рекламою)

`features`, `benefits` - список основних особливостей товару, послуги

`slider`, `carousel` - слайдер, інтерактивний елемент з прокручуванням вмісту

`pagination` - посторінкова навігація

`user`, `author` - користувач, автор запису або коментаря

`meta` - блок з додатковою інформацією, наприклад, блок тегів та дати в пості

`cart`, `basket` - кошик

`breadcrumbs` - навігаційний ланцюжок, «хлібні крихти»

`more`, `all` - посилання на повну інформацію

`modal` - модальне (діалогове) вікно

`popup` - спливаюче вікно

`tooltip`, `tip` - спливаюче підказки

`preview` - анонс, уривок, наприклад новини або посту, може складатися із заголовка, опису та картинки. Передбачається посилання на повну версію

`overlay` - перекриваючий шар, наприклад, для затемнення зображень або створення модальних вікон

## Стану

`active`, `current` - активний елемент, наприклад, поточний пункт меню

`visible` - видимий елемент

`hidden` - прихований елемент

`error` - статус помилки

`warning` - статус попередження

`success` - статус успішного виконання завдання

`pending` - стан очікування, наприклад, перед зміною статусу на error або success

## Приклади використання

### Простий список

```html
<ul class="list">
  <li class="item">Перше</li>
  <li class="item">Друге</li>
  <li class="item">Третє</li>
</ul>
```

### Картинка користувача (юзерпік)

```html
<div class="user">
  <img class="user__img" src="userpic.png" alt="Дормідонт Петрович" />
  <a class="user__link" href="#">Дормідонт Петрович</a>
</div>
```

### Галерея

```html
<div class="gallery">
  <ul class="gallery__list">
    <li class="gallery__item">
      <img
        class="gallery__img"
        src="flowers.jpg"
        alt="Цвітемо як останній раз"
      />
    </li>
    <li class="gallery__item">
      <img class="gallery__img" src="trees.jpg" alt="Парк «Три сосни»" />
    </li>
  </ul>
</div>
```

### Навігація

```html
<nav class="nav">
  <a class="nav__link nav__link--active">Головна</a>
  <a class="nav__link" href="#">Другорядна</a>
  <a class="nav__link" href="#">Третя з кінця</a>
  <a class="nav__link" href="#">Предостання</a>
  <a class="nav__link" href="#">Зовсім кінець</a>
</nav>
```

```html
<nav class="nav">
  <ul class="nav__list">
    <li class="nav__item nav__item--current">
      <a class="nav__link">Головна</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Статті</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Фотогалерея</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Контакти</a>
    </li>
  </ul>
</nav>
```

### Віджет у бічній колонці

```html
<div class="widget">
  <h4 class="widget__title">Вирощуємо желе</h4>
  <div class="widget__content">
    <p>
      Щоб виростити товариське доброзичливе желе, нам знадобиться рулон
      поролону, два кілограми цукру, три яйця та пів чайної чашки ацетону.
    </p>

    <a class="widget__link" href="#">Не читати далі...</a>
  </div>
</div>
```

### Блок новин

```html
<div class="news">
  <h3 class="news__title">Учорашні новини</h3>

  <ul class="news__list">
    <!-- до класу елемента додаємо клас блоку,
              щоб створити новий простір імен -->
    <li class="news__item item-news">
      <h4 class="item-news__title">
        Змагання серед обли з ковзанярського спорту
      </h4>
      <div class="item-news__text">
        <p>Перемогла команда кілок із Петрозаводська</p>

        <a href="#" class="item-news__link">Читати далі</a>
      </div>
    </li>

    <li class="news__item item-news">
      <h4 class="item-news__title">
        Науковці уточнили роль напилка у догляді за нігтями
      </h4>
      <div class="item-news__text">
        <p>
          Британські вчені високо оцінили внесок напильника у відрощуванні
          півтораметрових нігтів.
        </p>

        <a href="#" class="item-news__link">Не читати далі</a>
      </div>
    </li>
  </ul>
</div>
```

### Стаття або пост у блозі (простий варіант)

```html
<article class="article">
  <h3 class="article__title">Намацуємо чакри біля пучка петрушки</h3>
  <time class="article__datetime">32 травня, 10:87</time>

  <div class="article__author author-article">
    <img class="author-article__img" src="userpic.png" alt="Клішня Андріївна" />
    <a class="author-article__link" href="#">Клішня Андріївна Долгорука</a>
    <div class="author-article__desc">Наш експерт з чакрів</div>
  </div>

  <div class="article__content">
    Сходіть на ринок і купіть у стареньких пучок петрушки грам на 100. Як слід
    переберіть, очистіть від жуків та гусениць. Жуків віддайте погратися коту,
    гусениць поселіть у горщик з кактусами, нехай одна буде Джоном, друга Біллі,
    а у вас у горщику тепер буде Дикий Захід. Поверніться до пучка петрушки.
    Ласкаво погляньте на нього і добре почухайте за вухом, можна собі чи коту.
    Перев'яжіть атласною стрічкою, Обов'язково зав'яжіть бант. Вітаємо! Тепер у
    вас є повністю одомашнений пучок петрушки, який буде весело бігати за вами
    по п'ятах і пророщувати своє насіння у ваших капцях.
  </div>
</article>
```

### Стаття або пост у блозі (складний варіант)

```html
<article class="entry">
  <header class="entry__header">
    <h3 class="entry__title title-entry">
      <a class="title-entry__link" href="#"
        >Гумові качечки як спосіб самопізнання</a
      >
    </h3>

    <time class="entry__datetime">32 травня, 10:87</time>
  </header>

  <div class="entry__author author-entry">
    <img class="author-entry__img" src="userpic.png" alt="Василіс Сергійович" />

    <a class="author-entry__link" href="#">Василіса Сергійович</a>
  </div>

  <div class="entry__content">
    Дістаньте з горища коробку з півсотнею гумових качечок, решти після
    святкування нового року. З качечок і свічок викладіть пентаграму на підлозі
    кімнати. Сядьте посередині у позу лотоса, в кожну руку візьміть за
    німецько-бразильським словником, прокашляйтесь, наберіть повні груди повітря
    і голосно і впевнено, з повною самовіддачею скажіть "Кря!"
  </div>

  <div class="entry__tags tags-entry">
    <h4 class="tags-entry__title">Мітки</h4>

    <ul class="tags-entry__list">
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">хоровод своїми руками</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">порцелянові капці</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">гуталін у кулінарії</a>
      </li>
    </ul>
  </div>

  <div class="entry__actions actions-entry">
    <ul class="actions-entry__list">
      <li class="actions-entry__item actions-entry__item--read">
        <a class="actions-entry__link" href="#">238 відповідей</a>
      </li>
      <li class="actions-entry__item actions-entry__item--write">
        <a class="actions-entry__link" href="#">Написати в спортлото</a>
      </li>
      <li class="actions-entry__item actions-entry__item--share">
        <a class="actions-entry__link" href="#">Поділитись</a>
      </li>
    </ul>
  </div>
</article>
```
