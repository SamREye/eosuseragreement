# EOS User Agreement

# Foreword to the EOS User Agreement ("EUA")

## Purpose

This document was written by EOS New York for the benefit of the community and is a result of our participation in the community-driven development of EOS governance over the past year. In order to be more sensitive to the many different ways the word "constitution" can be perceived across cultures and languages we have shifted the title of this document to the EOS User Agreement. This document is an open-source template and EOS New York will not directly submit it for referendum. It is up to the community to decide if they believe this Agreement is a good foundation on which to build the ways we make collective decisions and direct the growth of the EOS Mainnet. In short, you should feel empowered to take this document and change it, amend it, propose it, or otherwise mold it to fit what you believe is best.

## Principles

The design principles for this document:

* Items are enforceable.
* Establishes a framework of “governing documents” so that amendment of the EOS governance can be agile.
* Defines roles and responsibilities of various user types.
* Establishes the foundation of a dispute resolution framework and empowers individuals to self-govern disputes.
* Establishes the uses of BP powers through `eosio.prod`.

# [Proposed] EOS User Agreement

## Title

We, the Members of the EOS Community, establish this document as the **EOS User Agreement** ("EUA").

## Definitions

* **Account**: An EOS account is a human-readable name that is stored on the blockchain. It can be owned through authorization by an individual or group of individuals depending on permissions configuration. An account is required to transfer or push any valid transaction to the blockchain.
* **Block Producer**: Block Producers are users who have called `regproduce` and receive income from `eosio.vpay`.
* **Call**: To submit an action to the EOS Blockchain `chain_id`
* **Chain ID**: `chain_id` — aca376f206b8fc25a6ed44dbdc66547c36c6c33e3a119ffbeaef943642f0e906
* **EOS User Agreement**: This document (EUA)
* **Governing Documents**: The EUA, **regproducer**, **regarb**, **regforum**, are considered governing documents.
* **Network Funds**: Network Funds are accounts that hold property which is subject to distributed ownership amongst the Users and has no single User owner. Network fund accounts are as follows: `eosio.names`, `eosio.ramfee`, `eosio.saving`.
* **On-Chain**: On-chain means any transaction, smart contract, or Ricardian contract which is located within a block that has been deemed irreversible and appended to the EOS blockchain `chain_id`.
* **Ownership**: Ownership is defined as direct or indirect access to an EOS account through one or more permissions or authorizations. Ownership may be shared between users and vary in weight.
* **Permissions**: Permissions are arbitrary names used to define the requirements for a transaction sent on behalf of that permission. Permissions can be assigned for authority over specific contract actions by “linking authorization” or `linkauth`.
* **Property**: Any object on-chain `chain_id` that requires a private key in order to directly manipulate, alter, transfer, influence, or otherwise effect.
* **Referendum**: User Referendum is the process by which token-holder opinion is solicited on-chain. Any user-referendum indicating a desired action or inaction may only be enacted, removed, or otherwise put into effect in any way, by at least 15 out of 21 duly elected Block Producers.
* **User**: A User is any person or organization of persons who maintain at least one of the following: (i) ownership of an EOS account, or (ii) property connected to an EOS account.

## Article I — Distributed Jurisdiction
All records and actions on the EOS blockchain `chain_id` are recorded permanently. Due to the distributed nature of blockchain, the EOS blockchain `chain_id` is not seated in any particular geographical jurisdiction. The EUA forms society which is to be governed by and construed under the rules contained herein. The said rules, as established herein, do not impose new laws or repeal existing laws of any geographical jurisdictions to which the Members may be subject.

## Article II — User Types
Users who call `**regproduce**` agree to, and are bound by, the ***regproducer*** terms.
Users who call `**regarb**` agree to, and are bound by, the ***regarb*** terms.
Users who call `**regforum**` agree to, and are bound by, the ***regforum*** terms.

## Article III — Consent of the EUA
All Users consent to these terms, definitions and standards. `chain_id` string is included in the signature of every valid transaction signifying consent.

## Article IV — Governing Documents
The governing documents are documents that define or compose the governance structure and rules of the EOS blockchain `chain_id`. Governing documents include only the following: EUA, **regproducer**, **regarb**, **regforum**. Governing documents may be modified only by User Referendum as prescribed in Article V.

## Article V — User Referendum
User Referenda must be submitted on-chain either in full text or as a hash of the referendum text. A User Referendum is considered approved for execution once there is at least 15% of issued tokens have registered a vote for the associated referendum; ‘yay’ staked tokens must exceed the number of ‘nay’ staked tokens by a threshold of no less than a 10% difference of total percentage of registered votes for the motion to be held. This threshold must be met and remain above the minimum requirements for a period of at least 30 consecutive days within a 120-day period. Should a User Referendum not be approved for execution within the 120-day period, it is considered expired. The 120-day period starts when the transaction which includes the referendum question is appended to the blockchain. EOS tokens issued during the 120-period are counted toward the total issued amount calculation.

## Article VI — Native Unit of Value
The native unit of value on EOS `chain_id` shall be the EOS token as defined and created by the `eosio.token` smart contract.

## Article VII — Maintaining the EOS blockchain
Block Producers who have agreed to **regproducer** will maintain the active blockchain. Furthermore, they shall participate in testing, review, and implementation of all changes to existing features, all optimizations, and all upgrades: present and future.

## Article VIII — Network Funds
Altering the state of any tokens contained within network fund accounts requires User Referendum, as per Article V. Altering any pre-existing code that directly or indirectly governs the allocation, fulfillment, or distribution of any network funds also requires User Referendum, as per Article V.

## Article IX — Dispute Resolution
Any on-chain provision included in any on-chain transaction, smart contract, or Ricardian Contract that results in controversy between parties to such a provision, or the refusal by any party to such a provision to perform the whole or any part thereof, or any controversy arising out of any other type of on-chain agreement between parties, shall fall within jursdiction of duly appointed arbitrator(s). If such a provision names or appoints arbitrator(s) registered through **regforum** or **regarb**, such method shall be followed. The application of either party to the controversy to the duly named **regforum** or **regarb** in such an on-chain provision is valid and enforceable, and **regforum** or **regarb** will act to resolve the controversy with full binding force and effect. Where agreed upon, users will submit to arbitration an existing controversy arising out of an on-chain transaction, smart contract, or Ricardian contract and will be administered by an arbitrator or arbitrators registered through **regforum** or **regarb**. The enforcement of any valid arbitral award relies solely on the parties to the dispute to execute.

## Article X — Freedom of Account Creation
Any person is free to create an EOS Account. Block Producers may never affect an EOS User Account unless the account owner has explicitly requested it, prescribing the exact actions to be taken, and having proven their ownership of the account. Block Producers may collectively charge a fee for this actions taken, which is to be deposited into `eosio.vpay`.

## Article XI — No Fiduciary
No User shall have a fiduciary purpose to support the value of the EOS token. No User can authorize anyone to hold assets, borrow, speak, contract on behalf of other EOS Users or the blockchain `chain_id` collectively. This blockchain shall have no owners, managers, or fiduciaries.

## Article XII — Personal Security
All items pertaining to personal account security, including but not limited to the safekeeping of private keys, is solely the responsibility of the User to secure. No Block Producer is liable for any EOS Account protection.

## Article XIII — Freedom of Association and Contract
The EUA grants freedom of contract based on agreement and free choice to all Users. No part of this Agreement shall impair, interfere, or infringe upon the mutually agreed upon contracts between Users.

## Article XIV — Inflation.
Inflation is set at 1% per annum which is to be allocated to Block Producers for services provided to the EOS Blockchain `chain_id`.
