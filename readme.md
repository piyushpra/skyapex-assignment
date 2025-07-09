This is a web-based tool built using PHP and dompdf that allows you to generate a professional-looking Sale Deed PDF document by filling out a simple form.


-> How to Use
Install PHP and run a local server (e.g., XAMPP, WAMP, or MAMP).
Place the project folder inside your htdocs (for XAMPP) or equivalent.
Access it in the browser:
http://localhost/your-folder-name/

Fill in:

Full Name
Father’s Name
Property Size (in sq.ft)
Sale Amount (₹)
Date of the deed

Click Generate PDF and your sale deed will be downloaded.

----------------------------------------------------------


-> Requirements: 

PHP 7+
dompdf (included in the dompdf/ folder)
:- No need for Composer – just drop the files and it works.

----------------------------------------------------------

-> Validation Rules\

Full Name / Father's Name: Only letters and spaces
Property Size / Sale Amount: Must be positive numbers
Date: Must be selected using the calendar
