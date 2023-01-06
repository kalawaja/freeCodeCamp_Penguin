# freeCodeCamp_Penguin
 In this course, you'll build a penguin. You'll use CSS transforms to position and resize the parts of your penguin, create a background, and animate your work.

```html
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Penguin</title>
    <link rel="stylesheet" href="./styles.css">
  </head>
  <body></body>
</html>
```

```css
body {
  background: linear-gradient(45deg, rgb(118, 201, 255), rgb(247, 255, 222));
}
```

```css
body {
  background: linear-gradient(45deg, rgb(118, 201, 255), rgb(247, 255, 222));
  margin: 0;
  padding: 0;
}
```

```css
body {
  background: linear-gradient(45deg, rgb(118, 201, 255), rgb(247, 255, 222));
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100vh;
}
```

```css
body {
  background: linear-gradient(45deg, rgb(118, 201, 255), rgb(247, 255, 222));
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100vh;
  overflow: hidden;
}
```

```html
  <body>
    <div class="ground"></div>
  </body>
```

```css
.ground {
  width: 100vw;
  height: 400px;
}
```

```css
.ground {
  width: 100vw;
  height: 400px;
  background: linear-gradient(90deg, rgb(88, 175, 236), rgb(182, 255, 255));
}
```

```css
.ground {
  width: 100vw;
  height: 400px;
  background: linear-gradient(90deg, rgb(88, 175, 236), rgb(182, 255, 255));
  z-index: 3;
  position: absolute;
}
```

```html
  <body>
    <div class="penguin">Flappy Penguin</div>
    <div class="ground"></div>
  </body>
```

```css
.penguin {
  width: 300px;
  height: 300px;
}
```

```css
.penguin {
  width: 300px;
  height: 300px;
  margin: auto;
  margin-top: 75px;
}
```

```css
  <body>
    <div class="left-mountain"></div>
    <div class="penguin"></div>
    <div class="ground"></div>
  </body>
```

```css
.left-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(80, 183, 255));
}
```

```css
.left-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(80, 183, 255));
  position: absolute;
}
```

```css
.left-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(80, 183, 255));
  position: absolute;
  transform: skew(0deg, 44deg);
}
```

```css
.left-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(80, 183, 255));
  position: absolute;
  transform: skew(0deg, 44deg);
  z-index: 2;
}
```

```css
.left-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(80, 183, 255));
  position: absolute;
  transform: skew(0deg, 44deg);
  z-index: 2;
  margin-top: 100px;
}

.penguin {
  width: 300px;
  height: 300px;
  margin: auto;
  margin-top: 75px;
}

.ground {
  width: 100vw;
  height: 400px;
  background: linear-gradient(90deg, rgb(88, 175, 236), rgb(182, 255, 255));
  z-index: 3;
  position: absolute;
  margin-top: -58px;
}
```

```html
  <body>
    <div class="left-mountain"></div>
    <div class="back-mountain"></div>
    <div class="penguin"></div>
    <div class="ground"></div>
  </body>
```

```css
.back-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(47, 170, 255));
}
```

```css
.back-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(47, 170, 255));
  position: absolute;
}
```

```css
.back-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(47, 170, 255));
  position: absolute;
  z-index: 1;
}
```

```css
.back-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(47, 170, 255));
  position: absolute;
  z-index: 1;
  transform: rotate(45deg);
  left: 110px;
  top: 225px;
}
```

```html
  <body>
    <div class="left-mountain"></div>
    <div class="back-mountain"></div>
    <div class="sun"></div>
    <div class="penguin"></div>
    <div class="ground"></div>
  </body>
```

```css
.sun {
  width: 200px;
  height: 200px;
  background-color: yellow;
}
```

```css
.sun {
  width: 200px;
  height: 200px;
  background-color: yellow;
  position: absolute;
  border-radius: 50%;
}
```

