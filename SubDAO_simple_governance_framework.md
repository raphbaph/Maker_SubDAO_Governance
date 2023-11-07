# SubDAO Simple Governance Framework
This proposal suggests an easy-to-implement framework that aligns with the natural life cycle of proposals, empowering SubDAO communities with a straightforward way to bootstrap decentralized decision-making. 

Building upon Maker Core's best-in-class polling system and with a clear delineation of responsibilities to Maker Core facilitators, the following framework ensures alignment with the principles of the Maker Atlas.

This proposal outlines our understanding of a proposal's lifecycle and presents a simple governance framework for SubDAOs, using off-the-shelf components to speed up implementation. The suggested framework is similar to MakerDAO's pre-Endgame governance and many other DAOs governance processes.

It contains some hard-won lessons and identifies some areas for experimentation and improvement.

## Proposal Lifecycle

A proposal begins as an idea, which matures through conversations and soft checks via chats with other community members. When the proposal's author believes it has a decent chance of making an impact and being successful, they share it on the forum.

A forum post is akin to a declaration of intent, addressing key questions:  
* What should be done?
* Why should it be done?
* What specific aspects of the DAO should be improved? 
* Which new projects should be started?

Formal discussions and more rigorous vetting typically occur as community members respond to the forum post. Many DAOs implement an RFC (Request for Comments) period, a minimum timeframe for a proposal to be open for discussion before it gets put to vote. 

While Maker Core doesn't have a formal "temp-check" process, it does rely on forum discussions to identify and weed out bad proposals quickly.

A formal off-chain poll as a temp-check adds value because it simulates the conditions of the actual on-chain decision later. Authors and Governance Facilitators can gauge community interest and the overall sentiment and make amends, if necessary.

