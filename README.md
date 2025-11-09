# Finance Data Automation System
Developed a suite of three integrated Python scripts to automate personal finance management, covering income, expenses, and invoice processing. The system streamlined repetitive financial tracking tasks, reduced errors, and improved data transparency through automated reporting. It demonstrates strong use of Python OOP, file and email automation (IMAP), PDF and CSV parsing, Excel manipulation, data validation, and workflow optimisation.

## Process Invoices
Connects securely to an Outlook inbox via IMAP, retrieves emails from predefined senders, extracts attached invoices or reports (PDF/CSV), and saves them in structured folders by financial year and date range.

## Process Income
Reads income transaction CSV files from multiple financial year directories, consolidates them into an Excel workbook, updates totals automatically, and prevents duplicate entries.

## Process Expenses
Records and organises expenses within an Excel workbook, automatically sorting them by date and financial year, calculating totals, and maintaining backup copies of previous files.
