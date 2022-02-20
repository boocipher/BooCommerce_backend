# BooCommerce

* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Acknowledgements](#acknowledgements)
* [Questions](#questions)

## Description
**BooCommerce** is a backend only application that demonstrates a simplified but fundamental architecture for a retail e-commerce website. <br>
E-commerce platforms support successfull businesses of all sizes today and enable them to sell physical goods, services and digital products over the internet, making them available worldwide.

## Installation
In order to run **BooCommerce** you must have **NodeJS** installed.
You can download it from [here](https://nodejs.org/en/download/)<br>
<br>
<br>
Next, you need to install the required packages <br> 
1. Start by entering this command in your terminal for Express

   ```
   npm i express
   ```
2. Enter this command for installing the Sequelize package

    ```
    npm i sequelize
    ```

3. Next, enter this command for MySQL2 package

   ```
   npm i mysql2
   ``` 
 
4. And follow by entering this command for the find-config package <br>   
   ```
   npm i find-config
   ```

5. Last, enter this command for the dotenv package  
   ```
   npm i dotenv
   ```


## Usage
This application contains a local database so in order to seed it, first you'll need to create the schema by logging into the MySQL shell. For that purpose, enter the following command in your terminal or command prompt <br>
```mysql -u root -p``` <br>
<br>
Then you'll be prompted for your password and upon successful provision, you'll see the mysql prompt. Create the schema by typing <br>
```SOURCE db/schema.sql``` <br>
<br>
Type in EXIT or QUIT once the schema is created.
<br>
<br>
Next, you need to seed the database by running the command <br>
```npm run seed```
<br>
<br>
Finally, to invoke the application run <br>
```npm run start```
<br>
<br>
As **BooCommerce** is backend only, you can run all routes on **Insomnia**. Please click [here](https://insomnia.rest/download) to download it.
<br>
<br>
For further help on how to set up and run the application, you can also refer to the walkthrough video [here](https://drive.google.com/file/d/1Nm_7dt990-qWQ8R7IFH8eWxFNQHAGQvo/view?usp=sharing).<br>
<br>


## Contributing
Please follow these guidelines if you want to contribute to this project: <br>
You can add issues or recommendations via the app GitHub Issues tab.
If you want to have your fix or feature added, you'll hoave to create and submit a PR for review.

## License
This project is licensed under the MIT license.

## Acknowledgements
Initial code was provided as part of an assignment for the Full Stack Coding Bootcamp at the University of Texas at Austin

## Questions
Any questions? You can reach me at
GitHub: [boocipher](https://github.com/boocipher)<br>
Email: boocipher@gmail.com

