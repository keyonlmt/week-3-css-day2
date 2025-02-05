# Introduction to CSS

Here is a guide to CSS (Cascading Style Sheets)! This  will teach you the basics of how to style your web pages using CSS.

## What is CSS?
CSS is used to change the appearance of a webpage. It controls things like colors, fonts, spacing, and layout. While HTML provides the structure of a page (like headings, paragraphs, and images), CSS makes it look visually appealing.

## Topics We Will Cover
1. **CSS Selectors** (Ways to select HTML elements to style)
   - Tag Selectors
   - Class Selectors
   - ID Selectors
2. **How to Add CSS to a Webpage**
   - Inline CSS
   - Internal CSS
   - External CSS
3. **Using HTML ID & Class Attributes**
   - Understanding IDs
   - Using Classes for Styling

## How to Get Started
1. **Fork this repository:**
   - Go to the GitHub page for this project.
   - Click the 'Fork' button in the top right corner to create your own copy of this project.
2. **Clone the repository:**
   - Open a terminal or command prompt.
   - Run this command to copy the project to your computer:
   ```sh
   git clone https://github.com/yourusername/css-basics.git
   ```
3. **Open the `index.html` file in a vscode.**
   - In your terminal, user `cd` to change directory into the folder you just cloned
   - Use the command `code .` to open the folder in vscode
4. **Experiment with CSS by changing the styles in the file!**
   - Modify the colors, fonts, and spacing to see how CSS works.

## Three Ways to Add CSS
### 1. Inline Styles (Directly inside an HTML element)
This method is used for quick changes but is not the best for large projects. Here is an example: 
```html
<p style="color: green; font-size: 18px;">This is an inline-styled paragraph.</p>
```
### 2. Internal Styles (Inside a `<style>` tag in the HTML file)
This method is good for applying styles to an entire page.
```html
<head>
    <style>
        p { color: blue; font-size: 16px; }
    </style>
</head>
```
### 3. External Stylesheet (In a separate `.css` file)
This method is best for keeping styles organized, especially for big projects.
```html
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
```
In `styles.css`:
```css
p {
    color: purple;
    font-size: 20px;
}
```

## Example Code
The `index.html` file includes the following example:
```html
<!DOCTYPE html>
<html>
<head>
    <title>CSS Basics</title>
    <style>
        p { color: blue; }
        .highlight { font-size: 20px; color: red; font-weight: bold; }
        #unique { background-color: yellow; padding: 10px; }
    </style>
</head>
<body>
    <h1>Welcome to CSS Basics</h1>
    <p>This is a paragraph with default styling.</p>
    <p class="highlight">This is a highlighted paragraph with bold text.</p>
    <p id="unique">This paragraph has a unique background and padding.</p>
</body>
</html>
```

## Have Fun Learning CSS!
Try changing the styles in the `index.html` file and see what happens! Play around with different colors, fonts, and layouts.
