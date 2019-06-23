# SuperCollider RFCs

RFC (Request for Comment) is an informal way for SuperCollider contributors to discuss large-scale decisions in project direction in a focused environment.

## What does an RFC do?

The RFC process is intended to bring focus and structure to discussions of important changes and new features in the SuperCollider project. It makes it easy to share and collaborate on design documents, and keeps the community organized and goal-oriented in case of controversial proposals.

Visibility and inclusivity are important values for RFCs. They are advertised to both developer and user communication channels so everyone can participate.

The following generally should go through an RFC:

- New features.
- Deprecation of features.
- Significant breaking changes.
- Organizational changes, including changes to the RFC process itself.

The following do not need to go through an RFC:

- Bug fixes.
- Releases of new SuperCollider versions.

## Proposing an RFC

Fork this repository. Copy `rfcs/0000-template.md` to `rfcs/0000-<my-proposal-title>.md`. Fill it out, and make a pull request back to this repository.

Great RFCs are strong and decisive with clear and direct writing. They do a great job at explaining and justifying their motivations and showing the reader what the problems are and how the proposal concretely and practically addresses them.

To help you write great RFCs, we have a template structure for you to fill out. This skeleton helps you write a coherent and persuasive proposal:

- **Summary.** Very short description.
- **Motivation.** Introduce and set the background for your proposal. Some example points of discussion:
  - What specific problems are you facing right now that you're trying to address?
  - Are there any previous discussions? Link to them and summarize them.
  - Is there any precedent set by other software? If so, link to resources.
- **Specification.** A concrete explanation of what is being planned.
- **Drawbacks.** Carefully consider every possible objection and issue with your proposal.
- **Unresolved questions.** Are there any portions of your proposal which need to be discussed with the community before the RfC can proceed? Be careful here -- an RFC with a lot of remaining questions is likely to be stalled. If your RFC is mostly unresolved questions and not too much substance, it may not be ready.

An RFC is only a design document, and does not need to be fully or partially implemented to be approved.

## Discussing an RFC

If you are discussing an RFC, it is your responsibility to work towards **reaching a conclusion**. When you make a post to the RFC thread, talk about the contents of the RFC, and the RFC alone.

It is especially important to address these questions:

- Do you agree with the proposal in its current form?
- Are concerns and questions adequately addressed?
- Do you have suggestions for how the RFC can be revised or expanded, especially in the Unresolved Questions section?

The RFC will likely undergo numerous revisions in the discussion process.

### Don't be shy

Even if you aren't an active SC contributor, or if you don't feel "qualified" to discuss the topic, you can and should directly state your opinion on an RFC that affects you in some way.

Even a brief message like

> I agree with this. X has caused a lot of problems for me and this would be great.

is extremely helpful.

People who disagree with a proposal are more likely to speak up. To counterbalance this, a lot of people simply posting "I agree" will give a good impression of the amount of support in the community.

### Stay on topic

The SC community is an enthusiastic one that loves talking about cool ideas. Unfortunately, tangential discussion often dilutes the thread and makes it hard to actually gauge what the consensus is. **Starting or continuing tangents is disrespectful to the RFC author and is strongly discouraged.**

The purpose of the RFC thread is to reach a conclusion, and any commentary that does not contribute to that is damaging to the RFC process.

### Avoid scope creep

You should make suggestions on how the RFC can be revised or expanded. But be careful not to expand it too much and develop it into something far more ambitious than was originally intended.

### Meetings are great

Whether you're authoring or discussing an RFC, scheduling Skype meetings with others involved is a really great way to move it forward.

## Finalizing an RFC

When it appears that most open questions in the discussion have been resolved and addressed in the RFC's text, a motion for a Final Comment Period may be made. A Final Comment Period lasts 14 days. If no major new developments occur, the RFC is marked as **passed** or **rejected**. The motion for the Final Comment Period may be made by anyone who was involved in the discussion.

## Implementing a passed RFC

Implementation of an RFC can start before, during, or after it has been approved. In fact, if you propose an RFC, you don't need to be the person to implement it. However, usually the implementer is the same person as the RFC author.
