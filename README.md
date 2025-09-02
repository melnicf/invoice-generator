# Invoice Generator

A simple, professional invoice generator that creates PDF invoices from HTML forms. Perfect for freelancers and small businesses.

## Features

- **Real-time Preview**: See your invoice as you type
- **PDF Export**: Generate professional PDF invoices using html2pdf.js
- **Auto-save**: Form data is automatically saved to browser localStorage
- **Auto-increment**: Invoice numbers automatically increment
- **EU VAT Support**: Includes reverse charge functionality for EU B2B transactions
- **Responsive Design**: Works on desktop and mobile devices
- **Professional Layout**: Clean, print-ready invoice design

## Usage

1. Open `invoice_gen.html` in your web browser
2. Fill out the invoice details:
   - Basic information (invoice number, dates)
   - Your company information (supplier)
   - Client information
   - Line items with quantities, prices, and VAT rates
   - Payment information
3. Watch the live preview update as you type
4. Click "Generate PDF" to download your invoice

## Key Sections

- **Basic Information**: Invoice number, issue date, due date
- **Supplier Details**: Your company information and contact details
- **Client Details**: Customer information and billing address
- **Line Items**: Add multiple services/products with quantities and pricing
- **Payment Info**: Bank details, payment method, and terms
- **EU Features**: Reverse charge checkbox for EU B2B transactions

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies except html2pdf.js)
- Uses localStorage for data persistence
- Responsive design with CSS Grid
- Print-optimized styling
- A4 page format for PDF export

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript features
- CSS Grid
- localStorage
- File downloads

## File Structure

```
invoice_generator/
├── invoice_gen.html    # Main application file
└── README.md          # This file
```

## License

This project is open source and available under the MIT License.
