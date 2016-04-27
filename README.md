# Задание 1. Тренировка именования классов по БЭМ.

Я здесь накидал скриншотов разных часто встречающихся блоков, нужно будет написать плоскую структуру блока, о которой говорили в видео №2. [Примеры именования блоков и элементов](materials/bem-names.md).
Пример как оформлять привел для картинки №1. Все остальные нужно придумать самим. Всего их 11, если считать первую.

<figure>
    <figcaption>Pic 1</figcaption>
    <div><img src="img/01.png" height="663" width="568" alt=""></div>
 </figure>

```less
// Pic 1qwe
.info-block {
	&__img {}
	&__container {}
	&__title {}
	&__text {}
	&__btn {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 2</figcaption>
    <div><img src="img/02.png" height="126" width="275" alt=""></div>
 </figure>

```less
// Pic 2
.post {
  &__description {}
  &__icon {}
  &__date {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 3</figcaption>
    <div><img src="img/03.png" height="125" width="521" alt=""></div>
 </figure>

```less
// Pic 3
.feature {
  &__icon {}
  &__title {}
  &__description {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 4</figcaption>
    <div><img src="img/04.png" height="321" width="926" alt=""></div>
 </figure>

```less
// Pic 4
.article {
  &__title {}
  &__icon-divider {}
  &__text {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 5</figcaption>
    <div><img src="img/05.png" height="703" width="853" alt=""></div>
 </figure>

```less
// Pic 5
.container {
  &__avatar {}
  &__description {}
  &__font-icon{}
  &__divider {}
  &__text {}
  .info-block {
    &__count{}
    &__description {}
  }
}
```
<hr> <br>

<figure>
    <figcaption>Pic 6</figcaption>
    <div><img src="img/06.png" height="522" width="1094" alt=""></div>
 </figure>

```less
// Pic 6
.feature {
  &__title {}
  &__description {}
  &__img {}
  &__divider {}
}
.btn {
  &_light{}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 7</figcaption>
    <div><img src="img/07.png" height="117" width="1176" alt=""></div>
 </figure>

```less
// Pic 7
.navbar {
  &__nav-item {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 8</figcaption>
    <div><img src="img/08.png" height="338" width="415" alt=""></div>
 </figure>

```less
// Pic 8
.container {
  &__title{}
  .contacts {
    &__address{}
    &__phone{}
  }
}
.favorite{
}
.rating-container {
  &__icon {}
  &__rate {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 9</figcaption>
    <div><img src="img/09.png" height="514" width="414" alt=""></div>
 </figure>

```less
// Pic 9
.info-box{
  &__title{}
  &__subtitle{}
  .features{
    &__icon{}
    &__item{}
  }
  .btn{
  }
}
```
<hr> <br>

<figure>
    <figcaption>Pic 10</figcaption>
    <div><img src="img/10.png" height="511" width="749" alt=""></div>
 </figure>

```less
// Pic 10
.container{
  &__title{}
  .info-block {
    &__subject{}
    &__description{}
  }
}
.ratings {
  &__icon{}
  &__name{}
  &__date{}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 11</figcaption>
    <div><img src="img/11.png" height="619" width="941" alt=""></div>
 </figure>

```less
// Pic 11
.wrapper{
  &__img{}
  &__cost{}
  .features{
   &__item{}
  }
  &__description{}
  &__submit-btn{}
  .info-block {
   &__item{}
  }
}
.social {
  &__text{}
  &__item{}
}
.ratings{
  &__icon{}
  &__count{}
}
.head {
  &__breadcrumbs{}
  &__title{}
}
.counter{
}
.pointer{
  &_horizontal{}
  &_vertical{}
}
```
<hr> <br>
