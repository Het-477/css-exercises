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