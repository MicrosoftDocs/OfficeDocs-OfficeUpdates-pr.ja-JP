---
title: Office Insider のリリース ノート
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 6/7/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: 6fca274c0acf56aa2ba5d926e7b4f61a1c8f33d1
ms.sourcegitcommit: 664eea7a20324858da3503f54d0efac97e2299e4
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/07/2019
ms.locfileid: "34773753"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="9f4a0-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="9f4a0-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="9f4a0-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="9f4a0-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="9f4a0-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="9f4a0-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="9f4a0-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="9f4a0-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります</span><span class="sxs-lookup"><span data-stu-id="9f4a0-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="9f4a0-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります</span><span class="sxs-lookup"><span data-stu-id="9f4a0-110">The release notes publication date may not match the actual build release date</span></span>


## <a name="june-7-2019"></a><span data-ttu-id="9f4a0-111">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-111">June 7, 2019</span></span>
<span data-ttu-id="9f4a0-112">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-112">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-113">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-113">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-114">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-114">Word</span></span> 
- <span data-ttu-id="9f4a0-115">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-115">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="9f4a0-116">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-116">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="9f4a0-117">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-117">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-118">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-118">Excel</span></span>
- <span data-ttu-id="9f4a0-119">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-119">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="9f4a0-120">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-120">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-121">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-121">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-122">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-122">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-123">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-123">Outlook</span></span>
- <span data-ttu-id="9f4a0-124">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-124">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-125">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-125">Access</span></span>
- <span data-ttu-id="9f4a0-126">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-126">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-127">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-127">Project</span></span>
- <span data-ttu-id="9f4a0-128">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-128">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="9f4a0-129">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-129">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="9f4a0-130">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-130">May 31, 2019</span></span>
<span data-ttu-id="9f4a0-131">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-131">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-132">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-132">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-133">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-133">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="9f4a0-134">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-134">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="9f4a0-135">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-135">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="9f4a0-136">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-136">Ink in Your Email!</span></span>

<span data-ttu-id="9f4a0-137">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-137">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-138">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-138">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="9f4a0-139">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="9f4a0-139">Open document links in Word</span></span>

<span data-ttu-id="9f4a0-140">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-140">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="9f4a0-141">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-141">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9f4a0-142">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9f4a0-142">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-143">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-143">Getting Started:</span></span>

<span data-ttu-id="9f4a0-144">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-144">Feature will default to off.</span></span> <span data-ttu-id="9f4a0-145">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-145">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9f4a0-146">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-146">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9f4a0-147">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-147">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9f4a0-148">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="9f4a0-148">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9f4a0-149">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-149">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-150">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-150">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-151">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-151">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9f4a0-152">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-152">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-153">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-153">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="9f4a0-154">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="9f4a0-154">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="9f4a0-155">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-155">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="9f4a0-156">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-156">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9f4a0-157">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9f4a0-157">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-158">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-158">Getting Started:</span></span>

<span data-ttu-id="9f4a0-159">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-159">Feature will default to off.</span></span> <span data-ttu-id="9f4a0-160">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-160">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9f4a0-161">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-161">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9f4a0-162">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-162">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9f4a0-163">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="9f4a0-163">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9f4a0-164">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-164">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-165">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-165">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-166">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-166">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9f4a0-167">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-167">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-168">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-168">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="9f4a0-169">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="9f4a0-169">Open the workbook in Excel.</span></span>

<span data-ttu-id="9f4a0-170">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-170">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="9f4a0-171">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-171">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="9f4a0-172">詳細については、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="9f4a0-172">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-173">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-173">Getting Started:</span></span>

