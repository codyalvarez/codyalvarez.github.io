---
layout: post
title:      "Star Wars CLI"
date:       2020-11-13 23:33:54 +0000
permalink:  star_wars_cli
---




For my first project I could not help but do the famous Swapi - star wars API. 



Getting started was a bit more difficult than first anticipated.  Putting together everything we learned the last few weeks was challenging but never-the-less, it all worked out. 



The basic setup was relatively easy, while following along the videos provided, but soon after my enviroment was set up - is when i started running into some issues.  My first big feat was learning how to move through the sub system of Linux - ensuring that I was coding on my windows side rather than ubuntu.  The learing curve of maneuvering in and out of the Linux file system was quite confusing.  A lot of trail and error until i grasped a firm foundation on where I was, and where I needed to go. 



After the essential structure was designed, it was time to start pulling data from the SWAPI site. This was one the most difficult errors i came across throughout the entire project. A 404 NOT FOUND request created a major obstacle in the first few steps of my project.  On the SWAPI site it reads - "if you ever make a request to swapi and you get back a 404 NOT FOUND response then check the Base URL first".  So, checking the base url, it was fine. No issues there.  After hours long debugging and researching google I found a solution.



I ended up creating a new folder in "lib" called "middleware"  In their I wrote up a file "raise_http_error.rb" that basically fixed any 400, 404, 500, 502, 503, 504, or 521 errors that are common with the SWAPI API. Storing the module "Middleware" inside StarwarsCLI - it fixed the issue. 



After most the hard debugging was taken care of, and built the command line interface file.  The real fun started.  That is when I was able to design my files for the data being retrieved.  Films, people, planets, species, starships, and vehicles are all included in the API.  The most interesting thing i learned was the difference between star-wars vehicles and starships.  I bet you didnt know that a starship is the only transport craft in the starwars universe that has hyper drive capability !



I have to say working on the star wars api was one of the most fun projects to start with.  Not to mention I watched the starwars prequels as background noise during the duration of my project.  It was a great time. !

[](https://usercontent1.hubstatic.com/13878754_f1024.jpghttp://)


