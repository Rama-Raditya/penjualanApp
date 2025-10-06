# TODO List for Adding Cart, Checkout, and WhatsApp Integration

## 1. Update index.html
- [x] Add cart modal HTML structure (view cart items, quantities, remove buttons, total price, checkout button)
- [x] Add checkout form modal HTML (fields: name, phone, address, submit button)

## 2. Update script.js
- [x] Add functions to show/hide cart modal
- [x] Add functions to display cart items in modal (with quantity, remove)
- [x] Add event listeners for cart icon click to open cart modal
- [x] Add checkout button handler to open checkout modal
- [x] Add checkout form submission handler: collect data, generate formatted message, open WhatsApp
- [x] Update cart array to handle quantities (change to object with id and qty)
- [x] Add remove from cart functionality

## 3. Update style.css
- [x] Add styles for cart modal and checkout modal if needed

## 4. Testing
- [x] Test adding to cart, viewing cart, removing items
- [x] Test checkout form submission and WhatsApp link generation
