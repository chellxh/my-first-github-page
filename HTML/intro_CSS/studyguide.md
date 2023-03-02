What does CSS stand for?

- Cascading Style Sheet

Define the parts of the following CSS rule:

- h1 = selector
- color and font-size = property
- purple and 36px = value
- h1 will be purple and 36 px font size

  h1 {
  color: purple;
  font-size: 36px;
  }

How does a declaration block differ from a declaration?

- declaration block is everything btw {}
- declaration is what are the property-value pairs

Using technical language, describe how the following CSS would affect an HTML page. Feel free to look up the properties and values.

- there will be a (property) border under every h2 - (value) 3px as size and red

  h2 {
  border-bottom: 3px solid red;
  }

Using technical language, describe how the following CSS would affect an HTML page. Feel free to look up the properties and values.

- every paragraph will have green text and font in helvetica or serif if helvetica is not available.

  p {
  color: green;
  font-family: Helvetica, serif;
  }

Using technical language, describe how the following CSS would affect an HTML page. Feel free to look up the properties and values.

- background property makesthe background yellow(value)
- height property makes height 200 px (value)
- overflow property when an elemts contents are too big to fit in its block formatting context, clips content if necessary to fit also allows a scrollbar to show preventing scrollbar from appearing and disappearing as content changes

  p {
  background: yellow;
  height: 200px;
  overflow: scroll;
  }

Using technical language, describe how the following CSS would affect an HTML page. Feel free to look up the properties and values.

- both declaration blocks affect the same selector, h1 any properties that are duplicated will get over written making h1 color red, fontsize 40 px, font-weight bold

  h1 {
  color: red;
  font-size: 10px;
  }

  h1 {
  font-size: 40px;
  font-weight: bold;
  }

What are the three ways you can connect CSS to an HTML page?

- link element - 2 attributes: rel & href
- inline style - add style to tag within HTML file
- style element - inside <head> element of page

What attributes are required in creating a link element?
rel - style name & href - link to css path

Why is creating an external stylesheet preferred to the other two methods?

- can link same css to other pages
- can easily update and locate css
