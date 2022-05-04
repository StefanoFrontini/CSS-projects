# CSS projects
## 07-bcg-images
Background images and linear gradient:
```css
.hero{
    background: linear-gradient(to right, rgba(105,62,27,0.3), rgba(105,62,27,1)), url("./hero-bcg.jpg") center/cover no-repeat fixed;
}
```
## 08-position-property
position: static - default, always positioned according to the normal flow

position: relative - position relative to it's normal position. top, bottom, left, right. Not placing any other elements in its place

position: absolute - relative to the parent with position:relative. will use other content to fill out the space

position: fixed - relative to viewport, stays as we are scrolling. will use other content to fill out the space

position: sticky - toggles between relative and fixed once the position is met in the viewport - then it sticks

z-index works with position: absolute

images:
```css
div {
    width: 70vw;
    margin: 100px auto;
}
img {
    width: 100%;
    display: block;
}
```
hovering over pseudo-elements:
```css
div:hover::after{
    top: 0;
    left: 0;
}
```

covering elements with position: absolute

```css
.special h1 {
    position: absolute;
    /* top: 0;
    left: 0;
    right: 0;
    bottom: 0; */
    inset: 0;
}
```
## 09-animation-property
```css
.hero-text{
    animation: moveDown 3s ease-in-out;

}
@keyframes moveDown {
    0% {
        opacity: 0;
        transform: translateY(-10rem);
    }
    100% {
        opacity: 1;
    }
}
```


## 10-cards-project

Images styling:

```css
.img {
  width: 100%;
  display: block;
  object-fit: cover;
}
```
