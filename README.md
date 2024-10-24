Caesar Cipher

A simple Python program that encrypts and decrypts messages using the Caesar Cipher technique. The Caesar Cipher is a basic encryption technique where each letter in a message is shifted by a fixed number of positions in the alphabet.

Features

Encrypt Messages: Shifts each character of a message forward by a specified number of positions.
Decrypt Messages: Shifts each character of an encrypted message backward to recover the original message.
Adjustable Shift: Customize the shift value to create different variations of encoded messages.
Handles Upper and Lowercase: Maintains the case of each letter while encoding/decoding.
Ignores Non-Alphabetic Characters: Leaves numbers, spaces, and symbols unchanged for simplicity.
Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing.

Prerequisites
Make sure you have Python 3 installed on your system. You can download Python from python.org.

Built With

Python 3 - The main programming language used.
How the Caesar Cipher Works

The Caesar Cipher shifts each letter in the input text by a fixed number of positions down the alphabet. For example, with a shift of 3:

A becomes D
B becomes E
Z wraps around and becomes C
