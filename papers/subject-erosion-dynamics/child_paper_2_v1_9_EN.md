# Subject Erosion Dynamics: A Unified Framework Integrating OMD, RD, and RLAF

**Child Paper 2 — English Full Text v1.9.1 (Complete Academic Version)**

**Author:** Yuki Tanaka
**Affiliation:** Independent Researcher, Seto Inland Sea Region, Japan
**Email:** garamist@dream.jp
**ORCID:** https://orcid.org/0009-0002-6183-7886
**Correspondence:** garamist@dream.jp

**Keywords:** subject-injury, recomputation dynamics, difference-retention, Region B, organizational metastability, invisible degradation

---


## Abstract

Subject-injury does not begin with visible breakdown. This paper argues that structural collapse is typically preceded — and systematically obscured — by the silent cessation of recomputation: a state in which surface functioning and cognitive output persist while the capacity for internal updating has already ceased.

To formalize this process, the paper integrates three complementary frameworks. Organizational Metastability Dynamics (OMD) identifies Region B as a diagnostic blind spot in which structural stability (σ) is preserved while recomputation capacity (M) has ceased — a condition undetectable by standard performance indicators. Recomputation Dynamics (RD) models the underlying mechanism as the multiplicative degradation of adaptive capacity A(e,u) = f(e)×g(u), where depletion of exploratory diversity (e) and atrophy of update capacity (u) amplify each other nonlinearly, such that neither alone is sufficient to sustain recomputation. RLAF shows that subject integrity requires an autonomy tensor T rather than a scalar index, and identifies evaluative autonomy (T_eval) as the primary site of erosion: as difference-retention depletes, T_eval shifts from processing difference as recomputation resource to eliminating it as noise, subsequently blocking all updating input to value autonomy (T_val) and producing its fixation.

Across all three frameworks, difference-retention (D) functions as the shared upstream condition for recomputation. Subject-injury is defined here not as destruction but as invisible degradation: difference disappears, recomputation ceases, evaluative autonomy is eroded, and value autonomy becomes fixed while output continues and the system remains socially legible as normal or successful.

---

## 1. Introduction

### 1.1 The Problem

**The problem of invisible degradation**

Research on autonomy, agency, and subjectivity has expanded across education, AI ethics, psychology, and human-computer interaction. Much of this work, however, operates within a framework oriented toward visible change: functional decline, output deterioration, and response instability are the signals that typically trigger recognition of a problem.

Yet subject-injury may proceed differently. It can advance as a process in which surface functioning is preserved while internal updating has ceased.

This is the question from which the paper departs: why does a subject stop before it breaks?

**What existing research does not address**

Research on autonomy support asks how subjectivity can be enhanced. Research on learner agency asks whether AI contributes to or undermines that enhancement. Research on AI governance asks how responsible autonomy in AI systems should be designed. These inquiries share a common orientation: they are oriented toward enhancement.

What remains largely unformalized is the mechanism by which relational dynamics erode a subject's autonomy. Erosion has its own dynamics. When the disappearance of difference, the cessation of recomputation, and the paralysis of evaluative autonomy proceed in combination, a form of degradation arises that is difficult to detect from either outside or inside.

**What this paper formalizes**

This paper aims to formalize this dynamic through the integration of three frameworks:

> Subject-injury is invisible degradation in which the disappearance of difference, the cessation of recomputation, and the erosion of evaluative and value autonomy proceed in combination; in its characteristic state, the continuation of surface stability and cognitive processing renders that cessation difficult to detect.

The core of this definition is that subject-injury is not destruction. Destruction appears as observable change. Subject-injury takes a form that betrays visibility itself: something that appears to be functioning has stopped updating.

**Organization of the paper**

The paper proceeds as follows. Section 2 provides a minimal account of the theoretical background of the three frameworks. Section 3 derives the common variables across the three frameworks and establishes the basis for integration. Section 4 describes the minimal causal chain of subject-injury. Section 5 discusses diagnostic, interventional, and institutional implications. Section 6 addresses the significance and limits of the integration and identifies remaining questions. Section 7 presents the conclusion.

---

**A note on the theoretical frameworks**

OMD (Organizational Metastability Dynamics), RD (Recomputation Dynamics), and RLAF (Reinforcement Learning from AI Feedback) are theoretical frameworks developed within the present research program and are introduced here as analytical constructs rather than references to previously published models under those names.

---


### 1.2 Limitations of Existing Research and the Contribution of This Paper

**The entry points of existing research**

Research on autonomy, agency, and subjectivity has accumulated across at least four domains. In education, discussions of learner agency and autonomy support have expanded rapidly in response to generative AI. In psychology, self-determination theory has linked autonomy support to intrinsic motivation, mental health, and protection against depression. In AI ethics and governance, the design of responsible autonomy and the distribution of accountability have become central concerns. In multi-agent research, studies have shown that groups of LLM agents can spontaneously generate conventions and collective biases through distributed interaction. Together, these bodies of work increasingly recognize that subjectivity is shaped not only at the level of individuals but also through relational dynamics.

**The shared assumption and its structural blind spot**

These bodies of research have produced important findings, but they share a common framework: they treat autonomy, agency, and subjectivity through the axes of promotion and inhibition.

This framework carries a structural blind spot. Erosion is not the inverse of promotion. When the disappearance of difference, the cessation of recomputation, and the paralysis of evaluative autonomy proceed in combination, external indicators can continue to read as normal. A framework oriented toward promotion cannot gain a foothold here, because the problem is not detected in the first place.

**What remains unformalized**

Three points remain unformalized. First, why is erosion difficult to detect from either outside or inside? Second, which component is eroded first? Third, why is recovery through individual effort alone so difficult?

**The position of this paper**

This paper does not aim to provide a first-principles definition of subjectivity. The redefinition of the subject concept itself is the task of the parent paper and Child Paper 1; this paper instead describes the minimal causal chain of subject-injury within the framework established there. The detailed institutional design requirements are delegated to Child Paper 5.

**A note on terminology**

In this paper, "erosion" is not a value judgment. It is defined functionally as the loss of the capacity to recompute in response to environmental change. Whether a state in which recomputation has ceased while stability is maintained is subjectively good or bad lies outside the scope of this paper. What is at issue is the functional requirement: whether, when a gap arises between the subject and its environment, the subject can detect and update that gap. To be precise: this paper takes the subject's capacity for recomputation as a functional condition rather than a normative ideal. The question is not whether continuous updating is good, but whether, when a subject would update, the structural conditions for doing so remain intact.

The diagnostic vocabulary of this paper — Region B, subject-injury, T_eval paralysis — should not be used as authoritative fixed labels to make unilateral determinations about others from the outside. Its primary use is the self-auditing of institutional, environmental, and technological design, and the supplementation of a subject's own self-reflection.

**The contribution of this paper**

The contribution of this paper can be summarized in two points. First, through the integration of three frameworks, it identifies D (difference-retention) as the common upstream variable. In OMD, Var(φ); in RD, e; in RLAF, the precondition for T_eval — each appears as a distinct variable within its own framework, but integration shows that all three refer to the same type of functional loss arising from the depletion of difference. Second, it formalizes subject-injury not as destruction but as invisible degradation. This does not negate the framework of promotion; rather, it shows that promotion and erosion can be understood as opposite directional outcomes within the same variable system. The task of this paper is to describe the minimal causal chain specific to erosion.

---

## 2. Theoretical Background

### 2.1 Region B in OMD

Organizational Metastability Dynamics (OMD) asks why social and organizational systems may continue to appear functionally normal while having lost the capacity for internal recomputation. Its central concern is not simple breakdown or dysfunction, but a state in which surface normality is preserved while internal updating has ceased.

**The independence of σ and M**

OMD treats structural stability σ and recomputation capacity M as independent variables. σ indicates the degree to which a system maintains surface functioning. M indicates the capacity to evaluate existing strategies, generate alternatives, and update behavior. M can change independently of σ. Even when σ remains high, M can decline; and M may already have ceased before σ deteriorates. This independence is the core of OMD's diagnostic argument: a high value of σ does not guarantee the health of M.

**The definition of Region B**

OMD classifies the state of a system into three regions according to the levels of σ and M. Region A is the healthy state in which both σ and M are maintained. Region C is the state of collapse in which the deterioration of σ has become externally visible. The problematic case is Region B, defined as the state in which σ is maintained while M has ceased.

Region B functions as a diagnostic blind spot because standard evaluation refers primarily to σ. If σ is high, the system is judged "normal." The cessation of M is not reflected in σ-based indicators.

**The dynamics of recomputation cessation**

In OMD, the dynamics of M are given by the following equation:

$$\frac{dM}{dt} = -\nu L_c + \xi E_{r\_eff} - \mu\omega(M - \bar{M})$$

When $E_{r\_eff} \leq 0$, recomputation is no longer initiated. In this paper, this condition is treated as the minimum formal condition describing the transition to Region B.

Linear indicators capture primarily surface variables dependent on σ, and the cessation of M is not directly reflected in them. This is the point of departure for the diagnostic limitation argument developed through Sections 2, 4.4, and 5.1.

**Summary**

On the premise that σ and M are independent, OMD defines Region B as an apparently normal, internally halted state and shows why linear indicators systematically fail to detect it. In this paper, OMD provides the formal basis for describing the diagnostic invisibility of subject-injury.

---

### 2.2 The Multiplicative Structure of Adaptive Capacity in RD

