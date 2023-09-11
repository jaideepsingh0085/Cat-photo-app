# Cat-photo-app
![Screenshot 2023-09-11 190137](https://github.com/jaideepsingh0085/Cat-photo-app/assets/128147644/ff098aed-374d-46b3-b147-b4f9e04a498e)
![Screenshot 2023-09-11 190147](https://github.com/jaideepsingh0085/Cat-photo-app/assets/128147644/76ad8220-87d2-481d-8989-a2eb9446600f)
![Screenshot 2023-09-11 190200](https://github.com/jaideepsingh0085/Cat-photo-app/assets/128147644/454899b4-9d8a-4526-8116-b02a88077020)

HTML :
<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Defines the root element of an HTML document and sets the document's language to English.
<head>: Contains meta-information about the document, such as character set and viewport settings.
<meta charset="utf-8">: Specifies the character encoding used for the document as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport settings for responsive web design.
<title>: Defines the title of the web page, displayed in the browser's title bar or tab.
<link rel="stylesheet" href="./styles.css">: Links an external CSS stylesheet to style the web page.
<body>: Contains the main content of the web page.
<header class="header">: Represents a header section, typically containing introductory content.
<h1>: Defines a top-level heading, typically the main title of a page or section.
<div class="gallery">: Defines a division or container with the class "gallery" for grouping elements.
<img src="URL" alt="text">: Embeds an image with a source URL and alternative text for accessibility.

CSS :
* { box-sizing: border-box; }: Applies the box-sizing model to all elements, ensuring that padding and borders are included in the element's total width and height.
body { margin: 0; font-family: sans-serif; background: #f5f6f7; }: Sets margin, font-family, and background color for the entire page body.
.header { text-align: center; text-transform: uppercase; padding: 32px; background-color: #0a0a23; color: #fff; border-bottom: 4px solid #fdb347; }: Styles the header element, centering text, changing text to uppercase, setting padding, background color, text color, and adding a bottom border.
.gallery { display: flex; flex-direction: row; flex-wrap: wrap; justify-content: center; align-items: center; gap: 16px; max-width: 1400px; margin: 0 auto; padding: 20px 10px; }: Configures a flexbox layout for the gallery element, controlling its layout, spacing, and alignment.
.gallery img { width: 100%; max-width: 350px; height: 300px; object-fit: cover; border-radius: 10px; }: Styles the gallery images, specifying their width, maximum width, height, object-fit behavior, and border radius.
.gallery::after { content: ""; width: 350px; }: Uses a pseudo-element to add an empty element with a specified width after the gallery.
