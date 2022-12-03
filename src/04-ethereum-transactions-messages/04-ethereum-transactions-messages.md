# Ethereum transactions and messages

In this chapter, we will introduce Ethereum transactions and messages, and explain their role and significance in the Ethereum ecosystem. We will also discuss the structure and components of transactions and messages, and the fees and limitations that apply to them.

## What are Ethereum transactions and messages?

Ethereum transactions and messages are the fundamental building blocks of the Ethereum network, and are used to transfer value, interact with smart contracts, and execute functions on the Ethereum Virtual Machine (EVM).

A transaction is a message that is sent from an Ethereum account to another account, or to a smart contract. It contains the following information:

- The sender and recipient addresses.
- The amount of Ether to be transferred.
- The data payload, which can be used to call a function on a smart contract or to pass data to it.
- The transaction nonce, which is used to prevent transaction replay attacks.
- The transaction fee, which is paid to the miner who includes the transaction in a block.

A message is a message that is sent from a smart contract to another account or smart contract. It contains the following information:

- The sender and recipient addresses.
- The data payload, which can be used to call a function on a smart contract or to pass data to it.

## Structure of Ethereum transactions and messages

Ethereum transactions and messages have the following structure:

- Header: This is the first part of the transaction or message, and contains the metadata and signature information. It includes the following fields:
  - The transaction or message nonce, which is used to prevent transaction replay attacks.
  - The sender and recipient addresses.
  - The amount of Ether to be transferred.
  - The gas limit, which is the maximum amount of gas that can be used to execute the transaction or message.
  - The gas price, which is the amount of Ether that the sender is willing to pay per unit of gas.
  - The signature, which is the cryptographic signature of the sender, using the Ethereum signature algorithm (ECDSA).

- Body: This is the second part of the transaction or message, and contains the data payload and function parameters. It includes the following fields:
  - The data payload, which can be used to call a function on a smart contract or to pass data to it. The data payload is encoded using the Ethereum ABI (Application Binary Interface) encoding, which specifies the structure and types of the data.
  - The function parameters, which are the input values that are passed to the called function. The function parameters are encoded using the same encoding as the data payload.

- Footer: This is the third part of the transaction or message, and contains the checksum and other metadata. It includes the following fields:
  - The transaction or message hash, which is the cryptographic hash of the transaction or message, using the Ethereum hash algorithm (Keccak-256).
  - The transaction or message receipt, which is the record of the transaction or message execution, including the gas used, the logs emitted, and the return value.

## Fees and limitations for Ethereum transactions and messages

Ethereum transactions and messages are subject to fees and limitations, which are determined by the Ethereum protocol and the network conditions.

The transaction and message fees are paid in Ether, and are used to incentivize miners to include the transactions and messages in blocks, and to cover the cost of their execution. The transaction and message fees are calculated based on the gas limit and gas price, as follows:

- Gas limit: The gas limit is the maximum amount of gas that can be used to execute the transaction or message. This limit is set by the sender, and must be greater than or equal to the actual gas usage of the transaction or message. If the gas limit is exceeded, the transaction or message is reverted and the fees are not refunded.
- Gas price: The gas price is the amount of Ether that the sender is willing to pay per unit of gas. This price is set by the sender, and determines the priority and likelihood of the transaction or message being included in a block. Higher gas prices result in faster and more reliable inclusion, but also in higher fees.

In addition to the fees, Ethereum transactions and messages are also subject to the following limitations:

- Block gas limit: The block gas limit is the maximum amount of gas that can be used by all the transactions and messages in a block. This limit is set by the Ethereum protocol, and is adjusted dynamically based on the network conditions. If the block gas limit is exceeded, the transactions and messages that exceed the limit are reverted and the fees are not refunded.
- Transaction size: The transaction size is the total size of the transaction, in bytes. This size is limited by the Ethereum protocol, and is currently set to 2,000,000 bytes. Transactions that exceed this limit are rejected by the network and the fees are not refunded.

## Conclusion

In this chapter, we have introduced Ethereum transactions and messages, and explained their role and significance in the Ethereum ecosystem. We have also discussed the structure and components of transactions and messages, and the fees and limitations that apply to them. In the next chapters, we will explore the different types of transactions and messages in more detail, and discuss how they can be used to transfer value and interact with smart contracts on the Ethereum network.


