---
layout: post
title: Password Cracking 
---

## Password Cracking

is a process used to identify an unknown or a forgotten password. It can be used be crackers to gain an unauthorized access to resources. Password cracking uses two primary methods to identify passwords. 

1. Brute Force 
2. Dictionary Search

### Brute Force Attack: 

it runs through a combination of characters through a predetermined length until it finds the correct combination. 

Example: if you want to crack a 4 digit pin code. you will need to run through a 10,000 combination possibility, which can be achieved easily using one of the well known password cracking softwares [Hash Cat](https://hashcat.net/oclhashcat/). Number of possibilities can be calculated by (10 power 4). 10 is the range of characters [0,1,2,3,4,5,6,7,8,9] and 4 is the number of characters on the targeted pin. 

### Dictionary Search Attack:

it uses each word in a dictionary for the correct password. Password dictionaries exists for a variety of topics. 

>A dictionary attack is based on trying all the strings in a pre-arranged listing, typically derived from a list of words such as in a dictionary (hence the phrase dictionary attack). In contrast to a brute force attack, where a large proportion of the key space is searched systematically, a dictionary attack tries only those possibilities which are deemed most likely to succeed. Dictionary attacks often succeed because many people have a tendency to choose short passwords that are ordinary words or common passwords, or simple variants obtained, for example, by appending a digit or punctuation character. Dictionary attacks are relatively easy to defeat, e.g. by choosing a password that is not a simple variant of a word found in any dictionary or listing of commonly used passwords. 

[source](https://en.wikipedia.org/wiki/Dictionary_attack)

#### Hybrid: 

are dictionary attacks that my combine letter, numbers, and special characters; depending on the target password requirements. 
example: 

><p>!H0tc0ffee</p>
><p>!H@cker1</p>
><p>!Hamburg?</p>


#### Password Guessing (Information Gathering & Foot-printing)

A cracker may use gathered information about a target to guess his/her password. a combination of information like name, date of birth, credit-card number, mobile number, marriage anniversary date, address and interests. 



## Resources
1. [Top ten password cracking techniques](http://www.alphr.com/features/371158/top-ten-password-cracking-techniques)
2. [How to Guess a Password](http://www.wikihow.com/Guess-a-Password)
