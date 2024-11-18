Time of Day Webpage

Overview

This project dynamically greets users based on the time of day. The webpage displays a different greeting message, background color, and image depending on whether it’s morning, afternoon, evening, or night. The greeting and visuals update automatically when the page loads, providing a personalized experience for the user.

Features

	•	Displays a greeting based on the current time of day:
	•	Morning (5 AM to 12 PM)
	•	Afternoon (12 PM to 6 PM)
	•	Evening (6 PM to 11 PM)
	•	Night (11 PM to 5 AM)
	•	Changes the background color and image according to the time of day.
	•	Responsive design for a better user experience on different screen sizes.

How It Works

	1.	JavaScript:
	•	The current hour is retrieved using new Date() and the getHours() method.
	•	Based on the time, the webpage assigns a corresponding greeting (Good Morning, Good Afternoon, etc.), background color, and image.
	2.	CSS:
	•	Basic styling is applied for layout, fonts, and images.
	•	The background color and image are dynamically updated based on the time of day using JavaScript.
	3.	HTML:
	•	The structure includes a greeting message, an image, and links to check the HTML and CSS code.

Files Included

	•	index.html – The main HTML file containing the structure and content of the webpage.
	•	style.css – The CSS file that contains the styling rules for the page.
	•	morning.jpg, afternoon.jpg, evening.jpg, night.jpg – The image files representing different times of day (these need to be in an images/ folder).
