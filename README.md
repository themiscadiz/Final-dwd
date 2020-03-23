<!-- Every README should start with an H1 -->
# Final Project - Voting Website for your Favorite Animal
<!-- A one sentence description of the project or assignment -->
## This project is a Website where the user can vote between four options for their favorite animal. 

## Click below for watch Video
[Video_Documentation](https://youtu.be/11yXDBP00xk "AnimalVoting - DWD")

<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/11.png" width="60%">

<!-- It is good practice to add an about or summary -->
## About
The website starts with a selection of four animals to choose from. After you click on your favorite animal, the user will see a confirmation that they already voted for a specidfic animal. Also, you can see how many votes each animal has in total and compare their percentage of votes to the other animals. The website uses node.js to create the database and have persistent data. 

<!-- It is essential to describe how to set up your project -->
## Setup
<!-- Any knowledge or tools you will need before hand -->
### Prerequisites

The following prerequisites are necessary:

A text editor - like VS Code
Terminal or Command line.
Install node.js
Postman - to manage your database
Glitch - to deploy your website

* To setup the project you need access to a computer and the internet. 
* To be able to see the website you can go to [Glitch Website](https://themiscadiz-final-dwd.glitch.me/)
* To use your terminal or command line to locally host your website (in case of Mac)
* Download P5.js libraries to run locally your p5 code. 



<!-- any installation needs should be defined -->
### Installation

To see the website you can go to [Glitch Website](https://themiscadiz-final-dwd.glitch.me/)

<!-- Write instructions on how to start working on your project -->
### Develop
**If you want to host this website locally:**

1. Open and use Node.js through your Terminal.
2. Initialize node.js
3. Install express, path, nodemon libraries using <code> npm install </code>
4. Use <code> .gitignore </code> for the folder that you dont want to make it public on Github if you plan to make a repository.
5. Download P5.js libraries to run locally your p5 code. 

Create an Glitch Account to Deploy the website.
Create a Postman account to manage the database

## Built with
* [Nodejs](https://nodejs.org/en/)
* [VS Code](https://code.visualstudio.com/)
* [Github](https://github.com)
* [Glitch](https://glitch.com/)
* [Postman](https://www.postman.com/downloads/)

## Authors
* [Themis Garcia](https://github.com/themiscadiz) -- NYU ITP student

***
***
***

<!-- For your assignments you might consider  -->
# Notes & Process

Note: Because I did a lot of trial and error, this project was developed in different Github repositories:
See here other versions: [Final project with NeDB - (it host locally)](https://github.com/themiscadiz/Final-Project) 



Mobile             |  Tablet  |  Desktop
:-------------------------:|:-------------------------:|:-------------------------:
<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/Documentation%20Wesite%20Design-01.png?raw=true" width="100%"> |  <img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/Documentation%20Wesite%20Design-02.png?raw=true" width="100%"> |  <img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/Documentation-Website-Design-03.png" width="100%">


## Design Process

<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/8.gif?raw=true" width="100%">

I had different challenges to acomplish during this process assignment. 

For my proposal a intended to: 

* Get multiple options for voting
* Responsive design
* Persisten data
* Visualize in a graph the amount of votes per animal (P5 sketch) 
* Open a window to confirm vote

Although I didn't not completed all of my original goals (open a new window to confirm the vote), it was good for my process to make a clear priorities that I wanted to complete and what options I had to get the main concept of the design. 

## Sketches

In this experience sketches were essential to understand from the beggining what were my design goals. This helps me to have a more focused approach when I was making the frontend of the website.

**Sketching**

My first concept was to make a window that opens to let the user confirm the vote that its casting. Because some other parts of the assigment took me more time that espected to make it work, I wasn't able to put this version in practice.

Desktop             |  Mobile  
:-------------------------:|:-------------------------:
<img src="https://github.com/themiscadiz/DWD-Proposal/raw/master/Images/1.png?raw=true" width="100%"> |  <img src="https://github.com/themiscadiz/DWD-Proposal/raw/master/Images/5.png?raw=true" width="100%">

**Reiterate the Wireframes**

However, the essence of that interaction is to confirm the vote. That is why I decided to just include a message when a person votes for a specific animal. The message indicates the animal that the user voted for.

<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/14.png?raw=true" width="50%">

**Style Guide**

The process of making my Style Guide helped me to visualize with anticipation, how I want to separe my sections to make it responsive. This gives me clarity in the CSS development. Although I applied also other measuramentes, I mostly used responsive width and height for my design.
<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/19.png?raw=true" width="100%">

## Development Process

In this assignment I started creating the folders and dependencies for my database and communication with node.js. Although it is a setup step, I sometimes get confused and consulted with the class material to make sure what steps to follow.
<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/1.png?raw=true" width="50%">



### Accesing two objects for voting and creating a database in NeDB

I continued working on a concept that I was trying to achieve for previous assignments: Make possible to choose between multiple options. I knew that this exploration was going to be complicated so I started from were I left my code last time. In my process of learning I need to repeat the task, to be able to understanding it a little bit better each time. 

Accesing Database from NeDB             |  .
:-------------------------:|:-------------------------:
<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/2.gif?raw=true" width="100%">  |  <img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/3.gif?raw=true" width="100%">

Accesing Database from NeDB             |  .
:-------------------------:|:-------------------------:
<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/9.png?raw=true" width="100%">  |  <img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/10.png?raw=true" width="100%">

One of the most challenging things in this part of the assignment was to update each animal in the database. I used If statements to pair the selected Item with the Id and update the number of votes.

After I was able to vote for two options I decided to work in a new version of the code were I started from the beggining creating the database. Even though I was repeating some steps from previous assigments, it is always something new to figure it out how to make it work. 

From NeDB to MongoDB

I started this project using NeDB for create the database. My purpose was to have a better flow with my last assigment approach. However, I tried to upload to Glitch and Heroku this version and I had problems accesing the website. I suspected that the problem was around using P5.js or how I created my database. I emailed the professor and concluded that to better understand the nature of the problem I need to make my database in MongoDB Atlas. I followed the two tutorials provided by the course:

* [MongoDB Guide - Joey Lee and Cassie Tarakajian](https://github.com/itp-dwd/2020-spring/blob/master/guides/mongodb-guide.md)

* [Database Services Guide - Joey Lee](https://github.com/itp-dwd/2020-spring/blob/master/guides/database-services-guide.md#mongodb-atlas)

The tricky part of setting up the database with MongoDB was figuring out that I had to change the Schema to see the right result. Before I was seeing the wrong message to put it in the database. So I changed the Schema to:

<code>const todoSchema = new Schema({
  "animal": String,
  "votes": Number
});</code>



### Adding new animals through Postman

Because this step I haven't done it correctly before, it is always confusing how to add new object to the database. Thanks to the Postman tutorial it was more easy to add *key* and *values* to the object. Definitely was very satisfying see the information be update it into the database. 
<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/8.png?raw=true" width="100%">


### HTML CSS and JS

I started early in the process to work on the frontend of the website. Although I had previously made a similar design with multipled buttons, this time I was also making the website responsive. 

<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/3.png?raw=true" width="50%">

I organized my html in sections identified with Id's to make the buttons to communicate with the main.js file and give it style in CSS. I left an available "div" in the page to simulate the space were the P5 canvas it is going to be located. The to follow better what I am doing in the css i like to color the divs and section to understand how I manipulate the sections. 

<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/1.gif?raw=true" width="50%">


**P5 Sketch**

The first and easy approach to use a p5 canvas into your website is to embed the code from the P5 web editor.  However, I thought because I am using Nedb locally I didn't have a way to call the api from the P5 web editor. I decided to work in a P5 sketch locally. 
<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/4.gif?raw=true" width="100%">
Originally I didn't have an intention to make and interactive visualization. But I was creating the graphics, I noticed that using P5 for this, and not making interactive could be a lost opportunity to experiment. Having said that, during the process I didnt figure out how to feed the animation of the shapes with the data that I was recieving from the database. 

I believe that the problem was that I wasn't able to update the data of the canvas without interferring with the actual information of the animal votes. 
Looking on the internet looks like passing a variable into a function doesnt affect the outside variable. A friend told me that maybe I was trying to reference a variable, but I didnt figure it out how to make work in js. 

<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/13.png?raw=true" width="50%">

I decided to make circle to visualize each information of the animal. The size of each circle is relative to the percentage of votes. So if an animal recieve more of votes it circle will be bigger while other circle would be smaller. If you hover the mouse inside the circle you can see what percentege of the votes that animal has.



<!-- How you built this project - Include images, gifs, and notes here ## Process & Documentation -->

<!-- Any specific challenges or struggles documented -->
## Challenges & Struggles

Because in general there is a lot of information to absorbe and apply during this process, I have to say that I encountered difficulties during each step of the development process. The hard part is not only ignore the reason why something didnt work, but also try to understand how sometimes you make it work. I think that that is the main reason why I feel that some challenges or struggles were to obscure to understand. 🙃

My process is heavy in challenges. Sometimes I spent a lot of time figuring out things that I was hoping to be fast and easy. 
**However, I noticed that things that were a challenge 3 weeks ago, this last time it weren't. That gives me hope!**

### The things that were more challenging were: 

**Accesing file in outside folders**

* I still have difficulties referencing files outside the views folder. I researched about how to referencing this folder but I wasn't able to make work.

**P5 Integrated in the website**

* Figuring out how to add a canvas in a specific area of the wesite. I found a P5 reference that helped me to achieve a specific location, but is not precise.

* Make a specific file for P5.js outside the main.js file. 

* Make a more dynamic sketch using the variables from the database.

**Creating a database**

Definitely this was the most challenging and abstract part of the project. Although my use of a database I consider to be simple, and have access to multiple tutorials, it is another state of mind and how to interact with a system that I am not used to.

**Deployment on Glitch**
* Not sure exacly why, but this time Glitch gave me a really hard time uploading the git repo. The errors on Glitch are not super clear, so it was hard for me understand the source of the problem.

**Trying Heroku**
* I tried to deploy my website on Heroku and also gave me errors.

Heroku screenshots             |  Heroku screenshots  
:-------------------------:|:-------------------------:
<img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/16.png?raw=true" width="100%"> |  <img src="https://github.com/themiscadiz/Images_for_Final_Project_Documentation/blob/master/Images/18.png?raw=true" width="100%">


<!-- Any questions you have -->

## Next Steps
For this project I built a simple voting system. Maybe I got this idea because we are in presidential election year, but I consider that this project give the fundaments to explore how to build and use adatabase and how to store different type of information added by the user. Definitely was a fun concept to approach a fully dynamic website!

However, if I was going to deploy a voting system I have to develop and think about solutions for this next steps:

* **Voters and vote’s integrity** 
- Make sure that the user can vote only one time. 
- Make and option to confirm their vote.
- Make the database secure and secure privacy

* **Administrator Experience** 
- it would be interesting to develope an area were an admin can support the system and analyze the data.

* **Analytics** 
- Include a dashboard were users can explore the information of the voting trends 

<!-- References for resources and inspiration -->

***

## References

* [MongoDB Guide - Joey Lee and Cassie Tarakajian](https://github.com/itp-dwd/2020-spring/blob/master/guides/mongodb-guide.md)

* [Database Services Guide - Joey Lee](https://github.com/itp-dwd/2020-spring/blob/master/guides/database-services-guide.md#mongodb-atlas)

* [express api tutorial - Joey Lee](https://github.com/joeyklee/simple-express-api)

* [Instance Container P5.js](https://p5js.org/examples/instance-mode-instance-container.html)

* [HTML File Paths](https://www.w3schools.com/html/html_filepaths.asp)

* [Serving static files in Express](http://expressjs.com/en/starter/static-files.html)

* [Problem serving static files with Express](https://stackoverflow.com/questions/53308128/problem-serving-static-files-with-express)

* [CSS file is not working in NODE js](https://stackoverflow.com/questions/37931357/css-file-is-not-working-in-node-js)

* [Heroku Tutorial For Beginners](https://www.youtube.com/watch?v=aUW5GAFhu6s)


<!--   <img src="" width="100%">  -->
