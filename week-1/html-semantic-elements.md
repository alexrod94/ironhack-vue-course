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

Headers are typically present in most websites, and in most sub elements such as articles.

#### Example

Here's an example of an `<article>` element with a header section.

```html
<article>
  <header>
    <h1>This is the article's title</h1>
    <p>And this is the article's description</p>
  </header>
  <p>
    Nam varius, mauris a scelerisque auctor, est quam tristique sapien, vitae
    venenatis magna velit id mauris.
  </p>
</article>
```

### Footer

The other side of the coin, the `<footer>` element is used to define the footer section of an HTML document.

Footers can include any kind of information, but some of the most common elements inside of it are the following:

- Authorship & copyright information
- Contact data & social links
- Sitemap
- Legal documents

It's possible to include several footer elements in a single document.

#### Example

Here's an example of a typical footer structure with some information about the website's author and a link to the main page.

```html
<footer>
  <p>Author: Ironhack</p>
  <p><a href="https://ironhack.com">Visit Our Website</a></p>
</footer>
```

### Nav

A `<nav>` element is used to include the main navigation links on a website. Not all navigation links have to be inside here; `<nav>` elements are typically used inside a navbar.

#### Example

A `<nav>` element is usually found in a website's `<header>`. Here's a typical navigation structure that might be included in an informational site:

```html
<nav>
  <a href="/">Home</a>
  <a href="/about">About</a>
  <a href="/services">Services</a>
  <a href="/contact">Contact</a>
</nav>
```

### Section

The `<section>` tag is one of the most generic semantic elements in HTML5. It is used to define a specific section inside a document, which involves a group of content that's thematically related.

For example, a website can have a `<section>` in the introductory part, another one for the 'About Us' section, and a final one with contact information inside.

#### Example

This is a document with two different sections:

```html
<section>
  <h1>This is my title 1</h1>
  <p>
    Aenean et congue est. Interdum et malesuada fames ac ante ipsum primis in
    faucibus. Donec facilisis, augue id egestas viverra, nisl diam maximus
    justo, ut laoreet lectus diam vitae eros. Cras pellentesque leo sem, et
    suscipit leo eleifend vel.
  </p>
</section>

<section>
  <h1>This is my title 2</h1>
  <p>
    Pellentesque id sagittis elit, vitae ullamcorper velit. Integer sed arcu
    vitae sem tempus feugiat vel et ipsum.
  </p>
</section>
```

### Article

The `<article>` semantic element is used to point to independent, self-contained content.

An article should make sense on its own, and it should be possible to distribute it independently from the rest of the document.

Examples of where the `<article>` element can be used:

- Forum posts
- Blog posts
- User comments

#### Example

Here's an HTML excerpt including two independent articles:

```html
<article>
  <h2>Article 1</h2>
  <p>
    Mauris ac est at nulla porta luctus. Donec commodo efficitur eros. Aenean
    accumsan iaculis eros rutrum maximus. Vestibulum ante ipsum primis in
    faucibus orci luctus et ultrices posuere cubilia curae.
  </p>
</article>

<article>
  <h2>Article 2</h2>
  <p>
    In id mi et turpis bibendum rhoncus vitae vitae purus. Sed a felis placerat,
    pulvinar elit et, pharetra risus. Aenean cursus ut neque vitae auctor.
  </p>
</article>
```

### Other semantic elements

Here are some other semantic elements and a brief description of their use:

| <b>Tab</b>  | <b>Description</b>                                    |
| ----------- | ----------------------------------------------------- |
| `<aside>`   | Defines content in a "sidebar" section                |
| `<details>` | Gives additional information that the user can toggle |
| `<figure>`  | Used to include self - contained, graphic content     |
| `<mark>`    | Defines marked/highlighted text                       |

## Example

Semantic elements can be used in many different ways. It is generally considered a good practice to use them to structure a web application whenever possible.

Here's an example that uses the `<article>` tag with a `<header>` inside of it:

```html
<article>
  <header>
    <h1>This is a sample article</h1>
    <p>Lorem ipsum</p>
  </header>
  <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus ultricies
    congue augue in laoreet. Nunc in tempor magna. Nunc nec interdum leo.
  </p>
</article>
```

## Summary

In this lesson we've learned what Semantic Elements are in HTML and how to use them.

We've also taken a look at some of the ones that are most commonly used in modern web applications.

## Extra resources

- [W3Schools Official Documentation](https://www.w3schools.com/html/html5_semantic_elements.asp) - A very comprehensive explanation of most HTML semantic elements and what to use them for.
- [FreeCodeCamp article on Semantic Elements](https://www.freecodecamp.org/news/semantic-html5-elements/) - This article gives additional information on some semantic elements and how to use them.
