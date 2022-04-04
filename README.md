## Registration form  using Pure JS and CSS Animation

## Final prototype
![image](https://user-images.githubusercontent.com/73720786/161541803-99ff816e-4b64-4070-9f59-fbfd91fc8602.png)
![image](https://user-images.githubusercontent.com/73720786/161541902-0e738486-243e-412b-a602-8eca483763c2.png)

## Challenges:
- [X] Make the form appear, smoothly, when the page opens
- [X] Make the fields appear from left to right, smoothing the input and making them come in distinct motions
- [X] When you click on Login, make the form exit the screen by going down
- [X] Remove form from HTML and not show scrolling while form is exiting screen
- [X] Add a different timing effect to the form output
- [X] Make form say no-no (vibrate) if there are empty fields.
- [X] Create some animated squares (that keep rotating) and that come out from below the screen (out of the field of vision) and go to the top of the screen (that is out of the field of vision too). _Details_: It must have different sizes, come out at different times, have different timing, continuous animation.

8 properties:

animation-name: animationname; -- Animation name
animation-duration: 2s; -- Total animation time
animation-delay: 3s; -- Time the animation takes to start
animation-fill-mode: none; -- After or before the animation, what happens
animation-play-state: running; -- Will it be running or pause
animation-timing-function: ease; -- Animation progression (polka dot graphic)
animation-direction: reverse; -- Animation direction
animation-iteration-count: infinite;

To create an animation:

@keyframes animation-name{

    from{

    }
    to{

    }
}

Multiple animations on the same element
