Image-Based Steganography for Secure Message Hiding
Overview
This project implements image-based steganography to securely hide and retrieve messages within an image. It modifies pixel values to embed secret text while maintaining the image’s visual integrity. A passcode authentication system ensures only authorized users can decrypt the message.

Features
✅ Hides secret messages inside images using pixel manipulation.
✅ Passcode authentication for secure decryption.
✅ Minimal image distortion while embedding data.
✅ Simple and lightweight Python implementation.
✅ Works on Windows OS using OpenCV and VS Code.

Technologies Used
Programming Language: Python
Libraries: OpenCV (cv2), OS, String
Platform: Windows OS
IDE: Visual Studio Code
Installation & Usage
1. Clone the Repository
git clone https://github.com/Misba810/aictesteganography
cd aictesteganography

2. Install Dependencies
Ensure you have Python installed, then install OpenCV:
pip install opencv-python

3. Run the Script
python stego.py

5. Enter Inputs
Provide the secret message to hide.
Set a passcode for decryption security.
The modified image will be saved as encryptedImage.jpg.

6. Decrypt the Message
Run the script again and enter the correct passcode to retrieve the hidden message.
