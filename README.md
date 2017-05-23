# a-blog cms 用テーマ『Carbon』

---

version 1.0.0

Author: Hisato Ishikawa    
Web: [hisato.me](https://hisato.me/)

Copyright (c) 2017 Hisato Ishikawa   
Released under the MIT license   
[https://opensource.org/licenses/MIT](https://opensource.org/licenses/MIT)

---

## このテーマについて

「Carbon（カーボン）」は、a-blog cms用のテーマ。2カラムのブログスタイルです。   

商用・非商用問わず、無償でご利用いただけます。   
よろしければ、ご利用いただいたサイトを教えてください。   
今後の開発・修正等に役立てていきます。

a-blog cms用テーマ「Carbon」は、[MITライセンス](https://opensource.org/licenses/MIT)のもとで配布いたします。

## 構成（template.yaml）

```yaml
tpl_top         : index.html
tpl_index       : index.html
tpl_detail      : index.html
tpl_404         : 404.html
tpl_admin       : admin.html
tpl_entry_edit  : index.html
tpl_entry_add   : index.html
tpl_login       : login.html
```

テンプレートは、index.html のみで作成しています。

## ビルトインモジュール

使用しているビルトインモジュールは次の4つです。

* エントリー本文（Entry_Body)
* エントリーリスト（Entry_List）
* カテゴリーリスト（Category_List）
* ユーザープロフィール（User_Profile）

## レイアウト機能

2カラムのメイン部分には、a-blog cms のレイアウト機能を採用しています。
これをつかうことで、左右が逆のレイアウトに変更できたり、モジュールの移動も可能になります。

## カスタムフィールド

ブログのカスタムフィールドに

* ヘッダーの背景色 or 画像
* メインボディの背景色 or 画像
* キーカラー

を用意しました。雰囲気を変えるのにご利用ください。

## サイズセレクト

画像や動画、地図のサイズは「横幅100%」の一択です。

## 設定方法

現在、作成しています。お待ちください。   

### 参考
[a-blog cmsのデータをブログ単位でインポートする](https://developer.a-blogcms.jp/document/datamanagement/blogImport.html)
 
 