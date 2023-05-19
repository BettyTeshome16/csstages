# HTML Tags

1,<html></html >    

• The  element is the root element of an HTML page.

2,<title></title> 

 The element contains meta information about the HTML page.

3, <h1></h1> 

element defines a large heading.

4,<p></p>

element defines a paragraph.

5, <title> </title> 

The element specifies a title for the HTML page.

6,<body></body> 

 element defines the document's body,

7,<style> ,/style>

 to add style for element.

8,<link> 

to like html and CSS.

9,<img>

 image tags.

10,<div> </div>

section html.css  selector

# CSS Tags

### **CSS Colors**

Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.

### CSS Background Color

You can set the background color for HTML elements:

For Example:

<h1 style="background-color:DodgerBlue;">Hello World</h1>

### CSS Borders

The CSS border properties allow you to specify the style, width, and color of an element's border.

### CSS Margins

The CSS `margin` properties are used to create space around elements, outside of any defined borders.

With CSS, you have full control over the margins. There are properties for setting the margin for each side of an element (top, right, bottom, and left)

For example:

.p {

margin-top: 100px;

margin-bottom: 100px;

margin-right: 150px;

margin-left: 80px;

}

### CSS Padding

The CSS `padding` properties are used to generate space around an element's content, inside of any defined borders.

With CSS, you have full control over the padding. There are properties for setting the padding for each side of an element (top, right, bottom, and left).

For example

.

div {

padding-top: 50px;

padding-right: 30px;

padding-bottom: 50px;

padding-left: 80px;

}

---

---

## **CSS selectors**

are used *to select the content you want to style*. Selectors are the part of CSS rule set.

they have many selector but those are the main selector:

1,**Simple selectors** : select elements based on name, id, class.

one of simple selector is **CSS Id Selector,** The id selector selects the id attribute of an HTML element to select a specific element. An id is always unique within the page so it is chosen to select a single, unique element.

2,**Attribute selectors** : The CSS **attribute selector** matches elements based on the presence or value of a given attribute.

For example: 

```css
/* <a> elements with a title attribute */
a[title] {
  color: purple;
}
```

3,**child selector** :selects all elements that are the children of a specified element.

4, **Pseudo-elements** : A CSS pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element.

For example, it can be used to:

- Style the first letter, or line, of an element
- Insert content before, or after, the content of an element.

5,A ***pseudo-class:*** is a keyword added to a selector that specifies a special state of the selected element.

For example: 

```css
/* Any button over which the user's pointer is hovering */
button:hover {
  color: blue;
}
```

6,A combinator: is something that explains the relationship between the selectors.

## **SCSS**

Sassy Cascading Style Sheets is one of [two syntaxes available](https://www.upwork.com/resources/scss-vs-sass) for the popular CSS preprocessor Sass (Syntactically Awesome Stylesheets). It can be used to style the visual elements of a webpage, including buttons, sliders, images, color schemes, fonts, themes, and layouts. As a true superset of CSS, all valid CSS is also valid SCSS.

# How does SCSS work

SCSS is simply one of two syntaxes available for the CSS preprocessor Sass. Like any preprocessor, Sass works by being compiled into native CSS code that will work across any browser.

The real time-saving magic comes into play on the developer’s end when they can write concise SCSS code that will compile into longer CSS code. In this way, SCSS empowers developers to do more with less, without compromising on compatibility with the web.

# What is XML

The Extensible Markup Language (XML) is a simple text-based format for representing structured information: documents, data, configuration, books, transactions, invoices, and much more

# What is XML Used For

XML is one of the most widely-used formats for sharing structured information today: between programs, between people, between computers and people, both locally and across networks.

## Bootstrap

is a popular CSS framework that provides pre-built components and styles for creating responsive websites. It includes a responsive grid system, pre-built components like forms and buttons, and CSS classes for common UI elements like typography and navigation. It is designed to help developers create modern, responsive websites quickly and easily using a standardized set of tools and conventions.

The first ****Starter template is:****

```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
```

## **Breakpoints**

are locations in your CSS where the layout of your website will change to accommodate different screen sizes. By setting breakpoints, you can ensure that your website looks great on both desktop and mobile devices. Common breakpoints include:

- 320px (for mobile devices)
- 768px (for tablets)
- 1024px (for smaller laptops)
- 1440px (for larger laptops and desktops)

To create breakpoints in your CSS, you can use media queries. For example:

### **@media (min-width: 768px) {
  /* Styles for tablets and larger devices */
}**

