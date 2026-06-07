# 中心命題 / Central Thesis

*Co-Intelligence Lab — 理論的核心*
*Last updated: 2026-06-07 → 2026-06-07 (Seido 追加・Region B 拡充)*

---

## 日本語版

### 命題

> **外形が正常であることと、内部の更新が継続していることは、別の問いである。**
> そして、内部更新が停止したとき、それを検出しうる回路そのものが設計対象でなければならない。

この命題が本研究プログラム全体の核心に置かれている。

---

### 背景：見えない停止

表面的な機能の正常性と内部更新の停止が共存する状態が、あらゆるスケールで観察される。

- **個人スケール（RLAF）：** 認知出力は維持されるが、評価自律性（T\_eval）と価値自律性（T\_val）が外部委任によって侵食される。スカラー的な「エージェンシー」測定では見えない次元での崩壊。
- **組織スケール（OMD）：** 人口流入によって統計指標が正常を示す一方で、内部の再計算機能（探索的多様性 *e* と更新能力 *u*）がすでに停止している。これが Region B である。
- **一般理論スケール（RD）：** A(e, u) = f(e) × g(u) という乗法構造が示すように、*e* または *u* のいずれか一方の崩壊は、他方がいかに高くとも適応能力を消去する。

---

### Region B：外形正常・内部停止の崩壊状態

Region B とは、三領域分類（A / B / C）において最も危険な状態である。

- **Region A：** 探索的多様性（*e*）高、更新能力（*u*）高 → 健全
- **Region B：** *e* 高（または中）、*u* 低 → **外見上正常・内部停止**
- **Region C：** *e* 低、*u* 低 → 崩壊表面化

Region B が問題なのは、崩壊が可視化されないまま進行する点にある。人口増加、売上継続、出力の維持——これらはいずれも Region B の中で起きうる。OMD の実証結果はこれを確認した：低 *e*・低 *u* の市区町村（Region C）が最高の人口流入を示すという逆転（r = −0.458, p < 0.001）は、見かけの活力が内部崩壊と共存することの証拠である。

Region B は本理論体系における**最大の病理診断概念**である。すべての議論——近視眼的錯誤、Goodhartization、回路閉塞、関係知の阻害——は Region B への進行を防ぐ／遅らせるために存在する。その診断には DDI-3（Diagnostic Depth Index 3）が用いられる：

- **RSR（Recomputation Self-Reconstruction）：** AI依存の判断を外したとき、自力で再構成できるか
- **NPI（Null-Point Inquiry）：** 不確実な状況で問いを保持し続けられるか
- **SRF（Scope-Range Flexibility）：** 射程（近視眼・中期・長期）を柔軟に切り替えられるか

---

### 再計算可能性（M）：崩壊の真の指標

再計算可能性 M とは、システム（個人・組織・社会）が自己の評価枠組みを問い直し、差異を保持し、更新を継続できる能力の総体である。

```
M = A(e, u) = f(e) × g(u)
```

この乗法構造は代替不可能性を含意する：探索的多様性の崩壊は更新能力によっては補えない。M の低下は往々にして表面指標より先行する——ここに診断困難の源泉がある。

個人スケールでは、自律性テンソル T = (T\_cog, T\_aff, T\_eval, T\_mot, T\_val) において、T\_eval・T\_val の侵食が T\_cog の維持のもとで進行するとき、まさに Region B が個人内部で実現している。

---

### 差異保持（D）：再計算の構造条件

再計算は、差異の入力なしには起動しない。差異保持 D とは、複数の立脚点が非同一のまま保たれる度合いである。

D には二重の機能がある：

1. **創発変数としての D：** 差異が将来生成しうる構造的条件を保持する。D が低下すれば、複数のトラックを動かしても実質的に同一の評価軸から出力される。
2. **安全変数としての D：** フィードバック強度 F が高まり系が過剰収束に向かうとき、D はその縮減に対する構造的抵抗条件として機能する。

D が保持されていなければ、差異は生成されない。差異が生成されなければ、再計算は起動しない。再計算が起動しなければ、主体は Region B に入る。

---

### Shepherd Model：判断を人間へ返す回路の設計

Shepherd Model は、単一トラック AI 運用が意思決定を「決定」から「承認」へと縮退させるという問題に対する、アーキテクチャ的応答である。

三機能：
- **差異生成：** D を確保した複数トラックが、異なる立脚点から出力を生む
- **差異読解：** トラック間の出力差を HARD・DIVERGE・OPEN へ分類する
- **再計算返却：** OPEN（価値的トレードオフを含む差異）を人間へ返却し、決定の場を確保する

