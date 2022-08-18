# Top Golf Ireland

#### Link to live project: https://jennydelaney.github.io/Portfolio_1_Project/

Top Golf Ireland is a site that gives a list of what is considered Ireland's top 5 golf courses.  It outlines some of the reasons as to why someone should pick Ireland for their next golfing holiday as well as what Ireland has to offer in the types of courses.  It is a list of courses that someone should try and get to play if they get the opportunity.

![Common Screen Sizes](/assets/readme-images/common-screen-sizes.jpg)

# User Experience (UX)
## -  User stories
### First Time Visitor Goals
1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn about golf courses in Ireland.
2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.
3. As a First Time Visitor, I want to be able to identify the top golf courses which I should try and visit in Ireland.
### Returning Visitor Goals
1. As a Returning Visitor, I want to see if the top 5 golf courses have changed in Ireland.
2. As a Returning Visitor, I want to find an easy way to make contact with the top 5 courses to be able to book a round.
### Frequent User Goals
1. As a Frequent User, I want to check to see if there are any newly added courses to the website.
2. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the courses available around Ireland.

# Design
-  #### Colour Scheme
Two main colours were used throughout green (shade: ##50a149) and white.

-  #### Typography
Font choice is Rubik with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly.

- #### Imagery
All images are golf related and reflect the great scenery that is given to every golfer when they play a round of golf in Ireland.

# Features:

- #### Wireframe -

![Wireframe Images](/assets/readme-images/Wireframe-image.jpg)

#### Main Page -
- Navigation bar

![Navigation Bar](/assets/readme-images/navbar.jpg)
A clean display showing the title and the 3 pages.

- Golf Courses around Ireland and a list of some reasons to play in Ireland

![Courses Around Ireland](/assets/readme-images/course-around-image.jpg)
A visual image of the courses avilable around the country as well as the types of courses we have and reasons to play.

- Why choose Ireland?

![Why choose Ireland](/assets/readme-images/why-choose-ireland.jpg)
Additional reasons why golfing in Ireland can give an experience of a lifetime.

- List of social media pages

![Social Media Image](/assets/readme-images/social-media.jpg)
Social media links to all of the platforms available to keep the user updated.

#### Second Page -
A list of what is currently conisdered the top five golf courses in Ireland.

![Top 5 Courses](/assets/readme-images/top-5-courses.jpg)
A screenshot of what are considered the top 5 courses available in Ireland.

#### Third Page -
A newsletter sign up page so that people can be kept informed of the latest list of courses and any offers that might be available through the clubs.

![Newsletter](/assets/readme-images/newsletter.jpg)
A screenshot of the newsletter sign up sheet to keep updated on what are the most popular golf courses.

## Issues:
Initial home page had the Golf Courses around Ireland set up at the top of the home page. However, upon review of the page this looked flat so I added a hero image with a small bit of animation.

## Features:
Responsive on all device sizes


## Technologies Used
### Languages Used
- HTML5
- CSS3

## Frameworks, Libraries & Programs Used

#### Hover.css:
Hover.css was used on the Newsletter form to add a different look while being hovered over.
#### Google Fonts:
Google fonts were used to import the 'Rubik' font into the style.css file which is used on all pages throughout the project.
#### Font Awesome:
Font Awesome was used on all pages to add icons to the footer to highlight social media pages for aesthetic and UX purposes.
#### Git:
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
#### GitHub:
GitHub is used to store the projects code after being pushed from Git.
#### Balsamiq:
Balsamiq was used to create the wireframes during the design process.

## Testing
The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

#### W3C HTML Validator - Results
Initial testing of HTML gave two errors - 
Home page had a stray "/i" which was removed (line 102 at the time)
Top 5 courses had a stray "p" which were removed (lines 49, 63, 82, 96, 110 at the time)

Second test gave one error and one warning - 
 Character reference was not terminated by a semicolon.
At line 20, column 42
mburger">&#9776</label>↩
Outcome - semicolon was entered as advised.

Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed.
From line 35, column 5; to line 35, column 32
    <section class="hero-outer">↩
Outcome - As this is only a warning, it was noted but no action was taken.

#### W3C CSS Validator - Results
Initial testing of css gave two errors - 
float: center was in media queries (lines 322/373 at the time).  Both were removed.

Second test gave one erro - 
469		Value Error : margin , is an incorrect operator : 0,auto
Outcome - , was removed.

#### Lighthouse test - Results
Inital testing of website gave the following results - 
![Lighthouse](/assets/readme-images/Lighthouse-test-1.jpg)

Test was run incognito. Results outlined that images were taking too long to load and it was suggested to change them over to webp or compress the images.

Second test gave the following results - 
![Lighthouse Test No2](/assets/readme-images/lighthouse-test-2.jpg)
  
Second Test run incognito.  Images were changed to webp versions which was the main problem for the performance of the first test.

## Testing User Stories from User Experience (UX) Section

#### First Time Visitor Goals
1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn about golf courses in Ireland.

Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. The first image gives them a great idea of the scenery which they can experience while playing a round of golf in Ireland. When they scroll down the main page it brings them a list of the types of courses we have available, how many courses we have, and some reasons to encourage them to play a round of golf in Ireland.

2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.

The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes what the page they will end up at clearly.
The user can also scroll to the bottom of any page on the site to locate social media links in the footer.

3. As a First Time Visitor, I want to be able to identify the top golf courses which I should try and visit in Ireland.

The site gives clear details of course name, address, phone number and website link of the top 5 golf courses in Ireland which will allow a golfer to find the best golf clubs to play.

#### Returning Visitor Goals
1. As a Returning Visitor, I want to see if the top 5 golf courses have changed in Ireland.

These would be clearly shown in a banner message.
They will be directed to the top 5 courses page with another hero image and call to action.

2. As a Returning Visitor, I want to find an easy way to make contact with the top 5 courses to be able to book a round.

A clear image is against every course which gives the user all of the required courses details.

#### Frequent User Goals
1. As a Frequent User, I want to check to see if there are any newly added courses to the website.

The user would already be comfortable with the website layout and can easily click the banner message.

2. As a Frequent User, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the courses available around Ireland.

The user would already be comfortable with the website layout and can easily click the newsletter registration link.
At the bottom of every page their is a footer which content is consistent throughout all pages.

## Further Testing
The Website was tested on Google Chrome, Microsoft Edge and Safari browsers.
The website was viewed on a variety of devices such as Desktop, Laptop, iPhone 6 & iPhone 8.
A large amount of testing was done to ensure that all pages were linking correctly.
Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bug
#### Fix Bug
The images on Top 5 Courses page merged and lost its gap when reduced under 950px. The fix was to add a new height to the course-images to give this gap.

Images on Top 5 Courses and Newsletter page not showing in incognito.  I confirmed the path in css and this was resolved.

#### Unresolved
The hamburger menu style implements when looking at it from a device screen of less than 450px however for some reason the drop-down list of items will not appear.   Tried to figure out the bug but couldn't.

## Deployment
GitHub Pages
The project was deployed to GitHub Pages using the following steps...

Log in to GitHub and locate the GitHub Repository
At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
Alternatively Click Here for a GIF demonstrating the process starting from Step 2.
Scroll down the Settings page until you locate the "GitHub Pages" Section.
Under "Source", click the dropdown called "None" and select "Master Branch".
The page will automatically refresh.
Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.
Forking the GitHub Repository
By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

Log in to GitHub and locate the GitHub Repository
At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
You should now have a copy of the original repository in your GitHub account.
Making a Local Clone
Log in to GitHub and locate the GitHub Repository
Under the repository name, click "Clone or download".
To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
Open Git Bash
Change the current working directory to the location where you want the cloned directory to be made.
Type git clone, and then paste the URL you copied in Step 3.
$ git clone  https://github.com/JennyDelaney/Portfolio_1_Project
Press Enter. Your local clone will be created.
$ git clone  https://jennydelaney.github.io/Portfolio_1_Project/
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
Click Here to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Content
All content was written by the developer.

Some of the template methodologies were used from the Love Running project walkthough but the developer tried to make most of it their own.

## Media
Images were obtained through pexels.com or sourced through free images available on the internet.

## Acknowledgements
My Mentor for continuous helpful feedback.

Kenan, my cohort faciliator, for helping when I thought I had conflicts when trying to push from gitpod to github on the second last day.
