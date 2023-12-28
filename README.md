**Notice**: 3 airdrops with 3 different smart contracts and 3 different merkle roots where created. To check if you're eligible for any of them open the merkle root file and search for your address.

# Guide [HOW TO CLAIM MANUALLY]

## 1) Open the MerkleDistributor smart contract on PolygonScan

IbexAirdrop1 contract:
https://polygonscan.com/address/0x9c7213207b5f8726164c96a76a4b9c0fbf984aba#writeContract

IbexAirdrop2 contract:
https://polygonscan.com/address/0x1c813cDd6dAecE2CB83C52F0798504e42816E9C5#writeContract

EthRefund contract: 
https://polygonscan.com/address/0x7ce2f634f0698ecdca051ef1dc4be96ef3d05a62#writeContract

## 2) Connect your wallet

## 3) Fill the claim form and send the transaction

In order to fill the form search for your address in the MerkleReadable file. As account, input your address. As index, amount and proof copy and past the text in the file.
Finally send the transaction (the transaction will revert if you have already claimed your airdrop).

# Example

Let's claim the EthRefund airdrop for the address 0x0010F663EEAF1f77B48a256992Fe2dbf0d8d8744.

First open the EthRefund file and search for the address.

This is the claim data:
```
    0x0010F663EEAF1f77B48a256992Fe2dbf0d8d8744: {
      index: 0,
      amount: 0x01180d9e0969,
      proof: [0x7ecc1be2a30e08db80e6712d04c3b4f5fe8e7a697641d4b9c9cda7cfbc690c14,0x1c4c92fb126fd636d83f47de6a0fb55b2ef771dae8d1a08ec0f7e56b74fb4c29,0xd83cf15666cd47a5e6791c5613680ffa201fdb397e8482ad3aa17bb24f549740,0x2bc485c934d2aa4dd9d93c891eba14b232622f60619afe4de419ecbf17cffecf,0x3dc4faa0a1c34da12b6492c76e763653af8950c8bc3ce4a9bcd5b61bb7717af2,0xda2e0d6e3eafb2352dfb22d1ca2f2ec00ed17091197f4b239c0c8319e8daedba,0x670106015d129e566239d203d6aec45ac07862f6f1468703399dd6f631db8538,0x7984673cf132fb55252185e4a8fa9870804fe0ff6378a997ff018638d36253df,0x5431e8bc21eaa4044dde31935bb4316ebb33ddd9f3df823f1038798a96b04ea2]
    },
```
Then open the EthRefund contract and connect the wallet.

Finally fill the form according to the claim data and send the transaction!
![image](https://github.com/Impermax-Finance/polyogn-airdrop-merkle-root/assets/48289911/1774accc-9e69-41c0-a0a2-e0050a10cef9)
