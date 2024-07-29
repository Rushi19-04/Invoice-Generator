# Invoice Generator

## Description

This is a Python application for generating invoices using a simple GUI built with Tkinter. The application allows users to input customer information and item details, and it generates a formatted invoice using a Word template.

## Features

- Input customer details: first name, last name, and phone number.
- Add multiple items with quantity, description, and unit price.
- Automatically calculates line totals, subtotal, sales tax, and grand total.
- Generates a Word document invoice using the `python-docx-template` library.
- Provides options to clear the form and start a new invoice.

## Prerequisites

- Python 3.x
- Required Python libraries:
  - `tkinter` (usually included with Python standard libraries)
  - `docxtpl`
  - `datetime`

## How to Run

1. Ensure you have Python and the required libraries installed. You can download Python from [python.org](https://www.python.org/).

2. Save the provided scripts (`main.py` and `invoice_template.docx`) to your local machine.

3. Open a terminal or command prompt.

4. Navigate to the directory where the scripts are saved.

5. Run the main script using the command:
   ```sh
   python main.py
   ```

### invoice_template.docx

The template file contains placeholders for customer details, item list, and totals. These placeholders are filled in by the `docxtpl` library when generating the invoice.

## Usage

1. Launch the application using the steps described above.

2. Enter customer details (first name, last name, phone number).

3. Add items to the invoice by specifying the quantity, description, and unit price, then clicking "Add item".

4. Once all items are added, click "Generate Invoice" to create the invoice document.

5. To start a new invoice, click "New Invoice".

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software as per the terms of the license.


