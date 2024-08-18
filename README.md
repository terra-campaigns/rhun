---
layout: default
title: Home
nav_order: 1
permalink: /

---

# Shadow of Rhûn

Context material for the RPG campaign Shadows of Rhûn 

# Contribute

Clone this repo, or edit a branch directly from GitHub's web app.
Look at the list of issues, and choose one to begin with.

Do not make changes on `main`.
Feature branches should be used and merged to `main` through Pull Requests (PR).
PR needs to be approved by another contributor.

The project uses markdown files.
When writing, use a new line for each sentence, and two RETURNS for new paragraphs.
This is better for versioning.

## Toolset

- Obsidian is a good (and free) markdown editor.
- If you don't have something like Obsidian Sync, edits on the fly can also be done using GitHub's web app.
- When adding images, do not add them directly to the repository, to keep it light. Use Imgur and html links instead. Obsidian has a [plugin](https://github.com/gavvvr/obsidian-imgur-plugin) that does that for you.

## Localhosting the website

If you'd like to build the website locally on your machine, before making pull requests to `main`, follow as below:

- install [jekyll on mac](https://jekyllrb.com/docs/installation/macos/)
- the next commands should be run on the repo folder:
	- point the repo folder to the new version of ruby: `echo '3.1.3' >> .ruby-version`
	- install gems: `gem install bundler jekyll`
	- for some reason I also have to do this: `bundle install`
	- you might need to also run: `bundle add webrick`
	- serve the site on localhost: `bundle exec jekyll serve`
- browse http://localhost:4000
- you can make changes on files and the localhost is reflected quickly without any new commands

### Tips & tricks

If you need to add text that does not get rendered into html, make a new paragraph with:

[This is a comment that will be hidden.]: # 

## Worldbuilding

Worldbuilding processes are defined in the run file.


