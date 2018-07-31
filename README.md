# ADPC
Ethereum smart contract for Asymmetric Durable Payment Channel 

- One direction only, Sender to Receiver
- Only Sender deposits money to the channel by making token transfer to the channel's address
- No timeout required for Receiver-requested settlement
- Channel settles batches of payments without closing the channel. There is only one active batch is active at any time.
- Channel keeps reference to all previously closed batches.
