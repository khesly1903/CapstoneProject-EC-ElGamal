# CapstoneProject-EC-ElGamal
This repository is designed to help understand elliptic curves and cryptosystems at a basic level. It includes implementations of elliptic curves, ElGamal encryption, elliptic curve ElGamal encryption, and the baby-step giant-step algorithm for attacks. Most of the code is available for both real numbers and finite fields.


The El-Gamal cryptosystem provides a secure encryption and decryption cryptosystem based on the fundamental principles of the Diffie-Hellman key exchange protocol.  
Main code is el_gamal_ec_pointmsg.py. This code demonstrates how the El-Gamal encryption system is applied on an elliptic curve. When selecting the elliptic curve, only the finite field F_p is used instead of the extended field F_p^n (different methods are used for the p^n case). It operates with large prime numbers used in El-Gamal encryption, but may experience a loss of performance with very large prime numbers.  
![Screenshot_2024-04-23_21-22-44](https://github.com/khesly1903/el-gamal/assets/98612716/4219b109-d95f-46c8-8cd0-bb2a58e569ea)
![Screenshot_2024-04-23_21-23-08](https://github.com/khesly1903/el-gamal/assets/98612716/e27c0bb8-7988-46bc-b8fe-e92a2943dec4)