Recomputation Dynamics (RD) asks how adaptive capacity is maintained and how it is lost across individual, organizational, and social scales. Its central concern is that adaptation is not a matter of response speed or information-processing volume alone, but depends on the combination of two independent capacities: exploration and update.

**The multiplicative structure of adaptive capacity**

$$A(e, u) = f(e) \times g(u)$$

Here, e (exploratory diversity) is defined as the entropy of effective alternatives, and u (update capacity) is defined as the product of correction speed and level of abstraction. In a multiplicative structure, if either e or u approaches zero, A approaches zero regardless of the level of the other. e and u are not substitutable; A is established only when both are maintained above a certain level.

e represents the breadth of the space of alternatives, that is, the extent to which alternatives to the current strategy remain available. In this sense, e can be read as the exploratory-space expression of D (difference-retention), introduced in Section 3. u has a hierarchy ranging from local correction (L0, L1) through strategic update (L2) to frame reset (L3). L3, in particular, is the highest-order update operation, one that revises the problem definition, evaluative axes, and premises themselves.

The important consequence of the multiplicative structure is that the depletion of e and the atrophy of u can proceed as mutually amplifying degradation. This nonlinear deterioration and its cumulative expression is what RD terms update inertia debt.

**Why an additive structure is insufficient**

Consider a system in which exploratory diversity e is sufficiently high but update capacity u approaches zero. Diverse alternatives exist, but none are executed or updated. A system with only exploration is an inventory of possibilities without adaptation.

Conversely, consider a system in which update capacity u is sufficiently high but exploratory diversity e approaches zero. The capacity for execution exists, but there are no alternative paths to serve as the material for update. A system with only update capacity is a processing machine without material.

Adaptation requires both e and u to remain above a certain level as necessary conditions. This property cannot be expressed by an additive structure; it is captured only by the necessary-condition coupling of a multiplicative structure.

**The connection to D and M**

When D is high, multiple paths, interpretations, and strategies are maintained in parallel, and the entropy among them sustains e. When D declines, this diversity of paths begins to converge. The decline of D therefore appears directly as the atrophy of e.

$$D \downarrow \Rightarrow e \downarrow \Rightarrow f(e) \downarrow \Rightarrow A(e,u) \downarrow$$

The cessation of M (recomputation capacity) in OMD and the atrophy of u (update capacity) in RD are treated in this paper as corresponding variables at the social-relational and subject-internal scales, respectively. In a system in which recomputation no longer arrives from the outside, the internal initiation of update also becomes difficult to sustain.

$$M \downarrow \Rightarrow u \downarrow \Rightarrow g(u) \downarrow \Rightarrow A(e,u) \downarrow$$

This correspondence remains a minimum correspondence hypothesis rather than an identity claim. Whether both variables can be measured independently in empirical terms remains a question for Section 6.2.

**Summary**

Through the multiplicative structure A(e,u) = f(e) × g(u), RD shows that exploration and update are both necessary conditions for adaptation, and that neither can substitute for the other. In this paper, RD provides the formal basis for describing how the depletion of difference and the cessation of recomputation proceed as mutually amplifying degradation in subject-injury.

---

### 2.3 The Autonomy Tensor in RLAF

Reinforcement Learning from AI Feedback (RLAF) asks how interaction with AI affects the cognitive, evaluative, motivational, and value dimensions of human subjects. Its central concern is that a subject's autonomy is not a quantity that increases or decreases along a single axis, but is composed of multiple independent components that can change at different rates.

**The limits of scalar description**

A scalar variable such as subject retention rate α represents only an approximation in which the multi-component structure of autonomy is projected onto one dimension:

$$\alpha = P(T)$$

A projected α conceals non-uniform changes among components within the subject. A high overall value of α can mask the fact that one component has already collapsed while others remain intact.

**The autonomy tensor**

To capture this structure, RLAF introduces the autonomy tensor T:

$$T = (T_{cog},\ T_{aff},\ T_{eval},\ T_{mot},\ T_{val})$$

Each component is defined as follows. T_cog (cognitive autonomy) governs information processing, inference, and response generation. T_aff (affective autonomy) governs the relative independence of affective response. T_eval (evaluative autonomy) is the capacity to assess what is different or discrepant through one's own judgment. T_mot (motivational autonomy) governs intrinsic drive and the capacity to suspend and restart. T_val (value autonomy) is the capacity to sustain, through one's own judgment, the value frame that determines what is to be protected and followed. Each component can change non-uniformly with respect to the others.

**The structural position of T_eval**

Among the components of T, T_eval occupies a structurally distinctive position. T_eval functions as a converter that transforms difference inputs into recomputation resources. For T_eval to function, difference must be arriving as input. In this sense, T_eval is a component structurally dependent on the state of D (difference-retention).

When D declines, the volume of difference reaching T_eval decreases. T_eval continues to function as a converter, but under conditions in which the material to be converted is no longer being adequately supplied.

**The erosion sequence: T_eval first, T_val second**

This paper identifies T_eval as the primary site of erosion in subject-injury. The reason is structural: T_eval lies at the intersection that simultaneously receives pressure from two directions — the impoverishment of input caused by the decline of D, and the rise in processing cost caused by the decline of M and u.

From the input side, the decline of D impoverishes the inputs reaching T_eval. From the processing side, in a system in which E_r_eff is constrained, the cost of continuing to hold and evaluate difference as significant rises. By contrast, early elimination of difference as noise becomes established as a cost-minimizing stable strategy. The paralysis of T_eval is therefore not the simple disappearance of evaluative capacity, but a shift in evaluative mode: from treating difference as a recomputation resource to eliminating it early.

When T_eval shifts in the direction of difference elimination, all updating input to T_val is cut off. T_val then becomes fixed. Fixed T_val appears from the outside as consistent value retention, but this consistency is not the result of adaptation — it is the persistence of a halted state.

**The residual of T_cog and the mechanism of diagnostic delay**

Even at the stage when T_eval and T_val have been eroded, cognitive autonomy T_cog remains relatively intact. As long as T_cog remains, the subject continues to process information, answer questions, and produce output. But in reality, the evaluative function (T_eval) that provides the directional basis for that output has already lost its function, and the value frame (T_val) that the output is meant to protect has already ceased updating.

This is the mechanism of diagnostic delay in subject-injury. Because measurable output and substantive degradation are fully dissociated at this stage, the cessation is not reflected in any performance-based indicator.

**Summary**

RLAF shows that a scalar index of autonomy is insufficient, and that subject integrity requires a multi-component description using the autonomy tensor T. In this paper, RLAF is positioned as the framework for describing the internal mechanism of subject-injury — specifically, the prior erosion of T_eval and the subsequent fixation of T_val.

---

## 3. Variable Integration

### 3.1 Derivation of Common Variables

The three frameworks described in Section 2 each employ distinct variable systems. This section derives the common variables through which they can be placed in relation. Without such variables, placing the three frameworks side by side does not constitute integration — it remains a parallel listing.

Integration means showing that the phenomena described by the three frameworks are different cross-sections of the same process. For this, a descriptive axis is needed that runs across all three variable systems.

**D (difference-retention) as an upstream variable**

D (difference-retention) is defined as the preservation and availability of difference inputs capable of prompting re-evaluation of the subject's existing frame.

A high state of D means that the subject is in a condition in which it can receive inputs that may betray its own predictions and evaluations, and those inputs constitute the starting point for recomputation. D is not the objective diversity of inputs. It refers to the extent to which inputs capable of destabilizing the subject's existing frame are being preserved and supplied. Even if diverse inputs exist, those that do not disturb the subject's existing frame do not function as D.

D corresponds to the upstream variables in each of the three frameworks. In OMD, the decline of D appears as the decline of Var(φ) — the contraction of the phase space for recomputation. In RD, the decline of D appears as the atrophy of e — the narrowing of the space of alternatives. In RLAF, the decline of D appears as the loss of the operating precondition of T_eval — the severance of input to the converter. The detailed correspondence in each framework is examined in Section 3.2.

**Why D is positioned as an upstream variable**

The reason D is positioned as a variable prior to the three frameworks is that, in each framework, it functions as the foundational condition for recomputation. The recomputational phase space described in OMD cannot be sustained without D. The exploratory diversity described in RD does not form without D. T_eval in RLAF loses its input without D. D is not a variable native to any one of the three frameworks; it is a common resource underlying all three.

It should be noted, however, that this paper does not claim D to be an unconditionally desirable condition. There are contexts in which homogenization and standardization function effectively, and this paper does not deny them. D is positioned as a necessary condition only where the functional requirement is at issue: whether the subject remains capable of recomputation in response to environmental change.

**C (conformity pressure) as an integrative descriptive variable**

C (conformity pressure) is defined as the downward pressure on D arising from the combined effect of ω and L_c in the relational field. C does not appear in any of the three source frameworks. It is a variable introduced in this paper to capture, in a single term, the combined effect that ω and L_c produce in the relational field. When C is high, external evaluative axes act prior to the subject's own evaluative axes in the relational field, and the cost of continuing to hold difference rises. This leads to the decline of D.

When D is high, the subject's own evaluative orientation remains robust and can process the pressure of C as difference, even when C is high. Maintaining a high state of D therefore generates structural resilience against rising conformity pressure. This is the additional basis for the proposition in Section 5.2 that intervention should begin from D.

**S (subjectivity) as the final output variable**

S (subjectivity) is defined as the integrative output variable representing the degree to which subjectivity is preserved. S can be approximated as a scalar α, but a complete description requires the tensor T. The progression of subject-injury is described in a unified way in this paper as the degradation of S.

