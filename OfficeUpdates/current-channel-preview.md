---
title: リリース ノートの最新チャネル (プレビュー)
ms.author: anankani
author: v-lislo
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Slow の対象ユーザーに新機能、修正プログラム、または既知の問題の最新リストを提供します
ms.openlocfilehash: 2702cc1098282aa53972a2b01beb8eb9545b04ff
ms.sourcegitcommit: 4b5ee25e335d9585dfe5660faac747600c9e3e69
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/23/2020
ms.locfileid: "49382637"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="724ce-103">Office 向けリリース ノートの最新チャネル (プレビュー)</span><span class="sxs-lookup"><span data-stu-id="724ce-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="724ce-p101">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span><span class="sxs-lookup"><span data-stu-id="724ce-p101">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="724ce-p102">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="724ce-p102">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="724ce-111">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-111">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (削除しないでください)

## <a name="version-2011-november-21"></a><span data-ttu-id="724ce-113">バージョン 2011: 11 月 21 日</span><span class="sxs-lookup"><span data-stu-id="724ce-113">Version 2011: November 21</span></span>
<span data-ttu-id="724ce-114">*バージョン 2011 (ビルド 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="724ce-114">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-116">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-116">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="724ce-117">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-117">PowerPoint</span></span>

- <span data-ttu-id="724ce-118">**ビデオ ライブラリ:** は、アプリ内で利用可能な、質の良い無料のビデオ フッテージのライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="724ce-118">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-121">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-121">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-122">Outlook</span></span>

- <span data-ttu-id="724ce-123">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="724ce-123">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="724ce-124">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にすることを許可できるように、レジストリキーを追加しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-124">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="724ce-125">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\添付ファイル。</span><span class="sxs-lookup"><span data-stu-id="724ce-125">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="724ce-126">REG_DWORD IncludeFileTimesInDataObject。</span><span class="sxs-lookup"><span data-stu-id="724ce-126">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="724ce-127">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-127">0 = filetimes are excluded.</span></span> <span data-ttu-id="724ce-128">1 = (既定) filetimes が含まれています</span><span class="sxs-lookup"><span data-stu-id="724ce-128">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="724ce-129">Azure Information Protection の保護ラベルを使用してメッセージに返信すると、インライン画像が表示されなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-129">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (BUGDETAILS コンテンツ を削除しないでください。終了)

## <a name="version-2011-november-18"></a><span data-ttu-id="724ce-131">バージョン 2011: 11 月 18 日</span><span class="sxs-lookup"><span data-stu-id="724ce-131">Version 2011: November 18</span></span>
<span data-ttu-id="724ce-132">*バージョン 2011 (ビルド 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="724ce-132">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="724ce-133">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-133">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="724ce-134">バージョン 2011: 11 月 16 日</span><span class="sxs-lookup"><span data-stu-id="724ce-134">Version 2011: November 16</span></span>
<span data-ttu-id="724ce-135">*バージョン 2011 (ビルド 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="724ce-135">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-137">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-137">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-138">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-138">Outlook</span></span>

- <span data-ttu-id="724ce-139">**同じ署名、すべてのデバイス:** 署名をクラウドに保存し ます。</span><span class="sxs-lookup"><span data-stu-id="724ce-139">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="724ce-140">一度作成して、Outlook を使用するすべての場所で使用します。</span><span class="sxs-lookup"><span data-stu-id="724ce-140">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-143">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-143">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-144">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-144">Outlook</span></span>

- <span data-ttu-id="724ce-145">タスクに対する進捗レポートの送信時に、[宛先] フィールドが空白になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-145">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="724ce-146">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-146">PowerPoint</span></span>

- <span data-ttu-id="724ce-147">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) でクラッシュする VBA 問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-147">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (BUGDETAILS コンテンツ を削除しないでください。終了)

## <a name="version-2011-november-09"></a><span data-ttu-id="724ce-149">バージョン 2011: 11 月 09 日</span><span class="sxs-lookup"><span data-stu-id="724ce-149">Version 2011: November 09</span></span>
<span data-ttu-id="724ce-150">*バージョン 2011 (ビルド 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="724ce-150">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-152">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-152">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-153">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-153">Excel</span></span>

- <span data-ttu-id="724ce-154">**クエリから Powe rPlatform データフローを作成する**: 新しい Powe rPlatform データフローの作成に使用できる Power Query テンプレートにクエリをエクスポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-154">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-157">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-157">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-158">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-158">Access</span></span>

- <span data-ttu-id="724ce-159">同期済みの OneDrive フォルダーからクエリをエクスポートしようとしたときに、一部のユーザーに "システム リソースの超過" というエラーが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-159">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="724ce-160">フォーム ウィンドウ間で別のフォームに切り替える場合の「自動」切り替えの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-160">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="724ce-161">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-161">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="724ce-162">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-162">Excel</span></span>

- <span data-ttu-id="724ce-163">COM アドインを有効にして SaveAs 操作を行った後、ファイル名が変更されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-163">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="724ce-164">Oracle データベースへの接続を使用する際の Power Pivot の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-164">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="724ce-165">Excel データモデルに不適切なメジャー定義がある場合に、自動保存が誤った、または誤解を招くエラーメッセージを表示して失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-165">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="724ce-166">MTR 計算およびグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) のプロセスがトリガーされたときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-166">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="724ce-167">ユーザーが SharePoint から .atomsvc (UTF8 + BOM) ファイルを直接開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-167">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="724ce-168">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-168">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="724ce-169">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-169">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="724ce-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-170">Outlook</span></span>

- <span data-ttu-id="724ce-171">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-171">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="724ce-172">画像の添付ファイルをクイック印刷すると、以下のエラーが発生する問題を修正しました。「Windows がこの画像を見つけることができません。</span><span class="sxs-lookup"><span data-stu-id="724ce-172">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="724ce-173">場所を確認してから、もう一度お試しください」。</span><span class="sxs-lookup"><span data-stu-id="724ce-173">Check the location, and then try again".</span></span>


- <span data-ttu-id="724ce-174">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-174">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="724ce-175">会議の場所からコピーした URL をブラウザーなどの別の場所に貼り付けると、URL の末尾にセミコロンが含まれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-175">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="724ce-176">ユーザーが基本認証で Microsoft 365 グループの予定表の予定を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-176">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="724ce-177">ニックネーム キャッシュの読み込み中に Outlook の起動に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-177">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="724ce-178">オプションがグレー表示され、メールボックスの所有者が自分のカレンダーの共有権限を管理できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-178">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="724ce-179">Outlook が制限付きのアクセス許可でメッセージを作成できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-179">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="724ce-180">メールテンプレートを .OFT として保存すると、中国語の文字が疑問符に変わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-180">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="724ce-181">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-181">PowerPoint</span></span>

- <span data-ttu-id="724ce-182">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-182">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="724ce-183">画像の横のコンテンツ プレースホルダー アイコンにツールヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-183">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="724ce-184">pptsx ファイルで表示されるスライド ショーの保護されたビューで、IRM で保護されたドキュメントの画面キャプチャが許可される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-184">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="724ce-185">デザインウィンドウを閉じるときにグリッド線がスライドからずれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-185">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="724ce-186">スライドショーを 2 台目のモニターに複製する場合、そのスライドショーが他のウィンドウの背面で非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-186">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="724ce-187">選択ウィンドウを開いた状態で画面の記録を停止した後、スライドのスクロールバーが自動的に調整を開始する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-187">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="724ce-188">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-188">Project</span></span>

- <span data-ttu-id="724ce-189">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-189">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="724ce-190">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-190">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="724ce-191">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-191">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="724ce-192">リソースエンゲージメントが GUID ではなく名前でリソースを検索する問題を修正しました。同じ名前のリソースが複数ある場合に問題が発生していました。</span><span class="sxs-lookup"><span data-stu-id="724ce-192">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="724ce-193">プロジェクトサイトにタスクリストがあり、タスクリストをグループ化すると、タスクリストをすばやく編集できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-193">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="724ce-194">CSOM を介してエンタープライズリソースを更新すると、リソースの最大単位数が失われることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-194">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="724ce-195">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-195">Word</span></span>

- <span data-ttu-id="724ce-196">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-196">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="724ce-197">コメントヒントをクリックしてもズームアウトしてコメントカードが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-197">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="724ce-198">列間の線がずれている場合があるレイアウトの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-198">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="724ce-199">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-199">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="724ce-200">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-200">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="724ce-201">機密度ラベルに透かしが適用される場合がある印刷の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-201">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-202">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-202">Office Suite</span></span>

- <span data-ttu-id="724ce-203">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-203">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="724ce-204">SSO API インタラクティブ サインインがエラー コードを返す問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-204">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2010-november-06"></a><span data-ttu-id="724ce-206">バージョン 2010: 11 月 6 日</span><span class="sxs-lookup"><span data-stu-id="724ce-206">Version 2010: November 06</span></span>
<span data-ttu-id="724ce-207">*バージョン 2010 (ビルド 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="724ce-207">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="724ce-208">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-208">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-04"></a><span data-ttu-id="724ce-211">バージョン 2010: 11 月 4 日</span><span class="sxs-lookup"><span data-stu-id="724ce-211">Version 2010: November 04</span></span>
<span data-ttu-id="724ce-212">*バージョン 2010 (ビルド 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="724ce-212">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-214">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-214">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-215">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-215">Excel</span></span>

- <span data-ttu-id="724ce-216">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-216">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="724ce-217">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-217">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="724ce-218">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-218">Outlook</span></span>

- <span data-ttu-id="724ce-219">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-219">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="724ce-220">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-220">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="724ce-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-221">PowerPoint</span></span>

- <span data-ttu-id="724ce-222">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-222">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="724ce-223">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-223">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="724ce-224">[ブログ記事](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-224">See details in [blog post](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="724ce-225">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-225">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="724ce-226">[ブログ記事](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-226">See details in [blog post](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="724ce-227">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します</span><span class="sxs-lookup"><span data-stu-id="724ce-227">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="724ce-228">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-228">Word</span></span>

- <span data-ttu-id="724ce-229">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-229">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="724ce-230">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-230">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-233">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-233">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-234">Outlook</span></span>

- <span data-ttu-id="724ce-235">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-235">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-236">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-236">Office Suite</span></span>

- <span data-ttu-id="724ce-237">同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-237">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2010-october-27"></a><span data-ttu-id="724ce-239">バージョン 2010: 10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="724ce-239">Version 2010: October 27</span></span>
<span data-ttu-id="724ce-240">*バージョン 2010 (ビルド 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="724ce-240">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-244">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-244">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-245">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-245">Outlook</span></span>

- <span data-ttu-id="724ce-246">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-246">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="724ce-247">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-247">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-24"></a><span data-ttu-id="724ce-249">バージョン 2010: 10 月 24 日</span><span class="sxs-lookup"><span data-stu-id="724ce-249">Version 2010: October 24</span></span>
<span data-ttu-id="724ce-250">*バージョン 2010 (ビルド 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="724ce-250">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-254">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-254">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-255">Outlook</span></span>

- <span data-ttu-id="724ce-256">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-256">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="724ce-257">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-257">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="724ce-258">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-258">Project</span></span>

- <span data-ttu-id="724ce-259">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-259">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="724ce-260">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-260">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-19"></a><span data-ttu-id="724ce-262">バージョン 2010 : 10 月 19 日</span><span class="sxs-lookup"><span data-stu-id="724ce-262">Version 2010: October 19</span></span>
<span data-ttu-id="724ce-263">*バージョン 2010 (ビルド 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="724ce-263">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-265">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-265">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-266">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-266">Outlook</span></span>

- <span data-ttu-id="724ce-267">**メッセージの作成にかかる時間を節約:** Outlook は、メッセージをすばやく作成するのに役立つ提案を作成することを示します。</span><span class="sxs-lookup"><span data-stu-id="724ce-267">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="724ce-268">提案を受け入れるには、Tab キーを使用するだけです。</span><span class="sxs-lookup"><span data-stu-id="724ce-268">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="724ce-269">[ブログ記事](https://insider.office.com/en-us/blog/text-predictions-in-word-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-269">See details in [blog post](https://insider.office.com/en-us/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="724ce-270">**組み込みの翻訳機能を使用して、言語の壁を取り除く:** 翻訳用のアドインは必要なくなりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-270">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="724ce-271">メッセージを右クリックすると、特定の単語、語句、またはメッセージ全体を翻訳できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-271">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="724ce-272">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-272">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="724ce-273">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新</span><span class="sxs-lookup"><span data-stu-id="724ce-273">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-274">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-274">PowerPoint</span></span>

- <span data-ttu-id="724ce-275">**発表者のコーチでプレゼンテーションを練習する:** 話す速度、特定の単語を使いすぎていないか、ボディーランゲージなど、聴衆の関心を引きつけておくのに役立つ内容についてコーチングを受けます。</span><span class="sxs-lookup"><span data-stu-id="724ce-275">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="724ce-276">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-276">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="724ce-277">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-277">Word</span></span>

- <span data-ttu-id="724ce-278">**Microsoft エディター ウィンドウにデスクトップ用の Word の更新が表示される:** デスクトップ クライアント用の Word エディター ウィンドウの現在のエクスペリエンスをアップグレードしました。</span><span class="sxs-lookup"><span data-stu-id="724ce-278">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="724ce-279">**ワンクリック ライティング候補:** ワンクリックでライティング候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-279">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="724ce-280">更新されたエディターウィンドウを使って、候補間を簡単に移動できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-280">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-283">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-283">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="724ce-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-284">PowerPoint</span></span>

- <span data-ttu-id="724ce-285">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="724ce-285">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-11"></a><span data-ttu-id="724ce-287">バージョン 2010: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="724ce-287">Version 2010: October 11</span></span>
<span data-ttu-id="724ce-288">*バージョン 2010 (ビルド13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="724ce-288">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-290">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-290">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-291">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-291">Excel</span></span>

- <span data-ttu-id="724ce-292">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-292">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="724ce-293">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-293">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="724ce-294">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-294">PowerPoint</span></span>

- <span data-ttu-id="724ce-295">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-295">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="724ce-296">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-296">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="724ce-297">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-297">Word</span></span>

- <span data-ttu-id="724ce-298">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-298">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="724ce-299">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-299">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-302">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-302">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-303">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-303">Access</span></span>

- <span data-ttu-id="724ce-304">スクロール中に保存されたクエリ/リレーションシップ ウィンドウを読み込むときに、スクロールバーの位置が正しく設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-304">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="724ce-305">[テーブルを追加する] 作業ウィンドウに「&」を含む名前が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-305">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="724ce-306">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-306">Excel</span></span>

- <span data-ttu-id="724ce-307">マルチレベル カテゴリの手動間隔がグラフで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-307">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="724ce-308">VBA を使用した、シリーズの最大値、中間値、最小値の色の設定が機能しないという 2D マップ グラフの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-308">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="724ce-309">Excel で 1 つまたは複数の数式を計算しようとする際に発生する、Excelはリソース不足になりましたというエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-309">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="724ce-310">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-310">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="724ce-311">[改ページ プレビュー] が有効になっているときに、大量のデータが含まれているワークシート間を切り替える際に顕著な遅延が発生する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-311">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="724ce-312">データ検証に使用されるテーブルに追加しても、ブック内のすべてのシートのオプションが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-312">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="724ce-313">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-313">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="724ce-314">数式バーに数式を入力したときに、ChartSheet がクラッシュする場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-314">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="724ce-315">デバイスへの接続が失われると (リモート セッションが接続されたり接続が解除されたり、モニターでの変更があった場合など) Excel の関数バーが完全に描画されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-315">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="724ce-316">OneNote</span><span class="sxs-lookup"><span data-stu-id="724ce-316">OneNote</span></span>

- <span data-ttu-id="724ce-317">ユーザーが OutSpace で [ファイル]、[情報] に移動してテキスト ボックスからノートブックの URL を選択してコピーできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-317">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="724ce-318">ノートブックのカラー セレクターで緑色にカーソルを合わせると、ポップアップに「赤チョーク」と表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-318">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="724ce-319">OneNote がカスタム テーマのキャンバスのハイ コントラスト カラーを尊重しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-319">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="724ce-320">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-320">Outlook</span></span>

- <span data-ttu-id="724ce-321">件名が空白の場合、自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-321">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="724ce-322">間違ったフォルダー GUID がフォルダーにキャッシュされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-322">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="724ce-323">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="724ce-323">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="724ce-324">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-324">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="724ce-325">オンライン共有フォルダーが親フォルダー名を返さない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-325">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="724ce-326">失敗する代わりに、プライマリ アカウントに誤って送信された空のパスを返しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-326">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="724ce-327">[名前を付けて保存] オプションが従来の添付ファイルで使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-327">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="724ce-328">ポリシーを上書きするときに正当化テキストをカスタマイズする方法をユーザーに提供する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-328">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="724ce-329">読み取り専のプレビュー ウィンドウから下書きを再開した後、トラックの変更がオンになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-329">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="724ce-330">優先受信トレイをオフにして並べ替えを行った後に、メールが非表示になるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-330">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="724ce-331">クラウド設定を有効にしているユーザーに対して、2つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-331">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="724ce-332">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-332">PowerPoint</span></span>

- <span data-ttu-id="724ce-333">PDF へのエクスポート中に PowerPoint が長方形の箇条書きをエクスポートしなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-333">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="724ce-334">エディターとスライド ショーで GIF のアニメーションが1 回だけしか再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-334">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="724ce-335">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-335">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="724ce-336">最後のスライドを表示していて、[セッションの終了] を押した後、概要が表示される前に次のスライドにスワイプすると、[セッションの終了] ダイアログ ボックスが概要ページにも表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-336">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="724ce-337">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-337">Project</span></span>

- <span data-ttu-id="724ce-338">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-338">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="724ce-339">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-339">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="724ce-340">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-340">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="724ce-341">数式を使用してカスタム フィールドを作成し、取得した値を使用している場合、表示の切り替えやプロジェクト/タスクの詳細を開く際にパフォーマンスの遅延が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-341">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="724ce-342">リソース配分状況ビューまたはシート ビューにグループ化を適用してから列を挿入すると、Project がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-342">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="724ce-343">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-343">Word</span></span>

- <span data-ttu-id="724ce-344">ワークフロー対応ファイルへのリンクが期待どおりに開かない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-344">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="724ce-345">変更履歴 (挿入/削除) をユーザーがタップすると、コメントがポップアップ表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-345">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="724ce-346">Word でコメントの吹き出しを削除するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-346">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="724ce-347">Outlook でメッセージが [転送不可] に設定される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-347">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="724ce-348">引用と数式を含む Word 文書を保存するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-348">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="724ce-349">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-349">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-350">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-350">Office Suite</span></span>

- <span data-ttu-id="724ce-351">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-351">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="724ce-352">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-352">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-07"></a><span data-ttu-id="724ce-354">バージョン 2009: 10 月 7 日</span><span class="sxs-lookup"><span data-stu-id="724ce-354">Version 2009: October 07</span></span>
<span data-ttu-id="724ce-355">*バージョン 2009 (ビルド 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="724ce-355">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-357">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-357">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-358">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-358">Excel</span></span>

- <span data-ttu-id="724ce-359">**Power Query を使用してデータ型を作成する: Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します**</span><span class="sxs-lookup"><span data-stu-id="724ce-359">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-360">Outlook</span></span>

- <span data-ttu-id="724ce-361">**文章校正による支援:** Outlook では、入力中に文章校正のエラーが表示されます。シングル クリックで候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-361">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="724ce-362">[ブログの投稿](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-362">See details in [blog post](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-365">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-365">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-366">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-366">Outlook</span></span>

- <span data-ttu-id="724ce-367">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-367">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="724ce-368">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-368">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="724ce-369">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-369">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="724ce-370">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-370">PowerPoint</span></span>

- <span data-ttu-id="724ce-371">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-371">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-372">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-372">Office Suite</span></span>

- <span data-ttu-id="724ce-373">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-373">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="724ce-374">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-374">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-26"></a><span data-ttu-id="724ce-376">バージョン 2009: 9 月 26　日</span><span class="sxs-lookup"><span data-stu-id="724ce-376">Version 2009: September 26</span></span>
<span data-ttu-id="724ce-377">*バージョン 2009 (ビルド13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="724ce-377">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-379">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-379">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-380">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-380">Outlook</span></span>

- <span data-ttu-id="724ce-381">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-381">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="724ce-382">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-382">Project</span></span>

- <span data-ttu-id="724ce-383">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-383">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-21"></a><span data-ttu-id="724ce-385">バージョン 2009: 9 月 21 日</span><span class="sxs-lookup"><span data-stu-id="724ce-385">Version 2009: September 21</span></span>
<span data-ttu-id="724ce-386">*バージョン 2009 (ビルド 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="724ce-386">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-388">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-388">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="724ce-389">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-389">Access</span></span>

- <span data-ttu-id="724ce-390">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-390">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-391">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-391">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-392">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-392">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="724ce-393">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-393">Excel</span></span>

- <span data-ttu-id="724ce-394">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-394">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="724ce-395">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-395">No conversion required.</span></span><br /><span data-ttu-id="724ce-396">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-396">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="724ce-397">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-397">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-398">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-398">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-399">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-399">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="724ce-400">OneNote</span><span class="sxs-lookup"><span data-stu-id="724ce-400">OneNote</span></span>

- <span data-ttu-id="724ce-401">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-401">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-402">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-402">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-403">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-403">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="724ce-404">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-404">Outlook</span></span>

- <span data-ttu-id="724ce-405">**メッセージの所有者として会話を削除する:** この機能を使用すると、メッセージの所有者による会話を削除できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-405">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="724ce-406">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-406">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="724ce-407">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-407">No conversion required.</span></span><br /><span data-ttu-id="724ce-408">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-408">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="724ce-409">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-409">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-410">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-410">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-411">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-411">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="724ce-412">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-412">PowerPoint</span></span>

- <span data-ttu-id="724ce-413">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-413">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="724ce-414">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-414">No conversion required.</span></span><br /><span data-ttu-id="724ce-415">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-415">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="724ce-416">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-416">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-417">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-417">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-418">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-418">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="724ce-419">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-419">Project</span></span>

- <span data-ttu-id="724ce-420">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-420">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-421">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-421">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-422">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-422">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="724ce-423">発行者</span><span class="sxs-lookup"><span data-stu-id="724ce-423">Publisher</span></span>

- <span data-ttu-id="724ce-424">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-424">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-425">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-425">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-426">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-426">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="724ce-427">Visio</span><span class="sxs-lookup"><span data-stu-id="724ce-427">Visio</span></span>

- <span data-ttu-id="724ce-428">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-428">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-429">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-429">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-430">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-430">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="724ce-431">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-431">Word</span></span>

- <span data-ttu-id="724ce-432">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-432">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="724ce-433">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-433">No conversion required.</span></span><br /><span data-ttu-id="724ce-434">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-434">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="724ce-435">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-435">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="724ce-436">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-436">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="724ce-437">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-437">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-440">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-440">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="724ce-441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-441">PowerPoint</span></span>

- <span data-ttu-id="724ce-442">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-442">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-14"></a><span data-ttu-id="724ce-444">バージョン 2009: 9 月 14 日</span><span class="sxs-lookup"><span data-stu-id="724ce-444">Version 2009: September 14</span></span>
<span data-ttu-id="724ce-445">*バージョン 2009 (ビルド 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="724ce-445">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="724ce-446">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-446">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-10"></a><span data-ttu-id="724ce-449">バージョン 2009: 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="724ce-449">Version 2009: September 10</span></span>
<span data-ttu-id="724ce-450">*バージョン 2009 (ビルド 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="724ce-450">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-452">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-452">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-453">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-453">Access</span></span>

- <span data-ttu-id="724ce-454">この問題は解決されましたので、クラッシュが発生しなくなったはずです。</span><span class="sxs-lookup"><span data-stu-id="724ce-454">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="724ce-455">ODBC データベースへの接続がサードパーティ製アプリケーションで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-455">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="724ce-456">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-456">Excel</span></span>

- <span data-ttu-id="724ce-457">LET 関数が含まれているファイルを開くと、以下の警告が表示される問題が修正されました: "ファイル名.xlsx" のコンテンツに問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-457">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="724ce-458">できるだけ多くの内容の復元を試みますか?</span><span class="sxs-lookup"><span data-stu-id="724ce-458">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="724ce-459">このブックの発行元が信頼できる場合は、[はい] をクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="724ce-459">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="724ce-460">ユーザーがかっこを含む数式名を入力し、F1 を介してヘルプを呼び出した場合、その数式に固有のヘルプ トピックが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-460">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="724ce-461">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="724ce-461">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="724ce-462">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-462">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="724ce-463">XLAM アドイン参照と名前付き範囲に関係するクラッシュが修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-463">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="724ce-464">ユーザーが動的配列にカスタム スタイルを適用すると、"配列の一部を変更することはできません" というエラーが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-464">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="724ce-465">これは以前に存在していた制約でしたが、現在は削除されています。</span><span class="sxs-lookup"><span data-stu-id="724ce-465">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="724ce-466">古いバージョンのファイルを復元した後、ボタンに割り当てられたマクロが壊れる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-466">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="724ce-467">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-467">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="724ce-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-468">Outlook</span></span>

- <span data-ttu-id="724ce-469">問題が修正され、グループ ポリシー経由で既定のログ記録オプションを有効または無効にするための柔軟性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-469">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="724ce-470">アシスタントのアクセス許可があるメールボックスと管理者のアクセス許可があるメールボックスの間でメールの下書きを移動した後も、メール送信者の従来のドメイン名が維持されて表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-470">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="724ce-471">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-471">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="724ce-472">1 行リボン (SLR) を有効にした後に VBA コード ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") を実行すると実行時エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-472">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="724ce-473">高解像度 (1750 x 1920 など) と大きなテキストサイズ (175% など) が同時に使用された場合に、[自動応答] ダイアログの [OK] ボタンと [キャンセル] ボタンが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-473">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="724ce-474">会議出席依頼を空の連絡先グループから別の連絡先グループに送信するとクラッシュする状態が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-474">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="724ce-475">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-475">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="724ce-476">アドインが常に有効になっていることがグループ ポリシーで要求される場合に、ユーザーがアドインを無効にすることを防ぐためにアドインの監視が使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-476">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="724ce-477">1 つ以上のメッセージを選択した場合に、OneNote に "転送不可" ポリシーが適用されているメール コンテンツを送信することができるようになっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-477">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="724ce-478">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-478">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="724ce-479">Active Directory の "otherTelephone" および "otherHomePhone" のユーザー アカウント属性が、対応する Outlook LDAP 属性にマッピングされていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-479">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="724ce-480">この変更により、ユーザーがタブを会議ページからスケジュール アシスタント ページに切り替えた後も会議ページが引き続き表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-480">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="724ce-481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-481">PowerPoint</span></span>

- <span data-ttu-id="724ce-482">特定の条件下でリボンまたはタイトル バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-482">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="724ce-483">PowerPoint を起動後にスライドを挿入してコメント ウィンドウを開いて閉じると、縮小版ウィンドウ内のスライドが重なって表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-483">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="724ce-484">ビデオを挿入する機能が無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-484">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="724ce-485">ビデオがスライドショーで自動的に再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-485">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="724ce-486">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-486">Project</span></span>

- <span data-ttu-id="724ce-487">リソースに複数のコスト単価テーブルが含まれている場合、残りのコストが正確に計算されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-487">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="724ce-488">SharePoint タスク リストに接続されているプロジェクトのプロジェクト終了日が更新されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-488">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="724ce-489">Visio</span><span class="sxs-lookup"><span data-stu-id="724ce-489">Visio</span></span>

- <span data-ttu-id="724ce-490">テキストを配置するとリアルタイムのプレビューがクラッシュする問題がお客様から報告されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-490">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="724ce-491">7 月のフォークで最も多く報告されているクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="724ce-491">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="724ce-492">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-492">Word</span></span>

- <span data-ttu-id="724ce-493">ユーザーがコメントをクリックした場合に、コメント カードでコメントのテキストの周囲に枠線が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-493">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="724ce-494">箇条書きのアイコンが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-494">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="724ce-495">コメントの選択時に、ヘッダー/フッターを閉じることができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-495">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="724ce-496">コメントが削除された後に Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-496">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="724ce-497">ユーザーがコメントの下書きを作成して、解決済みのコメントが既に含まれている行にアンカーすると、サイドトラックでは解決済みのコメントに対して正しくない順番で下書きが並べ替えられる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-497">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="724ce-498">ドキュメントの拡大率が 160% より大きく設定され、コメント ウィンドウが表示されていない場合に、フォーカスがコメント ウィンドウに移動しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-498">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="724ce-499">サイドトラックのスクロールが機能しないため、サイドトラックの境界を超えたコメントのスレッドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-499">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="724ce-500">サイドトラック ウィンドウで解決済みのコメントを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-500">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="724ce-501">開いている複数のドキュメントの間で切り替えを行うと、あるドキュメントのコメントが、開かれている別のドキュメントに表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-501">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="724ce-502">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-502">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="724ce-503">メールで箇条書きが正しく表示されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-503">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="724ce-504">AutoOpen が AutoExec. より前に実行されるというマクロの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-504">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-505">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-505">Office Suite</span></span>

- <span data-ttu-id="724ce-506">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-506">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="724ce-507">[図の圧縮] ダイアログで、ユーザーが選択した一部の DPI 設定が保持されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-507">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="724ce-508">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-508">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-september-04"></a><span data-ttu-id="724ce-510">バージョン 2008: 9 月 04 日</span><span class="sxs-lookup"><span data-stu-id="724ce-510">Version 2008: September 04</span></span>
<span data-ttu-id="724ce-511">*バージョン 2008 (ビルド 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="724ce-511">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-513">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-513">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="724ce-514">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-514">Office Suite</span></span>

- <span data-ttu-id="724ce-515">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-515">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-september-02"></a><span data-ttu-id="724ce-517">バージョン 2008: 9 月 02 日</span><span class="sxs-lookup"><span data-stu-id="724ce-517">Version 2008: September 02</span></span>
<span data-ttu-id="724ce-518">*バージョン 2008 (ビルド 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="724ce-518">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-520">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-520">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-521">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-521">Excel</span></span>

- <span data-ttu-id="724ce-522">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-522">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="724ce-523">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-523">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="724ce-524">**Excelペンを使用してすばやく編集する:** ペン ツールを使用すると、データを手書きしてすばやく編集できます</span><span class="sxs-lookup"><span data-stu-id="724ce-524">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-527">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-527">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-528">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-528">Excel</span></span>

- <span data-ttu-id="724ce-529">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-529">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="724ce-530">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-530">Word</span></span>

- <span data-ttu-id="724ce-531">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-531">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-august-27"></a><span data-ttu-id="724ce-533">バージョン 2008: 8 月 27 日</span><span class="sxs-lookup"><span data-stu-id="724ce-533">Version 2008: August 27</span></span>
<span data-ttu-id="724ce-534">*バージョン 2008 (ビルド 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="724ce-534">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-538">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-538">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-539">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-539">Outlook</span></span>

- <span data-ttu-id="724ce-540">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-540">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="724ce-541">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-541">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="724ce-542">クラウドの添付ファイルを操作しているときに不定期にクラッシュする場合があった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-542">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="724ce-543">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-543">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="724ce-544">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-544">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-545">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-545">Word</span></span>

- <span data-ttu-id="724ce-546">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレントな保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-546">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="724ce-547">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-547">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-25"></a><span data-ttu-id="724ce-549">バージョン 2008: 8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="724ce-549">Version 2008: August 25</span></span>
<span data-ttu-id="724ce-550">*バージョン 2008 (ビルド 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="724ce-550">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-552">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-552">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-553">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-553">Outlook</span></span>

- <span data-ttu-id="724ce-554">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、候補に表示される最も関連性の高いメールが届きます。</span><span class="sxs-lookup"><span data-stu-id="724ce-554">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-557">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-557">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-558">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-558">Outlook</span></span>

- <span data-ttu-id="724ce-559">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-559">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="724ce-560">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="724ce-560">Do you want to download them anyway?</span></span> <span data-ttu-id="724ce-561">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="724ce-561">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="724ce-562">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-562">Project</span></span>

- <span data-ttu-id="724ce-563">リソースに複数のコスト単価表が定義されている場合、残りのコストが常に正しく計算されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-563">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="724ce-564">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-564">Word</span></span>

- <span data-ttu-id="724ce-565">新しいメールに返信または作成するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-565">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-17"></a><span data-ttu-id="724ce-567">バージョン 2008: 8 月 17 日</span><span class="sxs-lookup"><span data-stu-id="724ce-567">Version 2008: August 17</span></span>
<span data-ttu-id="724ce-568">*バージョン 2008 (ビルド 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="724ce-568">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-570">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-570">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-571">Outlook</span></span>

- <span data-ttu-id="724ce-572">特定の状況において、代理人が会議を辞退したときに、上司の予定表から削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-572">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="724ce-573">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-573">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="724ce-574">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-574">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="724ce-575">右クリックのコンテキスト メニューが検索コントロールに表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-575">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-11"></a><span data-ttu-id="724ce-577">バージョン 2008: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="724ce-577">Version 2008: August 11</span></span>
<span data-ttu-id="724ce-578">*バージョン 2008 (ビルド 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="724ce-578">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="724ce-579">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="724ce-579">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-581">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-581">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-582">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-582">Access</span></span>

- <span data-ttu-id="724ce-583">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="724ce-583">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="724ce-584">Office 365 がインストールされている場合、Office エコシステム外に ACE を公開するために、ACE の再頒布可能エンジンをインストールする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-584">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="724ce-585">そのため、Office 365 を使用している場合は、ACE の再頒布可能エンジンが不要になったため、結果的にこの問題が発生することはありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-585">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="724ce-586">この問題は解決されました。これで、Office のクイック実行アプリケーション以外の ODBC ドライバーを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-586">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="724ce-587">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-587">Excel</span></span>

- <span data-ttu-id="724ce-588">グラフ系列の順序を変更した場合、系列に並んだチェックボックスが系列に沿って並び替えられない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-588">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="724ce-589">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="724ce-589">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="724ce-590">ブックの VBA を介して「ForceFullCalculation」が有効になっていると、グラフが期待どおりに更新されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-590">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="724ce-591">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-591">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="724ce-592">OneNote</span><span class="sxs-lookup"><span data-stu-id="724ce-592">OneNote</span></span>

- <span data-ttu-id="724ce-593">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="724ce-593">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-594">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-594">Outlook</span></span>

- <span data-ttu-id="724ce-595">Outlook で同じメール ドメインから複数のプロファイルを作成することに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-595">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="724ce-596">共有された予定表の機能強化を利用できないユーザーが、新しく追加した共有予定表を表示できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-596">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="724ce-597">S/MIME 暗号化メッセージのヘッダーにロック アイコンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-597">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="724ce-598">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-598">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="724ce-599">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-599">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="724ce-600">ユーザーが適切な印刷権限を持っていても、印刷ボタンが無効な状態で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-600">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="724ce-601">暗号化されずに送信されたときに添付ファイルが S/MIME メッセージから削除される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-601">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="724ce-602">送信時にプレーン テキストの S/MIME メッセージが文字化けする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-602">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="724ce-603">暗号化されていない S/MIME メールを送信すると添付ファイルが破損する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-603">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="724ce-604">送信者から名前を付けて保存のアクセス許可が付与されている場合でも、受信者が権利保護されたメッセージを保存できなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-604">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="724ce-605">この修正プログラムでは、ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-605">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="724ce-606">この修正プログラムでは、Outlook のMarkdown コンテンツでは改行が正常に表示されない問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="724ce-606">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="724ce-607">一部の言語で一部の高度な検索のオプションのラベルが切り捨てられる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-607">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-608">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-608">PowerPoint</span></span>

- <span data-ttu-id="724ce-609">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-609">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="724ce-610">Office ストアへのアクセスが許可されていない場合に、PowerPoint の [フォーム] ボタンでフォームを作成できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-610">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="724ce-611">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-611">Project</span></span>

- <span data-ttu-id="724ce-612">[タスク ボード] ビューに一覧表示されているタスクが [リソースの割り当て] ダイアログのタスクと同期していない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-612">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="724ce-613">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存しようとしても、何も起こらない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-613">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="724ce-614">複数の依存関係があるタスクをコピーして貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-614">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="724ce-615">SharePoint のタスク リストで、2番目のタブにあるリボン ボタンが無効になる場合がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-615">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="724ce-616">Skype</span><span class="sxs-lookup"><span data-stu-id="724ce-616">Skype</span></span>

- <span data-ttu-id="724ce-617">ダンス絵文字のスキントーンが中間色に変更されました</span><span class="sxs-lookup"><span data-stu-id="724ce-617">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="724ce-618">Visio</span><span class="sxs-lookup"><span data-stu-id="724ce-618">Visio</span></span>

- <span data-ttu-id="724ce-619">この修正プログラムを適用すると、ユーザーがいずれかのメカニズム (この場合はアドインを使用) によって delete コマンドの実行を停止した場合、メモリがリークすることはなく、コンピューター全体への影響もありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-619">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-620">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-620">Word</span></span>

- <span data-ttu-id="724ce-621">テキストとの画像をコメントボックスに貼り付けると Word が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-621">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="724ce-622">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-622">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="724ce-623">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="724ce-623">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="724ce-624">変更を追跡するコメントが追加された場合に、[変更履歴] ウィンドウが予期せず開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-624">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="724ce-625">フォーカスがコメント テキスト ボックスにあるときに「エディター」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-625">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="724ce-626">フォーカスがコメント テキスト ボックスにあるときに「変更履歴と​​コメントの表示」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-626">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="724ce-627">最後のコメントを削除すると [新しいコメント] ボタンが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-627">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="724ce-628">変更履歴の記録の[特定のユーザー]オプションが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-628">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="724ce-629">[挿入]、[リンク] ドロップダウンを通して、ドキュメントへのリンクがコメントボックスに挿入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-629">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="724ce-630">HTML ファイルを開くときに、時々切断される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-630">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="724ce-631">ドキュメントを開くとコメントの状態が失われる可能性があるカスタム XML の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-631">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="724ce-632">ハイパーリンクを含む画像を追加した後に、VBA のハイパーリンク コレクションにあるハイパーリンク数が正しく指定されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-632">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="724ce-633">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-633">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="724ce-634">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-634">This is now fixed.</span></span>

- <span data-ttu-id="724ce-635">ユーザーがタスクバーから新しいアプリ ウィンドウを開いて新しい空白のドキュメントを作成した後、追加のファイルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-635">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="724ce-636">ユーザーがドキュメントを編集していて権限を失っていた場合、再認証が必要であることをユーザーに通知しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-636">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-05"></a><span data-ttu-id="724ce-638">バージョン 2007: 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="724ce-638">Version 2007: August 05</span></span>
<span data-ttu-id="724ce-639">*バージョン 2007 (ビルド 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="724ce-639">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-643">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-643">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-644">Outlook</span></span>

- <span data-ttu-id="724ce-645">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-645">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="724ce-646">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-646">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="724ce-647">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-647">Project</span></span>

- <span data-ttu-id="724ce-648">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-648">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-29"></a><span data-ttu-id="724ce-650">バージョン 2007: 7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="724ce-650">Version 2007: July 29</span></span>
<span data-ttu-id="724ce-651">*バージョン 2007 (ビルド 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="724ce-651">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-653">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-653">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-654">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-654">Excel</span></span>

- <span data-ttu-id="724ce-655">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-655">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="724ce-656">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="724ce-656">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="724ce-657">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="724ce-657">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="724ce-658">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-658">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="724ce-659">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-659">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-660">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-660">Outlook</span></span>

- <span data-ttu-id="724ce-661">**検索する場所を選択する:** 新しい検索範囲のドロップ ダウン リストを使用すると、検索結果を簡単に変更したり、現在のフォルダーと現在のメールボックスを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-661">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="724ce-662">新しい検索についてフィードバックを提供してくれた皆さんに感謝します。</span><span class="sxs-lookup"><span data-stu-id="724ce-662">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="724ce-663">このデザインと更新プログラムは、お客様のフィードバックを反映しています。</span><span class="sxs-lookup"><span data-stu-id="724ce-663">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="724ce-664">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-664">Word</span></span>

- <span data-ttu-id="724ce-665">**最新のコメントによる共同作業の向上:** オブジェクトにコメントを追加したり、同僚に @mention したり、コメント スレッドを解決して共同作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-665">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="724ce-666">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-666">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-669">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-669">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-670">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-670">Outlook</span></span>

- <span data-ttu-id="724ce-671">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-671">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="724ce-672">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-672">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="724ce-673">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-673">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-27"></a><span data-ttu-id="724ce-675">バージョン 2007: 7 月 27 日</span><span class="sxs-lookup"><span data-stu-id="724ce-675">Version 2007: July 27</span></span>
<span data-ttu-id="724ce-676">*バージョン 2007 (ビルド 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="724ce-676">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="724ce-677">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-677">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="724ce-678">バージョン 2007: 7 月 20 日</span><span class="sxs-lookup"><span data-stu-id="724ce-678">Version 2007: July 20</span></span>
<span data-ttu-id="724ce-679">*バージョン 2007 (ビルド 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="724ce-679">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="724ce-680">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-680">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="724ce-681">バージョン 2007: 7 月 15 日</span><span class="sxs-lookup"><span data-stu-id="724ce-681">Version 2007: July 15</span></span>
<span data-ttu-id="724ce-682">*バージョン 2007 (ビルド 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="724ce-682">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-684">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-684">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-685">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-685">Excel</span></span>

- <span data-ttu-id="724ce-686">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="724ce-686">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="724ce-687">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-687">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-690">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-690">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-691">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-691">Access</span></span>

- <span data-ttu-id="724ce-692">リンクされた SQL テーブルが更新された場合、リンクされたテーブル マネージャーが主キーを要求する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-692">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="724ce-693">クエリ エディターのクエリがスクロールして表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-693">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="724ce-694">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-694">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="724ce-695">Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できず、行が削除されたと誤って報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-695">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="724ce-696">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-696">Excel</span></span>

- <span data-ttu-id="724ce-697">http または https ベースではない URL が最近使用したリストに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-697">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="724ce-698">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-698">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="724ce-699">テーブルに関連付けられたクエリが編集されていない場合でも、特定のバージョンの Excel で作成したデータ モデル テーブルが [テーブル プレビュー] に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-699">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="724ce-700">[名前の定義] \ [名前の適用] ダイアログの [相対/絶対参照を区別しない] 参照が原因で、数式が機能しなくなります。</span><span class="sxs-lookup"><span data-stu-id="724ce-700">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="724ce-701">SharePoint/OneDriveにブックを保存すると、ユーザー設定のリボンタブの CustomUI XML が削除される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-701">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="724ce-702">ファイルが読み取り専用である場合にのみ、ブックが読み取り専用であった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-702">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="724ce-703">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-703">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="724ce-704">レーダー チャートの主要な目盛線が正しく書式設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-704">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="724ce-705">高度なデータ フィルターをクリアするとテーブルの書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-705">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="724ce-706">埋め込まれた PDF 文書のフル パスがファイル名だけでなく文書の標題に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-706">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="724ce-707">Wolfram クラウド コネクターを無効にしてから、Excel ブックを保存してもう一度開くとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-707">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="724ce-708">ソルバー アドインを有効にして Excel を起動するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-708">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="724ce-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-709">Outlook</span></span>

- <span data-ttu-id="724ce-710">「To」行に 130 人を超える受信者がいる場合に Outlook がハングする問題を修正し、テキストのレンダリングのパフォーマンスも改善しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-710">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="724ce-711">解像度の異なる複数のモニターを使用している場合に、Input Method Editor (IME) ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-711">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="724ce-712">2 日を超えるイベントはそれ以降のすべての日に同じ終了時刻を表示するという「To Do バー」の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-712">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="724ce-713">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501 年 1 月 1 日に設定される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-713">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="724ce-714">ユーザーが配布リストの「送信者を指定して送信」または「代理送信」ができなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-714">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="724ce-715">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-715">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="724ce-716">以前に保存した予定を閉じると、次のエラーが表示される問題を修正しました。「別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。</span><span class="sxs-lookup"><span data-stu-id="724ce-716">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="724ce-717">アイテムの既定のフォルダーにコピーしますか?」</span><span class="sxs-lookup"><span data-stu-id="724ce-717">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="724ce-718">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-718">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="724ce-719">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-719">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="724ce-720">Outlook のユーザーが共有の予定表を使用した後、メッセージ一覧の更新が数分間停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-720">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="724ce-721">予定表のリマインダーで、1 週間以内に行われる会議の正確な時刻が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-721">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="724ce-722">メッセージに画像をインラインで挿入し、メッセージを下書きとして保存すると画像のサイズが変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-722">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="724ce-723">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-723">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="724ce-724">日本のユーザーに対してミニ カレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-724">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="724ce-725">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-725">PowerPoint</span></span>

- <span data-ttu-id="724ce-726">ライブの共同編集セッション中に共同編集ギャラリーでユーザーのプレゼンス カラー インジケーターが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-726">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="724ce-727">スライドのテキスト領域に HTML を貼り付けると、代わりにスライドの上部に作成されたテキスト ボックスに貼り付けられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-727">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="724ce-728">発表者ビューですべてのスライドを選択し、Alt + Tabを使用して発表者ビューを終了し、スライド ショーに戻って [ショーの終了] をクリックすると、未処理の例外が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-728">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="724ce-729">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-729">Project</span></span>

- <span data-ttu-id="724ce-730">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-730">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="724ce-731">URL の末尾が「.com」の場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-731">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="724ce-732">特定の XML ファイルを開くと、Project がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-732">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="724ce-733">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-733">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="724ce-734">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-734">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="724ce-735">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-735">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="724ce-736">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-736">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="724ce-737">固定期間タスクが 100% 完了しているが、実際の完了が指定されていない場合、タスク完了率が 100% 未満として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-737">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="724ce-738">ベースラインのリセットまたは更新により、時間単位の予算コスト/作業リソースが変更され、ベースラインが誤った予算値を反映する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-738">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="724ce-739">Government Community Cloud 環境でプロジェクト プランナのリンクが無効になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-739">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="724ce-740">ライブラリがモダン モードの場合、SharePoint ドキュメント ライブラリから Project ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-740">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="724ce-741">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-741">Word</span></span>

- <span data-ttu-id="724ce-742">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式設定をクリアする機能が動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-742">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="724ce-743">スケーラブル ベクター グラフィックス （SVG）に挿入されたテキストを、Word、Excel、または PowerPoint ファイルに挿入し、ファイルを保存して閉じ、再度開いた後、判読できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-743">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="724ce-744">ルーラーが表示されていないときにテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションが点滅し始める問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-744">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="724ce-745">共同編集モードで、コメントの返信がコメント ウィンドウに表示されず、変更履歴ウィンドウに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-745">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="724ce-746">マージの競合があり、ユーザーが既に変更を破棄することを選択している場合の共同編集モード中の問題を修正し、変更を保存または破棄するオプションを表示しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-746">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="724ce-747">HTML ハイパーリンクの色が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-747">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="724ce-748">Wordに 50 を超える頻繁に開かれる文書のリストがある場合、文書を保存して開いた後、その文書に変更が加えられていなくても、変更履歴が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-748">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="724ce-749">共同編集中の自動保存に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-749">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="724ce-750">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても「WRO0004.docx」というファイル名で保存されるため、その文書を使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-750">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-751">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-751">Office Suite</span></span>

- <span data-ttu-id="724ce-752">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります</span><span class="sxs-lookup"><span data-stu-id="724ce-752">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="724ce-753">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="724ce-753">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="724ce-754">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-754">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2006-july-09"></a><span data-ttu-id="724ce-756">バージョン 2006: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="724ce-756">Version 2006: July 09</span></span>
<span data-ttu-id="724ce-757">*バージョン 2006 (ビルド 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="724ce-757">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-759">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-759">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-760">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-760">Excel</span></span>

- <span data-ttu-id="724ce-761">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="724ce-761">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="724ce-762">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-762">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="724ce-763">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="724ce-763">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="724ce-764">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-764">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="724ce-765">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-765">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="724ce-766">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-766">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="724ce-767">**Excel のショートカットキー:** 更新された Excel のショートカットキー</span><span class="sxs-lookup"><span data-stu-id="724ce-767">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-768">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-768">Outlook</span></span>

- <span data-ttu-id="724ce-769">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="724ce-769">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="724ce-770">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-770">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-773">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-773">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-774">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-774">Access</span></span>

- <span data-ttu-id="724ce-775">この問題は解決されており、ID (オートナンバーなど) フィールドを含むリンクされた SQL テーブルを Access に正常に挿入できるようになります。</span><span class="sxs-lookup"><span data-stu-id="724ce-775">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="724ce-776">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-776">Excel</span></span>

- <span data-ttu-id="724ce-777">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-777">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-778">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-778">Outlook</span></span>

- <span data-ttu-id="724ce-779">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-779">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="724ce-780">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-780">Office Suite</span></span>

- <span data-ttu-id="724ce-781">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="724ce-781">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="724ce-782">レジストリ TabProcGrowth の値がREG_SZ型で値 "0" でアドインがアクティブ化されているときに、Windows の Office ホストがクラッシュしていました。</span><span class="sxs-lookup"><span data-stu-id="724ce-782">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="724ce-783">このレジストリ ボックスには、4つのパスのいずれかを使用できます。 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main。この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-783">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-25"></a><span data-ttu-id="724ce-785">バージョン 2006: 6月 25 日</span><span class="sxs-lookup"><span data-stu-id="724ce-785">Version 2006: June 25</span></span>
<span data-ttu-id="724ce-786">*バージョン 2006 (ビルド 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="724ce-786">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-788">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-788">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="724ce-789">Visio</span><span class="sxs-lookup"><span data-stu-id="724ce-789">Visio</span></span>

- <span data-ttu-id="724ce-790">**Excel で洗練された Visio 図を作成する:** ワークシートのデータに基づいて、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="724ce-790">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-793">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-793">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-794">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-794">Access</span></span>

- <span data-ttu-id="724ce-795">この問題は解決されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-795">This problem is now resolved.</span></span> <span data-ttu-id="724ce-796">このプロセスでさらに問題が発生した場合は、チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="724ce-796">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="724ce-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-797">Outlook</span></span>

- <span data-ttu-id="724ce-798"><span style="display:inline !important;">ドラッグ アンド ドロップによってファイル システムにコピーされた添付<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">ファイルの作成日&nbsp; が、&nbsp;4501年1月1日に設定された問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="724ce-798"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="724ce-799"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span></span><span class="sxs-lookup"><span data-stu-id="724ce-799"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="724ce-800"><span style="display:inline !important;">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="724ce-800"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="724ce-801"><span style="display:inline !important;">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="724ce-801"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-18"></a><span data-ttu-id="724ce-803">バージョン 2006: 6 月 18 日</span><span class="sxs-lookup"><span data-stu-id="724ce-803">Version 2006: June 18</span></span>
<span data-ttu-id="724ce-804">*バージョン 2006 (ビルド 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="724ce-804">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-806">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-806">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-807">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-807">Excel</span></span>



- <span data-ttu-id="724ce-808">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="724ce-808">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="724ce-809">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="724ce-809">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="724ce-810">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-810">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="724ce-811">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-811">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-812">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-812">PowerPoint</span></span>

- <span data-ttu-id="724ce-813">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="724ce-813">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="724ce-814">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="724ce-814">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="724ce-815">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-815">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="724ce-816">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-816">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="724ce-817">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-817">Word</span></span>

- <span data-ttu-id="724ce-818">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="724ce-818">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="724ce-819">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="724ce-819">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="724ce-820">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-820">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="724ce-821">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-821">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-824">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-824">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-825">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-825">Excel</span></span>

- <span data-ttu-id="724ce-826">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-826">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-827">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-827">Outlook</span></span>

- <span data-ttu-id="724ce-828">クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-828">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="724ce-829">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-829">Project</span></span>

- <span data-ttu-id="724ce-830">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-830">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-11"></a><span data-ttu-id="724ce-832">バージョン 2006: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="724ce-832">Version 2006: June 11</span></span>
<span data-ttu-id="724ce-833">*バージョン 2006 (ビルド 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="724ce-833">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-835">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-835">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="724ce-836">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-836">PowerPoint</span></span>

- <span data-ttu-id="724ce-837">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-837">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="724ce-838">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="724ce-838">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-839">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-839">Word</span></span>

- <span data-ttu-id="724ce-840">**テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-840">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-843">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-843">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-844">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-844">Excel</span></span>

- <span data-ttu-id="724ce-845">OneDrive を起動すると Excel がシャットダウンすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-845">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="724ce-846">グラフの軸にカスタム値が正しく適用されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-846">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="724ce-847">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-847">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="724ce-848">使用可能なプリンターのリストでプリンター名が重複する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-848">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="724ce-849">ユーザーがマージされた列を削除したときのパフォーマンス時間が向上する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-849">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="724ce-850">アドインは、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」 というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-850">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="724ce-851">Excelとサード パーティの支援技術アプリケーションの一部との間でフォントを管理する際にメモリが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-851">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="724ce-852">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-852">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="724ce-853">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-853">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="724ce-854">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-854">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="724ce-855">選択ロックがない図形を含むワークシート上で、アドインがホスト アイテムを要求すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-855">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="724ce-856">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-856">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-857">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-857">Outlook</span></span>

- <span data-ttu-id="724ce-858">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-858">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="724ce-859">新しいメール メッセージの作成時にテンプレートを表示するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-859">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="724ce-860">Outlook バージョン1911以降、ユーザーが Exchange 2010のパブリック フォルダーを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-860">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="724ce-861">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-861">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="724ce-862">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-862">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="724ce-863">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-863">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="724ce-864">ユーザーが予定表をゲストユーザーと共有できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-864">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="724ce-865">予定表のアイテムが真夜中にまたがっていると、終日イベントとして表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-865">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="724ce-866">高 DPI のモニターを使用しているユーザーに対して、フォルダー プロパティの [オンライン アーカイブ] ドロップダウンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-866">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="724ce-867">ユーザーがフォルダー間でアイテムを移動したときに、「BeforeItemMove」 イベントが正常に起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-867">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="724ce-868">2つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-868">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="724ce-869">テキスト形式のメールでハイパーリンクを使用して作業しているときに、Outlook でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-869">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="724ce-870">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-870">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="724ce-871">スクリーン リーダーを使用すると、Outlook ユーザーの断続的なハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-871">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="724ce-872">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-872">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-873">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-873">PowerPoint</span></span>

- <span data-ttu-id="724ce-874">サーバ構成のファイルをフォームベースの認証で開くときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-874">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="724ce-875">グラフまたはブックが埋め込まれた PowerPoint ファイルの保存時にエラーが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-875">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="724ce-876">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-876">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="724ce-877">マウス ホイールを使用して拡大した後、スライドが中央に配置されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-877">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="724ce-878">英語スイス (QWERTZ) キーボードを使用すると、キーボード ショートカットとスペル チェックが期待どおりに機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-878">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="724ce-879">ユーザーによって終了されたコメント ウィンドウが自動的に再起動するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-879">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="724ce-880">1つのスライドからのスライド エディタが次のスライドに重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-880">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="724ce-881">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-881">Project</span></span>

- <span data-ttu-id="724ce-882">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-882">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="724ce-883">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-883">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="724ce-884">オプションをクリックするとプロジェクトがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-884">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="724ce-885">親計画が削除された後、孤立したタスクの削除や再割り当てができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-885">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="724ce-886">Visio</span><span class="sxs-lookup"><span data-stu-id="724ce-886">Visio</span></span>

- <span data-ttu-id="724ce-887">依存コードに回帰がありましたが、これは修正されています。</span><span class="sxs-lookup"><span data-stu-id="724ce-887">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="724ce-888">これで、SharePoint Onprem で実行されている Visio services の画像が表示されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-888">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-889">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-889">Word</span></span>

- <span data-ttu-id="724ce-890">コメント ウィンドウのタイムスタンプがシステム ロケールの時間に基づいていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-890">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="724ce-891">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-891">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="724ce-892">テキストのコピーと貼り付けがコメント ウィンドウに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-892">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="724ce-893">コメント内のハイパーリンクが機能しなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-893">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="724ce-894">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-894">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="724ce-895">Web アプリとデスクトップ アプリケーションの間のコメントが同期していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-895">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="724ce-896">100% ズームでコメント ヒントの泡がぼやけて見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-896">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="724ce-897">空白のドキュメントに新しいコメントを追加しても何も発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-897">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="724ce-898">予定表用の WordMail に HTML を貼り付けできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-898">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="724ce-899">共同編集セッションのコメントに返信すると、Word がフリーズすることがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-899">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="724ce-900">100 個を超えるエントリを含むドキュメントにインデックスを挿入または更新すると、アプリケーションがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-900">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="724ce-901">ポリシー Word 2007以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集で失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-901">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="724ce-902">カスタム xml 値を含むファイルを開くのが非常に遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-902">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="724ce-903">長いパス名 (32K を超える) のファイルが開かず、適切なエラー メッセージが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-903">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="724ce-904">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-904">Office Suite</span></span>

- <span data-ttu-id="724ce-905">OS のシャットダウン後、InTune を介した Office 365 ProPlus の展開が停止する問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-905">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="724ce-906">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-906">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="724ce-907">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-907">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-08"></a><span data-ttu-id="724ce-909">バージョン 2005: 6月 8 日</span><span class="sxs-lookup"><span data-stu-id="724ce-909">Version 2005: June 08</span></span>
<span data-ttu-id="724ce-910">*バージョン 2005 (ビルド 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="724ce-910">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-912">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-912">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="724ce-913">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-913">PowerPoint</span></span>

- <span data-ttu-id="724ce-914">[フォントの置換] ダイアログボックスで、[フォントの置換] ドロップダウンリストには、システムにインストールされているフォントの代わりにプレゼンテーション内のフォントしか表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-914">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-04"></a><span data-ttu-id="724ce-916">バージョン 2005: 6月 4 日</span><span class="sxs-lookup"><span data-stu-id="724ce-916">Version 2005: June 04</span></span>
<span data-ttu-id="724ce-917">*バージョン 2005 (ビルド 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="724ce-917">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-919">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-919">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="724ce-920">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-920">Access</span></span>

- <span data-ttu-id="724ce-921">**時代に追いつきましょう! 日付/時刻の拡張データ型では、より精度が高くなります。:** 改良されたデータ型をご紹介します。</span><span class="sxs-lookup"><span data-stu-id="724ce-921">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="724ce-922">SQL との構文の互換性を高め、日付と時刻を含むレコードの精度と詳細レベルを向上させるため、Access に DateTime2 データ型を実装しています。</span><span class="sxs-lookup"><span data-stu-id="724ce-922">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="724ce-923">この追加の日付および時間のデータ型には、より大きい日付範囲 (0001-01-01 ～ 9999-12-31) が含まれます。これにより、指定された時間の精度 (秒単位ではなくナノ秒) で提供され、計算を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="724ce-923">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="724ce-924">有効にするには、[新しいフィールド] > [日付と時間の拡張] を選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-924">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="724ce-925">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-925">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="724ce-926">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-926">Excel</span></span>

- <span data-ttu-id="724ce-927">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-927">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="724ce-928">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-928">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="724ce-929">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="724ce-929">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-930">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-930">Outlook</span></span>

- <span data-ttu-id="724ce-931">**以前の Outlook セッションからアイテムを素早く再開するオプション:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-931">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-934">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-934">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="724ce-935">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-935">PowerPoint</span></span>

- <span data-ttu-id="724ce-936">これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-936">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-937">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-937">Office Suite</span></span>

- <span data-ttu-id="724ce-938">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-938">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-29"></a><span data-ttu-id="724ce-940">バージョン 2005: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="724ce-940">Version 2005: May 29</span></span>
<span data-ttu-id="724ce-941">*バージョン 2005 (ビルド 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="724ce-941">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-943">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-943">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="724ce-944">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-944">Excel</span></span>

- <span data-ttu-id="724ce-945">**シート ビュー:** Excel デスクトップで他のユーザーとの共同作業を行っているときに、並べ替えまたはフィルタリングを行います。</span><span class="sxs-lookup"><span data-stu-id="724ce-945">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-946">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-946">Outlook</span></span>

- <span data-ttu-id="724ce-947">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-947">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-950">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-950">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="724ce-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-951">Outlook</span></span>

- <span data-ttu-id="724ce-952">Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効です」という警告が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-952">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="724ce-953">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="724ce-953">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="724ce-954">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-954">Office Suite</span></span>

- <span data-ttu-id="724ce-955">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="724ce-955">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="724ce-956">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-956">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-21"></a><span data-ttu-id="724ce-958">バージョン 2005: 5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="724ce-958">Version 2005: May 21</span></span>
<span data-ttu-id="724ce-959">*バージョン 2005 (ビルド 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="724ce-959">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-963">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-963">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-964">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-964">Excel</span></span>

- <span data-ttu-id="724ce-965">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-965">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="724ce-966">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。</span><span class="sxs-lookup"><span data-stu-id="724ce-966">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="724ce-967">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-967">Outlook</span></span>

- <span data-ttu-id="724ce-968">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-968">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="724ce-969">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-969">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-14"></a><span data-ttu-id="724ce-971">バージョン 2005: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="724ce-971">Version 2005: May 14</span></span>
<span data-ttu-id="724ce-972">*バージョン 2005 (ビルド 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="724ce-972">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-974">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-974">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-975">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-975">Excel</span></span>

- <span data-ttu-id="724ce-976">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-976">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-977">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-977">PowerPoint</span></span>

- <span data-ttu-id="724ce-978">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="724ce-978">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="724ce-979">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-979">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="724ce-980">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="724ce-980">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="724ce-981">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-981">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="724ce-982">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-982">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-983">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-983">Word</span></span>

- <span data-ttu-id="724ce-984">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-984">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-987">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-987">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="724ce-988">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-988">Excel</span></span>

- <span data-ttu-id="724ce-989">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="724ce-989">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="724ce-990">グラフのデータ テーブルの日付軸の値が正しく表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-990">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="724ce-991">[ページ レイアウト] または [改ページ プレビュー] に移動した後に、改ページを無効にできなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-991">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="724ce-992">系列のデータを含む列を非表示にしてから非表示を解除すると、グラフの線のスタイルが失われる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-992">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="724ce-993">フィルタリングされたリストに列を挿入すると、通常よりも時間がかかってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-993">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="724ce-994">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-994">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="724ce-995">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-995">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="724ce-996">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-996">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="724ce-997">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="724ce-997">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="724ce-998">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-998">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="724ce-999">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-999">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="724ce-1000">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1000">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="724ce-1001">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1001">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="724ce-1002">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1002">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="724ce-1003">[Invert if negative]\(負の値を反転する\) オプションが有効になっていると、ピボット グラフのカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1003">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="724ce-1004">[Invert if negative]\(負の値を反転する\) オプションが選択されていると、ピボット グラフの単一のデータ ポイントに対するカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1004">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="724ce-1005">この変更により、CSV ファイルで "@" 文字をアップロードすると、その "@" 文字以降の文字列が数式に変換される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1005">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="724ce-1006">SEQUENCE 関数で小数点以下が正しく四捨五入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1006">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="724ce-1007">OneNote</span><span class="sxs-lookup"><span data-stu-id="724ce-1007">OneNote</span></span>

- <span data-ttu-id="724ce-1008">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1008">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1009">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1009">Outlook</span></span>

- <span data-ttu-id="724ce-1010">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1010">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="724ce-1011">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1011">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="724ce-1012">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1012">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="724ce-1013">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1013">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="724ce-1014">Outlook デスクトップ クライアントで、ユーザーがクリックした非常に長いセーフリンクが、切り捨てにより読み込みに失敗する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1014">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="724ce-1015">DBCS (2 バイト文字セット) 文字を含む名前が付けられた Outlook フォルダーが、サーバーと同期するときに断続的に表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1015">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="724ce-1016">この問題が発生する場合は、Outlook を IMAP アカウントを使用して構成し、ロケールが日本語に設定されたシステム上で実行する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1016">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="724ce-1017">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1017">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="724ce-1018">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1018">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="724ce-1019">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1019">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="724ce-1020">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1020">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="724ce-1021">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="724ce-1021">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-1022">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1022">PowerPoint</span></span>

- <span data-ttu-id="724ce-1023">ユーザーがコメントを作成したのに投稿せずにそのコメント ウィンドウを閉じ、新しいウィンドウを開いて、複数のスライドを移動してからそのウィンドウを閉じ、最後に、元のプレゼンテーションでコメント ウィンドウをもう一度開くと、下書きのコメントが利用できなくなっている問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1023">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="724ce-1024">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1024">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="724ce-1025">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-1025">Project</span></span>

- <span data-ttu-id="724ce-1026">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1026">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="724ce-1027">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1027">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="724ce-1028">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1028">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="724ce-1029">Project が Project Web App に接続されていて、小数点の記号がカンマの場合、タイム ラグを追加する際に TaskDependencies Add メソッドが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1029">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="724ce-1030">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1030">Word</span></span>

- <span data-ttu-id="724ce-1031">コラボレーション モードのドキュメントにコメントを挿入しても正常に動作しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1031">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="724ce-1032">この変更により、@メンションがクリックされると連絡先カードが点滅する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1032">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="724ce-1033">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="724ce-1033">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="724ce-1034">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1034">This has been fixed.</span></span>

- <span data-ttu-id="724ce-1035">下書きのコメントを含むドキュメントを閉じようとすると、その下書きのコメントを保存せずにドキュメントを閉じてもよいかユーザーに確認を求める問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1035">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="724ce-1036">このプロンプトをキャンセルすると、ドキュメントが開いたままになるのではなく、閉じられていました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1036">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="724ce-1037">見出しをコピー & ペーストする際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1037">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="724ce-1038">投稿されたコメントを翻訳しようとすると、"Inserting translated text failed" (翻訳されたテキストの挿入に失敗しました) エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1038">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="724ce-1039">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1039">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="724ce-1040">Web ビュー/イマーシブ リーダーでヒントをクリックすると、ヒントが既に表示されている場合でも一番上までスクロールしていました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1040">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="724ce-1041">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1041">This has been fixed.</span></span>

- <span data-ttu-id="724ce-1042">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても WRO0004.docx というファイル名で保存されるため、そのドキュメントを使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1042">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="724ce-1043">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-1043">Office Suite</span></span>

- <span data-ttu-id="724ce-1044">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1044">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="724ce-1045">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1045">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="724ce-1046">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-1046">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="724ce-1047">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1047">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="724ce-1048">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1048">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-11"></a><span data-ttu-id="724ce-1050">バージョン 2004: 5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1050">Version 2004: May 11</span></span>
<span data-ttu-id="724ce-1051">*バージョン 2004 (ビルド 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1051">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1053">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1053">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1054">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1054">Excel</span></span>

- <span data-ttu-id="724ce-1055">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1055">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1056">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1056">Outlook</span></span>

- <span data-ttu-id="724ce-1057">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1057">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="724ce-1058">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1058">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="724ce-1059">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-1059">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="724ce-1060">[ブログの投稿](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="724ce-1060">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="724ce-1061">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1061">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-1062">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1062">PowerPoint</span></span>

- <span data-ttu-id="724ce-1063">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1063">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="724ce-1064">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-1064">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="724ce-1065">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1065">Word</span></span>

- <span data-ttu-id="724ce-1066">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1066">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1069">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1069">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1070">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1070">Outlook</span></span>

- <span data-ttu-id="724ce-1071">ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1071">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-04"></a><span data-ttu-id="724ce-1073">バージョン 2004: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1073">Version 2004: May 04</span></span>
<span data-ttu-id="724ce-1074">*バージョン 2004 (ビルド 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1074">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1076">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1076">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1077">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1077">Outlook</span></span>

- <span data-ttu-id="724ce-1078">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1078">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="724ce-1079">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-1079">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="724ce-1080">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1080">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="724ce-1081">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-1081">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1084">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1084">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="724ce-1085">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-1085">Office Suite</span></span>

- <span data-ttu-id="724ce-1086">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1086">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-29"></a><span data-ttu-id="724ce-1088">バージョン 2004: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1088">Version 2004: April 29</span></span>
<span data-ttu-id="724ce-1089">*バージョン 2004 (ビルド 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1089">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1091">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1091">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1092">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1092">Outlook</span></span>

- <span data-ttu-id="724ce-1093">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1093">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1096">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1096">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1097">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1097">Outlook</span></span>

- <span data-ttu-id="724ce-1098">Windows の一部のビルドで Outlook がクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1098">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2004-april-25"></a><span data-ttu-id="724ce-1100">バージョン 2004: 4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1100">Version 2004: April 25</span></span>
<span data-ttu-id="724ce-1101">*バージョン 2004 (ビルド 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1101">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1103">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1103">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1104">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1104">Outlook</span></span>

- <span data-ttu-id="724ce-1105">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1105">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="724ce-1106">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-1106">Project</span></span>

- <span data-ttu-id="724ce-1107">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1107">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-1108">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-1108">Office Suite</span></span>

- <span data-ttu-id="724ce-1109">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1109">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-21"></a><span data-ttu-id="724ce-1111">バージョン 2004: 4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1111">Version 2004: April 21</span></span>
<span data-ttu-id="724ce-1112">*バージョン 2004 (ビルド 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1112">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1114">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1114">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1115">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1115">Outlook</span></span>

- <span data-ttu-id="724ce-1116">フォルダー ウィンドウの幅が予期せず変更される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1116">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="724ce-1117">Outlook の終了中にユーザーが応答停止を経験する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1117">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-15"></a><span data-ttu-id="724ce-1119">バージョン 2004: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1119">Version 2004: April 15</span></span>
<span data-ttu-id="724ce-1120">*バージョン 2004 (ビルド 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1120">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1122">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1122">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1123">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1123">Excel</span></span>

- <span data-ttu-id="724ce-1124">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1124">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1125">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1125">Outlook</span></span>

- <span data-ttu-id="724ce-1126">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="724ce-1126">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="724ce-1127">望むなら、オフにすることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1127">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-1128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1128">PowerPoint</span></span>

- <span data-ttu-id="724ce-1129">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1129">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-1130">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1130">Word</span></span>

- <span data-ttu-id="724ce-1131">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成できます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1131">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="724ce-1132">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1132">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1135">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1135">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-1136">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-1136">Access</span></span>

- <span data-ttu-id="724ce-1137">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1137">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="724ce-1138">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1138">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="724ce-1139">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1139">Excel</span></span>

- <span data-ttu-id="724ce-1140">シートのセル範囲を選択しているのに、単一セルの選択になってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1140">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="724ce-1141">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1141">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="724ce-1142">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1142">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="724ce-1143">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1143">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="724ce-1144">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1144">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="724ce-1145">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1145">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="724ce-1146">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1146">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="724ce-1147">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1147">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="724ce-1148">X 軸の範囲によっては、グラフのサイズを小さくすると、Excel が応答を停止する場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1148">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="724ce-1149">R1C1 セルの参照が有効になっている Excel シートが共同編集 / 共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動しても、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1149">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="724ce-1150">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1150">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1151">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1151">Outlook</span></span>

- <span data-ttu-id="724ce-1152">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1152">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="724ce-1153">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1153">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="724ce-1154">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1154">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="724ce-1155">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1155">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="724ce-1156">メール メッセージからカテゴリが消えることがあるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1156">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="724ce-1157">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1157">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="724ce-1158">ユーザーが組織フォームのプロパティを表示しようとするとクラッシュするという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1158">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="724ce-1159">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1159">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="724ce-1160">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1160">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="724ce-1161">返信の対象のメッセージに対してユーザーが所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1161">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="724ce-1162">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1162">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="724ce-1163">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1163">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="724ce-1164">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1164">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="724ce-1165">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1165">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="724ce-1166">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1166">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="724ce-1167">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1167">PowerPoint</span></span>

- <span data-ttu-id="724ce-1168">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1168">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="724ce-1169">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1169">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="724ce-1170">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1170">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="724ce-1171">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1171">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="724ce-1172">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-1172">Project</span></span>

- <span data-ttu-id="724ce-1173">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1173">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="724ce-1174">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1174">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="724ce-1175">ユーザーがスケジュール グループ内の [タスク] リボンにある [無効化] ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Application (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1175">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="724ce-1176">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1176">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="724ce-1177">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="724ce-1177">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="724ce-1178">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1178">This behavior has been fixed.</span></span>

- <span data-ttu-id="724ce-1179">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1179">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="724ce-1180">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1180">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="724ce-1181">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1181">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="724ce-1182">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1182">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="724ce-1183">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1183">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="724ce-1184">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1184">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="724ce-1185">[フォーム] ビュー内で先行処理 / 後続処理データを編集すると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1185">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="724ce-1186">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1186">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-1187">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1187">Word</span></span>

- <span data-ttu-id="724ce-1188">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1188">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="724ce-1189">この変更により、[表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1189">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="724ce-1190">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1190">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="724ce-1191">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1191">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="724ce-1192">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1192">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="724ce-1193">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1193">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="724ce-1194">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1194">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="724ce-1195">この変更により、2 ページ表示で、コメントを作成するとき、コメント アンカーが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1195">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="724ce-1196">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1196">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="724ce-1197">スタイルがリストにリンクされているスタイルの祖先である段落の場合、そのリストの番号が失われる場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1197">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="724ce-1198">この変更により、文書に存在しない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1198">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="724ce-1199">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1199">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="724ce-1200">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1200">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="724ce-1201">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1201">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="724ce-1202">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1202">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-14"></a><span data-ttu-id="724ce-1204">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1204">Version 2003: April 14</span></span>
<span data-ttu-id="724ce-1205">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1205">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="724ce-1206">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="724ce-1206">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

- <span data-ttu-id="724ce-1208">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-1208">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-09"></a><span data-ttu-id="724ce-1210">バージョン 2003: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1210">Version 2003: April 09</span></span>
<span data-ttu-id="724ce-1211">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1211">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1213">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1213">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1214">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1214">Excel</span></span>

- <span data-ttu-id="724ce-1215">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="724ce-1215">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="724ce-1216">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="724ce-1216">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1217">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1217">Outlook</span></span>

- <span data-ttu-id="724ce-1218">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="724ce-1218">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="724ce-1219">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="724ce-1219">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-1220">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1220">PowerPoint</span></span>

- <span data-ttu-id="724ce-1221">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="724ce-1221">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="724ce-1222">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="724ce-1222">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="724ce-1223">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1223">Word</span></span>

- <span data-ttu-id="724ce-1224">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="724ce-1224">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="724ce-1225">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="724ce-1225">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-03"></a><span data-ttu-id="724ce-1229">バージョン 2003: 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1229">Version 2003: April 03</span></span>
<span data-ttu-id="724ce-1230">*バージョン 2003 (ビルド 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1230">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1232">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1232">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1233">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1233">Excel</span></span>

- <span data-ttu-id="724ce-1234">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1234">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1235">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1235">Outlook</span></span>

- <span data-ttu-id="724ce-1236">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1236">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="724ce-1237">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-1237">Project</span></span>

- <span data-ttu-id="724ce-1238">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChangeevent が発生します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1238">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-1239">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1239">Word</span></span>

- <span data-ttu-id="724ce-1240">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1240">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="724ce-1242">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1242">Version 2003: March 31</span></span>
<span data-ttu-id="724ce-1243">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1243">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1245">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1245">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="724ce-1246">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-1246">Access</span></span>

- <span data-ttu-id="724ce-1247">**[テーブルの追加] 作業ウィンドウ:** Access の新しい [テーブルの追加] 作業ウィンドウを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1247">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="724ce-1248">この機能を使用すると、クエリやリレーションシップ ビューのために [テーブルの表示] ダイアログボックスに移動することなく、クエリ ウィンドウに追加またはそこから削除する 1 つ以上のテーブルを簡単に選択することができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1248">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="724ce-1249">この機能には、リンク テーブルを表示するための新しい [リンク] タブ、現在のリストをフィルター処理するための検索ボックス、"ドラッグ アンド ドロップ" による操作なども含まれます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1249">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1252">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1252">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="724ce-1253">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="724ce-1253">Project</span></span>

- <span data-ttu-id="724ce-1254"><span style="display:inline !important;">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="724ce-1254"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="724ce-1256">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1256">Version 2003: March 25</span></span>
<span data-ttu-id="724ce-1257">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1257">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="724ce-1258">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-1258">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="724ce-1259">バージョン 2003: 3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1259">Version 2003: March 23</span></span>
<span data-ttu-id="724ce-1260">*バージョン 2003 (ビルド 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1260">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="724ce-1261">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-1261">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="724ce-1262">バージョン 2003: 3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1262">Version 2003: March 21</span></span>
<span data-ttu-id="724ce-1263">*バージョン 2003 (ビルド 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1263">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1265">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1265">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1266">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1266">Outlook</span></span>

- <span data-ttu-id="724ce-1267">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="724ce-1267">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="724ce-1268">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1268">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="724ce-1269">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="724ce-1269">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="724ce-1270">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1270">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-1271">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1271">PowerPoint</span></span>

- <span data-ttu-id="724ce-1272">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1272">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-16"></a><span data-ttu-id="724ce-1274">Version 2003: March 16</span><span class="sxs-lookup"><span data-stu-id="724ce-1274">Version 2003: March 16</span></span>
<span data-ttu-id="724ce-1275">*バージョン 2003 (ビルド 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1275">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1277">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1277">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1278">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1278">Excel</span></span>

- <span data-ttu-id="724ce-1279">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1279">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1280">Outlook</span></span>

- <span data-ttu-id="724ce-1281">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1281">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-1282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1282">PowerPoint</span></span>

- <span data-ttu-id="724ce-1283">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1283">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-1284">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1284">Word</span></span>

- <span data-ttu-id="724ce-1285">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1285">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="724ce-1286">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-1286">Office Suite</span></span>

- <span data-ttu-id="724ce-1287">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1287">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="724ce-1288">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1288">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1291">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1291">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1292">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1292">Excel</span></span>

- <span data-ttu-id="724ce-1293">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1293">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1294">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1294">Outlook</span></span>

- <span data-ttu-id="724ce-1295">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1295">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-10"></a><span data-ttu-id="724ce-1297">バージョン 2003: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1297">Version 2003: March 10</span></span>
<span data-ttu-id="724ce-1298">*バージョン 2003 (ビルド 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1298">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="724ce-1299">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="724ce-1299">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)
### <a name="feature-updates"></a><span data-ttu-id="724ce-1301">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1301">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1302">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1302">Excel</span></span>
- <span data-ttu-id="724ce-1303">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1303">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="724ce-1304">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-1304">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a><span data-ttu-id="724ce-1305">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1305">PowerPoint</span></span>
- <span data-ttu-id="724ce-1306">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1306">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="724ce-1307">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-1307">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a><span data-ttu-id="724ce-1308">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1308">Word</span></span>
- <span data-ttu-id="724ce-1309">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1309">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="724ce-1310">詳細情報</span><span class="sxs-lookup"><span data-stu-id="724ce-1310">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1311">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1311">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1312">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1312">Excel</span></span>

- <span data-ttu-id="724ce-1313">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1313">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="724ce-1314">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1314">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="724ce-1315">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1315">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="724ce-1316">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1316">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="724ce-1317">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1317">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="724ce-1318">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1318">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="724ce-1319">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1319">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="724ce-1320">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1320">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="724ce-1321">この変更では、アドインによって noSelect ロックがある図形を含むドキュメントまたはワークシートのホスト アイテムが求められるときに、オブジェクト モデルでランタイム エラーが発生する問題および App (Excel、Word) がクラッシュする可能性がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1321">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="724ce-1322">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1322">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="724ce-1323">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1323">Outlook</span></span>

- <span data-ttu-id="724ce-1324">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1324">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="724ce-1325">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1325">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="724ce-1326">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1326">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="724ce-1327">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1327">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="724ce-1328">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1328">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="724ce-1329">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1329">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="724ce-1330">ユーザーが「&quot;空き時間情報オプション&quot;」予定表のアクセス許可ダイアログにアクセスできなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1330">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="724ce-1331">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「&quot;申し訳ございません、このアイテムを開くことができません&quot;」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1331">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="724ce-1332">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1332">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="724ce-1333">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1333">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="724ce-1334">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1334">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="724ce-1335">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1335">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="724ce-1336">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1336">PowerPoint</span></span>

- <span data-ttu-id="724ce-1337">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1337">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="724ce-1338">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1338">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="724ce-1339">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1339">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="724ce-1340">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1340">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="724ce-1341">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-1341">Project</span></span>

- <span data-ttu-id="724ce-1342">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1342">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="724ce-1343">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1343">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="724ce-1344">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1344">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="724ce-1345">Visio</span><span class="sxs-lookup"><span data-stu-id="724ce-1345">Visio</span></span>

- <span data-ttu-id="724ce-1346">Visio デスクトップで開いたファイルに関して、[図形情報] ウィンドウの [図形データ] セクションに矛盾した詳細が表示されていました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1346">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="724ce-1347">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1347">It has now been fixed.</span></span>

- <span data-ttu-id="724ce-1348">何らかのセキュリティ チェックが原因で、2016 より前のバージョンでインポートされたビットマップは表示されていませんでした。</span><span class="sxs-lookup"><span data-stu-id="724ce-1348">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="724ce-1349">この問題は Visio サブスクリプションで修正されました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1349">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-1350">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1350">Word</span></span>

- <span data-ttu-id="724ce-1351">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1351">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="724ce-1352">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1352">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="724ce-1353">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1353">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="724ce-1354">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1354">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="724ce-1355">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="724ce-1355">This issue has been fixed.</span></span>

- <span data-ttu-id="724ce-1356">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1356">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="724ce-1357">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1357">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="724ce-1358">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1358">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="724ce-1359">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-1359">Office Suite</span></span>

- <span data-ttu-id="724ce-1360">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1360">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="724ce-1361">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="724ce-1361">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="724ce-1362">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1362">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="724ce-1363">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1363">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="724ce-1364">同じ SharePoint ライブラリから Word、Excel、PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1364">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-05"></a><span data-ttu-id="724ce-1366">バージョン 2002: 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1366">Version 2002: March 05</span></span>
<span data-ttu-id="724ce-1367">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1367">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="724ce-1368">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-1368">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="724ce-1369">バージョン 2002: 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1369">Version 2002: March 04</span></span>
<span data-ttu-id="724ce-1370">*バージョン 2002 (ビルド 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1370">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1372">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1372">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="724ce-1373">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-1373">Project</span></span>
- <span data-ttu-id="724ce-1374">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1374">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-1375">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-1375">Office Suite</span></span>
- <span data-ttu-id="724ce-1376">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1376">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-01"></a><span data-ttu-id="724ce-1378">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1378">Version 2002: March 01</span></span>
<span data-ttu-id="724ce-1379">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1379">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1380">解決した問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1380">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1381">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1381">Outlook</span></span>

- <span data-ttu-id="724ce-1382">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1382">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-24"></a><span data-ttu-id="724ce-1384">バージョン 2002: 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1384">Version 2002: February 24</span></span>
<span data-ttu-id="724ce-1385">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1385">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="724ce-1386">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-1386">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="724ce-1387">バージョン 2002: 2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1387">Version 2002: February 22</span></span>
<span data-ttu-id="724ce-1388">*バージョン 2002 (ビルド 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1388">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="724ce-1389">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="724ce-1389">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="724ce-1390">バージョン 2002: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1390">Version 2002: February 21</span></span>
<span data-ttu-id="724ce-1391">*バージョン 2002 (ビルド 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1391">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1393">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1393">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="724ce-1394">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-1394">Access</span></span>

- <span data-ttu-id="724ce-1395">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="724ce-1395">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="724ce-1396">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1396">Search and replace text in SQL View.</span></span> <span data-ttu-id="724ce-1397">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1397">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1398">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1398">Outlook</span></span>

- <span data-ttu-id="724ce-1399">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="724ce-1399">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="724ce-1400">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1400">Outlook now detects this and helps you get connected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1403">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1403">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="724ce-1404">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1404">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="724ce-1405">CUBEVALUE 関数が間違った結果を返すことがある問題を修正しました。&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="724ce-1405">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="724ce-1406">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1406">Outlook</span></span>

- <span data-ttu-id="724ce-1407">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1407">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="724ce-1408">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1408">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="724ce-1409">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="724ce-1409">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="724ce-1410">黒のテーマを持つユーザーが [&quot;差出人&quot;] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1410">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="724ce-1411"><span style="display:inline !important;">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span></span><span class="sxs-lookup"><span data-stu-id="724ce-1411"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-18"></a><span data-ttu-id="724ce-1413">バージョン 2002: 2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1413">Version 2002: February 18</span></span>
<span data-ttu-id="724ce-1414">*バージョン 2002 (ビルド 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1414">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="724ce-1415">バージョン 2002: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="724ce-1415">Version 2002: February 11</span></span>
<span data-ttu-id="724ce-1416">*バージョン 2002 (ビルド 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="724ce-1416">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="724ce-1417">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="724ce-1417">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="724ce-1419">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="724ce-1419">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="724ce-1420">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1420">Outlook</span></span>

- <span data-ttu-id="724ce-1421">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="724ce-1421">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="724ce-1422">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1422">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="724ce-1423">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1423">Word</span></span>

- <span data-ttu-id="724ce-1424">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1424">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="724ce-1425">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-1425">Office Suite</span></span>

- <span data-ttu-id="724ce-1426">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1426">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="724ce-1429">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="724ce-1429">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="724ce-1430">Access</span><span class="sxs-lookup"><span data-stu-id="724ce-1430">Access</span></span>

- <span data-ttu-id="724ce-1431">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1431">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="724ce-1432">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1432">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="724ce-1433">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1433">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="724ce-1434">VB コードのレコーダー オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1434">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="724ce-1435">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1435">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="724ce-1436">Excel</span><span class="sxs-lookup"><span data-stu-id="724ce-1436">Excel</span></span>

- <span data-ttu-id="724ce-1437">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1437">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="724ce-1438">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1438">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="724ce-1439">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1439">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="724ce-1440">Outlook</span><span class="sxs-lookup"><span data-stu-id="724ce-1440">Outlook</span></span>

- <span data-ttu-id="724ce-1441">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1441">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="724ce-1442">左側のナビゲーション ウィンドウで [お気に入り] に保存したフォルダーが断続的に表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1442">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="724ce-1443">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1443">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="724ce-1444">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1444">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="724ce-1445">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1445">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="724ce-1446">アイテム保持ポリシーに基づいて期限切れになるメールに 2 つのラベルが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1446">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="724ce-1447">メールが 1 日で期限切れになることを示すものと、2 日で期限切れになることを示すものです。</span><span class="sxs-lookup"><span data-stu-id="724ce-1447">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="724ce-1448">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1448">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="724ce-1449">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="724ce-1449">PowerPoint</span></span>

- <span data-ttu-id="724ce-1450">インクが PowerPoint のインク アニメーションで使用すると完全にレンダリングされない、またはスキップされることがある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1450">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="724ce-1451">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1451">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="724ce-1452">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1452">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="724ce-1453">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="724ce-1453">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="724ce-1454">Project</span><span class="sxs-lookup"><span data-stu-id="724ce-1454">Project</span></span>

- <span data-ttu-id="724ce-1455">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1455">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="724ce-1456">Word</span><span class="sxs-lookup"><span data-stu-id="724ce-1456">Word</span></span>

- <span data-ttu-id="724ce-1457">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1457">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="724ce-1458">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1458">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="724ce-1459">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1459">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="724ce-1460">コメントを編集し、テキストをイタリック体にし、それを投稿すると、その後にイタリック体の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1460">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="724ce-1461">反転したページ色を使用する読み取りモードでコメントのヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1461">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="724ce-1462">ドキュメントが共同編集されている場合、ルート コメントの下書き版が保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1462">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="724ce-1463">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="724ce-1463">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="724ce-1464">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1464">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="724ce-1465">コメント コンテキスト メニューのコメント コマンド (コメントの編集、コメントへの返信、コメントの削除、コメントの解決) が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="724ce-1465">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="724ce-1466">Office スイート</span><span class="sxs-lookup"><span data-stu-id="724ce-1466">Office Suite</span></span>

- <span data-ttu-id="724ce-1467">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1467">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="724ce-1468">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="724ce-1468">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

