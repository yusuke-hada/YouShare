# YouShare  

## サービス概要  

YouShareは口コミベースのYoutube動画共有サービスです。  
ユーザーは自らのお気に入りのチャンネルやおすすめの動画を紹介し、他のユーザーと共有できます。新しいジャンルやハマれるコンテンツを探しているユーザーは、口コミを元に気軽にアクセスし新たな動画の発見を体験することができます。  


## このサービスへの思い・作りたい理由  

私は長い間、Youtubeを愛用しています。初めて中学生の時にPCを手に入れてから、約16年間このプラットフォームで多くのコンテンツを楽しんできました。  
最近になり私が主に楽しんでいたチャンネルが活動休止をしたことから、新たにハマれるYoutuberを探していました。しかし、Youtubeのトップページのカテゴライズは登録チャンネル・急上昇・音楽・ゲーム・ライブ(配信)・ミックス(音楽)・アニメ・アクション・アドベンチャー(ゲーム)"と限られており、目的を持たずに夢中になれるコンテンツを探そうとすると、どのように検索すればよいのか分からず迷ってしまいます。  
トップページに表示される動画はYoutube側がユーザーの好みの動画を推測して表示してくれていますが過去に視聴したことがあるものや同じ系統の動画が表示されており新しいジャンルのコンテンツを探したい時には使いづらいさを感じました。また動画のサムネイルとタイトルだけでは得られる情報に限りがあり、どの動画が自分の求めている動画なのか判別できないこともあります。登録者や動画視聴時間が少ないとアルゴリズム上検索でユーザーの目に映る機会が少なくなってしまいます。SNSでも同様で検索も難しく、タイムラインのおすすめ投稿も流れが速く、見逃してしまうこともしばしばあります。そのような理由から私は主に新しくコンテンツを探したいときは親しい友人などからおすすめを聞いたりすることが多いです。これを友人だけでなく同じ目的を持った多数のユーザー間でシェアすることができればより多くのコンテンツに出会えるのではないかと考えました。  
自分のお気に入りのコンテンツを他のユーザーとシェアすることができ、その口コミを閲覧できるアプリがあれば私の悩みを解決できると考えました。Youtubeというサービスを今後もより楽しみ、新しい発見をするために今回ポートフォリオの案としました。  



## ユーザー層について  

**新しくコンテンツを探しているユーザー**  
　Youtubeのような巨大なコンテンツから自分の好みのチャンネルや動画を手軽に見つけるのは難しいと感じています。私のように主に視聴していたコンテンツが停止した場合に新たにコンテンツを探したいユーザーや新しく自分の好みのコンテンツを探したいユーザーをターゲットとしています  

**おすすめ(推し)を共有したいユーザー**  
　ファンとして推しの存在を広めたいと言うユーザーもいると思います。広まることで登録者が少ないうちから応援していたファンとして古参と言うステータスを得られ、知名度や登録者数が増えることでさらに充実した活動が展開される可能性を期待できるため、おすすめ(推し)を共有するユーザーにとってもメリットがあります  

**特定のジャンルやテーマでのおすすめを知りたいユーザー**  
　多様なジャンルやテーマが存在するYouTubeで一つのジャンルに絞ってもそのジャンルのYoutuberは多数存在します。Youtubeのアルゴリズムだけでは新しいおすすめや隠れた名作を見つけるのが難しいことがあるためこのユーザーをターゲットとしています  


## サービスの利用イメージ  

会員登録しログインしていただきます(本リリース時にはGoogleアカウントログインを追加)  

**コンテンツを探したい方**  
チャンネルor動画のどちらを探したいか選択します  
チャンネル一覧or動画一覧の中から投稿者の紹介文や他ユーザーのコメント、カテゴリーやタグを見ながら自分の好みのコンテンツを探します  
チャンネル投稿ページに飛んだら投稿の中でチャンネルのリンクをクリックするとYoutubeのチャンネルページに飛びチャンネル登録などが行えます  
動画投稿ページに飛んだ場合は投稿の中に動画が埋め込んであるのでそのまま視聴することができます  
また、各投稿に対してコメントをすることができます  

**コンテンツを投稿したい方**  
投稿ページからチャンネルか動画のURL、カテゴリー、タグ、紹介文を入力し投稿します  
URLを貼り付けて投稿することでチャンネルの場合はAPIを用いてチャンネルのサムネイルや説明文、登録者数数などの情報を取得し表示させることができます  
動画の場合はURLの動画を投稿内に埋め込み、APIを用いて再生回数などの情報を取得し表示します  

 
## ユーザーの獲得について  

SNSでの宣伝やYoutubeを利用している友人に口コミで広める予定です  

## サービスの差別化ポイント・推しポイント  

おすすめのチャンネルや動画を共有する掲示板サービスはいくつか存在します。  
その多くは掲示板方式で投稿順に表示されると言うシンプルなもので、投稿がどんどん埋もれてしまいユーザーの目に映る機会は少なくなってしまいます。また特定の投稿やカテゴリ検索などの機能がないためユーザーの好みの投稿を探すことが難しいです。  
YouShareではこれらの課題を解決するためにカテゴリーやタグ機能を追加しユーザーの興味のあるジャンルやテーマに特化した投稿を検索することができます。  
また、情報の共有ができるように投稿者だけでなく投稿を閲覧したユーザーもコメントやそのYoutuberのおすすめ動画を投稿することが可能です。  


## 機能候補  

### MVP  
・会員登録  
・ログイン・ログアウト  
・パスワードリセット  
・投稿のCRUD機能(チャンネルor動画)  
・チャンネルor動画の検索機能（オートコンプリート機能）  
・タグ・カテゴリーでの検索機能  
・コメント機能  
・ブックマーク機能(マイページにブックマークした投稿を表示するため)  
・投稿されたチャンネル・動画の情報をYoutubeDataAPIを用いて情報を取得する  
・SNS(X)へのシェア機能  

### 本リリース  
・Googleアカウントログイン機能  
・ゲストログイン機能  
・LINE通知機能(投稿の中から'おすすめ投稿'をユーザーに送信)  


## 機能の実装方針予定  

・Ruby: 3.1.4  
・Rails: 7.0.8  
・フロントエンド: HotWire  
・CSSフレームワーク: boostrap5系  
・YoutubeDataAPI(ユーザーがおすすめのYoutubeチャンネルのURLを投稿するとURLからチャンネルIDを抽出しYoutubeDateAPIを用いてチャンネルのタイトルやサムネイル、概要等を表示できるようにする)  
・LINE Messaging APIとLINE Messaging API SDK for Rubyを用いてLINE連携をしたユーザーにおすすめのコンテンツを配信する  
・会員登録はMVP時にはSorceryを用い、その後Googleアカウント認証を実装する  