# Test Cases — Amazon Website

## TC-001 — Search product with valid keyword
**Preconditions:** User is on Amazon homepage  
**Steps:**
1. Enter a valid product name in the search bar
2. Click the search button

**Expected Result:**
- Search results related to the product are displayed

---

## TC-002 — Search product with invalid keyword
**Preconditions:** User is on Amazon homepage  
**Steps:**
1. Enter an invalid or random keyword in the search bar
2. Click the search button

**Expected Result:**
- System displays a message indicating no results found or shows related suggestions

---

## TC-003 — Open product details page
**Preconditions:** Search results are displayed  
**Steps:**
1. Click on any product from the search results

**Expected Result:**
- Product details page opens successfully
- Product image, title, and price are visible

---

## TC-004 — Add product to cart
**Preconditions:** User is on a product details page  
**Steps:**
1. Click on the "Add to Cart" button

**Expected Result:**
- Product is added to the cart
- Confirmation message is displayed

---

## TC-005 — Validate cart item
**Preconditions:** Product has been added to the cart  
**Steps:**
1. Open the cart page

**Expected Result:**
- Selected product is listed in the cart with correct quantity

  ## TC-006 — Search with empty input
**Preconditions:** User is on Amazon homepage  
**Steps:**
1. Leave the search field empty
2. Click the search button

**Expected Result:**
- System should not perform a search
- User should see a validation message or stay on the same page

  ## TC-007 — Product unavailable
**Preconditions:** User is on a product details page  
**Steps:**
1. Open a product marked as unavailable or out of stock

**Expected Result:**
- Product availability status is clearly displayed
- User cannot add the product to the cart

## TC-008 — Add same product twice
**Preconditions:** User is on a product details page  
**Steps:**
1. Click "Add to Cart"
2. Click "Add to Cart" again

**Expected Result:**
- Product quantity increases correctly in the cart

## TC-009 — Remove item from cart
**Preconditions:** Product is added to the cart  
**Steps:**
1. Open the cart page
2. Remove the product from the cart

**Expected Result:**
- Product is removed successfully
- Cart updates correctly


## TC-010 — UI validation on product page
**Preconditions:** User is on a product details page  
**Steps:**
1. Observe layout, text, images, and buttons

**Expected Result:**
- No broken layout
- Text is readable
- Buttons are visible and clickable


