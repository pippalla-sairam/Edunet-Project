# **Image Steganography - Hide Secret Messages in Images**

## **Overview**  
This project demonstrates a **basic steganography technique** that allows users to hide a **secret message** inside an image and retrieve it using a **passcode**. The message is embedded in the pixel values of the image, making it invisible to the human eye.  

---

## **Features**  
✅ Hide a secret message inside an image  
✅ Secure message retrieval using a passcode  
✅ Uses pixel modification for data hiding  
✅ Works with any image format supported by OpenCV  

---

## **Technology Used**  
- **Python**: Main programming language  
- **OpenCV (cv2)**: For image processing  
- **OS Module**: To open the encrypted image automatically  

---

## **How It Works?**  
1. The user **selects an image** and enters a **secret message** to hide.  
2. The program **modifies the pixel values** of the image to store the message.  
3. A **passcode is required** to decrypt and retrieve the hidden message.  
4. The modified image looks the same but contains **hidden data**.  

---

## **Installation & Setup**  
1. Clone the repository:  
   ```sh
   git clone <your-repository-link>
   cd <your-project-folder>
   ```  
2. Install dependencies:  
   ```sh
   pip install opencv-python
   ```  
3. Run the program:  
   ```sh
   python steganography.py
   ```  

---

## **Example Usage**  
### **Encryption Process**  
```plaintext
Enter secret message: Hello World!
Enter a passcode: 1234
(Encrypted image is saved as "encryptedImage.jpg")
```  

### **Decryption Process**  
```plaintext
Enter passcode for Decryption: 1234
Decryption message: Hello World!
```  

---

## **Future Scope**  
🔹 Support for **larger messages** using advanced encoding  
🔹 **AES encryption** for extra security  
🔹 A **GUI-based interface** for easy use  
🔹 Improved **image processing techniques** for better efficiency  

---
