<div align="center">
	<a target="_blank" href="https://gitforcetalent.com">
        <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo-light.png&w=1920&q=75">
            <source media="(prefers-color-scheme: light)" srcset="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png&w=1920&q=75">
            <img alt="https://gitforcetalent.com" src="https://gitforcetalent.com/_next/image?url=%2Fimages%2Flogo.png">
        </picture>
	</a>
    <br />
    <br />
</div>

---

---


### QA Manual Testing Plan for Ecommerce Website

**Website URL:** [OpenCart Demo](https://demo.opencart.com/)

**Test Objective:** To verify the functionality, usability, and performance of the ecommerce website by manual testing and to generate a comprehensive report.



---

### Test Cases

#### 1. **Homepage**

- **Objective:** Ensure the homepage loads correctly and all elements are functional.
  
- **Test Steps:**
  1. Navigate to the homepage.
  2. Verify that all links, images, and text are displayed correctly.
  3. Check the header for navigation links (Home, Products, About Us, Contact Us).
  4. Verify the search bar functionality.
  5. Ensure the promotional banner is visible and links work.

- **Expected Result:** Homepage loads within 2 seconds. All elements should be correctly displayed and functional.

#### 2. **Product Search**

- **Objective:** Verify the search functionality.

- **Test Steps:**
  1. Enter a product name in the search bar.
  2. Click the search button.
  3. Check if relevant products are displayed.

- **Expected Result:** Relevant products should appear based on the search query.

#### 3. **Product Detail Page**

- **Objective:** Check product details and functionality.

- **Test Steps:**
  1. Navigate to a product detail page.
  2. Verify product title, images, price, description, and availability.
  3. Test "Add to Cart" button.
  4. Check "Reviews" section for accuracy.

- **Expected Result:** All product details are correct and the "Add to Cart" functionality works.

#### 4. **Shopping Cart**

- **Objective:** Ensure the shopping cart functions correctly.

- **Test Steps:**
  1. Add products to the cart.
  2. Verify the cart page displays correct items and total price.
  3. Test "Remove" functionality.
  4. Proceed to checkout.

- **Expected Result:** Items are added to the cart correctly, and the total price is accurate.

#### 5. **Checkout Process**

- **Objective:** Test the checkout process.

- **Test Steps:**
  1. Click on "Checkout" from the cart.
  2. Fill in shipping information.
  3. Enter payment details.
  4. Confirm the order.

- **Expected Result:** Order is processed successfully, and a confirmation page is displayed.

#### 6. **User Registration and Login**

- **Objective:** Test user registration and login functionality.

- **Test Steps:**
  1. Navigate to the registration page.
  2. Fill in all required fields and submit the form.
  3. Log out and log in with the new credentials.

- **Expected Result:** User registration and login should be successful.


#### 7. **Performance Testing**

- **Objective:** Check website loading speed and responsiveness.

- **Test Steps:**
  1. Use tools like Google PageSpeed Insights or Lighthouse to test loading speed.
  2. Record load time for homepage, product page, and checkout.

- **Expected Result:** The website should load within 3 seconds.

#### 8. **Security Testing**

- **Objective:** Ensure the website is secure.

- **Test Steps:**
  1. Test for SQL injection and XSS vulnerabilities.
  2. Check HTTPS/SSL certificates.

- **Expected Result:** No security vulnerabilities should be present.


---

### Reporting Template

**Report Structure:**

1. **Test Case ID:** [e.g., TC-001]
2. **Test Case Description:** [e.g., Homepage Loading Test]
3. **Tested By:** [Name]
4. **Date Tested:** [MM/DD/YYYY]
5. **Test Results:** [Pass/Fail]
6. **Issues Found:** [Details of any bugs or issues]
7. **Screenshots/Logs:** [Attach relevant screenshots or logs]
8. **Recommendations:** [Suggestions for improvements or fixes]

---

**Example Report Entry:**

- **Test Case ID:** TC-001
- **Test Case Description:** Homepage Loading Test
- **Tested By:** John Doe
- **Date Tested:** 07/26/2024
- **Test Results:** Pass
- **Issues Found:** None
- **Screenshots/Logs:** [Attach Screenshot]
- **Recommendations:** None

---
