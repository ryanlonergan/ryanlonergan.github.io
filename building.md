---
layout: page
sitemap: false
---

* This unordered list will be replaced by the table of contents
{:toc}

# Building My Site

Details of how I created my website and the many problems I encountered. I ran into many challenges while building it and wanted to detail it for myself and also to outline the solutions I found in case it helps someone else.

This page is still a work in progress. Check back later!
{:.note}

### Using Hydejack

<a href="https://www.hydejack.com" target="_blank">Hydejack</a> is "a boutique Jekyll theme for hackers, nerds, and academics" and the skeleton of what my site was built on. It is based off of <a href="https://hyde.getpoole.com/" target="_blank">Hyde</a>, but I was drawn to it over its predecessor due to its utilization of Javascript to make a more dynamic page. However, I ultimately found it to be more trouble than it was worth.
<br><br>
Don't get me wrong, I was able to make a great website that functioned exactly how I wanted it to. But still, I wasted a lot of time trying to get it work how I wanted it to and spent many nights frustrated while trying to find solutions. Hydejack looks great, but it hides a lot of the backbone of the site inaccessible unless you really know what you are doing with HTML and CSS. Overall, it was a great exercise in learning those languages, but I would make my website without using Hydejack if I were to do it again.

### Using Ruby for the First time

One of the first hurdles I had was to learn how to use Ruby to run Jekyll. I originally thought it was going to be a huge issue, but it was much easier than I thought and actually quite easy. The first step is to install <a href="https://www.ruby-lang.org/en/documentation/installation/" target="_blank">Ruby</a> and once it is installed, everything can be ran from the command line. For Windows, the only commands you need are:


    cd folder you store your site

Changes current directory

    gem install bundle
    bundle install

Creates a bundler gem and installs the required packages, i.e. jekyll. These commands are only needed for the initial setup.

    bundle exec jekyll build
    bundle exec jekyll serve

These commands are used to run the site each time you work on or update it. The "build" version builds the website immediately, creating the static pages needed for it to function. The "serve" version creates a server that automatically makes changes to the site as you work on. This method makes it extremely easy to see and test your changes in real time and is what I mostly use.

### GitHub Pages

<i>build issues<br>
publish issues<br>
atom
</i>

### Images

<i>putting things in the right folder<br>
inkscape
favico
masks/layers etc</i>

### What I Would Have Done Differently
