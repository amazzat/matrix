# Oki

## Oki is a service for creating subscription based business models for any good

Users will have ability to buy subscriptions for variety of goods like products, coffee or event neo sticks. On the other hand business side will have stable income as number of subscribed clients.

## Git flow

### Branches:

**master** - production branch

**staging** - staging branch for testing

**develop** - development branch for synchronization

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
4. If task is done, merge your branch to **develop** branch for synchronization between other branches
5. From time to time **develop** branch will be merged with **staging** branch for testing and preview will be deployed automatically
6. If everything is ok, **staging** will be merged to **master** branch and application will be deployed to production
