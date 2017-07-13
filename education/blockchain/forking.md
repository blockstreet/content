# Forking
Blockchains have protocols, or a set of rules they must follow to remain consistent. If no one followed any of the protocol, the whole system wouldn't work.

When a cryptocurrency decides to update their protocols, sometimes they become incompatible with previous rules. It may make a rule which limits the size of blocks on the blockchain, or increases the amount of transactions per second by changing something else.  If any of these changes are incompatible with the old protocol rules, a fork will happen. A fork is just like a "fork in the road": The cryptocurrency can continue along the same path(the original protocol) or it can take a new direction, by using the new protocol rules. There are accidental forks, which can be the result of updating the blockchain protocol with code that seems like it should work with the old protocol, but an unforseen bug causes incompatibility, creating a fork.  There are also hard forks, where the developers of a particular cryptocurrency know that a protocol update will cause incompatibility.

This seems like a problem: If the blockchain is updated with this new protocol, what happens with all the previous blockchain transactions? What if this new protocol isn't how I think this cryptocurrency should be? Does everyone automatically switch?


## Hard Forks

When a **hard fork** occurs, you end up with two parallel blockchains. One is the old chain, with the nodes following the original protocol.  The other is the new chain, with nodes following the new set of rules. Whichever chain ends up with more support becomes the "official". A hard fork happens because the new protocol changes are not backwards compatible, so any nodes supporting the original chain see the new blocks/transactions being mined as invalid. This can end up as a very messy process if there isn't a clear majority of users willing to switch to the forked blockchain. If all of the nodes and users don't switch to one fork or the other, the cryptocurrency ends up becoming duplicated, with users unable to create transactions across the forks.  In this case, whichever cryptocurrency fork has the majority userbase becomes the "original" or main currency.  This has happened with Ethereum, due to an exploit in a smart contract allowing a "hacker" to withdraw 70 million USD worth of Ethereum from the DAO. This caused a call for a hard fork, and Ethereum split into Ethereum(ETH) and Ethereum Classic(ETC), with the vast majority of users choosing to follow ETH. You can read more about this particular fork [here](https://www.cryptocompare.com/coins/guides/the-dao-the-hack-the-soft-fork-and-the-hard-fork/).

## Soft Forks
A soft fork is when the protocol is updated, but it is backwards compatible with the old protocols.  This is preferable to a hard fork, because it doesn't stop the original chain from validating blocks.



## Think of it like this
Take driving(**bitcoin**), for example. Our government has rules for how people should be driving; stop at stoplights, drive on the right side of the road, pull over for emergency vehicles, etc(**these are the current protocols**). If people did whatever they wanted, this would cause lots of accidents. In the US, we always drive on the right side of the road. Imagine a study came out that showed traffic flowed more efficiently and there were less accidents(**more transactions/improved security**) if everyone drove on the left side(**new protocol**) of the road instead. Several major states(**nodes/miners**) decide to enforce the rule that you must drive on the left side of the road. I can't just leave one of the left-driving states and drive on the left side of the road all over the country, because I would be breaking other states laws(**protocols**). Eventually, if the majority of states(**minors/nodes**) switch to left-driving(**new protocols**), it would become the standard for driving(**cryptocurrency**).


