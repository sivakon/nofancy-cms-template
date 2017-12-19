# Bitcoin

[Investments](https://www.notion.so/8879df50-6244-412c-86b0-ab48191aed1e)

[Bitcoin sources](https://www.notion.so/fc77d0d0-20b0-4cf5-829e-f39de3334ebb)

[Reading List](https://www.notion.so/f0e67c1a-fed3-4bea-82c1-eee186aebdbf)

[Blockchain Workshop](https://www.notion.so/3ea296d5-f228-443b-be99-5caa868a086d)

[Important terms](https://www.notion.so/868bfb5c-95ea-4e0e-b986-08343a724010)

[Hardcore](https://www.notion.so/297f4b4f-161c-46e4-97e7-06161a1d09b6)

[Mastering Bitcoin](https://www.notion.so/dc3b6ff9-e79c-4ec5-aee9-e798c87c1bc0)

[Invest Like the Best: Hash Power - Ep. 1 - Understanding Blockchains](undefined)

Society gives you money if you give the society what it wants. Police men were given money to keep us all safe. That money actually comes from people like. One police man cannot keep complete Japan safe

Bunch of people providing the network the scarce resource that it wants and then network in exchange is paying them for it. In Bitcoin, the scarce resource is security because bitcoin is actually a ledger of all the IO use that ever happened to Bitcoin network, so it creates a form of money. Keep track of all the debts, in which the bearer

You keep track of all the transactions (who owes whom) and that is all the money there is. Society (network of people) assign a face value to it. etc.. etc..

Miners in the bitcoin network creates security, in that they do a lot of cryptographic computational mathematics that is useful for nothing else other than locking down current set of transactions in the system sealing them and make them impossible to revoke. (1000Yen is a piece of paper but we as a society believe that it has a value)

Filecoin - Distributed AWS, miners get paid to provide storage to customers (they get paid in filecoin)

Solarcoin (solar energy is scarce, someone has to pay the provider) - Distributing solar energy and get paid in Solar coin. Community of people who have solar panels but they are not using them all the time, some have higher capacity/demand than others. So I put solar panels on my roof top, I use it for myself and on the basis of demand, I provide solar panels for other people (solar power in the network) in need in exchange for solar coin. In the same way, if I want to use solar power, I have to pay in solar coins and get solar power from the network. (You can do this anyway with Tesla - tesla keeps track of solar energy etc. (airbnb)) In this model, there is **no central authority and permission less.** 

Scarcity -> Two of us cannot have the same bill or same bank account. Digital protocols have a sense of scarcity. Blockchain allows us to build scarce protocols and keep track of scarce protocols. When keeping track of scarcity, we need a way(token - keeps track of scarcity) [like this bandwidth belongs to that person, this file storage belongs to that machine, like internet -> http protocol has a scarcity element to it. Internet is free but bandwidth is what is purchased, ISP purchases bandwidth on your behalf]. 

Blockchains are ways of creating and storing digital currencies. These currencies are means of exchange within these networks each of which is designed to incentivize some set of participants to create value, things like security, computing power, solar energy, file storage and an another set to consume that value using blockchain's native currency. (well designed markets to facilitate exchange)

# Technology

Miners provide digital scarcity (remember how banks create scarcity) and secure the bitcoin network. Decentralized networks rely on trust and security, We are used to banks watching over our money and making sure the people don't cheat the system (trying to spend the same money twice etc.)

Miners are bitcoin's answer to the problem. The system is designed so then in order to verify transactions being sent out by all bitcoin users, a special group of computers that we call miners will be forced to do a lot of time-consuming and costly computational work. The important thing is that we make computers prove to the rest of the network that they did the work to verify the transactions. Because of this system, global network agrees and reaches consensus every 10 minutes or so in bitcoin's case on the state of the ledger (who owns what amount of bitcoin as a result of recent transactions).

This method to reach consensus on the ledger is called 'proof of work'. This is bitcoin's way of removing the need for us to have a central authority.

## What miners do? Analogy

jav_rddt 

Imagine that every transaction that has been sent out is a puzzle piece. There are tons of them. The role of the miner is to find a way to fit all these pieces together into a picture that resembles a pre-agreed form of shape (rectangle). Doing this work takes time and hard for each miner to attempt to complete. If a miner figures out how to combine the pieces, it is really easy for every one else to simply look at the picture and verify that he has done it correctly with the pieces available. The time spent solving the puzzle is the work, and the end picture is the proof of work. 

Reasons why miners put their computers to solve this puzzle, because if they were first to solve the puzzle, they are paid in bitcoin. (small tax paid by bitcoin network to miners for their work to secure their money). Miners pay hundreds of millions of dollars each year to solve the puzzle and for the change to get rewarded in bitcoin.

## Central concept of cyrptography - Hashing

Hashing is like fingerprint. Fingerprint identifies human being. 

Hash identifies piece of data. SHA-256 

All the hashes blocks from genesis are chained till date, if you change one bit (from the chain of hashes), the whole thing breaks and it is completely different. Current block does not work, if you change one bit in the transaction

What is current block height?

Time consistency ensure?: chain hashes in every block such that the hash of current block is completely reliant on hash of the previous block and new elements within it.

Set of transactions(block) -> sha-256 code (current block)

All the previous blocks have a combined sha-256 

Every new set of transactions is strung together with all the transactions that have happened from genesis. 

Miners are the ones who create new blocks letting new trnsactions on the block. 

How is it possible without central authority to control the distribution of bitcoin? How is it possible to enforce scarcity in a decentralized way? In order to do this, bitcoin says that you have to make the problem hard and bitcoin is the first platform to do this correctly.

How do you make a problem hard in digital world? How do you make digital currency scarce?

## Example of a hard problem-

Miners are given 25 cents at the start. First to get 5 heads in a row is going to create a new block. Now you flip the coins enough to get the 5 heads in a row. there is a target time (bitcoin 10 minutes). 

Hash functions <-> a coin flip

SHA-256 has 256 bits, consider each bit is like a coin flip. Given a input, each of these bits have 50-50 change of 0 or 1. 

Every block has a set of transactions and block header. You hash the hash of the transactions and hash of block header to get hash of the block

Nonce field - this is a random 255 bits

Bitcoin is a protocol, bitcoin is a currency. A protocol is a set of rules.

You don't need anybody's permission to transact 

## Taken from reddit — add link later

The major problem I see with this school of thought is, are people using it or investing in it? I know that I'm just treating it like a financial instrument, I have money in it because its making me money, I use dollars when I want to buy things. I'm not trying to shit on your point, but my question is is it actually being used increasingly for daily activity? Because if most of this new money is investment money, then that's a bubble.

This is a great point, and why I’m skeptical. In my eyes, the majority of buyers seem to be holding for financial gain rather than actually using bitcoin as a currency. When bitcoin is more readily accessible for actually purchasing goods and seems to be used like any other currency I’ll lose some of my skepticism.