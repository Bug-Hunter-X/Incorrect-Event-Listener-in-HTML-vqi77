# Incorrect Event Listener in HTML
This repository demonstrates a subtle error in using the `addEventListener` method in JavaScript within an HTML file.  The incorrect implementation can lead to unexpected behavior, such as the event listener not working as intended.

## Bug Description
The primary issue lies in the way the `addEventListener` method is called.  Instead of using it correctly with the event type and a function, the code mistakenly attempts to assign a function directly to `addEventListener`. This is incorrect syntax and causes the event listener to fail to register.

## Solution
The solution involves correctly using `addEventListener` with both the event type and the function to handle the event.  The updated code utilizes the correct syntax to attach the event listener successfully.

## How to reproduce
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Notice that no console log is registered when interacting with the div.
4. Open `bugSolution.html` and interact with the div.  The console log will be present indicating the event is correctly registered.
