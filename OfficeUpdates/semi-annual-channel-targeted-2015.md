---
title: 2015での半期チャネル (対象指定) リリースのリリースノート
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/8/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の半期チャネル (対象指定) リリースのリリースノートを IT 担当者に提供します (2015)
ms.openlocfilehash: 4b6eb5b96fddc57d8a1f64adfaeb10166d541c42
ms.sourcegitcommit: 358a0cbd1b722d309556c50d53abbe6c1a348f60
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2019
ms.locfileid: "32439142"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2015"></a>2015での半期チャネル (対象指定) リリースのリリースノート

これらのリリースノートには、2015で Office 365 ProPlus の半期チャネル (対象指定) 更新プログラムに含まれる新機能、セキュリティ更新プログラム、セキュリティ以外の更新プログラムに関する情報が記載されています。
 
> [!NOTE]
> - また、Visio Pro for Office 365 および Project Online デスクトップ クライアントの新機能、セキュリティ更新プログラム、セキュリティ以外の更新プログラムについても説明しています。
> - ここに記載されている情報は、Business Premium など一部の Office 365 プランに付属する Office のバージョンの、Office 365 Business にも該当します。
> - 半期チャネル (対象指定) は、2017年9月より前に段階的提供チャネルの最初のリリースという名前でした。


## <a name="version-1509-december-8"></a>バージョン 1509:12 月8日
*バージョン 1509 (ビルド 6001.1043)*

### <a name="onenote-non-security-updates"></a>OneNote: セキュリティ以外の更新プログラム
-   Windows 以外のデスクトップ クライアントではネイティブの XPS レンダリングがサポートされていないため、Windows クライアントを使用して作成した XPS または印刷イメージが、Windows 以外のデスクトップ クライアントで赤の X 印として表示されるという問題の修正。

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   複数の段落にまたがっているブックマークを作成しても、そのメールを受信して [移動] を使用するとブックマークの最初の段落のみが選ばれているという問題の修正。

