# 📄 Mock Requirements Document (BRD)

> **Project Name:** Magento Manual Testing Practice
> **Source:** This document is generated by ChatGPT for practice and portfolio purposes.
> **Purpose:** To provide mock business requirements for designing test cases.

---

## 🟩 1. Landing Page / Home

* **\[BR-001]** Homepage must load within 3 seconds.
* **\[BR-002]** Main banner must display with clickable CTA button ("Shop Now").
* **\[BR-003]** Main menu includes: What's New, Women, Men, Gear, Training, Sale.
* **\[BR-004]** Footer must include links: Privacy Policy, Contact Us, About Us.
* **\[BR-005]** A "Sign Up for Newsletter" field must be present and functional.

---

## 🟨 2. Register / Login / Logout

* **\[BR-101]** Users must input First name, Last name, Email, Password to register.
* **\[BR-102]** Password must be at least 8 characters long.
* **\[BR-103]** Duplicate emails must not be allowed to register.
* **\[BR-104]** Users must be able to login/logout from the "Sign In / Sign Out" menu.
* **\[BR-105]** After successful login, the username should appear at the top right corner.

---

## 🔵 3. Search Product

* **\[BR-201]** Search bar must be available in the header on all pages.
* **\[BR-202]** Minimum 3 characters must be entered before performing a search.
* **\[BR-203]** At least one product matching the keyword must be displayed.
* **\[BR-204]** If no product is found, display "Your search returned no results."

---

## 🔶 4. Filter / Sorting

* **\[BR-301]** Filters must be available in sidebar (e.g., Category, Size, Color, Price).
* **\[BR-302]** Sort options: Price (Low to High), Name (A-Z), Newest.
* **\[BR-303]** Multiple filters can be applied simultaneously.
* **\[BR-304]** Users must be able to clear all filters in one click.

---

## 🔴 5. Product Detail Page

* **\[BR-401]** Clicking on a product must lead to the Product Detail page.
* **\[BR-402]** Must display name, price, description, size, color, stock.
* **\[BR-403]** Users must be able to select size and color.
* **\[BR-404]** If out of stock, the "Add to Cart" button must be disabled.

---

## 🔳 6. Add to Cart / View Cart

* **\[BR-501]** Clicking "Add to Cart" must show a confirmation pop-up.
* **\[BR-502]** Cart icon must reflect the correct number of items.
* **\[BR-503]** View Cart page must display product image, name, price, quantity, total.
* **\[BR-504]** User must be able to remove products from the cart.

---

## 🔺 7. Checkout & Payment Simulation

* **\[BR-601]** Only logged-in users can proceed to checkout.
* **\[BR-602]** Billing Address, Shipping Address, Payment Method fields are required.
* **\[BR-603]** Payment is simulated only (no real transaction).
* **\[BR-604]** Upon successful order, show Order Number and Order Summary.

---

## 🟧 8. Wishlist

* **\[BR-701]** User must be logged in to use Wishlist.
* **\[BR-702]** "Add to Wishlist" button must appear on the Product Detail page.
* **\[BR-703]** Wishlist items can be moved to Cart.
* **\[BR-704]** User can remove items from Wishlist.
* **\[BR-705]** If Wishlist is empty, display: "You have no items in your wishlist."

---

## 🟩 9. Responsive Design (Desktop)

* **\[BR-801]** Website must render correctly on Chrome and Firefox (1920x1080).
* **\[BR-802]** No element should overlap on Product, Cart, Checkout pages.
* **\[BR-803]** Homepage must not overflow, and scroll bars must work normally.

---

### ℹ️ Note:

This document is a mock business requirement generated by ChatGPT for portfolio usage by **Nutchaphon K.** Feel free to reference this as "ChatGPT-generated practice requirement" in your GitHub project.
