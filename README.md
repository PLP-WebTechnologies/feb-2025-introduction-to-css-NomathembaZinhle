//1. Create the style.css file
/* style.css */

/* Apply styling to the body element */
body {
  font-family: Arial, sans-serif; /* Use a different font */
  background-color: #f4f4f4; /* Set a light background color */
  color: #333; /* Set text color */
  margin: 0;
  padding: 0;
}

/* Style elements with the 'header' class */
.header {
  background-color: #333; /* Dark background */
  color: #fff; /* White text color */
  padding: 20px;
  text-align: center;
}

/* Style elements with the 'image' class */
.image {
  width: 100%; /* Make the image span full width */
  max-width: 600px; /* Limit maximum width */
  display: block; /* Ensure the image is a block-level element */
  margin: 20px auto; /* Center the image horizontally */
}

/* Style the element with the ID 'content' */
#content {
  padding: 20px;
  margin: 20px;
  border: 2px solid #ccc; /* Add a border around the content */
  background-color: #fff; /* Set the background color of the content section */
}
//2. Link the style.css file to your HTML document
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Webpage</title>
    <!-- Link to the external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Apply class 'header' to a div element -->
    <div class="header">
        <h1>Welcome to My Webpage</h1>
    </div>

    <!-- Apply class 'image' to an image element -->
    <img src="https://via.placeholder.com/600" alt="Placeholder Image" class="image">

    <!-- Apply ID 'content' to a section element -->
    <div id="content">
        <h2>About This Webpage</h2>
        <p>This webpage demonstrates the use of CSS styling with external files. It includes elements styled with selectors like classes and IDs.</p>
    </div>
</body>
</html>


