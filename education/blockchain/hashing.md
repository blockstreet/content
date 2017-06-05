# Hashing
You can think of a hash as a fingerprint. Everything on a computer has its own fingerprint, so if two things have the same hash, you know that they are copies of each other. This is really useful because if you want to make sure everyone's version of the blockchain is correct, you can compare the hash or "fingerprint" to make sure they match.

## Specifics
The idea behind hashing is that you want to turn a complex piece of data (input) into a simple one (output), like a number. The way we make this change is called a "hash function". You want the simple output to be the same everytime when repeatedly putting in the same complex input data. For use in a blockchain, the hashing function needs to never take in two different inputs and produce the same output. This is called a "collision". We also want to make it impossible to figure out the input of a hash function based on it's output.

### Analogy
Imagine you have a new deck of cards. You write a step by step procedure for shuffling them. The end result is a 'mixed up' deck of cards. If you followed the same procedure for every new deck of cards you would get the same result.
A hash function is like shuffling a deck of cards except the input is whatever you are hashing, whether that be letters, words or numbers.
