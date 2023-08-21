
# Toy Problems

This repository contains solutions to three Toy Problems: converting 12-hour time to 24-hour time, determining if exactly two out of three integers are positive, and finding the highest value of consonant substrings.

## Challenge 1: Converting 12-hour time to 24-hour time

### Problem Statement

You are tasked with writing a function that takes an hour (in the range of 1 to 12), a minute (in the range of 0 to 59), and a period ("am" or "pm") as input, and converts the time to a four-digit 24-hour format.

### Solution

The function `convert_to_24_hour(hour, minute, period)` handles the conversion. It adjusts the hour based on the period, uses zero-padding, and concatenates the hour and minute to create the 24-hour time format.

## Challenge 2: Two numbers are positive

### Problem Statement

Your task is to create a function that takes three integers as arguments and returns True if exactly two out of the three integers are positive numbers (greater than zero).

### Solution

The function `exactly_two_positive(a, b, c)` checks the positivity of each integer and counts the number of positive integers. If exactly two of them are positive, the function returns True.

## Challenge 3: Consonant value

### Problem Statement

Write a function that takes a lowercase string containing alphabetic characters only (no spaces) and returns the highest value of consonant substrings. Consonants are any letters of the alphabet except "aeiou".

### Solution

The function `solve(s)` calculates the value of consonant substrings and returns the highest value found. It iterates through the string, calculates the value of each consonant substring, and updates the maximum value as needed.

## Usage

Each challenge has its corresponding function provided in this repository. You can use these functions to solve the respective challenges.


## Author
it is written by Philip ogaye.


# pytest cache directory #

This directory contains data from the pytest's cache plugin,
which provides the `--lf` and `--ff` options, as well as the `cache` fixture.

**Do not** commit this to version control.

See [the docs](https://docs.pytest.org/en/latest/cache.html) for more information.
