# "Unhealthy Comparisons to Promote Healthy Behavior?": Exploring the Impact of Social Comparison Strategies in Personal Informatics

### Citation

**Authors:** Daphne van Zandvoort, Marloes Vredenborg, Marit Bentvelzen (Utrecht University)
**Year:** 2025
**Conference:** CHI 2025

### Research Problem

What problem does this paper try to solve?

Health apps use social comparison everywhere, leaderboards, "you vs. others" stats, feeds of what other people are doing, and it's mostly just assumed to be motivating. The authors ask the question nobody bothers with: motivating at what emotional cost, and does that cost depend on what's actually being compared?

### Main Idea

They treat social comparison as a bundle of separate design choices, not one feature. Which strategy you use, which metric you compare, and who you're compared to all seem to matter independently, so "add social comparison" isn't really a single decision.

### Method

Reviewed the top 50 health & wellness apps (42 qualified) to see how comparison shows up in practice, then ran a vignette survey (n=192) testing different comparison setups on two metrics, steps and body fat, then did interviews (n=12) to hear how it actually feels.

### Key Findings

- Comparison does motivate, but it never comes alone, negative emotions like inferiority and disappointment showed up right next to it, not as rare exceptions.
- Metric choice matters a lot. Body fat comparisons hurt more than step comparisons across the board, even in the best-case scenario. Steps stayed pretty safe no matter how they were compared.
- Being shown someone doing better than you hurt more than being shown someone doing worse helped. Direction of comparison wasn't a minor detail, it was one of the biggest effects in the study.
- In interviews, people described real harm over time, obsessive checking, adjusting training to keep up with others, even injuries, and several had quietly built their own coping habits like hiding their data or only following people they wouldn't feel compared to.

### Open Questions I'm Sitting With

- This paper studies comparison built to motivate. My system isn't trying to motivate anyone, it's trying to help them reflect. I don't think this paper tells me whether the same emotional cost shows up when the framing is "here's someone else's experience" instead of "here's your rank."
- If my retrieval step just grabs the most similar peer experience without checking direction, am I quietly defaulting into the upward comparisons this paper flags as the riskiest?

### Why This Matters For My Research

This is a real stress test for the social branch in my pipeline. I'd been treating "retrieve peer experience and show it" as one step, this paper makes me think it's at least two: which metrics are even safe to compare, and which direction the comparison runs. It's also given me an actual reason, not just a hunch, to keep leaning narrative over leaderboard-style for that branch.
