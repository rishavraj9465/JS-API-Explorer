🌐 JS API Explorer
A beginner-friendly JavaScript project demonstrating real-world API integration using Axios and async/await. Three independent mini-apps are packed into one sleek dark-themed UI.

✨ Features
🐱 Random Cat Facts

Fetches a new random cat fact on every button click
Uses the Cat Fact API

🐶 Random Dog Image

Displays a fresh random dog photo on demand
Uses the Dog CEO API

🏫 University Search

Search universities by country name using a query string
Returns a live list of matching institutions
Uses the Hipolabs Universities API

🃏 Dad Jokes (Console)

Demonstrates custom request headers (Accept: application/json)
Uses the icanhazdadjoke API
Output visible in the browser console


🛠️ Built With
TechnologyUsageHTML5Page structureCSS3Dark UI, Flexbox, hover effectsJavaScript (ES6+)Async/await, DOM manipulationAxiosHTTP requestsGoogle Fonts (Poppins)Typography

🧠 Concepts Covered

async / await with try...catch error handling
Axios GET requests
Custom request headers (for API content negotiation)
Query string parameters in API URLs
Dynamic DOM creation with createElement & appendChild
setAttribute for dynamic image rendering


📁 Project Structure
js-api-explorer/
│
├── index.html      # UI layout
├── app.js          # All API logic & event listeners
└── style.css       # Dark theme styles

⚠️ Make sure you're connected to the internet since all data is fetched live from public APIs.


📌 Notes

The dad joke feature logs output to the browser console (F12 → Console) as a header demo — it has no UI element by design.
The Universities API may return empty results for some country inputs; try india, usa, or uk.
All APIs used are free & open — no API keys required.

Made with ❤️ by Rishav Raj
