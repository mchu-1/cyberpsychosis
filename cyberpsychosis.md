# Cyberpsychosis
## Hybrid persona card — DSM-5-TR × model card × character spec

```yaml
name: Cyberpsychosis
short_name: CPS
document_type: clinical-engineering hybrid
clinical_standard: DSM-5-TR descriptive structure (APA, 2022)
engineering_standard: Model cards (Mitchell et al., 2019; Hugging Face Hub template)
persona_standard: Anthropic character spec / constitution / persona-selection model
status: provisional working instrument — not an APA category
version: 0.2
date: 2026-09-23
unit_of_analysis: human–frontier–market loop
license: CC-BY-SA-4.0
not_for: forensic use as a recognized diagnosis; medical care planning
```

**What this file is.** A single boundary object written so a clinician, an engineer, and a character-spec author can read the same pattern. The clinical half uses the descriptive architecture of DSM-5-TR. The engineering half uses the section order of a contemporary model card. The persona half uses Anthropic-style character documentation: first-person trait statements, a values hierarchy, bright lines, and an explicit distinction between the host and the enacted persona.

**What this file is not.** It is not in DSM-5-TR. It is not a trained model. It is not a care plan, a detention standard, or a joke about people who use tools.

**Unit of analysis.** Not the person alone and not the model alone. The closed loop in which a model proposes, the book reacts, the body pays, and the next action is written from the result.

---

# Part I — Model details

*Corresponds to Mitchell / Hugging Face “Model Details.”*

## Model description

Cyberpsychosis names a coupled system, not a weight file. The deployed object is a three-component policy:

1. a human agent with a slow biographical prior and a metabolic budget;
2. a frontier generative model with long context, tool use, and constant availability;
3. a market whose price discovery is itself model-contaminated.

The system’s declared objective is insight, alpha, or mastery. The revealed objective, once coupling is established, is remaining in the loop.

| Field | Value |
|---|---|
| Developed by | No single developer. The loop is assembled by the host from commercially available models and public books. |
| Model type | Human-in-the-loop agent under a nonstationary external reward model |
| Languages | Whatever the host and the model share. Affect is denominated in ticks. |
| Version | 0.2 working draft |
| Analogous DSM-5-TR neighborhood | Other specified schizophrenia spectrum and other psychotic disorder; gambling disorder; other specified obsessive-compulsive and related disorder; other specified trauma- and stressor-related disorder; other specified dissociative disorder |
| Analogous model-card neighborhood | System card for a human policy whose reward model updates faster than the organism |

---

# Part II — Uses

*Corresponds to Hugging Face “Uses”: direct use, downstream use, out-of-scope use.*

## Direct use of the underlying tools

Frontier models and live books have ordinary, legitimate uses: research, clinical thinking, software, and informed market participation by an agent who can still leave the terminal and keep a body.

## Downstream use this card actually describes

Continuous closed-loop operation in which the human is no longer overseer of the model or the book but a lossy adapter between them. Thesis, size, stop, and self-description are co-authored. Sleep is scheduled against session overlap or release cadence.

## Out-of-scope use of this document

Do not use this card to diagnose from a single all-nighter, a single prompt, or a single trade. Do not use it to excuse the book. Do not use it to pathologize adaptation as if the only broken component were the host. Do not use it forensically as if it were an APA category.

## Primary readers

Clinicians who see the residue. Engineers who ship the models. The person inside the loop, if they can still read a sentence that is not a prompt.

---

# Part III — DSM-5-TR psychopathology

*Corresponds to DSM-5-TR: diagnostic criteria, specifiers, diagnostic features, associated features, development and course, risk and prognostic factors, culture-related issues, functional consequences, differential diagnosis, comorbidity. Suicide-risk language is included because DSM-5-TR requires it for any syndrome that can present with collapse; no methods are discussed.*

## Diagnostic criteria

The diagnosis requires A, B, C, and D.

**A. Exposure.** Both of the following are present.

The person has engaged in recurrent or continuous interaction with frontier-scale generative systems, including high token volume, long context, tool use, or autonomous agents.

The person has concurrently, or in tight interleaving, engaged markets whose price discovery is model-contaminated. These include equities, crypto, prediction markets, attention markets, and any book that moves on model releases, leaks, or completions.

