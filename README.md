# Independent Verification

A general-purpose skill for independently verifying factual claims instead of blindly relying on previous answers.

## What it does

When verification is needed, this skill requires the model to:

* Treat previous answers as unverified hypotheses
* Prefer primary and authoritative sources
* Verify versions, specifications, units, regions, and dates
* Independently recalculate results
* Cross-check important claims
* Explicitly correct previous answers when they are wrong

## When to use

Use when the user asks to:

* verify / recheck / confirm / validate / double-check something
* question whether a previous answer is correct
* verify information that may have changed
* verify important prices, specifications, limits, compatibility, policies, availability, or calculations

The model should also use it proactively when an unverified external fact could materially affect the conclusion.

## Key Principle

> Never use the previous answer as evidence for verifying the previous answer.

The goal is to **rebuild the conclusion from evidence**, not find evidence that supports an existing conclusion.

## Pricing Verification

For pricing, always verify:

**Platform → Product/Model → Version/Spec → Billing Unit → Unit Price → Usage → Final Cost**

Pay particular attention to differences in duration, resolution, model version, region, and billing units.

## Confidence

* **High** — directly verified from authoritative sources
* **Medium** — supported by reliable indirect evidence
* **Low** — incomplete or conflicting evidence
