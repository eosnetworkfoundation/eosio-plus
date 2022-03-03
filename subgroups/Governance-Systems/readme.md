# Home of the EOSIO+ Governance Systems subgroup

Working on the following objective:
- A description of the functional governance system for ongoing decision making.
  - Who are the members that can vote / rank?
    - One vote per "engaged" BP?  No - BPs were not acceptable (Rami / Douglas)
    - N votes per "engaged" Chain?  Again as above - attending meetings and helping drive the process
    - A BP that sits on multiple chains must only represent one chain at a time
    - Should their be a voting class for strong contributors that build tools - but not necessarily be a BP
    - Weighting by Chain? (Likely unecessary for early work as we have a huge backlog and consensus should likely guide us.)
    - Paying vs Non-Paying Members
    - Voters and Observers
    - Set up an interim process until the new organization is formally formed
  - How are new members added or removed?
  - How is voting or ranking accomplished [(see Software Development Group 2nd item)](../SoftwareDevelopment/objectives.md)
  - How are new proposals added, discussed, and prioritzed by the group (again see the SW Dev group issues)
  - Other questions we should tackle as part of this?
  - Using a tool: Telos Decide Governance system - mobile wallet or Web (decidevoter.app)
  - Voting Use Cases
    - New members of the committees
    - Approval of the Blue Paper sections for funding and development
    - Ranking of the Blue Paper sections for Mandel release
    - Funding of work outside the Blue Papers (future)
    - Voting on the election of the positions (EOSIO+ Executive Director, PM as example)
    - Roadmap

Current Working Group:
- [Rami](https://github.com/ramijames)
- [Douglas](https://github.com/douglashorn)
- [Ted](https://github.com/tedcahalleos)
- [Kersten](https://github.com/Kersten-TCD)

# Mission: Arrive at a method to reach consensus as to what it will actually fund.

From Rami

# EOSIO+ Governance

At it&#39;s most basic, we need a way to decide together what we&#39;re going to fund, and then decide how to fund it.

## Quick Thoughts

I think that governance for this initiative has to have a few key properties, which we can define as base principle:

- Fairness
- Transparency
- Flexibility
- Stability
- Security

For our purposes, we are trying to form some sort of stable governance structures that allow our networks to:

- Manage itself and update processes as needed
- Prioritize features and define a roadmap
- Fund ecosystem development
- Resolve network-level conflicts
- Ensure that what is developed is secure

I believe that for this governance structure to be widely accepted across all networks, it must:

- Run concurrently on all participating networks
  - If the system uses representative tokens as a form of voting system, then this should be accessible from a user&#39;s &quot;native&quot; network. Imagine this as the same as the EU, where individual countries allow users to vote in their own country, instead of going to a special country to vote.
- Allow users of the networks to act as the source of truth for who their representatives are
  - Users select their representatives, who then can efficiently craft policy
- Allow users to confirm that what their representatives want to build match community expectations
  - This acts as a check against representatives which are not adequately performing their duty
- Be funded by all participating networks, to ensure an equitable sharing of costs to ensure the future of the eosio protocol

Towards those ends, we should have a set of governance functions that allow for:

- Representative elections
- Proposal voting
- Funding mechanisms
- Auditing mechanisms

## Proposal

I think that we need

- Governance token
- Software that converts native tokens for a network-local governance token
- Representative Election Software which leverages a governance token
- On-chain DAO which leverages the above to enable key-holding representatives are the only ones allowed to propose proposals to a network
- Local-network Oracle which reads from other networks to sync the DAOs

Open questions

- Do we need to pay out from a centralized place?
- Can each network decide, &quot;we&#39;ll pay for this&quot; and ensure that local-network tokens are used?
