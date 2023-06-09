![Logo](assets/images/logo.png)

Welcome to, 
# HISTOTY OF MICHAEL COLLINS

This website provides a comprehensive overview of the life and accomplishments of Michael Collins, an influential figure in Irish history. From his role in the Irish War of Independence to his political career, this website aims to educate and inform visitors about the significant contributions made by Michael Collins. Here, you will find a wealth of information and resources about Collins, his role in shaping Irish history, and his enduring legacy.

The live link can be found here - https://jamie33o.github.io/history-of-michael-collins/ 

The last update to this file was: **June 22th, 2023**

![website on differnt devices](docs/readme_images/mock-up-different-devices.png)

## Features
In this section we go over the features of the website, and show examples of the different sections.


- __Header navigation bar__

  - Featured on all three pages, the full responsive navigation bar includes links trough the Logo, Home page, Gallery and Questions/Add Info page, website name and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](docs/readme_images/nav-bar.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for the History of Michael Collins. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](docs/readme_images/footer.png)

- __Favicon__ 

  - The Favicon is the website's logo and will be on each page of the website it will use different sized favicon for different devices. 
  - This will show in the tabs header and allow the user to identify the website if they have multiple browser tabs open.

![Favicon](docs/readme_images/favicon.png)

- __404 page__ 

  - A 404 page will will display if a user navigates to a broken link. 
  - The 404 page will allow the user to navigate back to the main website if they direct to a broken link/missing page, without the need of the browsers back button.

![404 page](docs/readme_images/404-page.png)


### Homepage
- The Homepage offers an interactive visual representation of the significant events in Michael Collins' life. 
- It allows users to navigate through key milestones and gain a better understanding of the chronology of his accomplishments and challenges.

- __Table of contents section__

  - The table of content's has links to each section of the timeline of Michael Collins life
  - This section introduces the user to information about Michael Collins also with an image of Michael Collins and some interesting facts

![table of content](docs/readme_images/table-of-contents.png)

- __Timeline section__

  - The timeline section has multiple seperate paragraghs leading the user through Michael Collins life. 
  - There is an image relating to each paragraph with a description so the user can really get a feel for Michael Collins life. 

![timeline section1](docs/readme_images/timeline-section1.png)
![timeline section2](docs/readme_images/timeline-section2.png)
![timeline section3](docs/readme_images/timeline-section3.png)
![timeline section4](docs/readme_images/timeline-section4.png)

### Gallery

- The gallery will provide the user with supporting images with description and also embeded youtube documentary videos to provided more insight into Collins life. 
- This section is valuable to the user as they will get a lot more information about collins and a better feel for what it was like in collins time. 

![Gallery](docs/readme_images/gallery.png)

### Questions/Add Info 

- This page will allow the user submit more info that they think we should add to the site, or ask any question they have. 
- On successful submission of the contact form, the user will be navigated to thank-you.html displaying a success message.. 
-  The form will consist of the following fields and attributes:
  - Name (required, type=text)
  - Email (required, type=email)
  - Message (required, type=textarea)

![Questions/Add Info](docs/readme_images/form.png)
![Questions/Add Info](docs/readme_images/thank-you.png)

### Existing Features
- Responsive design
- Contact form and success page
- 404 Error page
- Gallery with images and embeded youtube documentaries



### Features Left to Implement

- Another feature idea we are thinking of implementing is another page for links to more information on collins and maybe more influenical irish figures in history.

## Design

### Wireframes

Homepage

![wireframe design for large screen](docs/readme_images/wireframe-laptop.png)
![wireframe design for tablet](docs/readme_images/wireframe-tablet-home.png)
![wireframe design for gallery](docs/readme_images/wireframe-gallery.png)
![wireframe design for form](docs/readme_images/wireframe-form.png)

## Technologies

- HTML
  - The structure of the Website was developed using HTML as the main language.
- CSS
  - The Website was styled using custom CSS in an external file.
-Visual Studio Code
  - The website was developed using Visual Studio Code IDE
- GitHub
  - Source code is hosted on GitHub and delpoyed using Git Pages.
- Git
  - Used to commit and push code during the development opf the Website
