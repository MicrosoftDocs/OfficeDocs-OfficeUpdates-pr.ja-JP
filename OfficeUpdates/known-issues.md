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
ms.openlocfilehash: f863015cbf8680697509fdaf0bbd5c7000e4c142
ms.sourcegitcommit: e46d02cd54b8c164b853a130ca07ce9c85f586c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/12/2019
ms.locfileid: "38282165"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="e7cd9-103">Office 365 ProPlus の既知の問題</span><span class="sxs-lookup"><span data-stu-id="e7cd9-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="e7cd9-104">これらの既知の問題では、月次チャネルに含まれているセキュリティ以外の更新プログラム、2019 年の Office 365 ProPlus、Visio Pro for Office 365、Project Online デスクトップ クライアントおよび Office 365 Business に対する SACT および SAC の更新プログラムに関する情報を提供します。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-104">These known issues provide information about non-security updates that are included in Monthly Channel, SACT and SAC updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

<span data-ttu-id="e7cd9-105">次のテーブルでは、現在未解決の問題の概要と解決済みの問題を説明します。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="e7cd9-106">現在調査中の重要な問題に関する以下のテーブルは更新されます。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-106">We will update the table below with significant issues we are investigating.</span></span>

> [!NOTE]
>- <span data-ttu-id="e7cd9-107">この一覧は包括的ではありません。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-107">This list is not comprehensive.</span></span>
>- <span data-ttu-id="e7cd9-108">[解決済み] と表示されているチャネル以外の問題が発生した場合は、間もなく解決することができます。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-108">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="e7cd9-109">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e7cd9-109">Learn more</span></span>](https://docs.microsoft.com/ja-JP/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="e7cd9-110">解決済みの問題は、それぞれのチャネルのページにも記載されています。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-110">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="e7cd9-111">最終更新日: 2019 年 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="e7cd9-111">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="e7cd9-112">Excel</span><span class="sxs-lookup"><span data-stu-id="e7cd9-112">Excel</span></span>

- <span data-ttu-id="e7cd9-113">OneDrive からオブジェクトとしてファイルを挿入する場合の問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-113">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="e7cd9-114">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-114">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="e7cd9-115">以前のバージョンの Office で作成されたブックを、現在のバージョンの Office で開いたときに Excel がハングすることがある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-115">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="e7cd9-116">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20436)、SAC バージョン 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-116">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="e7cd9-117">範囲を削除した後に入力した値の表示が遅れる問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-117">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="e7cd9-118">**解決済み**: SAC バージョン 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-118">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="e7cd9-119">スクロール後にセルを選択すると間違ったセルが選択されるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-119">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="e7cd9-120">**調査中**: SACT</span><span class="sxs-lookup"><span data-stu-id="e7cd9-120">**Investigating**: SACT</span></span> <br><span data-ttu-id="e7cd9-121">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-121">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="e7cd9-122">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされないことがある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-122">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="e7cd9-123">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-123">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="e7cd9-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="e7cd9-124">Outlook</span></span>

- <span data-ttu-id="e7cd9-125">Exchange のセカンダ リアカウントを追加する際に、重複する特別なフォルダーが作成されたことが一部のユーザーに示される問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-125">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="e7cd9-126">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-126">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388)</span></span>

- <span data-ttu-id="e7cd9-127">メモリ リークを引き起こす可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-127">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="e7cd9-128">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20388)、SAC バージョン 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-128">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388)</span></span>

- <span data-ttu-id="e7cd9-129">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された重複した特別なフォルダーが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-129">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="e7cd9-130">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-130">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388)</span></span>

- <span data-ttu-id="e7cd9-131">ユーザーが Skype から '不参加の会話' メッセージを受信したときにクラッシュする可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-131">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="e7cd9-132">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-132">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="e7cd9-133">DisableBGSave が有効になっているコンピューターで添付ファイルを開くと、"操作に失敗しました" という汎用のエラーが表示される問題が特定されました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-133">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="e7cd9-134">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-134">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="e7cd9-135">cid: イメージ (Outlook のメールベースの画像) のリンクが解除できない問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-135">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="e7cd9-136">**解決済み**: SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-136">**Resolved**: SACT Version 1908 (11929.20396)</span></span>

- <span data-ttu-id="e7cd9-137">S/MIME で暗号化された電子メールを送信しようとする際に誤ったエラー メッセージが表示される可能性がある問題が特定されました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-137">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="e7cd9-138">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-138">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e7cd9-139">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e7cd9-139">PowerPoint</span></span>

- <span data-ttu-id="e7cd9-140">ハイパーリンク付きのテキストを貼り付けるときにハイパーリンクが作成されない問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-140">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="e7cd9-141">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-141">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="e7cd9-142">スライド マスターとスライド レイアウトのヘッダー/フッター/スライド番号プレースホルダーにテキストを貼り付けた後、TextRanges が破損する可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-142">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="e7cd9-143">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-143">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="e7cd9-144">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-144">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="e7cd9-145">**解決済み**: 月次バージョン 1910 (12130.20272)、SACT バージョン 1908 (11929.20396)、SAC バージョン 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-145">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="e7cd9-146">Project</span><span class="sxs-lookup"><span data-stu-id="e7cd9-146">Project</span></span>

- <span data-ttu-id="e7cd9-147">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-147">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="e7cd9-148">**解決済み**: 月次バージョン 1910 (12130.20344)、SACT バージョン 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-148">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388)</span></span>

### <a name="word"></a><span data-ttu-id="e7cd9-149">Word</span><span class="sxs-lookup"><span data-stu-id="e7cd9-149">Word</span></span>
- <span data-ttu-id="e7cd9-150">OneDrive からオブジェクトとしてファイルを挿入する場合の問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-150">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="e7cd9-151">**解決済み**: 月次バージョン 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="e7cd9-151">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="e7cd9-152">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="e7cd9-152">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
