# BCI-HRP Lab: Sound-QDR Protocol Brief

**Status:** Draft collaboration brief. Not IRB-approved. Not a clinical, diagnostic, crisis-detection, treatment, or neural-decoding protocol.


## Preliminary Phase -1: Pause-QDR Observational Dataset

Before testing sound probes, an exploratory static-pause dataset was collected from approximately ten participants. Participants paused ordinary tasks for roughly 10–12 minutes and provided pre/post ratings for mood, focus, and body state, plus open-ended qualia notes.

This dataset is **not** evidence of Sound-QDR efficacy. It is used to motivate a pause-only baseline. Descriptively, the strongest observed pattern was body relaxation and increased qualitative granularity, with heterogeneous mood responses and visible task-demand effects.

See:
- `pause_qdr_preliminary_dataset.md`
- `pause_qdr_preliminary_summary.csv`
- `pause_qdr_limitations.md`
- `pause_qdr_codebook.md`


## Data File Clarification

`data_schema.csv` is a future protocol data dictionary, not the static-pause preliminary dataset.

The anonymized derived static-pause summary is:

- `pause_qdr_preliminary_summary.csv`
- `pause_qdr_preliminary_dataset.md`
- `pause_qdr_limitations.md`
- `pause_qdr_codebook.md`

## 1. Research Question

Does a sound-probe + self-prediction + editable naming protocol improve within-person self-calibration, and do autonomic/neural proxies add explanatory value beyond self-report alone?

## 2. Candidate Hypotheses

**H1 — Prediction calibration.** Across repeated sessions, participants' pre-probe prediction error will decrease within person.

**H2 — Naming stability and granularity.** Across repeated sessions, participants will move from generic affect labels toward more stable, differentiated bodily-affective-perceptual-action descriptions.

**H3 — Proxy value.** Wearable/neural proxies will add explanatory value beyond self-report only in some participants or sound families, and only after data-quality filtering.

## 3. Phase 0 Design

- **Study type:** within-subject feasibility pilot.
- **Participants:** N = 5–12 non-clinical participants.
- **Purpose of N:** usability, data quality, adverse UX discovery, and variance estimates for a later powered study.
- **Duration:** partner lab determines; recommended 2–4 weeks or repeated short sessions.
- **Core claim boundary:** no diagnosis, no treatment, no crisis detection, no hidden-emotion inference.

## 4. Session Flow

1. Consent gate: sound family, intensity ceiling, stop method, data sharing, AI summary permission.
2. Baseline: short rest + self-report; optional physiological baseline.
3. Prediction: user predicts direction and intensity of state change before the sound.
4. Probe: fixed documented sound file with event markers and stop controls.
5. Report: body, affect, perception, action tendency, meaning.
6. Rename: accept / edit / reject / rename / delete / skip / stop / ground.

## 5. Outcomes

**Primary outcome:** within-person change in pre-probe prediction error.

**Secondary outcomes:**
- State-naming stability.
- Qualia granularity.
- Interpretive-agency events.
- Completion rate.
- Discomfort / stop / grounding events.

## 6. Confounds and Controls

**Stimulus familiarity confound:** prediction error may decrease because the participant memorizes a clip, not because self-calibration improves.

Controls:
- Transfer test on unheard stimuli from the same sound family.
- First-exposure prediction-error analysis.
- Novel-vs-familiar factor in the model.
- Report naming stability with the same familiarity-control logic.

## 7. Optional Signals

Self-report first. Wearables second. EEG/fNIRS optional and lab-dependent.

- HRV/RMSSD
- EDA/SCR
- respiration proxy
- skin temperature
- motion
- optional EEG/fNIRS quality flags

Physiological signals are proxies, not hidden truth.

## 8. Analysis Sketch

- Mixed-effects model for within-person change.
- Event-locked descriptive analysis.
- Ablation comparison: self-report only / sound + self-report / wearable + sound / optional head proxy + sound.
- Missing-data report.
- Artifact report.
- Individual trajectory plots.

## 9. Safety Boundary

This protocol is not a crisis system. High-risk disclosures leave the protocol and follow lab-approved human safety procedures.

Safety interaction requirements:
- Persistent Stop / Ground / Volume Down / Skip / Delete.
- Auto-pause triggers.
- Grounding mode suppresses deep interpretation.
- Stop / reject / rename / delete are primary outcome events, not UI afterthoughts.

## 10. What the Lab Decides

The partner lab may narrow, rename, reject, or split constructs before preregistration. The lab should lead IRB, recruitment, signal processing, statistical modeling, and safety review.
