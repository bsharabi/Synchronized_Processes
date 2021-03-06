# Synchronized Processes

> Process Synchronization means coordinating the execution of processes such that no two processes access the same shared resources and data. It is required in a multi-process system where multiple processes run together, and more than one process tries to gain access to the same shared resource or data at the same time.

![live-chat-apps-1280x720](https://miro.medium.com/max/1400/0*bbTnCsiT0klMbi3q.png)

## How to use the programm:
```bash
$ "PUSH [your input]" : inserting element into the stack
$ "POP" : to remove element from top of the stack
$ "TOP" : to show the top element of the stack (whithout removing it)
$ "COUNT" : to show how much elements at the stack
$ "CLEAN" : to remove all the elements from the stack
$ "EXIT" : to exit the programm and close the connection between the client and the server
```

## Running Programm:
```bash
# Clone the repository
$ git clone https://github.com/bsharabi/Synchronized_Processes
# Go into the repository
$ cd Synchronized_Processes
# Open the terminal on Linux
$ Run "make run"
$ Run make iserver"
$ Run make iclient"
```

## Running Test:

```bash
# Clone the repository
$ git clone https://github.com/bsharabi/Synchronized_Processes
# Go into the repository
$ cd Synchronized_Processes
# Open the terminal on Linux
$ Run "make run"
$ Run make tester"
```