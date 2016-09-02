[rename-markdown](#)
===

### What is it?
Simple bash renamer that reverses the irksome issue of many services changing or otherwise forcing *.markdown* rather than my personal preferred *.md*. So it checks for any files with this affliction and makes a copy named *.md*. It offers basic checking of things such as whether the file already exists and if so it simlpy passes over but for debugging reasons it will output a log as it goes. This sufficed for my use case but you can change it easy enough. Also it looks for files to change only in the current directory. 


#### The logic of the repo
As for the logic I guess I'm deciding on where to draw the line between whats a script and whats a function or long alias. Basically if its about the length of this or longer and not manageable as a long one liner in my *rc* file then I'm starting to have a preferencce for loading them in usr/bin in which case versioning on git is appropriate and likely useful. It seems like a waste but not diong that and correctly on a blog is why I have to write this now, so the mistake was made and wont be again right? 

#### The logic and naming conventions, my take
Maybe a touchy issue, I'm not sure but I do know that I just read this directly is the opposite of the stance daring fireball has taken in citing another developer that makes perhaps a popular argument that our file name conventions should no longer be bound to a legacy 8.3 world. I do not have any idea what the legacy compatibility impact is, but have always found myself in a place of tending towards bleeding edge and conservately sticking to old habits wherein if its even conceivable that honoring legacy would be beneficial for my own personal needs, then I do it. 

Keeping in mind of course the innumerable times something newer is also simpler as in the case of embedded and portable devices where its not uncommon to follow strict old restricted versions that need what is basically a certain legacy set of rules to be obeyed. This is not because they are themselves that but more because whatever the renderer is on whatever *it* is is saving space and time and well sometimes it's not android 12 with a toaster on the side, sometimes its just a fucking calculator and their are rules goddamnit. 

Anything I've written assumes *.md* I don't know what and where but when I do I'm betting my 5 minutes hurried scripts won't be so progressive and forward thinking as to naturally adapt so thats reason enough for me. 

Also, because it works. Moreover it's already established so its not a luddite indicator or holding up progress or flying in the face of making every fucking thing *beautiful*, its just a filename and for me, .md works. And guess what I just lost a whole blog I made 11 pages for over the issue so yeah, I'm sticking with .md and making it easier to do if it should happen again. It's simpler to have 1 extension so I'm sticking to it.

And because quite simply I've been through a thousand repos and **README.md** is like well, every single one with maybe 4 that differed. That's majority rules, thats a default standard by popular use.

#### Running and install 
later, its just a bash file if you dont know how to run it you probably shouldn't. And if you do well read it first it has some basic sanitizing checks but is barely worthy of putting in git at all, but knock yourself out if you are learning or curious or whatever.


[@rayrc]() [@rayantony]()
