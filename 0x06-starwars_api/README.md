0x06. Star Wars API
===================

This repo is included in Specializations - Web Stack programming ― Back-end Course of Holberton School. We will cover the `Star Wars API` concept for backend-interview folder.

![Logo](https://www.howtogeek.com/wp-content/uploads/2021/05/laptop-with-terminal-big.png?height=200p&trim=2,2,2,50)

More Info
---------

### Install Node 10

    $ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
    $ sudo apt-get install -y nodejs
    

### Install semi-standard

[Documentation](https://intranet.hbtn.io/rltoken/aHP62g9O1_ZGY34qeberZA "Documentation")

    $ sudo npm install semistandard --global
    

### Install `request` module and use it

[Documentation](https://intranet.hbtn.io/rltoken/mUx37zH56AfjkWx0O65QaA "Documentation")

    $ sudo npm install request --global
    $ export NODE_PATH=/usr/lib/node_modules
    

Tasks
-----

### 0\. Star Wars Characters

Write a script that prints all characters of a Star Wars movie:

*   The first positional argument passed is the Movie ID - example: `3` \= “Return of the Jedi”
*   Display one character name per line **in the same order as the “characters” list in the `/films/` endpoint**
*   You must use the [Star wars API](https://intranet.hbtn.io/rltoken/gOFjTqtp8L2xueAR74gqUw "Star wars API")
*   You must use the `request` module

    alexa@ubuntu:~/0x06$ ./0-starwars_characters.js 3
    Luke Skywalker
    C-3PO
    R2-D2
    Darth Vader
    Leia Organa
    Obi-Wan Kenobi
    Chewbacca
    Han Solo
    Jabba Desilijic Tiure
    Wedge Antilles
    Yoda
    Palpatine
    Boba Fett
    Lando Calrissian
    Ackbar
    Mon Mothma
    Arvel Crynyd
    Wicket Systri Warrick
    Nien Nunb
    Bib Fortuna
    alexa@ubuntu:~/0x06$ 
    

**Repo:**

*   GitHub repository: `holbertonschool-interview`
*   Directory: `0x06-starwars_api`
*   File: [0-starwars_characters.js]()

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
