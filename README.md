**IoT-Based Automated Medicine Dispenser**

**Overview**
This project is an IoT-based automated medicine dispenser designed to improve access to essential medicines in remote and underserved areas. It addresses challenges such as limited healthcare resources, difficulty in medicine distribution, and the risk of improper usage.
The system provides a secure, 24/7 solution for dispensing medicines with minimal human intervention.

**Features**

-> 24/7 automated medicine dispensing  
-> Secure access using RFID + PIN authentication  
-> Accurate pill dispensing using stepper motors  
-> Real-time data synchronization and monitoring  
-> Mobile app for medicine selection and tracking  
-> Credit-based controlled distribution system  

**How It Works :-**

1. Users register at a hospital and receive an RFID tag linked to their profile  
2. At the dispenser:
   - Enter a 4-digit PIN  
   - Scan RFID tag for authentication  
3. Available medicines are displayed in the mobile app  
4. User selects medicine and quantity  
5. Device dispenses medicine using a motor-controlled mechanism  
6. Credits are deducted and data is updated in real time  

**Hardware Used :-**

-> ESP32 NodeMCU Module  
-> RFID RC522 Tag & Reader  
-> Stepper Motor  
->A4988 Driver (Microstepping Motor Driver)  
-> Keypad  

**Software Used :-**

-> Firebase Realtime Database  
-> Flutter  

**System Architecture**
The system uses the ESP32 NodeMCU for control and internet connectivity. It communicates with Firebase to store and sync user data, medicine stock, and transaction details. A Flutter-based mobile app provides an easy-to-use interface for users.

 **Future Improvements**
 
-> Offline functionality with data sync  
-> Enhanced security mechanisms  
-> Smart prescription-based dosage limits  
-> Solar power integration for remote deployment  


## 📄 License
This project is for educational purposes.
