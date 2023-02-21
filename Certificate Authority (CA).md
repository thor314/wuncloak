# Term-Certificate Authority (CA)
In a PKI system, each user registers their public-key with a centrally trusted **Certificate Cuthority (CA)**. The user must prove ownership of their public-key, which they may do by [signing](https://wiki.uncloak.com/Signatures) a message. The CA returns a certificate, the CA's own signature of the user's public key. The user may then demonstrate ownership of their public-key by showing the certificate to other users.

To reduce risk that a CA may be compromised, PKI systems maintain several levels of CAs. The top root-level CA issues certificates for lower-level CAs. The lower-level CAs interact with users. Users may check that the lower-level CA is still trustworthy with the root CA.
```mermaid
flowchart TB
A(Root CA) --certifies--> B(User CA 1)
A --certifies--> C(User CA 2)
C <-..-> D(user)
C <-..-> E(user)
B <-..-> F(user)
B <-..-> G(user)
```


---
## Related Pages
*The related pages section is for linking this page other the rest of the graph, press F11 for details. If applicable, replace the following dummy links.*
- primary-topic:: [Public Key Infrastructure (PKI)](https://wiki.uncloak.com/Public Key Infrastructure (PKI))
- secondary-topic:: [Authentication](https://wiki.uncloak.com/Authentication)

## External Resources
- Wikipedia:: [Certificate Authority](https://en.wikipedia.org/wiki/Certificate_authority)

