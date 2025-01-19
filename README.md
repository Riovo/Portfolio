 Portfolio Website

This repository contains the codebase for a responsive and interactive portfolio website built with HTML, CSS, JavaScript, and PHP. The website includes dynamic features like a contact form, animations, and dark mode support.

## Features

- **Responsive Design:** Optimized for various screen sizes and devices.
- **Dynamic Contact Form:** Captures user inquiries and sends data to the server via PHP.
- **Scroll Reveal Animations:** Smooth animations for content appearance using the ScrollReveal library.
- **Dark Mode Support:** Users can toggle between light and dark themes.
- **Mobile Navigation:** User-friendly navigation menu for smaller devices.

## File Structure

- `index.php`: The main entry point of the website. It includes the PHP backend logic for form handling.
- `connect.php`: Handles database connectivity for storing user inquiries.
- `main.js`: Contains JavaScript for user interactions, including menu toggles, theme switching, and animations.
- `styles.css`: The main stylesheet for the website's design and layout.
- `remixicon.css`: Provides access to the Remix Icon library for icons used across the site.
- `scrollreveal.min.js`: A library for scroll animations, enabling elements to appear dynamically as the user scrolls.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- PHP 7.4 or higher
- A web server (e.g., Apache or Nginx)
- A database server (e.g., MySQL)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/portfolio-website.git
  ```
2. Place the files in your web server's root directory (e.g., `/var/www/html`).
3. Configure the database in `connect.php`:
   ```php
   $conn = new mysqli('hostname', 'username', 'password', 'database');
   ```
4. Start your web server and navigate to `http://localhost/` in your browser.

## Usage

1. **Navigate the Website:** Explore the homepage, about section, projects, and contact form.
2. **Send a Message:** Use the contact form to send a message. Ensure the database connection is configured for the data to be stored.

## Customization

- Modify `styles.css` for design changes.
- Update icons using the `remixicon.css` library.
- Add or update animations in `main.js` with ScrollReveal.

## Libraries and Tools

- [Remix Icon](https://remixicon.com): Icon library.
- [ScrollReveal](https://scrollrevealjs.org): JavaScript animation library.
- [Google Fonts](https://fonts.google.com): Custom fonts.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
