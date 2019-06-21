# Anarchoverse

## Anarchoverse: From Fiction and Games to Revolution

Asymmetric cryptography and the Internet are perhaps the most important inventions to realize the Anarchic Revolution. 

Yet, when Karl Marx penned the Communist Manifesto, it was a work of fiction, until it became a revolution. 

Anarchoverse is the name of a computer game that simulates the Anarchic Revolution, except that we do not know if the programs in Anarchoverse may one day connect themselves to the real world.

The "killer app" in Anarchoverse is the AnarchoToken, a simple yet revolutionary asymetric cryptographic scheme to realize borderless micropayments and decentralized messaging. 

While asymetric cryptography has become the foundations of numerous revolutionary technologies, from TLS to Bitcoin, its most radical use case takes a much simpler form:

https://github.com/udexon/DatongToken

We use the names DatongToken and AnarchoToken interchangeably, for different audiences. In terms of implementation, the name Anarchoverse captures the imagination much better, so that we can recruit as many collaborators as possible, as soon as possible.

The core engine of AnarchoToken is based on the "stack machine shell" -- also a simple yet revolutionary piece of work:

http://5gl.epizy.com/nsm/fgl.html?i=2

The basic idea is that AnarchoToken can be executed in computer games (mobile or desktop), allowing users to send "money" (definitons later!!), realizing "borderless micropayments".

Readers may wonder in the age of a thousand and one cryptocurrencies, who needs "borderless micropayments"?

The answer lies in "adoption". Any cryptocurrency system to date requires registration and login. AnarchoToken is basically a system of authentication that DOES NOT require registration, thus overcome the biggest obstacle of all crytocurrency systems.

Not only does AnarchoToken works with cryptocurrencies, it also works all national currencies and online banking systems as well.

Again some readers may ask: If AnarchoToken is so wonderful, why has it not been conceived and implemented earlier?

The answer is again simple and revolutionary: it may destroy the existing global financial system (read US Dollar) in the snap of a finger (Thanos style)!!

How is that possible? How is such a simple idea able to destroy the global financial system?

Let's remind ourselves that we are discussing the technicalities of AnarchoToken in the context of Anarchoverse -- a work of fiction and computer game.



Let's call the network for transmitting payments and messages using AnarchoToken Anarchonet. We may liken the conventional banking system to the old analogue telephone network, and Anarchonet to Internet.

In conventional banking system, in its most basic form, a sender can send money to the Recipient if and only if they have accounts in the same bank. If they have accounts on different banks, their banks would need to connected via payment gateways like Swift. 

In Anarchonet, any individual person can act as a payment gateway (Anarcho Agent), connecting to accounts of different banks. 

What is the barrier of entry for anyone to become an Anarcho Agent? Refer to traditional Hawala. Modern technology concentrate lots of technical advancement to make it possible ....

The short answer is: Most users would have at least one bank account in the modern world, but the chances of the sender and recipient to have accounts in the same bank would be much lower. In such cases, we need a chain of Anarcho Agents who can act as payment gateways (much like Internet router) to connect the bank of the sender to the bank of the recipient. The only other missing ingredient is a system to autheticate the identities of the sender, recipient and the Anarcho Agents, which asymmetric crytography can provide.

Although conventional commercial money transfer services like Western Union play the role of the payment gateway, their commission fees are quite hefty. With Anarchonet, Anarcho Agents will compete with each other to reach the lowest fees.

The advent of social networks has created the phenomena of Internet stars will millions of followers, with thousands of likes on videos or photos posted on a daily basis. It urgently needs a solution like Anarchonet to monetize these activities optimally. Although Facebook has launched its own cryptocurrency Libra recently, Anarchonet is much more superior, perhaps the final form of evolution in payment gateways. At the probability of 1 in 1000 users tipping USD 1 per day, based on 100 million users (a very conservative measure), that would be USD 100K of tips daily.

In accordance to the spirit of free software and anarchism, we will implement Anarchonet / AnarchoToken at the initial phase as a gaming token. The future implementation in real life is beyond our control. From the investors' perspective, this is a risk free venture -- if proven to work in gaming environment, they may decide on how to actually monetize it in real life.


### Anonymity and Decentralization

Although the Internet and the Unix operating system were developed by almost the same group of programmers, the philosophies of anonymity and decentralization were not clearly separated, until one examines the fundamental significance of asymmetric cryptography.

As a multi-user operating system, Unix has a centralized identity management system. Although the Internet is decentralized, the Unix servers connected to the Internet manage their users in a centralized manner. Even as modern social networks have reached billions in the number of users, the identity management of these social networks is still centralized.

Can identity management be decentralized? The short answer is yes. The long answer is that literature on asymmetric cryptography did not address this issue explicitly. 


Asymmetric cryptography was not publicized due to government secrecy during the early days of Unix development, as traditional symmetric encryption sufficed for a centralized multi-user system.

https://en.m.wikipedia.org/wiki/Public-key_cryptography


Perhaps the most common example of asymmetric cryptography is the transport layer security protocol used in web connections.  

-- The identity of the communicating parties can be authenticated using public-key cryptography. This authentication can be made optional, but is generally required for at least one of the parties (typically the server).

https://en.m.wikipedia.org/wiki/Transport_Layer_Security

In a typical web browser scenario, public key cryptography (asymmetric cryptography) is used to authenticate the identity of the server, not users. 

In messaging apps like WhatsApp, identity management is still centralized. 

How can identity management for payment transactions or messaging services be decentralized?

Again, the Internet itself provides the lessons. 

In a typical Internet connection, e.g. http used for web browsing, a data packet is sent through a port, together with the IP address (IPv4 or IPv6), from the source network interface, via a series of routers, until it reaches the destination network interface.

In this scenario, we may say that the identity  management of the network interfaces (IP addresses) is centralized, as all IP addresses used around the world are coordinated using the domain name system (DNS), so that there are no conflicts. 

However, for IP protocols, Intranets that are isolated from Internet can be set up. Within  Intranets, IP address (identity) management is independent. 


For Anarchonet, public keys of sender, recipient and agents need only to exist uniquely for the lifetime of a transaction. Public keys can be generated using any chosen cryptographic program as agreed by sender, recipient and agents. 

Much like an Intranet, where the identities (IP addresses) are unique within an isolated network, Anarchonet public keys (which represent the identities of sender, recipient and agents) are unique over a short period of time, involving a limited number of participants. 

Like an Intranet, where the identity management is centralized within the isolated network, the identity management for Anarchonet is only centralized within a cell consisting of the participants. 

We may say that the identity management for Intranet is decentralized with respect to the rest of the Internet. Similarly, we may say that identity management for Anarchonet is decentralized with respect to the rest of the Internet. 

Hence the vulnerabilities of Anarchonet are:

 i) Encrypted messages can be decrypted by brute force within the duration of a transaction, if sufficient computing power is available, which is every unlikely.

ii) Transaction logs are recorded by third party payment systems used by agents, e.g. cryptocurrencies or national banking systems.

iii) Anarchonet programs used by agents will not leave permanent records, unless agents use virtual machine or similar systems to log transactions, which can be detected.

Without transaction logs in (iii), regulators will have a hard time piecing together traces from logs in (ii).
