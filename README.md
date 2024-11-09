# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Do some research on semantic and non-semantic elements and share your findings. Your response should include:

- Examples of semantic and non-semantic tags
- The differences between semantic and non-semantic tags
- The benefits of using semantic tags (when possible)

### Response 1

Semantic elements are named after what they hold/represent in an HTML file.
Examples of semantic elements (<p></p>,<header></header>,<nav></nav>,<h1></h1>,...)
Non-semantic elements are not clear on what they hold in an HTML file based on the name.
Examples of non-semantic elements(<span></span>,<div></div>)
The semantic element benefits the developer when working on the file because of the clarity. It also helps other technologies like search engines be able to read the file easier.

## Prompt 2

Do some research on accessibility. What are some ways to make your website more accessible? Explain why it is important for developers to create websites that meet accessibility standards.

### Response 2

A few ways to make your website more accessible are, making sure to add alt attributes to images, keeping your navigation and layout consistent with semantic elements, and making your text clear and understandable.You can also use rem instead px. Accessibility is important because your website has to be accessible to everyone including those who have disabilities.

## Prompt 3

It is possible to add "inline" CSS styles to our html elements using the `style` attribute like so:

```html
<p style="color: red;">hello world</p>
```

While this is possible, it is a best practice to instead write styles in a separate CSS file. Provide at least one argument for why it _might_ be considered useful to write inline styles, and then provide a more compelling argument for writing styles in a separate CSS file.

### Response 3

Inline CSS can be beneficial when you are coding and want to change to a specific line of code. It also can be beneficial in debugging situations.
Making a separate file for your CSS makes your project more dynamic. It gives the developers more control and accessibility when modifying. It also makes the load time speed faster due to there being less code.

## Prompt 4

Imagine you are teaching a brand new programmer a brief lesson about the `class` and `id` attributes in HTML as well as how to use them to style elements using CSS. Your lesson should have the following components:

- An explanation of the concept of "classes" and "ids" with an analogy.
- An example of the usage using an HTML code block and a CSS code block.
- An explanation of the syntax using the terms: **attribute**, **selector**

### Response 4

IDs and Classes are attributes that categorize an element in a html file. They are like a store. Think of the IDs as a store name they can only have one. The classes are like the aisle the store can have as many as they need. Here’s an example “ <h1 id= ”walmart” class= “home-decor”>My store</h1>

## Prompt 5

The Document Object Model (DOM) API provides functions for manipulating HTML documents. It is possible to build an entire website using only JavaScript and the DOM API, however is that the best practice?

When building a website, how can I decide which content I should write using HTML/CSS and which content I should create using the JavaScript and the DOM API?

### Response 5

Creating websites with only JS and the DOM is not the best practice because takes away the accessibility. It would also be very labor-heavy compared to using HTML. When building a website you use HTML and CSS to create basic content like headings, paragraphs, and images. You also use them for styling by modifying the content's size, color, and format. You use the dom and javascript to give the content functionality. You use the make the content interactivity with website users. It creates alerts, forms, animations, etc.