<span data-ttu-id="9f4a0-174">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-174">Feature will default to off.</span></span> <span data-ttu-id="9f4a0-175">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-175">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="9f4a0-176">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-176">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="9f4a0-177">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-177">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="9f4a0-178">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="9f4a0-178">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="9f4a0-179">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-179">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-180">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-180">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-181">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-181">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="9f4a0-182">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-182">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-183">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-183">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9f4a0-184">すべて</span><span class="sxs-lookup"><span data-stu-id="9f4a0-184">All</span></span>
- <span data-ttu-id="9f4a0-185">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-185">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-186">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-186">Word</span></span> 
- <span data-ttu-id="9f4a0-187">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-187">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-188">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-188">Excel</span></span>
- <span data-ttu-id="9f4a0-189">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-189">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-190">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-191">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-191">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-192">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-192">Outlook</span></span>
- <span data-ttu-id="9f4a0-193">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-193">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="9f4a0-194">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-194">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="9f4a0-195">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-195">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-196">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-196">Access</span></span>
- <span data-ttu-id="9f4a0-197">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-197">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-198">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-198">Project</span></span>
- <span data-ttu-id="9f4a0-199">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-199">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="9f4a0-200">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-200">May 24, 2019</span></span>
<span data-ttu-id="9f4a0-201">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-201">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-202">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-202">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="9f4a0-203">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="9f4a0-203">User Experience Updates</span></span>

<span data-ttu-id="9f4a0-204">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-204">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-205">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-205">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9f4a0-206">すべて</span><span class="sxs-lookup"><span data-stu-id="9f4a0-206">All</span></span>

- <span data-ttu-id="9f4a0-207">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-207">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-208">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-208">Word</span></span> 
- <span data-ttu-id="9f4a0-209">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-209">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-210">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-210">Excel</span></span>
- <span data-ttu-id="9f4a0-211">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-211">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="9f4a0-212">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-212">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-213">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-213">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-214">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-214">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-215">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-215">Outlook</span></span>
- <span data-ttu-id="9f4a0-216">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-216">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-217">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-217">Access</span></span>
- <span data-ttu-id="9f4a0-218">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-218">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-219">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-219">Project</span></span>
- <span data-ttu-id="9f4a0-220">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-220">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="9f4a0-221">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-221">May 17, 2019</span></span>
<span data-ttu-id="9f4a0-222">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-222">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-223">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-223">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-224">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-224">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="9f4a0-225">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="9f4a0-225">User Experience Updates</span></span>

<span data-ttu-id="9f4a0-226">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-226">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-227">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-227">Getting Started:</span></span>

<span data-ttu-id="9f4a0-228">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-228">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="9f4a0-229">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="9f4a0-229">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="9f4a0-230">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-230">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-231">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-231">Getting Started:</span></span>

<span data-ttu-id="9f4a0-232">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-232">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-233">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-233">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-234">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="9f4a0-234">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="9f4a0-235">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-235">Pick your favorite action</span></span>

<span data-ttu-id="9f4a0-236">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-236">Don't use Flag and Delete?</span></span> <span data-ttu-id="9f4a0-237">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="9f4a0-237">How about Archive or Mark as Read?</span></span> <span data-ttu-id="9f4a0-238">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-238">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-239">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-239">Getting Started:</span></span>

<span data-ttu-id="9f4a0-240">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-240">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="9f4a0-241">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-241">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-242">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-242">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-243">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-243">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="9f4a0-244">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="9f4a0-244">Relaxed or tighter layout?</span></span> <span data-ttu-id="9f4a0-245">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="9f4a0-245">You choose</span></span>

<span data-ttu-id="9f4a0-246">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-246">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-247">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-247">Getting Started:</span></span>

<span data-ttu-id="9f4a0-248">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-248">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-249">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-249">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-250">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-250">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="9f4a0-251">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-251">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="9f4a0-252">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-252">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="9f4a0-253">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-253">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-254">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-254">Getting Started:</span></span>

<span data-ttu-id="9f4a0-255">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-255">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-256">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-256">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-257">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-257">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="9f4a0-258">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-258">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="9f4a0-259">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-259">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="9f4a0-260">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-260">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-261">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-261">Getting Started:</span></span>

<span data-ttu-id="9f4a0-262">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-262">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-263">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-263">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="9f4a0-264">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="9f4a0-264">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-265">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-265">Getting Started:</span></span>

