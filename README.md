# BlackBerryGPT
An OpenAI ChatGPT client for the standard BlackBerry Browser

This was designed for the BlackBerry Passport so you may want to alter the display settings within the code if you are going to use it with any other BB.

The software release that this was tested with is 10.3.3.2137

The Passport browser is old today by modern standard so I used:

For the BlackBerry Passport (OS 10.3.3) implementation:
Used:

- Basic HTML5
- CSS3 (without modern features)
- Vanilla JavaScript (ES5)
- XMLHttpRequest for API calls
- localStorage for data persistence
- document.execCommand for clipboard operations

Avoided/Could Not Use:

- Modern JavaScript (ES6+)
- async/await
- fetch API
- Modern CSS features (grid, flexbox)
- Web Crypto API
- Modern clipboard API

To get this to work I prioritized compatibility and functionality over modern features, keeping the code simple for the older BB browser environment.
