# javascript-winwheel
Create spinning prize wheels on HTML canvas with Winwheel.js

## Description
Winwheel.js is a feature packed JavaScript library that allows you to easily create HTML5 canvas Winning / Prize Wheels, Pie graphs and other things using a highly configurable JavaScript class.

Wheels can be animated using GreenSock's Animation Platform (TweenMax.js) which contain easing functions and many other powerful animation features.

Winwheel.js Features Include:
* Easy to use, highly configurable JavaScript classes.
* Draw wheels using code generated segments or graphically rich images.
* Responsive features so wheels display correctly on different sized devices.
* Numerous text orientation, direction, size and colour options.
* Random or Pre-calculated prize stopping location.
* Play sounds while the wheel is spinning including a "tick" sound.
* Ability to get the segment the user clicked upon.
* Fully commented source code. Plenty of tutorials and other documentation.
* Winwheel.js is free to use with an open source license.

## Example
```javascript
let theWheel = new Winwheel({
    'numSegments'    : 4,
    'segments'       :
    [
        {'fillStyle' : '#eae56f', 'text' : 'Prize One'},
        {'fillStyle' : '#89f26e', 'text' : 'Prize Two'},
        {'fillStyle' : '#7de6ef', 'text' : 'Prize Three'},
        {'fillStyle' : '#e7706f', 'text' : 'Prize Four'}
    ],
    'animation' :
    {
        'type'     : 'spinToStop',
        'duration' : 5,
        'spins'    : 8
    }
});
```

## More examples
See the /examples folder for examples of some of the types of things you can create with Winwheel.js, to see these examples in action please visit the examples section on my website http://dougtesting.net/winwheel/examples

## Tutorials and other documentation
Please visit http://dougtesting.net/winwheel/docs to see a complete set of tutorials on how to use Winwheel.js as well as other documentation such as class references.

## Maintainer
Douglas McKechie https://github.com/zarocknz

## Please note
I am not planning to do any further work on this library as my day job keeps me very busy and after 7 years of Winwheel I would rather spend
any spare time I do have for personal coding on other projects.

So this means if you would like a version of Winwheel.js for your current JavaScript framework of choice its up to you or others in the community
to create it. If you create one perhaps open an Issue with the details so others can find and use it. Thanks.

You are welcome to ask questions using the Issues feature of Github, but please don't be offended if I take quite a long time to respond to them. To be honest its probably quicker to ask the Stackoverflow community for help https://stackoverflow.com/search?tab=newest&q=Winwheel
