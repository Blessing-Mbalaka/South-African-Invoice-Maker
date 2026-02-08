# SA Invoice Maker - User Guide

## 🚀 Quick Start

1. **Open `invoice-maker.html`** in any modern web browser
2. Upload your company details JSON or fill in manually
3. Upload your logo (optional but recommended)
4. Fill in invoice and client details
5. Add line items
6. Preview and download as PDF

## 📁 Files Included

- `invoice-maker.html` - The main invoice application (single file, works offline!)
- `company-details-template.json` - Template for your company information
- `sample-invoice.json` - Example invoice data structure

## 💾 cPanel Hosting Compatible

This invoice maker works perfectly on cPanel hosting:

1. Upload `invoice-maker.html` to your `public_html` folder
2. Access it via `https://yourdomain.com/invoice-maker.html`
3. All data is stored in browser localStorage (no server-side database needed!)
4. Share the link with your team members

### Advantages for cPanel Hosting:
- ✅ No PHP or database required
- ✅ Works immediately after upload
- ✅ Each user's data saved in their browser
- ✅ No server configuration needed
- ✅ Fast and lightweight

## 🏢 Setting Up Your Company Details

### Option 1: Upload JSON File

1. Click "Download Template" to get `company-details-template.json`
2. Edit the file with your actual details:
```json
{
  "companyName": "Your Company (Pty) Ltd",
  "address": "123 Business Street",
  "city": "Johannesburg",
  "province": "Gauteng",
  "postalCode": "2000",
  "country": "South Africa",
  "phone": "+27 11 123 4567",
  "email": "info@yourcompany.co.za",
  "registrationNumber": "2023/123456/07",
  "vatNumber": "4123456789",
  "bankName": "First National Bank (FNB)",
  "bankAccountName": "Your Company (Pty) Ltd",
  "bankAccountNumber": "62812345678",
  "bankBranchCode": "250655",
  "bankAccountType": "Business Cheque Account"
}
```
3. Click "Upload JSON" and select your edited file
4. Click "💾 Save Details" to store in browser

### Option 2: Manual Entry

Simply fill in all the company information fields in the form and click "💾 Save Details"

## 🖼️ Adding Your Logo

1. Click "🖼️ Upload Logo"
2. Select your company logo (PNG or JPG)
3. Logo will be saved and appear on all future invoices
4. Recommended size: 400x200 pixels or similar ratio

## 📊 Creating an Invoice

1. **Invoice Details**: Enter invoice number, date, and due date
2. **Client Information**: Add your client's details
3. **Line Items**: 
   - Add products/services with description, quantity, and price
   - Amounts calculate automatically
   - Click "+ Add Line Item" for more rows
4. **Notes**: Add payment terms or thank you message (optional)
5. Click "Preview Invoice"

## 💰 VAT Calculation

- VAT is automatically calculated at 15% (South African standard rate)
- Subtotal, VAT, and Total are computed in real-time
- All amounts in South African Rands (R)

## 📥 Download Options

- **Download PDF**: Creates a professional PDF with your invoice
- **Print Invoice**: Direct print from browser
- **Export JSON**: Save your current company details

## 🔒 Data Storage

- All data is stored in your browser's localStorage
- Company details and logo persist across sessions
- Each invoice is created fresh (no auto-save of invoice data)
- Export important details using "📤 Export JSON"

## 🌐 Browser Compatibility

Works on:
- ✅ Chrome/Edge (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

## 📱 Mobile Support

The invoice maker is responsive and works on tablets and mobile devices, but desktop use is recommended for PDF generation.

## 🆘 Troubleshooting

**Logo not appearing in PDF:**
- Ensure logo file is under 2MB
- Use PNG or JPG format
- Try re-uploading the logo

**Company details not saving:**
- Check if cookies/localStorage is enabled in browser
- Try clearing browser cache
- Re-enter and click "💾 Save Details"

**PDF downloads with wrong formatting:**
- Use Chrome or Edge browser for best results
- Ensure pop-ups are not blocked
- Try the "Print Invoice" option instead

## 📞 Support

For customizations or support:
- The HTML file is fully self-contained
- Edit the HTML directly for custom branding
- All JavaScript is included in the single file

---

**Version**: 1.0  
**Compatible with**: All modern browsers, cPanel hosting, static hosting  
**License**: Free to use and modify
"# South-African-Invoice-Maker" 
