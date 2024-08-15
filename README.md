<div align="center">
  <h1 align="center">Awesome FHE Attacks</h1>
  <p align="center">
    <a href="https://awesome.re">
        <img src="https://awesome.re/badge.svg" alt="Awesome" style="vertical-align: middle; margin-left: 10px;">
    </a>
    <a href="https://github.com/Hexens/awesome-fhe-attacks/pulls">
        <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs welcome" style="vertical-align: middle; margin-left: 10px;">
    </a>
  </p>

  <p align="center">
    A curated list of research, articles, tools, and resources focused on attacks against Fully Homomorphic Encryption (FHE). 
    This compilation is intended for researchers, practitioners, and anyone interested in the security aspects of FHE.
  </p>
</div>

## Table of Contents
- [Research Papers](#research-papers)
  - [IND-CCA/IND-CPA/IND-CPAD Attacks](#ind-ccaind-cpaind-cpad-attacks)
  - [Lattice Based Attacks](#lattice-based-attacks)
  - [Side-Channel Attacks](#side-channel-attacks)
  - [Key Recovery Attacks](#key-recovery-attacks)
  - [Reaction Attacks](#reaction-attacks)
  - [Cryptanalysis and Other Attacks](#cryptanalysis-and-other-attacks)
  - [Security Guidelines and Considerations](#security-guidelines-and-considerations)
  - [Attacks on FHE-based Machine Learning](#attacks-on-fhe-based-machine-learning)
- [Articles](#articles)
- [Talks and Presentations](#talks-and-presentations)
- [Tools and Resources](#tools-and-resources)
- [CTF Challenges](#ctf-challenges)

## Research Papers

### IND-CCA/IND-CPA/IND-CPAD Attacks:
- [On the IND-CCA1 Security of FHE Schemes](https://eprint.iacr.org/2021/1624.pdf)
- [Fully Homomorphic Encryption Beyond IND-CCA1 Security: Integrity Through Verifiability](https://eprint.iacr.org/2024/202.pdf)
- [Attacks Against the INDCPA-D Security of Exact FHE Schemes](https://eprint.iacr.org/2024/127.pdf)
- [On the Practical CPAD Security of "Exact" and Threshold FHE Schemes and Libraries](https://eprint.iacr.org/2024/116.pdf)
- [On the Security of Homomorphic Encryption on Approximate Numbers](https://eprint.iacr.org/2020/1533.pdf)
- [Securing Approximate Homomorphic Encryption using Differential Privacy](https://eprint.iacr.org/2022/816.pdf)

### Lattice Based Attacks:
- [A Hybrid of Dual and Meet-in-the-Middle Attack on Sparse and Ternary Secret LWE](https://eprint.iacr.org/2019/1114.pdf)
- [A Successful Subfield Lattice Attack on a Fully Homomorphic Encryption Scheme](https://eprint.iacr.org/2021/1626.pdf)
- [On Dual Lattice Attacks Against Small-Secret LWE and Parameter Choices in HElib and SEAL](https://eprint.iacr.org/2017/047.pdf)
- [Revisiting the Hybrid Attack on Sparse and Ternary Secret LWE](https://eprint.iacr.org/2019/1019.pdf)
- [Revisiting Orthogonal Lattice Attacks on Approximate Common Divisor Problems and Their Applications](https://eprint.iacr.org/2018/1208.pdf)
- [Lattice Attacks on the DGHV Homomorphic Encryption Scheme](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=d09cf1180c55cf6c29c62ebf6ce93a4409365e86)
- [Revisiting Lattice Attacks on Overstretched NTRU Parameters](https://www.di.ens.fr/~fouque/euro17a.pdf)
- [Benchmarking Attacks on Learning with Errors](https://eprint.iacr.org/2024/1229.pdf)
- [Hybrid Dual and Meet-LWE Attack](https://eprint.iacr.org/2022/1330.pdf)
- [Attack on Fully Homomorphic Encryption over the Integers](https://arxiv.org/pdf/1202.3321)

### Side-Channel Attacks:
- [Leaking Secrets in Homomorphic Encryption with Side-Channel Attacks](https://eprint.iacr.org/2023/1128.pdf)
- [Attacking FHE-based Applications by Software Fault Injections](https://eprint.iacr.org/2016/1164.pdf)

### Key Recovery Attacks:
- [Key Recovery Attacks on Approximate Homomorphic Encryption with Non-Worst-Case Noise Flooding Countermeasures](https://www.usenix.org/system/files/sec24summer-prepub-822-guo.pdf)
- [A Practical Full Key Recovery Attack on TFHE and FHEW by Inducing Decryption Errors](https://eprint.iacr.org/2022/1563.pdf)
- [Securing FHE from Reaction-based Key Recovery Attacks](https://eprint.iacr.org/2023/561.pdf)
- [On NTRU-ν-um Modulo X^N − 1](https://eprint.iacr.org/2022/1092.pdf)

### Reaction Attacks:
- [Reaction Attack on Outsourced Computing with Fully Homomorphic Encryption Schemes](https://zhenfeizhang.github.io/pdf/pracfheatt.pdf)

### Cryptanalysis and Other Attacks:
- [Cryptanalysis of Homomorphic Encryption Schemes based on the Approximate GCD Problem](https://www.scitepress.org/Papers/2019/80716/80716.pdf)
- [Plaintext Recovery Attacks against Linearly Decryptable Fully Homomorphic Encryption Schemes](https://eprint.iacr.org/2020/264.pdf)
- [On the Hardness of the Finite Field Isomorphism Problem](https://eprint.iacr.org/2022/998.pdf)

### Security Guidelines and Considerations:
- [Security Guidelines for Implementing Homomorphic Encryption](https://eprint.iacr.org/2024/463.pdf)
- [Danger of Using Fully Homomorphic Encryption: A Look at Microsoft SEAL](https://arxiv.org/pdf/1906.07127)

### Attacks on FHE-based Machine Learning:
- [Model Stealing Attacks On FHE-based Privacy-Preserving Machine Learning through Adversarial Examples](https://eprint.iacr.org/2023/1665.pdf)


## Articles
- [On the Security of FHE in the "Slightly Beyond Passive" Adversary Regime](https://www.linkedin.com/pulse/security-fhe-slightly-beyond-passive-adversary-regime-renaud-sirdey-fen0e/)
- [Estimating the Security of Homomorphic Encryption Schemes](https://www.zama.ai/post/estimating-the-security-of-homomorphic-schemes)
- [Decoding Cryptographic Security: GCD, AGCD, and Lattice Attacks](https://tejnaren07.medium.com/decoding-cryptographic-security-gcd-agcd-and-lattice-attacks-cab9d8ed6b54)
- [Security and Cryptography](https://docs.zama.ai/tfhe-rs/get-started/security_and_cryptography)
- [New Key-Recovery Attacks Against FHE](https://www.zellic.io/blog/fhe-security-attacks/)

## Talks and Presentations
- [Damien Stehlé - Attacks Against the INDCPA-D Security of Exact FHE Schemes](https://www.youtube.com/watch?v=YvBZIcUVXZ8)
- [FHE Beyond IND-CCA1 Security w/ Jérôme Nguyen](https://www.youtube.com/watch?v=ssLXxH22xqQ)
- [Danger of Using Fully Homomorphic Encryption - Zhiniang Peng](https://www.youtube.com/watch?v=o52Y7UNli10)
- [On the Security of Homomorphic Encryption on Approximate Numbers](https://www.youtube.com/watch?v=1pcNGXqyiTo)
- [A Subfield Lattice Attack on Overstretched NTRU Assumptions - Cryptanalysis of Some FHE and Graded En.](https://www.youtube.com/watch?v=FB4_C3XWsWU)
- [Estimating the Difficulty of Breaking Lattice-Based Cryptography w/ Martin Albrecht](https://www.youtube.com/watch?v=BIDBfVFzuck)
- [LWE with Side Information: Attacks and Concrete Security Estimation](https://www.youtube.com/watch?v=wCaLcbWnwDI)
- [On the Hardness of the Finite Field Isomorphism Problem w/ Antoine Joux](https://www.youtube.com/watch?v=74wsTqr-b9I)
- [On Dual Lattice Attacks Against Small Secret LWE and Parameter Choices in HElib and SEAL](https://www.youtube.com/watch?v=NQ4pHmNBbAU)

## Tools and Resources
- [Lattice Estimator](https://github.com/malb/lattice-estimator)
- [IND-CPA-D Attacks](https://github.com/hmchoe0528/INDCPAD_HE_ThresFHE)
- [Benchmarking Attacks on Learning with Errors (LWE)](https://github.com/facebookresearch/LWE-benchmarking)

## CTF Challenges
- [PCTF2017 - FHE](https://duksctf.github.io/2017/04/24/PCTF2017-FHE.html)
- [PHEnomenal](https://ctftime.org/writeup/27171)
- [CryptoCTF 2021 Lower](https://11dimensions.moe/archives/267)
- [PwnThyBytes CTF 2019 – Wrong Ring](https://mslc.ctf.su/wp/pwnthybytes-ctf-2019-wrong-ring-crypto/)
- [PlaidCTF 2016 – sexec](https://mslc.ctf.su/wp/plaidctf-2016-sexec-crypto-300/)
- [HITCON CTF 2022 - Easy NTRU](https://hackmd.io/@vishiswoz/ryDA_PGPo)
