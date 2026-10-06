<!-- ELUCENIA technical documentation · cts-6 · ja · no clinical/professional/rights approval -->

# CTS-6（手根管症候群）

[条件・出典・許諾](https://elucenia.org/ja/tools/cts-6)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 主に、または正中神経領域だけのしびれ

`dorm`

### 夜間のしびれ

`noturna`

### 母指球筋の萎縮および／または筋力低下

`atrofia`

### Phalenテスト陽性

`phalen`

### 2点識別覚の低下（\> 6 mm）

`dpp`

### 手根管部のTinel徴候陽性

`tinel`

## 方法の版

CTS-6/Graham 2006：6つの重み付き手根管基準、診察

## 記載された計算式

該当項目の合計：正中神経領域しびれ3.5、夜間しびれ4、母指球萎縮・筋力低下5、Phalen陽性5、二点識別低下4.5、Tinel陽性4。合計0～26。

## 限界・対象集団

Graham 2006の開発では、専門家の合意と臨床基準を組み合わせた症例の記述を用いました。抄録に記載された検証では、モデルの確率を別の専門家パネルの判断と比較しています。この研究デザインだけでは、各臨床集団における電気生理検査との比較性能は確立されません。六項目のスコア、閾値、対象年齢は、方法の全文で確認する必要があります。

## 参考文献

- [Graham B et al. Development and validation of diagnostic criteria for carpal tunnel syndrome. J Hand Surg Am, 2006.](https://doi.org/10.1016/j.jhsa.2006.03.005)

- [Graham B. The value added by electrodiagnostic testing in the diagnosis of carpal tunnel syndrome. J Bone Joint Surg Am, 2008.](https://doi.org/10.2106/JBJS.G.01362)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

手根管症候群の可能性は低い（約25%未満）

代替診断を考慮する（頸椎神経根症、多発ニューロパチー）。


### 2

中間確率（約25%から80%の間）

この範囲では電気神経筋検査の有用性が高い。


### 3

中間確率（約25%から80%の間）

この範囲では電気神経筋検査の有用性が高い。


### 4

手根管症候群の可能性が高い（約80%以上）

この範囲では、電気神経筋検査が臨床診断を変えることはまれです。

