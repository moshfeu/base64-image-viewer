# Base64 Image Viewer

The "Base64 Image Viewer" is a simple HTML page designed to display an image encoded in base64 format. The base64 string is extracted from the query string of the URL and used as the source for an image element.

# Usage

1. Open the HTML file (_index.html_) in a web browser.

2. Append the base64-encoded image string to the URL as a query parameter named url. For example:

```
index.html?url=YOUR_BASE64_ENCODED_STRING
```

or

```
index.html?url=data:image/png;base64,YOUR_BASE64_ENCODED_STRING
```

3. The page will load, and the image will be displayed based on the provided base64 string.
