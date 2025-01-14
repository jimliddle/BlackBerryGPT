# BlackBerryGPT
An OpenAI ChatGPT client for the standard BlackBerry Browser

![photo_2025-01-14_18-46-41](https://github.com/user-attachments/assets/17c85e7d-f910-474a-9c52-154fc8e1db2d)

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

To run it, store the file local on your BlackBerry and  open it in the BB browser and bookmark it. When you first run it, it you will need to enter an OpenAI API Key (which you can get from the OpenAI Playground) but once entered it will be persisted in the local storage between sessions unless you reset it.
