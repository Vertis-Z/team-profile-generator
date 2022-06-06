# Team Profile Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Description
The Team Profile Generator is a command-line-input application run in Node that requests information from the user about members of an engineering team and generates an HTML file displaying that information.

## Table of Contents
- [Team Profile Generator](#team-profile-generator)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Tests](#tests)
  - [Demo Video](#demo-video)
  - [License](#license)
  - [Questions](#questions)

## Installation
Before running the application the user must perform an npm install to install all required dependencies.

## Usage
Upon launching the app, the user is asked to describe the first member of their team. The user enters the team member's name, selects that member's role from a list (options include "Engineer," "Intern," and "Manager), enters the member's ID (any string), enters the member's email address, and then must enter another piece of information that will differ depending on what role was selected. If "Engineer" was selected, the app asks the user for the team member's GitHub username; if "Intern" was selected, the member's school is requested; and if "Manager" was chosen, the user is prompted for the team member's phone number. When all information on the team member has been entered, the user is asked whether there are any more members they would like to add. If so, the user is asked the same questions about the new team member. If not, an HTML file is created with cards displaying the information on all the team members entered by the user in the "outputs" folder titled "team.html."

## Tests
If you wish to run a test on the application perform an npm test to see if everything passes.

## Demo Video
https://user-images.githubusercontent.com/48894365/172264294-542ed4bf-e8e8-4e38-83d8-05149c3e6cb0.mp4

## License 
Licensed under the MIT License. Copyright © 2022

## Questions
*For any additional information find me at* 

GitHub: [@Vertis-Z](https://github.com/Vertis-Z/)
