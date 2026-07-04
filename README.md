# 概要
- 本リポジトリはtitan823氏のti版GeminiPWA( https://github.com/titan823/geminipwa )をフォークし、TTS(音声読み上げ)機能を追加した私用の派生版です
- 系譜: 本家ona-oni/geminipwa→titan823/geminipwa→本リポジトリ
- ここではTTS機能に関する説明のみ記しておきますので、経緯やその他の全機能の詳細はフォーク元のREADMEを参照してください

## ■ 経緯
元々はどうにか簡単にTTSサーバーを使えないかと思ってノートブックを作っていたのが始まりで、SillyTavernを用意できない人はどうする？と考えた結果、個人的に愛用していたtitan版でのPWA制作を思い立ちました

## ■ 利用方法(PWA)
- 当PWAも例にもれずブラウザから以下のURLにて利用可能です:
https://aide0721.github.io/geminipwa/#chat

- TTSサーバーはどうすれば？って人はこちらをどうぞ:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aide0721/geminipwa/blob/main/colab.ipynb)

# 追加機能: TTS
- エンドポイントURL、モデル、ボイスなどを設定してサーバーに音声リクエストをします
- 使い方: 音声読み上げ機能にチェックを入れるとチャットにボタンが追加され、それを押すと指定されたボイスで読み上げます

# 注意事項
- 本PWAを初めてのデバイスから使用する場合は、必ず無料モデルを用いて必要最低限の機能構成からテストしてください。
- 当フォークはデバッグを十分に行ったとは言えず、うまく動作しなかったり、不具合が発生する場合があります。積極的にサポートをする予定はなく、また予告なく削除する可能性もあるのでご了承ください。
- PWA使用中に解決困難な問題が生じた場合は本PWAに関するキャッシュを全て削除することを推奨致します。
- 各種データは必ず各ユーザー様のご裁量で保存を行なってください。当アプリはアプリ内での恒久的なデータ保存や自動バックアップは意図されておりません。
- 本コードは本家(ona-oni/geminipwa)ないしフォーク元(titan823/geminipwa)の後継となることを意図するものでは断じてございません。すべての系譜のフォーク元コードに対し異を唱える意図も、開発を阻害する意図なども一切ございません。
- 本家またはフォーク元コードの製作者様を除き、ご質問・ご意見・ご要望は承りません。また、本コードによって損害や影響が生じた場合においても、公開陣は一切の責任を負いません。
- 本コードの利用基準(コードの改変、コードのフォーク、他コードへのコード流用など)、本コードのフォーク元の基準に準拠致します。(ITライセンス)

## ■ Dependencies
This project uses the following third-party libraries:

*   **Marked.js:** [MIT License](https://github.com/markedjs/marked/blob/master/LICENSE.md) - Used for rendering Markdown.