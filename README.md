# Hamburger Menu without JS

This repository demonstrates how to create a responsive hamburger menu for your website using only HTML and CSS, without relying on JavaScript. The hamburger menu is a popular navigation pattern, especially for mobile devices, as it provides a compact way to display menu items when screen space is limited.

## Features

- Basic HTML structure for a responsive navigation bar.
- CSS styling for the hamburger icon and the navigation menu.
- Responsive design that adapts to different screen sizes
- Implementing the checkbox hack to toggle the menu without JavaScript.
- Smooth animation for opening and closing the menu

## How It Works

The hamburger menu is created using the following HTML structure:

```html
<nav>
  <input type="checkbox" id="check">
  <label for="check" class="checkbtn">
    <i class="fas fa-bars"></i>
  </label>
  <div class="nav-mobile">
    <a href="#">Home</a>
    <a href="#">About</a>
    <!-- Add more menu items here -->
  </div>
</nav>
```

The CSS styles are responsible for toggling the visibility of the menu and animating its appearance. The main CSS rules used are:

1. `.nav-mobile` is initially hidden with `display: none;`.
2. When the checkbox input is checked (`#check:checked ~ .nav-mobile`), the `.nav-mobile` element is displayed.
3. Media queries are used to adjust the styles for different screen sizes, ensuring a responsive design.

<!-- ## Demo

You can see a live demo of the hamburger menu [here](https://your-demo-link.com). -->

## Usage

To use this hamburger menu in your project, simply copy the HTML and CSS code from the repository and customize it according to your needs. You can add or remove menu items, change the styles, or adjust the breakpoints for different screen sizes.

## Resources

- [CSS Tricks - The Checkbox Hack](https://css-tricks.com/the-checkbox-hack/)
- [MDN Web Docs - Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries)
- [W3Schools - Responsive Web Design](https://www.w3schools.com/html/html_responsive.asp)

## License

This project is licensed under the [MIT License](LICENSE).