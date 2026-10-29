# E-Commerce Application — Test Scenarios and Test Cases

## 1. Test Scenarios

| Scenario ID     | Scenario Description                                                     | Purpose                                                     |
| --------------- | ------------------------------------------------------------------------ | ----------------------------------------------------------- |
| TS_SEARCH_001   | Verify that searching for an existing product displays relevant results. | Confirm that customers can find products using search.      |
| TS_CATEGORY_002 | Verify that selecting a product category displays relevant products.     | Confirm that category filtering works as expected.          |
| TS_CART_003     | Verify that a customer can remove a product from the cart.               | Confirm that removed products no longer appear in the cart. |

## 2. Detailed Test Cases

### TC_SEARCH_001 — Search for an existing product

- **Preconditions:** The application is accessible, and the product exists.
- **Test Data:** Blue Top
- **Steps:**
  1. Open the application.
  2. Navigate to the Products page.
  3. Enter `Blue Top` in the search field.
  4. Click Search.
  5. Review the results.
- **Expected Result:** The results contain the matching product `Blue Top`.
- **Actual Result:** The `Blue Top` product was displayed in the search results.
- **Status:** Pass

### TC_CATEGORY_001 — Filter products by category

- **Preconditions:** The application is accessible, and the category is available.
- **Test Data:** Women category
- **Steps:**
  1. Open the application.
  2. Locate the category navigation.
  3. Select Women and, if required, a subcategory.
  4. Review the displayed products.
- **Expected Result:** The displayed products correspond to the selected category or subcategory.
- **Actual Result:** Relevant products appeared.
- **Status:** Pass

### TC_CART_001 — Remove a product from the cart

- **Preconditions:** The application is accessible, and a product has been added to the cart.
- **Test Data:** One product in the cart
- **Steps:**
  1. Open the shopping cart.
  2. Identify the product to remove.
  3. Click its remove control.
  4. Review the cart contents.
- **Expected Result:** The selected product is removed. Other products, if present, remain in the cart.
- **Actual Result:** The selected product was removed.
- **Status:** Pass
