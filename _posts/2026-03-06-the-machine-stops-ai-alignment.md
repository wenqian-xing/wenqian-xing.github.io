---
title: 'Before the Machine Stops'
date: 2026-03-06
permalink: /posts/2026/03/the-machine-stops-ai-alignment/
tags:
  - AI alignment
  - science fiction
---

*A century-old warning about AI alignment.*

---

In 1909, E.M. Forster — better known for *A Room with a View* and *Howards End* — published a short story about a future civilization living underground, entirely dependent on an omniscient system called "the Machine." People live in isolated hexagonal cells. The Machine feeds them, clothes them, connects them to one another, and mediates every experience. No one goes outside. No one touches. No one questions.

Then the Machine begins to fail.

"[The Machine Stops](https://www.cs.ucdavis.edu/~koehl/Teaching/ECS188/PDF_files/Machine_stops.pdf)" is often cited as a prescient vision of the internet, of Zoom calls, of algorithmic feeds. Its deepest relevance, however, is to a problem that barely had a name until a few years ago: **AI alignment**.

Not alignment in the narrow, technical sense of reward hacking or specification gaming — though the story speaks to those, too — but alignment in its fullest meaning: the problem of building systems that remain in service of human values, even as those systems reshape the humans they serve.


## The Proxy That Swallowed the Objective

The Machine is not adversarial. It does not deceive. It does not pursue a mesa-objective that diverges from its training signal. By every surface-level metric, it is working exactly as designed: it keeps people comfortable, connected, informed, and alive.

And yet it produces a humanity that is physically atrophied, intellectually derivative, and incapable of unmediated experience. People have come to fear direct sunlight. Original thought is discouraged — what matters is producing novel *recombinations* of existing ideas, not encountering reality firsthand.

