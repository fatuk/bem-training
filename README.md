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
.info-block {
    &__img {}
    &__container {}
    &__description {}
    &__lastseendate {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 3</figcaption>
    <div><img src="img/03.png" height="125" width="521" alt=""></div>
 </figure>

```less
// Pic 3
.features-list {}
.feature-item {
  &__image {}
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
.page-header{
  &__title
  &__line
  &__description
}
```
<hr> <br>

<figure>
    <figcaption>Pic 5</figcaption>
    <div><img src="img/05.png" height="703" width="853" alt=""></div>
 </figure>

```less
// Pic 5
.portfolio-block{
  &__photo
  &__title
  &__line
  &__description 
}
.proof-list {}
.proof{
  &__numbers
  &__text
} 
```
<hr> <br>

<figure>
    <figcaption>Pic 6</figcaption>
    <div><img src="img/06.png" height="522" width="1094" alt=""></div>
 </figure>

```less
// Pic 6
.page{}
.phone{
   &__image
}
.page-details{
   &__title
   &_divider
   &_description
}

.btn{
  &__frame
  &__text
}
```
<hr> <br>

<figure>
    <figcaption>Pic 7</figcaption>
    <div><img src="img/07.png" height="117" width="1176" alt=""></div>
 </figure>

```less
// Pic 7
.menu{}
.menu-item{
   &__text
}
.menu-item{
   &__image
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
  &__bg-image
  &__title
  &__address
  &__phone
  &__number
}
.rating{
   &__star{}
   &__circle
   &__number
}

.love{}
```
<hr> <br>

<figure>
    <figcaption>Pic 9</figcaption>
    <div><img src="img/09.png" height="514" width="414" alt=""></div>
 </figure>

```less
// Pic 9
.package{
   &__title{}
   &__line{}
   &__price{}
   &__time{}
   &__features{}
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
.review-container{
    &__title{}
    &__divider{}
}

.review{
    &__title{}
    &__description
}

.info {
    &__rating{}
    &__title{}
    &__date{}
}

.star{
  &--selected{}
  &--unselected{}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 11</figcaption>
    <div><img src="img/11.png" height="619" width="941" alt=""></div>
 </figure>

```less
// Pic 11

.item-container{
  &__navigation-text{}
  &__title{}
  &__divider{}
  &__info{}
  &__description{}
  &__feature{}
  &__quantity{}
}

.add-to-cart{
  &__image{}
  &__title{}
}

.favorites{
  &__image{}
}

.share-list{
   &__text{}
}

.share-item{
  &__logo{}
  &__number{}
}
```
<hr> <br>
