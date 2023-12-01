# West Cork Beekeeping

This website is designed to be responsive for users visiting on different-sized devices. It enables users to learn about bees and beekeeping and encourages visitors to register for beekeeping courses.

![Amiresponsive Screenshot](placholder/directory/image.png)

Live website on Github Pages: [West Cork Beekeeping](https://simonhw.github.io/beekeeping/index)

![Github last commit](https://img.shields.io/github/last-commit/simonhw/beekeeping) 
![W3C Validation](https://img.shields.io/w3c-validation/html?targetUrl=https%3A%2F%2Fsimonhw.github.io%2Fbeekeeping%2Findex)

## Contents
- [User Experience](#User-Experience)
    - [Initial Discussion](#Initial-Discussion)
    - [User Stories](#User-Stories)
- [Deployment](#Deployment)
  - [Local Deployment](#Local-Deployment)
    - [Forking](#Forking)
    - [Cloning](#Cloning)
- [Credits](#Credits)
- [Acknowledgements](#Acknowledgements)

## User Experience

### Initial Discussion
West Cork Beekeeping is a site that promotes interest in beekeeping in the West Cork area. The goal of the site is to generate interest in the environmental importance of the honey bee and encourage visitors to the site to register for beekeeping courses run by the owners of the website. The owners raise funding to keep promoting awareness of the honey bee by running for-profit training courses and selling a small range of relevant products. 

### User Stories

#### First-time Visitor Goals
* To understand what the purpose of the website is.
* To easily navigate between the pages and find what I'm looking for.
* To be able to contact the owners of the website for more information.

#### Returning Visitor Goals
* To be able to easily locate information previously found.
* To find up to date information on beekeeping courses.
* To find out where the website owners are based.
* To be able to purchase beekeeping equipment I need.

#### Frequent Visitor Goals
* To be able to purchase honey when I need to.

## Features

The website is comprised of six pages. Three are accessible from the main navigation bar: the Home page, Courses page, and Shop Page. The fourth is the Form page, accessible via the call to action button at the bottom of each of the above three pages, and also via links in the list of available courses. The Fifth page is the Thank You page which the user sees once they complete the form itself. The sixth and final page is a 404 page.

All pages on the website have:
- A navigation bar at the top allowing the user to move between the three main pages. As there are only three pages, the same format is used for the navigation bar on mobile screens. It was decided that the use of a dropdown menu by clicking a burger icon detracted from the aesthetic look of the header with its background image and centred heading.
- A footer at the bottom of the page containing three icon links to a phone number, email, and Google Maps location. This was determined to be more beneficial to the user than social media links and tied in well with the goals of the website to encourage users to get in touch and register for beekeeping courses.

The Home page has:
- A heading welcoming the user to the site followed by a summary of the motivation and intentions of the website owners. This immediately gives the user an idea of what to expect from the rest of the website. A picture of three beekeepers posing in their suits underneath this paragraph conveys a sense of fun and camaraderie to the user.
- A section briefly describing the role honey bees play in the environment and the challenges currently faced by them. This section ends with a call-to-action of sorts and places at the front of the user's mind the idea that becoming a beekeeper is a noble and worthwhile pursuit. A closeup image of a bee collecting nectar from a flower is nestled between the two paragraphs of this section. Its bright colours and focus on the bee itself should evoke thoughts about the beauty and importance of the honey bee in nature while also making the user think about its fragility as a small creature worthy of our care.
- A third and final section consisting of two sets of short descriptive sentences and associated images and headings. These two sections invite the user to either navigate to the Courses page to learn more about the beekeeping courses, or to visit the Shop page to purchase honey. The images are the links, and when viewed on mobiles and tablets, the final sentence says "*Tap the image to learn more*", while on desktops it says "*Click the image the learn more*". This was achieved with the use of spans.
- At the bottom of this page and the two other main pages, a call to action link that takes the user directly to the Form page to register for a beekeeping course. This link allows a returning user to navigate directly to the registration form without having to click other links to get there.

The Courses page has:
- A section listing the two different levels of courses offered. Beginner courses are listed first with information on the duration and times the courses start. An overview of the structure of the courses follows with distinct boxes listing upcoming courses. Courses that are sold out are still shown on this page to convey to the user that there is already interest and that they should not delay in booking their place. The Intermediate course information is presented next with the same structure as described above.
- A second section that aims to convince the undecided user that they should register their interest in an upcoming course. Four reasons to become a beekeeper are listed with accompanying imagery chosen to invoke thoughts of fun, relaxation, peacefulness, and enjoyment.
- A final paragraph that reminds the user that becoming a beekeeper requires time and effort but reassures them that it is a worthwhile endeavour.

The Shop page has:
- An introductory paragraph that informs the user of the payment process for products on this page as well as delivery terms and discounts for course graduates. A contact number and email are listed, distinct from each other, below the paragraph to offer the returning user quick access should they desire to contact the owners.
- Boxes listing the available products and short descriptions with accompanying imagery. These boxes will be displayed in single or multiple columns based on the screen width of the user.

The Form page has:
- A simple layout with only the minimum necessary information sought from the user. This style of layout is intended to make the user experience straightforward and quick, as very few people want to spend time filling out multiple form fields.
- Input fields that only accept the correct type of input, including a date of birth field which does not allow a user under the age of 18 to register.
- Radio buttons which limit the user to only registering for one available course at a time. The next available beginner course is selected by default.
- A button underneath the fieldset which submits the user's details only if all input fields have been correctly completed.

The Thank You page has:

The 404 page has:

## Deployment

Github Pages was used to deploy the live version of the website. The steps followed to do this were as follows:
  1. Log in or sign up to Github.
  2. Navigate to the repository for [West Cork Beekeeping](https://github.com/simonhw/beekeeping).
  3. Click the Settings link near the top of the page.
  4. Click on the Pages link on the left-hand side under Code and Automation.
  5. Under Build and Deployment click the dropdown menu for Branches and select 'main'. For the Folder dropdown menu, select 'root'.
  6. Click Save to deploy the website on Github Pages.

### Local Deployment
To deploy this project locally on your own device, follow the below steps:
#### Forking 
1. Log in or sign up to Github.
2. Navigate to the repository for [West Cork Beekeeping](https://github.com/simonhw/beekeeping).
3. Click the Fork button located in the top right part of the webpage.
#### Cloning
1. Log in or sign up to Github.
2. Navigate to the repository for [West Cork Beekeeping](https://github.com/simonhw/beekeeping).
3. Click on the green Code button and select your preferred option of HTTPS, SSH, or GitHub CLI and copy the relevant link.
4. Open the terminal in your IDE and navigate to your directory of choice for this new clone.
5. Type `git clone` into the terminal and paste in your copied link. Press enter.

## Testing

### Automated Testing
[W3C](https://validator.w3.org/) was used to validate the HTML on all website pages and the CSS stylesheet.
- [index.html](https://github.com/simonhw/beekeeping/blob/main/assets/images/readme/testing/w3c-index.PNG) - Passed.
- [courses.html](https://github.com/simonhw/beekeeping/blob/main/assets/images/readme/testing/w3c-courses.PNG) - Passed.
- [shop.html](https://github.com/simonhw/beekeeping/blob/main/assets/images/readme/testing/w3c-shop.PNG) - Passed.
- [form.html](https://github.com/simonhw/beekeeping/blob/main/assets/images/readme/testing/w3c-form.PNG) - Passed.
- [thankyou.html]()
- [404.html]()
- [style.css](https://github.com/simonhw/beekeeping/blob/main/assets/images/readme/testing/w3c-css.PNG) - Passed with no errors.

### Lighthouse
The Lighthouse feature in Chrome Developer Tools was used to test the performace, accessibility, best practices, and search engine optimisation of the website.

#### Desktop 
#### Mobile

## Bugs
### Known Bugs
### Solved Bugs
| # | Bug | Image | Solution |
| --- | --- | --- | --- |
| 1 | While creating the navbar unordered list, there was an unspecified left padding of 40px discovered which was pushing the nav links visually off center. | ![Navbar padding bug](assets/images/readme/bugs/bug001-nav-padding.PNG) | The solution was to force all padding for the element to 0px in the CSS stylesheet. |
|2|The first element in the header (the div containing the navbar) has a value of 5px for margin-top. This eemed to result in pushing the entire header down leaving an empty white space equal to 5px in height. | ![Navbar margin bug](assets/images/readme/bugs/bug002-nav-margin.PNG) | Adding the property `overflow:hidden` to the div resolved the problem. Solution found on [Stack Overflow](https://stackoverflow.com/questions/2680478/margin-top-push-outer-div-down) |
| 3 | When tilting the mobile screen or using larger width displays, the H1 element was finding itself positioned outside the limits of the header. | ![Navbar H1 position bug](assets/images/readme/bugs/bug003-h1-overflow.PNG) | I set the parent div to `display: flex` to ensure it stayed positioned inside the header and also utilised `flex-grow: 2` to visually centre the H1 in the new flex layout. This also seemed to solve Bug #2 when removing the `overflow:hidden` property added above. |

## Credits

### Code Used
Code for the website footer was copied and adapted from the Code Institute Love Running Walkthrough Project.
- [Code Institute - Creating the Footer](https://github.com/Code-Institute-Solutions/love-running-v3/tree/main/3.7-creating-the-footer)

### Content
All code content was written by Simon Henleywillis unless otherwise specified above.

Paragraph text content was generated by ChatGPT and either used as-is or edited by Simon Henleywillis. 

ChatGPT Prompts: [Beekeeping: A Buzzing Hobby](https://chat.openai.com/c/bfaa4756-e755-4300-8aa0-5cff9b9cc20b) ~ [Bee Importance Unveiled](https://chat.openai.com/c/f0fd6c9d-5851-4e78-9275-83b556ab52e9) ~ [Irish Honey Bee Info](https://chat.openai.com/c/a34d83b8-4d55-42c0-b478-e94abeb4d8de)

### Media
All images were found on [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/license). The Pexels website states that "*All photos and videos on Pexels can be downloaded and used for free*" and Unsplash states "*Unsplash photos are made to be used freely. Our license reflects that.*".

- Header Image: [A Beehive in the Garden](https://www.pexels.com/photo/a-beehive-in-the-garden-18014793/)
- Index Page: [Three People in White Suit](https://www.pexels.com/photo/three-people-in-white-suit-2260935/) ~ [A bee is sitting on top of a pink flower](https://www.pexels.com/photo/a-bee-is-sitting-on-top-of-a-pink-flower-17619735/) ~ [Man harvesting honey in apiary with bees](https://www.pexels.com/photo/man-harvesting-honey-in-apiary-with-bees-5247943/) ~ [Honey in Jars on Shelves](https://www.pexels.com/photo/honey-in-jars-on-shelves-12370134/)
- Courses Page: [Women Standing on the Grass While Holding a Bucket](https://www.pexels.com/photo/women-standing-on-the-grass-while-holding-a-bucket-2260936/) ~ [Close-up of a Honeycomb Filled with Honey](https://www.pexels.com/photo/close-up-of-a-honeycomb-filled-with-honey-11655535/) ~ [Bees on Purple Flower](https://www.pexels.com/photo/bees-on-purple-flower-164470/) ~ [Crop man harvesting honey in countryside area](https://www.pexels.com/photo/crop-man-harvesting-honey-in-countryside-area-5247947/)
- Shop Page: [Honey on Glass Jars](https://www.pexels.com/photo/honey-on-glass-jars-13246534/) ~ [bee person planting](https://unsplash.com/photos/bee-person-planting-8_WZU5xKFKk) ~ [Beehives on a Grass Field](https://www.pexels.com/photo/beehives-on-a-grass-field-17543926/) ~ [A Man in a Beekeeper Suit Near Blue Wooden Crates](https://www.pexels.com/photo/a-man-in-a-beekeeper-suit-near-blue-wooden-crates-4505623/) ~ [Close-Up Photo of an Empty Glass Jar on a White Surface](https://www.pexels.com/photo/close-up-photo-of-an-empty-glass-jar-on-a-white-surface-7604265/)