Title: 
Rocket League Trainer

Background: 
The idea behind this first project was to get a better understanding of HTML, CSS and various other features taught by Code Insitute. 
I invested a lot of time and effort tracking the current meta, looking for training packs, finding tutorial videos and could not find a site like mine. 
This project is for those in the same situation as myself, who wish to improve but simply without the unnecessary hassle.


UX and design choices:
When choosing this design it was meant to be simple, self explanatory and loading quickly on any device. 
In other words, an easy way to access the material players would need, but without the clutter seen on other sites. 
The color-scheme is intended to be darker, so it wont interfere too much when having late night training sessions.


User Stories:
1. "As a new player, I wish to see current meta videos and material, so I can gain an edge over my current level opponents."
2. "As an experienced player, I wish for a list of meta-accurate training packs, so I can copy and add them to my in-game favorites list."
3. "As any player, I wish to have the ability to submit training packs that could be useful to others."
	
The Wireframe:
I had one mock-up design in mind at first, overall I stuck to my original idea and adjusted the Showcase only.



Features:
1. Video Showcase
	- 4 videos describing what I think is the most current meta of what should be taught.
	- Short description of how to train and maintain, involving links to both the content creator and the suggested training method.

2. Training Pack List
	- A list of 10 training packs, which I believe is the most important items to improve and train during this meta.
	- Includes the 3 most important items, a short description, who created it and most importantly the training pack code itself.

3. Submit A Pack
	- A form where the users can submit what they think is a necessary pack at any given moment to be featured.
	- I didn't finish this in time, but the plan is to make a database with identical submissions and make a queue of the most submitted training packs.
	
Existing Features:
1. Navbar
	- Came with bootstrap 4, allows us to easily access and navigate the website.
2. Overall grid-system was used from bootstrap 4, then modified to fit the various mobile sizes.  
3. iframes, Youtube allows us to right click any playing video and copy an embed link.


Technologies used to create this website:
- HTML5 https://en.wikipedia.org/wiki/HTML5
	- Building the basic structure of the website, the very core of the site.
	
- CSS3  https://en.wikipedia.org/wiki/Cascading_Style_Sheets
	- Styling the website in conjunction with Bootstrap.
	
- Bootstrap 4 https://getbootstrap.com/
	- Assisted in creating the grid system of the website, the form and the submission element.
	
- Google https://google.com
	- To research, troubleshoot and investigate bugs with the website. 
	
- StackOverflow https://stackoverflow.com
	- Glanced at other peoples problems and how they solved their issues.
	
- Notepad++ https://notepad-plus-plus.org/
	- Using a client sided text editor for creating the readme and certain code snippets.
	
- GitHub https://github.com/
	- Used for deplying, updating, sharing and maintaining the website.
	
- GitPod IDE https://gitpod.io/
	- Could not have developed the website without Gitpod. 
	
- Chrome https://www.google.com/chrome/
	- Tested various situations by emulating the devices needed to make compatibility. 
	
- iPhone 7 https://www.apple.com/
	- Tested the mobile website for bugs. 
	
- Windows 10 https://www.microsoft.com/nl-nl/software-download/windows10
	- The OS responsible for running each tool. 
	
- Code Institute Training and Study Materials https://courses.codeinstitute.net/
	- Learning by doing and doing while learning.


Testing:
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well.
Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, 
with the project providing an easy and straightforward way for the users to achieve their goals.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. 


Contact form:
I was unfortunately out of time when working my way through adding a server which the form could submit to.
This is a feature I wish to implement in the future. 


Bugs and their resolution:
1. 	When swapping between 280px and 720px width, the gridsystem provided by bootstrap would overlap with eachother. This was solved by adding padding to each element as a workaround, I still need more experience with Bootstrap.
2. 	The background resolution would continue to decrease itself when switching from one mobile to another mobile emulation repeatedly in Chrome. It did not resolve itself until I cleared my browser cache!
3. 	The embedded iframe elements would not size according to the Div element it was wrapped in, found a scalable solution which allowed for responsive sizing when specified.
4. 	When adding a darker tint to the background, it interfered with everything else. Did some research on how to apply it directly to the background itself, instead of using a div with a separate class added to it.


