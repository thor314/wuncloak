# Security Model-Black-box Model
A **Black-box Model** describes what an [adversary](https://wiki.uncloak.com/Adversary, Security Model) may see as input and output to a cryptographic system. In a black-box model, the internal workings of the system lie inside the black-box: the adversary cannot see them, only test inputs to the system and observe the system's response. Black box models are used, for example, to analyze the security of encryption:
- [Chosen-Plaintext Attack (CPA)](https://wiki.uncloak.com/Chosen-Plaintext Attack (CPA)) - the adversary can choose plaintexts to encrypt and observe the outputs, but not analyze the execution of the algorithm within the black-box.
- [Chosen Ciphertext Attack (CCA)](https://wiki.uncloak.com/Chosen Ciphertext Attack (CCA)) - the adversary can choose plaintexts to encrypt and ciphertexts to decrypt, but not analyze the execution of the algorithm within the black-box.

Black box models are useful for analyzing the security of an algorithm in isolation, but are less realistic for real-world implementations, where attackers may be able to obtain the software or hardware implementing the algorithm. In the real world, [white box](https://wiki.uncloak.com/Side-Channel Attacks|side-channel attacks]] may extrapolate key information from binary analysis on software implementations, and power-differential attacks on hardware implementations. [Grey-box Model|Grey box](https://wiki.uncloak.com/Grey-box Model|Grey box) and [[Security Model-White-box Model) analysis models allow attackers to possess some or all knowledge of the internal workings of an algorithm.

---
## Related Pages
- primary-topic:: [Cryptography](https://wiki.uncloak.com/Cryptography)
- secondary-topic:: [Side-Channel Attacks](https://wiki.uncloak.com/Side-Channel Attacks)
- term:: [Grey-box Model](https://wiki.uncloak.com/Grey-box Model)
- term:: [White-box Model](https://wiki.uncloak.com/White-box Model)

## External Resources
- Wikipedia:: [Black box](https://en.wikipedia.org/wiki/Black_box)
- Investopedia:: [Black box](https://www.investopedia.com/terms/b/blackbox.asp)