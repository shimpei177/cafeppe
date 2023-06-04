# cafeppe
■ サービス概要
カフェが好きでカフェ巡りしたい人、コーヒーが好きな人が
訪れたことがある人がしている投稿をみて
味のイメージや雰囲気などを知ることができるカフェ情報サービスです。



■ユーザーが抱える課題
コーヒーが好きでカフェ巡りをしたいが、どこにどんな味のコーヒーを出しているカフェがあるかわからない、
イベント等で近くまで行ったが疲れてしまって一休みしたいという時にどのカフェにはいればいいかわからない。
どうせなら自分にとってニーズを満たせるカフェで時間を過ごしたい。


■課題に対する仮説
- 自分の好みや目的とマッチするカフェが行ったことがあるところでないと選べない。
  1. そもそもどこにどんなカフェがあるかわからない。
  2. 何店舗か行ってみたが、自分の好みにあまり合わなかった。深煎りのコーヒーが好きなのに浅煎りのコーヒーばかり。
  3. 自身の好みにあうカフェを選ぶ際に情報を収集することが大変。


■解決方法
- 実際に行ってしかわからないコーヒーの種類や煎り度合いなどを
　投稿内容を通して掴めるようにする。
  - 写真やメニューをコメント付きで投稿できるようにする。
  - 投稿フォームに、コーヒーの焙煎度、読書等できる雰囲気かにぎやかな雰囲気か、を評価できる機能をつける
  -  



■メインのターゲットユーザー
カフェ好きな方々


■実装予定の機能（以下の例は実際のアプリの機能から一部省略しています）
- 未ログインユーザー
    - LPに訪れたユーザーが登録店舗一覧を閲覧することができる
        - ユーザーがLPを閲覧できる
        - ユーザーが検索機能を使って絞り込みができる（ex.地域、駅名で）
        - ユーザーが店舗詳細ページを見にいくことができ、コメントや投稿を閲覧することができる。
        - GoogleMapのAPIを使って場所の確認をすることができる。
        - 登録されたメールが存在するかチェックするアクティベーション機能
       
        
- ログイン中のユーザー
    - 店舗の登録ページにて詳細ページの作成ができる
    - 店舗詳細ページからコメント付きの評価の投稿をすることができる 
    - アプリからユーザーへ、ユーザーのよく行く場所でのおすすめカフェを紹介するレコメンド機能
    - 登録されたメールが存在するかチェックするアクティベーション機能
    - like機能で登録した店を後から見ることができる
    - １週間単位で閲覧数の多い（興味を持たれている）カフェをランキング形式で発表する
- 管理ユーザー
    - ログインユーザーの検索、一覧、詳細、編集
    - 店舗詳細ページの一覧、詳細、作成、編集、削除
    - 投稿の一覧、詳細、作成、編集、削除
    - 管理ユーザーの一覧、詳細、作成、編集、削除

■なぜこのサービスを作りたいのか？
おいしいコーヒーが飲みたいが、個人経営のお店に行くのは少し緊張する、ましてや初めてのお店なら尚更、という気持ちがスタートです。

社会人になるまではカフェに行くもののコンビニエンスストアやチェーン店が大半でした。

そんな中、社会人になってとある個人経営のお店で飲んだコーヒーが飲んだことがないようなもので感動し、それ以来カフェ巡りが趣味になりました。


このアプリを通して、ユーザーの方々が自分お求めているコーヒーに巡り会え、気分よくカフェを楽しんでいただければ幸いです。


■スケジュール

▼スケジュール
企画〜技術調査：5/23〆切
README〜ER図作成：5/28 〆切
メイン機能実装：5/29~6/4
β版をRUNTEQ内リリース（MVP）：6/4〆切
本番リリース：6月末

■技術選定
- Rails7
- postgresql
- JavaScript
- Bootstrap
- AWS
- GoogleMapsJavascriptAPI

画面遷移図
https://www.figma.com/file/WhPYrkBeQibdBZnPlGeM0z/%E7%84%A1%E9%A1%8C?type=design&node-id=0%3A1&t=XigkRc6Wx5W1qdbi-1

ER図
https://drive.google.com/file/d/1pxodJlwG_2LnhyW-dA4n8uRjQExOWffu/view?usp=sharing