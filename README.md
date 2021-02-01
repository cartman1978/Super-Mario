## Super Mario the Nintendo Icon

### Super Mario Helped Nintendo Conquer the Video Game World

![Mario](assets/images/background.png)

### Description
#### I decide to buikd this website for those who enjoyed palying videogames back in the 80's and specifically the 8 bit era for the Nintendo users. What I want is let user find information about the best videogames for this console and why Super Mario became the face of the system. 

## Table of Content
* UX
  * Project Goals
  * User Goals
  * User Stories
  * Site Owner Goal
  * User Requirements and Expectations
  * Design
    * Fonts
    * Icons
    * Colours
* Technologies used
* Features
    * Develped Features
    * Future implementation
* Testing
* Bugs 
* Deployment
* Credit
# User Experience
___
## The Project Goal
##### When I first thinking of this project the idea was to build a website for the generation X users who enjoyed the NES system and  the library of their videogames but maybe they hanging up the controller. 

## User Goal
* Find information Super Mario saga.
* Get to know Super Mario and why is the most popular game ever.
* Images of Super Mario + funny images from internet artist.
* Have a look to the Mario World and the merchandising.
* Send email to the site owner to get specific information.

## User Story
| Users      |    
| -------   

* [ Mark ] User 1
* [ Rory ] User 2
* [ Claudio ] User 3

User 1: As a user I need a smooth navigation  through the web page, I want the main information visible once that I click on links.
 
| Acceptance Criteria     |    
| -------   

Ensure the user1 is able to:
* See the navigation bar clear;
* Navigate to each section by click on links;
* Able to easily read title of the article after link has been clicked.

User 2: As a user I want to know more about the creator, the game library and the story of how the game evolved since the first publication.

| Acceptance Criteria     |    
| -------   

Ensure the user2 is able to:
* Easily find related information on the top of the page;
* Read a brief introduction of the game main character and how it became so famous;
* On the same section user can click a video content about all the stories behind Super Mario publication, how Mario get new super power and when new characher were added to the series.

User 3: As a user I want to see more funny contents about mario and find related  online shop where I can buy articles for my self and family.

| Acceptance Criteria     |    
| -------   

Ensure the user3 is able to:
* Read content about videogame franchises.
* Find information about merchandising and being riderect to an online reseller of Super Mario Brand.
* Able to clink on a button and being redirect to some cool web blog/ page or articles that talking about funny memes or cool animation.
___



* As a user what I'm looking for is an attractive webiste where I can spend time and reading interesting information about retro videogames.
* I want to find information about Nintendo 8 bit and the raise of the 8 bit era.
* As a user I want to know more about Super Mario Bros, when was created and the evolution of the character.
* I want to be able to contact the site owner for more details and information about this game.

## Website Owner Goals
* My Goal as a site owner is to inform my users about the 8 bit gaming generation.
* I want to communicate how important was Super Mario for my generation and the story behind this amazing character.
* As a site owner is very important to get in touch with my users and answer any topic about gaming experience and fun fact.

## Customer requirements and expectations
1. Requirements
* Easy navigation using navbar -High-
* Each section most have main information displayed -High-
* Content dipslayed in a fancy way -Medium-
* intuitive Contact form -High-

2. Expectations
* All the content structured displayed with all the main information.
* Navigation redirect users to the specific part of the website.
* Read more button redirect user to useful information related the article.
* External resource used in the website will provide great informastion and topics.

## The Design
___
#### I got the first inspiration when I start to design this website from [Nintendo](https://www.nintendo.com/nes-classic/) classics website, I actually try to make a restyling of it with my personal touch, but I wasn't happy enough after the first view, so I decide to make my own design.

