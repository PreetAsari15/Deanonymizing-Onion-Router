# Deanonymizing Onion Routing Networks

## Introduction
Anonymity on the Internet is crucial for safeguarding user data and identity. It not only ensures safety but also upholds the fundamental human right to privacy, especially in the face of potential misuse by organizations and governments. While providing protection to vulnerable populations and fostering creative expression, anonymization also presents challenges for law enforcement, as malicious actors exploit it for illegal activities. This project explores the deanonymization of Onion Routing Networks, with a specific focus on Tor, aiming to strike a balance between user privacy and the need to apprehend those engaging in illicit online activities.

## Anonymization Methods
Various methods exist for Internet users to anonymize themselves, including VPNs, anonymous browsers, and search engines like DuckDuckGo. Anonymizing networks, such as the Invisible Internet Project (I2P) and Tor, offer advanced privacy features with multi-layered encryption, decentralized infrastructure, and complex routing mechanisms. These networks predominantly employ onion routing, a technique embraced by Tor, to anonymize users and their identifiable information.

## Onion Routing in Tor
Tor employs onion routing to achieve complete user anonymity. This method uses tunnel technology to direct data through specific locations, obscuring IP addresses and protecting user identities. Information packets sent through Tor are routed through a series of nodes, each encrypting the data. The original destination of the packets becomes untraceable, ensuring anonymity. The Tor network comprises Directory Servers, Onion Routers, and Onion Proxies, which collectively create a secure circuit for data transmission.

## Tor Circuit Encryption
Encryption in the Tor network occurs in layers, utilizing both asymmetric and symmetric encryption. Asymmetric encryption authenticates users and establishes secure connections, while symmetric encryption transfers data between nodes. The Tor circuit is built with each node holding a symmetric key for an encryption layer. Messages are encrypted layer by layer, and each node decrypts its allocated part. This layering, combined with node unlinkability, maintains user anonymity by concealing the complete path taken by the message.

## Threats and Research Focus
Onion routing's robust anonymization poses challenges for authorities tracking individuals involved in illegal activities. Our research aims to explore vulnerabilities in Onion Routing Networks, specifically Tor, focusing on quantitative data collection. We will investigate potential solutions for deanonymization, offering a method for authorities to apprehend wrongdoers while preserving the privacy of law-abiding users. Our study also addresses potential vulnerabilities in the network, contributing to the ongoing dialogue on striking a balance between anonymity and accountability.

![Figure 1: Visualization of a sample Tor circuit between two network users](https://davidleudolph.ch/dateien/projekte/how-tor-works-3-large-en.png)

