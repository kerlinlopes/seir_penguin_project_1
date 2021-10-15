# Project 1 
## by Kerlin


## Introduction

Scream themed Trivia Game

## Technologies Used

- HTML
- CSS
- JS
- jQuery

## Journey

#### I had fun with

Adding animations

```js
/* flickering animation */
  animation-duration: 1.5s;
  animation-iteration-count: infinite;
  animation-name: flickering;
```
```js
/* shake animation */
  animation-duration: 0.82s;
  animation-iteration-count: infinite;
  animation-name: shake;
  transform: translate3d(0, 0, 0);
  ```
 ```translate3d()``` repositions an element in 3D space.```
  ```js
  /* glitch animation */
  animation-duration: 2.5s;
  animation-iteration-count: infinite;
  animation-name: glitch;
  animation-timing-function: step-start;
  ```
```animation-timing-function:```Defines how the values between the start and the end of the animation are calculated.
```step-start``` value made it jump instantly to its final state
```js
/* fadeIn animation */
animation-name: fadeIn;
animation-duration: 5s;
animation-iteration-count: infinite;
```

#### Things I changed
```js
// const randomQuestion = q[randomIndex];
  const randomQuestion = q.splice(randomIndex, 1)[0]
```
I didn't want the questions to repeat so I used the ```splice()``` method.

### I had trouble with
Deciding what background image would fit the theme and sizing it to fit the browser.
```js
body {
  /* background-image: url("https://wallpaperaccess.com/full/162342.jpg"); */
  /* background-image: url("https://i.pinimg.com/originals/40/38/81/4038814f753e6fe214a3b53f2262dab0.jpg"); */
  background-image: url("https://i.pinimg.com/originals/a6/2e/c7/a62ec7093f912a1df885fcf4d9218b58.jpg");
  background-repeat: no-repeat;
  background-size: cover;
}
```