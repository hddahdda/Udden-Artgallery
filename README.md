


# Udden Artgallery

Live website: https://hddahdda.github.io/Udden-Artgallery/ 


## About

This is a website for a nonexisting artgallery placed at Blockhusudden in Djurgården, Stockholm. 

Udden Artgallery exhibits mostly modern contemporary art and photographs. It's thought to be funded through a fund, state contribution aswell as entry fees. Since not being entirelly reliant on Its visitors in the economic aspect Udden is granted partly the freedom of not having to be too commercial whilst gaining a greater responsibility towards Its donors. In conclusion this creates a dubble responsibility for Udden, that also has to be applied to the website. One being commercial and the other to make sure to follow Its contributors wishes, this to guarantee further economical grants. 

## UX

## Strategy

The goal of the website is for potential visitors to, in an intuitive way understand the focus on the gallery while still being informative aswell as accessible. 
Since the gallery hosts artworks made by modern artists the approach in colourschemes, fonts and images is according to the common subconcious view of the concept of modern art and galleries. 

#### User Stories

* Visitors of Djurgården, Stockholm 
* People interested in art 
* Artists
* Tourists 

#### Reasons for the website

* Attracting visitors
* Informing potential visitors about opening hours, pricing etc. 
* A way for artists and visitors to get in touch with the gallery

## Scope 
#### What the user may expect
* As a user I would expect the website to be easily navigated with the information clearly rendered and for it to render well across devices.

* The design of the website should be in line with what is expected for a gallery of modern or contemporary art. 

#### What the user may want
* To be able to find out which exhibitions that are currently shown with images and description.
* To be able to contact the gallery
* To be able to find out more about the gallery
* Social media Icons
* Locate the address, opening hours and pricing of the gallery

#### Addressing user needs and expectancies 
To address the former needs stated the website will have:
* A working navbar
* A "contact us" form
* Easy access to address, pricing and opening hours 
* Social media Icons
* Mobile-first approach in creating the website

## Structure
**The website consists of three pages:**

* "Home" page titled "Udden Artgallery" 
* "Visit" page titled "Udden Artgallery | Visit"
* "About Us" page "Udden Artgallery | About Us"

**The pages have these sections in common**
* All three pages has a navbar with the links: "Visit" and "About Us".
* All three pages has "Udden Artgallery" as logo which also links to the homepage. 
* All three pages has a footer with social media links.

**Homepage - Udden Artgallery**
* Hero image.
* Section that covers current exhibitions, images with text.
* Section that covers map, "how to get here" and opening hours (also covered in Visit page).

**Udden Artgallery | Visit**
* Section with images, pricing, Corona-virus info and a "Pre-booking form". 

**Udden Artgallery | About Us**
* Hero image with  text about the art gallery. 

## [Wireframes](https://github.com/hddahdda/Udden-Artgallery/tree/master/assets/wireframes)

### Design
 
#### Colors

* Using colors that are complementary aswell as monochromatic colors to enhance user experience. 

* Using the ColorPick Eyedropper tool extension for Google Chrome to use colors viewed in the header as footer.  

* For the background color i used #f5f5f5 which is a slightly off white, this to improve user experience. Straight white color is more demanding for the eyes. 

* The red header serves as a way of gaining the attention of the viewer.
* The titles have a color of dark blue, which is easier on the eyes then black. 

#### Fonts
* Logo is of the font "Syne Mono" which looks modern and slightly cubist. This is a font that works well in advertising for a gallery of contemporary art. 

