---
layout: archive
title: "Publications and preprints"
permalink: /research/
author_profile: true
---

### <u>Zero sum subsequences and hidden subgroups</u>
(April - 2023) <br>Authors: [Muhammd Imran](https://muh-imran.github.io) & [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/). <br>The preprint version is available in [arXiv]()
  
In this project, we succeed to construct the first exact quantum hidden subgroup algorithm for a class of non-abelian groups, namely nilpotent groups of constant class and the prime factors of the group order are also constant. The main key of the algorithm is by series of reductions to groups of smaller nilpotency class (through its central series) using new zero sum subsequences algorithm in the group $\mathbb{Z}_p^n$ for prime number $p$.

---

### <u>A private set intersection protocol based on multi-party quantum computation for greatest common divisor</u>
(March - 2023) <br>Author: [Muhammad Imran](https://muh-imran.github.io). <br>The preprint version is available in [arXiv](https://arxiv.org/abs/2303.17196).

Private set intersection (PSI) is a cryptographic primitive that allows two or more parties to learn the intersection of their input sets and nothing else. In this paper, we present a private set intersection protocol based on a new secure multi-party quantum protocol for greatest common divisor (GCD). The protocol is mainly inspired by the recent quantum private set union protocol based on least common multiple by Li, Yang, and Liu. Performance analysis guarantees the correctness and it also shows that the proposed protocols are completely secure in semi-honest model. Moreover, the complexity is proven to be efficient in the size of the input sets.

---
### <u>Hidden stabilizers and the Isogeny to Endomorphism Ring Problem</u>
(February - 2023) <br>Author: [Muhammad Imran](https://muh-imran.github.io), [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/), [Péter Kutas](https://sites.google.com/view/peterkutas89/main-page?authuser=0), & [Antonin Leroux](https://tonioecto.github.io/antoninleroux/). <br> The paper is submitted to [Crypto 2023](https://crypto.iacr.org/2023/).

This paper studies relations between some fundamental computational problems in isogeny-based cryptography. Moreover, we construct a new approach on attacking the Isogeny to Endomorphism Ring Problem (IsERP) using a new quantum algorithm for Borel hidden subgroup problem. We propose a quantum polynomial-time attack with subexponential classical precomputation on IsERP for any isogeny degree.  A key implication of this is that one should not reuse the starting curve and the degree in [pSIDH](https://link.springer.com/chapter/10.1007/978-3-031-22966-4_1).



---
### <u>An exact quantum order finding algorithm and its applications</u>
(May - 2022) <br>Author: [Muhammad Imran](https://muh-imran.github.io). <br>The preprint version is available in [arXiv](https://arxiv.org/abs/2205.04240).

The main key of Shor's algorithm for factoring integers $m$ is a quantum algorithm for finding order of elements in the unit group $\mathbb{Z}_m^*$ of the group of integer modulo $m$. However, the quantum algorithm is polynomial-time in the expected sense, which means it may fail with a small probability and in the unlucky case may take a very long time to succeed. By the observation that knowing a multiple of the group order $\varphi(m)$ would factor $m$ in randomized classical polynomial time, finding orders of group elements with a known multiple of the order is not necessarily as hard as factoring, so a multiple of the order may be a good help for derandomizition of the quantum algorithm for order finding problem. Some computational problems where such a help available are primality testing problem and the problem of finding primitive elements in arbitrary finite field $\mathbb{F}_q$, and some cryptographic protocols.

---

### <u>An exact quantum hidden subgroup algorithm and applications to solvable groups</u>
(February - 2022) <br>Authors: [Muhammd Imran](https://muh-imran.github.io) & [Gábor Ivanyos](http://old.sztaki.hu/~ivanyos/). <br>The paper is available in [Quantum Information and Computation](https://doi.org/10.26421/QIC22.9-10-4) or the preprint version in [arXiv](https://arxiv.org/abs/2202.04047).

The natural characteristic of quantum algorithms is probabilistic, since it takes advantage from the quantum principles (superposition, interference, entanglement, etc.). The common technique to boost up the success probability of quantum algorithms is amplitude amplification which is a generalization of Grover's algorithm. Therefore, it is a natural question whether it is possible to boost up the probability to certainty while maintaining the efficiency. In the hidden subgroup problem, the existing of exact quantum algorithms is still limited. In this paper, we construct an exact quantum algorithm for the hidden subgroup problem in the infinite family of groups $\mathbb{Z}_{m^k}^n$. Even for $m=3$ and $k=1$, our algorithm appears to be new. Moreover, we provide the applications of the algorithm in some computational problems in solvable groups such as membership testing, the construction of normal series, etc.

---

# Research in progress

---

### <u>Stripped, multidimensional version of the Childs–van Dam approach to the hidden multiple shift problem</u>
Author: [Muhammd Imran](https://muh-imran.github.io).

The hidden multiple shift problem (HMS) can be seen as an interpolation between the abelian and dihedral hidden subgroup problems. HMS is defined as follows, We are given a subset $H\subseteq \mathbb{Z}_q$ of cardinality $r$. (Here $q$ is an integer greater than $1$, not necessarily a prime.) A function $f_s:\mathbb{Z}_q^n\times H\rightarrow \\{0,1\\}^l$ is given by an oracle, where $f_s(x,h)=f(x-hs)$ for some $s\in \mathbb{Z}_q^n$, and an injective function $f:\mathbb{Z}_q^n \rightarrow \\{0,1\\}^l$. The goal is to find $s$ modulo $\gcd\\{q,h-h':h,h'\in H\\}$. Two extream cases are when $H=\mathbb{Z}_q$ then it is an abelian hidden subgroup problem in $\mathbb{Z}_q^{n+1}$ which can be efficiently solved by quantum computers, while when $\|H\|=2$ then it is dihedral hidden subgroup problem in which the best known quantum algorithm ([Kuperberg's algorithm](https://arxiv.org/abs/quant-ph/0302112)) has subexponential complexity. The study of HMS recently appears as a promising approach to both lattice-based and  isogeny-based cryptography, see [BKSW18](https://link.springer.com/chapter/10.1007/978-3-319-76581-5_24) and [IIKL23]() respectively.

In this project, we would like to construct a stripped (free of "pretty good measurement") version of the [Childs-van Dam](https://arxiv.org/abs/quant-ph/0507190) method to the hidden multiple shift problem for multidimensional case, particularly for constant dimension/rank.

---
### <u>An exact quantum algorithm for factoring univariate polynomials over finite fields</u>
Author: [Muhammd Imran](https://muh-imran.github.io).

In this project, we would like to construct a quantum version of [Berlekamp's algorithm](https://en.wikipedia.org/wiki/Berlekamp%27s_algorithm).

---
## Lecture notes & systematic literature reviews

---
### <u>Hidden subgroup problem in cryptography: a survey</u>
Author: Muhammad Imran

In this survey, we conduct a systematic literature review on the most recent and important development in classical and quantum algorithms for some instances of finite hidden subgroup problem which have strong connections with cryptography: lattice-based cryptography, isogeny-based cryptography, and some secure cryptographic protocols. The main purpose of this survey is to give cryptographic motivations for further investigations on finite hidden subgroup problem.

---
### <u>Recommended Source for Isogeny-based Cryptography</u>
* <b>Isogeny-Based Cryptography School 2021</b> [[link]](https://isogenyschool2020.co.uk/).
* <b>Leuven Isogeny Days 2022</b> [[link]](https://www.esat.kuleuven.be/cosic/projects/isocrypt/workshops/)
* <b>Isogeny Club</b> [[link]](https://isogeny.club)
 
---
