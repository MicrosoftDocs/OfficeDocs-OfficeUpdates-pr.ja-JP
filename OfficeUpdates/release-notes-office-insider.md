---
title: Office Insider のリリース ノート
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 4/19/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: b5d7bffcab3fd526fbf059f8868f86f8d5ff80fd
ms.sourcegitcommit: a9bf63c589b511ddc8c66c9221d20ea9654d60ea
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/22/2019
ms.locfileid: "31958138"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="36d30-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="36d30-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="36d30-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="36d30-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="36d30-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="36d30-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="36d30-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="36d30-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="36d30-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="36d30-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="36d30-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="36d30-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="36d30-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります</span><span class="sxs-lookup"><span data-stu-id="36d30-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="36d30-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります</span><span class="sxs-lookup"><span data-stu-id="36d30-110">The release notes publication date may not match the actual build release date</span></span>

## <a name="april-19-2019"></a><span data-ttu-id="36d30-111">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="36d30-111">April 19, 2019</span></span>
<span data-ttu-id="36d30-112">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="36d30-112">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="36d30-113">新機能:</span><span class="sxs-lookup"><span data-stu-id="36d30-113">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-114">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-114">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="36d30-115">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="36d30-115">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="36d30-116">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="36d30-116">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="36d30-117">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="36d30-117">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="36d30-118">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="36d30-118">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="36d30-119">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="36d30-119">Getting Started:</span></span>

- <span data-ttu-id="36d30-120">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="36d30-120">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="36d30-121">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="36d30-121">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="36d30-122">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="36d30-122">Scenarios to Try:</span></span>

- <span data-ttu-id="36d30-123">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="36d30-123">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="36d30-124">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-124">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="36d30-125">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="36d30-125">All Applications</span></span>
- <span data-ttu-id="36d30-126">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-126">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="36d30-127">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-127">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="36d30-128">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-128">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="36d30-129">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-129">Word</span></span> 
- <span data-ttu-id="36d30-130">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-130">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="36d30-131">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-131">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-132">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-132">Excel</span></span>
- <span data-ttu-id="36d30-133">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-133">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-134">PowerPoint</span></span>
- <span data-ttu-id="36d30-135">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-135">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="36d30-136">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-136">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-137">Outlook</span></span>
- <span data-ttu-id="36d30-138">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-138">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="36d30-139">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-139">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="36d30-140">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-140">Access</span></span>
- <span data-ttu-id="36d30-141">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-141">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="36d30-142">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-142">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="36d30-143">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-143">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="36d30-144">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-144">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="36d30-145">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-145">Project</span></span>
- <span data-ttu-id="36d30-146">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-146">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="36d30-147">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="36d30-147">April 12, 2019</span></span>
<span data-ttu-id="36d30-148">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="36d30-148">Version 1905 (build 11601.20042)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="36d30-149">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-149">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="36d30-150">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="36d30-150">All Applications</span></span>
 - <span data-ttu-id="36d30-151">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-151">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="36d30-152">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-152">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="36d30-153">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-153">Word</span></span> 
- <span data-ttu-id="36d30-154">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-154">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-155">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-155">Excel</span></span>
- <span data-ttu-id="36d30-156">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-156">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="36d30-157">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-157">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-158">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-158">PowerPoint</span></span>
- <span data-ttu-id="36d30-159">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-159">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-160">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-160">Outlook</span></span>
- <span data-ttu-id="36d30-161">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-161">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="36d30-162">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-162">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="36d30-163">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-163">Access</span></span>
- <span data-ttu-id="36d30-164">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-164">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="36d30-165">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-165">Project</span></span>
- <span data-ttu-id="36d30-166">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-166">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="36d30-167">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="36d30-167">April 5, 2019</span></span>
<span data-ttu-id="36d30-168">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="36d30-168">Version 1904 (build 11527.20014)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="36d30-169">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-169">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="36d30-170">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="36d30-170">All Applications</span></span>
 - <span data-ttu-id="36d30-171">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-171">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="36d30-172">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-172">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="36d30-173">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-173">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="36d30-174">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-174">Word</span></span> 
