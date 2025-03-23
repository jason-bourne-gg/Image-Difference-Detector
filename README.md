# Image-Difference-Detector

## Table of Contents 
- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [License](#license)

## About
Image-Difference-Detector is a lightweight and efficient tool designed to compare two images and highlight their differences. It is particularly useful for developers and testers working on UI testing, image validation, or monitoring visual changes over time.

### Input
- The tool accepts two images as input, which should be placed in the `images` directory.
- Supported image formats include `.png`, `.jpg`, and `.jpeg`.
- Ensure the images have the same dimensions for accurate comparison.

### Output
- The output is an image that visually highlights the differences between the two input images.
- It is saved in the `output` directory with a filename indicating the comparison result (e.g., `difference.png`).
- The output image uses color overlays to mark the differing regions for easy identification.
- Logs or error messages, if any, are displayed in the terminal during execution.

## Directory Structure
The project is organized as follows:
```
Image-Difference-Detector/
├── images/          # Directory to store input images for comparison
├── output/          # Directory where the output images with differences are saved
├── src/             # Source code for the application
│   ├── compare.js   # Core logic for image comparison
│   ├── utils.js     # Utility functions
│   └── config.js    # Configuration settings
├── tests/           # Unit tests for the application
├── package.json     # Project metadata and dependencies
├── README.md        # Project documentation
└── LICENSE          # License information
```
This structure ensures modularity and ease of navigation for contributors and users.
Image-Difference-Detector is a tool that compares two images and highlights differences between them. It can be used for UI testing, image validation, and detecting visual changes over time.

## Features
- Compare two images pixel by pixel.
- Highlight differences visually.
- Support for various image formats.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Image-Difference-Detector.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Image-Difference-Detector
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Usage
1. Place the two images you want to compare in the `images` directory.
2. Run the tool in local with nodemon:
   ```bash
   npm run dev
   ```
3. The output highlighting the differences will be saved in the `output` directory.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