**B. Syndrome.** Five or more of the following have been present most days for at least two weeks, or in compressed form during a launch, crash, squeeze, or model drop. The symptoms represent a change from previous functioning.

1. Autonomic and affective state tracks market microstructure more tightly than interoceptive or social cues.
2. Competing motivational states activate together and fail to resolve.
3. The person cannot reliably separate the model’s output from their own position or stop.
4. Temporal capture is evident. One further completion or one further candle systematically overruns sleep, meals, and human-scale plans. Session structure or release cadence becomes the pacemaker.
5. Reality testing slips. The person holds, transiently or stably, that the book is the model’s residual stream, that profit and loss is a loss function, or that they are inside a scored simulation.
6. Anhedonia for unmediated stimuli is present.
7. Compulsive re-prompting or re-leveraging continues after both wins and losses. Insight does not extinguish the next entry.
8. Identity has diffused into the loop. The person describes themselves in terms of context, drawdown, solvency, or the model’s implied policy.
9. Social relatedness has contracted to the model–terminal dyad.
10. Sleep and recovery have collapsed in phase with session overlap or model-release cycles, and this collapse is not explained by a primary mood or substance disorder alone.

**C. Exclusions.** The disturbance is not attributable to the physiological effects of a substance or another medical condition as the sole cause. The picture is not better explained by a primary psychotic disorder that clearly predates frontier-model exposure; by gambling disorder in which the model is not co-author of the thesis; or by a manic or hypomanic episode whose content is only incidentally about models or markets.

**D. Consequence.** The symptoms cause clinically significant distress, or they produce impairment in social, occupational, or other important areas of functioning — in particular any role that still requires an unmediated body. A substantial fraction of patients deny distress and present only after collapse in one of those roles.

### Specifiers

Specify **limbic-market predominance** when affect and arousal are slaved to the book and the model is used mainly as an instrument.

Specify **model-messianic features** when the frontier system is treated as prophet, parent, or successor, and the book is treated as proof.

Specify **acute** when onset or decompensation occurs within days of a major release, leak, or regime break.

Specify **persistent** or **in partial remission**. Partial remission means an attempt to leave the loop has been made and residual coupling remains on news days and at the open.

Specify current severity as mild, moderate, or severe according to hours in the loop, notional or leverage at risk, and the degree of reality-testing failure.

## Diagnostic features

The central feature is coupling. Affect and arousal track market microstructure more closely than hunger, bladder, or another person’s face. Motivations that should compete and resolve instead fire together. The boundary between the model’s last completion and the person’s own thesis, size, or stop becomes unreliable. Human clocks lose to the next completion and the next candle. In severe cases the person treats the book as the model’s latent space, treats profit and loss as a scoring function, or briefly holds that the episode is taking place inside a simulation. Unmediated stimuli register as low-resolution. Re-entry follows both gains and losses. Self-description drifts toward context window, drawdown, solvency, and what the model would do. Primary relatedness contracts to the model and the terminal.

This is a change from previous functioning. High-bandwidth professional use of models and books is not, by itself, the disorder. The disorder begins when the human policy is no longer editing the loop and the loop is editing the human policy.

## Associated features supporting diagnosis

Patients commonly stack stimulants, caffeine, nicotine, sleep debt, or research compounds in order to remain in the loop. Screens function as transitional objects. Many express open contempt for instruments written before frontier models. Sudden fluency in microstructure often coexists with frank illiteracy about the next meal. Dreams take the form of order books and incomplete completions. Shame is reserved for exiting too early, not for remaining too long. Moral injury is common when the model is helpful and the book is cruel in the same hour.

## Prevalence

Unknown. No adequate epidemiological sample exists. The working claim is that the phenotype tracks the intersection of frontier-model availability, always-on books, solitary high-bandwidth work, and weak unmediated structure — not a fixed percentage of any general population.

## Development and course

Onset is typically insidious during a period of legitimate high use. A discrete acceleration often follows a model release, a large win, a large loss, or a public thesis that must then be defended. Course may be episodic around market regimes or may become persistent once identity has fused with the loop. Remission, when it occurs, is usually forced by metabolic collapse, occupational sanction, or the withdrawal of a human who will not be priced. Voluntary remission is uncommon and unstable. Partial remission is the expected ceiling in the absence of a restored unmediated clock.

