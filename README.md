# Shopping Bill Generator

A console-based application built using **Java** for generating shopping bills efficiently. It calculates the total amount, applies discounts, computes GST, and provides a detailed invoice.

## Features
- 🛒 Add multiple products with unique IDs, names, quantities, and prices
- 💰 Calculates **total bill amount** and applies a **2% discount**
- 🧾 Computes **SGST** and **CGST** (12% each)
- 📅 Displays the invoice with date, time, and shop details
- 📊 Generates a clear and organized **bill format**

## Technology Stack
- **Java** - Core programming language
- **OOP Concepts** - Used for creating product objects
- **ArrayList** - Stores products dynamically
- **Scanner** - For user input
- **SimpleDateFormat & Calendar** - Displays the current date and time

## How It Works
1. Enter customer and product details (ID, name, quantity, and price).
2. The application calculates:
    - **Total Price** for each product.
    - **Overall Bill Amount**.
    - **Discount** (2%).
    - **SGST and CGST** (12% each).
3. Generates a formatted invoice with all details.

## Setup and Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Shopping-Bill-Generator.git
    ```
2. Navigate to the project folder:
    ```bash
    cd Shopping-Bill-Generator
    ```
3. Compile the code:
    ```bash
    javac ShoppingBill.java
    ```
4. Run the application:
    ```bash
    java ShoppingBill
    ```

## Example Output
```plaintext
--------------------Invoice-----------------
        Sai Srinivasa Grocery Shop
7-142, main road, Chebrolu, Eluru District, Andhra Pradesh
Opposite Patanjali Stores
GSTIN: 03AWBPP8756K592            Contact: (+91) 6300260522
Date: 17/03/2025 14:30:00 Monday              (+91) 9998887770

Enter Customer Name: John Doe
Product ID: P001
Product Name: Rice
Quantity: 5
Price (per unit): 40

Want to add more items? (y or n): n

Product ID        Name           Quantity      Rate            Total Price
---------------------------------------------------------------------------
P001              Rice            5             40.00            200.00

Total Amount (Rs.) 200.00
Discount (2%)      4.00
Subtotal           196.00
SGST (12%)         24.00
CGST (12%)         24.00
Invoice Total      244.00

----------------Thank You for Shopping!!-----------------
                    Visit Again
