# UI-test
# E-Commerce UI Design Specification

This document describes the full set of UI screens for a modern, responsive e-commerce website. All pages follow a unified design system using:

- **Primary color:** #3498db  
- **Secondary colors:** #2ecc71, #e74c3c  
- **Neutral background:** #f8f9fa, #dee2e6  
- **Font:** Inter or Roboto  
- **Design tokens:** Rounded corners (8px), soft shadows, consistent spacing, responsive layout

---

## 1. Homepage
- Hero banner with promotional CTA
- Horizontal product filter bar (category, price, rating, sort)
- Product grid (4-column, responsive)
- Featured products carousel
- Newsletter signup section
- Footer with About, Support, Socials, Payment icons

## 2. Category Page
- Sidebar filters (collapsible)
- Active filter tags + clear-all option
- Product grid with hover effects
- Sort-by dropdown
- Pagination or "Load More" button

## 3. Product Detail Page
- Product image gallery with zoom
- Title, price, rating, variant selection, quantity selector
- Add to Cart, Wishlist, Buy Now buttons
- Tabbed section: Description, Specifications, Reviews
- Related Products section

## 4. Cart Page
- List of selected products with quantity update & remove
- Promo code input
- Cost breakdown (subtotal, shipping, discount, total)
- Proceed to Checkout CTA

## 5. Checkout Page
- Highlighted product(s) at the top for context
- Multi-step form: Shipping Info → Shipping Method → Payment Method
- Order summary (right side)
- Secure payment badges
- “Place Order” CTA and “Back to Cart” link

## 6. Login Page
- Centered card layout with:
  - Email, Password input
  - Remember Me checkbox
  - Forgot Password link
  - Login CTA
  - Optional social login
  - Register redirect link

## 7. Register Page
- Similar layout to Login
- Inputs: Name, Email, Password, Confirm Password
- Terms & Policy agreement checkbox
- Register button
- Login redirect link

## 8. User Profile Page
- Sidebar navigation:
  - Account Info
  - My Orders
  - Wishlist
  - Addresses
  - Change Password
  - Logout
- Content area: view/edit profile, order list, address manager

## 9. Order Detail Page
- Order info: ID, status, date
- Shipping/payment details
- Item list with thumbnails and totals
- Download invoice and reorder options

## 10. Wishlist Page
- Grid of saved items
- Add to cart or remove

## 11. Search Results Page
- Results for search term
- Product grid
- Optional filters

## 12. 404 Page
- Friendly message
- Back to homepage button
- Optional search bar or featured products

## 13. Static Pages
- **About Us:** Company story, team section
- **Contact Us:** Embedded map, contact info, form
- **Terms & Privacy Policy:** Full-width legal content
- **Return & Refund Policy (optional)**

---

## 14. Admin Dashboard (for administrators only)
- Vertical sidebar:
  - Dashboard, Orders, Products, Users, Categories, Analytics, Settings, Logout
- Top header:
  - Admin avatar and dropdown menu
- Main content:
  - Dashboard: metric cards (Sales, Orders, Users)
  - Orders: data table with filters and actions
  - Products: searchable list with "Add Product"
  - Users: status toggle, role badges
  - Analytics charts (optional)

---

## Responsiveness
All pages are optimized for desktop and large tablets. Buttons are touch-friendly. Typography and grid layout are fluid for resolution scaling.

---

## Reusability & Style Consistency
All components are designed to be modular, consistent in spacing, color, and interaction states (hover, focus, disabled). Can be implemented in Figma, Tailwind CSS, or any component-based frontend framework.

---

## Author
UI Prompt created by Trợ lý Miu — under Daddy’s direction 💛
