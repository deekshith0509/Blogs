
# 🚀 Blogs using MarkDown


## 📖 Overview

The **Blogs** application is a dynamic web project designed to fetch and display blog posts from a GitHub repository. It utilizes [Marked.js](https://github.com/markedjs/marked) to convert Markdown files into beautifully formatted HTML, enhancing the reading experience. The app also features a seamless light/dark mode toggle for optimal viewing.

## 🌟 Features

- **Markdown Rendering**: Fetch and display Markdown content seamlessly using Marked.js.
- **Responsive Design**: Fully responsive layout for an optimal user experience on all devices.
- **Theme Toggle**: Easy switching between light and dark themes.
- **Dynamic Navigation**: Clickable cards for blog posts with smooth transitions and a back button for easy navigation.
- **Browser History Support**: Maintains application state, allowing for back and forward navigation.

## 🛠️ Technologies Used

- **Frontend**: 
  - HTML5
  - CSS3 (with custom variables for theming)
  - JavaScript (ES6+)
  - [Marked.js](https://github.com/markedjs/marked) for Markdown parsing
- **APIs**: GitHub API for accessing Markdown files

## 📥 Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```
git clone https://github.com/deekshith0509/Blogs.git
   cd Blogs
```

   #### Open the HTML file: Open index.html in your web browser.

   ##### Optional - Live Server: For a better development experience, consider using the Live Server extension for Visual Studio Code to serve your files.

## 🔧 Usage Instructions

-    The application will automatically fetch Markdown files from your GitHub repository specified in the JavaScript code.
    Click on the blog cards to navigate to the detailed view of each post.
    Utilize the theme switch at the top right corner to toggle between light and dark modes.
    Use the "Back to Main Page" link to return to the main blog list.

## 🎨 Theme Customization

You can customize themes by modifying the CSS variables in the section of index.html. Change the following variables to suit your design preferences:

```css
:root {
  --card-bg: #fff; /* Card Background Color */
  --header-start: #007BFF; /* Header Gradient Start Color */
  --link-color: #007BFF; /* Default Link Color */
  /* Add more custom variables as needed */
}

```

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request. Please follow these steps:

- Fork the project
- Create your feature branch (git checkout -b feature/YourFeature)
- Commit your changes (git commit -m 'Add some feature')
- Push to the branch (git push origin feature/YourFeature)
- Open a Pull Request

## 📫 Contact

For questions or feedback, feel free to reach out to me.


##### Future enhancements include:
-    Improved error handling for API requests.
  -  Caching of fetched Markdown files for offline access.
 -   Additional styling options for blog posts.
    User authentication for posting comments.

## 💡 Acknowledgements

 -   Marked.js: For providing a robust Markdown parsing solution.
  -  GitHub: For allowing easy access to Markdown files via its API.
   - Inspiration: Thanks to the open-source community for continuous learning.

 >>> **Feel free to clone, modify, and contribute to this project!**
