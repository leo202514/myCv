# Leonard Laing - Personal Webpage CV

## A Comprehensive Online Resume and Portfolio

This repository contains the source code for **Leonard Laing's personal webpage CV and portfolio**. This project serves as a dynamic and interactive resume, providing a comprehensive overview of my professional background, skills, education, and work experience in farm management, construction, and electronic security. It also features galleries showcasing work in farming and construction, along with a list of coding projects. The importance of this project lies in its ability to offer a more engaging and detailed presentation of my capabilities than a traditional resume, allowing potential employers or collaborators to quickly understand my diverse skill set and accomplishments. It acts as a central hub for my professional identity, demonstrating not only my practical expertise but also my growing proficiency in web development.

## Table of Contents

  - [Features](https://www.google.com/search?q=%23features)
  - [Technologies Used](https://www.google.com/search?q=%23technologies-used)
  - [Installation](https://www.google.com/search?q=%23installation)
  - [Usage](https://www.google.com/search?q=%23usage)
  - [File Structure](https://www.google.com/search?q=%23file-structure)
  - [Customization](https://www.google.com/search?q=%23customization)
  - [Credits](https://www.google.com/search?q=%23credits)
  - [Contact](https://www.google.com/search?q=%23contact)
  - [License](https://www.google.com/search?q=%23license)

## Features

  - **Comprehensive CV**: Details professional experience, skills (management, agriculture, equipment, construction), and education.
  - **Interactive Navigation**: A fixed sidebar and main navigation bar allow for easy access to different sections of the CV and portfolio pages.
  - **Galleries Section**:
      - **Farm Photos**: Showcases images related to sheep production, lucerne fields, olive orchards, apricot orchards, and seed crops (carrots, spring onion).
      - **Construction Work**: Displays examples of renovation projects, carpentry, and masonry.
  - **Coding Projects List**: A dedicated page featuring personal coding projects with links to their GitHub repositories and live demos.
  - **Contact Information**: Provides direct contact details including phone, email, and links to LinkedIn, GitHub, and Facebook profiles.
  - **Responsive Design**: The website adapts to various screen sizes, ensuring a consistent user experience on desktop, tablet, and mobile devices.
  - **Clean and Modern UI**: Designed with a professional aesthetic, utilizing clear typography and well-organized sections.

## Technologies Used

  - **HTML5**: The core markup language for structuring the content of all web pages (Home, Gallery, Projects, Contact).
  - **CSS3**: For styling and layout, defining the visual presentation of the website.
  - **SCSS (Sass)**: Used as a CSS pre-processor to enable more organized and maintainable stylesheets through variables and nested rules (compiled into `style.css`).
  - **Font Awesome**: Integrated for scalable vector icons, used for social media links and project links.
  - **JavaScript**: (Though not directly provided in the snippets, `script.js` is referenced in HTML, implying potential interactive elements).

## Installation

To get a local copy of this project up and running, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/leo202514/myCv.git
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd myCv
    ```
3.  **Install Sass (if you plan to modify SCSS)**:
    If you wish to make changes to the styling defined in `style.scss`, you will need Sass installed to compile it to `style.css`.
    ```bash
    npm install -g sass
    # or using yarn
    yarn global add sass
    ```

## Usage

After installation, you can view the website locally.

1.  **Compile SCSS to CSS (if you made changes to `style.scss`)**:
    If you've modified `style.scss` or if `style.css` is not present, you'll need to compile it. Open your terminal in the project root and run:
    ```bash
    sass style.scss css/style.css
    ```
    For continuous development, use the watch command:
    ```bash
    sass --watch style.scss:css/style.css
    ```
2.  **Open the HTML files**:
    Simply open `index.html` in your web browser. You can navigate to other pages (`gallery.html`, `projects.html`, `contact.html`) using the navigation links within the site.

### Screenshots of the Project in Action:

#### Home Page (`index.html`):

![Home Page screenshot.](README-assets/index.jpeg)

#### Gallery Page (`gallery.html`):

![Gallery Page screenshot.](README-assets/gallery.jpeg)

#### Projects Page (`projects.html`):

![Projects Page screenshot.](README-assets/projects.jpeg)

#### Contact Page (`contact.html`):

![Contact Page screenshot.](README-assets/contact.jpeg)

## File Structure

```
myCv/
├── css/
│   └── style.css           # Compiled CSS file for styling the website
├── images/
│   ├── your-image.jpg      # Placeholder for your profile picture
│   ├── farm-sheep.jpg      # Image of Dorper Sheep
│   ├── farm-lucerne.jpg    # Image of Lucerne Field
│   ├── farm-olives.jpg     # Image of Olive Orchard
│   ├── farm-apricots.jpg   # Image of Apricot Orchard
│   ├── farm-carrots.jpg    # Image of Carrot Seed Crop
│   ├── farm-spring-onion.jpg # Image of Spring Onion Crop
│   ├── construction-cottage.jpg # Image of Cottage Restoration
│   ├── construction-carpentry-example.jpg # Image of Carpentry Example
│   ├── construction-masonry-example.jpg # Image of Masonry Work
│   ├── construction-timber.jpg # Image of Timber Frame Building
│   ├── project-web-app-screenshot.jpg # Screenshot for Portfolio Website project
│   └── Hobby-website-screenshot.jpg # Screenshot for Hobby Website project
├── js/
│   └── script.js           # (Potentially) JavaScript file for interactive elements
├── style.scss              # Source SCSS file for styling
├── index.html              # The main CV page with About, Skills, Education, and Experience sections
├── gallery.html            # The page showcasing farm and construction project photos
├── projects.html           # The page listing coding projects
└── contact.html            # The page with contact details and social media links
```

## Customization

You can easily customize this portfolio website:

  - **Personal Information**: Update `index.html` and `contact.html` with your specific details, including your name, tagline, about me section, skills, education, and work experience.
  - **Profile Image**: Replace `images/your-image.jpg` with your actual profile picture.
  - **Gallery Content**: Add or replace images in the `images/` directory and update `gallery.html` with relevant `<img>` tags and descriptions for your farm and construction work.
  - **Coding Projects**: Modify `projects.html` to include your own coding projects, updating screenshots, descriptions, and links to your GitHub repositories and live demos.
  - **Styling**: All major styles are managed in `style.scss`. You can adjust colors, fonts, spacing, and responsive behaviors by modifying the variables and CSS rules in this file. Remember to recompile SCSS to CSS after changes.
  - **Social Media Links**: Update the URLs in `contact.html` for your LinkedIn, GitHub, and Facebook profiles.

## Credits

This personal CV website was developed by:

  * **Leonard Laing** - [GitHub Profile](https://github.com/leo202514)
    

## Contact

Feel free to reach out for any inquiries or opportunities:

  - **Name**: Leonard Laing
  - **Phone**: +27 82 324 7877
  - **Email**: [llaingdev@gmail.com](mailto:llaingdev@gmail.com)
  - **Location**: Ladismith, WC 6656, South Africa
  - **LinkedIn**: [linkedin.com/in/Leonard](https://www.linkedin.com/in/leonard-laing-b9a1a416))
  - **GitHub**: [github.com/leo202514](https://github.com/leo202514)
  - **Facebook**: [facebook.com/Leonard](https://www.facebook.com/share/1BaDvmUEWd/))

## License

This project is open-sourced. Consider adding a `LICENSE` file in the root directory if you wish to specify a particular open-source license (e.g., MIT, Apache 2.0).
