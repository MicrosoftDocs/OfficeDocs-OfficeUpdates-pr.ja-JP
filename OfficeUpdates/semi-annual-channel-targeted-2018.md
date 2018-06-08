---
title: 2018 年の半期チャネル (対象指定) リリースのリリース ノート
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 5/18/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の 2018 年の半期チャネル (対象指定) リリースのリリース ノートを IT プロフェッショナルに提供します
ms.openlocfilehash: 7e4a881b7981ecd23d9771a5d1f375f4cf07eba7
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/04/2018
ms.locfileid: "19556213"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2018"></a>2018 年の半期チャネル (対象指定) リリースのリリース ノート

これらのリリース ノートでは、Office 365 ProPlus 用の 2018 年の半期チャネル (対象指定) の更新プログラムに含まれる新機能、セキュリティ更新プログラム、セキュリティ以外の更新プログラムに関する情報を提供しています。
 
> [!NOTE]
> - また、Visio Pro for Office 365 および Project Online デスクトップ クライアントの新機能、セキュリティ更新プログラム、セキュリティ以外の更新プログラムについても説明しています。
> - ここに記載されている情報は、Business Premium など一部の Office 365 プランに付属する Office のバージョンの、Office 365 Business にも該当します。

## <a name="version-1803-may-18"></a>バージョン 1803: 5 月 18 日
*バージョン 1803 (ビルド 9126.2210)*

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
- グラフの操作によって Excel がクラッシュする問題を修正します。
- 一部のユーザーに対し、Power View のアドインが誤って無効になるの問題を修正します。
- ドキュメントの回復中に作成された一時的な自動回復ファイルがクリーンアップされないという問題を修正します。
- 保護されたブックでテキスト ファイルに新しい接続を作成しようとすると、「ブックは保護されており、変更できません」というエラー メッセージが出るという問題を修正します。

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
- 図形内でスペルを修正すると PowerPoint がクラッシュする問題を修正します。

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
- ユーザーがアプリケーションを開いたときに、セーフ モードでの起動に関するメッセージが表示され、アプリケーションが起動しない問題を修正します。



## <a name="version-1803-may-8"></a>バージョン 1803: 5 月 8 日
*バージョン 1803 (ビルド 9126.2191)*

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8147): Microsoft Excel のリモート コード実行の脆弱性
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8148): Microsoft Excel のリモート コード実行の脆弱性
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8162): Microsoft Excel のリモート コード実行の脆弱性
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8163): Microsoft Excel の情報漏えいの脆弱性

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   SharePoint Online からファイルを開くと Excel がクラッシュする問題を修正します。
-   印刷または印刷プレビューで、ワークシートの一部だけが印刷または表示され、ワークシート上のスライサーでコンテンツが切り詰められる問題を修正します。

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook のセキュリティ機能のバイパスの脆弱性

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   [送信トレイ] または [送信済みアイテム] フォルダーに切り替えると、Outlook がクラッシュする問題を修正します。
-   会議の本文や添付ファイルを変更すると、会議の更新情報の出席者への送信がオプションになる代わりに、すべての出席者が会議の更新を受信する問題を修正します。
-   ユーザー エージェント文字列が変更されたために、ユーザーが EWS エンドポイントおよび REST エンドポイントに接続できなくなる問題を修正します。

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   SharePoint Online からファイルを開くと PowerPoint がクラッシュする問題を修正します。
-   自動保存が有効な場合に回復ウィンドウが誤って表示される問題を修正します。
-   サインインが表示されないためにユーザーがファイルにアクセスできない問題を修正します。

### <a name="project-non-security-updates"></a>Project: セキュリティ以外の更新プログラム
-   日付列のオートフィルター ドロップダウンを使用すると、プロジェクト内のすべてのタスクが非表示になる問題を修正します。
-   タイムライン ビューで既存のタスクをタイムラインに追加すると、最初のサマリー タスクのタスクのみがダイアログ ボックスに表示される問題を修正します。

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   SharePoint Online からファイルを開くと Word がクラッシュする問題を修正します。
-   小文字のローマ数字ページ番号が誤って大文字に変更される問題を修正します。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8157): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8158): Microsoft Office のリモート コード実行の脆弱性



