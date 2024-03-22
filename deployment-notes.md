truffle migrate --reset --network sepolia

# Compiling your contracts...

> Compiling @openzeppelin\contracts\access\Ownable.sol
> Compiling @openzeppelin\contracts\token\ERC721\ERC721.sol
> Compiling @openzeppelin\contracts\token\ERC721\IERC721.sol
> Compiling @openzeppelin\contracts\token\ERC721\IERC721Receiver.sol
> Compiling @openzeppelin\contracts\token\ERC721\extensions\ERC721URIStorage.sol
> Compiling @openzeppelin\contracts\token\ERC721\extensions\IERC721Metadata.sol
> Compiling @openzeppelin\contracts\utils\Address.sol
> Compiling @openzeppelin\contracts\utils\Context.sol
> Compiling @openzeppelin\contracts\utils\Counters.sol
> Compiling @openzeppelin\contracts\utils\Strings.sol
> Compiling @openzeppelin\contracts\utils\introspection\ERC165.sol
> Compiling @openzeppelin\contracts\utils\introspection\IERC165.sol
> Compiling .\contracts\Migrations.sol
> Compiling .\contracts\NftMarket.sol
> Artifacts written to C:\projects\happycode\demo\nft-marketplace\public\contracts
> Compiled successfully using:

- solc: 0.8.13+commit.abaa5c0e.Emscripten.clang

# Migrations dry-run (simulation)

> Network name: 'sepolia-fork'
> Network id: 11155111
> Block gas limit: 30000000 (0x1c9c380)

# 1_initial_migration.js

Deploying 'Migrations'

---

> block number: 5539326
> block timestamp: 1711129675
> account: 0xd2347b50cE53fA3a5e9694f45cdbD1Cf63C83d6a
> balance: 1.724960195048149723
> gas used: 250212 (0x3d164)
> gas price: 20 gwei
> value sent: 0 ETH
> total cost: 0.00500424 ETH

---

> Total cost: 0.00500424 ETH

# 2_nftMarket_migration.js

Deploying 'NftMarket'

---

> block number: 5539328
> block timestamp: 1711129683
> account: 0xd2347b50cE53fA3a5e9694f45cdbD1Cf63C83d6a
> balance: 1.639339455048149723
> gas used: 4235124 (0x409f74)
> gas price: 20 gwei
> value sent: 0 ETH
> total cost: 0.08470248 ETH

---

> Total cost: 0.08470248 ETH

# Summary

> Total deployments: 2
> Final cost: 0.08970672 ETH

# Starting migrations...

> Network name: 'sepolia'
> Network id: 11155111
> Block gas limit: 30000000 (0x1c9c380)

# 1_initial_migration.js

Deploying 'Migrations'

---

> transaction hash: 0x310be9b2d141e2cd2e41062f45dcd5ea5fc2e524852aab038dae713815fb8f92
> Blocks: 1 Seconds: 10
> contract address: 0xB667B6cf69163dc2a8182C93FB5Df321B7BF1785
> block number: 5539334
> block timestamp: 1711129704
> account: 0xd2347b50cE53fA3a5e9694f45cdbD1Cf63C83d6a
> balance: 1.724960195048149723
> gas used: 250212 (0x3d164)
> gas price: 20 gwei
> value sent: 0 ETH
> total cost: 0.00500424 ETH

Pausing for 2 confirmations...

---

> confirmation number: 1 (block: 5539335)
> confirmation number: 2 (block: 5539336)
> Saving migration to chain.
> Saving artifacts

---

> Total cost: 0.00500424 ETH

# 2_nftMarket_migration.js

Deploying 'NftMarket'

---

> transaction hash: 0x2ea8e3534592ab3fd438428b55e5b67810cbe656d71b3332a4c1cb95fc7bba2b
> Blocks: 2 Seconds: 17
> contract address: 0xB2e615e7eBb29582172C5d70F2479feeA5CAfB51
> block number: 5539339
> block timestamp: 1711129776
> account: 0xd2347b50cE53fA3a5e9694f45cdbD1Cf63C83d6a
> balance: 1.639339455048149723
> gas used: 4235124 (0x409f74)
> gas price: 20 gwei
> value sent: 0 ETH
> total cost: 0.08470248 ETH

Pausing for 2 confirmations...

---

> confirmation number: 1 (block: 5539340)
> confirmation number: 2 (block: 5539341)
> Saving migration to chain.
> Saving artifacts

---

> Total cost: 0.08470248 ETH

# Summary

> Total deployments: 2
> Final cost: 0.08970672 ETH
