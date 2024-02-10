# Ruscliffe Country Park
## Purpose of the project
The [Ruscliffe Country Park website](https://houndhunger.github.io/Rushcliffe-Country-Park/) is a user-friendly website providing essential information about Rushcliffe Country Park.
The primary objective is to centralize information about the park and foster a sense of community among users interested in its offerings. The target audience for the website encompasses individuals planning to visit the park in the near future or those seeking information about upcoming events. The website provides a centralized hub for park-related activities, facilities, services, social groups, and other pertinent information. This project serves as a redevelopment effort for the [Rushcliffe Borugh Council - Rushlciffe Country Park website](https://www.rushcliffe.gov.uk/rushcliffecountrypark/).

## User stories
Each page serves different user needs:
- Home: This page serves as a welcoming introduction to the Rushcliffe Country Park.
- Activities: Users who have heard about the park as a family-friendly destination can find detailed information about available activities and relevant links to further explore.
- Facilities: Visitors who have previously experienced the park and are interested in hosting events, such as parties, can access information about facilities and booking options.
- Gallery: Users who are undecided about visiting the park can browse the gallery for compelling visual content that persuades them to experience the park firsthand.
- Friends: For those who consider the park a second home, this page provides additional information to connect with like-minded individuals.
- Contact: Users seeking further assistance or information can utilize the contact form, while a Google map offers detailed park location information. Additional contact details are conveniently located in the footer for easy access on every page, including the park's address, social media links, and email contact information.

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
- Cntact form will be upgraded to send an informative copy of the user's submission.
- The gallery modal will be upgraded to include control arrows for browsing through enlarged images directly.

## Typography and color scheme
- Rushcliffe logo defined coorporate colour - main colour: !['#1fb25a'](https://placehold.co/15x15/1fb25a/1fb25a.png) '#1fb25a'
- From this a complementary colour for higlights and headings: ![#a41fb2](https://placehold.co/15x15/a41fb2/a41fb2.png) '#a41fb2'
## Wireframes
- Home:

![Draft - Balasamiq Wireframe - Home](/readmedocs/wireframe-Home.png)

- Contact:

![Draft - Balasamiq Wireframe - Contact](/readmedocs/wireframe-Contact.png)

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

- index.html:

![Analyzeing with Lighthouse - index.html](/readmedocs/testing-images/Lighthouse-Home.png)

- gallery.html:

![Analyzeing with Lighthouse - galllery.html](/readmedocs/testing-images/Lighthouse-Gallery.png)

- index.html - mobile device:

![Analyzeing with Lighthouse - index.html for mobile device](/readmedocs/testing-images/Lighthouse-Mobile.png)

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

- Home:

![Test case - Home](/readmedocs/testing-images/Home.png)

- Activities:

![Test case - Activities](/readmedocs/testing-images/Activities.png)

- Gallery:

![Test case - Gallery](/readmedocs/testing-images/Gallery.png)

- Facilities:

![Test case - Facilities](/readmedocs/testing-images/Facilities.png)

- Friends:

![Test case - Friends](/readmedocs/testing-images/Friends.png)

- Contact:

![Test case - Contact](/readmedocs/testing-images/Contact.png)

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
Intially web was developed in Codeanywhere Workspace. Becasue of long Workspace starts, slow responces and git DB corruption on Code anywhere, development was moved to Gitpod. After Gitpod online web Workspace starts, "python3 -m http.server" is started and browser window opened with the web.
### Via github pages
- Website is publicly accesible on Github: [Rushcliffe Country Park website](https://houndhunger.github.io/Rushcliffe-Country-Park/)
- And website repostory: [Rushcliffe-Country-Park](https://github.com/houndhunger/Rushcliffe-Country-Park)

Once something is done, then it's added, commited and pushed with git commands to github repository:
git add .
git commit -m “Somethnig done”
git push


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