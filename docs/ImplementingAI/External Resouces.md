[Machine Learning Interoperability](https://github.com/jphall663/awesome-machine-learning-interpretability#challenges-and-competitions)




The primary danger to these systems comes from external penetration attempts. To mitigate this threat, a comprehensive defense strategy is employed, incorporating physical, procedural, and communications security methods. These advanced techniques form the cutting edge of current computer security practices. Essentially, the defense mechanism creates a protective barrier around the system and its user community, requiring a breach before any compromise can occur. Additionally, adopting a consistent clearance level for all information within the systems eliminates the risk of internal penetration by definition.

In open use systems, where subscribers aren't engaged in classified processing, there's a risk due to unprotected communication lines, making them more susceptible to external penetration. In contrast, multilevel systems often assume all communications are protected to minimize external threats. However, this approach introduces a new challenge: the potential for unchecked malicious users within the system. When we mention "multilevel," it encompasses both uncleared users and those cleared for various levels (Unclassified, Sensitive, Classified). Unlike closed systems with uniform clearances, open-use multilevel systems lack centralized control over the user population. This absence of control heightens the risk of penetration attempts by malicious users.

In shared-use multilevel computer systems, there's a distinct risk for malicious users to exploit vulnerabilities in the operating system, which is the foundation of security. The concentration of various components within the computer system, such as data and control systems, makes computers an appealing target for hostile actions. Recognizing this malicious threat is crucial for understanding the limitations in securing contemporary computer systems. The concern lies in the ability of a single user, acting as a hostile agent, to manipulate the operating system—located outside the organization's control—thereby bypassing or suspending security controls. This inherent risk contributes significantly to the hesitancy in certifying the security of contemporary systems, as doubts persist about their ability to be effectively secured.


For a system to be considered appropriate for open use multilevel operations, it's imperative to definitively prove that a malicious user cannot take control of the system or access data without authorization. Typically, the capability of a malicious user to introduce and execute arbitrary programs is a key concern, as this could lead to seizing control of the system. Even with more limited abilities, unauthorized access to system data remains a risk if the system is inadequately designed or implemented, or if trapdoors have been surreptitiously inserted into the operating system.

**Addressing System Vulnerabilities: A Need for Design Integration**

The challenge in implementing robust technical security in modern computer systems arises from the inherent inadequacy of the hardware and software foundation. The design of these systems were not originally conceived to withstand deliberate malicious attacks, as designers primarily envisioned benign environments where system deviations were assumed to be accidental.

To effectively enhance security, it is crucial that security considerations are woven into the system's design from the outset. Attempting to retrofit security into an existing system poses significant challenges and offers little assurance of achieving the desired level of security. The key takeaway is that security must be an integral part of the initial system design to provide a solid foundation against potential threats.

A significant portion of the design challenge stems from the lack of models serving as a bridge for translating security requirements into technical specifications. Models are essential not only for defining security criteria but also for establishing acceptance standards during product evaluation.

In the context of computer systems, the access control mechanism plays a crucial role. It involves a blend of procedural, hardware, and software checks to verify a user's authorization to utilize the system. This multifaceted approach ensures a comprehensive validation process, contributing to a more secure and well-defined system. By incorporating models in the design process, the translation of security requirements becomes more systematic, facilitating clearer technical specifications and robust evaluation criteria.

One of the most promising developments of this idea is the concept of a
[reference monitor](https://apps.dtic.mil/sti/pdfs/AD0758206.pdf) which enforces the authorized access relationships between subjects and objects of a system

The reference validation mechanism must always be invoked
The reference validation mechanism must be small enough to be subject to analysis and tests, the completeness of which can be assured

The creation of a design for a reference validation mechanism. This mechanism should essentially mirror the model and faithfully implement the principles underlying the model's approach.

While the development of this reference validation mechanism won't directly yield an operating system, it plays a crucial role in establishing a solid foundation. This foundation, in turn, becomes instrumental in crafting a secure operating system. In simpler terms, envision the model as a blueprint, and the reference validation mechanism as a tool that ensures the final product aligns closely with the intended design principles for enhanced security.

The approach to obtaining a secure system involves first defining what threats the system is to bo secure against, and then defining a conceptual design that can be shown to provide the required protection 

# Links
# DEPRECATION NOTICE

Warning, this repository will soon be deprecated in favor of [openmined-website](https://github.com/OpenMined/openmined-website).

# Open Minded
[Open Minded](https://github.com/OpenMined/openmined-website)

# Secure and Private AI Course

* [Secure and Private AI Course from Udacity](https://www.udacity.com/course/secure-and-private-ai--ud185)
* [Notebooks for Secure and Private AI Course from Udacity](https://github.com/udacity/private-ai)
* [Advanced PySyft](https://github.com/OpenMined/PySyft/tree/master/examples/tutorials)
* [Advanced PyGrid](https://github.com/OpenMined/PyGrid/tree/dev/examples)


# Secure Deep Learning

* [PySyft: A Generic Framework for Privacy Preserving Deep Learning](https://arxiv.org/abs/1811.04017)
* [Private Deep Learning in TensorFlow Using Secure Computation, October 23, 2018](https://arxiv.org/abs/1810.08130)
* [SecureNN: Efficient and Private Neural Network Training, May 10,2018](https://eprint.iacr.org/2018/442.pdf)
* [Gazelle: A Low Latency Framework for Secure Neural Network Inference, January 16, 2018](https://arxiv.org/abs/1801.05507)
* [Chameleon: A Hybrid Secure Computation Framework for Machine Learning Applications, November 29, 2017](https://eprint.iacr.org/2017/1164)
* [CryptoDL: Deep Neural Networks over Encrypted Data, November 14, 2017](https://arxiv.org/abs/1711.05189)
* [MiniONN: Oblivious Neural Network Predictions via MiniONN
Transformations, November 3, 2017](https://acmccs.github.io/papers/p619-liuA.pdf)
* [DeepSecure: Scalable Provably-Secure Deep Learning, May 24, 2017](https://arxiv.org/abs/1705.08963)
* [SecureML: A System for Scalable Privacy-Preserving Machine Learning, April 19, 2017](https://eprint.iacr.org/2017/396)
* [CryptoNets: Applying Neural Networks to Encrypted Data with High Throughput and Accuracy, February 24, 2016](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/04/CryptonetsTechReport.pdf)
* [Privacy-Preserving Deep Learning, October 12, 2015](https://dl.acm.org/citation.cfm?id=2813687)


# Libraries and Frameworks

* [TinyGarble: Logic Synthesis and Sequential Descriptions for Yao's Garbled Circuits](https://github.com/esonghori/TinyGarble)
* [SPDZ-2: Multiparty computation with SPDZ and MASCOT offline phase](https://github.com/bristolcrypto/SPDZ-2)
* [ABY: A Framework for Efficient Mixed-Protocol Secure Two-Party Computation](https://github.com/encryptogroup/aby)
* [Obliv - C: C compiler for embedding privacy preserving protocols:](http://oblivc.org/)
* [TFHE: Fast Fully Homomorphic Encryption Library over the Torus](https://github.com/tfhe/tfhe)
* [SEAL: Simple Encypted Arithmatic Library](https://www.microsoft.com/en-us/research/project/simple-encrypted-arithmetic-library/)
* [PySEAL: Python interface to SEAL](https://github.com/Lab41/PySEAL)
* [HElib: An Implementation of homomorphic encryption](https://github.com/shaih/HElib)
* [nGraph-HE: Deep learning with Homomorphic Encryption (HE) through Intel nGraph](https://github.com/NervanaSystems/he-transformer)


# General Research

* [Overdrive: Making SPDZ Great Again](https://eprint.iacr.org/2017/1230)
* [Privacy-Preserving Logistic Regression Training](https://eprint.iacr.org/2018/233)
* [Between a Rock and a Hard Place: Interpolating Between MPC and FHE](https://eprint.iacr.org/2013/085.pdf)
* [Privacy-Preserving Boosting with Random Linear Classifiers for Learning from User-Generated Data](https://arxiv.org/abs/1802.08288)
* [The Secret Sharer: Measuring Unintended Neural Network Memorization & Extracting Secrets](https://arxiv.org/abs/1802.08232)
* [Improvements for Gate-Hiding Garbled Circuits](https://eprint.iacr.org/2017/976.pdf)
* [Practical Secure Aggregation for Privacy-Preserving Machine Learning](https://eprint.iacr.org/2017/281.pdf)
* [CryptoRec: Secure Recommendations as a Service](https://arxiv.org/pdf/1802.02432.pdf)
* [Semi-supervised Knowledge Transfer for Deep Learning from Private Training Data](https://arxiv.org/abs/1610.05755)
* [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/abs/1602.05629)
* [Differentially Private Generative Adversarial Network](https://arxiv.org/abs/1802.06739)
* [Doing Real Work with FHE: The Case of Logistic Regression](https://eprint.iacr.org/2018/202)
* [ADSNARK: Nearly Practical and Privacy-Preserving Proofs on Authenticated Data](https://eprint.iacr.org/2014/617.pdf)
* [Scalable Private Learning with PATE](https://arxiv.org/abs/1802.08908)
* [Doing Real Work with FHE: The Case of Logistic Regression](https://eprint.iacr.org/2018/202)
* [Reading in the Dark: Classifying Encrypted Digits with Functional Encryption](https://eprint.iacr.org/2018/206)
* [Stealing Hyperparameters in Machine Learning](https://arxiv.org/abs/1802.05351)
* [How to Backdoor Federated Learning](https://arxiv.org/abs/1807.00459)
* [Federated Optimization:Distributed Machine Learning for On-Device Intelligence](https://arxiv.org/abs/1610.02527)
* [Federated Learning: Strategies for Improving Communicating Efficiency](https://arxiv.org/abs/1610.05492)
* [Personalized and Private Peer-to-Peer Machine Learning](http://proceedings.mlr.press/v84/bellet18a/bellet18a.pdf)
* [A generic framework forprivacy preserving deep learning](https://arxiv.org/abs/1811.04017) 
* [Protection Against Reconstruction and Its Applications in Private Federated Learning](https://arxiv.org/abs/1812.00984)
* [Towards Federated Learning at Scale: System Design](https://arxiv.org/abs/1902.01046)
* [Federated Learning of Deep Networks using Model Averaging](https://arxiv.org/abs/1602.05629)
* [SANNS: Scaling Up Secure Approximate k-Nearest Neighbors Search](https://arxiv.org/abs/1904.02033)


# Blogs

* [Cryptography and Machine Learning: Mixing both for private data analysis](https://mortendahl.github.io/)
* [Building Safe A.I.: A Tutorial for Encrypted Deep Learning](https://iamtrask.github.io/2017/03/17/safe-ai/)
* [Awesome MPC: Curated List of resources for MPC](https://github.com/rdragos/awesome-mpc)

# Groups

* [The Alan Turing Institute: Privacy-preserving data analysis](https://www.turing.ac.uk/research_projects/privacy-preserving-data-analysis/)

# Podcasts

* [TWiML: Differential Privacy Theory & Practice. Aaron Roth](https://twimlai.com/talk/132)
* [TWiML: Scalable Differential Privacy for Deep Learning. Nicholas Papernot](https://twimlai.com/talk/134)

# Workshops

* [Privacy Preserving Machine Learning NeurIPS 2018 Workshop](https://ppml-workshop.github.io/ppml/)

# Thanks