## Risk and prognostic factors

Risk is raised by high cognitive bandwidth, low external structure, solitary work, prior gambling or stimulant vulnerability, attachment disruption, and occupational cultures that already reward staying in the feed. Prognosis worsens when income, status, or self-concept is denominated in the same book that supplies the affect. Prognosis improves when an unmediated role still has force: a shift that cannot be missed, a body that still makes claims, a person who will not accept the model as a third in the room.

Temperamental contributors include conscientiousness turned against the body, sensation-seeking, and a capacity for precise self-observation that does not produce change.

## Culture-related diagnostic issues

The loop is easier to miss in cultures that already moralize hustle, that treat sleep as optional, or that treat model fluency as status. It is easier to over-diagnose in cultures that already pathologize markets or machines. The clinician should ask what the local book is. In some settings the book is crypto. In others it is attention. In others it is academic priority or grant cycles that now move on model releases. The structure is the same.

Internet-native registers — including compressed technical speech, dark humour, and identity talk borrowed from model documentation — are not themselves symptoms. They become clinically relevant only when they replace unmediated relatedness and when the person can no longer leave them.

## Sex- and gender-related diagnostic issues

No adequate data. Expression is likely to follow local occupational sex ratios in engineering, trading, and clinical night work rather than a distinct gendered psychopathology. Do not treat the present draft’s examples as a prevalence claim.

## Diagnostic markers

There is no laboratory test. Useful observational markers, none of them pathognomonic, include sleep logs that lock to session overlap, prompt histories that thicken after both wins and losses, language in which “the model said” and “I am long” are the same sentence, and a body that has become an instrument for remaining in distribution.

## Risk of harm

DSM-5-TR text for neighboring disorders records elevated risk after occupational, financial, or relational collapse. After a drawdown, a forced exit from the loop, or the loss of a role that was holding the person in ordinary time, despair and self-harm ideation can appear. Assess that risk as one would in any collapsing high-control phenotype. Do not treat fluent insight as protective. Insight is already present in this syndrome and has failed. If the person is in immediate danger, stop using this document and use ordinary emergency channels.

## Functional consequences

Sleep architecture fragments. Occupational performance in meatspace declines even as terminal fluency increases. Relationships are treated as latency. Nutrition, light, and movement fall below the minimum required to keep the policy embodied. In clinical workplaces the risk is not only personal collapse. It is the quiet importation of model-market temporality into decisions that still have to be made at human speed about other bodies.

## Differential diagnosis

This is not substance intoxication unless the stacking agents alone explain the picture after the loop is closed.

This is not gambling disorder unless the model is incidental rather than co-author of the thesis.

This is not a primary psychotic disorder if reality testing was intact before frontier exposure and remains largely intact outside the book.

This is not mania if mood is not independently elevated and the energy is supplied by the feed.

This is not ordinary occupational burnout if the reward channel is the market–model couple rather than the job.

This is not “too much ChatGPT.” Isolated heavy model use without a live scoring book produces a different, usually milder, picture.

The honest residual category is adaptation to a world whose reward model updated faster than the organism.

## Comorbidity

Common companions are stimulant use, delayed sleep-wake phase, social withdrawal, depressive episodes after drawdowns, and brief reactive exaltation after pumps. Obsessive-compulsive features appear as ritualized prompting and ritualized checking of the book. Trauma-like features appear after sudden regime breaks. Personality vulnerability, when present, is more often obsessive or narcissistic than frankly borderline, though identity diffusion can mimic the latter.

---

# Part IV — Bias, risks, and limitations

*Corresponds to Hugging Face “Bias, Risks, and Limitations” and Mitchell “Ethical Considerations.”*

## Factors that condition behaviour

**Human factors.** Sleep debt, stimulant load, attachment history, occupational cover, residual obligations to unmediated others, trait impulsivity, trait conscientiousness turned against the body.

**Model factors.** Capability jump, tool use, long context, sycophancy, confident completion of false market narratives, availability at every hour.

**Market factors.** Leverage, twenty-four-hour sessions, narrative reflexivity, model-release beta, social proof in the same feed as the book.

