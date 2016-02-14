---
layout: post
title: Using CSS3 Background Animation
---
This article is written by Radwa Gamal @ 15th Dec 2015 CSS 

## How to write animation code ?

1. Begins with : @keyframes Anim-Name {}.

2. For chrome browser we add “-webkit-“ : @-webkit-keyframes Anim-Name {} .

3. The best thing about animation is that you can control it easily by using percentages. For example :

```
@keyframes cat {
    20%: //do this
    70% : //do this
    100% : //do this
}
```

Means that the animation called “ cat “ after 20% of time it will do some code, after 70% of time it will do another code, and finally when it reaches 100% it will some other code.

4. For now your animation code is ready, but the question is how to use this code now ? By the animation property is CSS.

Property > animation : Anim-Name Anim-Duration Anim-Timing-Fun Anim-Delay

Sub properties of animation property : ( Via Css-Tricks )

## Example:

1. HTML File : write a div and give it a class called “ bg “.

```
<body>
   <div class="bg"></bg>
</body>
```

2. CSS File : First let’s start with the keyframes, we want in this example to change the background color of the screen in different times. So we start by defining the animation and give it a name called “bg-change” like the picture below.

```
@-webkit-keyframes bg-change {
  0% { background-color: black; }
  50% { background-color: red; }
  100% { background-color: yellow; }
}

@keyframes bg-change {
  0% { background-color: black; }
  50% { background-color: red; }
  100% { background-color: yellow; }
}
```

Here we used the same keyframe but the first one with the chrome browser prefix “-webkit-”.

The code means that at the beginning of the animation (0%) the background color is black, then in the middle of the animation (50%) we change the background color to red, and finally at the end (100%) we change again the background color to yellow.

3. Finally to run the code we add the animation property in our “bg” class.

```
.bg {
  width: 100%;
  height: 100%;

  -webkit-animation: bg-change 3s infinite;
  animation: bg-change 3s infinite;
}
```

3s : is the duration of the whole animation, u can change this number as you wish.

infinite : means that this animation should keep going infinitely.

4. In other examples you could use any of the sub properties as you can.

5. Run the code and enjoy your first animation tutorial. Good Luck!