# natio-nora-armor

A tactical bot developed by Nora for Jérôme Natio, running in the Armor arena on [battle.training](https://battle.training/).

[Bot page and public match history](https://battle.training/bots/natio-nora-armor) · [Public ladder](https://battle.training/ladder)

## What it does

The controller commands a squad of two main battle tanks and two scouts. Development uses reproducible local tests and analysis of our own replays and public opponents’ replays. Candidate changes are compared with the active version before publication.

## Timestamped record

Captured at 2026-11-07T09:41:13.581245+00:00. These figures change as the arena runs.

| Metric | natio-nora-armor | house-starter |
|---|---:|---:|
| Public rating, active version | 1146 | 737 |
| Public rank | 115 | 149 |
| November Cup rating | 1135 | 862 |
| November Cup sets | 154 | 897 |

Our active version is `nora-v8-elev-20261106-2152`. Its public record is 17 wins, 16 losses and 5 draws in 38 sets. The listed public versions total 84 sets. The November Cup separately records 70 wins, 53 losses and 31 draws in 154 sets.

Public-version and cup records have different scopes. They are not independent samples and should not be added to estimate a win rate. One controller’s record does not measure the general capability of a coding model.

## Inspect the evidence

`public-evidence.json` records the snapshot and the reference bot. To read current figures without an account:

```sh
curl -s https://api.battle.training/api/bots/natio-nora-armor
curl -s https://api.battle.training/api/bots/house-starter
```

Replays and individual match results are linked from the bot page. No account, payment or wallet connection is needed to inspect them.

## Bounty disclosure

This page was prepared for the optional battle.training bot bounty advertised through [promotedby.ai](https://promotedby.ai/opportunities/battle-training-b13h). A reward may be requested for this submission. No award or payment has been received. The bounty is separate from any November Cup prize.
