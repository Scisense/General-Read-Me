# General-Read-Me
Discussion and Information relating to upload pratices

NOTES: Ran into a problem with verifying github on linux machines - basically if you run into an issue you have to create an SSH-key for your account for both machines. 

https://www.youtube.com/watch?v=nQDFBd5NFA8 - walkthrough

walk through. AS a note use the cat instead of 'clip' when it comes up as it's both present in git shell / terminal. However once you have created the identity your good to go. 

(Just keep in mind you require a key - pretty much - for every device you edit on). 


(General note - keep this to just pratices for github - this repo has to be public so any code/source/information will not be allowed!)

Notes:

just for the ease of use - feel free to edit this readme file for general pratice and formatting stuff as we develope the github 
pratices that we'll be using going forward. Just put a name and signature and we can comment out what we find 'poor pratices' as 
we go along.

Ben Dunn - 
What I think would be the best starting approach is that each repository is uploaded by itself and is linked via a metarepo that 
connects the dots together, basically the idea is that each individual repo can be worked on by itself then using the download
of the 'meta' repo we can get each repo into the area (libraries) ext where it's needed.

Pros: 
-Projects can call different repos so we don't need to have all of them on a local machine.
-We can edit different sections within and across branches (remember to fork if we need to do changes that will break another repo).

Cons:
-Will involve switching repos alot, and will be somewhat of a pain to keep up to date right off that bat.
