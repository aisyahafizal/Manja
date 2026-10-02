# CSC649 Setup - Sentence Counter

## Description

This program accepts a sentence from the user and displays the number of words and characters in the sentence. It also handles empty input by displaying a suitable message.

## How to Run

1. Make sure Python 3.12 is installed.
2. Open the project in PyCharm.
3. Open `main.py`.
4. Run the program.
5. Enter a sentence when prompted.

## Features

* Counts the number of words in a sentence.
* Counts the number of characters in a sentence.
* Handles empty input.
* Handles sentences containing extra spaces.

## Test Results

### Test 1: Normal sentence

Input:

`I love Python programming`

Result:

* Word count: 4
* Character count (including spaces): 25

### Test 2: Empty input

Input:

`[empty]`

Result:

`You did not enter a sentence.`

### Test 3: Extra spaces

Input:

`I    love    Python`

Result:

* Word count: 3
* Character count (including spaces):  20

## Limitation

The character count includes spaces and punctuation marks. Therefore, the character count may not represent only letters in the sentence.
