# Digital Signature Verification System

**Digital Signature Verification** is a project built using Django and Elliptic Curve Cryptography (ECC) to ensure the authenticity and integrity of digital communications. The system provides a secure and user-friendly interface that allows users to generate cryptographic keys, sign messages, and verify digital signatures.

## 🔑 Key Features

- **Generate Key Pair**: Create a unique public and private key pair using elliptic curve cryptography.
- **Sign Messages**: Sign messages with the private key to generate a secure digital signature.
- **Verify Signatures**: Validate the authenticity of messages using the public key and corresponding signature.
- **Secure and Intuitive Interface**: A simple interface for easy key generation, signing, and verification.
- **Elliptic Curve Digital Signature Algorithm (ECDSA)**: Uses ECDSA for secure cryptographic operations.

## 🖥️ Live Demo

Check out the live version of the project here: [Digital Signature Verification](https://digital-signature-verification.vercel.app/)

## 📸 Screenshots

| Generate Key Pair | Sign Message | Verify Signature |
|-------------------|--------------|------------------|
| ![Generate Key](/assets/Generate_Key.jpg) | ![Sign Message](/assets/Sign_Message.jpg) | ![Verify Signature](/assets/Verify_Signature.jpg) |

**Clone the Repository**:

   ```bash
   git clone https://github.com/Pratham-verma/Digital_Signature_Verification
   ```
## 📚 How It Works

1. **Generate Key Pair**: 
   - Users can generate a unique pair of public and private keys.
   
2. **Sign Message**:
   - Input a message which you want to authenticate and use the private key to sign it, producing a digital signature.
   
3. **Verify Signature**:
   - Input the public key, original message, and digital signature to verify the message’s authenticity.

## 🛠️ Technologies Used

- **Backend**: Django
- **Cryptography**: Elliptic Curve Cryptography (ECC), ECDSA
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: postgesql
- **Deployment**: Vercel, Supabase

## 💡 Future Improvements

- Add support for different cryptographic algorithms.
- Add a documents instead of message to authenticate.
- Designed and integrated a certificate generation module.
- Enhance security features, such as key storage and management.
- Implement a more detailed logging and audit system for signing and verification activities.

## 🤝 Contributing

Feel free to open issues or submit pull requests to help improve the project!
