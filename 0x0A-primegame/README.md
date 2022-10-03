0x0A. Prime Game
================

Tasks
-----

### 0\. Prime Game

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `Prime Game` concept for backend-interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Maria and Ben are playing a game. Given a set of consecutive integers starting from `1` up to and including `n`, they take turns choosing a prime number from the set and removing that number and its multiples from the set. The player that cannot make a move loses the game.

They play `x` rounds of the game, where `n` may be different for each round. Assuming Maria always goes first and both players play optimally, determine who the winner of each game is.

*   Prototype: `def isWinner(x, nums)`
*   where `x` is the number of rounds and `nums` is an array of `n`
*   Return: name of the player that won the most rounds
*   If the winner cannot be determined, return `None`
*   You can assume `n` and `x` will not be larger than 10000
*   You cannot import any packages in this task

Example:

*   `x` \= `3`, `nums` \= `[4, 5, 1]`

First round: `4`

*   Maria picks 2 and removes 2, 4, leaving 1, 3
*   Ben picks 3 and removes 3, leaving 1
*   Ben wins because there are no prime numbers left for Maria to choose

Second round: `5`

*   Maria picks 2 and removes 2, 4, leaving 1, 3, 5
*   Ben picks 3 and removes 3, leaving 1, 5
*   Maria picks 5 and removes 5, leaving 1
*   Maria wins because there are no prime numbers left for Ben to choose

Third round: `1`

*   Ben wins because there are no prime numbers for Maria to choose

**Result: Ben has the most wins**

    carrie@ubuntu:~/0x0A-primegame$ cat main_0.py
    #!/usr/bin/python3
    
    isWinner = __import__('0-prime_game').isWinner
    
    
    print("Winner: {}".format(isWinner(5, [2, 5, 1, 4, 3])))
    
    carrie@ubuntu:~/0x0A-primegame$
    

    carrie@ubuntu:~/0x0A-primegame$ ./main_0.py
    Winner: Ben
    carrie@ubuntu:~/0x0A-primegame$
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x0A-primegame`
*   File: [0-prime_game.py]()

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
