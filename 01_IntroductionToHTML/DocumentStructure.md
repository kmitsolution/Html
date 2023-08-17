# Document Structure
Here's a more detailed breakdown of each of these elements and their role in the HTML document structure:

**1. `<!DOCTYPE html>`:**
The `<!DOCTYPE html>` declaration appears at the very beginning of an HTML document. It informs the web browser about the version of HTML being used. In modern practice, `<!DOCTYPE html>` is used for HTML5 documents. This declaration helps browsers render the page correctly and also ensures that the document follows the rules of that specific version of HTML.

Example:
```html
<!DOCTYPE html>
```

**2. `<html>`:**
The `<html>` element is the root element of the HTML document. It encloses all other elements in the document and establishes the main structure of the webpage.

Example:
```html
<!DOCTYPE html>
<html>
    <!-- Other elements will go here -->
</html>
```

**3. `<head>`:**
The `<head>` element contains metadata about the HTML document. This metadata is not displayed on the actual webpage but provides information to the browser and search engines. It typically includes the character encoding, document title, and links to external resources like stylesheets and scripts.

Example:
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Web Page</title>
    <!-- Other metadata and links go here -->
</head>
<body>
    <!-- Content of the webpage goes here -->
</body>
</html>
```

**4. `<title>`:**
The `<title>` element is used to define the title of the HTML document. The title is displayed in the browser's title bar or tab when the page is opened. It also appears in search engine results and bookmark listings.

Example:
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Web Page</title>
</head>
<body>
    <!-- Content of the webpage goes here -->
</body>
</html>
```

**5. `<body>`:**
The `<body>` element contains the visible content of the webpage that users see in the browser. This is where you include headings, paragraphs, images, links, forms, and other elements that make up the main content of the page.

Example:
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Web Page</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <p>This is some content.</p>
    <!-- More content goes here -->
</body>
</html>
```

These fundamental elements together form the basic structure of an HTML document. They provide the foundation for organizing and presenting content on the web.
