---
title: 2017 Semi-Annual チャネル (ターゲット) リリースのリリース ノート
ms.author: anankani
author: andymosten
manager: anankani
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: 2017 年の 365 ProPlus Semi-Annualチャネル (ターゲット) リリースのリリース ノートを IT Office提供
ms.openlocfilehash: 51a272f29ba9e68682285cb1de05e3964340d0f2
ms.sourcegitcommit: 90a9ee90251f072398574a437e5f45d406d617eb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/11/2021
ms.locfileid: "50735172"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>2017 Semi-Annual チャネル (ターゲット) リリースのリリース ノート

これらのリリース ノートには、2017 年の Semi-Annual チャネル (ターゲット) 更新プログラム (Office 365 ProPlus) に含まれる新機能、セキュリティ更新プログラム、およびセキュリティ以外の更新プログラムに関する情報が提供されています。
 
> [!NOTE]
> - また、Visio Pro for Office 365 および Project Online デスクトップ クライアントの新機能、セキュリティ更新プログラム、セキュリティ以外の更新プログラムについても説明しています。
> - ここに記載されている情報は、Business Premium など一部の Office 365 プランに付属する Office のバージョンの、Office 365 Business にも該当します。
> - Semi-Annualチャネル (ターゲット) は、2017 年 9 月より前の遅延チャネルのファースト リリースと命名されました。

## <a name="version-1708-december-12"></a>バージョン 1708: 12 月 12 日
*バージョン 1708 (ビルド 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel: セキュリティの更新
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Microsoft Excel のリモート コード実行の脆弱性

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   ユーザーが、マクロを含む Office 2007 以前のブック (.xls または .xla) を開くと、"致命的なエラー" のエラー メッセージが誤って表示される問題を修正します。
-   コマンド ラインからブックを開くとセルのリッチ テキストの書式が失われる場合があるという問題を修正します。

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): Microsoft Office の情報漏えいの脆弱性

### <a name="powerpoint-security-updates"></a>PowerPoint: セキュリティ更新プログラム
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint の情報漏えいの脆弱性

### <a name="project-non-security-updates"></a>Project: セキュリティ以外の更新プログラム
-   プロジェクト レベルのカスタム フィールド データが保存時に失われる問題を修正します。
-   保存に失敗するとファイルが破損して Project を開くときにクラッシュする問題を修正します。
-   プロジェクト プランを開くときにクラッシュする可能性がある問題を修正します。

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   [アドバイザリ 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office 多層防御の更新プログラム



## <a name="version-1708-november-14"></a>バージョン 1708: 11 月 14 日
*バージョン 1708 (ビルド 8431.2110)*

### <a name="access-non-security-updates"></a>Access: セキュリティ以外の更新プログラム
-   テキスト ボックスまたはコンボ ボックスでテキストを選択しようとすると、指示されたものが選択されるのではなく、すべてのテキストが選択されるという問題を修正します。

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Microsoft Excel のセキュリティ機能のバイパスの脆弱性
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): Microsoft Excel のメモリ破損の脆弱性
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): Microsoft Office のメモリ破損の脆弱性

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   ファイル名に角かっこが含まれている場合に、ユーザーが保護ビューでブックを閉じることができない問題を修正します。
-   ユーザーが既存のブックにオブジェクトを挿入しようとする場合に [参照] をクリックすると、Excel がクラッシュするという問題を修正します。
-   ([図の書式設定] ウィンドウのテキスト オプション/テキスト ボックスの部分で) [テキストを修正するために図形のサイズを変更する] を選択しても、図形のサイズが変更されないという問題を修正します。
-   ブックをダブルクリックして開くとセルのテキストのフォントと書式が読み込まれない、または 1 つのテンプレートに対して 2 つの同じブックが開かれる問題を修正します。
-   新しいブックを開いたり作成したりするときに、Excel の起動時に作成された最初のブックが閉じられない問題を修正します。
-   ドラッグまたはドラッグ フィルを実行するとヒントの配置がずれる問題を修正します。
-   [ファイル] \> [名前をつけて保存] を使用してブックを保存するときに、ピリオドを含むファイル名がファイル保存ダイアログで空白になるか切り詰められて見える問題を修正します。
-   同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。
-   グラフィック ドライバーの不具合の影響で、黒い線やヘッダーが表示されるというレンダリングの問題を修正します。
-   グラフを挿入した後に Excel がクラッシュしたり、ブックを保存できない問題を修正します。
-   改ページ プレビューのページの区切り位置が正しく配置されない問題を修正します。

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   メッセージを削除するときに、メッセージ一覧のフォーカスが予期せず移動する問題を修正します。
-   添付ファイルを扱う際に、ユーザーに認証プロンプトが表示される問題を修正します。

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。
-   表の中でテキストを元に戻した後に編集して書式設定すると、PowerPoint がクラッシュする問題を修正します。
-   Flash Player ベースの YouTube 埋め込みコードを参照すると、新しいウィンドウが開いて動画が再生される問題を修正します。現在、古い埋め込みコードは HTML5 ベースの YouTube 動画を参照するようにアップグレードされており、正しく再生されます。

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   [アドバイザリ 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Microsoft Office 多層防御の更新プログラム

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   ユーザーが OneDrive for Business で既存のドキュメントに対して [名前をつけて保存] をしようとしてから、その保存をキャンセルするか、既存の変更をマージしようすると Word がクラッシュする問題を修正します。
-   同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。
-   ユーザーが Word を開いた直後に [挿入] タブに移動すると、Word が応答しなくなる問題を修正します。
-   余白をクリックした後に文字を入力すると、画面の左上に文字が表示される問題を修正します。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): Microsoft Office のメモリ破損の脆弱性

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   動的 DPI 環境下における Office アドインのズームとスケーリングに関する問題を修正します。
-   Office 365 ProPlus が現在インストールされている場合でも、Office 構成サービス プロバイダー (CSP) の CurrentStatus ノードが空の文字列を返す問題を修正します。
-   .box ファイルが同じコンピューターの Office アプリのすべてのバージョンで共有されるために、box ファイルの形式の変更を引き起こし、その変更が同じコンピューターにインストールされている古いバージョンの Office の機能に影響を与える問題を修正します。
-   共有コンピューターのライセンス認証を使用する特定の状況で、アプリの正常な動作を妨げるエラーがアプリで発生したことを示し、修復を実行するかどうかをユーザーに尋ねるエラー メッセージが表示される問題を修正します。



## <a name="version-1708-october-10"></a>バージョン 1708: 10 月 10 日
*バージョン 1708 (ビルド 8431.2107)*

### <a name="access-non-security-updates"></a>Access: セキュリティ以外の更新プログラム
-   クエリに Microsoft Dynamics リンク テーブルの主キーとの結合がある場合に、クエリが実行されない問題を修正します。
-   Microsoft Dynamics テーブル内で、通貨値の小数点以下桁数が表示されない問題を修正します。

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   .XLL ファイルを開くと Excel がクラッシュする問題を修正します。
-   ページ レイアウト表示にヘッダーまたはフッターを追加した後、セルのパターンの種類が正しく表示されない問題を修正します。
-   ピボットテーブルのコピーを別のブックに貼り付けるとクラッシュする可能性がある問題を修正します。
-   [置換] コマンドを選択して、[検索と置換] ダイアログ ボックスが開くと、ダイアログ ボックスのフォーカスが [置換] タブではなく [検索] タブにある問題を修正します。
-   SharePoint Server 2016 より前の SharePoint サーバーから開いたブックのアクティビティ ウィンドウを開くと Excel がクラッシュする問題を修正します。
-   1 つ以上の XLL アドインを有効にすると、Excel で空白のウィンドウが表示される問題を修正します。
-   既に閉じているブックで [フォーム] ボタンを使用した後、Excel がクラッシュする問題を修正します。
-   SheetBeforeRightClick イベントを使用して、結合したセルと重なる列を挿入しても、結合したセルが拡張されない問題を修正します。

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Microsoft Outlook のセキュリティ機能のバイパスの脆弱性
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): Microsoft Outlook の情報漏えいの脆弱性

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   濃い灰色のテーマを使用すると、ポリシーのヒントにある [詳細] リンクが表示されない問題を修正します。
-   ユーザーが新しいアカウントを設定しようとして、アカウントの設定を完了せずにウィンドウを閉じると Outlook がクラッシュする問題を修正します。
-   グループの共有の受信トレイで、[既読] と [未読] がメッセージのオプションとして表示される問題を修正します。

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   SharePoint Server 2016 より前の SharePoint サーバーからプレゼンテーションを開くと PowerPoint がクラッシュする問題を修正します。

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): Microsoft Office のメモリ破損の脆弱性

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   SharePoint Server 2016 より前の SharePoint サーバーから開いたドキュメントのアクティビティ ウィンドウを開くと Word がクラッシュする問題を修正します。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Microsoft Office のリモート コード実行の脆弱性

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   オンライン修復の進行状況がユーザーに表示されない問題を修正します。
-   Office ファイルのプロパティがエクスプローラーで表示されない問題を修正します。
-   2 つ目のドキュメントが開いていると、Office アドインのボタンがリボンで非表示になる問題を修正します。
-   名前に全角文字が使用されている一部の VBA モジュールを開けない問題を修正します。



## <a name="version-1708-september-12"></a>バージョン 1708: 9 月 12 日
*バージョン 1708 (ビルド 8431.2079)*