<span data-ttu-id="9f4a0-266">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-266">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="9f4a0-267">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-267">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-268">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-268">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-269">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-269">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="9f4a0-270">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-270">Draw an ink stroke.</span></span> <span data-ttu-id="9f4a0-271">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-271">Select the Eraser dropdown.</span></span> <span data-ttu-id="9f4a0-272">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-272">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="9f4a0-273">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-273">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-274">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-274">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9f4a0-275">すべて</span><span class="sxs-lookup"><span data-stu-id="9f4a0-275">All</span></span> 
- <span data-ttu-id="9f4a0-276">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-276">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="9f4a0-277">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-277">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-278">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-278">Word</span></span> 
- <span data-ttu-id="9f4a0-279">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-279">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-280">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-280">Excel</span></span>
- <span data-ttu-id="9f4a0-281">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-281">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="9f4a0-282">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-282">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="9f4a0-283">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-283">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-284">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-285">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-285">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-286">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-286">Outlook</span></span>
- <span data-ttu-id="9f4a0-287">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-287">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-288">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-288">Access</span></span>
- <span data-ttu-id="9f4a0-289">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-289">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-290">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-290">Project</span></span>
- <span data-ttu-id="9f4a0-291">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-291">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="9f4a0-292">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-292">May 10, 2019</span></span>
<span data-ttu-id="9f4a0-293">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-293">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-294">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-294">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9f4a0-295">すべて</span><span class="sxs-lookup"><span data-stu-id="9f4a0-295">All</span></span>
- <span data-ttu-id="9f4a0-296">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-296">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-297">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-297">Word</span></span> 
- <span data-ttu-id="9f4a0-298">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-298">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-299">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-299">Excel</span></span>
- <span data-ttu-id="9f4a0-300">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-300">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-301">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-301">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-302">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-302">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-303">Outlook</span></span>
- <span data-ttu-id="9f4a0-304">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-304">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-305">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-305">Access</span></span>
- <span data-ttu-id="9f4a0-306">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-306">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-307">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-307">Project</span></span>
- <span data-ttu-id="9f4a0-308">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-308">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="9f4a0-309">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-309">May 3, 2019</span></span>
<span data-ttu-id="9f4a0-310">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-310">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-311">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-311">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="9f4a0-312">すべて</span><span class="sxs-lookup"><span data-stu-id="9f4a0-312">All</span></span>
- <span data-ttu-id="9f4a0-313">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-313">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-314">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-314">Word</span></span> 
- <span data-ttu-id="9f4a0-315">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-315">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-316">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-316">Excel</span></span>
- <span data-ttu-id="9f4a0-317">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-317">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="9f4a0-318">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-318">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-319">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-319">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-320">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-320">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-321">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-321">Outlook</span></span>
- <span data-ttu-id="9f4a0-322">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-322">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="9f4a0-323">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-323">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="9f4a0-324">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-324">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-325">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-325">Access</span></span>
- <span data-ttu-id="9f4a0-326">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-326">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-327">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-327">Project</span></span>
- <span data-ttu-id="9f4a0-328">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-328">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="9f4a0-329">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-329">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="9f4a0-330">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-330">April 26, 2019</span></span>
<span data-ttu-id="9f4a0-331">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-331">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-332">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-332">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-333">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-333">Word</span></span> 
- <span data-ttu-id="9f4a0-334">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-334">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-335">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-335">Excel</span></span>
- <span data-ttu-id="9f4a0-336">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-336">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="9f4a0-337">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-337">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-338">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-339">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-339">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-340">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-340">Outlook</span></span>
- <span data-ttu-id="9f4a0-341">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-341">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-342">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-342">Access</span></span>
- <span data-ttu-id="9f4a0-343">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-343">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-344">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-344">Project</span></span>
- <span data-ttu-id="9f4a0-345">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-345">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="9f4a0-346">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-346">April 19, 2019</span></span>
<span data-ttu-id="9f4a0-347">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-347">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-348">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-348">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-349">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-349">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="9f4a0-350">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="9f4a0-350">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="9f4a0-351">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-351">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="9f4a0-352">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-352">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="9f4a0-353">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-353">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="9f4a0-354">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-354">Getting Started:</span></span>

- <span data-ttu-id="9f4a0-355">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-355">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="9f4a0-356">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-356">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-357">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-357">Scenarios to Try:</span></span>

