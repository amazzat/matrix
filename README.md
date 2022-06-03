# Oki

## Oki is a service for creating subscription based business models for any good

Users will have ability to buy subscriptions for variety of goods like products, coffee or event neo sticks. On the other hand business side will have stable income as number of subscribed clients.

## Git flow

### Branches:

**master** - production branch

**staging** - staging branch for testing

**dev/\<name\>** - Development branches, where **\<name\>** is member's name

### Flow:

1. Create (if not exists) branch from master with name **dev/\<name\>**, where **\<name\>** is your name.
2. Make changes, run
   ```bash
       yarn lint
       #or
       npm run lint
   ```
3. Commit changes and push them to the remote
4. If task is done, merge your branch to **staging** branch, preview will be deployed automatically
5. If everything is ok - merge **staging** to **master** branch
