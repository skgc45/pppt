＝＝＝＝＝＝＝
乗りログアプリ
＝＝＝＝＝＝＝

目的
＝＝

Webブラウザーでコメントを投稿するWebアプリケーションの練習。

ツールのバージョン
＝＝＝＝＝＝＝＝＝
:Python:        3.6.4
:pip:           10.0.1

インストールと起動方法
＝＝＝＝＝＝＝＝＝＝＝

リポジトリーからコードを取得し、その下にvenv環境を用意します::

        $ git clone https://github.com/skgc45/pppt
        $ cd pppt
        # python3.6 -m venv venv
        # source venv/bin/activate
        (venv) $ pip install .
        (venv) $ norilog
         * Running on http://127.0.0.1:8000/

開発環境
＝＝＝＝

開発用インストール
ーーーーーーーーー

１．チェックアウトする
２．以下の手順でインストールする ::
        (venv) $ pip install -e .

依存ライブラリ変更時
ーーーーーーーーーー

1.``setup.py``の``install_requires``を更新する
2.以下の手順で環境を更新する::

        (venv) $ deactivate
        $ python3.6 -m venv --clear -venv
        $ source venv/bin/activate
        (venv) $ pip install -e ./norilog

3.setup.pyをリポジトリにコミットする
