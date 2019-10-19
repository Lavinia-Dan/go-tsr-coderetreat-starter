# 1. Introduction

The game of life is the best-known two-dimensional cellular automaton, invented by John H. Conway and popularised in Martin Gardner's Scientific American column starting in October 1970.

The life cellular automaton is run by placing a number of filled cells on a two-dimensional grid. Each generation then switches cells on or off depending on the state of the cells that surround them. The rules are defined as follows. All eight of the cells surrounding the current one are checked to see if they are on or not. The cells that are on are counted and this count is then used to determine what will happen to the current cell.

Death: if the count is less than 2 or greater than 3, the current cell is switched off.

Survival: if the count is exactly 2, or the count is exactly 3 and the current cell is on, the current cell is left unchanged.

Birth: if the current cell is off and the count is exactly 3, the current cell is switched on.

(from http://mathworld.wolfram.com/GameofLife.html)


## SETUP GO:

https://golang.org/doc/install


## RUN TESTS WITH GO:
example: 
```
go test hello_test.go hello.go
```

