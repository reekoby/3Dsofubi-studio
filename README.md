# SOFVI STUDIO

テキストや画像からの3D生成、既存モデルの読み込み、サイズ・向きの調整、局所的なメッシュ修復、STL出力を支援するWindows向けローカルアプリです。

## 最新の配布版

[SOFVI STUDIO 0.16.2（未署名・手動更新版）](https://github.com/reekoby/3Dsofubi-studio/releases/tag/v0.16.2)を公開しています。正式署名付きの製品版は準備中です。

- [Windowsインストーラー](https://github.com/reekoby/3Dsofubi-studio/releases/download/v0.16.2/SOFVI-STUDIO-0.16.2-Setup.exe)
- [日本語の更新手順](https://github.com/reekoby/3Dsofubi-studio/releases/download/v0.16.2/RELEASE-NOTES.md)
- [SHA256チェックサム](https://github.com/reekoby/3Dsofubi-studio/releases/download/v0.16.2/SHA256SUMS.txt)

アプリの「アプリの更新」からReleaseを確認し、サイズ・SHA256を照合して保存できます。保存後はアプリを終了し、Setupを実行してください。初回の移行では上記インストーラーを直接保存して実行します。同じ版は再導入用として保存できます。

既存と同じデータ保存先を指定すると、プロジェクト・バックアップを保持します。更新前にバックアップを作成し、ファイル置換に失敗した場合は旧版を復旧します。更新前バックアップとアプリの展開・退避に必要な空き容量を確保してください。

## 署名について

本版は正式なWindowsコード署名がありません。ダウンロードしたEXEを自動実行しません。SHA256照合は破損確認用であり、同じ配布先のチェックサムだけでは発行元の真正性を保証しません。

署名付き自動更新の利用には、コード署名済みEXE、署名付き更新情報、発行者証明書と公開鍵を固定した信頼設定が必要です。本版で未署名の自動適用を許可する設定は提供しません。

## このリポジトリについて

配布専用です。アプリのソースコード、APIキー、利用者の制作プロジェクト、モデル、バックアップ、秘密鍵は公開しません。オープンソース化を意味しません。

STLは色・テクスチャを保持しません。色付きモデルはGLBも併せて保存してください。3D生成APIの利用には別途APIキーと利用料が必要です。

公式サイト：[antrec.ai](https://antrec.ai)
