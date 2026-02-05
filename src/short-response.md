# Short Response Questions

Answer the following questions in your own words. Each response should be 2-4 sentences.

## Question 1: HTML Structure

What is the difference between the `<head>` and `<body>` sections of an HTML document? What kind of content goes in each?

**Your Answer:**

The `<head>` `section` contains **metadata** about the document, such as the page title, character encoding, links to `CSS` files, and `script` references. Content in the `<head>` is not displayed directly on the page. The `<body>` section contains all of the visible content that users see, including text, images, buttons, and other interactive elements. The `<body>` defines the structure and content of the webpage.

## Question 2: Semantic HTML

Why should we use semantic elements like `<header>`, `<main>`, and `<footer>` instead of using `<div>` tags for everything?

**Your Answer:**

**Semantic elements** clearly describe the meaning and purpose of their content, making the `HTML` more readable and maintainable. They also improve accessibility by helping screen readers understand the structure of the page. Also, semantic `HTML` helps search engines better interpret and index the content. Using **semantic elements** instead of generic `<div>` tags results in more structured pages.

## Question 3: CSS Selectors

Given the following HTML:

```html
<ul>
  <li class="vegetable">Carrots</li>
  <li class="vegetable">Broccoli</li>
  <li class="fruit" id="favorite">Mango</li>
</ul>
```

Write THREE different CSS rules:
1. One that makes ALL list items have a `yellow` background
2. One that makes only the vegetables have `green` text color
3. One that makes only the Mango `bold`

**Your Answer:**

```css
li {
  background-color: yellow;
}

.vegetable {
  color: green;
}

#favorite {
  font-weight: bold;
}
```


## Question 4: The Box Model

In your own words, explain the four parts of the CSS box model (content, padding, border, margin). What is the purpose of each part?

**Your Answer:**

The content is the actual area where text and images are displayed. `Padding` is the space between the content and the border, which adds internal spacing. The border surrounds the `padding` and content and defines the visible edge of the element. Margin is the space outside the border that separates the element from other elements on the page.

## Question 5: Box-Sizing

What problem does `box-sizing: border-box` solve? Why do we include it in a CSS reset at the top of our CSS files?

**Your Answer:**

`box-sizing: border-box` ensures that `padding` and **border** are included in an element’s total width and height. This prevents elements from becoming larger than expected when `padding` or **borders** are added. It makes layouts easier to reason about and more consistent. That is why it is commonly included in a CSS reset.

## Question 6: Display Property

What is the difference between `display: block`, `display: inline`, and `display: inline-block`? Give an example of when you might use `inline-block`.

**Your Answer:**

`display: block` elements take up the full width and start on a new line, while `display: inline` elements only take up as much width as their content and do not start a new line. `display: inline-block` allows elements to sit inline while still accepting width, height, margin, and padding. An example use of `inline-block` is for styling navigation links or buttons that need custom sizing but should appear side by side.
