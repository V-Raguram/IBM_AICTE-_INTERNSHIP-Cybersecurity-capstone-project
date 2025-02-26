# IBM_AICTE-_INTERNSHIP-Cybersecurity-capstone-project
simple capstone Project for Cybersecurity internship (IBM+AICTE) 

Overview

This project implements steganography to hide a secret message inside an image by modifying its pixel values. The message can only be retrieved using the correct passcode, ensuring secure and hidden communication.

Features

✅ Secret Message Embedding – Hides text inside an image using pixel value modification.

✅ Passcode Protection – Ensures only authorized users can decrypt the message.

✅ Minimal Image Distortion – The image remains visually unchanged.

✅ Lightweight & Fast – Simple implementation using Python and OpenCV.


Technologies Used
Python – Programming language

OpenCV (cv2) – Image processing library

OS Module – To open the encrypted image

How It Works

1. Hiding the Message
The user enters a secret message and a passcode.
The algorithm modifies the pixel values of the image to store the message.
The modified image is saved as "encryptedImage.jpg".

3. Retrieving the Message
The user provides the correct passcode.
The algorithm extracts the message from the pixel values.
If the passcode is incorrect, access is denied.

Setup & Usage:

Prerequisites

Install Python (3.x)

Install required libraries using:

pip install opencv-python

Running the Script
Place an image named "mypic.jpg" in the project directory.
Run the script:

"python stego.py"

Enter the secret message and passcode when prompted.
Open the "encryptedImage.jpg" file to see the modified image.
To decrypt, enter the correct passcode when prompted.

Future Enhancements

🔹 Stronger encryption for added security

🔹 Randomized pixel embedding to prevent detection

🔹 Support for more image formats

🔹 User-friendly GUI or mobile app


License
This project is open-source and free to use for educational purposes.


