Inventory and Sales Management System — Feature Roadmap
Project Overview
For the Inventory and Sales Management System, the features are divided into phases, from basic to advanced. This lets you build the project gradually while practicing C#, .NET Web API, SQL Server, Power BI, and networking.
The goal is to build a realistic application that you can explain during technical interviews and showcase in your portfolio.
Phase 1 — Product Management
Goal: Manage the products sold by the business.
[ ] Add a new product
[ ] View all products
[ ] View product details
[ ] Update product information
[ ] Delete or deactivate a product
[ ] Search products by name or SKU
[ ] Categorize products
Example product: Logitech Mouse, SKU `MOU-001`, price ₱500, stock quantity 25.
Phase 2 — Inventory Management
Goal: Track how much stock is available.
[ ] Add stock when new products arrive
[ ] Reduce stock when products are sold
[ ] Record stock adjustments
[ ] View current stock levels
[ ] Set minimum stock levels
[ ] Display low-stock alerts
[ ] View stock movement history
Important rule: Stock should not become negative when a sale is processed.
Phase 3 — Supplier Management
Goal: Keep records of product suppliers.
[ ] Add, view, update, and deactivate suppliers
[ ] Store supplier contact information
[ ] Associate products with suppliers
[ ] View products provided by each supplier
Phase 4 — Purchasing and Stock Receiving
Goal: Record products purchased from suppliers.
[ ] Create purchase orders
[ ] Add products and quantities to each order
[ ] Track order status: pending, ordered, received, or cancelled
[ ] Record received quantities
[ ] Increase inventory when goods are received
[ ] View purchase history
This phase connects supplier management with inventory management.
Phase 5 — Sales Management
Goal: Process customer purchases.
[ ] Create a sales transaction
[ ] Add multiple products to one sale
[ ] Enter quantities
[ ] Calculate subtotals and the total amount
[ ] Validate available stock
[ ] Reduce inventory after a successful sale
[ ] View sales history and individual receipts
[ ] Cancel or void sales with appropriate stock adjustments
Example: If a customer buys three mice at ₱500 each, the total is ₱1,500. The application must save the sale and update stock consistently.
Phase 6 — Customer Management
[ ] Register customers
[ ] View and update customer information
[ ] Associate customers with sales
[ ] View each customer's purchase history
This is useful if the business wants to track repeat customers, but you can build it after the main sales process works.
Phase 7 — User Accounts and Security
[ ] Implement login and logout
[ ] Add user authentication
[ ] Implement role-based access control
[ ] Create admin and staff roles
[ ] Restrict sensitive actions based on role
[ ] Validate incoming data
[ ] Store passwords securely using established password-hashing mechanisms
[ ] Protect API endpoints
For the Web API, learn authentication and authorization after the core features are working.
Phase 8 — Reports and Power BI
Goal: Turn stored business data into useful information.
[ ] Report total sales revenue
[ ] Report sales by day, month, and year
[ ] Identify best-selling products
[ ] Identify products with low stock
[ ] Calculate inventory value
[ ] Report purchase costs
[ ] Analyze sales and purchasing trends
Use SQL Server as the data source and Power BI to build interactive reports.
Note: Revenue and profit are different. To calculate profit, you need a reliable product cost or cost-of-goods-sold record.
Phase 9 — Testing and Software Quality
[ ] Test product creation and updates
[ ] Test sales calculations
[ ] Test stock validation
[ ] Test insufficient-stock scenarios
[ ] Test database transaction behavior
[ ] Handle errors and invalid inputs
[ ] Write automated unit tests
[ ] Write API integration tests
[ ] Use Git and GitHub for version control
[ ] Document setup instructions and API endpoints
This phase helps you practice software development and test-driven development.
Phase 10 — Networking and Deployment
[ ] Run the application locally
[ ] Understand localhost, IP addresses, ports, and HTTP
[ ] Test API access from another device on your local network
[ ] Understand DNS and firewall rules
[ ] Configure database connectivity safely
[ ] Deploy the application when ready
[ ] Configure environment settings and secrets securely
Security note: Do not expose your database directly to the public internet. External users should access it through your secured application API.
Feature Checklist
Use the checkboxes throughout this README to track your progress as you build the system.
Recommended Starting Milestones
You don't need to build all ten phases immediately. Start with these three milestones:
Milestone 1: Product Management — Build your first working feature.
Milestone 2: Inventory Management — Learn to update and track stock.
Milestone 3: Sales Management — Connect products, calculations, and inventory.
Once these work, add suppliers, purchasing, reporting, security, and deployment.
Your first goal is not to create a huge system. It is to build a small, working application, understand every part of it, and expand it as your skills improve.
