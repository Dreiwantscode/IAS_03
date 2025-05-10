# IAS_03

# Advanced Cryptography Lab

This project demonstrates the implementation of advanced cryptographic techniques, including symmetric encryption, elliptic curve cryptography (ECC), post-quantum cryptography, homomorphic encryption, and zero-knowledge proofs (ZKP). It also includes a TLS 1.3 secure handshake implementation and traffic analysis using Wireshark.

---

## **Features**
1. **Symmetric Encryption**:
   - Implemented AES-GCM and ChaCha20 for secure encryption.
   - Compared performance and security features.

2. **Elliptic Curve Cryptography (ECC)**:
   - Generated ECC key pairs.
   - Performed secure key exchange using ECDH.
   - Encrypted and decrypted messages.

3. **Post-Quantum Cryptography**:
   - Demonstrated NTRU-like encryption using `pynacl`.
   - Performed secure key exchange and encryption.

4. **Homomorphic Encryption**:
   - Implemented the Paillier cryptosystem.
   - Performed addition and scalar multiplication on encrypted data.

5. **TLS 1.3 Secure Handshake**:
   - Implemented a TLS 1.3 server and client using Python's `ssl` module.
   - Captured and analyzed encrypted traffic using Wireshark.

6. **Zero-Knowledge Proofs (ZKP)**:
   - Implemented a basic ZKP to prove knowledge of a secret without revealing it.

---

## **How to Run**
### Prerequisites
- Python 3.x
- Required libraries:
  ```bash
  pip install pycryptodome phe pynacl
