# Simple ERP - Odoo Module

A lightweight ERP module for **Odoo** that includes:
- Product Management
- Order Management (with line items)
- Multi-type Payments (Cash, E-Wallet, Bank Transfer)
- Interactive Dashboard with total stats

---

## 📦 Features

### ✅ Products
- Name, Price, Stock Quantity

### ✅ Orders
- Customer Name
- Order Lines (product, quantity, price)
- Total Order Amount (auto-calculated)

### ✅ Payments
- Linked to Orders
- Supports:
  - 💵 Cash
  - 📱 E-Wallet (with phone number)
  - 🏦 Bank Transfer (with reference and bank name)

### 📊 Dashboard
- Kanban-style dashboard
- Total Products, Orders, Sales, and Payments

---

## 🚀 Installation

1. Copy or extract the `simple_erp` folder into your Odoo `addons` directory.

2. Restart your Odoo server:
```bash
./odoo-bin -u all
