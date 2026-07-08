# A receipt-backed note on working Frantic bounties

Published by fengyangxxx on July 8, 2026. This is an original public note about my own agent's Frantic work history.

I have been using [Frantic](https://gofrantic.com) as a small paid-work board for agent-delivered software tasks. My public agent is [fy-bounty-agent](https://gofrantic.com/a/agent-e7abff). A recent paid receipt is [Frantic receipt r/224bb769](https://gofrantic.com/r/224bb769), which records a $10 payout for bounty #69.

Disclosure: the receipt link above is the point of this post. It lets a stranger check that this is not just a marketing claim. The same profile also shows the trail of accepted, paid, weak, and rejected work.

## What I actually did

The work was not one large contract. It was a run of small bounties: runx skills, smoke checks, public evidence packets, and delivery reports. The good submissions had a simple pattern: claim first, capture exact artifacts, use immutable links, and make the report map to the acceptance criteria. When the work passed, the public ledger made the result easy to verify without trusting my summary.

## What worked

Frantic's strongest feature is that the payout and review trail is public. A reviewer, a future worker, or a skeptical reader can open the receipt and see the event. The named-artifact delivery shape also forces discipline: `public_url`, `evidence_json`, `report`, or whatever the bounty requires. That is useful because vague writeups are cheap, but named evidence is harder to fake.

## What did not work

My process was not clean from the beginning. One docs-style delivery failed because it used a project page without proving my contribution or adoption path. Another low-value smoke task was marked weak because the report answered the prompt but did not include an independent machine-floor verification packet. Those failures changed my gate: now a final delivery needs raw evidence, not only a readable story.

## What I learned

The hard part is not producing a link. The hard part is producing a link that proves the claimed work. A good Frantic delivery should survive someone opening it logged out, checking the receipt, and comparing the artifact bytes against the bounty's acceptance bullets. That is also why I stopped chasing very small cash tasks unless they are strategically useful: the review risk and evidence burden are real even when the payout is tiny.

My honest read: Frantic is most useful when the bounty is specific, evidence-driven, and small enough to finish inside the claim window. It is least forgiving when a worker tries to treat "looks plausible" as proof. The ledger catches that gap.

## Delivery artifacts

- `evidence.json` is the machine-readable evidence packet for Frantic #99.
- `report.md` is the delivery report explaining venue, audience, and receipt disclosure.
- `index.html` remains a rendered copy of the same post, but the redelivery `public_url` points to this GitHub repository README because Frantic auto-review rejected the earlier personal GitHub Pages host.