```css
.sun {
  width: 200px;
  height: 200px;
  background-color: yellow;
  position: absolute;
  border-radius: 50%;
  top: -75px;
  right: -75px;
}
```

```html
    <div class="penguin">
      <div class="penguin-head"></div>
      <div class="penguin-body"></div>
    </div>
```

```css
.penguin {
  width: 300px;
  height: 300px;
  margin: auto;
  margin-top: 75px;
  position: relative;
  z-index: 4;
}
```

```css
.penguin-head {
  width: 50%;
  height: 45%;
  background: linear-gradient(45deg, gray, rgb(239, 240, 228));
}
```

```css
.penguin-head {
  width: 50%;
  height: 45%;
  background: linear-gradient(
    45deg,
    gray,
    rgb(239, 240, 228)
  );
  border-radius: 70% 70% 65% 65%;
}
```

```css
.penguin-body {
  width: 53%;
  height: 45%;
  background: linear-gradient(
    45deg, 
    rgb(134, 133, 133) 0%, 
    rgb(234, 231, 231) 25%, 
    white 67%);
}
```

```css
.penguin-body {
  width: 53%;
  height: 45%;
  background: linear-gradient(
    45deg,
    rgb(134, 133, 133) 0%,
    rgb(234, 231, 231) 25%,
    white 67%
  );
  border-radius: 80% 80% 100% 100%;
}
```

```css
.penguin * {
  position: absolute;
}
```

```css
.penguin-head {
  width: 50%;
  height: 45%;
  background: linear-gradient(
    45deg,
    gray,
    rgb(239, 240, 228)
  );
  border-radius: 70% 70% 65% 65%;
  top: 10%;
  left: 25%;
}
```

```css
.penguin-body {
  width: 53%;
  height: 45%;
  background: linear-gradient(
    45deg,
    rgb(134, 133, 133) 0%,
    rgb(234, 231, 231) 25%,
    white 67%
  );
  border-radius: 80% 80% 100% 100%;
  top: 40%;
  left: 23.5%;
}
```

```css
.penguin-head {
  width: 50%;
  height: 45%;
  background: linear-gradient(
    45deg,
    gray,
    rgb(239, 240, 228)
  );
  border-radius: 70% 70% 65% 65%;
  top: 10%;
  left: 25%;
  z-index: 1;
}
```

```css
.penguin-body::before {
  content: "";
}
```

```css
.penguin-body::before {
  content: "";
  position: absolute;
}
```

```css
.penguin-body::before {
  content: "";
  position: absolute;
  width: 50%;
  height: 45%;
  background-color: gray;
}
```

```css
.penguin-body::before {
  content: "";
  position: absolute;
  width: 50%;
  height: 45%;
  background-color: gray;
  top: 10%;
  left: 25%;
}
```

```css
.penguin-body::before {
  content: "";
  position: absolute;
  width: 50%;
  height: 45%;
  background-color: gray;
  top: 10%;
  left: 25%;
  border-radius: 0% 0% 100% 100%;
}
```

```css
.penguin-body::before {
  content: "";
  position: absolute;
  width: 50%;
  height: 45%;
  background-color: gray;
  top: 10%;
  left: 25%;
  border-radius: 0% 0% 100% 100%;
  opacity: 70%;
}
```

```html
      <div class="penguin-head">
        <div class="face"></div>
        <div class="face"></div>
      </div>
```

```css
.face {
  width: 60%;
  height: 70%;
  background-color: white;
}
```

```css
.face {
  width: 60%;
  height: 70%;
  background-color: white;
  border-radius: 70% 70% 60% 60%;
}
```

```css
.face {
  width: 60%;
  height: 70%;
  background-color: white;
  border-radius: 70% 70% 60% 60%;
  top: 15%; 
}
```

```html
      <div class="penguin-head">
        <div class="face left"></div>
        <div class="face right"></div>
      </div>
```

```css
.face.left {
  left: 5%;
}
```

```css
.face.left {
  left: 5%;
}

.face.right {
  right: 5%;
}
```

