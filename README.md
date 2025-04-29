

# Game Night Event Center Website

**Project Overview:**
This project is a multi-page static website built using HTML and CSS for a "Game Night" themed event center. It fulfills the requirements of the HTML & CSS Project module, demonstrating skills in structuring content, styling elements, and implementing responsive design.

**Theme:**
The chosen theme for the event center is "Game Night," reflecting a cozy, retro, and fun atmosphere for gaming enthusiasts.

**Website Structure:**
The website includes the following required pages:

1.  **Home Page (`index.html`):** Serves as the landing page, introducing the event center, highlighting its theme, and showcasing featured events.
2.  **Events Page (`events.html`):** Provides a detailed list of upcoming game night events with descriptions and images.
3.  **Menu Page (`menu.html`):** Displays the food and drink options available during events in a structured table format.
4.  **Location Page (`location.html`):** Gives information about the event center's location, including address, contact details, and a map.
5.  **Contact Us Page (`contact.html`):** Features a form for visitors to submit inquiries or feedback.
6.  **(Bonus) Error Page (`errorpage.html`):** A simple page displayed in case a requested resource is not found.

**Project Requirements Met:**

*   **Navigation Bar:** A consistent navigation bar with links to all main pages (`Home`, `Events`, `Menu`, `Location`, `Contact`) is present on `index.html`, `events.html`, `menu.html`, `location.html`, and `contact.html`.
*   **Home Page:** Includes a banner/hero image (`.banner`, `.hero-image`), a welcome message (`.welcome`), and a featured events section linking to the Events page (`.featured-events`, `.event-link`). An "About Us" section is incorporated into the Contact page.
*   **Events Page:** Uses semantic-like containers (`.events`, `.event-container`, `article.event`) for structuring event details. Lists more than three events with images and descriptions. Links to the Contact page for RSVP/inquiry.
*   **Menu Page:** Features a table (`.menu-table`) displaying menu items with Dish, Price, and Servings columns, plus an image column. Includes striped rows (`:nth-child(even/odd)`) and hover effects for better readability.
*   **Location Page:** Contains address, phone, email, and hours (`.location-details`) and an embedded Google Map (`iframe.map-embed`) within an image-styled container (`.map-image`). Content is visually centered using CSS margins.
*   **Contact Us Page:** Provides a form (`form.form`) with fields for Name, Email, and Feedback/Inquiry (via a textarea). Includes additional fields for Birthdate, Preferences (checkboxes/radios), and how the user heard about the event (radios/text). Form validation (`required`, `pattern`) is applied. Sample data is pre-filled. Fields are grouped using `fieldset` and `legend`.
*   **Responsive Design:** Utilizes CSS media queries (`@media (max-width: 700px)`, `@media (max-width: 800px)`, `@media (min-width: 801px)`) to adjust layouts for different screen sizes. Employs `display: flex` extensively for creating flexible and responsive layouts, along with properties like `flex-direction`, `justify-content`, and `align-items`.
*   **CSS Styling:** The CSS (`styles.css`) styles the form, uses flexbox for content organization, adds hover effects to various interactive elements (links, buttons, images, menu rows/items), includes custom cursors, and ensures the overall design adapts to different screen sizes. Vibrant gradients, box shadows, and border styles contribute to the themed presentation.

* **Attributions:**
<a href="https://www.flaticon.com/free-icons/videogames" title="videogames icons">Videogames icons created by Freepik - Flaticon</a>