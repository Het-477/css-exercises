# A small mistake which affects a lot

### Todays mistake and lesson

```css
.avatar .proportioned {
    height: auto;
    width: 300px;
```
  above and below lines may look same but they are not. cuz of that lil ' '(space) between them
    which acts as a ','(comma) symbol which totally changes the rules for both classes  

```css
.avatar.proportioned {
    height: auto;
    width: 300px;
}
```
#
#
# Points to remember 
- ' ' is used when selecting nested elements and classes, like:
```html
<div class="container">
    <p class="text">This should be styled.</p>
    </div>
```
and 
```css
.container .text {
    background-color: yellow;
    color: red;
    font-size: 20px;
    text-align: center;
}
```
- '.' period (dot) joining two or more classes like
```css
.class1.class2 {
    // rules here 
} 
```
is used to select similar class names inside one element in html file, like :
```html
<div class="class1 class2">
<div class="class4 class2">
```
