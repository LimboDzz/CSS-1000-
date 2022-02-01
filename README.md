# 1000+ CSS Practices from [HTML CSS Tutorial For Beginners](https://www.youtube.com/playlist?list=PL5e68lK9hEzdYG6YQZCHtM9gon_cDNQMh)

## 1 Simple Parallax Scrolling Effect
* object-fit
* blend-mode
* window.onscroll
* window.scrollX/Y
* z-index tricks
* linear-gradient(to top/right/bottom/left, start-color, stop-color)
* elem.style.trbl to move along scrolling

## 2 Fullscreen Video Background
* elem.firstchild vs firstElementChild
* #t=[starttime][,endtime]
* autoplay/muted/loop
* type="video/mp4"
* mix-blend-mode: soft-light;

## 3 CSS3 Transform Effects on Scroll
* transform-origin: top;
* white-space: nowrap;

## 4 Fullscreen Overlay Responsive Navigation Menu
* transition: 0.7s transform;

## 5 CSS3 Creative Check List
```css
input[type=checkbox] {
    appearance: none;
}
.list input[type=checkbox]:checked ~ i {}
.list input[type=checkbox]:checked ~ span {}
.list input[type=checkbox]:checked ~ span::before {}
```

## 6 Moving Car Using CSS Animation Effects
* background-size: cover;
* background-position-y: bottom;
* background-repeat: no-repeat;
* height: 15vmin;
* width: 30vmin;
```css
@keyframes animate{
    from {
        background-position: 0 0;
    }
    to {
        background-position: calc(100% - 100vw) 0;
    }
}
```

## 7 CSS Reverse Direction Hover Effects
* 

## 8 Align Text Center Vertical and Horizontal
* 