# BillGen

<img width="3124" height="2686" alt="BillGen" src="https://github.com/user-attachments/assets/f8d7ba8e-3cf1-4f09-b1e9-9d0831b3145a" />

# Fuel Bill Generator

A web-based fuel bill generator that creates professional-looking fuel station bills with customizable options.

## Features

- **Bill Generation**: Create fuel bills with station details, customer information, and transaction data
- **Customizable Fields**: Input station name, address, bill number, fuel type, quantity, rate, and total amount
- **Preset Types**: Support for amount-based or quantity-based fuel dispensing
- **Real-time Preview**: Live preview of the bill as you enter information
- **Export Options**:
  - Download as PDF (with gray background and optimized width)
  - Download as JPG image
  - Download as PNG image
- **Additional Features**:
  - Show/hide specific bill elements (Atot, Vtot, CST, LST, VAT)
  - Dark/Light theme toggle
  - Responsive design for mobile and desktop

## How to Use

1. **Open the Application**: Open `bill.html` in any modern web browser
2. **Enter Station Details**:
   - Station name and address
   - Bill number and local ID
   - FIP number and nozzle number
3. **Enter Transaction Details**:
   - Select fuel type
   - Choose preset type (Amount or Quantity)
   - Enter rate, quantity, and total amount
4. **Add Customer Information**:
   - Vehicle number
   - Mobile number
   - Date and time
5. **Customize Display**: Use the "Additional Features" section to show/hide bill elements
6. **Generate Bill**: Click "Generate Bill" to update the preview
7. **Export**: Choose from PDF, JPG, or PNG download options

## Requirements

- Modern web browser with JavaScript enabled
- Internet connection (for loading external libraries)

## Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and responsive design
- **JavaScript**: Interactive functionality
- **html2canvas**: For capturing bill as image
- **jsPDF**: For PDF generation
- **Google Fonts**: Thermal receipt font

## Browser Support

- Chrome 70+
- Firefox 65+
- Safari 12+
- Edge 79+

## File Structure

```
onemanarmy/
├── bill.html          # Main application file
└── README.md          # This file
```

## Customization

The bill template can be customized by modifying the HTML structure in the `billContainer` div. CSS styles can be adjusted in the `<style>` section for branding and appearance changes.

## License

This project is for personal use. Please ensure compliance with local regulations when using for business purposes.

## Contributing

Feel free to submit issues and enhancement requests.</content>
