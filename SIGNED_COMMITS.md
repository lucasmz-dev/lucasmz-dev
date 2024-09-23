# About signed commits

I don't currently provide any guarantee of signature validity using these. I always sign my commits, mostly, but I can't always guarantee that they will be marked as verified. I switch private keys frequently every time I need to potentially reinstall my OS. Git doesn't really seem to be the best at verification and that's fine, but do remember, just because a commit says it's from someone, without a signature, it can't be verified.

GitHub in certain instances can strip the signature, like specific merging methods, or even a maintainer merging in a certain way, giving commits an unverified status.

My setup for the GPG signing key is also not the most secure because of the reasons above. Inputting a password every commit and sync is impractical, if I could sandbox it to VSCodium, then I'd do it.

> [!WARNING]  
> Timestamps can *NOT* be used to try and correlate what commits are valid or not. The timestamp can and will be forged easily in case of a leak. Consider any commits signed with an un-trusted key here to not be valid. The history is only here to document signing keys and why they were removed. 

# History of Signing keys:

1. SSH: SHA256: tS5oJdDXkrP5MIaS3BD/Qqvsp/aRnFrmUaE6JPQsI9E (22/09/2024, current)
