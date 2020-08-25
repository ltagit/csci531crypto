# csci531crypto
CSCI 531 - applied cryptography @ USC
Research Paper Specs:
Research and design a privacy-preserving digital medical data system with proper access control and authorization methods
with varying levels of document access based on identities.

Based on credentials (e.g. doctors, nurses etc), each user should only have access to data needed to complete their jobs
without revealing more data than needed.

This paper explores the use of IBE (identity based encryption) as proposed by Adi Shamir in his paper,
Adi Shamir. Identity-based cryptosystems and signature schemes. In Proceedings of CRYPTO 84 on Advances in cryptology, pages 47-53. Springer-Verlag New York, Inc.,1985

This paper also explores ABE (attribute based encryption) techniques that were propsed by Sahai and Waters in their paper:
Sahai, A., Waters, B. 2004. Fuzzy Identity-Based Encryption. Cryptology ePrint Archive. 2004/086. 

This paper not only compares IBE and ABE with PKI methods, but also outlines some of the benefits and detriments of IBE/ABE
and attempts to tackle the design problem mentioned above.

Design specs:
The environment contains a medical facility with a private Lan, with some devices connected via wireless links,
uses various encryption schemes to accomplish the wanted demarcations, and creates a hierarchical access control architecture 
to satisfy the requirements.
