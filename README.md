
# Napenda Africa Safaris Website

## Description

This repository contains the source code for the single-page website for Napenda Africa Safaris, a tour company specializing in East African safari experiences. The website showcases their services, destinations, company information, and provides contact methods.

## Features

* **Single-Page Layout:** Smooth scrolling navigation between sections (Home, About Us, Tours, Why Us?, Contact).
* **Responsive Design:** Adapts to various screen sizes using Tailwind CSS for optimal viewing on desktop, tablet, and mobile devices.
* **Dark Mode Support:** Automatically adapts to the user's system preference for light or dark mode.
* **Content Sections:**
    * Hero section with background image.
    * Introduction and About Us.
    * Safari Tours overview and activities.
    * Popular Destinations showcase with images.
    * "Why Choose Us?" highlights.
    * Contact details and enquiry form.
    * Footer with copyright and social media links.
* **Interactive Elements:**
    * Collapsible mobile navigation menu.
    * Clickable social media icons (WhatsApp, LinkedIn, YouTube) in the footer with color change effect.
    * Dynamic copyright year update.

## Tech Stack

* **HTML5:** Structure and content.
* **Tailwind CSS (v3 via CDN):** Utility-first CSS framework for styling and responsiveness.
* **JavaScript:** For mobile menu toggle, social icon click effects, and dynamic year update.
* **Google Fonts:** Barlow Condensed (headings) and Open Sans (body text).
* **SVG Icons:** Inline SVGs used for footer social media icons.
* **Lucide Icons (Font):** Used for icons in contact details and feature highlights.

## File Structure

The project assumes the following basic structure:

.├── images/             # Folder containing all website images│   ├── logo.png│   ├── hero-image.jpg│   ├── team.jpg        # Placeholder - replace with actual image│   ├── masai-mara.jpg│   ├── amboseli.jpg│   ├── lake-nakuru.jpg│   ├── samburu.jpg│   ├── tsavo-east.jpg│   ├── tsavo-west.jpg│   ├── tanzania.jpg│   ├── zanzibar.jpg│   ├── whatsapp.png    # Used for SVG generation reference, now replaced by SVG│   ├── linkedin.png    # Used for SVG generation reference, now replaced by SVG│   └── youtube.png     # Used for SVG generation reference, now replaced by SVG│   └── ... (any other images)│├── index.html          # The main HTML file (or rename as needed)└── README.md           # This file
**Important:** Ensure your image filenames within the `images/` folder exactly match those referenced in the `index.html` file (e.g., `hero-image.jpg`, `masai-mara.jpg`). It's recommended to use lowercase and hyphens instead of spaces. You will also need to add an actual image named `team.jpg` (or update the `src` in `index.html` if you use a different name).

## Getting Started

This is a static website built with HTML, Tailwind CSS (via CDN), and vanilla JavaScript.

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Navigate to the directory:**
    ```bash
    cd <repository-name>
    ```
3.  **Ensure File Structure:** Make sure the `images` folder containing all necessary images is present in the same directory as the `index.html` file.
4.  **Open in Browser:** Simply open the `index.html` file in your web browser to view the website locally.

No build process or local server is strictly required due to the use of CDNs for Tailwind and fonts.

## Usage

Navigate through the different sections of the website using the links in the header navigation bar. The mobile menu provides access on smaller screens. The contact form allows users to send enquiries (requires backend integration to be functional). Social media links in the footer connect to the respective platforms (ensure links are updated).

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for bugs or feature suggestions. (You can expand this section if you have specific guidelines).

## License

Consider adding a license file (e.g., MIT License) to define how others can use your code.
