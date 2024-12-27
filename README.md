# stake-shards


### IIP: Stake shards

**Author:** hlolve

**Status:** Draft

**Type:** Standard

### Shards by IDs stake

### Motivation

Flips are the key element of Idena network security.
The protocol imposes severe penalties on users that create flips in breach of the rules.
If one of the flips is reported during the validation, the user that created this flip will not get any rewards for the validation.
So, the security is driven by a opportunity cost of lost rewards, but for IDs only seeking "human" status is not important.

### Rationale

For IDs with moderate to high stake is important to keep high score in short session and they take care to produce their flips.
The proposal consist in always at least have 2 shards, where half of top stakers belongs to one shard and the rest in other shard.
It could give a better ceremony experience to the top stake accounts, and incentive the IDs in the "low" shard to stake more and go to top shard.


### Backwards Compatibility

This proposal requires changes to validation ceremony results shards assignment.

### Security Considerations

The risk is shard with "low" stake could be a mess of bad flips, and IDs get all killed themselves. Maybe this is not bad at all.
