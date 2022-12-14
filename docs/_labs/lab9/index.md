# Lab 9 -- Priority queues

10:00pm, Sunday, April 21

In this lab, you will write a `PriorityQueue` (Java’s version of a heap) and
use it with different comparators to simulate a variety of operating system
scheduling algorithms.  

After this lab, you should be able to:
- implement a heap;
- use and implement comparators; and
- understand how changing comparators changes the behaviour of the data
  structure using it.

You can get the Lab 9 starter code [here](Lab9.zip).

We are providing you with the following files, which you will not have to change:
- `AvailableComparator.java`
- `Scheduler.java`
- `Task.java`

You will need to modify the following files:
- `MyPriorityQueue.java`

And you will need to create and implement the following:
- `DeadlineComparator.java`
- `LengthComparator.java`
- `NameComparator.java`
- `PriorityComparator.java`
- `MyComparator.java`
- `MyPriorityQueueTest.java`

We are also providing you with the following test files:
- `jobs10.txt`
- `jobs100.txt`
- `jobs1000.txt`
