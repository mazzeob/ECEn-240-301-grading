Go to [How to Grade in Learning Suite.md](/resources/How-to-Grade-in-Learning-Suite.md) to see how to get to the grader and begin grading. 

Note: "-3" means subtract three points.

# Lab 3:

```3. Why is it important to have a power switch on the robot? (3 points)```

If they have something about saving battery power from being drained or not needing to physically take the battery in and out as an answer, then give full points.
- -3 if the answer doesn’t make sense

```4. What happens when you plug a voltage greater than 5.5V into the wrong Arduino pin? (3 points)```

Say something about breaking the Arduino, frying the pin, or the computer.
- -3 if the answer doesn’t make sense

```5. Why is it important that the H-bridge heatsink be unobstructed? (3 points)```

They need to say something about it overheating or being damaged.
- -3 if they obviously don’t know what an H-bridge is.

```6. Upload your robot computer code here. (25 points)```
- 0 if they don't submit any code. Send them an email or message requesting it.
  - -5 if they send the code. 
- -5 if they didn’t change the LED_2s and LED_4s to ENABLE A and B. (Most students used H_BRIDGE_ENA and H_BRIDGE_ENB)
  - (Note) Still give them the points if they use a different variable name that shows they aren't using LEDs anymore. 
- -10 points if the code obviously doesn’t work.
- <240 only> -5 if no battery monitor .

(NOTE) If their code isn’t the skeleton code, still give points if it appears that the code functions. 
Just leave a note that we strongly suggest that they use the skeleton code.

```7. Paste a link to your video below:```

- 0 points if you can’t see the video. Add the comment:
  > Your video is not public. Please email me (insert TA email here) with a new link to the video and I will grade it. (With a -3 point deduction).
  - -3 points if they resend the video.
- 0 points if you can't see their name on the breadboard. Add the comment:
  > Your video does not have a name on the breadboard. Please email me (insert TA email here) with a new link a new video and I will grade it. (With a -3 point deduction).
  - -3 points if they send a new video, although if the original video would have had a lower score then give them that score. 
##### Video Rubric:
This video should show the name on the breadboard.
- -3 points per each of the combinations listed below: (note: they do not need their wheels on for this)
  - driving left
  - driving right
  - driving straight
  - collision interrupts driving.
- -3 points if no talking explanation (like explaining what buttons they’re pressing)
- -3 points mentioned above for having to request permission for the video. 
- (240) -5 points if the battery monitor doesn’t work as expected. 
  (Some students ran their power supply through the h-bridge, which may make the LED’s dimmer. It just has to clearly show switching up and down with the power supply.

```8. <240 Only>. Upload your lab report here (PDF only!).```

For 301: Give them the same points here as you gave them for Question 10.

For 240: Use the rubric on Learning Suite to assess the quality of the lab report. 

- Note: Most 240 lab reports should get full points as long as they put in effort, it looks professional, and they included most of or all the diagrams. 
- -3 if no picture of completed robot
- -3 if no Thevenin and Norton equivalent values (voltage and resistance, and current) for 9V Battery (can be pictures or just measurements)
- -3 if no Thevenin equivalent values of two 9 volt batteries in Series and Parallel  (can be pictures or just measurements)
- -3 if no description/figure/table of measurements characterizing your battery monitor
- -3 if no average voltage and current through the motor while running (I think this is usually in the 100-200 mA range) (if neither just take off 3 still)
- -3 if no battery power calculation (the one using the spreadsheet) and it changed values after it opened, so we’re not grading the value of power they get, just that they did it)
- -3 if not professional (this has to be really bad to take this off).
- -3 if not a PDF

```9. In what ways could this lab be improved?```

This usually grades automatically, but people often put “nothing” or something of the sort. Please check this and make sure it is right.  
- -1 point if they do not answer it with some real feedback.
