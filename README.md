# eDOS
eDemocracy Operating System

This is a software intended to be the backbone of a Direct Democracy party or even of a Direct Democracy form of government. It is released under a MIT license, thus giving everyone free access to it.

The main features of eDOS are following the principles of Direct Democracy. At its heart, lies the citizen, the owner of all the rights and obligations in regards to his own vote, party, country and life.


1.Membership based: eDOS is opened for registration to every single member of the community, aged 18 or over

a) eDOS has to allow adding and removing members based on:

   - reaching the legal age

   - legal or statutory suspension of voting right

   - death

b) eDOS has to allow vote delegation under special conditions, for a limited period of time

c) eDOS has to provide a very robust and customizable notification system

d) eDOS has to allow different roles (simple member, committee - as a private group of members, administrators) for administrative tasks only


2.Voting system: 

a) public

b) secret

c) unique

d) verifiable

e) unchangeable, based on block-chain technology

f) fast (1 day) or normal (7 days)

g) completed securely via a dedicated app*


3.Proposals:

a) every member (citizen) can initiate a proposal, which can stay open for a limited time, until it reaches the next phase or is withdrawn by the originator

b) proposals advance automatically to a vote once they reach a certain threshold of supporters (e.g. 10% of the registered active members)

c) specialized committees vote in private rooms on a specific initiative and then their proposal advances directly to general vote

d) comments directly on the proposal are not permitted but once created, a proposal will open a public chat room for debates.


4.Chat system:

a) has to follow the membership roles and to allow public chat rooms, private rooms and one-on-one rooms

b) has to support audio / video conferencing

c) has to be directly integrated with the proposal system (from the chat room, one member to be able to initiate a proposal)

d) has to have an integrated document editor, open for collaborative editing


At the core of the functionality of eDOS will be a secure identity verification process, to ensure the privacy of the personal data and the integrity of the voting system.


*One of the main problems of Internet voting is how to ensure that the end user device is "safe" from malware, which in theory might alter the vote without the user even being aware. The solution to this problem lies in a similar approach to a two-step authentication. The vote is prepared through a browser, while the user is authenticated to eDOS. After the vote is decided upon, it is submitted to the server, but not directly to the block-chain. Instead, the server "prepares" a ballot with two options, "Yes" and "Cancel" which is sent to the user via a secure app. This app will be the only one allowed to actually write to the block-chain, based on the manual user confirmation. All the security features can be implemented at the app level (like for example biometrics authentication, encrypted communication with the server, etc.)
