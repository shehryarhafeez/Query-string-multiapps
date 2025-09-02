🚀 Query String Applications

A single-page web application that demonstrates how to use query strings (?param=value) to pass data between pages.

The app includes five interactive mini-apps, each showing a different way query parameters can be used.

🔗 Live Demo
https://shehryarhafeez.github.io/Query-string-multiapps/?theme=blue

✨ Features
🔹 Navigation System

Clean, responsive navigation bar

Smooth transitions between apps

Mobile-friendly (collapsible menu)

🔹 Applications Included

1. Greeting App

Personal greeting generator using name parameter

Example: ?name=John → displays "Hello John! Welcome back."

2. Calculator App

Performs addition, subtraction, multiplication, division

Parameters: num1, num2, op

Example: ?num1=5&num2=3&op=add → 8

3. Theme Switcher

Switch between Light (default), Dark, Blue themes

Parameter: theme → light | dark | blue

4. Product Viewer

Displays product info based on ID

7 sample products (101–107)

Parameter: id → product ID

Example: ?id=102 → iPhone XR: $300

5. Quiz App

Simple 3-question quiz with scoring

Tracks user name & score in query string

Parameters: user, score

🛠️ Technical Implementation
📌 Query String Handling

Uses URLSearchParams API to:

Extract parameters from URL

Update app state dynamically

Modify URL when users interact

📌 Responsive Design

Flexbox-based layout for adaptive design

Mobile-first approach with vertical nav on small screens

Consistent, clean styling

📌 Theme System

CSS custom properties for theming

Three distinct color schemes

Smooth transitions between themes

📌 Code Structure

.HTML

Semantic sections for each app

Modular container design

.CSS

Custom properties for theming

Media queries for responsiveness

Smooth animations/transitions

.JavaScript

Event listeners for nav switching

Query parameter parsing

App logic for greeting, calculator, theme, products, quiz
