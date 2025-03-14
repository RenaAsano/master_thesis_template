# Master_thesis_template

$\LaTeX$ template for master thesis in Chiba University.

千葉大学 (融合理工学府) 修士論文用テンプレート．

## Getting Started

### Use as a repository template

To start, just click the [Use this template](https://github.com/RenaAsano/master_thesis_template/generate) link (or the green button).

[Use this template](https://github.com/RenaAsano/master_thesis_template/generate) リンクか上部の緑ボタンを押して新規リポジトリを作ってください．

### Clone repository

To clone the repository, use the following command:

クローンには下記コマンドを使ってください．

```sh
git clone https://github.com/RenaAsano/master_thesis_template.git
```

## Features

今は pLaTeX (`ptex2pdf -l -ot -kanji=utf8 -synctex=1`) でのコンパイルを想定しています．
今後 LuaLaTeX に対応する予定です．

参考文献は biber で管理するようにしています．

### Thesis

融合理工学府の修士論文は 30 ページ程度が目安となるため，文書クラスは `jsreport` および `subfiles` としました．章ごとに分割してコンパイルできます．

### Summary

千葉大学融合理工学府の修士論文発表会要旨集のテンプレートです．文書クラスは `jsarticle` としました．doc ファイルで渡される様式に合わせてあります．

### Presentation

修士論文発表会に使えるスライドのテンプレートです．文書クラスは `beamer` としました．[Metropolis](https://github.com/matze/mtheme) を想定したカスタム設定をコメントアウトした状態で載せています．
