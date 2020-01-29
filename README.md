This application will be a timer/stop watch using javascript.
* The program will display a Timer, an element on the screen that displays a number of seconds
* It should have a play button and a pause button
* Show an animated border around the timer
* Ability for user input 

* ...
Possible Implementation:
Event listener to watch for a click on 'start button'
Start counting down the timer
Each time the timer counts down, update the border
Each time the timer counts down, update the text
Handle what happens when the timer hits 0
Draw a full border around the timer
Reset the border
Reset internal timer to start again.

class Timer
constructor(durationInput, startButton, pauseButton)
start()
pause()
onDurationChange()
tick()