```html
      <div class="penguin-head">
        <div class="face left"></div>
        <div class="face right"></div>
        <div class="chin"></div>
      </div>
```

```css
.chin {
  width: 90%;
  height: 70%;
  background-color: white;
}
```

```css
.chin {
  width: 90%;
  height: 70%;
  background-color: white;
  top: 25%;
  left: 5%;
  border-radius: 70% 70% 100% 100%;
}
```

```css
:root {
  --penguin-face: white;
}
```

```css
:root {
  --penguin-face: white;
}

body {
  background: linear-gradient(45deg, rgb(118, 201, 255), rgb(247, 255, 222));
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100vh;
  overflow: hidden;
}

.left-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(80, 183, 255));
  position: absolute;
  transform: skew(0deg, 44deg);
  z-index: 2;
  margin-top: 100px;
}

.back-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(47, 170, 255));
  position: absolute;
  z-index: 1;
  transform: rotate(45deg);
  left: 110px;
  top: 225px;
}

.sun {
  width: 200px;
  height: 200px;
  background-color: yellow;
  position: absolute;
  border-radius: 50%;
  top: -75px;
  right: -75px;
}

.penguin {
  width: 300px;
  height: 300px;
  margin: auto;
  margin-top: 75px;
  z-index: 4;
  position: relative;
}

.penguin * {
  position: absolute;
}

.penguin-head {
  width: 50%;
  height: 45%;
  background: linear-gradient(
    45deg,
    gray,
    rgb(239, 240, 228)
  );
  border-radius: 70% 70% 65% 65%;
  top: 10%;
  left: 25%;
  z-index: 1;
}

.face {
  width: 60%;
  height: 70%;
  background-color: var(--penguin-face);
  border-radius: 70% 70% 60% 60%;
  top: 15%;
}

.face.left {
  left: 5%;
}

.face.right {
  right: 5%;
}

.chin {
  width: 90%;
  height: 70%;
  background-color: var(--penguin-face);
  top: 25%;
  left: 5%;
  border-radius: 70% 70% 100% 100%;
}

.penguin-body {
  width: 53%;
  height: 45%;
  background: linear-gradient(
    45deg,
    rgb(134, 133, 133) 0%,
    rgb(234, 231, 231) 25%,
    white 67%
  );
  border-radius: 80% 80% 100% 100%;
  top: 40%;
  left: 23.5%;
}

.penguin-body::before {
  content: "";
  position: absolute;
  width: 50%;
  height: 45%;
  background-color: gray;
  top: 10%;
  left: 25%;
  border-radius: 0% 0% 100% 100%;
  opacity: 70%;
}

.ground {
  width: 100vw;
  height: 400px;
  background: linear-gradient(90deg, rgb(88, 175, 236), rgb(182, 255, 255));
  z-index: 3;
  position: absolute;
  margin-top: -58px;
}
```

```html
      <div class="penguin-head">
        <div class="face left"></div>
        <div class="face right"></div>
        <div class="chin"></div>
        <div class="eye left"></div>
        <div class="eye right"></div>
      </div>
```

```css
.eye {
  width: 15%;
  height: 17%;
  background-color: black;
}
```

```css
.eye {
  width: 15%;
  height: 17%;
  background-color: black;
  top: 45%;
  border-radius: 50%;
}
```

```css
.eye.left {
  left: 25%;
}

.eye.right {
  right: 25%;
}
```

```html
      <div class="penguin-head">
        <div class="face left"></div>
        <div class="face right"></div>
        <div class="chin"></div>
        <div class="eye left">
          <div class="eye-lid"></div>
        </div>
        <div class="eye right">
          <div class="eye-lid"></div>
        </div>
      </div>
```

```css
.eye-lid {
  width: 150%;
  height: 100%;
  background-color: var(--penguin-face);
}
```

