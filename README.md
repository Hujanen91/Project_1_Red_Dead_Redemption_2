# Red Dead Redemption 2 Fan Page

This website is intended to provide information in different forms about Rockstars game Red Dead Redemption 2 that was released on different platforms in October 2018.
The intention is to provide a simple website that is easy to navigate, that provides information about the game in video, image and text. There's simple navigations, clear contrast between the colors on the webpage and the background. View the live site here [here](https://hujanen91.github.io/Code_Institute_Project_1/)

![Mockup](docs/readme_images/Mockup.png)

## Features

### Site wide

* Navigation Menu
  * Contains links to the Home, The gang, Screenshots, Game map and Contact pages and will be responsive on all devices.
  * This will allow users to easily navigate between the pages within the site on any size device.

![Nav Menu](docs/readme_images/navigationbar.png)
![Nav Menu](docs/readme_images/navbar-hover-effect.png)


* Header
   * The main element that you see when entering the website is a picture designed by Rockstar containing the image of 7 men walking on a row holding guns with the text "Rockstar games presents Red Dead Redemption 2" above them. You'll know immediatly what the website is going to be about. The image sits in the header tag.
![Header](docs/readme_images/header-img.png)

* Footer
  * This will contain icons as links to social media websites that will open in new tabs. Icons will be accessible to the visually impaired who may be using a screen reader, by the use of aria labels. The second part of the footer will contain contact information for 'Taco'.
  * This will allow the user to follow 'Taco' on various social media where they can get more up to date information that may not be displayed on the website. The contact information will allow the user to contact 'Taco' directly.

![Footer](docs/readme_images/footer.png)

* Favicon
  * A site wide favicon will be implemented with the Hair O' The Dog clubs emblem.
  * This will provide an image in the the tabs header to allow the user to easily identify the website if they have multiple tabs open.

![Favicon](docs/readme_images/android-chrome-192x192.png)

* 404 Page
  * A 404 page will be implemented and will display if a user navigates to a broken link.
  * The 404 page will allow the user to easily navigate back to the main website if they direct to a broken link / missing page, without the need  of the browsers back button.

![404](docs/readme_images/404_page.JPG)

### Landing Page

* Landing page image
  * This will be a collection of favourite images from some of 'Taco's Travels. Images will change on a timer.
  * This will help to immediately show the user what the website is about and help to animate the page.

![Landing Page Image](docs/readme_images/landing_page_image.JPG)

* Website information on 'Taco'
  * Information about 'Taco' and the websites purpose including an image of 'Taco' on his travels.
  * This information lets the user know what the site is about.

![Bio](docs/readme_images/about_me.JPG)

* Contact form
  * A contact form will be implemented to allow users to contact 'Taco'. The form will consist of the following fields and attributes:
    * First Name (required, type=text)
    * Last Name (required, type=text)
    * Email (required, type=email)
    * Message (required, type=textarea)
  * On successful submission of the contact form, the user will be navigated to contact.html displaying a success message.
  * This will allow user to contact 'Taco' if they have any queiries about travel destinations, charity events, club information or maybe to join him on some of his travels.

![Contact Form](docs/readme_images/contact_form.JPG)

![Contact Form Received](docs/readme_images/contact_form_received.JPG)

### Gallery Page

* Gallery
  * The gallery will provide the user with photos of 'Taco's Motorcycle adventures from various trips and charity events. The gallery will be fully     responsive on all devices and allows the user to filter by categories provided in a sub navigation.
  * This will allow users that are interested in 'Taco's Travels to filter items based on the category they wish to be displayed. As the gallery is responsive it will allow the user to view content from any device.

![Gallery](docs/readme_images/gallery.JPG)

### Adventures

* Adventure Summary
  * Sections containing 2 photos of the trip, a paragraph about the trip and a link to the gallery page to see more photos.
  * The sections will give the user an overview of the adventures that Taco has been on and the links will take the user to the gallery page where the user can view all the pictures that have been uplaoded for that trip.

![Adventure Summary](docs/readme_images/adventures_summary.JPG)

* More details dropdown
  * Hidden sections at the end of each Adventure Summary that will show a more detailed description of the trip which may include more details about longer trips and information about places visited along the way.
  * These section will be hidden by default so that user can only see the summaries on the page when loaded but the user will have ability with this feature to click and view more details at the end of the summary. This will allow user to easily scroll through the page and only view details of trips that they want to read more about.

![Details Dropdown](docs/readme_images/details_dropdown.JPG)

### Existing Features

* Responsive design
* Hidden interactive sections on adventure page
* Responsive gallery with filtering
* Contact form and success page
* 3 Adventure trips and information

