# Phylogenetic-tree-generator

### 概要
このツールは、Excelで記述された架空生物のデータをもとに、**自動で系統樹を生成するPythonスクリプト**です。

### 制作背景
私が生物(私の場合は特に無脊椎動物)に関する創作をしていく中で、コンセプトのアイデア出しと深堀りをするだけでなく、途中でコンセプトがぶれていく事態を回避するための支援ツールが欲しいと感じていました。
そこで、生成AIとPythonを活用し、インスピレーションをより膨らませ架空世界のベースとなるような構造を生み出すためのツールの一つとして、架空生物の系統樹生成を思いつきました。

### 使用方法
こちらのコードはGoogle Colab上で動作させることを想定しております。ete3ではなくMatplotlibを使っているので、Colab上であっても生成した系統樹を問題なく出力できます。

### DEMO
[phylum_data.xlsx](https://github.com/user-attachments/files/22192608/phylum_data.xlsx)
←こちらのファイルを使用した場合の出力結果は以下のようになります。
<img width="14625" height="23682" alt="67e0971e-6a3f-4dd1-ab56-40af820b7335" src="https://github.com/user-attachments/assets/4383195b-e50a-4411-ab7a-86335afe8bca" />

