# Stay Savvy: Tech Blog 💻🚀
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

Stay Savvy is a full-stack application in the form of a CMS-style blog. Similar to a Wordpress site, developers can publish their blog posts and comment on other developers' posts as well. This application follows the Model-View-Controller (MVC) paradigm in its architectural structure, Handlebars.js as the templating language, Sequalize for Object-Relational Mapping (ORM), and Express-session for authentication. Stay Savvy can be run locally or through our Heroku deployment, for more information see our documentation below!

## Table of Contents
1. [Description](#description)
2. [Table of Contents](#table-of-contents)
3. [Usage](#usage)
4. [Installation](#installation)
5. [License](#license)
6. [Technologies Employed](#technologies-employed)
7. [Future Development](#future-development)
8. [Contributing](#contributing)
9. [Tests](#tests)
10. [Questions](#questions)

## Usage
### User Story

```md
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```

### Acceptance Criteria 

```md
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```

## Installation
To run Stay Savvy locally:

1. Pull down and branch this repository
2. Run ```npm i``` to install all dependencies
3. Seed the database by running ```node seeds/seed.js```
4. Run the app with ```node server.js``` or ```npm run start```

To use this app in production, visit: https://stay-savvy.herokuapp.com/

The following shows this full-stack application's appearance and functionality:

![Placeholder]

## License
This project is licensed under the MIT license.

A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.<p/>For more information visit [MIT Licensing](https://choosealicense.com/licenses/mit/).

## Technologies Employed
<strong>Model</strong>
* MySQL2
* Sequelize
* Bcrypt
* Dotenv
* Express-session
* Connect-session-sequalize

<strong>View</strong>
* HTML5
* CSS3
* JavaScript
* Node.js
* Handlebars.js

<strong>Controller</strong>
* Express.js

## Future Development
We would like to continue to add the following functionality to our application:

## Contributing
We'd love for you to contribute! In order to do so, visit [Stay Savvy](https://github.com/isayani/mvc-tech-blog) and fork the repository. Your pull request will need approval in order to merge to ```main```. All contributers will be credited in the README.<br/>Please take a look at our [Future Development](#future-development) section to see what features we are looking to expand on.

## Tests
No tests were run to complete this application.

## Questions
[Find me on GitHub](https://github.com/isayani)<br/>
[Comment directly on the repository](https://github.com/isayani/mvc-tech-blog)

- - -
© 2022 Stay Savvy: Tech Blog by ISayani Creative Services, Confidential and Proprietary. All Rights Reserved.
