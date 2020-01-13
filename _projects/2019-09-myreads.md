---
title: 'MyReads: A Book Tracking App'
subtitle: 'A React bookshelf application'
date: 2018-06-30 00:00:00
description: This is a bookshelf app built using ReactJS that allows you to select and categorize books you have read, are currently reading, or want to read.
featured_image: '/images/myreads-book-app/myreads1.jpg'
repo_link: https://github.com/amar086/reactnd-project-myreads-starter
app_link: https://master.dc3naz24nc2ew.amplifyapp.com/
---

![](/images/myreads-book-app/myreads1.jpg)

## Project Description

In this application, the main page displays a list of "shelves", each of which contains a number of books. The three shelves are:

* Currently Reading
* Want to Read
* Read

Each book has a control that lets you select the shelf for that book. When you select a different shelf, the book moves there. 
The main page also has a link to /search, a search page that allows users to find books to add to their library. The search page has a text input that may be used to find books. As the value of the text input changes, the books that match that query are displayed on the page, along with a control that lets you add the book to your library.  The search page also has a link that leads back to the main page. When you navigate back to the main page from the search page, you should instantly see all of the selections you made on the search page in your library.

### Skills
* ReactJS
* React router
* Javascript 
* CSS3
* ServiceWorker for caching and offline use 
* Git, Github 


{% comment %}You can also add blockquotes, which are shown at a larger width to help break up the layout and draw attention to key parts of your content:

> “Simple can be harder than complex: You have to work hard to get your thinking clean to make it simple. But it’s worth it in the end because once you get there, you can move mountains.”{% endcomment %}


---

### Image galleries

Here's a gallery of the app's features:

<div class="gallery" data-columns="3">
	<img src="/images/myreads-book-app/myreads1.jpg">
	<img src="/images/myreads-book-app/myreads2.jpg">
	<img src="/images/myreads-book-app/myreads3.jpg">
	<img src="/images/myreads-book-app/myreads4.jpg">
</div>

{% comment %}Inspired by the Galleries feature from WordPress, we've made it easy to create grid layouts for your images. Just use a bit of simple HTML in your post to create a masonry grid image layout:

```html
<div class="gallery" data-columns="3">
    <img src="/images/demo/demo-portrait.jpg">
    <img src="/images/demo/demo-landscape.jpg">
    <img src="/images/demo/demo-square.jpg">
    <img src="/images/demo/demo-landscape-2.jpg">
</div>
```

*See what we did there? Code and syntax highlighting is built-in too!*

Change the number inside the 'columns' setting to create different types of gallery for all kinds of purposes. You can even click on each image to seamlessly enlarge it on the page.{% endcomment %}

---

### Image carousels

{% comment %}Here's another gallery with only one column, which creates a carousel slide-show instead.

A nice little feature: the carousel only advances when it is in view, so your visitors won't scroll down to find it half way through your images.{% endcomment %}

<div class="gallery" data-columns="1">
	<img src="/images/myreads-book-app/myreads2.jpg">
	<img src="/images/myreads-book-app/myreads4.jpg">
</div>
