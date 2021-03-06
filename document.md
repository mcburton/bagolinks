
# My bag of links

because I don't really like bookmarks or, I've recently decided, I don't like bookmarking services linke pinboard, I'm going to use this to save links. Why this, I like the unstructuredness of a document.

## IPython Notebooks 
[HN thread on first chapter of Mining the Social Web as IPython Notebook](https://news.ycombinator.com/item?id=6611848)  
some links Mathias put in the thread comments  
- [how to use nbconvert](http://nbviewer.ipython.org/urls/raw.github.com/Carreau/posts/master/06-NBconvert-Doc-Draft.ipynb)  
- [Github Issues thread about adding JATS support to nbconvert](https://github.com/ipython/ipython/issues/4119)  
- [IPython Notebooks & Github repository for Mathias's book *IPython In Depth*](https://github.com/ipython/ipython-in-depth) 

[Better typography for IPython Notebooks](http://slendrmeans.wordpress.com/2012/12/05/better-typography-for-ipython-notebooks/). One thing I have wanted to try is re-style an IPython notebook to look more like [Frank Chimero's essas, what screens want](http://frankchimero.com/what-screens-want/)

## autosaving changes from Chrome Developer Console
I was dorking around with derrida.js in the chome developer console when I was building [pomo.io](http://pomo.io) and I notice Chrome has a menu item to "save" changes to javascript (and HTML/CSS I presume). While it (obviously) doesn't appear you can save back to remote locations (without some server shit in place), you can save local files. I'll have to play with this more. [this blog post "Auto-saving CSS And JavaScript Changes Locally From The Chrome Developer Tools" has a video and more information.](http://addyosmani.com/blog/autosave-changes-chrome-dev-tools/)


## post-modern programming
when dreaming up [pomo.io](http://pomo.io) i was googling around for information about the post-modern web and post-modern programming. i found [this link with some thoughts/notes on what post modern programming should be.](http://martinfowler.com/bliki/PostModernProgramming.html)

Blog post by Ian Bicking - [*TogetherJS as a Postmodern Programming Tool*](http://www.ianbicking.org/blog/2013/10/togetherjs-a-postmodern-tool.html) He references the Martinfowler post I linked to above. THis is essentially a marketing post for the mozilla js library [Togetherjs](https://togetherjs.com/). Also some [interesting conversation about post-modern programming on hackernews.](https://news.ycombinator.com/item?id=6647168)

Post-Modering programming seems to be popping up everywhere. Here is a blog post by John Foreman of Mailchimp who just wrote a data science book, [*data science and the technological realization of postmodern thinking*](http://www.john-foreman.com/1/post/2013/10/data-science-and-the-techonological-realization-of-postmodern-thinking.html), I haven't read this yet, but I'm dubious...we'll see.

see also [this thread](https://groups.google.com/forum/#!topic/philosophy-in-a-time-of-software/uM526Nrtckc) from the [philosophy in a time of software list](https://groups.google.com/forum/#!forum/philosophy-in-a-time-of-software)

## Scholarly Markdown
[Citations in Scholarly Markdown blog post with a **lot** of good discussion in the comments.](http://blog.martinfenner.org/2013/06/19/citations-in-scholarly-markdown/) That link has the best discussion about citations in markdown I've seen so far. Here is [another post from that same blog "What is Scholarly Markdown"](http://blog.martinfenner.org/2013/06/17/what-is-scholarly-markdown/) Also a [PLOSOne post about scholarly markdown, which I've just found but haven't read.](http://blogs.plos.org/mfenner/2012/12/13/a-call-for-scholarly-markdown/). 

[Github repository for the Scholarly Markdown project](https://github.com/scholmd/scholmd/wiki). I'm not sure where this is going and it doesn't look like it has been updated in a while.

[RTF/ODF-Scan for Zotero is a lightweight markup format for expressing zotero citations in ascii text. The scanner picks them up from teh document and replaces them with citations.](http://zotero-odf-scan.github.io/zotero-odf-scan/) I think Frank Bennet pointed this to me on twitter I was thinking about implementing this with my [Editorial](http://omz-software.com/editorial/) zotero workflow/plugin.

I found this more general link about writing in markdown on the penflip help page, [*Markdown is the future of writing*](http://nerdplusart.com/markdown-is-the-future/). One thing to consider is the point [ptwobrussel made in the IPython Notebook publishing discussion on hackernews that made me think about why asciidoc may be a better choice than markdown for serious publishing endevors](https://news.ycombinator.com/item?id=6612288)

Came across this link on the twitters, a blog post by [@mfenner](https://twitter.com/mfenner) about converting [Markdown to JATS XML](http://blog.martinfenner.org/2013/12/12/from-markdown-to-jats-xml-in-one-step/). I'm interested because I wonder if this the pandoc-jats tool could be used to convert IPython Notebooks into JATS XML for publishing.

Another post, but @mfenner, called ["The Grammar of SCholarly Communication"](http://blog.martinfenner.org/2013/11/17/the-grammar-of-scholarly-communication/) that I should read.

Link to a workshop by Andrew Goldstone [about digital writing with HTML, markdown & latex](http://andrewgoldstone.com/blog/2013/11/23/emp2/). If I want to do a workshop on this I should check this out.

## A pile of machine learning links
[word2vec does soemthing to compute the distance between words in a corpus of text](https://code.google.com/p/word2vec/) it is being used by [ThisPlusThat.me](http://thisplusthat.me/) to do some cute Thing - trait + trait comparisons. [A nice writeup on ThisPlusThat.me by the creator.](http://insightdatascience.com/blog/thisplusthat_a_search_engine_that_lets_you_add_words_as_vectors.html) THere is also the [github repository](https://github.com/cemoody/wizlang) but I don't, at first glance, understand its structure.

- [Machine Learning in Python TF-IDF Text Extraction Vector space models - Part 1](http://pyevolve.sourceforge.net/wordpress/?p=1589)
- [Machine Learning in Python TF-IDF Text Extraction Vector space models - Part 2](http://pyevolve.sourceforge.net/wordpress/?p=1747)
- [Machine Learning in Python TF-IDF Text Extraction Vector space models - Part 3: Cosine similarity for Vector Space models](http://pyevolve.sourceforge.net/wordpress/?p=2497)

[A programmer's guide to machine learning](http://guidetodatamining.com/)

[Introduction to Pandas data structures](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/) a three part series that has been making the rounds on twitter, reddit, and HN that walks through Pandas. THe author also wrote a post on [pandas for SQL users](http://www.gregreda.com/2013/01/23/translating-sql-to-pandas-part1/)

Blog post on [textBlob](https://github.com/sloria/textblob) a text processing library in python. [This post focuses in on sentiment analysis.](https://www.openshift.com/blogs/day-9-textblob-finding-sentiments-in-text)

[Blog post Gensim author of Jensen reflecting on the Python machine learning library.](http://radimrehurek.com/2013/10/five-years-of-gensim/)

Nice introduction to [Principle Component Analysis with pretty pictures](http://georgemdallas.wordpress.com/2013/10/30/principal-component-analysis-4-dummies-eigenvectors-eigenvalues-and-dimension-reduction/). Looks like there are other nice posts on that blog about [data mining and machine learning](http://georgemdallas.wordpress.com/2013/06/11/big-data-data-mining-and-machine-learning-under-the-hood/)

Deep learning with python with [pylearn2](http://deeplearning.net/software/pylearn2/). Still under heavy development.

## Pythony STuff
[So You'd Like To Make a Map Using Python](http://sensitivecities.com/so-youd-like-to-make-a-map-using-python-EN.html). SOme interesitng bits on making a Choropleth and other links to python mapping libraries. interesting alternative to using [d3js.org](http://d3js.org/).

I haven't looked at these, but looks like [a nice collection of videos](http://blog.hartleybrody.com/google-python/) about how to properly python by a guy from Google.

[Dataset](https://dataset.readthedocs.org/en/latest/) looks like a friendly wrapper around [SQL Alchemy]](http://www.sqlalchemy.org/). Reminds me of [Requests](http://docs.python-requests.org/en/latest/) in that it has a friendly API. 

I am seeing a lot of python libraries using [Read the Docs](https://readthedocs.org/) as their main webpage. Cool.

Found a nice post on Medium about quick and easy [parrallelism in python with the multiprocessing library](https://medium.com/p/40e9b2b36148), then there was a great [discussion on the /r/python subreddit about using the concurrent.futures library instead](http://www.reddit.com/r/Python/comments/1tyzw3/parallelism_in_one_line/). parallel processing in python doesn't appear to be as hard as I thought. 

[Elephant](hhttps://github.com/kennethreitz/elephant/tree/master) is a S3 backed key-value store with ElasticSearch indexing. Built by the guy who did the [Requests library](http://docs.python-requests.org/en/latest/), [Kenneth Reitz](https://github.com/kennethreitz). Unfortunatley, it appears abandoned, but the idea is insteresting.



## DH Blog Topic Model Topography project
[**Kriging** is a method to build an approximation of a function from a set of evaluations of the function at a finite set of points.](http://en.wikipedia.org/wiki/Kriging) I think I can use this technique to build a continuous topography of from the Digital Humanities blogs topic points.

[dfr-browser is a tool for visualizing and interacting with MALLET topic models](http://agoldst.github.io/dfr-browser/) built by [Andrew Goldstone](http://andrewgoldstone.com/) who collaborated with [Ted Underwood](http://tedunderwood.com) on the PMLA topic modeling thing.


## Topic Modeling

[BEAGLE model source code](http://www.indiana.edu/~clcl/BEAGLE/) is the source code link to a text model, not sure if it technically a topic model, from Indiana. I haven't looked into this much yet.

I need to look at the [CV of Ying Ding at Indiana](http://info.slis.indiana.edu/~dingying/publication.html). She has done a bunch of work using topic models and scholary communication (in science).

I dumped [a bunch of links into a subreddit on topic modeling](http://www.reddit.com/r/topicmodeling/) should extract those to here.

Adding a link to [my blog post on topic modeling, *The Joy of Topic Modeling*](http://mcburton.net/blog/joy-of-tm/) 

[Alan Liu just tweeted](https://twitter.com/alanyliu/status/394514893371498496) a link about [Sub-corpus topic modeling](http://www.sciencedirect.com/science/article/pii/S0304422X13000648)

A woman from my topic modeling workshop, [Emily Marshall](http://www.psc.isr.umich.edu/people/profile/1071/Emily_Ann_Marshall) mentioned there is a special issues of [Poetics](http://www.journals.elsevier.com/poetics/)(boo Evilsevier) on topic modeling. I found [some abstracts in a pdf online but I'm not sure when it will be released.](http://www.soc.ucsb.edu/ct/pages/JWM/Papers/Y2013_Topic_Models/TOC%20Poetics%20Special%20Issue%202013%20December.pdf) 

[Alan Liu's eng236 class discussion on topic modeling](http://eng236introdh2013fstudentwork.pbworks.com/w/page/70465717/Questions%20about%20topic%20modeling)

## Scholarly communication

Check out [Carol Palmer's CV](http://people.lis.illinois.edu/~clpalmer/pubspresB.html) She has done some interesting work on scientific scholarly communication.

I need to look at the [CV of Ying Ding at Indiana](http://info.slis.indiana.edu/~dingying/publication.html). She has done a bunch of work using topic models and scholary communication (in science).

[A very long post discussing the affordances of twitter as a medium for communication](http://www.danielallington.net/2013/08/twitter-conversations-reply-retweet/#sthash.rl8sQ4qa.dpbs), I think this is applicable to conversations around scholarly communication.

Blog post by Alex Fink I found on HASTAC, but was cross posted on his personal blog, titled [Github for academics, next steps](http://kris.shaffermusic.com/2013/09/publishing-with-github-pages/) also inluded some additional interesting links to other posts on Github for academics inluding [this promising one by Kris Shaffer about publishing with Github](http://kris.shaffermusic.com/2013/09/publishing-with-github-pages/) 

Open Source Scholarship, a term I have been seeing around and found most recently in [this chapter in Hybrid Pedagogy](http://www.hybridpedagogy.com/Journal/files/Open_Source_Scholarship.html) and I think this connects with my idea of web-centric scholarship, but OSScholarship focuses on the technical apparatus of copyright, whereas WCScholarship focuses on the technical apparatus of the web. Obviously they are deeply intertwined.

[Alan Liu pointed me](https://twitter.com/alanyliu/status/419299302763032577) to [Voice of the Shulltle](http://vos.ucsb.edu/) an amazing project and a beautiful example of "web-centric scholarship/scholarly communication." I need to develop this concept more, I think this project could help as an illustrative example It is a **massive** collection of links & digital collection he and others have been compiling for 20 years.

## Design

[Butterick's Practical Typography is a "web book" and crash course on typography for the web or in general.](http://practicaltypography.com/)

[Shape of Design Book is a nice little book on design. I bought the book, but should probably have a link to it here.](http://www.shapeofdesignbook.com/)

Another thing by [Frank Chimero](http://frankchimero.com) that I want to read ["What Screens Want"](http://frankchimero.com/what-screens-want/). I like the design of this essay and want to copy it...I also wonder what an IPython Notebook would look like in this design...

## Web writing
a pile of links loosely related to digital writing, the web, and whatever else I feel belongs in here.

[Open call for peer review of the Web writing book](http://chronicle.com/blogs/profhacker/call-for-open-peer-review-web-writing/52393)

[Writing on the web with Ginko, a horizontal writing and outlining tool](http://chronicle.com/blogs/profhacker/write-in-a-new-way-with-gingko/52975)

[HTML5 is the future of book authorship](http://programming.oreilly.com/2013/09/html5-is-the-future-of-book-authorship.html) This is a really interesting post and it links to a paper from the [Basliage markup conference that makes the argument for HTML5 books.](http://balisage.net/Proceedings/vol10/html/Kleinfeld01/BalisageVol10-Kleinfeld01.html) I need to read this, I think it is really interesting.

[Digital Dissertation deliverables and how to complete them! is a post by Amanda Visconti](http://www.literaturegeek.com/timeandscope/) 

### Web Writing Tools I (may or may not) have tried
- [Penflip a web-based, git backed writing tool/site. HOsted in the cloud with git as API protocol.](http://www.penflip.com)
- [Draft like penflip but more features, not backed by git. HOsted in the cloud as service.](https://draftin.com/)
- [Prose.io is a writers frontend to github. Hosted front-end, backed in github.](http://prose.io/)
- [Ghost is a neo-wordpress blogging platform. Self-hosted or will be cloud service.](http://tryghost)
- [Substance.io a semantically rich writing tool, being kinda-developed. Hosted in the cloud.](http://substance.io/#substance) The developers have some [interesting things in github.](https://github.com/substance)
- [Editorially a tool for collaborative writing. Looks to be hosted in the cloud.](https://editorially.com/) Also have a journal, [STET](http://stet.editorially.com/about/) which provides high quality content. This remind me of [Medium](http://medium.com) in that they do medium AND message.
- [Markdown editor for scientific writing. -- Not sure if this is still being actively developed. Hosted locally or in cloud.](https://github.com/yoavram/markx)
- [Authorea, specifically focused on collaborative scientific writing](https://www.authorea.com/) I think it was Cory Knobel who first pointed me to it. 
- [Medium is one of these, but not like the others. I'm not sure why it is different, it is a tool, but also a lot of content.](http://medium.com)
- [Quip is a cross-channel (desktop, tablet, phone) writing app. I didn't like it very much.](https://quip.com/)
- My favorite writing app at the moment is [Editorial for the iPad](http://omz-software.com/editorial/). It is a writing platform backed with python. I love the idea. I need to figure out how to integrate it with other writing platforms. I like using git as the underlying sharing protocol.


## GIT
a pile of links related to GIT 

[Git concepts simplified.](http://gitolite.com/gcs/index.html) This post is similar to the class post I really liked, [git for computer scientists](http://eagain.net/articles/git-for-computer-scientists/), but it is intended for a broader audience.

A slightly old, but still nice set of slides on [using Git as a NoSQL data store](https://speakerdeck.com/bkeepers/git-the-nosql-database), also the [HN discussion includes some good links](https://news.ycombinator.com/item?id=7015746) like [this blog post on gitshelve.py](http://newartisans.com/2008/05/using-git-as-a-versioned-data-store-in-python) which is part of the [git-issues project](https://github.com/jwiegley/git-issues/)

Some Python Git integration projects:
- [Gittle: Pythonic Git for Humans](https://github.com/FriendCode/gittle)
- [Dulwich, a pure-python git](http://www.samba.org/~jelmer/dulwich/)
- [GitPython, a port of Grit-the ruby python library](https://gitorious.org/git-python)
- [pygit2, python bindings for libgit2](https://github.com/libgit2/pygit2)

There is also the Github maintained wiki, [Gollum](https://github.com/gollum/gollum) which I might actually migrate this bagolinks page to since I'm outgrowing this page.

## #Indieweb
I am facinated by the Indieweb stuff and need to start following it more seriously.

[I think this is the article that introduced me to the IndieWeb](http://www.wired.co.uk/news/archive/2013-08/15/indie-web)...no that is wrong, [this-"the #indieweb as a minimum viable web ecosystem" was the article that introduced #indieweb to me](http://werd.io/entry/51dca7e2bed7de945debf707/the-indieweb-as-a-minimum-viable-social-web-ecosystem)

[Indiewebcamp wiki seems to be the central place where it all happens. ](http://indiewebcamp.com/)
[What's open web and why is it important](http://codinginparadise.org/weblog/2008/04/whats-open-web-and-why-is-it-important.html) I found this on [Max Ogden's homepage](http://maxogden.com/)

## Blog Theory

Post on Nieman Lab by Jason Kottke called [the blog is dead](http://www.niemanlab.org/2013/12/the-blog-is-dead/) links to another appropriate post by Alexis Madgrigal about information streams [2013: The year the stream crested](http://www.theatlantic.com/technology/archive/2013/12/2013-the-year-the-stream-crested/282202/)

## learning & teaching 

The [software carpentry](http://software-carpentry.org/) project is pretty awesome. It doesn't appear to have much attention at the moment, but I think the model could be really interesting.


## web archiving

Found this project [browser mirror](https://github.com/mozilla/browsermirror) which serializes the active DOM and sends it to a server so you can sync what you see with someone else. I wonder if it might be possible to save this serialized representation of the dom.
> Traditional screensharing happens at the pixel level, but I’m going to refer to something I’ll call DOM Screensharing. In this model the current/live state of the DOM is transferred from one browser to another. I’ll call the browser that starts the screensharing is the “source” and the browser that receives the DOM is the “viewer”....In this approach you look at all the elements on the source browser, scrub out any scripts or event handlers, maybe scrub hidden elements (or don’t). Then you serialize this and send it to the viewer. The page is then recreated at a new URL, visually hard to distinguish from the original page, but it’s “dead”. 
- from [togetherjs as postmodern programming tool](http://www.ianbicking.org/blog/2013/10/togetherjs-a-postmodern-tool.html)

Article by [Jacob Harris about digital preservation.](http://source.opennews.org/en-US/learning/and-remember-ones-posterity/). Specifically he is addressing some of the technical challenges Archiving web applications. a couple interesting links in here I should follow. Also has a funny quip about the difficulty parsing digital archivist's jargon. [Matt Waite wrote an article, linked from Jacob's](http://source.opennews.org/en-US/learning/kill-all-your-darlings/) about letting applications die.

### Code archiving

Project called ["active papers"](https://bitbucket.org/khinsen/active_papers_py/wiki/Home) which reminds me of the IPython notebook but more focused on a rich scholarly product that inludes the data, workflow, and code to promote reproducable research. 

## Snowfalls

[A list apart article on "snowfalls"](http://alistapart.com/column/he-aint-snowfalling-hes-my-brother) which includes a few links I need to trace. 

[Google doc filled with "snowfallen" articles](https://docs.google.com/spreadsheet/lv?key=0AnWYxsUNHS4FdGVYMnpkdGdTNTU0RS1SXzktcnZwRWc&usp=sharing) by @bobbiejohnson based on a [post he wrote on Medium.](https://medium.com/inside-matter/66b9060333ad) 

## DevOps
I had a pile of links about various devops stuff that I haven't read through so I'm dumping them here.

A few links from the [devo.ps](http://devo.ps) blog. ["Ansible Simply Kicks Ass"](http://devo.ps/blog/2013/07/03/ansible-simply-kicks-ass.html) and ["Vagrant, Docker and Ansible. WTF?"](http://devo.ps/blog/2013/09/25/vagrant-docker-and-ansible-wtf.html). 

Here are a couple about just using [Vagrant](http://www.vagrantup.com/) for managing distributed systems. ["Distributed Architecture Faking with Vagrant"](http://philsturgeon.co.uk/blog/2012/12/distributed-architecture-faking-with-vagrant) and here is a github repo for [vagrant-aws: use Vagrant to manage your EC2 and VPC instances](https://github.com/mitchellh/vagrant-aws) 

Two last final links from some random blogs ["Docker vs Chef and Vagrant"](https://phunehehe.net/docker-vs-chef-vagrant/) and ["Scalable and Understandable Provisioning with Ansible and Vagrant"](http://julien.ponge.org/blog/scalable-and-understandable-provisioning-with-ansible-and-vagrant/)

## Research

A [blog post](https://likeinamirror.wordpress.com/2013/12/01/satoshi-nakamoto-is-probably-nick-szabo/) and [hacker news discussion](https://news.ycombinator.com/item?id=6828169) that uses text analysis to try and determine who is Satoshi Nakamoto. What I think is interesting is the rhetorical game being played. The author uses data and statistical analysis to make a claim about Satoshi's identity. The subsequent hacker news discussion unpacks the claim and evidence provided. 

[List of digital humanities and new media friendly journals](https://github.com/denten/dhnotes/wiki/journals). Compiled by Dennis on github.
