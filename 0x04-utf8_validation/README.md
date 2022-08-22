0x04. UTF-8 Validation
======================

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `UTF-8 Validation` concept for backend folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Resources
---------

**Read or watch**:

*   [UTF-8](https://intranet.hbtn.io/rltoken/06JcOZip0vKo429Lp_Mz6A "UTF-8")
*   [Characters, Symbols, and the Unicode Miracle](https://intranet.hbtn.io/rltoken/v4RSq0R9IYkAreClE-0rUg "Characters, Symbols, and the Unicode Miracle")

Tasks
-----

### 0\. UTF-8 Validation

Write a method that determines if a given data set represents a valid UTF-8 encoding.

*   Prototype: `def validUTF8(data)`
*   Return: `True` if data is a valid UTF-8 encoding, else return `False`
*   A character in UTF-8 can be 1 to 4 bytes long
*   The data set can contain multiple characters
*   The data will be represented by a list of integers
*   Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer

    carrie@ubuntu:~/0x04-utf8_validation$ cat 0-main.py
    #!/usr/bin/python3
    """
    Main file for testing
    """
    
    validUTF8 = __import__('0-validate_utf8').validUTF8
    
    data = [65]
    print(validUTF8(data))
    
    data = [80, 121, 116, 104, 111, 110, 32, 105, 115, 32, 99, 111, 111, 108, 33]
    print(validUTF8(data))
    
    data = [229, 65, 127, 256]
    print(validUTF8(data))
    
    carrie@ubuntu:~/0x04-utf8_validation$
    

    carrie@ubuntu:~/0x04-utf8_validation$ ./0-main.py
    True
    True
    False
    carrie@ubuntu:~/0x04-utf8_validation$
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x04-utf8_validation`
*   File: [0-validate_utf8.py]()

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
