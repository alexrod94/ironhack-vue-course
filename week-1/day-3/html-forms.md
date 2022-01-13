<!-- ![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)
# HTML | Form Tag -->

## Learning goals

After this lesson, you will know:

- how to create an HTML form,
- what are and what do form attributes (_action_ and _method_),
- what is a label used for,
- what are different types of inputs that can be used in forms, and
- how to _submit_ forms (add the button and define its type).

## Introduction

In this lesson, you will learn what HTML forms are and how to create them. You will know how to distinguish between different types of **input fields** you can use in forms. Finally, you will learn how to add labels and buttons to the form, so you process the data from the form.

## The `form` tag

:::success
The **`<form>`** tag:

- is a block level element.;
- represents a form;
- has nested inputs, labels, and buttons that will be used to retrieve data from the user and then process that data;
- has the structure:

```html
<form action="" method="">
  <!-- labels and inputs to be added here -->
</form>
```

:::

You can see an example here:

<iframe height='265' scrolling='no' title='bgQRqd' src='//codepen.io/ironhack/embed/bgQRqd/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/bgQRqd/'>bgQRqd</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

As we see, `<form>` tag has two mandatory [**attributes**](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form#Attributes):

- `action` - the form's task, when we get to backend development later, is to take input from a user and send it to a server. The `action` points to what URL the form will send its data to. **The default action of a form is to submit the data to the same page it is currently on.** We will focus in on this topic more when we get to backend development.
- `method` - refers to different ways form can be submitted. Later, when we get to the backend, you will know much more about HTTP methods, but for now, keep in mind that method can be _get_ or _post_. When to use one or the other will be explained later.

## The `label` tag

:::success
The **`label`** tag:

- is an inline element;
- represents a caption for input fields;
- has semantic and functional relation with the associated `input` field.
  :::

<iframe height='265' scrolling='no' title='xgMBXd' src='//codepen.io/ironhack/embed/xgMBXd/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/xgMBXd/'>xgMBXd</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

### The relation between `label` and `input`

As you can see in the previous CodePen, **the `id` input attribute is associated with the label `for` attribute**.

This is not just a semantic relation, but it has a simple functionality: _you can put the focus on input by clicking on the input or the associated label_. Try it!

We showed you a lot of different types of input types in this example, so now let's talk a bit about inputs and types of inputs.

:::success
**`<label>`** tag is not mandatory; you can use _input_ tag without it.
:::

## Input tags

:::success
The **`input`**:

- is an inline element;
- has the following structure (the order of attributes is flexible):

```html
<input type="" name="" id="" />
```

- allows to user to enter different types of data;
- has different types: - text, - textarea, - number, - email, - radio, - checkbox, - select.
  :::

Let's talk about different types.

### Type: `text`

The **text** `input` (`<input type="text" />`) allows to a user to fill any type of text. `type=text` is also the default type of input.

<iframe height='265' scrolling='no' title='jydxgY' src='//codepen.io/ironhack/embed/jydxgY/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/jydxgY/'>jydxgY</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

### Type: `textarea`

The **textarea** type of `input` also allows the user to submit the text.

<iframe height='265' scrolling='no' title='VPgEav' src='//codepen.io/ironhack/embed/VPgEav/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/VPgEav/'>VPgEav</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

The difference between `<input type="text">` and `<textarea></textarea>` is that `textarea` allows free form typing on multiple lines. It is usually used when there is a need for entering descriptions of products or comments on a blog.

The **text** `input` accepts a single line with a max length of 255 characters.

The size of a textarea is modified using the attributes **`rows`** and **`cols`**.
:::warning
_You should not use CSS to resize a textarea, because the text inside will be off-center_.
:::

### Type: `number`

The **number** type of `input` (`<input type="number" />`) allows to a user to enter numbers. Additionally, when you click on this type of input, two arrows will be added to the input so the user can increase or decrease the number.

If you try typing letters or special characters into the input field, which type is _number_, you won't be able to do it. This type of input accepts only numbers.

<iframe height='265' scrolling='no' title='QdYxLO' src='//codepen.io/ironhack/embed/QdYxLO/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/QdYxLO/'>QdYxLO</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

### Type: `email`

The **email** type of `input` (`<input type="email" />`) allows a user to input text, specifically text in the format of an email.

When the form is sent, it validates if the input contains a valid email.

<iframe height='265' scrolling='no' title='mRvGNP' src='//codepen.io/ironhack/embed/mRvGNP/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/mRvGNP/'>mRvGNP</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

:::info
If you try to input just some random text which doesn't have `@` in it and you hit `Save` button, you will get a warning:

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_429c3e46628807df529220844779b835.png)
:::