- <span data-ttu-id="9f4a0-358">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-358">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-359">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-359">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9f4a0-360">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="9f4a0-360">All Applications</span></span>
- <span data-ttu-id="9f4a0-361">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-361">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="9f4a0-362">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-362">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="9f4a0-363">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-363">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-364">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-364">Word</span></span> 
- <span data-ttu-id="9f4a0-365">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-365">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="9f4a0-366">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-366">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-367">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-367">Excel</span></span>
- <span data-ttu-id="9f4a0-368">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-368">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-369">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-370">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-370">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="9f4a0-371">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-371">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-372">Outlook</span></span>
- <span data-ttu-id="9f4a0-373">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-373">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="9f4a0-374">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-374">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-375">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-375">Access</span></span>
- <span data-ttu-id="9f4a0-376">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-376">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="9f4a0-377">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-377">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="9f4a0-378">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-378">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="9f4a0-379">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-379">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-380">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-380">Project</span></span>
- <span data-ttu-id="9f4a0-381">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-381">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="9f4a0-382">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-382">April 12, 2019</span></span>
<span data-ttu-id="9f4a0-383">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-383">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-384">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-384">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-385">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-385">Access</span></span>

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a><span data-ttu-id="9f4a0-386">Access の新機能 - Microsoft Graph でのデータ コネクタ</span><span class="sxs-lookup"><span data-stu-id="9f4a0-386">New in Access - Data Connector to Microsoft Graph</span></span>

<span data-ttu-id="9f4a0-387">Graph に保存されているスマート コンテキスト データを活用できるアプリケーションを構築できる Microsoft Graph サービスへのリンクまたはインポート フォーム</span><span class="sxs-lookup"><span data-stu-id="9f4a0-387">Link to or import form Microsoft Graph services to build applications that can leverage the smart contextual data stored in the Graph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-388">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-388">Getting Started:</span></span>

<span data-ttu-id="9f4a0-389">リボンの [外部データ] タブで、[新しいデータ ソース] をクリックし、[オンライン サービス] メニューの Graph コネクタを検索します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-389">External Data tab in the ribbon, click on New Data Sources and find the new Graph connector in the Online Services menu</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-390">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-390">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-391">ユーザー、グループ、OneDrive のアイテムなど、さまざまな Graph サービスからインポートまたはGraph サービスへリンクします。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-391">Import from or link to various Graph services including People, Groups and OneDrive Items.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-392">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-392">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9f4a0-393">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="9f4a0-393">All Applications</span></span>
 - <span data-ttu-id="9f4a0-394">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-394">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="9f4a0-395">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-395">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-396">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-396">Word</span></span> 
- <span data-ttu-id="9f4a0-397">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-397">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-398">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-398">Excel</span></span>
- <span data-ttu-id="9f4a0-399">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-399">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="9f4a0-400">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-400">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-401">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-401">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-402">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-402">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-403">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-403">Outlook</span></span>
- <span data-ttu-id="9f4a0-404">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-404">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="9f4a0-405">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-405">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-406">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-406">Access</span></span>
- <span data-ttu-id="9f4a0-407">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-407">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-408">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-408">Project</span></span>
- <span data-ttu-id="9f4a0-409">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-409">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="9f4a0-410">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-410">April 5, 2019</span></span>
<span data-ttu-id="9f4a0-411">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-411">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-412">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-412">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-413">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="9f4a0-414">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-414">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="9f4a0-415">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-415">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-416">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-416">Getting Started:</span></span>

<span data-ttu-id="9f4a0-417">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-417">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="9f4a0-418">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-418">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-419">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-419">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-420">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-420">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="9f4a0-421">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-421">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="9f4a0-422">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-422">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-423">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-423">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="9f4a0-424">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-424">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="9f4a0-425">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-425">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="9f4a0-426">多くのユーザーがすべて白、またはすべて黒の背景だと閲覧が難しいという課題があったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-426">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-427">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-427">Getting Started:</span></span>

