---
permalink: /
title: "👋Hello there, I'm Suchi"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<div style="display: flex; align-items: center;">
  <!-- Right Side: Text -->
  <div style="flex: 1; padding: 20px;">
    <p>
      👧 I'm a first year graduate student in the University of Salzburg at the Erasmus Mundus Joint Master (EMJM) <br>
      
      📚 My research interests are Remote Sensing, GIS, Urban Planning, Climate Change, Environmental Engineering. <br>
      
      🙋‍♀️I am also interested in assisting others on their path in the world of Digital Earth and academia.<br>
    </p>
  </div>
    <!-- Left Side: Image -->
  <div style="flex: 1; text-align: center;">
    <img src="images/logo.new.png" alt="Description" style="max-width: 100%; height: auto;">
  </div>
</div>

<!-- Bottom Bar -->
<div class="bottom-bar">
  <!-- Images -->
  <img src="images/EN Co-funded by the EU_POS.jpg" alt="Image 1" class="bottom-bar-image">
  <img src="images/PLUS Logo englisch Farbe.jpg" alt="Image 2" class="bottom-bar-image">
  <img src="images/UP_logo_stred_en.png" alt="Image 3" class="bottom-bar-image">
  
</div>



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Pages Bottom Bar</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Page Content -->
  <h1>Welcome to My GitHub Page</h1>
  <p>This is an example of a bottom bar with horizontally aligned images.</p>

  <!-- Bottom Bar -->
  <div class="bottom-bar">
    <img src="images/EN Co-funded by the EU_POS.jpg" alt="Image 1">
    <img src="images/PLUS Logo englisch Farbe.jpg" alt="Image 2">
    <img src="image3.jpg" alt="Image 3">
    <img src="images/UP_logo_stred_en.png" alt="Image 4">
  </div>

</body>
</html>


/* Bottom bar container */
.bottom-bar {
  position: fixed; /* Fix the bar at the bottom */
  bottom: 0;
  left: 0;
  width: 100%; /* Full-width bar */
  background-color: #333; /* Dark background */
  display: flex; /* Flexbox for horizontal alignment */
  justify-content: center; /* Center images horizontally */
  align-items: center; /* Align items vertically */
  padding: 10px 0; /* Padding for spacing */
  box-shadow: 0px -2px 5px rgba(0, 0, 0, 0.3); /* Shadow effect */
  z-index: 100; /* Ensure it's on top */
}

/* Style for images in the bar */
.bottom-bar img {
  height: 50px; /* Uniform height for images */
  width: auto; /* Maintain aspect ratio */
  margin: 0 15px; /* Spacing between images */
  transition: transform 0.3s ease; /* Smooth hover effect */
}

.bottom-bar img:hover {
  transform: scale(1.1); /* Slightly enlarge image on hover */
}









