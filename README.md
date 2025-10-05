# MadnessFM

This is a website for the MadnessFM Online Radio Station, so people can go to this and listen to our feed.

It has clear and concise pages and information with the intention of increasing revenue for the station by highlighting who we are and what we offer.

It is designed to be responsible and accessible on a range of devices.


## UX

The site's users are listeners and potential listeners who wish to learn more about the station's history and the station members.

The sites intention from the station’s perspective is to broadcast to the listener, sell advertising space, and also increase the listenership.

It’s a very simple UX idea having a station feed, description and ad space on the home page and then having separate pages for the main pieces of information that someone who is visiting the site would need.

Some user stories I thought of before designing my site;

* As a listener who is interested in hearing the station, I can go to the website and easily listen.
* As a listener who is interested in finding information about the station, I can go to the website and easily find the information on the Home page and even contact the station directly on the Contact page.
* As a person who might be just looking at different stations to listen to, I can easily see from the Home page the description of the station.
* As a person who wants to buy merchandise from the station, I can go to the website and easily find where to buy station merchandise on the Merch page.

### Design

* Colour Scheme
    * The colour scheme is 3 colours, black, grey and yellow, to match the colours used in the station’s logo
* Typography
    * The Roboto Font is the font used on the site for Headings with the Exo for descriptions and blocks of text, both with Sans Serif as the back up font in case there is an issue with Google Fonts. I like the combination of both fonts and I think they are easy to read on both a desktop and a mobile screen.
* Imagery
    * The imagery which has been used is important and has been chosen to be eye catching for anyone using the site.
* Wireframes
    * Links to my initial Wireframe design is in the “Wireframe” folder in assets in my repository.


## Features 

Each of the 5 pages has a universal header for the navigation of the site. It is made up of 3 columns. The middle column is the stations logo and links back to the home page. The side columns have 2 buttons in each and link to the other pages on the site.

Each of the 5 pages has a universal footer that leads to the station’s social media pages.

The Home page (index.html) is used to describe what the station do, has 2 customer reviews, and gives contact details on how to book them for a gig. I embeded a video from Youtube of the station. 

The Gigs page is a simple design of splitting the section into 2 columns and using a heading of the Month/Year on the left of the page and a list of Dates and Venues then down the right hand side of the page.

The Merch page took a bit of thinking on my part as the station itself doesn’t actually sell merchandise so I went and looked at The Killers website for inspiration which just had a list of links to the sites that sold their merchandise so I used the same idea but had three separate links. Records linked to HMV, Clothes linked to Pennys, and Memorabilia linked to a memorabilia site.

The station page is a simple design also of a 4 rows, each split into 2 columns, one for a photo and another for a quick name, instrument, and description of each member.

The Contact page is a form consisting of a name, email and message text input and a button to send the message.

### Existing Features

* Header (on each page) – allows users on each page to navigate the website, by having them select buttons to go to each page on the site.
* Footer (on each page) – allows users on each page to navigate to the stations social media sites which will open on a separate tab.
* Home page (index.html) – allows the users to see the station in action by clicking an embedded video of the station from Youtube.
* Merch page (merch.html) – allows the users to be redirected to sites which open on new tabs where the user can buy station merchandise.
* The Gigs page (gigs.html) – allows the users to see when and where the station are playing in the upcoming months.
* The station page (station.html) – allows the users to get to know the station members.
* The Contact page (contact.html) – allows the users to contact the station through use of a form.

### Features Left to Implement

* Header (on each page) – I’d like to make this shrink and stick to the top of the window when users scroll down on each page.
* The Contact page (contact.html) – I’d actually like to test this form and get it working to a actual email address.


## Technologies Used

### Languages Used

