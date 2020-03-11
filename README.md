# vueの入門者のためのシンプルなリポジトリ

Vue CLIで作成したデフォルトプリセットをちょっといじったプロジェクトです。  
フォークしたりクローンしたりして使ってください。

ブランチを切り替えることでいくつかのサンプルコードが入っているようにするつもりです。

現在のブランチリスト
- master：最もシンプル。dataとマスタッシュ展開のみ
- sample1/data_and_mastash dataとマスタッシュ展開2個
- 

## プロジェクトのセットアップ
リポジトリをチェックアウトして
```.bash
#初回のみ
npm install 
```

### 開発するとき
```
# なんかおかしくなったらCmd(Ctrl)+Cして止めてもう一回
npm run serve
#   App running at:
#  - Local:   http://localhost:8080/ 
#  - Network: http://192.168.11.8:8080/
# ↑みたいなメッセージが表示されるので、表示された Localのほうをブラウザで開く


```

### 最初に見るコード
src/App.vue を好きなエディタで開いてください。

### プロダクションビルドするとき
```
npm run build
```

### ライセンス
MIT
