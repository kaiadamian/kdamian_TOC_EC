# kdamian_TOC_EC
1. What was the extra work? <br />
For this extra credit, I simulated the TM variant RESET machine. I figured out how to make transitions such that the RESET transitions were correctly implemented. The tape head moves all the way to the left on a L transition, and the correct character is replaced on the tape even thogh the tape head moves back to the start. In addition, I implemented 2 csv files, one to shift the tape left using only the RESET machine, and another to shift the tape right and add a $ using only the RESET machine. 

2. Why did you choose it (i.e. in what area did you feel deficient and how did this work help improve your understanding) You can point to specific homeworks or problem types on exams. <br />
I chose this extra credit because, for me, the hardest homework was Homework 9B Teamable where we had to design a RESET machine. The concept was super hard for me to understand, as I could not grasp the concept that the character being replaced was not in the same place that the tape head ended up. However, doing this extra credit really helped me to understand how the TM variant RESET machine works!

3. What files are what? <br />
Aside from this README, I have the files below: <br />
reset_machine.py: RESET machine implementation, you can change the input string and file in the main() function. <br />
shift_left.csv: implementation of TM to shift tape left using only RESET. <br />
shift_right.csv: implementation of TM to shift tape right using only RESET. <br />