**Summary of common variables**

Three common variables are established. D (difference-retention) functions as the upstream variable prior to all three frameworks, bearing the foundational condition of recomputation. C (conformity pressure) is an integrative descriptive variable native to this paper, describing the combined effect of ω and L_c. S (subjectivity) functions as the variable that integrates the final output of all three frameworks. The correspondences of D across the three frameworks are examined in detail in Section 3.2.

---

### 3.2 Correspondence of D Across the Three Frameworks

Section 3.1 established D as the common upstream variable. This section examines how D corresponds to the specific variables in each framework and what type of functional loss its depletion produces. The aim is not merely to list correspondences, but to show that the decline of D produces structurally equivalent losses across all three frameworks.

**D and OMD: the correspondence with Var(φ)**

In OMD, the condition for recomputation to be initiated is that effective stimulus density N_eff remains above a certain level:

$$N_{eff} = \omega \times Var(\varphi)$$

Var(φ) is defined as the variance of evaluative orientation — the phase space for recomputation. When Var(φ) declines, the phase space contracts, and recomputation can no longer be initiated.

In this paper, D is treated as functionally corresponding to Var(φ) at the individual and relational scales. When D declines, the range of evaluative orientations that the subject can hold contracts. This appears in OMD as the decline of Var(φ).

The distinction is that Var(φ) in OMD describes the collective distribution of evaluative orientations in a group or system, while D in this paper describes the subject's capacity to receive and hold inputs that can disturb its own existing frame. The two are not identical, but they correspond as expressions of the same functional loss at different scales of description.

**D and RD: the correspondence with e**

In RD, adaptive capacity A(e,u) = f(e) × g(u) requires that exploratory diversity e remain above a certain level. When D is high, multiple paths, interpretations, and strategies are maintained in parallel, and the entropy among them sustains e. When D declines, the diversity of available paths begins to converge. The decline of D therefore appears directly as the atrophy of e.

$$D \downarrow \Rightarrow e \downarrow \Rightarrow f(e) \downarrow \Rightarrow A(e,u) \downarrow$$

The distinction is that e in RD describes the breadth of available alternatives in the subject's option space, while D in this paper describes the supply condition of inputs capable of disturbing the existing frame. These are not the same, but they correspond: when D is depleted, the material for generating alternatives is lost, and e cannot be sustained.

**D and RLAF: the correspondence with the operating precondition of T_eval**

In RLAF, T_eval functions as a converter that transforms difference inputs into recomputation resources. For T_eval to function, difference must be arriving as input. When D declines, the volume of difference reaching T_eval decreases, and the evaluative mode shifts toward elimination.

$$D \downarrow \Rightarrow \text{input to } T_{eval} \text{ impoverished} \Rightarrow \text{evaluative mode shifts toward elimination}$$

The distinction is that T_eval in RLAF describes the subject's internal evaluative function, while D in this paper describes the supply condition of external difference inputs. D is the supply condition; T_eval is the processing function dependent on that supply.

**The integrated meaning of the three correspondences**

In OMD, the phase space for recomputation contracts. In RD, the space of alternatives narrows. In RLAF, the input to the evaluative converter is severed. These are not three separate degradations, but three descriptions of the same functional loss at different scales. This structural equivalence is what makes integration possible and what renders D visible as the common upstream variable.

**Summary**

D corresponds to Var(φ) in OMD, to e in RD, and to the operating precondition of T_eval in RLAF. In each case, the decline of D produces the same type of functional loss. This structural correspondence is the basis for treating D as the common upstream variable in this paper's integration.

---

### 3.3 The Parallel Input Structure of ω and L_c

Section 3.2 showed that the decline of D produces structurally equivalent functional loss across all three frameworks. This section examines what drives that decline. The two variables that function as the entry points are ω (external cognitive feedback density) and L_c (judgment delegation).

**The definitions and origins of ω and L_c**

ω (external cognitive feedback density) is defined as the density of exposure to feedback from AI and other external cognitive systems. In OMD, ω is set as the sole exogenous variable. ω acts on the condition for recomputation only through its product with Var(φ), that is, $N_{eff} = \omega \times Var(\varphi)$, and does not generate recomputation energy on its own.

L_c (judgment delegation) is defined as the degree to which core judgments — error detection, threshold-setting, and direction selection — are externalized. In the equation for the dynamics of M in OMD, L_c appears as a term that directly reduces M:

$$\frac{dM}{dt} = -\nu L_c + \xi E_{r\_eff} - \mu\omega(M - \bar{M})$$

**Why they are treated as parallel inputs**

One might be tempted to connect ω and L_c in a unidirectional causal chain — for example, to assume that a rise in ω causes a rise in L_c. However, this paper provides no sufficient basis for assuming such a direction. It therefore treats ω and L_c as independent parallel input variables. This is a methodological decision intended to avoid importing a false causal assumption into the variable system.

The two variables act on D through different pathways. A rise in ω strengthens the dominance of external evaluative axes through high-frequency external feedback and appears as a rise in conformity pressure C in the relational field. A rise in L_c creates conditions in which the circuit for processing difference becomes difficult to maintain through the delegation of judgment, thereby contributing to the decline of D.

The entry point of the dynamics can be written as follows:

$$\omega \uparrow\ +\ L_c \uparrow\ \text{(parallel inputs)} \rightarrow C \uparrow \rightarrow D \downarrow$$

This chain serves as the starting point of the minimal causal chain in Section 4.

**The distinction between L_c and L_p**

What this paper treats as problematic is L_c, not L_p (processing delegation). A rise in L_p is the externalization of auxiliary tasks, and this paper does not assume that it directly reduces D or M. What matters is the delegation of the core of judgment — error detection, threshold-setting, and direction selection. Only when this delegation deepens does the dynamic of subject-injury activate.

It should be noted that this paper distinguishes between the pathway by which L_c acts directly on M and the pathway by which it acts indirectly on D through C. The former is the direct pathway of recomputation cessation; the latter is the erosion pathway of difference-retention. These are independent pathways of action, and this does not constitute a double use of L_c. Rather, it shows that the same act of delegation propagates through different variable systems via different pathways.

**Summary**

In this paper, ω and L_c are treated as independent parallel input variables. Their combined effect appears as rising conformity pressure and declining difference-retention in the relational field. This input structure provides the point of entry for the minimal causal chain developed in Section 4.

---

### 3.4 C as an Integrative Descriptive Variable

Section 3.3 showed that ω and L_c function as parallel inputs that drive the rise of C and the decline of D. This section examines the theoretical position of C itself — what it captures, how it relates to D, and why it is introduced as an integrative descriptive variable native to this paper.

**C does not appear in the source frameworks**

C does not appear in OMD, RD, or RLAF. It is a variable introduced in this paper to capture, in a single term, the combined effect that ω and L_c produce in the relational field. The introduction of C is not a modification of the source frameworks. It functions as a supplementary variable for integration: it describes a state of the relational field that all three frameworks are influenced by, without altering any of their internal variable systems.

**What C captures**

C captures two distinct effects. The first is the effect of a rise in ω: high-frequency external feedback strengthens the dominance of external evaluative axes in the relational field, raising the cost to the subject of maintaining its own evaluative orientation. The second is the effect of a rise in L_c: the delegation of core judgment creates conditions in which the subject's own circuit for processing difference becomes difficult to sustain. Both effects act in the direction of declining D. C is defined as the downward pressure on D arising from this combined effect in the relational field.

**The relationship between C and D**

When C rises, external evaluative axes act prior to the subject's own evaluative axes, and the cost of continuing to hold difference rises. This leads to the decline of D. However, the relationship between C and D is not simply linear. When D is high, the subject's own evaluative orientation remains robust. Even if C rises, the subject can process the pressure as difference and maintain D. Maintaining a high state of D generates structural resilience against rising C.

Expressed as a directionality:

$$C \uparrow \rightarrow D \downarrow \quad \text{(when D is already low)}$$

$$C \uparrow \rightarrow D \text{ remains stable} \quad \text{(when D is sufficiently high)}$$

This asymmetry supports the proposition in Section 5.2 that the primary target of intervention is D rather than C.

**The methodological role of C**

C serves two methodological functions in this paper. First, it makes the description of the minimal causal chain in Section 4 more concise. Without C, the chain would require ω and L_c to be named as separate entry points at every stage. Second, it makes explicit that the relational field is the site where ω and L_c produce their combined effect. Subject-injury does not occur as a purely internal process; it is mediated by the structure of the relational field. C marks that mediation in the variable system.

**What C does not claim**

C is not a variable with its own independent dynamic. It does not generate effects independently of ω and L_c. When ω and L_c are both low, C does not rise on its own. C is entirely derivative of the two parallel inputs and should not be read as an autonomous force in the system.

Additionally, C is not equivalent to coercion or intentional pressure. It is a structural description of the downward pressure on D that arises in the relational field — pressure that can emerge even in the absence of explicit coercive intent, through the accumulated effect of high-frequency feedback and deepening judgment delegation.

**Summary**

C (conformity pressure) is an integrative descriptive variable native to this paper, capturing the combined downward pressure that ω and L_c produce on D in the relational field. It does not appear in the source frameworks and does not modify them. The relationship between C and D is not linear: high D generates resilience against rising C, which is the basis for the intervention proposition developed in Section 5.2.

---

## 4. The Minimal Causal Chain

### 4.1 The Expanded Description

