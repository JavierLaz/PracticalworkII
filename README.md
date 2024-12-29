# PracticalworkII
A website repository where there are pages explaining:the practical work II,my experience in the double degree of computer science and mathematics in the UFV, with focus on fundamentals of computer engineering , some facts about myself, and a roadmap to start learning machine learning, and a webpage connecting to other classmates' practical work II. 

The project is structured in three levels, the root folder with the README.md and .gitignore files, the docs which has the public, images and CSS folders, and the index.html file. The final level's public folder, has the rest of the webpages:about, net, fund, degree, topic,contact .The CSS folder contains the css file commong to all the website and the images folder has the images used throughout the repository. 

The practical work II was developed in visual studio code with the Live Preview extension to help in the development of the webpage, although it sometimes caused  problems. 






# Index.html Push

The development of the index page can be explained cronologically and by items: 

## Stages of development:

### Template: 
The layout of the webpage was the first development, consisting mainly on sketches of a basic webpage:
#### Header 
Consisting of the title of the website,Practical work II, and a navigation tab. The navigation has the links of each of the webpages, Home(index), about, contact, topic, Net , Degree.
The background color uses linear-gradient function to give the color changing header. 
Inside the navigation bar there is the Dropdown class and dropdown content.
Dropdown works as the container of dropdown content, which is hidden(display:none) until dropdown is hovered on. 

#### Main Body
The background color is common to all webpages. 
The webpages use the main-container class for most of them, unless they need specific disposition compared to the template. 
#### Footer
The footer is almost a copy of activity III, a flex by row to separate the contact information in three icons. The menu class sets the default text and style to all the footer, then the menu-items makes the icon and text inside it stack vertically through the flex-direction:column;



### Items: 
Once the structure was mainly designed the development focused on putting the content and fixing some incompatibilities and some  design changes.

## Problems 
Adjusting the different properties of the classes and positions to give a consistent although basic layout. 


## Solutions
Most issues were solved by searching examples in pages like w3schools.com and stackoverflow. Although the lack of consistency between sources resulted in a less than ideal framework for scalability and style compatibility with external sources like a lot of images. 

# Contact.html push 

## Stages of development
### Investigation:
Revision of the information about forms taught in class. 
Online investigation on the properties of form, label and input. 
### Contact.html: 
The page follows the blueprint of the index page, with the same header and footer. The form has 4 mandatory fields, with email requiring the "@" character because of the type=email. 
The elements used in the form are, labels, inputs,text areas and a submit button
### Css style: 
The css of the form consists of two main states.
#### Normal:
The elements take the whole width of the parent div as specified by form-container ,although the max width can not be greater than 600px.
 The submit button has the transition property which changes the behaviour when hovered over, darkening the colour. 
#### Focused/selected: 
Once the input labels are selected they area outlined by a blue border. The rest keeps the same. 



## Problems: 
The implementation of the form did not cause many errors, mainly some distribution mistakes and syntax problems. 
Attempts at implementing certain features too complicated like an email form that would require external code. 
## Solutions: 
Revision of the code and trial and error. 


# About.html push: 

## Stages of development
### Curriculum vitae: 
The first step was to design a curriculum vitae with some basic facts about myself and my career based on units 2 and 3, technical skills, soft skills and professional profile. 
### About.html
The structure of about.html is the same as the rest in header and footer but the body is different than the others by making a division by columns. This was done after researching possible ways and finding the row class division with 2 column classes.
The :after condition and the display:none; makes it so that row only affects the distribution but not the content inside it. 
Inside row the 2 columns are assigned a percentage of row, with the main content taking a mayor proportion.
The main contetn implementation was not anything new, however, the contact information pictures had to be calibrated manually.  
The page is divided in two sections: the technical information and the personal information. 
#### Technical information: 
The technical information is divided in different sections,each with an id that can be accessed through the about dropdown in the header.
### Personal information: 
There is a photo of myself as well as links for my social media in the logos' images. 


## Problems: 
Finding how to make the division and mainly aligning and resizing the images. The footer alignment was also harder than the previous pages. 

## Solutions: 
Although not great, using specific sizes for each image was way to solve the resizing issue. The footer mistake was fixed by solving a syntax error. 


# Degree.html push

## Stages of development


### Implementation:
The page is divided in two sections: The aside side bar and the subject information. 
#### Aside side bar: 
The side bar uses the conditional css style of different div containers. 
The condition consists of the checked attribute of the sidebar id as it is a checkout type of label.
The main side bar container uses a static positioning for the purpose of moving the rest of the content when appearing, while the list content uses a fixed position to always stay on the left side of the page, independently of the scrolling. Moreover, the menu button is fixed on the top left corner. 
### Subject information:  
The first step was to gather the information of each subject through the UFV's webpage.The information used for each subject consisted of the contents taught for the subjects in the first term of the first year, and the contents of the study plan for the rest. 



## Problems: 
The display of the side bar was the toughest part of the work. The difficulties arose from: Making the list scrollable and show all the links while keeping it fixed and move the subject content. 
Moreover an unsolved problem is the fact that the aside scroll bar is visible and disturbs the rest of the webpage. 

Another problem that occured during the development of Degree.html was a wrong implementation of the .gitignore. The fix resulted in an incompatibility between the github version and the current version, leading to an unsuccessful merging and the need to restore previous versions. 

## Solutions: 
The main solutions were trial and error and  looking at different stackexchange forums where each problem was addressed individualy such as, https://stackoverflow.com/questions/72236952/can-a-gitignore-file-have-a-name#:~:text=No%2C%20it%20can't.,gitignore%20. | https://stackoverflow.com/questions/48247695/git-warning-unable-to-access-gitignore-permission-denied-gitignore-direc | https://stackoverflow.com/questions/9811465/scrollable-div-inside-container . 

## Post-Degree edit:

### Style change:
After developing the table for net.html I believed it would be better to use the new style for the degree.html page. The table consists of a 3 row table where each row has 2 years of the degree and all their respective subjects and their contents. 
# Fund.html push

## Stages of development

### Page division
The division of the page was simple compared to the rest as it only needed to have a few titles on the body template. 
### Information
The information exposed in the page is recovered from two main sources, the study plan of fundamentals of computer engineering and the personal experience from partaking on the subject. 

## Problems
There were no noticeable difficulties. 


# Topic.html push

## Stages of development

### Page division
The division of the page was simple.Created a .topic-content
### Information
The information exposed in the page is recovered from resources like https://d2l.ai/ https://www.geeksforgeeks.org/ https://www.w3schools.com/
## Problems
There were no noticeable difficulties. 

# Topic.html push

## Stages of development

### Page division
The division of the page was done through new css classes for the net page. These conist on .net-container , .net-row and .net-page . Which have a display:table , table-row and table-cell respectively. These properties allow for an even  distribution of the sites. The rest of the properties were experimented on until reaching a decent layout. 

## Problems
There were no noticeable difficulties.


# Conclusions: 

Despite not liking web development too much, I believe that the practical work II is a beginner friendly project to start developing software. As a beginner I did not feel like the git or the files and directories distribution were complex .Moreover, from the activity III and the information from the presentations I was able to do most of the features and style of the website. It is also true, however, that it was not an easy project, there were times where the styles behaved unexpectedly and trying to implement some features required external research. 

To conclude, this project is a great way to start software development and it could even be improved as our knowledge and experience increases. 