### Features Left to Implement

* As a future enhancement, the contact form will be updated with javascript to send an email to Taco with the contact information.

* Google map interaction to be added to the Adventures page instead of screen shots of the map.

## Design

### Wireframes

<br>
Home page
<br><br>

![Home Page large screen](docs/readme_images/home_wireframe.JPG)

![Home Page small screen](docs/readme_images/home_mobile_wireframe.JPG)
<br><br>
Contact form successful submission page.
<br><br>
![Contact form submission success](docs/readme_images/contact_wireframe.JPG)

![Contact form submission success](docs/readme_images/contact_mobile_wireframe.JPG)

Adventures page
<br><br>
![Adventures page large screen](docs/readme_images/adventures_wireframe.JPG)

![Adventures page small screen](docs/readme_images/adventures_mobile_wireframe.JPG)

Gallery page
<br><br>
![Gallery page large screen](docs/readme_images/gallery_wireframe.JPG)

![Gallery page small screen](docs/readme_images/gallery_mobile.JPG)

404 page
<br><br>
![Gallery page large screen](docs/readme_images/404_wireframe.JPG)

![Gallery page small screen](docs/readme_images/404_mobile_wireframe.JPG)
<br><br><br><br>

## Technologies

* HTML
  * The structure of the Website was developed using HTML as the main language.
* CSS
  * The Website was styled using custom CSS in an external file.
* Visual Studio Code
  * The website was developed using Visual Studio Code IDE
* GitHub
  * Source code is hosted on GitHub and delpoyed using Git Pages.
* Git
  * Used to commit and push code during the development opf the Website
* Font Awesome
  * Icons obtained from <https://fontawesome.com/> were used as the Social media links in the footer section.
* Tinyjpg
  * <https://tinyjpg.com/> was used to reduce the size of the images used throughout the website
* Favicon.io
  * favicon files were created at <https://favicon.io/favicon-converter/>
* balsamiq
  * wireframes were created using balsamiq from <https://balsamiq.com/wireframes/desktop/#>

## Testing

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome, Edge, Firefox and Opera browsers.

Steps to test:

