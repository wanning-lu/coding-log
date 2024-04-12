# Coding Log

**CURRENT**\
[Week 1](#day-1-march-30th-2024)

**OLD**\
[Week 1](#day-1-march-12th-2023)\
[Week 2](#day-8-march-19th-2023)\
[Week 3](#day-15-march-26th-2023)\
[Week 4](#day-22-april-5th-2023)\
[Week 5](#day-29-april-12th-2023)

## Day 7: April 11th, 2024

Can't lie, the MLP is very frustrating...the training error values kept getting stuck at amounts that were too high for my liking. My advisor suggested methods like batching, so I'll be working on that, and perhaps implementing that for the LSTM we'll be working on.

## Day 6: April 10th, 2024

I've been focusing on my research project as of late–it's on rendering expressive musical timings, given the sheet music timings. I'm mainly working on the AI models, as well as processing the data (csv files with the timings). Just working on tweaking our MLP today.

## Day 5: April 7th, 2024

So, I finally decided to dive into it. I learned how to crawl the web with Selenium! I realized that I felt more motivated about collecting the data than making the website first, so I've successfully pulled all the data from the UCSD degree planner on required courses for each major. I also started working on scraping data for details on each course (such as prerequisites and descriptions).

## Day 4: April 5th, 2024

The main focus of today was on static vs. dynamic pages, as well as how to load dynamic pages by using `<Suspense>` and streaming. There were also some useful APIs for searching and routing.

## Day 3: April 2nd, 2024

Today, I mainly did some database/data fetching. The core takeaways were that data fetching doesn't rely on the use of an API layer, at least server side. You can just query your database on the server and do some direct calls using SQL to populate your components with the data. Also, yes, I skipped April 1st. It was my birthday!

## Day 2: March 31st, 2024

Did a little more of the Next.js tutorial; learned a lot about how Next/React components just make web design so much smoother. For example, the nitty gritty behind image and font optimization is taken care of you, so you don't have to worry about responsiveness, fonts being loaded client-side, etc... Links are nice as well, since they preserve the components that don't need to be re-rendered every time.

## Day 1: March 30th, 2024

We start again...this time, with React and Next.js! I've been letting the ideas simmer in my head for too long, so I thought it was time to learn a tech stack that would properly accommodate what I actually want to build. I went through the React tutorial a few days ago, and I wrote down what I learned (privately, in a markdown file), and I'm going through the Next.js tutorial now. If you're curious, all of the tutorials I'm learning from is on the official [Next.js site](https://nextjs.org/learn).

## Day 1: August 31st, 2023

I haven't been doing too well. On the bright side...it's only been 4 months, and not 4 years. That's alright, isn't it?

Well, I took a look at where I left off for TOP. Truthfully, I felt a little lost and overwhelmed, as well as demotivated. I don't even know what kind of projects I want to make. Maybe I'll simply jump into making a project, rather than prepping myself and continuously learning for when I do make my own project. But it's good to start this again.

## Day 38: April 26th, 2023

Started working on TOP restaurant project.

## Day 37: April 25th, 2023

These updates might be a little more short since I don't think there's a need to talk too much about what I've done–it can be summarized into succinct phrases and sentences. Finished TOP ES6 modules + webpack readings.

## Day 36: April 24th, 2023

Progress made today! I completed the [Tic Tac Toe](https://github.com/wanning-lu/the-odin-project/tree/master/tic-tac-toe) project since I finally finished implementing the win condition. I think I'm getting really comfortable with the organization of my code as well as documentation. In addition, I'll probably stop adding images to my READMEs and try to add GIFs/simple explanations if possible.

## null: April 21st-April 23rd, 2023

To be honest, not much was done...I tried exploring a lot more out of my bounds, such as with Linux and AI. They have a higher barrier of entry imo, due to the level of math needed w/ AI and the commitment to install any Linux distribution. That's about it from me though...

## Day 35: April 20th, 2023

Started the Tic Tac Toe project today! Honestly, it's a lot. I had to plan everything out on my iPad beforehand (such as the game logic, board logic, down to the individual cells) so that I could understand the layout of my project. I think I got it down, however! I implemented a lot of the project today and I actually managed to finish a lot of what was necesssary, up until the game logic. I borrowed a lot of the logic from the Odin page "Building a house from the inside out", but I created my own website design, which, to be honest, was not terribly complicated.

## Day 34: April 19th, 2023

Decided to get back on the Odin track! Today was more of a reading day, where I learned about factory functions and modules. Honestly, it makes a lot more sense than constructors, but I really feel like Java classes make a lot more sense than...JS. I'll start the project tomorrow.

## Day 33: April 18th, 2023

Today was less of a coding day and more of a "watch a CS50w lecture" day. I watched the last lecture of CS50w, which was about scalability (figuring out how to scale up your web apps so that they can accommodate multiple users) as well as identifying security vulnerabilities in multiple aspects of your web app (such as anchor tags in HTML, SQL injections, etc.). I've decided not to finish the CS50w project since it doesn't incorporate much from the recent lectures and seems like a rehash of the commerce project.

## null: April 17th, 2023

I'm getting sort of sloppy nowadays :P I hope that I can at least keep coding consistently for the next week.

## Day 32: April 16th, 2023

So, I figured it out, but I think it was really dumb imo. The `div` container for my image had a minimum height that was automatically set to `auto`, which is why my images always kept overflowing the book container. I had to set it to `0`, and of course the layout started working again. Vertical layout is such a pain !!! On another note, I spent quite a bit of time styling the page...it looks OK, I guess. I still need to find out a way to code and document more efficiently. Surely there's a guide to this somewhere on the internet, right?

## Day 31: April 15th, 2023

I started pivoting from working on CS50w back to The Odin Project–surprisingly, it wasn't that hard to get back into working on the library project. Since CS50w also had JS content, it wasn't very difficult to get back into coding in JS. Also, TOP is conceptually easier than CS50w atm; it's more like a DFS into front-end than CS50w, which is more like a BFS into full stack development (_wink wink nudge nudge_). I managed to create the cards and implement a functionality for adding a new book, but layout is messing me up again...darn images.

## null: April 14th, 2023

Today was not a good day. It was the due date for a lot of my assignments, meaning I didn't really have time to focus on my coding projects.

## Day 30: April 13th, 2023

God, today was just a day of _debugging_. Honestly, it felt like I had a mental block all throughout my coding session; I took the entire time to debug the follow button + the feature, and in the end, it boiled down to a few syntactical errors that I made while writing my `urls.py` and API. At least I got it done!

## Day 29: April 12th, 2023

I started the fourth project today! Conceptually, it was very very similar to commerce, which I found pretty surprising. I worked on it until I implemented features to view all posts, create posts, and visit a profile page. I left off on implementing the follow feature; for that, I'm planning to create my own API with Django and using it with JS.

[To the top](#coding-log)

## Day 28: April 11th, 2023

I finished the 7th lecture today as promised, and I learned about some tools like Selenium (testing for JS in Django), unittest (in Python), and Docker (which allows for the standardization of packages/environments/etc). Haven't done much actual coding today but I will definitely get started on the fourth project tomorrow.

## Day 27: April 10th, 2023

Finished [the third project](https://github.com/wanning-lu/cs50w-projects/tree/main/project3_mail)! This one was definitely significantly easier; all I had to do was implement an archive feature (which was pretty easy w/ a PUT request) and allow for users to reply to the email (which was accomplished by fetching the email information and prefilling the input fields accordingly with `.value`). I'll be watching the second to last lecture of CS50w tomorrow, which focuses on testing + CI/CD.

## Day 26: April 9th, 2023

This CS50w project has so far been significantly easier than the second; I'm already halfway through and the main learning outcome of this project has mostly been to connect the frontend to the backend through the usage of APIs. The project came preloaded with some APIs already defined in the `views.py` and `urls.py` of the app, so the project was focused more around creating event listeners for HTML elements and sending requests to the URLs. I'm starting to feel somewhat confident with my JavaScript skills with this project and the previous TOP projects!

## Day 25: April 8th, 2023

Today I was working a bit on the design patterns section of TOP, focusing first on the object-focused design pattern. I've read all the material and I think I'm around halfway through the project (it's not terribly complex nor long) so I'm hoping to finish this project tomorrow and get started on the 3rd CS50w project!

## Day 24: April 7th, 2023

Didn't do too much actual coding today, but I updated all of the README files for my CS50w projects, since I think it's good to get some practice in for documenting my work. I'll be trying to refine my documentation as I go; so far I'm including not only the functionalities of my projects but also the learning outcomes, which I believe will be helpful for reviewing concepts later on.

## Day 23: April 6th, 2023

_Wow_, finishing the commerce project was a marathon I don't feel like I was prepared for. Every minor bug that caused me to go on a 10 minute hunt through Stack Overflow just drained my motivation over and over, but I FINALLY finished this project! I can't imagine having to take this class normally in a school semester/quarter, it just seems rough. My code was definitely very disorganized, as well as repeated, which is something I regret. I think I also need to add the README files to all the projects I've done for CS50w so far, just to improve my documentation and review what I did for the project. But congrats to me! I guess I'll be starting on the week 5 lecture tomorrow.

## Day 22: April 5th, 2023

I think I made some good progress today! I figured out the CSS for the active listings (which was quite simple with Flexbox, ty Flexbox). Afterwards, I was just figuring out the logistics of implementing the other aspects, including the watchlist, creating new bids, closing a listing, and comments. I mostly got the watchlist to work, including the button to add/remove it from a watchlist. I just have to implement the watchlist page for each user. Hopefully I can finish this project by tomorrow.

[To the top](#coding-log)

## Day 21: April 4th, 2023

I mostly just worked on the CS50 project today. I fixed my mistake of putting the entire listing on the active listings (too much detail), and made a listing page for each individual listing. I've left off on creating the HTML/CSS for the active listings page, which I'll work on tomorrow.

## null: April 1st - 3rd, 2023

Not a happy update, but a lots been happening in the past 3 days. I celebrated my birthday and moved back to my dorm all during that span of time, so I haven't been focusing too much on my coding progress. I do plan on getting back into it today, however!

## Day 20: March 31st, 2023

Ok, even though I _technically_ finished the [dashboard project](https://github.com/wanning-lu/the-odin-project/tree/master/dashboard) on April 1st, I was up at 3AM doing it. To me, I think that counts as being part of day 20. Plus, it's even a disadvantage to me since I already did some coding beforehand, which was implementing the actual listing creation function and formatting the listing UI for it (for the Django project).

I think one thing I regret about the dashboard project is how messy my HTML and CSS turned out. Sure, I saved some time using Emmet, but I don't think I really thought out my HTML layout. For example, I only put classes with incrementing numbers for each child element, which I should've used a universal class for and assigned each element with a unique ID. I guess that's something to keep in mind going ahead.

## Day 19: March 30th, 2023

Continued working on the CS50w project for a bit, but I mostly just created the form for creating a new listing as well as get stuck on the `login_required` decorator :/

## Day 18: March 29th, 2023

Working with anything other than a `div` block always feels like such a pain; I've finished the sidebar for the dashboard, but why was it so hard to put in the SVG?! On another hand, I created the models for the Commerce project (for CS50), and I've started trying to lay down the grounds for what comes next. All of the projects I've made so far with CS50w feel like legitimate applications, it's really exciting!

## Day 17: March 28th, 2023

I started on the CSS for the project, and although I've made a pretty decent layout so far, I feel like I'm still somehow hard-coding it (for desktop, I suppose), even while using relative units (`fr`, for example). I'm actually almost done with the barebones layout, I just need to style the last section (major events + connections).

## Day 16: March 27th, 2023

Just finished the CSS grids section, but wow does that end project look intimidating! At first glance I would assume the UI belonged to that of a legitimate, professional app. I guess my understanding of grid so far has been pretty limited. I'll be starting the barebones of the project today (probably just using only HTML for now) and then hashing out the details later.

## Day 15: March 26th, 2023

Wow, today was tiring. I finished the Django models lecture, where I learned about some more powerful tools (such as ManyToMany), as well as some login authentication! Django abstracts these details so much that it can be as easy as one method of `login(request, request.user)` which is pretty crazy. Now for the major progress: I finished the [forms project](https://github.com/wanning-lu/the-odin-project/tree/master/sign-up-form) for TOP! I feel like a big part of it was designing...more than the actual implementation of the forms...but I did use a bit of JS to implement a "password confirmation" feature. It's tricky switching between Python and JS, because I was held up for a bit before I realized I wasn't typing `let` before my variable declarations. I also moved on to the CSS grids section...which now I'm about halfway through.

[To the top](#coding-log)

## Day 14: March 25th, 2023

Still slogging through the week 4 lecture for the CS50w series; I followed along with about half of the Django section, which was about creating and manipulating databases in Django. I first learned how to create database models in `models.py` and migrate any changes to the actual database. Then, I used the Python shell to make some changes to the databases manually by inserting/selecting/deleting data. However, later on, I learned about how Django admin can take care of most of that action within the shell. Additionally, I used the power of relational databases by using models.ForeignKey, which allowed me to link an object from one database to the cell of another.

## Day 13: March 24th, 2023

Today, I went through the last 5 lessons in TOP before going on to the forms project. There was quite a bit of content on HTML forms, which I didn't expect; validations and styling were some of the main things that I learned. Additionally, I feel like I finally understand how they work and send information, which I didn't before even when creating forms for FCC/CS50w. I've only created the barebones of the form project as of now, with all of the HTML completed (thanks Emmet!) and some styling applied so it somewhat matches the image.

## Day 12: March 23rd, 2023

I worked on a mix of TOP and CS50w today, starting with coding along with the example project for the lecture. I didn't go too deep into the lecture (about halfway in so far), but I've learned how to set up a database inside Django, specifically models.py along with some Django commands to create it. As for TOP,
I started working through their JS path, which begins with some Intermediate
HTML/CSS. Although some of it was repeat knowledge, I did learn about Emmet and CSS functions/variables which was really useful. I'm almost at the project (sign-up form) but I've gone through about _12_ lessons so I think that's something for tomorrow.

## Day 11: March 22nd, 2023

Today, I finished [Project 1](https://github.com/wanning-lu/cs50w-projects/tree/main/project1_wiki) by implementing the "random search" function on the sidebar. It was pretty simple, as all I needed to do was import choice() from random, which allowed me to choose a pseudo?random element from the list of entries every
time. After that, I got started on the 4th lecture, which dove into databases; I watched the entirety of the SQL section, which gave some examples in SQLite on how to create a table and insert/join/delete/search data. The next section will
be on how to work with SQL through Django, so I'm looking forward to that!

## Day 10: March 21st, 2023

TBH, I didn't do much coding today. I was focused on packing and moving back, and the entire day has been dedicated to meeting up with familiar faces.

## Day 9: March 20th, 2023

Made some progress with Project 1 today, up until implementing several search functions. Setting the Django project up definitely requires some practice; even after going through the lecture and following along with every step, I still found myself wondering what commands I needed to use, as well as how I should use certain Django features. There are a **lot** of Django modules that I need to remember to use. After overcoming that initial barrier, however, I've successfully implemented the ability to visit a specific "wiki" page with a url pattern, as well as implement a search function for an existing wiki page. I'll try to finish the project by tomorrow, it seems pretty doable! Also, all of my finals are done, so I'll definitely have a lot of time to dedicate to coding during my break :)

## Day 8: March 19th, 2023

I finally finished the Django lecture! During the rest of the lecture video, I learned more about Django logic within HTML files, as well as several "tricks" that make it easier to control the web application from one spot, rather than scattered across the codebase (for ex. using HTML templates, naming the page that correponds with the URL). I coded along with the example, and now I have one more app in my example project that can display a list of tasks as well as add tasks, all for unique sessions (due to Django tables!). I'll be ready to start Project 1 tomorrow after my last final!

[To the top](#coding-log)

## Day 7: March 18th, 2023

Today, I worked through CS50's Django week. I've just been watching the lecture and I'm about 1 hour in, but I've already learned so much about making dynamic websites that I can host on my local computer. It's so cool that I can implement logic/variables in my HTML file with the Python files that are generated for me with Django. I didn't expect Django to be so beginner friendly, but it's a nice surprise! It feels like I'm "automating" my website creation process, rather than doing it manually through static webpages.

## Day 6: March 17th, 2023

I'll be pretty honest here, I didn't really code much today. Since it's finals week for me, I've been studying for CSE 12/MATH 20E and therefore haven't made much progress coding; rather, I'm studying code :P However, after my CSE 12 final tomorrow, I'll work more through some CS50. I did finish Project 0, however!

## Day 5: March 16th, 2023

I started on a new project today, also on the theme of web dev. CS50 is a pretty popular online course for programming beginners, but I've started going through the [web dev branch](https://cs50.harvard.edu/web/2020/) along with [sbsx](https://github.com/sbsx), which you can check out his projects there :) I mostly finished [Project 0](https://github.com/wanning-lu/cs50w-projects/tree/main/project0-search), which is about using GET requests from HTML forms to perform Google searches from my own web page. It was a fun little project, and it did expand my knowledge about HTML forms (which, tbh, have been quite a weak spot for me).

## Day 4: March 15th, 2023

I finished writing the tests today, although it took much longer than I expected. I also styled the last bit of my PA, but I usually try to style my program as I go. I also just completed around 80-90% of my calculator project; all of the functions work, as well as the clear button. However, implementing the ability to use decimal points is still a WIP...

## Day 3: March 14th, 2023

Today, I mostly focused my efforts on my PA. I finished off the main bulk of the PA previously (impelementing that actual BST) so today I wrote most of the tests. Additionally, if it counts (I'm half-counting it), I finished my preparation for the CSE 15L skill demo, which involved starting a Java server, fixing a JUnit test, and reading up on some Bash to find out how to retrieve a nested file. Tomorrow, I'll probably finish up writing the tests.

## Day 2: March 13th, 2023

I started working on the next TOP project, which is about making a calculator. I haven't finished it yet, but I've made around 30-40% progress so far (HTML/CSS are basically done, starting on JS for the functions). Additionally, I've been working on [my PA](https://github.com/CaoAssignments/cse12-wi23-pa8-BinarySearchTree-Sorting-starter) for CSE 12 (yup, this counts too!), which involves implementing a binary search tree. Finally, an opportunity to use recursion!

## Day 1: March 12th, 2023

I've been working on [The Odin Project](https://www.theodinproject.com/) for a bit now, on and off, here and there. I've been skimming their "Foundations" course since I already know some fundamentals of web development, such as basic OOP and HTML/CSS. I worked on one [project](https://github.com/wanning-lu/the-odin-project/tree/master/landing-page) prior to the creation of this log, which exercised my ability at using flexbox. Flexbox is absolutely amazing; I feel like if I had known that this existed in my past projects, I wouldn't have wasted so much time fiddling with different settings. Plus, they would all be somewhat responsive. Anyway, I worked on some basic JS today along with some DOM manipulation. Just for fun, I also tried making my HTML button look a little nicer. Here's [the project](https://github.com/wanning-lu/the-odin-project/tree/master/etch-a-sketch), where I created a rudimentary etch-a-sketch composed mostly of JS. This hour of code felt pretty substantial. I feel like I'm genuinely going somewhere this time with web development, rather than floating around looking for resources. If you're still debating whether you should try out TOP, you should just give one of their projects a shot.

[To the top](#coding-log)
