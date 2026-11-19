# Nature本誌の投稿図

2026年11月19日にNature本誌の著者案内とResearch figure guideを確認した。以下の寸法は実際の掲載寸法に対するもの。研究発表・単体画像にも書体、文字と記号の使い分け、簡潔な線を引き継ぐ。別誌への投稿では、その雑誌の著者案内と編集部からの個別指定を先に確かめる。[Natureの著者案内](https://www.nature.com/nature/for-authors)・[Nature Methodsの入稿案内](https://www.nature.com/nmeth/submission-guidelines/aip-and-formatting)

## 投稿段階を確かめる

| 用途 | 寸法・ファイル | 図説明 |
|---|---|---|
| 初回投稿・査読用 | 審査に十分な画質で用意する。本文と図を1つのWordまたはPDFにまとめることを推奨。初回案内の作図目安は幅90 mmまたは180 mm、高さ最大170 mm。制作段階の高解像度ファイルは初回の必須物ではない | 図と同じページに置く。[Initial submission](https://www.nature.com/nature/for-authors/initial-submission) |
| 原則採択後の本文主図 | 標準幅は1段89 mm、2段183 mm。必要なら1.5段の120–136 mmも取り得る。制作ガイドで図の高さは最大170 mm。線画・グラフ・混合図は文字と線を編集できるPDF、AI、EPSが適する | 図ファイルと分け、本文ファイルの参考文献の後にまとめる。[Final submission](https://www.nature.com/nature/for-authors/final-submission)・[図の寸法と形式](https://research-figure-guide.nature.com/figures/building-and-exporting-figure-panels/) |
| Extended Data | RGB、最大300 ppi、各ファイル10 MB以下。JPEG推奨、TIFF・EPSも可。図説明の余地を含めて1ページに収める | 本文ファイルのExtended Data legends欄に置く。[Extended Dataの入稿仕様](https://www.nature.com/nature/for-authors/final-submission) |

## 本文主図の版下

| 項目 | 指定と実装 |
|---|---|
| 書体・サイズ | 同じ論文の図はサンセリフで統一し、ArialまたはHelveticaを優先する。通常文字は5–7 pt。複数パネルの記号は小文字 **a, b, c** を8 pt、太字・立体で置く。一本の線の太さも含め、縮小後の値で確認する。[Final submission](https://www.nature.com/nature/for-authors/final-submission) |
| 軸と線 | 線幅は0.25–1 pt。軸線・目盛を表示し、有次元の軸は `Time (min)` のように単位を括弧に入れる。軸名は原則として先頭を大文字にし、末尾のピリオドを省く。数値と単位記号の間に空白を入れる（例：10 µm）。[Formatting guide](https://www.nature.com/nature/for-authors/formatting-guide)・[作図仕様](https://research-figure-guide.nature.com/figures/preparing-figures-our-specifications/)・[線幅](https://www.nature.com/nature/for-authors/final-submission) |
| 文字の保持 | 軸名・数字・記号をテキストとして残し、フォントを埋め込む。輪郭への変換や画像化は避ける。写真はラスター、上に載せる文字・矢印・スケールバーは編集可能な別レイヤーで用意する。[作図仕様](https://research-figure-guide.nature.com/figures/preparing-figures-our-specifications/) |
| 色と凡例 | 本文主図の色空間はRGB推奨。色覚の違いに配慮し、赤と緑だけに依存した区別や虹色の連続尺度を避ける。黒い文字と記号見本を組み合わせ、線種・点形状・直接ラベルでも区別する。[配色と凡例](https://research-figure-guide.nature.com/figures/building-and-exporting-figure-panels/) |
| 写真の解像度 | 写真単体の下限は、最大使用寸法で300 dpi。制作ガイドのパネル書き出しでは埋め込む画像に450 dpi以上を指定している。元画素数を確認し、配置寸法での実効解像度を計算する。89 mm幅なら300 ppiに1,052 px、450 ppiに1,577 px以上が必要。補間で画素を増やしても細部は復元できない。[写真と書き出しの仕様](https://research-figure-guide.nature.com/figures/preparing-figures-our-specifications/) |
| 主図のファイル | 線画・写真・文字が混ざる主図は、元写真を埋め込んだ編集可能なベクターPDF等にまとめる。Final submissionは写真素材にPSD/TIFFも挙げる一方、制作ガイドは完成主図として平坦化したJPEG/TIFF/PNGを受け付けないとしている。写真だけの最終ファイルに個別指定がある場合はそれに従う。[Final submission](https://www.nature.com/nature/for-authors/final-submission)・[完成主図の形式](https://research-figure-guide.nature.com/figures/building-and-exporting-figure-panels/) |

**図説明。** Nature本誌では1図につき英語で300語未満。図全体の短い題から始め、パネル順に対象と記号を説明する。図に示した誤差棒と統計量を定義し、正確なnと反復の種類、代表像なら測定の反復回数を示す。実験手順の詳細はMethodsに置く。[Formatting guide](https://www.nature.com/nature/for-authors/formatting-guide)・[統計の記載](https://www.nature.com/nature/for-authors/initial-submission)

**実験画像。** 原画像と校正値を保持する。明るさ・コントラスト調整は画像全体と対照に等しく適用し、弱い信号や背景の情報が消える設定を避ける。組み合わせた視野や切り継いだゲルは境界と由来が読めるようにし、処理内容を記録する。拡大率の数字だけで済ませず、校正した長さのスケールバーを置く。[画像の完全性](https://www.nature.com/nature-portfolio/editorial-policies/image-integrity)・[スケールバー](https://research-figure-guide.nature.com/figures/preparing-figures-our-specifications/)

## Matplotlibで本文主図を作る場合

[本文主図用のスタイル](../assets/nature-main.mplstyle)には通常文字6 pt、軸線0.5 pt、データ線0.8 ptを設定した。これらは上記の範囲内で選んだ初期値。キャンバスの幅・高さはパネル数と投稿段階に合わせて決める。この例はスキルのルートから実行する。

```python
import matplotlib.pyplot as plt

with plt.style.context("assets/nature-main.mplstyle"):
    fig, ax = plt.subplots(figsize=(89 / 25.4, 55 / 25.4), layout="constrained")
    # axに実データと軸ラベルを追加する。複数パネルなら記号を8 pt太字にする。
    fig.savefig("figure.pdf")
    plt.close(fig)
```

PDFを書き出したらページ寸法とフォントの埋め込みを調べ、軸名を文字として選択・検索できるか確かめる。PDFのページを画像にレンダリングして、パネル記号、線、単位記号、画像の階調を最終寸法で確認する。キャンバスを自動で切り詰める書き出しはページ寸法が変わるため、保存後の実測値を見る。
