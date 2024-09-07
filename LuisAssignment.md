Web Development Foundation (WDF)’s Assignments
I.Module 1: Introduction to Web Development

What is web development?
Web development is the process of building and maintaining websites.
What is a website? And explain the differences between static and dynamic websites.
A website is a collection of web pages under a domain name.Static shows the same content to every user. Dynamic changes content based on user interaction or data.
Explain the differences of web design, front-end and back-end development.
Web design focuses on visual layout and user experience.Front-end development builds the part users see and interact with (HTML, CSS, JavaScript).Back-end development manages server-side logic, databases, and APIs.
II.Module 2: HTML

What does HTML stand for? And Explain what HTML is and why we use it?
HTML stands for HyperText Markup Language. It is the structure of web pages. We use it to define content and layout.
Explain the HTML structure. E.g. what is and how many parts in HTML structure and so on.
HTML has two main parts:
Head: Contains meta data and links to assets and resources.
Body: Contains the visible content.
What are the differences between HTML tags and HTML elements?
Tags are the code used to define elements (e.g., <p>, <div>).
Elements are the actual content within the tags.
Describe at least 10 HTML tags and explain their definition.
<html>: Defines the root of an HTML document.
<head>: Contains metadata and links.
 <body>: Holds visible content.
<h1> to <h6>: Define headings.
 <p>: Defines paragraphs.
<div>: Defines a section or container.
<a>: Creates hyperlinks.
<img>: Embeds images.
 <ul>: Creates unordered lists.
 <form>: Defines a form for user input.

What is HTML Attribute?
Attributes provide additional information about HTML elements (e.g., src, href).
What is a Comment and why do we use it?
Comments are notes in the code that don't appear on the page. We use them to explain code.
Explain the usage of _self and _blank target attributes.
self: Opens the link in the same tab.
blank: Opens the link in a new tab.
Give a brief explanation of the HTML table.
HTML tables display data in rows and columns using <table>, <tr>, <td>, and <th> tags.
How many list elements in HTML and what are they?
There are 2 list elements in HTML and they are  ordered lists: <ol> and unordered lists: <ul>
Explain the differences between inline and block elements?
Inline: Takes up only as much space as needed (e.g., <span>).
Block: Takes up the full width available (e.g., <div>).



What are HTML form elements? Provide at least 5 HTML form elements with particular definition.
HTML form elements collect user input. The `<input>` tag allows text entry, `<textarea>` handles longer text, and `<select>` creates dropdowns. The `<button>` tag adds clickable buttons, while `<label>` links text to form elements for better usability.
What are the attributes of HTML video and audio elements and their definition?
HTML video and audio elements have important attributes. The `src` attribute defines the media file's location, while `controls` add play and volume options. `Autoplay` starts the media automatically, `loop` repeats it, and `muted` plays it without sound initially.
III.Module 3: CSS

What does CSS stand for? And Explain what CSS is and why we use it?

CSS stands for Cascading Style Sheets. It controls the look and layout of web pages.

How many ways can we use CSS in HTML documents and which one is the best?

There are 3 ways we can use CSS in HTML documents they are Inline, Internal, External.
In my opinion, external is best for maintaining larger projects.

Give a brief explanation of CSS syntax.

CSS syntax consists of a selector and a declaration block.  e.g., 
h1 { 
color: blue; 
}

What are selectors?

Selectors target HTML elements to apply styles e.g.,
p { 
}

To make an element bordered, what properties are needed?

To make an element bordered, we need to use border-width, border-style, border-color.

Explain the differences between padding and margin.

Padding is a space inside the element and margin is a space outside the element.

What is a box model and why do we need to use box-sizing?

The box model defines spacing and sizes. box-sizing: border-box ensures consistent sizing.

Describe the text properties and their definition?

Text properties in CSS control the appearance of text. The `font-size` defines the size of the text, while `color` sets the text color. `text-align` determines the alignment (left, right, center), and `line-height` adjusts the space between lines of text. `font-weight` changes the text's thickness, such as bold or normal.

When do we use display in CSS and what are the css display properties and their definition?

We use the `display` property in CSS to control how an element is rendered. `block` makes the element take up the full width, `inline` allows it to take up only as much space as needed, and `inline-block` combines both behaviors. `flex` and `grid` enable advanced layout structures, while `none` hides the element from the page.

When do we use position and provide its properties and their definitions.

We use the `position` property in CSS to control the placement of elements. `static` is the default and positions elements in the normal flow. `relative` positions elements relative to their normal position. `absolute` places elements relative to the nearest positioned ancestor. `fixed` keeps the element in the same place even when scrolling, and `sticky` toggles between relative and fixed based on the scroll position.

What are translate and scale in 2D transform?

Translate moves an element and scale resizes an element.

What is transition and when we have to use it?

A transition in CSS allows changes to CSS properties to happen smoothly over a specified duration. We use transitions when we want to animate changes, like color, size, or position, to create a gradual effect instead of an instant change, often during hover or focus interactions.

What is object fit in CSS and why do we use it?

`Object-fit` in CSS controls how content, like images or videos, fits within its container. It allows you to specify whether the content should cover the container, fit within it, or maintain its aspect ratio, helping to ensure a consistent and visually appealing layout.

What is flex box and what property do we have to use to make elements side by side?

Flex box is a CSS layout tool that arranges elements in a container. To place elements side by side, use `display: flex` on the container.Also you can manage flex directions upon what you wish for  your website. (e.g., column or row) 

What is responsive design? And provide some properties for implementing responsiveness in CSS.

Responsive design ensures that a website looks and functions well on various devices and screen sizes. It adapts the layout and content to fit different viewport. Key CSS properties for implementing responsiveness include:
- `media queries`: Apply different styles based on device characteristics (e.g., `@media (max-width: 600px)`).
- `flexbox`: Arrange elements dynamically with `display: flex`.
- `grid layout`: Create flexible grid-based layouts with `display: grid`.
- `width` and `max-width`: Control element sizes relative to the viewport.
