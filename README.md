# Introduction to Web Design Workshop
Hello, from Dalton's Girls Who Code club! This lesson is designed for our workshop at the Bit by Bit 2023 conference. All of the files and instructions are contained in this repo - have fun! :
)

## Project Description
We are creating a basic website where if you click on the main image, it will play a random song. Through building this website, you will learn about the implementation of:

* Audio Tags
* Google Fonts
* Images/MP3 files
* Javascript Event Listeners
* CSS Transitions
* Math.random

## Lesson Plan / Instructions
### Let's start by compiling your 'playlist':
* Find 3 songs on youtube (you can add more later!)
* For each song, convert the youtube link to an mp3 file using a converter website and download it.
* Rename each of your downloads to contain the song title in camelCase (ie. "Taylor Swift - Picture to Burn.mp3" to "pictureToBurn.mp3")

See our example image --> gif and choose your own! You could also have your button transition from image --> different image or color ---> different color. 

### Opening/Setting up a file for your website (instructions are written for replit):
** Note if you want to use IDE (VS Code, Sublime Text...) : these instructions can be adapted, but keep in mind that the images/files will have to be dragged to a folder on your computer - the same folder that has your HTML file.  
* Using replit create a new HTML/CSS/Javascript file
* Drag in your 3 mp3 files and images into the left hand dock of replit - where the file names are listed. 

### Let's begin coding! Head to "projectExample.HTML" and there will be comments within the file to guide you from there.

### Once you've arrived back, it's now time to do some final touchups. 

### How to use Google Fonts:
* Pick a Google Font: https://fonts.google.com/
* Click on the font you want, scroll down until there are different font weight (thickness) options and select the one you want using the '+ Select __' on the right.
* Once you have selected the font a window on the rightside should have appeared automatically. 
* As it states, copy and paste the first (and typically longer) block of code right after your title tags (<title></title>).
* You can apply this font to your whole website by having this in your style section and replacing the font-family with the second block of code that you can copy and past from that right side window on Google Fonts.
```
body {
  /* replace the line below with the CSS rule specific to your font family */
  font-family: 'Sigmar', cursive;
}
```

## Troubleshooting - Is something not working?
That's alright! Issues and debugging in coding is such a common thing! Let's try to figure it out with some common ways to find bugs:
* If you're using and IDE and running the file in your browser, double click and 'Inspect' your page. Find the "Console" tab and you might find errors there which will tell you what line to look at.
* If part of your CSS/style code isn't working, make sure you have your semicolons following each line and no typos!
* Not either of these? Ask- what part of my code isn't working -- is it that when I click, the song isn't working? --> check out your audio tags, make sure file names align and no typos, check your random number, maybe it's accessing an item that doesn't exist.

