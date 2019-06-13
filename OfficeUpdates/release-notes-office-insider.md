---
title: Office Insider のリリース ノート
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
//: ''
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: 8cc5c8c9b11dabce030095a2d56404856850377a
ms.sourcegitcommit: d8ac84be012031d41fc29caf7e5b0bc32425a523
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/11/2019
ms.locfileid: "34857757"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="eaca5-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="eaca5-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="eaca5-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="eaca5-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="eaca5-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="eaca5-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="eaca5-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="eaca5-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="eaca5-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="eaca5-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります</span><span class="sxs-lookup"><span data-stu-id="eaca5-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="eaca5-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります</span><span class="sxs-lookup"><span data-stu-id="eaca5-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="eaca5-111">Microsoft Teams に関連する既存の Office 365 ProPlus のインストール - 6 月の下旬から、これらの更新プログラムのインストール時に、Microsoft Teams が既存の Office 365 ProPlus (Office 365 Business) のインストールの中に含められます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="eaca5-112">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="eaca5-113">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](https://docs.microsoft.com/ja-JP/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="eaca5-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/en-us/deployoffice/teams-install) for additional information.</span></span>

## <a name="june-7-2019"></a><span data-ttu-id="eaca5-114">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-114">June 7, 2019</span></span>
<span data-ttu-id="eaca5-115">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="eaca5-115">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-116">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-116">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-117">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-117">Word</span></span> 
- <span data-ttu-id="eaca5-118">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-118">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="eaca5-119">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-119">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="eaca5-120">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-120">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-121">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-121">Excel</span></span>
- <span data-ttu-id="eaca5-122">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-122">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="eaca5-123">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-123">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-124">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-124">PowerPoint</span></span>
- <span data-ttu-id="eaca5-125">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-125">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-126">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-126">Outlook</span></span>
- <span data-ttu-id="eaca5-127">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-127">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-128">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-128">Access</span></span>
- <span data-ttu-id="eaca5-129">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-129">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-130">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-130">Project</span></span>
- <span data-ttu-id="eaca5-131">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-131">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="eaca5-132">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-132">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="eaca5-133">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-133">May 31, 2019</span></span>
<span data-ttu-id="eaca5-134">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="eaca5-134">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-135">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-135">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-136">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-136">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="eaca5-137">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-137">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="eaca5-138">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-138">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="eaca5-139">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="eaca5-139">Ink in Your Email!</span></span>

<span data-ttu-id="eaca5-140">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-140">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-141">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-141">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="eaca5-142">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="eaca5-142">Open document links in Word</span></span>

<span data-ttu-id="eaca5-143">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-143">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="eaca5-144">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-144">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="eaca5-145">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="eaca5-145">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-146">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="eaca5-146">Getting Started:</span></span>

<span data-ttu-id="eaca5-147">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="eaca5-147">Feature will default to off.</span></span> <span data-ttu-id="eaca5-148">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-148">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="eaca5-149">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-149">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="eaca5-150">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-150">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="eaca5-151">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="eaca5-151">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="eaca5-152">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-152">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-153">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-153">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-154">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="eaca5-154">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="eaca5-155">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-155">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-156">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-156">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="eaca5-157">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="eaca5-157">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="eaca5-158">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-158">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="eaca5-159">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-159">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="eaca5-160">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="eaca5-160">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-161">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="eaca5-161">Getting Started:</span></span>

<span data-ttu-id="eaca5-162">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="eaca5-162">Feature will default to off.</span></span> <span data-ttu-id="eaca5-163">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-163">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="eaca5-164">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-164">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="eaca5-165">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-165">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="eaca5-166">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="eaca5-166">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="eaca5-167">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-167">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-168">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-168">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-169">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="eaca5-169">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="eaca5-170">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-170">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-171">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-171">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="eaca5-172">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="eaca5-172">Open the workbook in Excel.</span></span>

<span data-ttu-id="eaca5-173">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-173">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="eaca5-174">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-174">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="eaca5-175">詳細については、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="eaca5-175">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-176">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="eaca5-176">Getting Started:</span></span>

