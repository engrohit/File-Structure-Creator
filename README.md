File Structure Creator
A modern, web-based tool to rapidly scaffold project directories from a simple text-based outline. Design your project's skeleton in seconds and download a complete .zip archive, ready for development.

✨ Features
Intuitive Text Syntax: Define complex nested folders and files using simple indentation and syntax.

Instant ZIP Generation: Creates a downloadable .zip file containing the complete folder and empty file structure.

Custom Project Name: Set a custom name for the root folder and the downloaded archive.

Professional UI: A clean, responsive interface with a code editor-like feel, complete with line numbers and syntax highlighting for structure elements.

Import Functionality: Easily import a project structure from a local .txt file.

Browser-Based: No installation or server-side processing required. Everything is handled securely in your browser using JavaScript.

Lightweight & Fast: Built with vanilla JavaScript and modern libraries for optimal performance.

🚀 How to Use
Navigate to the Tool: Open the index.html file in your browser or visit the live deployment URL.

Set Project Name: Enter your desired root project name in the "Project Name" input field. This will be the name of the main folder inside the zip file.

Define Structure: In the editor, type or paste your desired file and folder structure. Follow the syntax rules below.

Download: Click the Download .zip button. Your browser will download a zip archive containing the generated project structure.

Syntax Guide
The parser is simple and relies on two main rules: indentation and a trailing slash for folders.

Folders: End the name with a forward slash (/).

Indentation: Use two spaces to nest a file or folder within its parent.

Files: Any line that does not end with a / is treated as a file.

Example:
/src/
  ├── /api/
  │   └── client.js
  ├── /components/
  │   ├── Button.jsx
  │   └── Modal.jsx
  └── App.jsx
/public/
  └── index.html
.gitignore
package.json
README.md

🛠️ Tech Stack
HTML5: For the core structure and content.

Tailwind CSS: For utility-first styling and a professional, responsive design.

JavaScript (ES6+): For all client-side logic, DOM manipulation, and parsing.

JSZip.js: A powerful JavaScript library for creating, reading, and editing .zip files.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE.md file for details.
