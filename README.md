#Getaway Destination - Second Milestone Project
[View my project](https://timeakovacs86.github.io/Getawaydestination/)

This website is my second Milestone project at [Code Institute](https://codeinstitute.net/)
The main goal was to create a simple website which using the technologies that I got familiar with in the second phase and it's based on Java Script and its jQuery library and also on Google API libraries.
The website itself help us to find cities around the world and get back a list of restaurants, bars, coffee shops, museums and some other tourist attractions what would be useful, planning a vacation upfront.
We can see those places position on the map with markers to find them and plan the daily itinerary through the holiday around that area.
This is a single page website therefore very simple and easy to use, no need of any special technical skills to use it.
The results of our search is just one click away, it is also easy to use with one hand on our phones.

## UX

This website is created for everybody who wants to find a great weekend getaway destination.
I choose as a background picture the Fisherman's Bastion (Budapest, Hungary), because that's the city I am from, also I tried to use the background pictures colors, to ensure that this site has a user friendly and smooth surface.
The website is responsive, so it gives the same excellent user experience while you use it on a PC, tablet or mobile device with the same functionality.

### User Stories

#### Home page

- As a user, I want to get feedback is the searching field is empty.
- As a user, I want to find cities for vacation destination.
- As a user, I want to find restaurants around the searched city.
- As a user, I want to find bars around the searched city.
- As a user, I want to find coffee shops around the searched city.
- As a user, I want to find museums around the searched city.
- As a user, I want to see what kind of other opportunities I have as a tourist around the searched city.

#### Responsive:

- As a user, I want to use the website on Pc, tablet and mobile phone so, it should work on different devices with the same functionality.

#### Effects:

- As a user, I want to see the hover effect on the buttons, interest icons and social media links as well, so I can see that there is an interaction with those elements.

#### Social links:

-As a user, I want to click on the social links so that it can be open is a new tab.

#### UI:

- In General:
    - Font:
        - I use "Amaranth" font, because it is easy and comfortable to read. I imported that font through the custom.css file from the google font repository.
    - Icons:
        - I use Font Awesome icon toolkit with he below mentioned icons:
            - Restaurant
            - Bar
            - Cafe
            - Museum
            - Information 
            - Facebook
            - Github
            - LinkedIn
    - Hover effects:
        - Search and reset search button
        - Filter section:
            - Restaurant icon
            - Bar icon
            - Coffee shop icon
            - Museum icon
            - Tourists attraction icon                
        - Social links:
            - Facebook icon
            - Github icon
            - LinkedIn icon 
- On the page I have implemented:
    - Input type:
        - "type=search", so in this way it became more straightforward and user friendly to type in the destinations.
    - Alert message is the search input field is empty     

- Mockup


## Features

With this page you can find  restaurants, bars, coffes shops, museums and other tourist attractions around that area that you give in the search field.
If you finished you search, you can reset the process with clicking on the reset button.

### Existing Features

- The main page:
    - Field checking:
        - If the input search field is empty and I click on one of the filter buttons, I get an alert message about that empty fiels
    - Icons:
        - To click on the Restaurant icon, you get back restaurants around the given city
        - To click on the Bar icon, you get back bars around the given city
        - To click on the Coffee shops icon, you get back coffee shops around the given city
        - To click on Museum icon, you get back museums around the given city
        - To click on Tourist attractions icon, you get back other tourist attractions around the given city
    - Button:
        - If in the first round we find more than 20 places the "More result" button become active
        - If there are no more results, the "More result" button become disabled
        - If there is no result around the area at all the "More result" button become disabled
        - I can reset the search with the reset button         

        
- Responsive:

    - The page is responsive, usable and looks good on the below resolution:
        - Phones less than 768px
        - Tablets 768px and Up
        - Desktops 992ox and Up
        - Large desktops 1200px and Up
        


## Technologies Used

- [HTML5](https://www.w3.org/html/)
    - Hypertext Markup Language is the standard markup language for creating web pages and web applications.
- [CSS3](https://www.w3.org/Style/CSS/)
    - Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a 
    markup language like HTML.
- [BootStrap 4.3.1](https://getbootstrap.com/docs/3.3/)
    - Front End Framework for developing responsive websites.
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
    - JavaScript is a lightweight interpreted or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages.
- [JQuery 3.4.1](https://jquery.com)
    - The project uses to simplify DOM manipulation.
- [Git](https://git-scm.com/)
    - Git is a distributed version-control system for tracking changes in source code during software development.
- [GitHub](https://github.com/)
    -  GitHub Inc. is a web-based hosting service for version control using Git.
- [Google Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/tutorial)
    - The Maps JavaScript API lets you customize maps with your own content.
    - Library used:
        - Google Places API