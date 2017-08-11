# Mining
Mining is how new transactions get added to a blockchain. Something has to be done in order to add transactions to the chain, and depending on how the chain is set up, there are a few different ways this can happen.

### Think of it like this
In order to make sure that transactions are secure, somebody has to so a little bit of extra work before adding a transaction to the chain.

### How does it work?
For the blockchain to work, someone needs to be writing all the transactions down, and that's where miners come in. The miners have computers that do very difficult and complex math problems that take a long time to solve. They all work on the same problem at the same time; when one of the miner's computers solves the problem, the rest of the miners check their work, and if it is correct, a block of transactions is added to the blockchain. Because mining takes a lot of computational power and electricity, it costs money to do. To reward them, miners get to add a transaction onto the block they solve, giving themselves a certain amount of cryptocurrency. This is a standard amount, and over time the reward gets smaller and smaller. For many cryptocurrencies, this is the only way new coins are made.

## Hashing
Hashing a message means doing a math problem using the message to get an answer that can only be found using that message.

### Think of it like this
A hash is like a fingerprint. Everybody has one, and everyone's is different. If you see a person, it is really easy to make a copy of their fingerprint (just have them press their finger on something). But if you see a fingerprint, it is impossible to create a copy of the person whose fingerprint it is. 

### Why is hashing important?
Each block has a **hash** associated with it. This hash is a unique string of letters and numbers, (like A32DF9E43MSSN31F5, for example). A hash is calculated based on a piece of data; in this case, the previous block in the blockchain (previous page in the notebook). [not sure how else to rewrod this, to get the hash for the current block you use the hash for the previous block, etc. which leads you to an immutable chain because changing any hash will cause a cascading effect for the rest of the newer blocks] ---> To create the hash for a particular block, you take the content of the previous block, the hash of that content, and some other small pieces of information(like timestamp and software version), and run a math problem on it which turns all that data into a unique string of letters and numbers, known as a hash. [reworded; better?] ---> This hash is unique, and can only be gotten by using the hashing algorithm on the data that resulted in the hash. Changing any one letter or number of the original data will result in a completely new hash. Because new hashes are calculated partly based on previous hashes, [what wasn't techinically true, the bit about changing hashes? due to collisions?  I dunno if it's important to talk about hash collisions] ---> it's very difficult to change a previous hash and trick people into thinking it's legitimate, because none of the hashes after it would match up properly.

## Proof of Work
Proof of Work is a system used to verify transactions.  When transactions are bundled together in a block, the miners' computers do complex math problems to verify that the block is legitimate. The miners need to do complex math problems(work) in order to verify(prove) the transactions and block are legitimate. A large amount of electricity required to mine and do the math to keep the blockchain legitimate and secure.

## Proof of Stake
Proof of Stake is a way to verify the transactions that doesn't rely on the miners doing the math problems and consuming lots of electricity.  Instead of a race to create the next block in the blockchain, in Proof of Stake the creator of the next block is partially determined by the wealth of stakers.  For example, if I'm staking 900 units of my cryptocurrency, and you're staking 100 units of yours, there may be a 90% chance that I'll be the creator of the next block.  The actual algorithm is more complex and has more randomness, but this serves fine as an example.  With Proof of Stake, accounts that choose to stake will not be able to spend their locked up cryptocurrency, but may have other incentives(such as a constant rate of return) for staking. The cryptocurrency [Ethereum](https://ethereum.org) is planning to do a hard fork to Proof of Stake in the future.
