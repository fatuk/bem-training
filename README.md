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
.message {
  &__icon {}
  &__content {}
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
.features {
  &__item {}
  &__icon {}
  &__title
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
.theme {
  &__caption {}
  &__underscore {}
  &__description {}
  &__feature {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 5</figcaption>
    <div><img src="img/05.png" height="703" width="853" alt=""></div>
 </figure>

```less
// Pic 5
.profile {
  &__userpic {}
  &__quote {}
  &__mark {}
  &__delimiter {}
  &__description {}
}
.indicators {
  &__item {}
  &__value {}
  &__label {}
}

```
<hr> <br>

<figure>
    <figcaption>Pic 6</figcaption>
    <div><img src="img/06.png" height="522" width="1094" alt=""></div>
 </figure>

```less
// Pic 6
.product-preview {
  &__btn {}
}
.product-info {
  &__title {}
  &__description {}
  &__btn {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 7</figcaption>
    <div><img src="img/07.png" height="117" width="1176" alt=""></div>
 </figure>

```less
// Pic 7
.menu {
  &__item {}
}
.tools {
  &__cart {}
  &__search {}
  &__hamburger {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 8</figcaption>
    <div><img src="img/08.png" height="338" width="415" alt=""></div>
 </figure>

```less
// Pic 8
.place-card {
  &__description {}
  &__name {}
  &__address {}
  &__phone {}
}
.actions {
  &__stars {}
  &__score {}
  &__like {}
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
  &__section {
    &--wihtout-undescore {}
  }
  &__name {}
  &__price {}
  &__amount {}
  &__features {}
  &__item {
    &--included {}
  }
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
  &__caption {}
}
.review {
  &__statistics {}
  &__rating {
    &--0 {}
    &--1 {}
    &--2 {}
    &--3 {}
    &--4 {}
    &--5 {}
  }
  &__author {}
  &__date {}
  &__content {}
  &__title {}
  &__text {}
  &--wihtout-undescore {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 11</figcaption>
    <div><img src="img/11.png" height="619" width="941" alt=""></div>
 </figure>

```less
// Pic 11
.product {
  &__picture {}
  &__caption {}
  &__navbtn {
    &--prev {}
    &--next {}
  }
  &__price {}
  &__description {}
  &__attributes {}
  &__review-btn {}
  &__properties {}
}
.breadcrumbs {
  &__item {}
  &__delimiter {}
}

.reviews {
  &__rating {
    &--0 {}
    &--1 {}
    &--2 {}
    &--3 {}
    &--4 {}
    &--5 {}
  }
  &__count {}
}

.add-to-cart {
  &__quantity {}
  &__qty-btn {
    &--increase {}
    &--decrease {}
  }
  &__add-btn {}
}

.share-links {
  &__caption {}
  &__item {
    &--fb {}
    &--tw {}
    &--pin {}
  }
  &__count {
    &--hidden {}
  }
}
```
<hr> <br>
