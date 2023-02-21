# Topic-Cryptography
**Cryptography** (also cryptology) is the practice and study of [cryptography engineers](https://wiki.uncloak.com/Cryptographically Secure|secure]] techniques for communication, [Authentication|authentication]], and computation in the presence of a malicious or interfering [Adversary, Security Model|adversary]]. [[Term-Cryptographer|Cryptographers](https://wiki.uncloak.com/Authentication|authentication]], and computation in the presence of a malicious or interfering [[Term-Adversary, Security Model|adversary](https://wiki.uncloak.com/Adversary, Security Model|adversary]]. [[Term-Cryptographer|Cryptographers](https://wiki.uncloak.com/Authentication|authentication]], and computation in the presence of a malicious or interfering [[Term-Adversary, Security Model|adversary). [[Term-Cryptographer|Cryptographers) and [[Term-Cryptography Engineer) draw on techniques from a wide range of fields (mathematics, information theory, computer science, computer security, electrical engineering, distributed systems, physics, and beyond) to construct protocols.

Cryptographic protocols are designed in mathematical [computational hardness assumptions](https://wiki.uncloak.com/Adversary, Security Model|security models]] based on [[Term-Computational Hardness Assumptions). In order to "break" a cryptographic scheme, an adversary must be able to either:
- break the computational hardness assumption by performing computation thought to be effectively impossible
- exploit any flaws in the security proof, or take advantage of a weak security model
- beyond the protocol, cryptographic implementations may be insecure to any of a variety of [side channel attacks](https://wiki.uncloak.com/Side-Channel Attacks), or inaccurately implement the protocol

Even a cryptographically-secure system is not necessarily invulnerable. Adversaries in the real world are capable of attacking non-cryptographic parts of a system, including insecure elements of the system beyond the cryptography, or attacking individuals themselves, who may (unintentionally or by force) release secure information. But an attacker who breaks the cryptographic components of a system is more difficult to detect. Attacks external to the cryptographic system typically leave some trace, analogous to a broken window next to the door. A successful cryptographic attack is akin to picking a lock: [vulnerabilities](https://wiki.uncloak.com/Vulnerability) in the cryptography may allow an attacker to repeatedly attack the system without detection until the vulnerability is patched.

## Reducing Trust Assumptions
Cryptography can be seen as a general tool for reducing the necessary trust assumptions in a system. Taking [insecure channel](https://wiki.uncloak.com/Encryption|encryption]] as an example, suppose [Alice and Bob|Alice and Bob](https://wiki.uncloak.com/Alice and Bob|Alice and Bob) would like to privately exchange messages in the over an [[Term-Insecure Channel). Without encryption, Alice and Bob have few options. They may trust a third party to securely deliver messages between them, but the third party may inspect the contents of their private conversations.

If they have access to [symmetric encryption](https://wiki.uncloak.com/Symmetric Encryption), they have the capacity to communicate privately, but only if they each possess a shared secret key for encryption and decryption. It's possible the couple are previously acquainted and have already exchanged secret keys, but if they are unfamiliar with one another, they're back to square one, needing to exchange secret keys over the insecure channel. Limiting ourselves to symmetric encryption, Alice and Bob might request keys from a symmetric-key management intermediary, but this scenario is identical to the prior section: the key intermediary would also have access to the secret key, and by extension, the ability to read the private communication.

Symmetric encryption in the prior scenario represents a significant reduction in the necessary amount of trust: if Alice and Bob already know and trust one another, there is no need for an intermediary at all. But [asymmetric encryption](https://wiki.uncloak.com/Asymmetric Encryption, Public Key Encryption) allows Alice and Bob to communicate without a trusted intermediary, whether or not they have previously communicated. With an asymmetric encryption, Alice and Bob may privately communicate without trusting any other party.

## Recommended Paths through this topic

## Applications

## History
The word cryptography comes from the Greek root words *kryptos*, meaning hidden, and *graphikos*, meaning writing. Prior to 1976, cryptography was limited to the study of [Diffie Helman Assumption](https://wiki.uncloak.com/Encryption|encryption]] techniques: techniques for encrypting from [Plaintext and Ciphertext|unhidden plaintext to inscrutible ciphertext](https://wiki.uncloak.com/Plaintext and Ciphertext|unhidden plaintext to inscrutible ciphertext), and decrypting ciphertext to plaintext. In 1976, cryptographers Whitfield Diffie and Martin Hellman introduced the [[Security Assumption-Diffie Helman Assumption), along with a new set of asymmetric primitives to the field of cryptography in their appropriately named paper, New Directions in Cryptography[^1].

---
## External Resources
- Wikipedia:: [Cryptography](https://en.wikipedia.org/wiki/Cryptography)

## References
*This section is for citations of any claims made in the page*.

[^1]: https://ee.stanford.edu/~hellman/publications/24.pdf