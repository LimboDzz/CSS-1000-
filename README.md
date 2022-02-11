# 1000+ CSS Practices from [HTML CSS Tutorial For Beginners](https://www.youtube.com/playlist?list=PL5e68lK9hEzdYG6YQZCHtM9gon_cDNQMh)

## 1 Simple Parallax Scrolling Effect

- object-fit
- blend-mode
- window.onscroll
- window.scrollX/Y
- z-index tricks
- linear-gradient(to top/right/bottom/left, start-color, stop-color)
- elem.style.trbl to move along scrolling

## 2 Fullscreen Video Background

- elem.firstchild vs firstElementChild
- #t=[starttime][,endtime]
- autoplay/muted/loop
- type="video/mp4"
- mix-blend-mode: soft-light;

## 3 CSS3 Transform Effects on Scroll

- transform-origin: top;
- white-space: nowrap;

## 4 Fullscreen Overlay Responsive Navigation Menu

- transition: 0.7s transform;

## 5 CSS3 Creative Check List

```css
input[type="checkbox"] {
  appearance: none;
}
.list input[type="checkbox"]:checked ~ i {
}
.list input[type="checkbox"]:checked ~ span {
}
.list input[type="checkbox"]:checked ~ span::before {
}
```

## 6 Moving Car Using CSS Animation Effects

- background-size: cover;
- background-position-y: bottom;
- background-repeat: no-repeat;
- height: 15vmin;
- width: 30vmin;

```css
@keyframes animate {
  from {
    background-position: 0 0;
  }
  to {
    background-position: calc(100% - 100vw) 0;
  }
}
```

## 7 CSS Reverse Direction Hover Effects

```js
lis.forEach((li, idx) => {
  li.style.setProperty("--hue", idx * 70);
});
```

## 8 Align Text Center Vertical and Horizontal

```css
outer {
  display: table;
}
innerText {
  display: table-cell;
  vertical-align: middle;
  text-align: center;
}
```

## 9 ZigZag Div Shape

## 10 css Icon Hover Effect

- mix-blend-mode: exclusion;

## 11 Glass Text Effects

- mix-blend-mode: overlay;

## 12 Split Image On Hover

- background-size: 200% 100%;
- transform: rotateX(90deg);

## 13 Pure CSS Neon Light Text Effects

```html
<h1 class="neon" data-text="[Neon_]">[Neon_]</h1>
```

```css
background: url("brick.jpeg") no-repeat center center;
background-color: rgb(28, 28, 29);
background-blend-mode: multiply;
```
## 22 CSS Loader Animation
- animation pertaining to transform will interfere with the transform:translate(-50%,-50%) set to center your elem.

## 23 Css Scrolling Effect
```css
/* Keyword values */
background-attachment: scroll;
background-attachment: fixed;
background-attachment: local;
```