## <a name="version-1803-april-10"></a>バージョン 1803: 4 月 10 日
*バージョン 1803 (ビルド 9126.2152)*

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1029): Microsoft Excel のリモート コード実行の脆弱性

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   複数のユーザーが同じプレゼンテーションを共同編集すると、スライド マスターに正しくない重複が発生する問題を修正します。
-   OneDrive に保存されているファイルを開いた際、保護ビューを終了すると PowerPoint がクラッシュする問題を修正します。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   TLS 1.2 サポートに関連する問題を修正します。

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   メモリ不足を示すメッセージが表示される原因となる問題を修正します。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0950): Microsoft Office の情報漏えいの脆弱性
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1026): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1030): Microsoft Office のリモート コード実行の脆弱性



## <a name="version-1803-march-20"></a>バージョン 1803: 3 月 20 日
*バージョン 1803 (ビルド 9126.2098)*

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   Outlook メールに添付された Excel ブックのクイック印刷が機能しない問題を修正します。
-   ハイパーリンクをクリックすると Excel がクラッシュする問題を修正します。
-   キューブ関数を使用すると、Excel がクラッシュする問題を修正します。

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: セキュリティ以外の更新プログラム
-   延長期間にタスク マネージャーで OneDrive for Business (Groove.exe) が 1 つの CPU コアの CPU の価値を消費する (4 コア CPU の 25% など) 問題を修正します。

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   出席者に対する会議場所の更新に、新しい場所ではなく、古い場所が表示される問題を修正します。
-   ユーザーが閲覧ウィンドウで添付ファイルをプレビューすると、エラーが表示される問題を修正します。
-   ユーザーが電子メールを作成中に、表示名が電子メール アドレスに解決されると、Outlook がクラッシュする問題を修正します。
-   一部のユーザーがテナント管理者によって有効にされたサポート機能を受信しない問題を修正します。

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   カスタマ－ エクスペリエンスと診断テレメトリに関する更新プログラムがインストールされていない、Windows 7 を [実行しているコンピューターで Word が開かない問題を](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)修正します。
-   リスト内の行頭文字が印刷されない問題を修正します。



## <a name="version-1803-march-13"></a>バージョン 1803: 3 月 13 日
*バージョン 1803 (ビルド 9126.2072)*

### <a name="access-security-updates"></a>Access: セキュリティ更新プログラム
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0903): Microsoft Access のリモート コード実行の脆弱性

### <a name="access-non-security-updates"></a>Access: セキュリティ以外の更新プログラム
-   Access ランタイム アプリケーション (.accde ファイル) を開くと、"データベースの形式を認識できません" というエラー メッセージが表示され、アプリケーションが開かない問題を修正します。
-   テキスト ボックスまたはコンボ ボックスでテキストを選択しようとすると、指示されたものが選択されるのではなく、すべてのテキストが選択されるという問題を修正します。

