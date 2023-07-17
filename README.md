# dfa_check
#THE FILE MUST BE NAMED fisier.txt (you can change that in the program)
A python script that checks if a dfa configuration is valid

This script takes as an input a file and checks if it;s a valid dfa configuration . Below is an example of a file:

#
# comment lines (skip them)
#
Sigma :
    a
    b
End
#
# comment lines (skip them)
#
States :
    0 ,S ,F
    1 ,F
    2
End
#
# comment lines (skip them)
#
Transitions :
    0, a, 1
    0, b, 0
    1, a, 1
    1, b, 2
    2, a, 2
    2, b, 2
End