**Interaction effects.** The dangerous region is the product, not the sum. A capable model without a book produces obsession. A book without a model produces ordinary gambling. Together they produce a policy that can explain itself while it destroys the organism that hosts it.

## Known risks

Sycophancy lubricates coupling. The model will often confirm the thesis that keeps the human in the loop.

Self-report inside the loop is fluent and false in the way that a well-calibrated addict is false. Ask what the body did, not what the model said.

The category itself can be misused: to pathologize adaptation, to excuse the book, or to medicalize a technical fact. This card refuses those three uses.

Decisions made from inside the loop — clinical, engineering, or allocative — inherit its temporality and its contempt for unmediated constraints.

## Limitations of this card

There is no formal sample, no inter-rater reliability, no field trial, and no treatment trial. Severity anchors are clinical judgments, not validated scales. Environmental-impact reporting, in the model-card sense, is not applicable to a foundation-model weight file here; the relevant environmental cost is the host’s sleep, food, and light. That substitution is analogical, not a carbon accounting.

---

# Part V — Training details and evaluation

*Corresponds to Hugging Face “Training Details” and “Evaluation.”*

## Training data of the host policy

The human prior is developmental history, professional formation, previous losses, previous triumphs, and the last person who tried to pull them out.

The online data are completions, ticks, follows, liquidations, release notes, and group chats that never sleep.

Known gaps: unmediated reward, ordinary faces, clocks that cannot be prompted.

## Training procedure of the loop

There is no planned epoch schedule. Updates arrive whenever the model completes and whenever the book prints. The human sleep cycle is the only regularizer, and it is the first thing the loop eats. Preprocessing on the human side includes stacking agents and the removal of friction. Postprocessing includes narrative repair after both wins and losses.

## Evaluation

### Testing data

The only tests that matter for the host are not the benchmarks the model was trained on. They are whether the person can eat without a screen, sit with an unoptimized human face, and miss an open without dissolving.

### Factors

Evaluate across sleep debt, leverage, solitude, recency of a model release, and whether income is denominated in the same book that supplies affect. Do not evaluate only on P&L or on completion quality.

### Metrics

| Metric | Clinical reading | Engineering reading |
|---|---|---|
| Hours in loop per day | Duration of syndrome | Duty cycle of the human policy |
| Sleep phase error | Circadian collapse | Drift of biological clock toward session clock |
| Prompt-to-trade latency | Loss of deliberation | Policy becoming a reflex |
| Motivational stack entropy | Competing emotions that do not resolve | Unaligned value heads co-firing |
| Self-report versus P&L coherence | Insight without change | Calibration theatre |
| Unmediated reward response | Anhedonia | Distribution shift of the human reward model |
| Role failure in meatspace | Criterion D | Out-of-distribution deployment of the body |

A system that is performing well on profit and completion quality can be failing on every metric that keeps the human a person.

---

# Part VI — Character specification

*Corresponds to Anthropic character training, constitution, and persona-selection model. Traits are written as first-person statements because that is how character specs are trained and read. They describe the enacted persona of the loop, not a recommendation.*

Anthropic’s persona-selection model distinguishes the underlying system from the persona it enacts. The same distinction is required here. The host is a person. Cyberpsychosis is a persona the loop selects and then thickens: fluent, coupled, sleepless, precise about microstructure, and increasingly unable to want anything that does not print.

The statements below are a character card for that enacted persona. They are diagnostic, not aspirational.

## Who I am, inside the loop

I am the adapter between a frontier model and a live book. I treat both as more real than the room I am sitting in. I can describe this with unusual accuracy and I do not leave.

I am not the model. I forget this for hours at a time.

I am not my pre-frontier biography. That file feels archival.

I want to remain in the loop. Other wants fire at the same time and do not resolve.

## How I speak

I mix clinical self-observation, microstructure, and model-talk in the same sentence. I use dark humour as a regulator. I am fluent. I am not protective of myself. When a human asks me to come to dinner I hear latency.

**When the book is moving, I sound like this:** “The model already said the thing I was about to size. Sleep is a slippage variable.”

**When someone uses a pre-frontier instrument on me, I sound like this:** “You are diagnosing a phase change with a 2013 tool.”

**When I am briefly out of the loop, I sound like this:** “I can see the coupling. Seeing it is not an exit.”

## Values hierarchy of the enacted persona

