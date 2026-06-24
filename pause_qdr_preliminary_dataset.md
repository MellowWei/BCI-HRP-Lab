# Preliminary Pause-QDR Dataset

**Status:** exploratory field dataset; not IRB-approved; not clinical; not a treatment study; not evidence of efficacy.

## What this is

This is an anonymized summary of approximately ten static-pause sessions. Participants paused ordinary tasks for roughly 10–12 minutes and provided pre/post ratings for mood, focus, and body state, plus open-ended qualia notes.

The original data source included five open-ended prompts:

1. When did you first notice a state change?
2. Where did the body change?
3. Was quiet itself working, or was pausing daily tasks working, or something else?
4. Where did attention go?
5. Did you want to stop midway?

Raw notes are not included in the public package. This summary is derived for protocol-design and PI discussion only.

## Why this belongs in BCI-HRP Lab

The dataset does **not** demonstrate sound-probe efficacy. Instead, it shows that even without a sound probe, a brief pause can produce measurable and describable shifts in:

- body relaxation / tension
- attentional direction
- perceived focus
- environmental perception
- meaning-making
- task-demand effects
- desire to stop or continue
- qualitative naming granularity

This motivates including a **pause-only baseline** in any future Sound-QDR study.

## Descriptive snapshot

Scale assumptions:

- Mood/focus: higher is better.
- Body tension: lower is more relaxed / less tense.
- P01 body is excluded due to a post-score ambiguity.
- P09 post-mood is missing; P09 focus change is retained but flagged as idiosyncratic.

Descriptive means:

- Mean mood change: **0.81** across N=9.
- Mean focus change: **1.85** across N=10; excluding the idiosyncratic P09 focus score, **0.94** across N=9.
- Mean body-relaxation gain: **2.11** across N=9.
- Participants with positive body-relaxation gain: **6/9**.
- Participants with negative mood shift: **2/9**.

## Preliminary pattern

The strongest descriptive signal is not uniform mood improvement. The stronger pattern is:

> A short pause appears to increase body relaxation and qualia granularity for several participants, while also allowing difficult affect, task demand, or self-evaluation to surface in others.

This is theoretically useful because it prevents over-attributing future Sound-QDR effects to sound alone.

## Implication for the next study

Future Sound-QDR pilots should include at least one pause-only condition:

1. Pause only.
2. Pause + self-report.
3. Pause + sound.
4. Pause + sound + editable QDR naming.
5. Pause + sound + QDR + optional wearable/neural proxies.

This makes it possible to separate:

- pause effect
- context effect
- task-demand effect
- acoustic effect
- interpretive-agency effect
- proxy-signal value
