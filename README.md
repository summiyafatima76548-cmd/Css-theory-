🎨 CSS Fundamentals

# What is CSS?

CSS (Cascading Style Sheets) is a stylesheet language used to control the appearance and layout of web pages.

HTML creates the structure of a webpage, while CSS is responsible for the design and presentation of that webpage.

🏠 ## Real-Life Example

Technology| Purpose
HTML| Structure of a House
CSS| Paint, Decoration & Design

Without CSS, websites would look plain and unattractive.

---

# What Does CSS Stand For?

CSS = Cascading Style Sheets

 Meaning

- Cascading → Styles follow a priority order.
- Style → Controls appearance.
- Sheets → Collections of style rules.

---

# What Problem Does CSS Solve?

HTML only provides content and structure.

HTML Example

<h1>Welcome</h1>
<p>This is my website.</p>

Output

Welcome

This is my website.

The page looks very basic.

---

CSS Example

h1{
    color: blue;
    text-align: center;
}

Result

✅ Blue Heading

✅ Center Alignment

✅ Better Design

---

# Methods of Adding CSS

There are 3 ways to add CSS to HTML.

Method| Description
External CSS| Separate CSS File
Internal CSS| "<style>" Tag
Inline CSS| "style=""" Attribute

---

1️⃣ External CSS

External CSS stores styles in a separate ".css" file.

HTML File

<!DOCTYPE html>
<html>
<head>

<link rel="stylesheet" href="style.css">

</head>
<body>

<h1>External CSS Example</h1>

</body>
</html>

CSS File

h1{
    color: blue;
    font-size: 32px;
    text-align: center;
}

✅ Advantages

- Reusable
- Easy Maintenance
- Professional
- Faster Loading

---

2️⃣ Internal CSS

Internal CSS is written inside the "<style>" tag.

<!DOCTYPE html>
<html>
<head>

<style>

h1{
    color: green;
    font-size: 32px;
    text-align: center;
}

</style>

</head>
<body>

<h1>Internal CSS Example</h1>

</body>
</html>

Output

🟢 Green Heading

---

3️⃣ Inline CSS

Inline CSS is written directly inside HTML elements.

<!DOCTYPE html>
<html>
<body>

<h1 style="color:red; font-size:32px;">
Inline CSS Example
</h1>

</body>
</html>

Output

🔴 Red Heading

---

# Why External CSS is Preferred?

1. Separation of Concerns

HTML → Structure

CSS → Styling

<h1>My Website</h1>

h1{
    color: blue;
}

---

2. Reusability

One CSS file can style multiple pages.

<link rel="stylesheet" href="style.css">

Used in:

- Home Page
- About Page
- Contact Page

---

3. Easy Maintenance

Change one CSS file:

h1{
    color: green;
}

Entire website updates automatically.

---

4. Better Performance

Browsers cache CSS files.

Benefits:

- Faster Loading
- Better User Experience

---

# CSS Syntax

General Syntax:

selector{
    property: value;
}

Example

h1{
    color: blue;
}

Breakdown

Component| Description
h1| Selector
color| Property
blue| Value

---

# Complete Project Example

index.html

<!DOCTYPE html>
<html>
<head>

<title>CSS Demo</title>

<link rel="stylesheet" href="style.css">

</head>
<body>

<h1>Welcome to CSS</h1>

<p>This is my first styled webpage.</p>

</body>
</html>

style.css

body{
    background-color: lightgray;
}

h1{
    color: blue;
    text-align: center;
}

p{
    font-size: 18px;
}

---

🚀 Advantages of CSS

- ✅ Attractive Design
- ✅ Better User Experience
- ✅ Responsive Layouts
- ✅ Less Repetition
- ✅ Easy Maintenance
- ✅ Faster Website Performance
- ✅ Professional Development Practice

---

📝 Conclusion

CSS (Cascading Style Sheets) is used to style and design HTML web pages. It controls colors, fonts, layouts, spacing, and responsiveness. CSS can be added using External CSS, Internal CSS, and Inline CSS, but External CSS is the most recommended method because it keeps code clean, reusable, and easy to manage.

---
