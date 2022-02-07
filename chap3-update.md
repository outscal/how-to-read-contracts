# Updating smart contracts.
As we all know smart contracts are deployed on blockchain and are immutable by nature. Once you create them there is no way to alter them, effectively acting as an unbreakable contract among participants.

However,what if it is desirable to be able to modify them. Think of a traditional contract between two parties: if they both agreed to change it, they would be able to do so. On Ethereum, they may need to update a smart contract to fix a bug they found (which might even lead to a hacker stealing their funds!), to add additional features, or simply to change the rules enforced by it.

Here’s what you’d need to do to fix a bug in a contract you cannot upgrade:

Deploy a new version of the contract

Manually migrate all state from the old one contract to the new one (which can be very expensive in terms of gas fees!)

Update all contracts that interacted with the old contract to use the address of the new one

Reach out to all your users and convince them to start using the new deployment (and handle both contracts being used simultaneously, as users are slow to migrate).

I know this is very lengthy and irritating process but many companies are working around this problem. I hope a tool comes out soon enough to solve this. 
There exist one by [OpenZeppelin](https://docs.openzeppelin.com/). It;s the upgradable contract plugin but it has some limitations to it.


## Though we won’t use these features everyday, it’s very important to understand and analyze smart contracts before we can conduct transactions on them.
