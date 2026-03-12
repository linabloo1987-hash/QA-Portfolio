# UI/UX Bug Reports

**Project:** E-commerce Website (або назва сайту, який тестували)
**Environment:** Windows 10, Google Chrome (Latest version)


## Bug 1: Button text misalignment in the Footer
* **Severity:** Low
* **Priority:** Low
* **Summary:** The "Subscribe" button text is shifted 5px to the left, violating the UI layout.
* **Steps to reproduce:**
  1. Open the main page.
  2. Scroll down to the footer section.
  3. Observe the "Subscribe" button.
* **Actual Result:** Text is not centered.
* **Expected Result:** Text should be perfectly centered according to the design mockup.


## Bug 2: Broken image aspect ratio on Mobile View
* **Severity:** Medium
* **Priority:** Medium
* **Summary:** Product images in the "New Arrivals" section appear stretched on screens smaller than 375px.
* **Steps to reproduce:**
  1. Open the website on a mobile device (or use DevTools).
  2. Navigate to the "New Arrivals" section.
* **Actual Result:** Images are distorted.
* **Expected Result:** Images should maintain their aspect ratio (`object-fit: cover`).
