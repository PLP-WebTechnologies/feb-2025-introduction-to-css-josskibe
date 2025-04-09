# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨




html file - index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Intro to CSS</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header id="main-header">
    <h1 class="title">Welcome to My Styled Page</h1>
  </header>

  <section class="content">
    <p>This is a paragraph styled with CSS. We will play with fonts, colors, spacing, and borders.</p>
    <img src="https://via.placeholder.com/200" alt="Sample Image" class="styled-image">
  </section>

  <footer>
    <p class="footer-text">Happy Coding! 💻✨</p>
  </footer>
</body>
</html>



css external file - style.css


/* ID Selector */
#main-header {
  background-color: #4CAF50;
  color: white;
  padding: 20px;
  text-align: center;
}

/* Class Selector */
.title {
  font-family: 'Georgia', serif;
  font-size: 2rem;
  margin-bottom: 10px;
}

/* Element Selector */
p {
  font-family: 'Arial', sans-serif;
  font-size: 1.1rem;
  line-height: 1.6;
  margin: 20px;
  padding: 15px;
  border: 1px solid #ccc;
  background-color: #f9f9f9;
}

/* Style an Image */
.styled-image {
  display: block;
  margin: 20px auto;
  border: 5px solid #555;
  border-radius: 10px;
  max-width: 100%;
}

/* Footer styling */
.footer-text {
  text-align: center;
  font-size: 0.9rem;
  color: #888;
  margin-top: 30px;
}