- Font Awesome
  - Icons obtained from [fontawesome](https://fontawesome.com/) were used as the Social media links in the footer section.
- Tinyjpg
  - https://tinyjpg.com/ was used to reduce the size of the images used throughout the website
- Favicon.io
  - favicon files were created at [favicon.io](fahttps://favicon.io/favicon-converter/)
- balsamiq
  - wireframes were created using balsamiq from [balsamiq.com](https://balsamiq.com/wireframes/desktop/#)


## Testing 

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome, Edge, Firefox and Opera browsers.

Steps to test:

1. Open browser and navigate to [History of Michael Collins](https://jamie33o.github.io/history-of-michael-collins/ )
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width
6. Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched. No horizontal scroll is present. No elements overlap.

Actual:

Website behaved as expected with the exception of some images been to large at 320px.

Website was also opened on the following devices and no responsive issues were seen:

Oukitel C21 Pro
TCL 30 Pro
iPhone SE
Samsung Galaxy Tablet

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjamie33o.github.io%2Fhistory-of-michael-collins%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fjamie33o.github.io%2Fhistory-of-michael-collins%2F&usermedium=all&vextwarning=&warning=1)

![W3C validator homepage](docs/testing/w3c-validator-homepage.png)
![W3C validator question/add info](docs/testing/w3c-validator-question-add-info.png)
![W3C validator gallery](docs/testing/w3c-validator-question-gallery.png)
![W3C jigsaw validator css](docs/testing/w3c-validator-css.png)


### Accessibility

[Wave Accessibility](https://wave.webaim.org/) tool was used throughout development and for final testing of the deployed website to check for any aid accessibility testing.

Testing was focused to ensure the following criteria were met:

All forms have associated labels so that this is read out on a screen reader to users
Color contrasts meet a minimum ratio as specified in WCAG 2.1 Contrast Guidelines
Heading levels are not missed or skipped to ensure the importance of content is relayed correctly to the end user
All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions
All not textual content had alternative text or titles so descriptions are read out to screen readers
HTML page lang attribute has been set
Aria properties have been implemented correctly
WCAG 2.1 Coding best practices being followed


Manual tests were also performed to ensure the website was accessible as possible and an accessibility issue was identified.

Issue #1: Social media links in the footer had no text to explain what they link to.

Fix: added aria-label with name of site they link too.

Issue #2: some alt text for images was'nt descriptive.

Fix: change the alt text to better describe the image.

Issue #3: On the homepage the there was h3 tag before the h2 tag.

Fix: change the h3 to h2 and resized the text with css.

### LightHouse Testing

![Homepage](docs/testing/lighthouse-homepage.png)
![gallery](docs/testing/lighthouse-gallery.png)
![question/add info](docs/testing/lighthouse-form-page.png)

### Functional Testing

**Navigation Links**

Testing was performed to ensure all navigation links on the respective pages, navigated to the correct pages as per design. This was done by clicking on the navigation links on each page.

| Navigation Link   | Page to Load    |
| ---------------   | --------------- |
| Home              | index.html      |
| Gallery           | gallery.html    |
| Question/add info | question-add-info.html    |

Links on all pages navigated to the correct pages as exptected.

**Form Testing**

The form on the home page was tested to ensure it functioned as expected when correct data was input and when incorrect data was input. The following test scenarios were covered:

_Scenario One - Correct Inputs_

Steps to test:

1. Navigate to [History of Michael Collins - Questions/Add info](https://jamie33o.github.io/history-of-michael-collins/questions-add-info.html)
2. Scroll down to the form and input the following data:
   - Name: John doe
   - Email: doe.john@test.com
   - Comment: This is a test.
3. Click Submit
4. User should be redirected to thank-you.html confirmation page

Expected:

Form submits with no warnings or errors and user is redirected to contact.html confirmation page.

Actual:

Website behaved as expected with no errors or warnings and redirected to contact.html.

_Scenario Two - Missing Required Field_

Steps to test:

1. Navigate to [History of Michael Collins - Questions/Add info](https://jamie33o.github.io/history-of-michael-collins/questions-add-info.html)
2. Scroll down to the form and input the following data:
   - Name:
   - Email: doe.john@test.com
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.


**Footer Social Media Icons / Links**

Testing was performed on the Font Awesome Social Media icons in the footer to ensure that each one opened in a new tab and that each one had a hover affect of the orange branding color.

Each item opened a new tab when clicked as expected and correct hover color was present.


### Unfixed Bugs

1. The form section is currently not able to be submitted as it needs javascript and python to send the data and as this website is for education purposes we have not learnt these languages yet, but will be updated in the future.

2. On gallery.html lighthouse results for best practices are 85% because of embeded youtube videos.



## Deployment

### Version Control
The site was created using the Visual Studio code editor and pushed to github to the remote repository ‘history-of-michael-collins’.

The following git commands were used throughout development to push code to the remote repo:

- git add <file> - This command was used to add the file(s) to the staging area before they are committed.

- git commit -m “commit message” - This command was used to commit changes to the local repository queue ready for the final step.

- git push - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages
- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the menu on left select 'Pages'
  - From the source section drop-down menu, select the Branch: main
  - Click 'Save'
  - A live link will be displayed in a green banner when published successfully.

The live link can be found here - https://jamie33o.github.io/history-of-michael-collins/ 



### Clone the Repository Code Locally
- Navigate to the GitHub Repository you want to clone to use locally:
  - Click on the code drop down button
  - Click on HTTPS
  - Copy the repository link to the clipboard
  - Open your IDE of choice (git must be installed for the next steps)
  - Type git clone copied-git-url into the IDE terminal
  - The project will now of been cloned on your local machine for use.

## Credits 

Here we credit everywhere we have got content for the website and any code that was taken from other sources.

### Content 

- The text for the Home page was taken [wikipedia](https://en.wikipedia.org/wiki/Michael_Collins_(Irish_leader)).
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- Videos in the gallery where taken from Youtube here is the links to eace channel in order
 1. [Michael Collins House Museum](https://www.youtube.com/@michaelcollinshouse)
 2. [Diolún Ó hUigínn](https://www.youtube.com/@Dioluin)
 3. [Documentales Olvidados](https://www.youtube.com/@Documentalesolvidado)

- The images in the gallery were taken from these pages in order
 1. [Michael collins statue in cork](https://laracurtis.blogspot.com/2021/04/michael-collins-ireland-history-michael.html)
 2. [Micheal collins giving a speech](https://www.pinterest.jp/pin/museum-all-about-michael-collins-to-open-on-easter-saturday--128915608061888154/)
 3. [Michael collins being interviewed by press](https://www.pinterest.com/pin/421086633909672221/)
 4. [An eerie last photo of collins, worried about the camera's shutter noise as he's grabbing for his gun](https://www.pinterest.com/pin/454300681146697950/)

### Code 

- Part of the code in the footer was taken from the love running walktrough tutorial on Code Institue.
- Part of the code in the form section was taken from love running walktrough tutorial on Code Institue.

Thank you for visiting the History Michael Collins website! We hope that this website enriches your understanding of this remarkable figure and his significant contributions to Irish history.