This is also known as the **frontend form validation** (more about this during the course).

### Type: `password`

The **password** type is very used when working with confidential data. Anything you type in the field with type password won't be visible to outsiders, while you are typing.

Check the example:

<iframe height="265" style="width: 100%;" scrolling="no" title="password-type-example" src="//codepen.io/ironhack/embed/EJOyOd/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/ironhack/pen/EJOyOd/'>password-type-example</a> by Ironhack
  (<a href='https://codepen.io/ironhack'>@ironhack</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

You can see that anything you type gets turned into black circles.

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_64dddef33b5fb4f6c00790eeaaca4863.png)

### Type: `radio`

The **radio** `input` field (`<input type="radio"/>`) allows the user to choose only one of the multiple choices by clicking on one of the circles. As soon as you click on some other given option, that option gets picked, and the other one is not anymore.

<iframe height='265' scrolling='no' title='QdYZGm' src='//codepen.io/ironhack/embed/QdYZGm/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/QdYZGm/'>QdYZGm</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

**Attributes**

- `type` - "radio";
- `value` - represents the value that will be sent to the server (_more about this later in the course_);
- `name` - as you can see, all three buttons have the same name, which means that this attribute is used to gather the elements to the same group. If you have multiple radio input groups, they will have different names.

<iframe height='265' scrolling='no' title='Radio - Two Groups' src='//codepen.io/ironhack/embed/EmeGae/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/ironhack/pen/EmeGae/'>Radio - Two Groups</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

### Type: `checkbox`

The **checkbox** `input` field (`<input type="checkbox"/>`) allows to a user to select one or more options. It is used with two different purposes:

- Select multiple options:

  <iframe height='265' scrolling='no' title='LxqXeO' src='//codepen.io/ironhack/embed/LxqXeO/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/LxqXeO/'>LxqXeO</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
  </iframe>

- Mark an option as selected:
  <iframe height='265' scrolling='no' title='BpMGrb' src='//codepen.io/ironhack/embed/BpMGrb/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/BpMGrb/'>BpMGrb</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
  </iframe>

**Attributes**

- `type` - "checkbox";
- `value` - represents the value that will be sent to the server (_more about this later in the course_);
- `name` - represents the group of inputs that belong to the same field.

### Type: `select`

The **select** `input` field (`<select> ... </select>`) allows the user to select one option from a dropdown list.

Each of the options are represented by an `option` tag (`<option> ... </option>`).

<iframe height='265' scrolling='no' title='OWddQO' src='//codepen.io/ironhack/embed/OWddQO/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/OWddQO/'>OWddQO</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

As you can see, each option is wrapped by the `select` input, so it is not necessary to add the `name` attribute to the options. The value is required, though, as this will eventually be the value sent to the server.

### The `placeholder` property

Inputs can have one more property - _placeholder_. Anything you want to be displayed in the input field can be added to this property.

Check the example:

