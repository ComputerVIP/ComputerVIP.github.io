# Website Project

## Description
This project is a simple website that includes a redirecting page with Google Tag Manager and Google Analytics tracking configured. The website is designed to track user visits and provide analytics data.

## Project Structure
```
website-project
├── public
│   └── page.html
├── src
│   └── scripts
│       └── analytics.js
├── package.json
├── .gitignore
└── README.md
```

## Files Overview

- **public/page.html**: Contains the HTML structure for the webpage, including the Google Tag Manager and Google Analytics tracking code, along with a meta tag for redirecting users to a specified URL.

- **src/scripts/analytics.js**: Intended for additional JavaScript related to analytics. This file can include functions to handle events or custom tracking beyond the basic Google Analytics setup.

- **package.json**: Configuration file for npm, listing dependencies, scripts, and metadata for the project.

- **.gitignore**: Specifies which files and directories should be ignored by Git, such as `node_modules` and environment files.

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```
   cd website-project
   ```

3. Install dependencies (if any):
   ```
   npm install
   ```

4. Open `public/page.html` in a web browser to view the redirecting page.

## Usage Guidelines
- Ensure to replace the Google Analytics tracking ID in `public/page.html` with your own.
- Modify `src/scripts/analytics.js` to add any custom tracking or event handling as needed.
- Update the redirect URL in `public/page.html` to point to the desired destination.