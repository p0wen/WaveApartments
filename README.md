# Wave Apartments - 1milestone

1 Milestone Project for Code Institute - User-Centric Frontend Development

This sites represents the holiday Apartments of Wave Apartments in Sankt Peter Ording, Germany. The site gives the visitor an introduction to the apartment, area and activites around the area and allows to send a booking request to the host. 

## Demo
A live demo can be found here:

[![alt text](https://github.com/p0wen/WaveApartments/blob/master/assets/images/demo/portfolioview.gif?raw=true "WaveApartments Demo")](https://p0wen.github.io/WaveApartments/ "Wave Apartments")

## UX
The goal of the design and user experience is to make it as easy as possible to access information about the Apartment and ab about the destination while always maintaining the option to send a booking request right away. They color scheme with light grey, white and turquoise highlights is used to present an positive and modern look and feel. 

The visitor of the sites is being presented with beautiful pictures of the area to trigger an desire to have a vacation in the wave apartmens. Furthermore the visitor should get a good idea of what he can do and where he can enjoy local dishes. 

The wireframes were sketched in Balsamiq Mockups and can be found [here](https://github.com/p0wen/WaveApartments/tree/master/wireframes) or following the direct links:

[Landing Page](https://github.com/p0wen/WaveApartments/blob/master/wireframes/Landing.png "Landing Page")

[Sleep & Rates](https://github.com/p0wen/WaveApartments/blob/master/wireframes/Sleep.png "Sleep & Rates")

[Eat & Drink](https://github.com/p0wen/WaveApartments/blob/master/wireframes/Eat.png "Eat & Drink")

[Surf & Action](https://github.com/p0wen/WaveApartments/blob/master/wireframes/Surf.png "Surf & Action")

[Contact](https://github.com/p0wen/WaveApartments/blob/master/wireframes/Contact.png "Contact")

## Technologies

1. HTML
2. CSS
3. Bootstrap
4. JavaScript
5. Jquery
6. Font Awesome
7. PopperJS
8. Google Fonts

## User Stories

As a user I want to get an idea of how the Apartments looks like, so that i now where i will be staying.

As a User I want to know how much the Apartments costs so that I now if I can afford it.

As a User I want to know what activities I can do so that I can plan my activities beforehand.

As a User I want to send a booking request so that i don't have to open my Email Client.

As a User I want to get information about local restaurants so that  I don't have to make extra research.

As a User I want to know where the apartment is so that i find it right away.

## Testing
Testing was undertaken in different ways. First of all manual testing by the developer was done. Afterwards a "crowd" test was initiated. After some bugfixing the site was reviewed by code-institute participants and tutors. And finally validation-tools from W3 were used.

### Manual User Testing 
Manual testing was undertaken with a small set of test cases on different devices (Mac, iPhone, iPad) and with different browsers (Safari, Chrome, Brave). The following test cases where used:

1. Check caroussel on landing page
2. Check booking form in nav
3. Check in page links for "Sleep & Rates" & "Eat & Drink"
4. Validate Formcontrol
5. Check Flipcard function in "Surf & Action"
6. Validate links

### "Crowd" Testing
The page was spread within friends and family to collection feedback about what the users like/dislike and if errors/bugs were identified. Users reported that the liked the clean and light design of the page. A couple of errors were identified, e.g.:
1. Active site was not marked in Navbar 
2. Flipcard feature did not work on all Browsers `-webkit-`had to be added.
Minor details were reported and adjusted.

### Peer-Code-Review through Code Institute
Using the community and getting input from other developers was used to polish the code and identified not so obvious errors which were hidden in the code. This lead to cleaning up the html code and refactoring the css.

## Features to come

While finishing up the page the following features were identified to be added in the future:

1. Create german translation and implement a language toggle
2. Connect Booking Form in Modal and on Contact-Page to a email host or database
3. Finalize links to Legal (Contact, Privacy, Terms) and Social Media
4. Make use of `Polyfills` so that the date picker works on all browsers

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/p0wen/WaveApartments.git` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.

## Credits

#### Content

The whole content for this site was written by me.

#### Media

All photos were taken from Pexels, a stock image library, with the exception of the photos of the apartment pictures and pictures of the restaurant recommendations. 

#### Acknowledgments

Lightbox for Bootstrap was taken from [here](https://ashleydw.github.io/lightbox/)


**This is for educational use.**
