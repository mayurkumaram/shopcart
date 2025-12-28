# ShopCart — Test Website for Automation 🛍️🤖

This repository hosts a **test e-commerce website** deployed live at:  
**https://mayurkumaram.github.io/shopcart/** 🌐  
It’s used specifically for practicing and building **automation tests** (Playwright, Selenium, etc.).

> ⚠️ **Note:** This is *not* a real shopping site — it’s for QA/testing purposes only.

---

## 📌 About This Project

ShopCart simulates a basic shopping cart workflow typically found in e-commerce applications. You can use this site as a **target for automation test suites** covering common user journeys.

Typical flows you might automate include:  
✔️ Product browsing  
✔ Adding items to cart  
✔ Updating cart quantities  
✔ Removing items  
✔ Proceeding to checkout  
✔ Verifying UI elements and functional outcomes

This makes it ideal for testing frameworks like Playwright, Selenium, Cypress, Robot Framework, etc.

---

## 🔎 Example Test Scenarios

Here are some typical automation test scenarios you could build around this site:

### 🛒 Shopping Cart

- Add single or multiple items to the cart  
- Verify item count and total price  
- Check increasing/decreasing item quantity  
- Ensure items persist after navigation

### 🛍️ Checkout Flow

- Click “Proceed to Checkout” and reach the next page  
- Validate UI elements on checkout  
- Handle edge cases (empty cart, missing input, etc.)

### 🧠 Automation Best Practices

- Use Page Object Model (POM) or similar design patterns  
- Separate test logic from page definitions  
- Include assertions for both **success and failure paths**  
- Parameterize inputs for data-driven tests
