# Term-Adversary, Security Model
In cryptography, an **adversary** is an abstract malicious entity with some set of capabilities that may be employed toward interfering with a cryptographic system. Security models define adversaries under which the system can be proven [cryptographers](https://wiki.uncloak.com/Cryptographically Secure|secure]]. The strength of the security model defines the provable security of the system; [[Term-Cryptographer) therefore attempt to prove system security with the strongest possible adversaries.

As an example, a typical encryption adversary may want to recover the cipher key, though the adversary may possess other goals as well. A weak adversary may have the ability to intercept [Chosen Ciphertext Attack](https://wiki.uncloak.com/Plaintext and Ciphertext|ciphertext]] in-transit ([Ciphertext Only Attack|ciphertext only attack]]), but a strong adversary may be able to ask a [Black-box Model|black box oracle](https://wiki.uncloak.com/Ciphertext Only Attack|ciphertext only attack](https://wiki.uncloak.com/Black-box Model|black box oracle](https://wiki.uncloak.com/Ciphertext Only Attack|ciphertext only attack)), but a strong adversary may be able to ask a [[Security Model-Black-box Model|black box oracle) to decrypt any ciphertext or encrypt any plaintext (a [[Security Model-Chosen Ciphertext Attack (CCA))). The latter model may seem paradoxical--the adversary can already decrypt any ciphertext--but if the adversary still cannot retrieve the key given these advantages, then the encryption system is demonstrably secure.

---
## Related Pages
- primary-topic:: [Cryptography](https://wiki.uncloak.com/Cryptography)
- secondary-topic:: [Cryptanalysis](https://wiki.uncloak.com/Cryptanalysis)
- term:: [Cryptographically Secure](https://wiki.uncloak.com/Cryptographically Secure)

## External Resources
- Wikipedia:: [Provable security](https://en.wikipedia.org/wiki/Provable_security)
- Wikipedia:: [Adversary](https://en.wikipedia.org/wiki/Adversary_(cryptography))

Todo: promote security model into an object or topic?