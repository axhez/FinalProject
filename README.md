# Charity Website Project
#### Video Demo:  <URL HERE>
#### Description:

## Overview
This project is a Charity Website designed to facilitate donations, provide information about the charity, and allow users to contact the organization. The website is composed of several HTML files, a CSS stylesheet for styling, and a SQL file for database operations.

## Project Files
### HTML Files
1. **index.html**
   - This is the main landing page of the website. It contains an introduction to the charity, a hero section with a background image, and links to other sections of the site.
2. **about.html**
   - This page provides detailed information about the charity, its mission, vision, and team members. It includes a hero section and various content sections that describe the charity's activities and goals.
3. **contact.html**
   - This page allows users to get in touch with the charity. It includes a form for submitting inquiries and a section with contact details. The form includes validation to ensure all required fields are filled out correctly.
4. **donations.html**
   - This page is dedicated to displaying donation information. It includes a table that shows donor names, emails, and the amounts donated. The data is fetched from a server-side script using AJAX.

### CSS Files
1. **style.css**
   - This file contains the main styles for the website, including typography, layout, and color schemes. It defines the appearance of various elements such as headers, navigation bars, buttons, and forms.
2. **responsive.css**
   - This file contains styles to ensure the website is responsive and looks good on various screen sizes, from mobile devices to desktops. It includes media queries that adjust the layout and styling of elements based on the screen width.

### SQL File
1. **charity.sql**
   - This file contains SQL commands for setting up the database used by the website. It includes table definitions and sample data for the donations table.

## Design Choices
- **Responsive Design**: The use of `responsive.css` ensures that the website is accessible and user-friendly on all devices. Media queries are used to adjust the layout for different screen sizes.
- **AJAX for Data Fetching**: On the donations page, AJAX is used to fetch donation data from the server without reloading the page, providing a seamless user experience.
- **Form Validation**: The contact form includes client-side validation to ensure users provide valid input before submitting the form. This enhances the user experience by providing immediate feedback.
- **Modular CSS**: The CSS is split into two files, one for general styles and one for responsive styles, making it easier to maintain and update the design.

## Future Improvements
- **Backend Integration**: Integrate the website with a backend server to handle form submissions, process donations, and store contact inquiries.
- **Enhanced Security**: Implement security measures such as data sanitization, HTTPS, and protection against SQL injection for the backend.
- **Additional Features**: Add features such as user authentication, donation tracking, and a blog section to keep donors informed about the charity's activities.

By following this README.md template, you can thoroughly document your project, making it easier for others to understand and contribute to it.

