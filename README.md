# millis()

Generally, we use the **delay()** function to establish time intervals in our code, which works for basic interactions, such as when making an LED Blink. However, the delay() function operates by halting our whole code, creating conflicts in more complex operations. 

In other words, delay() blocks the code until the time set has passed, it doesn’t allow other operations to run. Using millis(), the code keeps running while we check whether enough time has passed.

**Instead of delay(), we use millis()**

The millis() function will allow us to: 

- create a non-blocking "delay"
  
- create event schedulers

- multitask events 

---
### Definition

The millis() function returns the current time in milliseconds from when you powered up the board, in other words, it performs as a counting timer. This gives you a way of measuring time from within your program.

Reminder: 1 second = 1000 milliseconds

---
### Learning to use millis()

Follow the steps below gradually learn how to use millis() in your project

---
STEP 1: 
Count the number of milliseconds passed since the Arduino board started running the code.

[Tutorial 1](https://docs.arduino.cc/language-reference/en/functions/time/millis/)

---
STEP 2:
Using millis() for timing and delay

[Tutorial 2 (watch video)](https://www.programmingelectronics.com/arduino-sketch-with-millis-instead-of-delay/)

---
STEP 3: Use millis to make 2 LEDs blink at different intervals

[Tutorial 3](https://leecuriosity.com/blink-without-delay-smarter-led-control-with-arduino/)

---
ADVANCED:

[Multi-tasking the Arduino - Part 1 - By ADAFRUIT](https://learn.adafruit.com/multi-tasking-the-arduino-part-1/overview)

[Multi-tasking the Arduino - Part 2 - By ADAFRUIT](https://learn.adafruit.com/multi-tasking-the-arduino-part-2/overview)

[Multi-tasking the Arduino - Part 3 - By ADAFRUIT](https://learn.adafruit.com/multi-tasking-the-arduino-part-3/overview)

---
### Further Learning

Read more about millis() for multitasking with Arduino [here](https://circuitdigest.com/microcontroller-projects/arduino-multitasking-using-millis-in-arduino)

More about millis() [here](https://www.programmingelectronics.com/arduino-sketch-with-millis-instead-of-delay/)
