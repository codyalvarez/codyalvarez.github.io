---
layout: post
title:      "the_collective. - & How to start sinatra project"
date:       2020-11-13 23:25:31 +0000
permalink:  the_collective_-_and_how_to_start_sinatra_project
---


*Building a simple Sinatra based web application using corneal*





Learning Sinatra was a bit of learning curve but once you get the general structure and what Sinatra actual takes care of for you, you realize how helpful it really is.  With the help of corneal (which i highly advice future students to take advantage of) my project soon took flight. 



The idea behind my application "the_collective" was that I wanted to build a super simple meeting place for people to collaborate on ideas either with others, or on their own.  I guess if I had to explain it under a few sentences to someone say, while waiting inline for a cup of coffee I would explain it like this;



> The collective is a server-based, web application that allows users to create, edit, and share/save their work - all in real-time. Picture a virtual blackboard - that users can sign up, post an idea, an ongoing error or bug, a solution to a problem - anything you can think of - that gets posted under "Current Objectives" and other users can view, edit or add to those objectives. Thus cutting down the time it takes to find solutions to problems and speeding up the "creative process".  

> 

> All in all, the_collective is an online neural network with users being the connections. 

![](https://iireporter.com/wp-content/uploads/2017/02/DataArt-Cliff-Moyce-ML-blockchain-540x349.jpg)




Although the application is still very developmental, the general structure and idea is something I plan to improve upon in the near future. 



Moving forward - I think that the one of the most difficult parts of starting any project is actually getting it started.  Everything from installing the right gems, to making sure your creating the folders in the right place to firing up the code and making sure it runs smooth in vscode, or atom etc. all takes a little getting used to. So, im going to take the hard parts out so that you can focus on building your app. 



First up - assume you already have your local enviroment set up - if you don't, go ahead and get that set up first then come back. 



Alrighty,



So, you open ubuntu - make sure you're at the ```home dir``` so it should look like this



```[14:17:28]  ~```



If you're not, simply type ```cd  ~``` 



Once there, type ```ls``` for list view and it should list any folder below - most of you will have few - im guessing if a cohort lead, or fellow student helped you in the past you will have something like 

```flatiron   projects  somethingelse``` 



If it is empty, no biggie let's go ahead and create a folder named ```projects``` or ```project_folder``` I don't know, be creative.  So to make a folder make sure you're in the home directory and type ```mkdir "filename"```. For example if i wanted to create a project names ```my_awesome_projects``` I would type ```mkdir my_awesome_projects```



Alrighty, awesome so we went ahead and created our project in the right directory, Now for phase 2. 

If your planning on building your project from scratch, good for you, you can skip these couple of steps BUT i highly suggest you use the ```corneal gem```. Saves you a lot of time. So that is what i will be walking your through. 



While in your projects folder - not sure if this part matters but it worked for me so, 

go ahead and install corneal via ```gem install corneal``` 



There you go, that's it. 

Now think of a killer name for your project. 

Once you got it. 

Type ```corneal new App-NAME```

and BOOM there you go, should take a few seconds but once its set up, you should now see the name of your project, and be in that directory.



Go ahead and type ```code .``` and it will open your project via the corneal gem and as long as you have vscode set up, you should be good to go.  Assuming this all went smoothly you should now be inside vscode with the appropriate file structure that corneal supplies for you.  Go ahead and run ```bundle install``` and your good to go. 



That it for setting up your Sinatra project - the rest is up to you ! 



For additional readings on connecting to github feel free to reach out to me via slack. 

Happy coding !

