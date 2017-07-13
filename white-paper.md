# LightStreams White Paper

## Executive Summary


## Problems for Authors using Online Digital Bookstores

Authors of digital books face the current problems with using online digital platforms for distributing their works.

### High sales fees 

The current high fees of online digital bookstores used by authors to sell their works mean that authors receive up to 50% less revenue than their potential. 

For example a book valued at $9.99 sold on Amazon, there are the following fees:

1. For a direct sale, an approximate 48% fee is charged, this comprises a 30% platform fee plus and an electronic delivery fee of $2.58.

2. For a subscription sale, an approximate 50% fee is charged. This calculation is based on the subscription fee structure, where the author receives $0.00496 per page read, with a max payout of $5.00 for a 1000 page book.

### Loss of attribution revenue

There have been a few high profile cases where creators of digital content have failed to recieve revenue due from certain online platforms that have published their works. Examples are:
- Facebook
- Spotify

### Lack of data provenance
Online bookstores control the ownership, custody and storage of customer and sales data. This means that authors have less information about the consumers of their content than the online delivery platform. 

Due to the lack of data, an opportunity is lost by authors to connect with their readers, to gain feedback, develop insightful new ideas, and access a new sales channel to realse early dafts to interested fans.

## Mission Statement

LightStreams mission is to create a peer to peer marketplace for online content: books, music, movies and more. Where production, distribution and exchange of content is owned by the creators and regulated by the community, such that creators and fans can connect and share in a low cost, fair and open marketplace.

## The Lightstream Token

The lightstream token (LST) is a blockchain token with the following capabilities:

1. Can be exchanged for accessing digital content.
2. Can be exchanged via a floating exchange rate for fiat or digital currency.
4. Indirectly used for voting on network decisions. Voting power is based upon number of tokens collected via sales over a fixed period.

The genesis block will specify the number of tokens and the account distribution based upon that outcome of a fundraising event. Upon the genesis block being published the number of tokens in circulation will remain fixed. 

## Blockchain Architecture

The Light Stream architecture is an Ethereum based blockchain network. It has the following features:

- Is a public network where any user can gain access and transmit transactions.
- Is an independant blockchain network that is ethereum compliant. 
- Uses Permissioned Blocks technology to achieve transaction level privacy and the sharing of digital content. This means that only certain accounts will be able to access specific information as the result of a sale of digital content. For example, the author of a digital book will be able to view certain details that have been authorised by the reader who bought their book, and the reader will only be able to view the digital content that they have bought.
- Is a high speed network designed for global scalability. A maximum throughput of 8,000 transactions per second and a maximum network latency of 2 secs.
- Uses a Tendermint consensus algorithm for achieving network consensus.

<p align="center">
<img src="/images/lightstreams-architecture.png">
<br>
<b>Lightstreams Architecture</b> 
</p>


## Sales Mechanism for Digital Content

The sale of digital content will be governed by a smart contract. The smart contract will use Permissoined Blocks technology that will control access to the digial content publishd by an author:

- By granting permission as a result of a direct sale between the author and reader.
- By granting permission based upon the reader being a member of a subscription based sales model.

### Direct Sales

An author will attach a version of their digital works to a direct sales contract and publish the contract at a specific LST price. The direct sales contract uses Permissioned Blocks technology to control access to the digital content. At any time the author can update the  price the version of their works. The buyer will pay the most recent LST price and will access to all digital versions attached to the contract. The author will be charge a 5% fee of the total price per book sold.

The procees of a direct sale is as follows:

### Subscription Sales

An author can opt to sell their content via a subsciption sales model. Using this model, an author will earn revenue based upon a normalised price per page accessed by the reader. To utilise this model, the author attaches their digital works to a smart contract that uses Permissioned Blocks technology to control access to each page of the book. The smart contract will only permit readers to access a page that are members of a subscription contract. 

Subscription contracts will be divided into subject categories. Readers will pay a monthly LST subsciption fee in order to gain access to unlimted content within the subject category controlled by the subscription contract. For any month the reader can decide to not pay the monthly subscription fee, upon which their membership to the subscription contract will be removed.

At the end of each month the total monies collected for the month per subject is distributed to the authors less a 5% Foundation Fee. The money will be divided and distributed by the ratio of pages accessed per book. If a book has more than 1000 pages, then the total number of pages for calculation purposes is capped to a 1000 pages. 

For example:

## Lightstream Marketplace

The lightstreams marketplace will give the ability for readers to search and browse for books available for sale. Readers will be able to search via book subject, author, popularity or promoted works. Upon selection of a book the reader can choose to view the content based upon a direct or subscription based purchase depending upon the author's sales model choice for the book. 

Just as any online bookstore, the marketplace will show free information to the reader to aid in order to aid their purchasing decision:

- book's font and back cover
- contents page
- index page if available
- A short blurb
- Reader reviews

A listing fee will be charged for publishing the book on the marketplace. The fee will cover the costs of reviewing uploaded content to the marketplace to ensure the quality of the marketplace is maintained.


## Lightstream Clients

## Network Consensus

Since the Lightstreams is a peer to peer network, consensus is required between nodes about the current state of the network. Standard Ethereum uses a Proof-of-Work (PoW)algorithm to achieve consensus, however PoW does not scale well, with transaction throughputs of ~10 transactions per second. Lightstream will instead use a Proof-of-Authority (PoA) algorithm where a set of "validator" - nodes that are explicitly allowed to create new blocks and secure the blockchain. Using a PoA algorithm such as Tendermint will allow for an order of magnitude increase in scalabilty ~10,000 transactions per second whilst also allowing for a governnace model for chain maintenance and keep the block issuers accountable.


Validators do not charge gas for validating transactions. In order to protect the network from malicious smart contracts with computationally expensive operations, validators only permit transactions to be added to blocks that a destination address for contracts that have been signed as Lightstream contracts. Any transaction to that publishes a smart contract that has not been signed by a valid lightstream account will be rejected. Valid accounts for signing Lightstream contracts will be specified on by the Lightstream Foundation via the lightstreams.io website.

## Governance

Authors with the highest number of sales above a certain threshold per year and per subject category will be invited to become network validators. Network validators have the responsibility to:

1. To inspect network transactions to ensure that they are valid, and then broadcast to the rest of the network.
2. Propose new resolutions to be voted by the community via smart contracts.
3. Propose and decide by majority vote on an arbitrator for resolving transaction disputes.

[1] http://andrewhy.de/amazons-markup-of-digital-delivery-to-indie-authors-is-129000/
[2] http://business.time.com/2013/12/03/heres-how-much-money-top-musicians-are-making-on-spotify/

https://www.quora.com/How-do-book-authors-get-paid-in-digital-unlimited-reading-platforms
https://www.writtenwordmedia.com/2016/05/24/amazon-kdp-kindle-unlimited/
https://taprun.com/examples/safari/
