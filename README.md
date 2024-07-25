# cc
  In this file, i'm going to leave information on the coding, where to find what is editable and try to keep everything in one place.


As a reminder;
  Do not at any stage, if you are unsure, do not touch any file ending in ".JS". This can break a few things on the site.
  Especially if you are unsure of what you are looking at.



INDEX:
  Section One - Style sheet. 
  Section Two - HTML Sheets.
  Section 3 - Changing Images.


SECTION ONE
  All the code style choices are found in "Style.css". 
  
  "* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  html {
    max-height: 100%;
    scroll-behavior: smooth;
  }
  
  body {
    height: 100%;
  }
  " should always remain where they are. 
  
  Anything between
  "/****************************************** HEADER PERMANENT**************************************************************/
  
  and
  
  /*media - change if you want to change the display for a device.*/
  "
  should remain untouched for the most part as this controls the base display for your navigation bar. 
  
  However, should you want to change the width of the logo, that can be found in ".nav-logo img" on line 43 or you can ctr + F to search for it.
  
  Beneath "/*media - change if you want to change the display for a device.*/" you will find a series of code labelled "@media".
  This code is the heart of your stylization, it defines how the website looks on different devices. Above each "@media" you
  will find a comment telling you what display this code represents. IE Large screen, small screen etc.
  
  Inside the "@media" sections you will find a comment marking out  what each block of code will look like. IE "Header" or "About Us" etc. These will
  match with the HTML sheet they are referencing.
  
  If you change something in one of these, make sure the site still looks how you want it to on other devices, if something has changed on another display,
  for example the small screen, check that section of code and adjust as appropriate. You may need to add or delete code where applicable.
  
  There is only one image held in "Style.Css" and that is the main image of a plant. It can be found in the subsection titled "HEADER" , code starting
  oint of ".main-.row" starting on line 162. Image changes are discussed in more detail in Section 3.
  
  
  "@media" starts from line 112, in the style.css file.



SECTION TWO