### Icons
Icons used were provided by [Font Awesome](https://fontawesome.com/)

### Colours
![coloursscheme](wireframes/colurspalette.png)

#### I decide to use colours that reminds the user the original NES console.

* The body is a combination of #E4001F and #FFF;
* For the Navbar I actually choose the same grey that Nintendo used #AEAEB5;
* I decide to replace Navbar colour #AEAEB5 with  rgb(107, 136, 254) to be consistent with the warp pipe zone theme I choose;

## Features
___

### Features implemented:
* Resposnsive navigation on all screensizes.
* Stylish design.
* Video's.
* Contact Form.
* Social media links.

### Features that will be implemented in the future:
* Another Video section.
___
## Technologies used
___
## Languages
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
## Tools & Libraries
* [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
* [Font-Awesome](https://fontawesome.com/)
* [Google fonts](https://fonts.google.com/)

## Testing
___
First Testing I used online tool [responsive design](http://ami.responsivedesign.is/#), to make sure the website is responsive.
Second responsive test made with [responsive test tool](http://responsivetesttool.com/), in order to check mobile, Tabled and Desktop in different size.

### Navbar

* Plan 

As the majority of my their mobile users my approach was mobile firts responsive, the idea it was to make mobile users confortable while exploring the website and add some animation on the navbar link that recall super mario videogame. Each section has a read me button which redirect to external links.

* Implementation

I made links in navbar with animation effect when hover on it, to divide sections I used diagonal box wiht title and super mario effect.

* Test 

When I first tested for mobile resolution I noticed that while hovering on the nav links the animation didn't behave like what I espected, the pipe image actually flip over and the result was poor in terms of UI.

I decide to wrap the list emelemts inside anothe div then I added diplay flex for mobile min-widht.

* Result

Animation is now working as planned with nice and smooth transition. On mobile screen is now easy to view and navigate.

### Videogame section

* Plan

My plan is to create a videogame section with text content to give an overview of the game history and a button where the user can click and being redirect to an external video link. 

* Implementation

I created a section with two text content, a carousel where the user can explore different videogame version, and one button to see the video.

* Test 

I have tried  to navigate on mobile and tablet, resolution was good but I wasn't happy in terms of UI. Users can be confused with the call to action button they may aspect to read more content rather than redirect to youtube video.

I decide to diplay the video directly in the section so no need to click another button but the video can be played directly in the website, underneath the first text content I placed the carousel  than the video iframe as a last element.

* Result

Videogame section is now working as planned, is more easy to read and intuitive for the UI point of view.

Testing HTML with  [HTML Validator](https://validator.w3.org/), first results:
* Warning
    * heading section lacks heading
    * section section lacks heading

* Errors
    * form action " " cannot be empty
    * end tag for emelemt /div which is not open

* Fixes
    * changed heading and section to div
    * Removed action in the form attribute as no needed for this project
    * Removed end tag for for the div which was not opened

Testing CSS with [CSS Validator](https://jigsaw.w3.org/css-validator/), no errors found.

#### Responsiveness
* Bootstrap implemented throughout the project to ensure mobile first responsive and   tested with devtools and Lambdatest.

* **Result** was successfull and as to be expected.

#### Design
* **Implementation** got inspiration from the official Mario website of Nintendo but not following any particular pattern, I decide to use diagonal separator for each section and using fonts and images that reminds me the game also to give sense of familiarity for those who knows the game.

* **Results** I'm quite happy as I made something original but consistent with the videogame character.

### Contact Form
* **Implementation** I got the contact form from the Bootstrap site and made few changes to meet my needs, Form validation was implemented to ensure that user put values to any field before sending the email.

* **Results** Contact form works as expected.
* **Verdict** Validation works, test passed.

## Deployment
___
The Origins of Super mario was developed on **GitPod** and host the repository.

When deploying The origins of Super Mario, the following steps were made:

* **GitHub** opened in the broser.
* Sign in  using username and password.
* Selected my repositories.
* Clicked **Settings** on the top navigation.
* Scrolled down to GitHub pages.
* Selected **Master-Branch** from the drop-down menu.
* The Origins of Super Mario is now live on GitHub Pages.

## Credits
___
* [Article](https://www.bbc.com/news/newsbeat-54163659) by Christian Hewgill.
* [Article](https://www.popmatters.com/141240-the-retirement-of-a-gen-x-gamer-or-my-8-bit-childhood-2496029806.html) by Clay Morgan.
* [Article](https://ultimateclassicrock.com/super-mario-bros-history/)

### Images used
* [Pinterest](https://www.pinterest.ie/)
* [IconArchive](https://iconarchive.com/)

### Special Thanks
* To my great mentor [Simen Daehlin](https://github.com/Eventyret)