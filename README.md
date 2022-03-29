# Summary of Go: The Complete Developer's Guide (Golang)
Summary of GO The Complete Developer's Guide (Golang) by Stephen Grider. The goal of this course :
- Build massively concurrent programs with Go Routines and Channels
- Learn the advanced features of Go
- Understand the differences between commonly used data structures
- Prove your knowledge with dozens of included quiz questions
- Apply Interfaces to dramatically simplify complex programs
- Use types to future-proof your code and reduce the difficulty of refactors

# A simple start
![strat](asset/img-1.png)

## How to run code in project
![project](asset/img-3.png)

## Package
> Package == Project == Workspace

![package 1](asset/img-4.png)

Type of packages :
- Executable (Generates a file that we can run)
- Reusable (Code used as `helpers`. Good place to used reusable logic)

![package type 1](asset/img-5.png)

## func
![func 1](asset/img-6.png)

## How the main.go file organized
![organized](asset/img-7.png)

# Channels and GO Routines
## Website status checker
![status checker](asset/img-8.png)
![status checker](asset/img-9.png)

## Printing site status
![print site checker](asset/img-10.png)
![print site checker](asset/img-11.png)

## GO routine
A goroutine is a lightweight execution thread in the Go programming language and a function that executes concurrently with the rest of the program. 

![go routine](asset/img-12.png)
![go routine](asset/img-13.png)

## Channels
Channels are the pipes that connect concurrent goroutines. You can send values into channels from one goroutine and receive those values into another goroutine.

![channel](asset/img-14.png)
![channel](asset/img-15.png)
