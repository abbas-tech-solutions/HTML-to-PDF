# HTML to PDF Converter

A modern, feature-rich web application for converting HTML files to PDF format. Built with vanilla JavaScript, HTML5, and Tailwind CSS.

## Features

- 🎨 **Modern UI** - Beautiful, responsive interface built with Tailwind CSS
- 📁 **Drag & Drop** - Easy file upload with drag and drop support
- 📄 **Multi-page Support** - Automatically handles long content across multiple PDF pages
- ⚙️ **Customizable** - Choose page orientation (Portrait/Landscape) and page size (A4, Letter, Legal)
- 🎯 **High Quality** - Maintains full quality with PNG format and 2x scale rendering
- ✅ **File Validation** - Validates file type and size (max 10MB)
- 🔔 **Notifications** - Success and error notifications with auto-dismiss
- 👁️ **Live Preview** - See your HTML rendered before converting
- 🧹 **Easy Reset** - Clear button to start over quickly

## How to Use

1. **Open the Application**
   - Simply open `web_to_pdf.html` in your web browser
   - No server or installation required!

2. **Upload HTML File**
   - Click the upload area or drag and drop your HTML file
   - Supported formats: `.html`, `.htm`, `.txt`
   - Maximum file size: 10MB

3. **Preview Content**
   - Your HTML will be rendered in the preview area
   - You can toggle the preview on/off

4. **Configure PDF Settings** (Optional)
   - Select page orientation: Portrait or Landscape
   - Choose page size: A4, Letter, or Legal

5. **Convert to PDF**
   - Click "Convert to PDF" button
   - Wait for the conversion to complete
   - Your PDF will automatically download with the same name as your HTML file

## Technologies Used

- **HTML5** - Structure and semantic markup
- **Tailwind CSS** - Modern, utility-first CSS framework
- **JavaScript (ES6+)** - Core functionality
- **jsPDF** - PDF generation library
- **html2canvas** - HTML to canvas conversion

## Browser Compatibility

- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## File Structure

```
web-to-pdf/
│
├── web_to_pdf.html    # Main application file
├── README.md          # This file
├── .gitignore         # Git ignore rules
└── LICENSE            # MIT License
```

## Features in Detail

### File Upload
- Drag and drop support for easy file selection
- File type validation (HTML, HTM, TXT only)
- File size validation (10MB limit)
- Visual feedback during upload

### PDF Generation
- High-quality rendering with 2x scale
- PNG format for maximum quality
- Automatic multi-page handling
- Preserves original filename

### User Experience
- Responsive design works on all devices
- Loading indicators during conversion
- Success/error notifications
- Preview toggle functionality
- Clear button to reset

## Limitations

- Maximum file size: 10MB
- External resources (images, CSS from URLs) may not render if CORS is restricted
- Complex CSS animations may not be captured perfectly
- Very large HTML files may take longer to process

## Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Credits

- [Tailwind CSS](https://tailwindcss.com/) - CSS Framework
- [jsPDF](https://github.com/parallax/jsPDF) - PDF Generation
- [html2canvas](https://github.com/niklasvh/html2canvas) - HTML to Canvas

## Support

If you encounter any issues or have questions, please open an issue on GitHub.

---

**Made with ❤️ for easy HTML to PDF conversion**

