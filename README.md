# ESHOP

A full-stack desktop e-commerce application where users can browse products, manage a shopping cart, place orders, and view order history. Admins can manage products and monitor customer orders through a dedicated admin interface.

---

## Demo

[![ESHOP Demo](https://img.youtube.com/vi/1iquZDUaLrs/0.jpg)](https://www.youtube.com/watch?v=1iquZDUaLrs)

> Click the thumbnail above to watch the demo video.

---

## Features

### Users
- Register and log in securely
- Browse and search products
- Sort products by price
- Add products to cart
- Checkout and place orders
- View order history

### Admin
- Add new products with images
- View all customer orders
- Filter orders by date and customer ID
- Mark products as Top Picks

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Java 17 |
| UI Framework | JavaFX |
| Styling | CSS |
| Database | MySQL |
| Authentication | SHA-256 password hashing |
| Performance | Multithreading |

---

```
ESHOP/
├── src/
│   ├── application/
│   │   ├── Main.java                   # App entry point
│   │   ├── Control.java                # Database connection
│   │   ├── UserController.java         # User actions
│   │   ├── AdminController.java        # Admin actions
│   │   ├── CartController.java         # Cart management
│   │   ├── CheckoutController.java     # Order placement
│   │   ├── OrderController.java        # Order history
│   │   ├── SearchController.java       # Product search
│   │   ├── Login.fxml                  # Login screen
│   │   ├── Registration.fxml           # Register screen
│   │   ├── UserInterface.fxml          # Main user screen
│   │   ├── Admin.fxml                  # Admin screen
│   │   ├── Cart.fxml                   # Cart screen
│   │   ├── Checkout.fxml               # Checkout screen
│   │   └── Orders.fxml                 # Orders screen
│   └── Resources/                      # Images and icons
└── bin/                                # Compiled class files
```

---

## Notes
- Requires **Java 17** and **JavaFX** to run
- Requires a **MySQL** database connection configured in `Control.java`
- Admin login is separate from the regular user login
