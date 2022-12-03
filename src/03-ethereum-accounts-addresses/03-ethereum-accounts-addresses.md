# Ethereum accounts and addresses

In this chapter, we will introduce Ethereum accounts and addresses, and explain their role and significance in the Ethereum ecosystem. We will also discuss the differences between external and contract accounts, and the security measures that are used to protect them.

## What are Ethereum accounts and addresses?

Ethereum accounts are entities that can hold Ether, interact with other accounts and smart contracts, and execute transactions on the Ethereum network. An Ethereum account has the following main components:

- An address, which is a unique identifier that is used to identify the account on the Ethereum network.
- A private key, which is a secret value that is used to sign transactions and access the account.
- A balance, which is the amount of Ether that the account holds.
- A nonce, which is a counter that is incremented for each transaction sent from the account, and is used to prevent transaction replay attacks.

An Ethereum address is a public identifier that is derived from the account's public key, using the Ethereum address generation algorithm (EIP-55). An address is a hexadecimal string that starts with "0x", and has a length of 40 characters.

## External and contract accounts

There are two main types of Ethereum accounts: external accounts and contract accounts.

External accounts are accounts that are controlled by individuals or organizations, and can be used to send and receive Ether, interact with other accounts and smart contracts, and execute transactions. External accounts are typically created by users who want to participate in the Ethereum ecosystem, and can be managed using Ethereum wallets and client applications.

Contract accounts, also known as smart contracts, are accounts that are controlled by a contract code, and are executed by the Ethereum Virtual Machine (EVM) when they receive a transaction or a message. Contract accounts can be used to automate processes, enforce agreements, and interact with other contract accounts and external accounts.

## Security measures for Ethereum accounts

Ethereum accounts are secured using a combination of cryptographic and network-level measures. These measures include:

- Cryptographic signing: To create a transaction, an external account must sign it with their private key, using the Ethereum signature algorithm (ECDSA). This ensures that only the owner of the private key can create transactions from the corresponding account.

- Nonce value: The nonce value of an account is a counter that is incremented for each transaction sent from the account, and is used to prevent transaction replay attacks. In a transaction replay attack, an attacker attempts to resend a previously executed transaction, in order to double-spend the Ether or manipulate the contract state. The nonce value ensures that each transaction can be executed only once, and that it cannot be replayed by an attacker.

- Network security: Ethereum accounts are also protected by the security of the Ethereum network, which uses the proof-of-work (PoW) or proof-of-stake (PoS) consensus mechanism to prevent attacks and ensure the integrity and security of the blockchain.

In addition to these measures, users can also protect their Ethereum accounts by using strong and unique passwords, enabling two-factor authentication, and keeping their private keys in a secure and offline location, such as a hardware wallet.

## Conclusion

In this chapter, we have introduced Ethereum accounts and addresses, and discussed their role and significance in the Ethereum ecosystem. We have also explained the differences between external and contract accounts, and the security measures that are used to protect them. In the next chapters, we will explore the different types of Ethereum accounts in more detail, and discuss how they can be used to interact with the Ethereum network and with each other.