![](https://hackmd.io/_uploads/ryCxEFFW6.png)

After a successful temp-check poll, a SubDAO governance decision would enter MakerDAO’s formal polling cycle and be put to vote on the [voting portal](https://vote.makerdao.com). 

Finally, proposals ratified by token holders are subject to inclusion in an omnibus spell for an Executive Vote.


Ideation is an amorphous process usually taking place outside of any formal system and is hard to support directly. Instead, this framework tries to influence the overall decision of proposal ideation by suggesting tools that enable prospective proposal authors to quickly gauge the topics the community is most interested in and the most pressing concerns that need to be addressed. Proposal ideas are likely aligned when they address a community goal or pain point.

## Facilitating soft consensus and intent declaration

### Discord / Group chat setup and moderation

MakerDAO currently uses Discord for discussion, which may change if Maker switches to a more decentralized chat solution. SubDAOs now operate their own Discord servers, some more active than others. Initially, these servers should serve three primary purposes:

* Foster general community discussion
* Facilitate focused discussion on governance topics
* Support community building and education

This proposal advocates for an iterative approach, starting with a few select channels and expanding as it becomes clear which topics are regular and which aren't.

TechOps Ecosystem Actors can administer Discord Servers in the beginning. Other Ecosystem Actors will need to moderate them. This could either be done by MakerDAO governance facilitators or by other Ecosystem Actors as soon as the burden exceeds the capacity of the former.

### Discourse / Forum setup and moderation

Discourse is the default software solution for hosting the forum, where more formal discussions on proposals take place.

From our experience, Discourse has some significant drawbacks for DAO decision-making, for example:

1. Comments take time to resolve fully, as they remain visible, even after the proposal author addresses them.
2. Replies are ranked by incoming time, which means the most valuable replies are often buried.

This proposal recommends looking into potential alternatives. After all, subDAOs are where experimentation takes place and could be the ideal testing ground for other, potentially more DAO-friendly and decentralized solutions.

SubDAO forum discussions have already begun in sections of the main forum, which allows the Maker community to discover topics across the whole Core + subDAO ecosystem. As soon as subDAO community activity necessitates it, subDAO forums should be moved to their own server, along with any desired restructuring or revamping.

As with Discord moderation, Forums also bring their day-to-day duties:

* Correctly tagging and filing proposals
* Moderating discussions 
* Flagging relevant posts and replies for follow-up by Maker Core Facilitators

The volume of forum posts across all subDAOs would make the involvement of additional Ecosystem actors focused on subDAO governance beneficial.

## Temp-checks and sentiment gauging

Temp checks should provide the community with a quick and effective way to tell a proposal author if his ideas are where they need to be or not.

SubDAO governance can also use temp-checks to detect community preferences and identify pain points, giving proposal authors valuable input on what they could work on.

There are numerous tools for temp-checks, from simple forum polls to tools using elaborate allow-lists or reputation tokens. SubDAO governance should experiment with different approaches to find the ideal fit for *their* community and to further the overall alignment of MakerDAO governance.

## On-chain voting

MakerDAO is fortunate to operate one of the most time-tested voting procedures and frontends in the entire space. This proposal assumes that subDAO on-chain voting will use subDAO tokens and likely fork the front-end for each subDAO. 

On-chain voting could be another avenue for experimentation. Some subDAOs might profit from gauge-voting similar to Curve's ve-model. Others might need different voting systems to ensure optimal candidate selection. 

Making sure that polls are correctly formatted, reference the proper forum discussions, and are launched on the correct dates with suitable durations will need support from Ecosystem Actors as volume ramps up.

## Spell creation and executive votes

Successful SubDAO proposals are eventually merged into spells with Maker Core governance output and presented for executive approval by governance token holders.

Executive votes need
* a well-audited and correctly developed smart contract to deploy
* a description and documentation to allow less technical community members to know what they're voting on
* communication so token holders are aware that their action is required

## Automation

DAOs are meant to automate as much of their operations as possible. Governance Facilitators or supporting Ecosystem Actors should always be on the lookout for processes that can automated or ossified.

The transition from a forum post to a temp check to an on-chain vote and, in parts, to an executive vote are ripe candidates here. A temp-check and an on-chain vote must be labeled precisely the same so that governance participants do not have to second-guess if it is still the same proposal they are supporting.

Each subsequent stage should clearly identify what has changed or improved since the stage before, if anything, and have a standardized format that allows users to catch the intention at a glance.

Given the rigid structure of this process, automation is ideal to ensure that formal requirements are met. 

## Alignment with ATLAS and Scope Bounded Mutable Artefacts

SubDAO governance output also needs to be universally aligned with the Maker Atlas. 
In particular, Governance Facilitators or their supporting Ecosystem Actors need to ensure that:

* Proposals are not out-of-alignment by trying to implement out-of-scope or prohibited endeavours
* Scope Bounded Mutable Artefacts co-evolve with SubDAOs and guide and support them while reflecting the realities of the market
* MIP102c2 proposals are created to update scopes when subDAOs need changes
* Regular Q&A calls for AVCs and ADs are held

SubDAOs should use specific Ecosystem Actors to support Maker Core Governance Facilitators in the various tasks outlined in this framework. The workload will only increase as subDAO governance matures.

## Summary

SubDAO governance can start with a simple framework that follows a proposal lifecycle and experiment and improve from there.

This proposal outlines some key areas of experimentation and identifies where Governance Facilitators likely need support from subDAO Ecosystem Actors. 

## How StableLab can help

StableLab is the premier DAO governance organization working with 20+ protocols. The team at StableLab boasts a long and storied history with MakerDAO. Our founders previously worked at the Maker Foundation and later inside Core Units. Our company has maintained active involvement in the DAO ever since. We align fully with the Endgame vision and closely follow its rapid development.

Here are some key initiatives we have spearheaded for our partners, including:

* [Aave Governance Process Update](https://governance.aave.com/t/arc-aave-governance-process-improvements/12234)
* [1Inch 1IP-12: Governance Process Improvements](https://gov.1inch.io/discussion/9363-1ip12-governance-process-improvements)
* [Hop DAO Governance Process V0](https://forum.hop.exchange/t/hop-governance-process-v0/750)

We can help subDAOs at any stage of the framework outlined above. In particular:
StableLab has seen dozens of Discord servers and identified some best practices for structuring channels so that participants can easily onboard and discuss important topics in the appropriate place. We know what works and have experience moderating high-velocity, high-stakes governance chats. Our moderation and structural input allow MakerDAO Core Facilitators to focus on more critical aspects of their work.

We would diligently collaborate with other designated Ecosystem Actors to handle technical aspects. The DAO doesn't have to pay twice for services. 

We also want to support proposal authors by ensuring the community knows about the *actual* state of a proposal through careful moderation and weekly updates. MakerDAO's famed Governance & Risk Calls were an excellent place for governance participants to get up to speed and for open and frank discussion. Anonymity requirements have made these calls harder to execute, but they could be a place for subDAO communities to gather.

Having worked with different temp-check and voting tools, we could propose suitable candidates to SubDAO communities. We are also continuously researching and trying out new approaches. 

StableLab can facilitate and manage these temp-checks, create polls, and communicate to the community when to vote. We ensure that proposals are easy to follow across the various tools and ensure all the Ts are crossed and all the Is are dotted in terms of formatting and numbering.

StableLab can work with other Ecosystem Actors to ensure that a proposal's intent is translated into code and has smart contract development resources to help with spell-checking.

We're particularly excited to leverage our extensive institutional knowledge to ensure that SubDAO governance works towards universal alignment.

StableLab is here to help SubDAOs succeed. We strive to empower SubDAO communities to focus on their unique strengths while simultaneously aiding in the establishment of robust governance frameworks that support their decision-making process.

We kindly request incubating SubDAOs to let us know where we can help support them further. We hope that this simple framework is a reasonable basis for further discussion.
