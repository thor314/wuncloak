# Attack-Birthday Attack
A **Birthday Attack** is a family of attacks on any algorithm whose security relies on [collision resistence](https://wiki.uncloak.com/Collision Resistance). The attacker 

The attack is named for the [Birthday Paradox](https://en.wikipedia.org/wiki/Birthday_problem): given that there are about 365 possible birthdays, any room of 23 people will have greater than 50% chance that two share a birthday. More generally, given a sample space of $N$ values, a collision occurs with $\ge50\%$ probability after $\sqrt N$ samples.

Any collision-resistant algorithm targeting $n$ bits of security ($2^n$ possible values) should therefore possess an output range of at least $2n$ bits ($(2^n)^2=2^{2n}$ possible values).

Birthday attacks are also applicable when calculating the minimum necessary size for the key-space for encryption keys. If a key collision should occur with likelihood at most $2^{-128}$, then the key space must be at least $2^{256}$.

---
## Related Pages
- primary-topic:: [Cryptanalysis](https://wiki.uncloak.com/Cryptanalysis)
- secondary-topic:: [Hash Functions](https://wiki.uncloak.com/Hash Functions)
- secondary-topic:: [Probability Theory](https://wiki.uncloak.com/Probability Theory)
- related:: [Collision Attack](https://wiki.uncloak.com/Collision Attack)
- attack-on:: [Collision Resistance](https://wiki.uncloak.com/Collision Resistance)

## External Resources
- Wikipedia:: [Birthday attack](https://en.wikipedia.org/wiki/Birthday_attack)

## References
*This section is for citations of any claims made in the page*.