<span data-ttu-id="9f4a0-428">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-428">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-429">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-429">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-430">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-430">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-431">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-431">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="9f4a0-432">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="9f4a0-432">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="9f4a0-433">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-433">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-434">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-434">Getting Started:</span></span>

1. <span data-ttu-id="9f4a0-435">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="9f4a0-435">Open Excel.</span></span>
2. <span data-ttu-id="9f4a0-436">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-436">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="9f4a0-437">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-437">The animated model will play in the editor!</span></span> <span data-ttu-id="9f4a0-438">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-438">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="9f4a0-439">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-439">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-440">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-440">Scenarios to Try:</span></span>

1. <span data-ttu-id="9f4a0-441">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-441">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="9f4a0-442">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-442">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="9f4a0-443">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-443">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-444">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-444">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="9f4a0-445">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="9f4a0-445">All Applications</span></span>
- <span data-ttu-id="9f4a0-446">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-446">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="9f4a0-447">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-447">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="9f4a0-448">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-448">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-449">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-449">Word</span></span> 
- <span data-ttu-id="9f4a0-450">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-450">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-451">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-451">Excel</span></span>
- <span data-ttu-id="9f4a0-452">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-452">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="9f4a0-453">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-453">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="9f4a0-454">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-454">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="9f4a0-455">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-455">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="9f4a0-456">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-456">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="9f4a0-457">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-457">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="9f4a0-458">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-458">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="9f4a0-459">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-459">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="9f4a0-460">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-460">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-461">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-462">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-462">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-463">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-463">Outlook</span></span>
- <span data-ttu-id="9f4a0-464">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-464">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="9f4a0-465">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-465">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="9f4a0-466">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-466">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-467">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-467">Access</span></span>
- <span data-ttu-id="9f4a0-468">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-468">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-469">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-469">Project</span></span>
- <span data-ttu-id="9f4a0-470">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-470">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="9f4a0-471">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-471">March 22, 2019</span></span>
<span data-ttu-id="9f4a0-472">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-472">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-473">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-473">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-474">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-474">Word</span></span> 
- <span data-ttu-id="9f4a0-475">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-475">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-476">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-476">Excel</span></span>
- <span data-ttu-id="9f4a0-477">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-477">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="9f4a0-478">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-478">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="9f4a0-479">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-479">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-480">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-480">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-481">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-481">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-482">Outlook</span></span>
- <span data-ttu-id="9f4a0-483">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-483">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-484">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-484">Access</span></span>
- <span data-ttu-id="9f4a0-485">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-485">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="9f4a0-486">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-486">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-487">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-487">Project</span></span>
- <span data-ttu-id="9f4a0-488">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-488">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="9f4a0-489">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-489">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="9f4a0-490">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-490">March 15, 2019</span></span>
<span data-ttu-id="9f4a0-491">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-491">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-492">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-492">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-493">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-493">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="9f4a0-494">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="9f4a0-494">Focus mode</span></span>

<span data-ttu-id="9f4a0-495">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-495">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="9f4a0-496">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-496">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-497">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-497">Getting Started:</span></span>

<span data-ttu-id="9f4a0-498">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="9f4a0-498">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-499">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-499">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-500">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-500">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-501">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-501">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-502">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-502">Word</span></span> 
- <span data-ttu-id="9f4a0-503">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-503">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-504">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-504">Excel</span></span>
- <span data-ttu-id="9f4a0-505">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-505">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-506">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-506">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-507">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-507">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="9f4a0-508">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-508">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="9f4a0-509">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-509">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-510">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-510">Outlook</span></span>
- <span data-ttu-id="9f4a0-511">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-511">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-512">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-512">Access</span></span>
- <span data-ttu-id="9f4a0-513">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-513">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-514">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-514">Project</span></span>
- <span data-ttu-id="9f4a0-515">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-515">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="9f4a0-516">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-516">March 8, 2019</span></span> 
<span data-ttu-id="9f4a0-517">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-517">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-518">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-518">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-519">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-519">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="9f4a0-520">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-520">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="9f4a0-521">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-521">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-522">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-522">Getting Started:</span></span>

- <span data-ttu-id="9f4a0-523">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-523">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-524">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-524">Scenarios to Try:</span></span>

