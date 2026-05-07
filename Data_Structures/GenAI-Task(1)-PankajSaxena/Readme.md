# Assignment 1: Python Data Structures

This assignment covers the four core Python data structures — **Lists**, **Tuples**, **Sets**, and **Dictionaries** — through a product catalog theme.

---

## Task 1: Product Collections (Lists & Tuples)

**File:** [task1.ipynb](task1.ipynb)

**Objective:** Work with lists and tuples to manage product data.

**Steps:**
1. Create a `product_list` containing at least 6 product names.
2. Create a tuple `sample_product` storing `(product_name, price, category)` for one product.
3. Print the 2nd and last product from the list.
4. Append two new products to the list and print the updated list.
5. *(Optional)* Convert the tuple to a list, modify the price, and convert it back to a tuple.

**Concepts Covered:** List indexing, `append()`, tuple immutability, type conversion between list and tuple.

---

## Task 2: Categories (Sets)

**File:** [task2.ipynb](task2.ipynb)

**Objective:** Use sets to manage unique product categories.

**Steps:**
1. Convert a list of categories (with duplicates) into a set to get unique values.
2. Add a new category and attempt to add a duplicate — observe set behavior.
3. Check whether a specific category exists in the set using the `in` operator.
4. *(Optional)* Print the total number of unique categories.

**Concepts Covered:** Set creation from list, `add()`, duplicate handling, membership testing with `in`, `len()`.

---

## Task 3: Product Pricing (Dictionaries)

**File:** [task3.ipynb](task3.ipynb)

**Objective:** Use dictionaries to store and manipulate product prices.

**Steps:**
1. Create a dictionary `price_dict` with at least 6 product-name/price pairs.
2. Add a new product, update an existing product's price, and remove a product safely.
3. Calculate and print the average price of all products using dictionary operations.
4. *(Optional)* Find and print the products with the maximum and minimum prices.

**Concepts Covered:** Dictionary CRUD operations, `sum()`, `len()`, `max()`/`min()` with `key` parameter, `pop()`.

---

## Task 4: Combined Operations

**File:** [task4.ipynb](task4.ipynb)

**Objective:** Combine lists, tuples, sets, and dictionaries in a single workflow.

**Steps:**
1. Given separate `products`, `categories`, and `price_dict` data, build a `catalog` list of tuples `(product_name, price, category)`.
2. Create a `category_to_products` dictionary mapping each category to its list of products.
3. Find and print the category with the maximum number of products.

**Concepts Covered:** Combining multiple data structures, iteration with `range()`, dictionary grouping, `max()` with a lambda key.

---

## Data Structures Summary

| Data Structure | Mutable | Ordered | Duplicates | Used In |
|----------------|---------|---------|------------|---------|
| List           | Yes     | Yes     | Yes        | Task 1, 4 |
| Tuple          | No      | Yes     | Yes        | Task 1, 4 |
| Set            | Yes     | No      | No         | Task 2 |
| Dictionary     | Yes     | Yes     | Keys: No   | Task 3, 4 |