<span data-ttu-id="eaca5-177">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="eaca5-177">Feature will default to off.</span></span> <span data-ttu-id="eaca5-178">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-178">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="eaca5-179">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-179">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="eaca5-180">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-180">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="eaca5-181">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="eaca5-181">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="eaca5-182">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-182">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-183">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-183">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-184">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="eaca5-184">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="eaca5-185">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-185">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-186">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-186">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eaca5-187">すべて</span><span class="sxs-lookup"><span data-stu-id="eaca5-187">All</span></span>
- <span data-ttu-id="eaca5-188">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-188">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-189">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-189">Word</span></span> 
- <span data-ttu-id="eaca5-190">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-190">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-191">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-191">Excel</span></span>
- <span data-ttu-id="eaca5-192">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="eaca5-192">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-193">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-193">PowerPoint</span></span>
- <span data-ttu-id="eaca5-194">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-194">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-195">Outlook</span></span>
- <span data-ttu-id="eaca5-196">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="eaca5-196">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="eaca5-197">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-197">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="eaca5-198">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-198">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-199">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-199">Access</span></span>
- <span data-ttu-id="eaca5-200">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-200">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-201">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-201">Project</span></span>
- <span data-ttu-id="eaca5-202">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-202">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="eaca5-203">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-203">May 24, 2019</span></span>
<span data-ttu-id="eaca5-204">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="eaca5-204">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-205">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-205">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="eaca5-206">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="eaca5-206">User Experience Updates</span></span>

<span data-ttu-id="eaca5-207">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-207">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-208">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-208">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eaca5-209">すべて</span><span class="sxs-lookup"><span data-stu-id="eaca5-209">All</span></span>

- <span data-ttu-id="eaca5-210">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-210">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-211">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-211">Word</span></span> 
- <span data-ttu-id="eaca5-212">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-212">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-213">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-213">Excel</span></span>
- <span data-ttu-id="eaca5-214">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-214">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="eaca5-215">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-215">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-216">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-216">PowerPoint</span></span>
- <span data-ttu-id="eaca5-217">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-217">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-218">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-218">Outlook</span></span>
- <span data-ttu-id="eaca5-219">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-219">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-220">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-220">Access</span></span>
- <span data-ttu-id="eaca5-221">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-221">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-222">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-222">Project</span></span>
- <span data-ttu-id="eaca5-223">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-223">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="eaca5-224">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-224">May 17, 2019</span></span>
<span data-ttu-id="eaca5-225">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="eaca5-225">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-226">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-226">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-227">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="eaca5-228">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="eaca5-228">User Experience Updates</span></span>

<span data-ttu-id="eaca5-229">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-229">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-230">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-230">Getting Started:</span></span>

<span data-ttu-id="eaca5-231">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-231">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="eaca5-232">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="eaca5-232">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="eaca5-233">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-233">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-234">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-234">Getting Started:</span></span>

<span data-ttu-id="eaca5-235">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-235">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-236">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-236">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-237">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="eaca5-237">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="eaca5-238">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="eaca5-238">Pick your favorite action</span></span>

<span data-ttu-id="eaca5-239">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="eaca5-239">Don't use Flag and Delete?</span></span> <span data-ttu-id="eaca5-240">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="eaca5-240">How about Archive or Mark as Read?</span></span> <span data-ttu-id="eaca5-241">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-241">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-242">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-242">Getting Started:</span></span>

<span data-ttu-id="eaca5-243">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-243">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="eaca5-244">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="eaca5-244">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-245">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-245">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-246">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-246">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="eaca5-247">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="eaca5-247">Relaxed or tighter layout?</span></span> <span data-ttu-id="eaca5-248">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="eaca5-248">You choose</span></span>

<span data-ttu-id="eaca5-249">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-249">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-250">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-250">Getting Started:</span></span>

<span data-ttu-id="eaca5-251">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-251">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-252">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-252">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-253">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-253">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="eaca5-254">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="eaca5-254">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="eaca5-255">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="eaca5-255">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="eaca5-256">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-256">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-257">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-257">Getting Started:</span></span>

<span data-ttu-id="eaca5-258">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-258">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-259">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-259">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-260">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="eaca5-260">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="eaca5-261">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="eaca5-261">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="eaca5-262">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-262">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="eaca5-263">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-263">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-264">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-264">Getting Started:</span></span>

<span data-ttu-id="eaca5-265">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-265">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-266">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-266">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="eaca5-267">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="eaca5-267">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-268">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-268">Getting Started:</span></span>

