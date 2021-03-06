# TokyoWebmining Presentation Style Guide

# 目次
- 

## はじめに
この文書は、データマイニング+WEB @東京(以下、TokyoWebmining)のプレゼンテーションスタイルガイドである。

このスタイルガイドの対象としているのは、TokyoWebminingで発表時間が20分以上のプレゼンテーションにおける資料である。
特に想定しているのは、伝統的な箇条書きを中心とする文字量が多くなりがちなプレゼンテーションに対する資料である。
いわゆるLightning Talksと呼ばれるような短時間での発表や、写真を中心とした資料については、このスタイルガイドでは言及しない。


以下の2つのキーワードを用いて表現をする。
"MUST"は必須の項目について記述する。
"SHOULD"は、推奨される項目について記述する。必ず従う必要はないが、特に理由がなければ従うことが望ましい。

## 議論を円滑にするために
- [MUST] "現在のページ数/総ページ数"を明記する
- [MUST] 一部非公開のスライドには、非公開のページのページ内に明記するか、もしくは公開/非公開切替のタイミングで切り替えるスライドを挟む
- [SHOULD] 議論を円滑にするため、適切な粒度でサマリーを作り、質問できる時間を設ける


## 箇条書き
- [SHOULD] 情報の粒度を揃えて記述する

```
# good
- 春の食材
  - アスパラ
  - 菜の花
  - たけのこ
- 夏の食材
  - きゅうり
  - スイカ

# bad
- 春の野菜
- 春の魚
- 昨日の晩御飯に使った春の食材
```

## グラフ

- [SHOULD] グラフの縦軸、横軸のラベルは明記し、発表時にも説明をする。ただし、公開できない情報の場合はこの限りではない

## 概念・アルゴリズム

- [MUST] 分野の異なる参加者が多いため、英字の略称がはじめて登場した時は、必ず正式名称を併記する。
  - `SVM(Support Vector Machine)`
  - `クリック率(Click through rate, CTR)`
- [MUST] 聴衆に知られていないと思われるアルゴリズムや概念には、参考文献を明記する
  - (用語集とかがあれば、そこに出ているのはknownとしても良いかも)

上記2点については、@tsubosakaさんの[Contexual bandit @TokyoWebMining](http://www.slideshare.net/tsubosaka/contexual-bandit)が参考になるので、一読をすすめる。


## デザイン

デザインの基本としては、[伝わるデザイン｜研究発表のユニバーサルデザイン](http://tsutawarudesign.web.fc2.com/)が分かりやすく、参考になるので一読をすることをおすすめする。

この章では、伝わるデザインの以下の項目を読んでいることを前提に説明をする。
- [レイアウト｜伝わるデザイン](http://tsutawarudesign.web.fc2.com/miyasuku1.html)
- [色彩と配色｜伝わるデザイン](http://tsutawarudesign.web.fc2.com/miyasuku2.html)
- [配色｜伝わるデザイン](http://tsutawarudesign.web.fc2.com/kakkoyoku5.html)


- [MUST] 背景と文字の色にコントラストをつける
- [MUST] 明度が近い色の組み合わせは避ける
- [SHOULD] メインで使う色を4色程度にする
- [SHOULD] 彩度の高すぎる色を避ける
