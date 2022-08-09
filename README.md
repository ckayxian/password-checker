# Password Checker

## Overview
This project is a password checker tool using Python, SHA1 Hash Generator and the Pwned Passwords API

It can be used to check if your password has ever been hacked, and how many times it has been found, to keep your password secured

## How It Works
The password checker works with an API using the K anonymity technique, that allows to check all the passwords that begin with the same first k characters as they are hashed with the SHA-1 algorithm

And the password checker can check the rest of the hash function on our end to match the exact same password

## Try It Out:
1. git clone this project
2. open new terminal at project folder
3. install requirements `pip install -r requirements.txt`
4. run `python3 checkmypass.py <Your password>`