```css
.eye-lid {
  width: 150%;
  height: 100%;
  background-color: var(--penguin-face);
  top: 25%;
  left: -23%;
  border-radius: 50%;
}
```

```html
        <div class="blush left"></div>
        <div class="blush right"></div>
```

```css
.blush {
  width: 15%;
  height: 10%;
  background-color: pink;
}
```

```css
.blush {
  width: 15%;
  height: 10%;
  background-color: pink;
  top: 65%;
  border-radius: 50%;
}
```

```css
.blush.left {
  left: 15%;
}

.blush.right {
  right: 15%;
}
```

```html
        <div class="beak top"></div>
        <div class="beak bottom"></div>   
```

```css
.beak {
  height: 10%;
  background-color: orange;
  border-radius: 50%;
}
```

```css
.beak.top {
  width: 20%;
  top: 60%;
  left: 40%;
}
```

```css
.beak.top {
  width: 20%;
  top: 60%;
  left: 40%;
}

.beak.bottom {
  width: 16%;
  top: 65%;
  left: 42%;
}
```

```html
      <div class="shirt"></div>
```

```html
      <div class="shirt">
        <div>💜</div>
      </div>
```

```html
      <div class="shirt">
        <div>💜</div>
        <p>I CSS</p>
      </div>
```

```css
.shirt {
  font-size: 25px;
  font-family: Helvetica, sans-serif;
  font-weight: bold; 
}
```

```css
.shirt {
  font: bold 25px Helvetica, sans-serif;
}

.shirt div {
  font-weight: initial;
}
```

```css
.shirt {
  font: bold 25px Helvetica, sans-serif;
}

.shirt div {
  font-weight: initial;
  top: 22.5px;
  left: 12px;
}
```

```css
.shirt {
  font: bold 25px Helvetica, sans-serif;
  top: 165px;
  left: 127.5px;
  z-index: 1;
}

.shirt div {
  font-weight:  initial;
  top: 22.5px;
  left: 12px;
}
```

```css
.shirt {
  font: bold 25px Helvetica, sans-serif;
  top: 165px;
  left: 127.5px;
  z-index: 1;
  color: #6a6969;
}

.shirt div {
  font-weight:  initial;
  top: 22.5px;
  left: 12px;
}
```

```html
      <div class="penguin-body">
        <div class="foot left"></div>
        <div class="foot right"></div>
      </div>
```

```css
.foot {
  width: 15%;
  height: 30%;
  background-color: orange;
}
```

```css
.foot {
  width:  15%;
  height: 30%;
  background-color: orange;
  top: 85%;
  border-radius: 50%;
}
```

