# Lindsay Daka — Software Engineering Portfolio

## 1. Project Overview

This project is a personal portfolio website developed to showcase my background, skills, projects, and contact information as a Software Engineering student at Africa University.

The website was developed using HTML5 and CSS3, with Tailwind CSS utilities used alongside custom CSS to improve the design and responsiveness of the page.

The main objective is to create a clean, accessible, and responsive portfolio that provides information about me and my journey in software engineering.

## 2. Project Objectives

The objectives of this project are to:

* Apply HTML5 semantic elements to structure a webpage.
* Use CSS to style the website consistently.
* Apply the CSS box model to manage spacing and layout.
* Use Flexbox to arrange elements effectively.
* Use CSS Grid to create responsive card layouts.
* Implement responsive design for mobile, tablet, and desktop screens.
* Integrate Tailwind CSS utilities into the existing design.
* Test the website at different screen sizes.
* Maintain readable, organised, and reusable code.

## 3. Technologies Used

The following technologies and tools were used:

* **HTML5:** Structures the webpage and its content.
* **CSS3:** Controls colours, typography, spacing, layouts, and responsive behaviour.
* **Tailwind CSS:** Provides utility classes for common styling tasks and responsive spacing.
* **JavaScript:** Not required for the current page layout.
* **Visual Studio Code:** Used to write and edit the code.
* **Git:** Used for version control.
* **GitHub:** Used to host the project repository.
* **Live Server:** Used to preview the website locally in a browser.

## 4. Website Structure

The portfolio contains the following sections:

### Header

The header displays my profile picture, name, professional subtitle, introductory statement, and navigation links.

The navigation links allow visitors to move directly to the Home, About, Skills, and Contact sections.

### About Me

This section introduces me as a Software Engineering student at Africa University.

It describes my interests in web technologies, user interface design, programming, and the use of artificial intelligence in software development.

It also includes a list of personal and academic facts.

### Skills and Projects

This section contains two main cards.

**Programming Languages:** Displays the technologies I am learning, including HTML, CSS, JavaScript, and Python.

**Recent Project:** Describes my Student Portfolio Website and the skills practised during its development.

### Contact

The Contact section provides my contact information and a form where visitors can enter their name, email address, phone number, and message.

The contact information and message form are arranged in separate cards to improve readability and organisation.

The form includes labels, input types, and basic HTML validation attributes.

### Footer

The footer displays the copyright notice and a link that allows visitors to return to the top of the page.

## 5. CSS Foundations and Box Model

Custom CSS is used to control the website's appearance and layout.

The CSS box model is applied through properties such as:

* `margin` to create space outside elements.
* `padding` to create space inside elements.
* `border` to define element boundaries.
* `border-radius` to create rounded corners.
* `box-sizing` to manage element dimensions.

CSS variables are used to maintain consistent colours throughout the website.

Typography, spacing, background colours, and borders are selected to create a consistent visual design.

The profile image and content cards are styled to maintain a clear visual hierarchy.

## 6. Flexbox and CSS Grid

Flexbox and CSS Grid are used for different layout purposes.

### Flexbox

Flexbox is used in the navigation links and skills list.

In the navigation, Flexbox arranges the links horizontally, maintains consistent spacing, and allows them to wrap when necessary.

In the skills list, Flexbox arranges the individual skill labels neatly and allows them to wrap onto additional lines when space is limited.

Flexbox is suitable for these layouts because the elements need to be arranged along a row or wrapped naturally.

### CSS Grid

CSS Grid is used in the Skills and Projects section through the `.skills-grid` class.

It organises the programming skills and project cards into a responsive layout.

CSS Grid is also used in the Contact section to arrange the contact information card and message form card.

On smaller screens, the contact cards are stacked vertically. On wider screens, they are displayed side by side.

Grid is suitable for these sections because it allows the cards to be organised into columns while adapting to the available screen space.

## 7. Responsive Design

The website uses a mobile-first approach to responsive design.

The initial CSS rules provide the layout for smaller screens. Additional styling is applied through media queries when the screen becomes wider.

Custom CSS media queries are used to adjust the layout at different screen sizes.

The website is designed to:

* Keep content within the available screen width.
* Allow navigation links and skills to wrap when necessary.
* Resize and arrange content appropriately.
* Display cards in a suitable layout for different devices.
* Prevent unwanted horizontal scrolling.
* Maintain readable text and usable form controls.

### Responsive Breakpoints

The following screen widths were used for testing:

* **375px — Mobile:** Tested. The content fits within the screen without horizontal scrolling.
* **768px — Tablet:** Tested. The responsive layout works correctly at this screen size.
* **1280px — Desktop:** Tested. The page displays correctly on a wider screen.

These tests help verify that the website adapts to mobile, tablet, and desktop screen sizes.

## 8. Tailwind CSS Approach

Tailwind CSS is used alongside custom CSS to style the portfolio.

