# TireTrack Management System

**Workflow System for Tire Manufacturing (Build 1.0.0.0)**

---

TireTrack Management System is a robust workflow system designed to efficiently manage the entire tire manufacturing process, from raw materials procurement to finished product distribution. This system provides production tracking, inventory management, quality control, and sales process automation features tailored for tire manufacturers.

---

## Key Features

### 🏭 Production Management

- Track the complete manufacturing lifecycle of tires.
- Manage raw materials, production batches, and quality control inspections.
- Record production steps and monitor batch-wise outputs.

### 📦 Inventory Control

- Monitor stock levels of raw materials, finished tires, and defective units.
- Categorize tires by model, size, and product categories for efficient inventory tracking.

### 🚚 Order and Shipment Management

- Manage customer orders with real-time order statuses such as "Pending," "Shipped," or "Delivered."
- Automate shipment scheduling and track shipments with unique tracking numbers.
- Record and manage supplier and customer details for seamless communication.

### ✅ Quality Assurance

- Record quality control inspections for each tire batch.
- Mark tires as "Passed" or "Defective" based on quality control results.

### 💳 Financial Management

- Manage payments for customer orders with multiple payment options, including credit cards, debit cards, PayPal, and cash.
- Track financial transactions, such as sales and purchases.
- Integrate payment records with sales orders for transparent financial reporting.

### 🔧 Maintenance Tracking

- Log maintenance activities for production equipment.
- Monitor maintenance costs and ensure the timely upkeep of machinery.

### 🗄️ Database Management

Designed and normalized database tables for efficient data storage and retrieval:

- **Raw Materials:** Records details of materials used in production.

- **Production Batches:** Tracks tire batches and the raw materials used.

- **Tires:** Stores information about finished products.

- **Quality Control:** Logs quality inspections and results.

- **Sales Orders:** Manages customer orders and their statuses.

- **Shipments:** Tracks order shipments and delivery statuses.

- **Customers:** Stores customer details for order processing.

- **Suppliers:** Records supplier details for procurement.

- **Payments:** Tracks customer payments for sales orders.

- **Equipment Maintenance:** Logs maintenance activities for production machinery.

- Ensured robust primary and foreign key relationships between tables for data integrity.

- Validated data population with over 30 records per table.

---

## Technologies Used

### 💻 Programming Languages

- SQL

### 🗄️ Database

- Oracle SQL 11G

### 🛠️ Development Tools

- SQL Developer 23.1.1

---

## Installation and Usage

### Prerequisites

- Oracle SQL 11G
- SQL Developer 23.1.1

### Steps to Install

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/tiretrack-management-system.git
   ```
2. Open SQL Developer and connect to your Oracle SQL database.
3. Import the database schema and data files provided in the `database` folder.
4. Run the SQL scripts to set up tables and relationships.

### Usage

1. Use the provided scripts to populate tables with sample data.
2. Run queries to manage inventory, orders, and quality control.
3. Use dashboards for visualizing production, inventory, and shipment statuses.

---

## Screenshots

### Dashboard



### Order Management



---

## Contribution

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or support, please contact:

- **Author:** Rajkumar
- **Email:** [rajkumar@example.com](mailto\:rajkumar@example.com)





