# Data_analysis_project-
📄 OCR PDF to Kannada Spreadsheet Converter
A powerful web-based tool that converts OCR PDFs, text files, and Excel files into structured Kannada voter list format. Perfect for election data processing, voter registration, and administrative tasks.
🌟 Features

Multi-format Support: PDF (OCR), TXT, CSV, Excel (.xlsx, .xls)
Drag & Drop Interface: Easy file upload with visual feedback
Manual Input: Direct text input with auto-detection of separators
Kannada Headers: Outputs data with proper Kannada column headers
Multiple Export Options: Copy to clipboard, download CSV, or Excel
Real-time Preview: See processed data before downloading
Smart Parsing: Auto-detects pipe (|), tab, comma, and space separators

📊 Output Columns
The tool generates spreadsheets with these Kannada headers:

ಮನೆ ಸಂಖ್ಯೆ - House Number
ಮತದಾರರ ಹೆಸರು - Voter Name
ಸಂಬಂಧ - Relationship
ಸಂಬಂಧಿಯ ಹೆಸರು - Relative's Name
ಲಿಂಗ - Gender
ವಯಸ್ಸು - Age
ಮತದಾರರ ಗುರುತಿನ ಚೀಟಿ ಸಂಖ್ಯೆ - Voter ID Number

🚀 Live Demo
Try it now!
💻 Usage
1. File Upload Method

Drag and drop your file onto the upload zone
Or click "Choose File" to browse and select
Supported formats: PDF (OCR), TXT, CSV, Excel

2. Manual Input Method

Paste your OCR text directly into the text area
Supports various separators (|, tab, comma, space)
Click "Process Data" to convert

3. Export Options

Copy to Clipboard: Paste directly into Excel/Google Sheets
Download CSV: Save as comma-separated values
Download Excel: Save as .xlsx file

📝 Input Format Examples
The tool accepts various input formats:
# Pipe separated (|)
123/A|राम कुमार|पुत्र|श्याम कुमार|M|25|ABCD1234567
124/B|सुनीता देवी|पत्नी|राम कुमार|F|23|EFGH2345678

# Tab separated
123/A	राम कुमार	पुत्र	श्याम कुमार	M	25	ABCD1234567

# Comma separated
123/A,राम कुमार,पुत्र,श्याम कुमार,M,25,ABCD1234567

# Space separated
123/A राम_कुमार पुत्र श्याम_कुमार M 25 ABCD1234567
🛠️ Technical Details
Built With

HTML5 - Structure and semantics
CSS3/Tailwind - Modern styling and responsive design
Vanilla JavaScript - Core functionality
PDF.js - PDF text extraction
SheetJS - Excel file processing

Browser Support

Chrome/Edge 80+
Firefox 75+
Safari 13+
Mobile browsers supported

File Size Limits

PDF files: Up to 50MB
Excel files: Up to 10MB
Text files: Up to 5MB

🔧 Installation & Setup
Option 1: Direct Use

Download or clone this repository
Open index.html in any modern web browser
Start using immediately - no server required!

Option 2: GitHub Pages Deployment

Fork this repository
Go to Settings → Pages
Enable GitHub Pages from main branch
Access via: https://yourusername.github.io/repository-name

Option 3: Local Development
bash# Clone the repository
git clone https://github.com/yourusername/repository-name.git

# Navigate to directory
cd repository-name

# Open in browser
open index.html
🎯 Use Cases

Election Management: Convert voter lists to standardized format
Data Migration: Transform legacy data into modern spreadsheets
Administrative Tasks: Process government documents
Research: Analyze demographic data
NGO Work: Organize community data

🔒 Privacy & Security

Client-side Processing: All data processing happens in your browser
No Server Upload: Files are never sent to external servers
No Data Storage: No data is stored or tracked
Offline Capable: Works without internet after initial load

📋 Requirements
For PDF Files

Must be OCR-processed (text-searchable)
Scanned image PDFs won't work without OCR

For Input Data

Minimum 3 fields per row required
Data should be consistently formatted
Special characters are supported

🐛 Troubleshooting
PDF not working?

Ensure PDF is OCR-processed (you can select/copy text)
Try converting to text file first

Data not parsing correctly?

Check if data uses consistent separators
Verify minimum 3 fields per row
Try manual input method

Excel export issues?

Try CSV export instead
Check browser compatibility

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
🙏 Acknowledgments

Built for Karnataka election data processing
Kannada language support for regional accessibility
Community feedback and testing
