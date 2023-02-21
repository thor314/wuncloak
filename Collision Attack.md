# Attack-Collision Attack
**Collision attacks** (also meet-in-the-middle attack) are a superset of [birthday attacks](https://wiki.uncloak.com/Birthday Attack), where the attacker may pre-compute a table of values, in addition to waiting for a value to repeat.

As an example, suppose a system uses 100-bit keys to encrypt messages. The attacker, Eve, is interested in some set of common messages, for example the message, $m=$"Send Bob \$5". Eve computes $E(m,k)$ for $2^{x}$ values of $k$. Now if a user of the system transmits a message in the set of values Eve computed, Eve has $2^{x-100}$ chance that she has pre-computed the message, and may recover the user's key.

todo: [Shanks' Babystep-Giantstep Algorithm](https://wiki.uncloak.com/Shanks' Babystep-Giantstep Algorithm)

---
## Related Pages
- primary-topic:: [Cryptanalysis](https://wiki.uncloak.com/Cryptanalysis)
- secondary-topic:: [Hash Functions](https://wiki.uncloak.com/Hash Functions)
- related:: [Birthday Attack](https://wiki.uncloak.com/Birthday Attack)
- attack-on:: [Collision Resistance](https://wiki.uncloak.com/Collision Resistance)

## External Resources
- Wikipedia:: [Collision attack](https://en.wikipedia.org/wiki/Collision_attack)

## References
*This section is for citations of any claims made in the page*.