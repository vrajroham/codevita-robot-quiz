# codevita-robot-quiz

-------------------

#Question
A robot is programmed to move forward F meters and backwards again, say B meters, in a straight line. The Robot covers 1 meter in T units of time. On Robot's path there is a ditch at a distance FD from initial position in forward direction as well as a ditch at a distance BD from initial position in backward direction. This forward and backward movement is performed repeatedly by the Robot.

Your task is to calculate amount of time taken, before the Robot falls in either ditch, if at all it falls in a ditch.

First line contains total number of test cases, denoted by N
Next N lines, contain a tuple containing 5 values delimited by space
F B T FD BD. 

where,

 - F denotes forward displacement in meters
 - B denotes backward displacement in meters
 - T denotes time taken to cover 1 meter
 - FD denotes distance from Robot's starting position and the ditch in forward direction
 - BD denotes distance from Robot's starting position and the ditch in backward direction

--------------
#Test Cases

- Sample Input

3

9 4 3 13 10

9 7 1 11 13

4 4 3 8 12
	
- Sample Output

63 F

25 F

No Ditch

---------------------
Vaibhavraj Roham
vaibhavraj.roham@gmail.com
