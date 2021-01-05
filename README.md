# Minigrep
This is my first attempt at programming in Rust!

## What does it do?
This is my own version of the classic command line tool grep (globally search a regular expression and print). 
In the simplest use case, grep searches a specified file for a specified string. To do so, grep takes as its 
arguments a filename and a string. Then it reads the file, finds lines in that file that contain the string 
argument, and prints those lines. This is exactly what I implemented in my version of grep!

## Features
- search file and print lines containing query
- case insensitive search when environment variable CASE_INSENSITIVE=true is set
