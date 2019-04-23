
# ✨ Welcome To The Crypto Archives ✨

The Crypto Archives is a living resource stewarded by the analysts at [Multicoin Capital](https://multicoin.capital/), a thesis-driven cryptofund that invests in tokens reshaping entire sectors of the global economy.  

It aims to provide a comprehensive archive of technical concepts, case studies, and essays in crypto. It traverses consensus algorithms, state machines, zero-knowledge proofs, hashing algorithms, peer-to-peer communication protocols, cryptoeconomics, and much, much more. 

🚧 **Note: This Archive Is Under Construction** 🚧 Anyone is welcome to contribute to the archive by submitting a pull request. Contributions will be reviewed and incorporated as regularly as possible. Contributors will be credited below. 



# 📖 Table of Contents 
*  [Cryptographic Primitives](#%EF%B8%8F-cryptographic-primitives)
	* [Bitcoin’s Predecessors](#itcoins-predecessors)
	* [Hashing Algorithms](#hashing-algorithms)
	* [Zero-Knowledge Argument Systems](#zero-knowledge-argument-systems)
	* [Proofs of Space, Time & Replication](#proofs-of-space-time--replication)
	* [Other](#other)

* [Web3 Stack](#-web3-stack)
	*  [The Web3 Stack, By Kyle Samani](#the-web3-stack)
	* [Consensus Algorithms](#consensus-algorithms)
		* [Classical Consensus](#classical-consensus)
		* [Nakamoto Consensus](#nakamoto-consensus)
		* [Permissioned Consensus](#permissioned-consensus) 
		* [Leaderless Consensus](#leaderless-consensus) 
	* [State Machines](#state-machines)
	*  [Interpreters, Runtimes and Virtual Machines](#interpreters-runtimes-and-virtual-machines)
		* [Ethereum Virtual Machine (EVM)](#ethereum-virtual-machine-evm)
		* [WebAssembly (WASM)](#webassembly-wasm) 
		* [Other Virtual Machines](#other-virtual-machines)
	* [Layer 2 Scaling](#layer-2-scaling) 
	* [Sharding](#sharding)
	* [Trusted Execution Environments](#trusted-execution-environments)
	* [Peer-to-Peer Communications](#peer-to-peer-communications)

*  [Cryptoeconomics](#-cryptoeconomics) 
	* [Tokenomics](#tokenomics) 
	* [Governance](#governance) 

* [Vulnerabilities, Bugs and Hacks](#-vulnerabilities-bugs-and-hacks)
	* [Attack Vectors](#attack-vectors)
	* [Protocol Failures and Issues](#protocol-failures-and-issues)
	* [Successful Hacks and Post-Mortems](#successful-hacks-and-post-mortems) 
* [External Resources](#-external-resources)
* [Contributors](#contributors) 




- - - -


# ⚛️ Cryptographic Primitives
## ₿itcoin’s Predecessors
 [E-cash](http://blog.koehntopp.de/uploads/Chaum.BlindSigForPayment.1982.PDF)  by David Chaum ( [ipfs](https://gateway.ipfs.io/ipfs/QmWWSsMLziTS3d7ooctn3GBTzhybqbyAeXFd1nPW1cpou6) )
* Laid the groundwork for a private, digital payments system. [1982]


 [Hashcash](https://nakamotoinstitute.org/literature/hashcash/)  by Adam Back ( [ipfs](https://gateway.ipfs.io/ipfs/QmbBYug3fnewfQpbtRCghwG4eoeyX11sQA85TkKDgxE11v) )
* Proposed the first proof-of-work (PoW) function for anti-DoS. [1997]


 [B-Money](http://www.weidai.com/bmoney.txt)  by Wei Dai ( [ipfs](https://gateway.ipfs.io/ipfs/Qmb1tnsutGuVL9KE6QvtoZTc7dhGik4GWQZGcKuh85JNXX) )
* Proposed an anonymous, distributed electronic cash system using PoW. [1998]


 [Karma](https://www.cs.cornell.edu/people/egs/papers/karma.pdf)  by Vivek Vishnumurthy, Sangeeth Chandrakumar and Emin Gün Sirer ( [ipfs](https://gateway.ipfs.io/ipfs/QmWNZaXWTPJ26Z4gcVxF9jb7JywUi6Nd6JHrdp7DD8ZtWf) )
* First cryptocurrency to use a distributed mint based on PoW. [2003]


 [Bit Gold](https://nakamotoinstitute.org/bit-gold/)  by Nick Szabo ( [ipfs](https://gateway.ipfs.io/ipfs/QmW9ZZM9Ay51yYqCstMnxAKpM86N9YHkynY1t8vqq7Yvvg) )
* Describes a system for the decentralized creation of unforgeable proof of work chains [2005]


 [Bitcoin’s Academic Pedigree](https://queue.acm.org/detail.cfm?id=3136559)  by Arvind Narayanan and Jeremy Clark ( [ipfs](https://gateway.ipfs.io/ipfs/QmSjw5Z1MgV2c2h8YAGNAGmv5rChMek9xbQQfYEefSjyZ9) ) 
* Excellent overview of the academic research upon which Bitcoin was built. [2017]

## Hashing Algorithms
Here are the links to all major types of  [hashing algorithms](https://blockgeeks.com/guides/what-is-hashing/) :

 [SHA-256](http://www.iwar.org.uk/comsec/resources/cipher/sha256-384-512.pdf)  and  [Implementation](https://www.cs.princeton.edu/~appel/papers/verif-sha.pdf)  by Andrew Appel ( [ipfs](https://gateway.ipfs.io/ipfs/QmaFF34jiQUDNWN6HhnRFXun8k1tyEPmhb9FtGKu54tSTW)  and  [ipfs](https://gateway.ipfs.io/ipfs/QmVpbbdJucpT3XZXRdFQ2wRkKYAhPQuUCtXZpYUfEJPYaf) )
* A one-way hashing function using 32-bit words. [2001]


 [Scrypt](https://www.tarsnap.com/scrypt/scrypt.pdf)  by Colin Percival ( [ipfs](https://gateway.ipfs.io/ipfs/QmfLQS9P7mb55J9STUNWZdUm9imH8M4Ko3gv8n91jaMCqw) )
* Introduced memory-hard hashing functions. [2009]


 [Blake2](https://blake2.net/)  by Jean-Philippe Aumasson, Samuel Neves, Zooko Wilcox-O’Hearn, and Christian Winnerlein ( [ipfs](https://gateway.ipfs.io/ipfs/QmeFsvh2pHJzsCVmWJWhUFC6DTgSSA2APozcTQzNFXtt2H) )
* Provides security superior to SHA-2 and similar to that of SHA-3: immunity to length extension, indifferentiability from a random oracle, etc. [2012]


 [Keccak256](https://keccak.team/files/Keccak-implementation-3.2.pdf)  by Guido Bertoni, Joan Daemen, Michaël Peeters, Gilles Van Assche and Ronny Van Keer ( [ipfs](https://gateway.ipfs.io/ipfs/QmZsHn55Z5d9NW4byQs5nsRsPt4EaekJ8rBxeigkrTYQca) )
* Parent family of SHA-3 standards using the sponge construction, in which data is “absorbed” into the sponge, then the result is “squeezed” out. [2012]


 [CryptoNight](https://cryptonote.org/cns/cns008.txt)  by Nicolas van Saberhagen ( [ipfs](https://gateway.ipfs.io/ipfs/QmUs6jPUgWWNJZaEwAfuCk2fuNCP9MjCvryuUeFENBeADq) )
* Memory-hard hash function designed to be inefficiently computable on GPU, FPGA and ASIC architectures. [2013]


 [Dagger](http://www.hashcash.org/papers/dagger.html)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmXkHRtSAz2m6wMXdTRbrnYVvVw4KmUMnUpvDtGzEmQGmL) )
* A memory-hard to compute, memory-hard to verify alternative to Scrypt. [2013]


 [Hashimoto](http://diyhpl.us/~bryan/papers2/bitcoin/meh/hashimoto.pdf)  by Thaddeus Dryja ( [ipfs](https://gateway.ipfs.io/ipfs/QmePkiUzASPH1rhTZMZr17RnqrEySh9UMUpAbhwk5vm3fw) )
* Difficult to optimize via ASIC design due to being I/O bound, and difficult to outsource to nodes without the full data set. [2014]


 [Ethhash](https://github.com/ethereum/wiki/wiki/Ethash)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmRiXDUg7WKAFzRiAoNxwR4WAAvDpA63RCLoG16u9Po4Nb) )
* A combination of the Dagger and Hashimoto algorithms used in Ethereum 1.0. [2014]


 [X11](https://docs.dash.org/en/latest/introduction/features.html#x11-hash-algorithm)  by strophy, thephez, Dimitris Apostolou (ipfs)
* Uses multiple rounds of 11 different hashes (Blake, bmw, groestl, jh, keccak, skein, luffa, cubehash, shavite, simd, echo). [2015]


 [ProgPoW](https://github.com/ifdefelse/ProgPOW)  by IfDefElse ( [ipfs](https://gateway.ipfs.io/ipfs/QmdqWegDt4bAsHaoSs8EdCpSYq9H2cgrHipm7kbxe84eBt) )
* An Ethhash redesign minimizing the improvements available to ASICs by maximizing the usage of the featureset of a commodity GPU. [2018]


 [Pederson Hash Function](https://github.com/zcash/zcash/issues/2234#issuecomment-383736266)  by Daira Hopwood ( [ipfs](https://gateway.ipfs.io/ipfs/QmeedxSgPfDquov4KPBPYLMVX5JEKRY2FCHkZ86oN6Fo6Q) )
* Used in Zcash’s Sapling SNARK construction, reduces to discrete log. [2017]

## Zero-Knowledge Argument Systems
 [The Knowledge Complexity of Interactive Proof Systems](http://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Proof%20Systems/The_Knowledge_Complexity_Of_Interactive_Proof_Systems.pdf)  by Shafi Goldwasser, Silvio Micali, Charles Rackoff ( [ipfs](https://gateway.ipfs.io/ipfs/QmZhkjD6VfcoQmQcqzTnEYWwRRTWWNT5w7RdEnWZ9nwa41) )
* Introduced the IP hierarchy of interactive proof systems and gave the first zero-knowledge proof for a concrete problem. [1985]


 [Zerocash](http://zerocash-project.org/media/pdf/zerocash-extended-20140518.pdf)  by Eli Ben-Sasson, Alessandro Chiesa, Christina Garman, Matthew Green, Ian Miers, Eran Tromer, Madars Virza ( [ipfs](https://gateway.ipfs.io/ipfs/QmSQ6iAKnXXfJMAVsXQAUSenvZiuG5w6Dn9xGJ3wBAWytx) )
* The specification for a private digital currency based on zk-SNARKS. [2014]


 [Fair-Zero Knowledge](https://people.csail.mit.edu/silvio/Selected%20Scientific%20Papers/Zero%20Knowledge/Fair_Zero_Knowkedge.pdf)  by Matt Lepinski, Silvio Micali, abhi shelat ( [ipfs](https://gateway.ipfs.io/ipfs/QmVJt8xLYY6hHN93xKN5MYu34Km1cdDT8CBN74h51ZJYXf) )
* A multi-verifier ZK system where every proof is guaranteed to be “zero-knowledge for all verifiers.” [2015]


 [Succinct Non-Interactive Zero Knowledge for a von Neumann Architecture](https://eprint.iacr.org/2013/879.pdf)  by Eli Ben-Sasson, Alessandro Chiesa, Eran Tromer, Madars Virza ( [ipfs](https://gateway.ipfs.io/ipfs/QmPurvYEq1HX4CJvTT9FJ7jnZ1r8PL6pD5we8BdosQsRey) )
* zk-SNARK: a non-interactive zk-proof with a trusted setup, constant sized proofs and near constant verification time. [2015]


 [Zcash Protocol Specification](https://github.com/zcash/zips/blob/master/protocol/protocol.pdf)  by Daira Hopwood, Sean Bowe, Taylor Hornby, Nathan Wilcox ( [ipfs](https://gateway.ipfs.io/ipfs/QmVb21dtiJoyy2n1jmZSThyCZyKEN8oK1yodmPSPrrnE8T) )
* Implementation of the Zerocash specification. [2016]


 [Doubly Efficient zk-SNARKs without Trusted Setup](https://eprint.iacr.org/2017/1132.pdf)  by Riad S. Wahby, Ionna Tzialla, abhi shelat, Justin Thaler, Michael Walfish ( [ipfs](https://gateway.ipfs.io/ipfs/QmXUWY7sW3z3JucuevpvxvMxaY9CXXYKg9iRbHHcaFTyRk) )
* Hyrax: a non-interactive zk-proof without a trusted setup where proof size is small, and proof generation time grows sublinearly, as does verification time. [2017]


 [Lightweight Sublinear Arguments Without a Trusted Setup](https://acmccs.github.io/papers/p2087-amesA.pdf)  by Scott Ames, Carmit Hazay, Yuval Ishai, Muthuramakrishnan Venkitasubramaniam ( [ipfs](http://qmsnkpdkccp8wwsrrvasf1f6gl5lujlr5w6bj3sev4cgbw/) )
* Ligero: a non-interactive zk-proof without a trusted setup. [2017]


 [Post-Quantum Zero-Knowledge and Signatures from Symmetric-Key Primitives](https://eprint.iacr.org/2017/279.pdf)  by Melissa Chase, David Derler, Steven Goldfeder, Claudio Orlandi, Sebastian Ramacher, Christian Rechberger, Daniel Slamanig, Greg Zaverucha (ipfs)
* ZKB++ design. [2017]


 [Bulletproofs](https://eprint.iacr.org/2017/1066.pdf)  by Benedikt Bu ̈nz, Jonathan Bootle, Dan Boneh, Andrew Poelstra, Pieter Wuille, and Greg Maxwell ( [ipfs](https://gateway.ipfs.io/ipfs/QmcPHJztetvMkCEzakCx4Ssd2jSbx6uBtoYVPyKynA42aQ) )
* Bulletproof: a non-interactive zk-proof without a trusted setup where proof size grows logarithmically, proof generation time grows linearly, as does verification time. [2017]


 [Scalable, Transparent, and Post-Quantum Secure Computational Integrity](https://eprint.iacr.org/2018/046.pdf)  by Eli Ben-Sasson, Iddo Bentov, Yinon Horesh, Michael Riabzev ( [ipfs](https://gateway.ipfs.io/ipfs/QmVjnxu2uxVW1iC4LD59vo82QR8XT9HHPxTNKLaiVJo3KY) )
* zk-STARK: a non-interactive zk-proof without a trusted setup where proof size is large, but proof generation time grows sublinearly, as does verification time. [2018]


Explaining zk-STARKS  [Part I](https://vitalik.ca/general/2017/11/09/starks_part_1.html) ,  [Part II](https://vitalik.ca/general/2017/11/22/starks_part_2.html) , and  [Part III](https://vitalik.ca/general/2018/07/21/starks_part_3.html)  by Vitalik Buterin ( [ipfs1](https://gateway.ipfs.io/ipfs/QmZ4Afbcsn3mAzvsHbTn2nvueDnX4PFJUmyP9HH6y3dxPn) ,  [ipfs2](https://gateway.ipfs.io/ipfs/Qmd1fpGoQS5AZy9LG369sSiC7HanDGWRmQYMdvGt42zNbs) ,  [ipfs3](http://qmx7bkbgattl87uvtkug5zqsdvc8rzid8hojag7mzttdot/) )
* Three part explanation for how zk-STARKs work. [2018]


 [Aurora: Transparent Succinct Arguments for R1CS](https://eprint.iacr.org/2018/828.pdf)  By Eli Ben-Sasson, Alessandro Chiesa, Michael Riabzev, Nicholas Spooner, Madars Virza, Nicholas P. Ward ( [ipfs](https://gateway.ipfs.io/ipfs/QmYTBpVu156KNRWWb1ppMF8yJxMwNvRBVFJoqCDfvqSLKX) )
* zk-STARK improvement where proof size is O(log2n), proof generation time is O(n log(n)), and verification time is O(n).


 [Zexe: Enabling Decentralized Private Computation](https://eprint.iacr.org/2018/962.pdf)  by Sean Bowe, Alessandro Chiesa, Matthew Green, Ian Miers, Pratyush Mishra, Howard Wu ( [ipfs](https://gateway.ipfs.io/ipfs/QmY4ss4XLbpa4Yfe7ffRoh4DV3n3JCVTPsRqSEhTT96DtL) )
* A ledger-based system where users execute offline computations, and produce transactions that hide all information about the offline computations and can be validated by anyone in constant time. [2018]

## Proofs of Space, Time & Replication
 [Proofs of Space](https://eprint.iacr.org/2017/893.pdf)  by Hamza Abusalah, Joel Alwen, Bram Cohen, Danylo Khilko, Krzysztof Pietrzak, Leonid Reyzin ( [ipfs](https://gateway.ipfs.io/ipfs/QmNxX8QutzqTgNhvaZ8pHFaeJVUbXKwMMAY2R5Ur9vBpdG) )
* Describes an alternative to Proof of Work where a service requester must dedicate a significant amount of disk space as opposed to computation. [2013]


 [Proofs of Unique Blockchain Storage](https://bitslog.wordpress.com/2014/11/03/proof-of-local-blockchain-storage/)  by Sergio Demian Lerner ( [ipfs](https://gateway.ipfs.io/ipfs/QmZ6bYQZ12t1UCmcyr9NwxYy1U3vyJhzJcDHpbhaiFNYH4) )
* Describes a construction that lets a node verify that a remote node has a unique copy of a data file over the Internet. [2014]


 [Proofs of Space and Time](https://cyber.stanford.edu/sites/default/files/bramcohen.pdf)  by Bram Cohen ( [ipfs](https://gateway.ipfs.io/ipfs/QmXeWHqKNkp7T5JL1U8gcKbcgAiha7jaAy3gubWZSxc5te) )
* Describes an improvement to the safety of Proofs of Space by alternating with a Proof of Time to prevent re-mining attacks. [2017]


 [Proof of Replication](https://filecoin.io/proof-of-replication.pdf)  by Juan Benet, David Dalrymple, Nicola Greco ( [ipfs](https://gateway.ipfs.io/ipfs/QmXfn1Q49hYEt6fbY1xwhqSWz4WedXHbqRnTFjkZAD6EMD) )
* Describes an improvement to Proofs of Storage that enables a verifier to check that a prover is not deduplicating multiple copies of data in the same storage space. [2017]


 [Verifiable Delay Functions](https://eprint.iacr.org/2018/601.pdf)  by Dan Boneh, Joseph Bonneau, Benedikt Bunz, Ben Fisch ( [ipfs](https://gateway.ipfs.io/ipfs/QmSzqbRB4yvTsjBYoaFu82gRAP6NLwL979YmX4MXN4deij) )
* Describes the requirements for functions that require a specified number of sequential steps to evaluate, yet produces a unique output that can be efficiently and publicly verified. [2018]


 [A Survey of Two Verifiable Delay Functions](https://eprint.iacr.org/2018/712.pdf)  by Dan Boneh, Benedikt Bunz, Ben Fisch ( [ipfs](https://gateway.ipfs.io/ipfs/QmXSzAjeYEuygVSA36T2wtw3CP2mWGei7q3hppPW2A2tJK) )
* A comparison of VDF constructions from Pietrzak and Wesolowski. [2018]


 [Minimal VDF Randomness Beacon](https://ethresear.ch/t/minimal-vdf-randomness-beacon/3566)  by Justin Drake ( [ipfs](https://gateway.ipfs.io/ipfs/QmXfjyxboD58cN3C6y1hMG2FYtL3kk92XSvEAYtSFnGG5d) )
* A proposal to use a VDF on Ethereum 2.0 as a source of randomness. [2018]

## Other
Merkle Tree:  [Patent](http://pdfpiw.uspto.gov/.piw?Docid=04309569&PageNum=0)  and  [Paper](https://link.springer.com/content/pdf/10.1007%2F3-540-48184-2_32.pdf)  and  [in Ethereum](https://blog.ethereum.org/2015/11/15/merkling-in-ethereum/)  by Ralph C. Merkle and Vitalik Buterin, respectively ( [ipfs1](https://gateway.ipfs.io/ipfs/QmSxtmZKzpombtWiW3irtj9SoHWBfWpbg4WmGUjQxAX8xN) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmVrpyKJcj1SL7Dxe1mprjx4KuVsPGhR6paFTvW5KbXHx8) ,  [ipfs3](https://gateway.ipfs.io/ipfs/Qmbztf7iYjAU8Bw1HQUw18g3wT3uCFotsGU7AnsYh1cC9d) )
* A fundamental data structure that allows for authenticating a small amount of data, like a hash, to be extended to also authenticate large databases of potentially unbounded size. (1982, 1988, 2015)


 [Why I Wrote PGP](https://www.philzimmermann.com/EN/essays/WhyIWrotePGP.html)  by Phil Zimmerman ( [ipfs](https://gateway.ipfs.io/ipfs/QmdjrnxU6vmG3jgqVmbi2BuUyKnLvVXro3qHKwnk79ipbd) )
* A short history of cryptography enabling digital privacy in the 1990s. [1991]


 [How to Time-Stamp a Digital Document](https://pdfs.semanticscholar.org/06b0/55b0b53d39aa969afc2ba2c1d87985587db7.pdf)  by Stuart Haber, W. Scott Stornetta ( [ipfs](https://gateway.ipfs.io/ipfs/QmPqk4USnH4MHFKxzdZsW46WRPBsDK11VmB37TaNe67WdJ) )
* Proposed computationally practical procedures for digital time-stamping such that it would be infeasible for a user either to back-date or to forward-date a document, even with the collusion of a time-stamping service. [1991]


 [Secure Names for Bit-Strings](https://nakamotoinstitute.org/literature/secure-names-bit-strings/)  by Stuart Haber, W. Scott Stornetta ( [ipfs](https://gateway.ipfs.io/ipfs/QmZYxa2AdnmEiGx9w5LWBc6EUVXge8qHfJRikQE9gBghzB) )
* Introduced procedures to create unique content-addressable names for digital data. [1997]


 [Design of a Secure Timestamping Service with Minimal Trust Requirements](https://nakamotoinstitute.org/literature/secure-timestamping-service/)  by H. Massias, X. Serret Avila, J.J. Quisquater ( [ipfs](https://gateway.ipfs.io/ipfs/QmSCmLM6HpLSvXNWd7qX7XKFdBnTLLBBzQ5yaS8dxqY9cE) )
* Defined the digital certificate intended to assure the existence of a generic digital document at a certain time. [1999]


 [The Elliptic Curve Digital Signature Algorithm](https://web.archive.org/web/20170921160141/http://cs.ucsb.edu/~koc/ccs130h/notes/ecdsa-cert.pdf)  by Don Johnson, Alfred Menezes, Scott Vanstone ( [ipfs](https://gateway.ipfs.io/ipfs/QmbfZRribzeAZGB2tZxphaY21k2Fn9GhS86fnYgGy8bt51) )
* The algorithm used to create digital certificates (e.g. public/private key pairs) for a large variety of blockchains. [2001]


 [Short Signatures from the Weil Pairing](https://www.iacr.org/archive/asiacrypt2001/22480516.pdf)  by Dan Boneh, Ben Lynn, Hovav Shacham ( [ipfs](https://gateway.ipfs.io/ipfs/QmYcCJAefa5JgKqzGeavGZnxyTXZ8wP9H85wca9QJKWvev) )
* A signature scheme with half the signature length of a DSA signature. [2001]


 [Aggregate and Verifiably Encrypted Signatures from Bilinear Maps](https://crypto.stanford.edu/~dabo/papers/aggreg.pdf)  by Dan Boneh, Craig Gentry, Ben Lynn, Hovav Shacham ( [ipfs](https://gateway.ipfs.io/ipfs/QmNj9kDiG6TpPQ8g5T33s2WoxXENsbfjT61XLRFSb2dfJY) )
* Efficient aggregate signatures based on the BLS signature schema. [2003]


 [Boneh-Boyen Signature Scheme](https://crypto.stanford.edu/~dabo/pubs/papers/bbsigs.pdf)  by Dan Boneh, Xavier Boyen ( [ipfs](https://gateway.ipfs.io/ipfs/QmdocYALHknPQ6BfHp16PGoEtUsgqucugUDeuiJiVQ2xEc) )
* Produces DSA-length signatures secure without random oracles or hash functions. [2014]


 [Compact Multi-Signatures for Smaller Blockchains](https://eprint.iacr.org/2018/483.pdf)  by Dan Boneh, Manu Drijvers, Gregory Neven ( [ipfs](http://gateway.ipfs.io/ipfs/QmNskpWYxcB4vPp5gRRs4q8P7NRkyeQvzuQXcyXGoTdYp6) )
* The first short accountable-subgroup multi-signature (ASM) scheme. [2018]


 [Schnorr Signatures in Bitcoin](https://eprint.iacr.org/2018/068.pdf)  by Gregory Maxwell, Andrew Poelstra, Yannick Seurin, Pieter Wuille ( [ipfs](https://gateway.ipfs.io/ipfs/QmdBGF8n6fAtd42WmJMTNDofPT4jEb5oAiFZmcTwRUh3ca) )
* An alternative to ECDSA that would allow for signature aggregation in Bitcoin. [2018]


 [Parity Substrate](https://medium.com/paritytech/substrate-in-a-nutshell-a54cd34c7863)  by Dmitriy Kashitsyn ( [ipfs](https://gateway.ipfs.io/ipfs/QmUJb6GcW8damCJ8T1fZzrJsjHvhsHy8nt8mnoViAWTT24) )
* Describing a library designed to help users build their own blockchain. [2018]


# 🌐 Web3 Stack 
## The Web3 Stack
[The Web3 Stack](https://multicoin.capital/2018/07/10/the-web3-stack/) by Kyle Samani, Multicoin Capital 
* This is the most comprehensive illustration of the Web3 stack that we have yet to find. Given how expansive the Web3 ecosystem is, this diagram is almost certainly incomplete. 

## Consensus Algorithms
Here are the links to all major types of  [consensus algorithms](https://medium.com/polkadot-network/consensus-and-finality-in-blockchains-21b1f634fd00) :

### Classical Consensus

 [The Byzantine Generals Problem](https://people.eecs.berkeley.edu/~luca/cs174/byzantine.pdf)  by Leslie Lamport, Robert Shostak, Marshall Pease ( [ipfs](https://gateway.ipfs.io/ipfs/QmR4m2MkjgrE2RxTxjYVQxRFdkPDVRNnjfuC2pvMN1qnmD) )
* Describes consensus amongst distributed, distrusting parties. [1982]


 [The Part-Time Parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf)  by Leslie Lamport ( [ipfs](https://gateway.ipfs.io/ipfs/QmTU359jicurmip7uvjQstu6G7orULJvBp2z5nuRUT1vKC) )
* Describes the Paxos protocol as a solution to the Byzantine Generals Problem. [1989]


 [Practical Byzantine Fault Tolerance (PBFT)](http://pmg.csail.mit.edu/papers/osdi99.pdf)  by Miguel Castro, Barbara Liskov ( [ipfs](https://gateway.ipfs.io/ipfs/QmcuvCi8J2xUCpzyyaH8Mix5UGMYBSTMp7tzCSYJZ1gdaT) )
* Describes a high-performance Byzantine state machine replication algorithm. [1999] 


 [RAFT](https://raft.github.io/raft.pdf)  by Diego Ongaro, John Ousterhout ( [ipfs](https://gateway.ipfs.io/ipfs/QmbxQJkxyJGbLnDqpHUJRYzgVY6g1yXp3RgpaLzBpHwdAL) )
* Describes a logically-separated alternative to the Paxos protocol. [2014]


 [Tendermint](https://arxiv.org/pdf/1807.04938.pdf)  by Ethan Buchman, Jae Kwon, Zarko Milosevic ( [ipfs](https://gateway.ipfs.io/ipfs/QmaMtD7xDgghqgjN62zWZ5TBGFiEjGQtuZBjJ9sMh816KJ) )
* Describes a PBFT algorithm that relies on a peer-to-peer gossip protocol. [2014]


 [Delegated Proof of Stake](https://steemit.com/dpos/@dantheman/dpos-consensus-algorithm-this-missing-white-paper)  by Dan Larimer ( [ipfs](https://gateway.ipfs.io/ipfs/QmcWK4dSJtMpMEnVXxr2wHaX4ZRz1VxTTRNKELNKX674PF) )
* Describes a classical consensus algorithm where leaders are elected by voting. [2016]


 [Casper Friendly Finality Gadget](https://arxiv.org/pdf/1710.09437.pdf)  by Vitalik Buterin and Virgil Griffith ( [ipfs](https://gateway.ipfs.io/ipfs/QmRPRczrEmpZB7h4QfveyRSKmKECDCdmKhcuGYMJj8VdzQ) )
* Describes an overlay algorithm to provide finality to any blockchain. [2017]


 [Delegated Proof of Stake BFT](https://github.com/EOSIO/eos/issues/2718)  by Dan Larimer ( [ipfs](https://gateway.ipfs.io/ipfs/QmNzJ231wNHzfB3GjdnHUyt6RXB27TBib8q2K1eeMwGYW6) )
* Describes a BFT extension to the previously described DPoS algorithm. [2018]


 [Byzantine Agreement](https://eprint.iacr.org/2018/377.pdf)  by Jing Chen, Sergey Gorbunov, Silvio Micali, Georgios Vlachos ( [ipfs](https://gateway.ipfs.io/ipfs/QmV4tLbN9DzLPtmAHYwc47tFJWsdHNthzfVsJetMvVcM3Q) )
* Describes a PBFT algorithm that elects leaders with a Verifiable Random Function. [2018]

### Nakamoto Consensus

 [Bitcoin](https://bitcoin.org/bitcoin.pdf)  by Satoshi Nakamoto ( [ipfs](https://gateway.ipfs.io/ipfs/QmRA3NWM82ZGynMbYzAgYTSXCVM14Wx1RZ8fKP42G6gjgj) )
* Describes a new consensus algorithm using a fork-choice rule. [2008]


 [Bitcoin-NG](https://www.usenix.org/system/files/conference/nsdi16/nsdi16-paper-eyal.pdf)  by Ittay Eyal, Adem Efe Gencer, Emin Gün Sirer, Robbert van Renesse ( [ipfs](https://gateway.ipfs.io/ipfs/QmNwwPWSiB65ATny51GaC6KN2MywS92WSNs9g7fkN5Ve9z) )
* Extends the algorithm by allowing leaders to produce microblocks. [2016]


 [Mimblewimble](https://download.wpsoftware.net/bitcoin/wizardry/mimblewimble.pdf)  by Andrew Poelstra ( [ipfs](https://gateway.ipfs.io/ipfs/Qmd99xmraYip9cVv8gRMy6Y97Bkij8qUYArGDME7CzFasg) )
* Describes an extension to the Bitcoin whitepaper using Confidential Transactions and cut-through of transactions. [2016]


 [Ouroboros](https://eprint.iacr.org/2016/889.pdf)  by Aggelos Kiayias, Alexander Russell, Bernardo David, Roman Oliynykov ( [ipfs](https://gateway.ipfs.io/ipfs/QmR9WprNQ2uwxdUu4uThMXjuvGoo2f4toK99m7jG3rHjmn) )
* Describes a Proof of Stake algorithm that uses a VRF and a fork choice rule. [2017]


 [Ouroboros Praos](https://eprint.iacr.org/2017/573.pdf)  by Bernardo David, Peter Gaži, Aggelos Kiayias, and Alexander Russell ( [ipfs](https://gateway.ipfs.io/ipfs/Qmb5xYqmq9FWtaKK7Q6eFhpGgRAcvJrnNfGXa599Z1gcyz) )
* Extends the algorithm to be secure vs. an adaptive adversary in semi-synchrony. [2017]


 [Ouroboros Genesis](https://eprint.iacr.org/2018/378.pdf)  by Christian Badertscher, Peter Gaži, Aggelos Kiayias, Alexander Russell, Vassilis Zikas ( [ipfs](https://gateway.ipfs.io/ipfs/QmaSHECCY5e6NfrerTpnpUNpni9hVDxpoDvmMiNtPYyabo) )
* Extends the algorithm to be secure for nodes with dynamic availability. [2018]


 [Chainweb](http://kadena.io/docs/chainweb-v15.pdf)  by Will Martino, Monica Quaintance, Stuart Popejoy ( [ipfs](https://gateway.ipfs.io/ipfs/Qmdr1DHQF4MeJE63Q5SQWkVdvyzBQ1zoGk45ds6iHEbLVA) )
* Describes a parallel-chain architecture for massive throughput. [2018]


 [Threshold Relay](https://dfinity.org/pdf-viewer/pdfs/viewer?file=../library/dfinity-consensus.pdf)  by Timo Hanke, Mahnush Movahedi, Dominic Williams ( [ipfs](https://gateway.ipfs.io/ipfs/QmaZScNPPsD47Bw4BnZ1SQFzV41JGw18BHnJCgMku9wB3s) )
* Describes a Proof of Stake algorithm that uses a VRF and a fork choice rule. [2018]

### Permissioned Consensus

 [Ripple](https://ripple.com/files/ripple_consensus_whitepaper.pdf)  by David Schwartz, Noah Youngs, Arthur Britto ( [ipfs](https://gateway.ipfs.io/ipfs/Qme4Y58ACM79gYukuNmLja8Yp4HMc2JuH7UpoaX3nh6ddz) )
* Describes a consensus protocol dependent on a trusted Unique Node List. [2014]


 [HoneyBadgerBFT](https://eprint.iacr.org/2016/199)  by Andrew Miller, Yu Xia, Kyle Croman, Elaine Shi, Dawn Song ( [ipfs](https://gateway.ipfs.io/ipfs/QmfEmofMA96V8ziqHc1sYLXEXpL9xaE84h9ij9mkariUjp) )
* Describes a leaderless, asynchronous algorithm dependent on a trusted setup. [2016]


 [Federated Byzantine Agreement](https://www.stellar.org/papers/stellar-consensus-protocol.pdf)  by David Mazières ( [ipfs](https://gateway.ipfs.io/ipfs/QmUV4ivAUfq1ZkkJbV8WAdCX7ZurQ9CyEknrWfAbEt5AMR) )
* Describes a protocol that achieves local consensus in trusted quorums before achieving consensus in a global, untrusted network . [2016]


 [Cobalt](https://arxiv.org/pdf/1802.07240.pdf)  by Ethan MacBrough ( [ipfs](https://gateway.ipfs.io/ipfs/QmcHEZfH4ArHFLuLcTiVsgB5mXVHFyxczghnwJZYTcYaET) )
* Extends Ripple to separate network governance from transaction approval. [2018]

### Leaderless Consensus

 [Hashgraph](https://swirlds.com/downloads/SWIRLDS-TR-2016-01.pdf)  by Leeman Baird ( [ipfs](https://gateway.ipfs.io/ipfs/QmcVN4MhMPfYfNC9JuHaPwcKNWfH5sSxh1spLWkcdNNEiU) )
* Describes a consensus protocol that reduces a blockDAG to a sequential blockchain via virtual voting and gossip about gossip. [2016]


 [Spectre: Serialization of Proof-of-work Events](https://eprint.iacr.org/2016/1159.pdf)  by Yonatan Sompolinsky, Yoad Lewenberg, Aviv Zohar ( [ipfs](https://gateway.ipfs.io/ipfs/QmaHdrny3GPP2YjXGMzm4FXC2FK3tchxPN8EXmiYXnkdeb) )
* Describes a consensus protocol that produces a blockDAG with pairwise ordering. [2016]


 [Phantom](https://eprint.iacr.org/2018/104.pdf)  by Yonatan Sompolinsky, Aviv Zohar ( [ipfs](https://gateway.ipfs.io/ipfs/QmcB1ZvY3zR2RNFCoqtjo4CUqCihgi3n8iSLrnqdpzXBwn) )
* Describes a consensus protocol that produces a blockDAG with linear ordering. [2018]


 [Spacemesh](https://spacemesh.io/assets/built/whitepaper1.2.pdf)  by Tal Moran, Iddo Bentov, Julian Loss ( [ipfs](https://gateway.ipfs.io/ipfs/QmVnUcyw5mMcU9NHs91PiAUgSvSdvC7N4uMVpRyprzQK58) )
* Describes a consensus protocol that combines a blockDAG with PoST. [2018]


 [Avalanche](https://ipfs.io/ipfs/QmUy4jh5mGNZvLkjies1RWM4YuvJh5o2FYopNPVYwrRVGV)  by Team Rocket ( [ipfs](https://gateway.ipfs.io/ipfs/QmUy4jh5mGNZvLkjies1RWM4YuvJh5o2FYopNPVYwrRVGV) )
* Describes a consensus protocol that uses metastability to agree on valid transactions, but does not provide sequential ordering. [2018]


 [CBC Casper](https://github.com/cbc-casper/cbc-casper-paper/blob/master/cbc-casper-paper-draft.pdf)  by Vlad Zamfir, Nate Rush, Aditya Asgaonkar, Georgia Piliouras ( [ipfs](https://gateway.ipfs.io/ipfs/QmVyjCpoW3gTxhJmRUMuwgn7ZVBecHFawdgYVZas3XwCki) )
* Describes a family of consensus protocols that are asynchronously safe and BFT. [2018]

## State Machines
Here are the links to all major types of  [state machines](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/unit-1-software-engineering/state-machines/MIT6_01SCS11_chap04.pdf) :

 [Blockchain as a State Machine](https://www.researchgate.net/profile/Jamsheed_Shorish/publication/322655559_Blockchain_State_Machine_Representation/links/5a66f262a6fdccb61c5b578b/Blockchain-State-Machine-Representation.pdf?origin=publication_detail)  by Jamsheed Shorish ( [ipfs](http://gateway.ipfs.io/ipfs/QmbULkziYYZxc4yy7kUPrUr8i7F2YD6vJPgQgYLujnCbQo) )
* Defines a blockchain as a hierarchy of state machines. [2017]


 [Ethereum as a State Machine](https://arxiv.org/pdf/1711.09327.pdf)  by Anastasia Mavridou, Aron Laszka ( [ipfs](https://gateway.ipfs.io/ipfs/QmSC1Srr3aa5eFxQfrPPxCW5FNMDzR2ypN6LXV7TmvqLDG) )
* Introduces a Finite State Machine Based Approach to writing smart contracts. [2017]

## Interpreters, Runtimes and Virtual Machines
 [Bitcoin Script](https://en.bitcoin.it/wiki/Script)  ( [ipfs](https://gateway.ipfs.io/ipfs/QmUiHTapHiJASXCPW3jw8raBmpBZpLAdjL2dBEtwpNzAQN) )
* Describes Bitcoin’s scripting system for transactions, including all active and disabled opcodes. [2017]

### Ethereum Virtual Machine (EVM)

 [Ethereum Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf)  by Dr. Gavin Wood ( [ipfs](https://gateway.ipfs.io/ipfs/QmS2z1f3jsnGvGiEgtKwj4fKTY3P3YCUh6AAtn6syGJp7D) )
* Describes the Ethereum Virtual Machine. [2014, updated 2018]


 [EVM Illustration](https://i.stack.imgur.com/afWDt.jpg)  by atomh33ls ( [ipfs](https://gateway.ipfs.io/ipfs/QmWQNcyceqb6CjFM6bJWjEKivNtRjBs9pepSM4bHVL8seT) )
* A helpful illustration of the Ethereum Virtual Machine. [2016]


 [KEVM](https://www.ideals.illinois.edu/bitstream/handle/2142/97207/hildenbrandt-saxena-zhu-rodrigues-guth-daian-rosu-2017-tr_0818.pdf?sequence=3&isAllowed=y)  by Everett Hildenbrandt, Manasvi Saxena, Xiaoran Zhu, Nishant Rodrigues, Philip Daian, Dwight Guth, Grigore Roșu ( [ipfs](https://gateway.ipfs.io/ipfs/QmdhL4RRForR4Rp8b9vXv5jp9za15cLVpQhkmHHZ4g5ueh) )
* A fully executable formal semantics of the EVM. [2017]

### WebAssembly (WASM)
 [WebAssembly](https://webassembly.github.io/spec/core/_download/WebAssembly.pdf)  by Web Assembly Community Group ( [ipfs](https://gateway.ipfs.io/ipfs/QmYtGq1kQXH2BML3txunDsyJX79ZTz76tPGY28yr5NChLi) )
* Specification for a safe, portable, low-level code format designed for efficient execution and compact representation. [2018]


 [WebAssembly Virtual Machine](https://github.com/AndrewScheidecker/WAVM)  by Andrew Scheideker ( [ipfs](https://gateway.ipfs.io/ipfs/QmNPHX8idEnKkg2L8pZMFG8wYqQwuAVbhxfGxqPMr5qCEr) )
* A standalone VM for WebAssembly, including the Intermediate Representation, Parser, and Runtime. [2018]


 [eWASM](https://github.com/ewasm/design)  ( [ipfs](https://gateway.ipfs.io/ipfs/QmPBVuYsbopiyQPUJ8C7a44qrjoPwcaBHhWVzKX1DCY1B7) ) 
* A restricted subset of WebAssembly for use in Ethereum. [2018]

### Other Virtual Machines
 [Kadena Pact](http://kadena.io/docs/Kadena-PactWhitepaper.pdf)  by Stuart Popejoy (ipfs)
* A human-readable, declarative, immutable and Turing-incomplete language for blockchains. [2017]


 [NEO VM](http://docs.neo.org/en-us/sc/introduction.html)  ( [ipfs](https://gateway.ipfs.io/ipfs/QmXMXKaASaQtqkoKR35iymmSoYXJ477Y1LbiJp6qYiiYwL) )
* A description of NEO’s smart contract compiler, execution engine, and interop service. [2017]


 [IELE](http://fsl.cs.illinois.edu/FSL/papers/2018/kasampalis-guth-moore-serbanuta-serbanuta-filaretti-rosu-johnson-2018-tr/kasampalis-guth-moore-serbanuta-serbanuta-filaretti-rosu-johnson-2018-tr-public.pdf)  and  [Explanation](https://iohk.io/blog/iele-a-new-virtual-machine-for-the-blockchain)  by Theodoros Kasampalis, Dwight Guth, Brandon Moore, Traian Serbanuta, Virgil Serbanuta, Daniele Filaretti, Grigore Roșu, Ralph Johnson ( [ipfs1](https://gateway.ipfs.io/ipfs/QmS6A5365qpWrazZwHFEghoyx2BpFcNv8wF6vqyxi93JHF) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmaTdbcp4jJ7shZG6eCR2dqeNgjTvnpPozRLy1FKNGm9dU) )
* An LLVM-like language for blockchains that was specified formally, and its implementation, a virtual machine generated from the specification. [2018]


 [Rholang VM](https://github.com/rchain/architecture-docs/blob/master/execution_model/rhovm.rst)  and  [Illustration](http://arch-doc.rchain.coop/en/latest/_images/architecture-overview.png)  by JosDenmark and C.R. Kirkwood-Watts ( [ipfs1](https://gateway.ipfs.io/ipfs/QmNfqR6dgfMixohaYdbcxh8Q37yN16q8BZgmCw65AchAti) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmcdAm5MXECtyDRfnM3daumBUdvHKfCq1vKJCFTNtx2Wrc) )
* A virtual machine based on repeatedly applying the rho calculus reduction rule to a key-value store. [2018]


 [Michelson: the Language of Smart Contracts in Tezos](https://tezos.gitlab.io/master/whitedoc/michelson.html)  ( [ipfs](https://gateway.ipfs.io/ipfs/QmNpvj4FwMgTU8UeoXKVDmthSDSBB5kA2J5zFY93c3YFcK) )
* The complete instruction set, type system and semantics of a stack-based language for blockchains with high level data types and primitives and strict static type checking. [2018]

## Layer 2 Scaling
 [Segregated Witness Proposal](https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki)  by Eric Lombrozo, Johnson Lau, Pieter Wuille ( [ipfs](https://gateway.ipfs.io/ipfs/QmZmGXDymFh4ASJF7WPdJu3mC1gm1AMJ8awAT5tZeakaML) )
* Fixed the problem of transaction malleability in Bitcoin, which enabled the building of trustless, unconfirmed transaction dependency chains, and payment channels. [2015]


 [State Channel Definition](https://www.jeffcoleman.ca/state-channels/)  by Jeff Coleman ( [ipfs](https://gateway.ipfs.io/ipfs/QmVWfjhZQUHFfR6BWcUF6PBoJHarwGQjhSUh7SrjhTw91S) )
* Defined interactions that could occur on the blockchain, but are instead conducted off-chain in a safe manner. [2015]


 [TrueBit: A Scalable Verification Solution for Blockchains](https://people.cs.uchicago.edu/~teutsch/papers/truebit.pdf)  by Jason Teutsch, Christian Reitwießner ( [ipfs](https://gateway.ipfs.io/ipfs/QmTrxXp2xhB2zWGxhNoLgsztevqKLwpy5HwKjLjzFa7rnD) )
* Incentivized verification games that allow for trustless off-chain smart contract execution. [2017]


 [Arbitrum: Scalable, Private Smart Contracts](https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-kalodner.pdf)  by Harry Kalodner, Steven Goldfeder, Xiaoqi Chen, S. Matthew Weinberg, Edward W. Felten ( [ipfs](https://gateway.ipfs.io/ipfs/QmZjdvnoNdUKJrnmZDo2CmaWXT8pLV1CvwfkbY7UMRefs3) )
* An off-chain smart contract execution protocol that only requires one honest miner per contract for trustlessness. [2018]


 [Lightning Network](https://lightning.network/lightning-network-paper.pdf)  by Joseph Poon, Thaddeus Dryja ( [ipfs](https://gateway.ipfs.io/ipfs/Qme5hKUMfBECzZvqfGxvpDgoeZsiKpk9WLXZjAk74ypuwN) )
* Describes a network of payment channels for Turing-incomplete blockchains that would allow members to send instantaneous, trustless, multi-hop payments. [2016]


 [Raiden Network](https://raiden.network/101.html)  ( [ipfs](https://gateway.ipfs.io/ipfs/QmTNT6Ph4CcdSdvYzhQTJDtfmKDv5Vxq6tDm3QEshrT56f) )
* Describes a network of payment channels for Turing-complete blockchains that would allow members to transfer tokens over multiple hops instantaneously and trustlessly. [2016]


 [Plasma](https://plasma.io/plasma.pdf)  by Joseph Poon, Vitalik Buterin (ipfs)
* Describes a construction of smart contracts on the main blockchain that use fraud proofs to enforce state transitions on a child blockchain, enabling off-chain scaling. [2017]


 [Bolt](https://eprint.iacr.org/2016/701.pdf)  by Matthew Green, Ian Miers ( [ipfs](https://gateway.ipfs.io/ipfs/QmaMG3PXCCbPSgep9gM2yuLBtXEisR71MAC64JyWQh96K6) )
* Describes a network of payment channels for private blockchains that would allow for members to send anonymous payments through at-most a single intermediary. [2018]


 [Making Sense of Ethereum’s Layer 2 Scaling Solutions](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4)  by Josh Stark ( [ipfs](https://gateway.ipfs.io/ipfs/QmdPiruUZaDTLePBUyEhZTqyyfV6kQSBP4jARiXy72vsDp) )
* A summary of state channels, Plasma, and Truebit. [2018]

## Sharding
 [Minimal VDF Randomness Beacon](https://ethresear.ch/t/minimal-vdf-randomness-beacon/3566)  by Justin Drake ( [ipfs](https://gateway.ipfs.io/ipfs/QmUR7RRTfzbxBg2v7wnry39Z7jRmrkJMDV9dN5fGptfeZo) )
* A discussion around using a Verifiable Delay Function (VDF) as a randomness beacon. [2018]


 [Ethereum 2.0 Spec - Beacon Chain](https://github.com/ethereum/eth2.0-specs/blob/master/specs/core/0_beacon-chain.md)  ( [ipfs](https://gateway.ipfs.io/ipfs/QmUoJZpeVW6Potmd9uSMJPbRH7U3ZdC3XyvSAG2SPKvAP4) )
* The specification for the system chain at the core of Ethereum’s network upgrade that stores and manages the registry of validators. [2019]


 [Ethereum 2.0 Spec - Sharding](https://github.com/ethereum/eth2.0-specs/blob/master/specs/core/1_shard-data-chains.md)  ( [ipfs](https://gateway.ipfs.io/ipfs/QmUoJZpeVW6Potmd9uSMJPbRH7U3ZdC3XyvSAG2SPKvAP4) )
* The specification for the data chains in Ethereum’s network upgrade. [2019]


 [Detailed Overview of Ethereum 2.0 Shard Chains](https://medium.com/nearprotocol/detailed-overview-of-ethereum-2-0-shard-chains-committees-proposers-and-attesters-a9992d2fd103)  by Alexander Skidanov ( [ipfs](https://gateway.ipfs.io/ipfs/Qmdb27ecdomzPDAENq1VqvmJpx1v6ppLgBxWTpeLHThd54) )
* An outside analysis of the Ethereum 2.0 specification as a whole. [2018]

## Trusted Execution Environments
 [SGX Review](https://www.blackhat.com/docs/us-16/materials/us-16-Aumasson-SGX-Secure-Enclaves-In-Practice-Security-And-Crypto-Review-wp.pdf)  by JP Aumasson, Luis Merino ( [ipfs](https://gateway.ipfs.io/ipfs/QmQ7EEG6huSi568QrNQrJ7q9TNUDPh2Lq4BqAMsDVoTTbJ) )
* A blackhat overview of Intel’s TEE, the Software Guard Extensions (SGX). [2016]


 [SGX Threat Model](https://eprint.iacr.org/2016/086.pdf)  by Victor Costan, Srinivas Devadas ( [ipfs](https://gateway.ipfs.io/ipfs/QmSG2yeydQLkCGEuQi7rrHTvm3BwdmHgZvUY87chSf6Ko2) )
* An in-depth engineering analysis of the SGX. [2016]


 [Meltdown Vulnerability](https://meltdownattack.com/meltdown.pdf)  by Moritz Lipp, Michael Schwarz, Daniel Gruss, Thomas Prescher, Werner Haas, Stegan Mangard, Paul Kocher, Daniel Genkin, Yuval Yarom, Mike Hamburg ( [ipfs](https://gateway.ipfs.io/ipfs/Qmf73kSTD8nxTFqzPR8LNFVD4nBqsDB5cTdeeswQXo61Rc) )
* Describes an attack on modern processors leveraging speculative execution to break the isolation between a machine’s operating system and its applications. [2017]


 [Spectre Vulnerability](https://spectreattack.com/spectre.pdf)  by Paul Kocher, Jann Horn, Anders Fogh, Daniel Genkin, Daniel Gruss, Werner Haas, Mike Hamburg, Moritz Lipp, Stefan Mangard, Thomas Prescher, Michael Schwarz, Yuval Yarom ( [ipfs](https://gateway.ipfs.io/ipfs/Qma1dM4Pwxs2HuJPY99P5oAm1FUbiPRNaGBxXyQuFzTbjV) )
* Describes an attack on modern processors leveraging speculative execution to break the isolation between applications on a machine. [2017]


 [Introduction to TEEs](https://globalplatform.org/wp-content/uploads/2018/05/Introduction-to-Trusted-Execution-Environment-15May2018.pdf)  by GlobalPlatform ( [ipfs](https://gateway.ipfs.io/ipfs/QmSdkbG154JGJnZyfCzg64523LVVb76e1h2fhsEZMxCo9Q) )
* A practical overview of Trusted Execution Environments (TEEs). [2018]


 [Ekiden](https://arxiv.org/pdf/1804.05141.pdf)  by Raymond Cheng, Fan Zhang, Jernej Kos, Warren He, Nicholas Hynes, Noah Johnson, Ari Juels, Andrew Miller, Dawn Song ( [ipfs](https://gateway.ipfs.io/ipfs/QmRXPqgR4hqMw1ZQBvrbTZ6bZ5C8JF3mpX5cwtincBcLEx) )
* Describes a platform leveraging TEEs for private smart contract execution. [2018]


 [Foreshadow Vulnerability](https://www.usenix.org/conference/usenixsecurity18/presentation/bulck)  by Jo Van Bulck, Marina Minkin, Ofir Weisse, Daniel Genkin, Baris Kasikci, Frank Piessens, Mark Silberstein, Thomas F. Wenisch, Yuval Yarom, Raoul Strackx ( [ipfs](https://gateway.ipfs.io/ipfs/QmdzNamU5ydwVhxiZrUaiaAubonijGQZ2WxqJHquz8PsT3) )
* Describes an attack on modern processors leveraging speculative execution to steal the keys to an SGX. [2018]


 [Nemesis Vulnerability](https://people.cs.kuleuven.be/~jo.vanbulck/ccs18.pdf)  by Jo Van Bulck, Frank Piessens, Raoul Strackx ( [ipfs](https://gateway.ipfs.io/ipfs/Qmcv66UitAPmukFk12qvaVijKDvC8LLbEn7piXaPj2Nzzr) )
* Describes an attack on modern processors leveraging speculative execution to steal information from within an SGX without the keys. [2018]


 [Row Hammer Vulnerability](http://users.ece.cmu.edu/~yoonguk/papers/kim-isca14.pdf)  by Yoongu Kim, Ross Daly, Jeremie Kim, Chris Fallin, Ji Hye Lee, Donghyuk Lee, Chris Wilkerson, Konrad Lai, Onur Mutlu ( [ipfs](https://gateway.ipfs.io/ipfs/QmVeSgEF97DUEwkyNKdsD8xMaWJ2P5zJeZWpCCXmskQNHR) )
* Describes an attack on modern processors that exposed the vulnerability of DRAM chips to disturbance errors. [2018]

## Peer-to-peer Communications
 [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf)  by Petar Maymounkov, David Mazières ( [ipfs](https://gateway.ipfs.io/ipfs/QmbBxAMCi5vNsKp6H3CRGnxiWb8vaSGcYosq5irXnSHWJ9) )
* Describes a p2p distributed hash table (DHT) that efficiently allows nodes to identify each other. [2002]


 [Whisper](https://github.com/ethereum/wiki/wiki/Whisper)  by Gavin Wood ( [ipfs](https://gateway.ipfs.io/ipfs/QmcrsJHZcMgMcH8eZsErFkcn3GDDp3fQnXWDwaStcWuHcL) )
* Describes a p2p protocol for Ethereum dApps to communicate with each other. [2018]


 [devp2p](https://github.com/ethereum/devp2p/blob/master/devp2p.md)  by Felix Lange ( [ipfs](https://gateway.ipfs.io/ipfs/QmWoA5RX1byxA6ySgsUL3UPWJo839EY7gcbqKPAVPZg2fJ) )
* Describes an application layer networking protocol for communication among nodes in a peer-to-peer network. [2018]


 [libp2p](https://github.com/libp2p/specs)  by Juan Benet and David Dias ( [ipfs](https://gateway.ipfs.io/ipfs/QmdGjePByEpij3dpxN5zSxHbaTMxhnqCUpQ4sq3ErLiUiK) )
* Describes the networking protocol for IPFS nodes to communicate with each other (ipfs link is a zip file for the repo). [2018]


 [Tezos p2p](https://tezos.gitlab.io/master/whitedoc/p2p.html)  ( [ipfs](https://gateway.ipfs.io/ipfs/QmNzrj2PQoUDMt3EuCsbxERRf5Sus8BQBP4VePNshPH4U7) )
* Describes a p2p protocol for Tezos nodes to communicate with each other. [2018]

# 🏦 Cryptoeconomics
Here are the links to all major concepts in  [cryptoeconomics](https://thecontrol.co/cryptoeconomics-101-e5c883e9a8ff) :

 [Nash Equilibrium](http://home.uchicago.edu/rmyerson/research/jelnash.pdf)  by Roger Myerson ( [ipfs](https://gateway.ipfs.io/ipfs/QmaGnvdqA3ywqXhYNcadzZFE9GFHGCJd8yWmH7AeyoCY1t) )
* Describes a key concept in cryptoeconomics within the broader context of economic history. [1999]


 [On Inflation, Transaction Fees, and Cryptocurrency Monetary Policy](https://blog.ethereum.org/2016/07/27/inflation-transaction-fees-cryptocurrency-monetary-policy/)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmVtNGJiX5t5yqjnYRkTgQi5uujtdMNe8TEUu3V7ypNgbd) )
* Describes the design space for how blockchain-based communities can pay for security. [2016]


 [Bitcoin’s Security Model](https://www.coindesk.com/bitcoins-security-model-deep-dive/)  by Jameson Lopp ( [ipfs](https://gateway.ipfs.io/ipfs/QmSb1w9zmyEXBmNLgVoqift7CT2Nm1q79piWo1cTPNRdZf) )
* Describes how Bitcoin’s community ensures security for its blockchain. [2016]


 [Cryptocurrency Game Theory](https://blockgeeks.com/guides/cryptocurrency-game-theory/)  by Blockgeeks ( [ipfs](https://gateway.ipfs.io/ipfs/QmSiP2WJyvtA9Zta1nUpGfJPeyH5fqM8EsM4B1CxAJVahM) )
* Gives an overview of basic concepts in cryptoeconomics. [2017]


 [Introduction to Cryptoeconomics](https://vitalik.ca/files/intro_cryptoeconomics.pdf)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmVJos4VSippwykT1zc7LU65JKdZB1xji8tjgPSTpgBfrE) )
* Describes a system that uses cryptography to prove properties about messages that have happened in the past, and economic incentives to encourage desired properties hold in the future. [2017]


Cryptoeconomics is Hard:  [Part 1](https://blog.coinfund.io/cryptoeconomics-is-hard-ad401b2428b9) ,  [Part 2](https://blog.coinfund.io/cryptoeconomics-is-hard-part-2-4d522cb3d3a4) , and  [Part 3](https://blog.coinfund.io/cryptoeconomics-is-hard-market-cap-4833c378a3e0)  by Aleksandr Bulkin ( [ipfs1](https://gateway.ipfs.io/ipfs/QmP1SF3mSmLzUbgPMyXcRciJFCYDEd5TkYSaayEjCrY2M9) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmYtfDiAFWAkWHjbmCBbM1UMj4nueRPjW9FFZUcNPqBjN2) ,  [ipfs3](https://gateway.ipfs.io/ipfs/QmdxFyJdDMpG4Cbp7u6xProCchZCHBTw7Z9iohDPGr53FB) )
* Describes common pitfalls with cryptoeconomic systems and why they occur. [2017]


 [Empirical Cryptoeconomics](https://www.reddit.com/r/ethereum/comments/453sid/empirical_cryptoeconomics/)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmV8MyTSTsxHFw8tgYggPmgX2Rq99zJFs2cL9kf6MJ3xLd) )
* Proposes empirical tests to measure the effectiveness of different cryptoeconomic theories. [2017]


 [Manipulation-Resistant Prediction Markets](https://blog.gnosis.pm/how-manipulation-resistant-are-prediction-markets-710e14033d62)  by Nadja Beneš (ipfs)
* Describes a foray into empirical cryptoeconomics to prove the results of prediction markets can be trusted. [2017]


 [Behavioral Crypto-Economics](https://medium.com/berlin-innovation-ventures/behavioral-crypto-economics-6d8befbf2175)  by Elad Verbin ( [ipfs](https://gateway.ipfs.io/ipfs/QmUy9rE2YfE6g32vLFWhLNxk9fvccnV1wVE46RaqMweMZB) )
* Describes how current cryptoeconomic systems underweight the learnings from behavioral economics. [2018]


 [Schelling Points](https://mindyourdecisions.com/blog/2008/04/01/focal-points-or-schelling-points-how-we-naturally-organize-in-games-of-coordination/)  by Presh Talwalkar ( [ipfs](https://gateway.ipfs.io/ipfs/QmYvQxHSa8RA44wz15LqDpBMHQsUCHmUktbtQt8fionyd9) )
* Describes Schelling Points, a key concept in cryptoeconomics. [2008]


 [Mechanism Design Theory](https://assets.nobelprize.org/uploads/2018/06/advanced-economicsciences2007-2.pdf)  (and  [slides](https://www.slideshare.net/stathisgrigoropoulos/mechanism-design-theory-examples-and-complexity-final?from_action=save) ) by the Prize Committee of the Royal Swedish Academy of Sciences and Stathis Grigoropoulos, respectively ( [ipfs1](https://gateway.ipfs.io/ipfs/QmT2ZAhHHGnoDryXV99tF23P81BeCBFkuRyqL3PUZbRvfi) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmVujyFoJJ93Nw37Hu4jJXLirMVkkJzafP6gcy1RHw7o47) )
* Provides a coherent framework for analyzing allocation mechanisms with a focus on the problems caused by incentives and private information. [2018]

## Tokenomics
Here are the links to all major concepts in  [tokenomics](https://medium.com/@wmougayar/tokenomics-a-business-guide-to-token-usage-utility-and-value-b19242053416) :

 [Cryptoasset Valuations](https://medium.com/@cburniske/cryptoasset-valuations-ac83479ffca7)  by Chris Burniske ( [ipfs](https://gateway.ipfs.io/ipfs/QmYzgNj3gxUzDEymiPGby3eGZt3tm2EpvRKqzaipsWy7Dr) )
* Describes a history of different valuation models for cryptoassets. [2017]


 [Justified Token Value](https://medium.com/@adrian_jonklaas/justified-token-value-part-1-3ac6836656b8)  by Indra Adrian Jonklass ( [ipfs](https://gateway.ipfs.io/ipfs/QmebEhovHc248XWVw6wEGtBu24WEdLWwFAx9AKBsp8k6hV) )
* Describes a token valuation model based on distributions. [2017]


 [Network Value to Transactions Ratio](https://coinmetrics.io/mtv-ratio-part-ii/)  by Coinmetrics ( [ipfs](https://gateway.ipfs.io/ipfs/QmNPUaHuf8TzTUrfDwri4CyB6EYNv58jdKoajuGP7PZLJr) )
* Proposes a normalized metric used to compare valuations of cryptocurrencies. [2017]


 [Token Classification Framework](http://www.untitled-inc.com/the-token-classification-framework-a-multi-dimensional-tool-for-understanding-and-classifying-crypto-tokens/)  by Thomas Euler ( [ipfs](https://gateway.ipfs.io/ipfs/Qmb7Uh6EfLorbdZsFnQWAar6U5AtqUWRFBF8JRpLLCw5RY) )
* Provides a framework for classifying, and therefore valuing, different types of tokens. [2018]


 [Quantity Theory of Money for Tokens](https://blog.coinfund.io/the-quantity-theory-of-money-for-tokens-dbfbc5472423)  by Warren Weber ( [ipfs](https://gateway.ipfs.io/ipfs/QmQuKURC1ZZdpXaZrbbjU1oQcmj31s6wV712xGqKjpcqRP) )
* Argues for using the Equation of Exchange to value cryptoassets. [2018]


 [MV=PQ Isn’t Right for Crypto](https://medium.com/@AustereCapital/mv-p-que-love-and-circularity-in-the-time-of-crypto-1626c8ac297f)  by Austere Capital ( [ipfs](https://gateway.ipfs.io/ipfs/QmfVc5B3YVzj95hrvatczDyG1QdWadkK8UcmnAq6K74LZT) )
* Argues against using the Equation of Exchange to value cryptoassets. [2018]


 [Bitcoin Market-Value-to-Realized-Value (MVRV) Ratio](https://blog.goodaudience.com/bitcoin-market-value-to-realized-value-mvrv-ratio-3ebc914dbaee)  by Murad Mahmudov, David Puell ( [ipfs](https://gateway.ipfs.io/ipfs/QmPmoBm3Sez4t2fCVmH4JVtqGw4gdeEesVpEbyaGLZzF3C) )
* Proposes an update to the NVT Ratio as a more effective metric for valuing cryptocurrencies. [2018]

## Governance
 [Governance and Network Effects](https://blog.aragon.org/thoughts-on-governance-and-network-effects-f40fda3e3f98/)  by Luke Duncan and Aragon ( [ipfs](https://gateway.ipfs.io/ipfs/QmZQ3CFETMGsvjqR3jz6mNo6VKofoSZXDN1mGHcmbzUcyY) )
* Argues for effective governance of blockchain-based communities as a value-added differentiator. [2017]


 [Notes on Blockchain Governance](https://vitalik.ca/general/2017/12/17/voting.html)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/Qmdei3ZGJ4c5EhhrrA1jMGE7MTVsnD3M3tS2rs9fFZZWkY) )
* Provides an overview of on-chain, off-chain, and algorithmic governance for blockchain-based communities. [2017]


 [Blockchain Governance: Programming our Future](https://medium.com/@FEhrsam/blockchain-governance-programming-our-future-c3bfe30f2d74)  by Fred Ehrsam ( [ipfs](https://gateway.ipfs.io/ipfs/QmSdrhBzq5kxk7SCfkYSaTTwzhdBewxhNThxdvjqnuczkE) )
* Describes the opportunities available within the design space of blockchain governance. [2017]


 [Against On-Chain Governance](https://medium.com/@Vlad_Zamfir/against-on-chain-governance-a4ceacd040ca)  by Vlad Zamfir ( [ipfs](https://gateway.ipfs.io/ipfs/Qmd4RTSgLegQJYjaDHrXZ5nUVg1CTAG6i3nKfCDCVkym75) )
* Argues against on-chain governance. [2017]


 [Why Decentralization Matters](https://medium.com/@cdixon/why-decentralization-matters-5e3f79f7638e)  by Chris Dixon ( [ipfs](https://gateway.ipfs.io/ipfs/QmYWbzQownw8xEFtU16xNFruSQ34WPuRmrxKx8CLYfT34z) )
* Describes how cryptonetworks and blockchain-based communities can outcompete their centralized competition, including a history of how the Internet got to this point. [2018]


 [Why On-Chain Governance?](https://medium.com/polkadot-network/why-on-chain-governance-82ecf28f314c)  by Phil Lucsok ( [ipfs](https://gateway.ipfs.io/ipfs/QmTPk2jHn4t355WftxJBPPbrrB59ZKotmsgYHUNqFhTGng) )
* Argues for more on-chain governance. [2018]


 [Against Szabo’s Law, For A New Crypto Legal System](https://medium.com/@Vlad_Zamfir/against-szabos-law-for-a-new-crypto-legal-system-d00d0f3d3827)  by Vlad Zamfir ( [ipfs](https://gateway.ipfs.io/ipfs/QmTdjxb75ujAmJxg5cAZAqzTfx7t2UbfSMtDorBCF7SSar) )
* Proposes the existence of three laws followed by all blockchain-based communities, and argues against the third. [2019]

# 🐞 Vulnerabilities, Bugs and Hacks
## Attack Vectors

 [$5 Wrench Attack](https://xkcd.com/538/)  by Randall Munroe ( [ipfs](https://gateway.ipfs.io/ipfs/QmdFfhXzFhrxK9X1esVVhrmykXskC98VTi8Zht8CndzsCx) )
* The simplest and cheapest out-of-band attack. 


 [Analysis of Bitcoin Pooled Mining Reward Systems](https://arxiv.org/pdf/1112.4980.pdf)  by Meni Rosenfeld ( [ipfs](https://gateway.ipfs.io/ipfs/QmXiGJqmdM4YQW3CLp2LUxS13nz6fpxhntdRhZYAEmd77M) )
* Describe the various scoring systems used to calculate rewards of participants in Bitcoin pooled mining, explain the problems each were designed to solve and analyze their respective advantages and disadvantages. [2011]


 [Timejacking & Bitcoin](http://culubas.blogspot.com/2011/05/timejacking-bitcoin_802.html)  by Alex Boverman ( [ipfs](https://gateway.ipfs.io/ipfs/QmVqFRsJJqkFkfScxXpBJtTjrUYL6ZyJ57549fFWeFJyJN) )
* Describes how an attacker could deceive a node into accepting an alternate block chain By announcing inaccurate timestamps when connecting it. [2011]


 [Two Bitcoins at the Price of One? Double-Spending Attacks on Fast Payments in Bitcoin](https://eprint.iacr.org/2012/248.pdf)  by Ghassan Karame, Elli Androulaki, Srdjan Capkun ( [ipfs](https://gateway.ipfs.io/ipfs/QmezYwc5u1woKou1X9ZnW5M2KLptH6hRbM5NZYeDHoAfyB) )
* Analyzes double spend attacks and proposes a lightweight countermeasure that enables their detection in fast transactions. [2012]


 [Selfish Mining](https://bitcoinmagazine.com/articles/selfish-mining-a-25-attack-against-the-bitcoin-network-1383578440/)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmUfj96x8doY7LeB5qosiwM2dZWxrxonLDdTA6q6p7ybZc) )
* An attack where miners can guarantee themselves multiple blocks in a row. [2013]


 [Feather-forks: enforcing a blacklist with sub-50% hash power](https://bitcointalk.org/index.php?topic=312668.0)  by socrates1024 ( [ipfs](https://gateway.ipfs.io/ipfs/QmVWtiPZv4bFNqLJEoiK33oukPEDpaKutxQZuMRPhwtRyq) )
* Describes an attack where a miner refuses to mine on any chain that includes a transaction it doesn’t like in the most recent several blocks. [2013]


 [Majority is not Enough: Bitcoin Mining is Vulnerable (e.g. Selfish Mining)](https://www.cs.cornell.edu/~ie53/publications/btcProcFC.pdf)  by Ittay Eyal, Emin Gün Sirer ( [ipfs](https://gateway.ipfs.io/ipfs/QmNukb1L8BhEsiCbrmnkEJWAvUjhBHidinKMZKfCaLG6ep) )
* Proposes a modification to the Bitcoin protocol that prohibits selfish mining by pools that command less than 1/4 of the resources. [2013]


 [Economics of Bitcoin Mining, or Bitcoin in the Presence of Adversaries (e.g. Goldfinger)](https://www.econinfosec.org/archive/weis2013/papers/KrollDaveyFeltenWEIS2013.pdf)  by Joshua A. Kroll, Ian C. Davey, Edward W. Felten ( [ipfs](https://gateway.ipfs.io/ipfs/QmRsLq4hCkWvSgwnPPnCkSKVAr1QHHeFKWz1dX1StXjsmo) )
* Shows how a motivated adversary might be able to disrupt the Bitcoin system and “crash” the currency. [2013]


 [Sybil Attack](https://ac.els-cdn.com/S1877050914007443/1-s2.0-S1877050914007443-main.pdf?_tid=f4b9edec-b971-49c2-a295-3a4f35186e55&acdnat=1538410700_7796407208c33344b0ec9ca14b727144)  by Zied Trifa, Maher Khemakhem ( [ipfs](https://gateway.ipfs.io/ipfs/QmaXsQoAj4VEmdoZc2D9XawREWmAHsQ7TafNfxP3eAp3Ci) )
* An attack on networks where users are free to join or leave at any time. [2014]


 [The Miner’s Dilemma](http://hackingdistributed.com/2014/12/03/the-miners-dilemma/)  by Ittay Eyal ( [ipfs](https://gateway.ipfs.io/ipfs/Qmcaiuok5j4gSxWSiXhw31NiRZSwLnhxdQVx9MunnZFair) )
* Describes the unstable balance between mining pools, and the attack vectors that balance presents. [2014]


 [Long Range Attacks in PoW](https://blog.ethereum.org/2014/05/15/long-range-attacks-the-serious-problem-with-adaptive-proof-of-work/)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmTy2csnUNCv6wCnnrEkPMonX71DLo1zmPGFRpnatZSfmA) )
* A classic attack vector in Proof of Work. [2014]


 [Empirical Analysis of Denial-of-Service Attacks in the Bitcoin Ecosystem](https://fc14.ifca.ai/bitcoin/papers/bitcoin14_submission_17.pdf)  by Marie Vasek, Micah Thorton, Tyler Moore ( [ipfs](https://gateway.ipfs.io/ipfs/QmYHNDNBQg8UM11PSijqoqSy4teY5E2PpC5Sf2zekMnfc6) )
* Analyzed 142 unique DDoS attacks on 40 Bitcoin services. [2014]


 [Game-Theoretic Analysis of DDoS Attacks Against Bitcoin Mining Pools](https://www.researchgate.net/profile/Aron_Laszka/publication/263605255_Game-Theoretic_Analysis_of_DDoS_Attacks_Against_Big_and_Small_Mining_Pools/links/53cf9f340cf2f7e53cf81963/Game-Theoretic-Analysis-of-DDoS-Attacks-Against-Big-and-Small-Mining-Pools.pdf)  by Benjamin Johnson, Aron Laszka, Jens Grossklags, Marie Vasek, Tyler Moore ( [ipfs](https://gateway.ipfs.io/ipfs/QmcK5onHpV1VXgpTi8FspFxjuL9DDo9ywUWHE35XCVy2TQ) )
* Determines an expected equilibrium for attacks between mining pools of varying sizes. [2014]


 [On Subversive Miner Strategies and Block Withholding Attack in Bitcoin Digital Currency](https://arxiv.org/pdf/1402.1718.pdf)  by Nicolas T. Courtois, Lear Bahack ( [ipfs](https://gateway.ipfs.io/ipfs/QmZAktjQ6ry6xS9kMJJJRS9zyN4sHHJXnuj7hw2L5Jo5uE) )
* Discusses several recent attacks in which dishonest miners obtain a higher reward than their relative contribution to the network. [2014]


 [An Analysis of Anonymity in Bitcoin Using P2P Network Traffic](https://pdfs.semanticscholar.org/c277/62257f068fdbb2ad34e8f787d8af13fac7d1.pdf)  by Philip Koshy, Diana Koshy, Patrick McDaniel ( [ipfs](https://gateway.ipfs.io/ipfs/QmPPcRDoai9muY44PKhvGg4KKNDfYZk1y5AaAXhBKHHetr) )
* Developed heuristics for identifying ownership relationships between Bitcoin addresses and IP addresses. [2014]


 [Deanonymisation of Clients in Bitcoin P2P Network](https://orbilu.uni.lu/bitstream/10993/18679/1/Ccsfp614s-biryukovATS.pdf)  by Alex Biryukov, Dmitry Khovratovich, Ivan Pustogarov ( [ipfs](https://gateway.ipfs.io/ipfs/QmPUQiXnEg7DebbKcScFSHm8nvWB7W8TJ2i97VUAqK3L2h) )
* Presents an efficient method to deanonymize Bitcoin users, which allows to link user pseudonyms to the IP addresses where the transactions are generated, with a success rate between 11% and 60%. [2014]


 [On Stake](https://blog.ethereum.org/2014/07/05/stake/)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmVBwAm4hNEdb9XprqhgMUqdJF6zcE1tD7Xr1QJeYG5CXm) )
* Discusses the strengths and weaknesses of Proof of Stake. [2014]


 [Censorship Attack](https://blog.ethereum.org/2015/06/06/the-problem-of-censorship/)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmatYwwPRLsMAHxbNxHNitv6LUPadNyrH4KFYKW7AXe1tx) )
* How to ensure transactions that people want to include on the blockchain get in. [2015]


 [P+ epsilon Attack](https://blog.ethereum.org/2015/01/28/p-epsilon-attack/)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/Qmcb4sMdUBwQNVsoWVyHUxPWjCBG1r8FYASaa1XoVtDEWN) )
* Describes an attack in which honest users are incentivized to vote to support the attacker, because the attacker takes on the failure risk themselves. [2015]


 [Eclipse attacks on Bitcoin’s peer-to-peer network](https://www.usenix.org/system/files/conference/usenixsecurity15/sec15-paper-heilman.pdf)  by Ethan Heilman, Alison Kendler, Aviv Zohar, Sharon Goldberg ( [ipfs](https://gateway.ipfs.io/ipfs/QmcsmoCQMu13rSN5FLFsHB5aV6WfsjxLdGp8vwSUhzP3Nu) )
* Analyzes an attack in which a full node is isolated from the rest of the network. [2015]


 [Tampering with the Delivery of Blocks and Transactions in Bitcoin](https://eprint.iacr.org/2015/578.pdf)  by Arthur Gervais, Hubert Ritzdorf, Ghassan O. Karame, Srdjan Capkun ( [ipfs](https://gateway.ipfs.io/ipfs/QmesfKbkp4bMMfffnecfnk9VqMiekjehpSWGBzFqgNMR3F) )
* Shows how the information broadcast limitations on full nodes open up DDOS attack vectors. [2015]


 [Bribery Attacks on Bitcoin-Style Consensus](https://www.springer.com/cda/content/document/cda_downloaddocument/9783662533567-c2.pdf?SGWID=0-0-45-1587311-p180215767)  by Joseph Bonneau ( [ipfs](https://gateway.ipfs.io/ipfs/QmVWJHUUhMfuYBtMezi2w1gJPiRhXXUdr1WPLhTvSzbMVd) )
* Show how an attacker might purchase mining power in-band with the system itself enforcing the bribe. [2016]


 [Refund attacks on Bitcoin’s Payment Protocol](https://eprint.iacr.org/2016/024.pdf)  by Patrick McCorry, Siamak F. Shahandashti, Feng Hao ( [ipfs](https://gateway.ipfs.io/ipfs/QmeT28wGBKrMJyERYZSkcKLgbR9ZkdpszhQtNGugTCq8j2) )
* Presents attack vectors on BIP70, and a revised standard to prevent those attacks. [2016]


 [Misbehavior in Bitcoin: A Study of Double-Spending and Accountability](http://users.encs.concordia.ca/~clark/biblio/bitcoin/Karame%202015.pdf)  by Ghassan Karame, Elli Androulaki, Marc Roeschlin, Arthur Gervais, Srdjan Capkun ( [ipfs](https://gateway.ipfs.io/ipfs/QmRPa8cLDteSGhX9erLYne9mPqqnLqVooWf3G5zT43Gpip) )
* Provides accountability and privacy definitions for Bitcoin, and investigates analytically and empirically the privacy and accountability provisions in Bitcoin. [2016]


 [Coordination Problems](https://vitalik.ca/general/2017/05/08/coordination_problems.html)  by Vitalik Buterin ( [ipfs](https://gateway.ipfs.io/ipfs/QmQt73FKLz2r2MAsk4sPqL1SkHYbmU9LD4FAgq4p2ysBWM) )
* Uses Bitcoin’s 2017 miner/full node disagreement to explain the unique coordination problems inherent in blockchain-based ecosystems. [2017]


 [Internal PoW Attacker](https://medium.com/@Vlad_Zamfir/simple-model-of-an-internal-pow-attacker-1a713cf00672)  by Vlad Zamfir ( [ipfs](https://gateway.ipfs.io/ipfs/QmcUk9KhcW5AFCGAJQQg7ZKPrcyb7Hvu3U8HbmjpNY2oWi) )
* Lays out an alternative to the classic “attacker buys 51% of existing hashpower” attack. [2017]


 [Hijacking Bitcoin: Routing Attacks on Cryptocurrencies](https://arxiv.org/pdf/1605.07524.pdf)  by Maria Apostolaki, Aviv Zohar, Laurent Vanbever ( [ipfs](https://gateway.ipfs.io/ipfs/QmVwyRRDhWxbZV1d7HgWMh22ZZpnbqfbv5DqC3jeA9dGvX) )
* Demonstrates how any network attacker can hijack few (<100) BGP prefixes to isolate ∼50% of the mining power—even when considering that mining pools are heavily multi-homed. [2017] 


 [Be Selfish and Avoid Dilemmas: Fork After Withholding (FAW) Attacks on Bitcoin](https://arxiv.org/pdf/1708.09790.pdf)  by Yujin Kwon, Dohyun Kim, Yunmok Son, Eugene Vasserman, Yongdae Kim ( [ipfs](https://gateway.ipfs.io/ipfs/QmU3Q5Wkj9HrnsAisKz2Df9pfcBNT4VjzDRB9Wq1gvXCDN) )
* Proposes an attack in which the attacker’s reward is always equal to or greater than that for a Block Withholding (BWH) attacker, and it is usable up to four times more often per pool than in a BWH attack. [2017]


Nothing at Stake  [Part 1](https://medium.com/coinmonks/understanding-proof-of-stake-the-nothing-at-stake-theory-1f0d71bc027)  by Julian Martinez ( [ipfs](https://gateway.ipfs.io/ipfs/QmcBkb5C4mRUjsUEn2h5hAeuos2zooCN2ByiWKqGEygCuE) )
* Discusses the naive Proof of Stake vulnerability in which every validator builds on every fork that takes place. [2018]


 [Long Range Attacks in PoS](https://medium.com/@abhisharm/understanding-proof-of-stake-through-its-flaws-part-3-long-range-attacks-672a3d413501)  by Abishek Sharma ( [ipfs](https://gateway.ipfs.io/ipfs/QmchWKCfpuKW24BkvMsskvvnA1FsD9tcQq9PMwFh5AK6cn) )
* Discusses how PoS removes the external costs to bitcoin mining, and what that means for the incentive structure and guarantees of having a single blockchain. [2018]


 [Low-Resource Eclipse Attacks on Ethereum’s Peer-to-Peer Network](https://eprint.iacr.org/2018/236.pdf)  by Yuval Marcus, Ethan Heilman, Sharon Goldberg ( [ipfs](https://gateway.ipfs.io/ipfs/QmWJxtwYMnrHVBC6H2eFjKkkPUXsVVJvQddgwqpKi2hwm3) )
* Analyzes an attack in which a full node is isolated from the rest of the network. [2018]

## Protocol Failures and Issues
BTC: March 2013 Chain Fork  [Post-Mortem](https://github.com/bitcoin/bips/blob/master/bip-0050.mediawiki)  and  [Explainer](https://bitcoinmagazine.com/articles/bitcoin-network-shaken-by-blockchain-fork-1363144448/)  by Gavin Andersen and Vitalik Buterin, respectively ( [ipfs1](https://gateway.ipfs.io/ipfs/QmanbTWX4oiMuo4uqWmC4zBYHrnruGMqgH4scWe7gRx6oi) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmdyiH1wskrasPSMfMWpaMPrDMCh7Noz9FtXohL8qmhxCv) )
* Explains how the switch from BerkeleyDB in bitcoind 0.7 to LevelDB in bitcoind 0.8, combined with an unusually large block, caused an unintentional chain fork. [2013]


 [Ethereum Solidity Optimizer Bug](https://blog.ethereum.org/2017/05/03/solidity-optimizer-bug/)  by Martin Swende ( [ipfs](https://gateway.ipfs.io/ipfs/QmTx1WM7GwZGLhp2GBr5o2fVA7A88TNdUACZhJcBsghMAT) )
* Identifies a bug that caused one method in a smart contract to cease functioning when another (unrelated) method was added to the contract. [2017]


Bitcoin CVE-2018-17144  [Full Disclosure](https://bitcoincore.org/en/2018/09/20/notice/)  and  [Analysis](https://medium.com/@jimmysong/bitcoin-core-bug-cve-2018-17144-an-analysis-f80d9d373362)  by Bitcoin Core and Jimmy Song, respectively ( [ipfs1](https://gateway.ipfs.io/ipfs/QmThd1H2ssH4GGbnRk8nqT9k8sHuNEeiaXD7VKHAY3dLWL) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmVbZ98Su1Mg4UZd5fC2KcqwjbXKM1sijQuVNdBsQjHbhg) )
* Describes a bug that could have allowed for inflationary double-spends in Bitcoin. [2018] 


Bitcoin Cash SIGHASH_BUG  [Incident Report](https://www.bitcoinabc.org/2018-05-07-incident-report/)  and  [Analysis](https://medium.com/mit-media-lab-digital-currency-initiative/http-coryfields-com-cash-48a99b85aad4)  by Bitcoin ABC and Cory Fields, respectively ( [ipfs1](https://gateway.ipfs.io/ipfs/QmQS88jxgETUhCmxUt1MvKuLUmMQ61y54bgHyZtBPcnXzE) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmQS88jxgETUhCmxUt1MvKuLUmMQ61y54bgHyZtBPcnXzE) )
* Describes a bug that could have allowed a single transaction to cause a chain fork in Bitcoin Cash. [2018]


 [Ethereum Cryptokitties Congestion Crisis](https://media.consensys.net/the-inside-story-of-the-cryptokitties-congestion-crisis-499b35d119cc)  by Consensys ( [ipfs](https://gateway.ipfs.io/ipfs/QmYmoMmAWgWs5cjYrsSYzTKzx7jDwAv7MErypQJZ235EAi) )
* Provides a narrative account of how the Cryptokitties dapp congested the Ethereum network, and how engineers from several different organizations came together to fix it. [2018]


 [EOS Blacklist Order](https://www.trustnodes.com/2018/06/26/eos-block-producer-fails-comply-arbitrators-blacklist-order-funds-sent-exchange)  by Trustnodes.com ( [ipfs](https://gateway.ipfs.io/ipfs/QmZADwRfZ4erPkg2MNm72dWYRNpGSTZfcaHbEvK1pqk33c) )
* Explains how an EOS block producer failed to comply a blacklist update and allowed a thief to transfer stolen funds to an exchange. [2018]

## Successful Hacks and Post-Mortems
 [Breaking the House](http://martin.swende.se/blog/Breaking_the_house.html)  by Martin Swende ( [ipfs](https://gateway.ipfs.io/ipfs/QmdjPkTKb59jYC96kVqecedFDpuqjzR7Rhey36nsv1bujd) )
* Describes an attack on a pseudo-random number generator used in a smart contract deployed on the Ethereum mainnet. [2015]


The DAO:  [pre-hack](http://hackingdistributed.com/2016/06/13/the-dao-can-turn-into-a-naturally-arising-ponzi/) ,  [post-hack analysis](http://hackingdistributed.com/2016/06/18/analysis-of-the-dao-exploit/) , and  [thoughts](http://hackingdistributed.com/2016/06/17/thoughts-on-the-dao-hack/)  by Emin Gün Sirer, Phil Daian, and Emin Gün Sirer, respectively ( [ipfs1](https://gateway.ipfs.io/ipfs/QmNsCsxqeLJRAPF6oAPDaMaLWm7TGNkCr5SE6XdiZM1ND2) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmWUTGJmGGCQE83kvf5UWFLZsicMExk8gLSy6K9Xn3aDpo) ,  [ipfs3](https://gateway.ipfs.io/ipfs/Qme8xYpMJ1ftuj5ZxeVQ9BpihHSta5w4ZhUDjqoSNSfsce) )
* Explains how the DAO smart contracts were vulnerable to attack, how those vulnerabilities were exploited by an attacker, and what that meant for smart contracts on Ethereum. [2016]


 [King of Ether Post-Mortem](http://www.kingoftheether.com/postmortem.html)  by Kieran Elby ( [ipfs](https://gateway.ipfs.io/ipfs/QmW8jsCpmbeFhL9egdc3pRzoEjW3uqYyrGn3v8vUzTnRJY) )
* Provides an example of a smart contract vulnerable to exploitation due to unexpectedly high gas fees. [2016]


Parity MultiSig #1:  [post-mortem](https://www.parity.io/the-multi-sig-hack-a-postmortem/)  and  [deep dive](http://hackingdistributed.com/2017/07/22/deep-dive-parity-bug/)  by Parity Technologies and  [Lorenz Breidenbach](http://hackingdistributed.com/lorenz/) ,  [Phil Daian](http://hackingdistributed.com/phildaian/) ,  [Ari Juels](http://hackingdistributed.com/arijuels/) , and  [Emin Gün Sirer](http://hackingdistributed.com/egs/) , respectively ( [ipfs1](https://gateway.ipfs.io/ipfs/QmQu7x72JAXQcsV5JQQPTTtShP9hbhcE41M6XKuJ1n5zAB) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmVUqN4S2PTr4PuNtFiWAvdqnZeLeVp4WiusdLdipws6Az) )
* Describes the vulnerabilities in the Parity 1.5 client’s multisig wallet contract that allowed an attacker to take ownership of a victim’s wallet with a single transaction. [2017]


 [Front-running Bancor](https://hackernoon.com/front-running-bancor-in-150-lines-of-python-with-ethereum-api-d5e2bfd0d798)  by Ivan Bogatyy ( [ipfs](https://gateway.ipfs.io/ipfs/Qmf4qVvnEcaC4PmmyQd9dUvAXmZLrKjEC3ZnB9b3nciDP6) )
* Describes an exploit that leveraged a game-theoretic security flaw in the smart contracts 

governing the Bancor exchange to allow non-miners to front-run trades. [2017]

Parity MultiSig #2:  [post-mortem](https://www.parity.io/a-postmortem-on-the-parity-multi-sig-library-self-destruct/)  and  [deep dive](https://hackernoon.com/parity-wallet-hack-2-electric-boogaloo-e493f2365303)  by Parity Technologies and Matt Condon, respectively ( [ipfs1](https://gateway.ipfs.io/ipfs/Qmcru7bmRZL9RTo6zE3WLEC1vPUhRZpxQfJgvx15Sh7m6K) ,  [ipfs2](https://gateway.ipfs.io/ipfs/QmZFXb2yQuSxu6U4YmZqA6z7Tir2MWknSJcCD1s315acGd) )
* Explains how 513k ETH was locked in Parity’s wallet smart contracts by a developer that accidentally removed a dependency from the blockchain. [2017]


 [EOSBet Transfer Hack](https://medium.com/@eosbetcasino/eosbet-transfer-hack-statement-31a3be4f5dcf)  by EOSBet ( [ipfs](https://gateway.ipfs.io/ipfs/QmZnNpCVWR1MTMyWM2MNBLRrjvKbSuEyy2ZtTG1nJJzX73) )
* Describes a flaw in the EOSBet smart contract that allowed an attacker to place bets without transferring tokens to the contract. [2018]


 [Predicting Random Numbers in Ethereum Smart Contracts](https://blog.positive.com/predicting-random-numbers-in-ethereum-smart-contracts-e5358c6b8620)  by Arseny Reutov ( [ipfs](https://gateway.ipfs.io/ipfs/QmNULfQ8zzsZHyHeMQ3wJXGBxXQ83TSsrerXhBy2i6btrQ) )
* Identifies four different categories of vulnerable pseudo-random number generators (PRNGs) used in smart contracts deployed on the Ethereum mainnet. [2018]

# 🔗 External Resources
 [Whitepaper Database](http://diyhpl.us/~bryan/papers2/bitcoin/)  by Bryan Bishop

 [A16z’s Crypto Canon](https://a16z.com/2018/02/10/crypto-readings-resources/)  by Sonal Chokshi, Chris Dixon, Denis Nazarov, Jesse Walden, and Ali Yahya

 [ZKP.Science](https://zkp.science/)  by idk

 # Contributors

 [Binance Research](https://research.binance.com/)

 [Messari](https://messari.io/)

 [Circle Research](https://research.circle.com/)

