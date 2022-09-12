0x07. Rotate 2D Matrix
======================

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `Rotate 2D Matrix` concept for backend-interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Tasks
-----

### 0\. Rotate 2D Matrix

Given an `n` x `n` 2D matrix, rotate it 90 degrees clockwise.

*   Prototype: `def rotate_2d_matrix(matrix):`
*   Do not return anything. The matrix must be edited **in-place**.
*   You can assume the matrix will have 2 dimensions and will not be empty.

    jessevhedden$ cat main_0.py
    #!/usr/bin/python3
    """
    Test 0x07 - Rotate 2D Matrix
    """
    rotate_2d_matrix = __import__('0-rotate_2d_matrix').rotate_2d_matrix
    
    if __name__ == "__main__":
        matrix = [[1, 2, 3],
                  [4, 5, 6],
                  [7, 8, 9]]
    
        rotate_2d_matrix(matrix)
        print(matrix)
    
    jessevhedden$
    jessevhedden$ ./main_0.py
    [[7, 4, 1],
    [8, 5, 2],
    [9, 6, 3]]
    jessevhedden$
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x07-rotate_2d_matrix`
*   File: [0-rotate_2d_matrix.py]()

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
