# ![songbird](assets/images/songbird_orange_xs.png)   Amanda T. - Milestone Project 1
***

##  Overview

In keeping with the music theme of the default project, I decided to code  (using HTML and CSS) a website for my neice, who is an up and coming singer and songwriter. She is hoping to be "discovered" and signed by a record label and also needs a place for potential clients to find her and contact her to book her for functions. She needs a site that can show case her talents and give her user a view of who she is and what she has to offer.

## UX
The artist requested that I design her a site that she could provide to potential clients and agents. 
Using Balsamiq [Here's My Mockup](https://github.com/cvdebeer/AmandaT_mp1/blob/master/assets/AmandaT_wireframe.pdf) (click to open) I designed a site that I believed would best answer that need by taking into consideration and answering the following needs:  
🔸 This user would be interested in getting to know the artist's style of music. To this end I created:-
- The "Home" section gives a few snaps of the artist, and shares her passion for music.
- The "Music" section, showcases some of her original and cover songs, showing her range of music genres.  
  - I presented the original songs in video format linked to her YouTube posts. This allows the user to see her passion for the songs that she writes and sings.
  - I presented the cover songs as audio, using album covers to trigger the users memory and identify the original artist. The album cover flips so that the user can go the the original song and compare if they want to.
  
🔸 The user would also want to be able to contact the artist in order to hire her for gigs/functions or set up a meeting for a collaboration. To this end I created :-
- Two points of getting in touch 
    - First ~ with the "Get in Touch" button that users can press which will take them immediately to the "Contact Form" Modal
    - Second ~ through the "Contact" link in the menu, which also takes them through to the "Contact Form" Modal.
  
🔸 The user might not want to contact the artist immediately and might want to see where the artist is performing in public, before hiring the artist or offering a record deal. To this end I created:-
- The "Events" section of the website, which shows up and coming public performances. This also allows any fans the opportunity to book tickets to see her perform.

🔸 Although not originally in my design, I was presented with the scenario that the user might want to see what the artist is currently working on or has been up to recently. To this end I created :-
- The "News" section of the site. In this section we have shown her latest public performance on TV (showing potential agents that she is being noticed). I also showcased her latest song, by making the lyrics available and providing a click through to the audio track.



## Features
🔸  In the "Home" section, information and visuals are given of the artist by using Carousels. The information is provided in small, easy to read pieces and hopes to keep the user engaged.  
🔸 The "Original Music" section, provides the user with a choice of videos that the artist has recorded. They can view them in the fram, enlarge them to full screen or follow them to YouTube. 
- In future I would like to add image posters onto the videos, with the title of the song and a link to the lyrics.    
  
🔸 The "cover music" section. Here I used a horizontal card design to create an audio-player.   
- Using styling provided by [David Walsh][1] I was able to create flip animations on the album covers and allows the user to click through to the original artists version of the song. 
- Using an answer provided by [Fábio Zangirolami][2] on a Stackoverflow question, I was able to style my audio player to fit in with my theme.

🔸 The "events" section has table with the location of future performances, allowing the user to book tickets. (The "Book Tickets" button is not currently functional  but will be on the list of future development, after  more knowledge is gained.).

🔸 The "news" section makes use of Bootstraps own "cards"  to create content that links to fuller articles or outside content for the user to explore. This is done so as not to overwhelm the user with too much content, but give them the ability to see more if they want to. Both buttons work and link to content.

🔸 The "Contact/ Get in touch" section is a Bootstrap Modal containing a form. The user can fill in their information and request the artist to make contact with them in relation to whatever category they have selected. There is a text box available should the user want to conver more information. (The contact form does not currently "go" anywhere as I don't have the knowledge yet so send the form- this will be part of future development)



## Technologies Used

***HTML5*** ~ main Language used to structure the sections of my website.  
***CSS3*** ~ styling language used to format and visually build upon the accompanying HTML.  
***Bootstrap4 Framework*** ~ <https://getbootstrap.com/> ~ Used as the core structuring layout building blocks of the website, ensuring mobile-frist design and responsive size display.  
***AWS Cloud9 and Visual Studio Code*** ~ Cloud9 was used as the initial IDE (Integrated Development Environment) for this project. VS code was coming highly recommended by other students, so I changed over due mainly to being kicked out of Cloud9 every hour.   
***Git*** ~ <https://git-scm.com/>~ Used to commit to local repository and further push to Github Repo ensuring version controlling of the project build. Originally used through Cloud9 and then downloaded to use in VScode.  
***Github*** ~ <https://github.com/>~ Used to host the deployed website and repository of all previous versions of the build.  
***Google Chrome Developer Tools*** ~ Used as the core testing mechanism throughout the project build to see what the repsonsiveness accross all devices.  
***ColorRules*** ~ <https://apps.apple.com/ca/app/colorrules/id1198369052> (Colour Picker) ~ Application used to obtain hexadecimal/rgba/hsl values of colours. It provides different varations of colour choices depending on the base colour you select.
***Balsamiq*** ~ <https://balsamiq.com/>~ Used for the Creation of my initial Wireframes for my project.  
***Pix-resizer*** ~ <https://pixresizer.windows10compatible.com/> ~ Programme used to make my images smaller without losing the aspect ratio.  
***Any Video converter*** ~ <https://www.any-video-converter.com/> ~ Used to change video into audio files.  
***Plyr*** ~ <https://plyr.io/> ~ used to style my video player.  
***Font-awesome*** ~ <https://fontawesome.com/> ~ Used for all the icons in my site.  
***Google Fonts*** ~ <https://fonts.google.com/> ~ Used for all the fonts on my site.  
***Hover.css*** ~ <https://ianlunn.github.io/Hover/> ~ Used to style the hovers on my "Get in Touch" button and navbar links.

## Testing
Most of the testing for the project was done with Chrome Developer Tools.  
- Breakpoint visuals were tested for each section.
  -   Carousel padding and margins needed to be adjusted to make sure that they were inline where needed.
  -   I had to break down the columns into more pieces to allow space for margins on the video columns so that the boxes weren't ontop of each other. (Original md-6 and lg-4 changed to md-5 and lg-3 .
  -    A lot of adjustments needed to be made with the audio- visuals to keep them aligned within the audio files. 
- The navigation bar was tested on all sizes. 
  - I became aware that my full screen navbar on mobile and tablet did not actually close when you clicked on the link, eventhough you could see it scrolling on the right to the correct place and it worked fine in the desktop. After much research and trial and error trying to fix this problem, I figured out that it was caused by my fixed navbar. I only had two solutions, with my current knowledge:  
        1.  Remove the sticky or fixed navbar (allowing my user no way to navigate once they had scrolled down) or  
        2.  Leave the navbar in place and add a note onto the navbar on how to get to navigate through to the sections.  
   I selected the second option.
-  The form in the Modal was not validating. By using a combination of outlining the required elements in red border and tooltips I was able to resolve the issues. The "send" button on the Modal also needed to be changed to "submit" in order to run the validations.
   
I also tested on my Iphone and and Ipad to see the functionality across devices. 
- I did notice that items that rendered well on the developer tools like the video, did not in fact properly render on the Iphone and Ipad, and I had to find work-arounds for them. I was able to partially fix the border-radius on the frame by using a mask with a radial gradient.



In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.
For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
Contact form: 
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.
If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment
This project was deployed using Git to the Github repository.


## Credits
  
[1]: <https://davidwalsh.name/css-flip> Flip-animations  
[2]: <https://stackoverflow.com/questions/4126708/is-it-possible-to-style-html5-audio-tag>
### Content
The text for section Y was copied from the Wikipedia article Z

### Media
The photos used in this site were obtained from ...
Songbird for logo and icon - https://svgsilh.com/image/1295782.html
https://upload.wikimedia.org/wikipedia/commons/thumb/f/f4/2_Kay_K235_acoustic-guitar.jpg/1024px-2_Kay_K235_acoustic-guitar.jpg
https://upload.wikimedia.org/wikipedia/en/4/47/Alanis_Morissette_-_Jagged_Little_Pill.jpg
https://upload.wikimedia.org/wikipedia/en/b/b6/City_of_angels_%28album_cover%29.jpg
https://upload.wikimedia.org/wikipedia/en/8/8c/Come_Together-Something_%28single_cover%29.jpg
### Acknowledgements
I received inspiration for this project from X


🔸 Favicon- https://www.quora.com/How-can-I-get-the-logo-on-title-bar (working code to get the icon into the tab bar at the top of the page)  and https://convertico.com/  - to convert my png to ico so that it is more compatible with all browsers
🔸 Google fonts- Jura, Marck Script and Exo 2 Marck+Script|Oswald|Righteous!!
🔸 Toggle button- https://stackoverflow.com/questions/42586729/bootstrap-4-change-hamburger-toggler-color/42587673
🔸 Cover full screen with navar - https://css-tricks.com/responsive-menu-concepts/ & https://stackoverflow.com/questions/46927448/bootstrap-full-screen-menu-on-all-devices
https://github.com/wagerfield/parallax
https://stackoverflow.com/questions/14203279/bootstrap-close-responsive-menu-on-click
https://startbootstrap.com/snippets/sticky-footer-flexbox/ - sticky footer
animated hover -https://github.com/IanLunn/Hover/blob/master/css/hover.css

https://stackoverflow.com/questions/9182978/semi-transparent-color-layer-over-background-image
https://pxhere.com/en/photo/720062 - background-image
https://stackoverflow.com/questions/4126708/is-it-possible-to-style-html5-audio-tag 
https://davidwalsh.name/css-flip - flip animations