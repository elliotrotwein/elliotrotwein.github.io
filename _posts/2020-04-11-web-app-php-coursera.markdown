---
layout: post
title:  "Full-Stack Development on Coursera"
date:   2020-04-11 15:31:25
categories: jekyll update
tags: featured
image: /assets/article_images/2014-08-29-welcome-to-jekyll/desktop.JPG
---
Over the past two months, I've been spending nights and weekends working through a series of web developer courses on coursera.org. The courses, which are grouped into what is known on coursera.org as a "specialization", is an introduction to web application development using LAMP (Linux, Apache, MySQL, PHP) stack. 

The course also covers Java Script, JSON, CSS and some libraries like jQuery and PDO.  Although, I mentioned the languages first, the focus is just as much learning to code in new languages, as it is focused on learning new web development concepts such as the request/response cycle, MVC architecture and GET/POST/REDIRECT. 

Chuck Severance, a University of Michigan professor who teaches the course, really drives home the importance of understanding the request-response cycle throughout course. Chuck made it known that the web development concepts being taught were equally if not more important than learning the language itself. 

Throughout the course, a diagram of the request-response cycle is shown to describe how the data is traveling between the browser, client and database when a user makes a HTTP request. At the beginning, Chuck starts with the simplest version being the client-browser relationship, and eventually introduces the web server and database server portion along with PHP and MySQL. I won't bore you with a chronicle of everything that was taught in the course as this is intended to be a brief "How did it go?" summary. Instead, I'll highlight some of the projects I worked on and things I learned. (Here’s the course <a href="https://www.coursera.org/specializations/web-applications?#courses">syllabus/overview</a> if you’re interested.)

The first project I completed was a simple HTML and CSS static page that was required to have specific features, like a link, image, headers, lists and basic styling. I say "had to" because the course had an auto-grader that validated assignments for accuracy and completeness. This project was incredibly basic, but a good refresher on a language which I've neglected for so long being a back-end Java developer. Here are the files (*still working on adding these*) if you would like to be amused. All you have to do is download the files to a specific location and then navigate to the index.html file path in your browser to see the static web page.

I also created a rock paper scissors app that just utilized the HTML, CSS and PHP (no DB yet). Then I moved on to making 2 pretty simple seeming CRUD applications that actually involved a lot of code.  This is where MVC, the whole request/response cycle, form validation, DOM manipulation, sessions/cookies, HTML/SQL injection and more all came together into two working projects. Here are the links to both of those projects that now live on my GitHub account: 

1. <a href="https://github.com/elliotrotwein/automobiles-crud-application">Automobiles Tracker</a>
2. <a href="https://github.com/elliotrotwein/resume-repository">Resume Registry</a>

There's a good description of each project in the READ.me file for each repo.

I'll have to say, it felt pretty good to actually complete a few projects from start to finish. I worked in industry writing code for almost 2 years, before I had ever built a "simple" CRUD application! Pretty crazy, right? But in the process of doing so, I learned so much and was able to tie together things that did not make sense when I first started my career as a developer. For example, I didn't really know how to do much with a web server other than stop and start it. In the process of taking this course, I became much more familiar with a web server. I learned how to install the web server itself, install php on the web server, modify configuration files, debug server issues, add/locate logs to error.log, tail -f those logs when debugging and more.

Throughout the process of building these applications, I realized there’s a whole lot that can go into building even the most seemingly simple application. One good example is form validation, which means making sure the user is entering valid text into a field. It's such a simple feature to the user, but it took some work to implement it by writing the validation logic, using flash messages and then implementing the validation on both server and client side. It's small features like this that the user just breezes through in seconds that actually can take a while for the developer to code.

Here's what I'm planning to tackle next: <a href="https://www.coursera.org/specializations/ruby-on-rails?">Ruby on Rails Web Development Specialization</a>

It seems like a slightly bigger undertaking and a good next step. It includes Angular 1 which is sort of dated from what it seems, but I'm more interested in core concepts, trying out a popular MVC framework, and getting familiar with any other tools that come along with it.
