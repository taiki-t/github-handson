class: center, middle

# GitHubとPull Request ハンズオン

### エフスタ!!「あなたも恋する♡GitHub勉強会」
### セッション1

2016/11/26 ビッグアイ７F 市民交流プラザ 第2会議室  
Naoyuki Yamada  

---
class: center, middle

このプレゼンテーションはremark.jsで作られGitHub上で公開されています

### GitHubレポジトリ

https://github.com/chokkoyamada/github-handson

### プレゼン資料

https://chokkoyamada.github.io/github-handson/

---

# もくじ

1. 自己紹介
2. このセッションでやること
3. GitHubに登録してみよう

---

# 自己紹介

* 福島県浪江町役場 復興推進課　任期付職員(2016/7~)
* 東京の民間のIT企業を休職中
* 郡山市在住
* インフラ・サーバーの運用を得意とするソフトウェアエンジニア  
  キーワード : オペレーションエンジニア, DevOps
* これまでのプレゼン資料 http://www.slideshare.net/satully

---

# このセッションでやること

### GitHubに登録してみよう(10分)

とにかく登録してみます。すでにアカウントある人はおさらいで。
スマホでも登録できます

### Pull Requestを体験してみよう(20分)

GitHubのシステムの最も肝の部分であるPull Requestについて実際に体験してみます

### その他のGitHubの機能(10分)

### 質疑応答(10分)

---

# GitHubに登録してみよう

<img height="500" alt="2016-11-26 11 06 35" src="https://cloud.githubusercontent.com/assets/843192/20637365/fb9614ae-b3c8-11e6-9bc8-a696b8a58d1d.png">

---

* GitHub ID, メールアドレス, パスワードを入力してSign Up

<img width="500" alt="_2016-11-26_11_07_10" src="https://cloud.githubusercontent.com/assets/843192/20637383/6862ee68-b3c9-11e6-83a4-6a0c28d8ae2d.png">

---

* Continue

<img width="500" alt="_2016-11-26_11_07_22" src="https://cloud.githubusercontent.com/assets/843192/20637386/87787d54-b3c9-11e6-890f-45555d724d86.png">

---

* アンケートはやっても、スキップでもどちらでもOK

<img width="500" alt="_2016-11-26_11_07_36" src="https://cloud.githubusercontent.com/assets/843192/20637391/a57a8dce-b3c9-11e6-936a-01c10c136b87.png">


---
* 登録完了

<img width="500" alt="2016-11-26 11 07 49" src="https://cloud.githubusercontent.com/assets/843192/20637396/bfeccf0a-b3c9-11e6-9640-3238d4ec5559.png">

---

* "Please verify your email address"と出たら・・・

<img width="500" alt="2016-11-26 11 08 00" src="https://cloud.githubusercontent.com/assets/843192/20637398/d2aab170-b3c9-11e6-8999-66eb7231989c.png">

---

* 自分のEメールを確認してください

<img width="500" alt="_2016-11-26_11_08_13" src="https://cloud.githubusercontent.com/assets/843192/20637402/f107a772-b3c9-11e6-9577-b19e228f63b1.png">

---

# Pull Requestを体験してみよう

GitHubにログインした状態で、
https://github.com/chokkoyamada/github-handson
にアクセスしてください。

---

* "Fork"を押します。

<img width="500" alt="_2016-11-26_11_28_29" src="https://cloud.githubusercontent.com/assets/843192/20637534/0236925c-b3ce-11e6-86a9-093489fa9a56.png">


---

* slide.mdを編集してみます。

<img width="500" alt="_2016-11-26_11_48_48" src="https://cloud.githubusercontent.com/assets/843192/20637561/90b48246-b3ce-11e6-8f5a-83b23d7a33f9.png">

---

* 編集します。

<img width="500" alt="_2016-11-26_11_32_36" src="https://cloud.githubusercontent.com/assets/843192/20637572/15e61a1a-b3cf-11e6-9514-12657c5b59ce.png">

---

# remark.jsとMarkdownの基本（このファイルの書き方）

* `---` 三本の―で区切ることでページの境目になります。
* `#`で見出しになります。 #の数が大きいほど小さな見出しになります。 #はh1, ##はh2...
* `*`で箇条書きのリストを作ります。

---

* 変更をcommitします。


<img width="500" alt="2016-11-26 11 32 15" src="https://cloud.githubusercontent.com/assets/843192/20637578/58c92534-b3cf-11e6-9a64-91c52e72ee78.png">

---

次にPull Requestを作成します。

https://github.com/chokkoyamada/github-handson  

に戻ります。

---

* New Pull Requestを押します 

<img width="500" alt="_2016-11-26_11_32_57" src="https://cloud.githubusercontent.com/assets/843192/20637581/79fe29d4-b3cf-11e6-82be-4239e27a699a.png">

---

* "Compare Accross Folks"を押し、自分のレポジトリを選択してPull Requestを作ります。さきほどの変更が反映されているはずです。

<img width="500" alt="_2016-11-26_11_33_59" src="https://cloud.githubusercontent.com/assets/843192/20637589/bfef9d24-b3cf-11e6-808e-98f1bf00c8b9.png">

---


* Pull Requestが作成されました。

<img width="500" alt="2016-11-26 11 40 51" src="https://cloud.githubusercontent.com/assets/843192/20637598/f559f2a2-b3cf-11e6-8973-6442f6ee16d6.png">


---

class: center, middle

# Pull Requestを受ける側

---
* Pull Requestが来ていることが確認できます。

<img width="500" alt="_2016-11-26_11_41_40" src="https://cloud.githubusercontent.com/assets/843192/20637610/68d8daa4-b3d0-11e6-9fc1-9f3866666082.png">

---

* 確認して、適宜コメントするか、内容がOKであればマージを行います


<img width="500" alt="_2016-11-26_11_41_49" src="https://cloud.githubusercontent.com/assets/843192/20637617/9450dd3a-b3d0-11e6-9880-e26480970e55.png">


---

* マージが完了しました。

<img width="500" alt="2016-11-26 11 42 21" src="https://cloud.githubusercontent.com/assets/843192/20637620/a9a73a4e-b3d0-11e6-93c0-337182662787.png">

---

# Pull Requestの何が良いのか？

* 小さなパッチを送ることが分かりやすく、かつオープンにできる
* レビューのプロセスが挟まることで、コードの品質が良くなる

---

# Git, GitHubと組み合わせたときの利点

* 大人数でいっぺんに開発がやりやすい
* ブランチをたくさん作ってコミットが多くなってきても重くならない
* GitHubはウェブサービスなのでどこからでもアクセスができる

---

# 他のGitHubの機能

* ウェブサイトのホスティング(GitHub Pages) ←このプレゼンでも利用
* Issue管理（バグトラッカー）
* Wikiの機能
* 自動テストとの連携

--- 

# GitHubと同じようなGitホスティングサービス

- Bitbucket
- GitLab
- など