<span data-ttu-id="eaca5-269">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-269">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="eaca5-270">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-270">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-271">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-271">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-272">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-272">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="eaca5-273">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-273">Draw an ink stroke.</span></span> <span data-ttu-id="eaca5-274">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-274">Select the Eraser dropdown.</span></span> <span data-ttu-id="eaca5-275">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-275">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="eaca5-276">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-276">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-277">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-277">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eaca5-278">すべて</span><span class="sxs-lookup"><span data-stu-id="eaca5-278">All</span></span> 
- <span data-ttu-id="eaca5-279">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-279">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="eaca5-280">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-280">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-281">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-281">Word</span></span> 
- <span data-ttu-id="eaca5-282">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-282">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-283">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-283">Excel</span></span>
- <span data-ttu-id="eaca5-284">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-284">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="eaca5-285">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-285">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="eaca5-286">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-286">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-287">PowerPoint</span></span>
- <span data-ttu-id="eaca5-288">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-288">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-289">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-289">Outlook</span></span>
- <span data-ttu-id="eaca5-290">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-290">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-291">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-291">Access</span></span>
- <span data-ttu-id="eaca5-292">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-292">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-293">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-293">Project</span></span>
- <span data-ttu-id="eaca5-294">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-294">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="eaca5-295">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="eaca5-295">May 10, 2019</span></span>
<span data-ttu-id="eaca5-296">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="eaca5-296">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-297">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-297">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eaca5-298">すべて</span><span class="sxs-lookup"><span data-stu-id="eaca5-298">All</span></span>
- <span data-ttu-id="eaca5-299">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-299">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-300">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-300">Word</span></span> 
- <span data-ttu-id="eaca5-301">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-301">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-302">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-302">Excel</span></span>
- <span data-ttu-id="eaca5-303">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-303">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-304">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-304">PowerPoint</span></span>
- <span data-ttu-id="eaca5-305">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-305">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-306">Outlook</span></span>
- <span data-ttu-id="eaca5-307">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-307">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-308">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-308">Access</span></span>
- <span data-ttu-id="eaca5-309">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-309">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-310">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-310">Project</span></span>
- <span data-ttu-id="eaca5-311">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-311">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="eaca5-312">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="eaca5-312">May 3, 2019</span></span>
<span data-ttu-id="eaca5-313">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="eaca5-313">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-314">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-314">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="eaca5-315">すべて</span><span class="sxs-lookup"><span data-stu-id="eaca5-315">All</span></span>
- <span data-ttu-id="eaca5-316">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-316">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-317">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-317">Word</span></span> 
- <span data-ttu-id="eaca5-318">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-318">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-319">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-319">Excel</span></span>
- <span data-ttu-id="eaca5-320">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-320">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="eaca5-321">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-321">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-322">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-322">PowerPoint</span></span>
- <span data-ttu-id="eaca5-323">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-323">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-324">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-324">Outlook</span></span>
- <span data-ttu-id="eaca5-325">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-325">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="eaca5-326">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-326">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="eaca5-327">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-327">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-328">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-328">Access</span></span>
- <span data-ttu-id="eaca5-329">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-329">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-330">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-330">Project</span></span>
- <span data-ttu-id="eaca5-331">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-331">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="eaca5-332">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-332">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="eaca5-333">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-333">April 26, 2019</span></span>
<span data-ttu-id="eaca5-334">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="eaca5-334">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-335">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-335">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-336">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-336">Word</span></span> 
- <span data-ttu-id="eaca5-337">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-337">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-338">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-338">Excel</span></span>
- <span data-ttu-id="eaca5-339">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-339">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="eaca5-340">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-340">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-341">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-341">PowerPoint</span></span>
- <span data-ttu-id="eaca5-342">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-342">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-343">Outlook</span></span>
- <span data-ttu-id="eaca5-344">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-344">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-345">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-345">Access</span></span>
- <span data-ttu-id="eaca5-346">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-346">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-347">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-347">Project</span></span>
- <span data-ttu-id="eaca5-348">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-348">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="eaca5-349">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-349">April 19, 2019</span></span>
<span data-ttu-id="eaca5-350">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="eaca5-350">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-351">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-351">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-352">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-352">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="eaca5-353">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="eaca5-353">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="eaca5-354">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="eaca5-354">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="eaca5-355">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="eaca5-355">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="eaca5-356">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-356">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="eaca5-357">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="eaca5-357">Getting Started:</span></span>

