# 3E DPF DOCTOR — ERP & Inventory Management

> **Efficient Environmental Edge Pvt. Ltd.**   
> **Advanced Emission Solutions**

A lightweight, high-performance, single-file ERP and inventory management web application built specifically for manufacturing, tracking, and auditing **3E DPF Doctor** core machines (Pro, Supreme, Plus+, and Franchise Turnkey Kits) and raw material components.

---

## 🚀 Key Features

* **Zero File-Upload Bloat (Hosting Cost Optimized):** Designed for lightweight free hosting with zero heavy storage costs. Features a fast **Invoice Received ✓** tick-mark audit workflow.
* **Secure Role-Based Access Control (RBAC):** Built-in authentication supporting distinct roles with configurable PINs:
  * **Admin / MD:** Full access, user management, and system configuration.
  * **Accountant:** Specialized access to the **Accountant Invoice Tick-Mark Audit** register and Tally export.
  * **Storekeeper:** Streamlined interface for inward stock purchases and shop-floor outward utilization.
* **Multi-Unit Inventory Tracking:** Manages raw parts and finished goods across diverse units (`Pcs`, `Kg`, `Grams`, `Liters`, `mL`, `Meters`, `Feet`, and `Sets`).
* **Automated Daily Backups & 1-Click Restore:** Local storage auto-snapshot engine with instant JSON file download and 1-click restoration support.
* **Machine BOM & Kits Integration:** Pre-configured bills of materials for *3E DPF Doctor Pro*, *Supreme*, and turnkey kits.
* **Tally Prime Integration Ready:** One-click CSV export formatted for seamless accounting ledger synchronization.

---

## 🔒 Default Staff Login Credentials

| Role | Username / ID | Default Password / PIN |
| :--- | :--- | :--- |
| **Admin / MD** | `admin` | `admin123` |
| **Accountant** | `accounts` | `accounts123` |
| **Storekeeper** | `store` | `store123` |

*(Note: Admins can change passwords/PINs anytime from the in-app **Users / PINs** menu).*

---

## 📦 Installation & Deployment

Because this application is packaged as a **100% self-contained single-file HTML application** (`index.html`), it requires no database servers, Node.js backends, or complex build steps.

### Run Locally
1. Download or clone this repository.
2. Ensure the main file is named **`index.html`**.
3. Double-click `index.html` to open it instantly in any web browser (Chrome, Safari, Edge, Firefox).

### Deploy for Free in 2 Minutes
* **Netlify Drop:** Go to [netlify.com/drop](https://app.netlify.com/drop) and drag-and-drop your project folder containing `index.html`. Your app will go live instantly with a free `.netlify.app` URL.
* **GitHub Pages:** 
  1. Upload `index.html` to your public GitHub repository.
  2. Navigate to **Settings → Pages**.
  3. Set the branch to `main` and save. Your app will be hosted live on GitHub Pages.

---

## 📂 Project Structure

```text
3e-dpf-inventory/
├── index.html       # Complete self-contained ERP application (HTML/CSS/JS)
└── README.md        # Repository documentation
