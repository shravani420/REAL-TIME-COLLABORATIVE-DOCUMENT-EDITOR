# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR

*COMPANY*-CODTECH IT SOLUTIONS

*NAME*-SHRAVANI KAKASO JAGTAP

*INTERN ID*-CT08HDQ

*DOMAIN*-WEB DEVELOPMENT

*DURATION*-4 WEEKS

*MENTOR*-NEELA SANTOSH

1. HTML Structure
The document follows a standard HTML structure with key elements:

Meta Tags: The <meta> tags set the character encoding and viewport settings for responsiveness.
Title: The <title> tag sets the page title as "Real-Time Collaborative Editor".
External Script: The application includes the Socket.io library (socket.io.min.js) for real-time communication.
The body consists of:

A Container (<div class="editor-container">): Holds the main components.
A Heading (<h1>): Displays the title.
A Username Input (<input>): Allows users to enter their name.
A Textarea (<textarea>): Acts as the main editor where users can type.
A Save Button (<button>): Simulates saving content.
2. CSS Styling
The provided CSS enhances the visual appeal and usability:

Flexbox (display: flex; flex-direction: column; align-items: center; justify-content: center;) aligns content centrally.
Container Styling: A white background, shadows, and rounded borders improve appearance.
Textarea and Input: Rounded corners, padding, and box shadows create a polished look.
Button Styling: A blue theme (background-color: #007BFF) makes the button stand out.
3. JavaScript Functionality
The JavaScript code manages real-time updates, user interaction, and content saving.

A. Establishing a Socket Connection
javascript
Copy
Edit
const socket = io('http://localhost:5000');
Connects to a WebSocket server at localhost:5000.
Enables real-time bidirectional communication.
