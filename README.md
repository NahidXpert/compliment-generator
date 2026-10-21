☕ Positivity Brew
Positivity Brew is a cheerful, browser-based web app that helps brighten the day with personalized compliments and lighthearted jokes. Choose a vibe and who the message is for, then generate something positive to share or keep for yourself.
✨ Features
- Personalized compliments — generate compliments based on the selected tone and recipient.
- Three tones — Professional, Hype, and Sincere.
- Three recipient options — Coworker, Partner, and Myself.
- Random jokes — get a joke with a delayed punchline reveal.
- Copy to clipboard — copy the current compliment or joke.
- Share — use your browser's native sharing feature when it is supported.
- Recent history — see up to five recent generated messages.
- Local persistence — recent history is saved in the browser using localStorage.
- Responsive, animated interface — colorful gradient backgrounds, decorative emoji, transitions, and a polished card layout.
- Accessibility basics — semantic sections, labeled controls, visible keyboard focus, and live announcements for generated content.
🛠️ Built With
- HTML5 — page structure and controls
- CSS3 — styling, gradients, animations, layout, and responsive presentation
- Vanilla JavaScript (ES6+) — app logic, random selection, event handling, clipboard, sharing, and local storage
- Google Fonts — Inter and Outfit
No framework, package installation, backend, or API key is required. Compliments and jokes are selected from data stored in the JavaScript code.
🚀 Getting Started
Run locally
1. Download or clone this repository.
2. Make sure the HTML file, yoruicci.png favicon (if you want to use it), and any other project assets are in the expected locations.
3. Open the HTML file in a modern browser.
For a more consistent local development experience, you can serve the project with a local development server, such as the Live Server extension in Visual Studio Code.
Use the app
1. Choose a vibe: Professional, Hype, or Sincere.
2. Choose who the message is for: Coworker, Partner, or Myself.
3. Select Get a Compliment to generate a personalized compliment.
4. Select Tell a Joke to generate a random joke.
5. Use Copy or Share to pass the result along.
6. Review the Recent Magic section to revisit recent messages.
📁 Project Structure
The current project is implemented in a single HTML file, with CSS and JavaScript embedded in it. A typical folder layout could look like this:
positivity-brew/
├── index.html       # HTML, CSS, and JavaScript for the app
├── yoruicci.png     # Favicon image referenced by the HTML
└── README.md        # Project documentation
If your HTML file has a different name or your assets are organized differently, update this example to match your repository.
💾 How Data Is Stored
The app stores recent generated messages in the browser's localStorage under the key:
compliment_history_v2
- Up to five recent messages are kept.
- The history is restored when the app is opened again in the same browser.
- The data is stored locally in that browser; there is no server-side database or account system.
- Clearing the browser's site data can remove the saved history.
🌐 Browser Compatibility
Use a modern browser with JavaScript enabled. Clipboard and native sharing support can vary by browser and security context. The Share button is hidden when the browser does not provide the Web Share API.
🔮 Possible Improvements
- Add more compliment categories and recipient types.
- Let users save favorites or clear their history.
- Add a search or filter for previously generated messages.
- Add dark mode and language options.
- Split the HTML, CSS, and JavaScript into separate files for easier maintenance.
- Add automated tests for message selection and history handling.