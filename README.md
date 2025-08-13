Analog Clock Project
📌 Overview
This is a simple analog clock built using HTML, CSS, and JavaScript.
It displays the current time with hour, minute, and second hands, styled in a modern look with smooth rotation updates every second.

📂 Project Structure
bash
Copy
Edit
.
├── index.html   # Main HTML file containing the clock structure
├── style.css    # Styling for the clock UI
├── main.js      # JavaScript logic for updating the clock
└── clk.jpg      # Favicon (clock image)
✨ Features
Real-time updating clock.

Smooth rotation for hour, minute, and second hands.

Stylish design with colored hands:

Red for hours.

Blue for minutes.

White for seconds.

Responsive and centered layout.

🛠️ How It Works
HTML (index.html)

Creates the structure for the clock, including 12 numbered positions and three hand elements for hours, minutes, and seconds.

CSS (style.css)

Styles the clock to be circular, adds shadows, and positions the numbers and hands correctly.

Uses CSS custom properties (--clr, --i) for dynamic coloring and rotation.

JavaScript (main.js)

Fetches the current time using Date().

Calculates rotation angles:

Hours → 30 * hh + mm / 2

Minutes → 6 * mm

Seconds → 6 * ss

Updates the transform: rotate() property of each hand every second using setInterval().

▶️ How to Run
Download all files (index.html, style.css, main.js, and clk.jpg).

Make sure they are in the same folder.

Open index.html in a web browser.