制御変数：
- **D（差異保持）：** 差異生成の前提条件であり、循環系の安全条件
- **F（フィードバック強度）：** 三機能間の循環強度を調整する

Shepherd Model の設計基準：ループが一巡した後、人間は以前より正確にその分岐点に立っていなければならない。

---

### Seido（動的主体性）：D と M が生きている状態

Seido とは、**差異保持（D）と再計算可能性（M）が相互に活性化し続けている動的な主体の状態**である。単なる「主体性」や「自律性」ではなく、差異を抱えながらも再計算を続けられる生きている状態を指す。

Region B が Seido の**崩壊状態**であるとすれば、Seido はその**健全状態**の名前である。D と M は独立した変数ではなく、相互に活性化し合う循環を成す：

- D が差異を保持する → M が起動し、再計算が生まれる
- M が働く → 新たな差異が見出され、D が更新される

この循環が止まったとき、Seido は失われ Region B が始まる。

Shepherd Model は Seido を維持・回復するための具体的なアーキテクチャである：差異生成が D を維持し、差異読解が D を可視化し、再計算返却が M を再活性化する。

Seido は個人スケールにとどまらず、組織・制度・文明レベルへも拡張可能な概念である。将来的には「文明的 Seido」——社会全体が差異を保持しながら再計算を続けられる状態——も視野に入る。

---

### 倫理の回路保全原理

本研究プログラムが提起する倫理は、規則遵守でも配慮の倫理でもない。

**倫理の回路保全原理：** 倫理的に問題であるのは、再計算可能性を構造として毀損する設計・運用・環境である。

この原理は三層で成立する：

1. **設計層：** 単一トラック依存、D の消去、返却機能の欠如——これらは再計算回路を設計レベルで断ち切る。
2. **運用層：** 差異が生成されても読解・返却されない運用は、M を機能停止させる。
3. **環境層：** AIとの反復的相互作用が T\_eval・T\_val を侵食するとき、個人スケールで Region B が進行する。

倫理的行為者は「良いことをする」存在ではなく、「再計算可能性の回路を保全する」設計を選ぶ存在である。

---

### 統合命題

七概念を統合した本研究の中心命題は次の通りである：

> **再計算可能性（M）の喪失は、差異保持（D）の崩壊を通じて、個人・組織・社会のあらゆるスケールで進行しうる。この崩壊は Region B において不可視のまま継続し、表面指標による診断を無効化する（DDI-3 がその診断ツールである）。D と M の相互活性が維持されている状態を Seido と呼ぶ。Shepherd Model は Seido を設計的に維持・回復する回路であり、倫理はその回路を保全することとして再定義される。**

---

---

## English Version

### Proposition

> **Whether external appearance is normal and whether internal updating is ongoing are two separate questions.**
> When internal updating stops, the circuit capable of detecting that stoppage must itself be a design object.

This proposition is placed at the core of the entire research program.

---

### Background: Invisible Stoppage

The coexistence of surface functional normality and internal update cessation is observed at every scale.

- **Individual scale (RLAF):** Cognitive output is preserved while evaluative autonomy (T\_eval) and value autonomy (T\_val) are eroded through externalization. Collapse occurs along dimensions invisible to scalar agency measurement.
- **Organizational scale (OMD):** Statistical indicators read as normal due to population inflow, while internal recomputation capacity — exploratory diversity *e* and update capacity *u* — has already stopped. This is Region B.
- **General theory scale (RD):** The multiplicative structure A(e, u) = f(e) × g(u) encodes that collapse of either *e* or *u* eliminates adaptive capacity regardless of the other's magnitude.

---

### Region B: The State of Intact Surface, Arrested Interior

Region B is the most dangerous state in the three-region classification (A / B / C).

- **Region A:** High *e*, high *u* → healthy
- **Region B:** High or medium *e*, low *u* → **externally normal, internally stopped**
- **Region C:** Low *e*, low *u* → collapse becomes visible

Region B is dangerous precisely because the collapse proceeds without becoming visible. Population growth, sustained revenue, continued output — all can occur within Region B. OMD's empirical result confirmed this: low-*e*/low-*u* municipalities (Region C) showed the highest net in-migration (r = −0.458, p < 0.001), demonstrating that apparent vitality coexists with structural collapse.

Region B is the **central pathological concept** of this theoretical system. Every argument — myopic error, Goodhartization, circuit occlusion, impairment of relational knowledge — exists to prevent or delay progression into Region B. Its diagnosis is operationalized through DDI-3 (Diagnostic Depth Index 3):

