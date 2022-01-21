## Learning Goals

After this unit you will be able to...

- Understand what CSS Layout techniques are and what you can do with them
- Know the difference between some of the most important layout techniques
- Understand the basics of Flexbox, Grid, Floats and Relative Display techniques

## Introduction to CSS Positioning

In previous lessons we've seen how to create basic HTML structures; but so far we've only created layouts that follow a linear order. In this lesson we'll see an introduction to how we can create more complex screens and designs using CSS in order to change our layout.

The most important thing to understand about CSS layout is that it's not just about boxes and margins — it's all about positioning elements within those boxes.

CSS page layout techniques let us change where an element is positioned inside a design, relative to some factors like its parent element, the others around it, or even the browser window. There are several techniques we can use for this; in no particular order:

- Normal flow
- Display property
- Flexbox
- Grid
- Positioning (absolute & relative)
- Floats
- Table layout
- Multiple column layout

In this lesson we'll see an introduction to each one of these possibilites. In future lessons we'll dive in deeper to some of the most commonly used ones.

## Normal flow

The normal flow is the order in which elements appear on the page when we don't do anything special. For example, in a simple HTML template like the following:

```html
<h2>This is a header</h2>

<p>This is a paragraph</p>
<ul>
  <li>This is a list element</li>
</ul>
```

All the included elements will appear one after the other. As we've previously seen, some elements like `<div>` or `<p>` are considered "block" elements, and will fit the whole width of the browser screen. Others, like `<span>`, are "inline" elements and won't have a predetermined size.

When we use any of the CSS layout techniques we will see in this lesson, we can change the normal flow of the elements inside a document.

## The display property

The `display` property is one of our main tools when it comes to creating complex layouts and designs with HTML & CSS. This property allows us to modify the way elements appear on screen.

Every HTML element has a default `display` property. For example, "block" elements have a default `display: block` property. We can change this with CSS, effectively turning a block element into an inline one or vice versa.

However this is not the only use of the `display` property. Two of the most powerful tools for creating complex CSS layouts, `flexbox` and `grid`, are actually `display` options. Let's talk a bit more about them.

### Flexbox

The `flexbox` module allows us to define our page's content by giving each element its own size and placing them within a container. It's the best tool to position elements in one dimension, be it a column or a row.

Using flexbox is very simple. We just need to apply the CSS `display: flex` to our parent element, effectively making all its child elements flex items.

When we're using `flex`, we can apply special properties both to the parent element and to its childs. Among other things, when using this tool we'll be able to change the items' alignment, their relative size, their order or their position.

In [this link](https://codepen.io/enxaneta/full/adLPwv/) you can see in a very visual way how the different `flex` properties affect the elements it's applied to.

We'll dive deeper into the Flexbox Module in the following lessons.

What is the CSS Grid Layout Module?

The CSS Grid Layout module is a new feature in CSS3 that allows us to divide our page into rows and columns. It's based on the concept of placing boxes inside each other like Lego bricks.

Positioning techniques

The most common way to lay out content on the web is using absolute positioning. This means that each element has its own space on the page and it's positioned relative to the viewport. It's easy to understand but not always flexible.

Relative positioning

The most important thing to know about relative positioning is that it's based on the parent element. So if you want to move something down the page, you'd use top: 100px; left: 50%;. If you wanted to move something from one side of the screen to another, you'd use margin-left: -100px;.

Absolute positioning

The absolute positioning property allows us to place elements anywhere within the page. It's important to note that it doesn't affect any other properties of the element, so if you want to move something around, you'll need to set its top, left, right, bottom, width, height, margin, padding, border, background color, etc. properties accordingly.

Fixed positioning

The most common way to set a fixed element's position is by using the `position` property. This works well if you want to place elements side by side or above each other but it doesn't allow you to control where they appear relative to the edges of the browser window.

Sticky positioning

The sticky positioning property allows us to define where elements should stick to the edges of their container if they don't fit inside it. This is useful for creating navigation bars, headers, footers, and toolbars.
