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
.tweet {
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
.items {
	&--responsive{}
	&--parallax-effect{}
	&--control{}
}
.item{
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
.announcement {
	&__title {}
	&__divider {}
	&__subtitle {}
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
	&__img {}
	&__description {}
	&__divider {}
	&__text {}
	&__advantages{}
}
.advantage{
	&__name {}
	&__value {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 6</figcaption>
    <div><img src="img/06.png" height="522" width="1094" alt=""></div>
 </figure>

```less
// Pic 6
.info {
	&__img {}
	&__title {}
	&__divider {}
	&__description {}
	&__btn{}
}

.button{}
// Your code goes here
```
<hr> <br>

<figure>
    <figcaption>Pic 7</figcaption>
    <div><img src="img/07.png" height="117" width="1176" alt=""></div>
 </figure>

```less
// Pic 7
.main-menu {
}
.text-item{
	&--home {}
	&--demos-and-features {}
	&--pages {}
	&--elements {}
	&--work{}
	&--blog{}
	&--shop{}
}
.search-item{
}
.cart-item{
}
.hamburger-item{
}
```
<hr> <br>

<figure>
    <figcaption>Pic 8</figcaption>
    <div><img src="img/08.png" height="338" width="415" alt=""></div>
 </figure>

```less
// Pic 8
.item {
	&__img {}
	&__title {}
	&__address {}
	&__phone {}
}
.reactions {
	&__rating{}
	&__like{}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 9</figcaption>
    <div><img src="img/09.png" height="514" width="414" alt=""></div>
 </figure>

```less
// Pic 9
.package-info {
	&__title {}
	&__divider {}
	&__price {}
	&__options {}
	&__btn{}
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

.rewiew-item{
	&__author {}
	&__date {}
	&__title {}
	&__text {}
}
.rating{
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
	&__image {}
	&__header{}
	&__link {}
	&__title {}
	&__nav-button
	&__divider {}
	&__price {}
	&__reviews {}
	&__description {}
	&__additional-info {}
	&__count {}
	&__add-to-cart-btn {}
	&__rate {}
}
.social-panel {
	&__share {}
}
.social-button{
	&&--facebook{}
	&&--twitter{}
	&&--?
}
.rating{
}
.count{
	&__text {}
	&__nav-button {}
}
```
<hr> <br>
