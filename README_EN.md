<!-- LANGUAGE NAVIGATION -->
<div align="right">
  <a href="https://github.com/KevinBertolini12/bertolini-erp/blob/main/README.md"><img src="https://img.shields.io/badge/Português-1f2428?style=for-the-badge&logo=github&logoColor=white" alt="Versão em Português"></a>
  <a href="https://github.com/KevinBertolini12/bertolini-erp/blob/main/README_EN.md"><img src="https://img.shields.io/badge/English-2E6EEF?style=for-the-badge&logo=github&logoColor=white" alt="English Version"></a>
</div>

# 📦 Bertolini ERP — Business Management System & Desktop POS

> Desktop ERP / POS system developed in Python with an offline-first architecture, focusing on product management, real-time inventory control, point of sale (POS), financial reports, and executive dashboard.

---

## 📌 About the Project

**Bertolini ERP** is a full desktop application built to streamline operational management for micro and small businesses. Combining a modern, responsive user interface built with PySide6 and a fast, secure backend engine, the system delivers complete control over inventory, cash flow, and daily sales.

### 🚀 Key Features

- **📦 Products:** Registration, editing, deletion, optional SKU, and real-time inventory tracking.
- **📊 Inventory Control:** Manual stock adjustments (inflow/outflow), movement history, and automatic sales integration.
- **🧾 POS / Checkout:** Fast lookup by name or SKU, quick add-to-cart via Enter, quantity controls, and automatic stock deduction.
- **📈 Executive Dashboard:** Overview of total products, total stock, low stock alerts, and interactive movement graphs for recent days.
- **📑 Reports:** General summary and period-based transaction records for financial tracking.
- **🏭 Suppliers:** Structured database and listing for future product association.

---

## 🧱 Tech Stack

- **Language:** Python 3.11+
- **Desktop Interface:** PySide6 (Qt)
- **Local API:** FastAPI
- **ORM & Database:** SQLAlchemy (async), SQLite (local/offline mode), PostgreSQL (planned)
- **Migrations:** Alembic
- **Architecture:** Offline-First

---

## 💻 How to Run the Project Locally

```bash
# Clone the repository
git clone [https://github.com/KevinBertolini12/bertolini-erp.git](https://github.com/KevinBertolini12/bertolini-erp.git)

# Navigate to the project directory
cd bertolini-erp

# Create and activate a virtual environment
python -m venv venv

# On Windows:
venv\Scripts\activate

# On Linux/Mac:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python main.py
```













---

## 🖥️ Screenshots

![Dashboard](docs/screenshots/dashboard.png)
![Produtos](docs/screenshots/products.png)
![PDV](docs/screenshots/pos.png)
![Relatórios](docs/screenshots/reports.png)

---


👤 Autor:
Desenvolvido por Kevin Bertolini
