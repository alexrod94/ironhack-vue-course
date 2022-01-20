## Learning Goals

After this unit you will be able to...

- Understand what CSS Units are and which ones exist
- Know which CSS Unit to choose depending on context
- Apply CSS units to an existing layout

## Introduction to CSS Units

In order to express size, CSS allows us to use different units. Don't get confused here - we expressed all measurement units through `px` (pixels) so far, but that is just one way to do it.

There are several CSS properties that use size measurements, such as padding, margin, width, font size...

As we've already seen in previous lessons, size measurements are composed of a number followed by a length unit. `px` is one of them, but there are others that we will have to use depending on what we're doing and what we want to accomplish.

:::info
Here are three of the most used units to express size through CSS:

1. **px**
2. **em**
3. **rem**
   :::

**`px`** stands for _pixel_ which is the standard and the easiest measurement to use but might not be the best option always. Imagine the following: you set the font size of each element in HTML document and now you have to make some changes to satisfy users' needs, and you have to do it manually, one by one since each value is fixed (value of 14px will always stay 14px). If you want to have more flexibility and be able to adjust the font of children elements based on the changes in font size of the parent element, you will have to go for other two options - _em_ and _rem_.

An **`em`** is equal to the computed _font-size_ of that element's parent. For example, if there is a _div_ element with `font-size: 16px;` then for that div and for its children `1em = 16px`.
If font-size is not defined explicitly, that element will inherit it from the parent element. The inheritance continues through ancestors up until the root element. Default font-size of the root element is provided by a browser.
Let's see an example:

<iframe height="265" style="width: 100%;" scrolling="no" title="em-example" src="//codepen.io/ironhack/embed/KYbWqZ/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/ironhack/pen/KYbWqZ/'>em-example</a> by Ironhack
  (<a href='https://codepen.io/ironhack'>@ironhack</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

So let's summarize the previous example: the `parent` has font size of _20px_. The child will inherit that as a base, so `1em = 20px`, and since we set font-size to 1.5em in child class, the child element will have `20 * 1.5 = 30px` font size. Going further, child of a child will inherit 30px as a base, so it is default proportion will be `1em = 30px` and based on the rule defined in child class, the font size will be `30 * 1.5 = 45px`.

Example and its explanation is based the following article: [CSS units for font-size: px | em | rem](https://medium.com/code-better/css-units-for-font-size-px-em-rem-79f7e592bb97).

**`rem`** values are relative to the root HTML element, not to the parent element. That is, if font-size of the root element is 20px then 1 rem = 20px for all elements. If font-size is not explicitly defined in the root element, then 1rem will be equal to the default font-size provided by the browser (usually 16px). Later, during the course, you will have a chance to explore more about these. If you want to conduct your own small research and learn more beforehand, we suggest using official docs ([MDN Font size](https://developer.mozilla.org/en-US/docs/Web/CSS/font-size)) or the previously mentioned article [CSS units for font-size: px | em | rem](https://medium.com/code-better/css-units-for-font-size-px-em-rem-79f7e592bb97).

:::warning
:exclamation: Keep in mind one thing - you shouldn't ever misuse _font-size_ property: you shouldn't make paragraphs look like headings or opposite.
:::

There are default tags for each HTML element, and we can adjust it is size if needed.
