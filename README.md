Product Authenticity Checker
A simple web-based application that checks whether a product is authentic by scanning a QR code or manually entering a product serial number.
Features
Scan product QR codes using the device camera.

Manually enter a product serial number.

Display authentic, fake, loading, and error states.

Support the Enter key for manual verification.

Responsive and clean user interface.

Uses the jsQR library for QR-code detection.

Simulates API verification with a 1.5-second delay.

Provides sample manufacturer, batch, and expiry details.
Technologies Used
HTML5

CSS3

JavaScript

Canvas API

How to Run
Option 1: Open Directly
Download or clone this repository.

Open the index.html file in a modern web browser.

Enter a serial number or start the QR scanner.

Manual Verification
Enter a product serial number in the input field.

Click Check Authenticity.

The application checks the entered value against the mock verification logic.

A result is displayed on the page.

QR Verification
Click Start Camera.

Allow camera access when requested.

Show a QR code to the camera.

The application reads the QR-code data automatically.

The scanned value is checked for authenticity.



Future Improvements
Add a real backend API for product verification.

Store product records in a database.

Add manufacturer authentication.

Generate and validate secure QR codes.

Prevent serial-number duplication.

Add scan history.

Improve QR-scanner controls and visual feedback.

Add batch number, manufacturing date, and expiry validation.




