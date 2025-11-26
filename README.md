# RESTful_API
# 🍽️ Restaurant Management System (Back Office)

A server-side system to manage **tables, customers, menu items, and orders** in a restaurant.  
Enables staff to efficiently handle restaurant operations:

- **Table management:** status (Available / Occupied / Waiting for Cleaning)  
- **Customer management:** status (Regular / VIP)  
- **Menu management:** availability (Available / Out of Stock)  
- **Order management:** status (Open / Ready / Delivered / Cancelled)

---

## 🏷️ Entities

- **Customer**  
- **Table**  
- **MenuItem**  
- **Order**

---

## 👥 Customer Routes

| Action | Method | Endpoint |
|--------|--------|---------|
| Get all customers | GET | `/customers` |
| Get customer by ID | GET | `/customers/{id}` |
| Add a customer | POST | `/customers` |
| Update a customer | PUT | `/customers/{id}` |
| Delete a customer | DELETE | `/customers/{id}` |
| Update customer status (VIP / Regular) | PUT | `/customers/{id}/status` |

---

## 🪑 Table Routes

| Action | Method | Endpoint |
|--------|--------|---------|
| Get all tables | GET | `/tables` |
| Get table by ID | GET | `/tables/{id}` |
| Add a table | POST | `/tables` |
| Update a table | PUT | `/tables/{id}` |
| Delete a table | DELETE | `/tables/{id}` |
| Update table status (Available / Occupied / Waiting for Cleaning) | PUT | `/tables/{id}/status` |

---

## 🍔 MenuItem Routes

| Action | Method | Endpoint |
|--------|--------|---------|
| Get all menu items | GET | `/menu` |
| Get menu item by ID | GET | `/menu/{id}` |
| Add a menu item | POST | `/menu` |
| Update a menu item | PUT | `/menu/{id}` |
| Delete a menu item | DELETE | `/menu/{id}` |
| Update menu item availability (Available / Out of Stock) | PUT | `/menu/{id}/availability` |

---

## 🧾 Order Routes

| Action | Method | Endpoint |
|--------|--------|---------|
| Get all orders | GET | `/orders` |
| Get order by ID | GET | `/orders/{id}` |
| Add an order | POST | `/orders` |
| Update an order | PUT | `/orders/{id}` |
| Delete an order | DELETE | `/orders/{id}` |
| Update order status (Open / Ready / Delivered / Cancelled) | PUT | `/orders/{id}/status` |
