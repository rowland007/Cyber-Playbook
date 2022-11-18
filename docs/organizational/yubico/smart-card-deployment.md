# YubiKey Smart Card Deployment Guide

## Introduction

Yubico changes the game for strong authentication, providing superior security with unmatched ease-of-use. Our core invention, the [:octicons-link-external-16: YubiKey](https://www.yubico.com/products/yubikey-hardware/), is a small USB and NFC device supporting multiple authentication and cryptographic protocols. With a simple touch, it protects access to computers, networks, and online services for the world’s largest organizations.

## PIV and YubiKeys

The YubiKey 5 Series devices, YubiKey 4 Series devices, and the YubiKey FIPS Series devices all support the Personal Identity and Verification Card (PIV) interface specified in the National Institute of Standards and Technology (NIST), [:octicons-link-external-16: SP 800-73-4 document, Interfaces for Personal Identity Verification](https://csrc.nist.gov/publications/detail/sp/800-73/4/final). Microsoft Windows supports traditional PIV smart cards for user authentication, allowing the YubiKey to be utilized as a strong authentication solution.

The YubiKey Minidriver extends the support of the YubiKey on Windows from just authentication to allowing Windows to load and directly manage certificates on it. This allows for an easy to use, easy to deploy scalable implementation of strong multi-factor authentication across an entire organization utilizing the native Windows tools and the YubiKey.

## PIV Deployment

This document covers the basic steps required to set up an Active Directory domain environment for smart card authentication, including considerations before provisioning YubiKeys for smart card login. We recommend that a qualified domain administrator be in charge of the process and that you use these instructions as a guideline for deployment. Rather than cover the complexities inherent in a corporate environment (for example, an Enterprise Root Certification Authority, multiple Subordinate Certificate Authorities, Certificate Revocation Lists, and so on), these instructions cover only the basic topics.

 

## YubiKey Smart Card & Minidriver Deployment Guides

- [:octicons-link-external-16: YubiKey Minidriver Features](https://support.yubico.com/support/solutions/articles/15000032351-yubikey-minidriver-features)  
    Overview of the features and functions the YubiKey Minidriver adds to the native Windows Smart Card framework.
- [:octicons-link-external-16: YubiKey Smart Card Deployment Considerations](https://support.yubico.com/support/solutions/articles/15000032352-yubikey-smart-card-deployment-considerations)   
    YubiKey Minidriver environmental and system requirements and compatibility, as well as items to consider prior to setup.
- [:octicons-link-external-16: Setting up Windows Server for YubiKey PIV Authentication](https://support.yubico.com/support/solutions/articles/15000033340-setting-up-windows-server-for-yubikey-piv-authentication)  
    Configuring Windows Server for Smart Card Authentication using the YubiKey.
- [:octicons-link-external-16: Smart Card Login for User Self-Enrollment](https://support.yubico.com/support/solutions/articles/15000033341-setting-up-smart-card-login-for-user-self-enrollment)  
    Steps on setting up Windows Server to allow users to enroll their own YubiKeys as smart cards directly.
- [:octicons-link-external-16: Smart Card Login for Enroll on Behalf of](https://support.yubico.com/support/solutions/articles/15000033342-setting-up-smart-card-login-for-enroll-on-behalf-of)  
    Steps on setting up Windows Server to allow IT admins, help desk staff or others to enroll YubiKeys on behalf of other users.
- [:octicons-link-external-16: Smart Card Deployment: Manually Importing User Certificates](https://support.yubico.com/support/solutions/articles/15000033343-smart-card-deployment-manually-importing-user-certificates)  
    Instructions on importing User certificates created on a different server.
- [:octicons-link-external-16: Deploying the YubiKey Minidriver to Workstations and Servers](https://support.yubico.com/support/solutions/articles/15000033344-deploying-the-yubikey-minidriver-to-workstations-and-servers)  
    How to deploy the YubiKey Minidriver to endpoints and servers.
- [:octicons-link-external-16: YubiKey PIN and PUK User Management](https://support.yubico.com/support/solutions/articles/15000033345-yubikey-pin-and-puk-user-management)  
    How users and administrators can set or change the PIN and PIN Unlock Key (PUK)
- [:octicons-link-external-16: Smart Card Basic Troubleshooting](https://support.yubico.com/support/solutions/articles/15000033346-smart-card-basic-troubleshooting)  
    Basic troubleshooting for the YubiKey as a PIV Smart Cards with Windows.

## Getting Additional Help

For more information, and to get help with your YubiKeys, see:
- Support home page 
- Documentation and FAQs

??? cite "Source"
    [:octicons-link-external-16: Yubico Support Article](https://support.yubico.com/hc/en-us/articles/360013707820-YubiKey-Smart-Card-Deployment-Guide)