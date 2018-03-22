<h1>Introduction:</h1>
 
<h3>Purpose of this Document</h3>
 
This document seeks to provide an overview of the POA Block Explorer and to inform  stakeholders of its purpose and developmental roadmap. This project will improve upon current closed source solutions (like [Etherscan](https://etherscan.io)), which inhibit community development, are intolerant of sidechain/forks, and unscrupulously monetize through ads and storing visitor data without consent.
 
This document has been written to involve stakeholders by providing a clear statement on the project’s goals, its development status and the work required. Contents of this document may be subject to change, pending ongoing development.
 
<h3>Scope</h3>
 
This project will expand upon the pre-existing POA Block Explorer (https://explorer-sokol.poa.network/en) to develop a blockchain viewer that is superior to current solutions. As an open source platform, the POA Block Explorer will allow developers access to advanced features and enable blockchain transparency for both users and developers.
 
This document defines the qualities by which the POA Block Explorer will be assessed for completeness, accuracy to vision, and technical quality. It has been created as an open resource for stakeholders, developers, and the Ethereum development ecosystem.

 
<h3>Description of Work</h3>

<h5>Overview / Fundamental Components</h5>
This work will expand upon the pre-existing POA Block Explorer to create a platform that allows users full insight across all Ethereum sidechains/forks and to provide advanced development tools for the Ethereum ecosystem. The POA Block Explorer will feature several core elements:

<ul>
<li><strong>Universal Block Explorer</strong> for Ethereum and all sidechains/forks to view blocks, transactions, accounts, and balances. ERC token support will be provided for many EIPs.</li>
 
<li><strong>Developer Tooling</strong> provides smart contract verification and interaction of smart contracts similar to MyCrypto.com.</li>
 
<li><strong>Open Source Development</strong> unlocks the full potential of the Ethereum Development ecosystem to progress development of the POA Block Explorer</li>
 
<li><strong>Smart Contact Library</strong> grants developers full access to pre-existing smart contracts to fast-track development and allow quick porting of smart contracts across different chains</li>
 
<li><strong>Download Blockchain</strong> functionality gives developers complete access full transaction history and data export to support off chain development</li>
</ul>
 
<img src="https://poaexplorer.com/assets/img/comparison.png" alt="POA Block Explorer Comparison" />

This documentation will be maintained to reflect the quality and standards of current Ethereum project documentation.
This project prioritizes the community review procedures as defined by the EIP process. It will work closely under its guidance for input on key design choices.

Furthermore, this project is fully committed to a democratic philosophy of universal access and transparency. Its goal is to deliver the most complete block explorer with advanced utilities which can benefit the whole Ethereum development ecosystem.

<h3>Timeline</h3>
<table>
<tr><th></th><th>Codename</th><th>Date</th><th>Feature Set</th></tr>
<tr><td>1</td><td>Vienna</td><td>Q2, 2018</td><td>== Etherchain Light 
Features will include: Browse and view blocks, accounts, contracts and transactions including failed and pending transactions, displays calls in contracts and more
</td></tr>
<tr><td>2</td><td>Kuala Lumpur</td><td>Q3, 2018</td><td>== Etherscan
Features will include: Interaction with smart contracts, interaction with other ERC20 tokens, other networks and sidechain
</td></tr>
<tr><td>3</td><td>Paris</td><td>Q4, 2018</td><td>New tokens types (721, 725, etc). Support of Plasma, Polkadot</td></tr>
<tr><td>4</td><td>Toronto</td><td>Q1, 2019</td><td>Feature set defined by Eth community</td></tr>

</table>

<h2>Universal Block Explorer</h2>
 
<h3>Description</h3>
 
Ethereum is routinely forked; as a result, sidechains will become ubiquitous. However, sidechains become useless if they cannot be viewed. Current Ethereum block explorers (like Etherscan.com) lack the capacity to support sidechains. This project is designed to bridge this gap by providing universal access to Ethereum and all Ethereum sidechains and forks. Any blockchain using the same virtual machines as Ethereum, could be viewed through the POA Block Explorer. The result is a tool that allows users to access blocks, transactions, accounts, balances and tokens across all blockchains utilizing Ethereum Virtual Machines.
 
Furthermore, this project will provide expanded support for tokens other than the standard ERC20 type. The POA Block Explorer intends support for all Ethereum Improvement Proposals, to allow functionality with token standards such as ERC 721 (non-fungible goods) or ERC 725 (identity).
 
<h3>Current Status</h3>
 
This feature is 65% complete. Two more teams are being brought on within the next 30 days to assist in this progress. v1.0 Block Explorer will launch with universal support, to allow the searching and navigation of blocks, transactions, addresses across Ethereum and all Ethereum sidechains. We expect V1.0 to be ready in Q2, 2018.
 
Required Work Before v1.0 Release:
<ul>
<li>Refactor Workers</li>
<li>Database Optimization</li>
<li>Account page Transaction History</li>
<li>Add support for ERC20 tokens.</li>
</ul>
 
<h3>Dependencies</h3>

Development is ongoing, with completion of V1.0 aimed at late Spring.
 
<h2>Open Source Development</h2>
 
<h3>Description</h3>
 
As an open source project, the POA Block Explorer will become the definitive hub for block explorer development. Users will be able to issue pull requests and aid in the development of the POA Block Explorer by suggesting improvements. This project intends to provide a utility that will benefit the entire Ethereum community.
 
Current block explorers are closed source, which inhibits community participation. With current solutions like Etherscan.com, developers have no access to pre-existing code; as a result, the potential talent brought by the open source community is wasted.
 
<h3>Current Status</h3>
 
This project is already open source, with complete access through the [Github repository](https://github.com/poanetwork/poa-explorer).
 
<h3>Dependencies</h3>

Upon v1.0 release, the project will allow pull requests from the community to unlock open source development.
 
<h2>Smart Contract Library</h2>
 
<h3>Description</h3>
 
The project will allow developers to fully view smart contracts deployed on Ethereum and Ethereum forks. Instead of coding from scratch, developers could conveniently take from pre-existing solutions for time efficiency. The cross-chain capability would also allow developers to quickly port smart contracts deployed on one Ethereum chain to another. Together these functionalities will establish the POA Block Explorer as the definite repository for Ethereum smart contracts, a true “smart contract library”.
 
There are no current block explorers which feature full Ethereum/ Ethereum sidechain support. Furthermore, they lack open access for developers to view smart contracts.
 
<h3>Current Status</h3>
 
The smart contract library is currently not functional. It will be available after v2.0 in late Spring. v2.0 will include developer tools such as verifying and interacting with smart contracts.
 
<h3>Dependencies</h3>
 
The smart contract library is reliant on v2.0 of the explorer. v2.0 includes all developer features such as verifying and interacting with smart contracts across all Ethereum sidechains.

<ul>
<li>[Here is an example of verified contract on etherscan.](https://etherscan.io/address/0xc8fe4a2d14cb9027ef955d15e8bf811a6db0bf74#code)</li>
<li>[Here is an example of interacting with the smart contract on etherscan.](https://etherscan.io/address/0xc8fe4a2d14cb9027ef955d15e8bf811a6db0bf74#readContract)</li>
</ul>

<h2>Download Blockchains</h2>
 
<h3>Description</h3>
 
When developing a sidechain, the ability to work with a block explorer in a local environment with full transaction history and developer tools is crucial. This project will allow users to readily export blockchain data.
 
Current block explorers do not allow the option to download full transaction history.
 
<h3>Current Status</h3>
 
After the release of v1.0, the teams will tackle the task of data export to csv and other formats.
 
<h3>Dependencies</h3>
 
This feature entails the v1.0 release. Ethereum and all sidechains will be able to clone the repository and custom tune the RPC endpoint for their nodes, to provide the full capability for their users to interact with their blockchain and view full transaction history.
 
<h2>Appendix:</h2>
 
<h3>POA Block Explorer - Prior Work</h3>
 
All development can be viewed on the project Github. Work that has been completed includes:

<ul>
<li>View blocks</li>
<li>View pending transactions</li>
<li>View mined/validated transactions</li>
<li>View full transaction history</li>
<li>View Accounts</li>
<li>View Balances</li>
</ul>
 
There are currently 2 dedicated teams from separate companies ([Gaslight](https://teamgaslight.com/) and [Dockyard](https://dockyard.com/)) and a dedicated project manager (Andrew Cravenho).
 

<h3>POA Block Explorer - Known Limitations</h3>
 
The project will maintain a list of troubleshooting tasks to exhibit ongoing development.

The current block explorer will be redesigned. We must refactor the workers and database logic, add transaction history to the account pages, and provide ERC20 token support prior to V1.0 release. ERC721 and other token standards will be supported after v1.0 is completed.
 

<h3>POA Block Explorer -  Points of Reference</h3>
<ul>
<li>Requires <a href="http://erlang.org/doc/" target="_blank">Erlang/OTP 20.2+</a></li>
<li>Requires <a href="https://elixir-lang.org/" target="_blank">Elixir 1.5+</a></li>
<li>Requires <a href="https://www.postgresql.org/" target="_blank">Postgres 10.0</a></li>
</ul>
