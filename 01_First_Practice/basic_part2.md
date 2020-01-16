# HTML Block and Inline Elements

- Every HTML element has a default display value depending on what type of element it is.

  The two display values are: **block** and **inline**.

### Block-level Elements

- A block-level element always starts on **a new line** and takes up the **full width available** (stretches out to the left and right as far as it can).

```HTML
<div>Hello World</div>
```

```html
// Block level elements in HTML:
// https://www.w3schools.com/html/html_blocks.asp 참조
// 많이 사용되는 elements 위주로
<h1> ~ <h6>
<form>
<div>
<li>
<ul>
<hr>
```

### Inline Elements

- An **inline element** does not start on **a new line and only takes up as much width as necessary**.

```html
// This is an inline <span> element inside a paragraph.

<span>Hello World!</span>
```

```html
// Inline elements in HTML:
// https://www.w3schools.com/html/html_blocks.asp 참조
<a>
<input>
<label>
<script>
<span>
<i>
<img>
<button>
```

## The <div> Element

- The <div> element is often used as a container for other HTML elements.
- The <div> element has no required attributes, but **style**, **class**, and **id** are common.
- When used together with CSS, the **div** element can be used to style blocks of content:

```html
<div style="background-color:black; color:white: padding:20px"> 
	<h2>
      London  
    </h2>
    <p>
        Hello World!
    </p>
</div>
```

## The <span> Element

- The <span> element is often used as a container for some text.
- The <span> element has no required attributes, but **style**, **class**, and **id** are common.

- When used together with CSS, the **span** element can be used to style parts of the text:

```html
<h1>
    My <span style="color:red">Important</span> Heading!
</h1>
```

# div and span elements

**div** Tag = Defines a section in a document (block-level)

**span** Tag = Defines a section in a document (inline)

# Forms

- The HTML <form> element defines a form that is used to collect use input:

```html
<form>
    ...
	form elements
    ...
</form>
```

- An HTML form contains **form elements**.
- Form elements are different types of input elements, like text fields, check boxes, radio buttons, submit buttons, and more...

# The <input> Element

- The <input> element is the most important form element.
- The <input> element can be displayed in several ways, depending on the **type** attribute.

| Type                  | Description                                                |
| :-------------------- | :--------------------------------------------------------- |
| <input type="text">   | Defines a one-line text input field                        |
| <input type="radio">  | Defines a radio button (for selecting one of many choices) |
| <input type="submit"> | Defines a submit button (for submitting the form)          |

# Text Input

<input type="text"> defines a one-line input field for text input:

```html
<form>
    First Name: <br>
    <input type="text" name="firstname"><br>
    Last Name: <br>
    <input type="text" name="lastname">
</form>
```

# Radio Button Input

















