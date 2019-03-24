### シンボリックリンクの作成

```.sh
$ln -s オリジナルの絶対パス シンボリックリンクを置きたいディレクトリのパス
```

### シンボリックリンクの確認

```.sh
$ls -l シンボリックリンク
```

### シンボリックリンクの更新

```.sh
$ln -nfs 更新したいディレクトリのパス 更新後のシンボリックリンク先の絶対パス
```