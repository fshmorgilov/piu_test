# PIU task

## Task scope

1. Get familiar with PIU and Pike ecosystem
2. Investigate technology stack behind the <https://piu.pike.finance/>
3. Make a guess and instight on the resource plan

## Tech stack

### Web stack

#### Javascript general frameworks

1. ReactJS
2. Next.js

#### Webserver & website backend

1. Next.js
2. Typescript
3. NodeJS

#### Miscelaneous

1. Webpack
2. PWA

#### Performance

1. Priority hints

#### Analythics

1. Event traking - not detected - Recommended Amplitude
2. A/B testing - not detected - Recomended Growth Book
3. Web visor - not detected  

#### Security

1. HSTS

#### Web3 Wallets

1. Metamask React SDK
2. Wallet connect React SDK
3. Rabby wallet React SDK

### Backend

#### Backend tech stack

1. Javascript
2. NodeJS
3. Typescript
4. Prisma for database
5. Express for web requests and DI

### Chain

#### Blockchain networks

+ Base - supports Solidity and Clarity
+ Arbitrium - supports Solidity, Rust, C, C++
+ Optimism - supports Solidity
+ Ethereum - Support Solidity

Considering the highlighted networks supported for crowdloan campaign I believe Solidity language as the primary smart contract language.

## Scope

1 pager website for crowdloan and allocation campaign

## Frontend

### Lamding page

+ Intro Video
+ Header
+ Connnect wallet
+ Connect Discord
+ Various links: Pike link, PIU Blog, More - Gitlook, FAQ, Changelog, Discord, Twitter

### Allocation

+ Token Allocation
+ PIU claim
+ PIU claim flow
+ PIU in wallet
+ Get PIU integration with UNI

### Breakdown tab

+ Cumulative $PIU from protocol activities
+ Supply
+ Borrow
+ Roles in discord

### Roles

+ Discord integration
+ Rules
+ Allocatrion
+ Status

### Tier ranking

+ Static content

### Presale

+ Current tier discplay
+ PIU burn action
+ Network select

### Linked accounts

+ Discord
+ Base /Solana wallet

### How it works

+ Static content - table
+ Q&A dropdowns

## Backend

### Backend services

1. Integration with discord
2. Service for tier and allocation calculation based on the discord role for a user.

## Chain

### Smart contract for token

Methods:

1. Burn - burn x PIU to participate in the crownload campaign
2. Claim - claim allocated PIU tokens for the specified account

This includes updating contract on chain. Here there is an assumption that token contract has been already created according to ERC-20 specification, contract base contract has been already deployed.

## Resources required

Considering a team already has a dedicated designer, various team compositions are available to perform the specified taks. This team compositions may include outsourcing developers/outstaffing (like ousourcing HTML/CSS development to better utilize the capacity of the Senior Frontend developer) to optimise costs and balance the load between roles.

### Resource required - option 1

1. Senior Frontend React develop with experience in web3 development, NodeJS development for web server.
2. Senior QA - manual, with experience testing web3 applications
3. Senior/Middle Smart contract developer with experience build on Solidity and smart concract deployment

### Resource required - option 2

1. Senior Frontend React develop with experience in web3 development.
2. Backend developer, NodeJS stack
3. Senior QA - manual, with experience testing web3 applications
4. Senior/Middle Smart contract developer with experience build on Solidity and smart concract deployment

### Resources required - option 3

1. Senior Frontend React develop with experience in web3 development, NodeJS development for web servcer.
2. Senior Smart contract and backend developer - former backend developer specializing in smart contracts on Solidity
3. Senior QA - manual, with experience testing web3 applications

#### Conclusion

Considering that there is not a lot of smart contract development for crowdloan campaign I would suggest moving with option 3, as it requires less people and less communication noise. It will also help balance the load between the backend, smartcontract and frontend development.

#### Estimates

Provided with such team, I assume it would take between 3 weeks to 1 month of active developemtn and testing phase to deliver such project.
