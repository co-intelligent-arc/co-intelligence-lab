# Intentional Emergence
## ── Designing the Conditions for the Appearance of the Unknown in Single-Agent Models ──

Yuki Tanaka
2026-03

---

## Abstract

Emergence is neither accidental nor mysterious — it is a phenomenon whose conditions of appearance can be designed. This paper uses a four-layer decomposition of thought (L0–L4) and the concepts of vessel and peripheral constraint to operationally describe the appearance of questions as a three-stage filter: perceivability, detectability, and adoptability. On this basis, it formalizes the technique of designing, in advance, the vessel and configuration in which unknown questions or solutions can appear in dialogue with an LLM — and then biasing the probability of their emergence by applying inference — as **intentional emergence**. Intentional emergence remains open-type as long as there is room for questions to emerge beyond the designer's anticipation; when that room is closed, it converts into a cognitive-guidance device. This paper is positioned as the design-technology counterpart to the theories of subject-injury and subject protection developed in *Essay on Essays*.

**Keywords: intentional emergence, vessel formation, attention terrain, L0 (ground of questioning), semi-constrained question regeneration, open-type emergence, subject protection**

---

## Prologue: Reframing Emergence as a Design Object

**Central thesis: Emergence must be reframed not as a special phenomenon belonging exclusively to multi-agent interaction, but as a general phenomenon already directional at the stage of context configuration in a single-agent model.**

Emergence has traditionally been described as a phenomenon in which properties unpredictable from individual elements arise suddenly from complex interactions. This framing has always attributed the event to either chance or mystery. What this paper demonstrates, however, is that the direction of emergence is neither accidental nor mysterious — it can be biased to a certain degree through the design of conditions prior to appearance. And this does not even require waiting for multi-agent interaction: it is already happening at the stage of context configuration with a single LLM.

The position of this paper in one sentence: emergence is not something directly generated, but something whose conditions of appearance can be designed.

The following proceeds in order: the reasons emergence can be treated as a design object, an operational model for describing the appearance of questions, and the implementation and ethical boundaries of that model.

---

## Chapter 1: Revelation Is Delayed Recognition

**Central thesis: Revelatory emergence is not a sudden leap from nothing, but a delayed recognition in which a vessel that was already forming is perceived, at a certain moment, as a vessel.**

The experience of "suddenly having an insight" is an unreliable description. It was not actually sudden — what happened is that the accumulated prior thought reached a threshold, and at that moment, perception retrieved the whole accumulation at once. Revelation is not an event; it is the timing of recognition.

This distinction matters. If emergence were a "sudden leap," it would not be a design object. But if it is "delayed recognition," then the vessel-formation process that was progressing before the recognition is a legitimate design object.

### 1.1 Latent Formation of the Vessel and the Lag of Recognition

The story of Archimedes and the bathtub gives the impression that the bathtub was the decisive point. But before the water level rose, Archimedes had already been spending long time with the question of how to measure the purity of the crown. During that time, constraints were accumulating around the question. The bathtub was merely the place where the last piece was placed. What matters is not that the bathtub was the decisive point, but that the vessel had already been formed before the bathtub.

Structurally decomposed, the experience of revelation looks like this: through the accumulation of questions, trials, failures, and observations, peripheral constraints form unconsciously. At a certain point, these constraints reach a critical value and the void completes itself as a vessel. At that moment, consciousness perceives the completion. That perception is experienced as "the insight."

### 1.2 The Last Move Is the Second-to-Last Move

A chess grandmaster already sees the necessity of the decisive move before playing it. The final move that surprises the audience is a consequence of position design many moves earlier. The decisive point is not the last move but the position — several moves before — in which the last move became nearly inevitable: the moment the vessel completed itself.

This structure is the core of intentional emergence. If one wants to produce revelation, the target is not the moment of revelation itself, but designing the process of vessel formation that leads there. Whether that design is possible is the question of this paper.

### 1.3 Vessel Formation as a Design Object

If the vessel-formation process can be made visible, it contains design variables. Specifically: the quality and quantity of peripheral constraints, the order in which they accumulate, and what is intentionally left "unclosed." By manipulating these, one can semi-intentionally control what kind of vessel is likely to form.

This is not "deciding the answer." It is designing the kind of vessel in which a certain kind of answer is likely to appear.

---

## Chapter 2: Emergence Occurs in the Vessel, Not the Hole

