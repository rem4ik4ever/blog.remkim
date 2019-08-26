---
layout: post
title:  "It all starts with 'Initial Commit'"
date:   2019-08-26 00:24:33 -0400
categories: blog
---

<pre>git commit -m 'initial commit'</pre>

<p class="content">
Every big project once started with "Initial Commit". This is the moment when something great is being created. So here it is. My first blog initial commit.  
</p>

<p>This blog has been long in my plan, but I never had a chance to actually start it. Funny enough I had enough time to read someones else blog, but never had time to setup my own. </p>

<p>This time I took vacation and promised myself to finally do it!</p>

<p class="content">So here we go.</p>


<h2 class="title is-4">
  First things first
</h2>

<p class="content">
  It took me some time to plan this all out.

  <ul>
    <li>What tools to use?</li>
    <li>Do I need to setup a server?</li>
    <li>Do I need to create database?</li>
    <li>What to do?</li>
  </ul>
</p>

<p class="content">
  I knew some things for sure. I didn't want this to become pain in the ass to setup. So after a quick google search I found out that there are ways to host your blog on github, manage content as a static html and deploy with simple push to master branch.
</p>

Here is a list of tools I decided to use:
- Github as a hosting platform
- Netlify as a deployment tool 
- Jekyll as a static site generator

### Setup

With Github its pretty straight forward. 
- Create a repository 
- Put index.html in root of the repository and some "Hello World!" text 
- fin

Netlify 
- Create free account for personal use
- Link your github account 
- Allow access to repository 
- Pick your new repository and follow initial setup
- Once everything is done you are ready to make your first deploy

Once you deploy Netlify will provide public url to your website which is subdomain name from Netlify. Later on you can buy your own domain name and link it to Netlify. 

Easy stuff if behind. Now to the building part.

#### Jekyll, Jekyll, Jekyll. 
It took me some time to understand how this works. Just because I've never worked with static site generators. I know ruby and I know how to setup servers create db, models, controllers etc etc. But this was something new. Yet, when you finally understand how things work it becomes very and very easy.

Once you setup your default layout and post layout. It all comes down to you just writing you blogs in Markdown. That basically it. 

### Fin

Now that everything is setup, go write some stuff! 
