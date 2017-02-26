## HTML

### Paragraph
```html
<p> this is a sample paragraph </p>
```
### Heading
```html
<h1> this is a big title</h1>
<h2> a subtitle </h2>
```
### Anchor Link
```html
<a href="http://www.codeatuni.com/"> My Favorite Website</a>
```
### Image
```html
<img src="images/cat.jpg" alt="cat sleeping">
```

### Lists
A way to list various items. Can be ordered `<ol>`, unordered `<ul>`, and a few more.
```html
<ul>
  <li> Broccoli </li>
  <li> Lentils </li>
  <li> Ice Cream </li>
</ul>

<ol>
  <li> Mandarin </li>
  <li> Spanish </li>
  <li> English </li>
</ol>
```

### Division
A way to group various elements
```html
<div>
  <h3> My Cat </h3>
  <img src="images/cat.jpg" alt="cat sleeping">
  <p> This is how my cat looks when he's asleep </p>
</div>
```
### Form
Simple way to collect user input. Has `<input>` elements for collection, which can vary in type. Should have a Submit button so the form can be stored, the store will have to be processed by the server, which needs to be defined in the `action=""` attribute on the form.
```html
<form action="/my_server">
  First name:<br>
  <input type="text" name="firstname"><br>
  Email:<br>
  <input type="email" name="email">
  Favorite Colour:<br>
  <input type="color" name="fav_color">
  
  <input type="submit">
</form>
```

### HTML Structure
The simple way to start every new page.
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Website</title>
    <link href="css/style.css" rel="stylesheet">
  </head>
  <body>
    <h1>Hello, world!</h1>
    <!-- This is a HTML comment, it will not show for the users -->
  </body>
</html>
```


## CSS

### Basic CSS Structure
```css
body{
  background-color: orange;
  width: 600px;
  margin: 0 auto;
}

h1 {
  color: white;
  font-size: 52px;
  text-align: center;
}

/* This is a CSS comment */

.blue-button{
  background-color: blue;
  color: white;
  border: 2px solid white;
  border-radius: 4px;
}
```

## Bootstrap
Bootstrap is a HTML,CSS and Javascript framework originally created by Twitter to easily prototype every possible layout configuration, it's now open source and ready to use by anyone, being the most popular framework choice for a professional or begginner web developers and designers.

### Grid

Bootstrap introduces the concept of the Grid, in which every element is positioned. Grid is divded by Rows and Columns. This allows to position any element horizontally and vertically by understanding how to use rows and columns.

- Rows will take an entire width of the element they are positioned in, think of it as an entire line on your screen, from the beggining to the end.
- Columns will be our way to split rows, into several "columns"

```html
<div class="row">
    <div class="col-md-12">
      Welcome To The Grid
    </div>
</div>
```

### 12 Divisions Only

Every row will be divided into 12 equal parts. 
When we create a column we need to tell just how much do we need from those 12 parts for its width. 
In case we want to split a column into 2 equal parts, we should divide 12 by 2 and we get 6. Therefore we need to apply a specific number, in this case 6, to our column class. Like this: `<div class="col-md-6> content </div>`.
The number can range from 1 to 12, and will follow always a format of `col-md-NUMBER`, if we put 12 it will occupy the whole row, in case of 6 it will occupy 50%, if we put 3 it will occupy 25% of it, etc..

```html
<div class="row">
  <div class="col-md-12">Full width row</div>
</div>

<div class="row">
  <div class="col-md-6">50% Width</div>
  <div class="col-md-3">25% Width</div>
  <div class="col-md-3">25% Width</div>
</div>
```

In case we try to fit 3 columns of size 6 in our row, it will break the layout, causing the last col-md-6 to go to the next line. This should be avoided.

### Screen Size Classes
`col-md-6` stands for Column Medium Size 6, the medium represents screen-size, in this case for laptops/tablets. It plays a part in the responsiveness of Bootstrap.

Instead of using `md` all the time, we also have:
- xs – Extra small screens like mobile screens.
- sm – Small screen devices like tablets.
- md – Medium sized screens such as desktops and laptops.
- lg – Large, high resolution screens.




## Authors
- Alexander Kustov [github/alexanderkustov](https://github.com/alexanderkustov)


## License

[MIT](https://github.com/jonschlinkert/remarkable/blob/master/LICENSE)
