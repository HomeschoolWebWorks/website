Some notes:

This project is built on SASS and Compass. Please learn some more about these by either asking Google or Micaiah BEFORE you delve into the code.
*Micaiah

- Download and install these before using source code.
- http://compass-style.org/
- https://github.com/olivierbossel/gridle

---------- INFO ---------- Hello group! This is just some info for you on what I am doing here.

First this is how I work.

If you take a look at the file structure then I can explain it to you.

First there are 5 folders are needed for the website. To keep everything in order. Please put files in their corresponding folders.

1: PHP - This folder will contain all of our PHP scripts.

2: JS - This folder contains all of our js scripts.

3: img - This contains all the images used on the website. If there is something on the website that is a component or a plugin. Please make a folder in the img folder to contain the images specific for that plugin/component.

4: CSS - This contains the output of the SASS files as well as a reset file.

5: Components - By far the most important folder of the website. The components folder contains 3 siblings.

5a: Fonts - This is where the fonts will be stored for the website.

5b: Ruby - This is where the Ruby files will be stored.

5c: SASS - This folder contains all of the SASS files for the website. Detailed info below.
---------- SASS Folder Info ----------

The SASS folder is where you will go to edit the website's style. There are two sibling folders and one SASS file.

The SASS file labeled "Main" is the import file. This file is where you will enter code to import SASS files from the imports folder. This file is the file to be exported into CSS in the CSS folder.

The imports folder contains all of the components of the main stylesheet. This includes things like basic.scss, buttons.scss, and colors.scss.

basic.scss - This is the basic styling of the website. (ex: h1, h2, a, p, etc)

buttons.scss - This is the style for the numerous buttons that will be on the website.

colors.scss - This is the color pallet for the website. They are in variables so they are easy to link too and remember. 

masthead.scss - This styles the masthead class. The big header in the website. 
Grid - This contains all of the code for the grid system. DO NOT EDIT unless you know what you are doing!!

---------- Grid Info ----------

The grid system is called Gridle. Google it if you would like to learn more.

to use the grid system. You will need to include the mixin like so.

@include gridle(12);

By entering a number in the (). You will call upon a grid mixin setting.

12 is the biggest while 1 is the smallest.

There are mobile classes as well.

Use:

@include gridle(6, mobile);

This will make the HTML element into a grid 6 if the user is on a mobile device.

FOR MORE INFO GOTO: http://gridle.org/documentation

If you have changes, comments, ideas. Contact Micaiah.
