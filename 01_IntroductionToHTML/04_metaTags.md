# meta Tags

meta tags contribute to both the user experience and search engine optimization (SEO) of the webpage.Below is the example meta tag.
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- meta charset to set unicode -->
    <meta charset="UTF-8" />
    <!-- viewport for the devices eg for mobile/tablet and initial scale indicates 1.0 no zoom in/out -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- This is short description on search engines -->
    <meta name="description" content="HTML Tutorial" />
    <meta name="keywords" content="html,static pages" />
    <title>HTML Tutorial</title>
  </head>
  <body></body>
</html>

```
Here’s an explanation of the meta tags used in the provided HTML example:

### 1. `meta charset`
```html
<meta charset="UTF-8" />
```
- **Purpose**: This meta tag specifies the character encoding used by the webpage. In this case, it uses `UTF-8`, which is a universal character set that supports a wide range of characters, including special characters from different languages.
- **Why it's important**: Without specifying the character set, browsers might assume a default one that may not support all characters, leading to misinterpretation of symbols or foreign letters.

### 2. `meta viewport`
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```
- **Purpose**: The viewport meta tag controls how a webpage is displayed on mobile and tablet devices. The `width=device-width` ensures the width of the page matches the width of the screen, preventing horizontal scrolling. The `initial-scale=1.0` ensures that the page is loaded without zooming in or out.
- **Why it's important**: This tag helps the page adapt to different screen sizes and ensures a better mobile viewing experience by making the layout responsive.

### 3. `meta description`
```html
<meta name="description" content="HTML Tutorial" />
```
- **Purpose**: This meta tag provides a brief description of the page’s content. This description may appear in search engine results beneath the page title, giving users an idea of what the page is about.
- **Why it's important**: It plays a crucial role in SEO (Search Engine Optimization). A well-written description can improve click-through rates from search engine results by making the page more attractive to users.

### 4. `meta keywords`
```html
<meta name="keywords" content="html,static pages" />
```
- **Purpose**: This tag lists relevant keywords related to the webpage content. These keywords are used by search engines to index the page.
- **Why it's important**: Although this tag is less significant today (many search engines no longer heavily rely on it for ranking), it can still provide some context to the page for search engines.

### Summary
The meta tags in this example serve the following functions:
- `charset`: Defines the character encoding of the page.
- `viewport`: Ensures the page is responsive and works well on mobile devices.
- `description`: Gives search engines a summary of the page’s content.
- `keywords`: Provides search engines with additional information about the page’s topic.

