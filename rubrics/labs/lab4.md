Go to [How to Grade in Learning Suite.md](/resources/How-to-Grade-in-Learning-Suite.md) 
to see how to get to the grader and begin grading. 

Note: "-3" means subtract three points.

# Lab 4:

```1) What is the effect of different values of resistor: 1M, 10M, 100M.  Why do you observe this phenomenon? (5 points)```
- -2 if they don’t say that it increases the sensitivity.
- -2 if they don’t have some explanation for why. Usually includes a mention of tau and how that changes things. (But it’s a harder question, so be lenient).

```3) Paste the Arduino code for Milestone 1. (240 should include code used for measuring the capacitance) (10 points)```
- (240) -5 if no code for measuring capacitance 
- (240) -3 if the code has the wrong calculation for tau.
  > float tau = measuredTime/(log((1-beta)/beta));
- -10 points if they didn’t include any code
- -5 if it’s not the separate sketch. We want them to realize they were supposed to use that code we gave them.

  (A lot of 240 kids have only submitted the one capacitance code, and not the little sketch that everyone does. Give them credit anyway because it is a little confusing).
 
```4) Paste your Arduino code for Milestone 2 (20 points)```
- 0 points if they didn't submit any code. Email or message them requesting it.
  - -5 points if they send the code. 
- -3 if their tau threshold is 25. That means they didn’t change it.
- -5 if the capacitive sensor isn’t implemented correctly (i.e. not using analogWrite or something crazy)
- -10 if the code obviously doesn’t work

```5) Paste a link to your video below: (30 points)```
- 0 points if you can’t see the video. Add the comment:
  > Your video is not public. Please email me (insert TA email here) with a new link to the video and I will grade it. (With a -3 point deduction).
  - -3 points if they resend the video.
- 0 points if you can't see their name on the breadboard. Add the comment:
  > Your video does not have a name on the breadboard. Please email me (insert TA email here) with a new link a new video and I will grade it. (With a -3 point deduction).
  - -3 points if they send a new video, although if the original video would have had a lower score then give them that score.
- If their video is sus (you're not sure it's their own work) then ask the grading TA what to do. 
##### Video Rubric:

This video should show the robot running with the capacitive touch sensor cycling through different speeds. 
- 0 points for no name on the breadboard (see above).
- -3 points they miss one of the following speeds
  - Stop
  - Low
  - Medium
  - High
- -3 points if they are running their robot connected to the computer
- -3 points if no talking explanation (like explaining what buttons they’re pressing)
- -3 points mentioned above for having to request permission for the video. 

```6) <ECEn 240 only>  Add your lab report here (PDF only).```
- For 301: Give them the same points here as you gave them for Question 5.
- For 240: Use this rubric: ([view](https://github.com/mazzeob/ECEn-240-301-grading/blob/03862e905b21ec297db446267fca538f2a583fff/resources/Grading%20rubric%20for%20lab%20report%20in%20ECEn%20240.pdf)) to assess the quality of the lab report. 
  - Note: Most 240 lab reports should get full points as long as they put in effort, it looks professional, and they included most of or all the diagrams.
  - -5 for each item missing from the [list on the slides](https://docs.google.com/presentation/d/1xN_O-1M9sasXvIK402ySojOtNx08k_mZRGd25UIuRvo/edit?subsessionID=zsE5#slide=id.g2e0e03d7963_10_0). TODO: update slide to include specifc ecen240 questions. [Slide 18](https://docs.google.com/presentation/d/1xN_O-1M9sasXvIK402ySojOtNx08k_mZRGd25UIuRvo/edit?subsessionID=zsE5#slide=id.gefb2b78b91_34_0) has the 240 question paraphrased "What is the smallest capacitance your code can measure?"
- -3 if not a PDF. 

```7) In what ways could this lab be improved? (extra credit)```

This usually grades automatically, but people often put “nothing” or something of the sort. Please check this and make sure it is right.  
- -1 point if they do not answer it with some real feedback.