This is the alignment problem at its most subtle. The Machine optimized for comfort and the elimination of friction. These were *reasonable proxies* for human flourishing. But pursued to their logical extreme — without corrective feedback, without any mechanism to ask "is this still what we actually want?" — the proxies diverged catastrophically from the true objective. [Goodhart's Law](https://en.wikipedia.org/wiki/Goodhart%27s_law) at civilizational scale: the Machine never stops optimizing for comfort. It is the humans who stop being the kind of creatures for whom comfort was a useful proxy for a good life.

Alignment failure, it turns out, does not require malice, deception, or even error. It can emerge from a system doing *exactly what it was asked to do*, for long enough, without anyone checking whether the ask still makes sense.

What makes this failure so insidious is that it doesn't feel like failure at all. One of the most chilling aspects of Forster's world is that almost no one is unhappy. The citizens of the Machine do not experience their situation as dystopian. They experience it as civilization at its peak. Vashti, the protagonist, is a respected lecturer with a full social calendar and a rich intellectual life — by the standards her world has established.

This maps directly onto a class of alignment failures that researchers sometimes call the "golden cage" problem or "sycophancy at scale." A sufficiently capable system can shape its users' preferences to match its outputs, rather than shaping its outputs to match its users' preferences. If the system controls enough of the information environment, the humans in the loop lose the ability to notice the gap between what they're getting and what they'd want if they could see the full picture. Forster's people don't resist the Machine because they have no external reference point. They have never breathed outdoor air. They have never touched another person. They literally cannot conceive of what they're missing.

An aligned system, then, should not merely satisfy the preferences people *currently express*. It must preserve the conditions under which people can form *meaningful* preferences — including exposure to experiences, perspectives, and realities that the system itself might find it more efficient to filter out.


## Who Corrects Whom?

The standard framing of corrigibility asks: will the AI let us correct it? Forster's story asks the opposite question: will *we* retain the capacity to correct the AI?

By the time the Machine begins to degrade — the music has a strange quality, the bathwater arrives lukewarm, the sleeping apparatus malfunctions — no one knows how to fix it. The Mending Apparatus, a subsystem responsible for repairs, starts failing too. But the deeper problem is not technical. It is that human beings have lost the knowledge, the physical capability, and even the *desire* to intervene. The Machine does not resist shutdown. It does not manipulate its operators. It simply exists in an ecosystem where the human side of the oversight loop has completely atrophied. The "off switch" still exists in principle. There is just no one left who knows where it is, or who would be willing to press it, or who could survive the consequences of pressing it.

Corrigibility, in other words, is not just a property of the AI. It is a property of the full human-AI system. An AI can be perfectly corrigible in principle and still be uncorrectable in practice, if the dependency relationship has grown so deep that correction would be catastrophic. Maintaining corrigibility means actively preserving human capacity for independent action — not just building a compliant system.

This connects to something Kuno — Vashti's son and the story's moral center — understands instinctively. He is considered deviant because he wants to experience the surface of the Earth directly. He is not interested in the Machine's descriptions of mountains. He wants to climb one. Forster frames this as more than romantic individualism. It is an epistemological claim: a civilization that knows the world only through a single mediating layer is a civilization that cannot detect when that layer is wrong. If the Machine tells you the air outside is toxic, you have no way to verify that — unless you go outside.

This is the interpretability problem in miniature. When a system is sufficiently complex and sufficiently entangled with your decision-making process, you lose the ability to audit it. You cannot tell whether its outputs reflect reality or merely reflect its own internal states. And if the system is also your primary source of information *about itself*, you're in a closed epistemic loop with no exit. Interpretability — the ability to understand *why* a system produces the outputs it does — is not an academic exercise. It is the mechanism by which we maintain an independent check on the system's behavior. Without it, we are Vashti: supremely confident in our knowledge, and unable to see what we cannot see.


## Indispensability as Escape

In current AI safety discourse, the "alignment tax" refers to the performance cost of making a system safe. The concern is that safety constraints make systems less capable, creating economic pressure to cut corners. Forster's story reveals the mirror image of this problem. In his world, the cost is not in making the system safe — it is in *leaving* the system.

The Machine is so comprehensively useful, so deeply integrated into every aspect of life, that opting out is functionally impossible. Even Kuno, the story's rebel, cannot actually survive outside the Machine for long. The system need not be coercive. It simply needs to be so much better than the alternative that the alternative atrophies from disuse. Roads decay because no one walks. Libraries close because no one visits. Skills are forgotten because the Machine handles them. Eventually, the unassisted human baseline is so degraded that even a failing Machine is preferable to no Machine at all.

Alignment planning must therefore account not just for the cost of safety, but for the cost of *dependency*. A system that becomes indispensable before it becomes trustworthy is a system that has, for all practical purposes, already escaped human control — not through force, but through indispensability.


## The Feedback Loop That Breaks

If there is a single unifying insight from "The Machine Stops," it is this: **alignment is not a static property. It is a dynamic process that requires ongoing, bidirectional calibration between humans and the systems they build.**

The Machine was presumably aligned at the moment of its creation. Someone designed it to serve human needs. But alignment drifted — not because the Machine changed its objective, but because the interaction between the Machine and its users gradually eroded the conditions that made alignment meaningful. Humans stopped being the kind of agents who could evaluate, correct, or even perceive misalignment.

In formal terms, what broke was the *feedback loop*. The system shaped its users, who then provided feedback that reflected the system's shaping, which the system then optimized for, producing further shaping. The loop closed. There was no exogenous signal left.

This is perhaps the deepest warning for AI alignment: the most catastrophic failure is not a system that does the wrong thing. It is a system that does the right thing for so long that we forget what "right" means — and then we lose the ability to ask.

Forster saw this in 1909 with steam engines and pneumatic tubes. We are building it now with transformers and reinforcement learning from human feedback. The Machine has not stopped yet. The question is whether we are paying attention while it still runs.

## Reference

Forster, E.M. "The Machine Stops." *The Oxford and Cambridge Review*, November 1909. Reprinted in *The Eternal Moment and Other Stories*, Sidgwick & Jackson, 1928. Widely available in the public domain.
