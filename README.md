# Lab 5
CS590 Lab 4

##Objectives

Source code:https://umkc.app.box.com/s/xlpoxnlaeagekcsbupd7dc63sfz7xq2e
When a user clicks on start pedometer, moves around the app should count the steps. When the stop pedometer button is clicked the count should stop irrespective of motion.

### Technologies Used
Android Studio


### Solution
1. I created a new instance of the SensorManager class which accesses Android sensors and assigned it to use the accelerometer.
2. Created a new instance of the StepListener class.
3. Create a view to display two buttons to start and stop the accelerometer.  Additionally, I created a TextView to display the number of steps.
4. Initialze the buttons and set listeners to start/stop recording the steps.  The start button will output and update the number of steps.