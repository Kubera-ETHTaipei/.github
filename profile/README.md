# Kubera
###  Verifiable on-chain credit score system
Kubera brings a paradigm shift with regards to **how users are whitelisted for Institutional DeFi Protocols**. Now, there is no need to trust any centralized provider for information regarding the credit worthiness of an user. Data on the blockchain is public and provably so. So why shouldn't we use that as a bsis for selection. <br/>
Although, this data is available to everyone, it is scattered and difficult to comprehend by a non technical user who would like to join a whitelist protocol. These types of protocols require users to meet certain checkpoints to be eligible for whitelisting. Kubera provides a **trust minimized solution** for these protocols to verify if a user meets their required threshold. Kubera utilizes zk proofs to ensure the integrity and inclusion of the indexed data. <br />
Examples of Institutional DeFi Protocols are:
* Aave Arc
* Fireblocks

There are 2 sides of Kubera- for users and for defi protocols

* USERS - it allows them to update their scores and synchronize till the latest block as and when they see fit. The credit score of a user X can only be viewed by X and no one else. This is by design, since our contracts are written as to not reveal any data.
Generally, credit score range from 300-900. However, currently for Kubera we are using a very bare bone basic aggregation that calculates the amount outstanding by a user to be repaid to a lending protocol like Aave.
This can easily be extended to a real world formula which uses credit history, mix and utilization.

* DEFI PROTOCOL - Currently for the alpha stage we only allow trusted protocols to have access to our platform. Hence, protocols will have to get themselves whitelisted. Once they are, they can leverage Kubera to find if a certain user’s score is greater than their threshold.This also means that the protocol never finds out what the score of an user is; only if they are higher than the threshold.

[Kubera](https://frontend-three-flax.vercel.app/)

[Presentation](https://pitch.com/v/kubera-snyix2)

[Demo Video](https://www.loom.com/share/ccb3125dc22e4e0fa0b45f6511ddf062?sid=87c86de9-8eda-4b67-ae58-4cd15d1cde46)

[High Level Architecture](https://excalidraw.com/#json=w8ty8iO-wzVatKMCx8N2H,g_pAD6upLwu7cIWg6Z6zRw)

![ARCHITECTURE](https://github.com/Kubera-ETHTaipei/.github/blob/main/Screenshot%202024-03-26%20122103.jpg)