- <span data-ttu-id="eaca5-358">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="eaca5-358">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="eaca5-359">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="eaca5-359">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-360">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-360">Scenarios to Try:</span></span>

- <span data-ttu-id="eaca5-361">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-361">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="eaca5-362">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-362">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="eaca5-363">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="eaca5-363">All Applications</span></span>
- <span data-ttu-id="eaca5-364">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-364">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="eaca5-365">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-365">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="eaca5-366">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-366">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-367">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-367">Word</span></span> 
- <span data-ttu-id="eaca5-368">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-368">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="eaca5-369">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-369">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-370">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-370">Excel</span></span>
- <span data-ttu-id="eaca5-371">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-371">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-372">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-372">PowerPoint</span></span>
- <span data-ttu-id="eaca5-373">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-373">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="eaca5-374">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-374">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-375">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-375">Outlook</span></span>
- <span data-ttu-id="eaca5-376">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-376">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="eaca5-377">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-377">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-378">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-378">Access</span></span>
- <span data-ttu-id="eaca5-379">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-379">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="eaca5-380">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-380">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="eaca5-381">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-381">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="eaca5-382">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-382">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-383">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-383">Project</span></span>
- <span data-ttu-id="eaca5-384">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-384">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="eaca5-385">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-385">April 12, 2019</span></span>
<span data-ttu-id="eaca5-386">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="eaca5-386">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-387">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-387">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-388">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-388">Access</span></span>

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a><span data-ttu-id="eaca5-389">Access の新機能 - Microsoft Graph でのデータ コネクタ</span><span class="sxs-lookup"><span data-stu-id="eaca5-389">New in Access - Data Connector to Microsoft Graph</span></span>

<span data-ttu-id="eaca5-390">Graph に保存されているスマート コンテキスト データを活用できるアプリケーションを構築できる Microsoft Graph サービスへのリンクまたはインポート フォーム</span><span class="sxs-lookup"><span data-stu-id="eaca5-390">Link to or import form Microsoft Graph services to build applications that can leverage the smart contextual data stored in the Graph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-391">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-391">Getting Started:</span></span>

<span data-ttu-id="eaca5-392">リボンの [外部データ] タブで、[新しいデータ ソース] をクリックし、[オンライン サービス] メニューの Graph コネクタを検索します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-392">External Data tab in the ribbon, click on New Data Sources and find the new Graph connector in the Online Services menu</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-393">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-393">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-394">ユーザー、グループ、OneDrive のアイテムなど、さまざまな Graph サービスからインポートまたはGraph サービスへリンクします。</span><span class="sxs-lookup"><span data-stu-id="eaca5-394">Import from or link to various Graph services including People, Groups and OneDrive Items.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-395">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-395">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="eaca5-396">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="eaca5-396">All Applications</span></span>
 - <span data-ttu-id="eaca5-397">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-397">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="eaca5-398">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-398">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-399">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-399">Word</span></span> 
- <span data-ttu-id="eaca5-400">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-400">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-401">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-401">Excel</span></span>
- <span data-ttu-id="eaca5-402">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-402">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="eaca5-403">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-403">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-404">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-404">PowerPoint</span></span>
- <span data-ttu-id="eaca5-405">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-405">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-406">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-406">Outlook</span></span>
- <span data-ttu-id="eaca5-407">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-407">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="eaca5-408">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-408">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-409">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-409">Access</span></span>
- <span data-ttu-id="eaca5-410">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-410">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-411">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-411">Project</span></span>
- <span data-ttu-id="eaca5-412">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-412">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="eaca5-413">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="eaca5-413">April 5, 2019</span></span>
<span data-ttu-id="eaca5-414">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="eaca5-414">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-415">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-415">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-416">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-416">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="eaca5-417">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-417">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="eaca5-418">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-418">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-419">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-419">Getting Started:</span></span>

<span data-ttu-id="eaca5-420">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-420">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="eaca5-421">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-421">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-422">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-422">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-423">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-423">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="eaca5-424">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="eaca5-424">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="eaca5-425">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-425">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-426">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-426">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="eaca5-427">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-427">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="eaca5-428">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-428">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="eaca5-429">多くのユーザーがすべて白、またはすべて黒の背景だと閲覧が難しいという課題があったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-429">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-430">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-430">Getting Started:</span></span>

