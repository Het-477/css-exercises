# Mistakes to avoid before flexing and positioning multiple items in a concise way 

## Mistake 1. Not looking at the main container which wraps all those items in html  

- instead of centering all the items manualy, find or make a container wrapper which wrapps all the items to position them like this: 

```html
<div class="header">
      <div class="left">
        <div class="logo">
          LOGO
        </div>
        <ul class="links">
          <li><a href="https://google.com">link-one</a></li>
          <li><a href="https://google.com">link-two</a></li>
          <li><a href="https://google.com">link-three</a></li>
        </ul>
      </div>
      <div class="right">
        <button class="notifications">
          1 new notification
        </button>
        <div class="profile-image"></div>
      </div>
    </div>
```
As you can see, all the items such as logo, notification bar, links, etc.. are inside the ```header``` div container class. this makes it easy to position the items altogether or in groups

## Organise the particular groups or complexly naming them:

Naming the group of things you want to center or position is a nessecity ,and naming them correctly is even bigger!

```html 
<div class="left">
        <div class="logo">
          LOGO
        </div>
        <ul class="links">
          <li><a href="https://google.com">link-one</a></li>
          <li><a href="https://google.com">link-two</a></li>
          <li><a href="https://google.com">link-three</a></li>
        </ul>
      </div>
      <div class="right">
        <button class="notifications">
          1 new notification
        </button>
        <div class="profile-image"></div>
      </div>
```
