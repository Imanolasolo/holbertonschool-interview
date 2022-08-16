0x03. Log Parsing
=================

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `Log Parsing` for interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

Tasks
-----

### 0\. Log parsing

Write a script that reads `stdin` line by line and computes metrics:

*   Input format: `<IP Address> - [<date>] "GET /projects/260 HTTP/1.1" <status code> <file size>` (if the format is not this one, the line must be skipped)
*   After every 10 lines and/or a keyboard interruption (`CTRL + C`), print these statistics from the beginning:
    *   Total file size: `File size: <total size>`
    *   where `<total size>` is the sum of all previous `<file size>` (see input format above)
    *   Number of lines by status code:
        *   possible status code: `200`, `301`, `400`, `401`, `403`, `404`, `405` and `500`
        *   if a status code doesn’t appear or is not an integer, don’t print anything for this status code
        *   format: `<status code>: <number>`
        *   status codes should be printed in ascending order

**Warning:** In this sample, you will have random value - it’s normal to not have the same output as this one.

    alexa@ubuntu:~/0x03-log_parsing$ cat 0-generator.py
    #!/usr/bin/python3
    import random
    import sys
    from time import sleep
    import datetime
    
    for i in range(10000):
        sleep(random.random())
        sys.stdout.write("{:d}.{:d}.{:d}.{:d} - [{}] \"GET /projects/260 HTTP/1.1\" {} {}\n".format(
            random.randint(1, 255), random.randint(1, 255), random.randint(1, 255), random.randint(1, 255),
            datetime.datetime.now(),
            random.choice([200, 301, 400, 401, 403, 404, 405, 500]),
            random.randint(1, 1024)
        ))
        sys.stdout.flush()
    
    alexa@ubuntu:~/0x03-log_parsing$ ./0-generator.py | ./0-stats.py 
    File size: 5213
    200: 2
    401: 1
    403: 2
    404: 1
    405: 1
    500: 3
    File size: 11320
    200: 3
    301: 2
    400: 1
    401: 2
    403: 3
    404: 4
    405: 2
    500: 3
    File size: 16305
    200: 3
    301: 3
    400: 4
    401: 2
    403: 5
    404: 5
    405: 4
    500: 4
    ^CFile size: 17146
    200: 4
    301: 3
    400: 4
    401: 2
    403: 6
    404: 6
    405: 4
    500: 4
    Traceback (most recent call last):
      File "./0-stats.py", line 15, in <module>
    Traceback (most recent call last):
      File "./0-generator.py", line 8, in <module>
        for line in sys.stdin:
    KeyboardInterrupt
        sleep(random.random())
    KeyboardInterrupt
    alexa@ubuntu:~/0x03-log_parsing$ 
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x03-log_parsing`
*   File: [0-stats.py]()

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
