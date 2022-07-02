<img src="https://user-images.githubusercontent.com/3040830/176997227-2e356070-1487-46d2-87e8-468aaf2862f1.png" alt="screen shot" width="640px"/>

### ダウンロード・インストール
- [Chrome Web Store](https://chrome.google.com/webstore/detail/carvewords/ihidmddjffcegbkfjhgkmijifjkammfl)

<br>

# 概要

語彙の学習と長期記憶を支援するウェブ拡張機能です。

ウェブページ上の未知の単語を強調表示し、覚えたい単語に印をつけることができます。  
類似の拡張機能と異なり、印をつけておしまいではなく、長期にわたり繰り返し記憶を試されるのが特長です。

<br>

# その他の特長

- ウェブページの可読性（既知の単語の割合）を表示
- マウスオーバーした単語と範囲選択した文章の読み上げ機能（速度調整可能）
- 学習語彙のエクスポートとインポート
- オフラインで動作（クラウド音声の利用を除く）
- 英語以外の学習も可能
- アカウント登録不要・広告なし・完全無料
- 最新のウェブ拡張機能仕様「Manifest V3」に準拠

注）辞書機能やフラッシュカードは搭載していません。他のお好みの辞書拡張機能やフラッシュカードアプリを併用してください。表示が重ならないよう、オプションでバルーンの位置を変更することができます。

<br>

# 使用法

1. まず、当拡張機能のオプション画面を開き、「既知の語彙セット」から既に知っている語彙を選択します。「ユーザー学習語彙」の注意事項もお読みください。
2. 学習対象の言語（通常は英語）で書かれた、お好きなウェブページを開きます。当拡張機能のアイコンをクリックするか、コンテキストメニューから「単語を強調」を実行します。
3. 未知の単語が強調表示されます。その単語にマウスカーソルを合わせると、３つのアイコンが現れます。  
すでに知っている単語なら、左のアイコンをクリックします。  
意味を調べて覚えようとしている単語なら、中央のアイコンをクリックします。  
以前覚えたのに忘れてしまった単語なら、右のアイコンをクリックします。
4. この学習プロセスを時間をあけて７回繰り返すと、その単語は長期記憶に定着したとみなされ、既知の単語に分類されます。忘れてしまった場合には、学習回数が０にリセットされ、再度７回学習し直さなければなりません。

<br>

# 既知の問題

## 表示されているすべての単語が既知のはずなのに、可読性が100％になりません

当拡張機能は、対象のウェブページのHTMLを走査し、特定のものを除くすべての要素から単語を機械的に収集します。  
しかし、HTMLの要素はすべてがユーザーに見えているとは限りません。操作に応じて表示されるタブやポップアップ、表示を目的としない隠し要素などさまざまです。  
そうした見えない要素の中に未知の単語があると、可読性の値はそのぶん下がります。これが問題の原因です。  
不特定多数のウェブサイトにおいて、可視の単語だけを選び取ることは技術的に困難であり、また内容が動的に書き換われば結局は見た目と値とが矛盾することになります。したがって、可読性の値は絶対正確なものではなく、おおよその傾向を表す概算と捉えてください。

## ウェブページの機能が効かなくなったり、動作がおかしくなることがあります

やむを得ない副作用です。  
当拡張機能は、単語を強調表示するためにHTMLの要素を書き換えます。しかし、ウェブページ上のプログラムにとって要素が書き換えられることは想定外のため、思わぬ誤作動を引き起こすことがあります。そのような場合には、ページをリロードすれば元に戻ります。  

この問題は、当拡張機能に限らず多くのウェブ拡張機能に共通の現象です。たとえば買い物の決済など、プログラムの誤作動が重大な結果につながりかねない状況では、ウェブ拡張機能全般の使用を控えたほうがよいでしょう。

<br>

# プライバシーポリシー

- 当拡張機能は、いかなるユーザー情報も収集しません。
- 当拡張機能は、開発者ないし第三者のサーバーと任意に通信する権限を持ちません。
- ただし、ウェブ拡張機能専用APIを通じて、次のクラウドサーバーと連携することがあります。いずれもデフォルトは無効であり、ユーザー自ら有効化する必要があります。
  - クラウドで提供されるスピーチ機能
  - Googleドライブ

## Googleドライブへのユーザー学習語彙の保存

- ユーザーが学習した語彙情報を、ユーザー自身のGoogleアカウントを用いてユーザーのGoogleドライブに保存することができます。
- この語彙情報は、Googleドライブ上の、アプリケーション（つまり当拡張機能）専用フォルダーに保存されます。当拡張機能は、これ以外のフォルダーやファイルにアクセスする権限を持ちません。
- Googleドライブの仕様により、アプリケーション専用フォルダーとその配下のファイルはユーザーから隠されています。ダウンロード・印刷・他ユーザーとの共有もできません。したがって、内容が第三者に意図せず知られるおそれはありません。
- Googleドライブへの語彙の保存機能を利用する際には、当拡張機能のオプション画面からGoogleアカウントへユーザー自らサインインし、Googleドライブと当拡張機能との接続を承認する必要があります。
- この機能の利用は、いつでもやめることができます。また、Googleドライブの設定画面にて、語彙情報（アプリケーションファイル）の削除と、当拡張機能との接続の解除が可能です。

<br>

# 謝辞

- 「既知の語彙セット」は、[New General Service List Project](https://www.newgeneralservicelist.org/)の成果物です。
- 当拡張機能は、[Razmik Badalyan氏のアイデア](https://razmikb.medium.com/comprehensible-reader-generator-9a881a497e2e)に基づいて開発されました。

<br>

# 改版履歴

- バージョン 0.2 （※開発中）  
ユーザー学習語彙のGoogleドライブによる同期機能を追加
- バージョン 0.1  
2022年6月 Chrome Web Storeに公開

不具合修正・UI改善などの軽微な改版では、バージョンの３つめの位が上がります（例：「1.0.0」→「1.0.1」）。
