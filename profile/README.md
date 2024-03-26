# Kubera
Kubera - a verifiable on-chain credit score system
Kubera is specifically designed to tackle the criteria selection for permissioned DeFi protocols. These types of protocols require users to meet certain checkpoints to be eligible for whitelisting. Kubera provides a trust minimized solution for these protocols to verify if a user meets their required threshold. Kubera utilizes zk proofs to ensure the integrity and inclusion of the indexed data.

There are 2 sides of Kubera- for users and for defi protocols

* For users, it allows them to update their scores and synchronize till the latest block as and when they see fit. The credit score of a user X can only be viewed by X and no one else. This is by design, since our contracts are written as to not reveal any data.
Generally, credit score range from 300-900. However, currently for Kubera we are using a very bare bone basic aggregation that calculates the amount outstanding by a user to be repaid to a lending protocol like Aave.
This can easily be extended to a real world formula which uses credit history, mix and utilization.

* Next, for the Defi protocol section- currently for the alpha stage we only allow trusted protocols to have access to our platform. Hence, protocols will have to get themselves whitelisted. Once they are, they can leverage Kubera to find if a certain user’s score is greater than their threshold.This also means that the protocol never finds out what the score of an user is; only if they are higher than the threshold.

