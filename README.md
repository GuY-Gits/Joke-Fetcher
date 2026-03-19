# 🚀 Joke Fetcher API

A lightweight, front-end web application designed to demonstrate asynchronous JavaScript data fetching, DOM manipulation, and modern CSS animation techniques. 

This project connects to a public REST API to retrieve randomized data (jokes) and displays them using a carefully timed, suspense-building user interface.

## ✨ Features
* **Asynchronous Data Fetching:** Utilizes modern ES6 `async/await` and the native `fetch()` API to handle HTTP GET requests.
* **Modern UI/UX:** Built with a "Glassmorphism" aesthetic, featuring frosted-glass backdrop filters and smooth CSS transitions.
* **State Management:** Implements interactive button states (disabled/enabled) to prevent API spamming during data retrieval.
* **Suspense Animations:** Uses JavaScript `Promises` to create an artificial delay, triggering a custom CSS loading animation before revealing the final data payload.

## 🛠️ Tech Stack
* **HTML5:** Semantic structure and accessible layout.
* **CSS3:** Flexbox centering, keyframe animations (`@keyframes`), and glassmorphism styling (`backdrop-filter`).
* **Vanilla JavaScript:** Promise-based asynchronous logic and dynamic DOM manipulation.

## 🚀 How to Run Locally
Because this project uses vanilla web technologies, it requires zero external dependencies or local servers to run.
1. Clone this repository to your local machine.
2. Navigate to the project folder.
3. Double-click the `index.html` file to open it directly in any modern web browser.

## 🧠 Core Learnings
This project served as a technical sandbox to master:
* Parsing JSON payloads from external servers.
* Handling network latency and potential API errors cleanly in the UI using `try/catch` blocks.
* Injecting dynamic HTML elements directly into the Document Object Model (DOM) without refreshing the page.