Tailwind utilities are applied to the header, About Me section, Contact section, footer, and Send Message button.

Examples of Tailwind utility classes used include:

* `text-center` for text alignment.
* `px-4` for horizontal padding.
* `py-8` for vertical padding.
* `md:px-8` for responsive horizontal padding.
* `md:p-8` for responsive padding.
* `bg-teal-800` for the button background.
* `text-white` for white button text.
* `rounded-lg` for rounded corners.
* `hover:bg-teal-700` for the button's hover background.
* `transition-colors` for colour transitions.

Responsive variants such as `md:px-8` and `md:p-8` adjust spacing at the medium breakpoint and above.

### Tailwind and Custom CSS Division

Tailwind CSS handles common styling tasks, including text alignment, padding, button colours, rounded corners, and responsive spacing.

Custom CSS in `style.css` controls the overall visual design, colour variables, profile image styling, navigation layout, card appearance, Flexbox and Grid layouts, form styling, and custom responsive media queries.

This division allows Tailwind utilities to simplify common styling tasks while custom CSS provides more detailed control over the portfolio's appearance and layout.

Tailwind CSS is generated locally and included through the `tailwind.css` stylesheet rather than being loaded from a CDN.

## 9. Contact Form

The contact form contains the following fields:

* Full Name
* Email Address
* Phone Number
* Message

The form uses HTML input types and validation attributes to improve the accuracy of the information entered.

The input fields and message area are styled consistently, with spacing between the labels and controls.

The form currently uses a placeholder action and does not send messages to an email address. A backend service or form-processing integration would be needed to enable actual message submission.

## 10. Testing and Code Quality

Testing was performed to check the layout and responsiveness of the website.

### Responsive Testing

The website was tested at the following viewport widths:

| Device category |  Width | Result |
| --------------- | -----: | ------ |
| Mobile          |  375px | Passed |
| Tablet          |  768px | Passed |
| Desktop         | 1280px | Passed |

The layout was checked to ensure that content fits within the available screen width and that horizontal scrolling does not occur unnecessarily.

### Code Quality

The following practices were applied during development:

* Use of semantic HTML elements.
* Consistent indentation and code formatting.
* Use of descriptive class names.
* Use of meaningful alternative text for the profile image.
* Use of labels for form controls.
* Use of appropriate input types and validation attributes.
* Separation of HTML structure and CSS styling.
* Use of reusable CSS rules and variables.
* Use of responsive media queries.

The browser console should be checked for unexpected errors before submission. HTML and CSS should also be reviewed for syntax errors and inconsistencies.

## 11. Project Files

The main project files include:

| File                 | Purpose                                                             |
| -------------------- | ------------------------------------------------------------------- |
| `profile2.html`      | Contains the portfolio's HTML structure and content.                |
| `style.css`          | Contains custom styling and responsive media queries.               |
| `tailwind-input.css` | Contains the Tailwind CSS input directive.                          |
| `tailwind.css`       | Contains the locally generated Tailwind CSS utilities.              |
| `profile.jpg`        | Profile picture displayed in the header.                            |
| `package.json`       | Contains project package information and dependencies.              |
| `package-lock.json`  | Records the installed package dependency versions.                  |
| `README.md`          | Documents the project, technologies, layout decisions, and testing. |
| `.gitignore`         | Specifies files and folders Git should ignore.                      |

## 12. Running the Project Locally

To run the project locally:

1. Clone or download the repository.

2. Open the project folder in Visual Studio Code.

3. Install the required Node.js dependencies by running:

   ```bash
   npm install
   ```

4. Generate the Tailwind CSS stylesheet by running:

   ```bash
   npx @tailwindcss/cli -i ./tailwind-input.css -o ./tailwind.css
   ```

5. Open `profile2.html` in a browser or use the Live Server extension in Visual Studio Code.

If you want Tailwind to regenerate the stylesheet automatically while editing, run:

```bash
npx @tailwindcss/cli -i ./tailwind-input.css -o ./tailwind.css --watch
```

Keep the watch command running while you make changes to the HTML or Tailwind input file.

## 13. Version Control and GitHub

Git was used to track changes during development, while GitHub hosts the project repository.

The project repository is:

https://github.com/lindsaydaka74-spec/lindsay-daka-profile

The updated portfolio should be committed and pushed to the same repository used for Assignment 1.

Meaningful commits should document the development stages, including responsive styling, Tailwind integration, contact layout improvements, documentation, and final testing.

## 14. Conclusion

This project demonstrates the application of HTML5, CSS3, Flexbox, CSS Grid, responsive design, and Tailwind CSS in developing a personal portfolio website.

The combination of Tailwind utilities and custom CSS provides a flexible approach to styling and layout.

Testing across mobile, tablet, and desktop screen sizes helps ensure that the website remains usable on different devices.

The project also provides an opportunity to practise code organisation, accessibility, version control, and documentation as part of my software engineering studies.
