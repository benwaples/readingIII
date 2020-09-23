# Summary of reading for Class-10

## User Modeling
Because users give us sensitive data, it is developers responsibility to make sure to store there data safely. Passwords need to be either hash encoded before going into a database, or the database needs to be password protected or behind a firewall.

When data is being shared between users, make sure that data is stored in a separate database than the sensitive data so that sensitive data can not be accidentally or maliciously sent to other users.

## Cryptography 
Science of encoding, only someone with a key can read an encoded message.

## Hash Algorithms
computers use hash algorithms to compare passwords without ever displaying or reading the actual password.

## Cypher Algorithms
I send an encoded message to someone with a password that is stored on a piece of paper in my pocket (cache) and the message prompts a response that is also encoded. When I get a response I can use the password stored in my pocket to decode the message.

## Basic Authorization
a POST method through HTTP to set authorization for a given user. Once a user has signed in/ up they recieve a token or key which acts like a wrist band at the bar that says you are good to go.

* Uses base 64 encoding which is not a form of encryption... no one is pointing the finger at everyone. use the library base-64 to encode and decode a key/token.