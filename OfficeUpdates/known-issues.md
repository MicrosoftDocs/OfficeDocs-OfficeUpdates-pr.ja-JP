---
title: Office 365 ProPlus の既知の問題
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus の既知の問題に関する情報を提供します。
ms.openlocfilehash: 45464d14ecfbf849929daba122b0a57bc74d05c5
ms.sourcegitcommit: beff319f87f2fbecd15468f3ffa9bb99416ed165
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/22/2020
ms.locfileid: "43715435"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="4c8f8-103">Office 365 ProPlus の既知の問題</span><span class="sxs-lookup"><span data-stu-id="4c8f8-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="4c8f8-104">この既知の問題には、2019 年の月次チャネル、半期チャネル (対象指定)、半期チャネルの更新プログラムに含まれるセキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-104">These known issues provide information about non-security updates that are included in Monthly Channel, Semi-Annual Channel (Targeted), and Semi-Annual Channel  updates in 2019 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!NOTE]
>- <span data-ttu-id="4c8f8-105">この一覧は包括的ではありません。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-105">This list is not comprehensive.</span></span>
>- <span data-ttu-id="4c8f8-106">[解決済み] と表示されているチャネル以外の問題が発生した場合は、間もなく解決することができます。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-106">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="4c8f8-107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4c8f8-107">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="4c8f8-108">解決済みの問題は、それぞれのチャネルのページにも記載されています。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-108">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="4c8f8-109">最終更新日: 2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="4c8f8-109">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="4c8f8-110">Excel</span><span class="sxs-lookup"><span data-stu-id="4c8f8-110">Excel</span></span>

- <span data-ttu-id="4c8f8-111">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-111">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="4c8f8-112">**調査中**: 月次、SACT</span><span class="sxs-lookup"><span data-stu-id="4c8f8-112">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="4c8f8-113">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-113">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="4c8f8-114">**解決済み**: SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-114">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="4c8f8-115">ユーザーが Office 365 の Excel ブック形式で保存できなくなることがある問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-115">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="4c8f8-116">**解決済み**: SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="4c8f8-117">ファイルに広範な条件付き書式が設定されている場合、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-117">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="4c8f8-118">**解決済み**: SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="4c8f8-119">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-119">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="4c8f8-120">**調査中**: SACT</span><span class="sxs-lookup"><span data-stu-id="4c8f8-120">**Investigating**: SACT</span></span><br><span data-ttu-id="4c8f8-121">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-121">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="4c8f8-122">SQL 表形式サーバーのクエリのピボットテーブルの残りの部分と一緒にレポート フィルターを変換すると、正しい結果が返されないことがある問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-122">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="4c8f8-123">**調査中**: 月次</span><span class="sxs-lookup"><span data-stu-id="4c8f8-123">**Investigating**: Monthly</span></span>

- <span data-ttu-id="4c8f8-124">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-124">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="4c8f8-125">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-125">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="4c8f8-126">OneDrive からオブジェクトとしてファイルを挿入する場合の問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-126">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="4c8f8-127">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-127">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="4c8f8-128">以前のバージョンの Office で作成されたブックを、現在のバージョンの Office で開いたときに Excel がハングすることがある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-128">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="4c8f8-129">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20436)、SAC バージョン 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-129">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="4c8f8-130">範囲を削除した後に入力した値の表示が遅れる問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-130">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="4c8f8-131">**解決済み**: SAC バージョン 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-131">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="4c8f8-132">スクロール後にセルを選択すると間違ったセルが選択されるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-132">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="4c8f8-133">**調査中**: SACT</span><span class="sxs-lookup"><span data-stu-id="4c8f8-133">**Investigating**: SACT</span></span> <br><span data-ttu-id="4c8f8-134">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-134">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="4c8f8-135">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされないことがある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-135">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="4c8f8-136">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-136">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="4c8f8-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="4c8f8-137">Outlook</span></span>

- <span data-ttu-id="4c8f8-138">Exchange のセカンダ リアカウントを追加する際に、重複する特別なフォルダーが作成されたことが一部のユーザーに示される問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-138">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="4c8f8-139">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-139">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="4c8f8-140">メモリ リークを引き起こす可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-140">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="4c8f8-141">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20388)、SAC バージョン 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="4c8f8-142">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された重複した特別なフォルダーが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-142">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="4c8f8-143">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="4c8f8-144">ユーザーが Skype から '不参加の会話' メッセージを受信したときにクラッシュする可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-144">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="4c8f8-145">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-145">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="4c8f8-146">DisableBGSave が有効になっているコンピューターで添付ファイルを開くと、"操作に失敗しました" という汎用のエラーが表示される問題が特定されました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-146">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="4c8f8-147">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="4c8f8-148">cid: イメージ (Outlook のメールベースの画像) のリンクが解除できない問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-148">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="4c8f8-149">**解決済み**: SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-149">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="4c8f8-150">S/MIME で暗号化された電子メールを送信しようとする際に誤ったエラー メッセージが表示される可能性がある問題が特定されました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-150">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="4c8f8-151">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-151">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4c8f8-152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4c8f8-152">PowerPoint</span></span>

- <span data-ttu-id="4c8f8-153">縦書きのテキスト ボックス内で一部のカタカナが正しく表示されないことがある問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-153">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="4c8f8-154">**調査中**: 月次</span><span class="sxs-lookup"><span data-stu-id="4c8f8-154">**Investigating**: Monthly</span></span>

- <span data-ttu-id="4c8f8-155">ハイパーリンク付きのテキストを貼り付けるときにハイパーリンクが作成されない問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-155">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="4c8f8-156">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-156">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="4c8f8-157">スライド マスターとスライド レイアウトのヘッダー/フッター/スライド番号プレースホルダーにテキストを貼り付けた後、TextRanges が破損する可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-157">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="4c8f8-158">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="4c8f8-159">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-159">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="4c8f8-160">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20396)、SAC バージョン 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-160">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="4c8f8-161">Project</span><span class="sxs-lookup"><span data-stu-id="4c8f8-161">Project</span></span>

- <span data-ttu-id="4c8f8-162">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-162">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="4c8f8-163">**調査中**: 月次</span><span class="sxs-lookup"><span data-stu-id="4c8f8-163">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="4c8f8-164">**解決済み**: SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-164">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="4c8f8-165">平準化によって割り当て超過が解決されない問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-165">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="4c8f8-166">**調査中**: 月次</span><span class="sxs-lookup"><span data-stu-id="4c8f8-166">**Investigating**: Monthly</span></span>

- <span data-ttu-id="4c8f8-167">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-167">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="4c8f8-168">**解決済み**: 月次バージョン 1910 (12130.20344)、SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-168">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="4c8f8-169">Word</span><span class="sxs-lookup"><span data-stu-id="4c8f8-169">Word</span></span>

- <span data-ttu-id="4c8f8-170">ナビゲーション ウィンドウから検索できない場合がある問題。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-170">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="4c8f8-171">**調査中**: 月次</span><span class="sxs-lookup"><span data-stu-id="4c8f8-171">**Investigating**: Monthly</span></span>

- <span data-ttu-id="4c8f8-172">OneDrive からオブジェクトとしてファイルを挿入する場合の問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-172">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="4c8f8-173">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="4c8f8-173">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="4c8f8-174">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4c8f8-174">Office Suite</span></span>
- <span data-ttu-id="4c8f8-175">接続されていないネットワーク共有にファイルを保存しようとすると、問題が発生する場合がある問題。**調査中**: 月次</span><span class="sxs-lookup"><span data-stu-id="4c8f8-175">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="4c8f8-176">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="4c8f8-176">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
