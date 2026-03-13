# Sync-Bot

Set up a GitHub Action to sync my fork's main branch with their upstream original.
- use https://github.com/wei/git-sync to do the synchronization
- create an SSH2 private/public keypair
    - put the private key as `SSH_PRIVATE_KEY` secret in the sync-bot repo
    - put the public key as **username > settings > ssh** authentication key (_not_ as the **Repo > Deploy Key**, like the action README suggests)
