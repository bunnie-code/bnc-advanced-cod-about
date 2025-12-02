# Bunniecode Advanced COD for WooCommerce

[![Requires at least: 5.0](https://img.shields.io/badge/Requires%20at%20least-5.0-blue.svg)](https://wordpress.org/about/requirements/)
[![WC tested up to: 8.3](https://img.shields.io/badge/WC%20tested%20up%20to-8.3-blue.svg)](https://woocommerce.com/)
[![Requires PHP: 7.2+](https://img.shields.io/badge/PHP-7.2%2B-blue.svg)](https://wordpress.org/about/requirements/)
[![License: GPLv2+](https://img.shields.io/badge/License-GPLv2%2B-blue.svg)](https://www.gnu.org/licenses/gpl-2.0.html)

> An advanced Cash on Delivery payment gateway extension for WooCommerce with extended configuration options.

This plugin extends the default WooCommerce Cash on Delivery (COD) payment gateway, allowing you to have full control over when and how COD is offered to your customers. It provides a robust rules engine to set availability conditions and allows you to configure advanced fees based on the cart contents.

**This is a commercial plugin and requires a valid license key to be activated.**

---

## ✨ Features

### 🚦 Conditional Availability (Restrictions)

Restrict the availability of the Cash on Delivery option based on various conditions:

*   **💰 Order Value:** Set a minimum or maximum cart subtotal for COD to be available.
*   **🌍 Geography:** Restrict by Country, State, City, or Postal Code. Each can be set to either 'Include' or 'Exclude'. Postal codes support ranges (e.g., `90210-90220`).
*   **🚚 Shipping:** Restrict by Shipping Zone or Shipping Class, also with 'Include'/'Exclude' modes. Shipping class restrictions can match if *any* or *all* products in the cart meet the criteria.
*   **👤 User Role:** Configure availability for guest users or registered users only.

### 💸 Advanced Fees

Charge extra for Cash on Delivery orders with a flexible fee system:

*   **🔧 Fee Types:** Charge a `fixed` amount or a `percentage` of the cart subtotal.
*   **🎉 Fee Waiver:** Automatically waive the fee for orders over a specified amount.
*   **🏠 Local Pickup Override:** Set a separate, specific fee for orders using 'Local Pickup'.
*   **🧾 Tax:** Configure the fee as taxable or non-taxable.

### 👨‍💻 User Experience & Debugging

*   **💬 Clarity:** Provides clear, dynamic feedback on the checkout page, showing the applicable fee and explaining why COD is unavailable if restricted.
*   **🐞 Debug Mode:** A developer option to enable detailed logging in the browser's console for easy troubleshooting.

---

## 🚀 Installation

1.  Upload the plugin files to the `/wp-content/plugins/bunniecode-advanced-cod` directory, or install the plugin through the WordPress plugins screen directly.
2.  Activate the plugin through the 'Plugins' screen in WordPress.
3.  Navigate to the plugin's license page to activate your license key.

---

## ⚙️ Configuration

1.  Navigate to `WooCommerce > Settings > Payments`.
2.  Click on **Cash on delivery**.
3.  Here you will find all the advanced configuration options for the plugin.

---

## 📄 License

This plugin is a commercial product and requires a valid license key for activation and updates. The license key can be purchased from [bunniecode.eu](https://bunniecode.eu).

The PHP code is licensed under GPLv2 or later. See `LICENSE` for details.

---

## 📜 Changelog

### [1.4.6] - 2025-12-02
-   **Tweak** - Updated plugin version in readme.

### [1.4.5]
-   Initial release.