# Attack-Man In The Middle (MITM)
If Alice has no way to authenticate that she is communicating with her intended recipient (Bob), her messages may be intercepted and manipulated by Eve in a man-in-the-middle attack. Eve may initiate communication with Bob while pretending to be Alice, decrypting all traffic, and re-encrypting it with her own key before passing it back to Alice.
```mermaid
flowchart LR
A(Alice) -.Hey Bob, can we establish secret?.-> E(Eve)
E -.Hey Bob, Can we establish secret key? <3 Alice.-> B(Bob)
B -.Sure Alice. .-> E
E -.Sure Alice. <3 Bob.-> A
```

## Affected algorithms

---
## Related Pages
- primary-topic:: [Authentication](https://wiki.uncloak.com/Authentication)
- secondary-topic:: [Asymmetric Encryption, Public Key Encryption](https://wiki.uncloak.com/Asymmetric Encryption, Public Key Encryption)

## External Resources
- Wikipedia:: [Man-in-the-middle attack](https://en.wikipedia.org/wiki/Man-in-the-middle_attack)