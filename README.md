## BlockChain
Exercises in Block Chain algorithms and Techniques

**UTXO.java**	

Represents an unspent transaction output. A UTXO contains the hash of the transaction from which it originates as well as its index within that transaction.

**UTXOPool.java**	
Represents the current set of outstanding UTXOs and contains a map from each UTXO to its corresponding transaction output. This class contains constructors to create a new empty UTXOPool or a copy of a given UTXOPool, and methods to add and remove UTXOs from the pool, get the output corresponding to a given UTXO, check if a UTXO is in the pool, and get a list of all UTXOs in the pool.

**Node.java**	

A basic interface for the CompliantNode class

**CompliantNode.java**	

A class skeleton for the CompliantNode class

**Candidate.java**	

A simple class to describe candidate transactions the node recieves

**MaliciousNode.java**	

A very simple example of a malicious node

**Simulation.java**

A basic graph generator that may be used to run simulations with varying graph parameters and test the CompliantNode class

**Transaction.java**	

The Transaction class, a transaction being merely a wrapper around a unique identifier (i.e., the validity and semantics of transactions are irrelevant for the purposes of this code).

**Block.java**

Stores the block data structure.

**BlockHandler.java**	

Uses BlockChain.java to process a newly received block, create a new block, or process a newly received transaction.

**ByteArrayWrapper.java**	

A utility file which creates a wrapper for byte arrays such that it could be used as a key in hash functions. (See TransactionPool.java)

**Transaction.java**	

This is similar to Transaction.java as provided in Assignment 1 except for introducing functionality to create a coinbase transaction. Take a look at Block.java constructor to see how a coinbase transaction is created.

**TransactionPool.java**	

Implements a pool of transactions, required when creating a new block.

