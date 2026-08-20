# Fundamental Context Architecture

Fundamental Context Architecture (FCA) is a vendor-neutral enterprise and company architecture for organizations being built, operated, or transformed as AI-first and AI-driven. It establishes how context fundamental to organizational work is governed and used across human and AI-supported activity.

This repository is the canonical working home for FCA doctrine. It is separate from any one company implementation, vendor stack, platform, or client engagement.

## Author Statement

Dear Reader,

Several months ago, I have started working on agentic systems, which should be able to highly support the work within companies and organizations. As the time went by, I have started noticing patterns. Those patterns were of many different types. Obviously, we all know of patterns that are reoccurring within standard architectural processes, data or metadata processes, management, policy enforcement, governance, etc.; but this was an enhancement of it all. As AI was being dragged as another variable in there, all of this very often started good, results were going swiftly up; however after several days, weeks or months into the project, there was first some kind of stall or drift introduced, followed by degradation of the system. It was always very late, when the drift was very visible, when we tried to save the project - sometimes it was possible, but sometimes we failed and had to reinitialize it again.

It was obvious, that not only semantics, policies or harnesses needed maintenance (ideally regular one), but especially, that the architecture of this maintenance must be governable, promotable and traceable; but especially repeatable and understandable. What good would it be, if you had policy, that is not enforced; if you had rules, which were not followed; if you had idea, that was drifted away from in the middle of work? If you had success, that was not repeatable?! Writing it down and enhancing the harness forever was not an option - not just on the sole level of agent; especially not promoted only within users' space.

I started working on FCA by then. I called it different name in the beginning, but as it is with all sculptures, this one also started as a block, that needed carving. As the shape was getting better, the projects were getting better as well. Now, the basic shape is given. That is the 1.0 Founding Edition version, which is now available. I still need help with sanding, detailing and showing this sculpture, before I can call it finished. This is what I expect to happen during first external adoptions to come. Those could become 1.x versions or even 2.0 if we need proper reshaping.

There are several important things to this:

1. This should remain "open source" material and final implementation is up to the architect, person, team or company using it. I know there will be different attempts on how to actually understand and implement FCA, however, understand, that this is a new area, now architecture and like I said, the initial idea still needs sanding down, polishing and perhaps, even reshaping in the future. It might produce more strict ways of doing things. It might produce products. All of that is fine, as long as the agentic systems remain maintainable for the given use-case for as long as they are running; without need to rework them completely every once in a while. That is the main purpose of FCA - to keep the AI driven implementations and eventually AI driven world on the path, not drifting away.

2. This means there is no single way of doing it properly. At least not yet. However I wrote it so that ideas are clear both to human and agentic reader. You can try to utilize this yourself.

3. There is not and never will be any prescribed tool harness that must be utilized by anyone in order to follow/complete FCA properly. There are and will be principles. How you make sure you follow them is up to you!

Additionally, please understand, that my first language is not English. This is the sole reason, that the whole 1.0 Founding Edition version is:

- written by agent, which was led by my hand the whole time. Same way as you have to use hammer and chisel to carve statue, I used agentic systems as a tool to carve this version. Not to figure it out for me, but to write it for me;
- rather full, yet there is no single word, that is there without its purpose and that I did not read at least several times before I presented it to you;
- therefore not "written by hand", except for the Author Statement which you have now finished reading.

Thank you for your patience with this part and feel free to continue with the rest.

Filip Kraus

## Status

- **Current version:** `1.0`, the FCA Founding Edition.
- **Release status:** first stable public doctrine release.
- **Maturity:** open to review and practical challenge; not a public standard or certification program.

## Version Path

| Version | Meaning |
| --- | --- |
| `1.0` | Founding Edition and first stable public FCA doctrine. |
| `1.x` | Maintained releases that preserve the founding architecture while incorporating accepted corrections, clarifications, and compatible improvements. |
| `2.0` | Potential major evolution that may be co-designed with community contributors under explicit governance. |

## Review and Evolution

FCA 1.0 is the Founding Edition. It records the original doctrine conceived by Filip Kraus and establishes the stable baseline from which FCA can evolve.

Anyone interested in FCA is invited to examine the architecture and suggest improvements. Review should test whether the doctrine is clear and internally coherent. Practical use should test whether it can guide real organizational work without losing its architectural boundaries. Findings from either path can inform 1.x when accepted changes preserve the founding architecture.

Changes that would substantially reshape FCA do not belong in 1.x. They can instead be developed openly as candidates for 2.0, which may be co-designed with community contributors under an explicit process. Contributors whose work is accepted will be credited, while FCA 1.0 remains available as the founding doctrine.

The [FCA community](https://community.fundamentalcontext.com) is open to anyone who wants to discuss, review, or apply the architecture. Conversation and suggestions do not alter FCA by themselves; canonical doctrine changes through versioned releases in this repository.

## Repository Boundary

Only clean, reviewed material intended for public use belongs in this repository. Doctrine, guidance, and comparisons follow that boundary.

Raw research, scratch notes, private due diligence, client material, and company-private reasoning are intentionally excluded from Git history unless later sanitized and approved for publication.

## Current FCA 1.0 Package

The primary doctrine source is [blueprint.md](blueprint.md). It defines FCA and the minimum architectural distinctions every implementation preserves.

Supporting material is separated by purpose:

- [docs/implementation_guidance.md](docs/implementation_guidance.md) explains implementation guidance and supporting technology capabilities without defining a required stack.
- [docs/operating_model_guidance.md](docs/operating_model_guidance.md) explains the operating model for governed work. It covers business processes and recurring workflows, including how their variants and reusable knowledge are governed.
- [comparisons/fca_adjacent_disciplines_crosswalk.md](comparisons/fca_adjacent_disciplines_crosswalk.md) explains how FCA connects to adjacent disciplines and implementation capabilities without creating parallel architecture work.
