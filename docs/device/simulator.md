# Simulator

The JavaScript simulator allows you to test and execute most BBC micro:bit programs in the browser.
It allows you to emulate sensor data or user interactions.

```sim
input.onButtonPressed(Button.N, () => {
   basic.showString("North");
});
input.onButtonPressed(Button.S, () => {
   basic.showString("South");
});
input.onPinPressed(Button.E, () => {
   basic.showString("East");
});
input.onPinPressed(Button.W1, () => {
   basic.showString("West");
});

input.compass()
input.compassHeading()
input.lightLevel()
```
