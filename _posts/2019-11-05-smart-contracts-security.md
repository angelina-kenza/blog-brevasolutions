---
layout: post
title:  "Enterprise smart contracts: Security aspects"
author: stelios
tags: [blockchain, smart contracts, security]
categories: [Blockchain, Security, Smart contracts]
featured: true
description: "Smart contracts promise to complete Africa's leapfrog into Internet 3.0. This post provides an analysis to navigate the security aspects of deploying smart contracts for mission-critical processes."
image: assets/images/smart-contracts/chris-ried-ieic5Tq8YMk-unsplash.jpg
---

Smart contracts are revolutionizing whole industries
and promise optimize and automate decades of inefficient processes

Africa has already [leapfrogged][1] ahead of the rest of the world
into the mobile-first technological era

Smart contracts can enable another leapfrog into the [Internet of Agreements][2] era

Like with any brave new world,
there are some very serious caveats and security implications
that decision makers have to take into account

This post
goes beyond the marketing hype
to highlight some key concepts that everyone should be familiar with


# Let's look around us

![A small world](../assets/images/smart-contracts/blur-cartography-close-up-concept-408503.jpg)
> Photo by slon_dot_pics from Pexels

The world around us works because of contracts
because of agreements

You are reading this blog post on your phone or computer
because you purchased the device
I.e. there was an agreement between you and the shop owner
which was fulfilled once money and device changed hands

The device arrived in the shop owner's hands
b/c a cargo ship full of these devices docked at some port
The device making its way from the factory to the shop
meant that tens if not hundreds of contracts and agreements had to be drafgted, verified and honoured:
the factory to the wholesaler,
the factory to the shipping agent,
the shipping agent to the shipping company,
the shipping company to XYZ

The device is powered by electricity b/c you have a contract with the power company: pay on time, receive electricity.

The house you live in
you know it is yours b/c you acquired the land based on... well, you get where this is going!

Almost every interaction around us happens, have happened and will continue to happen
b/c there is an agreement, a contract, between two or more parties
written or unwritten
recognized by both
and enforceable by a "power that be" (state, police, courts,...)

The majority of these transactions
especially the ones with a small monetary value
happen without a problem possibly without us noticing

The higher the value involved in a transaction the more friction is involved
in completing it
For example purchasing real estate
clearing of shipping
almost any type of insurance

There is a large amount of paperwork to be filled in
and checks to be completed
To secure the interests of the parties involved
as well as comply with legal requirements

For example, in a real estate purchase
a contract is drafted describing the building/land in detail
sometimes this needs to be drafted by a notary who acts as a trusted third party
both parties sign
then the signed contract needs to be submitted to the relevant authority (e.g. land registry)
to transfer the title
Upon confirmation of the transfer of the title (in one direction) and the agreed monetary value (in the other direction)
is the transaction complete.

# How about some automation?

![Computer](../assets/images/smart-contracts/johannes-plenio-FZpCcPss9to-unsplash.jpg)
> Photo by Johannes Plenio on Unsplash

Something seemingly so simple as a title of ownership transfer
involves different trusted third parties, authorities and "process gates"
to minimise the possibility of mistakes or fraud

In the enterprise domain
e.g. shipping and logistics
the contracts and process gates that need to be fulfilled
are [even more complex][4] involving multiple parties and authorities

One answer to this complexity is the introduction of automation
Paper- and rule-based processes
have been digitized for many years now
automating steps and constantly removing friction from even the most complex transactional processes

One great example of simplification made possible by digitization
is [parametric insurance][9]
where all manual processing

However digitization of contracts in IT systems
introduces a critical weak point: centralization in one or a few data centers
This makes critical transactional processes vulnerable to cyber attacks
This was demonstrated in a spectacular way in 2017 with the [NotPetya malware][3]
crippling the international shipping company [Maersk][5]
 along with almost the [entire infrastructure of Ukraine][6]

# A new paradigm

![Blockchain](../assets/images/smart-contracts/launchpresso-h5iazR-wljU-unsplash.jpg)
> Photo by Launchpresso on Unsplash

Smart contracts are a new way to address the problem of digitization
without any central points of failure, built on top of blockchain.

Let's unpack this "heavy" definition into more understandable concepts

## Blockchain

At its core a blockchain is a distributed data storage
And by distributed we mean from a few computers in a data center to many thousands across the globe
Public blockchains allow any computer to connect and become part of them
Private blockchains allow only a preselected set

<div
    style="width: 480px; height: 360px; margin: 10px; position: relative;">
    <iframe allowfullscreen frameborder="0" style="width:480px; height:360px"
        src="https://www.lucidchart.com/documents/embeddedchart/b29b2c36-bc5a-4af7-89f5-651da8d74ca1"
        id="lRl62L5eteGn">
    </iframe>
