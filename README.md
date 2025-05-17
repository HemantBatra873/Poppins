# Poppins - India's Premier Streaming Platform

![Poppins Logo](./images/logo.png)

## Overview

Poppins is a front-end web development project designed to emulate a modern streaming platform, offering users an immersive interface to explore movies, TV shows, web series, and more. Built with HTML, CSS, and JavaScript, Poppins showcases a responsive, visually appealing design inspired by leading streaming services. This project highlights best practices in web development, including semantic HTML, modular CSS, and interactive JavaScript functionalities.

The platform features a sleek user interface with sections for upcoming movies, top-rated content, TV series, and a call-to-action for user subscriptions. It is optimized for various screen sizes, ensuring a seamless experience across desktops, tablets, and mobile devices.

[Visit the Poppins Repository](https://github.com/HemantBatra873/Poppins)

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Features

- **Responsive Design**: Adapts seamlessly to different screen sizes, from mobile devices to large desktops.
- **Interactive Navigation**: Includes a fixed header with a hamburger menu for mobile views and a desktop-friendly navbar.
- **Dynamic Sections**:
  - **Hero Section**: Showcases a featured movie with metadata (rating, genre, duration) and a call-to-action button.
  - **Upcoming Movies**: Displays a scrollable list of upcoming releases with details like runtime and ratings.
  - **Top-Rated Movies**: Highlights popular movies with filter options for genres.
  - **TV Series**: Features trending web series with concise information.
  - **Service Section**: Promotes offline viewing and multi-device streaming capabilities.
  - **Call-to-Action**: Encourages users to sign up with a trial period offer.
- **Custom Styling**: Utilizes CSS custom properties for consistent theming, with a dark aesthetic and vibrant accents.
- **Smooth Animations**: Implements transitions and hover effects for an engaging user experience.
- **Social Media Integration**: Footer includes links to social platforms for enhanced connectivity.
- **Go-to-Top Button**: Improves navigation by allowing quick access to the page top.
- **Language Selector**: Offers multi-language support with a dropdown menu.
- **Accessibility**: Uses semantic HTML and ARIA attributes for better screen reader compatibility.

---

## Technologies Used

- **HTML5**: For semantic and structured content.
- **CSS3**: For styling, including CSS custom properties, Flexbox, Grid, and media queries for responsiveness.
- **JavaScript**: For interactive elements like the mobile menu toggle and scroll effects.
- **Google Fonts**: Poppins font for consistent typography.
- **Ionicons**: For scalable vector icons used in buttons and metadata.
- **Git & GitHub**: For version control and repository hosting.

---

## Project Structure

```plaintext
Poppins/
├── images/                  # Image assets (logo, banners, movie posters)
│   ├── logo.png
│   ├── hero-bg.jpg
│   ├── upcoming1.jpg
│   ├── movie1.jpg
│   ├── series1.jpg
│   └── ...
├── index.html              # Main HTML file
├── style.css               # CSS stylesheet
├── script.js               # JavaScript file
└── README.md               # Project documentation
```

- **index.html**: Contains the structure of the website, including header, main content, and footer.
- **style.css**: Defines the visual styling with a modular approach, using CSS custom properties and media queries.
- **script.js**: Handles interactivity, such as toggling the mobile menu and activating the go-to-top button.
- **images/**: Stores all visual assets, including the logo, background images, and movie posters.

---

## Installation

To set up the Poppins project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/HemantBatra873/Poppins.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd Poppins
   ```

3. **Open the Project**:
   - Open `index.html` in a web browser to view the website.
   - Alternatively, use a local development server (e.g., Live Server in VS Code) for a better experience.

4. **Dependencies**:
   - No external dependencies are required, as the project uses CDN-hosted Ionicons and Google Fonts.
   - Ensure an internet connection to load these resources.

---

## Usage

- **Exploring the Website**:
  - Navigate through the header links (Home, Movie, TV Show, Web Series, Pricing) to explore different sections.
  - Use the language selector to switch between available languages (EN, AU, AR, TU).
  - Click the "Sign in" button to simulate user authentication (placeholder functionality).
  - Scroll through movie and series cards to view details like ratings and durations.
  - Interact with filter buttons in the "Upcoming" and "Top Rated" sections to sort content.
  - Use the CTA form to simulate subscription sign-up.

- **Development**:
  - Modify `style.css` to customize the theme (e.g., change `--citrine` for a different accent color).
  - Update `script.js` to add new interactive features, such as dynamic content loading.
  - Add new movie or series data in `index.html` by following the existing card structure.

---

## Screenshots

### Hero Section
![home](https://github.com/user-attachments/assets/965b717a-0dfa-4740-96c2-17c7e2bd4a89)

### Upcoming Movies
![upcoming_movies](https://github.com/user-attachments/assets/1307bc8a-67b9-4d03-b9ab-1d8f15c69c5a)

### Top-Rated Movies
![top_movies](https://github.com/user-attachments/assets/8adf8a67-bd46-43e6-9ce4-ec603a17300f)

### TV Series
![tv_series](https://github.com/user-attachments/assets/251e0107-2203-4ca7-9fa0-595edf7c5e59)

### Call-to-Action
![Stamp_card](https://github.com/user-attachments/assets/e1311f68-8816-4fd2-bf32-4e7417a16393)

---

## Contributing

Contributions are welcome! To contribute to Poppins:

1. **Fork the Repository**:
   Click the "Fork" button on the GitHub repository page.

2. **Clone Your Fork**:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Poppins.git
   ```

3. **Create a Branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Changes**:
   - Add new features, fix bugs, or improve documentation.
   - Ensure code follows the existing style and structure.

5. **Commit Changes**:
   ```bash
   git commit -m "Add your commit message"
   ```

6. **Push to Your Fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request**:
   Submit a pull request on the original repository   repository with a clear description of your changes.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

- **Author**: Hemant Batra
- **GitHub**: [HemantBatra873](https://github.com/HemantBatra873)
- **Email**: hemantbatra567@gmail.com

For questions, suggestions, or feedback, feel free to open an issue on the repository or contact me directly.

---

*Enjoy streaming with Poppins!*