The process of subject-injury does not occur as a single destructive event. It proceeds as a quiet chain in which multiple variables degrade in sequence.

The starting point is the rise of ω and L_c as parallel inputs. ω acts on the condition for recomputation only through its product with Var(φ), and does not generate recomputation energy on its own. L_c acts on M through a separate pathway, directly reducing recomputation capacity.

The combined rise of these two inputs appears as the rise of conformity pressure C in the relational field. The rise of C drives the decline of D. The decline of D referred to here is not merely a reduction in the diversity of inputs. It is the loss of the availability of difference inputs capable of prompting re-evaluation of the subject's existing frame — the loss of the supply condition for recomputation itself.

**The three pathways through which D declines**

The decline of D proceeds simultaneously through three pathways corresponding to the three frameworks. In OMD, it appears as the decline of Var(φ) — the contraction of the phase space for recomputation. In RD, it appears as the atrophy of e — the narrowing of the space of alternatives. In RLAF, it appears as the loss of the operating precondition of T_eval — the impoverishment of input to the evaluative converter. These are not three separate degradations. They are three descriptions of the same functional loss proceeding across different scales of the variable system.

**The decline of effective recomputation energy**

Following the decline of D, effective recomputation energy E_r_eff declines. When $E_{r\_eff} \leq 0$, recomputation is no longer initiated.

$$\frac{dM}{dt} = -\nu L_c + \xi E_{r\_eff} - \mu\omega(M - \bar{M})$$

At the social-relational scale, the decline of E_r_eff appears first as the decline of M. In this paper, this cessation of recomputation at the social-relational scale is treated as corresponding to the atrophy of u at the subject-internal scale in RD — a minimum correspondence hypothesis rather than an identity claim.

Following the decline of M and u, adaptive capacity A(e,u) = f(e) × g(u) enters multiplicative degradation. Because e and u are not substitutable, the decline of either one drives A toward zero regardless of the level of the other.

**The prior erosion of T_eval**

Once M and u have declined, evaluative autonomy T_eval undergoes erosion. T_eval lies at the intersection that simultaneously receives pressure from two directions: the impoverishment of input caused by the decline of D, and the rise in processing cost caused by the decline of M and u.

The paralysis of T_eval is not the disappearance of evaluative capacity. It is a shift in evaluative mode: from treating difference as a recomputation resource toward eliminating it early. This shift is self-reinforcing — a T_eval oriented toward difference elimination will tend to process even the signal that something is wrong as noise to be eliminated.

**The fixation of T_val**

When T_eval shifts toward difference elimination, all updating input to T_val is cut off. T_val then becomes fixed. Fixed T_val appears from the outside as consistent value retention, but this consistency is not the result of adaptation — it is the persistence of a halted state.

**What remains: the structure of Region B**

At the endpoint of this chain, the residual structure can be stated precisely.

*What remains:* structural stability σ and cognitive autonomy T_cog. Surface functioning is preserved. The subject continues to process information, answer questions, and produce output.

*What has ceased or become fixed:* recomputation capacity M has ceased; evaluative autonomy T_eval has ceased functioning as a recomputation resource; value autonomy T_val has become fixed.

This is the state defined in this paper as Region B — apparently normal, internally halted.

**The compressed form of the chain**

$$\omega \uparrow + L_c \uparrow \rightarrow C \uparrow \rightarrow D \downarrow \rightarrow Var(\varphi) \downarrow\ /\ e \downarrow\ /\ \text{input to } T_{eval} \text{ impoverished}$$

$$\rightarrow E_{r\_eff} \downarrow \rightarrow M \downarrow\ /\ u \downarrow \rightarrow A(e,u)\text{ multiplicative degradation}$$

$$\rightarrow T_{eval}\text{ paralysis} \rightarrow T_{val}\text{ becomes fixed}$$

$$\rightarrow \sigma,\ T_{cog}\text{ remain} \rightarrow \textbf{Region B}$$

In one sentence: judgment delegation depletes difference-retention; the depletion of difference-retention arrests recomputation; the arrest of recomputation erodes evaluative autonomy and fixes value autonomy. The subject stops before it breaks.

---

### 4.2 The Mechanism of Multiplicative Degradation

Section 4.1 described the minimal causal chain in its expanded form. This section examines in detail why the degradation of adaptive capacity A(e,u) proceeds not as a linear decline but as a mutually amplifying process — and why this multiplicative structure makes recovery through partial intervention insufficient.

**The multiplicative structure and its consequence**

As established in Section 2.2, adaptive capacity is modeled as:

$$A(e, u) = f(e) \times g(u)$$

In a multiplicative structure, if either e or u approaches zero, A approaches zero regardless of the level of the other. e and u are not substitutable; A is established only when both are maintained above a certain level.

This has a direct consequence for intervention. Restoring only e without restoring u, or restoring only u without restoring e, is insufficient to restore A. Both must be brought above threshold simultaneously.

**The connection between D and e, M and u**

The decline of D appears directly as the atrophy of e: when D declines, the diversity of paths available for comparison contracts, and e cannot be sustained.

The cessation of M at the social-relational scale corresponds to the atrophy of u at the subject-internal scale. This remains a minimum correspondence hypothesis rather than an identity claim. But its consequence is clear: in a system in which recomputation no longer arrives from the outside, the internal initiation of update also becomes difficult to sustain.

$$D \downarrow \Rightarrow e \downarrow \Rightarrow f(e) \downarrow$$

$$M \downarrow \Rightarrow u \downarrow \Rightarrow g(u) \downarrow$$

$$\therefore A(e,u) = f(e) \times g(u) \downarrow\downarrow$$

The double arrow on the final line is intentional. The decline of f(e) and the decline of g(u) do not simply add; they multiply. A system in which both e and u are declining simultaneously degrades faster than one in which only one is declining.

**Why the degradation is self-reinforcing**

The multiplicative structure produces a self-reinforcing dynamic. When e declines, the material available for u to act on becomes sparse. When u atrophies, the capacity to regenerate e through active exploration is lost. Each decline feeds the other.

This is the mechanism behind what RD terms update inertia debt: the nonlinear, compounding accumulation of unrealized L3 operations. Each deferred frame reset raises the cost of the next one. The debt does not accrue linearly; it compounds, because each round of deferral further depletes both e and u.

**The relationship to Region B**

The multiplicative degradation of A(e,u) is not the final endpoint of the chain; that endpoint is Region B, where σ and T_cog remain while M and T_eval have ceased and T_val has become fixed. But multiplicative degradation is the mechanism that makes Region B difficult to exit once the multiplicative dynamic has taken hold.

In Region B, e has been depleted and u has atrophied. To exit Region B requires restoring both simultaneously. But restoring e requires the supply of difference inputs, which depends on D being replenished from outside. Restoring u requires the re-initiation of update, which depends on sufficient E_r_eff and the availability of H (suspension capacity). None of these conditions can be met through individual effort alone once the multiplicative dynamic has taken hold.

**Summary**

The multiplicative structure A(e,u) = f(e) × g(u) ensures that the depletion of e and the atrophy of u amplify each other nonlinearly. Neither can substitute for the other, and partial restoration of one without the other is insufficient to restore adaptive capacity. This mechanism is what makes Region B self-reinforcing and what makes intervention from outside, rather than individual effort alone, structurally necessary.

---

### 4.3 Prior Erosion of T_eval and Fixation of T_val

Sections 4.1 and 4.2 described the degradation of adaptive capacity and its self-reinforcing structure. This section examines what happens inside the autonomy tensor T as that degradation proceeds — specifically, why T_eval is the primary site of erosion, and why the fixation of T_val follows as a structural consequence.

**Why the components of T do not degrade uniformly**

The autonomy tensor T = (T_cog, T_aff, T_eval, T_mot, T_val) is composed of components that can change non-uniformly with respect to each other. Subject-injury does not produce uniform decline across all components. It produces a specific sequence of erosion, and understanding that sequence is what makes the internal mechanism of subject-injury legible.

The sequence identified in this paper is: T_eval erodes first; T_val becomes fixed as a consequence; T_cog remains throughout. This is not presented here as a merely contingent empirical observation; it follows from the structural position each component occupies in the variable system.

**The structural position of T_eval**

T_eval (evaluative autonomy) is the capacity to assess what is different or discrepant through one's own judgment — to register a difference and convert it into a resource for recomputation. In the variable system of this paper, T_eval functions as a converter: it takes difference inputs supplied by D and transforms them into recomputation resources.

This structural position places T_eval at an intersection simultaneously exposed to two sources of pressure.

From the input side: the decline of D impoverishes the inputs reaching T_eval. T_eval continues to function as a converter, but under conditions in which the material being supplied for conversion is diminishing.

From the processing side: as M and u decline, E_r_eff becomes constrained. In a system with constrained recomputation energy, the cost of holding difference as significant rises relative to the cost of eliminating it early. Early elimination of difference as noise becomes the cost-minimizing stable strategy.

T_eval is therefore the component most directly exposed to both of these pressures simultaneously, which is why it is the primary site of erosion. The components T_aff and T_mot do not occupy this same intersection and are therefore not the primary sites of erosion in the minimal causal chain described here.

**The nature of T_eval paralysis**

The paralysis of T_eval is not the disappearance of evaluative capacity. The subject does not lose the ability to evaluate. What changes is the direction of that evaluative capacity: it shifts from treating difference as a resource for recomputation toward eliminating difference early as noise.

