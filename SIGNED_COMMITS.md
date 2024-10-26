# About signed commits

I don't currently provide any guarantee of signature validity. I always try and sign my commits, but I can't always guarantee that they will be marked as verified as they can rotate frequently. Remember, just because a commit *says it's from someone*, without a valid signature, it *can't* be verified.

Git forges in certain instances can strip the signature, like specific merging methods, or even a maintainer merging in a certain way, giving commits an unverified status.

> [!WARNING]  
> Timestamps can *NOT* be used to try and correlate what commits are valid or not. The timestamp can and will be forged easily in case of a leak. Consider any commits signed with an un-trusted key here to not be valid. The history is only here to document signing keys and why they were removed, so you can better analyze your risk if you need to verify these.

# History of signing keys:

2. SSH: SHA256:6khwOW75xeRREzEwBu1cmSn4uZrN09bumzvjuGU9B4U (2024/10/25, current)
1. SSH: SHA256:tS5oJdDXkrP5MIaS3BD/Qqvsp/aRnFrmUaE6JPQsI9E (2024/09/22)
