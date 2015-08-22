<section id="themes">
	<h2>Themes</h2>
		<p>
			Set your presentation theme: <br>
			<!-- Hacks to swap themes after the page has loaded. Not flexible and only intended for the reveal.js demo deck. -->
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/black.css'); return false;">Black (default)</a> -
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/white.css'); return false;">White</a> -
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/league.css'); return false;">League</a> -
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/sky.css'); return false;">Sky</a> -
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/beige.css'); return false;">Beige</a> -
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/simple.css'); return false;">Simple</a> <br>
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/serif.css'); return false;">Serif</a> -
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/night.css'); return false;">Night</a> -
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/moon.css'); return false;">Moon</a> -
			<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/solarized.css'); return false;">Solarized</a>
		</p>
</section>

H:

# Introduction to git

by some [National University of Colombia collaborators](https://github.com/orgs/objetos/people)

H:

# Index

 1. Introduction <!-- .element: class="fragment" data-fragment-index="1"-->
 2. Getting started <!-- .element: class="fragment" data-fragment-index="2"-->
 3. Git basics <!-- .element: class="fragment" data-fragment-index="3"-->
 3. Git branching <!-- .element: class="fragment" data-fragment-index="4"-->
 5. References <!-- .element: class="fragment" data-fragment-index="5"-->
 6. Workshop <!-- .element: class="fragment" data-fragment-index="6"-->
 
H:

## Introduction

### What is git

> Git is a [free and open source](https://git-scm.com/about/free-and-open-source) [distributed](https://en.wikipedia.org/wiki/Distributed_revision_control) [version control system](https://en.wikipedia.org/wiki/Revision_control) designed to handle everything from small to very large projects with speed and efficiency.

V:

## Introduction
### Why use git?

1. Personal affairs
2. Work into a project you like with all sorts of people from everywhere

V:

## Introduction
### Why use git? Personal affairs

<li class="fragment">Whenever you wanna keep track of a personal project sources.
Be it a novel, a program, an image, a video, etc.

<li class="fragment">Whenever you wanna be creative a experiment some crazy idea
without fearing to lose your previous work

V:

## Introduction
### Why use git? Team affairs

<figure>
    <img height='400' src='fig/svn_workflow.png' />
    <figcaption><a href="https://git-scm.com/about/distributed">Subversion-Style Workflow</a></figcaption>
</figure>

V:

## Introduction
### Why use git? Team affairs

<figure>
    <img height='400' src='fig/manager_workflow.png' />
    <figcaption><a href="https://git-scm.com/about/distributed">Integration Manager Workflow</a></figcaption>
</figure>

V:

## Introduction
### Why use git?: Team affairs

<figure>
    <img height='400' src='fig/dictator_workflow.png' />
    <figcaption><a href="https://git-scm.com/about/distributed">Dictator and Lieutenants Workflow</a></figcaption>
</figure>

H:

## Getting started

H:

## Git basics

H:

## Git branching


H:

## References

* [Git site](http://git-scm.com/)
* [Pro Git book](Scott Chacon and Ben Straub and published by Apress) by Scott Chacon and Ben Straub and published by Apress, where most of the material found on this presentation has been hacked (when not noticed otherwise)
* [Git reference](http://gitref.org/) quick most-used command reference
* [Git tips & tricks](http://gitready.com/)
* [Try Git online](https://try.github.io/levels/1/challenges/1)
* [Further Git references](https://help.github.com/articles/good-resources-for-learning-git-and-github/)

H:

### Workshop

* (level 1) <!-- .element: class="fragment" data-fragment-index="1"-->
 1. Create a local Git repo to track some source files
 1. Create the program of your choice
 2. Begin to track your program source files with Git
 1. Commit some changes
 1. Use ```git tool``` and/or ```git difftool``` to study some changes
* (level 2) <!-- .element: class="fragment" data-fragment-index="2"-->
 2. Create a branch to test an experimental feature
 3. Merge your ```test branch``` into your ```master branch```
* (level 3) <!-- .element: class="fragment" data-fragment-index="3"-->
 1. Share your repo online using [Git on the server](https://git-scm.com/book/en/v2/Git-on-the-Server-The-Protocols)
 Tip: you may use a [third party hosted option](https://git.wiki.kernel.org/index.php/GitHosting)