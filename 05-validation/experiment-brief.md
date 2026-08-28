# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

A/B test (50/50 split), run at the trial-cohort level. This is a single, discrete change to onboarding and the habit loop — not multiple competing variants needing dynamic traffic allocation — so a clean control group is enough to isolate the effect. It also gives an unambiguous causal read before we commit the personalized onboarding + habit loop to all trial users.

_____

## Hypothesis + primary metric

If we replace generic sign-up/onboarding with a personalized flow (user-type quiz + fast result on real data) and add the Trigger→Action→Reward→Investment habit loop (open-item banner/email → categorize → forecast update → invite collaborator), then Trial→Paid conversion rate will increase from the current 2% baseline toward 8%.

_____

## Guardrail + read date

- **Guardrail:** One-year retention rate must not decrease. We’re fixing a conversion problem (2%) without making the retention problem (40%) worse — if the personalized paywall converts more users who then churn faster, that’s not a win. Guardrail threshold: retention must not drop by more than 3 percentage points from the 40% baseline.
- **Read date:** _set before launch, no peeking. Given trial length (~14 days) plus time to observe the habit loop’s first cycle, read the primary metric at 4 weeks post-launch; read the retention guardrail at 90 days post-launch, since retention can’t be honestly assessed on a shorter window._