### <a name="access-feature-updates"></a>Access: 機能の更新
-   **ラベル名のプロパティ:** ラベルにフォームのコントロールを関連付けることで、アクセシビリティが向上します。
-   **新しいアイテムの編集がより簡単に:** クイック ショートカット (Ctrl + E) キーを使用して、コンボ ボックスまたはリスト ボックスから新しいアイテムを編集できます。
-   **動的コネクタ:** Microsoft Dynamics からデータをインポートしたり、Microsoft Dynamics に保存されているデータにリンクしたりします。[詳細情報](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Salesforce コネクタ:** Salesforce からデータをインポートしたり、Salesforce に保存されているデータにリンクしたりします。[詳細情報](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel: 機能の更新
-   **"サンプルからの列の追加" の機能強化:** より多くの日付/時刻、数学、インデックス列の変換をサポートします。
-   **パフォーマンスの強化:** Excel は複雑なブックを複数のシートで速く開くので、複雑な数式を高速処理したり、多くの行をフィルター処理したり、すばやくコピー/貼り付けすることができます。
-   **オンライン画像の挿入:** 画像と属性情報を選択するための新しいランディング ページは、画像と一緒に自動で挿入されます。
-   **Azure Data Lake Store コネクタ:** ユーザーは、Azure Data Lake Store からデータをインポートできるようになりました。
-   **"サンプルからの列の追加" の機能強化:** 推奨事項、その他の日付/時刻の操作、追加の変換をサポートしています。
-   **[データ] タブ**: [データ] タブのリボン ボタンは、[取得と変換] と [クエリと接続] という 2 つの新しいグループに整理されました。
-   **クエリの共有**: すべてのクエリの定義を Office データベース接続 (ODC) ファイルにエクスポートし、複数のブックで、または他のユーザーと共有します。
-   **データの読み込み** クエリのデータをピボットテーブルまたはピボットグラフに直接読み込みます。データ モデルにデータを保存する必要はありません。
-   **共有ファイル アクティビティ:** ファイルの右上隅にある [アクティビティ] ボタンを選択し、OneDrive for Business や SharePoint で共有されているファイルを共有、編集、名前を変更、復元したタイミングを確認します。
-   **安全なリンク:** ユーザーがリンクをクリックすると、Office 365 Advanced Threat Protection (ATP) によって、そのリンクが悪意のあるリンクかどうかを検査します。悪意のあるリンクと判断された場合は、ユーザーは元のターゲット URL ではなく警告ページにリダイレクトされます。 [詳細情報](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **データ インポートの拡張機能:** さまざまなソースからデータを簡単にインポートし整形します。[クエリと接続] 作業ウィンドウでブックのクエリと接続を管理し、ODC ファイル経由でクエリを他のユーザーと共有します。 [詳細情報](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **共有ファイルの変更**: 共有ブックに変更を加えたユーザーを表示し、以前のバージョンを復元します。[詳細情報](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **ペン ボタンでなげなわ選択:** リボンにアクセスすることなく、サポートされているデジタル ペン ボタンを使ってインクのなげなわ選択を行います。

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): Microsoft Office のメモリ破損の脆弱性

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   ピボットテーブルを展開または折りたたんだとき、またはピボットテーブルのヘッダーが画面の外に移動したときに Excel が一時的に停止するという問題を修正します。
-   Word からタブ区切りのテキストをコピーして貼り付けるときにタブが無視され、テキストが列に解析されない問題を修正します。
-   [Web ページとして発行] ダイアログ ボックスを開いたときに Excel ページがクラッシュする問題を修正します。
-   データの更新に失敗する問題や、Excel のロケールおよび SQL Server Analysis Services サーバーのロケールが異なる場合に SQL Server Analysis Services サーバーからのデータを使用すると Excel がクラッシュする問題を修正します。
-   OneDrive クライアントと同期しているドキュメントへの変更を保存しようとするとエラーが発生する問題を修正します。
-   フィルター エリアにフィールドがあるピボットテーブルがあり、他にはフィールドがない場合に、ワークシートに変更を加えることができない問題を修正します。

### <a name="outlook-feature-updates"></a>Outlook: 機能の更新
-   **アクセシビリティの向上:** スクリーン リーダーを使用しているときの、メールでのテキスト、表、リスト、画像の読み取りおよび編集が簡単になりました。
-   **新しいアカウントの構成:** 新しいウィザードによる新しいアカウントの設定では、手動の手順が少なくなりました。
-   **リンクの添付ダイアログ:** リボンの [ファイルの添付] を使ってリンクを添付する場合、リンクとして追加するのか、添付ファイルとして追加するのかを選ぶことができます。このダイアログを毎回表示しないようにするには、[ファイル] \> [オプション] \> [全般] の順に移動して、[添付ファイルのオプション] でリンクの添付方法を指定します。
-   **オンプレミスの添付ファイルのサポート:** オンプレミスの SharePoint Server からのファイルは最近使用したファイルとして [メッセージ] \> [添付ファイル] に表示され、オンプレミスの OneDrive for Business および SharePoint チーム サイトは [添付ファイル] \> [Web 上の場所を参照] に表示され、ローカル ファイルはオンプレミスの OneDrive for Business サイトにアップロードすることができます。
-   **グループのビジネスの分類:**  グループを作成または編集するとき、テナント管理者によって定義されたビジネスの分類レベル (例: 社外秘) を割り当てることができ、その分類はグループ ヘッダーに表示されます。
-   **Office 365 のグループへのゲスト アクセス:** 組織外のユーザーにグループ会話、ファイル、予定表への招待、グループ ノートブックへのアクセス権を付与し、共同作業を行います。 [詳細情報](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **操作可能なメッセージ:** 開発者は、ユーザーが外部の Web サイトまたは別のアプリに切り替えずに、Outlook から単純なアクションまたはクイック アクションを簡単に実行できるようにするメッセージを作成できます。[詳細情報](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook のセキュリティ機能のバイパスの脆弱性
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook の情報漏えいの脆弱性
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Microsoft Office Outlook のメモリ破損の脆弱性

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   Outlook で IMAP アカウントを構成できない問題を修正します。
-   Outlook を開くときに断続的なクラッシュが起きる原因となる問題を修正します。

### <a name="powerpoint-feature-updates"></a>PowerPoint: 機能の更新
-   **オンライン画像の挿入:** 画像と属性情報を選択するための新しいランディング ページは、画像と一緒に自動で挿入されます。
-   **ビデオのクローズド キャプション:** アクセシビリティを高めるため、ビデオにクローズド キャプションを追加します。[詳細情報](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **レコーディングのナレーション:** プレゼンテーションをレコーディングするときに、自分のナレーションのビデオを含めることができます。レコーディングには、アニメーション、インク、オーディオ、ビデオを含めることができます。
-   **共有ファイル アクティビティ:** ファイルの右上隅にある [アクティビティ] ボタンを選択し、OneDrive for Business や SharePoint で共有されているファイルを共有、編集、名前を変更、復元したタイミングを確認します。
-   **代替テキストの作成:** クラウドベースのサービスによって、プレゼンテーションの画像に対して代替テキストが自動で生成されます。
-   **安全なリンク:** ユーザーがリンクをクリックすると、Office 365 Advanced Threat Protection (ATP) によって、そのリンクが悪意のあるリンクかどうかを検査します。悪意のあるリンクと判断された場合は、ユーザーは元のターゲット URL ではなく警告ページにリダイレクトされます。 [詳細情報](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **デザイナーの機能強化:** アクション指向リストの本格的なデザイン アイデアを提案します。
-   **共有ファイルの変更:** 共有プレゼンテーションに変更を加えたユーザーを表示し、以前のバージョンを復元します。[詳細情報](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: セキュリティ更新プログラム
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): PowerPoint のリモート コード実行の脆弱性
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): PowerPoint のリモート コード実行の脆弱性

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   フォントにリンクされているエンドユーザー定義の文字 (EUDC) が表示に失敗する問題を修正します。

### <a name="project-non-security-updates"></a>Project: セキュリティ以外の更新プログラム
-   Project Online から特定のファイルを開くとプロジェクトがクラッシュするという問題を修正します。
-   残存作業時間を設定したときに、実際の開始が間違って消去される問題を修正します。
-   割り当ての実際の開始日が、Project Web App の状態管理のリソースによって報告されたものと異なるデータを表示する問題を修正します。
-   タスクの終了日が変更された場合、実績作業時間が再スケジュールされる問題を修正します。
-   コスト フィールドをコピー/貼り付けすると、丸めの影響で、貼り付けられた値がコピーされた値と正確に一致しない問題を修正します。
-   あるベースラインから別のベースラインに保存するときに、予算リソースの時間配分データがコピーされない問題を修正します。
-   状態フィールドがサマリー タスクに対して常に正しく計算されない問題を修正します。
-   エンタープライズ リソースがローカル リソースを置き換え、保護された作業が有効になっているときに、実績作業時間が誤ってエンタープライズ リソースに転送される問題の修正。
-   最初の列がタスク名で、その列がロックされている表がある場合に、タスクをクリックするとプロジェクトがクラッシュする問題の修正。
-   [タスク配分状況] ビューから、同じリソースに同じリソースを複数回割り当てることができる問題の修正。
-   XML ファイルを開くときにユーザー設定の数値フィールドの値が失われる可能性がある問題の修正。
-   最上位のタスクのインデントが、プロジェクトから SharePoint タスク リストに適切に同期しない問題の修正。
-   タスク、リソース、または割り当て情報を Excel ブックからインポートすると、作業フィールドの値が無視されることがある問題の修正。
-   プロジェクトを XML ファイル形式で保存すると、時間配分のベースライン値が最初の値に一致しないという問題を修正します。
-   Project クライアントで、プロジェクトがチェックアウトされていないのにチェックアウトされていると判断され、プロジェクトが開かないという問題を修正します。
-   Project ファイルをファイル サーバーから開くときの待ち時間が長い問題を修正して、速く開くようにします。

### <a name="skype-for-business-security-updates"></a>Skype for Business: セキュリティ更新プログラム
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): Windows GDI+ の情報漏えいの脆弱性
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): Graphics コンポーネントの情報漏えいの脆弱性
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): Microsoft Graphics コンポーネントのリモート コード実行

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   特定のポートがブロックされている場合、または AP が許可されていない場合に、ユーザーが会議に参加できない理由を説明するダイアログを追加します。
-   IM 会話タブをクリックすると、常設チャット ルームの未読メッセージが既読としてマークされる問題を修正します。
-   IM トーストを受信するときに数秒の遅延が生じる問題を修正します。
-   Exchange との同期が無効である場合に、AD の連絡先で連絡先の名前の代わりに電話番号が表示される問題を修正します。
-   フェデレーションが無効で、会議の開催者が匿名での参加を明示的にブロックしていない場合に、匿名の参加ユーザーが参加することをブロックされる問題を修正します。
-   招待者の上限を超える会議で、会議の開催者に招待者の数が正しく表示されない問題を修正します。
-   PSTN 通話を着信したときに、トーストで電話番号が表示されない問題を修正します。
-   連絡先リスト グループの名前を変更するときに Delete キーを使用すると、グループ全体が削除される問題を修正します。
-   IM の会話で、共有を停止する前に共有通知が消去される問題を修正します。
-   英語以外のいくつかの言語でのサインイン画面が空白になる問題を修正します。
-   チャットとチャット履歴で英語以外の文字が文字化けする問題を修正します。
-   ユーザーの名前が不明の場合、組織の自動応答によって処理される着信呼び出しに対して発信者の電話番号を表示します。
-   インバンド設定を追加し、[ロビーで待つ必要のない参加者] の [すべてのユーザー (制限なし)] の制限をオプションとして許可します。
-   P2P ビデオ通話用のセルフビデオを VDIv2 でオンまたはオフにする機能を追加します。
-   呼び出しドロップダウン メニューで連絡先の番号が重複して表示されるという問題の修正。
-   Skype for Business と Skype for Business Basic の間を移動するユーザーの代理人が削除されるという問題の修正。
-   [オフラインでの表示を有効にする] および [カスタム状態 URL] クライアント ポリシーを使用する場合、[オフラインで表示] が表示されないという問題の修正。
-   [会議に参加] ボタンを拡大することで、一部のローカライズされた言語が切れてしまう問題を修正しました。
-   チャットで、[重要度 - 高] のメッセージをもっと目立つようにします。
-   Office と Skype for Business のファイル拡張子の種類を、許可するファイル転送ブロック リストに追加します。
-   フッター テキストが英語以外に設定された会議について、Outlook の会議出席依頼でのローカライズの修正。
-   送信者の名前を複数のユーザーの会話に切り替えることができるという問題を修正します。
-   会議に正常に参加するまで、空の会話ウィンドウが表示されないという問題を修正します。
-   タイトル フィールドが空の場合、連絡先カードの部署フィールドの情報が検索結果で空になるという問題を修正します。
-   ファイアウォール ルールにより、オンプレミスからオンラインに移行したユーザーについてサインインが失敗する問題を修正します。
-   ユーザーが LyncAutoD を実行して外部ネットワーク上のクライアントにサインインすると、クライアントが OAuthUsed レジストリ キーを false にリセットするという問題を修正するための新しい DWORD レジストリ キーを追加します。 問題を修正するには、HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\> の下の EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket の値を 1 に設定します。

### <a name="visio-feature-updates"></a>Visio: 機能の更新
-   **Excel データから図を作成します。** 新しいデータ ビジュアライザーのテンプレートを使用して、Excel データから基本フローチャートまたは部門連係フローチャートを自動的に作成します。 [詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **安全なリンク:** ユーザーがリンクをクリックすると、Office 365 Advanced Threat Protection (ATP) によって、そのリンクが悪意のあるリンクかどうかを検査します。悪意のあるリンクと判断された場合は、ユーザーは元のターゲット URL ではなく警告ページにリダイレクトされます。 [詳細情報](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: セキュリティ以外の更新プログラム
-   ファイル アイコンまたはファイル名をダブルクリックして Visio ファイルを開いたときに、ドキュメントによって開かれたイベントを COM アドインが受信しない問題を解決します。

### <a name="word-feature-updates"></a>Word: 機能の更新
-   **オンライン画像の挿入:** 画像と属性情報を選択するための新しいランディング ページは、画像と一緒に自動で挿入されます。
-   **代替テキストの作成:** クラウドベースのサービスによって、ドキュメントの画像に対して代替テキストが自動で生成されます。
-   **共有ファイル アクティビティ:** ファイルの右上隅にある [アクティビティ] ボタンを選択し、OneDrive for Business や SharePoint で共有されているファイルを共有、編集、名前を変更、復元したタイミングを確認します。
-   **安全なリンク:** ユーザーがリンクをクリックすると、Office 365 Advanced Threat Protection (ATP) によって、そのリンクが悪意のあるリンクかどうかを検査します。悪意のあるリンクと判断された場合は、ユーザーは元のターゲット URL ではなく警告ページにリダイレクトされます。 [詳細情報](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **共有ファイルの変更:** 共有ドキュメントに変更を加えたユーザーを表示し、以前のバージョンを復元します。 [詳細情報](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   Grammarly アドインの読み込み中に Word が予期せず終了する問題を修正します。
-   特定の状況で、クラウドベースのファイルを回復しようとしているときに Word がクラッシュする問題を修正します。
-   描画キャンバス内の図形を回転できない問題を修正します。
-   韓国語を入力する場合、子音や母音が正しく区切られないという問題の修正。
-   PDF としてドキュメントを保存すると、バージョン 1.7 の PDF としてドキュメントが保存されます。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): Microsoft Office のメモリ破損の脆弱性

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   新機能ダイアログが表示されない問題を修正します。
-   一部のユーザーについて、[描画] タブをクリックするとアプリケーションがクラッシュする問題を修正します。
-   ヒントがあるコモン コントロールの上にカーソルを置くとアプリケーションがクラッシュする問題を修正します。
-   コモン コントロールを使用する場合にライセンスのエラー メッセージが表示される問題を修正します。
-   一部のプログラム ファイルの署名において、ウイルス対策プログラムでこれらのファイルにフラグが設定されたり、Windows Information Protection (WIP) でのデータの保護およびアクセスに関して問題が発生したりするという問題を修正します。
-   support.to を追加すると、Office の 64 ビット バージョンを使用しているユーザーが mscomctl.ocx コントロールを含むマクロ ファイルを開けるようになります。
-   mscomctl.ocx で使用されているコントロールのアクセシビリティを向上させます。
-   コマンドが、リボンまたはクイック アクセス ツール バーのカスタマイズ ダイアログに表示されない問題を修正します。



## <a name="version-1705-august-8"></a>バージョン 1705: 8 月 8 日
*バージョン 1705 (ビルド 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   スクロールバーをドラッグしてメッセージの一覧内を移動するときの問題の修正。

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   一部のプログラム ファイルの署名において、ウイルス対策プログラムでこれらのファイルにフラグが設定されたり、Windows Information Protection (WIP) でのデータの保護およびアクセスに関して問題が発生したりするという問題を修正します。
-   新機能ダイアログが表示されない問題の修正。



## <a name="version-1705-july-27"></a>バージョン 1705: 7 月 27 日
*バージョン 1705 (ビルド 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   OneDrive クライアントと同期しているドキュメントへの変更を保存しようとするとエラーが発生する問題を修正します。
-   ワークシートのデータをデータ モデルに追加するときにハイ コントラスト テーマが黒に設定されていると Excel がクラッシュするという問題の修正。

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook のセキュリティ機能のバイパスの脆弱性
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook の情報漏えいの脆弱性
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): Microsoft Office Outlook のメモリ破損の脆弱性

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   別のユーザーがレイアウトを変更した後に図形を追加すると、結合が失敗するという問題の修正。

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   韓国語を入力する場合、子音や母音が正しく区切られないという問題の修正。
-   配送先住所がエンベロープの左端に近すぎる場所に印刷されるという問題の修正。



## <a name="version-1705-july-13"></a>バージョン 1705: 7 月 13 日
*バージョン 1705 (ビルド 8201.2136)*

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): Microsoft Office のメモリ破損の脆弱性

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   外部リンクを含むブックで Excel がクラッシュする問題の修正。
-   [ゼロ値のセルにゼロを表示する] 設定を選択していない場合に Excel のセルを Word に貼り付けると、セルにゼロが表示される問題の修正。

### <a name="project-non-security-updates"></a>Project: セキュリティ以外の更新プログラム
-   グラフ/テーブル用に選択された値が、グラフ/テーブル ウィンドウに表示されない問題の修正。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   会議に参加するときに会話ウィンドウがバックグラウンドで表示されず、オーディオ デバイスの参加ダイアログがユーザーに表示される問題の修正。
-   Outlook からの会議リンクが適切に内部 URI を渡さない場合があるという問題の修正。
-   [会議に参加] ボタンを拡大し、一部のローカライズされた言語を切り捨てました。

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   特定のアクションの後にテーブルが正しく表示されない問題の修正。
-   引用に対して複数の編集を行うと、連続した個別のアクションではなく、単一の元に戻すアクションとして表示されることがある問題の修正。
-   特定の操作を行った後に [元に戻す] が無効になる問題の修正。
-   特定の元に戻す操作を行った後にデータが失われないようにするための問題の修正。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office のリモート コード実行の脆弱性

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   Configuration Manager を使用すると、2016 Office 2013 2016 Office無人アップグレードが失敗する問題を修正します。
-   ストアから企業のカタログに展開された従来のアドインが読み込まれない問題の修正。



## <a name="version-1705-june-13"></a>バージョン 1705: 6 月 13 日
*バージョン 1705 (ビルド 8201.2102)*

### <a name="access-feature-updates"></a>Access: 機能の更新
-   **新機能ダイアログ:** 新機能のために Access を更新してから開くと、Access の新機能が強調表示されたダイアログ ボックスが表示されます。ダイアログ ボックスは、[ファイル] \> [アカウント] \> [新機能] からでもアクセスできます。
-   **大きい数値 (bigint) のサポート:** Access テーブルで大きい数値データ型を使用して、大きい数値を計算したり、SQL Server の bigint などの同等のデータ型を使用する外部データベースへの関連付けや外部データベースからのインポートを行ったりします。 [詳細情報](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel: 機能の更新
-   **Windows Information Protection (WIP) のサポート:**   現在、Excel は対応アプリになり、企業データと個人データを区別し、構成されているポリシーに基づいてどれを保護するかを判断します。  [詳細情報](https://aka.ms/wiptechnet)
-   **取得と変換の機能強化:** クエリ エディターで、サンプルの値を入力して、新しい列を作成します。入力すると、Excel で必要な変換が検出され、新しい列のプレビューが表示されます。
-   **最近使ったリンクの挿入:** 最近使ったクラウドベースのファイルまたは Web サイトへのハイパーリンクを付け、スクリーン リーダーを使用する人にわかりやすい表示名を付けることが簡単にできるようになりました。 [詳細情報](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **既定のピボットテーブルのレイアウトをカスタマイズする:** ピボットテーブルを好きなように設定し、新しいピボットテーブルを作成するときはいつもそのレイアウトで始めるようにします。 [詳細情報](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **機能強化の取得と変換:** ユーザーは、例に従って新しい列を作成したり、テーブル列を行に分割したりすることができます。SAP HANA へのパラメーターの指定とデータのグループ化がより簡単にできるようになりました。
-   **アドインの一元展開**: 管理者は、Office 365 の管理センターからユーザーまたはグループに対してアドインを展開し更新することができます。[詳細情報](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **クイック アクセス ツール バーのカスタマイズ** 下付き文字アイコンと上付き文字アイコンは、クイック アクセス ツールバーに追加できます。
-   **機能強化の取得と変換:** クエリ エディターを使用して列を分割するときに区切り記号文字を自動検出します。バイナリの結合に使用するサンプル ファイルを選択し、DB2 コネクタを使用するときに接続するパッケージ コレクションを指定します。
-   **Dubai フォント:** 西ヨーロッパ言語とアラビア文字を使用する主要言語の両方に対応しているフォント ファミリ。 [詳細情報](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景の削除:** 自由形式の描画ツールを使用して、画像の背景を削除します。
-   **機能強化の取得と変換:** ODCB コネクタと OLEDB コネクタのナビゲーター ダイアログで [関連テーブルの選択] を使用し、フォルダーの [データのプレビュー] ダイアログから複数のファイルを直接結合して、[クエリ エディター] ウィンドウで新しいコンテキスト メニューを使用して既存のクエリに新しい手順を挿入できます。
-   **ペンを使ったオブジェクトの選択や変更:** デジタル ペンでオブジェクト ハンドルをつかみ、サイズ変更、回転、移動などを行います。
-   **マップ グラフ:** 異なる地理的領域間で値を比較し、カテゴリを表示します。 [詳細情報](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **SVG 画像:** ブックにスケーラブル ベクター グラフィックス (SVG) を挿入して編集します。 [詳細情報](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **アイコンの挿入:** [挿入] \> [イラスト] \> [アイコン] の順に移動して、スケーラブル ベクター グラフィックス (SVG) ファイルの標準ライブラリのアイコンを使用します。 [詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **最近使用したフォルダーへの保存:** [ファイル] \> [名前を付けて保存] の順に移動し、[最近使用した項目] タブを使用して、最近使用したフォルダーにブックを保存します。
-   **アクセシビリティ機能の向上:** ブックの読み取りと編集に、キーボード、ナレーター、その他の支援技術を使用するためのサポートが改善されました。[詳細情報](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office のセキュリティ更新プログラム (3217868)

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   Excel 2010 以前に作成されたブックにプログラムで保護パスワードを適用する場合にシートに設定されない問題を修正します。
-   グループ化したワークシートで、結合と中央揃えが機能しない問題を修正します。
-   TEXTJOIN、CONCAT、IFS、MAXIFS、MINIFS など、Office 2016 のリリース後に導入された新しい機能がない問題を修正します。
-   ユーザーがセル レベルのアクセス許可を適用しようとすると Excel がクラッシュするという問題を修正します。
-   OneDrive for Business にサイズの大きなファイルを保存すると、ファイルがロックされ、ユーザーが Excel を終了して再度開くまでファイルを編集できないという問題を修正します。
-   .xls ブックを開くと、新しいウィンドウが灰色表示されるという問題を修正します。
-   ハイパーリンクを挿入するときに Excel がクラッシュする可能性がある問題を修正します。
-   XML の対応付けを追加するときに Excel が失敗する可能性がある問題を修正します。
-   アドインをアップグレードした後、またはアドインを削除して Office ストアからもう一度ダウンロードした後、アドインのコマンド ボタンが機能しない問題を修正します。
-   VBA で DLL シートを操作するときに Excel がクラッシュする可能性がある問題を修正します。
-   グラフ シートのフォーム コントロール コンボ ボックスを選択すると Excel がクラッシュする問題を修正します。

### <a name="onenote-feature-updates"></a>OneNote: 機能の更新
-   **Windows Information Protection (WIP) のサポート:** 現在、OneNote は対応アプリになり、企業データと個人データを区別し、構成されているポリシーに基づいてどれを保護するかを判断します。 [詳細情報](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote: セキュリティ以外の更新プログラム
-   段落が多数表示されている場合、OneNote キャンバスでコンテンツまたは更新プログラムが非表示になる問題を修正します。

### <a name="outlook-feature-updates"></a>Outlook: 機能の更新
-   **Windows Information Protection (WIP) のサポート:**   現在、Outlook は対応アプリになり、企業データと個人データを区別し、構成されているポリシーに基づいてどれを保護するかを判断します。  [詳細情報](https://aka.ms/wiptechnet)
-   **最近使ったリンクの挿入:** 最近使ったクラウドベースのファイルまたは Web サイトへのハイパーリンクを付け、スクリーン リーダーを使用する人にわかりやすい表示名を付けることができるようになりました。 [詳細情報](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Dubai フォント:** 西ヨーロッパ言語とアラビア文字を使用する主要言語の両方に対応しているフォント ファミリ。 [詳細情報](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景の削除:** 自由形式の描画ツールを使用して、画像の背景を削除します。
-   **共有ファイルへのアクセスの確認:** Outlook は、受信者が添付されている OneDrive ファイルまたは SharePoint ファイルにアクセスできない可能性がある場合は、事前にユーザーに通知し、問題を解決する方法を提案します。
-   **添付ファイルに対するアクセス許可の設定:** OneDrive または SharePoint の添付ファイルに関して、ユーザーは、組織内または組織外の受信者に添付ファイルに対する読み取りまたは編集のアクセス許可を付与するかどうかを設定できます。
-   **ピン留め可能な作業ウィンドウ:** メールボックス内のメッセージ間の切り替え中に、アドインの作業ウィンドウを開いたままにします。 [詳細情報](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **SVG 画像:** 電子メールにスケーラブル ベクター グラフィックス (SVG) を挿入して編集します。 [詳細情報](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **アイコンの挿入:** [挿入] \> [イラスト] \> [アイコン] の順に移動して、スケーラブル ベクター グラフィックス (SVG) ファイルの標準ライブラリのアイコンを使用します。  [詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Microsoft Outlook のリモート コード実行の脆弱性
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Microsoft Office のセキュリティ機能のバイパスの脆弱性
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): Microsoft Office のリモート コード実行
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): Microsoft Office のセキュリティ機能のバイパスの脆弱性

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   マシンのメモリが不足すると、Outlook ナビゲーション ウィンドウが表示されない問題を修正します。
-   添付ファイルの幅は、ファイル名とアクセス許可情報に合わせて視覚的に拡張されます。
-   ユーザーが PST ファイルを検索できないという問題を修正します。
-   [新しい Outlook データ ファイル] ダイアログ ボックスに "Microsoft Exchange" という新しいストアの種類が表示され、この新しいデータ型を選択するとユーザーのプロファイルを使用できなくなるという問題を修正します。
-   高 DPI を使用するコンピューターから送信されるメッセージ内の画像が真っ暗になる問題を修正します。

### <a name="powerpoint-feature-updates"></a>PowerPoint: 機能の更新
-   **Windows Information Protection (WIP) のサポート:**   現在、PowerPoint は対応アプリになり、企業データと個人データを区別し、構成されているポリシーに基づいてどれを保護するかを判断します。 [詳細](https://aka.ms/wiptechnet)
-   **最近使ったリンクの挿入:** 最近使ったクラウドベースのファイルまたは Web サイトへのハイパーリンクを付け、スクリーン リーダーを使用する人にわかりやすい表示名を付けることができるようになりました。 [詳細情報](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **アドインの一元展開**: 管理者は、Office 365 の管理センターからユーザーまたはグループに対してアドインを展開し更新することができます。 [詳細情報](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Dubai フォント:** 西ヨーロッパ言語とアラビア文字を使用する主要言語の両方に対応しているフォント ファミリ。 [詳細情報](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景の削除:** 自由形式の描画ツールを使用して、画像の背景を削除します。
-   **SVG 画像:** プレゼンテーションにスケーラブル ベクター グラフィックス (SVG) を挿入して編集します。 [詳細情報](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **アイコンの挿入:** [挿入] \> [イラスト] \> [アイコン] の順に移動して、スケーラブル ベクター グラフィックス (SVG) ファイルの標準ライブラリのアイコンを使用します。 [詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **共同編集時のリアルタイム入力:** プレゼンテーションで他のユーザーが作業している場所を確認し、入力時に変更を表示します。 [詳細情報](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **最近使用したフォルダーへの保存:** [ファイル] \> [名前を付けて保存] の順に移動し、[最近使った項目] タブを使用して、最近使用したフォルダーにプレゼンテーションを保存します。
-   **正確なインク図形の作成:** セグメント消しゴムをドラッグして、線のぎりぎりまで余分なインクを削除します。
-   **ペンを使ったオブジェクトの選択と操作:** デジタル ペンを使ってオブジェクト ハンドルをつかみ、オブジェクトの移動、サイズ変更、回転を行うか、サポートされているペン ボタンを使って、インクのなげなわ選択を行います。
-   **アクセシビリティ機能の向上:** プレゼンテーションの読み取りと編集に、キーボード、ナレーター、その他の支援技術を使用するためのサポートが改善されました。 [詳細情報](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   mfplat.dll ファイルがインストールされていないコンピューターで [デザイン アイデア] ウィンドウを表示すると、PowerPoint がクラッシュする問題を修正します。
-   アドインをアップグレードした後、またはアドインを削除して Office ストアからもう一度ダウンロードした後、アドインのコマンド ボタンが機能しない問題を修正します。

### <a name="project-feature-updates"></a>Project: 機能の更新
-   **先行タスクを簡単に設定できるドロップダウン:** ガント チャートのドロップダウンを使用して、どの先行タスクまたは後続タスクをタスクにリンクさせるかを選択します。
-   **Task Summary Name:**  Read-only task field that shows the name of the task’s summary task.  

### <a name="project-non-security-updates"></a>Project: セキュリティ以外の更新プログラム
-   Project Online で各エンタープライズ プロジェクト テンプレート (EPT) がプロジェクト サイトの独自の URL を持つようになり、[プロジェクト サイトの作成] ダイアログがサイトの正しい場所を示すように修正されます。
-   保存プロンプトの前に VBA BeforeClose イベントが発生する結果、保存プロンプトに対するユーザーの応答をプログラムによって判断する手段がないという問題を修正します。
-   プロジェクトの状況報告日の後に開始するタスクに対して [実際の達成率] が正しく重ね合わされない問題を修正します。
-   コストと時間単価型リソースが同じタスクに割り当てられているとタスクの進捗管理者を変更できない問題を修正します。
-   プロジェクト全体を平準化すると特定のプロジェクトで無限ループに陥る問題を修正します。
-   特定のスペイン語の地域設定を行うと、タスクの開始日と終了日が SharePoint タスク リストと正しく同期しないという問題を修正します。
-   Project クライアントから状態承認プロセスを開始するとプロセスが終了せず、プロジェクトが使用できない状態になる問題を修正します。
-   中国語と英語の単語があると、印刷プレビューでタスク名が正しくレイアウト表示されないという問題を修正します。
-   個々の図形としてタイムラインを PowerPoint にコピーする機能が作動しない問題を修正します。
-   [プロジェクト間のリンク] ダイアログ ボックスに値 "ファイルが見つかりません" が予期せず表示される問題を修正します。
-   最大単位数が 0 のリソースを割り当てると結果が矛盾する問題を修正します。
-   割り当ての開始日を削除すると、タスクの開始日が [できるだけ早く] にリセットされ、先行タスクなどが無視されることにより、割り当ての先行分割が生じる問題を修正します。
-   [最近使った項目] メニューを使用して SharePoint からファイルを開くと、設定 [ドキュメントを編集する前に必ずチェックアウトする] が有効になっていても、プロジェクトが自動的にチェックアウトされる問題を修正します。
-   Project プロファイル アプリケーションに直接移動すると、Project がクラッシュする問題を修正します。
-   Project 2013 からアップグレードしたユーザーに対して、手動でスケジュールされたタスクが正しく更新されない問題を修正します。
-   SharePoint タスク リストからプロジェクトを開くと、Project がタスク同期プロセスを開始するときに Project がクラッシュする可能性がある問題を修正します。
-   [チームの作成] に移動すると Project がクラッシュすることがある問題を修正します。
-   プロジェクトを保存すると基準計画の情報が失われる問題を修正します。
-   大規模なプロジェクト計画の印刷イメージが読みにくい問題を修正します。
-   Project Web App で編集したプロジェクトの数式フィールドに適切な値が表示されない問題を修正します。
-   プロジェクト計画のリソースのエンタープライズ カスタム フィールドの情報が正しく保存されない問題を修正します。
-   タスクの作業時間の達成率 (%) 情報を更新すると、タスクの達成率 (%) 情報が更新される問題を修正します。
-   プロジェクトを保存するとプロジェクトの所有者が変更される問題を修正します。
-   サマリー タスクの CPI の計算が正しくない問題を修正します。
-   保護された基準計画データの保存がユーザーに対して許可されていない場合でも、タスクのコピーと貼り付けにより基準計画データが引き継がれて保存される問題を修正します。
-   Excel のデータをインポートすると、タスクと割り当てに関するデータが不正確になる問題を修正します。
-   レポートを開いてから閉じると Project がクラッシュする問題を修正します。
-   カスタム リストに検証の設定が含まれている場合に、プロジェクトを保存すると Project が停止する問題を修正します。
-   [フィルターの定義] ダイアログの [テスト] 列に "\>" 文字を入力するときに、"より大きい" という意味に正しく解釈されない問題を修正します。
-   "基準計画" に関するイナズマ線の表示の問題を修正します。
-   フィールド名のドロップダウン リストがフィルターをカスタマイズするときに表示されない問題を修正します。
-   バー スタイルのプレビューが [バーのスタイル] ダイアログに表示されない問題を修正します。

### <a name="publisher-non-security-updates"></a>Publisher: セキュリティ以外の更新プログラム
-   Publisher に CMYK TIF 画像が表示されない問題を修正します。

### <a name="skype-for-business-feature-updates"></a>Skype for Business: 機能の更新
-   **リンクの挿入:** IM およびグループ チャットにリンクを追加し、そのリンクを示すために完全な URL の代わりにわかりやすいテキストを指定します。
-   **画面共有の通知:** IM の会話で画面を共有しているとき、または会議が終了した後に画面共有が継続されているときに、会話ウィンドウに通知が表示されます。この通知は、画面を共有していること、および [共有を停止] ボタンで簡単に共有を停止できることを示します。
-   **Windows Information Protection (WIP) のサポート:** Skype for Business は現在、WIP でのみ動作するアプリとしてサポートされています。Skype を許可されたアプリの一覧に追加すると、個人データが処理されないことが Windows に示されます。Windows では Skype for Business に代わってデータが保護されます。 [詳細情報](https://aka.ms/wiptechnet)
-   **パスワードのリセット オプション:** ユーザーがサインインに少なくとも 1 回失敗すると、サインイン ウィンドウにリセット ボタンのリンクが表示されます。

### <a name="skype-for-business-security-updates"></a>Skype for Business: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS17-013](https://technet.microsoft.com/library/security/ms17-013): Microsoft グラフィック コンポーネントのセキュリティ更新プログラム (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): Windows Uniscribe のリモート コード実行の脆弱性
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): Skype for Business のリモート コード実行の脆弱性

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   ポリシーで音声が無効になっているユーザーへの呼び出し試行メッセージを、「通話を完了することができません」から「IT 管理者がオーディオを制限しているため通話することができません。インスタント メッセージや電子メールを使用して、IT 管理者にご確認ください。」に変更します。
-   Skype for Business Online の PSTN 会議が有効なユーザーへの会議出席依頼に、「ダイヤルイン PIN を忘れた場合」のハイパーリンクが追加されます。
-   チームが Skype for Business Online から会議に参加できるようになります。
-   ラウドスピーカーのセッション音量の既定値を 40% から 75% に変更します。
-   タブのリストをより小さな最小幅までサイズ変更できるようになりました。
-   タブの順序と一致するようにショートカット キーを更新します。
-   ヘブライ語のテキストをモバイル デバイスから送信するときに方向が間違っていましたが、これを修正します。
-   [デスクトップの表示]/[制御を渡す] 機能を指してスクリーン リーダーが読み上げる情報の問題を修正します。
-   [ルームの選択] 一覧に、フォローされているルームに加え、開かれているルームを表示します。
-   カスタムの RCC アプリが有効になっているときに VoIP 機能を無効にする機能を追加します。
-   オフライン IM の紹介文を「Skype for Business モバイル アプリをお試しください」に変更します。
-   自動承諾された会話の会話ウィンドウが最小化ウィンドウではなく通常のウィンドウで開き、予期せずに他のウィンドウから注意をそらしてしまう問題を修正します。
-   [Skype 会議のオプション] ダイアログ ボックスでスクリーン リーダーを使用する場合の問題を修正します。
-   出席依頼の最初のメッセージが不在着信した会話の電子メールに表示されない問題を修正します。
-   [新しい Skype 会議] ボタンを使用して Outlook から会議出席依頼を作成するときに重複するダイヤルイン番号が表示される問題を修正します。
-   スクロール バーが表示されている場合、IM 履歴のすべての会話を Ctrl + A を使用して選択しようとすると、すべての会話が選択されない問題を修正します。
-   Export-CsArchivingData コマンドレットを使用すると、出力テキストの形式が正確に同じでないことがある問題を修正します。
-   3 人以上の参加者で [会議の開始] を使用すると、会議の開催者がリモートの参加者のビデオを見ることができない問題を修正します。
-   ユーザーが参加者リストの別のユーザーの名前を右クリックすると、会議の参加者一覧の最初の行が空白になる問題を修正します。
-   企業ネットワークの内部と外部との切り替え時にユーザーがサインインできなくなるという問題を修正します。
-   コンサルティング転送で IM からオーディオにエスカレーションする場合にチャット領域が閉じない問題を修正します。
-   2 つのエンドポイントの同時呼び出しを使用している場合のトースト通知で、名前が切り捨てられる問題を修正します。
-   ファイル共有通知でファイル名が切り捨てられる問題を修正します。
-   [通話に戻る] ボタンと転送ボタンのツール ヒントを追加します。
-   ナレーターなどのスクリーン リーダーで、コンサルティング転送ウィンドウにおける保留の時間を使用できるようにします。
-   コンサルティング転送の既定の設定として、IM または通話のいずれかを選択できる機能を追加します。
-   コンサルティング転送を行う場合、[転送] ボタンを右クリックして、連絡先の電話番号一覧を表示する機能を追加しました。
-   一般的なエラー メッセージが改善され、問題の原因は、ユーザーが無効なライセンスを持っているか、ユーザーにライセンスが割り当てられていないかであることが明確になります。
-   ユーザーが特定の連絡先と会話を開始し、別の連絡先を追加しようとすると、会話ウィンドウのタイトルに一部の連絡先が表示されない問題を修正します。
-   ナレーターが通知の 2 行目を読まない問題を修正します。
-   通話が、参照された番号ではなく VOIP に転送される問題を修正します。
-   ユーザーが [コンテンツ] ウィンドウに移動するときに、ナレーターによって正しくない情報が読み上げられる問題を修正します。
-   ホワイトボードのコメントにマウス カーソルを移動するときに作成者と変更者の名前が表示されない問題を修正します。

### <a name="visio-feature-updates"></a>Visio: 機能の更新
-   **サード パーティ製ステンシルの検索:** 選択したコンテンツ プロバイダーから提供されるサード パーティ製のステンシルを検索します。
-   **スライド スニペット:** Visio 図面のスニペットを取得し、PowerPoint のスライドとしてエクスポートします。 [詳細情報](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word: 機能の更新
-   **Windows Information Protection (WIP) のサポート:**  現在、Word は対応アプリになり、企業データと個人データを区別し、構成されているポリシーに基づいてどれを保護するかを判断します。  [詳細情報](https://aka.ms/wiptechnet)
-   **最近使ったリンクの挿入:** 最近使ったクラウドベースのファイルまたは Web サイトへのハイパーリンクを付け、スクリーン リーダーを使用する人にわかりやすい表示名を付けることができるようになりました。 [詳細情報](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **アドインの一元展開**: 管理者は、Office 365 の管理センターからユーザーまたはグループに対してアドインを展開し更新することができます。  [詳細情報](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Dubai フォント:** 西ヨーロッパ言語とアラビア文字を使用する主要言語の両方に対応しているフォント ファミリ。 [詳細情報](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **背景の削除:** 自由形式の描画ツールを使用して、画像の背景を削除します。
-   **並べて表示:** 印刷レイアウト表示で、積み重ねられた紙のように横にスライドさせてページを移動します。 [詳細情報](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **ペンを使ったオブジェクトの選択や変更:** デジタル ペンでオブジェクト ハンドルをつかみ、サイズ変更、回転、移動などを行います。
-   **SVG 画像:** ドキュメントにスケーラブル ベクター グラフィックス (SVG) を挿入して編集します。 [詳細情報](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **アイコンの挿入:** [挿入] \> [イラスト] \> [アイコン] の順に移動して、スケーラブル ベクター グラフィックス (SVG) ファイルの標準ライブラリのアイコンを使用します。  [詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **最近使用したフォルダーへの保存:** [ファイル] \> [名前を付けて保存] の順に移動し、[最近使用した項目] タブを使用して、最近使用したフォルダーにドキュメントを保存します。
-   **学習ツールでの閲覧機能の向上:** 閲覧モードでの新しいコマンドにより、文字間隔の調整、音節間の区切りの表示、およびドキュメントを音声で読み上げる際に各単語の強調表示が行われ、読み上げのスキルが向上しました。 [詳細情報](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **図形の認識:** [描画] \> [図形に変換] を使って、描画を自動的に図形に変換します。 [詳細情報](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office のセキュリティ更新プログラム (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): Windows PDF のリモート コード実行の脆弱性 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): Microsoft Office のリモート コード実行の脆弱性  

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   ユーザーが PST ファイルを検索できないという問題を修正します。
-   [新しい Outlook データ ファイル] ダイアログ ボックスに "Microsoft Exchange" という新しいストアの種類が表示され、この新しいデータ型を選択するとユーザーのプロファイルを使用できなくなるという問題を修正します。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Microsoft Office/ワードパッドのリモート コード実行の脆弱性/Windows API
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): Microsoft Office のリモート コード実行
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): Microsoft Office のリモート コード実行の脆弱性



## <a name="version-1701-may-9"></a>バージョン 1701: 5 月 9 日
*バージョン 1701 (ビルド 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   ユーザーがメッセージを削除するとき、メッセージの一覧でのメッセージの選択が断続的に予期せずにジャンプする問題を修正します。
-   断続的なクラッシュの原因となる問題を修正します。
-   管理者が [ファイル] タブのサポート選択を非表示とするには、HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableSupportBackstage レジストリ キーを追加します。
-   管理者が、[ファイル] \_ [フィードバック] にある “Outlook 2016 フィードバック“ と “Outlook のブログ“ オプションを無効にできるようにするには、HKEY\_CURRENT\\USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\>DisableOutlookFeedbackFeatures レジストリ キーを追加します。

### <a name="skype-for-business-security-updates"></a>Skype for Business: セキュリティ更新プログラム
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office のリモート コード実行の脆弱性

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   自動承諾された会話の会話ウィンドウが最小化ウィンドウではなく通常のウィンドウで開き、予期せずに他のウィンドウから注意をそらしてしまう問題を修正します。

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): Microsoft Office のメモリ破損の脆弱性
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office のリモート コード実行の脆弱性

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Microsoft Office のリモート コード実行の脆弱性
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office のリモート コード実行の脆弱性



## <a name="version-1701-april-11"></a>バージョン 1701: 4 月 11 日
*バージョン 1701 (ビルド 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   .xls ブックを開くと、新しいウィンドウが灰色表示されるという問題を修正します。

### <a name="outlook-security-updates"></a>Outlook: セキュリティ更新プログラム
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Microsoft Outlook のリモート コード実行の脆弱性
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): Microsoft Office のセキュリティ機能のバイパスの脆弱性

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   [新しい Outlook データ ファイル] ダイアログ ボックスに "Microsoft Exchange" という新しいストアの種類が表示され、この新しいデータ型を選択するとユーザーのプロファイルを使用できなくなるという問題を修正します。

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   USB サム ドライブなどのリムーバブル メディアに保存されている PowerPoint ファイルの別の場所に [名前を付けて保存] 操作を実行するとイメージ不足エラーが発生するという問題を修正します。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   企業ネットワークの内部と外部との切り替え時にユーザーがサインインできなくなるという問題を修正します。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): Microsoft Office/ワードパッドのリモート コード実行の脆弱性/Windows API



## <a name="version-1701-march-14"></a>バージョン 1701: 3 月 14 日
*バージョン 1701 (ビルド 7766.2071)*

### <a name="access-non-security-updates"></a>Access: セキュリティ以外の更新プログラム
-   フライアウト メニューを閉じることができない問題を修正します。

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office のセキュリティ更新プログラム (3217868)

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   ハイパーリンクを挿入するときに Excel がクラッシュする可能性がある問題を修正します。
-   XML の対応付けを追加するときに Excel が失敗する可能性がある問題を修正します。
-   アドインをアップグレードした後、またはアドインを削除して Office ストアからもう一度ダウンロードした後、アドインのコマンド ボタンが機能しない問題を修正します。
-   VBA で DLL シートを操作するときに Excel がクラッシュする可能性がある問題を修正します。

### <a name="onenote-non-security-updates"></a>OneNote: セキュリティ以外の更新プログラム
-   Windows 10 バージョン 1607 (別名: Windows Anniversary Update) で PIN を使用して認証後、OneNote ページ キャンバスがマウス クリックに反応しなくなる問題を修正します。
-   ユーザーが .docx または .pptx などの編集可能なドキュメントを挿入する場合、EDU 特有の最適化された印刷動作を無効にします。

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   共同編集時に結合の競合が間違って表示される問題を修正します。
-   アドインをアップグレードした後、またはアドインを削除して Office ストアからもう一度ダウンロードした後、アドインのコマンド ボタンが機能しない問題を修正します。
-   グラフで図形を適用するときに、VBA オブジェクト モデルを呼び出すとランタイム エラーになる問題を修正します。

### <a name="publisher-non-security-updates"></a>Publisher: セキュリティ以外の更新プログラム
-   Publisher に CMYK TIF 画像が表示されない問題を修正します。

### <a name="skype-for-business-security-updates"></a>Skype for Business: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS17-013](https://technet.microsoft.com/library/security/ms17-013): Microsoft グラフィック コンポーネントのセキュリティ更新プログラム (4013075)

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Microsoft Office のセキュリティ更新プログラム (3217868)

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   特定のモニター構成の場合に生じるメモリ消費量に関する問題を修正します。
-   アドインをアップグレードした後、またはアドインを削除して Office ストアからもう一度ダウンロードした後、アドインのコマンド ボタンが機能しない問題を修正します。



## <a name="version-1701-february-22"></a>バージョン 1701: 2 月 22 日
*バージョン 1701 (ビルド 7766.2060)*

### <a name="excel-feature-updates"></a>Excel: 機能の更新
-   **データ変換と接続性の機能強化:** 値の間に区切り記号を含む新しいテキスト列にリストを展開し、SQL に接続する際のフェールオーバー オプションを指定します。
-   **データ変換と接続性の機能強化:** パーセンテージ データ型がサポートされるようになり、バイナリの結合関数作成の操作性が強化されました。
-   **OLEDB コネクタ:** [取得と変換] で OLEDB コネクタを使用して、クエリを作成し、接続文字列、および必要に応じて、実行する SQL ステートメントを指定することによってデータをインポートします。
-   **インク再生:** [描画] \> [インク再生] で、手書き入力の入力前から入力後へと再生します。これによりコンテンツの表示と非表示を切り替え、ステップ バイ ステップの指示を出し、他のユーザーの考えの流れをより深く理解することができます。 [詳細情報](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **CSV (UTF-8) サポート:** UTF-8 文字エンコードを使用する CSV ファイルを開き、保存します。
-   **データ変換と接続性の機能強化:** OData ソースからデータを読み込むときに関連するテーブルを選択して、インポートしたり、関数の計算による値を持つカスタム列を追加したり、または専用のビューを使用してクエリ間の依存関係を表示したりします。
-   **自分と共有:** [ファイル] \> [開く] \> [自分と共有] で、他のユーザーが自分と共有しているのドキュメントを参照します。 [詳細情報](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **色の変更:** 操作アシストを使用して、フォント、強調表示、図形の塗りつぶしなどの色を設定します。 [詳細情報](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Microsoft Office のセキュリティ更新プログラム (3204068)

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   Office テーマを [黒] に設定して、[ブック クエリ] ウィンドウでクエリを右クリックすると「予期しないエラー」エラー メッセージが表示されるという問題を修正します。
-   ユーザーがピボットテーブル オプションにアクセスしようとすると、Excel がクラッシュする問題を修正します。
-   CSV または CSV UTF-8 として保存する際にテキストや二重引用符を含んだセルの値が正しくエクスポートされない問題を修正します。
-   Excel を閉じるときにハングするかクラッシュする問題を修正します。
-   連結式を含むハイパーリンクが連結結果の一部を無視する問題を修正します。
-   リッチ テキスト形式 (RTF) の Excel の表を Word に貼り付けると表の書式が保持されない問題を修正します。
-   ブックに MS Excel 4.0 マクロ ワークシートが含まれていると、ユーザーが [名前を付けて保存] を実行できない問題を修正します。
-   CTRL+ALT+5 を、他のアプリケーションに一致するオブジェクト層に選択範囲を移動するショートカットにします。
-   数式バーに入力して、VLOOKUP などの関数をドロップダウンから使うときに、Enter キーを押して数式を完成させようとすると、入力した値をそのままの形に残さず、オートコンプリート ドロップダウンの一番上の項目が選択される問題を修正します。
-   保護されたシート内にハイパーリンクが含まれている Excel 97 - Excel 2003 のバイナリ ファイル形式 (BIFF8) のファイルを開こうとすると、ファイルが壊れていると Excel が判断して読み取り不可能なコンテンツを修復または削除しようとする問題を解決します。

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: セキュリティ関連ではない更新プログラム
-   GrooveIntlResource.dll を正常に読み込むことができない場合 (通常の状況ではそうではありません)、ユーザーが同期済みフォルダーでファイルを開いたり保存したりしようとすると Office アプリがクラッシュする、あるいは Windows エクスプローラーを使用して同期済みフォルダーに移動すると Windows エクスプローラーがクラッシュする問題を修正します。
-   Office が Office Content Delivery Network (CDN) 以外の場所から更新プログラムを受け取るように構成されている場合、適切なレジストリ キーによって OneDrive for Business を無効に設定しても無効にならないという問題を修正します。

### <a name="onenote-feature-updates"></a>OneNote: 機能の更新
-   **ファイルと画像の同期の制御:** [ファイル] \> [オプション] \> [同期] と移動し、すべてのファイルと画像を、ノートブック内のすべてのページに自動的にダウンロードするかどうかを制御します。

### <a name="onenote-non-security-updates"></a>OneNote: セキュリティ以外の更新プログラム
-   ページより大きい画像を印刷すると OneNote がクラッシュする問題を修正します。
-   ユーザーがカスタム ページ テンプレートを削除できない問題を修正します。

### <a name="outlook-feature-updates"></a>Outlook: 機能の更新
-   **リアルタイムで添付ファイルの共同作業を行います。** OneDrive for Business に添付ファイルをアップロードして、すべてのユーザーが最新バージョンで作業できるようにします。添付ファイルのドロップダウン メニューを使用して、アップロードまたは保存します。
-   **旅行予約とパッケージのサマリー カード:** 受信トレイと予定表に自動的に作成されたサマリー カードを使用して、旅行予約およびパッケージの配送を確認して追跡します。 [詳細情報](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **エディター:** 高度なコンテキストの校正により文書の作成が改善されます。 [詳細情報](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   特定のスレッドの添付ファイル一覧にある添付ファイルを右クリックすると、該当するメニュー項目だけでなく、すべてのコンテキスト メニューが表示されるという問題を修正します。
-   リッチ テキスト形式 (RTF) の電子メール メッセージが、Information Rights Management を使って送信されたメッセージの場合、受信者によって開くことができない問題を修正します。

### <a name="powerpoint-feature-updates"></a>PowerPoint: 機能の更新
-   **クローズド キャプション:** クローズド キャプションが設定されているビデオがスライドに含まれていると、キャプションをスライドショーで再生できます。
-   **複数のオーディオ トラック:** 複数のオーディオ トラックが設定されているビデオがスライドに含まれていると、それらのトラックをスライドショーで再生できます。
-   **セクションのコピー:** プレゼンテーション間のセクションをコピーして貼り付けます。
-   **自分と共有:** [ファイル] \> [開く] \> [自分と共有] で、他のユーザーが自分と共有しているのドキュメントを参照します。 [詳細情報](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **インク再生:** 手書き入力を前方または後方に再生してコンテンツの表示と非表示を切り替え、ステップ バイ ステップの指示を提供し、他のユーザーの考えの流れをより深く理解できるようにします。 [詳細情報](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **より優れたレコーディング:** 記録されたスライド、画面録画、挿入されたビデオで構成されるプレゼンテーションを作成し、録画されたそのコンテンツをリモートで表示できるように共有します。リモート学習を支援し、プレゼンテーションをより対話的にするためにテストを埋め込むことや、インクの色を変更したり、単純なコントロールを使用してナレーションとオーディオを録音したりすることもできます。
-   **デザイナーの機能強化:** 箇条書きステップ リスト用に SmartArt を使用してデザインの推奨事項を示します。
-   **録画用のリボン タブ:** リボンをカスタマイズすることで、[録画] タブを追加します。
-   **色の変更:** 操作アシストを使用して、フォント、強調表示、図形の塗りつぶしなどの色を設定します。 [詳細情報](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **ズーム:** 自動ナビゲーション リンクを含むプレゼンテーションの対話型の概要を作成します。 [詳細情報](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **ハイパーリンクを開く:** プレゼンテーションを編集するときにハイパーリンクを開くには、Ctrl キーを押したままクリックします。
-   **テキストの強調表示:** テキストの蛍光ペンを使って、重要なテキストを強調します。

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   画像をトリミングすると、画像のトリミングした部分が暗く見える問題を修正します。
-   スライド ショー モードでナレーションを付けて実行している場合、ユーザーがハイパーリンクをクリックし、対象サイトの読み込み速度が遅いと、PowerPoint がクラッシュするという問題を修正します。
-   表に関して共同編集が動作しないというリアルタイム入力の問題を修正します。
-   Malwarebytes 3.0 がインストールされているコンピューターで PowerPoint を開く際に、"動作が停止しました" のエラーが表示されるか PowerPoint がクラッシュする問題を修正します。
-   [ファイル] \> [新規作成] に既定のテンプレートが表示されない問題を修正します。
-   埋め込みフォントを含むファイルが自動的に保存されるときにテキストの入力が中断され遅延する問題を修正します。
-   Adobe Illustrator からのスケーラブル ベクター グラフィックス (SVG) 画像のコピーに関する問題を修正します。

### <a name="project-feature-updates"></a>Project: 機能の更新
-   **[ロック] フィールド:** チーム メンバーが、タスクに関する更新を送信できないようにするには、値を [はい] に設定します。
-   **タイムライン ラベル:** ラベルを使用して内容を示す名前を付け、タイムライン バーを区別します。
-   **タイムラインの進行状況のインジケーター:** タイムライン ビューのチェック マークと色付きの進行状況バーを使用し、各タスクの進行状況を表示します。
-   **アクセシビリティ機能の向上:** プロジェクトの読み取りと編集に、キーボード、ナレーター、その他の支援技術を使用するためのサポートが改善されました。

### <a name="project-non-security-updates"></a>Project: セキュリティ以外の更新プログラム
-   マスター プロジェクトとサブプロジェクト間のプロジェクト間リンクを作成するときにリンク線が表示されない問題を修正します。
-   特に期間の一部を含む作業時間とコストの値など、時間配分のベースライン値が XML 形式に正しく保存されない場合があるという問題を修正します。
-   状態の更新を適用すると、チーム メンバーが報告していない割り当てに実作業が追加されるという問題を修正します。
-   リソースのベースラインが作成されていない場合でも、リソースのベースライン値が表示されるという問題を修正します。
-   印刷プレビューがテキストをクリップするためテキストが見えなくなる問題を修正します。
-   ショートカット URL を使用して SharePoint から .mpp ファイルを開くと、"編集する前にドキュメントをチェックアウトする必要がありますか?" の設定が有効になっている場合でも、ファイルがチェックアウト済みとして開くという問題を修正します。
-   Project Web App からの数量単価型リソースに対する更新によって、時間配分データが正しく変更されないという問題を修正します。
-   マイルストーン タスクを含むプロジェクトを開くと、そのプロジェクトを最後に保存したときの日付が設定されていなくても、実際の開始日が追加される場合がある問題を修正します。
-   作業分解構造 (WBS) の番号の再設定に関する問題を修正します。
-   グリッド ベースのビューを切り替えてナレーションを有効にすると Project がクラッシュするという問題を修正します。
-   XML ファイルを開くときにタイムスケール データの切り捨てに関する正しくないエラー メッセージが表示されるという問題を修正します
-   基準計画の保存で、タイムスケール値が正しく設定されないという問題を修正します。
-   XML ファイルからプロジェクト データを読み取るときに割り当ての延期期間が無視されるという問題を修正します。
-   Project Online からファイルを開くときに、[最終更新日] にタイムゾーン調整済み時刻ではなく UTC 時刻が表示されるという問題を修正します。
-   カラー バンドをグループ化すると、シート ビューを印刷するときにグループ化されていない行に表示されないという問題を修正します。
-   最大単位を超えて割り当てられたタスクをユーザーが検査するときに修復オプションが適切にユーザーに表示されないという問題を修正します。
-   プロジェクトの発行後、[アウトライン コード] フィールドの値を変更できないという問題を修正します。
-   175% 表示の高 DPI 画面で、ガント バーのサイズが正しく設定されない問題を修正します。
-   ユーザーが [タスク情報] ダイアログ ボックスでラグ タイム (時間差) を設定すると、ラグ タイムが誤って継続期間に設定される問題を修正します。
-   特定の XML ファイルを開くと、割り当てに関する問題が原因でタスクの開始日が正しく設定されない問題を修正します。

### <a name="skype-for-business-feature-updates"></a>Skype for Business: 機能の更新
-   **Windows の通知スタイル:** 着信と会話の通知の外観を変更します。 [詳細情報](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **コンサルティング転送:** 呼び出しの中から、IM を介して別のユーザーに相談するか、そのユーザーに通話を転送する前に呼び出しを行います。 [詳細情報](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **マイク通知:** オペレーティング システムでマイクがミュート状態の場合、またはマイクが音声を受信していない場合は、会話ウィンドウに通知を表示します。
-   **[自分の番号] の無効化:** DisableDisplayMyNumber レジストリ エントリを使用して、ダイヤル パッドの下の “自分の番号” を無効にします。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   参加者の許可または拒否に使用するロビー ボタンをテキストから画像に (X またはチェックマーク) に変更します。
-   会議のリマインダー通知テキストを "承諾" から "参加" に変更します。
-   受信者の状態が [応答不可] に設定されたときに、IM の送信者に表示するメッセージを更新します。
-   受信者がオフラインであり、"履歴に保存" が無効になっている場合は、IM の送信者に表示するメッセージを更新して、受信者がメッセージを受信しないことを明確にします。
-   グループ チャットのチャット履歴と参加者一覧の間の左右分割バーを移動する機能を追加します。
-   IM またはチャット ルーム ウィンドウにあるタブのリストのサイズを変更する機能を追加します。
-   トピック フィードを作成するときに検索されたチャット ルームを選択する機能を追加します。
-   会話中のチャット履歴にメッセージが表示されなくなる問題を修正します。
-   会話ウィンドウに重複したメッセージが表示される問題を修正します。
-   通知が大量にある場合に、トースト通知のアクション (承諾と無視) が正しく表示されない問題を修正します。
-   Alt + Tab を使用して最小化されている会話ウィンドウを開くと、ユーザーがメッセージを入力できないという問題を修正します。
-   IM が利用可能であっても、ユーザーの連絡先カードの IM ボタンが灰色表示されるという問題を修正します。
-   複数の会話ウィンドウを閉じてから再度開くと、以前のサイズと位置で開かないという問題を修正します。
-   選択したときにカスタム リンクが起動しないという問題を修正します。
-   [地域] フィールドのオンライン会議テキストが英語以外の文字で正しく表示されない問題を修正します。
-   通話時間などの通知情報が右から左方向の言語で正しく表示されない問題を修正します。
-   トピック フィードを作成するときに、検索結果をクリアしても、フォローされているルームのリストに結果がリセットされないという問題を修正します。
-   同時に複数の会話ウィンドウが開いているときに Skype for Business がハングする問題を修正します。
-   前回の会話ウィンドウが、他のすべてのタブを閉じると空白になるという問題を修正します。
-   タブ表示の会話が無効になっていると、チャット入力領域に既定のフォーカスが置かれないという問題を修正します。
-   会議の招待に「ダイヤルイン PIN を忘れた場合」リンクが表示されないという問題を修正します。
-   高 DPI スクリーンを 175% 以上の表示倍率で使用すると、[全般] ページまたは [オーディオ デバイス] ページで一部のテキストが切り捨てられて省略されるという問題を修正します。
-   ネットワークに接続していない、AOAC (Always On/Always Connected) コンピューターを中断する、または再開すると、Skype for Business がクラッシュするという問題を修正します。
-   Polycom CX100 デバイスを使用している場合に、発信でマイクが検出されないという問題を修正します。
-   IM メッセージで \\\\サーバー名またはファイル:// などのリンクを選択すると、対象の場所が開くのではなくエラー メッセージが表示されるという問題を修正します。
-   場所に基づいたルーティングを使用する仮想デスクトップ インフラストラクチャ (VDI) 環境で、サーバーがユーザーの場所では PSTN 通話を行えないと判断し、PSTN 通話の発信/受信を行えないという問題を修正します。
-   ユーザーの状態が [通知しない] または [表示しない] に設定されている場合に、メッセージが見つからない場合に送信されるメールの件名を [会話の欠落] から [Skype for Business でメッセージを送信しました] に変更 \<name\> \<Name\> します。
-   全数調査データの一環としてデバイスに初めてサインインしたときのタイムスタンプの [キャプチャを開始します。](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) サインインの信頼性の傾向を特定するのに役立ちます。
-   Windows 10 バージョン 1607 (Anniversary Update とも呼ばれる) の特定のモニター構成で、セカンダリ モニターを共有するオプションが表示されない問題を修正します。
-   共有先がサード パーティ製の RDP 実装を使用している場合に共有コンテンツにズームすると、Skype for Business がクラッシュする問題を修正します。
-   ユーザーが仮想デスクトップ インフラストラクチャ (VDI) 環境で音声通話のコントロール ボタンをクリックしたときに、オーディオ コントロール パネルが表示されない問題を修正します。
-   ユーザーが Windows 7 を実行している場合に、まずメイン モニターを共有してから、次にセカンド モニターを共有するために切り替えると、ビューアーに黒い画面が表示される問題を修正します。
-   アンパサンド (&) などの特定の特殊文字を、検索入力ボックスまたは [本日の予定やメッセージを入力] セクション ボックスに入力できない問題を修正します。
-   不在着信したオフラインの IM がある場合に未読アイテム数が表示されない問題を修正します。
-   [電子メールで招待] テンプレートの説明が Skype ではなく Lync である問題を修正します。
-   ダイヤル パッドの下にある [自分の番号] 領域に行番号が表示されない問題を修正します。
-   チャットでメッセージを送信した後、IM 入力領域にマウス ポインターが表示されない問題を修正します。
-   サインイン時にキャッシュ プールの読み込みに問題がある場合、Skype for Business が応答を停止する問題を修正します。
-   サインインして会話を復元すると、Skype for Business がクラッシュする問題を修正します。
-   再開後にサインインすると、Skype for Business が応答を停止する問題を修正します。
-   両方の組織の Exchange サーバーで TNEF が無効になっていると、会議のリンクが無効になる問題を修正します。
-   継続している IM 会話が 1 つだけの場合、ビデオ通話を再開できない問題を修正します。
-   ホワイトボードを PNG ファイルとして保存すると、ホワイトボードのテキスト注釈が失われる問題を修正します。
-   IM ウィンドウで、日本語で 2 行にまたがって入力すると最初の行が表示されない問題を修正します。
-   名前のアンパサンド文字 (&) がアンダースコア文字で誤って置き換えられる問題を修正します。
-   スケジュールされた会議の "オンライン会議に参加" URL に関する問題を修正します。
-   マウスをウィンドウ上に置くとウィンドウがアクティブになるようにオペレーティング システムを構成していても、ウィンドウがアクティブにならない問題を修正します。
-   発信の会話履歴項目に、呼び出し先ではなく呼び出し元が表示される問題を修正します。
-   F12 キーで会話がローカルに保存されない問題を修正します。
-   不在着信した会話の電子メールに最初の IM が含まれない問題を修正します。
-   発表者が IM への参加を無効にしていても、IM のテキスト領域に絵文字が追加できる問題を修正します。
-   [着信音と効果音のオプション] ダイアログ ボックスのレイアウトに関する問題を修正します。
-   会話ウィンドウを閉じると、Skype for Business がクラッシュする問題を修正します。
-   ドメインをバニティ ドメインとして登録すると、DNS レスのサインインが失敗する問題を修正します。
-   常設チャットの通知設定が正しく保存または読み込まれない問題を修正します。
-   会話を再度開くように設定されていても、サインインすると既存のピアツーピア会話ウィンドウまたはチャット ルームが表示されない問題を修正します。
-   アクティブな会話をミュートまたはミュートを解除すると、他の会話ウィンドウに未読のメッセージがあるかのように表示される問題を修正します。
-   メディア バイパスに対して構成されているユーザーが PSTN ゲートウェイからの通話を保留にすると、その通話を再開できない問題を修正します。
-   サード パーティによる RDP 実装を使用している場合に URL 経由でミーティングに参加すると、ユーザーにビデオではなく青いボックスが表示される問題を修正します。
-   トースト アラートに表示名ではなく、SIP アドレスのユーザー部分が表示される問題を修正します。
-   Skype for Business がポート 443 で SIP サーバーに接続し、プロキシ サーバーが存在している場合、およびプロキシがこのような接続を許可しない場合に、サインイン プロセスで大幅に遅延が発生する問題を修正します。EnableDetectProxyForAllConnections DWORD レジストリ エントリを HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync の下に追加し、値を 1 に設定すると修正は有効になります。
-   タブ表示の会話を使用しているときに、タブをダブルクリックして、入力を始めようとすると、フォーカスが別のタブに移動してしまうことがあり、その会話ウィンドウで入力が続いてしまう問題を修正します。
-   インスタント メッセージに含まれている URL を、キーボードを使用してチャット履歴ウィンドウで選択できない問題を修正します。
-   [着信音とサウンド] オプションの下にある [IM 会話を表示する場合、他のユーザーが入力しているときに音で知らせる] チェック ボックスが選択されている場合に、入力音が聞こえるようにする問題を修正します。
-   ナレーターなどのスクリーン リーダーを使用している場合に、表示されるダイアログ ボックスが読み上げられない問題を修正します。
-   最初の実行時のチュートリアルをキーボードで移動したり、ナレーターなどのスクリーン リーダーで読み上げたりできない問題を修正します。
-   タスク バーのプレゼンス アイコンを高 DPI 設定でスケールできない問題を修正します。
-   検索ボックスの [フィールドのクリア] ボタンをキーボードで選択できない問題を修正します。
-   招待状が別のプール内のユーザーからのものである場合、ユーザーが会議を開始できない問題を修正します。
-   自分自身を会議に追加しているユーザーが別のユーザーとして誤って表示される問題を修正します。
-   状態変更通知の連絡先のプレゼンス アイコンが上司の着信呼び出しに対して非表示になっていた問題を修正します。
-   IM ウィンドウでのテキスト カーソルの点滅の速さが、Windows で設定しているキーボードのプロパティと一致しない問題を修正します。
-   スクリーン リーダーがグループ会話の誤った連絡先の名前を読み上げる問題を修正します。
-   ユーザーがキーボードを使用して複数の連絡先を選択できない問題を修正します。
-   Exchange からユーザーの写真を取得できない問題を修正します。
-   ユーザーが直接アクセスを使用して接続している場合に、Skype for Business クライアントが外部ネットワークの Skype for Business Server に接続せずに、内部ネットワークの Skype for Business Server に接続する問題を修正します。
-   会議の所有者の名前を解決しようとすると、Skype for Business クライアントがクラッシュする問題を修正します。
-   Skype for Business を起動中、またはシャットダウン中に Windows の設定を変更すると、Skype for Business がクラッシュする原因となる問題を修正します。
-   常設チャット ルームで参加者リストを開いて、キーボード フォーカスを参加者リストに移動しようとすると、Skype for Business がクラッシュする問題を修正します。
-   ネットワークが使用できない場合、Skype for Business が再開時にクラッシュする問題を修正します。

### <a name="visio-feature-updates"></a>Visio: 機能の更新
-   **データベース モデルのアドイン:** アドインを使用して、既存のデータベースのデータベース モデルを作成し、新しいデータベースの計画や既存のデータベースの理解に役立てます。 [詳細情報](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614)、 [アドインのダウンロード](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **アクセシビリティ機能の向上:** キーボード、ナレーター、その他の支援技術を使用して図形を扱ったり、他の対象を編集したりするなどのサポートが改善されました。
-   **サード パーティ製のテンプレートやダイアグラム:** サード パーティのコンテンツ プロバイダーから入手可能な新しいテンプレートやサンプルのダイアグラムを参照または検索します。サード パーティ プロバイダーの名前は、サムネイルに表示されます。
-   **手描き入力のサポート:** ペンや指を使って、新しい描画タブのツールで図を描いたり注釈を入れたりします。

### <a name="word-feature-updates"></a>Word: 機能の更新
-   **アクセシビリティ機能の向上:** ドキュメントの読み取りと編集に、キーボード、ナレーター、その他の支援技術を使用するためのサポートが改善されました。 [詳細情報](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **エディター:** 高度なコンテキストの校正により文書の作成が改善されます。 [詳細情報](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **インク再生:** [描画] \> [インク再生] で、手書き入力の入力前から入力後へと再生します。これによりコンテンツの表示と非表示を切り替え、ステップ バイ ステップの指示を出し、他のユーザーの考えの流れをより深く理解することができます。 [詳細情報](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **自然なペン ジェスチャで編集する:** 円で囲んでの選択や、バツ印をつけての削除によって、ドキュメントに変更を加えます。 [詳細情報](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **自分と共有:** [ファイル] \> [開く] \> [自分と共有] で、他のユーザーが自分と共有しているのドキュメントを参照します。 [詳細情報](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **色の変更:** 操作アシストを使用して、フォント、強調表示、図形の塗りつぶしなどの色を設定します。 [詳細情報](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   1 つの文書を閲覧モードで表示すると、印刷レイアウトで表示中の 2 つ目のドキュメントで Tab キーが機能しない問題を修正します。
-   複数の文法ライブラリが読み込まれると Word がクラッシュするという問題を修正します。
-   2 つまたは 3 つのストローク以降、インク ストロークが表示されない問題を修正します。
-   Google Input Method Editor (IME) を使用する場合に引用符が表示されない問題を修正します。
-   ユーザーがコンテンツ コントロールを使用するか、または不連続の選択を行うと、手書き入力が使用できない問題を修正します。

### <a name="office-suite-feature-updates"></a>Office スイート: 機能の更新
-   **フィードバックの提供:** [ファイル] \> [フィードバック] にアクセスして、新しい機能を提案するか、気に入った点や正しく機能していない点を Microsoft に報告してください。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Microsoft Office のセキュリティ更新プログラム (3204068)

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   ドイツ語のキーボードで CTRL + ALT + 7、または CTRL + ALT + 8 を使用すると、適切な文字が挿入されず、ユーザー フィードバック ツールが開くという問題を修正します。
-   Office をインストールまたは更新すると、Windows 7 で TraceLogging がクラッシュする問題を修正します。
-   インクを使用して描画し、マウスを使用しているときに、マウス ボタンを放すとインクが若干ずれるという問題を修正します。
-   Office ドキュメントに SVG 画像を挿入し、その後ドキュメントを保存してから再び開くと、SVG 画像が表示されなくなるという問題を修正します。
-   Fix an issue where Office shows the following error message during activation for non-English users: "The maximum length of the product key is 25 characters."
-   フレームの Z オーダーが機能しなくなる、または正しく表示されなくなる可能性のある VBA フォームに関する問題を修正します。
-   Configuration Manager によってトリグされた更新プログラムが、レジストリの UpdateChannel 設定を有効な更新チャネルではない更新プログラムに変更する問題を修正します。



## <a name="version-1609-january-10"></a>バージョン 1609: 1 月 10 日
*バージョン 1609 (ビルド 7369.2102)*

注: Microsoft Security Bulletin [MS17-002](https://technet.microsoft.com/library/security/ms17-002) で説明されているセキュリティ更新プログラムは、このチャネル リリースの Word のバージョンには適用されません。

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   [メジャーの編集] ダイアログ ボックスを使用すると Excel がクラッシュする問題を修正します。

### <a name="powerpoint-non-security-updates"></a>PowerPoint: セキュリティ以外の更新プログラム
-   図形の操作によって、PowerPoint がクラッシュすることがある問題を修正します。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   Windows 10 バージョン 1607 (Anniversary Update とも呼ばれる) の特定のモニター構成で、セカンダリ モニターを共有するオプションが表示されない問題を修正します。
-   共有先がサード パーティ製の RDP 実装を使用している場合に共有コンテンツにズームすると、Skype for Business がクラッシュする問題を修正します。
-   Skype for Business がポート 443 で SIP サーバーに接続し、プロキシ サーバーが存在している場合、およびプロキシがこのような接続を許可しない場合に、サインイン プロセスで大幅に遅延が発生する問題を修正します。EnableDetectProxyForAllConnections DWORD レジストリ エントリを HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync の下に追加し、値を 1 に設定すると修正は有効になります。

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   InsertXML メソッドを使用する際に、実際の画像ではなく、画像への壊れたリンクのプレースホルダーが表示される問題を修正します。

