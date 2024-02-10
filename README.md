/* Tone simple and informative

# Ruscliffe Country Park
## Purpose of the project
[Ruscliffe Country Park website](https://houndhunger.github.io/Rushcliffe-Country-Park/) provides information about Ruscliffe Country Park. Main goal is to provide united information about the park and to unite users interested in park. Web visitor can be somone who will be soon visitting the Park or participate in some event. Web visitor can find park related information under one web about park actvities, facilties, services, social groups and websites etc.
This is a rebuilt for the [Rushcliffe Borugh Council - Rushlciffe Country Park website](https://www.rushcliffe.gov.uk/rushcliffecountrypark/).

## User stories
Each page sholud serve user diferent needs:
- Home - welcoming page
- Activities - user heard about the park, that it is a place where you can spend the day with your family. User is able to find necessary information about activties and relevant links, which leads him further.
- Facilties - user knows about the park and been there. He liked it a lot, that user woluds like to arange a party. this section provides user information about facilties and relevant links to help hium book the venue.
- Home - user heard about the park, but is unsure. User is imediatelly welcomed and amazed with true calming atmosphere of the park.
- Gallery - some other user is still unsure and keeps browsing the page and finds Gallery page which will provides plenty of visual material to pursuade user to visit the park and experience the place. 
- Friends - if user feels like park is his home, this page provides hgim more information to get in touch.
- Contact - if user still needs to reach somone, it's possible with contact form and Google map provides more info with park location. More reach out  information are located in the footer always accesible on every page LOCATION - park address, FOLLOW - social websites and CONTACT - email.

## Structure
Each web page show: Header, Main and Footer.
- Header - contains:
    - Rushcliffe Borough Council logo as image, then Rushcliffe Country Park text next to align to the left. 
    - Navigation menu the right header contains Navigation menu.
- Main: Provides space for web page content.
- Footer: Displays: 
    - LOCATION - PARK address 
    - FOLLOW - social networ references
    - CONTACT - link to email

Web cotains 6 web pages:
- Home - welcoming page
- Activities - information about activties and relevant  links
- Facilties - information about facilties and relevant  links
- Gallery - image gallery of the park areas
- Friends - information about friends and relevant links
- Contact - Submit form anf Google map with park location

## Development process
1. First I set main structure - header, main and footer and format it for small screen devices.
2. As I added new part, next thing I done is to add a style for bigger screens.
3. I have inserted logo, Navigation menu and make it beahiving correctly on small devices.
4. Then I added footer content and format it to show correctly.
5. Then I start adding individual web pages and it's content.
    - Home with large image, Contact with formular and Map, Gallery, then Acticities Facilties and Friends.
    - Folowed by constant improvements, styling and bug fixing
6. On the end I updated tags to have right accessbility info by adding aria-label atribute or proper alt atribute information.
7. On the end I have tested html, css and accesibiltiy of the website.

## Features
- Navigation menu:
It provides links to all pages of the web.
It shows in horizontal format for wider screens. For smaller screens it re-styles to vertical format, hidden initially, then recalled by hitting standard burger favicon provided by [Fonticons - fontawesome](https://fontawesome.com).

### Contact Submit form
It's standard Submit form where user have to provide his/her First Name, Last Name, Email and Message to succesfully Submit the form.

### Goolge map
I't seems to me visualy pleasing to add Google map of the park location. I have registered for API key with [Google Cloud](https://console.cloud.google.com/apis/credentials) platform and restricted it for security to Google Maps only and deployment website url.

### Gallery
Contains my photos.
### Gallery
Continues to what Home page started, to show beutiful views of the park in different locations, time of the year and the day.
Gallery is screen size responsive and progrss to show one, two, three or four columns of images as device viewing screen width grows.
User can click image to view enlarged version
### Video
Is located in Activities page at the top about Dog walking. It's well popular activity thorugh the week in the park.
### Activities, Facilities, Friends
Provides relevant information with links to external websites.
The information content is taken from Ruscliffe Borough Council website and restructured where needed.
### Contact
Contains Submit form
## Future features
Contact form in the future will send a informative copy of users submital.

## Typography and color scheme
- Rushcliffe logo defined coorporate colour - main colour: !['#1fb25a'](https://placehold.co/15x15/1fb25a/1fb25a.png) '#1fb25a'
- From this a complementary colour for higlights and headings: ![#a41fb2](https://placehold.co/15x15/a41fb2/a41fb2.png) '#a41fb2'
## Wireframes
# IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES
## Technology
Used were following technologies: 
- HTML, CSS
- [ChatGPT](https://chat.openai.com/)
- [Fontjoy](https://fontjoy.com/), [Google fonts](https://fonts.google.com/)
- Excel to generate Gallery content
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

Only one Alert was outstanding for Redundant Link - Logo and Home in Navigation menu.

Analyzeing with Lighthouse in Google Chrome was done with following results:
- index.html
- gallery.html

Improvements and issues (8) was caused by some 3rd pary extension.

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

### Test cases (user story based with screenshots)
# IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES IMAGES

- Scrolling down the web page, header is pulled up that much, that header scrolls up moving menu-burger out of the top of the screen. Problem was long email address in the footer. Solution for the same problem in next bug.
- Odd right padding or margin appeard on smaller screen sizes. It was caused by long email address in the footer. Solution was to break email for smaller screen sizes using style sheet.
- Logo shouldn't be H1 as there sholud be only one H1 tag on the page and H1 is used in main section. It was replaced by div. 
### Supported screens and browsers
Website was developed and tested on Google Chrome. 
After some troubles but now it's wortking correctly for Small screen size as Galaxy Fold as for large screens.
![Screens](https://houndhunger.github.io/Rushcliffe-Country-Park/readmedocs/screens.png)

## Deployment
### Via Gitpod
Intially web was developed in Code anywhere Workspace. Becasue of long Workspace starts, slow responces and git DB corruption on Code anywhere, development was moved to Gitpod. After Gitpod online web Workspace starts, "python3 -m http.server" is started and browser window opened with the web.
### Via github pages
- Website is publicly accesible on Github: [Rushcliffe Country Park website](https://houndhunger.github.io/Rushcliffe-Country-Park/)
- And website repostory: [Rushcliffe-Country-Park](https://github.com/houndhunger/Rushcliffe-Country-Park)

## Credits
- Initally layout was based on CL Love Running Project - Header, Main, Footer.
- Logo is [Rushcliffe Borough Council](https://www.rushcliffe.gov.uk/leisure-and-culture/rushcliffe-country-park/) Logo with added text to identify us Rudington Country Park web.
- Navigation manu as CL Love Running Porject and modified to author's graphical likeing.
- burger icon for Navigation Menu by [Fonticons - fontawesome](https://fontawesome.com)
- Footer is inspired by [Osmaston Park](https://www.osmastonpark.com/) footer.
- Home Page contains photo image taken by website author. Home page slogan is generated by ChatGPT. 
- Video in Activities is taken and formated by website author as the rest of images on the Actvities page.
- Activities, Facilties and Friends content was copied and formated from [Rushcliffe Borough Council](https://www.rushcliffe.gov.uk/leisure-and-culture/rushcliffe-country-park/) website - text. Images have been replaced becuase of low resolution.
- Gallery structure as CL Love Running Project (2, 3, 4 columns) and modal - photo preview added with help of ChatGPT. Pohots provicded by webiste author.
- Contact form based on CL Love Running Project but modified to fit the contact purpose.
- Fonts match was found with [Fontjoy](https://fontjoy.com/) and provided by [Google fonts](https://fonts.google.com/).
- Google Map by Google Cloud.
- manifest.json Generated with [ChatGPT](https://chat.openai.com/). ChatGPT assited me to sovle many problems and provided me solutions how to fix bugs or pointed me right dirtection to fix the bugs.
---
Happy browsing