### <a name="excel-feature-updates"></a>Excel: 機能の更新
-   **Microsoft Translator:** Microsoft Translator を使用して、単語、フレーズ、または文章を別の言語に翻訳します。これは、リボンの [校閲] タブから実行できます。
-   **SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。
-   **セルを選択解除する:** ワークシートで選択を行い、間違ってクリックしたセルを選択解除します。最初からやり直す必要はありません。
-   **サイトおよびグループへすばやくアクセス:**[ファイル] メニューを使用して、よく使用するサイトやグループに格納されているドキュメントを操作できます。
-   **デジタル鉛筆:** 新しい鉛筆のテクスチャで、アイデアを書き込んだり、スケッチしたりします。サポートされているデジタル ペンを傾けるだけで網かけができます。
-   **LinkedIn 機能の設定:** [ファイル] \> [オプション] \> [全般] と移動して、Office アプリケーションで LinkedIn 機能が表示されるかどうかを制御します。[詳細情報](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D モデル:** 3D を使用して、ブックを、より視覚的かつ独創的なものにすることができます。3D モデルの挿入も簡単で、360 度回転させることができます。 [詳細情報](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新しいインク効果:** メタリック ペンを使用し、ゴールド、シルバーあるいは虹、銀河、溶岩、海などを連想させる色などのインクの効果を活用して、アイデアの表現の幅を広めましょう。
-   **ファイル共有 UI:** OneDrive for Business または SharePoint のファイルの場合、リボンの右上隅にある [共有] ボタンをクリック、または [ファイル] \> [共有] の順に移動することにより、簡略化され改良された [共有] ダイアログが起動されます。新規のファイル、またはローカルに保存されたファイルの場合、この UI によって、ユーザーはファイルを OneDrive に簡単にアップロードし、共同作業を開始できます。
-   **危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。
-   **アクセシビリティを向上させるのに役に立つサウンド:** 音声キューを有効にすると、作業中に操作を指示してもらうことができます。[ファイル] \> [オプション] \> [簡単操作] の順に選択すると見つかります。アドインは必要ありません。 [詳細情報](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **アカウントごとのファイルの場所:** ファイルを開くときや保存する場合、場所のリストは、その場所に関連付けられたアカウントによって整理されます。
-   **ペンのカスタマイズ:** 手描き入力についてペンと蛍光ペンの個人用設定を選択します。カスタマイズした設定は、お使いのすべての Windows PC でご利用いただけます。

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11877): Microsoft Excel のセキュリティ機能のバイパスの脆弱性
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11878): Microsoft Excel のメモリ破損の脆弱性
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11884): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0796): Microsoft Excel のリモート コード実行の脆弱性
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0841): Microsoft Excel のリモート コード実行の脆弱性
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel のセキュリティ機能のバイパス
-   [アドバイザリ 170021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170021): Microsoft Office 多層防御の更新プログラム

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   Excel で、編集の言語が日本語、中国語、韓国語のいずれかの場合に、[ホーム] タブで新しいフォントを選ぼうとしたり、編集したりするときにフリーズするという問題を修正します。
-   Excel が最小化されているときにブックを開くとスクロールバーが表示されない問題を修正します。
-   ファイル エクスプローラーでファイル名をダブルクリックして複数のブックを開くときに、ブックの参照が失敗する問題を修正します。
-   ピボットテーブルのプログラムによる作成の後にプログラムによる更新が行われると、Excel がクラッシュする問題を修正します。
-   プログラムで Workbook.Open() を呼び出すと、Excel がクラッシュする可能性がある問題を修正します。
-   ユーザーが、マクロを含む Office 2007 以前のブック (.xls または .xla) を開くと、"致命的なエラー" のエラー メッセージが誤って表示される問題を修正します。
-   ユーザーがコンテキスト メニューを開くときに Excel がクラッシュする可能性がある問題を修正します。
-   ユーザーが既存のブックにオブジェクトを挿入しようとする場合に [参照] をクリックすると、Excel がクラッシュするという問題を修正します。
-   範囲をパスワードで保護している場合に、範囲のロックを解除するパスワードを入力するダイアログ ボックスが表示されない問題を修正します。
-   ファイル名に角かっこが含まれている場合に、ユーザーが保護ビューでブックを閉じることができない問題を修正します。
-   ドラッグまたはドラッグ フィルを実行するとヒントの配置がずれる問題を修正します。
-   [ファイル] \> [名前をつけて保存] を使用してブックを保存するときに、ピリオドを含むファイル名がファイル保存ダイアログで空白になるか切り詰められて見える問題を修正します。
-   同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。

