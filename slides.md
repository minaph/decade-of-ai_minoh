---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
# some information about your slides (markdown enabled)
title: 「認知のプロセス」を巡る
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
author: 美濃 佑輝
---

# {{ $frontmatter.title }}

東北支部所属 & IAMAS M2<br />
{{ $frontmatter.author }}


---
layout: image-right
image: /2024-08-17-12-50-53.png
---

<!-- [x] 自分の画像入れる -->

# 自己紹介ページ 

<p></p>

### おなまえ: 美濃 佑輝 { style="margin-top: 30px" }

岐阜県大垣市在住

**教育心理学**の人

情報科学芸術大学院大学でデザイン学やってます

<div style="margin-top: 40px"></div>

### どんなひと？

- 祖父が元校長先生
- プログラミング大好き（Python, JavaScript, LEAN）
- M3（M4になりそう！）

---

# 目次

<v-clicks>

  1. デザイン学研究
     1. プロトコル分析
     1. プロトコル分析の功罪
  1. AIとプロトコル分析
  1. 過去の認知研究とこれから
</v-clicks>


---
layout: image-right
hide: true
---

<!-- [-] （地図出す） -->

ばしょ：

- 兵庫県（出生～中学生）
- →東京都（高校生）
- →宮城県（大学生）
- →岐阜県（大学院生）


---
layout: two-cols
hide: true
---

<!-- 時間があればしゃべる -->

所属先：

### 情報科学芸術大学院大学

#### IAMAS

#### 岐阜県大垣市

<!-- [-] ここに大垣の画像 -->


大垣はいいぞ

- 水の都
- 知る人ぞ知る「大垣サウナ」
- 鮎うまい
- 関ケ原のとなり町
- 本来天下の分け目になるはずだった町
- 大垣祭りすごい

::right::

IAMASもいいぞ

- アーティストの人が大半
- 学生50人に対して教員20人！
- いろんなことができる
- メディアアートの先駆的な学校として有名（だった）
- めちゃくちゃ学際的
- 専門性はない。。。
- 卒業きびしい。。。

---
hide: true
---


# 美濃の関心

<div style="margin-top: 40px">

**人間の認識を理論的にうまく捉えるにはどうしたら？**
</div>


<v-click>

#### 美濃の関心の経緯 { style="margin-top: 40px" }
</v-click>

<!-- [-] 研究のわかりやすい画像 -->
<v-clicks>

1. 小説が好きな小学生時代
1. 中学時代から**メモを書く習慣**
1. 東北大学教育学部で**教育心理学コース**に進学
1. 教育工学系の研究室で、**自然言語処理**の工学部同然の教育を受ける
1. 紀要に載っていたデザイナーの方の研究に関心を惹かれてIAMAS入学を決意
1. （２年間＋α）大迷走...

</v-clicks>

<div style="margin-top: 40px"></div>

<v-click>

#### 美濃は、**言葉や心理学を通じた内面の追求**を続けてきた
</v-click>


<!-- 1. 国語が得意になり、ことばとこころの働きに興味を持つ -->
<!-- 1. 祖父が校長先生だったこともあり、東北大学教育学部に入学 -->
<!-- 1. （卒論が書けなくて軽く病み） -->
<!--       - 睡眠にも悩まされる -->

---
layout: two-cols
---

# 東北支部での活動（2018/04/15~）

<p />

交流会の企画やツールの導入等々の内務的なことを中心に、東北支部で活動してきました。

  スタッフとして:
<v-click>
  
  - 交流会企画
  - オンライン雑談会企画
  - Scrapboxの導入
</v-click>

  メンバーとして:
<div v-click>
  
  - 輪読会の主宰・参加
  - 外部のハッカソンへの参加
  - ペアプロ係
</div>


::right::

<img v-click src="/2024-08-17-14-51-35.png" />

<!-- [x] 画像入れる -->

---
layout: section
---

# テーマ: 認知のプロセスとAI

## プロトコル分析とAI



---
hide: true
---

# 認知のプロセスとは？

認知のプロセス: 人間が情報を受け取り、分析し、意味づける一連の内的な現象のこと


<v-clicks>

人間が何かを理解したり、作ったり、誰かと会話するとき、我々の心のなかでは何が起こっているのか？

要素: 

 - 知覚
 - 記憶
 - 学習
 - 等々...

→ 非常に広範で複雑なプロセス

→ 範囲の限定が難しい

うまく理論的に捉えたい！！！

</v-clicks>

<!-- どうせ専門家のみなさまなのでこのスライドは見せない-->


---
layout: section
---

# デザイン学研究

---

# デザイン学との出会い

<p/>

<!-- グラフィックデザインを本職とする瀬川晃先生の書いた論文を読んで、 -->

友人の勧めで読んだサインデザインのレポートに直感を得る

→ **IAMASに進学**

_瀬川晃, & 伊澤宥依. (2021年). サイン・スタディー：コミュニケーションのほころびを手掛かりにした持続可能な運用の試み. 情報科学芸術大学院大学紀要 第12巻, 95–101._


<div style="display: grid; grid-template-columns: 1fr 1fr;">

  <img src="/image.png" width=400 class="" />
  
  <div>
    <div v-click style="display: grid; grid-template-columns: 1fr 1fr;">
      <img src="/2024-08-16-08-43-13.png" />
      <img src="/2024-08-16-08-53-31.png" width=150 />
    </div>
    <Arrow v-click x1="470" y1="450" x2="580" y2="450" />
    <img v-click src="/2024-08-16-08-55-41.png" width=200 class="border border-black mx-auto" />
  </div>
