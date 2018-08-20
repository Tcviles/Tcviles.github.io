---
layout: post
title:      "My first job as a developer"
date:       2018-08-20 01:23:22 +0000
permalink:  my_first_job_as_a_developer
---


Back from my 5 month hiatus! on April 31st, 2018 I got my first position as a Software Engineer I at Ontario Systems in Muncie IN. The journey has been wild!!! I just recently finished up my first feature that I coded almost on my own in our Artiva RM product. 

There is a few things that I have learned,, now that I have just recently passed my 1 year mark since downloading my first app on my phone, and learning how to code in Python.


Your first programming language might not be your career language. D
. There are way more languages out there than I even knew of in April, when I first felt comfortable enough to push my resume (empty) onto zip-recruiter. For example, my Do-dot that I used on this entry is no where to be found in python, ruby, or javascript. But for my first position as a developer, I had to learn about a language based off of M programming. Object script, then formed into Intersystems Cache is a language that works great for my every day job,, I mean if you dont like using symple methods like list.sort,, or using css or html the normal way. Actually the language kind of stinks to be honest, but thats okay!. It is a ton of fun to learn something new everyday. In this language, there is a LOT of legacy code. My most recent feature dealt with finance code, and considering our products are typically used by collections agencies,,, that was some old code. I love object orientation, and thats what a lot of my job works on. But rather than objects being a hash of information, like in ruby. An object in ICache is a global variable that goes for a trip. 

In ruby
{name=>"bart",info=>{phone=>"8675309",address=>"123 batman is awesome lane"}}

In cache
^LBSHARE(%shareid, ID, "name", "bart", "phone", "8675309","address")="123 batman is awesome lane"



The job has used so much theory that I have learned from flatiron, but not as much practice. When I first got the job, my reason I got hired was because I had researched and built an application for the interviewer using their programming lannguage. But when I got hired, i had no idea what ^LBSHARE was, or how to use that kind of global. In ruby and js, i learned that global variables were a big no-no. But in Cache, gobals are the world. This is made possible by that %shareid, and ID variables in the global. Just like accounts have a unique key, each transaction has a unique %shareid that keeps things seperate.

Now that I am feeling more comfortable with Intersystems Cache, I plan to pursue finishing Flatiron by the end of the year. I look forward to continuing to learn about javascript,, and hopefully I will build a tool that we can use for our scrum presentations at my current company. Thank you to flatiron again for helping me find a job I love in lesss than a years time. I recommend the path I have been on this past year to everyone. 