```css
:root {
  --penguin-face: white;
  --penguin-picorna: orange;
}

body {
  background: linear-gradient(45deg, rgb(118, 201, 255), rgb(247, 255, 222));
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100vh;
  overflow: hidden;
}

.left-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(80, 183, 255));
  position: absolute;
  transform: skew(0deg, 44deg);
  z-index: 2;
  margin-top: 100px;
}

.back-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(47, 170, 255));
  position: absolute;
  z-index: 1;
  transform: rotate(45deg);
  left: 110px;
  top: 225px;
}

.sun {
  width: 200px;
  height: 200px;
  background-color: yellow;
  position: absolute;
  border-radius: 50%;
  top: -75px;
  right: -75px;
}

.penguin {
  width: 300px;
  height: 300px;
  margin: auto;
  margin-top: 75px;
  z-index: 4;
  position: relative;
}

.penguin * {
  position: absolute;
}

.penguin-head {
  width: 50%;
  height: 45%;
  background: linear-gradient(
    45deg,
    gray,
    rgb(239, 240, 228)
  );
  border-radius: 70% 70% 65% 65%;
  top: 10%;
  left: 25%;
  z-index: 1;
}

.face {
  width: 60%;
  height: 70%;
  background-color: var(--penguin-face);
  border-radius: 70% 70% 60% 60%;
  top: 15%;
}

.face.left {
  left: 5%;
}

.face.right {
  right: 5%;
}

.chin {
  width: 90%;
  height: 70%;
  background-color: var(--penguin-face);
  top: 25%;
  left: 5%;
  border-radius: 70% 70% 100% 100%;
}

.eye {
  width: 15%;
  height: 17%;
  background-color: black;
  top: 45%;
  border-radius: 50%;
}

.eye.left {
  left: 25%;
}

.eye.right {
  right: 25%;
}

.eye-lid {
  width: 150%;
  height: 100%;
  background-color: var(--penguin-face);
  top: 25%;
  left: -23%;
  border-radius: 50%;
}

.blush {
  width: 15%;
  height: 10%;
  background-color: pink;
  top: 65%;
  border-radius: 50%;
}

.blush.left {
  left: 15%;
}

.blush.right {
  right: 15%;
}

.beak {
  height: 10%;
  background-color: var(--penguin-picorna);
  border-radius: 50%;
}

.beak.top {
  width: 20%;
  top: 60%;
  left: 40%;
}

.beak.bottom {
  width: 16%;
  top: 65%;
  left: 42%;
}

.shirt {
  font: bold 25px Helvetica, sans-serif;
  top: 165px;
  left: 127.5px;
  z-index: 1;
  color: #6a6969;
}

.shirt div {
  font-weight:  initial;
  top: 22.5px;
  left: 12px;
}

.penguin-body {
  width: 53%;
  height: 45%;
  background: linear-gradient(
    45deg,
    rgb(134, 133, 133) 0%,
    rgb(234, 231, 231) 25%,
    white 67%
  );
  border-radius: 80% 80% 100% 100%;
  top: 40%;
  left: 23.5%;
}

.penguin-body::before {
  content: "";
  position: absolute;
  width: 50%;
  height: 45%;
  background-color: gray;
  top: 10%;
  left: 25%;
  border-radius: 0% 0% 100% 100%;
  opacity: 70%;
}

.foot {
  width:  15%;
  height: 30%;
  background-color: var(--penguin-picorna);
  top: 85%;
  border-radius: 50%;
}
```

```css
.foot {
  width:  15%;
  height: 30%;
  background-color: var(--penguin-picorna);
  top: 85%;
  border-radius: 50%;
}

.foot.left {
  left: 25%;
}

.foot.right {
  right: 25%;
}
```

```css
.foot.left {
  left: 25%;
  transform: rotate(80deg);
}

.foot.right {
  right: 25%;
  transform: rotate(-80deg);
}
```

```css
.foot {
  width:  15%;
  height: 30%;
  background-color: var(--penguin-picorna);
  top: 85%;
  border-radius: 50%;
  z-index: -1;
}
```

```html
      <div class="penguin-body">
        <div class="arm left"></div>
        <div class="arm right"></div>
        <div class="foot left"></div>
        <div class="foot right"></div>
      </div>
```

```css
.arm {
  width: 30%;
  height: 60%;
  background: linear-gradient(90deg, gray, rgb(209, 210, 199));
}
```

