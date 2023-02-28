**Title**: bDIP-01: Correcting Grant Proposal Requirements
**Scope**: patch (bug fix)
**Draft Authors:** links
Working Group: links, hirokennelly, trewkat, siddhearta

# BDIP SUMMARY

The BanklessDAO Constitution 2 failed to capture the operational realities of the Grants Committee, and incorporated incorrect requirements (quorum, ungated polls) for grant proposals. This bDIP will bring the Constitution in line with the practices of the Grants Committee, providing clarity for future funding requests.

# BDIP BACKGROUND

The BanklessDAO Constitution lists Forum quorum requirements for grant applications which are specified in the Firming Up Governance 13 Snapshot vote. Those quorum requirements were interpreted by the Grants Committee as having been vacated by the Quorum Removal Vote 5. In the perceived absence of a quorum, the Grants Committee created its own quorum adjustment method 5, with help from the GSE, and this has been in operation since July, 2022. Later, the Constitution was enacted via a Snapshot vote which incorporated the incorrect quorum information 7.

The BanklessDAO Constitution also states that proposal votes are REQUIRED to be ungated. This was never specified in any seasonal specification or previous Snapshot, and introduces significant security issues (sybil attacks). There have already been one suspected and one confirmed case of non-BanklessDAO members voting for grant proposals to meet quorum requirements, so it’s important we ensure the Constitution does not encourage this.

This bDIP’s intent is to patch the two bugs listed above.

# BDIP SPECIFICATION

Since this is a “bug fix”, this bDIP can be considered a patch.
Current Form

Forum voting leverages one vote per user and is not token-weighted or gated. Forum proposals require 70% approval to pass to successive stages of governance. Proposals must be posted for one week unless the request exceeds 1M BANK. In these instances, they must be posted for two weeks. Forum quorum is the minimum number of voters that need to be present for the vote to be valid and is listed in the following table. For example, if your Forum post is asking for 50,000 BANK or less, only 25 voters need to cast their votes for the vote to be valid.
 	


| Requested Bank  | Forum Quorum |
| -------- | -------- | 
|< 50k BANK 	|25|
50k - 250k BANK |	31|
250k - 500k BANK 	|40|
500k - 1M BANK 	|51|
| Requested Bank  | Forum Quorum | 
|> 1M BANK 	|63|
|Governance (Major) |	63|
|Governance (Minor) |	51|
Governance (Patch) |	40|

[See Snapshot 13]

## Proposed Form

Proposal votes are one vote per user and are not token-weighted. Grant proposals must meet the quorum requirements set by the Grants Committee (available on their Notion page 6), which may be adjusted seasonally at their discretion.

Governance quorums are listed below.
|Governance Update |	Forum Quorum 	|Approval % |	Timeline |
| -------- | -------- | -------- | --------|
Major |	63 	|70% |	1 week|
Minor |	51 |	70% |	1 week|
Patch 	|40 |	70% |	1 week|

## EXPECTED IMPACT

The Constitution will accurately reflect the current quorum requirements in effect at BanklessDAO.
## ANALYTICS

None
## NEXT STEPS

    Get Forum consensus (40 votes)
    Get Snapshot consensus
    Update the Constitution

## WORKING GROUP BACKGROUND

**links** was the Grants Committee Lead from S4-5 and Champion of Bankless Card.
**HiroKennelly** is a long-time DAO member and helps lead various projects…
**Trewkat** is a member of Writers Guild and Lead Staff Editor of the EPA.
**Siddhearta** is the Writers Guild Coordinator and Newsletter Team Champion.
