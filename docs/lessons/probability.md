# charting lesson

Measure the acceleration on the micro:bit in the "z" direction.

## Topic

Acceleration

## Quick Links

* [activity](/lessons/charting/activity)


## Prior learning/place of lesson in scheme of work

Learn the functions of **on data received**, **send number** and **receive number** and chart `plot bar graph` for `acceleration` in the "x" dimension.

## Documentation

```cards
basic.showNumber(0)
input.acceleration(Dimension.X)
led.plotBarGraph(0, 1023)
radio.onDataReceived(() => {})
radio.sendNumber(0)
radio.receiveNumber()
```

## Objectives

* learn how to repeat code in the background forever
* learn how to get the acceleration value (g-force), in one of three specified dimensions
* learn how to display a vertical bar graph based on the value and high value.
* learn how to register code to run when a packet is received over radio
* learn how to broadcast a number data packet to other micro:bits connected via radio
* learn how to read the next radio packet as a number data packet