### <a name="outlook-feature-updates"></a>Outlook: 機能の更新
-   **簡単にメールを並べ替える:** フィードバックにお答えし、メッセージ一覧の上に並べ替えを戻し、優先受信トレイを使用していないユーザーのために未読フィルターを戻しました。
-   **SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。
-   **Office 365 グループの機能強化:** グループ メッセージをダブルクリックして、独自のウィンドウで開くことができるので、これまで以上にグループ会話を読んで返信することが簡単になりました。
-   **LinkedIn 機能の設定:** [ファイル] \> [オプション] \> [全般] と移動して、Office アプリケーションで LinkedIn 機能が表示されるかどうかを制御します。[詳細情報](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D モデル:** 3D を使用して、電子メールを、より視覚的かつ独創的なものにすることができます。3D モデルの挿入も簡単で、360 度回転させることができます。 [詳細情報](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **プロファイル カード:** デスクトップ、Web、モバイル アプリのいずれかを使用している場合でも、ユーザーとグループに関する最も関連性の高い詳細を表示します。
-   **グループ予定表への予定の追加:** グループ内のメンバー全員に、メールで会議を送信せずに、会議の欠席について知らせることができます。
-   **クラウド添付ファイルのダウンロード:** OneDrive の添付ファイルをコンピューターに保存またはドラッグ アンド ドロップすると、ファイルがダウンロードされます。
-   **アクセシビリティを向上させるのに役に立つサウンド:** 音声キューを有効にすると、作業中に操作を指示してもらうことができます。[ファイル] \> [オプション] \> [簡単操作] の順に選択すると見つかります。アドインは必要ありません。 [詳細情報](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **優先受信トレイ:** 受信トレイは、[優先] と [その他] の 2 つのタブに分かれています。メッセージの分類は、メッセージの内容と、一番やりとりの多い相手がだれかに基づいて行われます。 [詳細情報](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **最も頻繁に使用するグループにすばやくアクセスする:** 一番やりとりの多いグループが、[フォルダー] ウィンドウの [グループ] のリストの先頭に表示されるようになりました。

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11939): Microsoft Office の情報漏えいの脆弱性
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook のリモート コード実行の脆弱性
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook 特権の昇格の脆弱性
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook のメモリ破損の脆弱性

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   検索範囲がすべてのメールボックスの場合、「一致する項目が見つかりませんでした」と表示されて検索できない問題を修正します。
-   Accessible Event Watcher (AccEvent.exe) を使用して監視する場合に、フォルダーを切り替えたときに Outlook がクラッシュする問題を修正します。

### <a name="powerpoint-feature-updates"></a>PowerPoint: 機能の更新
-   **Microsoft Translator:** Microsoft Translator を使用して、単語、フレーズ、または文章を別の言語に翻訳します。これは、リボンの [校閲] タブから実行できます。
-   **3D アニメーション:** 優しく揺らしたり、ジャンプして回転させたりするなど、アニメーションを使用して 3D モデルを生き生きとしたものにできます。
-   **SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。
-   **リビジョン進捗管理情報のローミング:** 他のユーザーによって変更された共有スライドを強調表示するための既読/未読のステータスは、この情報を複数のデバイスまたはプラットフォームで同期できるように、ローミング サービス (ユーザーのローカル コンピューターではない) に保存されるようになりました。
-   **サイトおよびグループへすばやくアクセス:**[ファイル] メニューを使用して、よく使用するサイトやグループに格納されているドキュメントを操作できます。
-   **デジタル鉛筆:** 新しい鉛筆のテクスチャで、アイデアを書き込んだり、スケッチしたりします。サポートされているデジタル ペンを傾けるだけで網かけができます。
-   **LinkedIn 機能の設定:** [ファイル] \> [オプション] \> [全般] と移動して、Office アプリケーションで LinkedIn 機能が表示されるかどうかを制御します。[詳細情報](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **デジタル ペンを使用してスライド ショーを実行します:** Surface ペン、または Bluetooth ボタンのあるその他のペンを使用し、高度なスライドを作成しましょう。Windows 10 Fall Creators Update が必要です。 [詳細情報](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **3D モデル:** 3D を使用して、プレゼンテーションを、より視覚的かつ独創的なものにすることができます。スライド間で映画のようなアニメーションを生み出す画面切り替え効果を生かして、3D モデルをプレゼンテーションで活用しましょう。 [詳細情報](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新しいインク効果:** メタリック ペンを使用し、ゴールド、シルバーあるいは虹、銀河、溶岩、海などを連想させる色などのインクの効果を活用して、アイデアの表現の幅を広めましょう。
-   **ファイル共有 UI:** OneDrive for Business または SharePoint のファイルの場合、リボンの右上隅にある [共有] ボタンをクリック、または [ファイル] \> [共有] の順に移動することにより、簡略化され改良された [共有] ダイアログが起動されます。新規のファイル、またはローカルに保存されたファイルの場合、この UI によって、ユーザーはファイルを OneDrive に簡単にアップロードし、共同作業を開始できます。
-   **危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。
-   **リビジョンの強調表示:** 他のユーザーによって変更されたスライドが強調表示されます。
-   **最近の変更:** PowerPoint は、共有のプレゼンテーションへの前回のアクセス以降、だれが編集したか表示されるようになりました。
-   **デザイナーの機能強化:** デザイナーで、タイムラインのお勧めのデザイン アイデアが箇条書きで提案されるようになりました。
-   **アクセシビリティを向上させるのに役に立つサウンド:** 音声キューを有効にすると、作業中に操作を指示してもらうことができます。[ファイル] \> [オプション] \> [簡単操作] の順に選択すると見つかります。アドインは必要ありません。 [詳細情報](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **アカウントごとのファイルの場所:** ファイルを開くときや保存する場合、場所のリストは、その場所に関連付けられたアカウントによって整理されます。
-   **ペンのカスタマイズ:** 手描き入力についてペンと蛍光ペンの個人用設定を選択します。カスタマイズした設定は、お使いのすべての Windows PC でご利用いただけます。
-   **デザイナーの機能強化:** デザイナーが、スライドに追加されたグラフのデザイン アイデアを提案するようになりました。
-   **QuickStarter:** アウトラインを自動的に作成し、ユーザーの選択対象に対して調査を開始できるようにします。[詳細情報](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **デジタル ルーラー:** タッチ スクリーンを備えたデバイスで、[描画] \> [ルーラー] の順に移動し、ペンや指で直線を描画したり、オブジェクトのセットを配置したりできます。 [詳細情報](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint: セキュリティ更新プログラム
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint の情報漏えいの脆弱性

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   ドキュメント プロパティと個人情報を削除すると、SharePoint への保存が失敗する問題を修正します。
-   Flash Player ベースの YouTube 埋め込みコードを参照すると、新しいウィンドウが開いて動画が再生される問題を修正します。現在、古い埋め込みコードは HTML5 ベースの YouTube 動画を参照するようにアップグレードされており、正しく再生されます。
-   同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。

### <a name="project-feature-updates"></a>Project: 機能の更新
-   **タスク ボード ビュー:** タスク ボード ビューでカードのタスクを並べ替えます。アジャイル プロジェクトと同様に、カードを並べ替え、ボード上の列の間で移動させます。
-   **アジャイル プロジェクト:** バックログ、タスク ボード、スプリントなどを使用して、アジャイル プロジェクトを管理します。スクラムまたはかんばんの両方の方法論がサポートされています。[詳細情報](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Planner でのタスクの管理:** Planner にプロジェクト タスクをリンクし、計画を作成します。タスクをサブタスクに分割し、チームを追加し、タスクを割り当て、タスク ボード上で作業を管理します。

### <a name="project-non-security-updates"></a>Project: セキュリティ以外の更新プログラム
-   あるセッションで複数のベースラインを設定すると、MOD\_DATE の値が同じになるという問題を修正します。
-   [共有用に保存] セッションで実績作業時間が削除された後にも、実績作業時間がレポート テーブルに表示されるという問題を修正します。
-   スケジュール設定するときに週の日付形式を使用するとエラーが返されるというドイツ語での問題を修正します。
-   スケジュール Web パーツで終了日を編集すると、タスクが時間範囲で配分されるのではなく、1 日に 8 時間ずつ割り当てられるという問題を修正します。
-   "進捗点の形状" が予期しない場所に描画されるという問題を修正します。
-   VBA コードがプロジェクトから失われる問題を修正します。
-   残存作業時間がある場合でも、タスクが終了と表示される問題を修正します。
-   タスク パス機能を使用しているときに Project が停止する問題を修正します。
-   タイムスケールにタイムスケールのラベルが表示されない問題を修正します。
-   ビジュアル レポートが不完全な情報を表示するか、完全に失敗する問題を修正します。
-   保存に失敗するとファイルが破損して Project を開くときにクラッシュする問題を修正します。
-   タイムラインとチーム プランナー ビューでタスクをドラッグできない問題を修正します。
-   Team Builder でリソースの可用性が表示されない問題を修正します。
-   マークが正しく表示されない問題を修正します。
-   時間単位または日単位で平準化している間に Project が停止する問題を修正します。
-   SharePoint ドキュメント ライブラリからマスター/サブ プロジェクトを操作する際の問題を修正します。
-   期間固定のタスクに割り当てを追加したときに、名前のないリソースになる可能性がある問題を修正します。
-   保護された作業での変更について、誤ったエラー メッセージが生成される問題を修正します。
-   いくつかの画像を含むレポートに移動すると Project がクラッシュする可能性がある問題を修正します。

### <a name="publisher-feature-updates"></a>Publisher: 機能の更新
-   **危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。

### <a name="publisher-non-security-updates"></a>Publisher: セキュリティ以外の更新プログラム
-   差し込み印刷ウィザードを実行しているときに、Null (空) 値を含むデータ ソース フィールドでのフィルター処理が失敗する問題を修正します。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   会議で [Skype 通話] を選択してユーザーを追加するとエラーが発生する問題を修正します。
-   Skype Room が場所として追加され、会議に既にチーム会議の座標が含まれている場合、会議に Skype 座標を追加するかどうかを確認するユーザー プロンプトを削除します。
-   UseLocationForE911Only が true に設定されている場合でも、場所が設定されるという問題を修正します。
-   "会議センターを使用して通話する" オプションを使用して参加者一覧にあるユーザーを招待する際に、Skype for Business が停止する問題を修正します。
-   Skype for Business 会議の作成中に、ターミナル サーバー上で動作している Outlook がフリーズする問題を修正します。
-   EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket の既定値を TRUE に変更します。
-   会議が全画面表示モードの場合に [その他のオプション] ボタンと [さらに参加者を招待] ボタンが非表示になる問題を修正します。
-   P2P 音声通話ウィンドウまたは電話会議ウィンドウが、参加しようとすると透明になるという問題を修正します。
-   近日開催される Skype 会議が [会議] タブに表示されない問題を修正します。
-   Skype for Business が音声なしの状態で会議に参加するよう構成されている場合、会議に音声を追加しようとすると、既存の会議に音声が追加されるのではなく、自分自身への新たな P2P 通話が開始される問題を修正します。
-   Outlook から会議出席依頼の [Skype 会議への参加] リンクをクリックすると、「この Skype 会議が見つかりませんでした」というエラー メッセージが表示される問題を修正します。
-   着信の PSTN 呼び出しのトースト UI に通話の転送ボタンを追加します。
-   ChatDefaultClient と CallDefaultClient がチームに設定されているとき、通話とチャットがチームに送信されていることをユーザーに通知します。
-   会議に参加しておらず、Skype for Business で無効になっており、会議参加エクスペリエンスが [Native Limited Client] に設定されているユーザーの場合、ユーザーのプレゼンスは [オフライン] と表示されます。
-   Skype for Business が通知エリアに最小化されているときに、[開く] および [終了] 以外のすべてのオプションを無効にします。
-   Aries の電話と RedirectClient とのペアリングが有効である場合、新しい通話と会話を表示しません。
-   日付形式が US 形式 (mm/dd/yy) 以外の場合、日付を使った PChat のメッセージの検索が失敗する問題を修正します。
-   EnableExternalP2PFileTransfer ポリシーが false に設定されている場合でも、ユーザーが引き続き会議にファイルを添付できる問題を修正します。
-   会話履歴で、呼び出し先ではなく呼び出し元が表示される問題を修正します。これは、Active Directory を使用して呼び出し先の勤務先番号が変更された場合に発生します。
-   携帯電話番号に PSTN 通話を発信するときに、会話履歴内の通話履歴に受信者情報が表示されない問題を修正します。
-   Outlook の電子メールから IM を開始するときに、電子メールの件名が IM の件名に含まれない問題を修正します。
-   IM の会話ウィンドウが片面にスナップされると、会話が二重にスタックされて表示される問題を修正します。
-   VDIv2 環境で、VbSS 画面共有要求が RDP ベースの要求として表示される問題を修正します。
-   通話転送が失敗したときに、失敗通知に、不在の受信者ではなく呼び出し元が表示される問題を修正します。
-   クライアント アップグレード リダイレクト バナー内で [Teams の使用を開始] ボタンが表示されない問題を修正します。
-   IM ウィンドウの DPI スケールの問題を修正します。
-   LinkedIn データが Skype for Business 連絡先カードに表示されない問題を修正します。
-   ユーザーがハント グループの代わりに通話の受信を停止する機能を追加します。
-   Skype for Business または Teams で通話中に、新たな通話を受信または開始したときに、通話を自動的に保留する機能を追加します。
-   全画面共有後に、ユーザーが IM を使用できなくなる問題を修正します。
-   ロビーにいるユーザーが会議に参加することを拒否されたときに、通知されないという問題を修正します。
-   通話中に自動ゲイン制御が次第に制御できなくなる問題を修正します。
-   会議の招待に会議室のリソース メールボックスを追加すると、ユーザーが会議のオプションで発表者を選択できなくなる問題を修正します。
-   AllowlPVideo が False に設定されているとピアツーピアのビデオ通話中にデスクトップの共有ボタンが淡色表示される問題を修正します。
-   [IM を無効にする] の設定で作成した既存の会議について会議のオプション設定を [IM を有効にする] に変更しても、IM が無効のままである問題を修正します。
-   チャット ウィンドウで [リンクの挿入] ボタンの上にカーソルを置くとヒントが表示されない問題と、ボタンを選択したときにアクセシビリティ名がない問題を修正します。

### <a name="visio-feature-updates"></a>Visio: 機能の更新
-   **組み込みのデータベース モデル図:** 新しいデータベース モデルのテンプレートを使用して、データベースを Visio 図面として正確にモデル化します。アドインは必要ありません。
-   **ビジネス用ダイアグラムのその他のステンシル:** 現代的な図形を使用して、データをベン図表と比較対照したり、循環、マトリックス、ピラミッド型図表を描いたりして、考えをわかりやすく伝えることができます。
-   **Web サイトのワイヤーフレーム図の作成:** インターフェイス、ナビゲーション、それらの連携方法を含む Web サイトのワイヤーフレーム図を速やかに作成します。 [詳細情報](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **モバイル アプリケーションのワイヤーフレームの作成:** テンプレートを使用して、モバイル アプリケーションのワイヤーフレームを作成します。[詳細情報](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **データ ビジュアライザーの図にデータ グラフィックが適用されます。** 図形データをデータ グラフィックとして自動的に適用してデータ ビジュアライザーの図を作成し、時間を節約しましょう。 [詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **描画の共同作業:** OneDrive for Business または SharePoint Online で描画を共有して、他のユーザーと同時に作業します。誰が描画しているかを確認したり、コメントを追加したり、ファイル アクティビティを確認したりできます。 [詳細情報](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。

### <a name="word-feature-updates"></a>Word: 機能の更新
-   **SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。
-   **文字数:** 入力時にステータス バーに文字数を表示します。カスタマイズ ステータス バー メニューから、これを有効にできます。
-   **サイトおよびグループへすばやくアクセス:** [ファイル] メニューを使用して、よく使用するサイトやグループに格納されているドキュメントを操作できます。
-   **Microsoft Translator:** Word で Microsoft Translator を使用して、単語、語句、ドキュメント全体を別の言語に翻訳します。[詳細情報](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **デジタル鉛筆:** 新しい鉛筆のテクスチャで、アイデアを書き込んだり、スケッチしたりします。サポートされているデジタル ペンを傾けるだけで網かけができます。
-   **LinkedIn 機能の設定:** [ファイル] \> [オプション] \> [全般] と移動して、Office アプリケーションで LinkedIn 機能が表示されるかどうかを制御します。[詳細情報](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **SharePoint プロパティ パネル:** ドキュメント内で SharePoint ドキュメント ライブラリ列の値を表示し、編集します。[表示] タブのリボン ボタンからパネルに簡単にアクセスが可能で、SharePoint 管理者はドキュメント ライブラリの設定を使用して [プロパティ] パネルを自動的に開くことができます。
-   **3D モデル:** 3D を使用して、ドキュメントを、より視覚的かつ独創的なものにすることができます。3D モデルの挿入も簡単で、360 度回転させることができます。 [詳細情報](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **新しいインク効果:** メタリック ペンを使用し、ゴールド、シルバーあるいは虹、銀河、溶岩、海などを連想させる色などのインクの効果を活用して、アイデアの表現の幅を広めましょう。
-   **ファイル共有 UI:** OneDrive for Business または SharePoint のファイルの場合、リボンの右上隅にある [共有] ボタンをクリック、または [ファイル] \> [共有] の順に移動することにより、簡略化され改良された [共有] ダイアログが起動されます。新規のファイル、またはローカルに保存されたファイルの場合、この UI によって、ユーザーはファイルを OneDrive に簡単にアップロードし、共同作業を開始できます。
-   **危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。
-   **学習ツールを使用した編集:** Word の Web レイアウトで学習ツールを使用できるようになりました。テキストの間隔を調整し、編集時に音節を表示します。任意のビューで、文書が読み上げられるときに単語が強調表示されていることを確認してください。 [詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **LaTeX 構文:** LaTeX 構文を使用して数式を作成および編集します。
-   **アクセシビリティを向上させるのに役に立つサウンド:** 音声キューを有効にすると、作業中に操作を指示してもらうことができます。[ファイル] \> [オプション] \> [簡単操作] の順に選択すると見つかります。アドインは必要ありません。 [詳細情報](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **アカウントごとのファイルの場所:** ファイルを開くときや保存する場合、場所のリストは、その場所に関連付けられたアカウントによって整理されます。
-   **ペンのカスタマイズ:** 手描き入力についてペンと蛍光ペンの個人用設定を選択します。カスタマイズした設定は、お使いのすべての Windows PC でご利用いただけます。
-   **強化された [エディター] ウィンドウでの文書作成支援:** [エディター] ウィンドウは、高度なスペル チェック、文章校正、文章のスタイルの推奨に使用します。支援技術の高度なサポートにより、アクセスできるように作成されています。

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0792): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0794): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0798): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0801): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0802): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0804): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0805): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0806): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0807): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0812): Microsoft Word のメモリ破損の脆弱性
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0919): Microsoft Office の情報漏えいの脆弱性
-   [アドバイザリ 170020](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170020): Microsoft Office 多層防御の更新プログラム

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   ユーザーが OneDrive for Business で既存のドキュメントに対して [名前をつけて保存] をしようとしてから、その保存をキャンセルするか、既存の変更をマージしようすると Word がクラッシュする問題を修正します。
-   差し込み印刷ウィザードを実行しているときに、Null (空) 値を含むデータ ソース フィールドでのフィルター処理が失敗する問題を修正します。
-   同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。
-   ドキュメントで IRM 保護を削除しても保護が削除されない問題を修正します。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11882): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0795): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0851): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0853): Microsoft Office の情報漏えいの脆弱性
-   [アドバイザリ 180003](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180003): Microsoft Office 多層防御の更新プログラム

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   Office 365 クライアントの更新が System Center Configuration Manager によって管理されるように、Office COM オブジェクトが有効になっている場合は、[ファイル] \> [アカウント] \> [更新オプション] で [今すぐ更新] オプションが非表示になっています。
-   ユーザーが [Office ライセンス認証] ダイアログ ボックスを使用して Office のライセンス認証をしようとすると、Office アプリがクラッシュする問題を修正します。
-   動的 DPI 環境下における Office アドインのズームとスケーリングに関する問題を修正します。
-   Office 365 ProPlus が現在インストールされている場合でも、Office 構成サービス プロバイダー (CSP) の CurrentStatus ノードが空の文字列を返す問題を修正します。
-   .box ファイルが同じコンピューターの Office アプリのすべてのバージョンで共有されるために、box ファイルの形式の変更を引き起こし、その変更が同じコンピューターにインストールされている古いバージョンの Office の機能に影響を与える問題を修正します。



## <a name="version-1708-february-13"></a>バージョン 1708: 2 月 13 日
*バージョン 1708 (ビルド 8431.2215)*

### <a name="access-non-security-updates"></a>Access: セキュリティ以外の更新プログラム
-   複数の項目のフォームを使って、マウス ホイールまたはスクロールバーのつまみを調整してもフォームに表示される項目が変化しないという問題を修正します。

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0841): Microsoft Excel のリモート コード実行の脆弱性

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook 特権の昇格の脆弱性
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook のメモリ破損の脆弱性

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0851): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0853): Microsoft Office の情報漏えいの脆弱性



## <a name="version-1708-january-9"></a>バージョン 1708: 1 月 9 日
*バージョン 1708 (ビルド 8431.2153)*

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0796): Microsoft Excel のリモート コード実行の脆弱性
-   [アドバイザリ 170021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170021): Microsoft Office 多層防御の更新プログラム

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   ピボットテーブルのプログラムによる作成の後にプログラムによる更新が行われると、Excel がクラッシュする問題を修正します。

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook のリモート コード実行の脆弱性
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0792): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0794): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0798): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0801): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0802): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0804): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0805): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0806): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0807): Microsoft Word のリモート コード実行の脆弱性
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0812): Microsoft Word のメモリ破損の脆弱性

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0795): Microsoft Office のリモート コード実行の脆弱性
-   [アドバイザリ 180003](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180003): Microsoft Office 多層防御の更新プログラム

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   ID がオンプレミスの Active Directory とフェデレーションされている Office 365 Germany プランのドメイン ユーザーに、シングル サインオン (SSO) のサポートを追加します。
-   Office ストアから入手する Office アドインを、未成年者が取得してアクティブ化することを防止する機能を追加します。
