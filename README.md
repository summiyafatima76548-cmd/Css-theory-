## What is CSS and how do you add it to an HTML page?


### What does CSS stand for?

CSS stands for Cascading Style Sheets. It is a stylesheet language used to control the appearance, layout, and visual design of web pages.

#### Html and Css Example 

```html

<h1>Hello World</h1>
```
```css

h1 {
    color: blue;
    text-align: center;
}
```

### What problem does CSS solve?

CSS separates the content of a web page from its design. Without CSS, websites would look plain and difficult to manage. CSS helps developers create attractive, organized, and user-friendly websites.

- CSS is also used to:

- Create layouts using Flexbox and CSS Grid

- Add shadows and borders

- Create animations and transitions

- Build responsive websites using Media Queries

- Manage reusable styles with CSS Variables

  ```Html

<h1>Welcome to My Website</h1>
<p>This is a paragraph.</p>
```

```Css

h1 {
    color: purple;
    text-align: center;
}

p {
    font-size: 18px;
}

.card {
    border: 2px solid black;
    box-shadow: 5px 5px 10px gray;
}
```

The heading becomes purple and centered, the paragraph becomes easier to read, and elements can have borders and shadows. This makes the website more attractive, professional, and easier to maintain. 

### Name all three methods of adding CSS?

Three Methods of Adding CSS

1. External CSS

In External CSS, styles are written in a separate .css file and linked to the HTML document. This is the most recommended method because it keeps code organized and allows one CSS file to style multiple web pages. 

#### index.html

<!DOCTYPE html>
<html>
<head>

    <link rel="stylesheet" href="style.css">

</head>
<body>

    <h1>External CSS Example</h1>

</body>
</html>
```

#### Style.css

```css
h1{
    color: blue;
}
```
#### Css:

In Internal CSS, styles are written inside the <style> tag in the <head> section of the HTML document. It is useful when styling a single web page.


<!DOCTYPE html>
<html>
<head>
<style>

h1{
    color: green;
}

</style>
</head>
<body>

<h1>Internal CSS Example</h1>

</body>

</html>


#### Inline Css:

In Inline CSS, styles are written directly inside an HTML element using the style attribute. It is suitable for applying styles to a specific element only. 

<!DOCTYPE html>
<html>
<body>

<h1 style="color:red;">Inline CSS Example</h1>

</body>
</html>

### Why is External CSS Preferred Over Inline CSS? 

Easier to Maintain
If you want to change a style, you only need to edit one CSS file instead of editing every HTML element.

Cleaner Code

HTML files remain simple and easy to read.

Styling code is stored separately.

Used in Professional Projects

Most real-world websites use External CSS because it is efficient and scalable.


#### Index.html

<!DOCTYPE html>
<html>
<head>

    <link rel="stylesheet" href="style.css">

</head>
<body>

    <h1>Home Page</h1>
    <p>Welcome to our website.</p>

</body>
</html>

#### About.html

<!DOCTYPE html>
<html>
<head>

    <link rel="stylesheet" href="style.css">

</head>
<body>

    <h1>About Us</h1>
    <p>Learn more about our company.</p>

</body>
</html>

#### Style.css

h1 {
    color: blue;
}

p {
    font-size: 18px;
}
