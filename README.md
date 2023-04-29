# Anagram Tester
Write an HTML page with the following functionality

## Requirements
1. It should have two input boxes (type=”text”)
2. It should have one button called `check` which does the following.st
    1. Check if both input boxes are filled
    2. Check if both boxes contain email addresses
        1. Check validity of an email address like this:
            1. There should be a `@` and a `.` character. 
            2. These characters should not be at the end or the start.
    3. If the above conditions are met, check whether the part before the `@` sign are anagrams.
        1. Two strings are anagrams if they contain same characters and same number of characters
        2. Example: `PART` and `TRAP`
