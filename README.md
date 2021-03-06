# Team-Profile-Generator

## Description

This application can be generated a team profile based on user input using the Inquirer module from Node.js. This project demonstrates use of OOP and using Jest.

## Table of Contents

- [Installation](#installation)
- [HowThisAppWorks](#Howthisappworks)
- [Usage](#usage)
- [License](#license)
- [Contributor](#Contributor)

## Installation

The user should clone the repository from GitHub and download Node. This application also requires a file system and inquirer module. If testing is required, this application uses Jest.

## How this app works:

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for my team members and their information
THEN an HTML file is generated that displays a nicely formatted team roster based on user input
WHEN I click on an email address in the HTML
THEN my default email program opens and populates the TO field of the email with the address
WHEN I click on the GitHub username
THEN that GitHub profile opens in a new tab
WHEN I start the application
THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
WHEN I enter the team manager’s name, employee ID, email address, and office number
THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
WHEN I select the engineer option
THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
WHEN I select the intern option
THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
WHEN I decide to finish building my team
THEN I exit the application, and the HTML is generated
```

## Usage

Use inquirer from your command line to answer questions about your project.
View walk through video here

![Team Profile Generator](./assets/demo/Team-Profile-Generator.png 'Team-Profile-Generator')

![Team Profile Generator](./assets/demo/Team-Profile-Generator.gif 'Team-Profile-Generator')

<br>
View walk through video here in google drive - [Screencastify](https://drive.google.com/file/d/14v9yIKAwgBavxCRG0UCHrWRL11IQgb-9/view?usp=sharing)

## License

This project is license under MIT

## Contributor:

Elham Bazazzadeh ©2021 All Rights Reserved.
