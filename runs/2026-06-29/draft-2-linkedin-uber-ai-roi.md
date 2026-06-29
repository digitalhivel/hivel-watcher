# DRAFT: LinkedIn Post
**Signal:** Uber abandoned "developer years saved" and moved to feature velocity — GetDX (competitor)
**Format:** linkedin_post
**Priority:** urgent
**Turnaround:** same day
**Angle:** differentiation
**Theme:** AI ROI
**Signal source:** https://newsletter.getdx.com/p/ubers-journey-of-measuring-ai-impact
**Status:** in_review

---

Uber just shared how their AI ROI measurement broke. Twice.

Their first framework tracked developer satisfaction. It told them people liked the tools, not whether the tools were working. Their second framework tracked developer years saved. Leadership loved it until engineers started gaming it, and until no one could explain what it actually meant to the board.

So Uber moved to feature velocity. How many customer-facing features shipped, and how fast.

This is the right direction. But there is a measurement gap in how they got there.

Feature velocity is hard to attribute when you do not know which commits were AI-generated versus human-authored, and which of those made it past review and into production. Accepted suggestions are not shipped code. PRs opened by an agent are not outcomes. A sprint with 5x more commits and 2x more bugs is not faster delivery. It is faster failure.

Teams we have analyzed show an average of 18% of AI suggestions reaching production. The rest stays in branches, gets reverted, or ships quietly as a defect. That is what your acceptance rate metric is hiding.

Hivel tracks the full chain: AI suggestions to accepted code to production-merged commits to business outcomes. That is the number you can take to the board without it breaking on the first question.

Here is what we see instead: hivel.ai/ai-impact

---
*Word count: ~230*
