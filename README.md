# ImageEncryptor
 Image Encryptor is a desktop application that encrypts an image specified by entering a secret key and decrypts the image using the same.
 The file-based cryptography procedure is accomplished using the built-in encryption and decryption libraries in Java key.
 The tools used for the project is Netbeans.
 
 # Process of Image Encryptor
 ![Image-encryption-decryption-with-a-bitwise-XOR-operation](https://github.com/NITHISHRAM1/imageEncryption/assets/82199785/c22ea027-c599-4c4b-aea4-2cda68f1632e)
### Encryption:
  * XOR operation performed between each and every value of byte array and key due to which all data of Image get change and due to which we are unable to open our Image.
  * Now, whenever we apply a Decryption operation with the same key-value byte array value get the change to its original value and able to see our original Image.
### Decryption:
  * In the case of Image Decryption as well we convert out encrypted Image into its original form. Here we will use XOR operation to perform decryption as well.
     
  * As we observe in the above example of XOR that how we get our original value of byte array by performing XOR operation on output and key value. Same logic we will use here.
 
# Project Demo
 
https://user-images.githubusercontent.com/82199785/226251116-c84ae32e-8801-481a-a7f4-c77ca08d7500.mp4
