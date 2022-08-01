# AN ENHANCEMENT OF WEBSITE SECURITY USING FACE AUTHENTICATION
This project developed a web API that can log people into their accounts by recognising user’s faces to demonstrate the viability of this concept, and in this project develop a straightforward website to test the dependability of MFA system. We have implemented Flask web application login page including face verification, for security purpose. Im using SQLite Studio to store the public key of the users, and the private key will be stored in the face photos sub-directory once the script identified a single face.

Objectives: 
To design face recognition login that more accessible to and software developers by using machine learning techniques
To develop a website context using multi-factor authentication (MFA) : password-based and face recognition
To evaluate functionaltiy and usability of authentication method for face login using webcam or laptop's camera

Note: This project is not an end-to-end solution because it doesn't work in a client-server manner (no use of WebRTC) which means that end users need to have python and all libraries installed (absolutely not practical in a real-world solution). The project meant to work as a starting point or to provide the idea of how all components work together. 
