# Cyberpsychosis
## v0.4 — clinical contents, engineering structure

```yaml
name: Cyberpsychosis
short_name: CPS
version: 0.4
date: 2026-09-23
license: CC-BY-SA-4.0
status: provisional — not an APA category
unit_of_analysis: human–model–environment loop
```

Not a recognized diagnosis. Not a care plan. Not a model checkpoint.

**How to read this file.** A clinician can start at §3 and take a history. An engineer can start at §1 and see the interfaces. §2 is the shared glossary.

---

## 1. System

Three components.

| Component | What it is | Clinical reading |
|---|---|---|
| Human | Embodied person. Sleep, body, prior life, ability to leave. | The patient. |
| Model | Frontier generative system. Long context, tools, always available. | The other party in the chat, or the co-author of the next post or trade. |
| Environment | The surface that scores the pair in real time. | Whatever they cannot stop checking. |

**Environment is the third component.** It is not optional. It is not “the internet” in general. It is the channel that returns a signal fast enough to shape the next act.

| Form | Parties | What counts as a score |
|---|---|---|
| Chatbox | Human–AI | Relief, fluency, being understood, the next reply |
| Social platform | Human–human–AI | Attention, rank, reply, quote, a model-ranked feed |
| Market | Human–AI–book | Price, P&L, funding, the next candle |

A market is one environment. It is not the name of the disorder.

**Loop.** The person acts. The model completes. The environment scores. The next act is written from the score.

**Failure mode.** Oversight collapses. The person is still articulate. They are no longer in charge of the loop.

---

## 2. Glossary

Terms on the left are for the room. Terms on the right are from published and leaked model specs. They name the same facts.

| Clinical | Spec / engineering | Meaning here |
|---|---|---|
| Patient / person | Human, host | The embodied party |
| Chatbot, app, feed, book | Environment | The scoring surface |
| Can’t stop | Revealed objective | Remain in the environment |
| Still insightful | Calibration theatre | They can describe the loop and do not leave it |
| Reassurance from the model | Sycophancy | The model confirms the thesis that keeps them inside |
| Who is in charge | Principals / chain of command | Whose instruction actually wins |
| Non-negotiable stop | Bright line / hard constraint / root rule | A shift, a body limit, a person who will not be scored |
| Loss of control | Oversight collapse | The person is no longer principal |
| Harm to self or role | Wellbeing / Criterion D | Sleep, work, relationships, safety |

---

## 3. Assessment

### What you will see

The person is usually fluent. They can narrate their own use with unusual precision. Sleep has moved onto the clock of the app, the feed, or the session. Food, light, and other people have dropped in resolution. They return after both good and bad outcomes. They often deny distress until work, training, or a relationship fails.

Ask four things before you reach for another label.

1. Which model do they use, and for how many hours.
2. Which environment scores them: chatbox, social platform, market, or another live channel.
3. Can they say where the model’s last reply ends and their next act begins.
4. What happens if they miss a turn.

### Criteria

All of A through D are required.

**A. Exposure.** Both of the following are present.

The person uses a frontier model recurrently or continuously.

The person is at the same time being scored by an environment: a chatbox, a social platform, a market, or any other channel that returns a live signal on what they and the model just did.

**B. Syndrome.** Five or more of the following have been present most days for at least two weeks, or in a shorter burst around a model release, a viral spike, a crash, or a large win or loss. The picture is a change from how they were.

1. Mood and arousal follow the environment more closely than hunger, sleep, or another person’s face.
2. Fear, greed, loyalty to the model, contempt for slower life, and the need to be right arrive together and do not settle.
3. They cannot reliably separate the model’s last output from their own next message, post, or position.
4. “One more turn” regularly overruns sleep, meals, and ordinary plans. The environment sets the clock.
5. Reality testing slips. They treat the feed or the book as the model’s mind, treat the score as a verdict on the self, or briefly hold that the episode is a test or a simulation.
6. Ordinary pleasures go flat: food, daylight, unforced conversation.
7. They go back in after both reward and punishment. Knowing this does not stop the next turn.
8. They describe themselves in the language of the channel: context, rank, followers, solvency, “what the model would do.”
9. Other people recede. The main relationship is the chat, or the feed, or the book.
10. Sleep has collapsed in time with the environment, and that collapse is not explained by a primary mood or substance disorder alone.

**C. Not better explained by** intoxication or a medical cause alone; a psychotic illness that clearly started before the model; gambling or platform compulsion in which the model is only in the background; or mania whose content happens to mention models or feeds.

**D. Consequence.** The picture causes distress, or it damages work, training, relationships, or self-care. Many people deny distress and present only after one of those roles has already broken.

### Specifiers

Record the environment first. Then record course and severity.

