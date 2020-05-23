# VR Intro

**Agenda**

1. Hello
2. What is Virtual Reality?
3. What is A-Frame
4. The Basics of HTML
5. Hello WebVR
6. Hello Google Cardboard
7. Home Work


***


## Hello

I'm Solomon.  Who the heck are you?


***


## What is Virtual Reality

[![What is Virtual Reality](https://img.youtube.com/vi/HBNH8tzsfVM/0.jpg)](https://www.youtube.com/watch?v=HBNH8tzsfVM)


***


## What is A-Frame

* A web framework for building virtual reality experiences. 
* Was developed to be an easy but powerful way to develop VR content.
* Is based on top of HTML, making it simple to get started. 

[Demo](https://aframe.io/a-blast/)


***

## glitch.com

* Sign-in with GitHub
* Username: **refreshav-coders**
* Password: **valleycoders2018**


***


## Basics of HTML

Go to glitch.com.  Search for the _refresh-aframe_ project.  Let's edit it.

1. Element
  * Start / end tag
  * Possibly includes child content
2. Attributes
  * Modifier of an element
  * key="value"
3. Nested elements
  * Elements that contain elements
  


***


## Hello WebVR

![Hello WebVR](https://aframe.io/aframe-school/media/img/hellowebvr.jpg)

Let's talk about the 3d grid.

* Position defines the position in 3D space (```X,Y,Z```) - measured in meters
  * ```X``` = left-right
  * ```Y``` = up-down
  * ```Z``` = forward-back
* Rotation defines the orientation in 3D space (```X,Y,Z```) - measured in degrees
  * ```X``` = pitch
  * ```Y``` = yaw
  * ```Z``` = roll

***

Let's Code
![structure](https://ladieslearningcode.github.io/teenslc-vr-with-aframe/framework/img/workshop/aframe-primitives.jpg)

1. create ```a-scene```
2. add some primitives
  * ```a-sky```
    * Give it some ```color```
  * ```a-sphere```
    * Give it a ```position``` **X Y Z** eg `-1 0.5 -3`
    * Give it a ```radius```
    * Give it some ```color```
  * ```a-box```
    * Give it some ```color```
    * Give it a ```position```
    * Let's ```rotate``` it
  * ```a-cylinder```
    * Give it a ```radius```
    * Give it some ```height```
    * Give it some ```color```
    * Give it a ```position```
  * ```a-plane```
    * Give it some ```width```
    * Give it some ```height```
    * Give it some ```color```
    * Let's ```rotate``` it
    * Give it a ```position```
    

***


## Hello A-Frame Inspector

1. ```<ctrl> + <alt> + i```
2. Reposition a primitive
3. Rotate a primitive
4. Resize a primitive
5. Copy primitive back into your project


      
***

## Hello Images and Textures

* Add an equirectangular image to the background. [Find some here](https://www.flickr.com/search/?text=equirectangular&license=2%2C3%2C4%2C5%2C6%2C9)
  * ```a-sky``` set ```src``` to the URL of an image
* Add a texture. [Find some here](https://www.flickr.com/groups/freetextures/pool/)
  * ```a-sphere``` set ```src``` to URL of an image

***

## Hello Animation

We can use the `<a-animation>` primitive to animate entities within our scene. Nest it within the entity you want to animate (e.g. between the `<a-box>` opening and `</a-box>` closing tag)

```html
<a-box>
  <a-animation attribute="position" 
               to="-1 1.5 -3" 
               direction="alternate" 
               dur="2000" 
               repeat="indefinite"></a-animation>
</a-box>
```

* `Attribute` specifies which part we are animating (e.g. position, rotation, scale.. even material.color!)
* `To` is the value we are animating it to (e.g. 1 meter higher than the original position)
* `Direction` is the direction of the animation (between from and to)
* `Dur` is how long it takes (in milliseconds)
* `Repeat` is the amount of times this happens

See the [Animations documentation](https://aframe.io/docs/0.8.0/core/animations.html) for more options!


***


## Hello Google Cardboard

Let's check out our projects on glitch with some fasionable headwear.

      
***

## Home Work

* Do the [A-Frame School Tutorial](https://aframe.io/aframe-school/)
* Geek out with [Refresh Annapolis Valley](https://refreshannapolisvalley.org) and [Hoist](https://refreshannapolisvalley.org/project/hoist/) (our teen tech / entrepreneurship / design monthly meetup)
* Exam next Friday.