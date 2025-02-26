# Secure-Data-Hiding-in-Image-Using-Steganography
## 📌 Project Overview  
This project implements **image-based steganography** to securely hide messages within images. Using Python and OpenCV, the system encodes text messages into pixel values, ensuring **invisible data transmission**. A **password-protected decryption** mechanism ensures that only authorized users can extract the hidden message.  

---

## 🔥 Features  
✔️ **Secure Message Embedding:** Hides text within an image without visible distortion.  
✔️ **Password-Protected Decryption:** Only users with the correct password can extract the message.  
✔️ **Efficient Pixel Encoding:** Uses dictionary-based character mapping for fast encryption.  
✔️ **Image Integrity Maintained:** No significant changes in the cover image.  
✔️ **Supports Common Image Formats:** Works with PNG, JPEG, and BMP images.  
✔️ **Lightweight & Fast Execution:** Minimal computational requirements.  

---

## 🛠️ Technologies Used  
- **Programming Language:** Python  
- **Libraries:**  
  - OpenCV (`cv2`) – For image processing.  
  - OS (`os`) – For handling system-level operations.  

---

## 🚀 How to Run  

### Prerequisites  
Ensure you have **Python 3+** installed with the following libraries:  
```bash
pip install opencv-python
1️⃣ Run the stego.py script:

bash
Copy
Edit
python stego.py
2️⃣ Enter the secret message when prompted.
3️⃣ Provide a password for security.
4️⃣ The script will generate an Encrypted Image (Encryptedmsg.jpg) with the hidden message.

🔓 Decoding (Retrieving the Message)
1️⃣ Run the script again:

bash
Copy
Edit
python stego.py
2️⃣ Enter the decryption password when prompted.
3️⃣ If the password is correct, the hidden message will be displayed.
4️⃣ If the password is incorrect, access is denied.

🎯 Use Cases
🔹 Secure communication for military & government agencies.
🔹 Data hiding for cyber forensics & digital investigations.
🔹 Confidential messaging for journalists & whistleblowers.
🔹 Private messaging for general users.

🔮 Future Enhancements
✅ Implement audio & video steganography.
✅ Improve encryption algorithms for enhanced security.
✅ Integrate with cloud-based secure messaging systems.
✅ Develop AI-based steganalysis to detect unauthorized hidden messages.
📜 License
This project is open-source and free to use. Feel free to modify and contribute!

🔗 GitHub Repository
Secure-Data-Hiding-in-Image-Using-Steganography

🤝 Contributing
Want to improve this project? Follow these steps:
1️⃣ Fork the repository.
2️⃣ Create a new branch (feature-improvement).
3️⃣ Commit your changes.
4️⃣ Push to your branch and create a Pull Request.
