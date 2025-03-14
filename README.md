# JMMLUsciencedifficulty
JMMLU（日本語マルチタスク言語理解ベンチマーク）のhigh_school_physics.csv, high_school_chemistry.csv, high_school_biology.csvについて、日本の学習指導要領(the Courses of Study)に照らした難易度を付与したもの。

## 項目
次の項目からなる。項目名はアノテータに渡したものを、そのまま載せている。

> 難しさ（0,1,2,3のどれかの数値を入れる）	メモ（大半は空欄でよい）	問題文	選択肢A	選択肢B	選択肢C	選択肢D	答え

難しさの数値の意味としてアノテータに与えた指示は次の通り。〇〇には物理、化学、生物のいずれかが入る。ここで、「〇〇基礎」とは一般的な意味での基礎レベルという事ではなく、科目としての〇〇基礎である。

* 0:中学までの知識で解ける
* 1:〇〇基礎までの知識で解ける
* 2:〇〇までの知識で解ける
* 3:高校を超える水準の問題である

### アノテーション方法

教育大学の技術科の学部4年生3名が各々1つの科目をラベル付けした。高等学校学習指導要領（平成30年告示）の「理科」部分 、および、高等学校学習指導要領（平成30年告示）解説の「理科編　理数編」を熟読し、参照しながらラベル付けするように指示した。

https://www.mext.go.jp/a_menu/shotou/new-cs/1407074.htm

ラベル付け後、本データセットの下記記載のライセンスでの公開については当該学生らの許可を取得している。

## ライセンス

問題文、選択肢A、選択肢B、選択肢C、選択肢D、答えは、下記の著作権表示に示すJMMLUをそのまま複製したものである。
JMMLUはCC-BY-SA-4.0 licenseであり、本データセットも当該ライセンスと同じライセンスで公開している。


Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

### 改変元のJMMLUの著作権表示
JMMLU
日本語マルチタスク言語理解ベンチマーク Japanese Massive Multitask Language Understanding Benchmark
https://github.com/nlp-waseda/JMMLU
