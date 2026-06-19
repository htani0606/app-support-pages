# 顔ぼかし動画カメラ App Store 用テキスト

## App Information

- App name: 顔ぼかし動画カメラ
- Bundle ID: com.htani.BlurMovie
- Support URL: https://htani0606.github.io/app-support-pages/face-blur-video-camera/support.html
- Privacy Policy URL: https://htani0606.github.io/app-support-pages/face-blur-video-camera/privacy.html
- Contact: tani@ymail.ne.jp
- Primary category suggestion: Photo & Video
- Secondary category suggestion: Utilities
- Age rating suggestion: 4+

## Subtitle

撮影時に顔を自動でぼかす

## Promotional Text

後から編集しなくても、撮影しながら顔をぼかせる動画カメラ。バンド練習、イベント、SNS用動画などに。

## Description

顔ぼかし動画カメラは、人の顔をリアルタイムでぼかしながら動画を撮影できるシンプルなカメラアプリです。

練習風景、イベント、作業記録、SNS投稿用の動画など、あとから顔を隠す編集が面倒な場面で使えます。カメラを向けて撮るだけで、検出した顔に自動でぼかしをかけながら録画します。

ぼかしの強さは撮影前に調整できます。顔の数や録画状態も画面上で確認できるため、必要な設定だけを素早く整えて撮影できます。

撮影した動画は、ぼかし処理済みの状態で写真ライブラリに保存されます。動画編集アプリを開いて、あとから一人ずつ顔を隠す手間を減らせます。

主な機能:
- 顔を検出してリアルタイムにぼかし
- 動画撮影と音声録音
- ぼかし強度の調整
- 前面/背面カメラ切り替え
- 録画開始/停止の音と触覚フィードバック
- 撮影した動画を写真ライブラリへ保存
- 無料版は録画時間5分まで

顔が完全に隠れることを保証するものではありません。暗い場所、横顔、顔が大きく隠れている場合などは検出できないことがあります。公開前には保存された動画をご確認ください。

## Keywords

顔ぼかし,モザイク,動画,カメラ,顔隠し,プライバシー,SNS,撮影,ビデオ,ぼかし,匿名,編集,ライブ,バンド,練習

## What's New

顔ぼかし動画カメラを公開しました。撮影しながら顔を自動でぼかし、ぼかし済み動画を写真ライブラリに保存できます。

## Review Notes

このアプリはアカウント登録なしで利用できます。
カメラとマイクを許可すると、顔をぼかしながら動画を撮影できます。
撮影した動画は写真ライブラリに保存されます。
広告表示には Google AdMob を使用しています。
無料版では録画時間が5分までに制限されています。

## App Review Reply - Face Data

Hello,

Thank you for reviewing 顔ぼかし動画カメラ. Below are the details about how the app handles face data.

1. What face data does the app collect?

The app does not collect face data. The app uses Apple's on-device Vision framework to detect face rectangles in the live camera frames only for the purpose of applying a blur effect. The temporary detection result is limited to face position/bounding-box information within the current video frame.

The app does not collect, store, or upload face images, facial recognition templates, faceprints, biometric identifiers, or facial feature vectors.

2. Planned uses of the face data

The temporary on-device face position information is used only to determine where to apply the blur effect while recording video. It is not used for face recognition, user identification, authentication, profiling, analytics, advertising targeting, or any other purpose.

3. Sharing and storage

Face data is not shared with any third parties. Face detection and blur processing are performed on the user's device. The app does not send video, audio, face images, face position information, or face detection results to our servers or to third parties.

The processed video, with the blur already applied, is saved only to the user's Photos library when the user chooses to record and save a video.

4. Retention

Face position information is used temporarily during live frame processing and is not retained after processing. The app does not store face data, face images, face templates, or face detection results.

5. Privacy policy sections

The face data handling is explained in the privacy policy under the following sections:

- 「動画・音声の処理と保存場所」
- 「顔データについて」
- 「第三者提供」

Privacy Policy URL:
https://htani0606.github.io/app-support-pages/face-blur-video-camera/privacy.html

6. Specific text from the privacy policy concerning face data

「顔検出とぼかし処理は、原則としてユーザーの端末内で行われます。撮影した動画はユーザーの写真ライブラリに保存されます。アプリ独自のサーバーへ、撮影した動画、音声、顔情報を送信することはありません。」

「本アプリは、顔をぼかすために端末内で顔の位置を検出します。検出される情報は、録画中の映像フレーム内における顔の位置情報のみで、本人確認、顔認証、個人の識別、プロフィール作成、分析、広告ターゲティングには使用しません。」

「顔の位置情報は、ぼかし処理を行うために一時的に利用され、アプリ独自のサーバーや第三者へ送信されません。顔の位置情報、顔画像、顔認証テンプレート、顔の特徴量データをアプリ内に保存することはなく、録画処理中の一時利用後に保持されません。」

「法令に基づく場合を除き、アプリ独自に取得した動画、音声、顔検出結果を第三者へ提供することはありません。ただし、広告配信に関する情報は Google AdMob SDK により Google に送信される場合があります。」

## App Privacy Draft

App Store Connect の回答時のたたき台です。最終回答は、AdMob の設定と Apple の画面上の選択肢に合わせて確認してください。

- アプリ独自のアカウント作成: なし
- アプリ独自サーバーへの動画、音声、顔情報の送信: なし
- カメラ: 顔検出と動画撮影のために使用
- マイク: 動画への音声録音のために使用
- 写真ライブラリ追加: 撮影した動画の保存のために使用
- 端末内保存: 撮影動画、設定、レビュー依頼や広告表示に関する軽量なカウンタ
- 第三者SDK: Google AdMob / Google User Messaging Platform
- Tracking: App Tracking Transparency に基づくトラッキング許可は求めない
- Data Linked to You: アプリ独自では収集なし
- Data Not Linked to You: 広告関連情報、使用状況データ、診断情報など AdMob SDK の実態に応じて確認
- User Content: アプリ独自サーバーへ動画・音声を送信しないため、アプリ独自の収集対象としてはなし

## Export Compliance Draft

独自の暗号化機能は実装していません。標準的なOS/SDK通信以外の非免除暗号化を使っていない前提です。

## Screenshot Notes

推奨スクリーンショット:
- 縦画面の撮影画面、顔ぼかしがかかった状態
- ぼかし強度スライダーと録画ボタンが見える画面
- 横画面撮影の例
- 保存完了または撮影後の導線が分かる画面