- <span data-ttu-id="9f4a0-525">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-525">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="9f4a0-526">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="9f4a0-526">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="9f4a0-527">共同編集</span><span class="sxs-lookup"><span data-stu-id="9f4a0-527">Coauthoring</span></span>

<span data-ttu-id="9f4a0-528">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="9f4a0-528">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="9f4a0-529">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-529">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-530">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-530">Getting Started:</span></span>

<span data-ttu-id="9f4a0-531">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-531">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="9f4a0-532">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-532">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="9f4a0-533">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-533">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-534">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-534">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-535">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-535">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-536">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-536">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-537">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-537">Word</span></span> 
- <span data-ttu-id="9f4a0-538">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-538">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="9f4a0-539">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-539">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="9f4a0-540">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-540">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-541">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-541">Excel</span></span>
- <span data-ttu-id="9f4a0-542">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-542">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-543">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-544">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-544">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-545">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-545">Outlook</span></span>
- <span data-ttu-id="9f4a0-546">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-546">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="9f4a0-547">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-547">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="9f4a0-548">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-548">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-549">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-549">Access</span></span>
- <span data-ttu-id="9f4a0-550">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-550">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="9f4a0-551">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-551">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-552">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-552">Project</span></span>
- <span data-ttu-id="9f4a0-553">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-553">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="9f4a0-554">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-554">March 1, 2019</span></span> 
<span data-ttu-id="9f4a0-555">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-555">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-556">新機能</span><span class="sxs-lookup"><span data-stu-id="9f4a0-556">What's New</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-557">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-557">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="9f4a0-558">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="9f4a0-558">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="9f4a0-559">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-559">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-560">利用するには:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-560">Getting Started:</span></span>

<span data-ttu-id="9f4a0-561">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-561">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="9f4a0-562">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-562">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-563">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-563">Scenarios to Try:</span></span>

<span data-ttu-id="9f4a0-564">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-564">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="9f4a0-565">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-565">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-566">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-566">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-567">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-567">Word</span></span> 
- <span data-ttu-id="9f4a0-568">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-568">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="9f4a0-569">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-569">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-570">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-570">Excel</span></span>
- <span data-ttu-id="9f4a0-571">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-571">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-572">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-572">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-573">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-573">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-574">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-574">Outlook</span></span>
- <span data-ttu-id="9f4a0-575">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-575">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="9f4a0-576">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-576">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="9f4a0-577">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-577">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-578">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-578">Access</span></span>
- <span data-ttu-id="9f4a0-579">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-579">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="9f4a0-580">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-580">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="9f4a0-581">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-581">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-582">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-582">Project</span></span>
- <span data-ttu-id="9f4a0-583">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-583">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="9f4a0-584">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-584">February 15, 2019</span></span> 
<span data-ttu-id="9f4a0-585">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-585">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="9f4a0-586">新機能:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-586">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-587">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-587">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="9f4a0-588">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="9f4a0-588">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="9f4a0-589">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-589">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-590">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-590">Getting Started:</span></span>

- <span data-ttu-id="9f4a0-591">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-591">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="9f4a0-592">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="9f4a0-592">The name must be prefaced with “!!”</span></span> <span data-ttu-id="9f4a0-593">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-593">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="9f4a0-594">名前の先頭に "!!" が付いていない図形の名前変更を続行できます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-594">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="9f4a0-595">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="9f4a0-595">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-596">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-596">Scenarios to Try:</span></span>

- <span data-ttu-id="9f4a0-597">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-597">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="9f4a0-598">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-598">Create a new slide</span></span>
- <span data-ttu-id="9f4a0-599">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-599">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="9f4a0-600">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-600">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="9f4a0-601">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-601">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="9f4a0-602">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="9f4a0-602">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="9f4a0-603">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="9f4a0-603">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-604">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-604">Getting Started:</span></span>

<span data-ttu-id="9f4a0-605">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-605">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-606">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-606">Scenarios to Try:</span></span>

