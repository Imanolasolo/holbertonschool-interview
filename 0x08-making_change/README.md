0x08. Making Change
===================

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `Making Change` concept for backend-interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Tasks
-----

### 0\. Change comes from within

Given a pile of coins of different values, determine the fewest number of coins needed to meet a given amount `total`.

*   Prototype: `def makeChange(coins, total)`
*   Return: fewest number of coins needed to meet `total`
    *   If `total` is `0` or less, return `0`
    *   If `total` cannot be met by any number of coins you have, return `-1`
*   `coins` is a list of the values of the coins in your possession
*   The value of a coin will always be an integer greater than `0`
*   You can assume you have an infinite number of each denomination of coin in the list
*   Your solution’s runtime will be evaluated in this task

    carrie@ubuntu:~/0x08-making_change$ cat 0-main.py
    #!/usr/bin/python3
    """
    Main file for testing
    """
    
    makeChange = __import__('0-making_change').makeChange
    
    print(makeChange([1, 2, 25], 37))
    
    print(makeChange([1256, 54, 48, 16, 102], 1453))
    
    carrie@ubuntu:~/0x08-making_change$
    

    carrie@ubuntu:~/0x08-making_change$ ./0-main.py
    7
    -1
    carrie@ubuntu:~/0x08-making_change$
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x08-making_change`
*   File: [0-making_change.py](https://github.com/Imanolasolo/holbertonschool-interview/blob/master/0x08-making_change/0-making_change.py)

## Credits

## Author(s):blue_book:

Work is owned and maintained by:
* Imanol Asolo <[3848](mailto:3848@holbertonschool.com)> [![M](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/25px-Octicons-mark-github.svg.png)](https://github.com/Imanolasolo) [![M](https://upload.wikimedia.org/wikipedia/fr/thumb/c/c8/Twitter_Bird.svg/25px-Twitter_Bird.svg.png)](https://twitter.com/jjusturi) [![M](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/25px-LinkedIn_logo_initials.png)](https://www.linkedin.com/in/imanol-asolo-5ba9b42a/)


## Acknowledgments :mega: 

### **`Holberton School`** (*providing guidance*)
This program was written as part of the curriculum for Holberton School.
Holberton School is a campus-based full-stack software engineering program
that prepares students for careers in the tech industry using project-based
peer learning. For more information, visit [this link](https://www.holbertonschool.com/).
<p align="center">
	<img src="https://assets.website-files.com/6105315644a26f77912a1ada/610540e8b4cd6969794fe673_Holberton_School_logo-04-04.svg" alt="This is a secret;)">
</p>
