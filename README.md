# 🔐Advanced-Folder-Encryption
## 📌 Overview
This project uses **encryption** to enable **secure folder encryption and decryption**.  
 Furthermore, for further protection, it **hides the folder or file after encryption** and restores it after decryption.  
 Additionally, the system has a **SMTP-based password-sharing feature** that makes sure the decryption key is sent securely via email.
## 🛠️ Technologies Used
- **Python** 🐍 (Core Programming)
- **AES Encryption (Cryptography Library)** 🔐
- **SMTP (Email Service for Key Sharing)** 📧
- **OS Module (For Hiding & Restoring Files/Folders)** 🗂️
- **Tkinter (GUI for User Interaction)** 🎨
  ## 📖 Features
✅ **Encrypt and Decrypt Folders & Files** using strong  encryption.  
✅ **Automatically Hides Files/Folders** after encryption.  
✅ **Restores Files/Folders** upon successful decryption.  
✅ **Secure Key Transmission** via SMTP email service.  
✅ **Graphical User Interface (GUI)** for easy usage.  
✅ **Prevents Unauthorized Access** to encrypted files.
## 🚀 Installation

### **Step 1: Clone the Repository**
```bash
git clone https://github.com/Akshaya-9753/advanced-folder-encryption.git
cd advanced-folder-encryption
```
### **Step 2: Install Required Dependencies**
pip install cryptography
pip install smtplib
### **Step 3: Run the Application**
python encryption_tool.py


🎯 How It Works

🔐 Encryption Process
 -To encrypt a file or folder, choose it.
 -The contents are secured using AES encryption.
 -For further security, the folder or file is automatically hidden.
 -After being generated, a decryption key is emailed.

 
 🔓 Decryption Process
 -After entering the decryption key that was sent to you via email 
 -The folder or file returns to its initial state and the concealed attribute is eliminated, restoring access.


🛡️ Security Considerations
🔹 Strong data protection is guaranteed by  encryption.
🔹 SMTP password-sharing guarantees safe key delivery.
🔹 Hidden files prevent unauthorized access to encrypted content.
🔹 the decryption key is never kept in plain text.





📬 Contact
For any issues or queries, contact:
📧 Email: battalaakshaya799@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/akshaya-battala-838434327/
