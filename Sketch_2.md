# DM-UY 1133-A Creative Coding
##### Fall 2024 • Katherine Bennett • Monday & Wednesdays • 12:00-13:50

### Sketch 2

### Interactive Repetition & Drawing: Modularity, Pattern


#### Step 1: Feb 12
#### Step 2A: Feb 21
#### Step 2B: Feb 26
#### Step 2C: March 4


        
##### Step 1:
 
 A. Using 1 small line or small simple shape (ellipse), twist or turn it and position it within space. Repeat this process, changing the orientation and position, yet keeping it close to the previous shape. Repeat this process at least 4-8 more times. By the end, you should a clustered arrangement of similar shapes. Now, thing of this cluster of shapes, as one stamp.

 B. Apply a variable to these shapes location coordinates, such as "50 + x" "100 + y"

 C. Wrap these lines of code into a function. Check that function by calling that function.

 D. Then pass parameters for that function, that are then used within that function, such as myCluster(int x, int y)

 E. Then call that function multiple times passing different values to it each time. (You can create parameters for color, width, height, etc)


![Inspired by Ancient Egyptian colors and tiles](http://1.bp.blogspot.com/-s3ks8j1jw6M/UASekhqS0BI/AAAAAAAAkRQ/oIW8a5qraS0/s1600/Egypt-047.jpg)


##### Step 2:  <-- these submission are graded

 2A.  Now, call that function inside a double for-loop. Use the *double for-loop* to create multiple instances of the shape cluster. But, they cannot appear on top of one another and they must appear on the sketch (ie, no background update).

 Create 3 _different_ patterns with your clusters this way. Work on getting different spacing between the pattern calls.

 How you structure your *double for-loops* (calling this stamp), will control how that pattern is made. See the image above.

 Use the previously created arrangement of shapes, as the cluster that you will use to create different patterns across the sketch window. 

 2B. _For the next 3 patterns_, use your cluster, calling it multiple times (again). Yet, turn aspects of this cluster "on" and "off"; Or, switch some physical (location, not just color) aspect of your cluster. Achieve this by using if-statements within your for-loop. _How can you start to deviate from a grid? How can that grid be transformed into a cone? Or strips? Can you skip every other one?_ <strong> Can you manipulate that grid so that it is less grid-like? That is your goal here.</strong> 


 2C. _The next 3 patterns_ must use matrix transformations and can be interactive using the mouse.


 By the end of all of this, You are to have created 9 DRASTICALLY different pattern arrangements (ie, location NOT JUST COLOR), using the same clusters of shapes (having them appear, not appear, or appear at different intervals.) Focus on trying to control the location of each cluster, by manipulating those location coordinates. 


 Variables, loops, and exit conditions are your key. Play and experiment here. Try different things out. Play with your operators in your for-loop (+, -, *, /), as well as how much you are operating by (ie, +1, -2, /.5, *5.5). 

 What happens when you throw an if-statement within the double for-loop? <---- Try it out!

 EXPERIMENT WITH YOUR OPERATORS, LOOP CONDITIONS, & IF-STATEMENTS

 Consider different rhythms that you can make with spacing, direction/orientation and repetition. Use a keyPress to switch between different patterns. As a result, all of your patterns should appear in ONE sketch

 - use active mode
 - use variables, manipulate variables
 - use custom functions
 - that passing parameters
 - use double loops (for, while). Make sure there is an exit condition
 - 2A: Create 3 different patterns with the same cluster. Shift the location by passing different parameters to your location variables. Can you make aspects of the pattern twinkle? Or change color occasionally.
 - 2B: use conditional(s) to make your pattern interesting, unique, and to have variety (3 patterns)
 - 2C: you use matrice transformations on only 3 patterns
 - At the end: you need to have 9 patterns total, within one sketch, controlled by key or mouse change.


 Reference: 

 [Shentong Yu] (https://openprocessing.org/sketch/1686211)

 [Connor Hester (previous student)](https://openprocessing.org/sketch/971975)

 [Neha Vasudevan (previous student)](https://openprocessing.org/sketch/971738)

 [Johnlouis Dahhan (previous student)](https://openprocessing.org/sketch/971999)

 [Chloe Chan (previous student)](https://openprocessing.org/sketch/971981)

 [Gregoire Drigo (previous student)](https://openprocessing.org/sketch/971994)

 Professional Artists:

 [Lia](http://www.liaworks.com/category/theprojects/)

 [Eno Henze](http://enohenze.de/)