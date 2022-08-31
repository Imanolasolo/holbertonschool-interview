0x05. N Queens
==============

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `N Queens` concept for backend-interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Tasks
-----

### 0\. N queens

The N queens puzzle is the challenge of placing N non-attacking queens on an N×N chessboard. Write a program that solves the N queens problem.

*   Usage: `nqueens N`
    *   If the user called the program with the wrong number of arguments, print `Usage: nqueens N`, followed by a new line, and exit with the status `1`
*   where N must be an integer greater or equal to `4`
    *   If N is not an integer, print `N must be a number`, followed by a new line, and exit with the status `1`
    *   If N is smaller than `4`, print `N must be at least 4`, followed by a new line, and exit with the status `1`
*   The program should print every possible solution to the problem
    *   One solution per line
    *   Format: see example
    *   You don’t have to print the solutions in a specific order
*   You are only allowed to import the `sys` module

Read: [Queen](https://intranet.hbtn.io/rltoken/u80efQj5HUl9-FwkzWieCA "Queen"), [Backtracking](https://intranet.hbtn.io/rltoken/OjIVuPYh-rEjUHc7crQ5lw "Backtracking")

    julien@ubuntu:~/0x08. N Queens$ ./0-nqueens.py 4
    [[0, 1], [1, 3], [2, 0], [3, 2]]
    [[0, 2], [1, 0], [2, 3], [3, 1]]
    julien@ubuntu:~/0x08. N Queens$ ./0-nqueens.py 6
    [[0, 1], [1, 3], [2, 5], [3, 0], [4, 2], [5, 4]]
    [[0, 2], [1, 5], [2, 1], [3, 4], [4, 0], [5, 3]]
    [[0, 3], [1, 0], [2, 4], [3, 1], [4, 5], [5, 2]]
    [[0, 4], [1, 2], [2, 0], [3, 5], [4, 3], [5, 1]]
    julien@ubuntu:~/0x08. N Queens$ 
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x05-nqueens`
*   File: [0-nqueens.py]()

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
