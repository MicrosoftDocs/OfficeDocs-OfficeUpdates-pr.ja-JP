---
title: ベータ チャネルのリリース ノート
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: d80bc153a2de2f3f364003a5691753d12bbb0416
ms.sourcegitcommit: 39056b7c6c4fc271ff1c559f4231800862f279b4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/10/2020
ms.locfileid: "45098671"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="19845-103">ベータ チャネルのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="19845-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="19845-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project のベータ チャネル ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="19845-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="19845-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="19845-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="19845-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたってベータ チャネルにロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="19845-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="19845-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="19845-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="19845-108">以下に示すものが表示されない場合でも、最終的には入手できますのでご安心ください。</span><span class="sxs-lookup"><span data-stu-id="19845-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="19845-109">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="19845-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="19845-110">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="19845-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="19845-111">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります。</span><span class="sxs-lookup"><span data-stu-id="19845-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="19845-112">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="19845-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (削除しないでください)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2008-july-10"></a><span data-ttu-id="19845-115">バージョン 2008: 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="19845-115">Version 2008: July 10</span></span>
<span data-ttu-id="19845-116">*バージョン 2008 (ビルド 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="19845-116">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-118">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-118">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-119">Outlook</span></span>

- <span data-ttu-id="19845-120">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-120">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="19845-121">ユーザーが適切な印刷権限を持っていても、印刷ボタンが無効な状態で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-121">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="19845-122">Project</span><span class="sxs-lookup"><span data-stu-id="19845-122">Project</span></span>

- <span data-ttu-id="19845-123">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存しようとしても、何も起こらない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-123">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="19845-124">Word</span><span class="sxs-lookup"><span data-stu-id="19845-124">Word</span></span>

- <span data-ttu-id="19845-125">テキストとの画像をコメントボックスに貼り付けると Word が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-125">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="19845-126">最後のコメントを削除すると [新しいコメント] ボタンが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-126">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-03"></a><span data-ttu-id="19845-128">バージョン 2007: 7 月 3 日</span><span class="sxs-lookup"><span data-stu-id="19845-128">Version 2007: July 03</span></span>
<span data-ttu-id="19845-129">*バージョン 2007 (ビルド 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="19845-129">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-131">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-131">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-132">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-132">Outlook</span></span>

- <span data-ttu-id="19845-133">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します [詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="19845-133">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="19845-134">**新しい会議室の検索機能:** これまでと違うさまざまな機能で会議室を検索できます。</span><span class="sxs-lookup"><span data-stu-id="19845-134">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-137">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-137">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-138">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-138">Excel</span></span>

- <span data-ttu-id="19845-139">テーブルに関連付けられたクエリが編集されていない場合でも、特定のバージョンの Excel で作成したデータ モデル テーブルが [テーブル プレビュー] に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-139">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="19845-140">[名前の定義] \ [名前の適用] ダイアログで [相対/絶対を無視] 参照を無効にすると数式が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-140">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="19845-141">高度なデータ フィルターをクリアするとテーブルの書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-141">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="19845-142">埋め込まれた PDF 文書のフル パスがファイル名だけでなく文書の標題に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-142">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="19845-143">Wolfram クラウド コネクターを無効にしてから、Excel ブックを保存してもう一度開くとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-143">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="19845-144">ソルバー アドインを有効にして Excel を起動するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-144">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-145">Outlook</span></span>

- <span data-ttu-id="19845-146">「To」行に 130 人を超える受信者がいる場合に Outlook がハングする問題を修正し、テキストのレンダリングのパフォーマンスも改善しました。</span><span class="sxs-lookup"><span data-stu-id="19845-146">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="19845-147">2 日を超えるイベントはそれ以降のすべての日に同じ終了時刻を表示するという「To Do バー」の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-147">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="19845-148">Outlook のユーザーが共有の予定表を使用した後、メッセージ一覧の更新が数分間停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-148">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-149">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-149">PowerPoint</span></span>

- <span data-ttu-id="19845-150">スライドのテキスト領域に HTML を貼り付けると、代わりにスライドの上部に作成されたテキスト ボックスに貼り付けられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-150">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="19845-151">発表者ビューですべてのスライドを選択し、Alt + Tabを使用して発表者ビューを終了し、スライド ショーに戻って [ショーの終了] をクリックすると、未処理の例外が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-151">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="19845-152">Project</span><span class="sxs-lookup"><span data-stu-id="19845-152">Project</span></span>

- <span data-ttu-id="19845-153">特定の XML ファイルを開くと、Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-153">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="19845-154">ライブラリがモダン モードの場合、SharePoint ドキュメント ライブラリから Project ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-154">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="19845-155">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-155">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="19845-156">Word</span><span class="sxs-lookup"><span data-stu-id="19845-156">Word</span></span>

- <span data-ttu-id="19845-157">マージの競合があり、ユーザーが既に変更を破棄することを選択している場合の共同編集モード中の問題を修正し、変更を保存または破棄するオプションを表示しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="19845-157">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="19845-158">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても「WRO0004.docx」というファイル名で保存されるため、その文書を使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-158">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-26"></a><span data-ttu-id="19845-160">バージョン 2007: 6月 26 日</span><span class="sxs-lookup"><span data-stu-id="19845-160">Version 2007: June 26</span></span>
<span data-ttu-id="19845-161">*バージョン 2007 (ビルド 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="19845-161">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-163">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-163">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="19845-164">Access</span><span class="sxs-lookup"><span data-stu-id="19845-164">Access</span></span>

- <span data-ttu-id="19845-165">リンクされた SQL テーブルが更新された場合、リンクされたテーブル マネージャーが主キーを要求する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-165">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="19845-166">クエリ エディターのクエリがスクロールして表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-166">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="19845-167">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-167">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-168">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-168">Outlook</span></span>

- <span data-ttu-id="19845-169">ユーザーが配布リストの「送信」または「代理送信」ができなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-169">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="19845-170">メッセージに画像をインラインで挿入し、メッセージを下書きとして保存すると画像のサイズが変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-170">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="19845-171">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-171">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="19845-172">Project</span><span class="sxs-lookup"><span data-stu-id="19845-172">Project</span></span>

- <span data-ttu-id="19845-173">政府機関向けコミュニティのクラウド環境でプロジェクト プランナのリンクが無効になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-173">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19845-174">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-174">Office Suite</span></span>

- <span data-ttu-id="19845-175">スケーラブル ベクター グラフィックス （SVG）に挿入されたテキストを、Word、Excel、または PowerPoint ファイルに挿入し、ファイルを保存して閉じ、再度開いた後、判読できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-175">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-19"></a><span data-ttu-id="19845-177">バージョン 2007: 6月 19 日</span><span class="sxs-lookup"><span data-stu-id="19845-177">Version 2007: June 19</span></span>
<span data-ttu-id="19845-178">*バージョン 2007 (ビルド 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="19845-178">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-180">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-180">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-181">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-181">Excel</span></span>

- <span data-ttu-id="19845-182">SharePoint/OneDriveにブックを保存すると、ユーザー設定のリボンタブの CustomUI XML が削除される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-182">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="19845-183">ファイルが読み取り専用である場合にのみ、ブックが読み取り専用であった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-183">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-184">Outlook</span></span>

- <span data-ttu-id="19845-185">解像度の異なる複数のモニターを使用している場合に、Input Method Editor (IME) ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-185">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="19845-186">以前に保存した予定を閉じると、次のエラーが表示される問題を修正しました。「別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。</span><span class="sxs-lookup"><span data-stu-id="19845-186">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="19845-187">アイテムの既定のフォルダーにコピーしますか? 」</span><span class="sxs-lookup"><span data-stu-id="19845-187">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="19845-188">日本のユーザーに対してミニ カレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-188">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="19845-189">予定表のリマインダーで、1 週間以内に行われる会議の正確な時刻が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-189">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-190">PowerPoint</span></span>

- <span data-ttu-id="19845-191">ライブの共同編集セッション中に共同編集ギャラリーでユーザーのプレゼンス カラー インジケーターが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-191">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="19845-192">Project</span><span class="sxs-lookup"><span data-stu-id="19845-192">Project</span></span>

- <span data-ttu-id="19845-193">固定期間タスクが 100% 完了しているが、実際の完了が指定されていない場合、タスク完了率が 100% 未満として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-193">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="19845-194">Word</span><span class="sxs-lookup"><span data-stu-id="19845-194">Word</span></span>

- <span data-ttu-id="19845-195">HTML ハイパーリンクの色が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-195">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19845-196">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-196">Office Suite</span></span>

- <span data-ttu-id="19845-197">http または https ベースではない URL が最近使用したリストに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-197">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-12"></a><span data-ttu-id="19845-199">バージョン 2007: 6月 12 日</span><span class="sxs-lookup"><span data-stu-id="19845-199">Version 2007: June 12</span></span>
<span data-ttu-id="19845-200">*バージョン 2007 (ビルド 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="19845-200">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-202">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-202">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="19845-203">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-203">Excel</span></span>

- <span data-ttu-id="19845-204">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-204">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="19845-205">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="19845-205">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="19845-206">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="19845-206">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="19845-207">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-207">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="19845-208">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="19845-208">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-211">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-211">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="19845-212">Access</span><span class="sxs-lookup"><span data-stu-id="19845-212">Access</span></span>

- <span data-ttu-id="19845-213">Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できず、行が削除されたと誤って報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-213">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="19845-214">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-214">Excel</span></span>

- <span data-ttu-id="19845-215">レーダーチャートの主要な目盛線が正しく書式設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-215">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="19845-216">Project</span><span class="sxs-lookup"><span data-stu-id="19845-216">Project</span></span>

- <span data-ttu-id="19845-217">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-217">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="19845-218">ベースラインのリセットまたは更新により、時間単位の予算コスト/作業リソースが変更され、ベースラインが誤った予算値を反映する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-218">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="19845-219">Word</span><span class="sxs-lookup"><span data-stu-id="19845-219">Word</span></span>

- <span data-ttu-id="19845-220">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式設定をクリアする機能が動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-220">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="19845-221">ルーラーが表示されていないときにテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションが点滅し始める問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-221">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="19845-222">共同編集モードで、コメントの返信がコメント ウィンドウに表示されず、変更履歴ウィンドウに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-222">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="19845-223">Wordに 50 を超える頻繁に開かれる文書のリストがある場合、文書を保存して開いた後、その文書に変更が加えられていなくても、変更履歴が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-223">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-05"></a><span data-ttu-id="19845-225">バージョン 2006: 6 月 5 日</span><span class="sxs-lookup"><span data-stu-id="19845-225">Version 2006: June 05</span></span>
<span data-ttu-id="19845-226">*バージョン 2006 (ビルド 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="19845-226">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-228">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-228">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="19845-229">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-229">Excel</span></span>

- <span data-ttu-id="19845-230">**Excel での共同作業中の並べ替え/フィルター処理:** Excel ファイルの並べ替えとフィルター処理を他のユーザーと行うことができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-230">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="19845-231">この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="19845-231">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="19845-232">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="19845-232">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="19845-233">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="19845-233"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="19845-234">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="19845-234">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="19845-235">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-235">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="19845-236">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-236">Outlook</span></span>

- <span data-ttu-id="19845-237">**以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="19845-237">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="19845-238">Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="19845-238">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="19845-239">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="19845-239">This feature is on by default.</span></span> <span data-ttu-id="19845-240">オフにするには、[オプション] > [一般] > [開始オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="19845-240">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-243">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-243">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-244">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-244">Excel</span></span>

- <span data-ttu-id="19845-245">グラフの軸にカスタム値が正しく適用されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-245">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="19845-246">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-246">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-247">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-247">Outlook</span></span>

- <span data-ttu-id="19845-248">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-248">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="19845-249">新しいメール メッセージの作成時にテンプレートを表示するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-249">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="19845-250">Outlook バージョン1911以降、ユーザーが Exchange 2010のパブリック フォルダーを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-250">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="19845-251">Office リボンのグループ予定表の [分類] ボタンが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-251">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="19845-252">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-252">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="19845-253">高 DPI のモニターを使用しているユーザーに対して、フォルダー プロパティの [オンライン アーカイブ] ドロップダウンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-253">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="19845-254">テキスト形式のメールでハイパーリンクを使用して作業しているときに、Outlook でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-254">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="19845-255">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-255">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="19845-256">スクリーン リーダーを使用すると、Outlook ユーザーに断続的なハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-256">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-257">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-257">PowerPoint</span></span>

- <span data-ttu-id="19845-258">サーバ構成のファイルをフォームベースの認証で開くときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-258">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="19845-259">グラフまたはブックが埋め込まれた PowerPoint ファイルの保存時にエラーが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-259">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="19845-260">ユーザーによって終了されたコメント ウィンドウが自動的に再起動する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-260">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="19845-261">1つのスライドからのスライド エディタが次のスライドに重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-261">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="19845-262">Project</span><span class="sxs-lookup"><span data-stu-id="19845-262">Project</span></span>

- <span data-ttu-id="19845-263">親計画が削除された後、孤立したタスクの削除や再割り当てができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-263">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="19845-264">Word</span><span class="sxs-lookup"><span data-stu-id="19845-264">Word</span></span>

- <span data-ttu-id="19845-265">コメント ウィンドウのタイムスタンプがシステム ロケールの時間に基づいていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-265">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="19845-266">Web アプリとデスクトップ アプリケーションの間のコメントが同期していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-266">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version2006may29"></a><span data-ttu-id="19845-268">バージョン 2006: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="19845-268">Version 2006: May 29</span></span>
<span data-ttu-id="19845-269">*バージョン 2006 (ビルド 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="19845-269">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="19845-270">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-270">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-271">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-271">Outlook</span></span>

- <span data-ttu-id="19845-272">**Outlook トースト通知に追加されたその他のボタン:** Windows 10 で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-272">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-273">PowerPoint</span></span>

- <span data-ttu-id="19845-274">**PowerPoint でのストリーム ビデオのパフォーマンス向上:** ビデオの読み込み時間を最小限に抑え快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="19845-274">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="19845-275">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="19845-275">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolvedissues"></a><span data-ttu-id="19845-278">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-278">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="19845-279">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-279">Excel</span></span>

- <span data-ttu-id="19845-280">OneDrive を起動すると Excel がシャットダウンすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-280">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="19845-281">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-281">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="19845-282">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-282">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="19845-283">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押してスクロールした後、Excel が応答しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-283">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-284">PowerPoint</span></span>

- <span data-ttu-id="19845-285">マウス ホイールを使用して拡大した後、スライドが中央に配置されていない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-285">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="19845-286">Word</span><span class="sxs-lookup"><span data-stu-id="19845-286">Word</span></span>

- <span data-ttu-id="19845-287">テキストのコピーと貼り付けがコメント ウィンドウに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-287">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="19845-288">100% ズームでコメント ヒントの吹き出しがぼやけて見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-288">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="19845-289">ポリシー Word 2007 以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集で失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-289">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="19845-290">長いパス名 (32K を超える) のファイルが開かず、適切なエラー メッセージが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-290">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="19845-291">バージョン 2006: 5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="19845-291">Version 2006: May 22</span></span>
<span data-ttu-id="19845-292">*バージョン 2006 (ビルド 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="19845-292">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-294">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-294">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="19845-295">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-295">Excel</span></span>

- <span data-ttu-id="19845-296">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="19845-296">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="19845-297">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="19845-297">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="19845-298">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="19845-298">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="19845-299">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="19845-299">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="19845-300">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="19845-300">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-301">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-301">PowerPoint</span></span>

- <span data-ttu-id="19845-302">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="19845-302">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="19845-303">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="19845-303">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="19845-304">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="19845-304">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="19845-305">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="19845-305">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="19845-306">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="19845-306">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="19845-307">Word</span><span class="sxs-lookup"><span data-stu-id="19845-307">Word</span></span>

- <span data-ttu-id="19845-308">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="19845-308">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="19845-309">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="19845-309">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="19845-310">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="19845-310">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="19845-311">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="19845-311">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="19845-312">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="19845-312">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-315">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-315">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-316">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-316">Excel</span></span>

- <span data-ttu-id="19845-317">アドインは、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-317">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="19845-318">Excelとサード パーティの支援技術アプリケーションの一部との間でフォントを管理する際にメモリが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-318">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="19845-319">選択ロックがない図形を含むワークシート上で、アドインがホスト アイテムを要求すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-319">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-320">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-320">Outlook</span></span>

- <span data-ttu-id="19845-321">ユーザーがフォルダー間でアイテムを移動したときに、Folder.BeforeItemMove イベントが正常に起動しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-321">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="19845-322">予定表のアイテムが午前 0 時のしきい値にまたがっていると、終日イベントとして表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-322">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="19845-323">2 つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-323">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="19845-324">ユーザーが予定表をゲスト ユーザーと共有できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-324">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-325">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-325">PowerPoint</span></span>

- <span data-ttu-id="19845-326">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-326">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="19845-327">Project</span><span class="sxs-lookup"><span data-stu-id="19845-327">Project</span></span>

- <span data-ttu-id="19845-328">オプションをクリックすると Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-328">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="19845-329">Word</span><span class="sxs-lookup"><span data-stu-id="19845-329">Word</span></span>

- <span data-ttu-id="19845-330">コメント内のハイパーリンクが機能しなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-330">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="19845-331">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-331">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="19845-332">予定表用の WordMail に HTML を貼り付けできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-332">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="19845-333">共同編集セッションのコメントに返信すると、Word がフリーズすることがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-333">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-15"></a><span data-ttu-id="19845-335">バージョン 2006: 5 月 15 日</span><span class="sxs-lookup"><span data-stu-id="19845-335">Version 2006: May 15</span></span>
<span data-ttu-id="19845-336">*バージョン 2006 (ビルド 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="19845-336">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-338">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-338">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="19845-339">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-339">Excel</span></span>

- <span data-ttu-id="19845-340">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="19845-340">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="19845-341">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-341">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="19845-342">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-342">Outlook</span></span>

- <span data-ttu-id="19845-343">**必要なものだけを見つける:** フォルダー、送信者、日付、添付ファイル情報などのオプションで検索を絞り込みます。</span><span class="sxs-lookup"><span data-stu-id="19845-343">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-344">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-344">PowerPoint</span></span>

- <span data-ttu-id="19845-345">\*\*クリッカーは不要: イヤホンでカバー: \*\* Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="19845-345">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="19845-346">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="19845-346">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="19845-347">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="19845-347">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="19845-348">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-348">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="19845-349">Word</span><span class="sxs-lookup"><span data-stu-id="19845-349">Word</span></span>

- <span data-ttu-id="19845-350">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="19845-350">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-353">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-353">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="19845-354">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-354">Excel</span></span>
- <span data-ttu-id="19845-355">ユーザーがマージされた列を削除したときのパフォーマンス時間が向上する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-355">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="19845-356">使用可能なプリンターのリストでプリンター名が重複する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-356">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="19845-357">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-357">PowerPoint</span></span>
- <span data-ttu-id="19845-358">英語スイス (QWERTZ) キーボードを使用すると、キーボード ショートカットとスペル チェックが期待どおりに機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-358">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="19845-359">Word</span><span class="sxs-lookup"><span data-stu-id="19845-359">Word</span></span>
- <span data-ttu-id="19845-360">空白のドキュメントに新しいコメントを追加しても何も発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-360">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="19845-361">100 個を超えるエントリを含むドキュメントにインデックスを挿入または更新すると、アプリケーションがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-361">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="19845-362">カスタム xml 値を含むファイルを開くのが非常に遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-362">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19845-363">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-363">Office Suite</span></span>
- <span data-ttu-id="19845-364">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-364">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-08"></a><span data-ttu-id="19845-367">バージョン 2006: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="19845-367">Version 2006: May 08</span></span>
<span data-ttu-id="19845-368">*バージョン 2006 (ビルド 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="19845-368">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-370">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-370">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="19845-371">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-371">Excel</span></span>

- <span data-ttu-id="19845-372">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-372">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-373">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-373">Outlook</span></span>

- <span data-ttu-id="19845-374">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="19845-374">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="19845-375">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-375">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="19845-376">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-376">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-377">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-377">PowerPoint</span></span>

- <span data-ttu-id="19845-378">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-378">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="19845-379">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-379">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="19845-380">Word</span><span class="sxs-lookup"><span data-stu-id="19845-380">Word</span></span>

- <span data-ttu-id="19845-381">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-381">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-384">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-384">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="19845-385">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-385">Office Suite</span></span>

- <span data-ttu-id="19845-386">OS のシャットダウン後、InTune を介した Office 365 ProPlus の展開が停止する問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="19845-386">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-01"></a><span data-ttu-id="19845-388">バージョン 2005: 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="19845-388">Version 2005: May 01</span></span>
<span data-ttu-id="19845-389">*バージョン 2005 (ビルド 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="19845-389">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-391">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-391">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-392">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-392">Outlook</span></span>

- <span data-ttu-id="19845-393">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="19845-393">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="19845-394">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="19845-394">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="19845-395">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-395">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-398">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-398">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-399">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-399">Excel</span></span>

- <span data-ttu-id="19845-400">グラフのデータ テーブルの日付軸の値が正しく表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-400">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="19845-401">[ページ レイアウト] または [改ページ プレビュー] に移動した後に、改ページを無効にできなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-401">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="19845-402">系列のデータを含む列を非表示にしてから非表示を解除すると、グラフの線のスタイルが失われる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-402">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="19845-403">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="19845-403">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="19845-404">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="19845-404">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="19845-405">[Invert if negative]\(負の値を反転する\) オプションが有効になっていると、ピボット グラフのカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-405">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="19845-406">[Invert if negative]\(負の値を反転する\) オプションが選択されていると、ピボット グラフの単一のデータ ポイントに対するカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-406">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="19845-407">この変更により、CSV ファイルで "@" 文字をアップロードすると、その "@" 文字以降の文字列が数式に変換される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-407">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="19845-408">SEQUENCE 関数で小数点以下が正しく四捨五入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-408">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-409">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-409">Outlook</span></span>

- <span data-ttu-id="19845-410">Outlook デスクトップ クライアントで、ユーザーがクリックした非常に長いセーフリンクが、切り捨てにより読み込みに失敗する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-410">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="19845-411">DBCS (2 バイト文字セット) 文字を含む名前が付けられた Outlook フォルダーが、サーバーと同期するときに断続的に表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-411">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="19845-412">この問題が発生する場合は、Outlook を IMAP アカウントを使用して構成し、ロケールが日本語に設定されたシステム上で実行する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="19845-412">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-413">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-413">PowerPoint</span></span>

- <span data-ttu-id="19845-414">ユーザーがコメントを作成したのに投稿せずにそのコメント ウィンドウを閉じ、新しいウィンドウを開いて、複数のスライドを移動してからそのウィンドウを閉じ、最後に、元のプレゼンテーションでコメント ウィンドウをもう一度開くと、下書きのコメントが利用できなくなっている問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-414">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="19845-415">Project</span><span class="sxs-lookup"><span data-stu-id="19845-415">Project</span></span>

- <span data-ttu-id="19845-416">Project が Project Web App に接続されていて、小数点の記号がカンマの場合、タイム ラグを追加する際に TaskDependencies Add メソッドが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-416">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="19845-417">Word</span><span class="sxs-lookup"><span data-stu-id="19845-417">Word</span></span>

- <span data-ttu-id="19845-418">コラボレーション モードのドキュメントにコメントを挿入しても正常に動作しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-418">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="19845-419">この変更により、@メンションがクリックされると連絡先カードが点滅する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-419">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="19845-420">下書きのコメントを含むドキュメントを閉じようとすると、その下書きのコメントを保存せずにドキュメントを閉じてもよいかユーザーに確認を求める問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-420">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="19845-421">このプロンプトをキャンセルすると、ドキュメントが開いたままになるのではなく、閉じられていました。</span><span class="sxs-lookup"><span data-stu-id="19845-421">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="19845-422">投稿されたコメントを翻訳しようとすると、"Inserting translated text failed" (翻訳されたテキストの挿入に失敗しました) エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-422">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="19845-423">Web ビュー/イマーシブ リーダーでヒントをクリックすると、ヒントが既に表示されている場合でも一番上までスクロールしていました。</span><span class="sxs-lookup"><span data-stu-id="19845-423">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="19845-424">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-424">This has been fixed.</span></span>
- <span data-ttu-id="19845-425">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても WRO0004.docx というファイル名で保存されるため、そのドキュメントを使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-425">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-24"></a><span data-ttu-id="19845-427">バージョン 2005: 4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="19845-427">Version 2005: April 24</span></span>
<span data-ttu-id="19845-428">*バージョン 2005 (ビルド 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="19845-428">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-430">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-430">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-431">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-431">Excel</span></span>
- <span data-ttu-id="19845-432">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-432">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="19845-433">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-433">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-434">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-434">Outlook</span></span>
- <span data-ttu-id="19845-435">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-435">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="19845-436">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-436">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-437">PowerPoint</span></span>
- <span data-ttu-id="19845-438">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-438">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="19845-439">Word</span><span class="sxs-lookup"><span data-stu-id="19845-439">Word</span></span>
- <span data-ttu-id="19845-440">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="19845-440">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="19845-441">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-441">This has been fixed.</span></span>
- <span data-ttu-id="19845-442">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-442">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-17"></a><span data-ttu-id="19845-444">バージョン 2005: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="19845-444">Version 2005: April 17</span></span>
<span data-ttu-id="19845-445">*バージョン 2005 (ビルド 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="19845-445">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-447">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-447">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-448">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-448">Excel</span></span>
- <span data-ttu-id="19845-449">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="19845-449">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="19845-450">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="19845-450">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="19845-451">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-451">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="19845-452">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="19845-452">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="19845-453">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-453">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="19845-454">OneNote</span><span class="sxs-lookup"><span data-stu-id="19845-454">OneNote</span></span>
- <span data-ttu-id="19845-455">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-455">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-456">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-456">Outlook</span></span>
- <span data-ttu-id="19845-457">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-457">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="19845-458">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-458">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="19845-459">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-459">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="19845-460">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="19845-460">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="19845-461">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-461">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="19845-462">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-462">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="19845-463">Project</span><span class="sxs-lookup"><span data-stu-id="19845-463">Project</span></span>
- <span data-ttu-id="19845-464">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="19845-464">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="19845-465">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-465">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="19845-466">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-466">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2004-april-10"></a><span data-ttu-id="19845-468">バージョン 2004: 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="19845-468">Version 2004: April 10</span></span>
<span data-ttu-id="19845-469">*バージョン 2004 (ビルド 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="19845-469">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-471">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-471">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="19845-472">Access</span><span class="sxs-lookup"><span data-stu-id="19845-472">Access</span></span>

- <span data-ttu-id="19845-473">**[テーブルの表示] ダイアログ ボックスをバイパスし、作業ウィンドウに直接移動して、テーブルを効率よくリレーションシップやクエリに追加します。:** 4 つのタブをクリックして、名前を複数選択して、テキストで検索し、作業中に開いたままの作業ウィンドウからドラッグして、テーブルやクエリを追加 ます。</span><span class="sxs-lookup"><span data-stu-id="19845-473">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="19845-474">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-474">Excel</span></span>

- <span data-ttu-id="19845-475">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="19845-475">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="19845-476">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="19845-476">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-477">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-477">Outlook</span></span>

- <span data-ttu-id="19845-478">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="19845-478">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="19845-479">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="19845-479">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="19845-480">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="19845-480">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-481">PowerPoint</span></span>

- <span data-ttu-id="19845-482">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="19845-482">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="19845-483">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="19845-483">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="19845-484">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="19845-484">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="19845-485">Word</span><span class="sxs-lookup"><span data-stu-id="19845-485">Word</span></span>

- <span data-ttu-id="19845-486">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="19845-486">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="19845-487">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="19845-487">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="19845-488">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成します。</span><span class="sxs-lookup"><span data-stu-id="19845-488">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="19845-489">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="19845-489">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-492">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-492">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="19845-493">Access</span><span class="sxs-lookup"><span data-stu-id="19845-493">Access</span></span>

- <span data-ttu-id="19845-494">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-494">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="19845-495">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-495">Excel</span></span>

- <span data-ttu-id="19845-496">シートのセル範囲を選択すると、1 つのセルが選択されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-496">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="19845-497">X 軸の範囲に合わせてグラフのサイズを小さくすると、Excel が応答を停止する可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-497">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="19845-498">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-498">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="19845-499">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-499">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="19845-500">R1C1 セルの参照が有効になっている Excel シートが共同編集/共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動すると、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-500">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-501">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-501">Outlook</span></span>

- <span data-ttu-id="19845-502">メール メッセージからカテゴリが消えることがあるという問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="19845-502">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="19845-503">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-503">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="19845-504">ユーザーが組織フォームのプロパティを表示とするときにクラッシュするという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-504">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="19845-505">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが発生しないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-505">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-506">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-506">PowerPoint</span></span>

- <span data-ttu-id="19845-507">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-507">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="19845-508">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-508">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="19845-509">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-509">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="19845-510">Project</span><span class="sxs-lookup"><span data-stu-id="19845-510">Project</span></span>

- <span data-ttu-id="19845-511">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-511">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="19845-512">Word</span><span class="sxs-lookup"><span data-stu-id="19845-512">Word</span></span>

- <span data-ttu-id="19845-513">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-513">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="19845-514">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-514">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="19845-515">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-515">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="19845-516">この変更により、コメントを作成するとき、コメント アンカーが表示されない場合があるという 2 ページ表示の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-516">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="19845-517">スタイルがリストにリンクされている祖先のスタイルである段落の場合、そのリストの番号が失われる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-517">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-27"></a><span data-ttu-id="19845-519">バージョン 2004: 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="19845-519">Version 2004: March 27</span></span>
<span data-ttu-id="19845-520">*バージョン 2004 (ビルド 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="19845-520">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-522">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-522">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-523">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-523">Outlook</span></span>

- <span data-ttu-id="19845-524">**メール作成時の @ メンションの候補表示を無効にするオプションが追加されました。** メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="19845-524">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="19845-525">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="19845-525">Now you can turn it off if you prefer.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-528">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-528">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-529">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-529">Outlook</span></span>
- <span data-ttu-id="19845-530">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-530">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="19845-531">ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-531">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="19845-532">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-532">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-533">PowerPoint</span></span>
- <span data-ttu-id="19845-534">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-534">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="19845-535">Project</span><span class="sxs-lookup"><span data-stu-id="19845-535">Project</span></span>
- <span data-ttu-id="19845-536">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-536">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="19845-537">Word</span><span class="sxs-lookup"><span data-stu-id="19845-537">Word</span></span>
- <span data-ttu-id="19845-538">この変更により、 [表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-538">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-20"></a><span data-ttu-id="19845-540">バージョン 2004: 3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="19845-540">Version 2004: March 20</span></span>
<span data-ttu-id="19845-541">*バージョン 2004 (ビルド 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="19845-541">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-543">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-543">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-544">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-544">Outlook</span></span>

- <span data-ttu-id="19845-545">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="19845-545">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="19845-546">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="19845-546">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="19845-547">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="19845-547">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-548">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-548">PowerPoint</span></span>

- <span data-ttu-id="19845-549">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="19845-549">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-552">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-552">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-553">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-553">Excel</span></span>

- <span data-ttu-id="19845-554">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="19845-554">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-555">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-555">Outlook</span></span>

- <span data-ttu-id="19845-556">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="19845-556">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="19845-557">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-557">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="19845-558">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="19845-558">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="19845-559">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="19845-559">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="19845-560">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-560">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="19845-561">Project</span><span class="sxs-lookup"><span data-stu-id="19845-561">Project</span></span>

- <span data-ttu-id="19845-562">ユーザーがスケジュール グループ内の [タスク] リボンにある「無効化」ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Applications (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-562">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="19845-563">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="19845-563">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="19845-564">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="19845-564">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="19845-565">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-565">This behavior has been fixed.</span></span>

- <span data-ttu-id="19845-566">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-566">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="19845-567">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-567">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="19845-568">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-568">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="19845-569">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-569">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="19845-570">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="19845-570">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="19845-571">Word</span><span class="sxs-lookup"><span data-stu-id="19845-571">Word</span></span>

- <span data-ttu-id="19845-572">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-572">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="19845-573">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="19845-573">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="19845-574">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="19845-574">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="19845-575">この変更により、文書に記載されていない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-575">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="19845-576">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="19845-576">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-13"></a><span data-ttu-id="19845-578">バージョン 2004: 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="19845-578">Version 2004: March 13</span></span>
<span data-ttu-id="19845-579">*バージョン 2004 (ビルド 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="19845-579">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-581">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-581">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="19845-582">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-582">Excel</span></span>
- <span data-ttu-id="19845-583">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-583">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="19845-584">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-584">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="19845-585">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-585">PowerPoint</span></span>
- <span data-ttu-id="19845-586">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-586">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="19845-587">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-587">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="19845-588">Word</span><span class="sxs-lookup"><span data-stu-id="19845-588">Word</span></span>
- <span data-ttu-id="19845-589">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="19845-589">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="19845-590">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-590">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-593">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-593">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="19845-594">Access</span><span class="sxs-lookup"><span data-stu-id="19845-594">Access</span></span>
- <span data-ttu-id="19845-595">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-595">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="19845-596">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-596">Excel</span></span>
- <span data-ttu-id="19845-597">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-597">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="19845-598">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-598">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-599">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-599">Outlook</span></span>
- <span data-ttu-id="19845-600">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-600">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="19845-601">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-601">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="19845-602">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-602">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="19845-603">Project</span><span class="sxs-lookup"><span data-stu-id="19845-603">Project</span></span>
- <span data-ttu-id="19845-604">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-604">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="19845-605">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-605">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="19845-606">Word</span><span class="sxs-lookup"><span data-stu-id="19845-606">Word</span></span>
- <span data-ttu-id="19845-607">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-607">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="19845-608">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-608">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="19845-609">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-609">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="19845-610">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-610">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-06"></a><span data-ttu-id="19845-612">バージョン 2003: 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="19845-612">Version 2003: March 06</span></span>
<span data-ttu-id="19845-613">*バージョン 2003 (ビルド 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="19845-613">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-615">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-615">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-616">Outlook</span></span>

- <span data-ttu-id="19845-617">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-617">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="19845-618">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-618">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="19845-619">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-619">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-620">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-620">PowerPoint</span></span>

- <span data-ttu-id="19845-621">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-621">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="19845-622">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="19845-622">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="19845-623">Word</span><span class="sxs-lookup"><span data-stu-id="19845-623">Word</span></span>

- <span data-ttu-id="19845-624">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-624">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19845-625">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-625">Office Suite</span></span>

- <span data-ttu-id="19845-626">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-626">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="19845-627">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-627">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2003-february-28"></a><span data-ttu-id="19845-630">バージョン 2003: 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="19845-630">Version 2003: February 28</span></span>
<span data-ttu-id="19845-631">*バージョン 2003 (ビルド 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="19845-631">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-633">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-633">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-634">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-634">Outlook</span></span>

- <span data-ttu-id="19845-635">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="19845-635">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="19845-636">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-636">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="19845-637">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-637">PowerPoint</span></span>

- <span data-ttu-id="19845-638">\*\*インクを図形に変換する作図エクスペリエンスの向上: \*\*より良い図を描いて変換し、Office オブジェクトを操作できるようにします。[詳細情報](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="19845-638">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-641">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-641">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19845-642">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-642">Excel</span></span>

- <span data-ttu-id="19845-643">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-643">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-644">Outlook</span></span>

- <span data-ttu-id="19845-645">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-645">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="19845-646">Word</span><span class="sxs-lookup"><span data-stu-id="19845-646">Word</span></span>

- <span data-ttu-id="19845-647">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-647">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="19845-648">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="19845-648">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="19845-649">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-649">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19845-650">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-650">Office Suite</span></span>

- <span data-ttu-id="19845-651">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-651">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-21"></a><span data-ttu-id="19845-653">バージョン 2003: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="19845-653">Version 2003: February 21</span></span>
<span data-ttu-id="19845-654">*バージョン 2003 (ビルド 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="19845-654">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-656">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-656">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="19845-657">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-657">Office Suite</span></span>

- <span data-ttu-id="19845-658">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキスト ハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="19845-658">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-661">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-661">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="19845-662">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-662">Excel</span></span>
- <span data-ttu-id="19845-663">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-663">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="19845-664">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-664">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="19845-665">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-665">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="19845-666">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-666">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="19845-667">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-667">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-668">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-668">Outlook</span></span>
- <span data-ttu-id="19845-669">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="19845-669">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="19845-670">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-670">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="19845-671">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="19845-671">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="19845-672">Word</span><span class="sxs-lookup"><span data-stu-id="19845-672">Word</span></span>
- <span data-ttu-id="19845-673">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-673">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="19845-674">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="19845-674">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="19845-675">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="19845-675">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19845-676">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-676">Office Suite</span></span>
- <span data-ttu-id="19845-677">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="19845-677">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="19845-678">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="19845-678">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="19845-679">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="19845-679">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-14"></a><span data-ttu-id="19845-681">バージョン 2003: 2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="19845-681">Version 2003: February 14</span></span>
<span data-ttu-id="19845-682">*バージョン 2003 (ビルド 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="19845-682">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-684">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-684">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-685">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-685">Outlook</span></span>

- <span data-ttu-id="19845-686">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="19845-686">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="19845-687">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="19845-687">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="19845-688">Word</span><span class="sxs-lookup"><span data-stu-id="19845-688">Word</span></span>

- <span data-ttu-id="19845-689">**描画ツールボックスでインク エディターを見つける**: [描画] を選択し、[インク エディター] ペンを選択して、指またはデジタル ペンでドキュメントを編集します。</span><span class="sxs-lookup"><span data-stu-id="19845-689">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="19845-690">詳細情報</span><span class="sxs-lookup"><span data-stu-id="19845-690">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="19845-691">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-691">Office Suite</span></span>

- <span data-ttu-id="19845-692">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました</span><span class="sxs-lookup"><span data-stu-id="19845-692">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-695">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-695">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="19845-696">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-696">Outlook</span></span>

- <span data-ttu-id="19845-697">ユーザーが「空き時間情報オプション」予定表のアクセス許可ダイアログにアクセスできなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="19845-697">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="19845-698">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「申し訳ございません、このアイテムを開くことができません」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-698">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="19845-699">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="19845-699">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="19845-700">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-700">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-701">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-701">PowerPoint</span></span>

- <span data-ttu-id="19845-702">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-702">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="19845-703">Word</span><span class="sxs-lookup"><span data-stu-id="19845-703">Word</span></span>

- <span data-ttu-id="19845-704">ドキュメントを PDF にエクスポートすると、画像の透明性が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-704">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-07"></a><span data-ttu-id="19845-706">バージョン 2002: 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="19845-706">Version 2002: February 07</span></span>
<span data-ttu-id="19845-707">*バージョン 2002 (ビルド 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="19845-707">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="19845-709">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="19845-709">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="19845-710">Access</span><span class="sxs-lookup"><span data-stu-id="19845-710">Access</span></span>

- <span data-ttu-id="19845-711">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="19845-711">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="19845-712">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="19845-712">Search and replace text in SQL View.</span></span> <span data-ttu-id="19845-713">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="19845-713">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="19845-716">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="19845-716">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="19845-717">Access</span><span class="sxs-lookup"><span data-stu-id="19845-717">Access</span></span>

- <span data-ttu-id="19845-718">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="19845-718">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="19845-719">VB コードのレコーダー オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="19845-719">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="19845-720">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="19845-720">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="19845-721">Excel</span><span class="sxs-lookup"><span data-stu-id="19845-721">Excel</span></span>

- <span data-ttu-id="19845-722">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-722">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="19845-723">Outlook</span><span class="sxs-lookup"><span data-stu-id="19845-723">Outlook</span></span>

- <span data-ttu-id="19845-724">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-724">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="19845-725">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="19845-725">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19845-726">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19845-726">PowerPoint</span></span>

- <span data-ttu-id="19845-727">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-727">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="19845-728">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="19845-728">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="19845-729">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="19845-729">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="19845-730">Word</span><span class="sxs-lookup"><span data-stu-id="19845-730">Word</span></span>

- <span data-ttu-id="19845-731">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="19845-731">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="19845-732">ドキュメントが共同編集されている場合、ルート コメントのドラフト バージョンが保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-732">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="19845-733">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-733">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="19845-734">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-734">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="19845-735">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="19845-735">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="19845-736">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="19845-736">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19845-737">Office スイート</span><span class="sxs-lookup"><span data-stu-id="19845-737">Office Suite</span></span>

- <span data-ttu-id="19845-738">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="19845-738">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|DevMain|Insiders| |16.0.13102.20002|version-2008-july-10|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
