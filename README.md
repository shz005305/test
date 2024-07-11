# test


## 概要
githubのコマンドテスト用。


## 便利なリンク集
Githubはよく接続できなくなる。そんなときに障害情報を確認。
[downdetector](https://downdetector.jp/shougai/github/)……リアルタイムでグラフでわかる。オススメ。
[githubstatus](https://www.githubstatus.com/)………全体を通しての稼働状況やカテゴリで個別の稼働状況まで掲載。
<br><br><br>


## How To
### GitBashの日本語文字化け防止
```bash
echo alias ls=\'ls --show-control-chars\' > .bashrc
```
その後GitBash再起動で完了
<br><br><br>


### 「git log」「git diff」「git show」での日本語の文字化けをまとめて対策
```bash
vim ~/.gitconfig

[core]
  pager = less -cm
  quotepath = false
```
<br><br><br>



## memo
なし

