# 🧾 Invoice Pro - Professional Invoice Generator

A sleek, modern, and high-performance invoice generator built with **React** and **Vite**. This application is designed for small business owners and shopkeepers who need a fast, reliable, and private way to generate professional invoices for their customers.

## ✨ Features

- **Live Preview:** See your invoice update in real-time as you type.
- **Dynamic Item Management:** Easily add or remove items with automatic subtotal and grand total calculations.
- **Detailed Business Info:** Include your shop name, tagline, address, GST details, branding, and UPI ID.
- **Tax & Discount Support:** Built-in calculation for GST/Tax percentages and discounts.
- **Multi-Currency Support:** Support for ₹ (INR), $ (USD), € (EUR), £ (GBP), and more.
- **Instant PDF Download:** Generate high-resolution, professional A4 PDF invoices directly in the browser.
- **Fully Responsive:** Works perfectly on desktops, tablets, and mobile devices.
- **100% Privacy:** No data is sent to any server. Everything happens locally on your device.

## 🚀 Tech Stack

- **Frontend:** React.js (Hooks & Functional Components)
- **Styling:** Custom CSS (Modern, Dark-themed UI with Glassmorphism)
- **PDF Generation:** `html2pdf.js` & `html2canvas`
- **Build Tool:** Vite

## 🛠️ Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vamsi123-coder/Invoice-generator.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd Invoice-generator
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Open your browser:**
   Navigate to `http://localhost:5173` to see the app running.

## 📁 Project Structure

```text
src/
├── components/
│   ├── InvoiceForm.jsx      # Input fields for invoice data
│   └── InvoicePreview.jsx   # Live-updating invoice layout
├── utils/
│   └── generatePDF.js       # Core PDF generation logic
├── App.jsx                  # Main layout and state management
├── App.css                  # Component-specific styles
└── index.css                # Global design system & theme
```

## 📝 How to Use

1. **Fill in Details:** Enter your business information and common invoice details.
2. **Add Items:** List your products/services with their quantity and price.
3. **Configure Tax:** Adjust the tax/GST percentage and any applicable discounts.
4. **Preview:** Check the "Live Preview" panel on the right (or "Preview" tab on mobile) to ensure everything looks correct.
5. **Download:** Click the **"Download Invoice PDF"** button to save the high-quality PDF to your device.


## 🌐 Deployment

🚀 This project is deployed on **Vercel** with seamless GitHub integration.

🔗 **Live Demo:** https://vjvk-invoice-generator.vercel.app/

Every push to the repository triggers an **automatic deployment**, ensuring the latest version is always live.

✨ Fast • Reliable • Always up-to-date

---

### 💡 About

Developed with ❤️ for **small businesses**.