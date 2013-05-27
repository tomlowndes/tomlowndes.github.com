---
title: 'Editing a github hosted website'
layout: post
cover: '<img class="white" src="http://www.tomlowndes.co.uk/images/blog/gitjekyll.gif" alt="Github + Jekyll" />'
---
{{ page.cover }}

Since starting to host my website on Github, the main problem has been the abillity of editing the code and testing the effects without committing it to github to be compiled into a working website.
<!--more-->

##Gitpages
GitHub Pages are hosted for free on github and easily published, by using the GitHub Mac app. I have a folder in dropbox called Github and in there is where I keep my local resporitory of my site. 

Using Sublime text I edit the posts which are seperated into my blog and my /index work posts and then had to commit there changes and go to my site to see if it works or looks good. 

##Jekyll
Gitpages is built using [jekyll](http://www.jekyllrb.com) and can be installed on mac and used to compile the gitpages code offline, but the problem is installing jekyll on a mac. As I am not the most tech savey person when it comes to using the terminal. So here is a step by step of what i did.

#Pre-Requisite: XCode

The easiest way to get a hold of XCode is to [download it here](https://developer.apple.com/xcode/).

• Install Homebrew, a package manager. 
	
	/ruby -e "$(curl -fsSkL raw.github.com/mxcl/homebrew/go)" 

It lets you install stuff easily.

•Install RVM: Ruby Version Manager. This lets you switch versions of Ruby without affecting the system version. 

	/curl -L https://get.rvm.io | bash -s stable --ruby.