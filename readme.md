# Strangelove's Cosmos Validator Management Transition Tracker

This document is designed to track the transition to having additional SL members participate in strangelove governance.

## Authz Support and Transactions

This section tracks whether each Cosmos chain supports authz and if Management has completed the necessary authz transaction to authorize the infra team to vote on his behalf.

### Authz Transaction Template

```
noded tx authz grant
$INFRA_ADDRESS generic
--msg-type /cosmos.gov.v1beta1.MsgVote \
--expiration 0 \
--chain-id <chain-id>
--node <node-url>
--gas auto --gas-prices 0.025udenom
--gas-adjustment 1.5
--from operator_key
```


# Cosmos Chains Tracker

| Cosmos Chain    | Key Owned By      | Supports Authz (Y/N) | Authz Transaction Completed |
| --------------- | ----------------- | :-------------------:| :-------------------------: |
| Agoric          | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Akash           | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Celestia        | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Cosmoshub       | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Crescent        | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Dydx            | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Evmos           | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Injective       | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Juno            | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Neutron         | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Nibiru          | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Noble           | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Nolus           | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Omniflixhub     | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Osmosis         | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Quasar          | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Sentinel        | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Stargaze        | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |
| Stride          | Jack [ ] Tyler [ ]| [ ] Yes [ ] No       | [ ]                         |

