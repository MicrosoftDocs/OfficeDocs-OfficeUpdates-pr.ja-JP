---
title: リリース ノートの現在のチャネル (プレビュー)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Slow の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: a8bf6662fb1c0fcd652f32068f3cf42e87fdae56
ms.sourcegitcommit: 8e0c8f95645d60a8651f7a2085a79c6e0bc02bdd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/30/2020
ms.locfileid: "46525058"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="7e36f-103">Office 向けリリース ノートの現行チャネル (プレビュー)</span><span class="sxs-lookup"><span data-stu-id="7e36f-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="7e36f-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の現行チャネル (対象指定) ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="7e36f-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="7e36f-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="7e36f-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="7e36f-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって現行チャネル (プレビュー) に展開されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="7e36f-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="7e36f-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="7e36f-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="7e36f-109">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="7e36f-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="7e36f-110">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7e36f-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="7e36f-111">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-111">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (削除しないでください)

## <a name="version-2007-july-29"></a><span data-ttu-id="7e36f-113">バージョン 2007: 7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-113">Version 2007: July 29</span></span>
<span data-ttu-id="7e36f-114">*バージョン 2007 (ビルド 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-114">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-116">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-116">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-117">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-117">Excel</span></span>

- <span data-ttu-id="7e36f-118">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-118">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="7e36f-119">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="7e36f-119">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="7e36f-120">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-120">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="7e36f-121">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-121">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="7e36f-122">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7e36f-122">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-123">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-123">Outlook</span></span>

- <span data-ttu-id="7e36f-124">**検索する場所を選択する:** 新しい検索範囲のドロップ ダウン リストを使用すると、検索結果を簡単に変更したり、現在のフォルダーと現在のメールボックスを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-124">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="7e36f-125">新しい検索についてフィードバックを提供してくれた皆さんに感謝します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-125">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="7e36f-126">このデザインと更新プログラムは、お客様のフィードバックを反映しています。</span><span class="sxs-lookup"><span data-stu-id="7e36f-126">This design and update came out of that feedback!</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-127">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-127">PowerPoint</span></span>

- <span data-ttu-id="7e36f-128">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-128">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="7e36f-129">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-129">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-130">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-130">Word</span></span>

- <span data-ttu-id="7e36f-131">**最新のコメントによる共同作業の向上:** オブジェクトにコメントを追加したり、同僚に @mention したり、コメント スレッドを解決して共同作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-131">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="7e36f-132">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-132">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-135">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-135">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-136">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-136">Outlook</span></span>

- <span data-ttu-id="7e36f-137">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-137">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="7e36f-138">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-138">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="7e36f-139">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-139">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-27"></a><span data-ttu-id="7e36f-141">バージョン 2007: 7 月 27 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-141">Version 2007: July 27</span></span>
<span data-ttu-id="7e36f-142">*バージョン 2007 (ビルド 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-142">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="7e36f-143">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7e36f-143">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="7e36f-144">バージョン 2007: 7 月 20 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-144">Version 2007: July 20</span></span>
<span data-ttu-id="7e36f-145">*バージョン 2007 (ビルド 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-145">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="7e36f-146">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7e36f-146">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="7e36f-147">バージョン 2007: 7 月 15 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-147">Version 2007: July 15</span></span>
<span data-ttu-id="7e36f-148">*バージョン 2007 (ビルド 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-148">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-150">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-150">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-151">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-151">Excel</span></span>

- <span data-ttu-id="7e36f-152">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-152">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="7e36f-153">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-153">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-156">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-156">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7e36f-157">Access</span><span class="sxs-lookup"><span data-stu-id="7e36f-157">Access</span></span>

- <span data-ttu-id="7e36f-158">リンクされた SQL テーブルが更新された場合、リンクされたテーブル マネージャーが主キーを要求する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-158">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="7e36f-159">クエリ エディターのクエリがスクロールして表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-159">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="7e36f-160">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-160">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="7e36f-161">Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できず、行が削除されたと誤って報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-161">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="7e36f-162">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-162">Excel</span></span>

- <span data-ttu-id="7e36f-163">http または https ベースではない URL が最近使用したリストに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-163">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="7e36f-164">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-164">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="7e36f-165">テーブルに関連付けられたクエリが編集されていない場合でも、特定のバージョンの Excel で作成したデータ モデル テーブルが [テーブル プレビュー] に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-165">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="7e36f-166">[名前の定義] \ [名前の適用] ダイアログの [相対/絶対参照を区別しない] 参照が原因で、数式が機能しなくなります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-166">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="7e36f-167">SharePoint/OneDriveにブックを保存すると、ユーザー設定のリボンタブの CustomUI XML が削除される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-167">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="7e36f-168">ファイルが読み取り専用である場合にのみ、ブックが読み取り専用であった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-168">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="7e36f-169">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-169">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="7e36f-170">レーダー チャートの主要な目盛線が正しく書式設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-170">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="7e36f-171">高度なデータ フィルターをクリアするとテーブルの書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-171">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="7e36f-172">埋め込まれた PDF 文書のフル パスがファイル名だけでなく文書の標題に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-172">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="7e36f-173">Wolfram クラウド コネクターを無効にしてから、Excel ブックを保存してもう一度開くとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-173">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="7e36f-174">ソルバー アドインを有効にして Excel を起動するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-174">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="7e36f-175">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-175">Outlook</span></span>

- <span data-ttu-id="7e36f-176">「To」行に 130 人を超える受信者がいる場合に Outlook がハングする問題を修正し、テキストのレンダリングのパフォーマンスも改善しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-176">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="7e36f-177">解像度の異なる複数のモニターを使用している場合に、Input Method Editor (IME) ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-177">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="7e36f-178">2 日を超えるイベントはそれ以降のすべての日に同じ終了時刻を表示するという「To Do バー」の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-178">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="7e36f-179">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501 年 1 月 1 日に設定される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-179">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="7e36f-180">ユーザーが配布リストの「送信者を指定して送信」または「代理送信」ができなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-180">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="7e36f-181">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-181">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="7e36f-182">以前に保存した予定を閉じると、次のエラーが表示される問題を修正しました。「別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。</span><span class="sxs-lookup"><span data-stu-id="7e36f-182">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="7e36f-183">アイテムの既定のフォルダーにコピーしますか?」</span><span class="sxs-lookup"><span data-stu-id="7e36f-183">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="7e36f-184">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-184">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="7e36f-185">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-185">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="7e36f-186">Outlook のユーザーが共有の予定表を使用した後、メッセージ一覧の更新が数分間停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-186">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="7e36f-187">予定表のリマインダーで、1 週間以内に行われる会議の正確な時刻が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-187">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="7e36f-188">メッセージに画像をインラインで挿入し、メッセージを下書きとして保存すると画像のサイズが変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-188">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="7e36f-189">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-189">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="7e36f-190">日本のユーザーに対してミニ カレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-190">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7e36f-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-191">PowerPoint</span></span>

- <span data-ttu-id="7e36f-192">ライブの共同編集セッション中に共同編集ギャラリーでユーザーのプレゼンス カラー インジケーターが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-192">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="7e36f-193">スライドのテキスト領域に HTML を貼り付けると、代わりにスライドの上部に作成されたテキスト ボックスに貼り付けられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-193">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="7e36f-194">発表者ビューですべてのスライドを選択し、Alt + Tabを使用して発表者ビューを終了し、スライド ショーに戻って [ショーの終了] をクリックすると、未処理の例外が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-194">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="7e36f-195">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-195">Project</span></span>

- <span data-ttu-id="7e36f-196">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-196">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="7e36f-197">URL の末尾が「.com」の場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-197">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="7e36f-198">特定の XML ファイルを開くと、Project がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-198">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="7e36f-199">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-199">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="7e36f-200">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-200">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="7e36f-201">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-201">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="7e36f-202">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-202">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="7e36f-203">固定期間タスクが 100% 完了しているが、実際の完了が指定されていない場合、タスク完了率が 100% 未満として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-203">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="7e36f-204">ベースラインのリセットまたは更新により、時間単位の予算コスト/作業リソースが変更され、ベースラインが誤った予算値を反映する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-204">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="7e36f-205">Government Community Cloud 環境でプロジェクト プランナのリンクが無効になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-205">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="7e36f-206">ライブラリがモダン モードの場合、SharePoint ドキュメント ライブラリから Project ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-206">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="7e36f-207">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-207">Word</span></span>

- <span data-ttu-id="7e36f-208">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式設定をクリアする機能が動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-208">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="7e36f-209">スケーラブル ベクター グラフィックス （SVG）に挿入されたテキストを、Word、Excel、または PowerPoint ファイルに挿入し、ファイルを保存して閉じ、再度開いた後、判読できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-209">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="7e36f-210">ルーラーが表示されていないときにテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションが点滅し始める問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-210">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="7e36f-211">共同編集モードで、コメントの返信がコメント ウィンドウに表示されず、変更履歴ウィンドウに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-211">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="7e36f-212">マージの競合があり、ユーザーが既に変更を破棄することを選択している場合の共同編集モード中の問題を修正し、変更を保存または破棄するオプションを表示しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-212">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="7e36f-213">HTML ハイパーリンクの色が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-213">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="7e36f-214">Wordに 50 を超える頻繁に開かれる文書のリストがある場合、文書を保存して開いた後、その文書に変更が加えられていなくても、変更履歴が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-214">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="7e36f-215">共同編集中の自動保存に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-215">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="7e36f-216">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても「WRO0004.docx」というファイル名で保存されるため、その文書を使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-216">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7e36f-217">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-217">Office Suite</span></span>

- <span data-ttu-id="7e36f-218">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります</span><span class="sxs-lookup"><span data-stu-id="7e36f-218">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="7e36f-219">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-219">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="7e36f-220">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-220">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2006-july-09"></a><span data-ttu-id="7e36f-222">バージョン 2006: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-222">Version 2006: July 09</span></span>
<span data-ttu-id="7e36f-223">*バージョン 2006 (ビルド 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-223">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-225">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-225">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-226">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-226">Excel</span></span>

- <span data-ttu-id="7e36f-227">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-227">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="7e36f-228">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-228">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="7e36f-229">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-229">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="7e36f-230">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-230">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="7e36f-231">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-231">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="7e36f-232">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7e36f-232">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="7e36f-233">**Excel のショートカットキー:** 更新された Excel のショートカットキー</span><span class="sxs-lookup"><span data-stu-id="7e36f-233">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-234">Outlook</span></span>

- <span data-ttu-id="7e36f-235">\*\*クイック投票を使用して、Outlook で投票を作成: \*\* 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="7e36f-235">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="7e36f-236">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-236">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-239">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-239">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7e36f-240">Access</span><span class="sxs-lookup"><span data-stu-id="7e36f-240">Access</span></span>

- <span data-ttu-id="7e36f-241">この問題は解決されており、ID (オートナンバーなど) フィールドを含むリンクされた SQL テーブルを Access に正常に挿入できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-241">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="7e36f-242">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-242">Excel</span></span>

- <span data-ttu-id="7e36f-243">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-243">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-244">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-244">Outlook</span></span>

- <span data-ttu-id="7e36f-245">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-245">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7e36f-246">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-246">Office Suite</span></span>

- <span data-ttu-id="7e36f-247">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="7e36f-247">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="7e36f-248">レジストリ TabProcGrowth の値がREG_SZ型で値 "0" でアドインがアクティブ化されているときに、Windows の Office ホストがクラッシュしていました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-248">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="7e36f-249">このレジストリ ボックスには、4つのパスのいずれかを使用できます。 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main。この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-249">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-25"></a><span data-ttu-id="7e36f-251">バージョン 2006: 6月 25 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-251">Version 2006: June 25</span></span>
<span data-ttu-id="7e36f-252">*バージョン 2006 (ビルド 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-252">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-254">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-254">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="7e36f-255">Visio</span><span class="sxs-lookup"><span data-stu-id="7e36f-255">Visio</span></span>

- <span data-ttu-id="7e36f-256">**Excel で洗練された Visio 図を作成する:** ワークシートのデータに基づいて、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-256">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-259">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-259">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7e36f-260">Access</span><span class="sxs-lookup"><span data-stu-id="7e36f-260">Access</span></span>

- <span data-ttu-id="7e36f-261">この問題は解決されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-261">This problem is now resolved.</span></span> <span data-ttu-id="7e36f-262">このプロセスでさらに問題が発生した場合は、チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="7e36f-262">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="7e36f-263">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-263">Outlook</span></span>

- <span data-ttu-id="7e36f-264"><span style="display:inline !important;">ドラッグ アンド ドロップによってファイル システムにコピーされた添付<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">ファイルの作成日&nbsp; が、&nbsp;4501年1月1日に設定された問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="7e36f-264"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="7e36f-265"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span></span><span class="sxs-lookup"><span data-stu-id="7e36f-265"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="7e36f-266"><span style="display:inline !important;">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="7e36f-266"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="7e36f-267"><span style="display:inline !important;">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="7e36f-267"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-18"></a><span data-ttu-id="7e36f-269">バージョン 2006: 6 月 18 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-269">Version 2006: June 18</span></span>
<span data-ttu-id="7e36f-270">*バージョン 2006 (ビルド 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-270">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-272">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-272">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-273">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-273">Excel</span></span>



- <span data-ttu-id="7e36f-274">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-274">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7e36f-275">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-275">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7e36f-276">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-276">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="7e36f-277">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7e36f-277">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-278">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-278">PowerPoint</span></span>

- <span data-ttu-id="7e36f-279">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-279">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7e36f-280">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-280">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7e36f-281">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-281">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="7e36f-282">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7e36f-282">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-283">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-283">Word</span></span>

- <span data-ttu-id="7e36f-284">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-284">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7e36f-285">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-285">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7e36f-286">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-286">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="7e36f-287">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7e36f-287">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-290">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-290">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-291">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-291">Excel</span></span>

- <span data-ttu-id="7e36f-292">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-292">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-293">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-293">Outlook</span></span>

- <span data-ttu-id="7e36f-294">クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-294">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="7e36f-295">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-295">Project</span></span>

- <span data-ttu-id="7e36f-296">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-296">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-11"></a><span data-ttu-id="7e36f-298">バージョン 2006: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-298">Version 2006: June 11</span></span>
<span data-ttu-id="7e36f-299">*バージョン 2006 (ビルド 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-299">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-301">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-301">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7e36f-302">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-302">PowerPoint</span></span>

- <span data-ttu-id="7e36f-303">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-303">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="7e36f-304">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-304">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-305">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-305">Word</span></span>

- <span data-ttu-id="7e36f-306">**テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-306">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-309">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-309">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-310">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-310">Excel</span></span>

- <span data-ttu-id="7e36f-311">OneDrive を起動すると Excel がシャットダウンすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-311">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="7e36f-312">グラフの軸にカスタム値が正しく適用されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-312">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="7e36f-313">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-313">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="7e36f-314">使用可能なプリンターのリストでプリンター名が重複する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-314">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="7e36f-315">ユーザーがマージされた列を削除したときのパフォーマンス時間が向上する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-315">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="7e36f-316">アドインは、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」 というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-316">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="7e36f-317">Excelとサード パーティの支援技術アプリケーションの一部との間でフォントを管理する際にメモリが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-317">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="7e36f-318">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-318">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="7e36f-319">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-319">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="7e36f-320">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-320">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="7e36f-321">選択ロックがない図形を含むワークシート上で、アドインがホスト アイテムを要求すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-321">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="7e36f-322">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-322">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-323">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-323">Outlook</span></span>

- <span data-ttu-id="7e36f-324">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-324">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="7e36f-325">新しいメール メッセージの作成時にテンプレートを表示するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-325">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="7e36f-326">Outlook バージョン1911以降、ユーザーが Exchange 2010のパブリック フォルダーを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-326">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="7e36f-327">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-327">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="7e36f-328">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-328">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="7e36f-329">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-329">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="7e36f-330">ユーザーが予定表をゲストユーザーと共有できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-330">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="7e36f-331">予定表のアイテムが真夜中にまたがっていると、終日イベントとして表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-331">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="7e36f-332">高 DPI のモニターを使用しているユーザーに対して、フォルダー プロパティの [オンライン アーカイブ] ドロップダウンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-332">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="7e36f-333">ユーザーがフォルダー間でアイテムを移動したときに、「BeforeItemMove」 イベントが正常に起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-333">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="7e36f-334">2つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-334">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="7e36f-335">テキスト形式のメールでハイパーリンクを使用して作業しているときに、Outlook でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-335">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="7e36f-336">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-336">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="7e36f-337">スクリーン リーダーを使用すると、Outlook ユーザーの断続的なハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-337">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="7e36f-338">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-338">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-339">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-339">PowerPoint</span></span>

- <span data-ttu-id="7e36f-340">サーバ構成のファイルをフォームベースの認証で開くときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-340">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="7e36f-341">グラフまたはブックが埋め込まれた PowerPoint ファイルの保存時にエラーが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-341">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="7e36f-342">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-342">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="7e36f-343">マウス ホイールを使用して拡大した後、スライドが中央に配置されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-343">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="7e36f-344">英語スイス (QWERTZ) キーボードを使用すると、キーボード ショートカットとスペル チェックが期待どおりに機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-344">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="7e36f-345">ユーザーによって終了されたコメント ウィンドウが自動的に再起動するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-345">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="7e36f-346">1つのスライドからのスライド エディタが次のスライドに重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-346">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="7e36f-347">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-347">Project</span></span>

- <span data-ttu-id="7e36f-348">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-348">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="7e36f-349">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-349">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="7e36f-350">オプションをクリックするとプロジェクトがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-350">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="7e36f-351">親計画が削除された後、孤立したタスクの削除や再割り当てができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-351">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="7e36f-352">Visio</span><span class="sxs-lookup"><span data-stu-id="7e36f-352">Visio</span></span>

- <span data-ttu-id="7e36f-353">依存コードに回帰がありましたが、これは修正されています。</span><span class="sxs-lookup"><span data-stu-id="7e36f-353">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="7e36f-354">これで、SharePoint Onprem で実行されている Visio services の画像が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-354">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-355">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-355">Word</span></span>

- <span data-ttu-id="7e36f-356">コメント ウィンドウのタイムスタンプがシステム ロケールの時間に基づいていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-356">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="7e36f-357">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-357">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="7e36f-358">テキストのコピーと貼り付けがコメント ウィンドウに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-358">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="7e36f-359">コメント内のハイパーリンクが機能しなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-359">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="7e36f-360">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-360">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="7e36f-361">Web アプリとデスクトップ アプリケーションの間のコメントが同期していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-361">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="7e36f-362">100% ズームでコメント ヒントの泡がぼやけて見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-362">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="7e36f-363">空白のドキュメントに新しいコメントを追加しても何も発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-363">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="7e36f-364">予定表用の WordMail に HTML を貼り付けできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-364">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="7e36f-365">共同編集セッションのコメントに返信すると、Word がフリーズすることがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-365">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="7e36f-366">100 個を超えるエントリを含むドキュメントにインデックスを挿入または更新すると、アプリケーションがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-366">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="7e36f-367">ポリシー Word 2007以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集で失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-367">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="7e36f-368">カスタム xml 値を含むファイルを開くのが非常に遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-368">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="7e36f-369">長いパス名 (32K を超える) のファイルが開かず、適切なエラー メッセージが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-369">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7e36f-370">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-370">Office Suite</span></span>

- <span data-ttu-id="7e36f-371">OS のシャットダウン後、InTune を介した Office 365 ProPlus の展開が停止する問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-371">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="7e36f-372">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-372">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="7e36f-373">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-373">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-08"></a><span data-ttu-id="7e36f-375">バージョン 2005: 6月 8 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-375">Version 2005: June 08</span></span>
<span data-ttu-id="7e36f-376">*バージョン 2005 (ビルド 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-376">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-378">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-378">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7e36f-379">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-379">PowerPoint</span></span>

- <span data-ttu-id="7e36f-380">[フォントの置換] ダイアログボックスで、[フォントの置換] ドロップダウンリストには、システムにインストールされているフォントの代わりにプレゼンテーション内のフォントしか表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-380">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-04"></a><span data-ttu-id="7e36f-382">バージョン 2005: 6月 4 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-382">Version 2005: June 04</span></span>
<span data-ttu-id="7e36f-383">*バージョン 2005 (ビルド 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-383">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-385">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-385">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7e36f-386">Access</span><span class="sxs-lookup"><span data-stu-id="7e36f-386">Access</span></span>

- <span data-ttu-id="7e36f-387">\*\*時代に追いつきましょう! 日付/時刻の拡張データ型では、より精度が高くなります。: \*\*改良されたデータ型をご紹介します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-387">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="7e36f-388">SQL との構文の互換性を高め、日付と時刻を含むレコードの精度と詳細レベルを向上させるため、Access に DateTime2 データ型を実装しています。</span><span class="sxs-lookup"><span data-stu-id="7e36f-388">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="7e36f-389">この追加の日付および時間のデータ型には、より大きい日付範囲 (0001-01-01 ～ 9999-12-31) が含まれます。これにより、指定された時間の精度 (秒単位ではなくナノ秒) で提供され、計算を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-389">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="7e36f-390">有効にするには、[新しいフィールド] > [日付と時間の拡張] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-390">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="7e36f-391">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-391">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="7e36f-392">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-392">Excel</span></span>

- <span data-ttu-id="7e36f-393">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-393">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="7e36f-394">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-394"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="7e36f-395">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="7e36f-395">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-396">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-396">Outlook</span></span>

- <span data-ttu-id="7e36f-397">**以前の Outlook セッションからアイテムを素早く再開するオプション:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-397">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-400">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-400">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7e36f-401">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-401">PowerPoint</span></span>

- <span data-ttu-id="7e36f-402">これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-402">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7e36f-403">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-403">Office Suite</span></span>

- <span data-ttu-id="7e36f-404">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-404">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-29"></a><span data-ttu-id="7e36f-406">バージョン 2005: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-406">Version 2005: May 29</span></span>
<span data-ttu-id="7e36f-407">*バージョン 2005 (ビルド 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-407">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-409">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-409">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="7e36f-410">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-410">Excel</span></span>

- <span data-ttu-id="7e36f-411">**シート ビュー:** Excel デスクトップで他のユーザーとの共同作業を行っているときに、並べ替えまたはフィルタリングを行います。</span><span class="sxs-lookup"><span data-stu-id="7e36f-411">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-412">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-412">Outlook</span></span>

- <span data-ttu-id="7e36f-413">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-413">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-416">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-416">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="7e36f-417">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-417">Outlook</span></span>

- <span data-ttu-id="7e36f-418">Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効です」という警告が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-418">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="7e36f-419">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="7e36f-419">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7e36f-420">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-420">Office Suite</span></span>

- <span data-ttu-id="7e36f-421">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-421">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="7e36f-422">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-422">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-21"></a><span data-ttu-id="7e36f-424">バージョン 2005: 5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-424">Version 2005: May 21</span></span>
<span data-ttu-id="7e36f-425">*バージョン 2005 (ビルド 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-425">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-429">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-429">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-430">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-430">Excel</span></span>

- <span data-ttu-id="7e36f-431">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-431">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="7e36f-432">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-432">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="7e36f-433">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-433">Outlook</span></span>

- <span data-ttu-id="7e36f-434">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-434">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="7e36f-435">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-435">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-14"></a><span data-ttu-id="7e36f-437">バージョン 2005: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-437">Version 2005: May 14</span></span>
<span data-ttu-id="7e36f-438">*バージョン 2005 (ビルド 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-438">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-440">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-440">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-441">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-441">Excel</span></span>

- <span data-ttu-id="7e36f-442">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-442">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-443">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-443">PowerPoint</span></span>

- <span data-ttu-id="7e36f-444">\*\*クリッカーは不要: イヤホンでカバー: \*\* Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-444">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="7e36f-445">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-445">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="7e36f-446">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7e36f-446">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="7e36f-447">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-447">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="7e36f-448">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-448">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-449">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-449">Word</span></span>

- <span data-ttu-id="7e36f-450">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-450">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-453">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-453">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="7e36f-454">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-454">Excel</span></span>

- <span data-ttu-id="7e36f-455">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-455">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="7e36f-456">グラフのデータ テーブルの日付軸の値が正しく表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-456">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="7e36f-457">[ページ レイアウト] または [改ページ プレビュー] に移動した後に、改ページを無効にできなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-457">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="7e36f-458">系列のデータを含む列を非表示にしてから非表示を解除すると、グラフの線のスタイルが失われる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-458">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="7e36f-459">フィルタリングされたリストに列を挿入すると、通常よりも時間がかかってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-459">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="7e36f-460">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-460">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="7e36f-461">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-461">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="7e36f-462">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-462">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="7e36f-463">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-463">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="7e36f-464">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-464">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="7e36f-465">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-465">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="7e36f-466">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-466">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="7e36f-467">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-467">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="7e36f-468">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-468">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="7e36f-469">[Invert if negative]\(負の値を反転する\) オプションが有効になっていると、ピボット グラフのカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-469">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="7e36f-470">[Invert if negative]\(負の値を反転する\) オプションが選択されていると、ピボット グラフの単一のデータ ポイントに対するカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-470">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="7e36f-471">この変更により、CSV ファイルで "@" 文字をアップロードすると、その "@" 文字以降の文字列が数式に変換される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-471">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="7e36f-472">SEQUENCE 関数で小数点以下が正しく四捨五入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-472">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="7e36f-473">OneNote</span><span class="sxs-lookup"><span data-stu-id="7e36f-473">OneNote</span></span>

- <span data-ttu-id="7e36f-474">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-474">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-475">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-475">Outlook</span></span>

- <span data-ttu-id="7e36f-476">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-476">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="7e36f-477">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-477">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="7e36f-478">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-478">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="7e36f-479">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-479">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="7e36f-480">Outlook デスクトップ クライアントで、ユーザーがクリックした非常に長いセーフリンクが、切り捨てにより読み込みに失敗する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-480">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="7e36f-481">DBCS (2 バイト文字セット) 文字を含む名前が付けられた Outlook フォルダーが、サーバーと同期するときに断続的に表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-481">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="7e36f-482">この問題が発生する場合は、Outlook を IMAP アカウントを使用して構成し、ロケールが日本語に設定されたシステム上で実行する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-482">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="7e36f-483">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-483">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="7e36f-484">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-484">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="7e36f-485">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-485">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="7e36f-486">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-486">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="7e36f-487">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="7e36f-487">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-488">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-488">PowerPoint</span></span>

- <span data-ttu-id="7e36f-489">ユーザーがコメントを作成したのに投稿せずにそのコメント ウィンドウを閉じ、新しいウィンドウを開いて、複数のスライドを移動してからそのウィンドウを閉じ、最後に、元のプレゼンテーションでコメント ウィンドウをもう一度開くと、下書きのコメントが利用できなくなっている問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-489">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="7e36f-490">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-490">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="7e36f-491">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-491">Project</span></span>

- <span data-ttu-id="7e36f-492">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-492">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="7e36f-493">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-493">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="7e36f-494">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-494">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="7e36f-495">Project が Project Web App に接続されていて、小数点の記号がカンマの場合、タイム ラグを追加する際に TaskDependencies Add メソッドが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-495">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="7e36f-496">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-496">Word</span></span>

- <span data-ttu-id="7e36f-497">コラボレーション モードのドキュメントにコメントを挿入しても正常に動作しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-497">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="7e36f-498">この変更により、@メンションがクリックされると連絡先カードが点滅する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-498">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="7e36f-499">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="7e36f-499">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="7e36f-500">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-500">This has been fixed.</span></span>

- <span data-ttu-id="7e36f-501">下書きのコメントを含むドキュメントを閉じようとすると、その下書きのコメントを保存せずにドキュメントを閉じてもよいかユーザーに確認を求める問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-501">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="7e36f-502">このプロンプトをキャンセルすると、ドキュメントが開いたままになるのではなく、閉じられていました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-502">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="7e36f-503">見出しをコピー & ペーストする際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-503">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="7e36f-504">投稿されたコメントを翻訳しようとすると、"Inserting translated text failed" (翻訳されたテキストの挿入に失敗しました) エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-504">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="7e36f-505">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-505">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="7e36f-506">Web ビュー/イマーシブ リーダーでヒントをクリックすると、ヒントが既に表示されている場合でも一番上までスクロールしていました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-506">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="7e36f-507">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-507">This has been fixed.</span></span>

- <span data-ttu-id="7e36f-508">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても WRO0004.docx というファイル名で保存されるため、そのドキュメントを使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-508">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7e36f-509">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-509">Office Suite</span></span>

- <span data-ttu-id="7e36f-510">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-510">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="7e36f-511">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-511">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="7e36f-512">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="7e36f-512">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="7e36f-513">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-513">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="7e36f-514">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-514">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-11"></a><span data-ttu-id="7e36f-516">バージョン 2004: 5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-516">Version 2004: May 11</span></span>
<span data-ttu-id="7e36f-517">*バージョン 2004 (ビルド 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-517">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-519">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-519">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-520">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-520">Excel</span></span>

- <span data-ttu-id="7e36f-521">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-521">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-522">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-522">Outlook</span></span>

- <span data-ttu-id="7e36f-523">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-523">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="7e36f-524">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-524">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="7e36f-525">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-525">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="7e36f-526">[ブログの投稿](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7e36f-526">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="7e36f-527">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-527">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-528">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-528">PowerPoint</span></span>

- <span data-ttu-id="7e36f-529">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-529">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="7e36f-530">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-530">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="7e36f-531">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-531">Word</span></span>

- <span data-ttu-id="7e36f-532">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-532">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-535">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-535">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-536">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-536">Outlook</span></span>

- <span data-ttu-id="7e36f-537">ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-537">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-04"></a><span data-ttu-id="7e36f-539">バージョン 2004: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-539">Version 2004: May 04</span></span>
<span data-ttu-id="7e36f-540">*バージョン 2004 (ビルド 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-540">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-542">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-542">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-543">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-543">Outlook</span></span>

- <span data-ttu-id="7e36f-544">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-544">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="7e36f-545">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-545">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="7e36f-546">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-546">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="7e36f-547">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-547">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-550">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-550">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="7e36f-551">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-551">Office Suite</span></span>

- <span data-ttu-id="7e36f-552">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-552">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2004-april-29"></a><span data-ttu-id="7e36f-554">バージョン 2004: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-554">Version 2004: April 29</span></span>
<span data-ttu-id="7e36f-555">*バージョン 2004 (ビルド 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-555">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-557">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-557">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-558">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-558">Outlook</span></span>

- <span data-ttu-id="7e36f-559">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-559">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-562">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-562">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-563">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-563">Outlook</span></span>

- <span data-ttu-id="7e36f-564">Windows の一部のビルドで Outlook がクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-564">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2004-april-25"></a><span data-ttu-id="7e36f-566">バージョン 2004: 4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-566">Version 2004: April 25</span></span>
<span data-ttu-id="7e36f-567">*バージョン 2004 (ビルド 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-567">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-569">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-569">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-570">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-570">Outlook</span></span>

- <span data-ttu-id="7e36f-571">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-571">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="7e36f-572">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-572">Project</span></span>

- <span data-ttu-id="7e36f-573">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-573">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7e36f-574">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-574">Office Suite</span></span>

- <span data-ttu-id="7e36f-575">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-575">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-21"></a><span data-ttu-id="7e36f-577">バージョン 2004: 4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-577">Version 2004: April 21</span></span>
<span data-ttu-id="7e36f-578">*バージョン 2004 (ビルド 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-578">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-580">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-580">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-581">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-581">Outlook</span></span>

- <span data-ttu-id="7e36f-582">フォルダー ウィンドウの幅が予期せず変更される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-582">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="7e36f-583">Outlook の終了中にユーザーが応答停止を経験する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-583">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-15"></a><span data-ttu-id="7e36f-585">バージョン 2004: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-585">Version 2004: April 15</span></span>
<span data-ttu-id="7e36f-586">*バージョン 2004 (ビルド 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-586">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-588">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-588">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-589">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-589">Excel</span></span>

- <span data-ttu-id="7e36f-590">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-590">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-591">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-591">Outlook</span></span>

- <span data-ttu-id="7e36f-592">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="7e36f-592">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="7e36f-593">望むなら、オフにすることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-593">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-594">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-594">PowerPoint</span></span>

- <span data-ttu-id="7e36f-595">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-595">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-596">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-596">Word</span></span>

- <span data-ttu-id="7e36f-597">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成できます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-597">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="7e36f-598">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-598">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-601">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-601">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7e36f-602">Access</span><span class="sxs-lookup"><span data-stu-id="7e36f-602">Access</span></span>

- <span data-ttu-id="7e36f-603">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-603">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="7e36f-604">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-604">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="7e36f-605">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-605">Excel</span></span>

- <span data-ttu-id="7e36f-606">シートのセル範囲を選択しているのに、単一セルの選択になってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-606">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="7e36f-607">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-607">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="7e36f-608">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-608">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="7e36f-609">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-609">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="7e36f-610">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-610">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="7e36f-611">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-611">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="7e36f-612">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-612">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="7e36f-613">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-613">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="7e36f-614">X 軸の範囲によっては、グラフのサイズを小さくすると、Excel が応答を停止する場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-614">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="7e36f-615">R1C1 セルの参照が有効になっている Excel シートが共同編集 / 共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動しても、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-615">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="7e36f-616">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-616">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-617">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-617">Outlook</span></span>

- <span data-ttu-id="7e36f-618">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-618">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="7e36f-619">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-619">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="7e36f-620">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-620">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="7e36f-621">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-621">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="7e36f-622">メール メッセージからカテゴリが消えることがあるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-622">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="7e36f-623">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-623">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="7e36f-624">ユーザーが組織フォームのプロパティを表示しようとするとクラッシュするという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-624">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="7e36f-625">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-625">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="7e36f-626">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-626">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="7e36f-627">返信の対象のメッセージに対してユーザーが所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-627">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="7e36f-628">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-628">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="7e36f-629">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-629">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="7e36f-630">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-630">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="7e36f-631">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-631">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="7e36f-632">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-632">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7e36f-633">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-633">PowerPoint</span></span>

- <span data-ttu-id="7e36f-634">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-634">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="7e36f-635">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-635">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="7e36f-636">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-636">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="7e36f-637">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-637">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="7e36f-638">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-638">Project</span></span>

- <span data-ttu-id="7e36f-639">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-639">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="7e36f-640">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-640">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="7e36f-641">ユーザーがスケジュール グループ内の [タスク] リボンにある [無効化] ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Application (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-641">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="7e36f-642">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-642">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="7e36f-643">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="7e36f-643">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="7e36f-644">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-644">This behavior has been fixed.</span></span>

- <span data-ttu-id="7e36f-645">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-645">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="7e36f-646">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-646">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="7e36f-647">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-647">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="7e36f-648">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-648">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="7e36f-649">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-649">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="7e36f-650">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-650">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="7e36f-651">[フォーム] ビュー内で先行処理 / 後続処理データを編集すると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-651">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="7e36f-652">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-652">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-653">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-653">Word</span></span>

- <span data-ttu-id="7e36f-654">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-654">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="7e36f-655">この変更により、[表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-655">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="7e36f-656">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-656">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="7e36f-657">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-657">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="7e36f-658">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-658">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="7e36f-659">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-659">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="7e36f-660">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-660">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="7e36f-661">この変更により、2 ページ表示で、コメントを作成するとき、コメント アンカーが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-661">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="7e36f-662">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-662">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="7e36f-663">スタイルがリストにリンクされているスタイルの祖先である段落の場合、そのリストの番号が失われる場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-663">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="7e36f-664">この変更により、文書に存在しない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-664">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="7e36f-665">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-665">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="7e36f-666">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-666">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="7e36f-667">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-667">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="7e36f-668">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-668">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-14"></a><span data-ttu-id="7e36f-670">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-670">Version 2003: April 14</span></span>
<span data-ttu-id="7e36f-671">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-671">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="7e36f-672">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7e36f-672">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

- <span data-ttu-id="7e36f-674">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7e36f-674">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-09"></a><span data-ttu-id="7e36f-676">バージョン 2003: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-676">Version 2003: April 09</span></span>
<span data-ttu-id="7e36f-677">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-677">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-679">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-679">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-680">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-680">Excel</span></span>

- <span data-ttu-id="7e36f-681">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="7e36f-681">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="7e36f-682">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="7e36f-682">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-683">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-683">Outlook</span></span>

- <span data-ttu-id="7e36f-684">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="7e36f-684">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="7e36f-685">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="7e36f-685">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-686">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-686">PowerPoint</span></span>

- <span data-ttu-id="7e36f-687">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="7e36f-687">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="7e36f-688">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="7e36f-688">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-689">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-689">Word</span></span>

- <span data-ttu-id="7e36f-690">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="7e36f-690">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="7e36f-691">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="7e36f-691">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-03"></a><span data-ttu-id="7e36f-695">バージョン 2003: 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-695">Version 2003: April 03</span></span>
<span data-ttu-id="7e36f-696">*バージョン 2003 (ビルド 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-696">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-698">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-698">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-699">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-699">Excel</span></span>

- <span data-ttu-id="7e36f-700">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-700">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-701">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-701">Outlook</span></span>

- <span data-ttu-id="7e36f-702">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-702">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="7e36f-703">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-703">Project</span></span>

- <span data-ttu-id="7e36f-704">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChangeevent が発生します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-704">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-705">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-705">Word</span></span>

- <span data-ttu-id="7e36f-706">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-706">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="7e36f-708">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-708">Version 2003: March 31</span></span>
<span data-ttu-id="7e36f-709">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-709">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-711">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-711">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7e36f-712">Access</span><span class="sxs-lookup"><span data-stu-id="7e36f-712">Access</span></span>

- <span data-ttu-id="7e36f-713">**[テーブルの追加] 作業ウィンドウ:** Access の新しい [テーブルの追加] 作業ウィンドウを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-713">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="7e36f-714">この機能を使用すると、クエリやリレーションシップ ビューのために [テーブルの表示] ダイアログボックスに移動することなく、クエリ ウィンドウに追加またはそこから削除する 1 つ以上のテーブルを簡単に選択することができます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-714">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="7e36f-715">この機能には、リンク テーブルを表示するための新しい [リンク] タブ、現在のリストをフィルター処理するための検索ボックス、"ドラッグ アンド ドロップ" による操作なども含まれます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-715">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-718">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-718">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="7e36f-719">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="7e36f-719">Project</span></span>

- <span data-ttu-id="7e36f-720"><span style="display:inline !important;">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="7e36f-720"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="7e36f-722">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-722">Version 2003: March 25</span></span>
<span data-ttu-id="7e36f-723">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-723">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="7e36f-724">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7e36f-724">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="7e36f-725">バージョン 2003: 3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-725">Version 2003: March 23</span></span>
<span data-ttu-id="7e36f-726">*バージョン 2003 (ビルド 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-726">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="7e36f-727">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7e36f-727">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="7e36f-728">バージョン 2003: 3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-728">Version 2003: March 21</span></span>
<span data-ttu-id="7e36f-729">*バージョン 2003 (ビルド 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-729">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-731">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-731">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-732">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-732">Outlook</span></span>

- <span data-ttu-id="7e36f-733">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="7e36f-733">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="7e36f-734">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-734">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="7e36f-735">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="7e36f-735">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="7e36f-736">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-736">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-737">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-737">PowerPoint</span></span>

- <span data-ttu-id="7e36f-738">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-738">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-16"></a><span data-ttu-id="7e36f-740">Version 2003: March 16</span><span class="sxs-lookup"><span data-stu-id="7e36f-740">Version 2003: March 16</span></span>
<span data-ttu-id="7e36f-741">*バージョン 2003 (ビルド 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-741">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-743">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-743">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-744">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-744">Excel</span></span>

- <span data-ttu-id="7e36f-745">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-745">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-746">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-746">Outlook</span></span>

- <span data-ttu-id="7e36f-747">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-747">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-748">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-748">PowerPoint</span></span>

- <span data-ttu-id="7e36f-749">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-749">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-750">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-750">Word</span></span>

- <span data-ttu-id="7e36f-751">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-751">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7e36f-752">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-752">Office Suite</span></span>

- <span data-ttu-id="7e36f-753">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-753">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="7e36f-754">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-754">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-757">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-757">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-758">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-758">Excel</span></span>

- <span data-ttu-id="7e36f-759">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-759">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-760">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-760">Outlook</span></span>

- <span data-ttu-id="7e36f-761">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-761">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-10"></a><span data-ttu-id="7e36f-763">バージョン 2003: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-763">Version 2003: March 10</span></span>
<span data-ttu-id="7e36f-764">*バージョン 2003 (ビルド 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-764">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="7e36f-765">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7e36f-765">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)
### <a name="feature-updates"></a><span data-ttu-id="7e36f-767">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-767">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-768">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-768">Excel</span></span>
- <span data-ttu-id="7e36f-769">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-769">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="7e36f-770">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-770">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="7e36f-771">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-771">PowerPoint</span></span>
- <span data-ttu-id="7e36f-772">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-772">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="7e36f-773">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-773">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="7e36f-774">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-774">Word</span></span>
- <span data-ttu-id="7e36f-775">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-775">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="7e36f-776">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7e36f-776">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-777">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-777">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-778">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-778">Excel</span></span>

- <span data-ttu-id="7e36f-779">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-779">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="7e36f-780">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-780">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="7e36f-781">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-781">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="7e36f-782">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-782">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="7e36f-783">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-783">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="7e36f-784">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-784">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="7e36f-785">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-785">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="7e36f-786">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-786">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="7e36f-787">この変更では、アドインによって noSelect ロックがある図形を含むドキュメントまたはワークシートのホスト アイテムが求められるときに、オブジェクト モデルでランタイム エラーが発生する問題および App (Excel、Word) がクラッシュする可能性がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-787">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="7e36f-788">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-788">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="7e36f-789">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-789">Outlook</span></span>

- <span data-ttu-id="7e36f-790">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-790">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="7e36f-791">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-791">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="7e36f-792">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-792">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="7e36f-793">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-793">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="7e36f-794">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-794">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="7e36f-795">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-795">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="7e36f-796">ユーザーが「&quot;空き時間情報オプション&quot;」予定表のアクセス許可ダイアログにアクセスできなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-796">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="7e36f-797">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「&quot;申し訳ございません、このアイテムを開くことができません&quot;」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-797">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="7e36f-798">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-798">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="7e36f-799">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-799">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="7e36f-800">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-800">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="7e36f-801">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-801">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7e36f-802">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-802">PowerPoint</span></span>

- <span data-ttu-id="7e36f-803">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-803">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="7e36f-804">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-804">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="7e36f-805">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-805">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="7e36f-806">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-806">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="7e36f-807">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-807">Project</span></span>

- <span data-ttu-id="7e36f-808">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-808">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="7e36f-809">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-809">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="7e36f-810">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-810">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="7e36f-811">Visio</span><span class="sxs-lookup"><span data-stu-id="7e36f-811">Visio</span></span>

- <span data-ttu-id="7e36f-812">Visio デスクトップで開いたファイルに関して、[図形情報] ウィンドウの [図形データ] セクションに矛盾した詳細が表示されていました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-812">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="7e36f-813">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-813">It has now been fixed.</span></span>

- <span data-ttu-id="7e36f-814">何らかのセキュリティ チェックが原因で、2016 より前のバージョンでインポートされたビットマップは表示されていませんでした。</span><span class="sxs-lookup"><span data-stu-id="7e36f-814">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="7e36f-815">この問題は Visio サブスクリプションで修正されました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-815">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-816">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-816">Word</span></span>

- <span data-ttu-id="7e36f-817">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-817">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="7e36f-818">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-818">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="7e36f-819">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-819">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="7e36f-820">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-820">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="7e36f-821">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="7e36f-821">This issue has been fixed.</span></span>

- <span data-ttu-id="7e36f-822">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-822">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="7e36f-823">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-823">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="7e36f-824">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-824">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="7e36f-825">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-825">Office Suite</span></span>

- <span data-ttu-id="7e36f-826">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-826">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="7e36f-827">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="7e36f-827">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="7e36f-828">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-828">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="7e36f-829">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word、Excel、PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-829">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="7e36f-830">同じ SharePoint ライブラリから Word、Excel、PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-830">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-05"></a><span data-ttu-id="7e36f-832">バージョン 2002: 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-832">Version 2002: March 05</span></span>
<span data-ttu-id="7e36f-833">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-833">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="7e36f-834">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7e36f-834">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="7e36f-835">バージョン 2002: 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-835">Version 2002: March 04</span></span>
<span data-ttu-id="7e36f-836">*バージョン 2002 (ビルド 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-836">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-838">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-838">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="7e36f-839">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-839">Project</span></span>
- <span data-ttu-id="7e36f-840">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-840">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7e36f-841">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-841">Office Suite</span></span>
- <span data-ttu-id="7e36f-842">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-842">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-01"></a><span data-ttu-id="7e36f-844">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-844">Version 2002: March 01</span></span>
<span data-ttu-id="7e36f-845">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-845">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-846">解決した問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-846">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-847">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-847">Outlook</span></span>

- <span data-ttu-id="7e36f-848">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-848">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-24"></a><span data-ttu-id="7e36f-850">バージョン 2002: 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-850">Version 2002: February 24</span></span>
<span data-ttu-id="7e36f-851">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-851">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="7e36f-852">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7e36f-852">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="7e36f-853">バージョン 2002: 2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-853">Version 2002: February 22</span></span>
<span data-ttu-id="7e36f-854">*バージョン 2002 (ビルド 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-854">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="7e36f-855">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7e36f-855">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="7e36f-856">バージョン 2002: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-856">Version 2002: February 21</span></span>
<span data-ttu-id="7e36f-857">*バージョン 2002 (ビルド 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-857">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-859">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-859">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7e36f-860">Access</span><span class="sxs-lookup"><span data-stu-id="7e36f-860">Access</span></span>

- <span data-ttu-id="7e36f-861">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="7e36f-861">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="7e36f-862">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-862">Search and replace text in SQL View.</span></span> <span data-ttu-id="7e36f-863">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-863">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-864">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-864">Outlook</span></span>

- <span data-ttu-id="7e36f-865">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="7e36f-865">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="7e36f-866">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-866">Outlook now detects this and helps you get connected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-869">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-869">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7e36f-870">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-870">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="7e36f-871">CUBEVALUE 関数が間違った結果を返すことがある問題を修正しました。&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="7e36f-871">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="7e36f-872">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-872">Outlook</span></span>

- <span data-ttu-id="7e36f-873">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-873">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="7e36f-874">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-874">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="7e36f-875">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="7e36f-875">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="7e36f-876">黒のテーマを持つユーザーが [&quot;差出人&quot;] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-876">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="7e36f-877"><span style="display:inline !important;">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span></span><span class="sxs-lookup"><span data-stu-id="7e36f-877"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-18"></a><span data-ttu-id="7e36f-879">バージョン 2002: 2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-879">Version 2002: February 18</span></span>
<span data-ttu-id="7e36f-880">*バージョン 2002 (ビルド 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-880">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="7e36f-881">バージョン 2002: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7e36f-881">Version 2002: February 11</span></span>
<span data-ttu-id="7e36f-882">*バージョン 2002 (ビルド 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="7e36f-882">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="7e36f-883">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="7e36f-883">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7e36f-885">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7e36f-885">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7e36f-886">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-886">Outlook</span></span>

- <span data-ttu-id="7e36f-887">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="7e36f-887">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="7e36f-888">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-888">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="7e36f-889">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-889">Word</span></span>

- <span data-ttu-id="7e36f-890">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-890">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7e36f-891">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-891">Office Suite</span></span>

- <span data-ttu-id="7e36f-892">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-892">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7e36f-895">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7e36f-895">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7e36f-896">Access</span><span class="sxs-lookup"><span data-stu-id="7e36f-896">Access</span></span>

- <span data-ttu-id="7e36f-897">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-897">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="7e36f-898">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-898">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="7e36f-899">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-899">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="7e36f-900">VB コードのレコーダー オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-900">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="7e36f-901">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-901">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="7e36f-902">Excel</span><span class="sxs-lookup"><span data-stu-id="7e36f-902">Excel</span></span>

- <span data-ttu-id="7e36f-903">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-903">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="7e36f-904">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-904">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="7e36f-905">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-905">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="7e36f-906">Outlook</span><span class="sxs-lookup"><span data-stu-id="7e36f-906">Outlook</span></span>

- <span data-ttu-id="7e36f-907">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-907">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="7e36f-908">左側のナビゲーション ウィンドウで [お気に入り] に保存したフォルダーが断続的に表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-908">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="7e36f-909">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-909">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="7e36f-910">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-910">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="7e36f-911">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-911">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="7e36f-912">アイテム保持ポリシーに基づいて期限切れになるメールに 2 つのラベルが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-912">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="7e36f-913">メールが 1 日で期限切れになることを示すものと、2 日で期限切れになることを示すものです。</span><span class="sxs-lookup"><span data-stu-id="7e36f-913">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="7e36f-914">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-914">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7e36f-915">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7e36f-915">PowerPoint</span></span>

- <span data-ttu-id="7e36f-916">インクが PowerPoint のインク アニメーションで使用すると完全にレンダリングされない、またはスキップされることがある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-916">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="7e36f-917">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-917">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="7e36f-918">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-918">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="7e36f-919">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="7e36f-919">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="7e36f-920">Project</span><span class="sxs-lookup"><span data-stu-id="7e36f-920">Project</span></span>

- <span data-ttu-id="7e36f-921">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-921">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="7e36f-922">Word</span><span class="sxs-lookup"><span data-stu-id="7e36f-922">Word</span></span>

- <span data-ttu-id="7e36f-923">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-923">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="7e36f-924">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-924">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="7e36f-925">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-925">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="7e36f-926">コメントを編集し、テキストをイタリック体にし、それを投稿すると、その後にイタリック体の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-926">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="7e36f-927">反転したページ色を使用する読み取りモードでコメントのヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-927">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="7e36f-928">ドキュメントが共同編集されている場合、ルート コメントの下書き版が保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-928">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="7e36f-929">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="7e36f-929">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="7e36f-930">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-930">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="7e36f-931">コメント コンテキスト メニューのコメント コマンド (コメントの編集、コメントへの返信、コメントの削除、コメントの解決) が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7e36f-931">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7e36f-932">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7e36f-932">Office Suite</span></span>

- <span data-ttu-id="7e36f-933">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-933">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="7e36f-934">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7e36f-934">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

