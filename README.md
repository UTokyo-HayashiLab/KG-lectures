# 知識処理（Knowledge Processing）講義資料

本リポジトリは、知識処理（Knowledge Processing）に関する講義資料を公開するものです。近年の人工知能研究において重要な役割を果たしている**知識グラフ（Knowledge Graph）**、**統計的知識表現**、および**知識表現学習（Knowledge Representation Learning）**を中心に解説します。

講義では、シンボリックAIと機械学習の両方の観点から知識の表現・推論手法を学び、知識グラフを活用した知識発見や推論技術について理解を深めます。

---

## 講義内容

### 1–2. 知識グラフからの Horn 規則マイニング

知識グラフに含まれる事実データから、論理規則（Horn規則）を自動的に発見する手法について学びます。

#### 主な内容

- 知識グラフの概要
  - RDF
  - トリプル表現
  - エンティティと関係
- 論理推論の基礎
  - 一階述語論理
  - Horn節
  - ルールベース推論
- Horn規則マイニング
  - Rule Miningの目的
  - Support・Confidence
  - Head Coverage
- 代表的手法
  - AMIE
  - AMIE+
  - AnyBURL
- 発見された規則を用いた知識補完
  - Link Prediction
  - Knowledge Graph Completion

#### 学習目標

- 知識グラフの構造を理解する
- Horn規則の表現方法を理解する
- 規則マイニングアルゴリズムの仕組みを説明できる
- 発見された規則を用いた知識推論を理解する

---

### 3. Markov Logic Networks（MLN）

Markov Logic Networks（MLN）は、論理と確率を統合した知識表現・推論手法です。本講義では、不確実性を含む知識をどのように扱うかを学びます。

#### 主な内容

- 不確実な知識表現
- 確率的推論の基礎
  - Bayesian Networks
  - Markov Networks
- Markov Logic Networks
  - 論理式への重み付け
  - Ground Markov Network
  - 確率分布の定義
- 推論
  - MAP Inference
  - Marginal Inference
- 学習
  - Weight Learning
  - Structure Learning
- MLNの応用事例
  - 情報抽出
  - 関係抽出
  - 知識ベース構築

#### 学習目標

- 論理と確率の統合的な考え方を理解する
- Markov Logic Networksの定式化を説明できる
- MLNにおける推論と学習の流れを理解する
- 不確実性を含む知識処理の考え方を習得する

---

### 4. 知識グラフ埋め込み（Knowledge Graph Embedding）

知識グラフ埋め込みは、エンティティや関係を低次元ベクトル空間へ写像することで、知識グラフの推論や予測を可能にする技術です。

#### 主な内容

- 知識グラフ埋め込みの概要
- Link Prediction問題
- 距離ベースモデル
  - TransE
  - TransH
  - TransR
  - RotatE
- 双線形モデル
  - RESCAL
  - DistMult
  - ComplEx
- ニューラルネットワークベース手法
- 評価指標
  - Mean Rank (MR)
  - Mean Reciprocal Rank (MRR)
  - Hits@K
- 応用事例
  - Knowledge Graph Completion
  - 推薦システム
  - 質問応答システム

#### 学習目標

- 知識グラフ埋め込みの目的を理解する
- 代表的な埋め込みモデルの特徴を説明できる
- Link Predictionの評価方法を理解する
- 知識グラフ埋め込みの実応用を理解する

---

## 想定する前提知識

- 線形代数の基礎
- 確率・統計の基礎
- 機械学習の基礎
- 一階述語論理の基礎（推奨）

---

## 参考文献

### Knowledge Graph Rule Mining

- Galárraga et al., *AMIE: Association Rule Mining under Incomplete Evidence in Ontological Knowledge Bases*, WWW 2013.
- Galárraga et al., *Fast Rule Mining in Ontological Knowledge Bases with AMIE+*, VLDB Journal 2015.
- Meilicke et al., *AnyBURL: Anytime Bottom-Up Rule Learning*, ISWC 2019.

### Markov Logic Networks

- Richardson and Domingos, *Markov Logic Networks*, Machine Learning, 2006.
- Domingos and Lowd, *Markov Logic: An Interface Layer for Artificial Intelligence*, Morgan & Claypool, 2009.

### Knowledge Graph Embedding

- Bordes et al., *Translating Embeddings for Modeling Multi-relational Data*, NeurIPS 2013.
- Nickel et al., *A Review of Relational Machine Learning for Knowledge Graphs*, Proceedings of the IEEE, 2016.
- Wang et al., *Knowledge Graph Embedding: A Survey of Approaches and Applications*, IEEE TKDE, 2017.

---

## ライセンス

本講義資料は教育目的で作成されています。利用条件についてはライセンスファイルを参照してください。