Deployment:
Each update has been to back up my work and progress between my work and office pc at home.
Ensuring the latest part of the code is available each place, despite sometimes introducing bugs. 
This unfortunately means I will have to find another way to work than I currently am, potentially running multiple duplicate workspaces or simply only pushing commits that have been completely cleared for bugs. 
During this project I have pushed 14 commits and learned the hard way that creating valuable messages and keeping consistent is important.


Credits:
Content Ive used from my search history, and not in any particular order.
(Disclaimer: Not all links have been written down, as some was on my work PC and I could not find them again.)

Darken image: 
https://www.geeksforgeeks.org/how-to-darken-an-image-using-css/#:~:text=The%20brightness()%20function%20can,the%20image%20by%20that%20percentage.
- Background image in the Body and some text elements. 

Centered buttons: 
https://stackoverflow.com/questions/22578853/how-to-center-buttons-in-twitter-bootstrap-3
- The Navbar and submit button were giving me some problems to begin with.

Embedded iframe didnt connect: 
https://stackoverflow.com/questions/36337086/my-youtube-video-wont-show-in-iframe
- iframe elements, clarified the size in an earlier version of the website. No longer in use.

Rounded separator: 
https://www.w3schools.com/howto/howto_css_dividers.asp (Ended up not using.)
- Used in an earlier version of the website, only on mobile. Provided a natural spacer, but ultimately removed as it didnt fit the design.

Responsive iframe documentation: 
https://blog.theodo.com/2018/01/responsive-iframes-css-trick/
- iframe elements, currently in use to ensure the design is responsive on "all" reasonable mobile devices. 280px and up.

Understanding media min/max width: 
https://stackoverflow.com/questions/13550541/media-min-width-max-width
- In use at the end of the CSS stylesheet, figuring out how to avoid bugs with bootstrap once a min-width has been declared.

Aspect ratio calculator: 
https://calculateaspectratio.com/
- iframe elements, ensuring the size fits each @media size. 

Centered Navbar:
https://www.websitecodetutorials.com/code/css/css-center-nav.php
- Used in an earlier version of the website, initially scrapped it and replaced it with one from bootstrap. 

Fixed top Navbar: 
https://www.w3schools.com/howto/howto_css_fixed_menu.asp
- Part of the code used in the .navbar class, but bootstrap is doing most of the work externally. 

Center content in responsive bootstrap navbar: 
https://stackoverflow.com/questions/18777235/center-content-in-responsive-bootstrap-navbar
- Part of the code used in the .navbar class, but bootstrap is doing most of the work externally. 

Bootstrap submission forms:
https://getbootstrap.com/docs/4.0/components/forms/
- The overall skeleton is used as a baseplate in submit.html, minimal parts have been changed to accomodate my needs.

Bootstrap table:
https://getbootstrap.com/docs/4.0/content/tables/
- In use in training.html, only a class from the background has been added on every second row to make them easier on the eyes.

Bootstrap toggle menu:
https://getbootstrap.com/docs/4.0/components/navbar/
- Part of the code used in the .navbar class, but bootstrap is doing most of the work externally.

(Youtube) Create Center Navigation Bar Menu Using CSS Easy Tutorial:
https://www.youtube.com/watch?v=HwXN4fiCxno
- Used in an earlier version of the website, initially scrapped it and replaced it with one from bootstrap. 

(Youtube) Navbar CSS Tutorial: 3 Ways to Create a Navigation Bar with Flexbox:
https://www.youtube.com/watch?v=PwWHL3RyQgk
- Used in an earlier version of the website, initially scrapped it and replaced it with one from bootstrap. 


Media:
Background (4000x2000px)
Downloaded from: https://www.jakpost.travel/wimages/large/238-2389378_rocket-league-draco-grey.jpg
Original copyright belongs to Rocket League.


Sites for inspiration:
Rocket League (psyonix):
https://www.rocketleague.com/

Rocket Garage:
https://rocket-league.com/training
One training site I used to look at, rarely gets updated.

Gamersrdy:
https://www.gamersrdy.com/rocket-league-training-packs/
Another training site I used to look at, but also rarely gets updated.

Acknowledgements:
The CI student care team and my fellow students, for being available around the clock.
My two cats, for providing me with stress relieving cuddles. 
My Mentor Precious Ijege, for providing me with guidance and direction.
My girlfriend Carmen, for human trials.
Special Thanks to Psyonix, for providing a game I have been able to play for the last 4 years without wanting to play anything else. 


Final Disclaimer:
No money will be made on this site, it is purely for the sake of improving my own skill and helping to improve others as well.