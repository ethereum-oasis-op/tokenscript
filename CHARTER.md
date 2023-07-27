# Technical Specification of TokenScript Working Group Charter

## Background

TokenScript operates as a dynamic framework, aiming to enhance the utility and interaction of digital tokens within the online realm. It fosters a paradigm where tokens transcend their traditional roles as mere assets. Instead, they evolve into intelligent interfaces for accessing and interacting with services across the web ecosystem.

In this evolved paradigm, users employ these enhanced tokens to access various online services. Instead of websites delivering user cookies, users provide token access, together with any integration enabled by the token, thereby transforming the Internet into a highly integrated, user-centric environment.

TokenScript comprises two integral components:

* TokenScript Engine, operating within the user's digital wallet, on the web, or via a browser plugin.
* TokenScript File, which is a comprehensive assembly of XML, HTML, and executable code in JavaScript or WASM, signed and issued by the relevant Token Issuer. It also instructs how websites provide and uses APIs to access token functions.

TokenScript Engine brings the power of token logic to third-party websites, allowing a seamless interaction between user tokens and the services these websites provide.

The TokenScript File structures and enhances the user experience of tokens within digital wallets and acts as a container and protection of user's data. It appends rules, data modules, transaction security measurements, secure computation methods, adding depth and functionality to the tokens. 

TokenScript files are verified and signed by the creator of the token smart contract or a trusted source, ensuring the secure import and verification of the files. This process assures that users only interact with authorized TokenScript from trusted sources.

In a broader context, TokenScript transcends the limitations of specific blockchain networks. Although initial developments focus on Ethereum tokens, TokenScript can adapt to other blockchains and even facilitate interactions across multiple blockchains. TokenScript is not a standard for tokens per se, but a standard for a dynamic layer of token interactions, enabling wallets, apps, and websites to interact with any token as efficiently as with an ERC token.

## Goals

The primary objectives of TokenScript standardization include:
* Developing standards for the TokenScript File, including its validation and the assertion of its authenticity, as well as the level of trust that can be placed in it. This standard forms the foundation supporting the following goals.
* Creating the runtime specification for TokenScript, outlining the specifications for browsers and future wallets to load, execute TokenScript, and communicate with the websites that utilize token functions.
* Establishing a standard for a web service deployment framework that enables a web service to offer token APIs based on token capabilities. This process permits a web service to learn a token's functions, acquire the necessary data and logic to serve the token to a website from the server-end, and allows for seamless interaction with token functions through traditional APIs.
* Implementing standards and methods for TokenScript protocols on data storage that ensure that only necessary information is shared during transactions or web interactions in order to increase privacy
* Establishing standards and methods for TokenScript protocols that ensure secure transactions. Users should have confidence in their expenditure and the benefits expected from the transaction. This includes standards for how transactions are created and prompted, aiming to absolve web2 websites from the obligation of securely creating transactions, and delegate that responsibility to the TokenScript engine, secured by the means described above.

## Project Scope
* Identify and document the most important and relevant use cases and business requirements with TokenScript for token issuers.
* Identify and define the business standard (like a set of business rules and/or interaction logics) for token issuers.
* Define a technical standard for TokenScript as required that meet both ecosystem and enterprise requirements, with a particular focus on interoperability between token issuers.
* Define and document the integration guidelines for token integrators.


## WG blockchains

To be updated


## WG Deliverables

To be updated.

## WG Budget
NA

## Constraints, Assumptions, Risks, and Dependencies

List any constraints, assumptions, risks and dependencies.

 
## Governance

The Governance Document is located [here](#).

**Approved by EEA Community Projects PGB , 25 July 2023**
