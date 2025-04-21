# Student_Time_Table_View
This is a simple web-based application that allows students to view and filter their weekly timetable based on selected day and subject. It's built using HTML, CSS, and JavaScript.

🧩 Features
🗓️ View a complete student timetable

🔍 Filter by day (e.g., Monday, Tuesday, etc.)

📘 Filter by subject (e.g., Math, Science, etc.)

🎨 Responsive and styled interface

🛠️ Technologies Used
HTML – Structure of the webpage

CSS (student.css) – Styling for layout and colors

JavaScript (student.js) – Logic for filtering table rows based on selected options

📁 Project Structure
graphql
Copy
Edit
student-timetable-view/
├── index.html         # Main HTML file (not uploaded but assumed required)
├── student.css        # Styling for timetable and layout
├── student.js         # JavaScript for filtering logic
└── README.md          # Project documentation
🔧 How It Works
The timetable is presented in a table format.

Users can choose a day and/or a subject from dropdown filters.

When the selection changes, JavaScript function filterTable() is triggered:

It hides rows that do not match the selected filters.

Rows are matched based on custom data-day and data-subjects attributes.

✅ How to Use
Clone or download the repository.

Make sure you have an index.html file that includes:

A timetable table with rows containing data-day and data-subjects attributes.

Dropdowns for day and subject filters.

Linked references to student.css and student.js.

Open index.html in your browser.

Use the filters to view relevant timetable entries.

📸 Screenshot (Optional)
Add a screenshot of the working timetable here if available.

📜 License
This project is open-source and free to use for educational purposes.

Let me know if you want help writing the index.html file or adding screenshots, setup instructions, or deployment tips!







You said:
make another one


ChatGPT said:
Sure! Here's another version of the README.md with a slightly different tone—simpler, more student-friendly, and a bit more casual:

🕒 Student Timetable Viewer
A clean and simple webpage to view and filter your class timetable by day and subject. Ideal for students who want to quickly find when and where their classes are.

🚀 What This Project Does
This mini web project displays a weekly timetable where you can:

🔄 Filter by Day (Monday to Friday)

📚 Filter by Subject

👀 Quickly find your classes

📂 Files Included

File Name	Description
student.css	Styles the page layout and table
student.js	Adds filter functionality
index.html	(You need this) The main HTML page
🧠 How It Works
You choose a day or subject (or both) from dropdowns.

The script (student.js) checks each row of the timetable.

It hides anything that doesn’t match your filter.

Clean and simple display using CSS.

📋 Example HTML Snippet
Here’s how your table row might look in HTML:

html
Copy
Edit
<tr data-day="Monday" data-subjects="Math, English">
  <td>9:00 AM</td>
  <td>Math</td>
  <td>Room 101</td>
</tr>
And don’t forget to include:

html
Copy
Edit
<script src="student.js"></script>
<link rel="stylesheet" href="student.css">
🛠️ Requirements
A modern web browser (Chrome, Firefox, Edge, etc.)

Basic HTML file (not included here but easy to make)

✅ To Run
Create an index.html with a timetable and dropdown filters.

Link student.css and student.js.

Open it in your browser.

Done ✅

🧑‍💻 Credits
Created for fun and learning. Feel free to modify and improve!
