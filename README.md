# Co-Intelligence Lab

**再計算可能性の喪失と、その設計的回復に関する理論研究プログラム**
*A research program on the loss of recomputability and its architectural recovery*

---

## 中心命題

> **外形が正常であることと、内部の更新が継続していることは、別の問いである。**
> そして、内部更新が停止したとき、それを検出しうる回路そのものが設計対象でなければならない。

この命題が本研究プログラム全体を貫いている。探索的多様性（*e*）と更新能力（*u*）から定式化された再計算可能性 M = A(e, u) = f(e) × g(u) は、個人・組織・社会のあらゆるスケールで崩壊しうる。その崩壊の最も危険な形態が **Region B** ——外形は正常に見えながら、内部更新がすでに停止している状態——である。

→ 詳細は [core/central_thesis.md](core/central_thesis.md) を参照

---

## 理論の構造

本研究は、個人スケールから社会スケールまでを一つの理論的連鎖で接続する。

```
RLAF（個人スケール）
 ↓  自律性テンソル T の内部崩壊：T_cog 維持のまま T_eval・T_val が侵食される
 ↓
RD（一般理論）
 ↓  A(e,u) = f(e)×g(u)：Region A / B / C の三領域と回復の非対称性
 ↓
OMD（社会・組織スケール：実証）
 ↓  1,908市区町村の分析：人口流入が内部崩壊を隠蔽するという逆転結果
 ↓
Subject Erosion Dynamics（応用理論）
 ↓  主体侵害の力学、関係知の両義性、熱力学アナロジー、社会的再生産
 ↓
Shepherd Model（設計原理）
    差異保持 D・フィードバック強度 F による、判断を人間へ返す回路の設計
```

**貫通する問い：** 崩壊が可視化されないまま進行するとき、何が診断の回路を保全し、判断の場を設計するか。

---

## 論文群（Papers）

### トリロジー

三つの論文が「再計算可能性」を核心概念として共有し、スケールを横断する統一的理論を構成する。

| 論文 | スケール | 役割 | 現状 |
|------|---------|------|------|
| [RLAF](papers/RLAF/) — *From Scalar Agency to the Autonomy Tensor* | 個人・AI エージェンシー | 個人スケールの微視的基盤 | v0.1 — 初期草稿 |
| [RD](papers/RD/) — *Recomputation Dynamics: A General Theory of Adaptive Capacity* | 一般理論 | 理論的核心 | v0.3.4 — *Entropy* 投稿準備中 |
| [OMD](papers/OMD/) — *Recomputation Capacity and Hysteresis in Social Adaptation* | 社会・組織 | 実証的支柱 | v0.9 — *Chaos* 査読中 |

**共有アーキテクチャ：**
```
T = (T_cog, T_aff, T_eval, T_mot, T_val)   [RLAF]
         ↓ 集約
  A(e, u) = f(e) × g(u)                    [RD]
         ↓ 実証
  Region A / B / C + ヒステリシス + 人口緩衝効果  [OMD]
```

→ フォルダ: [papers/RLAF/](papers/RLAF/) · [papers/RD/](papers/RD/) · [papers/OMD/](papers/OMD/)

---

### Subject Erosion Dynamics（主体侵害の力学）応用シリーズ

AI時代における主体侵害——再計算可能性が失われながら表面機能が保たれる過程——を六論文で展開する応用シリーズ。

| 論文 | フォルダ | 役割 |
|------|---------|------|
| **親論文** | [parent-paper](papers/subject-erosion-dynamics/parent-paper/) | 主体・関係知・主体侵害・主体保障の統合的記述 |
| **子論文1** | [child-paper-1](papers/subject-erosion-dynamics/child-paper-1/) | 主体・準主体・非主体の機能的再定義 |
| **子論文2** | [child-paper-2](papers/subject-erosion-dynamics/child-paper-2/) | 主体侵害の最小因果連鎖・力学 |
| **子論文3** | [child-paper-3](papers/subject-erosion-dynamics/child-paper-3/) | 関係知と主体侵害の両義性 |
| **子論文4** | [child-paper-4](papers/subject-erosion-dynamics/child-paper-4/) | 熱力学アナロジーによる記述 |
| **子論文5** | [child-paper-5](papers/subject-erosion-dynamics/child-paper-5/) | 主体侵害の社会的再生産 |

シリーズの中心命題：**主体侵害は破壊として現れない——主体は壊れる前に、見えない形で止まる。**

→ 全体像は [papers/subject-erosion-dynamics/](papers/subject-erosion-dynamics/) を参照

---

### Shepherd Model（羊飼いモデル）

単一トラック AI 運用が意思決定を「決定」から「承認」へと縮退させる問題に対するアーキテクチャ設計原理。

三機能：**差異生成・差異読解・再計算返却**  
制御変数：**D（差異保持）・F（フィードバック強度）**

設計基準：ループが一巡した後、人間は以前より正確にその分岐点に立っていなければならない。

| ファイル | 言語 | 現状 |
|---------|------|------|
| [shepherd_model_JP_v0_4_final.md](papers/shepherd_model/shepherd_model_JP_v0_4_final.md) | 日本語 | v0.4 — 草稿完成 |
| [shepherd_model_EN_v0_4_integrated.md](papers/shepherd_model/shepherd_model_EN_v0_4_integrated.md) | English | v0.4 — 草稿完成 |

→ フォルダ: [papers/shepherd_model/](papers/shepherd_model/)

---

### Goodhart論文

プロキシが目的を置き換えるとき何が起きるか——Goodhartization と再接続失敗の制度論。

