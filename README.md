# Commodore 64 - 40 year anniversary celebration

This will be a fan website celebrating and going into detail on the legendary microcomputer, the Commodore 64!

View the live site [here](https://daveguthib.github.io/Project_Portfolio_1/) 

![Mockup image of website on different devices](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/mockup.png)


## Features
---

### Navigation Menu
- This will link to the main page, music information page and contact page, while being responsive on all devices.
- Will allow easy navigation between all the parts of the website on devices of any size.

![Nav Bar](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/home_navbar.png)


### Social media Footer
- Will contain icons which link to the various social media websites, and open in new tabs. Aria-labels will facilitate the use of screen-readers for the visually impaired.

![Footer](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/home_footer.png)

### Logo Icon at the top of every page
- A stylised C64 logo will be placed at the top-left of every page, which allows thematic consistency and is also what the website colourscheme is based on.

![Logo](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/home_logo.png)

### Favicon

Since such a high quality C64 vector logo was available, this was turned into a favicon and put on all of the pages

This was tested to ensure it displayed correctly on each of the five pages

![Favicon on index page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/favicon_id.png)

![Favicon on music page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/favicon_ms.png)

![Favicon on contact page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/favicon_ct.png)

![Favicon on thankyou page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/favicon_ty.png)

![Favicon on 404 page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/favicon_404.png)



## Index page
---
- The index page will have a large hero image to be visually attractive to the visitor.
- It will feature an animated zoom effect featuring a different C64 logo to the stylised one used on the top-left of every page.
- Since this one will show the full brand name "Commodore 64" and the rainbow colour swash that was originally featured on the microcomputer itself, this will help users to recognise the content of the site even if they are not familiar with the stylised C64 logo.

![Hero Image](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/home_hero.png)

### Explanatory text

- Will attempt to catch the users attention with the main reasons behind the website and some interesting information.

![Text](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/home_text.png)

### Image gallery of famous games

- Will show users a collection of well known C64 games as well as a brief text description of each one.
- This gallery will be fully responsive on a devices and resize the images based on the screensize it is being viewed on.

Desktop
![Gallery Desktop](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/home_gallery_desktop.png)

Mobile
![Gallery Mobile](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/home_gallery_mobile.png)



## Music page
---

-  Will feature a detailed explanation of the C64's most uniquely powerful attribute: The SID music chip
- Also will include a variety of visual and audio media: Pictures, Music and Video.
- External links will be included at the bottom of the music page which all open in new tabs. These links will point to the most relevant modern resources if users wish to continue learning about the topic.

![Music](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/music.png)

A different media display style was used on this page instead of the gallery page, to be more dynamic with different media types.

In order to have the names of the media files (like *Commando (Arcade):* in the above image) display above the sound, video and image media; html figcaptions were used.

Information on them was sourced [from this link](https://www.w3schools.com/tags/tag_figcaption.asp)

## Contact page
---

A form will be feature on the page to allow the users to contact the webmaster. It will have the following fields
1. First name which will require the input type text
2. Last name which will require the input type text
3. Email which will require the input type email
4. Message which is a textarea input field

![Contact](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/contact.png
)

Once the submit button has been pressed, a confirmation page will appear.
No actual message is sent, as Javascript implementation would be required, but the loading of a confirmation page (called "thank you") meets the users expectation of a submit button.


![Thank you](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/thankyou.png)

This "thank you" page will not be accessible from the main navigation bar, and is intended only to appear after completion of the contact form

This "thank you" page will feature additional contact details for the webmaster

## 404 Error Page

If the user types an incorrect site url, they will be redirected to a custom 404 error page

![Error 404](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/Error_404_Example.png)

In this example index.html was intentionally typed incorrectly

## Existing features

- Responsive design
- Colour scheme themed to the subject matter
- Responsive gallery
- Contact form and thank you page
- Music information and playable media
- Error 404 redirection
- Favicon

## Future features

- Javascript on contact page to send email to webmaster
- Disqus integration to allow user comments on individual sections

## Design

Balsamic wireframes for site design

![Balsamic Wireframes](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/Wireframes_All.png)



## Testing

All of the main HTML pages had their code validated on the W3C HTML checker

### Home Page
![W3C Validation of Home page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/index_html_w3c_validated.png)

### Music Page
![W3C Validation of Music page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/music_html_w3c_validated.png)

### Contact Page
![W3C Validation of Contact page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/contact_html_w3c_validated.png)

### Thank you Page
![W3C Validation of Contact page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/thankyou_html_w3c_validated.png)

### 404 Page
![W3C Validation of Contact page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/404_html_w3c_validated.png)



### CSS

The CSS was validated using the Jigsaw Validator
![Jigsaw Validation of CSS page](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/css_jigsaw_validated.png)


### Lighthouse Performance Testing

The website received all green ratings on the Lighthouse Performance test

![Lighthouse performance rating of site](https://raw.githubusercontent.com/DaveGutHib/Project_Portfolio_1/main/docs/Lighthouse_report.png)



## References




[C64 vectorised logo by Lolman4408 on DeviantArt ](https://www.deviantart.com/lolman4408/art/Commodore-64-logo-vectorized-694733898)

[Commando Arcade music source ](https://www.youtube.com/watch?v=qX0rW4bKp3U)

[Commando C64 Oscilloscope video source ](https://www.youtube.com/watch?v=bCp_sG-haP0)

[W3 schools figcaptions used on Music page](https://www.w3schools.com/tags/tag_figcaption.asp)

[How-to Geek Commodore article](https://www.howtogeek.com/820304/the-best-selling-pc-of-all-time-commodore-64-turns-40/)

[Commodore in-game image archive](http://www.cbmitapages.it/c64/games/games.htm)

[.htaccess file for 404 page](https://www.inmotionhosting.com/support/website/set-custom-404-page/)

[Favicon generated here](https://favicon.io/)

[Contact form and thank you page inspiration](https://github.com/Gareth-McGirr/tacos-travels/blob/main/contact.html)