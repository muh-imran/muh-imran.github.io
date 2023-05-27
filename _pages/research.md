---
layout: archive
title: "Publications and preprints"
permalink: /research/
author_profile: true
---
### <u>Hidden stabilizers and the Isogeny to Endomorphism Ring Problem</u>
(February - 2023) <br>Author: [Mingjie Chen](https://www.birmingham.ac.uk/staff/profiles/computer-science/research-fellow/chen-mingjie.aspx), [Muhammad Imran](https://muh-imran.github.io), [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/), [Péter Kutas](https://sites.google.com/view/peterkutas89/main-page?authuser=0), [Antonin Leroux](https://tonioecto.github.io/antoninleroux/), & [Christophe Petit](https://christophe.petit.web.ulb.be/index.html). 

The \emph{Isogeny to Endomorphism Ring Problem} (IsERP) asks to compute the endomorphism ring of the codomain of an isogeny between supersingular curves in characteristic $p$ given only a \emph{representation} for this isogeny, i.e. some data and an algorithm to evaluate this isogeny on any torsion point. This problem plays a central role in isogeny-based cryptography; it underlies the security of 
pSIDH protocol (ASIACRYPT 2022) and it is at the heart of the recent attacks that broke the SIDH key exchange. Prior to this work, no efficient algorithm was known to solve IsERP for a generic isogeny degree, the hardest case seemingly when the degree is prime. 

In this paper, we introduce a new quantum polynomial-time algorithm to solve IsERP for isogenies whose degrees are odd and have $O(\log\log p)$ many prime factors. As main technical tools, our algorithm uses a quantum algorithm for computing hidden Borel subgroups, a group action on supersingular isogenies from EUROCRYPT 2021, various algorithms for the Deuring correspondence and a new algorithm to lift arbitrary quaternion order elements modulo an odd integer $N$ with $O(\log\log p)$ many prime factors to powersmooth elements.

As a main consequence for cryptography, we obtain a quantum polynomial-time key recovery attack on pSIDH. The technical tools we use may also be of independent interest.

---
### <u>Zero sum subsequences and hidden subgroups</u>
(April - 2023) <br>Authors: [Muhammd Imran](https://muh-imran.github.io) & [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/). <br>The paper is submitted for publication. The preprint version is available on [arXiv](https://arxiv.org/abs/2304.08376).
  
In this project, we succeed to construct the first exact quantum hidden subgroup algorithm for a class of non-abelian groups, namely nilpotent groups of constant class and the prime factors of the group order are also constant. The main key of the algorithm is by series of reductions to groups of smaller nilpotency class (through its central series) using new zero sum subsequences algorithm in the group $\mathbb{Z}_p^n$ for prime number $p$. 

---

### <u>A private set intersection protocol based on multi-party quantum computation for greatest common divisor</u>
(March - 2023) <br>Author: [Muhammad Imran](https://muh-imran.github.io). <br>The paper is submitted for publication. The preprint version is available on [Cryptology ePrint Archive](https://eprint.iacr.org/2023/476).

Private set intersection (PSI) is a cryptographic primitive that allows two or more parties to learn the intersection of their input sets and nothing else. In this paper, we present a private set intersection protocol based on a new secure multi-party quantum protocol for greatest common divisor (GCD). Performance analysis guarantees the correctness and it also shows that the proposed protocols are completely secure in semi-honest model. Moreover, the complexity is proven to be efficient (poly logarithmic) in the size of the input sets.


---
### <u>An exact quantum order finding algorithm and its applications</u>
(May - 2022) <br>Author: [Muhammad Imran](https://muh-imran.github.io). <br>The paper is submitted for publication. The preprint version is available on [arXiv](https://arxiv.org/abs/2205.04240).

We propose an efficient exact quantum order finding algorithm where a multiple of the order is known. As applications, it derandomizes the quantum algorithm for primality testing proposed by Donis-Vela and Garcia-Escartin. In the field of quantum cryptography, we propose an improved version of the multiparty quantum computation for least common multiple proposed recently by Li and Liu. Finally, the algorithm serves as a subroutine of an efficient exact quantum algorithm for finding primitive elements in arbitrary finite fields.

---

### <u>An exact quantum hidden subgroup algorithm and applications to solvable groups</u>
(February - 2022) <br>Authors: [Muhammd Imran](https://muh-imran.github.io) & [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/). <br>The paper is available on [Quantum Inf. Comput.](https://doi.org/10.26421/QIC22.9-10-4) or the preprint version on [arXiv](https://arxiv.org/abs/2202.04047).

The natural characteristic of quantum algorithms is probabilistic, since it takes advantage from the quantum principles (superposition, interference, entanglement, etc.). Therefore, it is a natural question whether it is possible to boost up the probability to certainty while maintaining the efficiency. In the hidden subgroup problem, the existing of exact quantum algorithms is still limited. In this paper, we construct an exact quantum algorithm for the hidden subgroup problem in the infinite family of groups $\mathbb{Z}_{m^k}^n$ and its the applications in some computational problems in solvable groups.

---

# Research in progress

---

### <u>Stripped, multidimensional version of the Childs–van Dam approach to the hidden multiple shift problem</u>
Author: [Muhammd Imran](https://muh-imran.github.io).

The hidden multiple shift problem (HMS) can be seen as an interpolation between the abelian and dihedral hidden subgroup problems. The study of HMS recently appears as a promising approach to both lattice-based and  isogeny-based cryptography, see [BKSW18](https://link.springer.com/chapter/10.1007/978-3-319-76581-5_24) and [IIKL23]() respectively. In this project, we would like to construct a stripped version of the [Childs-van Dam](https://arxiv.org/abs/quant-ph/0507190) method to the hidden multiple shift problem for multidimensional case, particularly for constant dimension/rank.

---
### <u>An exact quantum algorithm for factoring univariate polynomials over finite fields</u>
Author: [Muhammd Imran](https://muh-imran.github.io).

In this project, we would like to construct a quantum version of [Berlekamp's algorithm](https://en.wikipedia.org/wiki/Berlekamp%27s_algorithm).

---
## Lecture notes & systematic literature reviews

---
### <u>Hidden subgroup problem in cryptography: a survey</u>
Author: Muhammad Imran

In this survey, we conduct a systematic literature review on the most recent and important development in classical and quantum algorithms for some instances of finite hidden subgroup problem and other closely related problems (hidden shift and its generalization) which have strong connections with cryptography: group-based cryptography, lattice-based cryptography, isogeny-based cryptography, and some secure cryptographic protocols. The main purpose of this survey is to give cryptographic motivations for further investigations on finite hidden subgroup problem.

---
### <u>Recommended Source for Isogeny-based Cryptography</u>
* <b>Isogeny-Based Cryptography School 2021</b> [[link]](https://isogenyschool2020.co.uk/).
* <b>Leuven Isogeny Days 2022</b> [[link]](https://www.esat.kuleuven.be/cosic/projects/isocrypt/workshops/)
* <b>Isogeny Club</b> [[link]](https://isogeny.club)
 
---
