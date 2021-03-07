# Table of contents

- [Fiachra Holland - Portfolio](#fiachra-holland---portfolio)
- [UX](#ux)
  * [Project Research](#project-research)
    + [Research Analysis](#research-analysis)
  * [Specific expected users & their goals](#specific-expected-users---their-goals)
  * [User stories](#user-stories)
  * [Wireframe Files](#wireframe-files)
- [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Images](#images)
- [Features](#features)
  * [Existing Features](#existing-features)
  * [Features to be implemented in the future](#features-to-be-implemented-in-the-future)
- [Technologies Used](#technologies-used)
  * [Languages](#languages)
  * [Frameworks and Libraries](#frameworks-and-libraries)
- [Testing](#testing)
  * [**User Stories Testing](#--user-stories-testing)
  * [Additional testing](#additional-testing)
    + [Ongoing Bugs](#ongoing-bugs)
- [Deployment](#deployment)
  * [GitHub Pages](#github-pages)
  * [Forking the published GitHub repository](#forking-the-published-github-repository)
  * [Cloning the published GitHub repository](#cloning-the-published-github-repository)
- [Credits](#credits)
  * [Images](#images-1)
  * [Code](#code)
  * [Acknowledgements](#acknowledgements)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Fiachra Holland - Portfolio

A portfolio site for a full-stack web developer based in Ireland.
The website features an initial landing page with a fixed navbar on top, and is designed to be one continuous page that scrolls through and _biography/skills_ section, 
followed by a _projects_ sections, and finally a _contact_ section & footer.

The main goal of the website is to convince prospective employers/collaborators that the site owner is somebody with who they would like to work. The site attempts to achieve this goal
by providing an insight into their life & work history, their skills in the various programming languages, and by providing links to their past/upcoming projects and repo files.

Owner goals:
* Establish an online presence
* Collaborations with other professionals on projects
* Gain full/part-time employment opportunities
* Portray interest/willingness to work with charitable/non-profit organizations
* Portray their cultural and linguistic experiences
* Leave user with a memorable experience which makes them stand out from competitors

 General user goals:
* Assess site owners skills/weaknesses
* Determine if the site owner the is right person for the job/project in mind
* Determine site owners availability
* Make contact to discuss employment/collaboration
* Determine if the site owner has anything to offer which makes them stand out from competitors


# UX

## Project Research

Research for this project began with approaching potential users and competitors of the site. Attempts were made to conduct competitor interviews, however, despite setting up an interview, the interviewee ultimately failed to provide feedback in time. The attempt to conduct the interview has been noted here for clarity. 

For _user interviews_ [Google](http://google.com) was used to search for software development recruitment agencies/software companies in Ireland.
Out of 10 queries sent, one response was received from Míchéal O’Maoldomhnaigh, the Managing Director of [Software Placements](https://softwareplacements.ie/)[.]()

Míchéal was happy to answer questions about the hiring process and a telephone interview was conducted on 09/02/21. The email thread confirming the interview can be found [here.](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/gmail-re-contact-form-enquiry-from-fiachra-holland.pdf) Analysis of the interview can be found in the analysis section below.

For _competitor interviews_, queries were sent to various owners of sites from the following links:
* [15 Web Developer Portfolios to Inspire You](https://www.freecodecamp.org/news/15-web-developer-portfolios-to-inspire-you-137fb1743cae/)
* [10 Full Stack Web Developer Portfolio to Inspire You](https://tamuk.quickstart.com/blog/10-full-stack-web-developer-portfolio-to-inspire-you/)

One response was received from Mathieu Schatzler, the creative director of the site [Wokine](https://www.wokine.com/)[.]() The email thread with Mathieu can be found [here.](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/gmail-competitor-interview.pdf)

### Research Analysis

The _user interview_ with Míchéal O’Maoldomhnaigh yielded some surprising findings, most notable of all was the fact that in all of his years working in the software development recruitment business, he had never _heard of_ or visited a portfolio site, and by extension,
had never based his hiring decisions based off of one. Míchéal advised that his go-to resource for acquiring new talent was [LinkedIn](http://www.linkedin.com)[,]() and that if an individual wished to appear on his companies "radar" then they would have to have a LinkedIn profile.
In preparation for the interview this possibility was anticipated and a number of questions were prepared in the event this was the case. 

When asking Míchéal if there was anything that had prevented him from hiring someone in the past he mentioned that his company utilizes the boolean search function on LinkedIn by filtering the skills of the profiles, 
so by extension, unless the LinkedIn profile had the relevant skills section completed then they would not show up
in the results, which consequently would prevent them being considered for hire indirectly. Míchéal also mentioned that he likes to see LinkedIn accounts up-to-date and fully completed with years of experience included, etc.

In conclusion, while the associated LinkedIn profile was always intended to be a feature of the website via a clickable link in the footer, the importance of having a fully completed profile was not fully appreciated
prior to the interview being conducted. As such, when the website is deployed, the associated LinkedIn profile will be fully completed with the most up-to-date information and is intended to be an extension of the site. Based on Míchéal's feedback, users are likely to predominantly use LinkedIn
and the goal of completing the profile is to direct traffic to the website and vice versa. This will help to achieve the goal of leaving a lasting impression of the site owner on the user by virtue of having a portfolio site that many apparently do not have in this industry.



The _competitor interview_ with Mathieu Schatzler ultimately did not take place as Mathieu did not respond in time.


## Specific expected users & their goals

The kind of users expected to visit this website are as follows:
* Recruitment agencies
* HR departments
* Charitable/non-profit organizations
* Individual collaborators 
* Software SME owners

Users of this site are most likely to be:
* Searching for potential full/part-time employees
* Determining site owners availability for work
* Looking to collaborate on individual projects
* Looking for programmers who may be interested in charitable work
* Looking for something that makes the site owner stand out from competitors in the field

This website assists users in achieving these goals respectively by:
* Providing a comprehensive biography, skills, and work history section
* Providing a downloadable CV that has the site owners current work status listed
* Providing a projects section with links to repositories on GitHub, which they can visit to assess the site owners’ workflow and organizational skills.
* Providing a paragraph in the biography which states that they are interested in charitable/non-profit work in their spare time
* Providing their extensive travel background, linguistic skills and by portraying that money is not always the most important aspect of a project, and is interested in helping with good causes


## User stories

1. As a user visiting the site for the first time, I want to be able to intuitively navigate the website from anywhere on the site
1. As a potential employer, I want to be able to view the site owners skills, work history, and previous projects to help me determine if this person would be a good fit for my business
1. As a potential employer, I want to know if this person is currently employed
1. As a potential employer, I want to be able to see the site owners repo files for previous projects to assess their organizational and workflow skills
1. As a potential employer/collaborator, I want to be able to contact the site owner to discuss employment/collaboration
1. As a potential employer, I want to be able to download a copy of the site owners CV
1. As a charitable organization, I want to be able to determine if the site owner is interested in working on a project with potential financial constraints in place
1. As a potential collaborator, I want to be able to view the site owners social links to keep up to date with their work/projects
1. As a general user, I want to get feedback on any form submissions on the site to confirm contact has been successful

## Wireframe Files

As this site is one continuous page, one wireframe mockup per device - small, medium & large was created. The deployed site varied in a number of ways
from the wireframes. Throughout the project certain smaller aspects of the wireframes were found to be not aesthetically pleasing, mainly the background colour going from staggered gray and white, to continuous gray in the finished project,
also the footer was given more sections and information.
* [Small Device](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/iphone-wireframe.png?raw=true)
* [Medium Device](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/ipad-wireframe.png?raw=true)
* [Large Device](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/desktop-wireframe.png?raw=true)

# Design

## Colour Scheme

The colour scheme was based around [this](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/colour-hex.pdf) hex palette. The white sections of the site for example the paragraphs, are off-white rather than pure white, this
was decided upon to avoid a stark contrast between the elements.

## Typography

Three fonts were used in the construction of the site. The fonts - [Lobster](https://fonts.google.com/specimen/Lobster?preview.text_type=custom), [Poppins](https://fonts.google.com/specimen/Poppins?preview.text_type=custom) and [Quattrocento](https://fonts.google.com/specimen/Quattrocento?preview.text_type=custom) were taken from 
[Google Fonts](https://fonts.google.com/). Lobster was used only for the navbar logo portion to make it unique, 
Poppins was used for heading and buttons, and Quattrocento was used for paragraphs.

## Images

Background images and the project sections thumbnails were taken from [Unsplash](https://unsplash.com/) (credited below in the credits sections). The background images were specifically selected as the aim was to subliminally suggest that
the site owner is unique, the background images in both the _landing_ & _about_ section feature a single leaf and tree respectively that stand out from the surroundings of the image. The background images have an opaque overlay on top of them. This was done to make sure the user was not distracted from the main content of the respective sections.

     
# Features


## Existing Features

After consideration of the expected users, and that these users are likely to be working in an office environment, the decision was made not to include any audio or video files in the site 
as this has the potential to disrupt others around them resulting in a potentially poor user experience.

The website has the following features, listed in order of appearance - left to right & top to bottom respectively on the website.

* Logo - this feature is intended to clearly convey the site owner’s name/brand, this also serves as an anchor to the home of the site and is placed on the top-left of the site, as is convention.

* The Navbar - This is the heart of the site. The navbar allows the user to navigate the site from anywhere in the site that the user finds themself. It will have a 'mouse-over' feature to provide feedback about which link they are about to click.
The navbar is designed to expand at the _sm_ breakpoint.
    
* Call to action button - this feature is on the landing page and is designed for people who want to contact the site owner quickly without having to navigate through the other content.

* Scroll prompt - the scroll prompt is an animated feature that is placed on the bottom of the viewport of the landing section, this gives the user a visual prompt that the site is one continuous page and is best experienced as such, and will hopefully prevent them from first navigating through the site via the navbar.
This feature was coded entirely by [WEB CIFAR](https://www.youtube.com/channel/UCdxaLo9ALJgXgOUDURRPGiQ), specifically [this tutorial](https://www.youtube.com/watch?v=LY1jeQGUiAI&t=57s) and full credit goes to the author.

* About section - this feature gives the user an insight into the site owner’s background, interests, and professional style.
* Progress bars - this feature is intended to give the user a visual representation of proficiency in the various languages the site owner is fluent in. This feature is intended to show both the skills and, subtly, any potential relevant weaknesses of the site owner at the same time while emphasizing the strengths as to not convey incompetence.

* Project section links to finished sites and GitHub repositories - as these projects are not real projects at the time of writing, the links are intended to convey their eventual purpose. The links in the meantime, 
are linked to [example.com](http://example.com/)
    * [This tutorial](https://www.youtube.com/watch?v=AtWJRBdzanM&t=1594s&ab_channel=MDB-justcodeit) was used early on in the project to help with understanding the Bootstrap grid system.
    The code in the projects section was written entirely by me and is significantly different from the code in this tutorial, however, to be absolutely transparent I have included this tutorial as a source and leave it up to whom it concerns to determine if the code is significantly similar to warrant accreditation. If this is the case, then full credit goes to the author [MDB- just code it](https://www.youtube.com/channel/UC5CF7mLQZhvx8O5GODZAhdA) where applicable.

* The contact form - this feature is intended for the user to contact the site owner. Once all fields have been filled out correctly by the user and they click _submit_ the page links to a confirmation page. The confirmation page has a message informing the user that the submission is successful and that the site owner will
be in touch with them shortly. The confirmation page has a redirect function in the head tag which redirects to the main index.html page after 10 seconds.

* The footer - this feature is at the bottom of the page and has three sections: about, social-links, and a section that has a link to a downloadable CV. The footer is designed to be responsive and goes from
three full-width columns stacked vertically up to the _sm_ Bootstrap breakpoint, to three columns placed horizontally for larger screen sizes.

* CV Link - this feature is a clickable icon in the navbar/footer and opens in a new tab. This will open a downloadable pdf link to the site owner’s CV.

## Features to be implemented in the future

* The projects section will be updated with any future projects.
* When JavaScript proficiency has been acquired more animation & interactive features will be added.
* A fully functioning contact section will be added when JavaScript has been acquired.
* The skills feature will be updated if and when new languages are acquired.


# Technologies Used


## Languages

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS#CSS_3)

## Frameworks and Libraries

* [Bootstrap v5.0.0-beta2](https://getbootstrap.com/) was used responsiveness and layout purposes.
* [Google Fonts](https://fonts.google.com/) was used for the three fonts used in the site.
* [Font Awesome](https://fontawesome.com/) was used for the icons in the footer of the site.
* [Balsamiq](https://balsamiq.com/) was used to create the mockups of the site.
* [Gitpod](https://www.gitpod.io/) was used to create the site.
* [GitHub](https://github.com/) was used to store the committed/pushed repositories of the site.
* [jQuery](https://en.wikipedia.org/wiki/JQuery) was used as part of the Bootstrap CDN which gave the navbar the collapsible functionality and the smooth-scrolling effect of the site.
* [Autoprefixer](https://autoprefixer.github.io/) was used to automatically add any required prefixes for the CSS stylesheet.
* [GitHub Wiki TOC generator](https://ecotrust-canada.github.io/markdown-toc/) was used to create the table of contents in the readme file.

# Testing

## User Stories Testing

1. As a user visiting the site for the first time, I want to be able to intuitively navigate the website from anywhere on the site
    * User can navigate the site using the [navigation bar](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/navigation.png?raw=true). The navigator was tested on several various screen 
    sizes and all were functional at the time of writing
1. As a potential employer, I want to be able to view the site owner’s skills, work history, and previous projects to help me determine if this person would be a good fit for my business.
    * User can load the webpage, go to the _about_ section to view [skills](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/skills.png?raw=true) can be viewed via the downloadable CV
    and [previous projects](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/projects.png?raw=true) can be seen in the projects section.

1. As a potential employer, I want to know if this person is currently employed.
    * User can check the site owners [CV](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/work-experience-employment-status.png?raw=true) and see that they are currently employed or not.
    
1. As a potential employer, I want to be able to see the site owners’ repo files for previous projects to assess their organizational and workflow skills.
    * Users can go to the projects section on the site. There they will find the users previous projects and the links to the deployed sites & their respective 
    [repo files](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-repo.png?raw=true) underneath in the form of a button-style link.

1. As a potential employer, I want to be able to contact the site owner to discuss employment.
    * Users can go to the [contact](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/contact.png?raw=true) section and enter their name, email address, and their project description/query. 
    Contact can also be made via the social links in the footer.

1. As a potential employer, I want to be able to download a copy of the site owner’s CV.
    * Users can download the CV from [two places](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/cv-links.png?raw=true), one in the navigation bar, 
    and the other via a clickable icon in the footer. Both open in a new tab.

1. As a charitable organization, I want to be able to determine if the site owner is interested in working on a project with potential financial constraints in place.
    * Users can determine this from reading the [Bio](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/charity.png?raw=true) section on the _about_ page.

1. As a potential collaborator, I want to be able to view the site owners’ social links to keep up to date with their work/projects.
    * Users can go to the footer to source the site owners [social links](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/social.png?raw=true).

1. As a general user, I want to get feedback on any form submissions on the site to confirm contact has been successful.
    * Users can submit their query into the form in the contact section. Once they have clicked _submit_ they will be given a message that their 
    [form has been submitted](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/confirmation.png?raw=true)
     and will be redirected
    to the main page after 10 seconds.

All of the user stories above were tested on small, medium, and large devices. All user stories were fully functional at the time of writing.

## Additional testing

The HTML code for both index.html & confirmation.html were tested using the [W3C HTML Validator](https://validator.w3.org/)
* The results can be seen [here.](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/html-validator-results.pdf)

The CSS code in the style.css file was tested using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
* The results can be seen [here](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/css-validator-results.pdf)

Testing was conducted on [Google Chrome](https://www.google.com/intl/en_ie/chrome/) throughout, and on [Firefox](https://www.mozilla.org/en-US/firefox/new/), [Safari](https://www.apple.com/safari/), [Microsoft Edge](https://www.microsoft.com/en-us/edge) and [iOS](https://www.apple.com/ie/ios/ios-14/) at the final testing stage.
Family members and friends with various devices assisted in testing the deployed site and reported no serious bugs.

### Ongoing Bugs

There was only one major bug that was not resolved on the site. The navbar collapses on mobile devices as expected and the links are all functional. However, when clicking a link in mobile mode the menu does not automatically close and the user must close the menu manually to be able to see the page underneath in full.
Multiple attemps were made to resolve this, by going over the Bootstrap 5 documentation multiple times, by trying to implement JavaScript to close the menu however no solution was found by the time the project deadline came around.
Attemps were made to get assistance from the Slack community but nobody was able to assist, I also spoke to the tutors on the course and they advised me that this must be what Bootstrap does in v5.0.0-beta2 and that grades would not be deducted as long as the code was correct. 

This may not be the case however it is noted here for clarity. It would seem likely that at the time of writing there is a bug in the v5.0.0-beta2 of Bootstrap which is preventing this issue from being resolved. 
Reverting to an older version was not possible as the terms are slighly different and created more problems than it solved when it was tested.


# Deployment


## GitHub Pages

The project was deployed to [GitHub Pages](https://pages.github.com/) using the following method:

1. [Login](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-sign-in.png?raw=true) to [GitHub.]()
1. Locate your desired [repository.](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-locate-repo.png?raw=true)
1. Click [settings](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-setting.png?raw=true) on the top of the repository.
1. Scroll down until you see [GitHub Pages.](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-pages.png?raw=true)
1. In the _source_ section, select the [master branch](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-master.png?raw=true) and click [save.](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-save.png?raw=true)
1. If successful the page will refresh, scroll down again to the GitHub Pages section to confirm. You should see a [confirmation message](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-published.png?raw=true) with the new published URL.

## Forking the published GitHub repository

1. Repeat steps 1 & 2 from above.
1. Locate the [fork](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-fork.png?raw=true) option in the top-right hand corner of the repository page.
1. You will be asked where you want to fork it too if successful, see [here](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/fork-where-to.png?raw=true) for example.

## Cloning the published GitHub repository

1. Repeat steps 1 & 2 from above.
1. Click on the [code](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/github-code.png?raw=true) option on the top of the repository page.
1. Copy the [URL](https://github.com/FiachraCI/fiachra-holland-portfolio-site/blob/master/wireframes/clone-url.png?raw=true) under the HTTPS tab.
1. Consult your code editor of choice's documentation for cloning from GitHub to complete the process.

# Credits


## Images
[Unsplash]() was utilized for all images used on the site.
* Credit goes to [Shyam](https://unsplash.com/@thezenoeffect) for the landing section background image. 
* Credit goes to [Calvin Weibel](https://unsplash.com/@calvinweibel) for the about section background image.
* Credit goes to [Scott Webb](https://unsplash.com/@scottwebb) for the project 1 image.
* Credit goes to [Anastase Maragos](https://unsplash.com/@visualsbyroyalz) for the project 2 image.
* Credit goes to [David Hofmann](https://unsplash.com/@davidhofmann) for the project 3 image.
* Credit goes to [Scott Webb](https://unsplash.com/@scottwebb) for the project 4 image.
* Credit goes to [Sven Mieke](https://unsplash.com/s/users/sven-mieke) for the project 5 image.
* Credit goes to [Alexander Redl](https://unsplash.com/@alexanderredl) for the project 6 image.

## Code
All code except for the mentions directly below were written entirely by the developer.

Credit for the scroll prompt feature on the landing page goes to [WEB CIFAR.](https://www.youtube.com/channel/UCdxaLo9ALJgXgOUDURRPGiQ)

Credit where applicable goes to [MDB - just code it](https://www.youtube.com/channel/UC5CF7mLQZhvx8O5GODZAhdA) for Bootstrap tutorials specifically with regards to the projects section.

## Acknowledgements

Special thanks go to my mentor Dick Vlaanderen

Special thanks to the [Slack](https://slack.com/intl/en-ie/) community for assistance and guidance throughout the project.






