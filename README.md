# 🎓 OmniCert Studio

> **Universal Bulk & Individual Certificate Designer & Generator**  
> *A 100% standalone, serverless, single-file HTML5 web application to design, generate, customize, and batch-print academic, professional, and institutional certificates.*

---

## 🌟 Overview

**OmniCert Studio** is an all-in-one certificate generation studio built for universities, colleges, schools, conferences, and event organizers. It operates entirely inside your web browser with **zero external dependencies, zero installation, and complete data privacy** (all data stays locally on your machine).

Whether you need a single prestigious certificate of appreciation or hundreds of personalized participant certificates generated from an Excel/CSV spreadsheet, OmniCert Studio handles everything seamlessly.

---

## ✨ Key Features

### 1. 👥 Individual & Bulk Recipient Management
- **Role & Category Adaptation**:
  - `Resource Person`
  - `Program Coordinator`
  - `Organizer / Convenor`
  - `Participant`
  - `Paper Presenter`
  - `Keynote Speaker`
  - `Volunteer / Committee Member`
- **⚡ Self-Populating Auto-Dropdowns**:
  - Automatically captures previously entered values for **Designation** and **Institution / College**.
  - **Instant Next-Row Detection**: Typing a new designation or institution in any row automatically adds it to the dropdown suggestions for all subsequent rows.
- **Interactive Spreadsheet Database Modal**:
  - Full inline-editable spreadsheet view of all recipients.
  - Search, sort, filter, add/delete rows, and live sync with certificate preview.
- **📥 One-Click Excel / CSV Pre-Filled Template**:
  - Download a ready-to-edit template encoded with UTF-8 BOM for seamless compatibility with Microsoft Excel, Google Sheets, and LibreOffice Calc.
  - Upload CSV or paste raw data directly to populate hundreds of recipients in seconds.

### 2. 🏛️ Dynamic Event & Institution Customization
- **Institution Name & Accreditation**: e.g. NAAC A++ / Affiliated University.
- **Department & Organizing Bodies**: Customizable organizing committee details.
- **Program Types**:
  - Internship Program (FYUG / Summer / Winter)
  - National / International Seminar
  - Hands-on Workshop
  - Faculty Development Program (FDP)
  - National Symposium & Conferences
- **Flexible Dates & Durations**: Supports single dates, date ranges, and course hour annotations.

### 3. 🖼️ Multi-Logo Studio with Base64 & Canvas Downsampling
- **Multiple Placement Positions**:
  - Top-Left (College Crest)
  - Top-Right (University / Accreditation Seal)
  - Top-Center (Header Badge)
  - Bottom-Left (Official Stamp)
  - Bottom-Right (Sponsor / Partner Logo)
  - Center Background (Watermark Emblem)
- **Automatic Image Optimization**: Large high-resolution images are automatically down-sampled on an off-screen HTML5 `<canvas>` before Base64 encoding, preventing memory bloat and ensuring lightning-fast batch rendering.
- **Individual Controls**: Adjust height, position, and opacity (5% to 100%) per logo.

### 4. ✍️ Smart Signatories Engine
- Configure up to 5 signatories with **Name**, **Role / Title**, and **Institution**.
- **Cursive Digital Signature** or **Custom Uploaded Signature Image**.
- **Role-Based Signature Visibility**: Assign specific signatories to specific roles (e.g. Principal signs Resource Person certificates, while Coordinator signs Participant certificates).
- **Auto-Omit Self-Signature**: If a signatory is also the recipient, their signature slot is automatically omitted and remaining signatures realign symmetrically.

### 5. 🎨 12 Luxury Academic Themes & Layouts
- **Themes**:
  1. Classic Heritage (Navy & Royal Gold)
  2. Modern Minimalist (Slate Charcoal & Platinum)
  3. Royal Emerald (Deep Forest Green & Amber)
  4. Elite Imperial (Parchment & Warm Brown)
  5. Crimson Presidential (Ruby Crimson & Silver)
  6. Geometric Tech (Midnight Navy & Electric Cyan)
  7. Vintage Monogram (Royal Violet & Amethyst)
  8. Editorial Luxury (High-contrast Onyx & Haute Serif)
  9. Golden Award (Radiant Gold Metallic)
  10. Executive Slate Dark (Dark Mode Foil Luxury)
  11. Sapphire Academic (Regal Cobalt & Sterling Silver)
  12. Botanical Flora (Sage Green & Earth Tones)
- **Paper Sizes**: A4, US Letter, A3.
- **Orientations**: Landscape & Portrait.
- **Alignments**: Center-aligned (Classic Formal) & Left-aligned (Modern Editorial).

### 6. 🖨️ Automated Batch Printing & PNG Export
- **Print / Save as PDF**: Precise CSS page breaks (`page-break-after: always`) format every certificate cleanly onto its own page for direct printing or saving as a multi-page PDF.
- **Export PNG**: One-click high-resolution image download of any selected certificate.

---

## 🚀 Getting Started

### Option 1: Run Locally (Offline)
No web server, Node.js, or installation required!
1. Clone or download this repository:
   ```bash
   git clone https://github.com/sureshmagnolia/OmniCert-Studio.git
   ```
2. Double-click `index.html` or `certificate_generator.html` to open it in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: GitHub Pages (Online)
If GitHub Pages is enabled on this repository:
Visit: `https://sureshmagnolia.github.io/OmniCert-Studio/`

---

## 📁 Repository Structure

```text
OmniCert-Studio/
├── index.html                  # Main application entry point (GitHub Pages compatible)
├── certificate_generator.html  # Standalone certificate studio application
├── README.md                   # Project documentation and guide
└── .gitignore                  # Git ignore rules
```

---

## 🔒 Privacy & Security

OmniCert Studio processes all certificate data, recipient spreadsheets, and uploaded image logos **100% on the client side** inside the browser. No recipient records, names, or images are ever transmitted to any external server.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
