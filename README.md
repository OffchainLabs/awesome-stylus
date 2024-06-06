# Awesome Stylus
A curated list of Arbitrum Stylus code examples, libraries, projects and resources.

<img src="./Arbitrum_Stylus-Logomark.svg" width="128" height="128" />

- [Official Docs](https://docs.arbitrum.io/stylus/stylus-gentle-introduction) - Official docs on Stylus
- [Rust SDK](https://github.com/OffchainLabs/stylus-sdk-rs) - Rust SDK
- [Cargo Stylus](https://github.com/OffchainLabs/cargo-stylus) - CLI tool for compiling and deploying Stylus smart contracts
- [Discord](https://discord.gg/arbitrum) - Check out the #stylus channel in Arbitrum's Discord server
- [Telegram](https://t.me/arbitrum_stylus) - A dev focused chat for Stylus builders
- [Offchain Labs Twitter](https://twitter.com/OffchainLabs) - Follow along for Offchain Labs and Arbitrum news and info
- [Stylus Repo](https://github.com/OffchainLabs/stylus) - The repo hosting the core code

## Guides
- [A Gentle Introduction: Stylus](https://docs.arbitrum.io/stylus/stylus-gentle-introduction)
- [Quickstart (Rust, Stylus)](https://docs.arbitrum.io/stylus/stylus-quickstart)
- [How To Add a New Programming Language To Stylus](https://docs.arbitrum.io/stylus/how-tos/adding-support-for-new-languages)
- [How To Run a Local Dev Node With Stylus Support](https://docs.arbitrum.io/stylus/how-tos/local-stylus-dev-node)
- [Stylus Rust SDK: Feature Overview](https://docs.arbitrum.io/stylus/reference/rust-sdk-guide)

## Videos
- [Intro to Arbitrum Stylus: NFT Contracts in Rust | José Franco | Foss Asia Summit 2024 | 2024.04.08](https://www.youtube.com/watch?v=M31sqbb3f8I&t=107s)
- [Intro to Rust & Arbitrum Stylus | Chris Cordle | Foss Asia Summit 2024 | 2024.04.08](https://www.youtube.com/live/M31sqbb3f8I?si=0gYJZVm6KInd0sEy&t=107)
- [Intro to Arbitrum Stylus: Interactions Between Solidity and Rust | José Franco | ETHGlobal London 2024 | 2024.03.15](https://www.youtube.com/live/8xEkv5bRIjs?si=-QPJUZguT7a2c3T7&t=7140)
- [Onchain Chess in Rust with Arbitrum Stylus | Chris Cordle | ETH Denver 2024 | 2024.02.26](https://www.youtube.com/watch?v=EXFMRfTF83M)
- [Arbitrum Stylus | Mahsa Moosavi, Rachel Bousfield, Chris Cordle, Austin Marazza | Arbitrum Virtual Day | 2023.12.11](https://www.youtube.com/watch?v=dXiO6XQgIs0)
- [Arbitrum Smart Contracts in Rust | Raul Jordan | ETHGlobal Istanbul 2023 | 2023.11.23](https://www.youtube.com/watch?v=XIpxtXMCscg)
- [Rust smart contracts? Arbitrum Stylus Interview | Rachel Bousfield, Patrick Collins | Cyfrin Audits Interview | 2023.11.02](https://www.youtube.com/watch?v=UVLDP1jqEFM)
- [An Odyssey Into Arbitrum | Jose Franco | SmartCon 2023 | 2023.10.26](https://www.youtube.com/shorts/yOu0CvxhO4Y)
- [Arbitrum Stylus: Smart Contract Composability | Rachel Bousfield | Stanford Blockchain Club | 2023.10.16](https://www.youtube.com/watch?v=gP49H27JU04&t=4s)
- [Using AssemblyScript on Stylus | Jose Franco | Offchain Labs Dev Tutorials | 2023.09.28](https://www.youtube.com/watch?v=FdFvZeqeSBI)
- [Arbitrum Rust Smart Contracts for Solidity Devs | Rachel Bousfield | ETHGlobal NYC | 2023.09.26](https://www.youtube.com/watch?v=_Z27pN-U0N0&t=20s)
- [Building a Stylus Smart Contract Pt 1 | Rachel Bousfield | Offchain Labs Dev Tutorials | 2023.09.22](https://www.youtube.com/watch?v=DJjpPWuGKq0)
- [Building a Stylus Smart Contract Pt 2 | Rachel Bousfield | Offchain Labs Dev Tutorials | 2023.09.22](https://www.youtube.com/watch?v=HsuI1TOyMs4)
- [Getting Started with Arbitrum Stylus | Raul Jordan | Offchain Labs Dev Tutorials | 2023.09.12](https://www.youtube.com/watch?v=CF1hLTGnByM)
- [Arbitrum Stylus: Rust Smart Contracts on L2 | Raul Jordan | Rust x Ethereum Day (Paradigm) | 2023.09.11](https://www.youtube.com/watch?v=XjGbnvE-OTM)
- [Arbitrum Stylus | Rachel Bousfield | Arbitrum Day Paris | 2023.08.18](https://www.youtube.com/watch?v=Whefhca1Fmk)

## Tools
- [Stylus Playground](https://stylus-playground.vercel.app/) - An online playground for building, compiling and testing Stylus smart contracts
- [Zig Stylus](https://github.com/Stylish-Stylus/zig-stylus) - Zig SDK for Stylus smart contracts
- [stylus-toolkit](https://github.com/LimeChain/stylus-toolkit) - A toolkit of Stylus primitives and examples of their usage
- [Stylus Suite](https://github.com/tolgayayci/stylus-vscode-extension) - Manage your Stylus projects with this Vs Code extension. Call cargo stylus methods with simple user interface, use pre defined snippets, chat with Stylus GPT and many more

## Libraries
- [Inkmate](https://github.com/cygaar/inkmate) - Gas-efficient smart contracts written in Rust, including ERC20 and ERC721
- [Rustmate](https://github.com/cairoeth/rustmate) - Blazing fast, modern, and optimized Rust building blocks for smart contract development using Stylus
- [OpenStylus](https://github.com/Prabhat1308/OpenStylus) - Modular and gas-optimized smart contract libraries and frameworks for Stylus smart contract development

## Examples

:warning: **IMPORTANT**: Some of these examples were created using an older version of cargo-stylus (v0.1.x or v0.2.x), and might not be compatible with recent versions of cargo-stylus without making some modifications to the source code. Those examples are labelled as `[cs v0.1.x]` and `[cs v0.2.x]` in the list.

- ERC20 Examples
  - [Stylus Permit](https://github.com/prestwich/stylus-permit) `[cs v0.1.x]` - An ERC20 Permit example in Rust
  - [Stylusmate](https://github.com/DeVazzi/stylusmate) `[cs v0.1.x]` - An ERC20 with Ownable module in Rust
  - [Rustmate ERC20](https://github.com/cairoeth/rustmate/blob/main/src/tokens/erc20.rs) `[cs v0.1.x]` - An ERC20 + EIP-2612 implementation equivalent to Solmate
- ERC721 Examples
  - [https://github.com/cygaar/ERC721Stylus/ (Rust)](https://github.com/cygaar/ERC721Stylus/) `[cs v0.1.x]` 
  - [https://github.com/0xcacti/stylus_erc721 (Rust)](https://github.com/0xcacti/stylus_erc721) `[cs v0.1.x]` 
  - [https://github.com/gvladika/stylus-erc721 (Rust)](https://github.com/gvladika/stylus-erc721/tree/main) `[cs v0.1.x]`
  - [https://github.com/OffchainLabs/stylus-workshop-basic-nft (Rust)](https://github.com/OffchainLabs/stylus-workshop-basic-nft)
- [Uniswap V2 In Wasm](https://github.com/evmcheb/univ2-wasm) `[cs v0.1.x]` - A Uniswap v2 proof of concept implementation
- [Stylus workshop (Rust & Solidity)](https://github.com/OffchainLabs/stylus-workshop-rust-solidity) - An example of 3 contracts (two written in Rust, and one in Solidity) interacting with each other.
- [Stylus workshop (Update Proxy logic from Solidity to Rust)](https://github.com/OffchainLabs/stylus-workshop-proxy-update) - An example of a Proxy written in Solidity that updates its logic contract from an ERC-20 Solidity contract to an ERC-20 Rust contract.
- [Greeter tutorial](https://github.com/OffchainLabs/stylus-tutorials/tree/main/packages/greeter) - Example of Arbitrum's cross-chain message passing system
- [Zk-sunade](https://github.com/supernovahs/zk-sunade) `[cs v0.2.x]` - An optimized , handwritten implementation of Groth16 using Arbitrum Stylus
- [P256 Verification Using Arbitrum Stylus](https://github.com/jake-nyquist/stylus-p256-example) - Example of C code compiled to Stylus to verify an ECDSA signature using a standard P256 Curve
- [Keccak Looper](https://gist.github.com/cygaar/ee3cf1d1f98a57369717c9d91e076fd1) - A Rust contract that loops n times and hashes an input string repeatedly
- [Stylus Proxy](https://github.com/byteZorvin/stylus-proxy) `[cs v0.2.x]` - An example contract for implementing minimal proxy pattern in Stylus
- [Stylus BLST](https://github.com/rauljordan/stylus-blst) - A C based smart contract that verifies BLS signatures onchain
- [Stylus AssemblyScript Example](https://github.com/OffchainLabs/stylus-as-example) `[cs v0.2.x]` - Sieve of Erathosthenes implemented with AssemblyScript
- [RKFall NFT](https://github.com/yahgwai/rkfall-nft/) `[cs v0.1.x]` - A Rust based project that uses gravitational field computation for generating NFTs
- [Pausable Library in Rust](https://github.com/ggonzalez94/stylus-pausable) - A sample implementation of Pausable and Ownable in Rust
- [Stylus ERC4626](https://github.com/solidoracle/erc4626-rs) - A sample implementation of OpenZeppelin ERC4626 contract in Rust
- [stylus-benchmark](https://github.com/Daniel-K-Ivanov/stylus-benchmark) - A project benchmarking Stylus vs EVM implementations on their gas consumption
- [create2 tutorial](https://github.com/rollchad/stylus-create2): Deploy stylus contracts with `create2` and derive their addresses.

### How to make code created with an older version of cargo-stylus compatible with the latest cargo-stylus v0.3.0

#### From cargo-stylus v0.2.x to v0.3.x

When trying to use the latest version of `cargo stylus` on a project created first on cs v0.2.x you might run into this error:

```
missing import pay_for_memory_grow
```

To make the code compatible with the latest version, you might need to update the stylus-sdk version used to v0.5.0

#### From cargo-stylus v0.1.x to v0.3.x

When trying to use the latest version of `cargo stylus` on a project created first on cs v0.1.x you might run into this error:

```
error: no library targets found in package `your-package-name`
```

Here are some tips for making this code compatible with the latest version:

- Use `lib.rs` instead of `main.rs` for the main logic of your program
- Add also a `[lib]` target to your Cargo.toml file if you don't have one
- Update the stylus-sdk version used to v0.5.0
- Modify the function names from `camelCase` to `snake_case`