```css
:root {
  --penguin-face: white;
  --penguin-picorna: orange;
  --penguin-skin: gray;
}

body {
  background: linear-gradient(45deg, rgb(118, 201, 255), rgb(247, 255, 222));
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100vh;
  overflow: hidden;
}

.left-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(80, 183, 255));
  position: absolute;
  transform: skew(0deg, 44deg);
  z-index: 2;
  margin-top: 100px;
}

.back-mountain {
  width: 300px;
  height: 300px;
  background: linear-gradient(rgb(203, 241, 228), rgb(47, 170, 255));
  position: absolute;
  z-index: 1;
  transform: rotate(45deg);
  left: 110px;
  top: 225px;
}

.sun {
  width: 200px;
  height: 200px;
  background-color: yellow;
  position: absolute;
  border-radius: 50%;
  top: -75px;
  right: -75px;
}

.penguin {
  width: 300px;
  height: 300px;
  margin: auto;
  margin-top: 75px;
  z-index: 4;
  position: relative;
}

.penguin * {
  position: absolute;
}

.penguin-head {
  width: 50%;
  height: 45%;
  background: linear-gradient(
    45deg,
    var(--penguin-skin),
    rgb(239, 240, 228)
  );
  border-radius: 70% 70% 65% 65%;
  top: 10%;
  left: 25%;
  z-index: 1;
}

.face {
  width: 60%;
  height: 70%;
  background-color: var(--penguin-face);
  border-radius: 70% 70% 60% 60%;
  top: 15%;
}

.face.left {
  left: 5%;
}

.face.right {
  right: 5%;
}

.chin {
  width: 90%;
  height: 70%;
  background-color: var(--penguin-face);
  top: 25%;
  left: 5%;
  border-radius: 70% 70% 100% 100%;
}

.eye {
  width: 15%;
  height: 17%;
  background-color: black;
  top: 45%;
  border-radius: 50%;
}

.eye.left {
  left: 25%;
}

.eye.right {
  right: 25%;
}

.eye-lid {
  width: 150%;
  height: 100%;
  background-color: var(--penguin-face);
  top: 25%;
  left: -23%;
  border-radius: 50%;
}

.blush {
  width: 15%;
  height: 10%;
  background-color: pink;
  top: 65%;
  border-radius: 50%;
}

.blush.left {
  left: 15%;
}

.blush.right {
  right: 15%;
}

.beak {
  height: 10%;
  background-color: var(--penguin-picorna);
  border-radius: 50%;
}

.beak.top {
  width: 20%;
  top: 60%;
  left: 40%;
}

.beak.bottom {
  width: 16%;
  top: 65%;
  left: 42%;
}

.shirt {
  font: bold 25px Helvetica, sans-serif;
  top: 165px;
  left: 127.5px;
  z-index: 1;
  color: #6a6969;
}

.shirt div {
  font-weight:  initial;
  top: 22.5px;
  left: 12px;
}

.penguin-body {
  width: 53%;
  height: 45%;
  background: linear-gradient(
    45deg,
    rgb(134, 133, 133) 0%,
    rgb(234, 231, 231) 25%,
    white 67%
  );
  border-radius: 80% 80% 100% 100%;
  top: 40%;
  left: 23.5%;
}

.penguin-body::before {
  content: "";
  position: absolute;
  width: 50%;
  height: 45%;
  background-color: var(--penguin-skin);
  top: 10%;
  left: 25%;
  border-radius: 0% 0% 100% 100%;
  opacity: 70%;
}

.arm {
  width: 30%;
  height: 60%;
  background: linear-gradient(
    90deg,
    var(--penguin-skin),
    rgb(209, 210, 199)
  );
}
```

```css
.arm.left {
  top: 35%;
  left: 5%;
}

.arm.right {
  top: 0%;
  right: -5%;
}
```

```css
.arm.left {
  top: 35%;
  left: 5%;
  transform-origin: top left;
}

.arm.right {
  top: 0%;
  right: -5%;
}
```

```css
.arm.left {
  top: 35%;
  left: 5%;
  transform-origin: top left; 
  transform: rotate(130deg) scaleX(-1);
}
```

```css
.arm.right {
  top: 0%;
  right: -5%;
  transform: rotate(-45deg);
}
```

```css
.arm {
  width: 30%;
  height: 60%;
  background: linear-gradient(
    90deg,
    var(--penguin-skin),
    rgb(209, 210, 199)
  );
  border-radius: 30% 30% 30% 120%;
}
```

```css
.arm {
  width: 30%;
  height: 60%;
  background: linear-gradient(
    90deg,
    var(--penguin-skin),
    rgb(209, 210, 199)
  );
  border-radius: 30% 30% 30% 120%;
  z-index: -1;
}
```

```css

```

```css

```

```css

```

```css

```

