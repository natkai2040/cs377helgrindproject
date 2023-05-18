# CS 377 Final Project
Regarding the thead-error checking capabilities of Helgrind
# LINK TO GOOGLE SLIDES:
https://docs.google.com/presentation/d/1BaeQvUlVVUbYbJ9ZEoNYnDEd_9t0aw6MslQt0oloXmk/edit?usp=sharing
# Example Code: 
In Repo, called **valgrind_tests.cpp**
Compile: _g++ -g valgrind_tests.cpp -o val_test -pthread_

Test: _valgrind with valgrind --tool=helgrind --read-var-info=yes ./val_test_
# LINK TO VIDEO:
