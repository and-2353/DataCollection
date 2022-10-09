# 面白そうなデータまとめ
###### tags: `卒業研究`
###### 作成：2022-10-06 最終更新：2022-10-10

## 目次
[toc]

## はじめに: 作成の意図
本来、検証したい問いを設定してから、問いの検証方法を考え、それにあたって使えるデータを探す or 作成する ということが研究にあるべき姿勢と理解していますが、適切な問いを設定するのは研究の中で一番といっていいほど難しいものですし、データを作成するのにもコスト・知識・時間などの問題で難しい場合があるでしょう。

ですので、卒業研究においては、存在するデータから確かめられそうなことを考えるという進め方になることが、ある程度仕方ないものとして認められているように思います。

とはいえ、経営学部で普通に生活していても公開されているデータを使うことはなかなかないですし、思い浮かぶデータといっても、スポーツのデータ・財務諸表や株価など・国が出してるやつ(人口とか)くらいだという人も多いのではないでしょうか。

知っているデータが少ないと、確かめたいことを諦めることになったり、似通った研究になったりといったことがあるように思いました。また、現在のインターネットは、必要なもの(たとえば、特定のデータ)を取りに行くためにはかなり有用なものでありますが、知らないもの(たとえば、利用可能でユニークなデータ)を取りに行くためにはうまくいかないことが多く、知見を広げるような使い方はなかなか困難なものがあります。

なので、僕が知っている範囲で研究に使えるかもしれない面白そうなデータを集めることにしました。なお、主な収集元は本・ウェブサイト・Twitterです。よければ活用してください。
村上がいつか時間あったら分析してみたいな～とか思っていたものも含まれていたりするので、面白い結果が出たら教えてください。

## 更新ポリシー
プルリクエストは歓迎します。
内容は確認しようと思いますが、なるべく多くのデータが記載されていた方が良いと考えています。

## 補足
- 本に使い方のっているものは、参考文献記載しましたが、基本的に検索しても使い方は出ると思うので必要なら本見てくださいという感じです

## 【表/数値データ】
### Iris: アヤメの花びら/がくの幅・長さのデータ
https://archive-beta.ics.uci.edu/ml/datasets/iris
[2]

### Wine Quality Data Set: ワインのデータ
https://archive.ics.uci.edu/ml/datasets/wine+quality
[2]

### Mushroom Data Set: 毒キノコのデータ
http://archive.ics.uci.edu/ml/datasets/Mushroom

### タイタニック号の生存者予測: タイタニック号乗車客のデータ
https://www.kaggle.com/c/titanictcilearn/data
[3]

### メディア芸術データベース（ベータ版）データセット: マンガ・アニメ・ゲーム・メディアアートのデータ
https://mediag.bunka.go.jp/madb_lab/lod/download/
もしくは
https://github.com/mediaarts-db/dataset



## 【画像データ】
### MNIST: 手書き数字の画像データ
https://atmarkit.itmedia.co.jp/ait/articles/2001/22/news012.html
[1]

### Fashion-MNIST: 洋服の画像データ
https://atmarkit.itmedia.co.jp/ait/articles/2005/28/news016.html
[1]

### EMNIST: 手書きアルファベットの画像データ
https://atmarkit.itmedia.co.jp/ait/articles/2009/28/news024.html
[1]

### CIFAR-10/CIFAR-100: 動物や飛行機などの画像データ
https://www.cs.toronto.edu/~kriz/cifar.html
[1]

### Optical Recognition of Handwritten Digits Data Set: 手書き数字の画像データ
https://archive.ics.uci.edu/ml/datasets/optical+recognition+of+handwritten+digits
[2]

### ETL文字データベース: 手書きまたは印刷の英数字、記号、ひらがな、カタカナ、漢字などの文字画像データ
http://etlcdb.db.aist.go.jp/?lang=ja
[2]

### 写っているオブジェクトの位置カテゴリを含む画像データ
ImageNet Object Localization Challenge：https://www.kaggle.com/c/imagenet-object-localization-challenge/overview/description
AlexNetが話題になったImageNet Object Localization Challengeのデータです

### Amazon/楽天などの商品データ
集め方知らない

### Shift15M: ファッションアプリに投稿されたコーディネートのデータ(株式会社ZOZOテクノロジーズが公開)
https://ledge.ai/tech-zozo-shift15m/
https://research.zozo.com/data.html#Shift15mDataset

---

## 【音声データ】
### BirdCLEF 2021 - Birdcall Identification: 鳥の鳴き声のデータ
https://www.kaggle.com/competitions/birdclef-2021/data

---


## 【言語資料/コーパス】
### Wikipedia
https://ja.wikipedia.org/wiki/Wikipedia:%E3%83%87%E3%83%BC%E3%82%BF%E3%83%99%E3%83%BC%E3%82%B9%E3%83%80%E3%82%A6%E3%83%B3%E3%83%AD%E3%83%BC%E3%83%89
英語版や日本語版など色々あるはずなので、必要なもの使ってください

### 現代日本語書き言葉均衡コーパス(BCCWJ): 日本語書き言葉のデータ
https://clrd.ninjal.ac.jp/bccwj/

### 昭和話し言葉コーパス（Showa Speech Corpus: SSC）: 約44時間分の音声（約53万語）を含むコーパス
音声データ、転記テキスト、形態論情報など を含む
https://www2.ninjal.ac.jp/conversation/showaCorpus/

### 青空文庫: 著作権切れした小説などのデータ
https://www.aozora.gr.jp/

### 極性辞書
単語のネガポジ値(極性)が載っている
感情分析(極性分析、ネガポジ分析)に有効

### メルカリデータセット: メルカリの商品・画像・コメントデータ
https://www.nii.ac.jp/dsc/idr/mercari/

### Mama Katu DM Corpus(ママ活DMコーパス): ママ活DMのデータ
https://www.opensourceagenda.com/projects/mama-katu-dm-corpus

### 中納言: コーパスを検索するためのWebアプリケーション
https://clrd.ninjal.ac.jp/chu-00.html
検索可能なコーパスリスト: https://clrd.ninjal.ac.jp/corpus-list.html

### keigo_transfer_task: 敬語変換タスクにおける評価用データセット
https://github.com/cl-tohoku/keigo_transfer_task

### Leipzig Corpora Collection: 多言語コーパス
https://wortschatz.uni-leipzig.de/en/download/

### asdc: Accommodation Search Dialog Corpus (宿泊施設探索対話コーパス)
https://github.com/megagonlabs/asdc

### open2ch-dialogue-corpus(おーぷん2ちゃんねる対話コーパス)
https://github.com/1never/open2ch-dialogue-corpus

### Project CodeNet: 55種類以上のプログラミング言語、約5億行のコードで構成される大規模データセット(IBMが公開)
https://ledge.ai/ibm-project-codenet/
https://research.ibm.com/blog/codenet-ai-for-code

---

## 【3Dモデル】
### 3D都市モデル（Project PLATEAU）東京都23区
https://www.geospatial.jp/ckan/dataset/plateau-tokyo23ku

---

## 【API/APIカタログ/クローラ】
### icrawler: 検索エンジンから画像を自動収集できるクローラ
https://zenn.dev/robes/articles/fb617fc0144e80

### 【2022年最新】作りたいアプリ別API一覧を全紹介〜随時更新〜 -侍エンジニア
https://www.sejuku.net/blog/7278
Yahooオークション、じゃらん、Qiita、ニコニコ動画、LinkedIn、Studyplus, Instagramなどのデータ集められる(?)ようです。面白そう

### Twitter のツイート/ 他SNSのいろいろ
Tweepy などを使って集められるそうです

### グルメサーチAPI/店名サーチAPI: ホットペッパー上の情報収集API
https://webservice.recruit.co.jp/doc/hotpepper/reference.html

### Yelp API
海外の食べログのようなものらしいです
https://fusion.yelp.com/
（前まで食べログ・ぐるなびの情報も収集できたんですが提供終了してしまったようです）

### Frickr API: 料理写真のデータ
Flickrという写真共有サイトからAPIを使用して料理の部分だけ集めるということみたいです
[2]
https://www.flickr.com/services/api/

### API一覧 -APIbank
https://www.apibank.jp/ApiBank/api?category_no=0

---

## 【データカタログ】
### kaggle
https://www.kaggle.com/datasets
kaggleは機械学習コンペティションの有名なサイト、とてもたくさんのデータがあります

### 各種データ・資料 -気象庁: 気象に関するデータ
気候・海洋・火山・地震など
https://www.jma.go.jp/jma/menu/menureport.html

### コーパス -自然言語処理の餅屋
https://www.jnlp.org/nlp/%E3%83%87%E3%83%BC%E3%82%BF/%E3%82%B3%E3%83%BC%E3%83%91%E3%82%B9?s[]=%E3%82%B3%E3%83%BC%E3%83%91%E3%82%B9

### データ -自然言語処理の餅屋
https://www.jnlp.org/nlp/%E3%83%87%E3%83%BC%E3%82%BF/top?s[]=%E3%82%B3%E3%83%BC%E3%83%91%E3%82%B9

### 日本の言語資源・ツールのカタログ
http://www.jaist.ac.jp/project/NLP_Portal/doc/LR/lr-cat-j.html

### GEC-Info-ja: 文法誤り訂正に関する日本語文献を収集・分類するためのリポジトリ
https://github.com/gotutiyan/GEC-Info-ja

### 日本語学習者コーパス: 文法誤りのデータ
https://qiita.com/mamorlis/items/516f48b0e53df61be2df

---

## 【学習済みモデル/学習済みモデルカタログ】
### フリーで使える日本語の主な大規模言語モデルまとめ
https://zenn.dev/hellorusk/articles/ddee520a5e4318

---

## 出典
[1][PyTorchニューラルネットワーク実装ハンドブック (Pythonライブラリ定番セレクション) ](https://www.amazon.co.jp/PyTorch%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF%E5%AE%9F%E8%A3%85%E3%83%8F%E3%83%B3%E3%83%89%E3%83%96%E3%83%83%E3%82%AF-Python%E3%83%A9%E3%82%A4%E3%83%96%E3%83%A9%E3%83%AA%E5%AE%9A%E7%95%AA%E3%82%BB%E3%83%AC%E3%82%AF%E3%82%B7%E3%83%A7%E3%83%B3-%E5%AE%AE%E6%9C%AC-%E5%9C%AD%E4%B8%80%E9%83%8E/dp/4798055476/ref=sr_1_1?keywords=pytorch%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%E3%83%8D%E3%83%83%E3%83%88%E3%83%AF%E3%83%BC%E3%82%AF%E5%AE%9F%E8%A3%85%E3%83%8F%E3%83%B3%E3%83%89%E3%83%96%E3%83%83%E3%82%AF&qid=1664986562&qu=eyJxc2MiOiIwLjk1IiwicXNhIjoiMC41OSIsInFzcCI6IjAuMDAifQ%3D%3D&sprefix=pytorch+%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%A9%E3%83%AB%2Caps%2C182&sr=8-1)
[2][すぐに使える! 業務で実践できる! Pythonによる AI・機械学習・深層学習アプリのつくり方](https://www.amazon.co.jp/%E3%81%99%E3%81%90%E3%81%AB%E4%BD%BF%E3%81%88%E3%82%8B-%E6%A5%AD%E5%8B%99%E3%81%A7%E5%AE%9F%E8%B7%B5%E3%81%A7%E3%81%8D%E3%82%8B-Python%E3%81%AB%E3%82%88%E3%82%8B-AI%E3%83%BB%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%E3%83%BB%E6%B7%B1%E5%B1%A4%E5%AD%A6%E7%BF%92%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E3%81%A4%E3%81%8F%E3%82%8A%E6%96%B9-%E3%82%AF%E3%82%B8%E3%83%A9%E9%A3%9B%E8%A1%8C%E6%9C%BA/dp/4802611641/ref=sr_1_1?crid=2L6VHEXVW73QV&keywords=python%E3%81%AB%E3%82%88%E3%82%8Bai+%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92+%E6%B7%B1%E5%B1%A4%E5%AD%A6%E7%BF%92%E3%82%A2%E3%83%97%E3%83%AA%E3%81%AE%E4%BD%9C%E3%82%8A%E6%96%B9&qid=1664986438&qu=eyJxc2MiOiIwLjk0IiwicXNhIjoiMC44MSIsInFzcCI6IjAuMDAifQ%3D%3D&sprefix=python%E3%81%AB%E3%82%88%E3%82%8Bai%2Caps%2C201&sr=8-1)
[3][Kaggleのチュートリアル第５版](https://www.amazon.co.jp/Kaggle%E3%81%AE%E3%83%81%E3%83%A5%E3%83%BC%E3%83%88%E3%83%AA%E3%82%A2%E3%83%AB%E7%AC%AC%EF%BC%95%E7%89%88-%E3%82%AB%E3%83%AC%E3%83%BC%E3%81%A1%E3%82%83%E3%82%93/dp/B09L3C69ZW/ref=sr_1_12__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&crid=2L8BRVVM9QKXV&keywords=kaggle&qid=1664988385&qu=eyJxc2MiOiI0LjcwIiwicXNhIjoiMy45MSIsInFzcCI6IjMuODkifQ%3D%3D&sprefix=kaggle%2Caps%2C241&sr=8-12)
