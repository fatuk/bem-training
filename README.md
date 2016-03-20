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
.social-post {
	&__img {}
	&__text {}
	&__time {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 3</figcaption>
    <div><img src="img/03.png" height="125" width="521" alt=""></div>
 </figure>

```less
// Pic 3
.tiles-container {
}
.tile {
	&__img {}
	&__titile {}
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
.post-preview {
	&__title {}
	&__divider {}
	&__img-divider {}
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
.profile-info {
	&__img {}
	&__status {}
	&__divider
	&__text {}
	&__stats-container {}
}
.stat {
	&__value {}
	&__descrption {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 6</figcaption>
    <div><img src="img/06.png" height="522" width="1094" alt=""></div>
 </figure>

```less
// Pic 6
.slide {
	&__img {}
	&__title {}
	&__divider {}
	&__text {}
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
.main-menu {}
.menu-text-item {
	&__text {}
}
.menu-image-item {
	&__img {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 8</figcaption>
    <div><img src="img/08.png" height="338" width="415" alt=""></div>
 </figure>

```less
// Pic 8
.poi {
	&__top-container {}
	&__img {}
	&__name {}
	&__address {}
	&__phone-img {}
	&__phone-text {}
	&__bottom-container {}
}
.rate-bar {
	&__stars-container {}
	&__star {}
	&__value {}
}
.favourites-icon {}
```
<hr> <br>

<figure>
    <figcaption>Pic 9</figcaption>
    <div><img src="img/09.png" height="514" width="414" alt=""></div>
 </figure>

```less
// Pic 9
.subscription {
	&__name {}
	&__divider {}
	&__price {}
	&__duration {}
	&__benefit-icon {}
	&__benefit-text {}
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
	&__divider {}
}
.review {
	&__left-container {}
	&__name {}
	&__date {}
	&__right-container {}
	&__title {}
	&__text {}
}
.rate-bar {}
.star {
	&--selected {}
	&--deselected {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 11</figcaption>
    <div><img src="img/11.png" height="619" width="941" alt=""></div>
 </figure>

```less
// Pic 11
.apparel {
	&__img {}
	&__container {}
	&__nav {}
	&__nav-text {}
	&__name {}
	&__nav-icon {}
	&__nav-icon--pressed {}
	&__divider {}
	&__price {}
	&__description {}
	&__quantity-container {}
	&__quantity-count {}
	&__quantity-img {}
	&__quantity-img--pressed {}
	&__btn-add {}
	&__add-icon {}
	&__btn-bookmark {}
	&__bookmark-icon {}
	&__info-text {}
}
.rate-bar {
	&__stars-container {}
	&__reviews-count {}
}
.star {
	&--selected {}
	&--deselected {}
}
.share {
	&__text {}
	&__counter {}
	&__img {}
}
```
<hr> <br>
