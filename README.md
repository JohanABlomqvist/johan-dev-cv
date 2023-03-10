# Johan-Dev-CV 
The goal of this project is to have a functioning site to build upon for the future while I progress on my journey as I get better at coding.
longterm I want it to be easily accessible for recruiters and other people interested in what I do, so a easily available and usable website is important.

![Responsice Mockup](https://github.com/JohanABlomqvist/johan-dev-cv/blob/178767a103fb3b2f6aaebfc975b307c8f80c707e/assets/images/amiresp.PNG)

[View Johan's Dev Journey on Github pages](https://johanablomqvist.github.io/johan-dev-cv/index.html)

# CONTENTS
* [User Experience](#user-experience-ux)
  * [User stories](#user-stories)

* [Existing Features](#existing-features)
* [Features Left to Implement](#features-left-to-implement)
* [Testing and Bugs](#testing-and-bugs)
* [Validator Testing](#validator-testing)
* [Technologies Used](#technologies-used)
* [Deployment](#deployment)
* [Credits](#credits)

# User Experience (UX)

Johan's Dev Journey is a website that will build over time, and get expanded upon as Johan gathers knowledge in coding, the goals are simple, make is easy to access and a clear goal for the user has to be set.

I want for user experience is that they a calm as they enter the website, nothing out of the ordinary that makes you wonder how to find anything, it should be really easy to see what you can click and use as you come in for the first time. 
## User Stories

### First time visitor goals
- Know more about me as a developer.
- Seeing what I am capable of. 

### Returning visitor goals
- Them looking up on my new projects.
- Clients or employers getting contact.

# Existing Features 

- __Navigation bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Portfolio and Contact Me page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/JohanABlomqvist/johan-dev-cv/blob/cae27726fa795bd4eb209c0468c33735c48c727d/assets/images/Nav-bar.PNG)

- __Landing Page__
 
  - The home page includes a picture and information about me and my journey towards being a Fullstack Developer.
   - The aim is to be engaging and give them a good sense of what I want to accomplish, both now and in the future.

![Home Page](https://github.com/JohanABlomqvist/johan-dev-cv/blob/cae27726fa795bd4eb209c0468c33735c48c727d/assets/images/Landing-page.PNG)

- __Contact me page__ 

 - The contact me page has easily navigated form that you can fill out to get in contact with me
 - After completion it redirects you to a success message.

![Contact me](https://github.com/JohanABlomqvist/johan-dev-cv/blob/80bcd8ca9e2a63dd2a5d39fa38941054068f9b74/assets/images/contactmepage.PNG)

- __Portfolio__ 

 - Has a basic layout of pictures for now, but will be pictures with links to my projects that im working on. 
 - Will also add proper frames and info on each picture with a small description what the project is for and what I am to accomplish with it.

![Portfolio](https://github.com/JohanABlomqvist/johan-dev-cv/blob/80bcd8ca9e2a63dd2a5d39fa38941054068f9b74/assets/images/portfpage.PNG)

- __Success form__ 

  - Simple layout for now that tell the one that uses the form that I will get in contact as soon as I can.
  - Will build upon with and add a take me to homepage sticky link in the text in the future.

![Success form](https://github.com/JohanABlomqvist/johan-dev-cv/blob/80bcd8ca9e2a63dd2a5d39fa38941054068f9b74/assets/images/successpage.PNG)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/JohanABlomqvist/johan-dev-cv/blob/cae27726fa795bd4eb209c0468c33735c48c727d/assets/images/Footer.PNG)

- __Coloring__

  - Made to be easy on the eye's and give off a soothing comforting feel.

![Coloring](https://github.com/JohanABlomqvist/johan-dev-cv/blob/6fae0e57436933ffb205419feccc2f1458a46c38/assets/images/coloringwebsite.PNG)

# Features Left to Implement

- Frames for the portfolio pictures with added information on the projects in the frame
- A take me to home link on the success page
- Fleshing out the Landing page AKA Home page, Want more information about what im working on and general info about myself.

# Testing and Bugs
- Fixed a bug where I forgot to properly link my css style sheet to all my webpages.
- Fixed typo in linking HTML pages to eachother causing 404 errors
- Fixed a bug where I spent 4-5 hours on getting my footer to stick to the bottom, after alot of troubleshooting and shouting I came to the conclusion that I am blind because I forgot to check the position attribute in css, it was set to absolute, setting it to fixed solved all my issues.
- Started testing using Flexbox, spent hours figuring out how it works. I think I broke my header and body elements atleast 200 time's.
- With all this said, I ran into minor issues all through this project in both HTML and CSS, styling, and realigning things back and forth. 

## Unfixed bugs
- No bugs that I know of.

# Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/)
  
  ![HTML Check](https://github.com/JohanABlomqvist/johan-dev-cv/blob/240e631298527273e0ab07ee05196ee97743086b/assets/images/htmlcheck.PNG)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)
  
  ![CSS Check](https://github.com/JohanABlomqvist/johan-dev-cv/blob/240e631298527273e0ab07ee05196ee97743086b/assets/images/csspass.PNG)

- Lighthouse
  - High percentages when running lighthouse, so I'm really happy about that.

  ![Lighthouse check](https://github.com/JohanABlomqvist/johan-dev-cv/blob/712d3f4aeb3cab8c6aeab4fab5088efd05d219dc/assets/images/Validator_test.PNG)

## Full testing
To fully test my website I did the following tests using different browsers (google chrome, mozilla firefox) and devices (Samsung s21pro).

I went through each page using google chrome developer tools to ensure that they responsive on all different screen sizes.

Links
1. Tested my social links on index.html, clicking popped out a new tab with the requested site as expected , both on mobile, mozilla, firefox, chrome and opera.
2. Tested my social links on contact-me.html, clicking popped out a new tab with the requested site as expected , both on mobile, mozilla, firefox, chrome and opera.
3. Tested my social links on portfolio.html, clicking popped out a new tab with the requested site as expected , both on mobile, mozilla, firefox, chrome and opera.
4. Tested my social links on success.html, clicking popped out a new tab with the requested site as expected , both on mobile, mozilla, firefox, chrome and opera.

I did the same type of testing on my navigation links.


# Technologies Used
## Languages Used
- HTML and CSS were used to create this website
- Used Javascript on my copyright date, found out how to do it by a youtube tutorial, see link below.
 [Future Web Design - Tutorial - Dynamic JavaScript year/date in copyright footer with HUGO the static site generator.](https://www.youtube.com/watch?v=HcyBdgJhDZI)

## Frameworks, Media, Libraries & Programs Used

- Balsamiq - Used to create wireframes.  
  - Used this to draw up a basic concept before I got to work on the design, I think the original sketch didnt deviate alot from the final product!  
  ![Balsamiq](https://github.com/JohanABlomqvist/johan-dev-cv/blob/ef60a3f80162da6f6854bb0ec3b8a2ff1924229c/assets/images/balsamic.PNG)
- Git - For version control.
- Github - To save and store the files for the website.
- Google Fonts - To import the fonts used on the website. Roboto (300) and Lato (300) Alltho I mainly used Roboto for the whole page.
- Font Awesome - For the iconography on the website. (Header navigation links and Footer icons)
- [Formsubmit](https://formsubmit.co) - To redirect emails when people use the contact me form.
- [Pexels.com](https://www.pexels.com) - Used for images on the website.
- [Pixabay.com](https://pixabay.com) - Pictures for the Portfolio page.
- [Am I Responsive?](https://ui.dev/amiresponsive) - Used to make the mockup picture for the Readme.

# Deployment
Github Pages was used to deploy the live website. The instructions to achieve this are below:

- Log in (or sign up) to Github.
- Find the repository for this project, johan-dev-cv.
- Click on the Settings link.
- Click on the Pages link in the left hand side navigation bar.
- In the Source section, choose main from the drop down select branch menu. Select Root - From the drop down select folder menu.
- Click Save. Your live Github Pages site is now deployed at the URL shown.

## Local Development
### How to Fork
To fork the Zero waste design repository:

- Log in (or sign up) to Github.
- Go to the repository for this project, JohanABlomqvist/johan-dev-cv.
- Click the Fork button in the top right corner..

### How to Clone
To clone the Zero waste design repository:

- Log in (or sign up) to GitHub.
- Go to the repository for this project, JohanABlomqvist/johan-dev-cv.
- Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
- Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
- Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.


# Credits

## Code Used
- Readme help from [Kera Cudmore](https://github.com/kera-cudmore/readme-examples/blob/main/milestone1-readme.md).
- [Dev-Bowers](https://dev-bowers.com) for serving as an inspiration for the layout of my site.
## Content
All the written content is done by Johan Blomqvist.
## Media
- Images are taken from pexels.com and pixabay.com, royalty free. 
- Font Awesome for the nav icons and social icons.
## Acknowledgments
- Lauren-Nicole, my lovely mentor that guided me through this.
- Kera Cudmore, for all the information about the Readme-file.
- Stack Overflow for having great examples of both html and css and how to use it.
