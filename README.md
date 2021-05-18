# HaiNFT

This NFT smart contract builds on the following interfaces -

IERC165 - declaring support of contract interfaces, which can then be queried by others (ERC165Checked)
IERC721Enumerable - enumeration extension
IERC721Metadata - defining ERC721 token metadata URI 

It also utilizes the following role controls -

PauserRole - allowing child contract to implement an emergency stop, triggered by an authorized account
MinterRole - access control to caller by minter only functions.
Ownable - providing a basic access control mechanism

All the contracts/interfaces are consolidated in one solidity file for easy nagivation. 
