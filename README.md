# Code-Chef-Python-Task For Alexey
Alexey is trying to develop a program for a very simple microcontroller. It makes readings from various sensors over time, and these readings must happen at specific regular times. Unfortunately, if two of these readings occur at the same time, the microcontroller freezes and must be reset. 
There are N different sensors that read data on a regular basis. For each i from 1 to N, the reading from sensor i will occur every Ai milliseconds with the first reading occurring exactly Ai milliseconds after the microcontroller is powered up. Each reading takes precisely one millisecond on Alexey's microcontroller. 
Alexey wants to know when the microcontroller will freeze after he turns it on. 

## Input
The first line of the input contains an integer T denoting the number of test cases. The description of T test cases follows.
The first line contains single integer N denoting the number of sensors.
The second line contains N space-separated integers A1, A2, ..., AN denoting frequency of measurements. Namely, sensor i will be read every Ai milliseconds with the first reading occurring Ai milliseconds after the microcontroller is first turned on. 

## Output
For each test case, output a single line containing the number of milliseconds until the microcontroller freezes.

### Example
### Input:
3 <br />
3 <br />
2 3 5 <br />
4 <br />
1 8 7 11 <br />
4 <br />
4 4 5 6 <br />

### Output:
6 <br />
7 <br />
4 <br />
