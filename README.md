# QRgenerator

This is a simple QR code generator web application that allows you to generate QR codes for various types of data using HTML, CSS, and JavaScript, while utilizing the [QR Server API](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=).

## Features

- Generate QR codes for URLs, text, contact information, and more.
- Customize the QR code size and data.
- Download generated QR codes for your use.
- Easy-to-use and user-friendly interface.

## How to Use

1. Clone or download this repository to your local machine.

2. Open the `index.html` file in a web browser to launch the QR code generator application.

3. Enter the data for which you want to generate a QR code in the input field.

4. Optionally, customize the QR code size by adjusting the input fields for width and height.

5. Click the "Generate QR Code" button.

6. Your QR code will be generated and displayed on the screen.

7. You can right-click on the generated QR code and select "Save image as..." to download the QR code to your device.

## API Usage

This web application utilizes the [QR Server API](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=) to generate QR codes. The JavaScript code in the `script.js` file makes HTTP requests to this API to create QR codes based on the data you provide.

You can customize the API URL in the JavaScript code if you want to use a different QR code generation service or modify the parameters.

```javascript
// Modify this URL to use a different QR code generation service if needed
const qrCodeApiUrl = "https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=";
