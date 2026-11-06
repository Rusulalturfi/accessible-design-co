# Accessible Design Co.

## Project Description
A responsive webpage for a fictional company, built with HTML and CSS. It includes Home, About Us, Services, and Contact sections.

## How to View
Download the project, keeping the files and images folder together. Open index.html in a web browser.

## Accessibility Features
-Semantic HTML elements and a clear heading hierarchy.
- A navigation bar with an ARIA label.
- Alternative text for the company logo.
- Decorative service icons hidden from screen readers.
- Form labels connected to their inputs.
- Message instructions connected using aria-describedby.
- Required fields and email format validation.
- Visible keyboard focus styles.
- Flexbox, Grid, and media queries for responsive layouts.

## Notes
The contact form demonstrates browser validation but does not send messages. The email address and social media links are placeholders.

## Image Credit
Background photo by Domenico Loia on Unsplash.



### 1. What accessibility challenges did you face, and how did you address them?

I had difficulty understanding form labels and ARIA attributes. Part of my textarea code appeared as text on the webpage because I had placed attributes outside the opening tag. I corrected the tag and used matching for and id values for the labels and inputs. I also connected the message instructions using aria-describedby. Adding keyboard focus styles was challenging because I misspelled focus-visible and missed a closing brace. I reviewed and corrected these mistakes.
### 2. How did you ensure that your design was responsive and accessible to all users?

I used Flexbox for the navigation, Grid for the service cards, and media queries at 600px and 1024px. My Grid layout did not work at first because I wrote “gird” instead of “grid” in the CSS class name. After checking the HTML and CSS, I corrected the names to match, and the layout worked.

I checked the page at a mobile width of 400px. The navigation became vertical, the cards stacked in one column, and the form stayed within the screen. I also tested required fields and email validation.
### 3. What tools or resources did you find most helpful during this project?

VS Code helped me edit my code and find mistakes. Microsoft Edge DevTools helped me check the mobile layout, although I needed practice finding and using the device view. Viewing the page in the browser helped me notice problems and check my corrections. I also used Unsplash for the background photo and Paint to create the logo.