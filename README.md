[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7943329&assignment_repo_type=AssignmentRepo)
<div id="top"></div>


<!-- GETTING STARTED -->
## About the Project

Given a list of Github repositories, assuming all of them are node js projects with a package.json and package-lock.json in the root, and the name and version of a dependency, this project finds and gives the current version of that dependency and tells if the version is greater than or equal to the version specified or not. Also if the version is lower than the specified version than the update command creates the pull request to update the version. 


### Prerequisites

Node.js Support 
  
## Installation

### Get a free Github Token by following steps:
-Login to your github account

-Go to your account settings

-Select Developer options/Personal access tokens [https://github.com/settings/tokens](https://github.com/settings/tokens)

-Generate new token (Give some name and select all the scopes)

-The token is generated

-Copy the generated token
   
### Clone the repo
   sh
   git clone [https://github.com/github_username/repo_name.git](https://github.com/dyte-submissions/dyte-vit-2022-drs08.git)
   
### Install NPM packages
   run `npm i` in the terminal to install all the required packages
   
### Enter your Generated token in `commands.js`
   
   ```const TOKEN = "Your_Token";```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

### To check the Version Package
 ```node .\commands.js -i input.csv package-name@package-version```
 
### To create a PR updating the version

```node .\commands.js -i -u input.csv package-name@package-version```

### The `-i` command is used to check the version
### The `-u` command is used to create a PR updating the version

### For example the command ```node .\commands.js -i -u input.csv web-vitals@3.9.0``` will give the following result-
  

| Repo                          |                   Repository                     | version | version_satisfied |                      update_pr                      |
|:------------------------------|:------------------------------------------------:|:-------:|:-----------------:|:---------------------------------------------------:|
| dyte-js-sample-app            | https://github.com/dyte-in/javascript-sample-app |   N/A   |      false        |                                                     |
| dyte-sample-app-backend       |  https://github.com/dyte-in/backend-sample-app   |   N/A   |       false       |                                                     |
| dyte-react-sample-app         |   https://github.com/dyte-in/react-sample-app/   |  1.0.1  |       false       | https://github.com/dyte-in/react-sample-app/pull/30 |

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Devarsh Shah - [@LinkedIn_handle](https://www.linkedin.com/in/devarsh-shah-075720206/) - devarshshah08@gmail.com

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
