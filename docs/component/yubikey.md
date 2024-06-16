# Yubikey with GPG

## Overview

Yubikey is a hardware component that enhances security through cryptographic functions like key storage and digital signatures. Using OpenPGP/GPG on a Yubikey to digitally sign code commits and emails, or encrypt messages.

## Obtain Public Key from Yubikey

!!! info
    This section is after you've already generated keys, put them on your Yubikey, uploaded your public key to a key server, and placed the URL to that public key on your Yubikey.

1. Plug Yubikey into computer
2. Run ```gpg --card-status``` to ensure your computer sees the Yubikey
3. Run ```gpg --card-edit```
4. Run ```fetch```
5. Type ```quite```

Now confirm the keys are there by using:

To view the public key: ```gpg -k```
To view the secret key: ```gpg -K```