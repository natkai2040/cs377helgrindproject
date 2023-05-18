# CS 377 Final Project
Regarding the thead-error checking capabilities of Helgrind
# LINK TO GOOGLE SLIDES:
https://docs.google.com/presentation/d/1BaeQvUlVVUbYbJ9ZEoNYnDEd_9t0aw6MslQt0oloXmk/edit?usp=sharing
# Example Code: 
In Repo, called **valgrind_tests.cpp**. You can also test out HW.4 on valgrind and my commented errors. 
# Compile with
_g++ -g valgrind_tests.cpp -o val_test -pthread_
# Test with
_valgrind --tool=helgrind --read-var-info=yes ./val_test_ **AND FOR HW4:** valgrind _--tool=helgrind --read-var-info=yes ./bank_app 10 pt.txt_

# VIDEO:
PPTVideo.mp4, 8 Min: Goes through the PPT, Explains Helgrind
