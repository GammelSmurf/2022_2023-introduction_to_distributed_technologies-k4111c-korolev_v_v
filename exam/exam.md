# Exam questions

## Turing completeness EVM, EVM interrupts

The Ethereum virtual machine is what makes it possible to execute smart contracts on the Ethereum protocol. 
These smart contracts are at the heart of decentralized applications, tokens, and many projects running on the Ethereum blockchain.

Functions of EVM:
1. Providing a runtime environment for smart contracts
2. Functioning as a decentralized computing unit
3. Tracking Status Changes

The EVM is a computing engine that facilitates the deployment and operation of smart contracts. 
Without the EVM, it would be impossible to run programs on the Ethereum protocol. 
Thus, the EVM is an important part of the Ethereum core architecture.

A Turing-complete machine can handle any computation, no matter how complex, provided it has enough time and resources.

The EVM is Turing complete because it can be used to perform computations of varying complexity. 
This is what makes Ethereum different from Bitcoin.
Bitcoin functions primarily as a “distributed ledger” that specifies the rules for transferring value. 
In addition to handling value transfers, Ethereum (via the EVM) allows smart contracts to be deployed. 
As a result, Ethereum is described as a "distributed state machine".

## The mechanism for staking tokens in various networks

**A consensus algorithm** is a mechanism by which users and programs can coordinate their actions in a distributed network. 
It ensures that all participants in the network agree on the current state of the data, even if some nodes fail. 
In other words, consensus helps maintain system resiliency.

### Differences between PoS and PoW:
Proof of Work blockchains use mining to add new blocks to the blockchain, while Proof of Stake networks produce and validate new blocks through staking. Staking involves validators who lock their coins in order to be able to be selected to create a block. Generally, participants who stake large amounts are more likely to be selected as the next block validator.
Staking allows you to create blocks without the use of specialized mining hardware, such as application-specific integrated circuits (ASICs). While mining requires a significant investment in hardware, staking involves direct investment in the cryptocurrency itself.
So instead of competing for the next block with processing power, PoS validators are selected based on the number of coins locked.

### Stimulus:
Staking coins or stake is what incentivizes validators to keep the network secure. If they do not comply with this condition, their funds may be at risk.

### Reward:
Most Proof of Stake chains have their own staking currency, and some chains use a two-token system to split reward payouts.
In practice, staking is simply the storage of funds in a special wallet that allows any user to perform various network functions in exchange for a reward. The mechanism also offers the possibility of adding funds to the staking pool.

A staking pool is a group of coin holders who pool resources to be more likely to qualify for block validation and rewards. They pool their resources and share the reward in proportion to their contributions to the pool.

Each blockchain network can use its own way of calculating staking rewards.
Considering many different factors:
1. Number of validator coins
2. Duration of the validator's share in staking
3. Total number of coins allocated for staking
4. Inflation rate
and other factors.

### Ethereum Casper
Casper is an update to the Ethereum network that involves switching the algorithm to Proof of Stake (PoS) (also known as Ethereum 2.0). Although the Ethereum project was launched in the summer of 2015 with a Proof of Work (PoW) blockchain, the developers planned a transition to a staking model in the long term. After the transition is completed, the Ethereum network will no longer need to be mined.

To date, two versions of the update have been jointly developed in the Ethereum ecosystem: Casper CBC and Casper FFG.
Initially, work on CBC focused on PoS protocols targeting public blockchains.
The original FFG proposal consisted of a hybrid system including both PoW and PoS, 
but this approach is still under discussion and eventually new proposals may replace it with pure PoS.

Except the Ethereum, the Solana, Terra and Cardano are among the biggest cryptocurrencies that use proof of stake.