# Advent of Code Day 5 - Javascript

## The Problem

We are given input that represents crates in stacks and instructions on how to
move them.

It resembles the following:

```txt
{
    [D]
[N] [C]
[Z] [M] [P]
 1   2   3

move 1 from 2 to 1
move 3 from 1 to 3
move 2 from 2 to 1
move 1 from 1 to 2
}
```

## My thought process for part 1

We need to read the lines until the row of numbers. In my initial implementation
I iterated through the lines of the file then through each line by intervals
of 4.
