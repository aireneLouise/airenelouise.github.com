---
layout: post
title: "Learning Jekyll"
tagline: The path I took through Jekyll
description: ""
category: 
tags: []
---
{% include JB/setup %}

### First Stop : Github 

With my [GitHub](https://github.com) account, I created a new repository and names it **myUsername.github.com**. *(change "myUsername to your own github username")*.

<br />

### Second Stop : Installing Jekyll

    $ git clone https://github.com/plusjade/jekyll-bootstrap.git myUsername.github.com
    $ cd myUsername.github.com
    $ git remote set-url origin git@github.com:myUsername/myUsername.github.com.git
    $ git push origin master

<br />

### Third Stop : Starting the Server

    $ jekyll --server

After this, your blog would be available at [http://localhost:4000/](http://localhost:4000/).

<br />

### Fourth Stop : Creating a Post

Posts are created using the `rake` command

    rake post title="Post Title"

<br />

### Fifth Stop : Publishing

    $ git add .
    $ git commit -m "Add new content"
    $ git push origin master

<br />

### End of the Road

See it [here](http://username.github.com/)*(change username to your github username)*.


 