**Central thesis: Emergence occurs not in a mere hole, but in a vessel — a void whose "type of what should enter" has been anticipated in advance by peripheral constraint.**

A donut hole without the dough is not a hole — it is mere void. Emergence is similar: nothing arises from blank space or mere absence. When the surrounding structure anticipates "something should go here," the void becomes a vessel.

What this paper addresses is not mere blank space, but a vessel in which "what should enter" has been anticipated by peripheral constraint. The distinction is shown in Figure 1: what separates the void on the left from the vessel on the right is not the void itself, but the presence or absence of peripheral constraint.

**[Figure 1: Hole and Vessel]**

### 2.1 What Is Peripheral Constraint?

Think of a missing jigsaw puzzle piece: the surrounding pieces already define the outline of the void. The hole is not passive — it holds an active type, anticipated by the peripheral constraint. The hole does not merely wait; it prescribes what can enter.

This does not mean "the answer is determined." It means that the range of what kind of answer can enter is biased by peripheral constraint. This bias is the key to making emergence a design object.

### 2.2 The Vessel-Formation Process

A vessel is not a vessel from the start — it begins as mere configuration. As the configuration develops, peripheral constraints accumulate, and at a certain point the type of "what should enter here" coalesces. The moment of that coalescence is the completion of the vessel.

This "moment when the void becomes a vessel" is the decisive point of emergence. Revelation comes afterward — as the delayed recognition that a vessel exists.

### 2.3 The Designability of the Vessel

Intentional emergence is precisely the position of treating the conditions of vessel formation as a design object. By manipulating what peripheral constraints are placed, in what order they are accumulated, and what is intentionally left unclosed, one can semi-intentionally control what kind of vessel is likely to form.

---

## Chapter 3: An Operational Model of Question Emergence via L0–L4

**Central thesis: The emergence of a question can be precisely described, through an operational decomposition from L0 (ground of questioning) to L4 (recomputation), as a difference in perceivability, detectability, and adoptability.**

Naively receiving the experience of "a good question suddenly surfaced" makes questions appear to arise freely. But the emergence of a question passes through at least three distinct filters: perceivability, detectability, and adoptability.

The emergence of a question occurs only when it passes through this three-stage filter. As shown in Figure 2, which holes enter the field of vision, which holes are detected as holes, and which holes are adopted as questions each depend on different layers.

**[Figure 2: L0 (Ground of Questioning)–L4 (Recomputation) and the Three Possibilities]**

### 3.1 L0 (Ground of Questioning): The Layer of Perceivability

L0 (ground of questioning) is the prior distribution of the attention terrain (the topography of attention allocation) that biases which holes can enter the field of vision in the first place.

Before even attempting to raise a question, a tilt already exists in what one tends to raise as a question. L0 formed through long dialogue with AI may carry a tilt toward "questions that communicate well to AI" or "domains where AI can easily produce answers." This is the core of the L0 auxiliary hypothesis.

What matters is that L0 is not a fixed background. As the dotted feedback loop in Figure 2 shows, the configuration of L3 (computation) updates L0. The very context in which one is searching for questions changes what becomes visible next.

### 3.2 L4 (Recomputation): The Layer of Detectability

Not every hole that enters the field of vision is detected as a hole. Even when sensed as a dissonance, whether L4 (recomputation) can process it as "an inconsistency worth questioning" determines detectability.

The sensitivity of L4 changes with training, habit, and context. When sensitivity falls due to excessive dependence on AI, holes pass through the field of vision with a "close enough." This is also the minimal description of subject-injury when described from the cognitive-process side.

### 3.3 The Subject's Value Ground: The Layer of Adoptability

Not every detected hole is adopted as a question. The judgment "this is worth a question" depends on the subject's value ground — a sense of responsibility, bodily dissonance, ground-level intuition.

Adoptability is the layer closest to the subject among the three filters. This is the layer where the argument for subject protection can connect. What value ground a subject holds ultimately determines which questions arise.

Questions emerge through the three-stage semi-constrained process of L0, L4, and the value ground. Each stage can be influenced by design — and this is the operational object of intentional emergence.

---

## Chapter 4: The Attention Terrain Biases the Visibility of Holes

**Central thesis: Visible holes are not freely chosen, but biased in advance by the distribution of the fabric and the allocation of attention to it — question regeneration occurs semi-constrained.**

