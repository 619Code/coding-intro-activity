# Coding Intro Activity

## Hello world activity

The goal of this activity is to get a Hello World! program running on your machine. Please follow the steps outlined here. You are strongly encouraged to examine all the files in this repository and learn what they do. 

1. Download the code for this project from Github. You can download the source code or clone the repo (if you're familiar with git). 

2. Extract the files into a directory of your choice the recommended name is coding-intro-activity. If you've you've cloned the repo, this has been done for you. 

3. Make sure you have Java installed. You will need Java 21+ installed. You can install it from [here](https://openjdk.org/projects/jdk/21/). A note on Java installs. You want to get the OpenJDK version of the Java binaries, not the "official" version from Oracle (although Oracle distributes both). The OpenJDK is licensed under the GPL (GNU Public License) which means it's free for your use. The "official" binaries are under a proprietary license. If you use them, and your app becomes successful then you can tell us all about the lawsuit. 

4. Try running `.\gradlew.bat run` from the terminal. If you see 
```
> Task :app:run
Hello World!
```
then congratulations! You're done.

## Counting Primes Activity

Please make sure you've completed the Hello World! activity before starting this one. 

You are tasked with finding all the primes between 1 and 1,000,000 (inclusive). Using the Hello World code as a starting place, write a program that prints how many primes there are, followed by a new line and then a comma separated list of those primes. 

Example output:
```
> .\gradlew.bat run
Reusing configuration cache.

> Task :app:run
There are 78498 primes between 1 and 1000000
[2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, ...]
```

Your program must complete in less than 10 seconds (as measured by the gradle task). There is approximately 700ms taken up by the gradle task itself, which will NOT be subtracted from your time. If you're over 10 seconds, even by a bit, think about how you can make your code faster. If you're interested in a quick benchmarking tool, I recommend [hyperfine](https://github.com/sharkdp/hyperfine)
