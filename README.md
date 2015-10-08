# python実行環境のインストール
対象のホスト上でaptでインストールを行います。  
インストール対象は次のパッケージです。  

+ python
+ python-pip

すでにこれらのパッケージがインストールされている場合はこの手順は必要ありません。

```sh
$ ansible-playbook -i hosts python.yml
```