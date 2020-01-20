# outline

1. WPFにおけるリソースの説明
    * リソースの種類
        * 文言
        * 画像
        * other
    * リソースの持ち方
        * 文言
            * resxファイル
                * 実態はXMLファイル
            * other
        * 画像
            * Resourceフォルダ
            * other
1. 文言リソース
    * resxファイルを用いたアプリの国際化の手法について
        1. Resource.resxの編集
        1. ローカライズする言語のResource.resxの追加
            * 命名規則
        1. App.xamlへのResourceの登録（プログラム全体で使える）
        1. 登録したリソースの利用
            * xamlからのアクセス（マークアップ拡張）
            * コードからのアクセス
    * resxファイル参照の仕組み
        1. 実行環境の言語リソース探す
            * なければ、デフォルト言語リソースを使う
        1. 指定されたID探す
            * なければ、デフォルト言語リソースを探しに行く
1. 画像リソース
    画像の表示にはImageコントロールを利用する
    https://docs.microsoft.com/ja-jp/dotnet/api/system.windows.controls.image?view=netframework-4.8
    1. Resourceフォルダを使う方法
    https://aitos.jp/blogs/ito/?p=119
        1. Resourceフォルダへの登録
            * VS上でビルドアクション？をいじる
        1. App.xamlへのResourceの登録（WindowのXamlへの登録でもよい）
        1. 登録したリソースの利用
            * xamlからのアクセス
                * StaticResourceとDynamicResourceの違い
            * コードからのアクセス
    1. Dllにする方法

    1. resxファイルへ登録する方法

