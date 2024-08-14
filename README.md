■サービス概要

職場の上司やお局様、嫌いな人からの嫌味な言葉をいいように変換したり、
苦手なシュチュエーションから回避方法を知る・共有するアプリ

■ このサービスへの思い・作りたい理由

仕事やプライベートで失礼な話、嫌味や意地悪る言う人がいます。
そんな時にこうやって聞き流したり、自分なりに言葉を変換すると楽になる時がある。
共感する空間を作るわけではないが、同じ境遇の人がいれば何か助けになれば

■ ユーザー層について

10代後半〜30代  

■サービスの利用イメージ

トップ画面からログイン→場面や記事をいくつか用意（掲示板）→ユーザーは気になる場面や記事に飛ぶ。開発者側で解答みたいなものを用意　
→ユーザー自身で対応や逸話があれば投稿できるようにする。

例　「朝から機嫌の悪い上司がいる。なぜか、部下に当たりが強い。どうしてだろう」
    「飲み会、行きたくない。どうやったら行かなくて済むかな」
　　　→開発者側が考えるコミニケーションの取り方や気持ちのもちようを準備
　　　「いつもの神のような優しさはどこにいったんですか」
　　　「〇〇さん、朝から奥さんと喧嘩したな。部下に八つ当たりしないとやってられないんだな」
　　　「今日はどうしても食べたいものあり、お腹に余裕を持たせたいので帰ります」など
　　　→ユーザーが思う考え方がある時はコメントできるようにする

■ ユーザーの獲得について

現状、働いている人も含めて、こういう風な関わり方があるんだ
自分がこう理解するば、楽なんだと利用するユーザーの気持ちに寄り添えれば
少しでも獲得できると考えている。

■ サービスの差別化ポイント・推しポイント

Xにはなく、自身のイメージするアプリにあるのは
ユーザーがコメントや回答する際にご自身ならこうするといった解答欄を別で設けて差別化する。
記事や内容に合わせて、イライラ度や対応の難しさがわかるメーターなどをつける

■ 機能候補

ユーザー登録機能
新規登録、プロフィール編集機能
ログイン、ログアウト機能

検索機能

掲示板への投稿→記事への投稿　変更

一覧表示→掲示板一覧　変更

投稿→記事への投稿　変更

投稿削除

デプロイの使用技術
→Herokuを使用予定
 講師からのアドバイスを参考に変更。自信で調べたところ、自分でも利用しやさを感じた。

DBの使用技術→My SQLを使用予定。こちらも再度、調べた結果、初心者には向いていること
　　　　　　　学習したことを踏まえて、扱いやすいと判断した。

本リリース

アンケート投票機能　
アンケート集計

ランキング結果発表（ベストアンサー風）→グラフを使って、アンケート集計を発表　変更

※機能候補追加分
マルチ検索
コメントに対するいいね機能


■ 機能の実装方針予定

一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。

ユーザー登録機能

→ Sorceryを使用して実装予定

掲示板一覧機能

→rails基礎７の掲示板の一覧機能作成をベースに実装する予定

掲示板への投稿

→rails基礎11のコメント投稿作成をベースに実装する予定

### 画面遷移図
Figma：https://www.figma.com/board/dS0Dob3SDjHBjIqyMIlxqO/%E5%8D%92%E6%A5%AD%E5%88%B6%E4%BD%9C?node-id=0-1&t=jKR4DxTtnJE3017y-0


ER図：[![Image from Gyazo](https://i.gyazo.com/a494f2f4b920b5d0cb3ce7847107be88.png)](https://gyazo.com/a494f2f4b920b5d0cb3ce7847107be88)