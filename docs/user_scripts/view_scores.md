---
title: コンテストの成績や関連する統計情報を見る
---

## リアルタイムの情報を見る

!!! danger "警告"
    コンテスト中にSNSでの言及や投稿は避ける。賠償が請求される可能性があるため。

### 問題の統計情報

- [AtCoderColorStandings](https://greasyfork.org/ja/scripts/423713-atcodercolorstandings) - 「順位表」ページと「バーチャル順位表」ページで、コンテスト参加者のレーティング別正解率を表示する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_color_standings.png" alt="atcoder color standings">
    </div>

- [AtCoderStandingsAnalysis](https://greasyfork.org/ja/scripts/398439-atcoderstandingsanalysis) - 「順位表」ページから、自分の得点・正解者数 / 提出者数・正解率・平均ペナルティ数・ペナルティ率・内部レートの分布を集計する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_standings_analysis.png" alt="atcoder standings analysis">
    </div>

- [atcoder-standings-difficulty-analyzer](https://greasyfork.org/ja/scripts/419541-atcoder-standings-difficulty-analyzer) - 「順位表」ページに、問題別の推定難易度の推移・ACした人数の推移などを表示する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_standings_difficulty_analyzer.png" alt="atcoder standings difficulty analyzer">
    </div>

### コンテストの成績

- [ac-predictor](https://greasyfork.org/ja/scripts/369954-ac-predictor) - コンテスト開催中に推定パフォーマンスとレーティングの推移を表示する。[Webページ版](https://ac-predictor.com/)もある。使用されている技術に興味がある方は、作者による[解説記事(2020年12月時点)](https://qiita.com/keymoon/items/e83259f882f26c8f10a1)を参照されたい。
    - [ac-predictor-minimal](https://greasyfork.org/ja/scripts/386999-ac-predictor-minimal) - [ac-predictor](https://greasyfork.org/ja/scripts/369954-ac-predictor)の機能限定版。スクリプトの透明性を確保する観点から、パフォーマンスを表示するのは「順位表」ページに限定される。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_predictor.png" alt="ac predictor">
    </div>

- [AtCoderScoreHistogram](https://greasyfork.org/ja/scripts/462131-atcoderscorehistogram) - 「順位表」ページに、得点分布を追加する。ユーザ名を入力すると、該当ユーザの得点も表示される。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_score_histogram.png" alt="atcoder score histogram">
    </div>

## 問題に関する統計

### 難易度(推定)

- [AtCoder Difficulty Display](https://greasyfork.org/ja/scripts/397185-atcoder-difficulty-display) - AtCoderの「問題」のページに[AtCoder Problems](https://kenkoooo.com/atcoder/)の難易度を表示する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_difficulty_display.png" alt="atcoder difficulty display">
    </div>

## ユーザに関する統計

### パフォーマンスの推定値

- [AtCoderUnratedPerfDisplayer](https://greasyfork.org/ja/scripts/457150-atcoderunratedperfdisplayer) - ユーザの「コンテスト成績表」ページに、Unrated参加したときのパフォーマンス値(推定)を表示する。

    !!! info "参考"

        アルゴリズム部門、かつ、レーティングの更新対象者が存在するコンテストで有効。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_unrated_perf_displayer.png" alt="atcoder unrated perf displayer">
    </div>

### レーティングの推移・分布

- [AtCoderAnotherGraph](https://greasyfork.org/ja/scripts/455542-atcoderanothergraph) - 「ユーザ」ページにあるレーティンググラフ︎を、ヒューリスティック/アルゴリズムの計算式で表示する。

    !!! info "参考"

        以下のサンプルでは、アルゴリズム部門のレーティングをヒューリスティックの計算式に基づいて表示している。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_another_graph.png" alt="atcoder another graph">
    </div>

- [AtCoder Graph Time](https://greasyfork.org/ja/scripts/454517-atcoder-graph-time) - 「ユーザ」ページにあるレーティンググラフの横軸をコンテストの参加回数に変更する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_graph_time.png" alt="atcoder graph time">
    </div>

- [AtCoderRecentGraph](https://greasyfork.org/ja/scripts/418562-atcoderrecentgraph) - 「ユーザ」ページにあるレーティンググラフのうち、最近（注: 詳細は不明）の推移を表示する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_recent_graph.png" alt="atcoder recent graph">
    </div>

- [AtCoder Rating Cumlative Distribution](https://greasyfork.org/ja/scripts/419055-atcoder-rating-cumlative-distribution) - 「ユーザ」ページにあるRating分布の累積人数および累積パーセントを表示する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_rating_cumlative_distribution.png" alt="atcoder rating cumlative distribution">
    </div>

### 正解した問題の総得点の推移

- [AtcoderDevotionGraph](https://greasyfork.org/ja/scripts/416588-atcoderdevotiongraph) - 「ユーザ」ページのレーティンググラフに、ACした問題の総得点の推移を上書き表示する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder_devotion_graph.png" alt="atcoder devotion graph">
    </div>

### ユーザの成績で検索

- [AtCoder Auto Pager](https://greasyfork.org/ja/scripts/421991-atcoder-auto-pager) - 「順位表」ページに、順位・得点・解答時間・パフォーマンスによる検索機能を追加する。

    !!! warning "警告"
        パフォーマンスによる検索を行うためには、[ac-predictor](https://greasyfork.org/ja/scripts/369954-ac-predictor)を導入する必要がある。

    <div align="center">

      <img loading = "lazy" src="../../images/userscript/atcoder_auto_pager.png" alt="atcoder auto pager">
    </div>

### ユーザの使用言語を見る

- [atcoder-standings-lang](https://greasyfork.org/ja/scripts/415894-atcoder-standings-lang) - 「順位表」ページおよび「バーチャル順位表」ページで、ユーザ名の横にAC数の多い言語を表示する。

    <div align="center">
      <img loading = "lazy" src="../../images/userscript/atcoder-standings-lang.png" alt="atcoder standings lang">
    </div>
