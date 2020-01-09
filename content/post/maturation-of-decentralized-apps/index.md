---
title: 'The Maturation of Decentralized Applications'
subtitle: ''
summary: A retrospective summary on the Internet's evolution and where we are headed.
authors:
- admin
tags:
- dapp
- dweb
- web3
- ethereum
categories:
- distributed computing
date: "2019-12-19T00:00:00Z"
lastmod: "2019-12-19T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
#image:
#  placement: 2
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
#  focal_point: ""
#  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

Having grown up during the birth of AOL, Google, Amazon, Facebook, etc., I have seen the Internet grow from a fringe technology to critical infrastructure for nearly all people and businesses.  Today, it is hard to imagine not having access to many of the services the Internet provides, but it wasn't so long ago that these companies didn't even exist.

The Internet and the applications that run on it has evolved quickly over the past three decades. When the Internet burst into the public's consciousness in the early 90's, few people really understood what it was and the things that would one day be able to be accomplished with it.  I myself recall getting home internet access and struggling to understand the difference between browsing America Online and going on the World Wide Web.  Even today, many people (young and old) still don't really understand the difference between the Web and the Internet.  What matters today, to most people, is **just using their apps while being online (connected) with other people**. 

You can see this most explicitly with how smart phones have supplanted our interaction with online services.  In the late 90's and eary 2000's the way you interacted online would be through your computer by logging into websites to access your accounts, do your shopping, or talk to people.  You can still do this today, but the norm has become interacting directly with these services through one's mobile phone.  If you make a post to Facebook from your phone, for example, the only involvement of the Web is the use of an HTTP API for the Facebook phone app to communicate to Facebook servers.  The Web itself has receded to the background and has simply become an enabling technology for the applications.

This evolution of the Internet and maturation of the applications running on it, can be thought of as two distinct generations. In the first generation you primarily have websites designed to work with web browsers on users' computers/laptops.  These applications had limited capabilities and were largely read-only. (i.e. They were dedicated to consuming information rather than producing it.) 

#### First Generation Internet Applications (1991 to early 2000's)

|Application(s)|Description|
|---|---|
|Lycos, Excite, Yahoo!, Google|Search Engines|
|Amazon (original bookstore)|Online shopping for books|
|GeoCities|Online community of static web pages|

The second generation was really brought on by the maturation of dynamic capabilities within the web browser using Javascript and related technologies (AJAX), the generation and editing of content by end users, and the rise of smart phones/tablets and the related app ecosystems.  

#### Second Generation Internet Applications (2000 to present)

|Application(s)|Description|
|---|---|
|Gmail|Dynamic web-based mail applicaton|
|Wikipedia|User edited and maintained online encyclopedia|
|Google Maps|Interactive mapping application (drag map)|
|Facebook, Twitter, LinkedIn, Instagram|Social Networks|

The downside of this second generation is that it has led to a siloed centralization of data (and in turn control) with a small number of companies.  Users today live within various *[walled gardens](https://en.wikipedia.org/wiki/Closed_platform)* and have to trust these companies with their data and hope that they will handle it responsibly.  Further, this centralization of control also results in a lack of competition due to the barrier to entry presented by the network effects of the incumbent services. (e.g. if everyone is already using Facebook it is hard to convince people to leave for another centralized social network)

This outcome is largely due to the convenience and simplicity in designing networked applications to only connect to one or only a few central points.  There is however an alternative way to design Internet applications in a decentralized manner.  In fact, there is another class of Internet applications missing from the above lists, but that existed during the same period.  They are peer-to-peer (P2P) applications. 

Many readers are familiar with the rise/fall of Napster for sharing music and the continued use of Bittorent for file distribution.  P2P applications have existed and continue to exist for some time now.  In the late 90's and early 2000's, P2P technology offered a vision of software running on the Internet that had no central point of control and could not be shutdown.  

This vision; however, did not fully materialize due to the economics of operating decentralized applications.  For example, if you operate a node on a decentralized network there is a non-trivial cost for the bandwidth and storage of that node.  How do you charge users who make use of this resource?  The inability to cover the costs of node operations and provide economic incentives to operate nodes has restricted the growth of decentralized networks and the applications running on top of them.  Nevertheless, this first generation of decentralized applications has continued to exist, albeit with volunteer effort and relatively illiquid credit based markets. (e.g. If you share a file you then have a credit to download a file, but this credit can not be converted to fiat currency)

Thus, decentralized applications languished as they were lacking a solution for the economic realities that must be addressed to achieve autonomous and trusted operation of a distributed network.  In 2008; however, Bitcoin introduced the world to an encrypted distributed ledger system, known generically as a blockchain.  The use of a secure distributed ledger, such as Bitcoin, provided a *solution to the [double-spend problem](https://en.wikipedia.org/wiki/Double-spending), thereby guaranteeing true digital asset ownership that could be trivially verified*.  This innovation of trusted and verifiable networks offers a range of new technological capabilities such as:  

- Performing large money transfers quickly and cheaply anywhere in the world 
- Cheap, decentralized, vendor independent file storage
- Automated insurance markets
- Digital asset and prediction markets 

The economic models of blockchains enable a new generation of peer-to-peer or decentralized applications to compete with centralized systems.  Further, by the very nature of decentralized systems not having central servers owned by a single entity, people are able to regain control over their data, which in turn increases the privacy of users.  

There are critics that bemoan the performance of the current implementations of blockchains and their related decentralized applications.  It's certainly true that the primary chains have experienced long confirmation times on occassions and the energy and space consumption is far from efficient.  With that said, already improved consensus mechanisms have been developed for some of the existing blockchains (and new blockchains have been and are currently being created) that will provide orders of magnitude improvements to on-chain performance.  (i.e. the technology will improve just as any technology does) 

Also, many people mistakenly assume that decentralized apps primarily run on a blockchain directly or require constant communication with the blockchain.  In reality, most applications will run off-chain, but use blockchains to finalize and secure important primary information.  This will allow them to achieve acceptable performance while enabling a range of new capabilties.  

#### Third Generation Internet Applications (2008 to present)

|Application(s)|Description|
|---|---|
|Bitcoin|Financial Transactions|
|Ethereum|Financial Transactions, Smart Contracts|
|Filecoin|Decentralized file storage|
|Etherisc|Flight delay insurance|

Many people's familiarty with this third generation of Internet applications is limited.  They may have heard of cryptocurrencies such as Bitcoin or Ethereum and the ability to use them to buy things or [build machines](https://www.ethmining.net) to mine the cryptocurrencies directly.  Normally though, people have not heard about the decentralized applications (dapps) that have already been built to run on top of the larger chains: such as [patreon type services](https://bitpatron.co/), [prediction markets](https://www.augur.net/), or [games](https://knightstory.io).  

These new applications will create a world in which rather than trusting a company and their proprietary software you are trusting a secure network of computers running open and independently verifiable code.  The trusted intermediary involved in an exchange has been replaced by software.  To be clear, there are still companies involved and core developers have control over how the networks and applications operate; however, there is a level of transparency and auditiability that did not previously exist.

At Plyint, we believe that the point of maturity of this new generation of applications is approaching.  We think eventually there will be a major breakout success within this space that becomes an indispensable application to the everyday consumer.  When that happens, we expect an accelerated industry shift towards building on these new decentralized primitives.

We can't wait to be a part of the ride. :)