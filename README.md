This is an under-construction set of files to support teaching some basic coding and data analysis to law students.  

Right now, hack-law.ipynb is an ipython notebook that includes a very basic lesson in how to sort your way around python, aimed at law students who have never written code before.  It seemed to work in the classroom.  Hack-law working is just the same notebook, but with some extra stuff I threw in mid-lecture, some of the exercises carried out, etc.  (students should not use or look at it) supcourt.json contains U.S. Supreme Court cases (plus a lot of noise) from 2011-present.

crunch-law is part 2, the data analysis part.  Right at the moment, it's a work in progress.  I'll update this when it's finished.  enronjson.json is a small subset of that old enron email dataset that everyone uses for text-mining exercises.  I stole it from some folks at Berkeley (http://bailando.sims.berkeley.edu/enron_email.html) and then cleaned it up a little, turning it from a gzipped collection of text files plus label files to a single json with just one binary label for the most interesting category.

Anyone else who wants to use this stuff for similar purposes, please feel free to do so.  It's available under the Creative Commons CC BY-NC-SA license (and I consider "noncommercial" use to include any teaching of university students at any level).  Copyright 2015, Paul Gowder, http://paul-gowder.com.  I would appreciate if you let me know if this is useful to you.

That copyright claim only applies to the code and text in the ipython notebooks. Not data file(s).  

With respect to data files:

The first associated data file is just a bunch of Supreme Court opinions.  It is derived from data made available by the Free Law Project at http://www.courtlistener.com/, so I claim no rights whatsoever to that file; neither do the folks at the Free Law Project, who have committed their database to the public domain (and anyway, it's a standard format mostly comprised of government documents; copyright claims in it would be pretty dubious in general).  

The second, the Enron one, didn't have any copyright label attached to it.  But I don't think there's likely to be a meaningful copyright claim, for reasons relating to fair use on the originals, and Feist v. Rural on the selection & labels added by the Berkeley people---obviously, however, this is just a statement of my own position should someone complain about my use and distribution of it, and not legal advice to you.  I highly doubt anyone will complain at any rate, since traditionally researchers who put their raw data on the web mean for it to be used.  But you use it at your own risk.