</div>

---

# デザイン学研究

<!-- [ ] 説明しすぎなのでは... -->

<!-- 瀬川先生のサインスタディーを出発点に、美濃の関心の紆余曲折が始まる... -->

<!-- → デザイン学へ。 -->

### デザイン学とは？

デザインとは非常に魅力的で複雑なプロセス

<v-click>→ そのプロセスの解明から彼らの独自性・創造性の根源に迫ろう！</v-click>


たとえば。。。
<v-clicks>
  
   - 建築デザイン: 
       - 大聖堂
       - 美術館
   - 産業デザイン:
       - iPhone
   - etc...
</v-clicks>


<!-- <div class="my-10" v-click>これらの独自性・創造性の根源が判明すれば、その利益は計り知れない。</div> -->


---

# デザイン学

<p />

デザイナーの内面を明らかにするためには、どうすればいいか？

→ デザイナーに全部言語化させよう！

### （デザイン）プロトコル分析

<v-clicks>

  1. デザイナーの方に簡単なデザインをしてもらう
  1. デザインの最中、考えていることをすべて喋ってもらう
  1. 録音を書き起こし、発言を小さな部分に分割する
  1. 分割した発言をそれぞれ分類し、どのような前後関係があるかを分析する

</v-clicks>

<!-- [x] プロトコル分析の結果得られたダイアグラム img[v-click] -->
<div style="display: grid; grid-template-columns: 1fr 1fr;">
  <div v-click>
    <img src="/2024-08-17-14-10-40.png" width=300 class=inline/>
    <em class="text-xs pos-absolute color-gray">Kim, E., & Kim, K. (2015). Cognitive styles in design problem solving: Insights from network-based cognitive maps. Design Studies, 40, 1–38. https://doi.org/10.1016/j.destud.2015.05.002</em>
  </div>
  <div class="py-10">

   ## <v-click>しかし、プロトコル分析は功罪両面</v-click>

  </div>
</div>


---

# デザインプロトコル分析でわかったこと

<p />

<v-clicks depth=2>

  - 熟練したデザインは、様々な側面で異なる領域を往復することがその効果の源泉なのではないか
      - ゴールの設定 / 製品造形の選択
      - デッサンの描画 / 描いたものの再解釈
      - 建築の形式・見た目 / 建築の機能
      - ...
  - エピソード的な情報源が重要
      - デザイナー自身の体験
      - ユーザーのレビュー
      - 同業他社の社員の感覚
  - 言動の間の参照や接続が密

<!-- 
      - 後方参照（過去に発見・整理したことの参照） / 前方参照（問いや目的の設定）
      - 問題の理解 / 解決策の作成と評価
 -->
</v-clicks>

---

# プロトコル分析の弱点

<p />

<v-clicks>
  デザイン学研究において「デザインプロトコル分析」は広く使われ、一定の成果をあげてきた。
  
  しかし反論は当初から...
  
  ### なぜデザイナーが自分の考えを随時喋るだけで、<br/>デザインプロセスが正確に捉えられるのか？
  
  <div class="my-5">また、デザイナーに対して実験を行うことは、研究上の負担もある。</div>
  
  - 自身の思考プロセスを開示することへの**デザイナーの抵抗感**
  - 複雑な内的プロセスであるため、個人差を消して客観的な議論をするために**量がほしい**。
      - → しかし複雑で長いプロセスのデータの収集と分析には、**多大な時間と労力**がかかる
</v-clicks>

---
layout: section
---

# AIとプロトコル分析

---

# AIによる書き起こし生成

<p />

大規模自然言語モデルにデザインプロセスの妥当なプロトコルを作成させることは可能なのか？

<v-click>→ 実はありえるのではないか</v-click>

### 注 {class="my-10"}

<v-clicks>

  1. 無論、大前提としてAIと人間が同じ内的プロセスを保持しているとはいえない。
  1. しかし、人間が生成するのと同じ品質・バラエティのプロトコルデータ（書き起こしテキスト）を<br/>将来的に作成できるのであれば？
  1. **むしろ、なぜ既存のプロトコル分析は（少なくとも一見）妥当な知見を生んできたのか？**
</v-clicks>

<div v-click class="my-10">AIにプロトコルを生成させ、その分析結果を人間の認知プロセスとして発表する日が、いつかやってくるかもしれない。</div>


---
layout: section
---

# 人間認知研究 with AI

---

# 内的シンボル操作 VS 社会構築主義

<p />

人間の認知プロセスについて、（教育学等の文脈で）参照されてきた、ピアジェとヴィゴツキーの考え方がある

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 40px;">
<div>

### 内的シンボル操作: ピアジェの理論

<v-clicks>

  - 人間は**シンボル操作**を学習
  - **スキーマ**（思い込み、メンタルモデルのようなもの）を追加したり修正したりしながら、発展した内的表象を構築
  - 最終的に、**科学的な思考**が可能になる
</v-clicks>

</div>
<div>

### 社会構築主義: ヴィゴツキーの理論

<v-clicks>

  - 人間は**他者との関わり**の中で学ぶ
  - **言語や絵筆などの道具**を使いながら、少しずつ自分でできることを増やしていく
  - 最終的に、**社会的な行動**が可能になる
</v-clicks>

</div>
</div>

<div style="margin-top: 40px"></div>

<v-click>→ 人間の学習は、内面的に、そして社会的に進行していく</v-click>


### 人間の内面性と社会性をAIが模倣することは可能か {class="my-10" v-click}

---
layout: section
---

## 人間の認知研究をAIは<br/>（いつ）変えられるのか？

