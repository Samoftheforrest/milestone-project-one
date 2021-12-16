# Arist Page - SAWYL

## Goals for project
Every modern artist needs to have an online presence. It is a fantastic way to keep fans up to date with your work, whether it be new music, tour dates, or merchandise. It can also be a great way for fans, or potential clients, to get in touch.

Here I have created a web page for the fictional artist "SAWYL". This is a place for this artist to display all of their music, merchandise and tour dates; along with a contact form for any fans or clients to get in touch.

Thank you for visiting my project - if you have any questions please feel to contact me via my GitHub contact details.

## Table of contents
- [Arist Page - SAWYL](#arist-page---sawyl)
  * [Goals for project](#goals-for-project)
  * [Table of contents](#table-of-contents)
  * [UX](#ux)
    + [User Goals](#user-goals)
    + [User Stories](#user-stories)
    + [Site Owner's Goals](#site-owner-s-goals)
    + [User Requirements and Expectations](#user-requirements-and-expectations)
    + [Design choices](#design-choices)
  * [Wireframes](#wireframes)
      - [Desktop Wireframes](#desktop-wireframes)
      - [Tablet Wireframes](#tablet-wireframes)
      - [Mobile Wireframes](#mobile-wireframes)
  * [Features](#features)
    + [Existing Features](#existing-features)
    + [Features to be implemented](#features-to-be-implemented)
  * [Technologies used](#technologies-used)
    + [Languages](#languages)
    + [Frameworks](#frameworks)
  * [Testing](#testing)
    + [Access to Artist's Discography](#access-to-artists-discography)
    + [Access to Merchandise](#access-to-merchandise)
    + [Tour Dates Visibility](#tour-dates-visibility)
    + [Get in Contact with the Artist](#get-in-contact-with-the-artist)
    + [Mobile Responsivity](#mobile-responsivity)
  * [Bugs](#bugs)
    + [Smooth scrolling between sections not working](#smooth-scrolling-between-sections-not-working)
    + [Bootstrap mobile menu not displaying when toggler button clicked](#bootstrap-mobile-menu-not-displaying-when-toggler-button-clicked)
    + [Bootstrap layout not applying to iPad pro size devices](#bootstrap-layout-not-applying-to-ipad-pro-size-devices)
  * [Deployment](#deployment)
    + [Local Deployment](#local-deployment)
  * [Credits](#credits)
    + [Navbar toggler button styling](#navbar-toggler-button-styling)
    + [Smooth scrolling](#smooth-scrolling)
    + [Object-fit property for imagess](#object-fit-property-for-imagess)
    + [General Thanks](#general-thanks)
## UX
### User Goals
- The website must be responsive, working on a range of screen sizes (desktop, tablet, phones, etc.).
- To be able to easily find out about the artist's latest releases, tour dates, and merchandise.
- I wanted to have a clear flow of information on the page.

### User Stories
- As a user, I want to be able to access the artist's discography
- As a user, I want to be able to access the artist's merchandise easily.
- As a user, I would like to see the artist's upcoming tour dates easily.
- As a user, I would like to be able to get in contact with the artist - including links to social media.
- As a user, I want to to be able to access this website on different devices.

### Site Owner's Goals
- To have a visually appealing website that allows users to keep up to date with the artist.
- For the website to have give the user a positive experience, with all functionality working smoothly.
- For all the information to be contained within one page, with easily navigable sections.
- For the website to reflect the artist, so that any users who visit the site have a clear idea of the artist's style.

### User Requirements and Expectations
**Requirements**
- To have an easily navigable page, using only a few nav buttons.
- When nav buttons are clicked, the page should smoothly scroll to the appropriate section.
- For each section to have a clear title that demarcates the section's purpose.
- For all of the site's links to be functional.

**Expectations**
- For the page to have a clear flow of information.
- For all links to external sites should open in a new tab.
- To have a visually appealing page.
- For the page to reflect the style of the artist.

### Design choices

I used [Coolors](https://coolors.co/) to create my colour scheme. The artist's style of music is slow and melancholy - I wanted this to be reflected through the colour choices. I used hues of blue and white for the majority of the page, to evoke feelings of coldness. However, I did contrast this colour by adding in red sparsely to highlight the artist's tour dates - the artist expressed their desire to expand their ticket sales, so I wanted to choose a colour that demanded attention.

Below, I will go into my colour selection more thoroughly.

![Colour palette](colour-palette.png)

- `#002855`: I decided to use this colour as the main background for the page as I felt this cold hue was inkeeping with the artist's style.
- `#0353A4`: This colour was used for the page's buttons. I felt that it was inkeeping enough with the overall style of the page, while being different enough from the background as to clearly highlight all buttons.
- `#EB3E3E`: The artist expressed interest in directing people toward their tour dates, to achieve this I used red to contrast from the background. Also, I felt that this colour paired well with the image displayed in the tour section.
- `#D6D6D6`: I used this colour for the hover effects on all icons - I felt that it was dark enough to clearly show the user that they had highlighted the current icon.
- `#FAFAFA`: This culture was used for all of the text on the page. I checked the colour contrast of this colour against the background colour using [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) - which returned a contrast ratio of 14.02:1, which complies with the WCAG AAA requirements (which is 7:1).

**Fonts**

I used [Google Fonts](https://fonts.google.com/) to select the page's fonts. For the page titles, I used [Roboto Condensed](https://fonts.google.com/specimen/Roboto+Condensed?query=roboto+cond) and for all other text, I used [Cabin](https://fonts.google.com/specimen/Cabin?query=cabin). I found this font pairing on [Font Pair](https://www.fontpair.co/).

## Wireframes

I created the following wireframes using [Figma](https://www.figma.com)

These wireframes demonstrate how to the information displayed varies across screen sizes - including any potential hidden content.

#### Desktop Wireframes
- [Main section](wireframes/desktop-main.png)
- [Discography](wireframes/desktop-discography.png)
- [Tour](wireframes/desktop-tour.png)
- [Shop](wireframes/desktop-shop.png)
- [Contact](wireframes/desktop-contact.png)

#### Tablet Wireframes
- [Main section](wireframes/tablet-main.png)
- [Discography](wireframes/tablet-discography.png)
- [Tour](wireframes/tablet-tour.png)
- [Shop](wireframes/tablet-shop.png)
- [Contact](wireframes/tablet-contact.png)

#### Mobile Wireframes
- [Main section](wireframes/phone-main.png)
- [Discography](wireframes/phone-discography.png)
- [Tour](wireframes/phone-tour.png)
- [Shop](wireframes/phone-shop.png)
- [Contact](wireframes/phone-contact.png)

## Features

### Existing Features
- Smooth scroll functionality from nav menu.

### Features to be implemented
- To allow users to click on different images in the shop sections to go directly to the different categories within the shop.
- To have an audio player on each album card to play a demo of each album.
- When a user visits the site, the tour date that is closest to them geographically should be highlighted in a different colour.

## Technologies used
### Languages
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

### Frameworks
- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)

## Testing
 
 ### **Access to Artist's Discography**

 **User Story: As a user, I want to be able to access the artist's discography.**
 - **Plan**
 I want to create three sections on the page in which the user can be redirected to the artist's discography: either to their latest album in the main section (at the top of the page), to a selection of featured album (in the discography section), or to the remainder of their music in the shop section - within each of these sections, I will add either a button or icon that will lead them to the artist's discography when clicked.

 - **Implementation**
 In each of these sections, I included links that leads to the artist's music in a different ways: the main section and discography section give the user options to either stream the artist's music by taking them to Spotify, or to buy the album directly from Bandcamp; then, in the shop section, the link takes the user to the artist's Big Cartel page.

 - **Test**
 I went through all of the possible links that could lead to the artist's discography and clicked them five times to ensure that they took the user to the correct page consistently.

 - **Result**
 All of the links took me to the appropriate page when clicked each time.

 - **Verdict**
 This test passed all success criteria.
 
 ### **Access to Merchandise**
 **As a user, I want to be able to access the artist's merchandise easily.**

 - **Plan**
 I want the user to be able to be redirected to the artist's external merchandise store on Big Cartel when they click on the **_Shop Now_** button in the shop section.
 
 - **Implementation**
 In the shop section of the website, I added a clear **_Shop Now_** button which includes a link to the Big Cartel page (which opens in a new tab).

 - **Test**
 I clicked this link as part of the test above ('Access to Artist's Discography') - I clicked the **_Shop Now_** button five times in this test to ensure I was redirected to the correct page without issue.

 - **Result**
 I was taken to the correct web page (Big Cartel) on all five occaisons.

 - **Verdict**
 This test has been successful.

 ### **Tour Dates Visibility**
 **As a user, I would like to see the artist's upcoming tour dates easily.**

 - **Plan**
 I wanted to give the artist's tour dates their own clear space so that anyone who is reading this section is not distracted by any other content onscreen.
 
 - **Implementation**
 I created a section dedicated to displaying the artist's most recent tour dates - which includes an attention grabbing image in the hopes of getting users to stop in this section and to consider going to see the artist live.
 
 - **Test**
 For this test, I enlisted the help of my partner Laura - I wrote her a short quiz asking which venue the artist was playing in on a particular date, and asked her if she could find the information from the website easily.
 
 - **Result**
 The quiz was returned to me with all the answers correct - my partner's feedback was that the fact that the tour dates have their own section, with a clear title makes them very easy to find, and that the simple layout makes them easily understandable.
 
 - **Verdict**
 This test has been successful.

 ### **Get in Contact with the Artist**
 **As a user, I would like to be able to get in contact with the artist - including links to social media.**
 
 - **Plan**
 I want to add a section to the page which contains two ways to get in contact with the artist: either through a contact form, or through links to the artist's social media accounts.
 
 - **Implementation**
 I created a contact section of the page dedicated to containing a contact form, as well as links to the artist's social media.
 
 - **Test**
 I will fill out and "submit" the form five separate times to ensure that the appropriate information is processed properly. Additionally, I will click on the social media links five times to ensure that they take the user to the correct webpage consistently.
 
 - **Result**
 The contact form outputted the correct information all five times, and all of the social media links took me to the correct pages.
 
 - **Verdict**
 Both tests have met their success criteria.

 ### **Mobile Responsivity**
 **As a user, I want to to be able to access this website on different devices.**
 
 - **Plan**
 I want the flow of information on the page, as well as the actual content on the page, to change dependent on the screen size of the device it is being viewed upon.
 
 - **Implementation**
 I used a combination of Bootstrap classes and CSS media queries in order to change the flow of content on the page dependent on the screen size - I did this in three ways:
 - To change the order of the content: on smaller devices, I adopted a column view in which the content is one on top of another, whereas on larger devices, some of the content is ordered horizontally.
 - To remove content on smaller pages: to improve the readability of the page on smaller devices, I decided to only keep the most relevant information.
 - To alter the order of information on smaller screens: using the Bootstrap "order" class I rearranged some of the content to improve the flow of information.
 
 - **Test**
 I will use the [Chrome Developer Tools](https://developer.chrome.com/docs/devtools/) to resize my browser to emulate three mobile devices (Galaxy S5, iPhone X, Pixel 2) and two tablet devices (iPad, iPad pro) and compare the page layout to the wireframes I created.
 
 - **Result**
 The pages rearranged as expected on four of the devices (Galaxy S5, iPhone X, Pixel 2 and iPad), but did not on the iPad Pro - on this device, it displays the desktop layout where it is meant to display the tablet view.
 
 - **Verdict**
I will need to amend the Bootstrap classes on the page to make sure that the desktop layout displays on screens larger than the XL Bootstrap breakpoint. I will add this issue to "Bugs" to make sure it is remedied.

After making the amendments mentioned above - the page's layout on the iPad Pro is now displaying as expected.

## Bugs
### Smooth scrolling between sections not working

- **Bug**  
When a user clicks on one of the nav links, to move to another section of the page, it does nothing. I have added the "scroll behaviour: smooth" property to the html tag within the css - this leads me to believe that the issue will be found within the HTML markup itself.

- **Fix**  
When I examined the HTML markup of the nav ul, I came to the source of the problem - the href attribute contained no `#` before the id name of the section it would move to. I added the `#` in and tested each of the links, which all began to scroll smoothly to the appropriate section.

- **Verdict**  
This feature of the page is now working as expected.

### Bootstrap mobile menu not displaying when toggler button clicked

- **Bug**  
On smaller screen sizes, the navigation links become contained within a burger menu, which should open when the burger button is clicked. However, clicking on the button does not reveal the nav.

- **Fix**  
During a discussion with my mentor, he mentioned to me that the Bootstrap css link and js script I was using came from different versions of Bootstrap - and that this was not best practice as it could cause issues. I rectified this by making sure all appropriate Bootstrap links/scripts used the same version (4.6.0). After doing this, the burger menu now opens consistently.

- **Verdict**  
This bug has been resolved, and the element now works as expected.

### Bootstrap layout not applying to iPad pro size devices

- **Bug**  
When designing this page, I created wireframes for mobile, tablet, and desktop devices - the iPad Pro should display the tablet layout, but it currently displays the desktop layout.

- **Fix**  
I needed to change the breakpoint between tablet and desktop devices - making it higher to that the tablet breakpoint will include the width dimensions of iPad Pros (1024px). I did this by changing all instances of the `lg` Botostrap class in my HTML markup to the `xl` Bootstrap class. This increased the breakpoint of the desktop layout to >1200px - after making this change, the iPad Pro displays the tablet view as intended.

- **Verdict**  
The bug has now been resolved, and the appropriate layout is displayed on iPad Pros.

## Deployment

### Local Deployment

I created this project using [GitHub](https://github.com/) to store the code and [Gitpod](https://www.gitpod.io/) as my code editor. To store my Gitpod code in GitHub, I used git commits followed by git pushing the code to the repository.

This page is deployed using [GitHub Pages](https://pages.github.com/).

## Credits
### Navbar toggler button styling
I used [this video](https://www.youtube.com/watch?v=45QSuJaHEss&ab_channel=ADesignerWhoCodes) to help me find a suitable strategy for styling the Bootstrap navbar toggler button.

Following a meeting with my mentor, we decided a more efficient way to style the navbar toggler button was to replace the toggler icon with [Font Awesome - bars](https://fontawesome.com/v5.15/icons/bars) icon - which can be easily styled using the `color` property.

### Smooth scrolling
[This Stack Overflow question](https://stackoverflow.com/questions/53543484/smooth-scrolling-in-css) showed me how to easily implement a smooth scroll feature on my own website.

### Object-fit property for imagess
I discovered how to use the `object-fit: cover` property to make images fill their container after reading this [Stack Overflow](https://stackoverflow.com/questions/34247337/object-fit-not-affecting-images) question. I used what I learned from this thread on several of the images on my page.

### General Thanks
- I would like to thank my mentor, [Simen](https://github.com/Eventyret), for all of his support and guidance throughout this project.
- I would like to thank [Unsplash](https://unsplash.com/) for providing a fantastic selection of free-to-use images.
- I would like to thank my partner, Laura, for testing my website and providing feedback for improvements.