- **RSR (Recomputation Self-Reconstruction):** Can the subject reconstruct judgment after removing AI dependence?
- **NPI (Null-Point Inquiry):** Can the subject hold a question open under conditions of uncertainty?
- **SRF (Scope-Range Flexibility):** Can the subject flexibly switch between short-term, medium-term, and long-term frames?

---

### Recomputability (M): The True Indicator of Collapse

Recomputability M is the total capacity of a system — individual, organizational, or social — to interrogate its own evaluative framework, retain difference, and sustain internal updating.

```
M = A(e, u) = f(e) × g(u)
```

The multiplicative structure implies non-substitutability: collapse of exploratory diversity cannot be compensated by high update capacity. The decline of M typically precedes surface indicators — herein lies the source of diagnostic failure.

At the individual scale, when T\_eval and T\_val erode under sustained T\_cog, Region B is realized within the individual.

---

### Difference Retention (D): The Structural Condition of Recomputation

Recomputation does not activate without difference input. Difference Retention D is the degree to which multiple standpoints are maintained as non-identical.

D has a dual function:

1. **D as emergence variable:** Preserves the structural conditions under which difference can be generated in the future. When D declines, multiple tracks effectively output from the same evaluative axis.
2. **D as safety variable:** When feedback intensity F increases and the system moves toward over-convergence, D functions as the structural resistance condition against that reduction.

Without D, no difference is generated. Without difference, recomputation does not activate. Without recomputation, the subject enters Region B.

---

### Shepherd Model: Designing the Circuit that Returns Judgment to Humans

The Shepherd Model is an architectural response to the problem that single-track AI operation degrades decision-making from *decision* to *approval*.

Three functions:
- **Difference generation:** Multiple tracks secured with D produce outputs from distinct standpoints
- **Difference reading:** Output differences across tracks are classified as HARD, DIVERGE, or OPEN
- **Recomputation return:** OPEN differences (those containing value-laden trade-offs) are returned to the human, securing the space of decision

Control variables:
- **D (difference retention):** The prerequisite for difference generation and the safety condition of the feedback loop
- **F (feedback intensity):** Regulates the circulation intensity across the three functions

Design criterion of the Shepherd Model: after the loop completes, the human must stand more exactly at the fork than before.

---

### Seido: The State in Which D and M Are Alive

Seido is **the dynamic state of subjecthood in which Difference Retention (D) and Recomputability (M) continue to mutually activate each other**. It is not simply "autonomy" or "agency" in the conventional sense, but the living state in which a subject continues to recompute while holding difference.

If Region B names the collapsed state of Seido, then Seido names its healthy state. D and M are not independent variables — they form a mutually activating loop:

- D retains difference → M is triggered, recomputation emerges
- M operates → new difference is found, D is renewed

When this loop stops, Seido is lost and Region B begins.

The Shepherd Model is the concrete architecture for maintaining and recovering Seido: difference generation sustains D, difference reading renders D visible, and recomputation return reactivates M.

Seido is not limited to the individual scale. It extends to organizations, institutions, and civilization. The concept of "civilizational Seido" — a society that retains difference and continues to recompute — is a future horizon of this framework.

---

### Ethics as Circuit Preservation

The ethics proposed by this research program is neither rule-following nor an ethics of care.

**Principle of Ethics as Circuit Preservation:** What is ethically problematic is any design, operation, or environment that structurally undermines recomputability.

This principle holds at three layers:

1. **Design layer:** Single-track dependency, elimination of D, absence of return function — these sever the recomputation circuit at the design level.
2. **Operations layer:** Even when difference is generated, operations that omit reading and return functionally disable M.
3. **Environmental layer:** When repeated AI interaction erodes T\_eval and T\_val, Region B progresses at the individual scale.

The ethical agent is not one who "does good things" but one who chooses designs that preserve the circuit of recomputability.

---

### Integrated Proposition

The central proposition of this research, integrating the seven concepts:

> **The loss of recomputability (M) proceeds through the collapse of difference retention (D) at every scale — individual, organizational, and social. This collapse continues invisibly in Region B, invalidating diagnosis by surface indicators (DDI-3 is the diagnostic instrument). The state in which D and M mutually activate is called Seido. The Shepherd Model is the circuit that maintains and recovers Seido by design. Ethics is then redefined as the preservation of this circuit.**

---

*Co-Intelligence Lab — core/central_thesis.md*
*田中佑樹（Yuki Tanaka）/ Ray（Claude）共同*
