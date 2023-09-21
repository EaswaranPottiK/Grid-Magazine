
# index.html

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/155dc4ab-278d-48d7-859a-5726f49910ed)

!doctype defines that code written is html

html lang=en specify that language used is html

meta charset specify the encoding user in this it is utf-8

meta name, content is used to ensure consistancy in view among different browser

title is the text written on tab - here magazine is printed 

the first link is used to import fonts from google 

the 2th link is used to import fonts from fontawsome 

the 3rd link is used to bind css code with html

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/109418c8-7fbc-4cd2-81be-0df57d7a5017)

inside main tag there is section with class name heading; inside that there is a header with class name hero 

an image is imported in line no 21; src specify the location of image, text written inside alt is for image reader, loding lazy ensure image is loaded only after all the on lazy elemts have been loaded; class is also specify so that image can be styled 

h1 is used for headings 

p is used to write paragraph

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/d43e09af-6c77-4fbb-8248-be33f0bf3513)

inside div with class author i have specified 2 paragraph tag. This is the text written below large orange colord text 
each p tag has classes lined to it 

a is the anchor tag - provides a link to another website 

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/1ac0fbf7-05e3-4232-b0f2-914ce908e739)

i tag used standered font awwsome classes to import images. These i tags are nested inside anchor a tag

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/aacf3083-7381-45a1-8e7c-a5557767beab)

these are the text printed in main section 

the contents are written inside section with class div. This section consists of multiple p tags 

hr is used to put a line - as a separator 

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/fd1790d7-8cf9-42e1-ac94-88d19e4eb036)

section tag uses 2 classes - text and text-with-images 

it consists of an article with class name brief history which inturn consists of a heading tag, paragraph tag and an
unordered list

each items (li) inside unordered list consists of a heading and a paragraph tag

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/d76f3a8b-d249-4d4b-9d95-5a352d3131b7)

backquote is used to print text aread with a space ie intended block 

hr is use to put a horizontal line 

i have also imported an image; width and height are diamesions of the image, src specify location of the image, loading lazy ensure image is loaded only after non lazy contents are loaded it is helpful for users with slow speed connections 


# style.css

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/eec77f02-72ad-4ebd-b554-c19a38e5bd12)

* is the universal selector; Using * i have made padding (space between element and its div box), magin (space between the div box and parent element) to 0

box sizing border box ensure the elements does not overflow the space allocated 

font size 62.5% means 62.5*16px ie 10px

inside body tag i have made font family to baskervville and backup font family to serif similarly i have changed font of h1 tag also

font color is set to linen (almost white) 

background color to rgb(20,30,40) 

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/dbf4b754-2b32-4ffc-9e01-5a22ece5556c)

inside main i have defined spacing property using grid 

grid-template-column defines the template of columns here to make page responsive i have set values using minmax(). Minmax() speciy the minimum value content should occupy and max value upto which space can be taken 

width 100% ensure all avaiable content is taken 

object fit cover ensure that image get filled int the allocated space while maintaing aspect ratio

margin 1.5rem 0 means there should be a margin of 1.5rem on top and bottom but no margin on left and right

border is specified of 1px thickness soild style and of color rgba(120,120,120,0.6) here 0.6 specify the intensity 

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/6de9ddaa-4b32-4a02-bad5-e3b5ac42060b)

line no 49 - grid column specify that content should occupy space between column 2 and 3

display grid specify that spacing property used is grid 

grid -template - columns: repeat(2,1fr) specify there should be 2 columns with equal width 

row gap specify there should be a gap of 1.5 rem (24px) between 2 rows

letter-spacing defines the gap between each letter

text align justify says to strech lines so that lines have equal length like newspaper 

grid column: 1/-1 says that content should occupy space in last column 

position relative is use so that child element can be said to have position absolute 

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/7003bff0-5c07-4422-a70c-83500cfe434d)

grid-auto-flow: column is used so as to fill items in column; once one row column is filled it will move to next column

grid auto columns: 1fr is used to ensure ean column is of same size 

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/2c9d3a96-761c-4006-8f7d-07537a38064e)

float left ensure contents are aligned towards left side 

.quote tags ensure contents are printed like this:

 "hello there" 

 ie a gap qyote contents quote and finally a gap

 rest of the property i have already explained 

 ![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/09a21e0c-ba90-4f79-b7b2-bc4e60abd326)

list-style-type none is used to remove any style used 

media querys are used to make the website scaleable on differnet screensizes 

in line not 156 says if the screensize is less than 720px then apply css property defined below

![image](https://github.com/EaswaranPottiK/Grid-Magazine/assets/38095510/114b35a5-0a11-4cb9-9239-88aa30af509a)

i have  already explained the the properties used in the above screenshot































