# Terminal Screenshot Generator

> **Note:** This project is currently in active development and is considered a work in progress. Features may change, and you might encounter some bugs. Feedback is highly appreciated!

A professional web-based tool for creating beautiful, high-quality terminal code screenshots. Designed for developers, documentation writers, and content creators who need clean and customizable code snippets for presentations, blogs, or social media.

## Features

- **Live Code Preview**: Real-time syntax highlighting and terminal styling.
- **Multiple Themes**: Includes popular color schemes like Monokai, Dracula, Nord, Solarized, and GitHub Dark.
- **Language Auto-Detection**: Automatically identifies programming languages including JavaScript, Python, Java, C++, HTML, CSS, PowerShell, Bash, JSON, and SQL.
- **Customizable Interface**:
  - Adjustable terminal window title.
  - Toggle between different window control button styles.
  - Custom file names for export.
- **Export Options**:
  - **Full Image**: Download the entire code snippet as a high-resolution PNG.
  - **Multiple Sections**: Automatically slice long code snippets into multiple images based on social media presets (e.g., Instagram Story, Twitter Post).
  - **ZIP Download**: Download multiple sliced images as a single ZIP archive.
- **Responsive Design**: Fully functional on desktop and mobile devices.

## Technologies Used

- **HTML5 & CSS3**: Core structure and responsive styling.
- **JavaScript (ES6+)**: Application logic and interactivity.
- **html2canvas**: Canvas generation for screenshot capture.
- **JSZip**: Client-side ZIP file creation for multiple image downloads.
- **Font Awesome**: Iconography.

## Usage

1.  Open `sscode.html` in any modern web browser.
2.  Paste your code into the editor panel on the left.
3.  Customize the look using the tabs at the bottom:
    - **Themes**: Choose a color scheme.
    - **Colors**: Adjust the prompt color.
    - **Settings**: Set the terminal title, filename, and download mode.
4.  Click **Generate** to create the screenshot.
5.  Click **Download** to save the image to your device.

## Installation

No installation is required. This is a client-side application that runs directly in the browser.

1.  Clone the repository:
    ```bash
    git clone https://github.com/dexccv/sscode.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd sscode
    ```
3.  Open `sscode.html` in your browser.

## Browser Support

Compatible with the latest versions of Chrome, Firefox, Safari, and Edge.

## License

This project is open source and available under the MIT License.

## Credits

- Syntax highlighting logic inspired by common editor themes.
- Screenshot functionality powered by [html2canvas](https://html2canvas.hertzen.com/).
- ZIP functionality powered by [JSZip](https://stuk.github.io/jszip/).

