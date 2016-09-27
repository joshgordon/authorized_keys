Authorized keys
===============


These are the ssh authorized keys I want deployed across all my infrastructure. Because I'm tired of tracking that, I want a public place to put them and sync them.

There's a gpg signature of my public keys. Eventually I want to write an agent that syncs this git repo, checks the signature, and then updates the authorized keys
files in place on the system. That will be separate, and will not be synced automatically, so that I don't have to trust my github account. (I'm pretty confident in
the security of that anyways, but when it comes to security of my systems in general, the more layers of protection, the better...)
