Download Link: https://assignmentchef.com/product/solved-cs205-assignment-2-simulate-a-terminal
<br>
The problem is to simulate a terminal. We are asked to write a program that can follow some commands. We also need to use “switch” statement instead of using “if…else” structure. By the way, to ensure my program will not crash, I also need to consider the bad input. In the terminal, the program will ignore the letter caes, so my program should also recognize the commands ignoring the case.Part 2-Code

Part 3-Result &amp; Verification

Test case #1

Test case #2

Test case #3

Test case #4

Part 4-Difficulties &amp; Solutions

1.Using scanf( ) cause we may only read the data before ‘ ‘, and leave the other information in the cache. And it may cause my program crash. So cin.getline() is used to read the whole line.2.Since the bad input may have some blank before the commands or at the end of the commands, so we need to delete these blanks at the beginning.3.Another problem we should notice is that if the user only input the blanks, the program should prompt the user to input the command again.4.Actually, in the terminal the commands’ excution will ignore the case. So, we should also ignore the letter cases in my program. Such that, if the input include upper cases, the program should excute normally.