<span data-ttu-id="eaca5-431">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-431">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-432">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-432">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-433">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-433">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-434">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-434">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="eaca5-435">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="eaca5-435">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="eaca5-436">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-436">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-437">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-437">Getting Started:</span></span>

1. <span data-ttu-id="eaca5-438">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="eaca5-438">Open Excel.</span></span>
2. <span data-ttu-id="eaca5-439">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="eaca5-439">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="eaca5-440">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-440">The animated model will play in the editor!</span></span> <span data-ttu-id="eaca5-441">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="eaca5-441">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="eaca5-442">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="eaca5-442">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-443">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-443">Scenarios to Try:</span></span>

1. <span data-ttu-id="eaca5-444">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-444">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="eaca5-445">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="eaca5-445">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="eaca5-446">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-446">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-447">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-447">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="eaca5-448">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="eaca5-448">All Applications</span></span>
- <span data-ttu-id="eaca5-449">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-449">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="eaca5-450">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-450">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="eaca5-451">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-451">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-452">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-452">Word</span></span> 
- <span data-ttu-id="eaca5-453">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-453">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-454">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-454">Excel</span></span>
- <span data-ttu-id="eaca5-455">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="eaca5-455">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="eaca5-456">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-456">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="eaca5-457">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-457">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="eaca5-458">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-458">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="eaca5-459">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-459">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="eaca5-460">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-460">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="eaca5-461">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-461">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="eaca5-462">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-462">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="eaca5-463">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-463">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-464">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-464">PowerPoint</span></span>
- <span data-ttu-id="eaca5-465">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="eaca5-465">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-466">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-466">Outlook</span></span>
- <span data-ttu-id="eaca5-467">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-467">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="eaca5-468">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-468">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="eaca5-469">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-469">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-470">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-470">Access</span></span>
- <span data-ttu-id="eaca5-471">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-471">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-472">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-472">Project</span></span>
- <span data-ttu-id="eaca5-473">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-473">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="eaca5-474">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-474">March 22, 2019</span></span>
<span data-ttu-id="eaca5-475">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="eaca5-475">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-476">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-476">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-477">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-477">Word</span></span> 
- <span data-ttu-id="eaca5-478">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-478">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-479">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-479">Excel</span></span>
- <span data-ttu-id="eaca5-480">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-480">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="eaca5-481">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-481">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="eaca5-482">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-482">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-483">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-483">PowerPoint</span></span>
- <span data-ttu-id="eaca5-484">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-484">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-485">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-485">Outlook</span></span>
- <span data-ttu-id="eaca5-486">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-486">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-487">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-487">Access</span></span>
- <span data-ttu-id="eaca5-488">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-488">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="eaca5-489">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-489">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-490">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-490">Project</span></span>
- <span data-ttu-id="eaca5-491">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-491">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="eaca5-492">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-492">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="eaca5-493">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-493">March 15, 2019</span></span>
<span data-ttu-id="eaca5-494">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="eaca5-494">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-495">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-495">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-496">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-496">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="eaca5-497">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="eaca5-497">Focus mode</span></span>

<span data-ttu-id="eaca5-498">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-498">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="eaca5-499">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="eaca5-499">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-500">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-500">Getting Started:</span></span>

<span data-ttu-id="eaca5-501">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="eaca5-501">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-502">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-502">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-503">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="eaca5-503">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-504">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-504">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-505">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-505">Word</span></span> 
- <span data-ttu-id="eaca5-506">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-506">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-507">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-507">Excel</span></span>
- <span data-ttu-id="eaca5-508">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-508">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-509">PowerPoint</span></span>
- <span data-ttu-id="eaca5-510">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-510">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="eaca5-511">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-511">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="eaca5-512">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-512">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-513">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-513">Outlook</span></span>
- <span data-ttu-id="eaca5-514">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-514">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-515">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-515">Access</span></span>
- <span data-ttu-id="eaca5-516">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-516">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-517">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-517">Project</span></span>
- <span data-ttu-id="eaca5-518">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-518">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="eaca5-519">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-519">March 8, 2019</span></span> 
<span data-ttu-id="eaca5-520">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="eaca5-520">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-521">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-521">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-522">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-522">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="eaca5-523">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="eaca5-523">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="eaca5-524">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-524">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-525">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="eaca5-525">Getting Started:</span></span>

- <span data-ttu-id="eaca5-526">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="eaca5-526">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-527">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-527">Scenarios to Try:</span></span>

