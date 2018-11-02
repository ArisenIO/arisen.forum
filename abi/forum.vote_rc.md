# Action - `{{ vote }}`

## Description

A user is able to cast a vote by associating it to {{ proposal_name }}. To 
change a vote, a {{ voter }} only needs to call another `vote` action - only the 
most recent vote of {{ vote_value }} by {{ voter }} will be considered as valid . A user
could also use `unvote` to override their previous `vote`.

If I, {{ voter }}, am not the beneficial owner of these tokens, I stipulate I have proof 
that I’ve been authorized to vote these tokens by their beneficial owner(s).

A user who has a proxy set on their account will be providing implicit consent
for that proxy to `vote` on their behalf. A user who has a designated proxy
may choose to also cast a `vote`, which will override the delegation of voting
authority to that proxy.

I stipulate I have not and will not accept anything of value in exchange for these 
votes, on penalty of confiscation of these tokens, and other penalties. 

Any disputes arising out of use of this contract shall be ruled under the Rules
for Dispute Resolution of the EOS Core Arbitration Forum by one or more arbitrators 
appointed in accordance with said Rules.
