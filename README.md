## MTM6230 - Client-Side Web Development

### Keeping Things Accessible
##### Submitted By: Parth Chauhan | 040957345
##### Due Date: May 12, 2019

| No. | Accessibility Problem | Solution |
| --- | --- | --- |
| 1 | Not used schemantic elements of HTML | Use of schemantic HTML elements like `<header></header>`, `<aricle></article>`,  `<footer></footer>`, `<nav></nav>`, etc. |
| 2 | Text alternative of images are missing | Use `alt` attribute of `<img>` for setting alternatives. for example, `<img src="images/2019-01-11_06-05-41.png" alt="WebAIM Checklist">`. |
| 3 | Focus Manually turned off | Removing or commenting `*:focus {outline: none;}` in CSS will turn focus on |
| 4 | Labels for input are missing | Including `<label>` before `<input>` will generate labels for inputs.|
| 5 | Website is not enough responsive to view correctly on smaller device | Using `@media` in CSS website can be converted in Responsive Website. |
| 6 | Sub menu opens even after not hover on menu item | Instead of `opacity: 0;` `display: none;` or `visibility: hidden;` must be used. |
| 7 | Monochromatic background color and paragraph font color | Using `Shades of Black` for fonts instead of using light grey color. | 
| 8 | Dead navigation links | Adding hyperlinks in `href` attribute of `<a>` will make navigation work. |
| 9 | Inappropriate use of Accessible Rich Internet Application | Using `role` attribute inside `<div>` will work. Only using `class` will not make ARIA. |
| 10 | Tab Flows over sub menu. That results in consistently pressing tab key but cannot determine which section is selected | Using proper `display` options this can be solved. |
| 11 | Dead Flow after filling form. No Submit Button is there. | Adding `Submit` button at the end of form this can be overcomed. |