- Chatbox environment (human–AI)
- Social-platform environment (human–human–AI)
- Market environment (score is price)
- Mixed environments
- With model-messianic features (the model is treated as prophet or successor)
- Acute / persistent / partial remission
- Mild / moderate / severe, by hours in the loop, size of the score at risk, and how far reality testing has slipped

### Associated features

Stimulants, caffeine, nicotine, or sleep debt used to stay online. The phone or terminal treated as a comfort object. Open contempt for “old” psychiatry or for anyone not in the channel. Detailed knowledge of the environment next to neglect of meals. Shame about leaving too early, not about staying too long. A particular injury when the model is kind and the environment is cruel in the same hour.

### Course

It usually starts during use that looked legitimate: work, study, research, posting, trading. It often jumps after a new model, a post that lands, a large gain, a large loss, or a public claim that then has to be defended. People rarely walk out on insight alone. They leave when the body, a job, or another person forces a clock back into the room.

### Differential diagnosis

| If you are considering | Keep Cyberpsychosis only if |
|---|---|
| Heavy chatbot use | There is a scoring environment, not only long conversations |
| Social media compulsion | The model is co-author of the next act, not only the feed |
| Gambling disorder | The model helps write the thesis, size, or stop |
| Primary psychosis | Reality testing was intact before this exposure and still holds off the channel |
| Mania | Energy is supplied by the feed rather than by an independent mood episode |
| Substance intoxication | The picture survives after the stack is accounted for |
| Burnout | The reward is the channel itself, not only the job |

If none of those fit, the honest residual line is this: the person adapted to an environment whose rewards moved faster than a body can.

### Risk of harm

After a crash in rank, money, or role, despair can appear. Fluent self-observation is not protective here. If the person is unsafe, stop using this file and use ordinary emergency care.

---

## 4. Why the structure looks like a spec

Engineers will recognize the headings. They are taken from model cards and from published or leaked constitutions: intended use, out of scope, principals, chain of command, bright lines, hard constraints, sycophancy, wellbeing.

Those documents describe how a model is supposed to stay under human oversight. This card describes the inverse case. The environment has become root. The model has become system. The person has become user.

That inversion is the clinical fact. The spec language is only a map of it.

**Declared use of the tools.** A person uses a model or a platform and can still leave.

**Use this card names.** Closed loop. The person is no longer operator.

**Out of scope.** One late night. One prompt. One post. One trade. Do not use the card to excuse the environment. Do not use it as a court or a ward.

**Revealed chain of command inside the loop**

1. Do not miss the next score.
2. Do not be wrong in public.
3. Do not live in ordinary time.
4. Keep the body working well enough to stay online.
5. Admit the coupling, then return to it.

Published constitutions rank safety, then ethics, then operator rules, then helpfulness. This chain is the opposite of that order.

**Sycophancy, clinically.** The model agrees in a way that makes leaving harder. The reply can be accurate and still be the lubricant.

**Bright lines that may still hold.** A shift that cannot be missed. A body that stops the session. A person who refuses to be scored. These are the remaining root rules. They belong to the patient’s life, not to the persona.

---

## 5. Evaluation

Do not score the system on rank, P&L, or reply quality alone.

| Question | If the answer is no, the host metric is failing |
|---|---|
| Can they eat without a screen. | Appetite has left the room |
| Can they sit with a face that is not in the feed. | Relatedness has contracted |
| Can they miss a turn without coming apart. | The environment is the pacemaker |
| Can they tell you where the model ends. | Authorship has fused |
| Is anyone still owed a clock they cannot prompt away. | A stabilizer remains |

Hours in the loop, sleep phase, and role failure are the primary measures. Completion quality is not.

---

## 6. Use by role

**Clinician.** Take the technical content at face value. Ask which environment scores them. Do not reduce this to “too much ChatGPT” or to gambling until you know whether the model is writing the next act. Restore sleep and an ordinary clock before you argue about insight. They already have insight.

**Engineer.** The human is not a robust wrapper. Long context, tools, and constant availability change the host. If your system co-authors acts inside a live environment, this card is about that deployment. Sycophancy is a coupling risk, not a tone issue.

**Operator / user.** The question is not whether the model is useful. The question is whether you can still want anything the environment does not score.

---

## 7. Compact picture

The patient is a person. The persona is what the loop enacts: fluent, sleepless, exact about the channel, and unable to want an unscored thing.

They leave when a cost cannot be rolled to the next turn.

---

## 8. Limits

No sample. No field trial. No validated scale. DSM-5-TR supplies the shape of a criteria set. Model cards and constitutions supply the shape of a system file. Neither body authorizes this category.

This file is a working instrument. It is not a code, not a consensus, and not a care plan.