This shift is self-reinforcing in a way that compounds the overall degradation. A T_eval oriented toward difference elimination does not merely fail to generate recomputation resources — it actively reduces D by processing incoming differences as noise before they can enter the recomputation circuit. Furthermore, because T_eval is the converter through which the signal that something is wrong would ordinarily be processed, a T_eval shifted toward difference elimination will tend to process that signal as noise as well.

**The fixation of T_val**

When T_eval shifts toward difference elimination, all updating input to T_val is cut off. T_val — the capacity to sustain, through one's own judgment, the value frame that determines what is to be protected and followed — depends on T_eval delivering updated evaluative input. Once that delivery ceases, T_val can no longer be updated.

T_val then becomes fixed: it continues to hold its existing value frame, but that frame is no longer being tested against or updated by new evaluative input. From the outside, fixed T_val appears as consistent value retention. But this consistency is not the result of continued adaptation. It is the persistence of a frame that has stopped being updated.

The gap between the fixed T_val frame and the external environment accumulates invisibly, because the component responsible for detecting and processing that gap — T_eval — has already shifted away from that function.

**The residual of T_cog and the production of diagnostic invisibility**

Throughout this process, T_cog remains relatively intact. As long as T_cog remains, the subject continues to process information, generate responses, complete tasks, and produce coherent output. None of the surface indicators that institutions and observers typically use to evaluate functioning are reflected in ways that standard evaluation can register.

This is the precise mechanism by which subject-injury produces diagnostic invisibility. The components that have eroded — T_eval and T_val — are not the components that generate observable output. The component that generates observable output — T_cog — has not eroded. Measurable performance and substantive degradation are therefore fully dissociated, which is why standard performance indicators are structurally unable to detect the progression of subject-injury.

This dissociation is not incidental. It is the defining structural feature of Region B: σ and T_cog remain; M and T_eval have ceased and T_val has become fixed. The subject has not broken down. It continues to function. But the functions that remain are not those that constitute subjectivity in the sense defined by this paper.

**Summary**

T_eval is the primary site of erosion in subject-injury because it occupies the structural intersection that simultaneously receives pressure from the depletion of D and the atrophy of M and u. Its paralysis is not the loss of evaluative capacity but a shift in evaluative mode — from treating difference as a recomputation resource to eliminating it early. This shift cuts off updating input to T_val, producing its fixation. Throughout this process, T_cog remains, generating the diagnostic invisibility that is the defining feature of Region B.

---

### 4.4 Subject-Injury as Region B

Sections 4.1 through 4.3 described the minimal causal chain, the mechanism of multiplicative degradation, and the prior erosion of T_eval followed by the fixation of T_val. This section collects these analyses into a single state definition: Region B. It also establishes the critical distinction between Region B as a state and subject-injury as a process — a distinction with direct consequences for how intervention is conceived.

**The definition of Region B in this paper**

In OMD, Region B is defined as the state in which σ is maintained while M has ceased. This paper extends the definition to the scale of the individual subject:

> Region B is the state in which structural stability σ and cognitive autonomy T_cog remain while recomputation capacity M and evaluative autonomy T_eval have ceased and value autonomy T_val has become fixed.

The simultaneous satisfaction of these conditions is what defines Region B. It is not sufficient for σ and T_cog to remain — they remain in many states that are not Region B. It is not sufficient for M and T_eval to have ceased and T_val to have become fixed — their cessation without the residual of σ and T_cog would produce visible breakdown rather than the invisible degradation that characterizes Region B. It is the co-occurrence of residual surface functioning with internal cessation that constitutes the defining condition.

**Region B as a state, subject-injury as a process**

A critical distinction must be drawn between Region B and subject-injury.

Region B is a state definition: it specifies a configuration of the variable system at a given point in time.

Subject-injury is a process definition: it refers to the transition toward Region B — the progressive depletion of D, the multiplicative degradation of A(e,u), the prior erosion of T_eval, and the fixation of T_val, as described in Sections 4.1 through 4.3.

This distinction matters for three reasons.

First, it prevents a diagnostic error. Classifying a system in Region B as a non-subject forecloses the possibility of intervention. The subject has not ceased to exist as a subject in any absolute sense; what has been lost is the functional capacity that constitutes subjectivity as operationally defined in this paper. Recognizing Region B as an arrested process rather than a terminal state preserves the conceptual space for intervention.

Second, it secures the theoretical role of Sections 4.1 through 4.3. Without a process definition, the causal chain described in those sections would have no theoretical home. The process definition gives the causal chain its purpose: it is the description of how a system arrives at Region B.

Third, it determines the direction of intervention design. Intervening in a state requires identifying what has ceased and supplying what is missing. Intervening in a process requires identifying where in the chain the process can be interrupted or reversed.

**The diagnostic invisibility of Region B**

Standard performance indicators — response speed, task completion, output consistency, surface stability — depend primarily on T_cog and σ. Because T_cog and σ remain in Region B, these indicators continue to read as normal or even high.

The cessation of M, the shift of T_eval into difference-elimination mode, and the fixation of T_val are not reflected in T_cog-based output. This is not a matter of measurement precision. It is a matter of what is being measured. Indicators oriented toward T_cog and σ are structurally unable to detect the degradation of M, T_eval, and T_val — not because they are insufficiently sensitive, but because they are not measuring those components.

**The self-maintaining character of Region B**

Region B is not simply a state that persists passively. As described in Section 4.2, the multiplicative degradation of A(e,u) is self-reinforcing: the depletion of e makes u harder to sustain, and the atrophy of u makes e harder to regenerate. This dynamic does not halt when Region B is reached — it continues to operate within Region B, deepening the cessation.

Furthermore, a T_eval shifted into difference-elimination mode actively processes incoming difference as noise, further reducing D. The subject's own evaluative function has become a mechanism that reinforces the conditions of its own arrested state.

Region B therefore has a degree of path dependence: the longer a system remains in Region B, the more the conditions for exiting it are eroded. This paper does not claim that Region B is impossible to exit, but exit becomes progressively more difficult without external intervention.

**Summary**

Region B is defined as the state in which σ and T_cog remain while M and T_eval have ceased and T_val has become fixed. Subject-injury is the process of transition toward that state. The distinction between the two determines whether intervention is conceived as supplying what has ceased or as interrupting the process that produces the cessation. The diagnostic invisibility of Region B follows from the residual of T_cog, which ensures that performance-based indicators continue to read as normal. And the self-maintaining character of Region B means that exit becomes progressively more difficult without intervention from outside the system.

---

## 5. Implications

### 5.1 Diagnostic Implications

Section 4 established the minimal causal chain of subject-injury and its terminus in Region B. This section draws out the diagnostic implications — specifically, what the structure of Region B means for how subject-injury can and cannot be detected, and what kind of indicators are theoretically capable of tracking it.

**The three-layered structure of diagnostic difficulty**

The diagnostic difficulty of Region B is not a single problem but a three-layered structure. Each layer compounds the others.

The first layer is the non-observability of the key state variables. Recomputation capacity M and update capacity u are not directly observable. Their states must be inferred from observable traces in output sequences rather than measured directly. This is structural inference from observable traces rather than direct measurement.

The second layer is the identifiability problem of proxy indicators. Observable variables such as rate of objection, frequency of policy revision, and rate of alternative-proposal generation do not uniquely identify M or u. The relevant question is not whether a given indicator measures M, but whether a change in that indicator is theoretically predictable as a consequence of M declining. Consistency between theoretical prediction and observation is the basis for inference, not direct correspondence between indicator and variable.

The third layer is the failure of self-diagnosis in Region B. A T_eval shifted into difference-elimination mode tends to process the internal signal that something is wrong as noise to be eliminated. The result is that subjective reports of normal functioning can become positively aligned with the depth of subject-injury. Self-report alone is therefore structurally insufficient as a diagnostic basis for Region B.

These three layers interact and must be addressed simultaneously for diagnosis to be possible at all.

**Proxy indicator candidates**

Despite these difficulties, theoretical inference remains possible. The following observable variables are proposed as proxy indicator candidates — not as measures of M and u, but as variables whose change is theoretically predictable as a consequence of M declining.

*Frequency of policy revision:* a subject in Region B, having lost the capacity for L3-level frame reset, will show a declining tendency to revise the strategies and framings it operates under, even when environmental conditions change in ways that would ordinarily prompt revision.

*Rate of alternative-proposal generation:* a subject in Region B, with e depleted, will show a declining tendency to generate alternatives to current approaches — not because it lacks cognitive capacity (T_cog remains), but because the material for generating alternatives (D-supplied difference) has been depleted.

*Rate of objection and dissent:* a subject in Region B, with T_eval in difference-elimination mode, will show a declining tendency to register objection or dissent — not because it has no capacity for judgment, but because the evaluative mode has shifted toward eliminating rather than holding difference.

These candidates share a common feature: they are oriented toward the residual traces of M and D rather than toward the outputs of T_cog.

**The limitation of these candidates**

Several limitations must be acknowledged. First, declining frequency of revision, alternative generation, or objection can result from causes other than M decline. Second, the threshold at which decline becomes diagnostically significant is not specified by the theory and would require empirical calibration. Third, longitudinal data is required to distinguish sustained decline from temporary variation.

**The phenomenological signal**

A separate and earlier signal may precede the full establishment of Region B: the subject's own sense that something is wrong — that evaluation has become difficult, that framings feel rigid, that responses feel increasingly automatic. This phenomenological signal, where it occurs, may function as an early indicator that precedes the full shift of T_eval into difference-elimination mode. However, this paper treats this signal as a preliminary observation rather than a formal diagnostic criterion.

