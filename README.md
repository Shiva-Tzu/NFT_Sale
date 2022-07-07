# ScalableNFTSaleContract

Contract has not been audited. Use at your own risk.

This is a functioning and scalable NFT token contract. It comes with whitelist and public sale features.

I intend to upload a minting dApp that functions with this contract so that you have everything you need to launch your collection, no matter how big. 
In the meantime, here is a great resource that has just about everything you need: https://github.com/HashLips/hashlips_nft_minting_dapp

Here are the edits you need to make to get the public mint to work (You will need to do a lot more to get the whitelist mint to work, so you can either put in the 
time to figure that out or just hold tight for me to upload a mintind dApp within the next week or so): 

On line 133 of App.js in the src folder, replace contractmint with publicMint
This will call the public mint function in this smart contract.

You will also need to replace the abi.json file in /public/config/
To do this, compile the NFT.sol contract on remix and there will be an option to copy the abi. Once done, replace all the code in the abi.json file with the new abi.

Hashlips has a great ReadMe file in their repo so be sure to check that out for the rest of the info on how to get the thing to work.

If you appreciate this work and would like to send me some ETH, a starving programmer could always use contributions, here is my wallet address 0xBe1B4F4820F0925dAFB88cCa9398472e50c3cc2A
