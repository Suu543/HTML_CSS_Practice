# Pseudo Classes
- Style elements when they're in a particular state
  - hover, focus, first child of a parent

```html
:hover        :focus       :first-child
```

```css
nav li a:hover {
    text-decoration: underline;
    background-color: pink;
    padding: 3px;
}

.images li:hover {
    position: relative;
    top: -4px;
}

form input:focut {
    border: 4px dashed #4b4b4b;
    outline: none;
}

/* email validation */
form input:valid {
    border: 4px solid #71d300;
}

/* ALL CSS Pseudo Elements */
article p::first-line {
    font-weight: bold;
    font-size: 1.2em;
}

section.join p::first-letter {
    font-size: 1.5em;
}

/* drag시 색깔 변경 */
section.join p::selection {
    background-color: red;
}

p::after {
    content: '...'
}

p::before {
    content: 'hahahaha'
}
```

/* https://www.youtube.com/redirect?redir_token=t_Zx8RpfqgvhTYFpzkaEG7uhiud8MTU3OTIzODU2MEAxNTc5MTUyMTYw&q=https%3A%2F%2Fwww.w3schools.com%2Fcss%2Fcss_pseudo_elements.asp&event=video_description&v=FMu2cKWD90g */