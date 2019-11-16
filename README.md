# openml_sklearn_example

## 概要

本プロジェクトは、OpenMLの動作確認を目的としたノートブックを集めたのものです。
特に、 [公式Example] を元に説明を加えたり、見た目を整えたり、理解のための処理を加えたりしたものである。

[公式Example]: https://openml.github.io/openml-python/develop/examples/index.html

## Pipefile

[pipenv] で環境構築するためのPipfile、Pipfile.lockを含めてある。

[pipenv]: https://pipenv.kennethreitz.org/en/latest/

aptやpipでpipenvをインストールした後、本ディレクトリ内で `pipenv install` すると、
このノートブックを実行する際に必要なライブラリが仮想Python環境にインストールされる。
その後、 `pipenv run jupyter notebook` でノートブックを開くとよい。

## 注意点

なお、注意点として、lzma関連の開発パッケージをインストールしておかないと警告が生じるという点が挙げられる。
Ubuntuであれば、 `liblzma-dev` をインストールしてから、pyenv、pipenvでPython環境を構築すること。

<!-- vim: set tw=0 ts=4 sw=4 number: -->
