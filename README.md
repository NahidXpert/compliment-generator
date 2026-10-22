# Positivity Brew ☕✨

A fun, interactive web app that generates personalized compliments and light-hearted jokes. Choose the vibe and who the message is for, then create, copy, or share something positive.

## ✨ Features

- **Personalized compliments** — generate a random compliment based on your selected tone and recipient.
- **Three tones**
  - Professional
  - Hype
  - Sincere
- **Three recipient options**
  - Coworker
  - Partner
  - Myself
- **Random jokes** — display a joke with a delayed punchline reveal.
- **Copy to clipboard** — quickly copy the current compliment or joke.
- **Share** — share the generated message using the browser's Web Share API when supported.
- **Recent history** — keep up to five recent messages in the browser's local storage.
- **Animated interface** — enjoy a colorful gradient background, playful decorations, and smooth transitions.
- **Responsive layout** — designed to work on different screen sizes.
- **No backend required** — compliments and jokes are stored in the JavaScript code.

## 🛠️ Built With

- **HTML5** — page structure
- **CSS3** — styling, responsive layout, gradients, and animations
- **Vanilla JavaScript (ES6+)** — generation logic, event handling, clipboard, sharing, and history
- **Google Fonts** — Inter and Outfit typography

## 🚀 Getting Started

No package installation or build tools are required.

### Run locally

1. Download or clone this repository.
2. Make sure the main HTML file and any referenced assets (such as `yoruicci.png`, if included) are in the same project folder.
3. Open the HTML file in a modern web browser.

Alternatively, use the **Live Server** extension in Visual Studio Code to run it locally.

## 🎮 How to Use

1. Open the app in your browser.
2. Select a **vibe**: Professional, Hype, or Sincere.
3. Choose who the message is for: Coworker, Partner, or Myself.
4. Click **Get a Compliment** to generate a personalized compliment.
5. Click **Tell a Joke** to display a random joke.
6. Use **Copy** to copy the current message.
7. Use **Share** to share the message if your browser supports the Web Share API.
8. Check **Recent Magic** to see your latest generated messages.

## 💾 Data Storage

The app uses the browser's **localStorage** to save recent messages under the key `compliment_history_v2`.

- A maximum of **five** recent messages is saved.
- The history is stored in the current browser on the current device.
- No database or server is used.
- Clearing the browser's site data may remove the saved history.

## 📁 Project Structure

The project can be organized like this:

```text
project-folder/
├── index.html       
├── yoruicci.png     
└── README.md
```

## 🌐 Browser Compatibility

Use a modern browser such as the latest version of Chrome, Edge, Firefox, or Safari. Sharing depends on browser and device support for the Web Share API. Clipboard behavior can also vary by browser and security context.

## 🔮 Possible Improvements

- Add custom compliment categories or user-written messages.
- Add a way to clear recent history.
- Add more tones, recipients, and jokes.
- Add accessibility and reduced-motion options.
- Move the compliment database to a backend or external API if a larger, dynamic collection is needed.

Made with positivity and a little bit of JavaScript. ☕
