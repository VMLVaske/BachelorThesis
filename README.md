# Stateless Ethereum Syncing - Comparing Beam Sync

This is the topic of my bachelor (undergrad) thesis that I wrote over the course of 2020. It was scientifically sufficient to graduate with this :) If you have any questions or I can be of any assistance, feel free to reach out or raise an Issue. 

## Contents
1. Introduction
  * Overview
  * Contributions
  * Outline
2. Basics
  * Ethereum-Blockchain
  * State
  * Modified Merkle Patricia Trie
    * Merkle Tree
    * Patricia Trie
    * Modification
3. Stateful Tech Tree
  * Theoretical Concept
  * Practical Implementation
    * Full Sync
        Clients
    * Fast Sync
        Client: Geth
    * Warp Sync
        Clients: OpenEthereum (a.k.a. Parity)
  * Time Complexity Class
4. Stateless Tech Tree
  * Theoretical Concept
    * Witness Size + Specification, Size, Indexing, Gas Accounting, Chunking, Stateless Transaction Validation
    * Binary Trie, Overlay Conversion Method
    * Code Merklization
    * Ethereum Virtual Machine Changes
  * Praxtical Implementation
    * Beam Sync
    * Clients: Trinity + Nethermind
  * Time Complexity Class
  * Problems, Opportunities and Vectors of Attack
5. Conclusion


## Special thanks to
Jussi Salzwedel, my first examiner. 
Jason Carver, my second examiner. 
Christoph Burgdorf who guided me through the whole thought-process and was my mentor and supervisor. 
Kurt Merbeth who always had an open ear in the middle of the night to listen

## License
If you want to use any of this, feel free. 
