---
title: Office Insider のリリース ノート
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 6/14/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: 8a2bf54f60b7d35a0f3b2f023e0100ff65d09ed2
ms.sourcegitcommit: 288bea365b4c0265fb9ff182b19ff4eb30b4c7d7
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/14/2019
ms.locfileid: "34948793"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="2eb87-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="2eb87-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="2eb87-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="2eb87-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="2eb87-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="2eb87-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="2eb87-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="2eb87-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="2eb87-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="2eb87-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります</span><span class="sxs-lookup"><span data-stu-id="2eb87-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="2eb87-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります</span><span class="sxs-lookup"><span data-stu-id="2eb87-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="2eb87-111">Microsoft Teams に関連する既存の Office 365 ProPlus のインストール - 6 月の下旬から、これらの更新プログラムのインストール時に、Microsoft Teams が既存の Office 365 ProPlus (Office 365 Business) のインストールの中に含められます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="2eb87-112">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="2eb87-113">追加情報については、「[Office 365 ProPlus で Microsoft Teams を展開する](https://docs.microsoft.com/ja-JP/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2eb87-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/en-us/deployoffice/teams-install) for additional information.</span></span>

## <a name="june-14-2019"></a><span data-ttu-id="2eb87-114">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-114">June 14, 2019</span></span>
<span data-ttu-id="2eb87-115">バージョン 1907 (ビルド 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="2eb87-115">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-116">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-116">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-117">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-117">Word</span></span> 
- <span data-ttu-id="2eb87-118">OneDrive に保存しているときにユーザーがサインインするのを妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-118">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="2eb87-119">アクセス制限モード中にユーザーによる SharePoint のプロパティの変更が妨げられていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-119">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="2eb87-120">余白を調整しているときにヘッダーやフッターの内容が変更されてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-120">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="2eb87-121">Web ビューに切り替えているときに書式設定が崩れてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-121">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="2eb87-122">SharePoint で開いたときにユーザーによるカスタム フィールドの使用を妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-122">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-123">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-123">Excel</span></span>
- <span data-ttu-id="2eb87-124">フィルター処理された行を削除するときのパフォーマンスの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-124">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="2eb87-125">時々、保護ビューでマウスをちらつかせる原因になっていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-125">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="2eb87-126">系列を削除しているときにクラッシュを引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-126">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="2eb87-127">利用できなかった場合に一部のユーザーがバージョン履歴を追加するオプションを使用していたところの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-127">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="2eb87-128">スプレッドシート比較ツールを使用しているときに例外を引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-128">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-129">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-129">PowerPoint</span></span>
- <span data-ttu-id="2eb87-130">SharePoint へのリンクをクリックしたときにクラッシュを発生させていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-130">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="2eb87-131">ユーザーが Surface ペンを使用して入力しているのに、次のページに切り替わってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-131">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-132">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-132">Outlook</span></span>
- <span data-ttu-id="2eb87-133">一部の宛先フィールドが通常より大きくなってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-133">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-134">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-134">Access</span></span>
- <span data-ttu-id="2eb87-135">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-135">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-136">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-136">Project</span></span>
- <span data-ttu-id="2eb87-137">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-137">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="2eb87-138">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-138">June 7, 2019</span></span>
<span data-ttu-id="2eb87-139">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="2eb87-139">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-140">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-140">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-141">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-141">Word</span></span> 
- <span data-ttu-id="2eb87-142">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-142">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="2eb87-143">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-143">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="2eb87-144">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-144">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-145">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-145">Excel</span></span>
- <span data-ttu-id="2eb87-146">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-146">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="2eb87-147">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-147">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-148">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-148">PowerPoint</span></span>
- <span data-ttu-id="2eb87-149">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-149">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-150">Outlook</span></span>
- <span data-ttu-id="2eb87-151">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-151">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-152">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-152">Access</span></span>
- <span data-ttu-id="2eb87-153">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-153">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-154">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-154">Project</span></span>
- <span data-ttu-id="2eb87-155">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-155">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="2eb87-156">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-156">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="2eb87-157">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-157">May 31, 2019</span></span>
<span data-ttu-id="2eb87-158">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="2eb87-158">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-159">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-159">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-160">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-160">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="2eb87-161">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-161">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="2eb87-162">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-162">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="2eb87-163">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="2eb87-163">Ink in Your Email!</span></span>

<span data-ttu-id="2eb87-164">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-164">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-165">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-165">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="2eb87-166">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="2eb87-166">Open document links in Word</span></span>

<span data-ttu-id="2eb87-167">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-167">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="2eb87-168">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-168">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2eb87-169">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2eb87-169">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-170">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="2eb87-170">Getting Started:</span></span>

<span data-ttu-id="2eb87-171">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="2eb87-171">Feature will default to off.</span></span> <span data-ttu-id="2eb87-172">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-172">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2eb87-173">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-173">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2eb87-174">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-174">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2eb87-175">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="2eb87-175">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2eb87-176">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-176">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-177">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-177">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-178">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="2eb87-178">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2eb87-179">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-179">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-180">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="2eb87-181">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="2eb87-181">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="2eb87-182">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-182">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="2eb87-183">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-183">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2eb87-184">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2eb87-184">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-185">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="2eb87-185">Getting Started:</span></span>

<span data-ttu-id="2eb87-186">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="2eb87-186">Feature will default to off.</span></span> <span data-ttu-id="2eb87-187">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-187">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2eb87-188">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-188">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2eb87-189">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-189">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2eb87-190">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="2eb87-190">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2eb87-191">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-191">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-192">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-192">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-193">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="2eb87-193">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2eb87-194">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-194">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-195">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-195">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="2eb87-196">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="2eb87-196">Open the workbook in Excel.</span></span>

<span data-ttu-id="2eb87-197">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-197">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="2eb87-198">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-198">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="2eb87-199">詳細については、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="2eb87-199">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-200">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="2eb87-200">Getting Started:</span></span>

<span data-ttu-id="2eb87-201">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="2eb87-201">Feature will default to off.</span></span> <span data-ttu-id="2eb87-202">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-202">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="2eb87-203">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-203">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="2eb87-204">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-204">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="2eb87-205">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="2eb87-205">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="2eb87-206">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-206">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-207">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-207">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-208">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="2eb87-208">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="2eb87-209">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-209">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-210">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-210">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2eb87-211">すべて</span><span class="sxs-lookup"><span data-stu-id="2eb87-211">All</span></span>
- <span data-ttu-id="2eb87-212">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-212">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-213">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-213">Word</span></span> 
- <span data-ttu-id="2eb87-214">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-214">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-215">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-215">Excel</span></span>
- <span data-ttu-id="2eb87-216">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-216">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-217">PowerPoint</span></span>
- <span data-ttu-id="2eb87-218">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-218">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-219">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-219">Outlook</span></span>
- <span data-ttu-id="2eb87-220">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-220">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="2eb87-221">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-221">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="2eb87-222">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-222">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-223">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-223">Access</span></span>
- <span data-ttu-id="2eb87-224">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-224">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-225">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-225">Project</span></span>
- <span data-ttu-id="2eb87-226">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-226">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="2eb87-227">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-227">May 24, 2019</span></span>
<span data-ttu-id="2eb87-228">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="2eb87-228">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-229">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-229">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="2eb87-230">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="2eb87-230">User Experience Updates</span></span>

<span data-ttu-id="2eb87-231">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-231">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-232">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-232">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2eb87-233">すべて</span><span class="sxs-lookup"><span data-stu-id="2eb87-233">All</span></span>

- <span data-ttu-id="2eb87-234">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-234">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-235">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-235">Word</span></span> 
- <span data-ttu-id="2eb87-236">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-236">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-237">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-237">Excel</span></span>
- <span data-ttu-id="2eb87-238">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-238">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="2eb87-239">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-239">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-240">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-240">PowerPoint</span></span>
- <span data-ttu-id="2eb87-241">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-241">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-242">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-242">Outlook</span></span>
- <span data-ttu-id="2eb87-243">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-243">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-244">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-244">Access</span></span>
- <span data-ttu-id="2eb87-245">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-245">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-246">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-246">Project</span></span>
- <span data-ttu-id="2eb87-247">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-247">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="2eb87-248">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-248">May 17, 2019</span></span>
<span data-ttu-id="2eb87-249">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="2eb87-249">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-250">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-250">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-251">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-251">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="2eb87-252">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="2eb87-252">User Experience Updates</span></span>

<span data-ttu-id="2eb87-253">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-253">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-254">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-254">Getting Started:</span></span>

<span data-ttu-id="2eb87-255">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-255">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="2eb87-256">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="2eb87-256">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="2eb87-257">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-257">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-258">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-258">Getting Started:</span></span>

<span data-ttu-id="2eb87-259">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-259">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-260">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-260">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-261">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="2eb87-261">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="2eb87-262">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="2eb87-262">Pick your favorite action</span></span>

<span data-ttu-id="2eb87-263">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="2eb87-263">Don't use Flag and Delete?</span></span> <span data-ttu-id="2eb87-264">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="2eb87-264">How about Archive or Mark as Read?</span></span> <span data-ttu-id="2eb87-265">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-265">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-266">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-266">Getting Started:</span></span>

<span data-ttu-id="2eb87-267">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-267">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="2eb87-268">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="2eb87-268">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-269">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-269">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-270">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-270">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="2eb87-271">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="2eb87-271">Relaxed or tighter layout?</span></span> <span data-ttu-id="2eb87-272">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="2eb87-272">You choose</span></span>

<span data-ttu-id="2eb87-273">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-273">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-274">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-274">Getting Started:</span></span>

<span data-ttu-id="2eb87-275">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-275">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-276">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-276">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-277">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-277">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="2eb87-278">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="2eb87-278">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="2eb87-279">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="2eb87-279">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="2eb87-280">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-280">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-281">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-281">Getting Started:</span></span>

<span data-ttu-id="2eb87-282">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-282">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-283">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-283">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-284">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="2eb87-284">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="2eb87-285">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-285">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="2eb87-286">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-286">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="2eb87-287">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-287">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-288">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-288">Getting Started:</span></span>

<span data-ttu-id="2eb87-289">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-289">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-290">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-290">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="2eb87-291">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="2eb87-291">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-292">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-292">Getting Started:</span></span>

<span data-ttu-id="2eb87-293">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-293">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="2eb87-294">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-294">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-295">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-295">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-296">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-296">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="2eb87-297">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-297">Draw an ink stroke.</span></span> <span data-ttu-id="2eb87-298">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-298">Select the Eraser dropdown.</span></span> <span data-ttu-id="2eb87-299">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-299">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="2eb87-300">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-300">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-301">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-301">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2eb87-302">すべて</span><span class="sxs-lookup"><span data-stu-id="2eb87-302">All</span></span> 
- <span data-ttu-id="2eb87-303">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-303">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="2eb87-304">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-304">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-305">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-305">Word</span></span> 
- <span data-ttu-id="2eb87-306">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-306">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-307">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-307">Excel</span></span>
- <span data-ttu-id="2eb87-308">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-308">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="2eb87-309">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-309">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="2eb87-310">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-310">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-311">PowerPoint</span></span>
- <span data-ttu-id="2eb87-312">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-312">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-313">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-313">Outlook</span></span>
- <span data-ttu-id="2eb87-314">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-314">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-315">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-315">Access</span></span>
- <span data-ttu-id="2eb87-316">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-316">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-317">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-317">Project</span></span>
- <span data-ttu-id="2eb87-318">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-318">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="2eb87-319">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="2eb87-319">May 10, 2019</span></span>
<span data-ttu-id="2eb87-320">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="2eb87-320">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-321">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-321">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2eb87-322">すべて</span><span class="sxs-lookup"><span data-stu-id="2eb87-322">All</span></span>
- <span data-ttu-id="2eb87-323">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-323">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-324">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-324">Word</span></span> 
- <span data-ttu-id="2eb87-325">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-325">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-326">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-326">Excel</span></span>
- <span data-ttu-id="2eb87-327">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-327">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-328">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-328">PowerPoint</span></span>
- <span data-ttu-id="2eb87-329">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-329">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-330">Outlook</span></span>
- <span data-ttu-id="2eb87-331">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-331">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-332">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-332">Access</span></span>
- <span data-ttu-id="2eb87-333">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-333">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-334">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-334">Project</span></span>
- <span data-ttu-id="2eb87-335">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-335">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="2eb87-336">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="2eb87-336">May 3, 2019</span></span>
<span data-ttu-id="2eb87-337">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="2eb87-337">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-338">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-338">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="2eb87-339">すべて</span><span class="sxs-lookup"><span data-stu-id="2eb87-339">All</span></span>
- <span data-ttu-id="2eb87-340">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-340">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-341">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-341">Word</span></span> 
- <span data-ttu-id="2eb87-342">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-342">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-343">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-343">Excel</span></span>
- <span data-ttu-id="2eb87-344">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-344">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="2eb87-345">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-345">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-346">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-346">PowerPoint</span></span>
- <span data-ttu-id="2eb87-347">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-347">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-348">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-348">Outlook</span></span>
- <span data-ttu-id="2eb87-349">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-349">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="2eb87-350">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-350">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="2eb87-351">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-351">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-352">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-352">Access</span></span>
- <span data-ttu-id="2eb87-353">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-353">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-354">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-354">Project</span></span>
- <span data-ttu-id="2eb87-355">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-355">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="2eb87-356">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-356">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="2eb87-357">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-357">April 26, 2019</span></span>
<span data-ttu-id="2eb87-358">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="2eb87-358">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-359">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-359">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-360">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-360">Word</span></span> 
- <span data-ttu-id="2eb87-361">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-361">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-362">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-362">Excel</span></span>
- <span data-ttu-id="2eb87-363">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-363">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="2eb87-364">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-364">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-365">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-365">PowerPoint</span></span>
- <span data-ttu-id="2eb87-366">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-366">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-367">Outlook</span></span>
- <span data-ttu-id="2eb87-368">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-368">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-369">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-369">Access</span></span>
- <span data-ttu-id="2eb87-370">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-370">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-371">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-371">Project</span></span>
- <span data-ttu-id="2eb87-372">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-372">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="2eb87-373">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-373">April 19, 2019</span></span>
<span data-ttu-id="2eb87-374">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="2eb87-374">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-375">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-375">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-376">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-376">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="2eb87-377">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="2eb87-377">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="2eb87-378">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="2eb87-378">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="2eb87-379">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="2eb87-379">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="2eb87-380">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-380">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="2eb87-381">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="2eb87-381">Getting Started:</span></span>

- <span data-ttu-id="2eb87-382">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="2eb87-382">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="2eb87-383">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="2eb87-383">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-384">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-384">Scenarios to Try:</span></span>

- <span data-ttu-id="2eb87-385">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-385">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="2eb87-386">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-386">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2eb87-387">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="2eb87-387">All Applications</span></span>
- <span data-ttu-id="2eb87-388">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-388">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="2eb87-389">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-389">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="2eb87-390">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-390">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-391">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-391">Word</span></span> 
- <span data-ttu-id="2eb87-392">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-392">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="2eb87-393">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-393">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-394">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-394">Excel</span></span>
- <span data-ttu-id="2eb87-395">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-395">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-396">PowerPoint</span></span>
- <span data-ttu-id="2eb87-397">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-397">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="2eb87-398">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-398">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-399">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-399">Outlook</span></span>
- <span data-ttu-id="2eb87-400">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-400">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="2eb87-401">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-401">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-402">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-402">Access</span></span>
- <span data-ttu-id="2eb87-403">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-403">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="2eb87-404">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-404">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="2eb87-405">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-405">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="2eb87-406">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-406">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-407">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-407">Project</span></span>
- <span data-ttu-id="2eb87-408">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-408">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="2eb87-409">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-409">April 12, 2019</span></span>
<span data-ttu-id="2eb87-410">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="2eb87-410">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-411">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-411">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-412">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-412">Access</span></span>

#### <a name="new-in-access---data-connector-to-microsoft-graph"></a><span data-ttu-id="2eb87-413">Access の新機能 - Microsoft Graph でのデータ コネクタ</span><span class="sxs-lookup"><span data-stu-id="2eb87-413">New in Access - Data Connector to Microsoft Graph</span></span>

<span data-ttu-id="2eb87-414">Graph に保存されているスマート コンテキスト データを活用できるアプリケーションを構築できる Microsoft Graph サービスへのリンクまたはインポート フォーム</span><span class="sxs-lookup"><span data-stu-id="2eb87-414">Link to or import form Microsoft Graph services to build applications that can leverage the smart contextual data stored in the Graph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-415">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-415">Getting Started:</span></span>

<span data-ttu-id="2eb87-416">リボンの [外部データ] タブで、[新しいデータ ソース] をクリックし、[オンライン サービス] メニューの Graph コネクタを検索します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-416">External Data tab in the ribbon, click on New Data Sources and find the new Graph connector in the Online Services menu</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-417">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-417">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-418">ユーザー、グループ、OneDrive のアイテムなど、さまざまな Graph サービスからインポートまたはGraph サービスへリンクします。</span><span class="sxs-lookup"><span data-stu-id="2eb87-418">Import from or link to various Graph services including People, Groups and OneDrive Items.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-419">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-419">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2eb87-420">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="2eb87-420">All Applications</span></span>
 - <span data-ttu-id="2eb87-421">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-421">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="2eb87-422">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-422">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-423">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-423">Word</span></span> 
- <span data-ttu-id="2eb87-424">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-424">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-425">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-425">Excel</span></span>
- <span data-ttu-id="2eb87-426">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-426">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="2eb87-427">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-427">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-428">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-428">PowerPoint</span></span>
- <span data-ttu-id="2eb87-429">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-429">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-430">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-430">Outlook</span></span>
- <span data-ttu-id="2eb87-431">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-431">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="2eb87-432">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-432">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-433">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-433">Access</span></span>
- <span data-ttu-id="2eb87-434">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-434">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-435">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-435">Project</span></span>
- <span data-ttu-id="2eb87-436">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-436">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="2eb87-437">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="2eb87-437">April 5, 2019</span></span>
<span data-ttu-id="2eb87-438">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="2eb87-438">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-439">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-439">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-440">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-440">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="2eb87-441">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-441">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="2eb87-442">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-442">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-443">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-443">Getting Started:</span></span>

<span data-ttu-id="2eb87-444">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-444">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="2eb87-445">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-445">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-446">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-446">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-447">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-447">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="2eb87-448">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="2eb87-448">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="2eb87-449">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-449">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-450">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-450">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="2eb87-451">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-451">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="2eb87-452">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-452">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="2eb87-453">多くのユーザーがすべて白、またはすべて黒の背景だと閲覧が難しいという課題があったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-453">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-454">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-454">Getting Started:</span></span>

<span data-ttu-id="2eb87-455">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-455">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-456">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-456">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-457">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-457">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-458">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-458">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="2eb87-459">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="2eb87-459">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="2eb87-460">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-460">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-461">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-461">Getting Started:</span></span>

1. <span data-ttu-id="2eb87-462">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="2eb87-462">Open Excel.</span></span>
2. <span data-ttu-id="2eb87-463">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="2eb87-463">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="2eb87-464">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-464">The animated model will play in the editor!</span></span> <span data-ttu-id="2eb87-465">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="2eb87-465">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="2eb87-466">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="2eb87-466">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-467">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-467">Scenarios to Try:</span></span>

1. <span data-ttu-id="2eb87-468">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-468">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="2eb87-469">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2eb87-469">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="2eb87-470">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-470">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-471">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-471">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="2eb87-472">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="2eb87-472">All Applications</span></span>
- <span data-ttu-id="2eb87-473">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-473">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="2eb87-474">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-474">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="2eb87-475">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-475">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-476">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-476">Word</span></span> 
- <span data-ttu-id="2eb87-477">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-477">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-478">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-478">Excel</span></span>
- <span data-ttu-id="2eb87-479">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-479">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="2eb87-480">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-480">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="2eb87-481">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-481">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="2eb87-482">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-482">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="2eb87-483">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-483">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="2eb87-484">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-484">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="2eb87-485">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-485">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="2eb87-486">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-486">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="2eb87-487">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-487">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-488">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-488">PowerPoint</span></span>
- <span data-ttu-id="2eb87-489">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="2eb87-489">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-490">Outlook</span></span>
- <span data-ttu-id="2eb87-491">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-491">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="2eb87-492">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-492">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="2eb87-493">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-493">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-494">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-494">Access</span></span>
- <span data-ttu-id="2eb87-495">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-495">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-496">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-496">Project</span></span>
- <span data-ttu-id="2eb87-497">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-497">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="2eb87-498">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-498">March 22, 2019</span></span>
<span data-ttu-id="2eb87-499">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="2eb87-499">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-500">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-500">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-501">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-501">Word</span></span> 
- <span data-ttu-id="2eb87-502">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-502">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-503">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-503">Excel</span></span>
- <span data-ttu-id="2eb87-504">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-504">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="2eb87-505">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-505">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="2eb87-506">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-506">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-507">PowerPoint</span></span>
- <span data-ttu-id="2eb87-508">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-508">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-509">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-509">Outlook</span></span>
- <span data-ttu-id="2eb87-510">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-510">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-511">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-511">Access</span></span>
- <span data-ttu-id="2eb87-512">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-512">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="2eb87-513">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-513">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-514">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-514">Project</span></span>
- <span data-ttu-id="2eb87-515">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-515">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="2eb87-516">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-516">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="2eb87-517">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-517">March 15, 2019</span></span>
<span data-ttu-id="2eb87-518">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="2eb87-518">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-519">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-519">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-520">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-520">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="2eb87-521">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="2eb87-521">Focus mode</span></span>

<span data-ttu-id="2eb87-522">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-522">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="2eb87-523">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="2eb87-523">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-524">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-524">Getting Started:</span></span>

<span data-ttu-id="2eb87-525">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="2eb87-525">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-526">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-526">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-527">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="2eb87-527">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-528">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-528">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-529">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-529">Word</span></span> 
- <span data-ttu-id="2eb87-530">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-530">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-531">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-531">Excel</span></span>
- <span data-ttu-id="2eb87-532">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-532">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-533">PowerPoint</span></span>
- <span data-ttu-id="2eb87-534">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-534">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="2eb87-535">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-535">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="2eb87-536">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-536">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-537">Outlook</span></span>
- <span data-ttu-id="2eb87-538">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-538">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-539">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-539">Access</span></span>
- <span data-ttu-id="2eb87-540">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-540">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-541">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-541">Project</span></span>
- <span data-ttu-id="2eb87-542">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-542">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="2eb87-543">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-543">March 8, 2019</span></span> 
<span data-ttu-id="2eb87-544">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="2eb87-544">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-545">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-545">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-546">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-546">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="2eb87-547">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="2eb87-547">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="2eb87-548">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-548">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-549">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="2eb87-549">Getting Started:</span></span>

- <span data-ttu-id="2eb87-550">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="2eb87-550">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-551">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-551">Scenarios to Try:</span></span>

- <span data-ttu-id="2eb87-552">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="2eb87-552">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="2eb87-553">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="2eb87-553">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="2eb87-554">共同編集</span><span class="sxs-lookup"><span data-stu-id="2eb87-554">Coauthoring</span></span>

<span data-ttu-id="2eb87-555">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="2eb87-555">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="2eb87-556">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-556">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-557">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-557">Getting Started:</span></span>

<span data-ttu-id="2eb87-558">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="2eb87-558">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="2eb87-559">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="2eb87-559">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="2eb87-560">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="2eb87-560">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-561">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-561">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-562">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="2eb87-562">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-563">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-563">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-564">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-564">Word</span></span> 
- <span data-ttu-id="2eb87-565">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-565">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="2eb87-566">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-566">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="2eb87-567">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-567">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-568">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-568">Excel</span></span>
- <span data-ttu-id="2eb87-569">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-569">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-570">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-570">PowerPoint</span></span>
- <span data-ttu-id="2eb87-571">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-571">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-572">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-572">Outlook</span></span>
- <span data-ttu-id="2eb87-573">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-573">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="2eb87-574">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-574">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="2eb87-575">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-575">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-576">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-576">Access</span></span>
- <span data-ttu-id="2eb87-577">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-577">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="2eb87-578">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-578">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-579">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-579">Project</span></span>
- <span data-ttu-id="2eb87-580">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-580">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="2eb87-581">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-581">March 1, 2019</span></span> 
<span data-ttu-id="2eb87-582">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="2eb87-582">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-583">新機能</span><span class="sxs-lookup"><span data-stu-id="2eb87-583">What's New</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-584">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-584">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="2eb87-585">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="2eb87-585">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="2eb87-586">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-586">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-587">利用するには:</span><span class="sxs-lookup"><span data-stu-id="2eb87-587">Getting Started:</span></span>

<span data-ttu-id="2eb87-588">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-588">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="2eb87-589">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-589">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-590">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-590">Scenarios to Try:</span></span>

<span data-ttu-id="2eb87-591">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-591">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="2eb87-592">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="2eb87-592">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-593">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-593">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-594">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-594">Word</span></span> 
- <span data-ttu-id="2eb87-595">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-595">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="2eb87-596">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-596">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-597">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-597">Excel</span></span>
- <span data-ttu-id="2eb87-598">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-598">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-599">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-599">PowerPoint</span></span>
- <span data-ttu-id="2eb87-600">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-600">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-601">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-601">Outlook</span></span>
- <span data-ttu-id="2eb87-602">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-602">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="2eb87-603">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-603">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="2eb87-604">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-604">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-605">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-605">Access</span></span>
- <span data-ttu-id="2eb87-606">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-606">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="2eb87-607">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-607">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="2eb87-608">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-608">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-609">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-609">Project</span></span>
- <span data-ttu-id="2eb87-610">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-610">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="2eb87-611">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-611">February 15, 2019</span></span> 
<span data-ttu-id="2eb87-612">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="2eb87-612">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="2eb87-613">新機能:</span><span class="sxs-lookup"><span data-stu-id="2eb87-613">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-614">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-614">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="2eb87-615">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="2eb87-615">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="2eb87-616">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="2eb87-616">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-617">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="2eb87-617">Getting Started:</span></span>

- <span data-ttu-id="2eb87-618">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-618">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="2eb87-619">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="2eb87-619">The name must be prefaced with “!!”</span></span> <span data-ttu-id="2eb87-620">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="2eb87-620">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="2eb87-621">名前の先頭に "!!" が付いていない図形の名前変更を続行できます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-621">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="2eb87-622">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="2eb87-622">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-623">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-623">Scenarios to Try:</span></span>

- <span data-ttu-id="2eb87-624">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="2eb87-624">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="2eb87-625">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="2eb87-625">Create a new slide</span></span>
- <span data-ttu-id="2eb87-626">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="2eb87-626">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="2eb87-627">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="2eb87-627">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="2eb87-628">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="2eb87-628">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="2eb87-629">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="2eb87-629">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="2eb87-630">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="2eb87-630">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-631">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="2eb87-631">Getting Started:</span></span>

<span data-ttu-id="2eb87-632">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="2eb87-632">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-633">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-633">Scenarios to Try:</span></span>

- <span data-ttu-id="2eb87-634">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="2eb87-634">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="2eb87-635">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="2eb87-635">Duplicate the Slide</span></span>
- <span data-ttu-id="2eb87-636">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="2eb87-636">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="2eb87-637">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="2eb87-637">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="2eb87-638">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="2eb87-638">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="2eb87-639">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="2eb87-639">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="2eb87-640">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="2eb87-640">Getting Started:</span></span>
<span data-ttu-id="2eb87-641">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="2eb87-641">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-642">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-642">Scenarios to Try:</span></span>

- <span data-ttu-id="2eb87-643">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="2eb87-643">Insert a Table in a slide</span></span>
- <span data-ttu-id="2eb87-644">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="2eb87-644">Duplicate the slide</span></span>
- <span data-ttu-id="2eb87-645">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="2eb87-645">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="2eb87-646">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="2eb87-646">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="2eb87-647">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="2eb87-647">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="2eb87-648">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="2eb87-648">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="2eb87-649">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2eb87-649">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="2eb87-650">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-650">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="2eb87-652">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="2eb87-652">Scenarios to Try:</span></span>
- <span data-ttu-id="2eb87-653">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="2eb87-653">Switch between accounts</span></span>
- <span data-ttu-id="2eb87-654">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="2eb87-654">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="2eb87-655">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="2eb87-655">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="2eb87-656">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-656">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-657">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-657">Word</span></span> 
- <span data-ttu-id="2eb87-658">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-658">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-659">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-659">Excel</span></span>
- <span data-ttu-id="2eb87-660">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-660">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="2eb87-661">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-661">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-662">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-662">PowerPoint</span></span>
- <span data-ttu-id="2eb87-663">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb87-663">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-664">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-664">Outlook</span></span>
- <span data-ttu-id="2eb87-665">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-665">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-666">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-666">Access</span></span>
- <span data-ttu-id="2eb87-667">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-667">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-668">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-668">Project</span></span>
- <span data-ttu-id="2eb87-669">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-669">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="2eb87-670">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-670">February 11, 2019</span></span>
<span data-ttu-id="2eb87-671">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="2eb87-671">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="2eb87-672">主な修正:</span><span class="sxs-lookup"><span data-stu-id="2eb87-672">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-673">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-673">Word</span></span> 
- <span data-ttu-id="2eb87-674">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-674">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="2eb87-675">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-675">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="2eb87-676">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-676">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-677">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-677">Excel</span></span>
- <span data-ttu-id="2eb87-678">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="2eb87-678">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="2eb87-679">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-679">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-680">PowerPoint</span></span>
- <span data-ttu-id="2eb87-681">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-681">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-682">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-682">Outlook</span></span>
- <span data-ttu-id="2eb87-683">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-683">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-684">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-684">Access</span></span>
- <span data-ttu-id="2eb87-685">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-685">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-686">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-686">Project</span></span>
- <span data-ttu-id="2eb87-687">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-687">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="2eb87-688">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2eb87-688">February 1, 2019</span></span> 
<span data-ttu-id="2eb87-689">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="2eb87-689">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="2eb87-690">主な修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-690">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="2eb87-691">Word</span><span class="sxs-lookup"><span data-stu-id="2eb87-691">Word</span></span> 
- <span data-ttu-id="2eb87-692">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-692">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="2eb87-693">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-693">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="2eb87-694">Excel</span><span class="sxs-lookup"><span data-stu-id="2eb87-694">Excel</span></span>
- <span data-ttu-id="2eb87-695">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-695">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="2eb87-696">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-696">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="2eb87-697">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-697">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2eb87-698">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2eb87-698">PowerPoint</span></span>
- <span data-ttu-id="2eb87-699">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-699">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="2eb87-700">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-700">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="2eb87-701">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-701">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="2eb87-702">Outlook</span><span class="sxs-lookup"><span data-stu-id="2eb87-702">Outlook</span></span>
- <span data-ttu-id="2eb87-703">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-703">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="2eb87-704">Access</span><span class="sxs-lookup"><span data-stu-id="2eb87-704">Access</span></span>
- <span data-ttu-id="2eb87-705">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2eb87-705">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="2eb87-706">Project</span><span class="sxs-lookup"><span data-stu-id="2eb87-706">Project</span></span>
- <span data-ttu-id="2eb87-707">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="2eb87-707">Various performance and stability fixes</span></span>