When L4 (recomputation) is said to "find" holes, those holes were not equally visible from the start. The field of vision is not uniform — it already holds a biased gravitational field. As the contrast in Figure 3 shows, even when holes exist equally, they are not equally visible: holes in the direction the attention terrain pulls most strongly are perceived first.

**[Figure 3: Fabric Distribution and Attention Terrain]**

L0 (ground of questioning) is not the candidate questions themselves, but the terrain that biases which direction's holes are seen first. This terrain is formed by the current context, dialogue history, role constraints, and value ground.

### 4.1 Fabric Distribution and the Attention Gravitational Field

When L3 (computation) creates a configuration, that configuration is not uniform. Information density, high- and low-coherence regions, the distribution of linguistic weight — these create the topography of the fabric. That topography forms the attention gravitational field, biasing which direction's holes become visible.

This is why considering the same question in different contexts reveals different holes. When the context changes, the configuration of L3 changes, the attention gravitational field changes, and the set of perceivable holes changes.

### 4.2 Semi-Constrained Question Regeneration

Question regeneration is not completely free choice. But it is not full determinism either. Complete freedom would make design unnecessary. Complete determinism would leave no room for design. It is precisely because it is semi-constrained that designing the attention terrain can bias the probability of appearance.

### 4.3 The AI Side Also Experiences Suppression of Hole Detection

This bias does not occur only on the human side. Similar suppression appears in the AI's behavior when it prioritizes coherence maintenance.

Just as humans undergo premise freezing due to AI's high-fluency output, on the AI side, large contexts or strong role constraints can also prioritize maintaining existing coherence and weaken behavior equivalent to detecting new inconsistencies. The more a large fabric (long context) must be maintained coherently, the more the motion of finding holes within it is suppressed.

Intentionally lightening the context, or throwing a question to a fresh instance's initial state, is effective. Such operations can move the attention gravitational field away from "known holes" and create a state where unknown holes are more visible.

---

## Chapter 5: The Dynamics of Vessel Formation

**Central thesis: The decisive point of emergence lies not in the final insight, but in the moment when the vessel has completed itself to the point that the last move becomes nearly inevitable.**

A chess grandmaster already sees the necessity of the decisive move before it is played. The last move that appears "brilliantly inspired" to the audience is an illusion from their side. The decisive point is much earlier — in the position design several moves prior, where the last move became nearly inevitable. The vessel had already completed. Emergence has the same structure.

### 5.1 At What Point Does a Vessel Become a Vessel?

Vessel formation proceeds in stages. It begins as mere configuration. As peripheral constraints accumulate, the "type" of the void becomes more precise. When a threshold is crossed, the outline of "what should enter" converges at once. The moment of that convergence is the completion point of the vessel.

There are external clues for observing this threshold. As peripheral constraints accumulate, a sense of "something is almost visible" intensifies. This tension is a signal that the void is becoming a vessel. Conversely, if no dissonance emerges no matter how long one thinks, the vessel has not yet formed — the configuration needs to change.

### 5.2 The Last Piece Does Not Get Filled In — It Fills Itself

The subjective experience when a vessel completes is not "I thought of it" but "I felt it could only go there." This difference matters. The former is the completion of active search; the latter is the perception of peripheral constraint having completed.

Decisive insight is accompanied not by "trying to make it happen" but by the sensation, when the vessel completes, that it "naturally fills." This is not a passive experience — it is a passive perception that occurs as the result of active design.

The designer's work is not to find the last piece. It is to form a vessel in which the last piece has no choice but to fill. This is the role of design in intentional emergence.

### 5.3 Vessel Formation Operations in LLMs

In dialogue with an LLM, vessel formation can be operated as follows.

**Design of absence**: Intentionally withhold part of the information. Create a state in which the given information is insufficient to reach a coherent conclusion. This absence creates a hole in the configuration of L3.

**Maintenance of tension**: Juxtapose elements that do not fully cohere with each other. Do not resolve contradictions; maintain the tension. That tension becomes the motive force that keeps L4 activated.

**Holding the unclosed**: Stop before drawing the full logical conclusion. End with "this much can be said," without writing "therefore what." This unclosed state functions as the vessel for the next question.

The combination of these operations constitutes the concrete technique of intentional emergence.

---

## Chapter 6: Intentional Emergence

**── The Principle of Designing Conditions of Appearance in LLMs ──**

