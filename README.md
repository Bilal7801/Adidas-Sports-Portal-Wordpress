# Adidas Sports Portal - Custom WordPress Theme

This project is a bespoke WordPress theme development focused on high-performance sports branding. It bridges the gap between a standard CMS and a feature-rich sports portal by utilizing the WordPress Customizer API and specialized plugin integrations.

## 🚀 Key Features
* **Dynamic Hero Slider:** Managed via custom theme options, supporting high-resolution images, titles, subtitles, and video link popups.
* **Event Management System:** Built using a Custom Post Type (CPT) for "Events." Includes backend fields for Event Date and Time, displayed through a custom-coded sidebar widget.
* **Advanced Navigation:** 3-level deep navigation support in the primary menu and a secondary header menu for membership/account links.
* **Integrated Social Hub:** Custom-styled widgets for "Latest Tweets" (X), Facebook Page integration, and real-time Weather/Clock displays.
* **Tabbed Content Areas:** A specialized section for Match Info, Results, and Schedules to keep the UI clean and organized.

## 🛠️ Technical Implementation

### 1. WordPress Customizer API
I utilized the Customizer API to provide site administrators with a "Live Preview" experience. Specific controls include:
* **Top Notification Bar:** Toggleable and editable notification text.
* **Logo Management:** Flexible logo uploading that persists across the header.
* **Footer Disclaimer:** A dedicated section to manage legal text and copyright information dynamically.

### 2. Custom Post Types & Meta Boxes
To handle the sports-specific data (like Events and Featured Players), I registered custom post types.
* **Events CPT:** Uses meta boxes to store `event_date` and `event_time`, which are then queried in the front-end sidebar.
* **Feature Post Slider:** A custom query filters specific posts to display in the mid-page carousel.

### 3. Plugin Integration & Widgets
The project leverages a mix of custom-coded widgets and popular plugins to achieve functionality:
* **Weather & Time:** Integrated via API-driven widgets.
* **Social Feeds:** Configured to pull live data while maintaining the dark-green brand aesthetic of the theme.
* **Search:** Integrated WordPress native search into the navigation bar with customized styling.

## 📂 Installation
1. Clone the repository.
2. Move the **`adidas-theme`** folder into your WordPress installation directory at `/wp-content/themes/`.
3. Activate the theme through the **WordPress Dashboard > Appearance > Themes**.
4. Install the recommended plugins (e.g., Advanced Custom Fields, Custom Post Type UI).
5. Navigate to **Appearance > Customize** to configure the Hero Slider, Logos, and Footer notifications.
