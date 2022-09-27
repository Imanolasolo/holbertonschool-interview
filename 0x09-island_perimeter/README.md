0x09. Island Perimeter
======================

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `Making Change` concept for backend-interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Tasks
-----

### 0\. Island Perimeter

Create a function `def island_perimeter(grid):` that returns the perimeter of the island described in `grid`:

*   `grid` is a list of list of integers:
    *   0 represents water
    *   1 represents land
    *   Each cell is square, with a side length of 1
    *   Cells are connected horizontally/vertically (not diagonally).
    *   `grid` is rectangular, with its width and height not exceeding 100
*   The grid is completely surrounded by water
*   There is only one island (or nothing).
*   The island doesn’t have “lakes” (water inside that isn’t connected to the water surrounding the island).

    guillaume@ubuntu:~/0x09$ cat 0-main.py
    #!/usr/bin/python3
    """
    0-main
    """
    island_perimeter = __import__('0-island_perimeter').island_perimeter
    
    if __name__ == "__main__":
        grid = [
            [0, 0, 0, 0, 0, 0],
            [0, 1, 0, 0, 0, 0],
            [0, 1, 0, 0, 0, 0],
            [0, 1, 1, 1, 0, 0],
            [0, 0, 0, 0, 0, 0]
        ]
        print(island_perimeter(grid))
    
    guillaume@ubuntu:~/0x09$ 
    guillaume@ubuntu:~/0x09$ ./0-main.py
    12
    guillaume@ubuntu:~/0x09$ 
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x09-island_perimeter`
*   File: [0-island_perimeter.py](https://github.com/Imanolasolo/holbertonschool-interview/blob/master/0x09-island_perimeter/0-island_perimeter.py)

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
