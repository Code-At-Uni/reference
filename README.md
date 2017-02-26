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



## Authors
- Alexander Kustov [github/alexanderkustov](https://github.com/alexanderkustov)


## License

[MIT](https://github.com/jonschlinkert/remarkable/blob/master/LICENSE)
