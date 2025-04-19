```javascript
// 🚀 Motivational inspire function
function inspire(name) {
  const quotes = [
    "Believe in yourself and all that you are.",
    "Dream big, work hard, make it happen!",
    "Every line of code is a step towards greatness.",
    "Your potential is unlimited."
  ];
  const emojis = ['🌟','🔥','💫','🚀'];
  const quote = quotes[Math.floor(Math.random() * quotes.length)];
  const emoji = emojis[Math.floor(Math.random() * emojis.length)];

  console.log(`
${emoji}  ${quote}  ${emoji}
`);
  console.log(`Hello, ${name}! Let's build something amazing today!`);
  console.log('✨ Keep coding, keep shining! ✨');
}

inspire('Developer'); // Swap in your name and start coding with a smile 😊
```
