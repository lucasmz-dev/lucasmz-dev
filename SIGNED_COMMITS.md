# About signed commits

I don't currently provide any guarantee of signature validity using these. I always sign my commits, mostly, but I can't always guarantee that they will be marked as verified. I switch private keys frequently every time I need to potentially reinstall my OS. Git doesn't really seem to be the best at verification and that's fine, but do remember, just because a commit says it's from someone, without a signature, it can't be verified.

GitHub in certain instances can strip the signature, like specific merging methods, or even a maintainer merging in a certain way, giving commits an unverified status.

My setup for the GPG signing key is also not the most secure because of the reasons above. Inputting a password every commit and sync is impractical, if I could sandbox it to VSCodium, then I'd do it.

I no longer have vigilante mode enabled, meaning my commits are not marked "Unverified" when there is no signature.

# History of Signing keys:

1. SSH: ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIA8hJnFMDMmpr0J91g8FIAHI/9ep14yEdCgWUqn6Mj3K lucas@fedora (22/09/2024, current)
