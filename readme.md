# Blockstreet Education
This repository contains the educations content of the blockstreet.io website.

## How To Contribute
The format we use for files is just like any other format on your computer and it's called `.md` which stands for "markdown". Markdown is a syntax that lets you write documentation with styling. If you've ever posted on a forum back in the day, they might have used BBCode, which let you bold text like [b][/b] and whatnot. Markdown is a little simpler.
 
It doesn't allow you to visually see your styling in real time, but lets you work with the source so you know exactly what is going on (if you know markdown). Here on github you can previous your changes so it's easy.

This will help: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

As for workflow / organization, on github, we have a repository called "blockstreet" (nkmlombardi/blockstreet). It contains files (mostly in markdown format) and represents the content of the site. What we can do is have multiple versions of the files, called "branches". Imagine a tree, where a branch is split off from a previous one. Changes made to either branch are independent of one another, but they started with the same base.

The `master` branch is what is seen live on the site. The code I wrote is pulling from the repository and displaying it on the page. The `staging` branch is for changes that are waiting to go live. Usually we want to release new education / site features in set releases, not trickle them in that way we can announce it.

If you are creating a new file, you can just click "create file" in the staging branch, and put your formatted content there. If you are editing a file, you can edit the file on the staging branch, but when you go to save it, make it create a new branch and pull request.

Pull requests are requests to merge your changes into another branch. You'd name it `justin-pr-1` or something, and someone would review your changes before they are committed to staging.
