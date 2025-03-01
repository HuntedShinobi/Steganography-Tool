# Python Steganography Tool
 Steganography Tool is a Python application that enables users to hide and extract secret messages within image files using LSB (Least Significant Bit) steganography. Built with Tkinter for the graphical user interface (GUI) and the Stegano library for image manipulation, this tool offers an easy and intuitive way to apply steganography techniques for secure communication. Use it responsibly and explore the fascinating world of hidden messages!

## Features

- Select an image file to hide a secret message.
- Enter a secret message in the provided text box.
- Hide the message within the selected image.
- Extract the hidden message from an image.
- User-friendly interface with clear instructions.

## Prerequisites
- Python 3.6 or above
- Required Python packages can be installed using the following command:
- pip install stegano
- pip install tkinter

## Usage

### Open terminal and use these commands.

```
git clone https://github.com/HuntedShinobi/Steganography-Tool.git
cd Steganography-Tool
pip install -r requirements.txt
python steganography.py
```

The graphical user interface (GUI) will open.


<img src="https://github.com/user-attachments/assets/f1b48756-db35-4177-b86b-fbf4feaf32d9" alt="Screenshot of the tool" width="500">


1. Click the "Select Image" button to choose an image file.

2. Enter your secret message in the "Secret Text" field.

3. Click the "Hide Message" button to hide the secret message within the selected image.

4. To extract the hidden message, click the "Extract Message" button.
