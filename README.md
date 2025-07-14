# File-Encryption-Decryption-Tool

Encryptor - Windows Application
DashBoard Screenshot

Overview
Encryptor is a Windows Forms-based application developed in C#/.Net that provides secure encryption and decryption functionalities. It allows users to encrypt and decrypt files and folders using AES and Twofish cryptographic algorithms. Additionally, it includes functionality to unzip compressed files before encryption or after decryption.

Features
Encrypt Files & Folders: Securely encrypt files and entire folders using AES and Twofish algorithms.
Decrypt Files & Folders: Easily decrypt previously encrypted files and folders.
Multiple Encryption Algorithms: Choose between AES (Advanced Encryption Standard) and Twofish.
File Compression Support: Automatically unzip files before encryption and after decryption.
User-Friendly Interface: Simple and intuitive Windows Forms UI for easy operation.
Cryptographic Algorithms Used
AES (Advanced Encryption Standard): A widely used symmetric encryption algorithm providing strong security.
Twofish: A fast and secure symmetric encryption algorithm, considered an alternative to AES.
Prerequisites
Before running the application, ensure you have the following installed:

Microsoft Visual Studio (with C#/.Net support and Windows Forms enabled)
Crypto++ Library (for AES and Twofish implementations)
zlib or any unzip library (for file decompression support) Unzip the file
Installation
Clone the repository:
git clone https://github.com/your-repo/encryptor.git
Open the project in Visual Studio.
Install necessary dependencies (Crypto++, zlib, etc.).
Build and run the application.
Usage
Launch the Encryptor application.
Select a file or folder for encryption or decryption.
Choose an encryption algorithm (AES or Twofish).
Click on the "Encrypt" or "Decrypt" button.
If dealing with compressed files, the application will handle unzipping automatically.
Save the output file or folder at the desired location.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Crypto++ for cryptographic functions.
zlib for file compression support.
Microsoft Windows Forms for GUI framework.
