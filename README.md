<h1 align="center">E-commerce Back End 👋</h1>
  
![badge](https://img.shields.io/badge/license-Open-brightgreen)<br />

## Description
A back end to an ecommerce site using Express.js API, Sequalize, and MYSQL. Link to a walkthrough video <a href='https://drive.google.com/file/d/1Pukd-1pWWAQj5-hC4gHSo2UPxtda_0CA/view?usp=sharing'>here</a>.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation
First clone this repository into your local repository, then make sure that you have a mysql account, here's a <a href='https://coding-boot-camp.github.io/full-stack/mysql/mysql-installation-guide'>link</a> to help you set up mysql if needed. 

## Usage
First make sure you're in the root of the repository, then open the command line and run `npm i`. After that in the root of the directory create a file named `.env` and in that file write 3 lines: `DB_NAME='ecommerce_db'`, `DB_USER ='<YOUR MYSQL USERNAME>'`, and `DB_PW ='<YOUR MYSQL PASSWORD>'`.
In the command line run `mysql -u <YOUR MYSQL USERNAME> -p`, then enter your password. After you've successfully logged in, run `source db/schema.sql` then `quit;`. After you'll need to seed the data so in the command line run `node seeds`. After this you can run `node server.js` and head to an API design platform like Insomnia and test the CRUD operations in different routes.

## License
![badge](https://img.shields.io/badge/license-Open-brightgreen)
<br />
This application is covered by the Open license.
<br />
Link to the <a href='https://www.google.com/search?q=Open+license'>Open license</a>

## Contributing
Joel Abankwah


## Questions
If you're stuck or having problems with the application, If you run into any issues try and repeat the installation and run steps, if you run into any issues with getting mysql setup refer to the link I provided  or
email me with any questions: joelabankwah15@gmail.com<br />
GitHub: [JoelAbankwah](https://github.com/JoelAbankwah)
