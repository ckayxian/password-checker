# Password Checker

## Overview
This project is a password checker tool using Python, SHA1 Hash Generator and the Pwned Passwords API
It can be used to check if your password has ever been hacked, and how many times it has been found, to keep your password secured

## How It Works
The password checker works with an API using the K anonymity technique, that allows to check all of the passwords that begin with the same first k characters as they are hashed with the SHA1 algorithm
And the password checker can check the rest of the hash function on our end to match the exact same password