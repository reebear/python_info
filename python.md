# Python # 

Python is an interpreted, high-level, general-purpose programming language. Created by Guido van Rossum and first released in 1991, Python's design philosophy emphasizes code readability with its notable use of significant whitespace. Its language constructs and object-oriented approach aim to help programmers write clear, logical code for small and large-scale projects.
Python interpreters are available for many operating systems. A global community of programmers develops and maintains CPython, an open source reference implementation. A non-profit organization, the Python Software Foundation, manages and directs resources for Python and CPython development.

The Raspberry Pi single-board computer project has adopted Python as its main user-programming language.

## Strings ##
first_name = 'Tom'
last_name = 'Cruise'
welcome_message = f'Welcome {first_name} {last_name}'
print(welcome_message) # Welcome Tom Cruise

The f before the string denotes formatted string. The dynamic values are placed within {}

### String Indexes ###

Strings in Python are simply ordered collection of characters. So we can do a lot of cool tricks with it. We can access characters of a string, select a substring, reverse a string and much more very easily. It is also called slicing of string.
language = 'python'
first_character = language[0] # indexing starts from 0
second_character = language[1]
print(first_character) # p
print(second_character) # y
# Strings can be manipulated easily with this syntax [start:stop:step-over]
range_1 = language[0:2] # here it starts from index 0 and ends at index 1
range_2 = language[0::1] # starts at 0, stops at end with step over 1 
range_3 = language[::2] # starts at 0, till end with step 2
range_4 = language[1:] # starts at index 1 till end of string
range_5 = language[-1] # selects last character
range_6 = language[-2] # second last character
reverse_string = language[::-1] # starts from end and reverses the string
reverse_string_2 = language[::-2] # reverses string and skips 1 character

print(range_1) # py
print(range_2) # python
print(range_3) # pto
print(range_4) # ython
print(range_5) # n
print(range_6) # o
print(reverse_string) # nohtyp
print(reverse_string_2) # nhy
https://www.digitalocean.com/community/tutorials/how-to-index-and-slice-strings-in-python-3

## Lists ##
