# githubの使い方及びやること
## ステップ１．gitをインストールする
## ステップ２．githubアカウントを作る
## ステップ３．git cloneして編集，commit&pushする

### ステップ１
windowsならgitで検索，Linuxなら```yum install git```コマンドでインストールする
### ステップ２
githubアカウントを作る(github.comで検索)
githubアカウント名をしゅんに伝え，アクセス権限をもらう

### ステップ３
１．cmdで，自分のPCのデスクトップなどファイルを保存するディレクトリに移動
２．
```git clone https://github.com/Tivo0921/projectC```

コマンドでファイルをcloneしてディレクトリを移動
```cd projectC```

３．(vscode推奨)vscodeの拡張機能を追加する(github pull request, gitlens - git supercharged, (自由：git graph))
４．自分のファイルを編集，テスト(デバッグ)する 
５．以下コマンドを1行ずつ順に打つ
```git remote set-url origin https://github.com/Tivo0921/projectC```

```git remote -v```

```git add .```

```git commit -m "ここに変更内容をコメント"```

例：Changed life6.c file. Added manzai_life.
```git push origin main```
