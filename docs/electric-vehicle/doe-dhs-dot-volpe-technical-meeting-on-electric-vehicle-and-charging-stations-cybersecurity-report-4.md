---
layout: default
title: 4. Trust 
parent: § DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report 
grand_parent: Electric Vehicle
nav_order: 40 
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

  -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}
</style>

<div class="dont-break-out" markdown="1">
1. TOC
{:toc}

## 4. Trust
Electric vehicles and charging infrastructure need a method to ensure secure trusted communication between the EV and EVSE. An essential concept in cybersecurity, trust is when computers prove their identities to each other through the use of applied cryptography. Key aspects of trusted

- Authentication – The sending and receiving parties identities are verified

- Data integrity – Data is not able to be altered by a 3rd party during the transmission process

- Data secrecy – Data is not able to be read by a 3rd party during the transmission process

EVSEs and the networks that will carry the communications (e.g. demand response, price charging, authentication and authorization) between the EVSE, the utility and other connected devices like CEMS, smart meters, etc. must have a secure trusted end-to-end communications path. If the malware/attacks can be propagated from one node to another node (e.g. EVSE), it will be only a matter of time before all the nodes are compromised. Options to secure these interfaces will be encryption and authentication:

- **Encryption** – In cryptography, encryption is the process of encoding a message or information in such a way that only authorized parties can access it and those who are not authorized cannot. Encryption does not itself prevent interference, but denies the intelligible content to a would-be interceptor. In an encryption scheme, the intended information or message, referred to as plaintext, is encrypted using an encryption algorithm – a cipher – generating cipher text that can be read only if decrypted

- **Authentication** – For a positive authentication, elements that could be verified include:

 - **Knowledge factors:** Something the user knows (e.g., a password, partial password, pass phrase, or personal identification number (PIN), challenge response, security question)
 - **Ownership factors:** Something the user has (e.g., wrist band, ID card, security token, implanted device, cell phone with built-in hardware token, software token, or cell phone holding a software token)
 - **Inherence factors:** Something the user is or does (e.g., fingerprint, retinal pattern, DNA sequence, signature, face, voice, unique bio-electric signals, or other biometric identifier).

In effect, trusted communication allows two parties, such as a customer and a store, to use an untrusted medium, such as the Internet, for a specific purpose, such as buying or selling goods, without fear that a third party will manipulate their order (violate data integrity) or steal their financial information (violate data secrecy). Currently, there is no consensus on a trusted communication standard for securing communications between electric vehicles and charging infrastructure. However, there are a number of existing standards and technology for securing end to end communications in use today (see Appendix A). Instead of creating a new standard, existing Internet security standards and best practices can be adapted for use in the EV and EVSE domain.

The Internet, and the range of mature security technologies which support it, is one of the best places to look for existing technologies to adapt to electric vehicle charging networks. One common security concept which the internet relies on is the concept of zero-trust, or that the network itself is untrustworthy. This means that communications over that network are secured in an end-to-end manner (through encryption and/or authentication), and that the end devices themselves are responsible for authenticating, and ensuring integrity and secrecy of their communications. Some of the standards and technologies that enable this are X.509, which defines the format of public key certificates, a common method of authentication, and Transport Layer Security (TLS) which allows the two endpoints to establish a secured session which ensures data integrity and secrecy. TLS enables protocols, such as HTTP, to be run in a secure manner, such as HTTPS. This robust system for exchanging keys, validating identities, and establishing a secure session is the keystone which supports e-commerce, and can be adapted to the electric vehicle charging ecosystem to enable secure communications between any combinations of stakeholders in the industry. The World Wide Web Consortium (W3C) has expressed interest in adapting web protocols and technology for use in the automotive domain and is a potential partner for this effort. In order to use this technology, industry must adopt a trust anchor or root of trust, upon which the rest of chain of trust is derived.

In cryptographic systems with hierarchical structure, a trust anchor is an authoritative entity for which trust is assumed and not derived. For example in X.509 certificates, a “root certificate” is the trust anchor from which the whole chain of trust, and therefore authentication process, is derived. The trust anchor must be in the possession of the trusting party beforehand to make any further certificate path validation possible. Vehicles and charging infrastructure have unique trust challenges related to their physical properties. Unlike personal computers and servers, which are usually kept behind locked doors, charging stations and automobiles are frequently left unattended in public and need periodic maintenance. These properties make secure storage of trust anchors a significant challenge. Both devices need some form of tamper-proof storage for keys and a method to revoke keys which have been compromised. The Society of Automotive Engineers (SAE) is currently in the process of developing *Standard J3101: Requirements for Hardware-Protected Security for Ground Vehicle Applications* which addresses the need for hardware-based trust anchors in the car. It is possible to leverage the trust anchors proposed in this standard to address electric vehicles. The Hybrid Communication and Interoperability Task Force has also published the *Technical Information Report J2931/7*: Security for Plug-In Electric Vehicle Communications. The report establishes the security requirements for digital communication between Plug-In Electric Vehicles (PEV), the Electric Vehicle Supply Equipment (EVSE) and the utility, ESI, Advanced Metering Infrastructure (AMI) and/or Home Area Network (HAN).

</div>
