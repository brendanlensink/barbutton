# barbutton
Sample project to show incoorect nav bar behaviour in iOS 11.2


To reproduce using iOS 11.2:
1. Press the left or right button
2. Press back button

What should happen: 
On returning to the main screen, the left and right buttons should be tinted blue

What happens:
The button pressed in step 1 will appear inactive, tinted grey. It is however still selectable. You can also restore the tint color by pressing down and swiping on the button.
