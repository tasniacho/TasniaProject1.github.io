# TasniaProject1.github.io
CSC 5750 Personal Project 1

The purpose of this project is to practice writing basic web pages with HTML and CSS and deploy
them. You will have to write 2 static web pages and at least 1 CSS sheet. You can do this using a text
editor such as Notepad editor. You are not allowed to use any HTML-generating tools, such as
FrontPage, for any part of this project.
- The 1st (index) web page is your personal home page.
- The 2nd web page is your course page, where you can write about your current school
schedule list of courses and projects/assignments.

Part 1: Personal Home Page
Create a page named index.html that describes you. On your page, include some or all of the
following information (just a suggestion):
- Your name
- A short bio or description of yourself.
- A list of classes you are taking right now. Make a link to your course web page. Hints: Use
relative URLs so that links don’t break as the pages are moved. All file names are case
sensitive.
- Your 3 favorite sports, movies, books, or TV shows. Make at least one link to an interesting
site.
- Two images (e.g. one of your personal pictures) or you can even use an introductory video
instead.
- Include a table.
- Should use at least 10 different HTML tags
- 
Part 2: Personal Course Web Page
Create a personal course web page that describes courses you took/are taking and highlight some
noteworthy assignments/projects.

Part 3: Style Your Page with CSS
Create at least 1 CSS style sheet to improve the appearance of your web pages. The pages must have
the same visual structure to give the site consistency and the style sheet(s) should define different
color schemes and fonts and be interchangeable (i.e. all pages should work with the stylesheet(s)).
You should define the styles for each different element used in your web pages.

Part 5: Deploy Your Web Site using a hosting service like Amazon Web Services
You may host your website using AWS Elastic Beanstalk, AWS S3 for static websites, Netlify, or
Heroku (or any other hosting service you want to use like Microsoft’s Azure App Service, etc.).
Guides embedded below
Some key notes if you are deploying your website using the AWS Elastic Beanstalk service:
- Name your Environment in the format: firstName-LastName-Project1, e.g. john-smith-
project1
- Remember to only launch t2.micro instances. All other instance types cost more money!
- Just create one application. If you make any changes, you can deploy a new version in your
current application.
AWS Elastic
Beanstalk hosting a website.docx
AWS_S3_Deploy_stat
ic_website.docx How to deploy your website using Netlify.pdf Depoly_using_heroku
.docx
Project 1: Creating a Personal Web Site
3
- Your main page must be named “index”
- Put all your html, CSS, and image files under the same folder, and zip them up. Please don’t
include the parent folder in the zip file. In other words, the “index” file should be in the root
directory of your zip file. Otherwise, the system will not be able to locate your files. Refer to
the guide for more details.
- Terminate the environment after each use (unless I ask you leave it on for grading). It will
terminate the underlying EC2 instances.
