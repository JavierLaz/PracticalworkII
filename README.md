# PracticalworkII
A repository of a webpage explaining my experience in the double degree of computer science and mathematics in the UFV, with focus on fundamentals of computer engineering and a topic of my choice. 






# Index.html Push

The development of the index page can be explained cronologically and by items: 

## Stages of development:

### Layout: 
The layout of the webpage was the first development, consisting mainly on sketches of a basic webpage: A header with a navigation bar, main body subdivided in section and footer, implemented in both the css and main file. 

### Classes: 
The main classes were inspired by the activity iii page and the different ones were brought up depending on the features intended. 

### Items: 
Once the structure was mainly designed the development focused on putting the content and fixing some incompatibilities and some slight design changes. 



## Files


### CSS file: 
The creation of the css file was the main task while developing index.html since it is the foundation for the rest of the pages. 
The css file changes the style of certain tags like nav or header and creates various classes like header-title or main-content. 


### index.html file: 
The index.html file was created based on the activity iii html file, using the flex display, the containers and the footer structure. 
While the content was a brief explanation of the project's requirements. 



## Issues 
Adjusting the different properties of the classes and positions to give a consistent although basic layout. 
Attempts at implementing certain features too complicated like an email form that would require external code. 

## Solutions
Most issues were solved by searching examples in pages like w3schools.com and stackoverflow. Although the lack of consistency between sources resulted in a less than ideal framework for scalability and reuse. 

# Contact.html push 

## Stages of development
### Investigation:
Revision of the information about forms taught in class. 
Online investigation on the properties of form, label and input. 

### Css style: 
The css of the form consists of two main styles for the labels and inputs: 
#### Normal:
The boxes take the whole width and have the transition property which changes the behaviour, such as delay, between states of the classes.
#### Focused/selected: 
Once the box is selected there is a highlight of the border. 

### Contact.html: 
The page follows the blueprint of the index page, with the same header and footer. The form has 4 mandatory fields, with email requiring the "@" character because of the type=email. 

## Problems: 
The implementation of the form did not cause many errors, mainly some distribution mistakes and syntax problems. 
## Solutions: 
Revision of the code and trial and error. 


# About.html push: 

## Stages of development
### Curriculum vitae: 
The first step was to design a curriculum vitae with some basic facts about myself and my career based on units 2 and 3, technical skills, soft skills and professional profile. 

### Implementation:
The page is divided in two sections: the technical information and the personal information. 
#### Technical information: 
The technical information is divided in different sections,each with an id that can be accessed through the about dropdown in the header.
### Personal information: 
There is a photo of myself as well as links for my social media in the logos' images. 

### About.html
The structure of about.html is the same as the rest in header and footer but the body is different than the others by making a division by columns. This was done after researching possible ways and finding the row class division with 2 column classes. 

## Problems: 
Finding how to make the division and mainly aligning and resizing the images. The footer alignment was also harder than the previous pages. 

## Solutions: 
Although not great, using specific sizes for each image was way to solve the resizing issue. The footer mistake was fixed by solving a syntax error. 


# Degree.html push

## Stages of development


### Implementation:
The page is divided in two sections: The aside side bar and the subject information. 
#### Aside side bar: 
The side bar uses the conditional css style of different div containers. The condition consists of the checked attribute of the sidebar id.
The main side bar container uses a static positioning for the purpose of moving the rest of the content when appearing, while the list content uses a fixed position to always stay on the left side of the page, independently of the scrolling. Moreover, the menu button is fixed on the top left corner. 
### Subject information:  
The first step was to gather the information of each subject through the UFV's webpage.The information used for each subject consisted of the contents taught for the subjects in the first term of the first year, and the contents of the study plan for the rest. 



## Problems: 
The display of the side bar was the toughest part of the work. The difficulties arose from: Making the list scrollable and show all the links while keeping it fixed and move the subject content. 
Moreover an unsolved problem is the fact that the aside scroll bar is visible and disturbs the rest of the webpage. 

Another problem that occured during the development of Degree.html was a wrong implementation of the .gitignore. The fix resulted in an incompatibility between the github version and the current version, leading to an unsuccessful merging and the need to restore previous versions. 

## Solutions: 
The main solutions were trial and error and  looking at different stackexchange forums where each problem was addressed individualy such as, https://stackoverflow.com/questions/72236952/can-a-gitignore-file-have-a-name#:~:text=No%2C%20it%20can't.,gitignore%20. | https://stackoverflow.com/questions/48247695/git-warning-unable-to-access-gitignore-permission-denied-gitignore-direc | https://stackoverflow.com/questions/9811465/scrollable-div-inside-container . 
