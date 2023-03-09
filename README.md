# Creative Sliders


Good multiple scrolling in different directions is great for a portfolio 


>The limitations of [Swiper.js](https://swiperjs.com) depend only on your mind


## Should note

- **Slider setup**

```javascript
new Swiper(n, {
    freeMode: true,
    centeredSlides: true,
    direction: "vertical",
    mousewheel: true,
    slidesPerView: 1.75,
    slidesOffsetBefore: -125,
  });
```
>Use the bindSwiper add-on to make sure that the four sliders work correctly

```javascript
bindSwipers(slider1, slider2, slider3, slider4)
```

- **Stylized tilt**

```css
.slider {
  transform: rotate(12.5deg);
}
.slider:nth-child(odd) {
  transform: rotate(192.5deg);
}
```

>Don't forget to flip the images

```css
.slider:nth-child(odd) .slider__img {
  transform: rotate(-180deg);
}
```

## Screenshot

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/113831614/224044998-d128fae0-b093-4507-a2c5-46cbb6c68013.gif)

