# Home of the EOSIO+ Governance Systems subgroup

Objective: A description of the functional governance system for ongoing decision making.

  - **Approved:** Establishment of an top level **interim** Governance Council and some manual processes for now.
    - **Approved:** We are ready for decide voter app now if we want.
  - Who are the members that can vote / rank?
    - N votes per "engaged" Chain?  Chains: WAX, Ultra, Telos, UX, Proton, FIO, EOS
      - **Approved:** One per chain **for now** to keep it simple in the **interim process**.
    - **Approved:** Only "contributing" chains (TBD) may vote.  Non-contributing (TBD) chains may participate in discussions and debates.
    - A voting class for strong contributors (ie. that build tools) - but generally not just a BP.
      - **Approval:** These members are nominated, seconded and voted in by the voting chains with a simple majority
    - A BP that sits on multiple chains must only represent one chain at a time (meaning they participate as part of that chain's vote)
    - Contibuting vs Non-Contributing Members - shoud non-contibuting members get a vote?  
      - **Approved:** No.  They can debate and add to the discussion, but not vote.
  - How are new members added or removed?
    - **Approved:** They would need to be a chain and agree to be a contibuting member (or could be a non-voting, non-contributing, observer)
    - **Approved:** They are a "strong contributing" community member that the chains vote in with a nominated, seconded, simple majority.
  - How is voting or ranking accomplished [(see Software Development Group 2nd item)](../SoftwareDevelopment/objectives.md)
    - We mostly stopped here last meeting.
  - **Approved:** Cross-chain Governance token be proposed to the Governance Council once formed and them potentially funded.  Should not be approved here.
    - Currnet need for expediency requires manual processes or the Blue Papers are effectuively dead
    - Governance token, token conversion, and DAO software to be proposed as a funded software effort and voted upon by the Council
  - **Approved:** Each chain uses their own processes and methodologies to elect its representative(s) to the the Governance Council
  - How are new proposals added, discussed, and prioritzed by the group (again see the SW Dev group issues)
    - **Approved** Any voting or non-voting member can make a new proposal to the Governance Council.
  - How will the Governance Council provide audit or overview audit that what was built was what was actually commisioned
  - Use a tool to record the governance decisions devidevoter.app poll.
    - **Approved:** Telos Decide Governance system - mobile wallet or Web (decidevoter.app)
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
