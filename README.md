# CapstoneProject-EC-ElGamal
This repository is designed to help understand elliptic curves and cryptosystems at a basic level. It includes implementations of elliptic curves, ElGamal encryption, elliptic curve ElGamal encryption, and the baby-step giant-step algorithm for attacks. Most of the code is available for both real numbers and finite fields.


The El-Gamal cryptosystem provides a secure encryption and decryption cryptosystem based on the fundamental principles of the Diffie-Hellman key exchange protocol.  
Main code is el_gamal_ec_pointmsg.py. This code demonstrates how the El-Gamal encryption system is applied on an elliptic curve. When selecting the elliptic curve, only the finite field F_p is used instead of the extended field F_p^n (different methods are used for the p^n case). It operates with large prime numbers used in El-Gamal encryption, but may experience a loss of performance with very large prime numbers.  


An $\textbf{elliptic curve}$ over a field $F$ of characteristic not equal to 2 or 3 is defined as a non-singular curve $E$ given by the equation:
        $E: y^2 = x^3 + ax + b$  
    where $x,y,a,b \in F$ and $\Delta = 4a^3 + 27b^2 \neq 0$. Additionally, the point at infinity, denoted by $\mathcal{O}$ is included as part of the curve.  
    The elliptic curves of the above form are called $\textbf{(short) Weierstrass Form}$ elliptic curves. The codes for elliptic curves are use this form and finite fields $F_p$ but not $F_{p^n}$. You can use large primes to construct an elliptic curve but may experience a loss of performance with very large prime numbers. Here the operations:  
    1: Elliptic Curve points and graph  
    2: Addition  
    3: Scalar multiplication  
    4: Scalar multiplication with double and add algorithm  
    5: Order of an element and its graph  


![Screenshot_2024-04-23_21-22-44](https://github.com/khesly1903/el-gamal/assets/98612716/4219b109-d95f-46c8-8cd0-bb2a58e569ea)
![Screenshot_2024-04-23_21-23-08](https://github.com/khesly1903/el-gamal/assets/98612716/e27c0bb8-7988-46bc-b8fe-e92a2943dec4)
