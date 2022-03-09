# EOSIO+ Software Development Subgroup Objectives
- [ ] A set of standards and organizational processes to integrate code from outside developers.
- [ ] A description of the method to determine how various demands for new code development will be prioritized and implemented.
- [ ] A description of the process for performing ongoing release of new code and code binaries.
- [ ] Commenters, Issue Triage and how they are handled.  What access?
- [x] Should we keep this time for recurring weekly meeting? Yes

[Team members](readme.md)

## Standards and Organizational Processes to Integrate Code from Outside Developers
- Should we consider the Apache Software Foundation (ASF) Model of [Contributors and Committers](https://community.apache.org/contributors/)?
  - This requires a committee of "commiters" (gatekeepers) that peridoically approves or rejects new contributor submissions
- This team to write the clear Policy and Process for all developers submitting code
  - Does the code do what the commit says?
  - Does the commit do what was on the roadmap?
  - Is it a bug fix to a known issue?
  - The commiter approval process.  One approval enough - one rejection enough to stop the process and require discussion.
- Capture use case where we assigned work to a 3rd party that we have little to no experience with
- How to ensure the priorities of the gatekeepers/commiters are in alignment
  - Must be on the roadmap
  - Must be agreed to by general consensus
  - Is there a consensus mechanism above them if they (commiters) are blocking items?
- How to handle a 3rd party feature that was not on the roadmap but seems beneficial?
  - Have a committee (not necessarily the commiters) that took these as input, and then ammended the roadmap.
  - Need a clear published policy on GitHub as to how to submit new code, features or proposals (Pomelo / Grant Framework)
  - Make the decisions and committe of the above type decisions public and transparent

## Process to Prioritize Demands for New Code Development
- Handled by the Governance Committee
- Consider the blue paper work as different than post blue paper.
  - Ted [review process](../../eosio+PathToRoadmapProposal.md) he plans for larger group on Thu?
    - Blue papers broken into SOWs (there are 7 in Audit+, 8 in API+)
    - SOWs prioritized by vote - some SOWs are "killed" (not agreed work needs to be done by group)
    - Authors of top prioritized SOWs make initial cost/time estimate
    - If Author estimate accepted they begin developing
    - If Author estimate rejected, SOW placed out for RFP
    - Winner of RFP begins development
    - Note: some portions may be released prior to need (APIs before Wallets)
    - APIs and SDKs recommended in the core system
    - [ECMA Script standards](https://tc39.es/process-document/) to ensure coordination of standards between scripts
- Process used Post Blue Papers to prioritize work
  - Inbound requests (Pomelo)
  - Inbound requests (Grant Framework)
  - Outbound commission (Blue Papers)
- Ranking?  Who gets to vote/rank?  Who should be on the committees?
  - One vote per Chain
  - One vote per Block Producer team (all chains)
  - Scope of this goup only for "core software" that affect multiple chains
  - Goal is to prioritize and see where there is consensus - and what is controversial and to delay
- Ranking weighted by contribution of chain?
- Other ranking proposals?
  - Next two to three waves of features it will likely be common sense and little disention
  - Once we get beyond that, we will likely be happy we had determined a voting structure that we practiced

## Ongoing Release of New Code and Binaries Process
- Prefer independent and incremental releases of non-dependent components (Wallets for example)
- Should this also include CI/CD?
  - Jesse, Aaron, Ted agree CI/CD necessary
  - Need to fund and drive this - need addition to one of the papers
  - Both a speed pipeline and a functionality pipeline
  - Can have multiple classes of CI/CD: Blue (power-up), Green (no power-up), etc
    - Telos, Fio, Ultra, etc.
  - Run the client binaries against live networks - vs fake networks
- Should we consider an integration enviroment hosted by this group?
  - Check with core developers.  Is this the same thing as an CI/CD?
  - Depends on scope of work. Minor work on edges would not need this.  Large refactoring would need it.
- Testnets
  - One testnet for EOSIO+ does that take care of other nets?
  - Would need dedicated test net for consensus changes.  Or changin the peer-to-peer protocol.
  - Could CI/CD solve this?
-  Should we host Docker images and .deb file?
   - How do we validate the artifacts are legitimate?  Hash or signature of binary.
   - How often do we generate?
   - How well do we document?
- More frequent now due to full pipeline of features and bug fixes
  - Two feature releases per year is the current target

## Commenters, Issue Triage and how they are handled.  What access?

