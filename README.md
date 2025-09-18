# PDFProtector

A simple Python utility to **create a password-protected PDF** file.

# Features
- Reads an existing PDF and writes a copy that requires a password to open.
- Works on any PDF that is not already encrypted.
- Cross-platform (Windows / macOS / Linux).

# Requirements
- Python 3.8+
- [PyPDF2](https://pypi.org/project/PyPDF2/)

Install the dependency:
pip install PyPDF2

Usage
Run from the command line:
python pdf_protector.py <input_pdf> <output_pdf> <password>

Arguments:
<input_pdf> : Path to the source PDF.
<output_pdf> : Path where the password-protected PDF will be saved.
<password> : The password users will need to open the protected file.

Example:
python pdf_protector.py report.pdf report_protected.pdf MySecret123
This creates report_protected.pdf which can only be opened using the password MySecret123.

Notes
Ensure the input PDF is not already encrypted.
Keep your password safe—losing it means you may not be able to open the protected file yourself.

csharp
Copy code