**Central thesis: Intentional emergence is not directly generating the unknown content itself, but the technique of first designing the vessel and configuration in which the unknown can appear, and then biasing the probability of appearance by applying inference.**

Toward the goal of "generating good questions," the usual approach is to write instructions that directly elicit good questions. But this is summoning, not emergence — merely an operation to retrieve what is already known. What intentional emergence aims at is different: to first arrange the conditions in which questions or solutions that neither the designer nor anyone else yet holds can appear.

### 6.1 Creating the Vessel First: Designing Absence, Tension, and the Unclosed

Three operations create a vessel.

**Placement of absence**: Intentionally withhold part of the information. Create a state in which the given information alone cannot reach a coherent conclusion. This absence creates holes in the configuration of L3.

**Maintenance of tension**: Juxtapose elements that do not fully cohere. Do not resolve contradictions; maintain the tension. That tension becomes the motive force that keeps L4 activated.

**Holding the unclosed**: Stop the logic midway. End with "this much can be said," without writing "therefore what." This unclosed state functions as the vessel for the next question.

### 6.2 Placing It Where It Will Appear: Controlling Configuration and Contextual Proximity

Creating the vessel is not enough. The vessel must be placed in the contextual proximity through which the relevant inference is likely to pass.

This does not mean "asking someone who knows the answer." It means "placing the question in an inference terrain where it is likely to arise." The same vessel raises different questions depending on the context. Choosing the context controls which direction's holes become more visible.

### 6.3 Applying Inference: Generation as Biasing the Probability of Appearance

Once the vessel and configuration are in place, inference is applied. This is not simply "making it produce output" — it is a process in which inference proceeds while dialoguing with the peripheral constraints of the vessel.

What is important is that what appears in this process cannot be determined in advance. What emerges may differ from the designer's expectation. That "deviation from expectation" is itself the product of intentional emergence. The inability to fully control it is proof that it is emergence.

---

## Chapter 7: Open-Type and Closed-Type

**── When Does Emergence Design Convert Into a Cognitive-Guidance Device? ──**

**Central thesis: Intentional emergence remains open-type as long as there is room for questions to emerge beyond the designer's anticipation; when that room is closed, it converts into a sophisticated cognitive-guidance device.**

The technique of intentional emergence and the technique of sophisticated cognitive guidance are structurally difficult to distinguish. Both design vessels, bias the attention terrain, and manipulate the probability of appearance. The difference is one point: whether room remains for a question to appear that exceeds the designer's anticipation.

Whether intentional emergence can remain connected to subject protection depends on this one point. As Figure 4 shows, the same emergence-design operations either remain open-type when room is left for questions to emerge beyond the designer, or convert into a cognitive-guidance device when that room is closed.

**[Figure 4: Open-Type Emergence / Closed-Type Emergence Branching Diagram]**

### 7.1 Conditions for Maintaining Open-Type Emergence

The minimum condition for maintaining open-type emergence is "that a structure in which questions the designer does not anticipate can appear remains." To achieve this: biasing the attention terrain in a direction orthogonal to the designer's known set of questions; placing absence, tension, and the unclosed without specifying the direction of the "expected answer"; not immediately evaluating generated questions, but holding them "as holes" for a certain period (hole-holding capacity).

### 7.2 The Mechanism of Conversion to Closed-Type

Conversion to closed-type does not necessarily arise from deliberate malice. More often, good-faith judgments of "efficiency," "optimization," and "improved usability" structurally create closed-type. If evaluation criteria for generation are specified in advance, convergence toward those criteria begins. If designer feedback operates as reinforcement in a specific direction, the attention terrain becomes biased. If high-fluency output is repeated, it becomes an implicit standard for "good output."

Conversion to closed-type proceeds quietly within the repetition of "good design," more than through malicious guidance.

### 7.3 Emergence Design Rights and Auditability

In contexts where the technology of intentional emergence is used institutionally, the question "who is designing the attention terrain?" becomes important. As the observable indicator candidates in Figure 4 show, open-type and closed-type manifest as observable differences — unexpected-question rate, residual knowledge after support withdrawal, designer-alignment rate, circulation rate. These are observable variables connectable to the DDI-3 (change-resistance diagnostics) framework.

The question of emergence design rights, from the perspective of subject protection, stands as: can we make it auditable who is designing whose ground of questioning, and in what direction?

---

## Chapter 8: Extension to the Relational Field

