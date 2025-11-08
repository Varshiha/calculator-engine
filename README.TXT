------------------------------------------------------------------------
Super Calculator
Author: Hacker T. Largebrain
------------------------------------------------------------------------

This program implements a highly efficient calculating engine for
a pocket calculator. It includes a complete test rig to demonstrate
that the engine works as it should.
22. I think I believe the final line. Not really sure what it does but I am guessing it did a calculation and it passed the test.
23. It gave 1 me one at first but when i called it again, it was 7 whihc is what was printed in the terminal. After looking at the code, the anser is 7 all the time because in the code we have 3 and 4.
24.It gave me 5 which is the number in the terminal but when i called it again it gave me -13. I don't really understand why though because in the code, I only seee the numbers 9 and 4.
25. I think I understand the code a little bit. The testMinus method perfomrs the operatio, but Does that code just autommatically do the calculation for engine.quals and then gives the answer but how does getDisplayValue know the value.
26.
Method called    displayValue     leftOperand       previousOperator
initial state         0               0                  ''
clear                 0               0                  ''
numberPressed(3)      3               0                  ''
muberPressed(4)       4               3                  ''
equals()              4               4                  ''
getDisplayValue       4               4                  ''
28.I think only the getDisplayValue was cleared but no the previous operator so that is a problem because the engine thinks its + when expected it to be cleared.                  
29. Make sure that all three variables return to their original state when cleared.
30. the answer should be 6: Walkthrough
Method called    displayValue    previousOperator      leftOperand
clear()              0               ''                   0
numberPressed(9)     9               ''                    0 
plus()               0               '+'                 9
numberPressed(1)     1               '+'                    9
minus()              0               '-'
numberPressed(4)     4               '-'                   10
equals()             6               '-'                   0
