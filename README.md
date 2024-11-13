#SHOE-STORE

An E-Commerce website which is being built using HTML, CSS, JavaScript . I have also integrated a payment gateway

**CSS Styling Tweaks:**

Ensure the cart icon is aligned consistently by adding styles for different screen sizes in style.css.

**Use display:** none for the payment section initially and only show it when the "BUY NOW!" button is clicked.

For a subtle font choice, keep Lato or consider Google Fonts like "Poppins" or "Montserrat", which offer a clean, modern look.

**JavaScript Optimization:**

**Event Listeners:** Rather than re-selecting elements each time, move common selections (like cartCount, cartPopup) outside function scopes for better performance.

**Color Selection Logic:** Add a check in the currentProductColors.forEach loop to handle cases where a product has fewer than two colors.

**Responsive Design:**

Test the navigation, sliders, and cart pop-up on mobile devices to ensure they adjust seamlessly. Consider hiding the cart pop-up or moving it to the bottom of the screen on smaller screens for accessibility. 

**Accessibility:**

Add aria-label attributes to important interactive elements like the cart icon, close buttons, and product buttons.

Use role="button" for div elements acting as buttons for better screen reader support.

**Technologies**

List the main technologies or libraries used in your project:

**JAVASCRIPT:** For building the user interface.
**HTML:** For building a structure.
**CSS:** For desinging the site.

