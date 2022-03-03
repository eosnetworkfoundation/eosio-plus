# Home of the EOSIO+ Governance Systems subgroup

Working on the following objective:
- A description of the functional governance system for ongoing decision making.
  - Proposal: Establishment of a top level Governance Council
  - Who are the members that can vote / rank?
    - N votes per "engaged" Chain?  Chains: WAX, Ultra, Telos, UX, Proton, FIO, EOS
      - Proposal: One per chain for now to keep it simple in the interim process.
    - Proposal: Only "paying" chains may vote.  Non-paying chains may participate in discussions and debates.
    - A voting class for strong contributors (ie. that build tools) - but generally not just a BP.
      - Proposal: These members are voted in by the voting chains with a supermajority
    - A BP that sits on multiple chains must only represent one chain at a time (meaning they participate as part of that chain's vote)
    - Weighting by Chain? Not solely by Funding - but some non-majority increase due to EOS funding 70%-80%? 10 total votes and EOS gets 4 of them?
    - Paying vs Non-Paying Members - shoud non-paying members get a vote?  
      - Proposal: No.  They can debate and add to the discussion, but not vote.
    - Voters and Observers - obervers can participate in discussions - but not in the votes (same as above?)
    - Set up an interim process until the new organization is formally formed - critically needed by the Blue Papers now
    - **Rejected:** One vote per "engaged" BP?  No - BPs are not acceptable (Rami / Douglas) except for "Strong Contributors" described above.
  - How are new members added or removed?
    - They would need to be a chain and agree to be a paying member (or could be a non-voting, non-paying, observer)
    - Or they are a "strong contributing" community member that the chains vote in with a supermajority
  - How is voting or ranking accomplished [(see Software Development Group 2nd item)](../SoftwareDevelopment/objectives.md)
  - Proposal: Each chain uses their own processes and methodologies to elect its representative(s) to the the Governance Council
  - Proposal: Cross-chain Genernance token be proposed to the Governance Council once formed and them potentially funded.  Should not be approved here.
    - Currnet need for expediency requires manual processes or the Blue Papers are effectuively dead
    - Governance token, token conversion, and DAO software to be proposed as a funded software effort and voted upon by the Council
  - How are new proposals added, discussed, and prioritzed by the group (again see the SW Dev group issues)
  - How will the Governance Council provide audit or overview audit that what was built was what was actually commisioned
  - Using a tool: Telos Decide Governance system - mobile wallet or Web (decidevoter.app)
  - Voting Use Cases
    - New members of the committees
    - Approval of the Blue Paper sections for funding and development
    - Ranking of the Blue Paper sections for Mandel release
    - Funding of work outside the Blue Papers (future)
    - Voting on the election of the positions (EOSIO+ Executive Director, Head of Development, PM as example)
    - Roadmap priorities and releases

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
