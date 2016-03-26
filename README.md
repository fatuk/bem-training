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
    &__msg-container
	&__img {}	
	&__text {}
	&__time-since-created {}
}
```
<hr> <br>

<figure>
    <figcaption>Pic 3</figcaption>
    <div><img src="img/03.png" height="125" width="521" alt=""></div>
 </figure>

```less
// Pic 3
.feature-block {
    &__img {}
    &__img--responsive {}
    &__img--paralax {}
    &__img--size-control {}
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
.project-description {
    &__title {}
    &__delimiter {}
    &__img {}   
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
.personal-info {
    &__photo {}
    &__title {}
    &__amp-img {}
    &__delimiter {}
    &__text{}
    
    .experience-statistics{
        &__count {}
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
.project-feature {
    .linked-image {
        &__img {}
        &__link {}
    }
    
    &__title {}
    &__text{}
    &__btn{}    
}
```
<hr> <br>

<figure>
    <figcaption>Pic 7</figcaption>
    <div><img src="img/07.png" height="117" width="1176" alt=""></div>
 </figure>

```less
// Pic 7
.project-name {}
.menu {
    &__text-item {}
    &__img-item {}
    &__img-item--cart {}
    &__img-item--search {}
    &__img-item--burger {}
} 
```
<hr> <br>

<figure>
    <figcaption>Pic 8</figcaption>
    <div><img src="img/08.png" height="338" width="415" alt=""></div>
 </figure>

```less
// Pic 8
.company-info {
    .description{
        &__title{}
        &__text{}
        &__phone-icon{}
        &__phone{}
    }

    .rate{
        &__stars{}
        &__number{}
    }
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
.package {
    &__title{}
    &__delimiter{}
    &__price{}
    &__period{}
    &__text{}    
}
.check-mark{}
.btn{}
```
<hr> <br>

<figure>
    <figcaption>Pic 10</figcaption>
    <div><img src="img/10.png" height="511" width="749" alt=""></div>
 </figure>

```less
// Pic 10
.reviews {
    &__title{}
    .review{
        &__rate-wr
        &__rate
        &__author
        &__date-created
        &__text-wr
        &__title
        &__text        
    }
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
    &__pictur{}
    &__description-wr{
        .breadcrumbs{}
        .arrow-btn{
            &--left{}
            &--right{}
        }
        &__title{}
        &__price{}
        &__rate{}
        &__delimiter{}
        &__description{}
        &__features{}
        &__title{}
        .product-actions-wr{
            &__product-count{}
            &__add-to-cart{}
            &__wish-list{}
        }
        &__sku{}
        &__category{}
        &__tags{}
        .social-buttons-wr{
            &__social-button
            &--facebook
            &--twitter
            &--pinterest
        }
    }    
}
```
<hr> <br>