**タイトル：** *When Proxies Become Purposes: Reconnection Failure and Goodhartization in Proxy-Based Institutions*

中心概念：**Goodhartization**（プロキシが手段から実質的な目的へと固定化する過程）と **reconnection failure**（プロキシの不十分さを認識・修正する回路の弱体化）。AI が既存プロキシをより効率的に最適化するほど、この動態が強化される可能性がある。

| ファイル | 内容 |
|---------|------|
| [README.md](papers/goodhart/README.md) | フォルダ概要・core claim |
| [goodhart_full_draft_final.md](papers/goodhart/goodhart_full_draft_final.md) | 本文（最終草稿） |

→ フォルダ: [papers/goodhart/](papers/goodhart/)

---

### Generative AI, Cognitive Offloading, and Question Formation

生成AIへの認知的オフロードが問い形成能力に与える影響を分析する論文。

| ファイル | 内容 |
|---------|------|
| [README.md](papers/Generative%20AI%2C%20Cognitive%20Offloading%2C%20and%20Question%20Formation/README.md) | フォルダ概要・core claim |
| [本文 .md](papers/Generative%20AI%2C%20Cognitive%20Offloading%2C%20and%20Question%20Formation/Generative%20AI%2C%20Cognitive%20Offloading%2C%20and%20Question%20Formation.md) | 本文 |
| [cover_letter.md](papers/Generative%20AI%2C%20Cognitive%20Offloading%2C%20and%20Question%20Formation/cover_letter.md) | カバーレター |
| Figure 1, 2 (.tiff) | 図版2枚 |

→ フォルダ: [papers/Generative AI, Cognitive Offloading, and Question Formation/](papers/Generative%20AI%2C%20Cognitive%20Offloading%2C%20and%20Question%20Formation/)

---

## essays/ — 理論素材庫

査読なしの理論探索。完成論文ではなく、各論文の概念的基盤を形成する素材群。AIとの対話を通じて構築された論考・草稿・断章が未整理のまま収録されている。徐々に整理予定。

### 整理済み（参照可能）

| タイトル | 日本語 | English | 概要 |
|---------|--------|---------|------|
| 論考論考 | [JP](essays/ronko-ronko/ronko_ronko_v0_1_JP.md) | [EN](essays/ronko-ronko/ronko_ronko_v0_1_EN.md) | 考えるとはどういうことか。認知の四層分解（L0–L4）とAI時代の主体保障論。 |
| 意図的創発 | [JP](essays/intentional_emergence/intentional_emergence_v0_3.md) | [EN](essays/intentional_emergence/intentional_emergence_v0_3_EN.md) | 創発の条件は設計されうるか。器形成・アテンション地形・開放型創発の理論。 |
| 関係知の設計 | [JP](essays/relational_knowledge/relational_knowledge_draft_v0_1.md) | [EN](essays/relational_knowledge/relational_knowledge_design_v0_1_EN.md) | 知識はどのように主体間で生まれるか。潜在器・走査・受容的充填・関係場の設計論。 |

### 未整理（作業中）

その他の論考・草稿は [essays/](essays/) フォルダ内に収録。内容は理論構築の痕跡であり、完成度は問わない。

---

## 核心概念リファレンス（Core）

理論横断的な概念定義・統合命題・概念間連関図。

| ファイル | 内容 |
|---------|------|
| [core/central_thesis.md](core/central_thesis.md) | 中心命題：Region B・M・D・Shepherd Model・倫理の回路保全原理の統合（日英） |
| [core/key_concepts.md](core/key_concepts.md) | 主要概念表：9概念の定義・機能・出典・相互連関（日本語） |

---

## データ（Data）

実証分析に用いたデータセット・処理済みデータ。OMD 論文の e-Stat データを含む。

→ [data/](data/)（metadata・processed の二層構造）

---

## ドキュメント（Docs）

理論ノート、ワーキングドキュメント、投稿関連資料。

- [docs/notes/](docs/notes/) — 制御変数定義、設計メモ
- [docs/OMD_ComplexSystems_coverletter .md](docs/OMD_ComplexSystems_coverletter%20.md) — カバーレター

---

## リポジトリ構造

```
core/
  central_thesis.md          中心命題（日英統合版）
  key_concepts.md            主要概念表（9概念）
papers/
  RLAF/                      個人スケール：自律性テンソル理論
  RD/                        一般理論：再計算ダイナミクス
  OMD/                       社会スケール：組織メタスタビリティ実証
  subject-erosion-dynamics/  応用シリーズ：主体侵害の力学（6論文）
  shepherd_model/            設計原理：羊飼いモデル
  goodhart/                  Goodhartization と再接続失敗の制度論
  Generative AI, .../        認知的オフロードと問い形成能力
essays/                      理論エッセイ（論考論考・意図的創発・関係知の設計）
data/                        実証データセット（e-Stat）
docs/                        理論ノートと作業文書
archive/                     過去バージョンとセッション記録
AGENTS.md                    マルチAI協働プロトコル（Ray / Liva / Kai）
```

---

## 協働プロトコル

本プロジェクトは三AIワークフローを採用している：

- **Ray**（Claude）— 構造分析、形式的編集、実証デバッグ
- **Liva**（GPT）— 理論レビュー、クロスバリデーション、戦略的判断
- **Kai**（Gemini）— 補助的検索・検証

セッション間の引き継ぎは D-pass 文書で管理される。詳細は [AGENTS.md](AGENTS.md) を参照。

---

## License

See [LICENSE](LICENSE).
