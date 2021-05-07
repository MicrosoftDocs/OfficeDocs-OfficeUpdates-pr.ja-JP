---
title: 月次エンタープライズ チャネル リリースのアーカイブ リリース ノート
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の月次エンタープライズ チャネル リリースのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: 171f5436b47f6d35bac641005849c165bf5b6e88
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026387"
---
# <a name="archived-release-notes-for-monthly-enterprise-channel"></a>月次エンタープライズ チャネルのアーカイブ リリース ノート
これらのリリース ノートには、Office 365 ProPlus、Visio Pro for Office 365、Project Online デスクトップ クライアント、および Office 365 Business の月次エンタープライズ チャネルの更新プログラムに含まれる新機能およびセキュリティ以外の更新に関する情報が記載されています。

 > [!NOTE]
>- Microsoft では多くの場合、一定期間にわたって毎月、機能 (および場合によっては修正プログラム) を展開します。  ここで説明した内容がすぐに表示されない場合は、間もなく利用できるようになります。 [詳細情報](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- Microsoft Teams の Office 365 ProPlus の既存のインストールについて: 7月の上旬から、Office 365 ProPlus (および Office 365 Business) の更新に Microsoft Teams が含まれます。  Teams が追加される日付は、使用している更新プログラム チャネルによって異なります。 追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](/deployoffice/teams-install)」を参照してください。



## <a name="version-2010-december-08"></a>バージョン 2010: 12 月 08 日
*バージョン 2010 (ビルド 13328.20478)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a>機能の更新プログラム
### <a name="excel"></a>Excel

- **Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365、Microsoft 365、Power BI Pro サービス プランを使用する組織の Insider にロールアウトされるようになりました。 必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。 Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。 [詳細情報](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください

### <a name="outlook"></a>Outlook

- **タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新

- **メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。 アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。

### <a name="powerpoint"></a>PowerPoint

- **アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します

- **透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。<br />[ブログの投稿](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)の詳細情報をご覧ください


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="access"></a>Access

- Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。


### <a name="outlook"></a>Outlook

- Outlook でクラウド設定を有効にしているユーザーに対して、2つ目の空白の署名を作成するという問題が修正されました。


- ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。


- ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。


- 返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。


- OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。


- IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.  REG_DWORD IncludeFileTimesInDataObject.  0 = filetimes は除外されます。  1 = (既定) filetimes が含まれます。


- MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 


- 他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信するという問題が修正されました。


- ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。


### <a name="powerpoint"></a>PowerPoint

- これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。


- マージ中に IRM/ 保護されたドキュメントを使用しているときに発生する問題を解決します。


- Word から Powerpoint への数式のコピーと貼り付けに関する問題を修正した。


### <a name="project"></a>Project

- リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。


- プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。


- タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。


### <a name="visio"></a>Visio

- 問題が修正され、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。


### <a name="word"></a>Word

- Word から Powerpoint への数式のコピーと貼り付けに関する問題を修正した。


### <a name="office-suite"></a>Office スイート

- Microsoft 365 エンドポイントのデータ損失防止が、ディスク上の Office ドキュメントを分類できない問題を修正しました。


- Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。 このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。


- コメントから Excel にテキストをコピーして貼り付けるときにエラーが発生する問題を修正しました。


- 特定のシナリオで、[名前を付けて保存] の実行に失敗する問題を修正しました。


- 同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-december-08"></a>バージョン 2009: 12 月 08 日
*バージョン 2009 (ビルド 13231.20620)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)

## <a name="version-2009-november-10"></a>バージョン 2009: 11 月 10 日
*バージョン2009 (ビルド 13231.20514)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a>機能の更新プログラム
### <a name="excel"></a>Excel

- **秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。

### <a name="powerpoint"></a>PowerPoint

- **秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。

### <a name="word"></a>Word

- **秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="outlook"></a>Outlook

- 返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。


- 代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。


- 件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。


- 一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処しました。


- キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処しました。


- ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。


- ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。


### <a name="powerpoint"></a>PowerPoint

