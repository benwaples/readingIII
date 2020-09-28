# Summary of reading for Class-12

## [Why you should use bcrypt](https://medium.com/@danboterhoven/why-you-should-use-bcrypt-to-hash-passwords-af330100b861)
* plain text passwords - passwords only containing letters
* one way hash - server doesnt store the plain text password, it stores a hash and uses a hashing algorithm to authenticate a user. The algorithms are not completely secure and someone can guess until they figure it out. 
* salting the password - using a one way hash but also adding a string of bytes to the password before it gets hashed. Secure unless a hacker figures out the source code for the salting.
* random salt string - each salting will be different for a user.
* BCrypt - uses Key Factor makes the cost of hashing much higher. So running a hashing algorithm would take for longer and not worth it.

## [Understanding BCyrpt](https://auth0.com/blog/hashing-in-action-understanding-bcrypt/)
* Cyrptographic funciton - SHA2, SHA-3. These are designed to be fast, the faster that hashing takes has significance to how secure a password is. Fast calculations means that you are more vulnerable to brute force attacks.
* OAuth uses bycrpt to hash and salt passwords so that attackers have to take longer to hack a password.
* Bycrpt will scale with improving hardware because it can be turned to run slower on new hardware.

* 