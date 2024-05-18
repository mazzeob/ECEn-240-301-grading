Got to [How to Grade in Learning Suite.md](/resources/How-to-Grade-in-Learning-Suite.md) to see how to get to the grader and begin grading. 

# Lab 2:

```1.) For your push button, did you use a pull-up or a pull-down resistor? Why did you choose this configuration, and what does it accomplish (i.e. what happens without it)? (5 points)```

Almost everyone chose pull-down.
- -2 points if they don’t correctly identify what their choice does. (e.g. saying they chose pull-up but their description of how it works is a pull down).
- -2 points if they don’t explain why they personally chose it.
- -1 points if what they say they chose doesn’t match their video.

```2) How have you set up your FSMs so that the up and down sensor can move independently from the right and left wheels (LEDs)? (5 points)```
- -2.5 points if they don’t say something like “they’re completely separate state machines”.

```3) How have you implemented dependency of one state machine on another in your implementation? (5 points)```
- -2.5 if they don’t get one of these answers:
  - The steering FSM is dependent on the collision (e.g. the ActionRobotDrive = DRIVE_STOP)
  - We call fsmSteerRobot() in the collision FSM.
  - Our action / planning FSMs use states provided by previous FSMs, i.e. one FSM's output is the next one's input. 

```4) Paste your Arduino code below: (25 points)```
- -5 points if ActionRobotDrive = DRIVE_STOP isn’t implemented.
- -10 points if the code obviously doesn’t work.

```5) Paste a link to your video below:```
- 0 points if you can’t see the video. Add the comment:
  > Your video is not public. Please email me (insert TA email here) with a new link to the video and I will grade it. (With a -3 point deduction).
 -3 points if they resend the video.
##### Video Rubric:
This video should show that the LED is blinking, the name should be on the breadboard, and the wires (like the ground connection, etc.) and resistors must be cut.
- -3 points for no name on the breadboard
- -3 points for not cutting resistors or not cutting the LEDs. The only jumpers should be the LEDs and buttons.
- -3 points if their LEDs appear to be flickering
- -3 points per each of the combinations listed below:
  - Drive left (we’re not enforcing that the left button turns on the left light because the code was not set up to support that, so either works).
  - Drive right 
  - Drive straight
  - Collision interrupting driving
  - Servo up
  - Servo down
  - Servo up and down (lights turn off)
  - Servo and driving working together
- -3 points if no talking explanation (like explaining what buttons they’re pressing)
- -3 points mentioned above for having to request permission for the video. 

```6) <ECEn 240 only>  Add your lab report here (PDF only).```

For 301: Give them the same points here as you gave them for Question 10.

For 240: Use the rubric on Learning Suite to assess the quality of the lab report. 

Note: Most 240 lab reports should get full points as long as they put in effort, it looks professional, and they included most of or all the diagrams. 
- -3 if they don’t explain how the robot “brain” divides out perception, planning, and action.
- -3 if they don’t describe the purpose of the ‘pull down and ‘pull up’ resistors’
- -3 if no oscope measurements of the rise times and fall times.
- -3 if the oscope plots were not taken via USB.
- -3 if they don’t describe how they used debugging tools to aid development (like the debugger, or multimeters and oscopes)
- -3 if no screenshots of the serial plotter with the 5 volts and the 3.3 volts.
- -3 if no description in words each of the FSMs.
- -3 if no diagram of the servo FSM.
- -3 if no conclusion or introduction.
- -3 if not professional (this has to be really bad to take this off).
- -5 if not a PDF

```7) In what ways could this lab be improved? (extra credit)```

This usually grades automatically, but people often put “nothing” or something of the sort. Please check this and make sure it is right.  
- -1 point if they do not answer it with some real feedback.
