# Drive-Through-Restaurant-Ordering-UI
Modern drive-through restaurants need fast and intuitive ordering interfaces that allow customers to browse menus, customize their food, manage their

# Heritage Drive – Drive-Through Restaurant Ordering UI

## 📌 Project Overview

**Heritage Drive** is a modern and responsive **drive-through restaurant ordering website** designed to provide customers with a fast, simple, and convenient way to browse food items, add them to a cart, select a pickup time, and place a drive-through order.

The website combines a **classic restaurant-inspired visual design** with modern interactive features such as search, category filters, cart management, checkout, order confirmation, and a dark/light mode toggle.

---

## ✨ Features

### 🍔 Menu System

* Displays a variety of restaurant food items.
* Includes burgers, wraps, sides, drinks, desserts, and breakfast.
* Shows item name, description, price, image, and tags.
* Menu items are dynamically generated using JavaScript.

### 🔍 Search

* Search for food items using the search box.
* Searches through:

  * Food name
  * Description
  * Category

### 🏷️ Category Filtering

Users can filter menu items by categories such as:

* All
* Burgers
* Wraps
* Sides
* Drinks
* Desserts
* Breakfast

### 🛒 Shopping Cart

* Add food items to the order.
* Increase or decrease item quantities.
* Remove items from the cart.
* Automatically calculates:

  * Subtotal
  * Service fee
  * Total amount
* Cart data is stored using browser `localStorage`.

### 🌙 Dark / Light Mode

* Toggle between light and dark themes.
* Selected theme is saved using `localStorage`.
* Theme remains available after refreshing the page.

### 🚗 Drive-Through Checkout

Customers can enter:

* Name
* Mobile number
* Pickup time slot

The system validates the required information before placing the order.

### ✅ Order Confirmation

After checkout:

* A unique order number is generated.
* A confirmation modal is displayed.
* The customer sees the order status:

  1. Order placed
  2. Being prepared
  3. Ready for pickup

### 📱 Responsive Design

The interface adapts to:

* Desktop
* Tablet
* Mobile devices

---

## 🛠️ Technologies Used

| Technology   | Purpose                           |
| ------------ | --------------------------------- |
| HTML5        | Website structure                 |
| CSS3         | Styling and responsive layout     |
| JavaScript   | Dynamic functionality             |
| LocalStorage | Saving cart and theme preferences |
| Unsplash     | Food images                       |

---

## 📂 Project Structure

```text
Heritage-Drive/
│
├── index.html
└── README.md
```

The project is implemented as a **single HTML file**, containing the HTML structure, CSS styling, and JavaScript functionality.

---

## 🚀 How to Run

### Step 1: Download or copy the project

Save the provided code as:

```text
index.html
```

### Step 2: Open the file

Double-click `index.html` to open it in a web browser.

Alternatively, open it using:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari

### Step 3: Use the website

You can:

1. Browse the menu.
2. Search for food.
3. Filter items by category.
4. Add items to the cart.
5. Change quantities.
6. Open the cart.
7. Enter pickup details.
8. Select a pickup slot.
9. Place the order.
10. View the generated order number.

---

## 💰 Pricing

The project uses Indian Rupees (`₹`) for menu prices.

Example menu items include:

* Heritage Burger – ₹249
* Classic Chicken Burger – ₹229
* Smoky BBQ Wrap – ₹199
* Golden Fries – ₹99
* Cheese Loaded Fries – ₹149
* Classic Cold Coffee – ₹129
* Lemon Iced Tea – ₹89
* Chocolate Sundae – ₹119
* Breakfast Stack – ₹179

A **₹20 service fee** is added when the cart contains at least one item.

---

## 💾 LocalStorage

The application uses browser `localStorage` to maintain user preferences.

### Cart Storage

```text
heritageCart
```

This stores the customer's current cart.

### Theme Storage

```text
heritageTheme
```

This stores whether the user selected light mode or dark mode.

---

## 🧠 Main JavaScript Functions

The application contains several important functions.

### `renderMenu()`

Displays menu items based on the selected category and search query.

### `setCategory()`

Changes the active menu category.

### `addToCart()`

Adds a food item to the shopping cart.

### `changeQuantity()`

Increases, decreases, or removes cart items.

### `saveCart()`

Saves cart information to browser localStorage.

### `renderCart()`

Updates the cart interface, item count, subtotal, service fee, and total.

### `checkout()`

Validates customer information and creates a new order number.

### `openCart()`

Opens the shopping cart panel.

### `closeCart()`

Closes the shopping cart panel.

### `showToast()`

Displays short notification messages to the user.

---

## 🎨 Design

The website uses a **classic heritage restaurant theme** with:

* Cream background
* Burgundy accents
* Dark green elements
* Gold highlights
* Serif typography
* Rounded cards
* Subtle shadows
* Responsive layouts

## The CSS defines separate color variables for light and dark modes.

## 📱 Responsive Breakpoints

The website includes responsive CSS for smaller screens.

### Tablet

At screen widths below `900px`:

* Hero content becomes one column.
* About section becomes one column.
* Menu changes to two columns.
* Navigation links are hidden.

### Mobile

At screen widths below `600px`:

* Menu becomes one column.
* Steps become one column.
* Navigation height is reduced.
* Hero and section spacing is reduced.
* Cart and theme toggle become more compact.

---

## 🔐 Validation

Before placing an order, the application checks that:

* At least one item is present in the cart.
* Customer name is entered.
* Mobile number is entered.
* Pickup slot is selected.

If information is missing, the website displays a notification message instead of completing the order.

---

## 📦 Order Number

When an order is successfully placed, the website generates a random order number in the following format:

```text
HD-XXXXXX
```

For example:

```text
HD-583214
```

The order number is displayed on the confirmation screen.

---

## 🌐 External Resources

Food images are loaded from **Unsplash** using image URLs included in the JavaScript menu data.

An internet connection may therefore be required for the food images to load correctly.

---

## 🔮 Future Improvements

The project can be extended with:

* Online payment integration
* Real restaurant backend
* User login and registration
* Order history
* Live order tracking
* Restaurant admin dashboard
* Database integration
* GPS/location-based pickup
* Coupon and discount system
* Delivery option
* Email/SMS order notifications
* Real-time kitchen order management

---

## 👨‍💻 Project Type

**Project:** Drive-Through Restaurant Ordering UI
**Website:** Heritage Drive
**Technology:** HTML, CSS, JavaScript
**Year:** 2026

---

## 📄 License

This project is created for **educational and demonstration purposes**.

You are free to modify the design, menu items, prices, styling, and functionality according to your project requirements.

---

## ⭐ Conclusion

Heritage Drive demonstrates how a restaurant can provide a simple and user-friendly **digital drive-through ordering experience**.

The project focuses on:

> **Classic food. Modern service. Fast ordering.**


LIVE DEMO: subtle-gumption-24aec0.netlify.app


