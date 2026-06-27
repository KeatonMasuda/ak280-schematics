# ak280-schematics (日本語版)

[English README is here](README.md)

このリポジトリには、Amazonで購入したオーディオ・アンプ「AK-280」のプリント・パターンと実装部品から作成した回路図を格納しています。回路図はKiCadで作成しています。

## プロジェクトの目的
このプロジェクトは、あくまで個人の趣味として解析を行ったものです。特定の目的や意図はありません。

## ディレクトリ構成 (Directory Structure)

```text
ak280-schematics/
├── hardware/
│   ├── AK-280.kicad_pro
│   └── AK-280.kicad_sch
├── images/
│   ├── ak280-schematic.pdf
│   ├── fig01-topside-with-refno.png
│   ├── fig01-topside-with-refno.xcf
│   ├── fig02-bottomside-with-refno-org.png
│   ├── fig02-bottomside-with-refno-org.xcf
│   ├── fig03-bottomside-with-refno-mirror.png
│   ├── fig03-bottomside-with-refno-mirror.xcf
│   └── fig04-ai-generated-reference.png
├── LICENSE
├── README.ja.md
└── README.md
```

## 各ファイルの説明 (File Descriptions)

* **hardware/**: KiCadの回路図データ一式 (回路図ファイルや設計データ) が入っています。
* **images/**: 以下の回路図および関連資料が格納されています。
    * **ak280-schematic.pdf**: 回路図 (PDFファイル)
    * **fig01-topside-with-refno.png**: 部品面の回路番号付き写真 (閲覧用・レイヤ統合済)
    * **fig01-topside-with-refno.xcf**: 部品面の回路番号付き写真 (GIMP編集用・レイヤ保持・圧縮)
    * **fig02-bottomside-with-refno-org.png**: ハンダ面の回路番号付き写真・オリジナル (閲覧用・レイヤ統合済)
    * **fig02-bottomside-with-refno-org.xcf**: ハンダ面の回路番号付き写真・オリジナル (GIMP編集用・レイヤ保持・圧縮)
    * **fig03-bottomside-with-refno-mirror.png**: ハンダ面の回路番号付き写真・反転 (閲覧用・レイヤ統合済)
    * **fig03-bottomside-with-refno-mirror.xcf**: ハンダ面の回路番号付き写真・反転 (GIMP編集用・レイヤ保持・圧縮)
    * **fig04-ai-generated-reference.png**: AIで生成し目視確認したパターン図
* **LICENSE**: ライセンスに関する情報を記載しています。
* **README.ja.md**: このプロジェクトについての日本語での詳細な説明です (本ファイル)。
* **README.md**: このプロジェクトについての英語での詳細な説明です。

## 使い方
1. このリポジトリをローカル環境にクローン (ダウンロード) します。
2. KiCad (v7.0以降を推奨) を起動し、`hardware/AK-280.kicad_pro` を開きます。
3. 回路図エディタを開くことで、作成された回路図を閲覧・編集できます。
4. `images/` フォルダ内にある `.xcf` ファイルの閲覧・編集には、GIMPが必要です。

## 免責事項
本リポジトリの回路図は、実物基板の目視確認およびAI生成のパターン図 (`fig04-ai-generated-reference.png`) を参考にして作成されたものです。正確性には万全を期していますが、ネットリストの完全性を100%保証するものではありません。本データの利用によって生じた、機器の破損、事故、予期せぬ不具合、その他いかなる損害や不利益についても、作者は一切の責任を負いません。各自の責任において利用してください。

## 謝辞
* 本プロジェクトで使用しているTDA7377のKiCadシンボルは、Snapmagic (https://www.snapmagic.com/) のデータを使用させていただきました。

## ライセンス
本プロジェクトはMITライセンスのもとで公開されています。詳細は [LICENSE](LICENSE) ファイルを参照してください。