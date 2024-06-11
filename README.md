- [Tennis Buddy Match](#tennis-buddy-match)
  * [Overview](#overview)
  * [Features](#features)
  * [Design Thought Process](#design-thought-process)
  * [Typography](#typography)
  * [Installation](#installation)
  * [Testing](#testing)
  * [Deployment](#deployment)
  * [Encountered bugs/errors and resolutions (just to name a few for now)](#encountered-bugs-errors-and-resolutions--just-to-name-a-few-for-now-)
  * [Contributing](#contributing)
  * [Contact Us](#contact-us)
  * [NB: The site is still a work in progress and will be enhanced as we proceed with the course. In the end, it will look amazing and work so well! For example, there will be a gallery page added and an About Us page which are being worked on.](#nb--the-site-is-still-a-work-in-progress-and-will-be-enhanced-as-we-proceed-with-the-course-in-the-end--it-will-look-amazing-and-work-so-well--for-example--there-will-be-a-gallery-page-added-and-an-about-us-page-which-are-being-worked-on)
  * [ACKNOWLEDGEMENTS](#acknowledgements)

# Tennis Buddy Match Intro

Tennis Buddy Match Dublin - your go-to platform for finding tennis partners and organizing matches in Dublin.

## Overview 
Tennis Match Dublin is a web application designed to connect tennis enthusiasts across Dublin, fostering a vibrant community of players who share a passion for the game. Whether you're a beginner looking to improve your skills or a seasoned pro seeking competitive matches, TennisMatch Dublin has something for everyone.

## Features
1.  **Find Tennis Partners:** Easily search for tennis partners based on skill level, availability, and location.

2. **Organize Matches:** Join organized matches held regularly throughout Dublin, including competitive tournaments and friendly rallies.

3. **Community Engagement:** Connect with like-minded players, share tips and advice, and stay updated on the latest tennis events in Dublin.

4. **User Profiles:** Create a personalized profile to showcase your tennis skills and preferences, making it easier for others to find and connect with you. 

## Design Thought Process
Green (#EAF5F0): Most tennis courts are usually green so I wanted to pick a colour that connects to the sport while at the same time is friendly to the user's eyes. This colour that is chosen is different from the one that was used in the beginning when submitting the project. The one that was used when submitting the project was a gradient colour which was not very user friendly and would also make the words "disappear" becauseof the different shades. Therefore, I decided t stick to one shade of green and use the black font for the text in most places but also some dark green for some of the headings to still stay in theme. 

The website contrastchecker (https://webaim.org/resources/contrastchecker/) came in very handy in this situation and I was able to pick a suitable background for the different site pages. 

![alt text](image-7.png)

## Typography
The logo and headings use Poppins.
The choice of Poppins was selected using Google Fonts.
The headings decrease in size to ensure responsiveness of the website.

![alt text](image-8.png)


## Installation

To run Tennis Buddy Match Dublin locally, go to the site address which can be visited on:  https://github.com/lavenderweche/tennis-buddy-finder.git

## Testing
- HTML
No errors were returned when passing through the official [HTML validator](https://validator.w3.org/nu/#textarea)
1. The contact.html file
![alt text](image-9.png)

2. The index.html file
![alt text](image-10.png)

3. The register.html file (this file did not pass the validation check and I do not seem to undeerstand the errors, they will be fixed after resubmission of the project is graded)
![alt text](image-12.png)

4. The style.css file
![alt text](image-11.png)

## Deployment
1. Click on the settings link in the menu from Github (https://github.com/lavenderweche/tennis-buddy-finder/):
![alt text](image-13.png)

2. In the left hand menu, click on the pages link:
![alt text](image-14.png)

3. In the sources area of the GitHub pages, select the main option from the dropdown as the source:
![alt text](image-16.png)

4. Save this by clicking the save button (since this was already done before, the save option is greyed out and can be seen in the above image)

5. Since this is not the first deployment, the site was already live. However, the details now show when the last deployment was
![alt text](image-17.png)



## Encountered bugs/errors and resolutions (just to name a few for now)

- **Missing Closing Tags**: Forgetting to close HTML tags. Resolution: Double-checked the HTML markup for missing closing tags and ensured to close any where the errors appeared. This only happened when I deleted an already closed tag because the tool is helpful in the sense that it closed every tag that I opened but when I deleted it for some reason and forgot to close it back, it would cause an error.

- **CSS Selectors Not Targeting Elements**: Sometimes I would put the wrong "target" for example targetting a ul that is in a different section from the one that I actually wanted to target. Resolution: Reviewed the CSS selectors to ensure they matched the HTML elements to be styled, and used browser developer tools to inspect element styles for debugging. 

- **Responsive Design Problems**: Layout not adapting properly to different screen sizes or devices. Resolution: I had to use the CSS media queries to adjust layout and styling based on viewport size, and test the website on various devices to ensure it displays correctly. The google chrome inspecting tool was also very useful because I got to test the different devices.

- **Image Loading Errors**: This was a huge issue for me, I was always mixing up the file paths then the images were not loading or displaying incorrectly. Resolution: Checked the image file paths and updated them. 

## Contributing
We welcome contributions from the community to improve TennisMatch Dublin. If you have ideas for new features, bug fixes, or enhancements, feel free to open a pull request or submit an issue on our GitHub repository.

## Contact Us 
If you have questions, feedback, or just want to chat tennis? Get in touch with me via [email](mailto:lavenderweche@gmail.com)

Below are some screenshot of how the site currently looks. 
## NB: The site is still a work in progress and will be enhanced as we proceed with the course. In the end, it will look amazing and work so well! For example, there will be a gallery page added and an About Us page which are being worked on. 
- The landing Page
![alt text](image-4.png)

- The Registration Page
![alt text](image-5.png)

- Contact Us Page
![alt text](image-6.png)

## ACKNOWLEDGEMENTS
- Thank you to my mentor for continuous helpful feedback and support throughout the project.
   - My mentor provided the following feedback for resubmission and most if not all of the items have been worked on
   1. L1.1 contrast:  right click and inspect, do lighthouse audit and address contrast issues. Sometimes I copy the colors into https://webaim.org/resources/contrastchecker/ and tweak colors to meet WCAG AA Normal Text (light green, turn text to black, dark green, make background blacker)
   2. W3C Validation: run each HTML file through https://validator.w3.org/
   3. L2.5 External Links: update to include mailto:, https://www. ... click on them and make sure they work for each HTML file. You may want to add rel="nofollow" to the links that have target="_blank" (here's an article if you want to know more about this attribute )
   4. L2.6 Responsive: Get the navigation responsive first then work on others.
   5. Work on the readme file
   6. Use: validator.w3.orgvalidator.w3.org. The W3C Markup Validation Service W3C's easy-to-use markup validation service, based on SGML and XML parsers.

- The tutors at Code Institute for their patience and support.
- The Code Institute Slack community for tips and guidance.
- Extra coding support for the sign up form via W3schools, YouTube videos and css-tricks.com
