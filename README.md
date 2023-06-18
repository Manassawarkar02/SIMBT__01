# SIMBT__01
Portfolio website using HTML & CSS

In the HTML code, we have a basic structure of an HTML document. It starts with the <!DOCTYPE html> declaration, followed by the opening and closing <html> tags. The lang attribute specifies the language of the document as English.

Inside the <head> section, we have a <meta> tag that sets the character encoding to UTF-8, ensuring proper display of special characters. The <title> element sets the title of the webpage. The <link> tag is used to include an external CSS file called "Styles.css" for styling the HTML elements. The <script> tag contains JavaScript code for the openPicture() function, which opens an image file in a new window when the logo image is clicked.

The <body> section contains the content of the webpage. The main container element is a <div> with the class "hero". Inside the hero section, we have a navigation bar defined by the <nav> element. It contains a logo image, represented by the <img> tag, which triggers the openPicture() function when clicked. The navigation bar also includes an unordered list (<ul>) with list items (<li>) that represent different sections of the website such as Home, About, Service, and Contact. Each list item contains an anchor (<a>) element that links to different HTML files, and when clicked, triggers the openPage() function (not shown in the provided code).

Below the navigation bar, there is a content section represented by a <div> with the class "content". It includes a heading (<h1>), a paragraph (<p>), and a button (<a>) for downloading a CV/resume.

In the CSS code, we have various styles defined for different HTML elements. The * selector sets margin, padding, and box-sizing for all elements to have consistent spacing and box models. The font-family is set to "Poppins", a Google Font used throughout the website. The a selector removes the default underline decoration from anchor elements.

The .hero class sets the width, height, and background image properties for the hero section. The nav class styles the navigation bar by displaying it as a flex container with items aligned horizontally. The .logo class defines the maximum height for the logo image. The styles for nav ul li and nav ul li a define the appearance of the navigation links and their hover states. The nav ul li a:after selector adds a line below the navigation links when hovered.

The .btn class styles the download button with specific colors, font size, and padding. The :hover selector changes the background color, border color, and text color of the button on hover.

The .content class positions the content section absolutely within the hero section. It sets the color, font size, and positioning for the title, heading, and paragraph elements. The .content h1 span selector sets the color for the span element within the heading.

Overall, this code creates a visually appealing personal portfolio website with a navigation bar, hero section, and content section, styled using CSS. The website provides links to different sections, a logo image, and a download button for the user's CV/resume.