### <a name="skype-for-business-security-updates"></a>Skype for Business: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-128](https://go.microsoft.com/fwlink/?LinkId=690559): リモートでのコード実行に対応する Microsoft Graphics コンポーネント用のセキュリティ更新プログラム (3104503)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   アプリ共有セッションが特にトラフィックの集中時に失敗するという問題の修正。
-   Office 2016 のインストール後に最初に起動するアプリが Skype for Business であった場合に、Skype for Business が クラッシュするという問題の修正。

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-131](https://go.microsoft.com/fwlink/?LinkId=699410): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3116111)

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   使用するフォントによっては、改行なしハイフンが四角形として表示されるという問題の修正。

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   更新プログラムをバックグラウンドでダウンロードするための既定のトランスポートが、Cached/BITS から HTTP に変更。
-   自動アップグレードの際にライセンス関連の操作によるエラーが発生し、Office がインストールされないという問題の修正。
-   Office プレインストール キットを監査モードで実行している Windows 7 OEM コンピューターで Office 2016 にアップグレードすると、ライセンス認証時にエラー 0x80070005 が発生するという問題の修正。



## <a name="version-1509-november-10"></a>バージョン 1509:11 月10日
*バージョン 1509 (ビルド 6001.1038)*

### <a name="access-security-updates"></a>Access: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="excel-non-security-updates"></a>Excel: セキュリティ以外の更新プログラム
-   クエリ作成用マクロを記録するとコンパイル エラーになるという問題の修正。
-   クエリ エディター内の列を削除した後にクエリを更新すると、テーブルの末尾に空白列が表示されるという問題の修正。
-   クエリ テーブルの [クイック分析] にある [スパークライン] タブを選択すると、予期しないエラーが発生するという問題の修正。
-   クエリ テーブルで切り取り/貼り付け操作を実行後、[ブック クエリ] ウィンドウを使用してクエリを更新できないという問題の修正。
-   クエリを更新すると、関連付けられているクエリ テーブルのシートにフォーカスが移動するという問題の修正。
-   サポートされている OData バージョンに関するエラー メッセージから、Power Query という文言を削除。
-   製品がまだアクティブ化されていないうちに Power Query 機能が使用可能として表示されるが使用はできないという問題の修正。
-   [ファイル] \> [アカウント] \> [Excel について] の Dotlesscss の URL の更新。

### <a name="onenote-security-updates"></a>OneNote: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   Outlook にテキストを貼り付ける場合、貼り付けるテキストのサイズがウィンドウの高さを超えるとテキスト全体が表示されないという問題の修正。

### <a name="powerpoint-security-updates"></a>PowerPoint: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="project-security-updates"></a>Project: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="publisher-security-updates"></a>Publisher: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="skype-for-business-security-updates"></a>Skype for Business: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)
-   マイクロソフト セキュリティ情報 [MS15-123](https://technet.microsoft.com/library/security/ms15-123): 情報漏えいに対処する Skype for Business および Microsoft Lync 用のセキュリティ更新プログラム (3105872)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   2 つの入力用マイクがあるデバイス上におけるオーディオ ノイズの問題の修正。
-   ノート PC をスリープ モードから再開した後、Skype クライアントに再びサインインするまでの間、ユーザーが正常に会議に参加できないという問題の修正。
-   ユーザーが利用できる機能を把握できるようにするための、コンテキスト メッセージのサポートの追加。
-   [音声会議への参加方法] ダイアログ ボックス内のテキストの更新。設定を変更するための UI 内の場所が正しく示されるようになりました。
-   送信および受信の両方のネットワークの問題がある場合にユーザーに表示される通知に関する問題の修正。

### <a name="visio-security-updates"></a>Visio: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   脚注が [ページごとに振り直し] に設定されているドキュメントをバックグラウンドで印刷すると、脚注の番号が、Word 上で表示される番号と、印刷される番号で異なるという問題の修正。
-   リアルタイムの共同編集において、ユーザーがリアルタイム編集時に他のユーザーに表示されなかったり、使用可能な情報が表示されなかったりするなどという、OneDrive 上に格納されているファイルのリアルタイム共同編集での問題の修正。
-   SharePoint または OneDrive から開いたドキュメントのリアルタイム共同編集中に Word がクラッシュするという問題の修正。
-   表を Outlook の HTML メールに配置し、ウィンドウのサイズを変更すると、表が正しく表示されないという書式設定の問題の修正。

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-116](https://technet.microsoft.com/library/security/ms15-116): リモートでのコード実行に対応する Microsoft Office 用のセキュリティ更新プログラム (3104540)

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   SharePoint Online からファイルをユーザーが開こうとすると、繰り返しサインインを求めるプロンプトが表示されるという問題の修正。
-   手動アップグレードのときに、タスク バーに固定されているショートカットがすべてのユーザーで削除されないという問題の修正。
-   クイック実行の手動アップグレード処理において、アップグレードに関して生じる可能性がある問題をユーザーに警告するために、Outlook が Exchange Server 2007 に接続されているかどうか、または Business Contact Manager がインストールされているかどうかを検出する機能の追加。
-   アンインストールまたはアップグレード中に処理を終了させるためのダイアログの見やすさの改善。このダイアログは、開かれているアプリや他の UI に隠れてユーザーから見えなくなることがありました。
-   ドメインとクラウド ドメインの両方に参加していると識別されているコンピューターを使用していると、ユーザーが Office アプリに自動的にサインインされないという問題の修正。



## <a name="version-1509-october-21"></a>バージョン 1509:10 月21日
*バージョン 1509 (ビルド 6001.1034)*

### <a name="onenote-non-security-updates"></a>OneNote: セキュリティ以外の更新プログラム
-   カラー ピッカーで境界線に同じ色を 2 回選ぶと、OneNote がクラッシュするという問題の修正。

### <a name="outlook-non-security-updates"></a>Outlook: セキュリティ以外の更新プログラム
-   メールの署名を編集する際に、メールの署名に段落が複数あると、スクリーン リーダーが最初の段落のみを読み取るという問題の修正。
-   電子メールに書き込みまたは返信するときにカーソルが正しい位置にないという問題の修正。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   メモリ不足の状態で、共有のデスクトップまたはアプリを表示しようとすると、接続が切断され、自動的に共有のデスクトップまたはアプリに再び参加して表示しようと繰り返すという問題の修正。
-   参加者数が増加すると、共有デスクトップの操作性が悪化するという問題の修正。
-   多要素認証が構成されていると、1 日中何度も電話認証のプロンプトを受け取るという問題の修正。

### <a name="visio-non-security-updates"></a>Visio: セキュリティ以外の更新プログラム
-   Visio を終了して再び開くと、アイコンとして表示するために挿入された Word オブジェクトが空白であるという問題の修正。

### <a name="word-non-security-updates"></a>Word: セキュリティ以外の更新プログラム
-   ドキュメントが SharePoint Server 2013 にあると、共同編集が利用できず、ドキュメントがロックされるという問題の修正。
-   テーブル内のコンテンツのスタイルに [非表示] オプションを含むものが適用されていても、テーブルが表示されるという docx ドキュメントでの問題の修正。
-   自動修正の実行後、相対ハイパーリンクを含むドキュメントが保存できないという問題の修正。
-   見開きページのインデント幅を設定しているドキュメントの段落編集中に、行が移動するという問題の修正。
-   部分ピクセルが無効になっていると、編集中に行の表示に一貫性がないという問題の修正。
-   複数のコメントのうち最初のコメントが [完了] としてマークされている場合、コメントのポップアップをクリックすると、クラッシュするという問題の修正。
-   誤った改行に関する問題の修正。
-   ヘッダーかフッターにテキストボックスを含むドキュメントで TransformDocument 関数を使用するマクロを実行すると、クラッシュするという問題の修正。
-   .docm ドキュメントで、すべての ActiveX コントロールを削除するとドキュメントを開いたときにエラーが発生するという問題の修正。
-   ヘッダー内をクリックしたとき、ContentControlOnExit イベントがトリガーされないという問題の修正。
-   変更履歴の記録に同じ名前を持つ校閲者の削除が表示されるという問題の修正。
-   個人情報を削除するよう構成されているドキュメントでリアルタイムの共同編集を行うと、ドキュメントが保存される度に変更が変更履歴として表示されるという問題の修正。

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   Office 2016 へのアップグレード後、最初に Office アプリを開くと、アプリが機能制限モードで起動され、フル機能を取得するにはアプリの再起動が必要になるという問題の修正。
-   リモート デスクトップ サービスを実行しているコンピューターで共有コンピューターのライセンス認証を有効にして Office を実行している場合、アプリを開くと、ユーザーにボリューム ライセンス版の Office を使用する必要があることを示すエラーが発生する問題の修正。
-   インストールが約 90% 完了した時点で滞るという問題の修正。
-   製品名が不必要にローカライズされている問題の修正。
-   "操作アシスト" の ToolTip と KeyTip が一致せず、さまざまなローカライズされたバージョンのリボンにある他の KeyTip と競合するという問題の修正。
-   Office 2013 から Office 2016 へのアップグレード後、Windows が Outlook を新しいアプリとして表示しているという問題の修正。
-   Office 2013 バージョン 15.0.4615.1002 (2014年 5 月) から Office 2016 へアップグレードすると、0x80041015 エラーが発生するという問題の修正。



## <a name="version-1509-october-5"></a>バージョン 1509:10 月5日
*バージョン 1509 (ビルド 4229.1029)*

### <a name="onenote-non-security-updates"></a>OneNote: セキュリティ以外の更新プログラム
-   Office 365 Business の問題の修正。OneNote を SharePoint と併用しようとすると、別のバージョンの Office にアップグレードする必要があることを示すエラー メッセージが表示されました。
-   Surface Pro 3 の問題の修正。ビデオ録画のプレビューで録画中の内容が表示されませんでした。

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: セキュリティ以外の更新プログラム
-   共有者が RDP で画面をロックしたときに閲覧者に表示される内容が変更されました。RDP の一時停止のイメージではなく、通知が閲覧者に表示されるようになりました。

### <a name="office-suite-non-security-updates"></a>Office スイート: セキュリティ以外の更新プログラム
-   クイック実行に関する問題の修正。Office 2016 に対する自動更新がエラーまたはユーザーによるキャンセルのために完了しなかった場合に Office 2013 クイック実行サービスが復元されませんでした。
-   クイック実行に関する問題の修正。Office 2016 に対する自動更新中にエラーが生じると更新が失敗し、Office 2013 アプリを使用することもアンインストールすることもできなくなりました。
-   クイック実行に関する問題の修正。Office 2016 に対する自動更新の試行中に再起動して再び自動更新を試行すると、更新エラーになり、シャットダウンできなくなりました。
-   クイック実行に関する問題の修正。コンピューターが再起動された場合、インストール時のストリーム タスクが復元できませんでした。
-   クイック実行に関する問題の修正。Office 2016 に対する手動更新中に再起動すると、タスクが "実行中" 状態のままになりました。
-   クイック実行に関する問題の修正。新しくインストールするアプリをそのインストール処理中に開始すると、「インターネット接続が失われました」というダイアログ ボックスが表示されました。
-   クイック実行に関する問題の修正。インストールがアクティブではないときにアプリ タイルが表示され、ユーザーがそのアプリ タイルをクリックしても起動しませんでした。
-   クイック実行に関する問題の修正。Office 2016 (Sr-latn-cr インストール) に対する自動更新の実行で、クライアントの言語が sr-latn-cr に変換されませんでした。
-   クイック実行に関する問題の修正。同一コンピューター上に複数の SKU の Office がインストールされている場合、自動更新が更新の準備中に失敗しました。
-   クイック実行に関する問題の修正。自動更新の実行中に手動更新を開始すると、エラー ダイアログが表示されました。
-   製品 UI の中の「アドイン (Add-ins)」という単語の更新。この単語の大文字/小文字の使い方が正しくありませんでした。



## <a name="version-1509-september-22"></a>バージョン 1509: 9 月22日
*バージョン 1509 (ビルド 4229.1024)*

このチャネルの最初のリリースです。Office 2016 アプリケーションが利用可能な最初のリリースです。

### <a name="excel-security-updates"></a>Excel: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-099](https://technet.microsoft.com/library/security/ms15-099): Microsoft Office の脆弱性により、リモートでコードが実行される (3089664)
-   マイクロソフト セキュリティ情報 [MS15-110](https://technet.microsoft.com/library/security/ms15-110): リモートでのコード実行に対処する Microsoft Office 用のセキュリティ更新プログラム (3096440)

### <a name="visio-security-updates"></a>Visio: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-081](https://technet.microsoft.com/library/security/ms15-081): Microsoft Office の脆弱性により、リモートでコードが実行される (3080790)

### <a name="word-security-updates"></a>Word: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-081](https://technet.microsoft.com/library/security/ms15-081): Microsoft Office の脆弱性により、リモートでコードが実行される (3080790)

### <a name="office-suite-security-updates"></a>Office スイート: セキュリティ更新プログラム
-   マイクロソフト セキュリティ情報 [MS15-081](https://technet.microsoft.com/library/security/ms15-081): Microsoft Office の脆弱性により、リモートでコードが実行される (3080790)
-   マイクロソフト セキュリティ情報 [MS15-099](https://technet.microsoft.com/library/security/ms15-099): Microsoft Office の脆弱性により、リモートでコードが実行される (3089664)
