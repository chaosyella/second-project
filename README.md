# project "how-to-learn" by yella
## description
this is a website made up with **css** and **html**. it contains _useful information about studying and different tecniques to make it easier_.
## functionality
creating website helped to improve these skills:
* **BEM-methodology**
* using **object-fit** and **object-position** in image's position
* changing **properties of position** for z-index and other properties
* **flexbox** layout
* **semantic's tags** for different blocks
## technologies
* **animations**
```css
@keyframes rotation {
    from {
        transform: rotate(0);
    }
    to {
        transform: rotate(360deg);
    }
}

.rotation {
    animation: rotation 20s linear infinite;
}
```
* **transition**
```css
.resources__link {
    opacity: .7;
    transition: opacity .5s ease-in;
}
```
* **iframes**
```html
<iframe class="video__iframe" id="ytplayer" type="text/html" width="515" height="316" 
src="https://www.youtube.com/embed/arj7oStGLkU?hl=ru&modestbranding=1"
frameborder="0" allowfullscreen></iframe>
```
* **lists**
```html
<ul class="cards">
                <li class="cards__item">
                    <img class="cards__image" src="images/cards-attention.png" alt="attention">
                    <h3 class="cards__title">Два вида внимания</h3>
                    <p class="cards__description">Глубокие знания возникают, если чередовать сфокусированное 
                        и рассеянное мышление.</p>
                </li>
```
* **nested type of structure**
```css
@import url(../blocks/header/header.css);
@import url(../blocks/logo/logo.css);
@import url(../blocks/logo/_place/logo_place_header.css);
``` 
