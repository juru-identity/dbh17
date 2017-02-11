# Juru Core - DBH2017

## Table of Contents

- [What is Juru Core?](#what-is-juru-core)
- [Our Vision](#our-vision)
- [DBH2017 Use Case](#dbh2017-use-case)
- [Disclaimer](#disclaimer)

## What is Juru Core?

Juru Core is an open platform where you can securely store and manage your Identity and Reputation.

Today Juru Core is built on Hyperledger Fabric and BigChainDB, and runs on a permissioned private blockchain.
The contributing nodes are hosted by all major banks, which act as reputable gatekeeper.

It represents your identity and reputation using a smart contract, attributes can be added by the identity owner and are stored in hash form.
Attributes and endorsements are formed of field sets, merkle-root hashes are used to allow sharing and verification of partial data (such as date of birth within a driving license).
Sharing can be set up that allows you to share any kind of document / reputation with another Juru account (individual or company)
Sharing permissions are revocable and are considered current if not revoked.

An open API middle tier will allow for trusted third parties to connect their application and pull / push data to the core identity.

## Our Vision

Our official identifying documents are currently stored with various parties like banks, notaries and governments.  In today's fast-moving e-Commerce world, this fragmented proof of identity is no longer sufficient to cover the needs that facilitate trade: Trust and Reputation.  With Juru we provide Identity and Reputation in Juru Core, an open foundation consisting of European banks and governments.

A short introduction can be seen on https://www.youtube.com/watch?v=TpBH0lB94kk

## DBH2017 Use Case

For the Hackaton we are focussed on the creation of a new Individual inside Juru Core.
This will happen as follows :
- We will create a unique identifier based on the mother of the child, the time of birth and place of birth.
- The first Identifying Document is the Birth Certificate
- The gynecologist will be the initial owner of this Document
- He will transfer ownership of the certificate asset to the newborn child
- The child now has ownership of the asset, and the first action his timeline is a facilitate
- He can share the document with a third party
- The third party can see the document (and it's metadata)
- The newborn stops sharing the document
- The third party can no longer access the document

## Disclaimer

Unless required by applicable law or agreed to in writing, Licensor provides the Work (and each Contributor provides its Contributions) on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied, including, without limitation, any warranties or conditions of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A PARTICULAR PURPOSE. You are solely responsible for determining the appropriateness of using or redistributing the Work and assume any risks associated with Your exercise of permissions under this License.

It has not been exhaustively tested and should be treated as a prototype, not a production-ready application.
