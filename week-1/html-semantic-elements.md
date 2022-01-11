## Learning Goals

After this lesson, you will be able to:

- Understand what Semantic Elements are in HTML.
- Know when to use a Semantic Element instead of a traditional one.

## HTML Semantic Elements

### What are Semantic Elements in HTML?

As opposed to non - semantic elements, in HTML semantic components are elements that have an inherent meaning that describe & define their content.

- Examples of non - semantic elements: `<div>` or `<span>`. These elements could include any kind of content and are very generic.
- Examples of semantic elements: `<footer>` or `<article>`. The tag itself gives us information about the kind of content it includes.

HTML introduced Semantic Elements in its latest versions, and their use is recommended whenever possible. A lot of developers still use HTML code like the following: `<div id="footer">`. This is disencouraged nowadays, given that more descriptive options exist.

#### Why are Semantic Elements important?

Semantic Elements are a very useful tool to create a website following a universal standard. When used, any developer can dive into a website's source code and know exactly what each part of the HTML code does.

For this reason, it's considered a good practice to use Semantic Elements over non semantic ones whenever possible.

## Important Semantic Elements

There are many different Semantic Elements that can be used when building a website. In no particular order, these are some of the most important ones:

- `<article>`
- `<aside>`
- `<details>`
- `<figcaption>`
- `<figure>`
- `<footer>`
- `<header>`
- `<main>`
- `<mark>`
- `<nav>`
- `<section>`
- `<summary>`
- `<time>`

Next we'll review some of these elements in depth.

### Header

The `<header>` element represents a container for introductory content or a set of navigational links.

A `<header>` element typically contains:

- One or more heading elements
- A logo or icon
- Authorship information

Note: You can have several `<header>` elements in one HTML document. However, `<header>` cannot be placed within a `<footer>`, `<address>` or another `<header>` element.
