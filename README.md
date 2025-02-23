# VlockVRise

VlockVRiseは、Meta Questシリーズ用に作成したVR版テトリスライクゲームです。
従来のテトリスゲームをVR空間でプレイすることが可能であり、インタラクティブなミノ（ブロック）の操作が可能です。
また、本アプリケーションは大学院の研究で用いるユーザスタディ用アプリケーションとして作成しました。
本リポジトリは、アプリの動作確認や技術的な理解の支援、共有のために作成、公開されています。

## 公開方法
このアプリケーションは以下の二つの方法で提供されております。

### ① APK ファイルとして提供（実行形式）
Meta Questシリーズに直接インストールして動作確認が可能なAPKファイルを提供します。
#### APKダウンロード

#### インストール手順
1. PC側でSideQuest をインストール
2. MetaQuestシリーズをPCに接続し、開発者モードを有効化
3. SideQuest で APK を Quest に転送
4. Quest の 「不明なソース」 からアプリを実行

### ② Unity パッケージ（必要Assetのみ）として提供
本プロジェクトの主要なシーンおよび関連するScriptなどのコンポーネントのみを Unity パッケージ（.unitypackage） として提供します。
この方法では、Meta XR SDK やその他の外部ライブラリを含めずに、VlockVRise のコア部分のみを共有します。
そのため、Unityエディタでのアプリカスタマイズが可能ですが、いくつかのSDKやコンポーネントを別途インポートする必要があります。

#### Unity パッケージのダウンロード

#### インストール手順（Unity で開く場合）
1. Unity 2021.3 LTS 以上をインストール(本プロジェクトはUnity 2021.3.25f1を使用し作成)
2. Meta XR SDK や XR Plug-in Management など、MetaQuestアプリ開発に必要なパッケージを導入し、環境構築
   - 詳しい環境構築の仕方はこちらのサイトを参考 https://tech.framesynthesis.co.jp/unity/metaquest/
4. File > Import Package > Custom Package から XX.unitypackage をインポート


