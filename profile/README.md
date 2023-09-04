## Hey, welcome to the Sanata Protocol 🐬 👋

### 😎 What is Sanata
The lack of centralized control, combined with highly dynamic adversarial behaviors, makes data durability a challenge in decentralized storage systems.

Sanata protocol offers strong data durability guarantees in a fully decentralized, permissionless setting. 
It leverages the rateless property of fountain code to encode each data object into an infinite stream of encoding fragments. To ensure durability in the presence of dynamic Byzantine behaviors and targeted attacks, an infinite sequence of storage nodes are randomly selected to store encoding fragments. Encoding generation and candidate selection are fully decentralized.

Simulations and large-scale EC2 experiments demonstrate that Sanata provides close-to-ideal mean-time-to-data-loss (MTTDL) with
low storage redundancy, scales to more than 10,000 nodes, and attains performance comparable to IPFS.

### ⛱ Components
 - Rateless Fountain Code
 - Verifiable Randomness
 -  Dual-Layer Erasure Coding

