<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Google Drive Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f1f1f1;
    }

    /* Content Container */
    .content-container {
      margin-bottom: 60px; /* To prevent content from overlapping with bottom nav */
    }

    /* Page Sections */
    .section {
      display: none;
    }

    .active {
      display: block;
    }

    iframe {
      width: 100%;
      height: 600px;
      border: none;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .header {
      text-align: center;
      margin-bottom: 30px;
    }

    .header h1 {
      font-size: 36px;
      color: #333;
      line-height: 1.4;
    }

    /* Gallery Section */
    .gallery-title {
      text-align: center;
      margin-bottom: 20px;
      font-size: 24px;
      color: #555;
    }

    /* Gallery Container */
    .gallery-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); /* Create dynamic columns */
      gap: 20px; /* Space between columns */
      padding: 20px;
    }

    .gallery-item {
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      padding: 10px;
      text-align: center;
    }

    /* Divider Styling */
    hr {
      border: 0;
      height: 1px;
      background-color: #ccc;
      margin: 20px 0;
    }

    /* Bottom Navigation Styles */
    .bottom-nav {
      position: fixed;
      bottom: 0;
      width: 100%;
      background-color: #333;
      display: flex;
      justify-content: space-around;
      padding: 10px 0;
      box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.2);
    }

    .bottom-nav a {
      color: white;
      text-decoration: none;
      font-size: 16px;
      text-align: center;
      padding: 5px 10px;
    }

    .bottom-nav a:hover {
      background-color: #555;
      border-radius: 5px;
    }

    @media (max-width: 600px) {
      .bottom-nav a {
        font-size: 14px;
      }
    }

    /* Button Styling */
    .nav-buttons {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-bottom: 20px;
    }

    .nav-buttons a {
      background-color: #2D92E0;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-size: 18px;
    }

    .nav-buttons a:hover {
      background-color: #1c7bb6;
    }

    /* Contact Section Styling */
    .contact-column {
      display: flex;
      flex-direction: column;
      align-items: center;
      background-color: #f9f9f9;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      margin-top: 20px;
      max-width: 400px;
      margin-left: auto;
      margin-right: auto;
    }

    .contact-info {
      text-align: center;
      font-size: 14px;
      color: #555;
      margin: 10px 0;
    }

    .contact-column h2 {
      font-size: 24px;
      color: #333;
      margin-bottom: 10px;
    }

    .contact-column p {
      font-size: 18px;
      color: #555;
      line-height: 1.5;
    }
  </style>
</head>
<body>
  <!-- Content Container -->
  <div class="content-container">
    <!-- Gallery Section -->
    <div id="gallery" class="section">
      <div class="gallery-title">
        <p>Explore My Photos and Videos</p>
      </div>

      <!-- Navigation buttons for Photos and Videos -->
      <div class="nav-buttons">
        <a href="javascript:void(0);" onclick="loadContent('photos')">Photos</a>
        <a href="javascript:void(0);" onclick="loadContent('videos')">Videos</a>
      </div>

      <!-- Divider or Text in Gallery -->
      <hr>
      <p style="text-align: center; color: #000; font-size: 18px; font-weight: bold;">Deepak Studio - Capturing moments in time</p>

      <!-- Gallery Container with Grid Layout -->
      <div class="gallery-container">
        <!-- Each gallery item wrapped in a .gallery-item -->
        <div class="gallery-item">
          <iframe id="gallery-frame" src="https://drive.google.com/embeddedfolderview?id=1e3OEyaST352zu7Jbap166vWLbivYSwKv#grid"></iframe>
        </div>
      </div>
    </div>

    <!-- Contact Section (Original Layout) -->
    <div id="contact" class="section">
      <div class="header">
        <h1>Simplify Services, Amplify Results</h1>
      </div>
      <p class="home-section-text">Get service instantly.</p> <!-- This text is now centered -->

      <!-- New Contact Column Section -->
      <div class="contact-column">
        <h2>Why Choose MYDGP?</h2>
        <p>MYDGP offers streamlined, scalable solutions to manage your services efficiently. Our platform is designed to help businesses maximize results with minimal effort. Get started with us today!</p>
      </div>

      <div class="header">
        <h1>Contact Me</h1>
      </div>
      <p class="contact-info">Feel free to reach out to me. Here’s how you can contact me:</p>
      <!-- Contact Information Column -->
      <div class="contact-column">
        <h2>Contact Information</h2>
        <ul class="contact-details" style="text-align: center;">
          <li>Email: <a href="https://mail.google.com/mail/?view=cm&fs=1&to=mydgp7@gmail.com" target="_blank">mydgp7@gmail.com</a></li>
          <li>Phone: <a href="tel:+917827343931">+91 78273 43931</a></li>
        </ul>
      </div>
      
      <hr>
    </div>
  </div>

  <!-- Bottom Navigation Bar -->
  <div class="bottom-nav">
    <a href="javascript:void(0);" onclick="showSection('home')">Home</a>
    <a href="javascript:void(0);" onclick="showSection('gallery')">Gallery</a>
    <a href="javascript:void(0);" onclick="showSection('contact')">Contact</a>
  </div>

  <script>
    // Function to show the selected section and hide others
    function showSection(section) {
      var sections = document.querySelectorAll('.section');
      sections.forEach(function(sec) {
        sec.classList.remove('active');
      });
      document.getElementById(section).classList.add('active');
    }

    // Function to load content into the iframe based on button click
    function loadContent(type) {
      var iframe = document.getElementById('gallery-frame');
      if (type === 'photos') {
        iframe.src = "https://drive.google.com/embeddedfolderview?id=1e3OEyaST352zu7Jbap166vWLbivYSwKv#grid"; // Photos link
      } else if (type === 'videos') {
        iframe.src = "https://drive.google.com/embeddedfolderview?id=1G-SQHcALx0QA5YUITv8V7ilgu5ge1Kmw#grid"; // Videos link
      }
    }
  </script>
</body>
 
  
  
  
  
