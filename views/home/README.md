This is the view for the post list. It contains 2 parts:

- Template: in the `template.twig` file
- CSS: in the `style.css` file

View settings:

- Type: Code
- Code: `is_front_page() && !is_paged()`
- Render for: The whole page layout, including header and footer