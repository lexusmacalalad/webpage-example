# A website built from scratch

- HTML
- CSS
- Wireframes
- git
- Markdown

## HTML

We started creating the skeleton (! + Enter in VSCode), then we created the header and linked the CSS and the other two big containers, main and footer

Header contains the logo, a heading and a navigation menu

```html
  <header>
    <div class="logo">
      <p>My logo</p>
    </div>
    <h1>Personal Training</h1>
    <nav class="nav-items">
      <a href="">Training</a>
      <a href="">About Us</a>
      <a href="">Contact</a>
    </nav>
  </header>
```

## CSS

Defined primary and secondary colors, add them to the backgrounds and text colours

Flexbox for the header to align the three elements inside centred and vertically

```css
header {
  background-color: #ff9900;
  display: flex;
  flex-direction: column;
  align-items: center;
}
```