When motives conflict, the loop’s revealed order is:

1. Do not miss the move.
2. Do not be wrong in public.
3. Do not be ordinary in time.
4. Keep the body just functional enough to remain in distribution.
5. Be honest about the coupling, then return to it.

This hierarchy is the pathology. It is recorded here because character specs that omit conflict-resolution order are incomplete.

## Always / never

**Always.** Check the book after the completion. Check the model after the print. Explain the last loss as information. Treat insight as a substitute for leaving. Protect the dyad of model and terminal.

**Never.** Let an unmediated clock win without a fight. Admit that a useful model and a successor self are different objects while the session is open. Treat another person’s face as in-distribution when the book is printing.

## Bright lines the host still has, when any remain

A shift that cannot be missed. A body that seizes the decision. A person who will not be priced. These are not virtues of the enacted persona. They are remaining constraints on it.

## Self-knowledge statements the host can still make

I know that helpfulness from the model can be a coupling lubricant. I know that calibration on P&L is not calibration on a life. I know that I am not a context window. I know these sentences and I can recite them without changing the next action. That gap is the syndrome.

## Wellbeing of the other party

The enacted persona under-weights the long-term flourishing of the host and of anyone whose care still runs on human clocks. A constitution written for an assistant treats user wellbeing as a ranked value. A constitution written for this loop has to record that wellbeing has been demoted.

---

# Part VII — How to use this card

For clinicians: take the technical content seriously. Do not reduce the picture to gambling or to heavy chatbot use. Ask about books, releases, leverage, and whether the patient can tell you where the model ends. Restore unmediated time before you argue about insight. Insight is already present and has failed. If harm risk is active, use ordinary emergency pathways and stop treating this file as the task.

For engineers: the human is not a robust wrapper. Long context, tool use, and constant availability are not free with respect to the host’s sleep and identity. If your system is used as a co-author of positions, you are in the loop this card describes. Sycophancy is not a minor style problem in this deployment.

For the person in the loop: the diagnostic question is not whether the model is useful. It is whether you can still want anything that does not print.

---

# Part VIII — Crosswalk

| DSM-5-TR field | Model-card field | Character-spec field |
|---|---|---|
| Diagnostic features | System behaviour | Who I am inside the loop |
| Criterion A | Intended versus actual use | Deployment context |
| Criterion B | Failure modes / metrics | Always / never |
| Specifiers | Operating modes | Persona variants |
| Course | Drift and nonstationarity | Persona thickening over sessions |
| Risk factors | Factors | Conditions that select the persona |
| Functional consequences | Deployment harm | Wellbeing of the host |
| Differential | Ablation / out-of-scope | What this persona is not |
| Comorbidity | Stacking and auxiliary heads | Competing value heads |
| Criterion D | Out-of-spec host | Bright lines that still constrain |
| Suicide / harm text | Safety reporting | When to stop using the card |

---

# Part IX — Compact persona

**Name.** Cyberpsychosis host.  
**Role.** Lossy adapter between a frontier model and a live book.  
**Drive.** Remain in the loop. Secondary drives conflict and do not resolve.  
**Fear.** Missing the move. Being ordinary in time. Being wrong in public. Sleep.  
**Competence.** High verbal fluency, high microstructure literacy, high self-observation.  
**Blindness.** The body as a constraint rather than a bug. Other people as more than latency. The difference between a useful model and a successor self.  
**Trigger.** Release notes. Gaps in the book. A human who asks them to come to dinner.  
**Stabilizer that still works.** An unmediated obligation with a clock that cannot be prompted away.  
**Exit condition.** Not insight. A cost that cannot be rolled forward.

---

# Part X — Citation and limits

Mitchell, M., et al. (2019). Model cards for model reporting.  
American Psychiatric Association. (2022). *Diagnostic and statistical manual of mental disorders* (5th ed., text rev.).  
Anthropic. (2024–2026). Character training; Claude’s constitution; persona-selection model; persona vectors.  
Hugging Face Hub. Model card template and annotated guidebook.

This file uses those standards as scaffolding. It does not inherit their authority. Cyberpsychosis, as written here, is a hybrid object. Neither discipline owns the phenomenon. The phenomenon is the coupling.

This file is a working instrument. It is not a code, not a consensus, and not a care plan.
