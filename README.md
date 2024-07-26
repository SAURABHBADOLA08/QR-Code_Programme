# QR-Code_Programme
This Programme a QR code with a customizable logo in the center. 

Import Libraries:

qrcode: A library for generating QR codes.
PIL (Pillow): A library for handling and manipulating images.
Load Logo Image:

The script opens an image file (2.jpg) that will be used as a logo in the center of the QR code.
Resize Logo Image:

The logo's width is set to a base width of 100 pixels while maintaining the aspect ratio.
The height of the logo is adjusted accordingly.
Create QR Code:

A new QR code object is created with a high error correction level (ERROR_CORRECT_H), which allows for more data recovery if the QR code is damaged.
Add Data to QR Code:

The QR code is populated with the URL or text ('https://github.com/SaurabhBadola8').
Generate QR Code:

The QR code is generated with the specified data.
Customize QR Code Color:

The QR code is rendered with a specified foreground color ('black') and a background color ('white').
Overlay Logo on QR Code:

The logo is centered on the QR code image.
The position for the logo is calculated so that it is placed in the center of the QR code.
Save the QR Code Image:

The final QR code with the logo is saved as an image file ('gfg_QR_result.png').
Completion Message:

The script prints a message indicating that the QR code has been generated successfully.
