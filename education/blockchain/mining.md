# Mining
Mining is how new transactions get added to a blockchain. Something has to be done in order to add transactions to the chain, and depending on how the chain is set up, there are a few different ways this can happen.

#### Think of it like this
In order to make sure that transactions are secure, somebody has to do a little bit of extra work before adding a transaction to the chain.

## How does it work?
Well, it's a little complicated to explain the specifics, so here's a simplified version. For the blockchain to work, someone needs to be writing all the transactions down, and that's where miners come in. The miners have computers that do very difficult and complex math problems that take a long time to solve. They all attempt the same problem at the same time; when one of the miner's computers solves the problem, the rest of the miners verify it, and a block of transactions is added to the blockchain. Because mining takes a lot of computational power and electricity, it costs money to do. To reward them, miners get to add a transaction onto the block they solve, giving themselves a certain amount of cryptocurrency. This is a standard amount, and over time the reward gets smaller and smaller. For many cryptocurrencies, this is the only way new cryptocurrencies get introduced.

## Hashing
Hashing a message means doing a math problem using the message to get an answer that can only be found using that message.

#### Think of it like this
A hash is like a fingerprint. Everybody has one, and everyone's is different. If you see a person, it is really easy to make a copy of their fingerprint (just have them press their finger on something). But if you see a fingerprint, it is impossible to create a copy of the person whose fingerprint it is. 

#### Why is hashing important?
Each block has a **hash** associated with it. This hash is a unique, jumbled up string of letters and numbers, like A32DF9E43MSSN31F5, for example. A hash is created based on a message, in this case, the previous block in the blockchain(previous page in the notebook). To get the hash, you take the content of the previous block, the hash of that content, and some other small pieces of information, and run a math problem on it which turns it into the jumbled string of letters and numbers, known as a hash. This hash is unique, and can be turned back into the original message with another math problem. Changing any one letter of the original problem will result in a completely new hash. Because new hashes are calculated partly based on previous hashes, it's impossible to change a previous hash, because none of the hashes after it would match up properly.

## Consensus Algorithms
Consensus is the ability for a group of people to come together to a conclusion of the truth. An algorithm is a process to be followed to solve a problem. Combined, we have the process that people use to figure out the true state of the blockchain.

### Proof of Work (PoW)
Proof of work was the first method used to verify transactions. When transactions are bundled together in a block, the miners' computers do complex math problems to verify that the block is legitimate. The miners need to do complex math problems (work) in order to verify (prove) the transactions and block are legitimate. A large amount of electricity is required to mine and do the math to keep the blockchain legitimate and secure.

### Proof of Stake (PoS)
Proof of Stake is a solution that was created to solve the issue of heavy electricity usage by the Proof of Work algorithm. Instead of solving difficult math problems, Proof of Stake allows anyone (regardless of computer power) to participate in securing the network. In order to participate, people can "stake" an amount of their Cryptocurrency, which is used as collateral. Participants wager these funds in an expectation to earn more of the Cryptocurrency as a reward for their participation. The amount of reward they receieve is equal to the amount of Cryptocurrency they are risking in compared to the rest of the network (the more you wager, the more you earn).

#### Think of it like this
If Alice is staking 900 units of her cryptocurrency, and Bob is staking 100 units his, there may be a 90% chance that Alice will be the creator of the next block. The actual algorithm is more complex and has more randomness, but this serves fine as an example. With Proof of Stake, participants that choose to stake will not be able to spend their locked up cryptocurrency, but will receieve interest on their funds to compensate.

### Delegated Proof of Stake (DPoS)
Delegated Proof of Stake is an alternative version of Proof of Stake that is being used by many Cryptocurrencies to avoid using Proof of Work while real Proof of Stake models are being developed. In this model, holders of the Cryptocurrency are allowed to vote for a certain number of "delegates" that are responsible for processing transactions. The larger the amount of Cryptocurrency you hold, the more votes you have for who those delegates are. This consensus algorithm is considered to be flawed in the sense that it sacrifices decentralization (there are typically only a few delegates that hold a lot of power), for the ability to handle more transactions per second. This brings into question the security of these blockchains.