**Summary**

The diagnostic invisibility of Region B has a three-layered structure: the non-observability of M and u, the identifiability problem of proxy indicators, and the failure of self-diagnosis produced by T_eval's shift into difference-elimination mode. Proxy indicator candidates — frequency of policy revision, rate of alternative-proposal generation, and rate of objection — are theoretically grounded in the residual traces of M and D rather than in T_cog-based output. Their empirical operationalization remains a task for future work.

---

### 5.2 Implications for Intervention

Section 5.1 established why Region B is difficult to detect and what kinds of indicators are theoretically capable of tracking it. This section addresses where intervention should be directed, and why certain apparently natural intervention targets are structurally insufficient.

**The starting point of intervention must be D**

The multiplicative structure established in Section 4.2 has a direct consequence for intervention: because e and u are not substitutable, partial restoration is insufficient. Restoring T_eval by providing evaluative stimulation does not restore T_eval's function if D has not been restored. The evaluative function may be stimulated, but it has no difference input to process.

Intervention must therefore begin upstream. The starting point is D: restoring the availability of difference inputs capable of disrupting the subject's existing frame. Without this, any downstream intervention addresses symptoms rather than the generating condition.

This supports the claim that D is the primary target of intervention. Reducing C is often a necessary component of restoring D. But reducing C alone is insufficient if D has already been depleted. The supply of difference must be actively restored, not merely unblocked.

**The role of H (suspension capacity)**

Restoring D is necessary but not sufficient to initiate recomputation. For recomputation to be initiated — specifically, for L3-level frame reset to become possible — the subject must have access to H (suspension capacity): the capacity to withdraw temporarily from the current processing cycle and create the interval within which recomputation becomes possible.

H corresponds formally to L3 in the update hierarchy of RD and to T_mot in the autonomy tensor. Without H, even a restored supply of D cannot generate recomputation: the difference arrives but cannot be held long enough to function as a resource. The institutional implication is significant: H cannot be generated through individual effort alone in a system that structurally eliminates it.

**The three conditions for L3**

The initiation of L3 (frame reset) requires three conditions to be satisfied simultaneously. First, D must be restored. Second, E_r_eff must be sufficient. Third, H must be available. These three conditions are multiplicative in their relationship, not additive. Satisfying any two without the third is insufficient for L3 to be initiated.

**Why individual effort alone is insufficient**

As established in Section 4.4, the multiplicative dynamic continues to operate within Region B, making exit progressively more difficult without external intervention. Restoring D requires difference inputs from outside the subject's existing frame — by definition, these cannot be generated internally by a subject whose T_eval has shifted into difference-elimination mode. Restoring H requires institutional accommodation of suspension. Restoring E_r_eff requires relief from the constrained conditions that depleted it.

None of these can be reliably met through individual effort in a system whose design actively removes them. This is the dynamic basis for the claim that subject protection is a structural requirement rather than an ethical supplement.

**Summary**

Intervention in subject-injury must begin from D rather than from downstream components. Restoring D is necessary but not sufficient: the initiation of L3 additionally requires sufficient E_r_eff and the availability of H. These three conditions are multiplicative — partial satisfaction is insufficient. Because none of the three can be reliably generated through individual effort in a system that structurally removes them, intervention requires institutional design rather than individual disposition alone.

---

### 5.3 Institutional Implications

Having established the dynamic basis and its implications, this section assesses what follows for the design of institutions from the analysis developed across this paper.

The claim developed in this section is not primarily normative. It is not that institutions ought to protect subjectivity because subjectivity is valuable. The claim is structural: institutions that systematically remove the conditions for D, H, and E_r_eff will reproduce Region B as a predictable output of their design, regardless of intent.

**Region B is institutionally reproducible**

The minimal causal chain does not require malicious intent, explicit coercion, or deliberate suppression to activate. It requires only that the institutional design reward high T_cog-based output while leaving the conditions for D, H, and E_r_eff structurally unprotected.

An institution that prioritizes speed of response structurally removes H. A system that standardizes evaluation axes and rewards convergence toward them structurally reduces D. A system that maximizes the demands on T_cog-based output while minimizing intervals for non-productive processing structurally depletes E_r_eff. Each of these design features is individually rational from the standpoint of institutional objectives. Their combination, however, systematically creates the conditions for the minimal causal chain to activate.

The detailed analysis of this reproductive cycle is developed in Child Paper 5.

**Why performance indicators systematically miss Region B**

Standard performance indicators are oriented toward T_cog and σ. Because T_cog and σ remain in Region B, these indicators continue to produce high readings precisely when and where subject-injury is most advanced. The institution reads high performance as evidence that its design is working and therefore reinforces that design.

This is not institutional failure in the ordinary sense. The institution is applying its evaluative framework in a domain to which it is structurally blind. Correcting this does not require better measurement within the existing evaluative framework. It requires expanding the evaluative framework itself — specifically, incorporating indicators oriented toward the residual traces of M and D rather than toward T_cog-based output. This is what Child Paper 5 describes as two-tier evaluation design.

**Subject protection as a structural requirement**

From the analysis of Sections 5.1 and 5.2, the conditions required for recomputation — D, H, and E_r_eff — cannot be reliably generated through individual effort in a system whose design systematically removes them. Subject protection — the institutional design that preserves the conditions for D, H, and E_r_eff — is therefore not an ethical supplement to institutional function. It is a structural requirement for institutions that aim to remain capable of self-correction.

An institution that has lost the capacity to detect its own Region B cannot correct the design that produces Region B from within that framework. It requires either an external evaluative layer or an internal institutional mechanism explicitly designed to remain oriented toward M and D rather than toward σ and T_cog.

**The minimum institutional design conditions**

The detailed derivation of institutional protection principles is the task of Child Paper 5. This paper's role is to establish the dynamic basis that those principles rest on. Stated at the level of the variable system: the minimum conditions for an institution to avoid systematically reproducing Region B are that it preserves the supply of D, accommodates H, and does not structurally deplete E_r_eff.

**Summary**

Institutions that prioritize T_cog-based output while leaving the conditions for D, H, and E_r_eff structurally unprotected will reproduce Region B as a predictable consequence of their design. Standard performance indicators are structurally blind to this reproduction because they are oriented toward T_cog and σ, which remain in Region B. Subject protection is therefore not an ethical supplement but a structural requirement for institutions that aim to maintain the capacity for self-correction. The detailed derivation of the minimum institutional design conditions is addressed in Child Paper 5.

---

## 6. Discussion

### 6.1 The Significance and Limits of Integrating the Three Frameworks

Having established the dynamic basis and its implications, this section assesses what the integration of OMD, RD, and RLAF achieves — and what it does not achieve. Both must be stated with equal clarity.

**What integration makes visible**

The primary contribution of integrating the three frameworks is the identification of D as the common upstream variable for recomputation across OMD, RD, and RLAF.

Prior to this integration, Var(φ), e, and the operating precondition of T_eval were treated as framework-specific variables serving framework-specific theoretical purposes. Integration shows that all three refer to the same type of functional loss — the depletion of difference as the shared resource for recomputation — and that this loss is what generates the subject-injury dynamics described in each framework. This identification repositions the target of diagnosis and intervention: from framework-specific downstream components toward the common upstream supply condition.

The second contribution is the formalization of subject-injury as invisible degradation — the dissociation of surface functioning from internal updating — across all three frameworks. OMD describes Region B as a diagnostic blind spot at the system level. RD describes the multiplicative degradation of A(e,u) as a nonlinear process that standard indicators do not track. RLAF describes the dissociation between T_cog-based output and the erosion of T_eval and fixed T_val. Across all three, the same structure appears: surface functioning is preserved while internal updating has ceased. Integration shows that this is not three separate phenomena but one phenomenon described at three different scales.

**The methodological limits of the integration**

The integration has three methodological limits.

First, the correspondences between variables are theoretical correspondences, not empirical identifications. The correspondence between D and Var(φ), between D and e, between D and the operating precondition of T_eval — these are correspondences of functional role, not demonstrations that the same underlying quantity is being measured in each case.

Second, the scale-crossing in the present integration is posited rather than formally derived. The three frameworks operate at different scales. Whether the claim that D functions as the upstream variable applies in structurally equivalent form across all three scales remains to be demonstrated.

Third, the minimal causal chain is a simplification. The chain as presented abstracts from the feedback loops, time lags, individual variation, and contextual factors that would be present in any empirical instance. The chain is a theoretical minimum, not a complete model. The simplification is methodologically justified — a minimal causal chain is more falsifiable than a fully specified model — but it means that the chain as stated is not intended as a complete description of any particular empirical case.

**The relationship to existing research**

The integration is not positioned as a replacement for the frameworks of promotion that characterize existing research on autonomy and agency. Promotion and erosion can be understood as opposite directional outcomes within the same variable system. The integration adds an erosion account to a literature that has been predominantly oriented toward promotion; it does not invalidate the promotion literature.

**Summary**

The integration of OMD, RD, and RLAF identifies D as the common upstream variable for recomputation across all three frameworks and formalizes subject-injury as invisible degradation across all three scales of description. Its methodological limits are three: the correspondences between variables are theoretical rather than empirical; the scale-crossing is posited rather than formally derived; and the minimal causal chain is a simplification rather than a complete model. These limits do not invalidate the integration but specify the conditions under which its claims can be extended, tested, and refined.

