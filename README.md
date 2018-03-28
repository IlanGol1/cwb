# cwb
controllable web browser

#initial edit

isn't it annoying you have to send http request onwards and backwards from your console, when you're looking for something specific?
for example - if you want to investigate the javascript of the application, or perhaps add your own 'additions' to it?
you don't want to be restricted by javascript, and you want control over what's coming and going.
editing the contents of the html page should be easy! why isn't it? well, this is what it's all about.

cwb attempts to create a modern web brower as an application you can control and fully edit.
you can send and recieve stuff when you feel like it. you can prevent from javascript doing things you don't want it to, and prevent you (even slightly from) from quickly getting into the insides of the application.
besides that, we all need a platform for integrating easy front end development - that looks real.
having code on one side, and the page on the other, being able to superwise the web contents, and add automations by
external applications. you should be able, for example, send millions of request through a website with an external application and save the information, or implement a machine learning program over the internet and actually save what you discovered easily.
one development shouldn't be far from the other.

is shouldn't be difficult to go to google , and then finding a random website to implement software.

so:
I'll be using python , and will create a simple library for irritating the DOM.
sadly, I suck. there are a lot of things to do here, this can be one of the more useful things, but it has a few challenges to it :

1) creating a modern browser - should be damn difficult.
2) creating the editing environment - should be damn difficult as well.
3) adding the options for controlling the page (for example - don't start javascript till I tell you to, or view all external page contents).
4) python DOM irritation and http requests control.
5) visualization of the information coming and going - this is the cherry on top.

while writing this, I barely know how to use github.
I've never created a desktop application before, and rarely used python for sending and receiving http requests.
but damn it, it sounds so simple to get control over web browsers. why isn't it easy?????!!!!!
that's something that needs changing.

I'll actually begin with a short python library for sending and viewing http requests easily, and irritating throughout DOM.
this will be the basics branch.

afterwards - I want to start the application itself (GUI!!!!! YAY!). but sadly, I still suck.
this well be the GUI branch.

after the application will have a basic look, the time will be for viewing the contents nicely (more GUI!).
so - basics of viewing html, basic css and exetra.
It will be up to other people to finish this branch, I hope it will not take too long, and it will
at least look close to a web browser.
this should be the browserBasics branch. it's a branch over the GUI branch.

after css and html - it will be time for creating the editing platform.
this will be a branch over the browserBasics branch, I'll call it editing.

and integrating the editing platform we will finally reach javascript!
YAY! 
so, a basic javascript interperter will be added to the python interperter,
and it will not start till you tell it to, besides sending console messages when something important happens.
let's begin , shall we?

#second edit
I can't believe it had taken me 8 months to go back to this project. well, I had it rough though. almost 4 months without a computer
when I was constantly working on a low end job. however, I still like the idea of this project. and I still have much to learn,
but it feels as if I didn't actually learn anything from my time even when I had a computer. I guess that whenever I would learn something I could apply to one of my projects, I could come back to it and apply it until it's finished. for now, this is no time for writing my own code. it's more appropriate for me to read about various subjects related to computer programming as well as contributing whenever I can to open source projects, such as python even. I did learn, however, that it is more comfortable to use JAVA for gui. I'll see how I am going to implement that. I also learned that you can use selenium in python for doing many of the things I planned on doing here. which is the main reason why I had abandoned this project. since I felt it is useless. though I could see various applications for it. a form of an open source window builder for websites that actually works, that could also be used for creating bots and crawlers. as well as viewing the inner-workings of sites such as youtube (which was part of my initial motivation for building this project).
