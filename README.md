pixivTagCollectorChrome
=======================

pixiv Tag Collector for Chrome extentions Version 1.0

Authers:
  sato1043 and monsier-oui

はじめまして。
pixiv Tag Collector Chrome拡張版のリリースをご案内します。

これはpivivのタグ巡回を快適にするChrome拡張です。
pixivの普段使いの検索リンクをクリックしやすい位置に常に表示します。
このChrome拡張はあなたが見るpixivの見た目を多少書き換えます。


## できること
* pixivの普段使いの検索リンク＝タグをクリックしやすい位置に常に表示
* 企画の〆切り日時と残り時間を３つまで、目につくように常に表示
* マイページの自分があんまり使わない一覧など表示切り替え
* 検索結果をクリックしたときに別ウィンドウに開くように指定
* 検索結果にNGワードを設定し、画像非表示

このスクリプトのオリジナルはpivivのタグ巡回を快適にするGreasemonkyスクリプトです。
これが使えなくて Chrome が不便だった方にどうぞ。

ただし、このChrome拡張はオリジナルの作者様とは関わりがありませんので、
このChrome拡張へのお問い合わせは私(sato1043@gmail.com)にお願い致します。


## 配布物
* pixivTagCollector.crx ... Chrome拡張。これだけです。


## インストール
Chromeを起動して、メニューから[ツール]-[機能拡張]を開きます。
その中へ pixivTagCollector.crx をドロップしてください。
機能拡張の問題が指摘されますが、それに同意頂ければインストールは完了です。


## アンインストール
Chromeを起動して、メニューから[ツール]-[機能拡張]を開きます。
pixivTagCollector行の右端にあるゴミ箱アイコンをクリックしてください。
機能拡張は削除され、設定も残りません。


## アップデート
まず、以前のバージョンのオプションをどこかにコピペしてバックアップしてみてください。
それと、現状のバージョン番号を控えておいて下さい。

Chromeを起動して、メニューから[ツール]-[機能拡張]を開き、
その中へ pixivTagCollector.crx をドロップしてください。
バージョン番号が上がっていれば成功です。設定を確認したらバックアップや控えは破棄できます。


## 設定
インストール後にツールバーにボタンが増えます。それをクリックしてください。
メニューが現れますので、設定を開き、ご自分用のタグを追加して下さい。
（もしくは以前の設定をコピペしてください。）

左のテキストエリアが「一文字たがわず同じタグの絵の検索」を書き込むところ、
右のテキストエリアが「一部同じ言葉を含むタグの絵の検索」を書き込むところです。
いずれも、１行１単語で書くようにおねがいします。

設定を変えたら必ずSaveを押してください。
また、変更した設定をpixivに反映するには一度ページをリロードしてください。


## 動作確認
タグを設定してpixivを開きます。
ページの先頭にタグの一覧が現れるはずです。
タグをクリックしてみてください。pixivの検索結果が開きます。


## 謝辞
  * オリジナルの作者 カンジャさんに感謝致します。
  * ouiさんは、やるきのない私にやる気をくれました。ありがとうございます。
  * それからいつも応援してくれる私のメインユーザに。いつもありがとう。
  * それと最後にpixivに。


## TODO
  * pixivを開いているタブ(ウィンドウ?)のリロード


## 履歴
* 2013/12/30 - 0.7 (aka. 1.0alpha)
    - 検索結果のNGワード機能追加

* 2013/12/30 - 0.6 (aka. 1.0alpha)
    - Chromeのmanifest.json 2に対応(oui)
    - UIをおおはばに改善(oui)
    - 〆切りタイマー機能を追加(oui)
    - 現状のpixivに対応
    - AutoPagerize / AutoPatchwork の動作に対応
    - マイページのパーツ表示切り替え機能を追加

* 2012/08/09 
    - 流用・公開の許可をいただきました。

* 2012/05/20 - 0.3
    - create a git repository
    - modify our file layout

* 2012/05/19 - 0.2
    - works `mouseover'
    - works `open in a new tab'
    - click browser action button then get pixiv tab

* 2012/05/03 - 0.1 
    - created

__END__