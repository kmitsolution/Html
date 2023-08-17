# HTML Basic Structure
The basic structure of an HTML document consists of several essential elements that provide information about the document, its content, and how it should be displayed in a web browser. Here's a breakdown of the basic structure:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Document Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

Let's go through each part:

1. `<!DOCTYPE html>`: This declaration specifies the document type and version of HTML being used. In this case, it's HTML5. It's always placed at the very beginning of the document.

2. `<html>`: This is the root element of the HTML document. It encloses all other elements in the document. The `lang` attribute can be used to specify the language of the content.

3. `<head>`: The `<head>` section contains metadata and links to external resources. It doesn't display content directly on the page but provides information about the document.

   - `<meta charset="UTF-8">`: Specifies the character encoding for the document. UTF-8 supports a wide range of characters from different languages.
   - `<title>`: Sets the title of the web page, which is displayed in the browser's title bar or tab.

4. `<body>`: The `<body>` section contains the visible content of the web page that users see in the browser.

   - <b>Content:</b> This is where you place headings, paragraphs, images, links, forms, and other content that you want to display on the web page.
   - <b>Comments:</b> `<!-- Comment goes here -->` is used to add comments that are not displayed on the page but can provide explanations for the code.

### Example
Here's a simple example with some content added:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First Web Page</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is a paragraph of text.</p>
    <a href="https://www.example.com">Visit Example</a>
    <img src="image.jpg" alt="Description of the image">
</body>
</html>
```

In this example, the page displays a heading, a paragraph of text, a hyperlink, and an image. This is a basic HTML structure that you can build upon to create more complex web pages.
