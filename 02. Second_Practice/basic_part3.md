# CSS Classes & Selectors

https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade

```css
p.error {
    color: red;
}

p.success {
    color: green;
}

p.success.feedback {
    border: 1px dashed black;
}


#content {
    background-color: #ebebeb;
    padding: 20px;
} 

/* only p tag in div id="content" */
/* space가 있어야 child 로 인식함. */
div .error {
    color: purple;
}

/* particular attribute */
a[href] {
    background-color: #edd13e;
}

/* particular href */
a[href="www.google.com"] {
    background-color: #3dd13d;
    color: white;
    text-decoration: none;
    font-weight: bold;
    text-transform: uppercase;
}

/* face 이라는 값 만을 포함하면 다 style 적용도 가능하다 */
a[href*="www.facebook.com"] {
    background-color: #3dd13d;
    color: white;
    text-decoration: none;
    font-weight: bold;
    text-transform: uppercase;
}


/* $를 사용하면 어떤 마지막에 .com 으로 끝나는 것 */
/* pdf 같은 것을 찾는데 되게 유용하다 */
a[href$=".com"] {
    padding: 10px;
}

/* The Cascade */

```



# Inheritance

- HTML elements can inherit CSS properties that are applied to their parents

```html
<div>
    <p>
        hello
    </p>
</div>
```

```css
div {
	color: red
}
```

- 이 경우 p tag 또한 red color를 가지게된다.

```html
<div>
    <p>
        hello , <span>ninjas</span>
    </p>
</div>
```

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="./inheritnace.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>

<body>
    <!-- id cannot be reusable -->
    <div id="content">

        <p class="error">Lorem ipsum dolor</p>
        <p class="success">Lorem ipsum dolo</p>
        <p class="success feedback">Lorem ipsum dolo</p>

        <div class="error">Hello World</div>
    </div>


    <a href="www.facebook.com">Facebook Hello</a>
    <a href="www.google.com">Hello World</a>
</body>

</html>
```

Case #1

```css
/* not every style is inherited, such as border, margin */
div {
    color: lightcoral;
    font-weight: bold;
    border: 1px solid grey;
    margin: 40px;
}

```

- 모든 style element가 상속되지는 않는다.

Case #2

```css
/* not every style is inherited, such as border, margin */
div {
    color: lightcoral;
    font-weight: bold;
    border: 1px solid grey;
    margin: 40px;
}

/* 만약에 border와 margin 등 by default로 inherit 되지 않는 요소를 상속하고 싶을때 */
/* 만약에 color와 같이 상속됨에도 불구하고 p tag 자체에 color를 따로 제공하면 따로 제공된 color가 적용된다. */
p {
    border: inherit;
    margin: inherit;
    color: crimson;
}
```

- 비록 부모element에 lightcoral이 적용됨에도 불구하고, p tag에 직접적으로 color를 적용하면 더 구체적인 p tag에 적용한 color style이 적용된다.

Case #3

```css
p {
    border: inherit;
    margin: inherit;
    color: crimson;
}

p {
    border: inherit;
    margin: inherit;
    color: orange;
}
```

- 동일한 element에 적용시 제일 마지막에 적용한 style이 overwrite되 적용된다.

Case #4

```css
div p {
    border: inherit;
    margin: inherit;
    color: crimson;
}

p {
    border: inherit;
    margin: inherit;
    color: orange;
}
```

- 비록 마지막 p tag 에 orange color가 적용됨에도 불구하고, div p 가 더 구체적이기 때문에 crimson color가 적용된다.