# lars::event

A c++11 event-listener system template. Usage example:

```
$ g++ -std=c++11 example.cpp 
$ ./a.out 
A has two listeners, B has two listeners
l1 : A clicked at 1, 0
tmp: A clicked at 1, 0
l2 : B clicked at 0, 1
   : B clicked at 0, 1
A has one listener, B has one listener
l1 : A clicked at 2, 0
   : B clicked at 0, 2
```
