# Rocket League Trainer

## Background:
The idea behind this first project was to get a better understanding of HTML, CSS and various other features taught by Code Insitute. 
I invested a lot of time and effort tracking the current meta, looking for training packs, finding tutorial videos and could not find a site like mine. 
This project is for those in the same situation as myself, who wish to improve but simply without the unnecessary hassle.


## UX and design choices:
When choosing this design it was meant to be simple, self explanatory and loading quickly on any device. 
In other words, an easy way to access the material players would need, but without the clutter seen on other sites. 
The color-scheme is intended to be darker, so it wont interfere too much when having late night training sessions.


## User Stories:
1. "As a new player, I wish to see current meta videos and material, so I can gain an edge over my current level opponents."
2. "As an experienced player, I wish for a list of meta-accurate training packs, so I can copy and add them to my in-game favorites list."
3. "As any player, I wish to have the ability to submit training packs that could be useful to others."
	
### The Wireframe:
I had one mock-up design in mind at first, overall I stuck to my original idea and adjusted the Showcase only.

Page | Link to image of wireframe
------------ | -------------
index.html | [index](https://github.com/isitaslinky/rl-training-site/blob/master/assets/images/index.png)
training.html | [training](https://github.com/isitaslinky/rl-training-site/blob/master/assets/images/training_pack.png)
submit.html | [submit](https://github.com/isitaslinky/rl-training-site/blob/master/assets/images/submit.png)

## Features:
1. Video Showcase
	- 4 videos describing what I think is the most current meta of what should be taught.
	- Short description of how to train and maintain, involving links to both the content creator and the suggested training method.

2. Training Pack List
	- A list of 10 training packs, which I believe is the most important items to improve and train during this meta.
	- Includes the 3 most important items, a short description, who created it and most importantly the training pack code itself.

3. Submit A Pack
	- A form where the users can submit what they think is a necessary pack at any given moment to be featured.
	- I didn't finish this in time, but the plan is to make a database with identical submissions and make a queue of the most submitted training packs.
	
## Existing Features:
1. Navbar
	- Came with bootstrap 4, allows us to easily access and navigate the website.
2. Overall grid-system was used from bootstrap 4, then modified to fit the various mobile sizes.  
3. iframes, Youtube allows us to right click any playing video and copy an embed link.


## Technologies used to create this website:
- [HTML5](https://en.wikipedia.org/wiki/HTML5) - Building the basic structure of the website, the very core of the site.
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - Styling the website in conjunction with Bootstrap.
- [Bootstrap 4](https://getbootstrap.com/) - Assisted in creating the grid system of the website, the table and the submission element.
- [Google](https://google.com) - To research, troubleshoot and investigate bugs with the website. 
- [StackOverflow](https://stackoverflow.com) - Glanced at other peoples problems and how they solved their issues.
- [Notepad++](https://notepad-plus-plus.org/) - Using a client sided text editor for creating the readme and certain code snippets.
- [GitHub](https://github.com/) - Used for deplying, updating, sharing and maintaining the website.
- [GitPod IDE](https://gitpod.io/) - Could not have developed the website without Gitpod. 
- [Chrome](https://www.google.com/chrome/) - Tested various situations by emulating the devices needed to make compatibility. 
- [Apple iPhone 7](https://www.apple.com/) - Tested the mobile website for bugs. 
- [Windows](https://www.microsoft.com/nl-nl/software-download/windows10) - The OS responsible for running each tool. 
- [Code Institute Training and Study Materials](https://courses.codeinstitute.net/) - Learning by doing and doing while learning.


## Testing:
1. Tested using various mobile emulators on my Windows Machine.
2. Tested on mobile to ensure the links, layout and scaling works as intended.
3. Tested using responsive design in the browser on most used breakpoints. 
4. Had friends and family test the website on their devices and received design feedback.
6. Ran a [CSS validator](https://jigsaw.w3.org/css-validator/#validate_by_input).
    - Result: [CSS](https://github.com/isitaslinky/rl-training-site/blob/master/assets/images/css_w3_pass.png)
7. Ran a [HTML Validator](https://validator.w3.org/#validate_by_input).
    - Results:
    - [Index](https://github.com/isitaslinky/rl-training-site/blob/master/assets/images/html_w3_pass_index.png)
    - [Training Pack](https://github.com/isitaslinky/rl-training-site/blob/master/assets/images/html_w3_pass_training_pack.png)
    - [Submit](https://github.com/isitaslinky/rl-training-site/blob/master/assets/images/html_w3_pass_submit.png)
6. Ran an online [responsiveness tester](http://ami.responsivedesign.is/#).
    - Result: [Amiresponsive?](https://github.com/isitaslinky/rl-training-site/blob/master/assets/images/amiresponsive.png)

## What I would like to work on in the future:
- Contact form
I was unfortunately out of time when working my way through adding a server which the form could submit to.
This is a feature I wish to implement in the future. 


## Bugs and their resolution:
1. 	When swapping between 280px and 720px width, the gridsystem provided by bootstrap would overlap with eachother. This was solved by adding padding to each element as a workaround, I still need more experience with Bootstrap.
2. 	The background resolution would continue to decrease itself when switching from one mobile to another mobile emulation repeatedly in Chrome. It did not resolve itself until I cleared my browser cache!
3. 	The embedded iframe elements would not size according to the Div element it was wrapped in, found a scalable solution which allowed for responsive sizing when specified.
4. 	When adding a darker tint to the background, it interfered with everything else. Did some research on how to apply it directly to the background itself, instead of using a div with a separate class added to it.


## Deployment:
Ensured all tools were installed, this includes:
1. Using the GitPod IDE plugin for Chrome.
2. Installed Notepad++ to keep a local copy.
3. Ensured Chrome was up to date, latest version installed. Version 84.0.4147.89 (Official Build) (64-bit)
4. Accessed the Code Institude project template.
5. Regularly uploaded commits whenever a big change has been made.
6. Hosting the website on GitHub Pages.


## Credits:
Content Ive used from my search history, and not in any particular order.
(Disclaimer: Not all links have been noted down, as some was found on my work PC and I could not find them again when making this.)

[Darken image:](https://www.geeksforgeeks.org/how-to-darken-an-image-using-css/#:~:text=The%20brightness()%20function%20can,the%20image%20by%20that%20percentage.)
- Background image in the Body and some text elements. 

[Centered buttons:](https://stackoverflow.com/questions/22578853/how-to-center-buttons-in-twitter-bootstrap-3)
- The Navbar and submit button were giving me some problems to begin with.

[Embedded iframe didnt connect:](https://stackoverflow.com/questions/36337086/my-youtube-video-wont-show-in-iframe)
- iframe elements, clarified the size in an earlier version of the website. No longer in use.

[Rounded separator:](https://www.w3schools.com/howto/howto_css_dividers.asp)
- Used in an earlier version of the website, but ultimately removed as it didnt fit the design.

[Responsive iframe documentation:](https://blog.theodo.com/2018/01/responsive-iframes-css-trick/)
- iframe elements, currently in use to ensure the design is responsive on "all" reasonable mobile devices. 280px and up.

[Embed respobsive:](https://getbootstrap.com/docs/4.0/utilities/embed/)
- iframe elements, currently in use as part of the responsive design.

[Understanding media min/max width:](https://stackoverflow.com/questions/13550541/media-min-width-max-width)
- In use at the end of the CSS stylesheet, figuring out how to avoid bugs with bootstrap once a min-width has been declared.

[Aspect ratio calculator:](https://calculateaspectratio.com/)
- iframe elements, ensuring the size fits each @media size. 

[Centered Navbar:](https://www.websitecodetutorials.com/code/css/css-center-nav.php)
- Used in an earlier version of the website, initially scrapped it and replaced it with one from bootstrap. 

[Fixed top Navbar:](https://www.w3schools.com/howto/howto_css_fixed_menu.asp)
- Part of the code used in the .navbar class, but bootstrap is doing most of the work externally. 

[Center content in responsive bootstrap navbar:](https://stackoverflow.com/questions/18777235/center-content-in-responsive-bootstrap-navbar)
- Part of the code used in the .navbar class, but bootstrap is doing most of the work externally. 

[Bootstrap submission forms:](https://getbootstrap.com/docs/4.0/components/forms/)
- The overall skeleton is used as a baseplate in submit.html, minimal parts have been changed to accomodate my needs.

[Bootstrap table:](https://getbootstrap.com/docs/4.0/content/tables/)
- In use in training.html, only a class from the background has been added on every second row to make them easier on the eyes.

[Bootstrap toggle menu:](https://getbootstrap.com/docs/4.0/components/navbar/)
- Part of the code used in the .navbar class, but bootstrap is doing most of the work externally.

[Container sizing:](https://stackoverflow.com/questions/41174380/how-do-i-make-a-container-fill-the-whole-page-also-to-be-responsive)
- Added to HTML and BODY element.

[Stretching the background to always fit the body element:](https://www.tutorialrepublic.com/faq/how-to-stretch-and-scale-an-image-in-the-background-with-css.php)
- In use in the Body element. 

[No background image displayed on github pages:](https://stackoverflow.com/questions/41607049/background-images-not-showing-on-github-pages-for-website)
- In use under background image

[(Youtube) Create Center Navigation Bar Menu Using CSS Easy Tutorial:](https://www.youtube.com/watch?v=HwXN4fiCxno)
- Used in an earlier version of the website, initially scrapped it and replaced it with one from bootstrap. 

[(Youtube) Navbar CSS Tutorial: 3 Ways to Create a Navigation Bar with Flexbox:](https://www.youtube.com/watch?v=PwWHL3RyQgk)
- Used in an earlier version of the website, initially scrapped it and replaced it with one from bootstrap. 

[Sticky footer:](https://css-tricks.com/couple-takes-sticky-footer/)
- Used in the Footer section of the CSS file. 

## Media:
Background (4000x2000px)
[Download location:](https://www.jakpost.travel/wimages/large/238-2389378_rocket-league-draco-grey.jpg)

Various content creators on youtube:
[Gpepper](https://www.youtube.com/channel/UC-d1NAX6MeEYgwMkd6TMEyg)
[FusioNine](https://www.youtube.com/channel/UCOT7Vqfqb2oFl_mMBhDQRVA)
[Snap10a](https://www.youtube.com/channel/UCUCnQu9TR7qEqa52PF7Djaw)
[SubParButInHD](https://www.youtube.com/channel/UCOw0zA-Gf5gpQ6K446mR0wA)

[Bakkesmod (A Rocket League plugin):](https://www.bakkesmod.com/)

Sites for inspiration:
[Rocket League (psyonix):](https://www.rocketleague.com/)

[Rocket Garage:](https://rocket-league.com/training)
One training site I used to look at, rarely gets updated.

[Gamersrdy:](https://www.gamersrdy.com/rocket-league-training-packs/)
Another training site I used to look at, but also rarely gets updated.

## Acknowledgements:
The CI student care team and my fellow students, for being available around the clock.
My two cats, for providing me with stress relieving cuddles. 
My Mentor Precious Ijege, for providing me with guidance and direction.
My girlfriend Carmen, for human trials.
Special Thanks to Psyonix, for providing a game I have been able to play for the last 4 years without wanting to play anything else. 


## Final Disclaimer:
No money will be made on this site, it is purely for the sake of improving my own skill and helping to improve others as well.