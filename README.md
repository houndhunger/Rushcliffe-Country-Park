# Ruscliffe Country Park
## Purpose of the project
The [Ruscliffe Country Park website](https://houndhunger.github.io/Rushcliffe-Country-Park/) is a user-friendly website providing essential information about Rushcliffe Country Park.
The primary objective is to centralize information about the park and foster a sense of community among users interested in its offerings. The target audience for the website encompasses individuals planning to visit the park in the near future or those seeking information about upcoming events. The website provides a centralized hub for park-related activities, facilities, services, social groups, and other pertinent information. This project serves as a redevelopment effort for the [Rushcliffe Borugh Council - Rushlciffe Country Park website](https://www.rushcliffe.gov.uk/rushcliffecountrypark/).

## User stories
For small screen devices, all user interactions begin by clicking on the burger icon to reveal the navigation menu. The following stories describe user experiences when viewing the website on larger screens with Navigation menu content directly visible.

- Story No. 1: As a new user, I've heard about the park.
    - Upon visiting the park's website, users are greeted with a full-screen image of the lake, capturing the essence of the park's atmosphere. The navigation menu at the top provides further avenues of exploration.
- Story No. 2: As a visiting user, I'm interested in sports opportunities in the park.
    - Users interested in sports can navigate to the Activities section, where they'll find information about various activities, including cycling tracks, trails, and events like parkrun.
- Story No. 3: As a returning user who enjoys the park, I want to arrange a small wedding anniversary party.
    - Users seeking venue options for events like a wedding anniversary party can click on Facilities. This section provides details about venue rentals, leading users to the Rushcliffe Venues website for booking arrangements.
- Story No. 4: As a visiting user, I want to view photo images of the park.
    - Intrigued by the captivating lake image on the homepage, users can navigate to the Gallery section via the navigation menu. Here, they can browse through a collection of park images and enlarge them for a closer view.
- Story No. 5: As a returning user who feels connected to the park, I want to support it and connect with the team.
    - Users interested in supporting the park or getting to know the team can visit the Friends section, where they can join a Facebook group or explore social media links available in the footer under the FOLLOW section.
- Story No. 6: As a visiting user, I want to contact the park owner for business inquiries.
    - Users can easily reach out by clicking on the Contact section, which directs them to a contact form for quick responses. Additionally, the CONTACT email is available in the footer for accessibility on larger screens.

## Structure
The structure of the website includes three main components:
- Header: Contains the Rushcliffe Borough Council logo followed by the Rushcliffe Country Park text aligned to the left. On the right side of the header is the navigation menu.
- Main: Provides the space for the webpage content, where information about the park, activities, facilities, gallery, friends, and contact details are displayed.
- Footer: Displays essential information such as the park's address under "LOCATION," social network references under "FOLLOW," and a link to email under "CONTACT."

The website consists of six web pages:
-Home: A welcoming page introducing users to the park.
-Activities: Information about park activities and relevant links.
-Facilities: Details about park facilities and relevant links.
-Gallery: An image gallery showcasing different areas of the park.
-Friends: Information about park-related social groups and relevant links.
-Contact: A submission form for inquiries and a Google map displaying the park's location.

## Development process
1. The main structure - header, main, and footer - was established and formatted for small screen devices initially.
2. New components were added with a focus on incorporating styles for larger screens.
3. The logo and navigation menu were integrated, ensuring functionality on both small and large devices.
4. The footer was populated with relevant content and formatted appropriately.
5. Individual web pages were created, starting with the Home page featuring a large image, Contact page with a submission form and map, followed by Gallery, Activities, Facilities, and Friends pages. Throughout this process, continuous improvements were made, styles were adjusted, and any encountered bugs were addressed.
6. Attention was given to enhancing accessibility by ensuring all tags had appropriate attributes such as aria-label or alt attributes for images.
7. Thorough testing of the HTML, CSS, and accessibility features was conducted to ensure a seamless and user-friendly experience.

## Features
- Landing page image:
A captivating, full-screen-width picture designed to immerse the user in the serene atmosphere of the park, igniting their curiosity to explore further sections of the website.
- Navigation menu: 
It provides links to all pages of the web. It shows in horizontal format for wider screens. For smaller screens it re-styles to vertical format, hidden initially, then recalled by hitting standard burger favicon provided by [Fonticons - fontawesome](https://fontawesome.com).

![Navigation menu](/readmedocs/feature-images/nav-menu.png)

- The Footer: Displays essential information such as the park's address under "LOCATION," social network references under "FOLLOW," and a link to email under "CONTACT."

![Navigation menu](/readmedocs/feature-images/footer.png)

- Contact Submit form: It's standard Submit form where user have to provide user First Name, Last Name, Email and Message to succesfully Submit the form.

![Navigation menu](/readmedocs/feature-images/form.png)

- Goolge map: I't seems to me visualy pleasing to add Google map of the park location. I have registered for API key with [Google Cloud](https://console.cloud.google.com/apis/credentials) platform and restricted it for security to Google Maps only and deployment website url.

![Navigation menu](/readmedocs/feature-images/map.png)

- Gallery: Continues to what Home page started, to show beutiful views of the park in different locations, time of the year and the day.
Gallery is screen size responsive and progrss to show one, two, three or four columns of images as device viewing screen width grows.
User can click image to view enlarged version

![Navigation menu](/readmedocs/feature-images/gallery.png)
![Navigation menu](/readmedocs/feature-images/gallery-modal.png)

- Video: Is located in Activities page at the top about Dog walking. It's well popular activity thorugh the week in the park.

![Navigation menu](/readmedocs/feature-images/video.png)

- Sections: Activities, Facilities, Friends: Provides relevant information with links to external websites.
The information content is taken from Ruscliffe Borough Council website and restructured where needed.

## Future features
- Cotact form will be upgraded to send an informative copy of the user's submission.
- The gallery modal will be upgraded to include control arrows for browsing through enlarged images directly.

## Typography and color scheme
- Rushcliffe logo defined coorporate colour - main colour: !['#1fb25a'](https://placehold.co/15x15/1fb25a/1fb25a.png) '#1fb25a'
- From this a complementary colour for higlights and headings: ![#a41fb2](https://placehold.co/15x15/a41fb2/a41fb2.png) '#a41fb2'
## Wireframes

Home | Contact
:---: | :---:
![Draft - Balasamiq Wireframe - Home](/readmedocs/wireframe-home.png) | ![Draft - Balasamiq Wireframe - Contact](/readmedocs/wireframe-contact.png)

## Technology
Used were following technologies: 
- Balsamiq V4.7.4, Photopea - logo edit
- HTML, CSS
- [ChatGPT 3.5](https://chat.openai.com/)
- [Fontjoy](https://fontjoy.com/), [Google fonts](https://fonts.google.com/)
- Excel to batch format Gallery content - div and img tags
- [Fonticons - fontawesome](https://fontawesome.com)

## Testing
Web site was tested in Google Chrome browser for various screen sizes.
Web accessibilty evaluation was tested with [Wave](https://wave.webaim.org/):
- [index.html](https://wave.webaim.org/report#/https://houndhunger.github.io/Rushcliffe-Country-Park/index.html)
- [activities.html](https://wave.webaim.org/report#/https://houndhunger.github.io/Rushcliffe-Country-Park/activities.html)
- [facilities.html](https://wave.webaim.org/report#/https://houndhunger.github.io/Rushcliffe-Country-Park/facilities.html)
- [gallery.html](https://wave.webaim.org/report#/https://houndhunger.github.io/Rushcliffe-Country-Park/gallery.html)
- [friends.html](https://wave.webaim.org/report#/https://houndhunger.github.io/Rushcliffe-Country-Park/friends.html)
- [contact.html](https://wave.webaim.org/report#/https://houndhunger.github.io/Rushcliffe-Country-Park/contact.html)

Only one Alert was outstanding - Redundant Link - Logo and Home in Navigation menu have the same link to index.html.

Analyzeing with Lighthouse in Google Chrome was done with following scores:

index.html | gallery.html | index.html - mobile device
:---: | :---: | :---:
![Analyzeing with Lighthouse - index.html](/readmedocs/testing-images/lighthouse-home.png) | ![Analyzeing with Lighthouse - galllery.html](/readmedocs/testing-images/lighthouse-gallery.png) | ![Analyzeing with Lighthouse - index.html for mobile device](/readmedocs/testing-images/lighthouse-mobile.png)

Improvements and issues (8) were caused by 3rd pary extension.

### Code validation
HTML code was validated succesfuly with no errors or warnings:
- [index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhoundhunger.github.io%2FRushcliffe-Country-Park%2Findex.html)
- [activities.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhoundhunger.github.io%2FRushcliffe-Country-Park%2Factivities.html)
- [facilities.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhoundhunger.github.io%2FRushcliffe-Country-Park%2Ffacilities.html)
- [gallery.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhoundhunger.github.io%2FRushcliffe-Country-Park%2Fgallery.html)
- [friends.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhoundhunger.github.io%2FRushcliffe-Country-Park%2Ffriends.html)
- [contact.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fhoundhunger.github.io%2FRushcliffe-Country-Park%2Fcontact.html)

CSS validation with no errors:
- [style.css](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fhoundhunger.github.io%2FRushcliffe-Country-Park%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Test cases

- Home - image cover:
    - When the user accesses the Home page, an image cover scales to 100% width or height to cover the screen. This cover image is responsive to changes in screen size to maintain its coverage. User can scroll down to reach the footer.
    ![Test case - Home](/readmedocs/testing-images/home.png)
---
- Activities:
    - The user opens the Activities section by clicking on "Activities" in the Navigation menu, leading to the display of the Activities and Events section.
    - Within this section, users can play a video by clicking on it, and pause it by clicking again. Video controls are visible at the bottom of the video.
    ![Test case - Activities](/readmedocs/testing-images/activities.png)
    - User can navigate further through relevant links on the webpage.
    ![Test case - Activities](/readmedocs/testing-images/activities2.png)
 ---
- Gallery - size responsiveness and modal:
    ![Test case - Gallery](/readmedocs/feature-images/gallery.png)
    - To access the Gallery, the user clicks on "Gallery" in the Navigation menu. The gallery is then displayed in a column format, with the number of columns adjusting based on the screen size.
    - User can click on a photo in the gallery to enlarge it, displaying a modal with the enlarged photo.
    ![Test case - Gallery - modal](/readmedocs/feature-images/gallery-modal.png)
    - The modal can be closed by clicking anywhere on the screen or on the "X" symbol in the top right corner of the modal for an obvious action.
    - User can then open another photo to display the modal.
 ---
- Facilities:
    - User open the Facilities section by clicking on "Facilities" in the Navigation menu, leading to the display of the Facilities section.
    - User can navigate further through relevant links on the webpage.
    ![Test case - Facilities](/readmedocs/testing-images/facilities.png)
 ---
- Friends:
    - User open the Friends section by clicking on "Friends" in the Navigation menu, leading to the display of the Friends section.
    - User can navigate further through relevant links on the webpage.
    ![Test case - Friends](/readmedocs/testing-images/griends.png)
 ---
- Contact - Size Responsiveness, Form Restrictions, and Form Submission:
    - Users access the Contact section by clicking on "Contact" in the Navigation menu, leading to the display of the Contact section with a Contact form and a Google map displaying the park's location.
    ![Test case - Contact](/readmedocs/testing-images/contact.png)
    - The webpage displays correctly on medium-sized screens like iPad Air.
    ![Test case - Contact - iPad Air](/readmedocs/testing-images/contact-medium-screen.png)
    - The webpage also displays correctly on small screens like Galaxy Fold.
    ![Test case - Contact - Galaxy Fold](/readmedocs/testing-images/contact-mobile.png)
    - Users are required to fill in their First Name and Last Name.
    ![Test case - Contact - fill](/readmedocs/testing-images/contact-fill1.png)
    - Users must enter their email address correctly.
    ![Test case - Contact - fill](/readmedocs/testing-images/contact-fill2.png)
    - The form submits successfully.
    ![Test case - Contact - submiy](/readmedocs/testing-images/contact-submit.png)

### Fixed bugs
- When scrolling down the webpage, the header scrolled up a bit, causing the menu burger icon to move out of the screen's top. This issue was attributed to the lengthy email address in the footer.
- An unusual right padding or margin appeared on smaller screen sizes due to the extended email address in the footer. This and above was resolved by adjusting the email layout for smaller screens using CSS.

### Supported screens and browsers
Website was developed and tested on Google Chrome. 
After some troubles but now it's wortking correctly for Small screen size as Galaxy Fold as for large screens.
FIle style.css optimizes web for these screen width changes: 365px 579px 768px and 992px (based on CL Love Running Project)
![Screens](/readmedocs/screens.png)

## Deployment
### Via Gitpod
The initial development of the website took place in the Codeanywhere Workspace. However, due to slow response times and Git database corruption issues, the development environment was transitioned to Gitpod.
1. Upon starting the Gitpod online workspace,
2. I initiated a Python web server using the command: ```"python3 -m http.server"```
3. Gitpod prompted to open the website within its environment.
4. After making updates and saving them on Gitpod,
5. I refreshed the website to reflect the changes.

### Via github pages
- The website is publicly accessible on GitHub:  [Rushcliffe Country Park website](https://houndhunger.github.io/Rushcliffe-Country-Park/)
- he website repository is hosted at: [Rushcliffe-Country-Park](https://github.com/houndhunger/Rushcliffe-Country-Park)

Upon completing any modifications:
1. I added the changes using the command: ```git add .```
2. Followed by committing them with a descriptive message: ```git commit -m “Something done”```
3. Finally, I pushed the changes to the GitHub repository: ```git push```
4. Refreshing the [Rushcliffe Country Park Github](https://houndhunger.github.io/Rushcliffe-Country-Park/) webpage reflected the updates.

## Credits
- The initial layout was inspired by the CL Love Running Project - Header, Main, Footer.
- The logo is adapted from the [Rushcliffe Borough Council Logo](https://www.rushcliffe.gov.uk/leisure-and-culture/rushcliffe-country-park/) with additional text to represent Rudington Country Park.
- The navigation menu design is based on the CL Love Running Project and customized to the author's preferences.
- The burger icon for the Navigation Menu is provided by [Fonticons - fontawesome](https://fontawesome.com)
- The footer design takes inspiration from the footer of [Osmaston Park](https://www.osmastonpark.com/).
- The Home Page features a photo taken by the website author, with the slogan generated by ChatGPT. 
- The video in the Activities section is captured and formatted by the website author, along with other images on the Activities page.
- Content for Activities, Facilities, and Friends sections is adapted from the [Rushcliffe Borough Council](https://www.rushcliffe.gov.uk/leisure-and-culture/rushcliffe-country-park/), with image replacements due to low resolution.
- The Gallery structure, including the 2, 3, and 4 column layouts, is inspired by the CL Love Running Project. Modal photo preview written with help of ChatGPT. Pohots are provided by the website author.
- The Contact form is based on the CL Love Running Project but modified to suit the contact purpose.
- Fonts are selected using [Fontjoy](https://fontjoy.com/) and provided by [Google fonts](https://fonts.google.com/).
- The Google Map integration is powered by Google Cloud.
- The manifest.json file is generated with the assistance of [ChatGPT](https://chat.openai.com/), which also helped in solving various issues and providing solutions for bug fixes. CHatGPT helped me with restructuring english in this document.
---
Happy browsing