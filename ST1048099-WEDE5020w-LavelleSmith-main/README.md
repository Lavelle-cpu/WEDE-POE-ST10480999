# ST1048099-WEDE5020w-LavelleSmith

1- Features

- Responsive Design: Works on various screen sizes
- Five Main Pages: Home, About Us, Our Services, Enquiry, and ContactUs
- Embedded Video: Motivational content from YouTube
- Clean Navigation: Easy access to all site sections
- Professional Layout: Modern and appealing design for fitness audience

1.1- Timeline and milestone

- Research & Planning Complete	29 July 2025
- Wireframes and Design Mock-ups	10 August 2025
- Development Begins	12 August 2025
- Functional Website Prototype	24 August 2025
- Testing & Feedback	27 August 2025
- Final Website Submission	29 August 2025

1.2- Goals and objectives

- Increase website traffic by 40% over the next 6 months.
- Generate new client leads through a contact form and newsletter sign-up.
- Promote personal training services and online programs.
- Provide valuable fitness content (e.g., blog posts, exercise videos, and health tips).
- Sell digital fitness plans and branded merchandise online.
- KPIs: website visits, newsletter sign-ups, form submissions, and digital sales.


2-Technologies Used

- HTML5
- CSS (to be implemented)
- Responsive design principles

3-Pages Overview

3.1- Home Page (index.html)

- Welcome message and company introduction
- Embedded motivational video
- Company branding and imagery
- Navigation to all other pages

3.2- About Us (about.html)

- Information about the company and trainers
- Mission and vision statment

3.3- Our Services (services.html)

- Details of training programs offered
- Package information

3.4- Enquire (enquiry.html)

- Contact form for potential clients
- Service inquiry system

3.5- Contact Us (contact.html)

- Company contact information
- Location details and map

4- References

- CS Sports internal documents and marketing material
- Market research from South African fitness and wellness websites
- HostAfrica Hosting Plans
- Typography and colour theory resources (Google Fonts, Adobe Colour)
- HostAfrica. (2025). SSD Shared Web Hosting Plans. [online] Available at: https://www.hostafrica.co.za/web-hosting/ [Accessed 29 Jul. 2025].
- ThemeIsle. (2025). Astra WordPress Theme Pricing. [online] Available at: https://wpastra.com/pricing/ [Accessed 29 Jul. 2025].
- WordPress. (2025). Top Plugins for WordPress Websites. [online] Available at: https://wordpress.org/plugins/ [Accessed 29 Jul. 2025].
- Google Fonts. (2025). Montserrat Font – Google Fonts. [online] Available at: https://fonts.google.com/specimen/Montserrat [Accessed 29 Jul. 2025].
- Google Fonts. (2025). Open Sans Font – Google Fonts. [online] Available at: https://fonts.google.com/specimen/Open+Sans [Accessed 29 Jul. 2025].
- Adobe. (2025). Adobe Color – Create and Explore Color Palettes. [online] Available at: https://color.adobe.com/ [Accessed 29 Jul. 2025].
-  Canva. (2025). Color Meanings and Color Theory. [online] Available at: https://www.canva.com/colors/color-meanings/ [Accessed 29 Jul. 2025].


Design Features

Color Scheme

Primary Colors: Deep blue (#2c3e50), Bright blue (#3498db), Red accent (#e74c3c) Gradient Backgrounds: Purple-to-blue gradient for body, various section gradients Text Colors: Dark gray (#333) for content, white for navigation Typography

Font Family: Arial, sans-serif fallback Line Height: 1.6 for optimal readability Responsive Font Sizes: Scales appropriately on different devices

Page-Specific Styling

Home Page (home-page)

Gradient text effects for main heading Card-style content containers with shadows Hover effects on images and navigation Centered layout with responsive video embedding About Page (about-page)

Colored borders for section differentiation Background highlights for paragraphs Consistent spacing and typography hierarchy Services Page (services-page)

Animated list items with hover effects Color-coded borders for different list types Gradient text for main heading Contact Page (contact-page)

Form styling with focus states Map embedding with custom borders Consistent spacing and alignment Enquiry Page (enquiry-page)

Centered form layout with maximum width Interactive form elements with transitions Gradient buttons with hover effects

Technical Features

Layout & Structure

CSS Reset: Box-sizing border-box for consistent sizing Flexbox: Used for navigation and content containers Grid: Potential for future layout enhancements Responsive Design

Mobile First: Base styles work on small screens Tablet: 768px breakpoint for navigation adjustments Mobile: 480px breakpoint for smaller screen optimizations Interactive Elements

Hover Effects: Scale transformations, color changes Transitions: Smooth 0.3s easing on interactive elements Focus States: Accessible form field highlighting Visual Enhancements

Box Shadows: Layered shadows for depth Border Radius: Consistent rounded corners (8-15px) Backdrop Filter: Glassmorphism effect on header/footer

File Structure Integration

This CSS file should be linked in all HTML pages:

html

Compatible with HTML pages:
index.html (Home) about.html (About Us) services.html (Our Services) enquiry.html (Enquire) contact.html (Contact Us)

Browser Compatibility

Modern Browsers: Chrome, Firefox, Safari, Edge (latest versions) CSS Features Used:

CSS Grid and Flexbox CSS Variables (potential for future enhancement) CSS Filters and Backdrop Filters CSS Animations and Transitions

Customization Guide

Color Changes

Modify these CSS custom properties (if converted) or directly edit:

css /* Primary colors */ header { background: #your-color; } nav a { background: #your-accent; } Font Changes

Replace the font family:

css body { font-family: 'Your-Font', sans-serif; } Layout Adjustments

Modify container widths and spacing:

css main { max-width: 1400px; } /* Increase max width / nav { gap: 3rem; } / Increase navigation spacing */

Responsive Breakpoints

≥ 1200px: Desktop optimized layout 768px - 1199px: Tablet adjustments 480px - 767px: Mobile landscape < 480px: Mobile portrait optimizations

Performance Notes

File Size: Optimized single CSS file Render Blocking: Consider async loading for large sites Animation Performance: Uses transform for better GPU acceleration

Accessibility Features

Color Contrast: Meets WCAG guidelines Focus Indicators: Clear focus states for keyboard navigation Text Scaling: Responsive to browser text size settings