</div>

This diagram shows
how a disparate collection of servers
* form a robust network through [peer-to-peer networking][12]
* can confirm and validate transactions originating from users.
These transactions belong to (and originate from) users because they are signed with the users' cryptographic keys

Through cryptography and game theory incentives blockchain nodes
which do not necessarily trust each
reach a consensus on what the true state of the world is

For a deeper technical analysis this [article][10] and this [article][11] are good starting points.

The important takeaway for our discussion is that at its core
**a blockchain is a distributed trust machine**
A way for any 2 people or systems on the planet to agree on the truth
without an intermediary

Law, contracts and agreements are underpinning trust in the real world.
Blockchain is now offering this underlying fabric for the digital world

## Smart contracts

The obvious question then is: how do we fully utilize this trust machine to replicate real world processes?
The answer is smart contracts.

A smart contract is a piece of code which
* belongs to (and is deployed by) a user on the blockchain network,
* can be called by (and can call) other smart contracts, and
* is executed by **all** of the nodes of the network

<div
    style="width: 480px; height: 360px; margin: 10px; position: relative;">
    <iframe allowfullscreen frameborder="0" style="width:480px; height:360px"
        src="https://www.lucidchart.com/documents/embeddedchart/d65697d0-4df3-4fb5-8de0-5f71f6c8e3ba" id="L9l6W1HWTkXY">
    </iframe>
</div>

This is an even more powerful concept
Blockchain provides the foundation for random participants to agree on the state of the world (e.g. `A belongs to X`)
Smart contracts provide the mechanism for anyone to verify **how and when** the state of the world changes (`if W happens, then
A belongs to Y`)
Immutably and at scale

# Security concerns


## Public vs private infrastructure

![Private area](../assets/images/smart-contracts/business-dirty-door-security-241028.jpg)
> Photo by Nguyen Nguyen from Pexels

## Private keys

![Keys, keys, keys!](../assets/images/smart-contracts/antique-close-up-equipment-hanging-615350.jpg)
> Photo by Skitterphoto from Pexels


## Contract logic



## Future-proofing


## Oracles

In the world of smart contracts the term *oracle*
identifies any trusted source of information  and events from the external world

In ancient Greece oracles were believed to be the [undisputable voice of the gods][7]
a ["golden source"][8] of information from the "world beyond"

Remember from the introduction that smart contracts
execute in a secure, isolated environment
they can be called by users (who identify themselves via their private keys)
as well as other smart contracts

for their logic to be useful to the real world
smart contracts need to react to real-world events
and get real-world information

For example
"is the ship docked in port?"
"has $X dollars landed in bank account Y?"
"what product model does serial number XYZ correspond to?"

This external stimuli results in the smart contract taking some action
and recording a side-effect in the blockchain for ever

However the finality of all smart contract actions
raises an important question
How trust-worthy is the oracle?
What if it gives the wrong information the moment I request it?

For example a property purchase smart contract depends on a banking oracle
to confirm that the funds have landed in the account
What if (by accident or malicious action) the banking oracle incorrectly reports that the money is there
when in fact it is not?
The contract will be triggered and the property title will be irrevocably transferred
when the money was not.

Depending on the situation and the domain there are various strategies to address
oracle security issues

* Owned oracle

* Consensus-based decision

* Cooling off period

* Legal framework

# Parting thought

Like space travel
opens vast new horizons
but take extreme preparation and diligence
once rocket takes off, one wants all systems to function perfectly



  [1]: https://www.worldbank.org/en/news/opinion/2017/10/11/africa-can-enjoy-leapfrog-development
  [2]: https://en.wikipedia.org/wiki/Smart_contract
  [3]: https://www.wired.com/story/notpetya-cyberattack-ukraine-russia-code-crashed-the-world/
  [4]: https://transporteca.co.uk/shipping-process/
  [5]: https://www.zdnet.com/article/ransomware-the-key-lesson-maersk-learned-from-battling-the-notpetya-attack/
  [6]: https://en.wikipedia.org/wiki/2017_cyberattacks_on_Ukraine
  [7]: https://en.wikipedia.org/wiki/Oracle
  [8]: https://whatis.techtarget.com/definition/golden-record
  [9]: https://en.wikipedia.org/wiki/Parametric_insurance
  [10]: https://blockchainhub.net/blockchain-intro/
  [11]: https://bitsonblocks.net/2015/09/09/gentle-introduction-blockchain-technology/
  [12]: https://en.wikipedia.org/wiki/Peer-to-peer