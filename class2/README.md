# Class 2: HTML Forms and Images

## forms.html

### Overview
Exercise demonstrating how to create an HTML form for user input.

### Form Structure

```html
<form action="/action_page.php">
    <label for="fname"> First name: </label><br>
    <input type="text" id="fname" name="fname" value="john"><br>
    <label for="lname">Last name: </label>
    <input type="text" id="lname" name="lname" value="Doe"><br>
    <input type="submit" value="Submit"> 
</form>
```

### Key Elements

- **`<label>`** elements associated with input fields via `for` attribute
- **`<input type="text">`** for free-text entries (first name, last name)
- **`<input type="submit">`** to send form data
- **`action`** attribute specifying where form data is submitted (`/action_page.php`)

### Learning Points

- Form layout and field grouping
- Accessibility: linking labels to inputs
- Form submission workflow
- Default button styling

## image.html

### Overview
Exercise demonstrating CSS background image properties applied to the `body` element.

### CSS Applied

```css
body {
    background-image: url('images.jpeg')
}
```

### Features Demonstrated

- Setting a background image on the `body` element
- Default behavior: image repeats if smaller than the element
- Text color styling for headings (`<h2>`) and paragraphs (`<p>`)

### Visual Layout

- **Heading**: "Background Image" in blue text
- **Paragraph**: Explains that background images repeat by default when smaller than the container

### Learning Points

- Background image placement and tiling
- Combining background images with text styling
- Default CSS behavior for background images