- <span data-ttu-id="eaca5-528">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="eaca5-528">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="eaca5-529">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="eaca5-529">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="eaca5-530">共同編集</span><span class="sxs-lookup"><span data-stu-id="eaca5-530">Coauthoring</span></span>

<span data-ttu-id="eaca5-531">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="eaca5-531">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="eaca5-532">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-532">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-533">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-533">Getting Started:</span></span>

<span data-ttu-id="eaca5-534">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="eaca5-534">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="eaca5-535">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="eaca5-535">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="eaca5-536">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="eaca5-536">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-537">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-537">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-538">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="eaca5-538">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-539">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-539">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-540">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-540">Word</span></span> 
- <span data-ttu-id="eaca5-541">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-541">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="eaca5-542">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-542">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="eaca5-543">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-543">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-544">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-544">Excel</span></span>
- <span data-ttu-id="eaca5-545">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-545">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-546">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-546">PowerPoint</span></span>
- <span data-ttu-id="eaca5-547">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-547">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-548">Outlook</span></span>
- <span data-ttu-id="eaca5-549">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-549">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="eaca5-550">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-550">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="eaca5-551">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-551">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-552">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-552">Access</span></span>
- <span data-ttu-id="eaca5-553">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-553">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="eaca5-554">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-554">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-555">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-555">Project</span></span>
- <span data-ttu-id="eaca5-556">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-556">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="eaca5-557">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-557">March 1, 2019</span></span> 
<span data-ttu-id="eaca5-558">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="eaca5-558">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-559">新機能</span><span class="sxs-lookup"><span data-stu-id="eaca5-559">What's New</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-560">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-560">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="eaca5-561">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="eaca5-561">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="eaca5-562">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-562">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-563">利用するには:</span><span class="sxs-lookup"><span data-stu-id="eaca5-563">Getting Started:</span></span>

<span data-ttu-id="eaca5-564">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-564">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="eaca5-565">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-565">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-566">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-566">Scenarios to Try:</span></span>

<span data-ttu-id="eaca5-567">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-567">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="eaca5-568">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="eaca5-568">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-569">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-569">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-570">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-570">Word</span></span> 
- <span data-ttu-id="eaca5-571">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-571">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="eaca5-572">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-572">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-573">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-573">Excel</span></span>
- <span data-ttu-id="eaca5-574">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-574">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-575">PowerPoint</span></span>
- <span data-ttu-id="eaca5-576">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-576">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-577">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-577">Outlook</span></span>
- <span data-ttu-id="eaca5-578">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-578">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="eaca5-579">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-579">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="eaca5-580">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-580">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-581">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-581">Access</span></span>
- <span data-ttu-id="eaca5-582">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-582">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="eaca5-583">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-583">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="eaca5-584">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-584">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-585">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-585">Project</span></span>
- <span data-ttu-id="eaca5-586">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-586">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="eaca5-587">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-587">February 15, 2019</span></span> 
<span data-ttu-id="eaca5-588">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="eaca5-588">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="eaca5-589">新機能:</span><span class="sxs-lookup"><span data-stu-id="eaca5-589">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-590">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="eaca5-591">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="eaca5-591">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="eaca5-592">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="eaca5-592">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-593">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="eaca5-593">Getting Started:</span></span>

- <span data-ttu-id="eaca5-594">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-594">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="eaca5-595">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="eaca5-595">The name must be prefaced with “!!”</span></span> <span data-ttu-id="eaca5-596">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="eaca5-596">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="eaca5-597">名前の先頭に "!!" が付いていない図形の名前変更を続行できます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-597">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="eaca5-598">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="eaca5-598">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-599">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-599">Scenarios to Try:</span></span>

- <span data-ttu-id="eaca5-600">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="eaca5-600">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="eaca5-601">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="eaca5-601">Create a new slide</span></span>
- <span data-ttu-id="eaca5-602">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="eaca5-602">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="eaca5-603">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="eaca5-603">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="eaca5-604">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="eaca5-604">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="eaca5-605">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="eaca5-605">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="eaca5-606">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="eaca5-606">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-607">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="eaca5-607">Getting Started:</span></span>

<span data-ttu-id="eaca5-608">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="eaca5-608">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-609">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-609">Scenarios to Try:</span></span>

