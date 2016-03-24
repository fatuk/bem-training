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
.twitt {
  &__img {}
  &__container {}
  &__text {}
  &__timeline {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 3</figcaption>
    <div><img src="img/03.png" height="125" width="521" alt=""></div>
 </figure>

```less
// Pic 3
.container {}
.info-block {
  &__img {}
  &__title {}
  &__text {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 4</figcaption>
    <div><img src="img/04.png" height="321" width="926" alt=""></div>
 </figure>

```less
// Pic 4
.container {
  &__title {}
  &__divider {}
  &__text
}
```
<hr> <br>

<figure>
    <figcaption>Pic 5</figcaption>
    <div><img src="img/05.png" height="703" width="853" alt=""></div>
 </figure>

```less
// Pic 5
.main-container {}
.logo {
  &__img {}
  &__text {}
}
.main-info {
  &__divider {}
  &__text {}
}
.metrics {}
.metric-info {
  &__count {}
  &__text {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 6</figcaption>
    <div><img src="img/06.png" height="522" width="1094" alt=""></div>
 </figure>

```less
// Pic 6
.logo {
  &__img {}
  &__btn {
    &_hover {}
    &_pressed {}
  }
}
.main-info {
  &__title {}
  &__description {}
  &__btn {
    &_hover {}
    &_pressed {}
  }
}
```
<hr> <br>

<figure>
    <figcaption>Pic 7</figcaption>
    <div><img src="img/07.png" height="117" width="1176" alt=""></div>
 </figure>

```less
// Pic 7
.main-menu {
  &__container {}
  &__btn {}
  &__search {}
  &__more-info {}
  &__shopping-cart {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 8</figcaption>
    <div><img src="img/08.png" height="338" width="415" alt=""></div>
 </figure>

```less
// Pic 8
.card {
  &__container {}
  &__title {}
  &__address {}
  &__footer {}
}
.phone {
  &__img {}
  &__text {}
}
.rating {
  &__img {}
  &__img-set {}
  &__number {}
  &__review {}
}
.like-btn {
  &__img {
    &_hover {}
    &_clicked {}
  }
}
```
<hr> <br>

<figure>
    <figcaption>Pic 9</figcaption>
    <div><img src="img/09.png" height="514" width="414" alt=""></div>
 </figure>

```less
// Pic 9
.package {
  &__title {}
  &__price {}
  &__advantage-list {}
  &__advantage-item {}
  &__btn {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 10</figcaption>
    <div><img src="img/10.png" height="511" width="749" alt=""></div>
 </figure>

```less
// Pic 10
.reviews {
  &__title {}
  &__title-count {}
  &__items {}
}
.review-item {
  &__author {}
  &__date {}
  &__title {}
  &__description {}
}
.rating {
  &__img {}
}

```
<hr> <br>

<figure>
    <figcaption>Pic 11</figcaption>
    <div><img src="img/11.png" height="619" width="941" alt=""></div>
 </figure>

```less
// Pic 11
.main-container {}
.photo {}
.product {
  &__price {}
  &__rating {}
  &__description {}
  &__features {}
  &__detail-info {}
}
.category-navigation {
  &__structure {}
  &__title {}
  &__back-btn {}
  &__forward-btn {}
}
.cart-btn {
  &__img {}
  &__text {}
}
.starred-btn {}
.quantity {
  &__text {}
  &__selector {}
}
.socials {
  &__text {}
  &__count {}
  &__facebook {}
  &__twitter {}
  &__circle {}
}
```
<hr> <br>
