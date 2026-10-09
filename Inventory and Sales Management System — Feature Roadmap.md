# 📦 Inventory and Sales Management System

## 📌 Project Overview

The **Inventory and Sales Management System** is a portfolio project for managing products, inventory, suppliers, purchases, customers, and sales for a small business, such as a computer shop.

🎯 **Project Goal:** Build a working application while learning and applying these technologies:

* 💻 **C#** — business rules, calculations, and validation
* 🌐 **ASP.NET Core Web API** — API endpoints
* 🗄️ **SQL Server** — storing and querying data
* 📊 **Power BI** — dashboards and business reports
* 🌍 **Networking** — HTTP, IP addresses, ports, LAN access, firewalls, and deployment

> 💡 Build the project step by step. The goal is to create an application that you understand and can explain in a technical interview.

## 🗺️ Project Features and Roadmap

### 🛍️ Phase 1: Product Management

* [ ] ➕ Add a product
* [ ] 📋 View the product list
* [ ] 🔍 View product details
* [ ] ✏️ Update product information
* [ ] 🗑️ Delete or deactivate a product
* [ ] 🔎 Search products by name or SKU
* [ ] 🏷️ Organize products by category

**Example:** Logitech Mouse, SKU `MOU-001`, price ₱500, stock 25.

### 📦 Phase 2: Inventory Management

* [ ] 📥 Record stock received
* [ ] 📤 Reduce stock when a sale is completed
* [ ] 🔧 Record manual stock adjustments
* [ ] 📊 View current stock levels
* [ ] 🎯 Set minimum stock levels
* [ ] ⚠️ Identify low-stock products
* [ ] 🧾 Keep a history of stock movements
* [ ] 🛡️ Prevent stock from becoming negative

### 🏭 Phase 3: Supplier Management

* [ ] ➕ Add and view suppliers
* [ ] ✏️ Update supplier information
* [ ] 🚫 Deactivate a supplier
* [ ] 📞 Store supplier contact information
* [ ] 🔗 Associate suppliers with products
* [ ] 📦 View products supplied by each supplier

### 🛒 Phase 4: Purchasing and Stock Receiving

* [ ] 📝 Create a purchase order
* [ ] 📦 Add products and quantities to an order
* [ ] 🔄 Track order status: Pending, Ordered, Received, or Cancelled
* [ ] 📥 Record the quantity received
* [ ] 📈 Increase inventory when items are received
* [ ] 📚 View purchase history

### 💰 Phase 5: Sales Management

* [ ] 🛍️ Create a sale containing one or more products
* [ ] 🧮 Calculate line subtotals and the sale total
* [ ] ✅ Validate available stock before completing a sale
* [ ] 📉 Reduce stock when a sale is completed
* [ ] 📜 View sales history and transaction details
* [ ] 🧾 Generate a basic receipt
* [ ] ↩️ Cancel or void a sale and adjust stock correctly
* [ ] 🔒 Keep related database changes consistent if an operation fails

**Example:** 3 mice × ₱500 = ₱1,500.

### 👥 Phase 6: Customer Management

* [ ] ➕ Register a customer
* [ ] 👤 View and update customer details
* [ ] 🔗 Associate a sale with a customer
* [ ] 📚 View a customer's purchase history

### 🔐 Phase 7: User Accounts and Security

* [ ] 🔑 Implement login and logout
* [ ] 🛡️ Add authentication
* [ ] 👨‍💼 Create roles such as Admin and Staff
* [ ] 🔒 Restrict actions based on user roles
* [ ] ✅ Validate user input
* [ ] 🔑 Store passwords using secure password hashing
* [ ] 🛡️ Protect API endpoints

### 📊 Phase 8: Reports and Power BI

* [ ] 💵 Report total sales revenue
* [ ] 📅 View sales by day, month, and year
* [ ] 🏆 Identify best-selling products
* [ ] ⚠️ Report low-stock products
* [ ] 🧮 Calculate inventory value
* [ ] 💸 Track purchasing costs
* [ ] 📈 Create Power BI dashboards and charts
* [ ] 📉 Explore sales and purchasing trends

> ⚠️ **Important:** Revenue is not the same as profit. Profit reporting requires reliable product cost and cost-of-goods-sold (COGS) records.

### 🧪 Phase 9: Testing and Software Quality

* [ ] ✅ Test product create, read, update, and delete operations
* [ ] 🧮 Test sales calculations
* [ ] 🚫 Test insufficient-stock validation
* [ ] 🔄 Test inventory updates and database transactions
* [ ] 🛠️ Handle errors and exceptions
* [ ] 🧪 Learn unit testing
* [ ] 🔌 Learn API integration testing
* [ ] 🔁 Practice test-driven development (TDD)
* [ ] 🌿 Use Git and GitHub with clear commits
* [ ] 📝 Document setup instructions and API endpoints
* [ ] 🏗️ Learn basic software architecture
* [ ] 📋 Practice planning work with an Agile-style backlog

### 🌐 Phase 10: Networking and Deployment

* [ ] 🖥️ Run the API locally and understand `localhost`
* [ ] 🔌 Understand IP addresses, ports, and HTTP requests
* [ ] 📡 Test the API from another device on the same LAN
* [ ] 🌍 Learn how DNS and firewalls affect connectivity
* [ ] 🗄️ Configure database connectivity safely
* [ ] 🚀 Prepare the application for deployment
* [ ] 🔐 Use environment configuration for settings and secrets
* [ ] 📖 Document how to run the project

> 🔒 **Security Note:** Do not expose the SQL Server database directly to the public internet. Clients should access data through a secured API.

## 🚀 Recommended Build Order

1. 🛍️ **Product Management** — build the first working API feature.
2. 📦 **Inventory Management** — add stock rules and prevent negative stock.
3. 💰 **Sales Management** — calculate sales and update inventory safely.
4. 🏭 Add suppliers and purchasing.
5. 👥 Add customers and user security.
6. 📊 Add reporting and Power BI.
7. 🧪 Improve testing, architecture, documentation, and deployment.

## 📚 Learning Approach

* 🎯 Work on one feature at a time.
* 🧠 Make implementation decisions independently before asking for help.
* 💡 Ask for hints or explanations when stuck instead of copying a complete solution.
* 💻 Understand the code you write and be able to explain it in an interview.
* 🌿 Use Git commits to record progress.
* 📈 Keep the first version simple, then improve it gradually.

## 🏁 Completion Goal

The project is complete when the core features work reliably, the database and API are connected, important business rules are tested, the project is documented on GitHub, and the reporting, networking, and deployment components have been explored.

> 💪 This roadmap is a learning checklist. You do not need to finish every phase before you have a useful portfolio project.

---

⭐ **Built as a learning project to develop practical C#, .NET, SQL Server, testing, and software development skills.**