- <span data-ttu-id="eaca5-610">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="eaca5-610">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="eaca5-611">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="eaca5-611">Duplicate the Slide</span></span>
- <span data-ttu-id="eaca5-612">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="eaca5-612">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="eaca5-613">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="eaca5-613">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="eaca5-614">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="eaca5-614">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="eaca5-615">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="eaca5-615">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="eaca5-616">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="eaca5-616">Getting Started:</span></span>
<span data-ttu-id="eaca5-617">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="eaca5-617">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-618">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-618">Scenarios to Try:</span></span>

- <span data-ttu-id="eaca5-619">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="eaca5-619">Insert a Table in a slide</span></span>
- <span data-ttu-id="eaca5-620">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="eaca5-620">Duplicate the slide</span></span>
- <span data-ttu-id="eaca5-621">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="eaca5-621">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="eaca5-622">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="eaca5-622">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="eaca5-623">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="eaca5-623">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="eaca5-624">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="eaca5-624">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="eaca5-625">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="eaca5-625">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="eaca5-626">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-626">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="eaca5-628">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="eaca5-628">Scenarios to Try:</span></span>
- <span data-ttu-id="eaca5-629">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="eaca5-629">Switch between accounts</span></span>
- <span data-ttu-id="eaca5-630">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="eaca5-630">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="eaca5-631">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="eaca5-631">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="eaca5-632">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-632">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-633">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-633">Word</span></span> 
- <span data-ttu-id="eaca5-634">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-634">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-635">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-635">Excel</span></span>
- <span data-ttu-id="eaca5-636">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-636">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="eaca5-637">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-637">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-638">PowerPoint</span></span>
- <span data-ttu-id="eaca5-639">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="eaca5-639">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-640">Outlook</span></span>
- <span data-ttu-id="eaca5-641">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-641">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-642">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-642">Access</span></span>
- <span data-ttu-id="eaca5-643">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-643">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-644">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-644">Project</span></span>
- <span data-ttu-id="eaca5-645">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-645">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="eaca5-646">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-646">February 11, 2019</span></span>
<span data-ttu-id="eaca5-647">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="eaca5-647">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="eaca5-648">主な修正:</span><span class="sxs-lookup"><span data-stu-id="eaca5-648">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-649">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-649">Word</span></span> 
- <span data-ttu-id="eaca5-650">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-650">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="eaca5-651">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-651">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="eaca5-652">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-652">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-653">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-653">Excel</span></span>
- <span data-ttu-id="eaca5-654">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="eaca5-654">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="eaca5-655">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-655">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-656">PowerPoint</span></span>
- <span data-ttu-id="eaca5-657">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-657">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-658">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-658">Outlook</span></span>
- <span data-ttu-id="eaca5-659">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-659">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-660">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-660">Access</span></span>
- <span data-ttu-id="eaca5-661">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-661">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-662">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-662">Project</span></span>
- <span data-ttu-id="eaca5-663">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-663">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="eaca5-664">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="eaca5-664">February 1, 2019</span></span> 
<span data-ttu-id="eaca5-665">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="eaca5-665">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="eaca5-666">主な修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-666">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="eaca5-667">Word</span><span class="sxs-lookup"><span data-stu-id="eaca5-667">Word</span></span> 
- <span data-ttu-id="eaca5-668">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-668">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="eaca5-669">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-669">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="eaca5-670">Excel</span><span class="sxs-lookup"><span data-stu-id="eaca5-670">Excel</span></span>
- <span data-ttu-id="eaca5-671">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-671">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="eaca5-672">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-672">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="eaca5-673">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-673">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="eaca5-674">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="eaca5-674">PowerPoint</span></span>
- <span data-ttu-id="eaca5-675">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-675">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="eaca5-676">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-676">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="eaca5-677">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-677">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="eaca5-678">Outlook</span><span class="sxs-lookup"><span data-stu-id="eaca5-678">Outlook</span></span>
- <span data-ttu-id="eaca5-679">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-679">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="eaca5-680">Access</span><span class="sxs-lookup"><span data-stu-id="eaca5-680">Access</span></span>
- <span data-ttu-id="eaca5-681">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="eaca5-681">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="eaca5-682">Project</span><span class="sxs-lookup"><span data-stu-id="eaca5-682">Project</span></span>
- <span data-ttu-id="eaca5-683">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="eaca5-683">Various performance and stability fixes</span></span>
