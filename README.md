 Currency Converter

A simple, fast and responsive currency converter built with HTML, CSS and vanilla JavaScript. Convert between 150+ world currencies using live exchange rates — no API key, no signup, no backend required.

✨ Features
🌍 Convert between 150+ currencies
🔄 One-click swap button to reverse the conversion
🚩 Country flag shown next to each selected currency
🔢 Supports decimal amounts (e.g. 12.50)
⚡ Rates fetched live from a free API, rounded to 2 decimal places
📱 Clean, simple UI with no external framework
🆓 Uses only free services — no API key needed
🛠️ Tech Stack
HTML5
CSS3
JavaScript (ES6+) — fetch, async/await, DOM manipulation
🔌 APIs & Services Used
Service	Purpose	Cost
Currency API by fawazahmed0 (via jsDelivr CDN)	Live exchange rates	Free, no rate limits, no key
FlagsAPI	Country flag images	Free, no key
Font Awesome (via cdnjs)	Swap icon	Free
📁 Project Structure
currency-converter/
├── index.html    # Page structure
├── style.css     # Styling
├── code.js       # Currency code → country code mapping
├── app.js        # App logic (fetch rates, swap, update flags)
└── README.md
🚀 Getting Started

No installation or build step is needed.

Clone the repository

Open the folder
bash
   cd currency-converter
Run it — simply open index.html in your browser.

An internet connection is required to fetch live exchange rates and flag images.


⭐ If you found this project useful, consider giving it a star!
