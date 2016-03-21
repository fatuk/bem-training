# Задание 1. Тренировка именования классов по БЭМ.

Я здесь накидал скриншотов разных часто встречающихся блоков, нужно будет написать плоскую структуру блока, о которой говорили в видео №2. [Примеры именования блоков и элементов](materials/bem-names.md).
Пример как оформлять привел для картинки №1. Все остальные нужно придумать самим. Всего их 11, если считать первую.

<figure>
    <figcaption>Pic 1</figcaption>
    <div><img src="img/01.png" height="663" width="568" alt=""></div>
 </figure>

```less
// Pic 1
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
.api-down-message {
  &__logo {}
  &__description {}
  &__last-update {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 3</figcaption>
    <div><img src="img/03.png" height="125" width="521" alt=""></div>
 </figure>

```less
// Pic 3

.features {}

.feature-block {
  &__logo {
    &--responsive {}
    &--parallax {}
    &--full-size {}
  }
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
.theme-annotation {
  &__title {}
  &__decoration {}
  &__description {
    &--stressed {}
  }
}

.decoration {
    &__line {}
    &__icon {}
}

```
<hr> <br>

<figure>
    <figcaption>Pic 5</figcaption>
    <div><img src="img/05.png" height="703" width="853" alt=""></div>
 </figure>

```less
// Pic 5
.cv-profile {
  &__avatar {}
  &__title {}
  &__decoration-line {}
  &__description {}
  &__counters-block {}
}

.counter {
  &__number {}
  &__type {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 6</figcaption>
    <div><img src="img/06.png" height="522" width="1094" alt=""></div>
 </figure>

```less
// Pic 6
.optimized-block {
  &__image {}
  &__title {}
  &__underline {}
  &__description {}
  &__button {
    &--view {}
    &--see {}
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
.top-menu {
  &__category {}
  &__shopping-cart {}
  &__icon {
    &--search {}
    &--menu {}
  }
}

.shopping-cart {
  &__items-count {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 8</figcaption>
    <div><img src="img/08.png" height="338" width="415" alt=""></div>
 </figure>

```less
// Pic 8
.contact-info {
  &__image {}
  &__status {}
}

.contact-address {
  &__title {}
  &__text {}
  &__icon {}
}

.contact-status {
  &__stars {}
  &__score {}
  &__favorite {}
}

.star {
  &--selected {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 9</figcaption>
    <div><img src="img/09.png" height="514" width="414" alt=""></div>
 </figure>

```less
// Pic 9
.package-item {
  &__title {}
  &__underline {}
  &__price {}
  &__price-time {}
  &__logo-feature {
    &--unallowed {}
  }
  &__feature-text {}
  &__button {}
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
  &__count {}
}

.review-item {
  &__info {}
  &__text {}
}

.review-info {
  &__stars {}
  &__place {}
  &__date {}
}

.review-stars {
  &__star {
    &--selected {}
  }
}

.review-text {
  &__title {}
  &__description {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 11</figcaption>
    <div><img src="img/11.png" height="619" width="941" alt=""></div>
 </figure>

```less
// Pic 11
.shop-item {
  &__image {}
  &__title {}
  &__decoration {}
  &__info {}
  &__description {}
  &__options {}
  &__cart {}
  &__article {}
  &__share {}
}

.shop-item-title {
  &__breadcrumbs {}
  &__title {}
  &__button {
    &--next {}
    &--prev {}
  }
}

.shop-item-info {
  &__price {}
  &__stars {}
  &__reviews {}
}

.show-item-stars {
  &__star {
    &--selected {}
  }
}

.shop-item-cart {
  &__count {}
  &__button {
    &--up {}
    &--down {}
  }
  &__cart-button {}
  &__favorite {
    &--added {}
  }
}

.cart-button {
  &__logo {}
  &__text {}
}

.shop-item-share {
  &__title {}
  &__item {}
}

.share-item {
  &__icon {}
  &__count {}
}
```
<hr> <br>
