# Ruscliffe Country Park
## Purpose of the project

This is website provides information about Ruscliffe Country Park. Main goal is to provide united information about the park, or it can be somone who will be soon visitting the Park or participate in some event. Web visitor can find under one web information about park actvities, facilties, services, social groups and websites etc.

![Ruscliffe Country Park - Home](https://houndhunger.github.io/Rushcliffe-Country-Park/screenshots/Home.jpg)


/* Tone simple and informative

rebuilt for the Council website: https://www.rushcliffe.gov.uk/rushcliffecountrypark/.
/*
As an assignment, I proposed a joint interest in developing this website by Friends of Ruscliffe Country, Ruscliffe Borough Cancil and facilities businesses to attract more customers.

There is no need to reinvent the wheel. Just functionally correct joint content from Ruscliffe Borough Council Ruscliffe Country Park with new web page design. By applying familiar web structure including standard navigation will be easy for visitors to find relevant information.
*/

## Strategy

## Scope

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
First I set main structure - header, main and footer and format it for small screen devices.
As I added new part, next thing I done is to add a style for bigger screens.
I have inserted logo, Navigation menu and make it beahiving correctly on small devices.
Then I added footer content and format it to show correctly.
Then I start adding individual web pages.
On the end I updated tags  to have right accessbility info by adding aria-label atribute or proper alt atribute information.
On the end I have tested html, css and accesibiltiy of the website.



### Media

## User stories
Each page sholud serve user diferent needs:
- Home - welcoming page
- Activities - user heard about the park, that it is a place where you can spend the day with your family. User is able to find necessary information about activties and relevant links, which leads him further.
- Facilties - user knows about the park and been there. He liked it a lot, that user woluds like to arange a party. this section provides user information about facilties and relevant links to help hium book the venue.
- Home - user heard about the park, but is unsure. User is imediatelly welcomed and amazed with true calming atmosphere of the park.
- Gallery - some other user is still unsure and keeps browsing the page and finds Gallery page which will provides plenty of visual material to pursuade user to visit the park and experience the place. 
- Friends - if user feels like park is his home, this page provides hgim more information to get in touch.
- Contact - if user still needs to reach somone, it's possible with contact form and Google map provides more info with park location. More reach out  information are located in the footer always accesible on every page LOCATION - park address, FOLLOW - social websites and CONTACT - email.

## Features
- Navigation menu:
It provides links to all pages of the web.
It shows in horizontal format for vider screens. For smaller screens it restyles to vertical format, hidden initially, then recalled by hitting standard burger favicon provided by [Fonticons - fontawesome](https://fontawesome.).

### Contact Submit form
It's standard Submit form where user have to provide his/her First Name, Last Name, Email and Message to succesfully Submit the form.

### Goolge map
I't seems to me visualy pleasing to add Google map of the park location. I have registered for API key with [Google Cloud](https://console.cloud.google.com/apis/credentials) platform and restricted it for security to Google Maps only and deployment web page url.

### Google fonts


### Gallery
Continues to what Home page started, to show beutiful views of the park in different locations, time of the year and the day.
Gallery is screen size responsive and progrss to show one, two, three or four columns of images as device viewing screen width grows.
User can click image to view enlarged version
### Video
Is located in Activities page at the top about Dog walking. It's well popular activity thorugh the week in the park.
### Activities, Facilities, Friends
Provides relevant information with links to external web pages.
The information content is taken from Ruscliffe Borough Council website and restructured where needed.
### Gallery
Contains my photos.
### Contact
Contains Submit form
## Future features
Contact form in the future will send a copy of users submital.

## Content
### Home
Page sholud reveil the pleasing atmosphere ogf the par by displaying full width a pohoto of park lake with bueutiful reflection.

## Typography and color scheme
## Wireframes
## Technology
## Testing
### Code validation
### Test cases (user story based with screenshots)

### Fixed bugs
- Odd right padding or margin appeard on smaller screen sizes. It was caused by long email address in the footer. Solution was to break email for smaller screen sizes.
- Logo shouldn't be H1 as there sholud be only one H1 tag on the page and H1 is used in main section. It got replaced by div. 
### Unfixed bugs
- Scrolling down the web page, header is pulled up that much, that header scrolls up moving menu-burger out of the top of the screen.



### Supported screens and browsers
## Deployment
### Via code anywhere
### Via github pages
## Credits
Initial structure is based on CL Love Running Project.

Footer is inspired by [Osmaston Park](https://www.osmastonpark.com/) footer.

Home Page contains photo image taken by author of this page. Slogan is generated by ChatGPT. Video is my own 
production.

Logo is Rushcliffe Borough Council Logo with added text to identify Rudington Country Park.

Navigation manu as CL Love Running Porject and modified to my graphical likeing.

Activities, Facilties and Friends content was copied from Rushcliffe Borough Council website - text and images.

Gallery images are my own production.

Contact form based on CL Love Running Project but modified to fit the purpose.

I used ChatGPT asking if particular caases is aria-label needed or not
manifest.json Generated with ChatGPT

---

Happy browsing