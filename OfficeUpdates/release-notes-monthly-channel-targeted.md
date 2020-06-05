---
title: リリース ノートの月次チャネル (対象指定)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Slow の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: 41dba1efa79735aafd74b318fd49c7c3211736e3
ms.sourcegitcommit: e9b127c7dfd80f3beb3c9aa9dadfb9e7f442c58c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/04/2020
ms.locfileid: "44563677"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="af0ae-103">Office 月次チャネルのリリース ノート (対象指定)</span><span class="sxs-lookup"><span data-stu-id="af0ae-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="af0ae-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の月次チャネル (対象指定) ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="af0ae-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="af0ae-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="af0ae-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="af0ae-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって月次チャネル (対象指定) に展開されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="af0ae-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="af0ae-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="af0ae-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="af0ae-109">Microsoft 365 アプリの更新チャネルの更新プログラムチャネルに、新しい更新チャネル (月間エンタープライズ チャネル) の追加や、既存の更新プログラムチャネルの名前の変更など、いくつかの変更を行っています。</span><span class="sxs-lookup"><span data-stu-id="af0ae-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="af0ae-110">詳細については、[こちらの記事を参照](https://go.microsoft.com/fwlink/p/?linkid=2127441)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="af0ae-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="af0ae-111">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-111">The release notes publication date may not match the actual build release date.</span></span>


[//]: # (削除しないでください)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-04"></a><span data-ttu-id="af0ae-115">バージョン 2005: 2004 年6月</span><span class="sxs-lookup"><span data-stu-id="af0ae-115">Version 2005: June 04</span></span>
<span data-ttu-id="af0ae-116">*バージョン 2005 (ビルド 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-116">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-118">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-118">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="af0ae-119">Access</span><span class="sxs-lookup"><span data-stu-id="af0ae-119">Access</span></span>

- <span data-ttu-id="af0ae-120">**いつでも使用できるようになります。日付/時刻の拡張データ型には、より高い精度があります。:** 新しいデータ型と改良されたデータ型を導入しています。</span><span class="sxs-lookup"><span data-stu-id="af0ae-120">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="af0ae-121">SQL との構文の互換性を向上させ、日付と時刻を含むレコードの精度と詳細レベルを向上させるために、DateTime2 データ型を Access に実装しています。</span><span class="sxs-lookup"><span data-stu-id="af0ae-121">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="af0ae-122">この追加の日付 & time データ型には、より長い日付範囲 (0001-01-01 ~ 9999-12-31) が含まれており、指定された時間精度 (秒ではなくナノ秒) を使用して計算を提供したり実行したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-122">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="af0ae-123">有効にするには、[新しいフィールド > 日付 & 時間を延長します] を選択します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-123">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="af0ae-124">詳細情報</span><span class="sxs-lookup"><span data-stu-id="af0ae-124">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="af0ae-125">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-125">Excel</span></span>

- <span data-ttu-id="af0ae-126">**Excel 内の POWER BI のデータセットからピボットテーブルを作成します。** Excel では、いくつかのクリックで Power BI に格納されたデータセットに接続されたピボットテーブルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-126">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="af0ae-127">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-127"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="af0ae-128">セキュリティで保護された Power BI データセットからのピボットテーブルを使用して、データの計算、要約、および分析を行います。</span><span class="sxs-lookup"><span data-stu-id="af0ae-128">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-129">Outlook</span></span>

- <span data-ttu-id="af0ae-130">**以前の Outlook セッションからアイテムをすばやく再び開くオプション:** 以前の Outlook セッションからアイテムをすばやく開くオプションを追加しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-130">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-133">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-133">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="af0ae-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-134">PowerPoint</span></span>

- <span data-ttu-id="af0ae-135">これにより、ユーザーがモダンおよび従来のコメントをファイルに保持しているときに、コメントのアップグレードをトリガーするクラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-135">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af0ae-136">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-136">Office Suite</span></span>

- <span data-ttu-id="af0ae-137">既定で Bing アドオンインストールの検証を true に設定し、MSI リターンがインストールが成功したことを考慮して、ValidateInstall fail rate 問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-137">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-29"></a><span data-ttu-id="af0ae-139">バージョン 2005: 5 月29日</span><span class="sxs-lookup"><span data-stu-id="af0ae-139">Version 2005: May 29</span></span>
<span data-ttu-id="af0ae-140">*バージョン 2005 (ビルド 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-140">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-142">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-142">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="af0ae-143">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-143">Excel</span></span>

- <span data-ttu-id="af0ae-144">**シートビュー:** Excel デスクトップで他のユーザーとの共同作業を行うときに、並べ替え/フィルター処理を行います。</span><span class="sxs-lookup"><span data-stu-id="af0ae-144">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-145">Outlook</span></span>

- <span data-ttu-id="af0ae-146">**Outlook トースト通知に追加された追加のボタン:** Windows 10 で Outlook を実行しているときに、クイックアクションボタンが Outlook トースト通知に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-146">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-149">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-149">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="af0ae-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-150">Outlook</span></span>

- <span data-ttu-id="af0ae-151">Windows 10 server バージョンのユーザーがウイルス対策の状態を確認することを引き起こした問題に対処しました。無効です。</span><span class="sxs-lookup"><span data-stu-id="af0ae-151">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="af0ae-152">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正しくインストールされているにもかかわらず、ウイルス対策は検出されませんでした。</span><span class="sxs-lookup"><span data-stu-id="af0ae-152">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af0ae-153">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-153">Office Suite</span></span>

- <span data-ttu-id="af0ae-154">レジストリキー HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth が0に設定されている間にアドインがアクティブ化されると、office ホストが windows でクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-154">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="af0ae-155">この変更により、この問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-155">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-21"></a><span data-ttu-id="af0ae-157">バージョン 2005: 5 月21日</span><span class="sxs-lookup"><span data-stu-id="af0ae-157">Version 2005: May 21</span></span>
<span data-ttu-id="af0ae-158">*バージョン 2005 (ビルド 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-158">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-160">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-160">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-161">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-161">Excel</span></span>

- <span data-ttu-id="af0ae-162">**Excel のデータ型を使用して、POWER BI から組織のデータを取得します。** Excel のデータ型を使用して、組織からデータを挿入できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-162">**Get Organization Data from Power BI using Excel Data Types:** You can insert data from your Organization using Excel Data Types.</span></span> <span data-ttu-id="af0ae-163">ブック内のセルを変換し、追加情報を取得して、必要に応じていつでもデータを更新します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-163">Convert a cell in your workbook and get additional information, and refresh the data anytime you need!</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-166">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-166">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-167">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-167">Excel</span></span>

- <span data-ttu-id="af0ae-168">Ctrl + Shift + 方向キーを使用して、Excel ウィンドウが Teams によって共有されている場合に、Excel が応答しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-168">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="af0ae-169">場合によっては、同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-169">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="af0ae-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-170">Outlook</span></span>

- <span data-ttu-id="af0ae-171">返信/転送ラベルの clp 監査イベントに関する問題に対処した。</span><span class="sxs-lookup"><span data-stu-id="af0ae-171">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="af0ae-172">ユーザーが管理者の通知からフィードバックを送信する際にクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-172">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-14"></a><span data-ttu-id="af0ae-174">バージョン 2005: 5 月14日</span><span class="sxs-lookup"><span data-stu-id="af0ae-174">Version 2005: May 14</span></span>
<span data-ttu-id="af0ae-175">*バージョン 2005 (ビルド 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-175">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-177">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-177">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-178">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-178">Excel</span></span>

- <span data-ttu-id="af0ae-179">**自動適用または推奨される機密ラベル:** Office では、検出された機密コンテンツに基づいて機密ラベルを推奨または自動適用できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-179">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af0ae-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-180">PowerPoint</span></span>

- <span data-ttu-id="af0ae-181">**クリッカーを使用する必要はありません。 earbuds について説明します。** Surface Earbuds を使用して PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-181">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="af0ae-182">重要: プレゼンテーションを制御するためにジェスチャを使用するには、Surface Audio app in Windows 10 で Surface Earbuds をペアにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-182">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="af0ae-183">Windows 10 で Surface Audio アプリの使用を開始する手順はこちらから入手できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-183">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="af0ae-184">詳細情報</span><span class="sxs-lookup"><span data-stu-id="af0ae-184">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="af0ae-185">**自動適用または推奨される機密ラベル:** Office では、検出された機密コンテンツに基づいて機密ラベルを推奨または自動適用できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-185">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="af0ae-186">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-186">Word</span></span>

- <span data-ttu-id="af0ae-187">**自動適用または推奨される機密ラベル:** Office では、検出された機密コンテンツに基づいて機密ラベルを推奨または自動適用できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-187">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-190">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-190">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="af0ae-191">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-191">Excel</span></span>

- <span data-ttu-id="af0ae-192">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-192">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="af0ae-193">グラフデータテーブルで、日付軸の値が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-193">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="af0ae-194">ページレイアウトまたは改ページプレビューに入った後に改ページを無効にできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-194">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="af0ae-195">系列データを使用して列の表示/非表示を切り替えると、グラフの線のスタイルが失われるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-195">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="af0ae-196">フィルター処理されたリストに列を挿入するときに予想より長くかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-196">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="af0ae-197">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-197">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="af0ae-198">ファイルパスが長すぎる場合にファイルを再度開いた後、外部リンクが機能しなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-198">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="af0ae-199">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-199">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="af0ae-200">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-200">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="af0ae-201">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-201">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="af0ae-202">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-202">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="af0ae-203">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-203">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="af0ae-204">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-204">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="af0ae-205">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を表示しようとすると、クラッシュが発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-205">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="af0ae-206">"負の値を反転する" オプションが有効になっていると、ピボットグラフでユーザー設定の書式設定が保存されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-206">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="af0ae-207">[負にする] オプションが選択されている場合に、ピボットグラフの1つのデータ要素に対してユーザー設定の書式設定が保存されなかったという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-207">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="af0ae-208">この変更により、CSV ファイルに ' @ ' 文字がアップロードされると、"@" 文字の後の文字列が数式に変換されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-208">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="af0ae-209">SEQUENCE 関数の10進数値が正しく丸められない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-209">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="af0ae-210">OneNote</span><span class="sxs-lookup"><span data-stu-id="af0ae-210">OneNote</span></span>

- <span data-ttu-id="af0ae-211">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-211">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-212">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-212">Outlook</span></span>

- <span data-ttu-id="af0ae-213">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-213">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="af0ae-214">Office リボンのグループ予定表の [分類] ボタンが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-214">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="af0ae-215">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-215">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="af0ae-216">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-216">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="af0ae-217">ユーザーが Outlook デスクトップクライアントでクリックし、切り捨てによって読み込みに失敗したことを示す、非常に長い safelinks を発生させた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-217">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="af0ae-218">サーバーとの同期時に、DBCS (2 バイト文字セット) 文字を含む名前を持つ Outlook フォルダーが断続的に非表示になる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-218">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="af0ae-219">これを行うには、Outlook で IMAP アカウントを構成し、ロケールが日本語に設定されているシステムで実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-219">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="af0ae-220">ユーザーのプライマリメールボックス以外のメールボックスに対して作成された削除ルールが無効になる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-220">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="af0ae-221">暗号化されたメッセージを転送するときに添付ファイルが削除される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-221">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="af0ae-222">スケジュールアシスタントで会議の件名が表示されないようにするために、2か月を超える会議が発生した問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-222">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="af0ae-223">大きな HTML メッセージを転送するときに、ユーザーがメッセージ本文の切り捨てを表示する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-223">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="af0ae-224">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="af0ae-224">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af0ae-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-225">PowerPoint</span></span>

- <span data-ttu-id="af0ae-226">ユーザーが投稿せずにコメントを作成し、[コメント] ウィンドウを閉じてから、新しいウィンドウを開いて、複数のスライドに移動した後、ウィンドウを閉じ、最後に元のプレゼンテーションの [コメント] ウィンドウを再度開いた場合、下書きコメントを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-226">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="af0ae-227">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-227">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="af0ae-228">Project</span><span class="sxs-lookup"><span data-stu-id="af0ae-228">Project</span></span>

- <span data-ttu-id="af0ae-229">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-229">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="af0ae-230">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-230">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="af0ae-231">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-231">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="af0ae-232">Project が Project Web App に接続されていて、小数点がコンマであるという問題を修正しました。ラグが追加されると、TaskDependencies Add メソッドが失敗します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-232">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="af0ae-233">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-233">Word</span></span>

- <span data-ttu-id="af0ae-234">グループ作業モードでドキュメントにコメントを挿入すると必ずしも機能しないという問題を修正した。</span><span class="sxs-lookup"><span data-stu-id="af0ae-234">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="af0ae-235">この変更により、@ メンションがクリックされた場合に、People card がフラッシュされるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-235">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="af0ae-236">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="af0ae-236">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="af0ae-237">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-237">This has been fixed.</span></span>

- <span data-ttu-id="af0ae-238">下書きコメントを含むドキュメントを閉じるときに、下書きコメントを保存せずにドキュメントを閉じる必要がある場合にメッセージを表示するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-238">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="af0ae-239">プロンプトを取り消した場合は、ドキュメントを開いたままにして閉じます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-239">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="af0ae-240">見出しのコピーと貼り付けに関する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-240">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="af0ae-241">投稿されたコメントを変換すると、エラー ' 翻訳されたテキストの挿入に失敗しました ' が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-241">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="af0ae-242">この変更により、"値の代わりにフィールドコードを表示する" が有効になっている場合にハイパーリンクを含むテキストが表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-242">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="af0ae-243">Web 表示/イマーシブリーダーでは、ヒントをクリックすると、表示されていた場合でも、上にスクロールします。</span><span class="sxs-lookup"><span data-stu-id="af0ae-243">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="af0ae-244">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-244">This has been fixed.</span></span>

- <span data-ttu-id="af0ae-245">マクロを含むファイルを新しい名前で保存しようとしたときに、ユーザーが入力した内容に関係なく .docx 拡張子とファイル名 WRO0004 を付けて保存すると、ドキュメントが使用できなくなるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-245">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af0ae-246">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-246">Office Suite</span></span>

- <span data-ttu-id="af0ae-247">ユーザーに対して、それらを Teams のみに移動するポリシーが付与されている場合でも、Skype for Business Outlook アドインを使用して会議をスケジュールすることができます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-247">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="af0ae-248">この更新プログラムを実行すると、ユーザーが Teams のみであることを示すポリシーをクライアントが読み取った後、Skype for Business 会議をスケジュールすることができなくなります。また、[ミーティングの参加のみ] モードに入ります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-248">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="af0ae-249">さらに、skype for business Outlook アドインは、Skype for business クライアントが会議参加のみのモードであることが確認された場合に起動してもアクティブ化されません。</span><span class="sxs-lookup"><span data-stu-id="af0ae-249">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="af0ae-250">この更新プログラムを実行すると、PATH 環境変数で指定されている場所を検索することによって検出された参照を含む Visual Basic for Applications プロジェクトが、実行時に適切に検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-250">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="af0ae-251">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-251">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-11"></a><span data-ttu-id="af0ae-253">バージョン 2004: 5 月11日</span><span class="sxs-lookup"><span data-stu-id="af0ae-253">Version 2004: May 11</span></span>
<span data-ttu-id="af0ae-254">*バージョン 2004 (ビルド 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-254">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-256">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-257">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-257">Excel</span></span>

- <span data-ttu-id="af0ae-258">**ストーリーにアニメーション gif を通知します。** Office editor では、アニメーション Gif がサポートされるようになりました。ドキュメントは snazzier しただけです。</span><span class="sxs-lookup"><span data-stu-id="af0ae-258">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-259">Outlook</span></span>

- <span data-ttu-id="af0ae-260">**メール内の強化**されたリンク:ファイルへのリンクを含めると、そのファイル名が URL に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-260">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="af0ae-261">すべての受信者がアクセスできるようにアクセス許可を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-261">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="af0ae-262">詳細情報</span><span class="sxs-lookup"><span data-stu-id="af0ae-262">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="af0ae-263">[ブログの投稿](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="af0ae-263">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="af0ae-264">**ストーリーにアニメーション gif を通知します。** Office editor では、アニメーション Gif がサポートされるようになりました。ドキュメントは snazzier しただけです。</span><span class="sxs-lookup"><span data-stu-id="af0ae-264">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af0ae-265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-265">PowerPoint</span></span>

- <span data-ttu-id="af0ae-266">**ストーリーにアニメーション gif を通知します。** Office editor では、アニメーション Gif がサポートされるようになりました。ドキュメントは snazzier しただけです。</span><span class="sxs-lookup"><span data-stu-id="af0ae-266">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="af0ae-267">詳細情報</span><span class="sxs-lookup"><span data-stu-id="af0ae-267">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="af0ae-268">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-268">Word</span></span>

- <span data-ttu-id="af0ae-269">**ストーリーにアニメーション gif を通知します。** Office editor では、アニメーション Gif がサポートされるようになりました。ドキュメントは snazzier しただけです。</span><span class="sxs-lookup"><span data-stu-id="af0ae-269">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-272">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-272">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-273">Outlook</span></span>

- <span data-ttu-id="af0ae-274">トースト通知を表示しているときにユーザーがクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-274">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-04"></a><span data-ttu-id="af0ae-276">バージョン 2004: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-276">Version 2004: May 04</span></span>
<span data-ttu-id="af0ae-277">*バージョン 2004 (ビルド 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-277">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-279">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-279">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-280">Outlook</span></span>

- <span data-ttu-id="af0ae-281">**より良い結果-jiffy では次のようになります。** 検索機能を更新して、これまでよりも賢明で迅速に、かつ信頼できるものにしました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-281">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="af0ae-282">詳細情報</span><span class="sxs-lookup"><span data-stu-id="af0ae-282">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="af0ae-283">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-283">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-286">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-286">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="af0ae-287">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-287">Office Suite</span></span>

- <span data-ttu-id="af0ae-288">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-288">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-29"></a><span data-ttu-id="af0ae-290">バージョン 2004: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-290">Version 2004: April 29</span></span>
<span data-ttu-id="af0ae-291">*バージョン 2004 (ビルド 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-291">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-293">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-293">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-294">Outlook</span></span>

- <span data-ttu-id="af0ae-295">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-295">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-298">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-298">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-299">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-299">Outlook</span></span>

- <span data-ttu-id="af0ae-300">Windows の一部のビルドで Outlook がクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-300">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2004-april-25"></a><span data-ttu-id="af0ae-302">バージョン 2004: 4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-302">Version 2004: April 25</span></span>
<span data-ttu-id="af0ae-303">*バージョン 2004 (ビルド 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-303">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-305">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-305">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-306">Outlook</span></span>

- <span data-ttu-id="af0ae-307">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-307">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="af0ae-308">Project</span><span class="sxs-lookup"><span data-stu-id="af0ae-308">Project</span></span>

- <span data-ttu-id="af0ae-309">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-309">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af0ae-310">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-310">Office Suite</span></span>

- <span data-ttu-id="af0ae-311">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-311">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-21"></a><span data-ttu-id="af0ae-313">バージョン 2004: 4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-313">Version 2004: April 21</span></span>
<span data-ttu-id="af0ae-314">*バージョン 2004 (ビルド 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-314">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-316">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-316">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-317">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-317">Outlook</span></span>

- <span data-ttu-id="af0ae-318">フォルダー ウィンドウの幅が予期せず変更される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-318">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="af0ae-319">Outlook の終了中にユーザーが応答停止を経験する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-319">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-15"></a><span data-ttu-id="af0ae-321">バージョン 2004: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-321">Version 2004: April 15</span></span>
<span data-ttu-id="af0ae-322">*バージョン 2004 (ビルド 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-322">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-324">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-324">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-325">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-325">Excel</span></span>

- <span data-ttu-id="af0ae-326">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-326">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-327">Outlook</span></span>

- <span data-ttu-id="af0ae-328">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="af0ae-328">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="af0ae-329">望むなら、オフにすることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-329">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af0ae-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-330">PowerPoint</span></span>

- <span data-ttu-id="af0ae-331">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-331">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="af0ae-332">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-332">Word</span></span>

- <span data-ttu-id="af0ae-333">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成できます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-333">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="af0ae-334">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-334">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-337">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af0ae-338">Access</span><span class="sxs-lookup"><span data-stu-id="af0ae-338">Access</span></span>

- <span data-ttu-id="af0ae-339">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-339">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="af0ae-340">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-340">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="af0ae-341">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-341">Excel</span></span>

- <span data-ttu-id="af0ae-342">シートのセル範囲を選択しているのに、単一セルの選択になってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-342">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="af0ae-343">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="af0ae-344">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="af0ae-345">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-345">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="af0ae-346">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-346">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="af0ae-347">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-347">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="af0ae-348">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-348">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="af0ae-349">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-349">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="af0ae-350">X 軸の範囲によっては、グラフのサイズを小さくすると、Excel が応答を停止する場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-350">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="af0ae-351">R1C1 セルの参照が有効になっている Excel シートが共同編集 / 共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動しても、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-351">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="af0ae-352">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-352">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-353">Outlook</span></span>

- <span data-ttu-id="af0ae-354">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-354">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="af0ae-355">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-355">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="af0ae-356">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-356">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="af0ae-357">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-357">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="af0ae-358">メール メッセージからカテゴリが消えることがあるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-358">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="af0ae-359">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-359">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="af0ae-360">ユーザーが組織フォームのプロパティを表示しようとするとクラッシュするという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-360">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="af0ae-361">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-361">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="af0ae-362">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-362">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="af0ae-363">返信の対象のメッセージに対してユーザーが所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-363">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="af0ae-364">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-364">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="af0ae-365">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-365">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="af0ae-366">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-366">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="af0ae-367">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-367">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="af0ae-368">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-368">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af0ae-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-369">PowerPoint</span></span>

- <span data-ttu-id="af0ae-370">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-370">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="af0ae-371">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-371">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="af0ae-372">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-372">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="af0ae-373">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-373">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="af0ae-374">Project</span><span class="sxs-lookup"><span data-stu-id="af0ae-374">Project</span></span>

- <span data-ttu-id="af0ae-375">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-375">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="af0ae-376">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-376">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="af0ae-377">ユーザーがスケジュール グループ内の [タスク] リボンにある [無効化] ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Application (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-377">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="af0ae-378">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-378">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="af0ae-379">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="af0ae-379">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="af0ae-380">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-380">This behavior has been fixed.</span></span>

- <span data-ttu-id="af0ae-381">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-381">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="af0ae-382">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-382">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="af0ae-383">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-383">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="af0ae-384">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-384">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="af0ae-385">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-385">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="af0ae-386">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-386">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="af0ae-387">[フォーム] ビュー内で先行処理 / 後続処理データを編集すると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-387">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="af0ae-388">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-388">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="af0ae-389">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-389">Word</span></span>

- <span data-ttu-id="af0ae-390">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-390">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="af0ae-391">この変更により、[表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-391">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="af0ae-392">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-392">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="af0ae-393">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-393">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="af0ae-394">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-394">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="af0ae-395">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-395">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="af0ae-396">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-396">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="af0ae-397">この変更により、2 ページ表示で、コメントを作成するとき、コメント アンカーが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-397">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="af0ae-398">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-398">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="af0ae-399">スタイルがリストにリンクされているスタイルの祖先である段落の場合、そのリストの番号が失われる場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-399">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="af0ae-400">この変更により、文書に存在しない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-400">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="af0ae-401">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-401">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="af0ae-402">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-402">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="af0ae-403">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-403">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="af0ae-404">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-404">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-14"></a><span data-ttu-id="af0ae-406">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-406">Version 2003: April 14</span></span>
<span data-ttu-id="af0ae-407">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-407">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="af0ae-408">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="af0ae-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

- <span data-ttu-id="af0ae-410">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="af0ae-410">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-09"></a><span data-ttu-id="af0ae-412">バージョン 2003: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-412">Version 2003: April 09</span></span>
<span data-ttu-id="af0ae-413">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-413">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-415">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-416">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-416">Excel</span></span>

- <span data-ttu-id="af0ae-417">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="af0ae-417">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="af0ae-418">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="af0ae-418">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-419">Outlook</span></span>

- <span data-ttu-id="af0ae-420">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="af0ae-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="af0ae-421">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="af0ae-421">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af0ae-422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-422">PowerPoint</span></span>

- <span data-ttu-id="af0ae-423">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="af0ae-423">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="af0ae-424">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="af0ae-424">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="af0ae-425">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-425">Word</span></span>

- <span data-ttu-id="af0ae-426">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="af0ae-426">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="af0ae-427">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="af0ae-427">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-03"></a><span data-ttu-id="af0ae-431">バージョン 2003: 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-431">Version 2003: April 03</span></span>
<span data-ttu-id="af0ae-432">*バージョン 2003 (ビルド 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-432">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-434">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-434">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-435">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-435">Excel</span></span>

- <span data-ttu-id="af0ae-436">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-436">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-437">Outlook</span></span>

- <span data-ttu-id="af0ae-438">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-438">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="af0ae-439">Project</span><span class="sxs-lookup"><span data-stu-id="af0ae-439">Project</span></span>

- <span data-ttu-id="af0ae-440">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChangeevent が発生します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-440">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="af0ae-441">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-441">Word</span></span>

- <span data-ttu-id="af0ae-442">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-442">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="af0ae-444">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-444">Version 2003: March 31</span></span>
<span data-ttu-id="af0ae-445">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-445">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-447">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-447">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="af0ae-448">Access</span><span class="sxs-lookup"><span data-stu-id="af0ae-448">Access</span></span>

- <span data-ttu-id="af0ae-449">**[テーブルの追加] 作業ウィンドウ:** Access の新しい [テーブルの追加] 作業ウィンドウを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-449">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="af0ae-450">この機能を使用すると、クエリやリレーションシップ ビューのために [テーブルの表示] ダイアログボックスに移動することなく、クエリ ウィンドウに追加またはそこから削除する 1 つ以上のテーブルを簡単に選択することができます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-450">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="af0ae-451">この機能には、リンク テーブルを表示するための新しい [リンク] タブ、現在のリストをフィルター処理するための検索ボックス、"ドラッグ アンド ドロップ" による操作なども含まれます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-451">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-454">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-454">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="af0ae-455">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="af0ae-455">Project</span></span>

- <div><span data-ttu-id="af0ae-456"><span style="display:inline !important;">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="af0ae-456"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="af0ae-458">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-458">Version 2003: March 25</span></span>
<span data-ttu-id="af0ae-459">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-459">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="af0ae-460">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="af0ae-460">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="af0ae-461">バージョン 2003: 3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-461">Version 2003: March 23</span></span>
<span data-ttu-id="af0ae-462">*バージョン 2003 (ビルド 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-462">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="af0ae-463">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="af0ae-463">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="af0ae-464">バージョン 2003: 3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-464">Version 2003: March 21</span></span>
<span data-ttu-id="af0ae-465">*バージョン 2003 (ビルド 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-465">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-467">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-467">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-468">Outlook</span></span>

- <span data-ttu-id="af0ae-469">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="af0ae-469">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="af0ae-470">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-470">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="af0ae-471">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="af0ae-471">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="af0ae-472">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-472">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af0ae-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-473">PowerPoint</span></span>

- <span data-ttu-id="af0ae-474">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-474">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-16"></a><span data-ttu-id="af0ae-476">Version 2003: March 16</span><span class="sxs-lookup"><span data-stu-id="af0ae-476">Version 2003: March 16</span></span>
<span data-ttu-id="af0ae-477">*バージョン 2003 (ビルド 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-477">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-479">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-480">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-480">Excel</span></span>

- <span data-ttu-id="af0ae-481">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-481">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-482">Outlook</span></span>

- <span data-ttu-id="af0ae-483">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-483">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af0ae-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-484">PowerPoint</span></span>

- <span data-ttu-id="af0ae-485">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-485">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="af0ae-486">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-486">Word</span></span>

- <span data-ttu-id="af0ae-487">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-487">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af0ae-488">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-488">Office Suite</span></span>

- <span data-ttu-id="af0ae-489">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-489">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="af0ae-490">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-490">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-493">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-494">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-494">Excel</span></span>

- <span data-ttu-id="af0ae-495">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-495">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-496">Outlook</span></span>

- <span data-ttu-id="af0ae-497">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-497">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-10"></a><span data-ttu-id="af0ae-499">バージョン 2003: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-499">Version 2003: March 10</span></span>
<span data-ttu-id="af0ae-500">*バージョン 2003 (ビルド 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-500">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="af0ae-501">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="af0ae-501">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)
### <a name="feature-updates"></a><span data-ttu-id="af0ae-503">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-504">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-504">Excel</span></span>
- <span data-ttu-id="af0ae-505">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-505">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="af0ae-506">詳細情報</span><span class="sxs-lookup"><span data-stu-id="af0ae-506">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="af0ae-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-507">PowerPoint</span></span>
- <span data-ttu-id="af0ae-508">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-508">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="af0ae-509">詳細情報</span><span class="sxs-lookup"><span data-stu-id="af0ae-509">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="af0ae-510">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-510">Word</span></span>
- <span data-ttu-id="af0ae-511">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-511">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="af0ae-512">詳細情報</span><span class="sxs-lookup"><span data-stu-id="af0ae-512">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-513">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-513">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-514">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-514">Excel</span></span>

- <span data-ttu-id="af0ae-515">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-515">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="af0ae-516">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-516">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="af0ae-517">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-517">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="af0ae-518">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="af0ae-519">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-519">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="af0ae-520">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-520">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="af0ae-521">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-521">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="af0ae-522">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-522">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="af0ae-523">この変更では、アドインによって noSelect ロックがある図形を含むドキュメントまたはワークシートのホスト アイテムが求められるときに、オブジェクト モデルでランタイム エラーが発生する問題および App (Excel、Word) がクラッシュする可能性がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-523">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="af0ae-524">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-524">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="af0ae-525">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-525">Outlook</span></span>

- <span data-ttu-id="af0ae-526">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-526">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="af0ae-527">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-527">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="af0ae-528">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-528">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="af0ae-529">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-529">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="af0ae-530">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-530">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="af0ae-531">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-531">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="af0ae-532">ユーザーが「&quot;空き時間情報オプション&quot;」予定表のアクセス許可ダイアログにアクセスできなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-532">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="af0ae-533">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「&quot;申し訳ございません、このアイテムを開くことができません&quot;」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-533">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="af0ae-534">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-534">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="af0ae-535">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-535">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="af0ae-536">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-536">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="af0ae-537">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-537">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="af0ae-538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-538">PowerPoint</span></span>

- <span data-ttu-id="af0ae-539">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-539">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="af0ae-540">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-540">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="af0ae-541">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-541">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="af0ae-542">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-542">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="af0ae-543">Project</span><span class="sxs-lookup"><span data-stu-id="af0ae-543">Project</span></span>

- <span data-ttu-id="af0ae-544">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-544">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="af0ae-545">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-545">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="af0ae-546">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-546">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="af0ae-547">Visio</span><span class="sxs-lookup"><span data-stu-id="af0ae-547">Visio</span></span>

- <span data-ttu-id="af0ae-548">Visio デスクトップで開いたファイルに関して、[図形情報] ウィンドウの [図形データ] セクションに矛盾した詳細が表示されていました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-548">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="af0ae-549">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-549">It has now been fixed.</span></span>

- <span data-ttu-id="af0ae-550">何らかのセキュリティ チェックが原因で、2016 より前のバージョンでインポートされたビットマップは表示されていませんでした。</span><span class="sxs-lookup"><span data-stu-id="af0ae-550">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="af0ae-551">この問題は Visio サブスクリプションで修正されました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-551">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="af0ae-552">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-552">Word</span></span>

- <span data-ttu-id="af0ae-553">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-553">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="af0ae-554">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-554">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="af0ae-555">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-555">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="af0ae-556">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-556">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="af0ae-557">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="af0ae-557">This issue has been fixed.</span></span>

- <span data-ttu-id="af0ae-558">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-558">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="af0ae-559">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-559">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="af0ae-560">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-560">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="af0ae-561">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-561">Office Suite</span></span>

- <span data-ttu-id="af0ae-562">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-562">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="af0ae-563">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="af0ae-563">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="af0ae-564">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-564">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="af0ae-565">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word、Excel、PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-565">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="af0ae-566">同じ SharePoint ライブラリから Word、Excel、PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-566">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-05"></a><span data-ttu-id="af0ae-568">バージョン 2002: 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-568">Version 2002: March 05</span></span>
<span data-ttu-id="af0ae-569">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-569">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="af0ae-570">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="af0ae-570">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="af0ae-571">バージョン 2002: 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-571">Version 2002: March 04</span></span>
<span data-ttu-id="af0ae-572">*バージョン 2002 (ビルド 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-572">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-574">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-574">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="af0ae-575">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="af0ae-575">Project</span></span>
- <div><span data-ttu-id="af0ae-576">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-576">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="af0ae-577">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-577">Office Suite</span></span>
- <div><span data-ttu-id="af0ae-578">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-578">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-01"></a><span data-ttu-id="af0ae-580">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-580">Version 2002: March 01</span></span>
<span data-ttu-id="af0ae-581">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-581">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-582">解決した問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-583">Outlook</span></span>

- <div><span data-ttu-id="af0ae-584">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-584">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-february-24"></a><span data-ttu-id="af0ae-586">バージョン 2002: 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-586">Version 2002: February 24</span></span>
<span data-ttu-id="af0ae-587">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-587">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="af0ae-588">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="af0ae-588">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="af0ae-589">バージョン 2002: 2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-589">Version 2002: February 22</span></span>
<span data-ttu-id="af0ae-590">*バージョン 2002 (ビルド 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-590">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="af0ae-591">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="af0ae-591">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="af0ae-592">バージョン 2002: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-592">Version 2002: February 21</span></span>
<span data-ttu-id="af0ae-593">*バージョン 2002 (ビルド 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-593">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-595">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-595">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="af0ae-596">Access</span><span class="sxs-lookup"><span data-stu-id="af0ae-596">Access</span></span>

- <span data-ttu-id="af0ae-597">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="af0ae-597">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="af0ae-598">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-598">Search and replace text in SQL View.</span></span> <span data-ttu-id="af0ae-599">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-599">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-600">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-600">Outlook</span></span>

- <span data-ttu-id="af0ae-601">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="af0ae-601">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="af0ae-602">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-602">Outlook now detects this and helps you get connected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-605">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-605">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="af0ae-606">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-606">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="af0ae-607">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="af0ae-607">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;</span></span></div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a><span data-ttu-id="af0ae-608">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-608">Outlook</span></span>

- <div><span data-ttu-id="af0ae-609">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-609">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span></div>


- <div><span data-ttu-id="af0ae-610">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-610">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span></div>


- <div><span data-ttu-id="af0ae-611">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="af0ae-611">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span></div>


- <div><span data-ttu-id="af0ae-612">黒のテーマを持つユーザーが [&quot;差出人&quot;] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-612">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span></div>


- <div><span data-ttu-id="af0ae-613"><span style="display:inline !important;">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span></span><span class="sxs-lookup"><span data-stu-id="af0ae-613"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-18"></a><span data-ttu-id="af0ae-615">バージョン 2002: 2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-615">Version 2002: February 18</span></span>
<span data-ttu-id="af0ae-616">*バージョン 2002 (ビルド 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-616">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="af0ae-617">バージョン 2002: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="af0ae-617">Version 2002: February 11</span></span>
<span data-ttu-id="af0ae-618">*バージョン 2002 (ビルド 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="af0ae-618">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="af0ae-619">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="af0ae-619">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="af0ae-621">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="af0ae-621">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="af0ae-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-622">Outlook</span></span>

- <span data-ttu-id="af0ae-623">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="af0ae-623">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="af0ae-624">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-624">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="af0ae-625">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-625">Word</span></span>

- <span data-ttu-id="af0ae-626">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-626">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="af0ae-627">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-627">Office Suite</span></span>

- <span data-ttu-id="af0ae-628">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-628">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="af0ae-631">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="af0ae-631">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="af0ae-632">Access</span><span class="sxs-lookup"><span data-stu-id="af0ae-632">Access</span></span>

- <span data-ttu-id="af0ae-633">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-633">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="af0ae-634">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-634">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="af0ae-635">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-635">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="af0ae-636">VB コードのレコーダー オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-636">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="af0ae-637">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-637">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="af0ae-638">Excel</span><span class="sxs-lookup"><span data-stu-id="af0ae-638">Excel</span></span>

- <span data-ttu-id="af0ae-639">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-639">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="af0ae-640">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-640">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="af0ae-641">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-641">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="af0ae-642">Outlook</span><span class="sxs-lookup"><span data-stu-id="af0ae-642">Outlook</span></span>

- <span data-ttu-id="af0ae-643">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-643">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="af0ae-644">左側のナビゲーション ウィンドウで [お気に入り] に保存したフォルダーが断続的に表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-644">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="af0ae-645">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-645">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="af0ae-646">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-646">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="af0ae-647">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-647">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="af0ae-648">アイテム保持ポリシーに基づいて期限切れになるメールに 2 つのラベルが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-648">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="af0ae-649">メールが 1 日で期限切れになることを示すものと、2 日で期限切れになることを示すものです。</span><span class="sxs-lookup"><span data-stu-id="af0ae-649">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="af0ae-650">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-650">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="af0ae-651">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="af0ae-651">PowerPoint</span></span>

- <span data-ttu-id="af0ae-652">インクが PowerPoint のインク アニメーションで使用すると完全にレンダリングされない、またはスキップされることがある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-652">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="af0ae-653">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-653">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="af0ae-654">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-654">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="af0ae-655">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="af0ae-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="af0ae-656">Project</span><span class="sxs-lookup"><span data-stu-id="af0ae-656">Project</span></span>

- <span data-ttu-id="af0ae-657">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-657">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="af0ae-658">Word</span><span class="sxs-lookup"><span data-stu-id="af0ae-658">Word</span></span>

- <span data-ttu-id="af0ae-659">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-659">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="af0ae-660">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-660">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="af0ae-661">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-661">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="af0ae-662">コメントを編集し、テキストをイタリック体にし、それを投稿すると、その後にイタリック体の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-662">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="af0ae-663">反転したページ色を使用する読み取りモードでコメントのヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-663">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="af0ae-664">ドキュメントが共同編集されている場合、ルート コメントの下書き版が保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-664">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="af0ae-665">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="af0ae-665">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="af0ae-666">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-666">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="af0ae-667">コメント コンテキスト メニューのコメント コマンド (コメントの編集、コメントへの返信、コメントの削除、コメントの解決) が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="af0ae-667">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="af0ae-668">Office スイート</span><span class="sxs-lookup"><span data-stu-id="af0ae-668">Office Suite</span></span>

- <span data-ttu-id="af0ae-669">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-669">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="af0ae-670">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="af0ae-670">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