* [HTML5](https://en.wikipedia.org/wiki/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)

### Frameworks, Libraries & Programs Used
* [Code-Institute-Org/gitpod-full-template](https://github.com/Code-Institute-Org/gitpod-full-template)
    * The project was built using this template
* [Bootstrap](https://getbootstrap.com/docs/4.3/getting-started/introduction/)
    * The project uses Bootstrap for styling
* [Font Awesome](https://fontawesome.com/)
    * The project uses Font Awesome for the Icons
* [Google Fonts](https://fonts.google.com/)
    * The project uses Google Fonts for the Icons
* [hover.css](https://cdnjs.com/libraries/hover.css)
    * The project uses hover.css for the hover effect on the buttons and links
* [Balsamiq](https://balsamiq.com/)
    * I used this to create the wireframes 
* [GitHub](https://github.com/)
    * I used this to store the project as I was developing it
* [GitPod](https://gitpod.io/)
    * I used this to write the code and used it to push the code to GitHub


## Testing

I used the W3C Markup Validator and W3C CSS Validator to validate my project making sure that there was no syntax errors.
* [W3C Markup Validator](https://jigsaw.w3.org/css-validator/)
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

I used Google Chrome and Google Developer Tools for mobile devices to work through and test the page using real world events as the parameters, eg booking the station, contacting the station, checking gig dates, and trying to buy station merchandise.

1. Header/Navigation; from the home page:
    * Go to gigs page – go back to Home page
    * Go to Merch page – go back to home page
    * Go to station page – go back to Home page
    * Go to Contact page – go back to Home page

* Also tested on mobile device
* Also tested from each page to every other page

2. Footer; Social Media links:
    * Go to the Home page
    * Click on Instagram link – Instagram opens
    * Click on Twitter link – Twitter opens
    * Click on Facebook link – Facebook opens
    * Click on TikTok link – TikTok opens
    * Click on Snapchat link – Snapchat opens
    * Click on Youtube link – Youtube opens

3.	Header/Navigation; from the home page:
    * Go to gigs page – go back to Home page
    * Go to Merch page – go back to home page
    * Go to station page – go back to Home page
    * Go to Contact page – go back to Home page

4.	Home Page; image/video link:
    * On Home page click on Youtube video image
    * Youtube video opens in new tab

5.	Home Page; “Or Click Here” link:
    * On Home page click on “Or Click Here” link
    * contact.html opens

6.	Gigs Link; gigs.html:
    * Gigs page opens and looks as intended on desktop and mobile device

7.	Merch page; links:
    * Merch page opens and looks as intended on desktop and mobile device
    * Records link – opens link in a new tab
    * Clothes link – opens link in a new tab
    * Memorabilia link – opens link in a new tab 

8.	station page:
    * station page opens and looks as intended on desktop and mobile device

9.	Contact page:
    * Contact page opens and looks as intended on desktop and mobile device
    * Can input “details” and message
    * When I click send it refreshes the page 


## Deployment

This project was developed using GitPod, committed to git and pushed to GitHub using the built in function within GitPod.

To deploy this page to GitHub Pages from its GitHub Repository, the following steps were taken:
1.	Log into GitHub.
2.	From the list of repositories on the screen, select docmartin87/Deuces-Wild
3.	From the menu items near the top of the page, select Settings
4.	Scroll down to the GitHub Pages section
5.	Under Source, select Master Branch in the dropdown menu and hit Save
6.	The page will refresh
7.	Scroll back down the page to locate the now published site link

Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps;

1. Log in to GitHub and locate the GitHub Repository
2. At the top right of the page locate and click the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.


## Credits

### Code
* Bootstrap Library was used to make the site responsive using mainly it’s grid system.
* Header Button Verticle Alignment [here](https://medium.com/wdstack/bootstrap-4-vertical-center-1211448a2eff#:~:text=One%20way%20to%20vertically%20center,col%2Dsm%2D12%20column.)

### Content
* The text for the Home page was taken from the [Deuces Wild](https://www.facebook.com/deuceswildlive/) Facebook page
* The text for the station page and the station members information was taken from the [Teenage Mutant Ninja Turtles](https://en.wikipedia.org/wiki/Teenage_Mutant_Ninja_Turtles) Wikipedia page

### Media
* The video and logo on the Home page was taken from the [Deuces Wild](https://www.facebook.com/deuceswildlive/) Facebook page
* The pictures for the station page for the station members was taken from the [Teenage Mutant Ninja Turtles](https://en.wikipedia.org/wiki/Teenage_Mutant_Ninja_Turtles) Wikipedia page

### Acknowledgements
* My mentor for continuous feedback on the project.
* Tutor support from Code Institute.
* I received inspiration for this project from the Code Institute Module - User Centric Frontend Development, Resume Project. Whiskey page and Love Running page from previous modules.
* I received styling inspiration for this project from [The Killers](https://www.thekillersmusic.com/) website
