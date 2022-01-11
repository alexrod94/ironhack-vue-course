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

Headers are typically present in most websites.

### Footer

The other side of the coin, the `<footer>` element is used to define the footer section of an HTML document.

Footers can include any kind of information, but some of the most common elements inside of it are the following:

- Authorship & copyright information
- Contact data & social links
- Sitemap
- Legal documents

It's possible to include several footer elements in a single document.

### Nav

A `<nav>` element is used to include the main navigation links on a website. Not all navigation links have to be inside here; `<nav>` elements are typically used inside a navbar.

### Section

The `<section>` tag is one of the most generic semantic elements in HTML5. It is used to define a specific section inside a document, which involves a group of content that's thematically related.

For example, a website can have a `<section>` in the introductory part, another one for the 'About Us' section, and a final one with contact information inside.

### Article

The `<article>` semantic element is used to point to independent, self-contained content.

An article should make sense on its own, and it should be possible to distribute it independently from the rest of the document.

Examples of where the `<article>` element can be used:

- Forum posts
- Blog posts
- User comments

### Other semantic elements

Here are some other semantic elements and a brief description of their use:

| <b>Tab</b>  | <b>Description</b>                                    |
| ----------- | ----------------------------------------------------- |
| `<aside>`   | Defines content in a "sidebar" section                |
| `<details>` | Gives additional information that the user can toggle |
| `<figure>`  | Used to include self - contained, graphic content     |
