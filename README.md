# The IAH Creations Business Brochure

A professional LaTeX-based business brochure showcasing The IAH Creations' comprehensive digital services with global pricing in multiple currencies.

## Overview

This repository contains a 6-page professional business brochure created using LaTeX, featuring:
- Website creation services (Single Page & Dynamic Multi-Page)
- Web application development (SPA & Multi-Tasking Dynamic)
- Mobile application development (Mobile SPA & Dynamic Multi-Tasking)
- Three-tier pricing structure (Basic, Medium, Advance)
- Multi-currency pricing (INR, USD, EUR)
- Professional branding with custom color scheme

## Features

- **Professional Design**: Deep blue and gold color scheme with modern typography
- **Comprehensive Services**: Detailed breakdown of all digital service offerings
- **Global Pricing**: Multi-currency pricing in INR, USD, and EUR
- **Tiered Structure**: Basic, Medium, and Advance tiers for all services
- **Interactive Elements**: Clickable hyperlinks to virtual business card
- **Print-Ready**: 6-page layout optimized for both digital and print

## Services Covered

### 1. Website Creations
- **Single Page Website (SPW)**: 24-hour prototyping (₹4,999 - ₹14,999)
- **Dynamic Multi-Page Website**: 72 hours - 1 week (₹19,999 - ₹59,999)

### 2. Web Application Creations
- **Single Page Application (SPA)**: 24-hour prototyping (₹24,999 - ₹89,999)
- **Multi-Tasking Dynamic Application**: 72 hours - 1 week (₹49,999 - ₹2,00,000+)

### 3. Mobile Application Creations
- **Mobile SPA**: 24-48 hours (₹29,999 - ₹79,999)
- **Dynamic Multi-Tasking Application**: 72 hours - 1 week+ (₹99,999 - ₹2,50,000+)

## Technical Requirements

To compile this LaTeX document, you need:
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- XeLaTeX engine (for Noto Sans font support)
- Required packages:
  - `geometry` - Page layout
  - `fontspec` - Font specification
  - `babel` - Language support
  - `xcolor` - Color definitions
  - `titlesec` - Section formatting
  - `booktabs`, `tabularx`, `colortbl` - Professional tables
  - `tcolorbox` - Callout boxes
  - `hyperref` - Interactive links
  - `float` - Table positioning
  - `enumitem` - List formatting

## Compilation

1. Clone this repository
2. Compile using XeLaTeX:
   ```bash
   xelatex Documents.sty
   ```
3. The output PDF will be generated in the same directory

## File Structure

```
Business Brochure/
├── Documents.sty          # Main LaTeX document (6 pages)
├── README.md             # Project documentation
├── LICENSE               # MIT License
├── .gitignore           # Git ignore rules
├── CONTRIBUTING.md       # Contribution guidelines
└── CHANGELOG.md         # Version history
```

## Customization

The brochure can be easily customized by modifying:
- **Brand Colors**: Update `primaryBlue`, `accentGold`, `lightGray` definitions
- **Pricing**: Modify pricing tables for different tiers
- **Services**: Add or remove service categories and features
- **Typography**: Change font from Noto Sans to preferred typeface
- **Layout**: Adjust page margins and spacing

## Brand Identity

- **Primary Color**: Deep Professional Blue (RGB: 0, 51, 102)
- **Accent Color**: Gold (RGB: 218, 165, 32)
- **Background**: Light Gray (RGB: 245, 245, 245)
- **Typography**: Noto Sans (modern, clean sans-serif)
- **Tagline**: "Future-Ready Digital Solutions"

## Contact

For inquiries about services mentioned in this brochure:
[The IAH Creations Virtual Business Card](https://infinity-aggarwalharshul.github.io/The-IAH-Creations-Virtual-Business-Card/)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**The IAH Creations** - *Designed for Commercial Success*