**Core concepts**

1,**Breakpoints are the building blocks of responsive design.**
2,**Use media queries to architect your CSS by breakpoint.**

3,,**Mobile first, responsive design is the goal.**

# **Containers**

Containers are a fundamental building block of Bootstrap that contain, pad, and align your content within a given device or viewport.

Bootstrap comes with three different containers:

- `.container`, which sets a `max-width` at each responsive breakpoint
- `.container-fluid`, which is `width: 100%` at all breakpoints
- `.container-{breakpoint}`, which is `width: 100%` until the specified breakpoint

for example

- **Extra small (**<576px)
- **Small (**≥576px)
- **Medium (**≥768px)
- **Large (**≥992px)
- **X-Large (**≥1200px)
- **XX-Large (**≥1400px)

## **Grid system**

is a powerful tool for creating flexible and responsive layouts in CSS. With a grid system, you can divide your page into columns and rows, and then position your content within those columns and rows.

Bootstrap's grid system is based on a 12-column layout. You can use classes like `col-sm-4` to specify how many of those columns your element should span at different screen sizes. For example, `col-sm-4` would span 4 columns on small screens and up, while `col-md-6` would span 6 columns on medium screens and up.

To create a row in the grid system, you can use the `.row` class. Inside that row, you can create columns by using the `.col-*` classes, where * is the number of columns you want that element to span.

For example:

```
<div class="container">
  <div class="row">
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
  </div>
</div>
```

This would create a row with three columns that each span 4 columns on small screens and up.

You can also use offset classes to push your columns to the right or left. For example, `col-sm-offset-4` would push a column over by 4 columns on small screens and up.

Overall, the grid system is a powerful tool for creating flexible and responsive layouts in CSS that can adapt to different screen sizes and devices.

## ****Columns****

**Columns build on the grid’s flexbox architecture.**

**When building grid layouts, all content goes in columns.**

**Bootstrap includes predefined classes for creating fast, responsive layouts.**  

## ****Alignment****

In alignment they have ****Vertical alignment and Horizontal alignment.****

**Vertical alignment** can be achieved using CSS flexbox. By setting the parent element's display property to "flex" and using the "align-items" property, child elements can be vertically aligned within the parent element. For example:

```
<div class="container">
  <div class="row align-items-start">
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
  </div>
  <div class="row align-items-center">
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
  </div>
  <div class="row align-items-end">
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
    <div class="col">
      One of three columns
    </div>
  </div>
</div>
 

```

****Horizontal alignment****

Bootstrap offers a variety of classes for aligning elements horizontally. For example, you can use the `text-center` class to center text within an element, or the `justify-content-center` class to center content within a flex container. Other classes include `text-left`, `text-right`, `float-left`, and `float-right`.

other example

```
<div class="container">
  <div class="row justify-content-start">
    <div class="col-4">
      One of two columns
    </div>
    <div class="col-4">
      One of two columns
    </div>
  </div>
  <div class="row justify-content-center">
    <div class="col-4">
      One of two columns
    </div>
    <div class="col-4">
      One of two columns
    </div>
  </div>
  <div class="row justify-content-end">
    <div class="col-4">
      One of two columns
    </div>
    <div class="col-4">
      One of two columns
    </div>
  </div>
  <div class="row justify-content-around">
    <div class="col-4">
      One of two columns
    </div>
    <div class="col-4">
      One of two columns
    </div>
  </div>
  <div class="row justify-content-between">
    <div class="col-4">
      One of two columns
    </div>
    <div class="col-4">
      One of two columns
    </div>
  </div>
  <div class="row justify-content-evenly">
    <div class="col-4">
      One of two columns
    </div>
    <div class="col-4">
      One of two columns
    </div>
  </div>
</div>
```