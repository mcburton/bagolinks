### Bag O Links

This project began as an experiment with [Penflip](http://penflip.com), an online writing tool that is backed by [Git](http://git-scm.com/). The site desires to be "GitHub for writers" and I think it has the potential to be so, but that is a different story.

The project I started was a single [markdown](http://en.wikipedia.org/wiki/Markdown) document collecting links to various resources I've been coming across the Internets. Some of the links are things I've opened up in browser tabs and haven't had a chance to read, others are good articles I've read and want to quickly find again. 

The problem with penflip is the site was designed for writing. Penflip has two kinds of projects, single document and books, my bag of links fits neither. My document is beginning to get rather long and its organization difficult. There are several sections divided by header tags, I need a method of quickly navigating to the proper section to find links and add links in the correct space. A wiki, I think, might be a better way of organizing these links (I could be wrong, but I've got an interesting idea up my sleeve). After reading [a Hackernews discussion about Git as a datastore](https://news.ycombinator.com/item?id=7015746) I was reminded about the [Gollum](https://github.com/gollum/gollum) wiki system used on GitHub. Gollum is interesting for two reasons. One, it can use markdown for its syntax and two, it is backed by git. 

Gollum has [a very lightweight directory structure and syntax](https://github.com/gollum/gollum/wiki) and as such can be easily edited using plain text editors or (and here is the interesting part) maybe even fancy git-powered markdown writing tools...like Penflip!

Ok, I had to delete the bagolinks document project and create a new book project. Now I'm going to try and push this repository up... we'll see what happens...

So I had to delete my old penflip document project, then create a new book project, and then merge the new book repository into the local repository on my laptop. It wasn't pretty, but it worked. Now I have a Gollum wiki running on my local machine living in the Penflip cloud. The next major step is to create a github project and push this repository to the github cloud and then into the project wiki. 

So now I have this project living in four different repositories:
- On my local machine
- As a Penflip book project
- As a GitHub project
- As the aformentioned Github project's wiki

The first three are immenently compatable as they are just plain old git repositories filled with markdown files. The forth, the wiki repository, is a different beast entirely. Where the Penflip and Github repositories treat the markdown files with the same semantics, the wiki has some additional "wiki syntax" that would not be rendered correctly in other places (although github now supports linking to local markdown files, I wonder if penflip does the same....)

Considering the fact I can edit markdown files directly in Github and this project is essentially a documentation project, I don't think it makes sense to manage a Gollum wiki above and beyond the markdown files. What I DO need to do however is come up with an organizational strategy for the markdown files so I can better keep track of my big bag of links.

So this has been an interesting exercise in thinking-doing. 
- I started out with a markdown document that was becoming unwieldy
- I got the Gollum wiki software installed on my local machine and brewed up a wiki in the same repository as my local branch of my bagolinks project on Penflip. 
- I deleted my document project and started a book project on Penflip. 
- I pushed the my local repository back up into the new Penflip repository
- I created a GitHub project for my bagolinks and pushed the penflip repository up there
- Push the repository up into the Github project's wiki (after some mucking around with files
- Finally I realized, maybe a wiki isn't what I want or need, but instead I just need to be a bit smart about organizing the links.

What is funny about this whole process is I've avoided the actual hard problem of breaking up the document filled with links into separate markdown files. I suppose I'll have to do it eventually, and when I do I might find the wiki actually isn't that bad. 

What is curious is how I've gone about writing this particular file. I've edited it on Penflip, on Github, and I think on my local machine as well. I actually kind of like the full-screen editing mode on Github, but I fear it is tenuous as it doesn't save your work. I really wish the online, web-based markdown editors had an option to save an index (save but not commit)...without this feature I don't think I can ever "commit" to writing in these web-based environments for any length of time.

Ok, I've written enough. This barely resembles an About page at this point, I'll probably remove all of this once I figure out more about how I want to organize this repository.
