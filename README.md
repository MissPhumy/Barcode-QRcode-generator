# QR and Barcode Generator & Reader

Generate and read QR codes and barcodes effortlessly with this Python project. Whether you need to create a series of unique identifiers for products or decode information from images, this versatile tool has got you covered.

## Features

### Barcode Generation
Easily generate barcode images in various formats using the `barcode` and `qrcode` libraries. Simply provide a list of data, and watch as the script creates barcode images for each entry, ready to be printed or used in your applications.

### QR Code Generation
Need to encode more data? No problem! This project also supports QR code generation. Customize the size and scale of the QR codes to fit your needs. Perfect for embedding URLs, contact information, or any other data in a compact and easily scannable format.

### QR Code Reading
Not just for generating codes - this project also includes a script to read QR codes from images using OpenCV. Simply point the script to a folder containing images, and it will automatically detect and decode any QR codes it finds, providing you with the decoded data.

## Why Use This Project?

- **Efficiency**: Generate hundreds of barcodes or QR codes in seconds, saving you time and effort.
- **Flexibility**: Customize the appearance and content of your codes to suit your specific requirements.
- **Accuracy**: The QR code reader script ensures accurate decoding of QR codes from images, providing you with reliable data extraction.

## Getting Started

1. Clone the repository to your local machine.
2. Install the necessary dependencies using `pip`.
3. Run the provided scripts to generate codes or read QR codes from images.
4. Customize the scripts to fit your specific use case by modifying the data lists or adjusting parameters.

## Example Usage

### Barcode Generation
```
python generate_codes.py
```

### QR Code Reading

```
python read_qr_code.py
```

## Requirements
- Python 3.x
- barcode
- qrcode
- PIL (Python Imaging Library)
- OpenCV (cv2)

### Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

### Author
Missphumy (Prudence Radebe)
Email: missphumy@gmail.com