- <span data-ttu-id="9f4a0-607">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-607">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="9f4a0-608">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-608">Duplicate the Slide</span></span>
- <span data-ttu-id="9f4a0-609">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="9f4a0-609">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="9f4a0-610">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-610">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="9f4a0-611">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="9f4a0-611">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="9f4a0-612">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="9f4a0-612">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="9f4a0-613">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-613">Getting Started:</span></span>
<span data-ttu-id="9f4a0-614">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-614">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-615">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-615">Scenarios to Try:</span></span>

- <span data-ttu-id="9f4a0-616">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-616">Insert a Table in a slide</span></span>
- <span data-ttu-id="9f4a0-617">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-617">Duplicate the slide</span></span>
- <span data-ttu-id="9f4a0-618">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="9f4a0-618">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="9f4a0-619">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="9f4a0-619">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="9f4a0-620">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="9f4a0-620">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="9f4a0-621">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="9f4a0-621">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="9f4a0-622">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-622">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="9f4a0-623">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-623">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="9f4a0-625">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-625">Scenarios to Try:</span></span>
- <span data-ttu-id="9f4a0-626">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="9f4a0-626">Switch between accounts</span></span>
- <span data-ttu-id="9f4a0-627">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="9f4a0-627">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="9f4a0-628">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="9f4a0-628">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-629">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-629">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-630">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-630">Word</span></span> 
- <span data-ttu-id="9f4a0-631">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-631">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-632">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-632">Excel</span></span>
- <span data-ttu-id="9f4a0-633">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-633">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="9f4a0-634">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-634">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-635">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-635">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-636">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="9f4a0-636">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-637">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-637">Outlook</span></span>
- <span data-ttu-id="9f4a0-638">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-638">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-639">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-639">Access</span></span>
- <span data-ttu-id="9f4a0-640">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-640">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-641">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-641">Project</span></span>
- <span data-ttu-id="9f4a0-642">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-642">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="9f4a0-643">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-643">February 11, 2019</span></span>
<span data-ttu-id="9f4a0-644">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-644">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-645">主な修正:</span><span class="sxs-lookup"><span data-stu-id="9f4a0-645">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-646">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-646">Word</span></span> 
- <span data-ttu-id="9f4a0-647">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-647">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="9f4a0-648">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-648">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="9f4a0-649">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-649">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-650">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-650">Excel</span></span>
- <span data-ttu-id="9f4a0-651">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="9f4a0-651">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="9f4a0-652">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-652">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-653">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-653">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-654">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-654">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-655">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-655">Outlook</span></span>
- <span data-ttu-id="9f4a0-656">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-656">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-657">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-657">Access</span></span>
- <span data-ttu-id="9f4a0-658">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-658">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-659">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-659">Project</span></span>
- <span data-ttu-id="9f4a0-660">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-660">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="9f4a0-661">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="9f4a0-661">February 1, 2019</span></span> 
<span data-ttu-id="9f4a0-662">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="9f4a0-662">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="9f4a0-663">主な修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-663">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="9f4a0-664">Word</span><span class="sxs-lookup"><span data-stu-id="9f4a0-664">Word</span></span> 
- <span data-ttu-id="9f4a0-665">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-665">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="9f4a0-666">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-666">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="9f4a0-667">Excel</span><span class="sxs-lookup"><span data-stu-id="9f4a0-667">Excel</span></span>
- <span data-ttu-id="9f4a0-668">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-668">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="9f4a0-669">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-669">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="9f4a0-670">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-670">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9f4a0-671">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9f4a0-671">PowerPoint</span></span>
- <span data-ttu-id="9f4a0-672">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-672">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="9f4a0-673">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-673">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="9f4a0-674">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-674">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="9f4a0-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="9f4a0-675">Outlook</span></span>
- <span data-ttu-id="9f4a0-676">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-676">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="9f4a0-677">Access</span><span class="sxs-lookup"><span data-stu-id="9f4a0-677">Access</span></span>
- <span data-ttu-id="9f4a0-678">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="9f4a0-678">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="9f4a0-679">Project</span><span class="sxs-lookup"><span data-stu-id="9f4a0-679">Project</span></span>
- <span data-ttu-id="9f4a0-680">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="9f4a0-680">Various performance and stability fixes</span></span>
