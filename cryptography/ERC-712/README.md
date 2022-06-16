# EIP-712: Ethereum typed structured data hashing and signing 

🔗 https://eips.ethereum.org/EIPS/eip-712#definition-of-domainseparator

---

##  Simple Summary
Signing data is a solved problem if all we care about are bytestrings. Unfortunately in the real world we care about complex meaningful messages. Hashing structured data is non-trivial and errors result in loss of the security properties of the system.

As such, the adage “don’t roll your own crypto” applies. Instead, a peer-reviewed well-tested standard method needs to be used. This EIP aims to be that standard.

---

**Checks** | OpenZepplin | Projects | Audits
--- | --- | --- | ---
**Support** | ✅ | ✅ | **nicely**
**Links** | [🔗 draft-EIP712.sol](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/utils/cryptography/draft-EIP712.sol) | [gnosis/gp-v2-contracts](https://github.com/gnosis/gp-v2-contracts) | [multisig-diligence-audit.pdf](multisig-diligence-audit.pdf)