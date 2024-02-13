<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Details</title>
    <style>
        body {
            background-color: #f0f2f5; /* A light gray background for a subtle look */
            color: #333; /* Dark gray color for text */
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 18px; /* Increased font size for readability */
            padding: 20px;
            margin: 0;
        }
        a {
            color: #007bff; /* Bootstrap primary blue */
            text-decoration: none; /* Removes underline from links */
        }
        a:hover {
            color: #0056b3; /* Darker blue on hover */
            text-decoration: underline; /* Adds underline on hover */
        }
        .container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap; /* Allows items to wrap in smaller screens */
            gap: 20px; /* Adds space between columns */
        }
        .social-media {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            border: 1px solid #ddd; /* Light gray border */
            border-radius: 10px; /* Rounded corners */
            box-shadow: 0 2px 4px rgba(0,0,0,0.1); /* Subtle shadow */
            background-color: white; /* White background for the social media cards */
        }
        .social-media img {
            width: 80px; /* Uniform image size */
            height: 80px; /* Uniform image size */
            margin-bottom: 10px; /* Adds space below the image */
            object-fit: cover; /* Ensures images cover the area nicely */
        }
        p {
            margin: 5px 0; /* Reduces space around paragraphs */
        }
    </style>
</head>
<body>
    <h1>Contact Details</h1>
    <div class="container">
        <div class="social-media">
            <img src="in.WEBP" alt="LinkedIn">
            <p>Linkedin: <a href="https://www.linkedin.com/in/varad-sarda-5b525b287" target="_blank">@varad_sarda</a></p>
            <img src="inst.WEBP" alt="Instagram">
            <p>Instagram: <a href="https://instagram.com/varad_1305" target="_blank">@varad_1305</a></p>
        </div>
        <div class="social-media">
            <img src="wp.JPG" alt="WhatsApp">
            <p>WhatsApp: <a href="https://wa.me/7875912744" target="_blank">+91 7875912744</a></p>
            <img src="gm.WEBP" alt="Gmail">
            <p>Email: <a href="mailto:@varadsarda1305.com">@varadsarda1305.com</a></p>
        </div>
    </div>
</body>
</html>
