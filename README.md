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
.twitter-post {
    &__message {}
    &__timestamp {}
    &__logo {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 3</figcaption>
    <div><img src="img/03.png" height="125" width="521" alt=""></div>
 </figure>

```less
// Pic 3
.option {
    &__name {}
    &__descrition {}
    &__btn {}
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
    &__subline {}
    &__text {}
    &__text--attention {}
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
    &__note {}
    &__note--attention {}
    &__disclaimer-message {}
}
.index {
    &__count {}
    &__description {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 6</figcaption>
    <div><img src="img/06.png" height="522" width="1094" alt=""></div>
 </figure>

```less
// Pic 6
.product {
    &__title {}
    &__subline {}
    &__description {}
}
.btn-details {
    &__text {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 7</figcaption>
    <div><img src="img/07.png" height="117" width="1176" alt=""></div>
 </figure>

```less
// Pic 7
.tab-panel {
    &__tab {}
    &__tab--trash {}
    &__tab--search {}
    &__tab--settings {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 8</figcaption>
    <div><img src="img/08.png" height="338" width="415" alt=""></div>
 </figure>

```less
// Pic 8
.contacts {
    &__title {}
    &__address {}
    &__phone {}
}
.estimate {
    &__star {}
    &__star--filled {}
    &__estimate {}
    &__like {}
    &__like--selected {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 9</figcaption>
    <div><img src="img/09.png" height="514" width="414" alt=""></div>
 </figure>

```less
// Pic 9
.rate {
    &__title {}
    &__subline {}
    &__cost {}
    &__period {}
    &__btn {}
}
.rate-option {
    &__status {}
    &__label {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 10</figcaption>
    <div><img src="img/10.png" height="511" width="749" alt=""></div>
 </figure>

```less
// Pic 10
.reviews-panel {
    &__title {}
    &__subline {}
    &__count {}
}
.review {
    &__rate {}
    &__rate--filled {}
    &__user {}
    &__date {}
    &__subline {}
}
.review-details {
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
.product {
    &__image {}
    &__title {}
    &__subline {}
    &__breadcrumb {}
    &__btn-navigate {}
    &__price {}
    &__rate {}
    &__rate--filled {}
    &__reviews {}
    &__description {}
    &__quality {}
    &__btn-submit {}
    &__btn-bookmark {}
    &__detail {}
}
.counter {
    &__btn {}
    &__text {}
}
.social {
    &__title {}
    &__item {}
}
```
<hr> <br>