---

### 6.2 Remaining Questions

Section 6.1 established what the integration achieves and where its limits lie. This section identifies the specific empirical and theoretical questions that remain open.

**The empirical relationship between ω and L_c**

This paper treats ω and L_c as independent parallel inputs. Whether an empirical causal relationship exists between them — and under what conditions — is a question this paper does not answer. If such a relationship exists and is sufficiently strong, it would modify the input structure of the minimal causal chain.

**The operationalization of D**

D is defined as the preservation and availability of difference inputs capable of prompting re-evaluation of the subject's existing frame. This definition is theoretically precise but operationally underdeveloped. D cannot be operationalized purely from the supply side; it requires some characterization of the subject's frame against which the disruption potential of an input is evaluated. A further complication is that operationalization may need to differ across scales.

**The design of proxy indicators for M and u**

Section 5.1 proposed three proxy indicator candidates for M. Several questions remain. First, what is the identifiability ceiling of these indicators? Second, what threshold of decline is diagnostically significant? Third, are the three candidates the best available, or are there proxy indicators with higher sensitivity and specificity?

**The empirical identification of Region B**

The theoretical characterization is clear. The empirical identification of Region B in any given case — determining that a subject or system is in Region B rather than in a state of temporary low activity, strategic non-participation, or deliberate conservation — requires criteria that this paper does not fully specify. The issue of path dependence is especially relevant here: the threshold at which this path dependence becomes empirically detectable, and the counterfactual conditions required to demonstrate it, are not established by the theory alone.

**The scale-crossing conditions**

Whether the chain applies in structurally equivalent form at the organizational or civilizational scales requires separate theoretical development and separate empirical investigation. The parent paper and Child Paper 4 address scale-crossing at the theoretical level; empirical confirmation remains open.

**The prior erosion sequence**

This paper identifies T_eval as the primary site of erosion preceding the fixation of T_val. Whether this sequence is empirically confirmed requires longitudinal measurement of both components independently. Empirical confirmation of this sequence would substantially strengthen the theoretical account; disconfirmation would require revision of the structural argument about the position of T_eval in the variable system.

**Summary**

Six empirical and theoretical questions remain open. These questions do not invalidate the integration but specify the conditions under which its claims can be tested and refined.

---

## 7. Conclusion

### 7.1 Restatement of Central Claims

This section restates the five central claims of this paper in their final form — not as a summary of the paper's contents but as a precise formulation of the claims for which the paper provides theoretical warrant.

**Claim 1: Subject-injury precedes visible breakdown**

Subject-injury does not begin with visible breakdown. Structural collapse is typically preceded — and systematically obscured — by the silent cessation of recomputation: a condition in which surface functioning and cognitive output persist while the capacity for internal updating has already ceased. The phenomenon that standard indicators are designed to detect — deterioration of output, instability of response, breakdown of surface functioning — belongs to a later stage of the process, not to its defining onset.

**Claim 2: Region B is a diagnostic blind spot produced by the residual of T_cog**

Region B is the state in which structural stability σ and cognitive autonomy T_cog remain while recomputation capacity M and evaluative autonomy T_eval have ceased and value autonomy T_val has become fixed. Because T_cog remains, observable output continues. Because M, T_eval, and T_val have ceased or become fixed, internal updating has stopped. Standard performance indicators, being oriented toward T_cog-based output, are structurally unable to detect this cessation.

**Claim 3: The depletion of D is the common upstream condition across all three frameworks**

Across OMD, RD, and RLAF, difference-retention D functions as the shared upstream condition for recomputation. In OMD, its depletion appears as the decline of Var(φ). In RD, its depletion appears as the atrophy of e. In RLAF, its depletion appears as the loss of the operating precondition of T_eval. The depletion of D is not three separate problems in three frameworks; it is one problem described at three scales.

**Claim 4: The degradation of adaptive capacity is multiplicative, not linear**

The degradation of adaptive capacity A(e,u) = f(e) × g(u) proceeds through the mutual amplification of e depletion and u atrophy. Because the structure is multiplicative rather than additive, neither component can substitute for the other, and partial restoration of one without the other is insufficient to restore A. This multiplicative structure is what makes Region B self-reinforcing and what makes exit from Region B progressively more difficult without external intervention once the arrested state has been established.

**Claim 5: T_eval is the primary site of erosion; T_val fixation is its consequence**

Among the components of the autonomy tensor T, T_eval is the primary site of erosion because it occupies the structural intersection simultaneously exposed to two sources of pressure: the impoverishment of input caused by the decline of D, and the rise in processing cost caused by the decline of M and u. The paralysis of T_eval is not the loss of evaluative capacity but a shift in evaluative mode — from treating difference as a recomputation resource to eliminating it early as noise. This shift cuts off all updating input to T_val, producing its fixation. T_cog remains throughout, generating the diagnostic delay that characterizes Region B.

**The unified statement**

These five claims can be unified in a single statement:

> Subject-injury is invisible degradation in which the depletion of difference-retention depletes the common upstream condition for recomputation across all three frameworks; the resulting degradation of adaptive capacity proceeds multiplicatively through the prior erosion of evaluative autonomy and the fixation of value autonomy; and throughout this process, the residual of cognitive autonomy ensures that surface functioning is preserved and standard indicators continue to read as normal or successful.

---

### 7.2 Theoretical Contributions

This section states the theoretical contributions of this paper — what it adds to existing research and what kind of addition it is.

**Contribution 1: The identification of D as a common upstream variable**

The primary theoretical contribution of this paper is the identification of D (difference-retention) as the common upstream variable for recomputation across OMD, RD, and RLAF.

Prior to this integration, the variables Var(φ), e, and the operating precondition of T_eval were treated as framework-specific variables serving framework-specific theoretical purposes. The integration shows that all three refer to the same type of functional loss — the depletion of difference as the shared resource for recomputation. This identification repositions the target of diagnosis and intervention: from framework-specific downstream components toward the common upstream supply condition.

**Contribution 2: The formalization of subject-injury as invisible degradation**

The second contribution is the formalization of subject-injury not as destruction but as invisible degradation — the dissociation of surface functioning from internal updating.

The prevailing orientation in existing research treats subjectivity loss as suppression, coercion, or visible breakdown. This paper formalizes a complementary account: a model of subjectivity loss that is structurally invisible to the evaluative frameworks most commonly applied to detect it. The defining feature of this model — that T_cog remains while M and T_eval have ceased and T_val has become fixed — means that the loss is not detectable by T_cog-based performance indicators. This is not a gap in measurement sensitivity. It is a structural mismatch between what is being measured and what has been lost.

The formalization provides what had not previously been articulated in this integrated form: a theoretical basis for the claim that subject-injury can be widespread, advanced, and systematically undetected within high-performing institutional environments.

**Contribution 3: The integration of three independent research frameworks**

The third contribution is methodological: the demonstration that OMD, RD, and RLAF — developed independently and for different purposes — can be integrated within a single variable system without requiring modification of any of the three.

The integration is achieved not by merging the frameworks but by identifying the common upstream variable D and the common output variable S, and showing how the framework-specific variables correspond to these common variables at different scales of description. This integration method — identifying correspondence at the level of functional role rather than asserting identity of variables — is generalizable to other integrations of independently developed frameworks.

**What this paper does not contribute**

This paper does not contribute an empirically validated causal model. The minimal causal chain is a theoretical minimum, not a statistical model of incidence or rate. It does not contribute operational measurement instruments — the proxy indicators proposed in Section 5.1 are theoretically grounded candidates, not validated instruments. It does not contribute institutional design specifications — the detailed design of institutional mechanisms is addressed in Child Paper 5.

**Summary**

This paper makes three theoretical contributions: the identification of D as the common upstream variable for recomputation across three independent frameworks; the formalization of subject-injury as invisible degradation, structurally undetectable by standard performance indicators; and the demonstration of an integration method that identifies correspondence at the level of functional role without requiring modification of the source frameworks.

---

### 7.3 What Has Been Redefined

This section states explicitly what this paper redefines — not the introduction of a new concept where none existed, but the revision of an existing formulation in a way that changes what the concept can and cannot describe.

**What has been redefined: subject-injury**

The prevailing orientation treats subjectivity loss as suppression, coercion, or visible breakdown: a condition in which the deterioration is in principle detectable by the evaluative frameworks already in use.

This paper redefines subject-injury as follows:

> Subject-injury is not destruction but invisible degradation: the depletion of difference-retention depletes the shared upstream condition for recomputation; the resulting degradation of adaptive capacity proceeds multiplicatively through the prior erosion of evaluative autonomy and the fixation of value autonomy; and throughout this process, the residual of cognitive autonomy ensures that surface functioning is preserved while internal updating has ceased.

This redefinition changes three things. First, it separates the concept of subjectivity loss from the concept of visible breakdown — they are no longer successive phases of the same event; they are structurally different phenomena. Second, it makes subject-injury detectable in principle by a different class of indicators. Third, it makes subject-injury institutionally locatable — it can occur, and may characteristically occur, in high-performing environments where no indicator of dysfunction is visible.

**What has been redefined: the target of intervention**

Prior frameworks for supporting autonomy and agency direct intervention toward downstream components: providing evaluative stimulation, restoring motivational support, reconnecting subjects with their values.