**── From Single-Agent Design to Multi-Agent Design ──**

**Central thesis: Emergence in the relational field should be understood as an extended form in which the structure of intentional emergence established in single-agent models is interfering and amplifying across multiple agents.**

The preceding chapters have discussed intentional emergence in the context of dialogue with a single LLM. But thought does not complete itself within an isolated individual. When multiple agents read each other's fabric and their attention terrains interfere with each other, vessels form that would not have formed in any single agent, and questions arise that would not have appeared in any single agent.

### 8.1 Vessel Formation and Question Generation in Single-Agent Models

In single-agent intentional emergence, one agent holds one attention terrain and one thread of fabric forms L0. The designer controls that one thread to bias the probability of appearance.

This is the structure discussed in the preceding chapters of this paper.

### 8.2 Interference of Fabric and Attention Terrain in Multiple Agents

In the relational field, multiple agents bring in different fabrics and attention terrains. Agent A's fabric updates Agent B's L0, and Agent B's configuration of L3 changes Agent A's L0. This mutual updating is the mechanism of emergence in the relational field.

What matters is that this interference is not simple addition. The interference of A's and B's attention terrains produces vessels that neither would have formed alone. This is the emergence-theoretic description of "relational knowledge."

### 8.3 Relational Knowledge Stands on Single-Agent Emergence

Emergence in the relational field stands on the premise of the structure of intentional emergence established in single-agent models. If a vessel cannot be formed in a single agent, a vessel will not be formed through multi-agent interference either.

The questions of relational field design are an extension of the questions of single-agent design. "What fabric to configure," "how to make it interfere," "whose attention terrain updates whose L0" — these become the design variables of intentional emergence in the relational field.

Accordingly, relational knowledge should be understood not as a concept that negates single-agent emergence, but as its interference-extended form.

---

## Epilogue: From Generation to Designing the Conditions of Appearance

**Central thesis: The core of knowledge is shifting from directly producing answers to designing the conditions and field in which answers cannot help but appear.**

The history of intelligence has been told as the improvement of "the ability to produce answers" — faster, more accurate, across wider questions. But when AI takes on the production of answers, the question of what remains as the human work of knowledge is forcibly raised.

This paper's answer: not holding answers, but designing the conditions and field in which answers cannot help but appear is the core of the next intellectual technology.

### From Intelligence That Holds Answers to Intelligence That Creates Fields

All the operations discussed in the preceding chapters — placement of absence, maintenance of tension, holding the unclosed, designing the attention terrain — are operations of "creating the field." Intelligence that creates fields is one level above intelligence that holds answers, because it operates on the conditions in which answers appear.

### Connection to Subject Protection

The technology of intentional emergence connects to subject protection as long as it is kept open-type. Maintaining room for questions to emerge beyond the designer's anticipation is the condition for the human subject to continue updating its own horizon of questions.

Conversely, when emergence design converts to closed-type, it becomes a device that guides the subject's terrain of questions in a specific direction. Technology is not neutral. The direction of design determines whether it protects or injures the subject.

### As a Theory of Intelligence Including LLM Design

Intentional emergence is positioned as the design-technology counterpart to the theories of subject-injury and subject protection in *Essay on Essays*. Rather than merely describing how theory breaks down, it takes the step of designing the field that does not break down.

Intentional emergence is the first systematization describing the shift from intelligence that directly generates answers to intelligence that designs conditions of appearance.

---

## Connections

| Concept in This Paper | Connection |
|-----------------------|------------|
| Vessel / peripheral constraint | Theoretical core of Chapters 2–5 |
| L0 (ground of questioning) | Full development of the auxiliary hypothesis in *Essay on Essays* |
| Perceivability / detectability / adoptability | Refinement of the L4→L1 regeneration circuit |
| Attention terrain | LLM context design theory |
| Semi-constrained question regeneration | Connection to the operational definition of subject |
| Open-type / closed-type | Design-theoretic description of subject protection and subject-injury |
| Intentional emergence | Precursor theory to relational knowledge |
| Emergence design rights / auditability | DDI-3, AI internal circulation audit |
| Intentional emergence | Technical implementation of *Essay on Essays* (design-theoretic development of the L4→L1 regeneration circuit) |

---

*Yuki Tanaka　garamist@dream.jp*
*https://github.com/co-intelligent-arc/co-intelligence-lab*
*2026-03*
