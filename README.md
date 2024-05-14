# Awesomegpts.vip 🦄️
This code repository contains **all the code** for the website https://awesomegpt.vip.
![AwesomeGPTs gif](https://github.com/ai-boost/ai-boost.github.io/blob/main/images/awesomegpts.gif?raw=true)

## Code Structure 🏗️
```
.
├── CNAME                  # Custom domain configuration file for the website
├── LICENSE.txt            # License file for the project
├── README.md              # README file providing information about the project
├── assets                 # Folder containing assets for the website
│   ├── css                # CSS files for styling the website
│   │   ├── fontawesome-all.min.css # FontAwesome CSS for icons
│   │   ├── main.css       # Main stylesheet for the website
│   │   └── noscript.css   # Stylesheet for no-script support
│   ├── js                 # JavaScript files for interactivity
│   │   ├── breakpoints.min.js # Helper script for responsive design
│   │   ├── browser.min.js # Script for browser detection
│   │   ├── jquery.min.js  # jQuery library for simplified JavaScript coding
│   │   ├── main.js        # Main JavaScript file for the site
│   │   └── util.js        # Utility script for various functions
│   └── webfonts           # Folder intended for webfonts (currently empty)
├── images                 # Folder intended for image files (currently empty)
└── index.html             # The main HTML file for the website
```

**Note 📝**

This structure represents a typical static website setup. It includes configuration files like `CNAME` for custom domain linking, a `LICENSE.txt` file that outlines the terms under which the website's content can be used, and a `README.md` file that typically provides an overview of the project, how to set it up, and other important information.

The `assets` folder is divided into subfolders for CSS and JavaScript files, which are crucial for the styling and functionality of the website. The `css` folder includes stylesheets for the website's design, including a version of FontAwesome for iconography, a main stylesheet, and a noscript stylesheet for users who have JavaScript disabled. The `js` folder contains JavaScript files for adding interactivity to the website, including utility scripts, jQuery for easier DOM manipulation, and scripts for responsive design and browser detection.

The `webfonts` folder is reserved for webfont files, which would typically include various font formats to ensure compatibility across different browsers and devices. However, in this simplified structure, it is left empty to indicate the original presence of font files without including them.

The `images` folder is intended to house image files for the website, but it is also left empty in this simplified structure to indicate that images have been excluded.

Finally, the `index.html` file is the entry point to the website, containing the markup that defines the structure and content of the homepage.

## How to use 💡

#### Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript
- A GitHub account
- Git installed on your computer

#### Cloning the Repository

1. **Fork the Repository** (Optional): If you plan to contribute, start by forking the repository to your GitHub account by clicking the "Fork" button on the repository page.

2. **Clone the Repository**: Open your terminal or command prompt and run the following command to clone the repository:

   ```bash
   git clone https://github.com/ai-boost/ai-boost.github.io.git
   ```

   If you forked the repository, replace `ai-boost` with your GitHub username.

3. **Navigate into the Repository**:

   ```bash
   cd ai-boost.github.io
   ```

#### Understanding the Directory Structure

- `CNAME`: Contains custom domain configuration for GitHub Pages.
- `LICENSE.txt`: The license file specifies the terms under which the project can be used or contributed to.
- `README.md`: Provides an overview of the project and other essential information.
- `assets/`: Contains subdirectories for CSS, JavaScript, and webfonts (empty).
  - `css/`: Style sheets for the website's appearance.
  - `js/`: JavaScript files for website functionality.
  - `webfonts/`: Intended for font files (this directory is empty as of the provided structure).
- `images/`: Intended for storing image files (this directory is empty as of the provided structure).
- `index.html`: The main HTML file, serving as the entry point of the website.

#### Running the Website Locally

To view the website on your local machine, simply open the `index.html` file in a web browser. For a more advanced setup, you might consider using a local server environment like `http-server` in Node.js or Python's HTTP server module.

#### Making Changes

- To add or modify content, you can edit the `index.html` file or the respective HTML files if your site contains multiple pages.
- Update the CSS in the `assets/css/` directory to alter the site's appearance.
- JavaScript files in the `assets/js/` directory can be modified or extended to change or add website functionalities.
- Fonts and images can be added to their respective directories (`assets/webfonts/` and `images/`) and linked within your HTML or CSS files.

#### Contributing

If you've forked the repository and made improvements or additions you'd like to share:

1. Commit your changes to your fork:

   ```bash
   git add .
   git commit -m "Your descriptive commit message"
   git push origin main
   ```

2. Open a pull request from your forked repository to the original `ai-boost` repository with a clear description of the changes and the value they add to the project.

#### Deployment

GitHub Pages automatically serves the content from the `main` branch of your repository at `https://<your-username>.github.io/ai-boost.github.io` or a custom domain if configured in the `CNAME` file.

#### Updating Your Site

To update your website, simply make changes to your files, commit, and push them to your GitHub repository. GitHub Pages will automatically rebuild and redeploy your site.


# Thanks 🥰
This website is based on Phantom template from @ajlkn in html5up. Thanks for the open sourced html template, I only spent less than 10 minutes creating this website using this template.
