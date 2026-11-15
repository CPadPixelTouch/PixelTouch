# 重要なお知らせ

> [!IMPORTANT]
> v3 をもちまして、サポート終了（EOS）とさせていただきます。  
> 認証システムが同梱されている v2 をご利用の方は、OTA アップデートを必ずおこなってください。

# PixelTouch v3.0.0 Release（EOS）

<img alt="PixelTouch ロゴ" src="https://pixeltouch.org/src/Material/PixelTouch-logo-TM.png" width="40%">
<img alt="PixelTouch 対応デバイス" src="https://pixeltouch.org/src/Device.png" width="45%">

## リリース情報

PixelTouch v3.0.0は、2026年11月15日のサービス終了に伴う最終バージョンです。
認証機能やOTA機能の削除と、各種不具合の修正を行いました。

詳しくは **[ホームページ](https://pixeltouch.org/download/)** をご覧ください。

## 変更点

- v2.0.0から導入された認証機能を削除
- TeamPixelTouchに関する内容を削除
- OTA機能を削除
- QSパネルにGoogle Turboのバッテリー予測が表示されなかった問題を修正
- 設定のホームアクティビティからデバイス情報にアクセスできるように修正
- 設定のホームにサジェストカードが表示されなかった問題を修正
- 設定から天気の華氏・摂氏を切り替えられるように修正
- 設定で自動バッテリーの機能が使えなかった問題を修正
- 設定でアプリの検索が使えなかったため、検索機能を追加

> [!NOTE]
> v3.0.0では、PixelTouchの認証用にGoogleアカウントとシリアルナンバーを連携する必要はありません。
> また、OTA機能を削除しているため、v3.0.0導入後はOTAアップデートを利用できません。

> [!IMPORTANT]
> **インストールは、バッテリー残量が100%の状態で行ってください。**
>
> **新規インストールでは現在のデータがすべて消えます。大切なデータは、必ず事前にバックアップしてください。**
> バックアップ方法はご自身で調べ、作業前に実施してください。
>
> 未成年の方は、保護者の許可を得てから作業してください。

## 導入方法

**[Zennの導入ガイド](https://zenn.dev/minekura_1001/articles/0d37e5f877ace6)** をご覧ください。

導入・改造の前に、**[利用上の規則](https://pixeltouch.org/terms/)** もご確認ください。

## 署名ツール（PixelTouchSignTools.zip）

**PixelTouch用の署名鍵と、APK・OTAアップデートZIPの署名ツールをまとめたものです。**
Windows PCと、`java`コマンドを実行できるJava環境が必要です。

ZIPを展開し、署名したいファイルを対応するバッチファイルへドラッグ＆ドロップしてください。

- **APKの署名：** `PixelTouch_sign_apk.bat`
- **OTAの署名：** `PixelTouch_sign_ota.bat`

詳しい使い方は、同梱の **README.txt** をご覧ください。