<iframe height="265" style="width: 100%;" scrolling="no" title="placeholder-example" src="//codepen.io/ironhack/embed/WWYxJR/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/ironhack/pen/WWYxJR/'>placeholder-example</a> by Ironhack
  (<a href='https://codepen.io/ironhack'>@ironhack</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

## Buttons

:::success
The **`button`** tag is an inline element.
:::

There are different ways to represent a button in HTML5.

- You can use the `input` tag.
  ```html
  <input type="button" value="Click me!" />
  <input type="submit" value="Click me!" />
  ```
- You can use the `button` tag.
  ```html
  <button type="submit">Click me!</button>
  <button type="button">Click me!</button>
  ```

Whichever way you choose, the main difference is the **type** of the buttons:

- `submit` - This button type is normally used inside forms to send the data that the form contains.
- `button` - This button type is used as a general button for any other purpose when it is clicked, such as playing a video, or displaying a popup.

### The input button

The `input` tag which type is `"button"` (`<input type="button">`) is an element that represents just a simple button and, by default, does nothing when you click on it.

<iframe height='265' scrolling='no' title='EZJyOg' src='//codepen.io/ironhack/embed/EZJyOg/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/EZJyOg/'>EZJyOg</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

**Attributes**

- `type` - "button";
- `value`- indicates the text that will be shown in the button.

### Type: submit button

The **submit** `input` (`<input type="submit">`) is an element that represents a simple button. By default, it does nothing when you click on it unless it is located in a form. If it is part of the form, it will redirect (change the page) to the one that is stated in the form's _action_ attribute.

- Example: outside of the form

<iframe height='265' scrolling='no' title='qRwaZp' src='//codepen.io/ironhack/embed/qRwaZp/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/qRwaZp/'>qRwaZp</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

- Example: inside the form

<iframe height="265" style="width: 100%;" scrolling="no" title="input-submit" src="//codepen.io/ironhack/embed/axQNgV/?height=265&theme-id=0&default-tab=html,result" frameborder="no" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/ironhack/pen/axQNgV/'>input-submit</a> by Ironhack
  (<a href='https://codepen.io/ironhack'>@ironhack</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

:::warning
When you click on save, you will be redirected to _404_ since "/some-url" is a non-existing page.
:::

**Attributes**

- `type` - "submit";
- `value` - represents the text that will be shown in the button. By default, the value is "Submit".

### The button tag

The `button` tag (`<button>Text</button>`) is an element that represents a simple button. It can have the `type` attribute set to `button` or `submit`. The default type is `submit` in most of the browsers. By default, it does nothing when you click on it.

<iframe height='265' scrolling='no' title='ygragJ' src='//codepen.io/ironhack/embed/ygragJ/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/ygragJ/'>ygragJ</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

### Button behavior inside a form

By default, when you place a `submit` button, `input` or `button` inside a form, it will try to send the form data to a URL through the `action` attribute. If there is no action specified, it will be sent to the current page.

Try clicking these two buttons to see the difference, and feel free to change the types and values of each button.

<iframe height='265' scrolling='no' title='egodVR' src='//codepen.io/ironhack/embed/egodVR/?height=265&theme-id=0&default-tab=html,result&embed-version=2' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='http://codepen.io/ironhack/pen/egodVR/'>egodVR</a> by Ironhack (<a href='http://codepen.io/ironhack'>@ironhack</a>) on <a href='http://codepen.io'>CodePen</a>.
</iframe>

As you can see, when clicking on "Send data!" the page gets refreshed/reloaded, since the form is submitting to the same page.

## Quick reference

In the table below, you can find a quick reference with the controls, their HTML syntax, and a brief description about how to use them in our forms:

| Name         | HTML                                | Description                                                                   |
| ------------ | ----------------------------------- | ----------------------------------------------------------------------------- |
| Form         | `<form action="" method=""></form>` | Sends user data to the server                                                 |
| Text Input   | `<input type="text">`               | Allows a user to enter text                                                   |
| Textarea     | `<textarea></textarea>`             | Allows a user to enter multi-line text                                        |
| Number Input | `<input type="number">`             | Allows a user to enter numbers                                                |
| Email Input  | `<input type="email">`              | Allows a user to enter an email                                               |
| Radio button | `<input type="radio">`              | Allows the user to mark one of multiple choices                               |
| Checkbox     | `<input type="checkbox">`           | Allows the user to select one or more options                                 |
| Select       | `<select></select>`                 | Allows the user to select one option from a dropdown list                     |
| Label        | `<label></label>`                   | Represents a caption for an HTML input                                        |
| Button       | `<button></button>`                 | Represents a button that will perform an action on the page, or submit a form |

## Summary

In this lesson, you have learned what a form is, when and why we use it. You also learned about the different types of inputs you can use in a form, including buttons as inputs or as tags.

Finally, you have learned all that you need about labels and how these tags are related to inputs.

## Extra resources

- [The button element](http://web.archive.org/web/20110721191046/http://particletree.com/features/rediscovering-the-button-element/)
- [Difference between anchors, inputs and buttons](https://davidwalsh.name/html5-buttons)