> "Syne is an exploration of atypical associations of weights and
> styles" - [Google Fonts](https://fonts.google.com/specimen/Syne+Mono?preview.text_type=custom#about)

 * All other text is of the font "Montserrat" which is a font created to "rescue the beauty of urban typography that emerged in the first half of the twentieth century" ([Google Fonts](https://fonts.google.com/specimen/Montserrat?preview.text_type=custom#about)). This while still being easily readable made me choose this font. 

By setting the fontsize of the paragraphs to 1rem, the font is both responsive aswell as on the larger scale. I also increased letter-spacing, this to create a more readable website.


## Features

### Existing Features
* Navbar
* Footer with social media links
* "Contact Us" modal (Bootstrap)
* Pre-booking form
* [Google maps](https://google-map-generator.com/) 
* Bootstrap Modal
### Features Left to implement 
* JUMBOTRON - concerning Corona - link to "visit" page.
* During holidays the logo could change Its colors, this could be done using the css `text-shadow:` property. A christmas logo could have the red color remain but with a green shadow. 
* Changing the modal to become a contact form. This will need some use of JavaScript for the "required" attribute to work.

## Technologies Used

* HTML5
* CSS3
* Bootstrap 4.5 
* GitHub
* Git
* GitPod
* [Favicon creator](https://www.favicon.cc/) (to create favicons for the different pages)


## Testing 
* Navbar 
**Expected outcome**: being visible and responsive on all screens.
**Result**: Navbar is rendering correctly.

* Form
**Expected outcome**: The form requires text in name and email input boxes to be able to send.
**Result**: Form has the attribute "required".

* Social Media links
**Expected outcome**: The links opens in a new tab (good UX).
**Result**: The links opens in a new tab.

The site has been tested in browsers as Google Chrome, Safari and Firefox without errors. It has also been tested across devices on Huawei P20 and Iphone 11 without known bugs or errors. 

**The  W3C Markup Validator**
* When trying to use a html codesnippet with google maps this didn't get approved by the W3C validator, to solve this i changed the live map to a screenshot of the map. 
* As h5 was not accepted as childs of button items I had to remove the textitem, which also affected the layout. 

**The  W3C CSS Validator**
* Everything was valid.  

## Deployment
This website is deployed from the master branch in GitHub pages.  To deploy a website you follow the following steps:
1. Go to GitHub repository
2. Go to "Settings"
3. In Settings, find the "GitHub pages"
4. Click on  "select source" and then select "Master branch"
5. Save
After a small while a live version of you website is published and presented: https://hddahdda.github.io/Udden-Artgallery/ 

To "clone this website" 
* you copy this link: https://github.com/hddahdda/Udden-Artgallery.git
* In a empty repository, open the terminal in your code editor and write the command: git clone https://github.com/hddahdda/Udden-Artgallery.git
* Pressing "Enter"

I would recommend doing this in GitPod which is a free code editor where you could simply use your GitHub account to login.  
* To view your project in GitPod write:
"python -m http.server" in your command bar.

* To view which files has been changed or committed put:
"git status" in your command bar

* To add files that needs to be committed put;
"git add filehere.html" in your command bar.

* To commit your file to Git put:
"git commit -m comment on the commit here" in your command bar.

* To push your files och changes to the files to GitHub put:
"git push" in your command bar.

There are other ways of cloning this website, you could also [Fork](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) your website or you could go to https://github.com/hddahdda/Udden-Artgallery press the "Code" button then "Download Zip" for then to be downloaded. You then need to "extract" them to be able to work with them in your code editor.

## Credits 

### Code credits

* Keyframe code snippet is borrowed from the "Love Running" project at Code Institute. 
* Modal from: https://getbootstrap.com/docs/4.5/components/modal/

### Colors and fonts 
#### Colours: 

* Mozilla Color Picker: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Color_picker_tool
*  ColorPick Eyedropper: https://chrome.google.com/webstore/detail/colorpick-eyedropper/ohcpnigalekghcmgcdcenkpelffpdolg?hl=en

 #### Fonts: 

* Google Fonts: https://fonts.google.com/

### Media

* All images are taken from Unsplash. 

### Acknowledgements

* Mentor Brian Macharia

* Moderna Museet for inspiration in designing the website.

* https://www.moma.org/ - inspiration in designing the website.
* Friends Jasenko and Harald for support.
