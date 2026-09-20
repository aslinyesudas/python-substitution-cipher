# python-substitution-cipher
The process is reversed using the same key.

# Python Substitution Cipher

A simple Python program that encrypts and decrypts messages using a randomly shuffled substitution key.

## Features

- Encrypts text messages
- Decrypts encrypted messages
- Uses a randomly generated substitution key
- Supports letters, numbers, punctuation, and spaces
- Beginner-friendly Python project

## How It Works

The program creates a list of characters and makes a shuffled copy of that list.

Each character in the original message is replaced with the character at the corresponding position in the shuffled key.

### Encryption

```text
Original character → Shuffled key character
        A          →          x
        B          →          #
        C          →          7