1. Open browser and navigate to [Tacos Travels](https://gareth-mcgirr.github.io/tacos-travels/)
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width

Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched.
No horizontal scroll is present.
No elements overlap.

Actual:

Website behaved as expected with the exception of switching to landscape view in Mozilla Firefox. Details can be found in [Unfixed Bugs](#unfixed-bugs)

Website was also opened on the following devices and no responsive issues were seen:

* Oukitel C21 Pro
* TCL 30 Pro
* iPhone SE
* Samsung Galaxy Tablet

### Accessibility

[Wave Accessibility](https://wave.webaim.org/) tool was used throughout development and for final testing of the deployed website to check for any aid accessibility testing.

Testing was focused to ensure the following criteria were met:

* All forms have associated labels or aria-labels so that this is read out on a screen reader to users who tab to form inputs
* Color contrasts meet a minimum ratio as specified in [WCAG 2.1 Contrast Guidelines](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)
* Heading levels are not missed or skipped to ensure the importance of content is relayed correctly to the end user
* All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions
* All not textual content had alternative text or titles so descriptions are read out to screen readers
* HTML page lang attribute has been set
* Aria properties have been implemented correctly
* WCAG 2.1 Coding best practices being followed

Manual tests were also performed to ensure the website was accessible as possible and an accessibility issue was identified.

Issue #1: Use of hidden check boxes and labels for the gallery filter and accordion on the gallery page were not accessible via the keyboard due to the property display: none;

Fix: I could not find a way to fix this issue with html and css alone so a tabindex of 0 was added to allow the label to be tabbed to and an onkeypress event to target and click the correct checkbox was implemented. Javascript code was taken from this [Mozilla Doc](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/click)

Issue #2: After keyboard controls were implemented, while testing the site with windows 'Narrator' screenreader, it was not clearly known what the purpose of the labels/checkboxes were. An aria-label label was added to the labels for screen readers to alert them that the labels were clickable and what their purpose was.

### Lighthouse Testing

![Home](docs/testing/index_lighthouse.JPG)

![Gallery](docs/testing/gallery_lighthouse.JPG)

![Adventures](docs/testing/adventures_lighthouse.JPG)

### Functional Testing

**Navigation Links**

Testing was performed to ensure all navigation links on the respective pages, navigated to the correct pages as per design. This was done by clicking on the navigation links on each page.

| Navigation Link | Page to Load    |
| --------------- | --------------- |
| Home            | index.html      |
| Aventures       | adventures.html |
| Gallery         | gallery.html    |

Links on all pages navigated to the correct pages as exptected.

**Form Testing**

The form on the home page was tested to ensure it functioned as expected when correct data was input and when incorrect data was input. The following test scenarios were covered:

_Scenario One - Correct Inputs_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   * First Name: John
   * Last Name: Doe
   * Email: doe.john@test.com
   * Comment: This is a test.
3. Click Submit
4. User should be redirected to contact.html confirmation page

Expected:

Form submits with no warnings or errors and user is redirected to contact.html confirmation page.

Actual:

Website behaved as expected with no errors or warnings and redirected to contact.html.

_Scenario Two - Missing Required Field First Name_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   * First Name:
   * Last Name: Doe
   * Email: doe.john@test.com
   * Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Three - Missing Required Field Last Name_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   * First Name:John
   * Last Name:
   * Email: doe.john@test.com
   * Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Four - Missing Required Field Email_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   * First Name:John
   * Last Name: Doe
   * Email:
   * Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Six - Incorrect email format_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   * First Name:John
   * Last Name: Doe
   * Email: doe.johntest.com
   * Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that a valid email is required and the format it should be in.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

**Footer Social Media Icons / Links**

Testing was performed on the Font Awesome Social Media icons in the footer to ensure that each one opened in a new tab and that each one had a hover affect of the orange branding color.

Each item opened a new tab when clicked as expected and correct hover color was present.

**Footer Contact Information**

Testing was performed on the phone number in the contact information section of the footer to ensure behaviour was as expected.

_Steps to test Telephone Number_

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Click the phone number in the footer (01 123 456 789)

Expected:

A window is opened asking which device you would like to call from.

Actual:

Behavior was as expected and the window presented me with the following option to call:

* Oukitel Mobile Phone

_Steps to test Email Link_

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Click the email address in the footer (taco@gmail.com)

Expected:

A windows popup is displayed asking what application you would like to send a mail from or your default email application is opened.

Actual:

Behavior was as expected and my outlook application was opened ready to send an email to the target address.

### Validator Testing

* HTML
  * No errors were returned when passing through the official [W3C validator](https://validator.w3.org)

![Contact HTML Validator Results](docs/testing/contact_validator.JPG)

![Avdentures HTML Validator Results](docs/testing/adventures_validator.JPG)

![Home HTML Validator Results](docs/testing/home_validator.JPG)

![Gallery HTML Validator Results](docs/testing/gallery_validator.JPG)

![404 HTML Validator Results](docs/testing/404_validator.JPG)

* CSS
  * No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org)

![CSS Validator Results](docs/testing/css_validator.JPG)

### Unfixed Bugs

Responsiveness of the website worked on all devices, screen sizes and orientation with the exception of landscape orientation on mozilla firefox. I was unable to resolve this bug on time but will address in a future release.

## Deployment

### Version Control

The site was created using the Visual Studio code editor and pushed to github to the remote repository ‘tacos-travels’.

The following git commands were used throughout development to push code to the remote repo:

```git add <file>``` - This command was used to add the file(s) to the staging area before they are committed.

```git commit -m “commit message”``` - This command was used to commit changes to the local repository queue ready for the final step.

```git push``` - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages

* The site was deployed to GitHub pages. The steps to deploy are as follows:
  * In the GitHub repository, navigate to the Settings tab
  * From the menu on left select 'Pages'
  * From the source section drop-down menu, select the Branch: main
  * Click 'Save'
  * A live link will be displayed in a green banner when published successfully.

The live link can be found here - <https://gareth-mcgirr.github.io/tacos-travels/>

### Clone the Repository Code Locally

Navigate to the GitHub Repository you want to clone to use locally:

* Click on the code drop down button
* Click on HTTPS
* Copy the repository link to the clipboard
* Open your IDE of choice (git must be installed for the next steps)
* Type git clone copied-git-url into the IDE terminal

The project will now of been cloned on your local machine for use.

## Credits

* [Accordion without javascript](https://supfort.com/pure-css-accordion-without-javascript)
  * Code was used from this site to create the accordian effect on the adventures page sections for the hidden sections for each days travels. Styles were changed to suit styling on my Website.
* [Youtube Gallery Filter Tutorial](https://www.youtube.com/watch?v=U-CujW5OlW0)
  * Gallery page was created with inspiration from this video. I adapted code to use flexbox rather than css grid to make the page responsive on every device.

### Content

All content with the exception of those listed in the Media section of this document was owned by Hair O'The Dog club members Rocket and Taco. Permission was granted from Rocket to use the images.

### Media

Website Logo was created by my wife [Daisy McGirr](https://github.com/Daisy-McG) using Canva.

Maps on the adventure page were from google maps timeline.