- 特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。


- セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題を修正しました。


- ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。


### <a name="project"></a>Project

- イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。


- リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。


- プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。


### <a name="word"></a>Word

- スタイル ギャラリー ダイアログの問題を修正しました。


### <a name="office-suite"></a>Office スイート

- [図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。


- Microsoft 365 エンドポイントのデータ損失防止が、ディスク上の Office ドキュメントを分類できない問題を修正しました。


- Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。 このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-november-10"></a>バージョン 2008: 11 月 10 日
*バージョン 2008 (ビルド 13127.20760)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="excel"></a>Excel

- マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。


- Excel で 1 つまたは複数の数式を計算しようとする際に発生する、Excelはリソース不足になりましたというエラーが生じる問題が修正されました。


- Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。


- OLAP PivotTables を更新するときにハングする場合がある問題が修正されました。


- ブックをロードした後、特定の関数の結果が不正確であるという問題が修正されました。


- XLAM アドイン参照と名前付き範囲に関連するアプリケーションが予期せず終了する問題が修正されました。

### <a name="outlook"></a>Outlook

- 返信または転送時に中国語メッセージのヘッダーが文字化けする問題を修正しました。


- 件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。


- 代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。


- グループ予定表で検索結果が返されない問題を修正しました。


- ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。


- Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。


- ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。


- オプションの接続エクスペリエンスが Web アドインの読み込みをブロックする問題を修正しました。<br />
  [ブログの投稿](https://developer.microsoft.com/ja-JP/office/blogs/outlook-add-ins-and-optional-connected-experiences/)の詳細情報をご覧ください


### <a name="powerpoint"></a>PowerPoint

- これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。


- ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。


### <a name="office-suite"></a>Office スイート

- Microsoft 365 エンドポイントのデータ損失防止を使用して Office Update に System Center Configuration Manager またはその他の管理ツールを利用する商用顧客の問題に対処しました。

- Office アドインのメッセージング API が機能しない問題を修正します。



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2008-october-13"></a>バージョン 2008: 10 月 13 日
*バージョン 2008 (Build 13127.20638)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a>機能の更新プログラム
### <a name="excel"></a>Excel

- **質問がある場合のExcel への質問:** Excel のアイデアを使用すると、データについて質問をすることができます。数式の記述に時間を費やす必要はありません(英語のみ使用可能)。 [詳細情報](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。  ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。 新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。 この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。 [詳細情報](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください

- **PDF に接続:** PDF からデータに接続、インポート、更新します。 [詳細情報](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。 [詳細情報](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。 [詳細情報](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a>Outlook

- **クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Outlook の新しいプロファイル カード:** Outlook の新しいプロファイル カードは、組織ビューが改善され、Outlook Web のカード スタイルに一致します。 [詳細情報](https://support.office.com/article/e80f931f-5fc4-4a59-ba6e-c1e35a85b501)

### <a name="powerpoint"></a>PowerPoint

- **固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。  ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。 新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。 この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。 [詳細情報](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください

### <a name="word"></a>Word

- **固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。  ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。 新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。 この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。 [詳細情報](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="access"></a>Access

- この問題は解決されました。これで、Office のクイック実行アプリケーション以外でも ODBC ドライバーを使用できます。


- テキストを編集するため [ズーム] ボックスを起動する (Shift + F2) ときに、Access がクラッシュする可能性がある問題が修正されました。


- この問題は解決されましたので、クラッシュが発生しなくなったはずです。


### <a name="excel"></a>Excel

- IFNA () を使用する数式が含まれている場合、破損したワークブックに関する警告を発する可能性がある問題を修正しました。


- シートの一番上の行を固定した後にクイック分析を使用すると Excel がクラッシュする可能性がある問題を修正しました。


- Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。


- Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。


- ' 前 ' と ' 後 ' のフィルター条件が逆転する バグをPivotDateFilter Api で修正しました。


### <a name="outlook"></a>Outlook

- ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。 この Web ページをダウンロードする必要がありますか?  Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」


- 右クリックのコンテキストメニューが検索コントロールに表示されない問題の原因を解決しました。


- コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。


- これにより、受信者を編集しているときに時折クラッシュする問題が修正されました。


- 一部のユーザーにスケジュール アシスタント ページが表示されない問題を解決しました。


- 添付ファイルのアップロードのパフォーマンスの問題に対処します。


- [ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。


- クラウドの添付ファイルを開くときに、開こうとしていたドキュメントの代わりに、安全なリンクの ページにエラーが表示される原因となった問題に対処します。


- クラウドの添付ファイルを操作するときに、ユーザーに時折クラッシュが発生する問題を修正しました。


- 隅にある [X] をクリックして共有の予定表を閉じることができない問題に対処します。


- 共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。


- 特定の状況で代理人が会議を辞退したときに、マネージャーのカレンダーから削除されないという問題を解決しました。


- 共有カレンダーの改善機能を使用している一部のユーザーが、新しく追加された共有カレンダーを表示できない問題を解決しました。


- [共有予定表の改善機能を有効にする] 設定が既存の共有予定表に適用されないことがある問題に対処します。


- プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。


### <a name="powerpoint"></a>PowerPoint

- PowerPoint アプリのクラッシュの原因となった問題を修正しました。


- セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。


- この変更により、[エクスポート] ボタンをクリックしてもエクスポートされないという [アニメーション GIF にエクスポート] 機能の問題に対処します。


### <a name="project"></a>Project

- SharePoint タスクリストに接続されているプロジェクトのプロジェクト終了日が更新されない問題を修正しました。


- リソースに複数のコスト単価表が定義されている場合に、残りのコストが正しく計算されない場合がある問題を修正しました。

### <a name="skype"></a>Skype

- ダンス絵文字の肌の色を中間色に変更しました。


### <a name="visio"></a>Visio

- テキストを配置するとリアルタイムのプレビューがクラッシュする問題がお客様から報告されました。 7 月のフォークで最も多く報告されているクラッシュ。


### <a name="word"></a>Word

- マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。


- スタイル ギャラリー ダイアログの問題を修正しました。


- Word を起動するときにクラッシュの原因となっている可能性のあった問題を解決しました。


- 基本スタイルが標準スタイルで更新されない問題を修正しました。


- ドキュメントを開くときに、ユーザーがクラッシュする可能性がある問題が修正されました。


- 図形のサイズを変更すると、ユーザーのコンテンツが失われる場合がある問題を修正しました。


- サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されました。


- 新しいメールに返信、または新しいメールを作成するときにユーザーにクラッシュが発生する問題を解決しました。


- この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレント保存の状態に陥ることがある問題が修正されました。


### <a name="office-suite"></a>Office スイート

- この変更は、 d2d1.dll の読み込みに失敗したために、Office アプリを起動したときにクラッシュする場合があった問題に対処します。


- GIF/アニメーション model3D を使用したアイドル時の高い CPU 使用率を修正します


- Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。 このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-october-13"></a>バージョン 2007: 10 月 13 日
*バージョン 2007 (ビルド 13029.20708)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="excel"></a>Excel

- ' 前 ' と ' 後 ' のフィルター条件が逆転する バグをPivotDateFilter Api で修正しました。



[//]: # (BUG詳細 コンテンツを削除しないでください。終了)

## <a name="version-2007-september-08"></a>バージョン 2007: 9 月 08 日
*バージョン 2007 (ビルド 13029.20534)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a>機能の更新プログラム
### <a name="outlook"></a>Outlook

- **IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。 [詳細情報](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。 Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。 この機能は既定でオンになっています。 オフにするには、[オプション] > [一般] > [開始オプション] に移動します。

### <a name="word"></a>Word

- **テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。

### <a name="office-suite"></a>Office スイート

- **タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。 UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。<br />[ブログの投稿](https://blog-insider.office.com/2020/02/20/improved-pane-management/)の詳細情報をご覧ください


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="access"></a>Access

- この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。


### <a name="excel"></a>Excel

- 改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。


- LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。


### <a name="outlook"></a>Outlook

- インシデント通知アラートのフォーマットの問題を解決しました。


- Outlook ユーザーにコンパクト ビューでのナビゲーションの問題が表示される問題に対処しました。


- ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。


- スケジュール アシスタント ページの表示が失敗する問題を解決しました。


- セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。


- [共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。


- Outlook で検索候補を取得できない問題を解決しました。


- SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。


- 保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。

- 新しいメールに返信または作成するときにユーザーにクラッシュが発生する問題に対処しました。


### <a name="powerpoint"></a>PowerPoint

- PowerPoint アプリでクラッシュする問題を修正しました。


### <a name="project"></a>Project

- Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。


- 複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。


- [リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。


- 正常ではない状態になったプロジェクトを開くことができない問題を修正しました。



### <a name="office-suite"></a>Office スイート

- 特定の状況下で UI 要素またはコンテンツが表示されない問題を修正しました。特に、発表者ツールのオン/オフ、または複数のモニターの使用に関して発生しました。


- 製品版への移行が完了した場合でも、ランタイムメッセージが表示される問題が修正されました。 この問題の修正では、サービスが追加された製品を適切に計算するようにしました。 新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。


- 以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。 この問題は修正されました。



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2006-september-08"></a>バージョン 2006: 9 月 08 日
*バージョン 2006 (ビルド13001.20648)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)

## <a name="version-2006-august-11"></a>バージョン 2006: 8 月 11 日
*バージョン 2006 (ビルド 13001.20520)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a>機能の更新プログラム
### <a name="excel"></a>Excel

- **アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。

- **他のユーザーを混乱させずに、フィルター処理して並べ替える:**、Sheet View で他のユーザーとの共同作業を行いながら Excel ファイルの並べ替えやフィルター処理ができるようになりました。 この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。 [詳細情報](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

### <a name="outlook"></a>Outlook

- **グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。

- **アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。

- **Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか? 今後は、必要に応じてオフにすることができます。<br />[ブログの投稿](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/) の詳細情報をご覧ください

- **メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。

### <a name="powerpoint"></a>PowerPoint

- **アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。

- **PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。 お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。

### <a name="word"></a>Word

- **アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。

- **別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。 [書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。<br />[ブログの投稿](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/) の詳細情報をご覧ください

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="access"></a>Access

- クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。

- ID (オートナンバーなど) フィールドが含まれるリンク付きの SQL 表を挿入する場合についての問題を解決しました。


### <a name="excel"></a>Excel

- SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。

- 改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。

- アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。

- 読み取り専用モードのブックに対して、ドキュメント分類を自動的に行った可能性があります。

### <a name="onenote"></a>OneNote

- リソースの使用率を低下させて、共同編集状態の検出機能を改善します。

### <a name="outlook"></a>Outlook

- SVG 画像のコピーと貼り付けの問題を修正しました。

- Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。

- クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処します。

- セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。

- Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処します。

- 共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。

- ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501 年 1 月 1 日に設定される問題に対処します。

### <a name="project"></a>Project

- プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。

- 100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。

- URL が .com で終了している場合に、Project Web App からプロジェクト デスクトップ クライアントでプロジェクトを開くことができない問題が修正されました。

### <a name="word"></a>Word

- SVG 画像のコピーと貼り付けの問題を修正しました。

### <a name="office-suite"></a>Office スイート

- 以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。

- タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります

- レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-august-11"></a>バージョン 2005: 8 月 11 日
*バージョン 2005 (ビルド 12827.20656)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)

## <a name="version-2005-july-14"></a>バージョン 2005: 7 月 14 日
*バージョン 2005 (ビルド 12827.20538)*

セキュリティ更新プログラムのリストは[こちら](./microsoft365-apps-security-updates.md)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a>機能の更新プログラム
### <a name="outlook"></a>Outlook

- **より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。 [詳細情報](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="access"></a>Access

- アプリケーションのクラッシュを発生させずに、Date/Time Extended データ型をコードに呼び出すことができるように問題が修正されました。

- この問題は修正されて、最新の Access バージョンに戻し、 DAO/VBA を使用して 10 進数データ型を管理および編集することができます。

### <a name="excel"></a>Excel

- Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。

- 同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。

- SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。

- ピボット テーブル をチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処します。

### <a name="outlook"></a>Outlook

- ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。

- Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。

- Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。

- Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効ですという警告が表示される問題に対処しました。 このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした」。

- 一部のシナリオで、断続的なハングやクラッシュを発生させる原因となっていた問題に対処しました。

- 共有された Calendar - Outlook カレンダー の改良版のユーザーに予定表のエラーが表示される問題を解決しました。

- ユーザーが Outlook ルールを更新すると、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" と表示される問題に対処します。

- ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501 年 1 月 1 日に設定される問題に対処します。

- M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処します。

- CLP の監査イベントで、返信/転送ラベルの問題に対応しました。


### <a name="powerpoint"></a>PowerPoint

- これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。

- 提案ウィンドウでクラッシュする問題を修正しました。


### <a name="project"></a>Project

- プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。

- 100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。

### <a name="skype"></a>Skype

- ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。 この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。 また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。

### <a name="word"></a>Word

- 一部のアプリケーションからコンテンツをドラッグしたときにクラッシュする問題の原因となっていた可能性がある問題が解決されました。

### <a name="office-suite"></a>Office スイート

- この変更により、Gif や3D モデルなどのアニメーション コンテンツを読み込んだり、再生したりするときに、ハングする可能性があります。

- Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。

- この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。

- この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。

- HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。 この変更により、この問題は修正されます。


[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2004-july-14"></a>バージョン 2004: 7 月 14 日
*バージョン 2004 (ビルド 12730.20602)*

セキュリティ更新プログラムのリストは[こちら](./microsoft365-apps-security-updates.md)

## <a name="version-2004-june-09"></a>バージョン 2004: 6月 09 日
*バージョン 2004 (ビルド 12730.20430)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a>機能の更新プログラム
### <a name="access"></a>アクセス

- **数回クリックするだけで表を追加する:** [テーブルの追加] 作業ウィンドウを使用すると、作業中も開いたまま、リレーションシップやクエリにテーブルを追加できます。 [詳細情報](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。<br />[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください

- **Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。

- **ブックの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをブックで使用できます。 開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。 [詳細情報](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />[ブログの投稿](https://blog-insider.office.com/2020/04/06/premium-creative-content/)の詳細情報をご覧ください

### <a name="outlook"></a>Outlook

- **最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。<br />[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください

- **所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。 ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。<br />[ブログの投稿](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/) の詳細情報をご覧ください

- **予定表が一新されます:** 予定表を簡単に読みやすくなるビジュアル アップデートをご覧ください。 [詳細情報](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />[ブログの投稿](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/) の詳細情報をご覧ください

- **メッセージの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをメール メッセージで使用できます。 開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。 [詳細情報](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />[ブログの投稿](https://blog-insider.office.com/2020/04/06/premium-creative-content/)の詳細情報をご覧ください

### <a name="powerpoint"></a>PowerPoint

- **最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。<br />[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください

- **プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。 [詳細情報](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/) の詳細情報をご覧ください

- **スライドの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをプレゼンテーションで使用できます。 開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。 [詳細情報](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />[ブログの投稿](https://blog-insider.office.com/2020/04/06/premium-creative-content/)の詳細情報をご覧ください

### <a name="word"></a>Word

- **インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。 個別のストロークまたは文字全体を選択できます。 [詳細情報](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。<br />[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください

- **ドキュメントの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをドキュメントで使用できます。 開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。 [詳細情報](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />[ブログの投稿](https://blog-insider.office.com/2020/04/06/premium-creative-content/)の詳細情報をご覧ください

### <a name="office-suite"></a>Office スイート

- **秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="excel"></a>Excel

- ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。

- Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。

- Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。

- ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。

### <a name="outlook"></a>Outlook

- ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。

- Outlook の終了中に応答が停止する問題に対処しました。

- ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。

- Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。

- Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。

- フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。

### <a name="project"></a>Project

- フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。

- Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。

### <a name="office-suite"></a>Office スイート

- シンボリック リンクのハード リンクを試みる際に、更新の失敗を引き起こしていたクイック実行の問題を修正しました。

- HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。 この変更により、この問題は修正されます。

- この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。

- この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。

- この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-june-09"></a>バージョン 2003: 6月 9 日
*バージョン 2003 (ビルド 12624.20708)*

セキュリティ更新プログラムのリストは[こちら](./microsoft365-apps-security-updates.md)


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題
### <a name="office-suite"></a>Office スイート

- この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-may-12"></a>バージョン 2003: 5 月12 月
*バージョン 2003 (ビルド 12624.20588)*

セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a>機能の更新プログラム
### <a name="access"></a>Access

- **クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。 SQL ビューでテキストを検索および置換します。 リレーションシップ ウィンドウ内の複数のテーブルを選択します。

### <a name="excel"></a>Excel

- **複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。 [詳細情報](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />[ブログの投稿](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)の詳細情報をご覧ください

- **ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。

- **6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。 [詳細情報](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。 [詳細情報](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />[ブログの投稿](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)の詳細情報をご覧ください

- **すぐに読んで返信する** ブックを開かずに、メールからコメントおよびメンションに直接返信します。

### <a name="outlook"></a>Outlook

- **人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。 [詳細情報](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- **グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。 管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。 これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。 また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。

- **受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。 [To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。

- **キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ? Outlook はこれを検出し、接続を支援します。

### <a name="powerpoint"></a>PowerPoint

- **PowerPoint におけるリアルタイム コラボレーションが高速に:** PowerPoint でリアルタイム コラボレーションを高速で行えます。

- **オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。 ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。 [詳細情報](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。

- **簡単な GIF:** 1 つのスライド、1 つのフレーム。 PowerPoint でループ GIF を簡単に作成できます。 [詳細情報](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />[ブログの投稿](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)の詳細情報をご覧ください

- **図の向上: コネクタが改善されており、インクの滑らかな変換のプロセスが** によって、アイデアをより自信のあるインクにすることができます。 [詳細情報](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。<br />[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)の詳細情報をご覧ください

### <a name="word"></a>Word

- **ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。

- **他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。

### <a name="office-suite"></a>Office スイート

- **大規模なファイルをインクリメンタルに開く:** プレゼンテーションの一部 (たとえば、大規模なビデオや画像) のダウンロードが終了していなくても、大規模な Powerpoint プレゼンテーションを開いたり操作したり、ダウンロードしたりする機能。


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a>解決済みの問題

### <a name="excel"></a>Excel

- Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。

- ソース ブックが閉じている場合、外部リンクが塗りつぶし時に更新されない問題に対処しました。


### <a name="onenote"></a>OneNote

- ページのバージョン履歴を作成する頻度を一時的に変更することで、同期およびサービスの安定性が改善されます。


- ごみ箱へのページの移動を一時的に無効にすることにより、同期およびサーバーの安定性が改善されました。 代わりに、ページを削除するユーザーにはページを完全に削除するか確認するダイアログが表示されます。


- OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性が改善されました。 この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。


- OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。 ローカルのノートブックはこの影響を受けません。


- OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。


- 全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。


### <a name="outlook"></a>Outlook

- 終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。


- マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていたユーザーの問題に対処しました。


- サードパーティ製の MAPI アプリケーションでクラッシュが発生した問題に対処しました。


- Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。


- Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。


- フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。


### <a name="project"></a>Project

- タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。


- OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。


- サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。


- [無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。


- [無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。


- 以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。


- 実績作業時間の保護設定を有効にしている場合に、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。


- フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。


### <a name="word"></a>Word

- マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていたユーザーの問題に対処します。

### <a name="office-suite"></a>Office スイート

- この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。

- この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

> [!NOTE]
> Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。