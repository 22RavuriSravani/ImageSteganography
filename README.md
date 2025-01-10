# Image Steganography – Securing Method of Communication

In today's digital age, data security is paramount. This project focuses on **Image Steganography** using the **Least Significant Bit (LSB)** technique to conceal sensitive data within images, enabling secure and covert data transmission.

## 🚀 **Features**
- **Data Concealment**: Embed sensitive messages or files into images using the LSB technique.
- **Secure Communication**: Ensures confidentiality, even when intercepted by third parties.
- **Lossless Image Compression**: Supports **PNG format** to preserve image quality during data embedding.
- **Custom Decoder**: Extracts the hidden data from steganographic images with accuracy.


## 📂 **Project Structure**
- **Sender Functionality**: 
  - Converts images into binary form.
  - Replaces least significant bits of the image with the binary form of the message.
- **Receiver Functionality**:
  - Decodes the binary data from the image to reconstruct the hidden message.
- **Supported Formats**: 
  - PNG (Lossless compression ensures data integrity).
  - Other formats tested for understanding implications of compression.


## 🛠️ **Technologies Used**
- **Programming Language**: Java
- **Techniques Used**: 
  - Least Significant Bit (LSB) method
  - Lossless image compression
- **Development Tools**: Java Applets for UI

## 📸 **How It Works**
1. **Original Image**: A regular image (e.g., a sunset).
2. **Encoded Image**: The same image with hidden data, visually undetectable.
3. **Decoded Message**: The original message extracted using the application.


## 🔍 **Challenges**
- Different image formats handle compression differently, affecting data embedding.
- Focused on **PNG format** due to its **lossless compression**.
- Tested various formats to evaluate consistency in hiding data.


## 📋 **Installation and Usage**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/image-steganography.git
   cd image-steganography

2. Compile and run the application:
   ```bash
   javac SteganographyApp.java
   java SteganographyApp
3. Use the UI to:
    - Upload an image.
    - Enter a message to encode.
    - Decode messages from received images.



## 📬 **Contact**
For any questions or contributions, feel free to contact me at: ravurisravani54@gmail.com
