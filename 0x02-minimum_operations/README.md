0x02. Minimum Operations
========================

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `Minimum Operations` for interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Tasks
-----

### 0\. Minimum Operations

In a text file, there is a single character `H`. Your text editor can execute only two operations in this file: `Copy All` and `Paste`. Given a number `n`, write a method that calculates the fewest number of operations needed to result in exactly `n` `H` characters in the file.

*   Prototype: `def minOperations(n)`
*   Returns an integer
*   If `n` is impossible to achieve, return `0`

**Example:**

`n = 9`

`H` \=> `Copy All` \=> `Paste` \=> `HH` \=> `Paste` \=>`HHH` \=> `Copy All` \=> `Paste` \=> `HHHHHH` \=> `Paste` \=> `HHHHHHHHH`

Number of operations: `6`

    carrie@ubuntu:~/0x02-minoperations$ cat 0-main.py
    #!/usr/bin/python3
    """
    Main file for testing
    """
    
    minOperations = __import__('0-minoperations').minOperations
    
    n = 4
    print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))
    
    n = 12
    print("Min # of operations to reach {} char: {}".format(n, minOperations(n)))
    
    carrie@ubuntu:~/0x02-minoperations$
    

    carrie@ubuntu:~/0x02-minoperations$ ./0-main.py
    Min number of operations to reach 4 characters: 4
    Min number of operations to reach 12 characters: 7
    carrie@ubuntu:~/0x02-minoperations$
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x02-minimum_operations`
*   File: [0-minoperations.py](https://github.com/Imanolasolo/holbertonschool-interview/blob/master/0x02-minimum_operations/0-minoperations.py)

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
