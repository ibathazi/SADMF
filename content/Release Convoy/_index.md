---
title: SADMF Release Convoy
description: Set Sail with the Scaled Agile DevOps Delivery LifeCycle (SAD DLC)
weight: 1
---

At Scaled Agile DevOps, we believe keeping track of many frequent releases is just too much cognitive load. We need to *"work in small batches."* We've developed the **Release Convoy&trade;** to simplify things. Why try to track dozens or hundreds of releases per week if we can simplify it to one easily managed Release Convoy&trade;?

### Why convoys?

Other frameworks have tried to coordinate things with more limited transportation metaphors. However, they were constrained to a single direction. With Release Convoys&trade; we have more options. We can turn left or right or even make a U-turn.

### Critical Release Convoy&trade; Ceremonies

Below are the simple ceremonies required to manage changes the SADMF way!

#### Shipment planning

This is a 5-day meeting held every 6 weeks for planning the next 8 quarters of features to make sure the critical paths are aligned.

#### Captain's Mast

In this ceremony anyone wishing to change the priorities set in Shipment Planning must file a "Priority Change Request" and represent it for approval. This allows the Chief Signals Officer to adjust the *[Completed vs Committed metric](../metrics/#features-completed-vs-committed)* to ensure it does not reflect poorly on the Commodore.

#### Captains' Meeting

Meeting of the Feature Captains to plan the date when the Release Convoy&trade; will be assembled.

#### Press Gang

In the Press Gang step, the Feature Captain will choose between 2 and 20 people from the coding pool to "self-organize" around delivering the next feature. This ensures each coder is given the opportunity to work on new and interesting things and that all coders are fully utilized.

#### Post Standup Standup

We understand that only the most important status updates are given in Standup and that some defects are lower priority than some features. To address this, we use the Post Standup Standup ceremony. Here everyone on the Convoy participates to provide status updates to the Commodore on the lower priority work that is not being worked on.  

#### Post Standup Standup Review

To ensure no information is lost through insufficient documentation, each Feature Captian will also submit a daily report using the SAD Update form and email it to the Commodore who will consolidate it and file it.

#### Manufacturing

The group of coders assigned to each feature will implement the requirements they are given as rapidly as possible using the industry best practice, *[Continuous Isolation](https://continuousisolation.com)*. This ensures it can be tested and delivered on the Convoy it is planned for. Once the feature is coded, the coders can return to the coding pool to await their next adventure!.

#### Testing

The to keep the coders productive, we need them to focus only on coding. For unit testing, the Feature Captain will assign the complete feature to the Unit Testing Team to ensure 100% test coverage.

#### System Integration Testing

If two teams validating a change are good, three teams are better! This SIT team tests all of the new features of the Convoy together.

#### Convoy

The convoy coordinates transportation of the features that were planned. The Commodore is responsible for keeping the convoy together.

#### Tribunal

We must "build quality in" by removing things that cause poor quality. In this monthly ceremony we identify and remove the person who created each defect.

#### Dry Dock

It's normal for a little wear and tear to occur when we are moving so quickly. Defects will accumulate. The Dry Dock is the process of halting feature development for a few weeks so that repairs can be made.

#### Rota Fortunae

We know that a static organizational structure limits improvement and also becomes boring for some executives. While many outside the SADMF community may propose Value Stream Mapping to identify constraints, we know that the process is time consuming and uses too many Post-Its. To resolve these we introduced the Rota Fortunae ceremony where we "spin the wheel", restructure, and then see if we are delivering better. If we fail, then we convene a [Tribunal](#tribunal) to address it.

#### Branching Strategy

CFF branching strategy. To ensure high quality, new branch creation is recommended for every task in the story. To be able to meet high quality standards it is also recommended to have planned half week merging team exercises in every sprint. If multiple teams are working together on same products and half week is not enough, teams are allowed to expand this excercise to a week or even longer if needed. 
Note: bonus points can be earned if stories have to split to next sprint to double the fun.
