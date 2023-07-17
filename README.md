# QR Code Generator

This is a simple Python program that generates a QR code using the `pyqrcode` library. The generated QR code can be saved as an SVG file.

## Prerequisites

Before running this program, make sure you have the `pyqrcode` library installed.<br>
 You can install it by running the following command:

<!-- ```shell -->
pip install pyqrcode

##  Usage
Run the program and enter the text or link for which you want to generate a QR code..<br>
The program will create a QR code using the pyqrcode.create() function..<br>
The QR code will be saved as an SVG file with the name qr_code.svg..<br>
Open the generated SVG file to view the QR code..<br>

HOSTED LINK: https://lambent-alpaca-062c66.netlify.app


## Getting Started
1. Clone this repository to your local machine.
2. Install the pyqrcode library by running the following command:

```pip install pyqrcode```

1.Run the Python program by executing the following command:

```python qr_code_generator.py```

2. Follow the prompts to enter the text or link for which you want to generate a QR code.
   
3. After running the program, you will find the generated QR code as an SVG file named qr_code.svg in the current working directory.


# NOTE :
After importing the pyqrcode module, the code prompts the user to enter the text or link for which they want to generate the QR code. The input is stored in the data variable.

The pyqrcode.create() function is then used to create a QR code object based on the provided data.

The .svg() method of the QR code object is used to save the QR code as an SVG (Scalable Vector Graphics) file. The method takes two arguments: the file name to save the QR code as (qr_code.svg in this case), and the scale parameter which determines the size of the QR code in the SVG file (in this case, a scale of 8 is used).

## Contributing
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License.