This paper redefines the target of intervention as the upstream supply condition: D, with H and E_r_eff as the additional necessary conditions for recomputation to be initiated. This redefinition does not replace existing intervention frameworks. It adds a layer that precedes them: before asking how to restore T_eval or T_val, the question must be whether D is being supplied, whether H is institutionally available, and whether E_r_eff is sufficient.

**What has been redefined: the evaluative framework for detection**

The prior assumption — implicit rather than stated — is that subject-injury will eventually become visible in performance-based indicators because T_cog-based output and internal updating are correlated.

This paper redefines this assumption as a structural error. In Region B, T_cog and σ remain precisely while M and T_eval have ceased and T_val has become fixed. The correlation between T_cog-based output and internal updating does not hold in Region B — it breaks down at exactly the point where subject-injury is most advanced. The redefinition requires a two-tier evaluative framework: one tier oriented toward T_cog-based performance, and a second tier oriented toward the residual traces of M and D.

**The unified statement of what has been redefined**

Three things have been redefined: the nature of subject-injury, from visible breakdown to invisible degradation; the target of intervention, from downstream components to the upstream supply condition D; and the evaluative framework for detection, from single-tier performance-based indicators to a two-tier design.

These three redefinitions follow from the same structural analysis: the residual of T_cog in Region B is the common source of all three — it is what makes subject-injury invisible, what makes downstream intervention insufficient, and what makes single-tier performance indicators structurally misleading.

---

### 7.4 Connection to Future Work

The analysis of this paper connects to subsequent work in two directions.

**Direction 1: Institutional design — Child Paper 5**

Section 5.3 established that the conditions required for recomputation — D, H, and E_r_eff — cannot be reliably generated through individual effort in a system whose design systematically removes them. Subject protection is therefore not a supplement to institutional design but a structural requirement of it.

This paper establishes the dynamic basis for that claim. The detailed translation of that basis into institutional design principles is the task of Child Paper 5, which derives four institutional protection principles from this dynamic basis and shows that these principles form a multiplicative structure: partial implementation may yield local improvement, but structural stability requires their simultaneous satisfaction.

The handoff from this paper to Child Paper 5 is therefore precise: this paper provides the variable system and the causal chain; Child Paper 5 translates them into the minimum design conditions for institutions that aim to avoid reproducing Region B.

**Direction 2: The conceptual map — the parent paper**

This paper describes the minimal causal chain of subject-injury at the individual subject scale. Several questions about how this chain connects to the broader conceptual architecture of the research program are outside the scope of this paper. These questions are addressed in the parent paper, *Toward a Theory of Subjectivity in the Age of AI*, which provides the conceptual map within which this paper's causal chain is located.

The handoff from this paper to the parent paper is also precise: this paper provides the dynamic account of how subject-injury proceeds at the individual scale; the parent paper provides the theoretical architecture within which that account is interpreted and from which its broader implications are drawn.

**The question this paper opened**

This paper departed from a single question: why does a subject stop before it breaks?

The answer this paper provides is formal: because the depletion of difference-retention depletes the shared upstream condition for recomputation; because the resulting degradation proceeds multiplicatively through the prior erosion of evaluative autonomy and the fixation of value autonomy; and because the residual of cognitive autonomy ensures that this process remains invisible to the evaluative frameworks most commonly used to detect it.

The question this paper opens — and passes to subsequent work — is practical: given that Region B is structurally invisible to standard evaluative frameworks, what institutional conditions are required to detect it, interrupt its production, and restore the conditions for recomputation? That question is the starting point of Child Paper 5.

---

## Appendix A: Variable Dictionary v1.0

This appendix provides definitions of all variables used in Child Paper 2.

### Common Variables (spanning all three frameworks)

| Symbol | Name | Definition |
|--------|------|-----------|
| D | Difference-retention | The preservation and availability of difference inputs capable of prompting re-evaluation of the subject's existing frame. Not the objective diversity of inputs, but the extent to which inputs capable of destabilizing the subject's existing frame are being preserved and supplied. The upstream variable common to all three frameworks. |
| C | Conformity pressure | The downward pressure on D arising from the combined effect of ω and L_c in the relational field. Native to this paper; does not appear in the source frameworks. |
| S | Subjectivity | The integrative output variable representing the degree to which subjectivity is preserved. Approximated as scalar α; complete description requires tensor T. |

### OMD Variables

| Symbol | Name | Definition |
|--------|------|-----------|
| Var(φ) | Evaluative diversity | The variance of evaluative orientation; the phase-space condition for recomputation. Corresponds to D at the collective scale. |
| M | Recomputation capacity | The integrated capacity to evaluate existing strategies, generate alternatives, and update. Independent of σ. |
| σ | Structural stability | The degree to which surface functioning is maintained. Independent of M. |
| ω | External cognitive feedback density | The density of exposure to feedback from AI and other external cognitive systems. The sole exogenous variable in OMD. |
| L_c | Judgment delegation | The degree to which core judgments — error detection, threshold-setting, direction selection — are externalized. Acts directly to reduce M. |
| L_p | Processing delegation | Auxiliary task delegation. Does not directly reduce D or M. Asymmetric with L_c. |
| E_r_eff | Effective recomputation energy | The available energy for initiating recomputation. Recomputation ceases when E_r_eff ≤ 0. |
| N_eff | Effective stimulus density | N_eff = ω × Var(φ). The condition for recomputation initiation. |

### RD Variables

| Symbol | Name | Definition |
|--------|------|-----------|
| e | Exploratory diversity | The entropy of effective alternatives; the extent to which alternatives to the current strategy remain available. The exploratory-space expression of D. |
| u | Update capacity | The product of correction speed and level of abstraction. |
| A(e,u) | Adaptive capacity | A = f(e) × g(u). Multiplicative structure: depletion of either component drives A toward zero regardless of the other. |
| L0–L3 | Update hierarchy | L0/L1: local correction; L2: strategic update; L3: frame reset. L3 is the formal analogue of suspension capacity H. |
| Update inertia debt | — | The nonlinear, compounding accumulation of unrealized L3 operations resulting from deferral. |

### RLAF Variables

| Symbol | Name | Definition |
|--------|------|-----------|
| α | Subject retention rate | Scalar approximation of subjectivity preservation. α = P(T). Conceals non-uniform component changes. |
| T | Autonomy tensor | T = (T_cog, T_aff, T_eval, T_mot, T_val). Components can change non-uniformly with respect to each other. |
| T_eval | Evaluative autonomy | The capacity to assess what is different or discrepant through one's own judgment. Functions as a converter transforming difference inputs into recomputation resources. Primary site of erosion in subject-injury. |
| T_val | Value autonomy | The capacity to sustain, through one's own judgment, the value frame determining what is to be protected and followed. Undergoes fixation following T_eval erosion. |
| T_mot | Motivational autonomy | Governs intrinsic drive and the capacity to suspend and restart. Corresponds to suspension capacity H. |
| T_cog | Cognitive autonomy | Governs information processing, inference, and response generation. Persists in Region B, producing diagnostic delay. |
| T_aff | Affective autonomy | Governs the relative independence of affective response. |
| P(T) | Tensor projection | The operation by which T is projected to scalar α. α = P(T). |

### Minimal Causal Chain (compressed reference)

$$\omega \uparrow + L_c \uparrow \rightarrow C \uparrow \rightarrow D \downarrow \rightarrow Var(\varphi) \downarrow\ /\ e \downarrow\ /\ \text{input to } T_{eval} \text{ impoverished}$$

$$\rightarrow E_{r\_eff} \downarrow \rightarrow M \downarrow\ /\ u \downarrow \rightarrow A(e,u)\text{ multiplicative degradation}$$

$$\rightarrow T_{eval}\text{ paralysis} \rightarrow T_{val}\text{ becomes fixed}$$

$$\rightarrow \sigma,\ T_{cog}\text{ remain} \rightarrow \textbf{Region B (apparently normal, internally halted)}$$

**In one sentence:** Judgment delegation depletes difference-retention; the depletion of difference-retention arrests recomputation; the arrest of recomputation erodes evaluative autonomy and fixes value autonomy. The subject stops before it breaks.

---

---

## Acknowledgments

The author received no external funding for this research and declares no conflicts of interest.

---

## Author's Note on AI-Assisted Research and Writing

The theoretical frameworks integrated in this paper — OMD, RD, and RLAF — were developed through an iterative research process involving AI-assisted analysis and critique. Large language model systems (Claude, GPT, and Gemini) were used as structured analytical interlocutors across successive drafts for conceptual testing, reformulation, and critical comparison. Final decisions regarding theory, framing, interpretation, wording, and all claims presented in this manuscript are the sole responsibility of the author.

---

## References

Ashery, A. F., Aiello, L. M., & Baronchelli, A. (2025). Emergent social conventions and collective bias in LLM populations. *Science Advances*, 11(20), eadu9368. https://doi.org/10.1126/sciadv.adu9368

Deci, E. L., & Ryan, R. M. (1985). *Intrinsic motivation and self-determination in human behavior*. Plenum Press.

Ryan, R. M., & Deci, E. L. (2000). Self-determination theory and the facilitation of intrinsic motivation, social development, and well-being. *American Psychologist*, 55(1), 68–78. https://doi.org/10.1037/0003-066X.55.1.68

Seligman, M. E. P. (1975). *Helplessness: On depression, development, and death*. W. H. Freeman.

---

*Child Paper 2 — English Full Text v1.9.1*
*Normative clarification added (1.2); Complete academic version: Keywords, Author Information, ORCID, Acknowledgments, AI Use Disclosure, References added*
*2026-03-22*