- <span data-ttu-id="36d30-175">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-175">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-176">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-176">Excel</span></span>
- <span data-ttu-id="36d30-177">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="36d30-177">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="36d30-178">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-178">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="36d30-179">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-179">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="36d30-180">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-180">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="36d30-181">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-181">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="36d30-182">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-182">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="36d30-183">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-183">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="36d30-184">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-184">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="36d30-185">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-185">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-186">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-186">PowerPoint</span></span>
- <span data-ttu-id="36d30-187">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="36d30-187">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-188">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-188">Outlook</span></span>
- <span data-ttu-id="36d30-189">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-189">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="36d30-190">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-190">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="36d30-191">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-191">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="36d30-192">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-192">Access</span></span>
- <span data-ttu-id="36d30-193">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-193">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="36d30-194">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-194">Project</span></span>
- <span data-ttu-id="36d30-195">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-195">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="36d30-196">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="36d30-196">March 22, 2019</span></span>
<span data-ttu-id="36d30-197">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="36d30-197">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="36d30-198">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-198">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="36d30-199">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-199">Word</span></span> 
- <span data-ttu-id="36d30-200">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-200">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-201">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-201">Excel</span></span>
- <span data-ttu-id="36d30-202">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-202">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="36d30-203">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-203">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="36d30-204">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-204">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-205">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-205">PowerPoint</span></span>
- <span data-ttu-id="36d30-206">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-206">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-207">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-207">Outlook</span></span>
- <span data-ttu-id="36d30-208">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-208">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="36d30-209">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-209">Access</span></span>
- <span data-ttu-id="36d30-210">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="36d30-210">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="36d30-211">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-211">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="36d30-212">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-212">Project</span></span>
- <span data-ttu-id="36d30-213">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-213">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="36d30-214">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-214">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="36d30-215">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="36d30-215">March 15, 2019</span></span>
<span data-ttu-id="36d30-216">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="36d30-216">Version 1904 (build 11504.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="36d30-217">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-217">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="36d30-218">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-218">Word</span></span> 
- <span data-ttu-id="36d30-219">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="36d30-219">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-220">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-220">Excel</span></span>
- <span data-ttu-id="36d30-221">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-221">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-222">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-222">PowerPoint</span></span>
- <span data-ttu-id="36d30-223">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="36d30-223">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="36d30-224">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="36d30-224">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="36d30-225">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="36d30-225">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-226">Outlook</span></span>
- <span data-ttu-id="36d30-227">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="36d30-227">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="36d30-228">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-228">Access</span></span>
- <span data-ttu-id="36d30-229">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-229">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="36d30-230">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-230">Project</span></span>
- <span data-ttu-id="36d30-231">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-231">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="36d30-232">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="36d30-232">March 8, 2019</span></span> 
<span data-ttu-id="36d30-233">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="36d30-233">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="36d30-234">新機能:</span><span class="sxs-lookup"><span data-stu-id="36d30-234">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="36d30-235">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-235">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="36d30-236">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="36d30-236">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="36d30-237">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="36d30-237">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="36d30-238">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="36d30-238">Getting Started:</span></span>

- <span data-ttu-id="36d30-239">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="36d30-239">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="36d30-240">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="36d30-240">Scenarios to Try:</span></span>

- <span data-ttu-id="36d30-241">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="36d30-241">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="36d30-242">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="36d30-242">Look up a topic or subject to get more information on it</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="36d30-243">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-243">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="36d30-244">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-244">Word</span></span> 
- <span data-ttu-id="36d30-245">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-245">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="36d30-246">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-246">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="36d30-247">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-247">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-248">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-248">Excel</span></span>
- <span data-ttu-id="36d30-249">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-249">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-250">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-250">PowerPoint</span></span>
- <span data-ttu-id="36d30-251">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-251">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-252">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-252">Outlook</span></span>
- <span data-ttu-id="36d30-253">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-253">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="36d30-254">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-254">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="36d30-255">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-255">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="36d30-256">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-256">Access</span></span>
- <span data-ttu-id="36d30-257">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-257">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="36d30-258">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-258">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="36d30-259">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-259">Project</span></span>
- <span data-ttu-id="36d30-260">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-260">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="36d30-261">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="36d30-261">March 1, 2019</span></span> 
<span data-ttu-id="36d30-262">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="36d30-262">Version 1903 (build 11414.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="36d30-263">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-263">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="36d30-264">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-264">Word</span></span> 
- <span data-ttu-id="36d30-265">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-265">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="36d30-266">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-266">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-267">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-267">Excel</span></span>
- <span data-ttu-id="36d30-268">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-268">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-269">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-269">PowerPoint</span></span>
- <span data-ttu-id="36d30-270">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-270">We fixed an issue with slide image size when using  in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-271">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-271">Outlook</span></span>
- <span data-ttu-id="36d30-272">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-272">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="36d30-273">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-273">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="36d30-274">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-274">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="36d30-275">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-275">Access</span></span>
- <span data-ttu-id="36d30-276">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="36d30-276">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="36d30-277">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-277">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="36d30-278">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-278">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="36d30-279">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-279">Project</span></span>
- <span data-ttu-id="36d30-280">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-280">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="36d30-281">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="36d30-281">February 15, 2019</span></span> 
<span data-ttu-id="36d30-282">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="36d30-282">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="36d30-283">新機能:</span><span class="sxs-lookup"><span data-stu-id="36d30-283">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-284">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="36d30-285">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="36d30-285">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="36d30-286">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="36d30-286">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="36d30-287">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="36d30-287">Getting Started:</span></span>

- <span data-ttu-id="36d30-288">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="36d30-288">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="36d30-289">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="36d30-289">The name must be prefaced with “!!”</span></span> <span data-ttu-id="36d30-290">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="36d30-290">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="36d30-291">名前の先頭に "!!" が付いていない図形の名前変更を続行できます。</span><span class="sxs-lookup"><span data-stu-id="36d30-291">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="36d30-292">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="36d30-292">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="36d30-293">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="36d30-293">Scenarios to Try:</span></span>

- <span data-ttu-id="36d30-294">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="36d30-294">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="36d30-295">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="36d30-295">Create a new slide</span></span>
- <span data-ttu-id="36d30-296">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="36d30-296">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="36d30-297">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="36d30-297">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="36d30-298">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="36d30-298">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="36d30-299">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="36d30-299">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="36d30-300">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="36d30-300">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="36d30-301">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="36d30-301">Getting Started:</span></span>

<span data-ttu-id="36d30-302">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="36d30-302">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="36d30-303">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="36d30-303">Scenarios to Try:</span></span>

- <span data-ttu-id="36d30-304">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="36d30-304">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="36d30-305">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="36d30-305">Duplicate the Slide</span></span>
- <span data-ttu-id="36d30-306">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="36d30-306">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="36d30-307">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="36d30-307">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="36d30-308">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="36d30-308">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="36d30-309">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="36d30-309">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="36d30-310">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="36d30-310">Getting Started:</span></span>
<span data-ttu-id="36d30-311">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="36d30-311">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="36d30-312">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="36d30-312">Scenarios to Try:</span></span>

- <span data-ttu-id="36d30-313">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="36d30-313">Insert a Table in a slide</span></span>
- <span data-ttu-id="36d30-314">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="36d30-314">Duplicate the slide</span></span>
- <span data-ttu-id="36d30-315">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="36d30-315">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="36d30-316">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="36d30-316">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="36d30-317">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="36d30-317">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="36d30-318">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="36d30-318">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="36d30-319">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="36d30-319">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="36d30-320">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="36d30-320">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="36d30-322">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="36d30-322">Scenarios to Try:</span></span>
- <span data-ttu-id="36d30-323">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="36d30-323">Switch between accounts</span></span>
- <span data-ttu-id="36d30-324">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="36d30-324">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="36d30-325">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="36d30-325">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="36d30-326">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-326">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="36d30-327">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-327">Word</span></span> 
- <span data-ttu-id="36d30-328">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-328">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-329">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-329">Excel</span></span>
- <span data-ttu-id="36d30-330">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-330">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="36d30-331">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-331">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-332">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-332">PowerPoint</span></span>
- <span data-ttu-id="36d30-333">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="36d30-333">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-334">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-334">Outlook</span></span>
- <span data-ttu-id="36d30-335">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-335">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="36d30-336">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-336">Access</span></span>
- <span data-ttu-id="36d30-337">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-337">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="36d30-338">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-338">Project</span></span>
- <span data-ttu-id="36d30-339">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-339">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="36d30-340">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="36d30-340">February 11, 2019</span></span>
<span data-ttu-id="36d30-341">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="36d30-341">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="36d30-342">主な修正:</span><span class="sxs-lookup"><span data-stu-id="36d30-342">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="36d30-343">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-343">Word</span></span> 
- <span data-ttu-id="36d30-344">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-344">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="36d30-345">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-345">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="36d30-346">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-346">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-347">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-347">Excel</span></span>
- <span data-ttu-id="36d30-348">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="36d30-348">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="36d30-349">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-349">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-350">PowerPoint</span></span>
- <span data-ttu-id="36d30-351">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-351">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-352">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-352">Outlook</span></span>
- <span data-ttu-id="36d30-353">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-353">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="36d30-354">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-354">Access</span></span>
- <span data-ttu-id="36d30-355">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-355">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="36d30-356">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-356">Project</span></span>
- <span data-ttu-id="36d30-357">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-357">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="36d30-358">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="36d30-358">February 1, 2019</span></span> 
<span data-ttu-id="36d30-359">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="36d30-359">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="36d30-360">主な修正</span><span class="sxs-lookup"><span data-stu-id="36d30-360">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="36d30-361">Word</span><span class="sxs-lookup"><span data-stu-id="36d30-361">Word</span></span> 
- <span data-ttu-id="36d30-362">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-362">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="36d30-363">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-363">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="36d30-364">Excel</span><span class="sxs-lookup"><span data-stu-id="36d30-364">Excel</span></span>
- <span data-ttu-id="36d30-365">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-365">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="36d30-366">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-366">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="36d30-367">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-367">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="36d30-368">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="36d30-368">PowerPoint</span></span>
- <span data-ttu-id="36d30-369">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-369">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="36d30-370">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-370">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="36d30-371">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-371">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="36d30-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="36d30-372">Outlook</span></span>
- <span data-ttu-id="36d30-373">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-373">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="36d30-374">Access</span><span class="sxs-lookup"><span data-stu-id="36d30-374">Access</span></span>
- <span data-ttu-id="36d30-375">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="36d30-375">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="36d30-376">Project</span><span class="sxs-lookup"><span data-stu-id="36d30-376">Project</span></span>
- <span data-ttu-id="36d30-377">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="36d30-377">Various performance and stability fixes</span></span>
