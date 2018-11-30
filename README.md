# Scott Connick - Tattoo Artist - Professional  Website

## Project One: User Centric Frontend Development

This is a static, frontend-only website, to demonstrate my HTML and CSS skills.

The website is a personal page, for a professional tattoo artist. The aim of the site is to engage users by showcasing the artist's work, and provide contact details for any prospective clients to engage with the artist.

The website will be a single scrolling page, as I believe this is optimum for mobile-first design, which is how I believe the most traffic will view the website. There will be separate page areas for separate parts of the website.

### Demo

A live demo of the website can be found here: https://sarahcrosby.github.io/Scott-Connick-Website/

### Technologies and Languages
* [Bootstrap (4.1.3)](https://getbootstrap.com/) - for the template, and to build a responsive and visually appealing site.
* [Javascript (1.8.5)](https://en.wikipedia.org/wiki/JavaScript) - the language and logic of the interactive elements on the page
* [jQuery(3.3)](https://jquery.com/) - a JavaScript library to enhance the user's experience
* [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - the language used to customise and present the web app.
* [HTML5](https://en.wikipedia.org/wiki/HTML) - the language used to write and create the web app.
* [GitHub](https://github.com/) - for version control, and to host the project.
* [Cloud 9](https://c9.io/) - the cloud-based integrated development environment used to write the code.

### UX

I will use a Bootstrap template, which will make the website as responsive and visually-appealing as possible. I will maintain a clear distinction between my code and the Bootstrap code, by including a library with the original Bootstrap code. I will demonstrate my HTML and CSS skills by adding custom elements and styles to the template.

I chose this particular template because it is a single scrolling page, and I believe it is well tailored for the creative industry. The website source can be found here: https://startbootstrap.com/template-overviews/creative/

I ensured there was a clear division between my code and the Bootstrap code, by included the original code in the library folder. This way, my code can be compared against the library Bootstrap code, to see the edits I have made. 

I included CSS3 media queries to enhance the user's experience on different screen sizes. I extensively tested this, by using the emulator in developer tools, and also by maually testing the website on my various devices (mobile, tablet, laptop, larger second screen), and also on my friend's devices. 

Originally, I chose my colour scheme by picking colours from the header image, finding the HEX number (using this website: https://www.rgbtohex.net/ ) and generated a colour scheme using this website: https://coolors.co/

However, I was not happy with the colour scheme, so I decided to take an evening away from the project, so I could take a fresh approach the next day. I believe this worked, as I changed the colour scheme, and I am a lot happier with it. The scheme attempts an 'old school 3D' effect, using text-shadows, the invert filter on images, and images manipulated in the Android app 'Glitchr'.

I also wanted to implement the following user stories:
* As a prospective client, I want to be able to make contact with the artist, by being provided with multiple methods of communication.
* As a prospective client, I want to see examples of the artist's work, so I can decide whether I am a fan.
* As the artist, I want to peak interest in viewers, increase my client-base and reach more interested persons, by having a stylish website that showcases my work and provide means of communication.
* As the artist, I want my website to be an online business cart, so I can boost my sales.
* As a user, I don't want to be overloaded with information, because this damage the artist's reputation.
* As a user, I want the website to be responsive, so I can view it on different size screens without losing integrity.

### Features

* Navigation - allows users to navigate the page, so they don't have to scroll the entire site to find the part they are looking for.
* Home - the website's introduction, where the intent of the website, ie. a tattoo artist's professional page, is explained.
* About - an informative section about the subject of the web page. Includes a profile image.
* Connect - allows users to connect and engage with the artist via. social media.
* Portfolio/Gallery - showcases a selection of the artist's work.
* Portfolio More - allows the user to access the artist's full portfolio, and also includes a link to a timelapse video.
* Contact - encourages the user to make contact with the artist. 

### Deployment

I have deployed my code to GitHub, which can be found here: https://github.com/sarahcrosby/Scott-Connick-Website

To run the app locally, download the files from GitHub and upload to your workspace.

Alternatively, you could clone the repository, by typing the following command into the terminal:

> $ git clone https://github.com/sarahcrosby/Scott-Connick-Website

You will then be able to run the website by running 'index.html'.

### Testing

When making changes to my custom CSS, I opened my project in my internet browser's private mode, to ensure the CSS wasn't cached. I then opened the developer tools, and tested the changes I wanted to make before I committed them to my code. I found this easier than changing my CSS then refreshing the page, and allowed me to test different approaches.

When manally testing my website on different screen sizes, I encountered a bug that changed the alignment of the header div - at a screen size of approximately 764 pixels wide, the text was not centrally aligned. To resolve this, I tried multiple methods using CSS, but they affected the smaller size screen negatively. Instead, I changed the break points of my media queries, as I was able to align everything centrally this way. If I hadn't done this, the page would have looked out of sync on certain screen sizes - and granted, this was only for a very specific screen width of between 760 and 764 pixels wide, but this would have changed the user's experience if they had this screen size, so I wanted to resolve the issue.

I decided to overhaul the website's colour scheme after manually testing the website, and I realised I was not happy with how the colours looked. As I use a blue light filter on my mobile, the colours did not look right, and I understand that the website will look different on the myriad devices with different screen settings. I decided to use less colours, and simplify my approach, and I believe this has produced a more visually appealing website.

Once I was happy with the layout and content of my website, I viewed it on different devices - my mobile, tablet, laptop and larger screen. I was happy that the website was responsive. I then tried to 'break' my website - I followed every link, clicked on every image, tried the navigation on mobile and laptop; I made sure everything was working and there were no issues. I also asked a friend to do the same thing. Everything appeared to be working fine, however I did notice a colour issue with the navigation bar, which was resolved by changing a text color.

I then checked the console log, and realised that I had not closed a link in my 'index.html' - after resolving this, no errors were occurring in the console.

### Credit

* All original artwork is from [Scott Connick](https://www.instagram.com/scottconnick/), which I had permission to use.
* I used an app called ['Glitchr'](https://glitchr.en.uptodown.com/android) to generate the 3D effects on images.


### Version Control

1. Initial commit. Implemented Bootstrap template and library, to show separation of code. Started editing text.
2. Started README.md. 
3. Updated vulnerable dependencies.
4. Updated vulnerable dependencies.
5. Added custom header image. Edited CSS including media queries. Added to README.
6. Added custom colours, images to portfolio, profile picture.
7. Overhaul of colour scheme - changes to CSS. Personalised 'portfolio' section. Added custom logo.
8. Added custom 'portfolio' images and a timelapse video. Edited colour scheme and style.
9. Completed README. Fixed final issues. Added comments to code.