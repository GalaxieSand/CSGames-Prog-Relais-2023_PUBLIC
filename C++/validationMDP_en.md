# Password validation Challenge - CSGames 2023

## Context

The university commitee places great importance to security. To this end, they've put in place many policies regarding information security for the new underwater cities. To this end, they've mandate that all new services put in place must be protected by complexe passwords to better safeguard the systems and the personal information of users.

## General overview

Your team have been mandated by the commitee to create a password validator. The first object of this program to recieve a password in string format and validate if it satisfies a series of pre defined rules. The second objective is the ability to be able to dynamically be able to change the rules to **stronger** rules. The third objective is to provide the user with information on how to create a better password if it doesn't pass validation. The final objective is to offer a password generation function that satisfies the current rules.

## Comptetition value

`500 points`

## Tasks

This program must be created in **C++**

### Password Validation

- A password must be between 10 and 24 characters long (10 points)
- A password must contain two **different** numbers (10 points)
- A password must contain two **different** special characters (10 points)
- A password must not containt three identical characters in a row (20 points)

### Change the rules

- Include the ability to modify the rules to determine if a password is sufficiently complexe (60 points)
- The new rules must be **stronger** then the previous rules. We cannot downgrade. (60 points)
- Changing the rules must be as easy as possible for the user (40 points)

### Provide feedback

- Provide the user feedback after a password validation (10 points)
- Indicate to the user **ALL** the reasons why his password is not valid (40 points)
- Indicate to the user how many changes are necessay for his password to be valid (30 points)

### Generate a strong password

- Generate a randomized strong password based on the pred defined rules (50 points)
- Generate a randomized strong password based on the rules after they where modified (30 points)

### Usability

- Make a menu that is easy to use for the user to interact with (40 points)
- Provide clear and efficient feedback to the user (20 points)

### General

- Project runs without modifications (20 points)
- Code is clean and commented (20 points)
- Provide a README with clear instructions on how to run and use your program (30 points)
