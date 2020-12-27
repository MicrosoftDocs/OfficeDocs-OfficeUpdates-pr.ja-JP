---
title: ベータ チャネルのリリース ノート
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: 6b42dcee02fa315647a1176bda1d581833ca5211
ms.sourcegitcommit: 9a0952ac6d6c19231b3f4148a69d3260300ae78a
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/25/2020
ms.locfileid: "49733210"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="63b96-103">ベータ チャネルのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="63b96-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="63b96-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project のベータ チャネル ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="63b96-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="63b96-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="63b96-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="63b96-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたってベータ チャネルにロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="63b96-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="63b96-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="63b96-108">以下に示すものが表示されない場合でも、最終的には入手できますのでご安心ください。</span><span class="sxs-lookup"><span data-stu-id="63b96-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="63b96-109">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="63b96-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="63b96-110">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="63b96-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="63b96-111">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります。</span><span class="sxs-lookup"><span data-stu-id="63b96-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="63b96-112">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="63b96-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (削除しないでください)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2101-december-25"></a><span data-ttu-id="63b96-115">バージョン 2101: 12 月 25 日</span><span class="sxs-lookup"><span data-stu-id="63b96-115">Version 2101: December 25</span></span>
<span data-ttu-id="63b96-116">*バージョン 2101 (ビルド 13617.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-116">*Version 2101 (Build 13617.20002)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-118">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-119">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-119">Excel</span></span>

- <span data-ttu-id="63b96-120">Excel からグラフをコピーして Word に貼り付けるときに、10 進数と桁区切りの記号の設定を継承するように更新しました</span><span class="sxs-lookup"><span data-stu-id="63b96-120">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="63b96-121">無効なファイル属性 (作成時刻、修正時刻など) を持つ UNC ファイルを開くと、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-121">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="63b96-122">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-122">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-123">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-123">Outlook</span></span>

- <span data-ttu-id="63b96-124">Word から差し込み印刷を開始するときに、ユーザーがアクセスを許可する時間の長さを指定できず、ユーザーに対して余分なプロンプトが表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-124">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="63b96-125">引き換えベースのアドインのユーザーの Outlook が予期せず終了してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-125">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-126">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-126">PowerPoint</span></span>

- <span data-ttu-id="63b96-127">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-127">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-128">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-128">Word</span></span>

- <span data-ttu-id="63b96-129">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-129">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="63b96-130">コメント カードの返信ボックスが画面に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-130">Fixes an issue where the reply box on a comment card is off the screen.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-december-18"></a><span data-ttu-id="63b96-132">バージョン 2101: 12 月 18 日</span><span class="sxs-lookup"><span data-stu-id="63b96-132">Version 2101: December 18</span></span>
<span data-ttu-id="63b96-133">*バージョン 2101 (ビルド 13610.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-133">*Version 2101 (Build 13610.20002)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-135">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-135">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-136">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-136">Excel</span></span>

- <span data-ttu-id="63b96-137">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="63b96-137">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="63b96-138">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="63b96-138">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-139">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-139">Outlook</span></span>

- <span data-ttu-id="63b96-140">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="63b96-140">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="63b96-141">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="63b96-141">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-142">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-142">PowerPoint</span></span>

- <span data-ttu-id="63b96-143">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="63b96-143">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="63b96-144">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="63b96-144">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-145">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-145">Word</span></span>

- <span data-ttu-id="63b96-146">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="63b96-146">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="63b96-147">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="63b96-147">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-150">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-150">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-151">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-151">Excel</span></span>

- <span data-ttu-id="63b96-152">ピボット テーブルに書式設定スタイルを適用するときのパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-152">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-153">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-153">Outlook</span></span>

- <span data-ttu-id="63b96-154">ユーザーが検索対象のカテゴリを複数選ぶことができなかった原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-154">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="63b96-155">イベントが別の予定からコピーされたときに、一部の予定表アイテムの開始時刻が予期せず変更される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-155">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


### <a name="project"></a><span data-ttu-id="63b96-156">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-156">Project</span></span>

- <span data-ttu-id="63b96-157">更新された情報が保存されているはずのプロジェクトをユーザーが開いた際に、更新された情報が見つからないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-157">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-158">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-158">Word</span></span>

- <span data-ttu-id="63b96-159">コメント カードの下部に入力するときのアニメーションを修正します。</span><span class="sxs-lookup"><span data-stu-id="63b96-159">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="63b96-160">文書を隠し文字で PDF に保存する際に、Word が固まる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-160">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-december-11"></a><span data-ttu-id="63b96-162">バージョン 2101: 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="63b96-162">Version 2101: December 11</span></span>
<span data-ttu-id="63b96-163">*バージョン 2101 (ビルド 13604.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-163">*Version 2101 (Build 13604.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-165">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-165">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-166">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-166">Outlook</span></span>

- <span data-ttu-id="63b96-167">**クラウドでの Outlook の設定** [自動応答]、[優先受信トレイ]、[プライバシー] などの Outlook for Windows の設定を選択し、任意の PC でアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="63b96-167">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-168">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-168">Word</span></span>

- <span data-ttu-id="63b96-169">**最新のコメントによる共同作業の向上:** オブジェクトにコメントを追加したり、同僚に @mention したり、コメント スレッドを解決して共同作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-169">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="63b96-170">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-170">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br /><span data-ttu-id="63b96-171">[ブログの投稿](https://insider.office.com/ja-JP/blog/modern-commenting-in-word)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-171">See details in [blog post](https://insider.office.com/ja-JP/blog/modern-commenting-in-word)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-174">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-174">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-175">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-175">Excel</span></span>

- <span data-ttu-id="63b96-176">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-176">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="63b96-177">Selection.Parent.Copy コールの後に区切り文字の切り替えに関連する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-177">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-178">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-178">Outlook</span></span>

- <span data-ttu-id="63b96-179">送信時にプレーン テキストの S/MIME メッセージが正しく表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-179">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-180">PowerPoint</span></span>

- <span data-ttu-id="63b96-181">この変更により、スライドショーでバックグラウンドビデオ再生がループする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-181">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="63b96-182">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-182">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-183">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-183">Word</span></span>

- <span data-ttu-id="63b96-184">編集不可とマークされているコンテンツ コントロールでの最新のコメントの削除に関する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-184">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>



[//]: # ( BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-04"></a><span data-ttu-id="63b96-186">バージョン 2012: 12 月 4 日</span><span class="sxs-lookup"><span data-stu-id="63b96-186">Version 2012: December 04</span></span>
<span data-ttu-id="63b96-187">*バージョン 2012 (ビルド 13530.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-187">*Version 2012 (Build 13530.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-189">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-189">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-190">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-190">Outlook</span></span>

- <span data-ttu-id="63b96-191">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分遅く会議を開始するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="63b96-191">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="63b96-192">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-192">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a><span data-ttu-id="63b96-193">Visio</span><span class="sxs-lookup"><span data-stu-id="63b96-193">Visio</span></span>

- <span data-ttu-id="63b96-194">**新しい Azure ステンシルと図形:** 最新の Azure 図を作成するために、多くのステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-194">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="63b96-195">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-195">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-198">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-199">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-199">Excel</span></span>

- <span data-ttu-id="63b96-200">上書きモードでの編集時に、IME を使用する必要がある言語での編集がうまくいかない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-200">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="63b96-201">自動保存が無効になっている場合に、通知のヘルプ記事へのハイパーリンクが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-201">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="63b96-202">数式ビューでデータをコピーして貼り付けると、Excel が予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-202">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-203">Outlook</span></span>

- <span data-ttu-id="63b96-204">下書きに保存したときに SmartLinks の書式設定が失われるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-204">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


### <a name="project"></a><span data-ttu-id="63b96-205">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-205">Project</span></span>

- <span data-ttu-id="63b96-206">沢山のリソースが付いたプロジェクトを開くのに、長い時間かかっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-206">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="63b96-207">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-207">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-208">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-208">Word</span></span>

- <span data-ttu-id="63b96-209">リッチ テキストとして貼り付けるより、通常のテキストとして貼り付けることが推奨されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-209">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="63b96-210">このコンテキスト メニューの修正プログラムでは、テキストとして貼り付けることができます。</span><span class="sxs-lookup"><span data-stu-id="63b96-210">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="63b96-211">それ以外の場合、ユーザーはメモ帳などのプレーンテキスト エディターにコピーして、メモ帳から目的のターゲット アプリにコピーする必要があります。</span><span class="sxs-lookup"><span data-stu-id="63b96-211">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-november-27"></a><span data-ttu-id="63b96-213">バージョン 2012: 11 月 27 日</span><span class="sxs-lookup"><span data-stu-id="63b96-213">Version 2012: November 27</span></span>
<span data-ttu-id="63b96-214">*バージョン 2012 (ビルド 13519.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-214">*Version 2012 (Build 13519.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-216">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-216">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-217">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-217">Excel</span></span>

- <span data-ttu-id="63b96-218">これにより、Power Pivot がタブ区切りのテキストファイルを正しくインポートできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-218">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-219">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-219">Outlook</span></span>

- <span data-ttu-id="63b96-220">Outlook 以外のアプリケーションから Outlook メールを送信するときに、ユーザーに問題が発生しているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-220">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-221">PowerPoint</span></span>

- <span data-ttu-id="63b96-222">この変更により、インク分析中のタイムアウトに関連する問題が解決します。</span><span class="sxs-lookup"><span data-stu-id="63b96-222">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="63b96-223">この変更は、アニメーション GIF ユーザー インターフェイスの作成に関する文法エラーに対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-223">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="63b96-224">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-224">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="63b96-225">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-225">Project</span></span>

- <span data-ttu-id="63b96-226">タスクに関連付して、割り当てられていない割り当てが複数存在するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-226">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="63b96-227">大規模なプロジェクトでは、タスク名の入力に非常に時間がかかることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-227">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-november-20"></a><span data-ttu-id="63b96-229">バージョン 2012: 11 月 20 日</span><span class="sxs-lookup"><span data-stu-id="63b96-229">Version 2012: November 20</span></span>
<span data-ttu-id="63b96-230">*バージョン 2012 (ビルド 13512.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-230">*Version 2012 (Build 13512.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-232">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-232">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-233">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-233">Outlook</span></span>

- <span data-ttu-id="63b96-234">**会議はすべてオンラインで:** 新しい設定により、オンライン会議のスケジュールを簡単に立てれるため、既定ですべての会議をオンラインにできます。</span><span class="sxs-lookup"><span data-stu-id="63b96-234">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-235">PowerPoint</span></span>

- <span data-ttu-id="63b96-236">**ビデオ ライブラリ:** アプリ内で利用可能な、質の良い無料のビデオ フッテージのライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="63b96-236">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-239">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-239">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="63b96-240">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-240">PowerPoint</span></span>

- <span data-ttu-id="63b96-241">共同編集者の詳細情報が有効になった際に、不明だった共同編集者のプレゼンス インジケーターを完全に更新できなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-241">Fixed an issue where the presence indicator for an unknown coauthor does not get completely refreshed, once more information about the coauthor is available.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-242">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-242">Word</span></span>

- <span data-ttu-id="63b96-243">文書を隠し文字で PDF に保存する際に、Word が固まる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-243">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2012-november-13"></a><span data-ttu-id="63b96-245">バージョン 2012: 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="63b96-245">Version 2012: November 13</span></span>
<span data-ttu-id="63b96-246">*バージョン 2012 (ビルド 13510.20004)*</span><span class="sxs-lookup"><span data-stu-id="63b96-246">*Version 2012 (Build 13510.20004)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-248">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-248">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-249">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-249">Excel</span></span>

- <span data-ttu-id="63b96-250">OneDrive のローカル同期フォルダーからファイルを挿入する際に、「オブジェクトの挿入」コマンドにおいて正しいアイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-250">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-251">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-251">Outlook</span></span>

- <span data-ttu-id="63b96-252">タスク進捗レポートの [宛先] フィールドが空白になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-252">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-253">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-253">PowerPoint</span></span>

- <span data-ttu-id="63b96-254">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-254">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


### <a name="project"></a><span data-ttu-id="63b96-255">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-255">Project</span></span>

- <span data-ttu-id="63b96-256">成果物が関連付けられていた SharePoint サイトが存在しなくなった場合に、成果物の依存関係を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-256">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="63b96-257">更新された情報が保存されているはずのプロジェクトをユーザーが開いた際に、更新された情報が見つからないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-257">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-258">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-258">Word</span></span>

- <span data-ttu-id="63b96-259">ズーム中に写真がぼやけてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-259">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="63b96-260">長いハイパーリンクが一部省略されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-260">We fixed an issue where long hyperlinks were getting truncated.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2012-november-06"></a><span data-ttu-id="63b96-262">バージョン 2012: 11 月 6 日</span><span class="sxs-lookup"><span data-stu-id="63b96-262">Version 2012: November 06</span></span>
<span data-ttu-id="63b96-263">*バージョン 2012 (ビルド 13430.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-263">*Version 2012 (Build 13430.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-265">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-265">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-266">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-266">Excel</span></span>

- <span data-ttu-id="63b96-267">**複数のシートを同時に再表示する:** 一度に再表示できるのが、1枚のシートだけではなくなりました。一度に複数の非表示シートを表示します。</span><span class="sxs-lookup"><span data-stu-id="63b96-267">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="63b96-268">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-268">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a><span data-ttu-id="63b96-269">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-269">Outlook</span></span>

- <span data-ttu-id="63b96-270">**同じ署名、すべてのデバイス:** 署名をクラウドに保存し ます。</span><span class="sxs-lookup"><span data-stu-id="63b96-270">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="63b96-271">一度作成して、Outlook を使用するすべての場所で使用します。</span><span class="sxs-lookup"><span data-stu-id="63b96-271">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-274">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-274">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-275">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-275">Excel</span></span>

- <span data-ttu-id="63b96-276">一部のリボン要素が簡体字中国語でローカライズされていないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-276">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="63b96-277">更新時に Excel が予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-277">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-278">Outlook</span></span>

- <span data-ttu-id="63b96-279">Zip ファイルから開いたメッセージに添付ファイルを追加するときに問題が発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-279">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-30"></a><span data-ttu-id="63b96-281">バージョン 2011: 10 月 30 日</span><span class="sxs-lookup"><span data-stu-id="63b96-281">Version 2011: October 30</span></span>
<span data-ttu-id="63b96-282">*バージョン 2011 (ビルド 13426.20004)*</span><span class="sxs-lookup"><span data-stu-id="63b96-282">*Version 2011 (Build 13426.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-284">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-284">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-285">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-285">Excel</span></span>

- <span data-ttu-id="63b96-286">**改善された条件付き書式ダイアログ**: 条件付き書式ダイアログのサイズが変更可能になり、シングルクリックでルールを複製できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-286">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="63b96-287">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-287">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-290">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-290">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-291">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-291">Access</span></span>

- <span data-ttu-id="63b96-292">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-292">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="63b96-293">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-293">Excel</span></span>

- <span data-ttu-id="63b96-294">Oracle データベースへの接続を使用する際の Power Pivot の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-294">Fixed a problem with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="63b96-295">MTR 計算およびグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) のプロセスがトリガーされたときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-295">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="63b96-296">この変更により、atomsvc ファイルを読み込もうとすると Excel でエラーが発生するバグが修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-296">This change fixes a bug, which causes a failure in Excel on attempt to load an atomsvc file.</span></span>


- <span data-ttu-id="63b96-297">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-297">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-298">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-298">Outlook</span></span>

- <span data-ttu-id="63b96-299">オプションがグレー表示され、メールボックスの所有者が自分のカレンダーの共有権限を管理できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-299">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="63b96-300">メールテンプレートを .OFT として保存すると、中国語の文字が疑問符に変わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-300">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


- <span data-ttu-id="63b96-301">Outlook が制限付きのアクセス許可でメッセージを作成できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-301">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="63b96-302">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-302">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-303">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-303">PowerPoint</span></span>

- <span data-ttu-id="63b96-304">デザインウィンドウを閉じるときにグリッド線がスライドからずれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-304">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="63b96-305">選択ウィンドウを開いた状態で画面の記録を停止した後、スライドのスクロールバーが自動的に調整を開始する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-305">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="63b96-306">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-306">Project</span></span>

- <span data-ttu-id="63b96-307">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-307">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="63b96-308">リソースエンゲージメントが GUID ではなく名前でリソースを検索する問題を修正しました。同じ名前のリソースが複数ある場合に問題が発生していました。</span><span class="sxs-lookup"><span data-stu-id="63b96-308">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-309">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-309">Word</span></span>

- <span data-ttu-id="63b96-310">コメントヒントをクリックしてもズームアウトしてコメントカードが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-310">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="63b96-311">列間の線がずれている場合があるレイアウトの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-311">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="63b96-312">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-312">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="office-suite"></a><span data-ttu-id="63b96-313">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-313">Office Suite</span></span>

- <span data-ttu-id="63b96-314">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-314">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2011-october-23"></a><span data-ttu-id="63b96-316">バージョン 2011: 10 月 23 日</span><span class="sxs-lookup"><span data-stu-id="63b96-316">Version 2011: October 23</span></span>
<span data-ttu-id="63b96-317">*バージョン 2011 (ビルド 13415.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-317">*Version 2011 (Build 13415.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-319">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-319">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="63b96-320">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-320">PowerPoint</span></span>

- <span data-ttu-id="63b96-321">**プレゼンター コーチでプレゼンテーションのリハーサルを行う:** 話す速度、ピッチ、つなぎ語、機微な表現など、聴衆の関心を引きつけておくのに役立つ内容についてフィードバックを受けます。</span><span class="sxs-lookup"><span data-stu-id="63b96-321">**Rehearse your presentation with Presenter Coach:** Get feedback on the things that help keep an audience engaged — like pacing, pitch, filler words, sensitive phrases, and more.</span></span> [<span data-ttu-id="63b96-322">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-322">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-325">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-325">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-326">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-326">Access</span></span>

- <span data-ttu-id="63b96-327">同期済みの OneDrive フォルダーからクエリをエクスポートしようとしたときに、一部のユーザーに "システム リソースの超過" というエラーが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-327">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>

- <span data-ttu-id="63b96-328">フォーム ウィンドウ間で別のフォームに切り替える場合の「自動」切り替えの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-328">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-329">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-329">Outlook</span></span>

- <span data-ttu-id="63b96-330">会議の場所からコピーした URL をブラウザーなどの別の場所に貼り付けると、URL の末尾にセミコロンが含まれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-330">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-331">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-331">PowerPoint</span></span>

- <span data-ttu-id="63b96-332">スライドショーを 2 台目のモニターに複製する場合、そのスライドショーが他のウィンドウの背面で非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-332">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-333">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-333">Project</span></span>

- <span data-ttu-id="63b96-334">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-334">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-335">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-335">Word</span></span>

- <span data-ttu-id="63b96-336">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-336">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>

- <span data-ttu-id="63b96-337">機密度ラベルに透かしが適用される場合がある印刷の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-337">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-16"></a><span data-ttu-id="63b96-339">バージョン 2011: 10 月 16 日</span><span class="sxs-lookup"><span data-stu-id="63b96-339">Version 2011: October 16</span></span>
<span data-ttu-id="63b96-340">*バージョン 2011 (ビルド 13408.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-340">*Version 2011 (Build 13408.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-342">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-342">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-343">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-343">Excel</span></span>

- <span data-ttu-id="63b96-344">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-344">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="63b96-345">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-345">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="63b96-346">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-346">Outlook</span></span>

- <span data-ttu-id="63b96-347">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-347">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="63b96-348">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-348">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="63b96-349">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-349">PowerPoint</span></span>

- <span data-ttu-id="63b96-350">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-350">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="63b96-351">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-351">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a><span data-ttu-id="63b96-352">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-352">Word</span></span>

- <span data-ttu-id="63b96-353">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-353">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="63b96-354">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-354">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-357">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-357">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-358">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-358">Outlook</span></span>

- <span data-ttu-id="63b96-359">ユーザーが基本認証で Microsoft 365 グループの予定表の予定を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-359">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="63b96-360">ニックネーム キャッシュの読み込み中に Outlook の起動に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-360">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-361">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-361">PowerPoint</span></span>

- <span data-ttu-id="63b96-362">画像の横のコンテンツ プレースホルダー アイコンにツールヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-362">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="63b96-363">pptsx ファイルで表示されるスライド ショーの保護されたビューで、IRM で保護されたドキュメントの画面キャプチャが許可される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-363">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-09"></a><span data-ttu-id="63b96-365">バージョン 2011: 10 月 09 日</span><span class="sxs-lookup"><span data-stu-id="63b96-365">Version 2011: October 09</span></span>
<span data-ttu-id="63b96-366">*バージョン 2011 (ビルド 13406.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-366">*Version 2011 (Build 13406.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-368">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-368">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-369">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-369">Excel</span></span>

- <span data-ttu-id="63b96-370">**クエリから Powe rPlatform データフローを作成する**: 新しい Powe rPlatform データフローの作成に使用できる Power Query テンプレートにクエリをエクスポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-370">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-371">PowerPoint</span></span>

- <span data-ttu-id="63b96-372">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します</span><span class="sxs-lookup"><span data-stu-id="63b96-372">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="63b96-373">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="63b96-373">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-376">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-376">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-377">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-377">Excel</span></span>

- <span data-ttu-id="63b96-378">COM アドインを有効にして SaveAs 操作を行った後、ファイル名が変更されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-378">We fixed an issue where  Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="63b96-379">Excel データモデルに不適切なメジャー定義がある場合に、自動保存が誤った、または誤解を招くエラーメッセージを表示して失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-379">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="63b96-380">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-380">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-381">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-381">Outlook</span></span>

- <span data-ttu-id="63b96-382">画像の添付ファイルをクイック印刷すると、以下のエラーが発生する問題を修正しました。「Windows がこの画像を見つけることができません。</span><span class="sxs-lookup"><span data-stu-id="63b96-382">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="63b96-383">場所を確認してから、もう一度お試しください」。</span><span class="sxs-lookup"><span data-stu-id="63b96-383">Check the location, and then try again".</span></span>


- <span data-ttu-id="63b96-384">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-384">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-385">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-385">PowerPoint</span></span>

- <span data-ttu-id="63b96-386">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-386">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="project"></a><span data-ttu-id="63b96-387">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-387">Project</span></span>

- <span data-ttu-id="63b96-388">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-388">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="63b96-389">プロジェクトサイトにタスクリストがあり、タスクリストをグループ化すると、タスクリストをすばやく編集できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-389">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="63b96-390">CSOM を介してエンタープライズリソースを更新すると、リソースの最大単位数が失われることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-390">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-391">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-391">Word</span></span>

- <span data-ttu-id="63b96-392">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-392">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="office-suite"></a><span data-ttu-id="63b96-393">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-393">Office Suite</span></span>

- <span data-ttu-id="63b96-394">SSO API インタラクティブ サインインがエラー コードを返す問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-394">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-02"></a><span data-ttu-id="63b96-396">バージョン 2010: 10 月 2 日</span><span class="sxs-lookup"><span data-stu-id="63b96-396">Version 2010: October 02</span></span>
<span data-ttu-id="63b96-397">*バージョン 2010 (ビルド 13328.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-397">*Version 2010 (Build 13328.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-399">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-399">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-400">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-400">Excel</span></span>

- <span data-ttu-id="63b96-401">**[詳細] ダイアログ ボックスを使用してデータ型を作成する:** [詳細] ダイアログ ボックスでは、作成するデータ型を組み合わせる列を手動で選択できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-401">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-404">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-404">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="63b96-405">OneNote</span><span class="sxs-lookup"><span data-stu-id="63b96-405">OneNote</span></span>

- <span data-ttu-id="63b96-406">ユーザーが OutSpace で [ファイル]、[情報] に移動してテキスト ボックスからノートブックの URL を選択してコピーできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-406">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-407">Outlook</span></span>

- <span data-ttu-id="63b96-408">件名が空白の場合、自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-408">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="63b96-409">間違ったフォルダー GUID がフォルダーにキャッシュされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-409">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="63b96-410">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="63b96-410">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="63b96-411">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-411">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="63b96-412">オンライン共有フォルダーが親フォルダー名を返さない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-412">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="63b96-413">失敗する代わりに、プライマリ アカウントに誤って送信された空のパスを返しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-413">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="63b96-414">読み取り専のプレビュー ウィンドウから下書きを再開した後、トラックの変更がオンになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-414">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="63b96-415">[名前を付けて保存] オプションが従来の添付ファイルで使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-415">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="63b96-416">ポリシーを上書きするときに正当化テキストをカスタマイズする方法をユーザーに提供する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-416">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-417">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-417">PowerPoint</span></span>

- <span data-ttu-id="63b96-418">PDF へのエクスポート中に PowerPoint が長方形の箇条書きをエクスポートしなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-418">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="63b96-419">最後のスライドを表示していて、[セッションの終了] を押した後、概要が表示される前に次のスライドにスワイプすると、[セッションの終了] ダイアログ ボックスが概要ページにも表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-419">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="63b96-420">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-420">Project</span></span>

- <span data-ttu-id="63b96-421">リソース配分状況ビューまたはシート ビューにグループ化を適用してから列を挿入すると、Project がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-421">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


- <span data-ttu-id="63b96-422">数式を使用してカスタム フィールドを作成し、取得した値を使用している場合、表示の切り替えやプロジェクト/タスクの詳細を開く際にパフォーマンスの遅延が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-422">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="63b96-423">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-423">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="63b96-424">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-424">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-september-25"></a><span data-ttu-id="63b96-426">バージョン 2010: 9 月 25 日</span><span class="sxs-lookup"><span data-stu-id="63b96-426">Version 2010: September 25</span></span>
<span data-ttu-id="63b96-427">*バージョン 2010 (ビルド 13318.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-427">*Version 2010 (Build 13318.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-429">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-429">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-430">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-430">Excel</span></span>

- <span data-ttu-id="63b96-431">**Power Query を使用してデータ型を作成する: Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します**</span><span class="sxs-lookup"><span data-stu-id="63b96-431">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-432">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-432">Outlook</span></span>

- <span data-ttu-id="63b96-433">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新</span><span class="sxs-lookup"><span data-stu-id="63b96-433">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="63b96-434">**メッセージの作成にかかる時間を節約:** Outlook は、メッセージをすばやく作成するのに役立つ提案を作成することを示します。</span><span class="sxs-lookup"><span data-stu-id="63b96-434">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="63b96-435">提案を受け入れるには、Tab キーを使用するだけです。</span><span class="sxs-lookup"><span data-stu-id="63b96-435">To accept the suggestion, just use the Tab key.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-436">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-436">Word</span></span>

- <span data-ttu-id="63b96-437">**Microsoft エディター ウィンドウにデスクトップ用の Word の更新が表示される:** デスクトップ クライアント用の Word エディター ウィンドウの現在のエクスペリエンスをアップグレードしました。</span><span class="sxs-lookup"><span data-stu-id="63b96-437">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-440">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-440">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-441">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-441">Access</span></span>

- <span data-ttu-id="63b96-442">スクロール中に保存されたクエリ/リレーションシップ ウィンドウを読み込むときに、スクロールバーの位置が正しく設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-442">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="63b96-443">[テーブルを追加する] 作業ウィンドウに「&」を含む名前が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-443">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="63b96-444">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-444">Excel</span></span>

- <span data-ttu-id="63b96-445">マルチレベル カテゴリの手動間隔がグラフで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-445">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="63b96-446">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-446">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="63b96-447">データ検証に使用されるテーブルに追加しても、ブック内のすべてのシートのオプションが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-447">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


### <a name="onenote"></a><span data-ttu-id="63b96-448">OneNote</span><span class="sxs-lookup"><span data-stu-id="63b96-448">OneNote</span></span>

- <span data-ttu-id="63b96-449">OneNote がカスタム テーマのキャンバスのハイ コントラスト カラーを尊重しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-449">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


- <span data-ttu-id="63b96-450">ノートブックのカラー セレクターで緑色にカーソルを合わせると、ポップアップに「赤チョーク」と表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-450">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


### <a name="powerpoint"></a><span data-ttu-id="63b96-451">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-451">PowerPoint</span></span>

- <span data-ttu-id="63b96-452">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-452">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-453">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-453">Word</span></span>

- <span data-ttu-id="63b96-454">ワークフロー対応ファイルへのリンクが期待どおりに開かない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-454">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-september-18"></a><span data-ttu-id="63b96-456">バージョン 2010: 9 月 18 日</span><span class="sxs-lookup"><span data-stu-id="63b96-456">Version 2010: September 18</span></span>
<span data-ttu-id="63b96-457">*バージョン 2010 (ビルド 13312.20006)*</span><span class="sxs-lookup"><span data-stu-id="63b96-457">*Version 2010 (Build 13312.20006)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-459">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-459">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-460">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-460">Outlook</span></span>

- <span data-ttu-id="63b96-461">**エディターによるメッセージの校正:** Outlook 64 ビットのユーザーのメールで、文法や他のスタイル修正候補が提供されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-461">**Proofread your messages with Editor:** You can now get grammar and other style suggestions in your emails for Outlook 64-bit users.</span></span> <span data-ttu-id="63b96-462">下線が引かれた単語には、文章を洗練させるための修正候補がエディターから提示されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-462">Look for underlined words to see Editor’s suggestions to refine your writing.</span></span>

- <span data-ttu-id="63b96-463">**組み込みの翻訳機能を使用して、言語の壁を取り除く:** 翻訳用のアドインは必要なくなりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-463">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="63b96-464">メッセージを右クリックすると、特定の単語、語句、またはメッセージ全体を翻訳できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-464">In a message, right-click to translate specific words, phrases, or the whole message.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-467">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-467">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-468">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-468">Excel</span></span>

- <span data-ttu-id="63b96-469">VBA を使用した、シリーズの最大値、中間値、最小値の色の設定が機能しないという 2D マップ グラフの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-469">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="63b96-470">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-470">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="63b96-471">「Excel で 1 つまたは複数の数式を計算しようとする際にリソース不足になりました」というエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-471">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="63b96-472">数式バーに数式を入力したときに、ChartSheet がクラッシュする場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-472">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


### <a name="outlook"></a><span data-ttu-id="63b96-473">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-473">Outlook</span></span>

- <span data-ttu-id="63b96-474">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="63b96-474">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="63b96-475">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-475">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


### <a name="word"></a><span data-ttu-id="63b96-476">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-476">Word</span></span>

- <span data-ttu-id="63b96-477">変更履歴 (挿入/削除) をユーザーがタップすると、コメントがポップアップ表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-477">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="63b96-478">Word でコメントの吹き出しを削除するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-478">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="63b96-479">Outlook でメッセージが [転送不可] に設定される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-479">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="63b96-480">引用と数式を含む Word 文書を保存するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-480">We fixed an issue with saving Word document that contains citation and equation.</span></span>



[//]: # (BUGDETAILS を削除しないでください 終了)

## <a name="version-2010-september-11"></a><span data-ttu-id="63b96-482">バージョン 2010: 9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="63b96-482">Version 2010: September 11</span></span>
<span data-ttu-id="63b96-483">*バージョン 2010 (ビルド 13304.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-483">*Version 2010 (Build 13304.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-485">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-485">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="63b96-486">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-486">Access</span></span>

- <span data-ttu-id="63b96-487">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-487">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-488">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-488">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-489">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-489">Excel</span></span>

- <span data-ttu-id="63b96-490">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-490">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-491">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-491">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="onenote"></a><span data-ttu-id="63b96-492">OneNote</span><span class="sxs-lookup"><span data-stu-id="63b96-492">OneNote</span></span>

- <span data-ttu-id="63b96-493">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-493">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-494">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-494">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-495">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-495">Outlook</span></span>

- <span data-ttu-id="63b96-496">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-496">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-497">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-497">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-498">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-498">PowerPoint</span></span>

- <span data-ttu-id="63b96-499">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-499">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-500">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-500">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-501">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-501">Project</span></span>

- <span data-ttu-id="63b96-502">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-502">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-503">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-503">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="publisher"></a><span data-ttu-id="63b96-504">Publisher</span><span class="sxs-lookup"><span data-stu-id="63b96-504">Publisher</span></span>

- <span data-ttu-id="63b96-505">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-505">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-506">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-506">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="visio"></a><span data-ttu-id="63b96-507">Visio</span><span class="sxs-lookup"><span data-stu-id="63b96-507">Visio</span></span>

- <span data-ttu-id="63b96-508">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-508">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-509">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-509">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-510">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-510">Word</span></span>

- <span data-ttu-id="63b96-511">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="63b96-511">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="63b96-512">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-512">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-515">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-515">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-516">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-516">Excel</span></span>

- <span data-ttu-id="63b96-517">[改ページ プレビュー] が有効になっているときに、大量のデータが含まれているワークシート間を切り替える際に顕著な遅延が発生する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-517">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-518">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-518">Outlook</span></span>

- <span data-ttu-id="63b96-519">優先受信トレイをオフにして並べ替えを行った後に、メールが非表示になるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-519">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-520">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-520">PowerPoint</span></span>

- <span data-ttu-id="63b96-521">エディターとスライド ショーで GIF のアニメーションが1 回だけしか再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-521">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>

[//]: # (BUGDETAILS を削除しないでください 終了)

## <a name="version-2010-september-04"></a><span data-ttu-id="63b96-523">バージョン 2010: 9 月 4 日</span><span class="sxs-lookup"><span data-stu-id="63b96-523">Version 2010: September 04</span></span>
<span data-ttu-id="63b96-524">*バージョン 2010 (ビルド 13301.20004)*</span><span class="sxs-lookup"><span data-stu-id="63b96-524">*Version 2010 (Build 13301.20004)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-526">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-526">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-527">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-527">Outlook</span></span>

- <span data-ttu-id="63b96-528">**メールのピン留め:** この機能を使うことで、他のユーザーに返信する必要があるメールを追跡したり、忘れないようにそれらのメールをメッセージ一覧の一番上に固定したりできます。</span><span class="sxs-lookup"><span data-stu-id="63b96-528">**Pinning email:** This feature helps users keep track of mails they need to go back to you or have as a reminder by keeping them at the top of the message list.</span></span>

- <span data-ttu-id="63b96-529">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、関連性が最も高いメールが候補に表示されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-529">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="63b96-530">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、関連性が最も高いメールが候補に表示されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-530">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="63b96-531">**Microsoft エディターが Word と Outlook のデスクトップ クライアント向けにアップグレードされました:** エディターのスペルチェック、文章校正、および詳細なスタイルの修正候補で、新しい、クリックによるレビュー モデルが導入されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-531">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="63b96-532">この変更には、候補をレビューするために表示される専用のカードも含まれています。</span><span class="sxs-lookup"><span data-stu-id="63b96-532">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-533">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-533">Word</span></span>

- <span data-ttu-id="63b96-534">**Microsoft エディターが Word と Outlook のデスクトップ クライアント向けにアップグレードされました:** エディターのスペルチェック、文章校正、および詳細なスタイルの修正候補で、新しい、クリックによるレビュー モデルが導入されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-534">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="63b96-535">この変更には、候補をレビューするために表示される専用のカードも含まれています。</span><span class="sxs-lookup"><span data-stu-id="63b96-535">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-538">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-538">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-539">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-539">Excel</span></span>

- <span data-ttu-id="63b96-540">LET 関数が含まれているファイルを開くと、以下の警告が表示される問題が修正されました: "ファイル名.xlsx" のコンテンツに問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-540">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="63b96-541">できるだけ多くの内容の復元を試みますか?</span><span class="sxs-lookup"><span data-stu-id="63b96-541">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="63b96-542">このブックの発行元が信頼できる場合は、[はい] をクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="63b96-542">If you trust the source of this workbook, click Yes".</span></span>
- <span data-ttu-id="63b96-543">XLAM アドインの参照と名前付き範囲に関連するクラッシュが修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-543">We fixed a crash related to XLAM add-in references and named ranges.</span></span>
- <span data-ttu-id="63b96-544">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-544">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>
- <span data-ttu-id="63b96-545">ユーザーが動的配列にカスタム スタイルを適用すると、"配列の一部を変更することはできません" というエラーが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-545">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="63b96-546">これは以前に存在していた制約でしたが、現在は削除されています。</span><span class="sxs-lookup"><span data-stu-id="63b96-546">This was a legacy restriction that has been removed.</span></span>
- <span data-ttu-id="63b96-547">デバイスへの接続が失われると (リモート セッションが接続されたり接続が解除されたり、モニターでの変更があった場合など) Excel の関数バーが完全に描画されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-547">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-548">Outlook</span></span>

- <span data-ttu-id="63b96-549">問題が修正され、グループ ポリシー経由で既定のログ記録オプションを有効または無効にするための柔軟性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-549">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>
- <span data-ttu-id="63b96-550">アシスタントのアクセス許可があるメールボックスと管理者のアクセス許可があるメールボックスの間でメールの下書きを移動した後も、メール送信者の従来のドメイン名が維持されて表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-550">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>
- <span data-ttu-id="63b96-551">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-551">We fixed an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>
- <span data-ttu-id="63b96-552">1 行リボン (SLR) を有効にした後に VBA コード ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") を実行すると実行時エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-552">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>
- <span data-ttu-id="63b96-553">高解像度 (1750 x 1920 など) と大きなテキストサイズ (175% など) が同時に使用された場合に、[自動応答] ダイアログの [OK] ボタンと [キャンセル] ボタンが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-553">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>
- <span data-ttu-id="63b96-554">会議出席依頼を空の連絡先グループから別の連絡先グループに送信するとクラッシュする状態が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-554">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>
- <span data-ttu-id="63b96-555">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-555">We fixed an issue that caused users to experience a crash when opening certain very large emails.</span></span>
- <span data-ttu-id="63b96-556">アドインが常に有効になっていることがグループ ポリシーで要求される場合に、ユーザーがアドインを無効にすることを防ぐためにアドインの監視が使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-556">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-557">PowerPoint</span></span>

- <span data-ttu-id="63b96-558">ビデオがスライドショーで自動的に再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-558">We fixed an issue where videos were not playing automatically in slideshows.</span></span>
- <span data-ttu-id="63b96-559">PowerPoint を起動後にスライドを挿入してコメント ウィンドウを開いて閉じると、縮小版ウィンドウ内のスライドが重なって表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-559">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-560">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-560">Project</span></span>

- <span data-ttu-id="63b96-561">リソースに複数のコスト単価テーブルが含まれている場合、残りのコストが正確に計算されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-561">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>
- <span data-ttu-id="63b96-562">SharePoint のタスク リストに接続されているプロジェクトでプロジェクト終了日が更新されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-562">We fixed an issue where the Project finish date wasn't getting updated for projects connected to SharePoint tasks list.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-563">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-563">Word</span></span>

- <span data-ttu-id="63b96-564">ユーザーがコメントをクリックした場合に、コメント カードでコメントのテキストの周囲に枠線が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-564">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>
- <span data-ttu-id="63b96-565">ドキュメントの拡大率が 160% より大きく設定され、コメント ウィンドウが表示されていない場合に、フォーカスがコメント ウィンドウに移動しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-565">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>
- <span data-ttu-id="63b96-566">開いている複数のドキュメントの間で切り替えを行うと、あるドキュメントのコメントが、開かれている別のドキュメントに表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-566">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>
- <span data-ttu-id="63b96-567">ユーザーがコメントの下書きを作成して、解決済みのコメントが既に含まれている行にアンカーすると、サイドトラックでは解決済みのコメントに対して正しくない順番で下書きが並べ替えられる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-567">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>
- <span data-ttu-id="63b96-568">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-568">We fixed an issue where long links were not being wrapped when saving a document to HTML format.</span></span>
- <span data-ttu-id="63b96-569">AutoOpen が AutoExec. より前に実行されるというマクロの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-569">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>

[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2009-august-28"></a><span data-ttu-id="63b96-571">バージョン 2009: 8 月 28 日</span><span class="sxs-lookup"><span data-stu-id="63b96-571">Version 2009: August 28</span></span>
<span data-ttu-id="63b96-572">*バージョン 2009 (ビルド 13219.20004)*</span><span class="sxs-lookup"><span data-stu-id="63b96-572">*Version 2009 (Build 13219.20004)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-574">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-574">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-575">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-575">Outlook</span></span>

- <span data-ttu-id="63b96-576">1 つ以上のメッセージを選択した場合に、OneNote に "転送不可" ポリシーが適用されているメール コンテンツを送信することができるようになっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-576">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-577">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-577">PowerPoint</span></span>

- <span data-ttu-id="63b96-578">ビデオを挿入する機能が無効になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-578">We fixed an issue where the functionality to insert a video was disabled.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-579">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-579">Word</span></span>

- <span data-ttu-id="63b96-580">コメントの選択時に、ヘッダー/フッターを閉じることができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-580">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>
- <span data-ttu-id="63b96-581">サイドトラックのスクロールが機能しないため、サイドトラックの境界を超えたコメントのスレッドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-581">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>
- <span data-ttu-id="63b96-582">サイドトラック ウィンドウで解決済みのコメントを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-582">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-583">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-583">Office Suite</span></span>

- <span data-ttu-id="63b96-584">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-584">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>
- <span data-ttu-id="63b96-585">[図の圧縮] ダイアログで、ユーザーが選択した一部の DPI 設定が保持されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-585">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-21"></a><span data-ttu-id="63b96-587">バージョン 2009: 8 月 21 日</span><span class="sxs-lookup"><span data-stu-id="63b96-587">Version 2009: August 21</span></span>
<span data-ttu-id="63b96-588">*バージョン 2009 (ビルド 13212.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-588">*Version 2009 (Build 13212.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-590">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-590">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-591">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-591">Excel</span></span>

- <span data-ttu-id="63b96-592">**Excel のアクション ペン:** ペン ツールを使用すると、データを手書きしてすばやく編集できます</span><span class="sxs-lookup"><span data-stu-id="63b96-592">**Action Pen in Excel:** Pen Tool to help you handwrite and make quick edits to your data</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-593">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-593">Outlook</span></span>

- <span data-ttu-id="63b96-594">**メッセージの所有者として会話を削除する:** この機能を使用すると、メッセージの所有者による会話を削除できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-594">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-597">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-597">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-598">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-598">Access</span></span>

- <span data-ttu-id="63b96-599">ODBC データベースへの接続がサードパーティ製アプリケーションで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-599">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-600">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-600">Excel</span></span>

- <span data-ttu-id="63b96-601">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="63b96-601">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>
- <span data-ttu-id="63b96-602">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-602">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-603">Outlook</span></span>

- <span data-ttu-id="63b96-604">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-604">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-605">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-605">Word</span></span>

- <span data-ttu-id="63b96-606">コメントが削除された後に Word がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-606">We fixed an issue where Word could crash after comments were deleted.</span></span>
- <span data-ttu-id="63b96-607">メールで箇条書きが正しく表示されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-607">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-14"></a><span data-ttu-id="63b96-609">バージョン 2009: 8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="63b96-609">Version 2009: August 14</span></span>
<span data-ttu-id="63b96-610">*バージョン 2009 (ビルド 13205.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-610">*Version 2009 (Build 13205.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-612">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-612">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-613">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-613">Excel</span></span>

- <span data-ttu-id="63b96-614">ユーザーがかっこを含む数式名を入力し、F1 を介してヘルプを呼び出した場合、その数式に固有のヘルプ トピックが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-614">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>
- <span data-ttu-id="63b96-615">古いバージョンのファイルを復元した後、ボタンに割り当てられたマクロが壊れる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-615">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-616">Outlook</span></span>

- <span data-ttu-id="63b96-617">この変更により、ユーザーがタブを会議ページからスケジュール アシスタント ページに切り替えた後も会議ページが引き続き表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-617">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-618">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-618">Word</span></span>

- <span data-ttu-id="63b96-619">箇条書きのアイコンが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-619">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-07"></a><span data-ttu-id="63b96-621">バージョン 2009: 8 月 7 日</span><span class="sxs-lookup"><span data-stu-id="63b96-621">Version 2009: August 07</span></span>
<span data-ttu-id="63b96-622">*バージョン 2009 (ビルド 13130.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-622">*Version 2009 (Build 13130.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-624">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-624">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-625">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-625">Outlook</span></span>

- <span data-ttu-id="63b96-626">Active Directory の "otherTelephone" および "otherHomePhone" のユーザー アカウント属性が、対応する Outlook LDAP 属性にマッピングされていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-626">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-627">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-627">PowerPoint</span></span>

- <span data-ttu-id="63b96-628">特定の条件下でリボンまたはタイトル バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-628">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-31"></a><span data-ttu-id="63b96-630">バージョン 2008: 7 月 31 日</span><span class="sxs-lookup"><span data-stu-id="63b96-630">Version 2008: July 31</span></span>
<span data-ttu-id="63b96-631">*バージョン 2008 (ビルド 13127.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-631">*Version 2008 (Build 13127.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-633">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-633">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-634">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-634">Excel</span></span>

- <span data-ttu-id="63b96-635">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-635">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="63b96-636">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="63b96-636">No conversion required.</span></span><br /><span data-ttu-id="63b96-637">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-637">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-638">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-638">Outlook</span></span>

- <span data-ttu-id="63b96-639">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-639">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="63b96-640">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="63b96-640">No conversion required.</span></span><br /><span data-ttu-id="63b96-641">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-641">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-642">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-642">PowerPoint</span></span>

- <span data-ttu-id="63b96-643">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-643">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="63b96-644">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="63b96-644">No conversion required.</span></span><br /><span data-ttu-id="63b96-645">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-645">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="word"></a><span data-ttu-id="63b96-646">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-646">Word</span></span>

- <span data-ttu-id="63b96-647">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-647">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="63b96-648">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="63b96-648">No conversion required.</span></span><br /><span data-ttu-id="63b96-649">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-649">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-652">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-652">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-653">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-653">Access</span></span>

- <span data-ttu-id="63b96-654">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="63b96-654">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex.'</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-655">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-655">Excel</span></span>

- <span data-ttu-id="63b96-656">グラフ系列の順序を変更した場合、系列に並んだチェックボックスが系列に沿って並び替えられない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-656">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>
- <span data-ttu-id="63b96-657">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-657">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-658">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-658">Outlook</span></span>

- <span data-ttu-id="63b96-659">この修正プログラムでは、ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-659">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>
- <span data-ttu-id="63b96-660">この修正プログラムでは、Outlook のMarkdown コンテンツでは改行が正常に表示されない問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="63b96-660">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-661">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-661">PowerPoint</span></span>

- <span data-ttu-id="63b96-662">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-662">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="63b96-663">Office ストアへのアクセスが許可されていない場合に、PowerPoint の [フォーム] ボタンでフォームを作成できないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-663">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to the Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-664">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-664">Project</span></span>

- <span data-ttu-id="63b96-665">SharePoint のタスクリストで、2番目のタブにあるリボン ボタンが無効になる場合がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-665">We fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-666">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-666">Word</span></span>

- <span data-ttu-id="63b96-667">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-667">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="63b96-668">変更を追跡するコメントが追加された場合に、[変更履歴] ウィンドウが予期せず開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-668">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>
- <span data-ttu-id="63b96-669">[挿入]、[リンク] ドロップダウンを通して、ドキュメントへのリンクがコメントボックスに挿入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-669">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>
- <span data-ttu-id="63b96-670">ハイパーリンクを含む画像を追加した後に、VBA のハイパーリンク コレクションにあるハイパーリンク数が正しく指定されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-670">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-24"></a><span data-ttu-id="63b96-672">バージョン 2008: 7 月 24 日</span><span class="sxs-lookup"><span data-stu-id="63b96-672">Version 2008: July 24</span></span>
<span data-ttu-id="63b96-673">*バージョン 2008 (ビルド 13117.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-673">*Version 2008 (Build 13117.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-675">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-675">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-676">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-676">Excel</span></span>

- <span data-ttu-id="63b96-677">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="63b96-677">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="63b96-678">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-678">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-681">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-681">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="63b96-682">OneNote</span><span class="sxs-lookup"><span data-stu-id="63b96-682">OneNote</span></span>

- <span data-ttu-id="63b96-683">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="63b96-683">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-684">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-684">Word</span></span>

- <span data-ttu-id="63b96-685">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="63b96-685">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>
- <span data-ttu-id="63b96-686">変更履歴の記録の[特定のユーザー]オプションが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-686">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>
- <span data-ttu-id="63b96-687">HTML ファイルを開くときに、時々切断される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-687">We fixed an occasional hang while opening HTML files.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-17"></a><span data-ttu-id="63b96-689">バージョン 2008: 7 月 17 日</span><span class="sxs-lookup"><span data-stu-id="63b96-689">Version 2008: July 17</span></span>
<span data-ttu-id="63b96-690">*バージョン 2008 (ビルド 13115.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-690">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-692">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-692">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-693">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-693">Excel</span></span>

- <span data-ttu-id="63b96-694">引き出し線が非表示のピボット グラーフが保存されて再度開かれると、引き出し線が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-694">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="63b96-695">ブックの VBA を介して「ForceFullCalculation」が有効になっていると、グラフが常に期待どおりに更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-695">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-696">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-696">Outlook</span></span>

- <span data-ttu-id="63b96-697">Outlook で同じメール ドメインから複数のプロファイルを作成することに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-697">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="63b96-698">S/MIME 暗号化メッセージのヘッダーにロック アイコンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-698">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="63b96-699">暗号化されずに送信されたときに添付ファイルが S/MIME メッセージから削除される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-699">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="63b96-700">送信時にプレーン テキストの S/MIME メッセージが文字化けする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-700">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="63b96-701">暗号化されていない S/MIME メールを送信すると添付ファイルが破損する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-701">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="63b96-702">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-702">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="63b96-703">送信者から名前を付けて保存のアクセス許可が付与されている場合でも、受信者が権利保護されたメッセージを保存できなくなる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-703">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="63b96-704">一部の言語で一部の高度な検索のオプションのラベルが切り捨てられる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-704">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-705">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-705">Project</span></span>

- <span data-ttu-id="63b96-706">[タスク ボード] ビューに一覧表示されているタスクが [リソースの割り当て] ダイアログのタスクと同期していない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-706">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="63b96-707">複数の依存関係があるタスクをコピーして貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-707">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-708">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-708">Word</span></span>

- <span data-ttu-id="63b96-709">フォーカスがコメント テキスト ボックスにあるときに「エディター」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-709">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="63b96-710">フォーカスがコメント テキスト ボックスにあるときに「変更履歴と​​コメントの表示」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-710">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="63b96-711">ドキュメントを開くとコメントの状態が失われる可能性があるカスタム XML の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-711">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-712">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-712">Office Suite</span></span>

- <span data-ttu-id="63b96-713">ユーザーがタスクバーから新しいアプリ ウィンドウを開いて新しい空白のドキュメントを作成した後、追加のファイルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-713">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="63b96-714">ユーザーがドキュメントを編集していて権限を失っていた場合、再認証が必要であることをユーザーに通知しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-714">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2008-july-10"></a><span data-ttu-id="63b96-716">バージョン 2008: 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="63b96-716">Version 2008: July 10</span></span>
<span data-ttu-id="63b96-717">*バージョン 2008 (ビルド 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-717">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-719">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-719">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-720">Outlook</span></span>

- <span data-ttu-id="63b96-721">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-721">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="63b96-722">ユーザーが適切な印刷権限を持っていても、印刷ボタンが無効な状態で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-722">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-723">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-723">Project</span></span>

- <span data-ttu-id="63b96-724">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存しようとしても、何も起こらない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-724">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-725">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-725">Word</span></span>

- <span data-ttu-id="63b96-726">テキストとの画像をコメントボックスに貼り付けると Word が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-726">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="63b96-727">最後のコメントを削除すると [新しいコメント] ボタンが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-727">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-03"></a><span data-ttu-id="63b96-729">バージョン 2007: 7 月 3 日</span><span class="sxs-lookup"><span data-stu-id="63b96-729">Version 2007: July 03</span></span>
<span data-ttu-id="63b96-730">*バージョン 2007 (ビルド 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="63b96-730">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-732">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-732">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-733">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-733">Outlook</span></span>

- <span data-ttu-id="63b96-734">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します [詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="63b96-734">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="63b96-735">**新しい会議室の検索機能:** これまでと違うさまざまな機能で会議室を検索できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-735">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-738">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-738">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-739">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-739">Excel</span></span>

- <span data-ttu-id="63b96-740">テーブルに関連付けられたクエリが編集されていない場合でも、特定のバージョンの Excel で作成したデータ モデル テーブルが [テーブル プレビュー] に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-740">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="63b96-741">[名前の定義] \ [名前の適用] ダイアログで [相対/絶対を無視] 参照を無効にすると数式が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-741">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="63b96-742">高度なデータ フィルターをクリアするとテーブルの書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-742">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="63b96-743">埋め込まれた PDF 文書のフル パスがファイル名だけでなく文書の標題に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-743">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="63b96-744">Wolfram クラウド コネクターを無効にしてから、Excel ブックを保存してもう一度開くとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-744">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="63b96-745">ソルバー アドインを有効にして Excel を起動するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-745">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-746">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-746">Outlook</span></span>

- <span data-ttu-id="63b96-747">「To」行に 130 人を超える受信者がいる場合に Outlook がハングする問題を修正し、テキストのレンダリングのパフォーマンスも改善しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-747">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="63b96-748">2 日を超えるイベントはそれ以降のすべての日に同じ終了時刻を表示するという「To Do バー」の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-748">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="63b96-749">Outlook のユーザーが共有の予定表を使用した後、メッセージ一覧の更新が数分間停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-749">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-750">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-750">PowerPoint</span></span>

- <span data-ttu-id="63b96-751">スライドのテキスト領域に HTML を貼り付けると、代わりにスライドの上部に作成されたテキスト ボックスに貼り付けられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-751">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="63b96-752">発表者ビューですべてのスライドを選択し、Alt + Tabを使用して発表者ビューを終了し、スライド ショーに戻って [ショーの終了] をクリックすると、未処理の例外が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-752">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-753">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-753">Project</span></span>

- <span data-ttu-id="63b96-754">特定の XML ファイルを開くと、Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-754">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="63b96-755">ライブラリがモダン モードの場合、SharePoint ドキュメント ライブラリから Project ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-755">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="63b96-756">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-756">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-757">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-757">Word</span></span>

- <span data-ttu-id="63b96-758">マージの競合があり、ユーザーが既に変更を破棄することを選択している場合の共同編集モード中の問題を修正し、変更を保存または破棄するオプションを表示しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-758">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="63b96-759">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても「WRO0004.docx」というファイル名で保存されるため、その文書を使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-759">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-26"></a><span data-ttu-id="63b96-761">バージョン 2007: 6月 26 日</span><span class="sxs-lookup"><span data-stu-id="63b96-761">Version 2007: June 26</span></span>
<span data-ttu-id="63b96-762">*バージョン 2007 (ビルド 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="63b96-762">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-764">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-764">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-765">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-765">Access</span></span>

- <span data-ttu-id="63b96-766">リンクされた SQL テーブルが更新された場合、リンクされたテーブル マネージャーが主キーを要求する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-766">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="63b96-767">クエリ エディターのクエリがスクロールして表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-767">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="63b96-768">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-768">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-769">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-769">Outlook</span></span>

- <span data-ttu-id="63b96-770">ユーザーが配布リストの「送信」または「代理送信」ができなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-770">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="63b96-771">メッセージに画像をインラインで挿入し、メッセージを下書きとして保存すると画像のサイズが変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-771">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="63b96-772">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-772">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-773">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-773">Project</span></span>

- <span data-ttu-id="63b96-774">政府機関向けコミュニティのクラウド環境でプロジェクト プランナのリンクが無効になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-774">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-775">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-775">Office Suite</span></span>

- <span data-ttu-id="63b96-776">スケーラブル ベクター グラフィックス （SVG）に挿入されたテキストを、Word、Excel、または PowerPoint ファイルに挿入し、ファイルを保存して閉じ、再度開いた後、判読できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-776">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-19"></a><span data-ttu-id="63b96-778">バージョン 2007: 6月 19 日</span><span class="sxs-lookup"><span data-stu-id="63b96-778">Version 2007: June 19</span></span>
<span data-ttu-id="63b96-779">*バージョン 2007 (ビルド 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-779">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-781">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-781">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-782">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-782">Excel</span></span>

- <span data-ttu-id="63b96-783">SharePoint/OneDriveにブックを保存すると、ユーザー設定のリボンタブの CustomUI XML が削除される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-783">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="63b96-784">ファイルが読み取り専用である場合にのみ、ブックが読み取り専用であった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-784">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-785">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-785">Outlook</span></span>

- <span data-ttu-id="63b96-786">解像度の異なる複数のモニターを使用している場合に、Input Method Editor (IME) ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-786">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="63b96-787">以前に保存した予定を閉じると、次のエラーが表示される問題を修正しました。「別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。</span><span class="sxs-lookup"><span data-stu-id="63b96-787">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="63b96-788">アイテムの既定のフォルダーにコピーしますか? 」</span><span class="sxs-lookup"><span data-stu-id="63b96-788">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="63b96-789">日本のユーザーに対してミニ カレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-789">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="63b96-790">予定表のリマインダーで、1 週間以内に行われる会議の正確な時刻が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-790">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-791">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-791">PowerPoint</span></span>

- <span data-ttu-id="63b96-792">ライブの共同編集セッション中に共同編集ギャラリーでユーザーのプレゼンス カラー インジケーターが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-792">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-793">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-793">Project</span></span>

- <span data-ttu-id="63b96-794">固定期間タスクが 100% 完了しているが、実際の完了が指定されていない場合、タスク完了率が 100% 未満として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-794">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-795">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-795">Word</span></span>

- <span data-ttu-id="63b96-796">HTML ハイパーリンクの色が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-796">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-797">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-797">Office Suite</span></span>

- <span data-ttu-id="63b96-798">http または https ベースではない URL が最近使用したリストに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-798">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-12"></a><span data-ttu-id="63b96-800">バージョン 2007: 6月 12 日</span><span class="sxs-lookup"><span data-stu-id="63b96-800">Version 2007: June 12</span></span>
<span data-ttu-id="63b96-801">*バージョン 2007 (ビルド 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-801">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-803">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-803">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-804">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-804">Excel</span></span>

- <span data-ttu-id="63b96-805">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-805">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="63b96-806">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="63b96-806">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="63b96-807">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="63b96-807">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="63b96-808">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-808">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="63b96-809">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-809">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-812">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-812">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-813">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-813">Access</span></span>

- <span data-ttu-id="63b96-814">Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できず、行が削除されたと誤って報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-814">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-815">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-815">Excel</span></span>

- <span data-ttu-id="63b96-816">レーダーチャートの主要な目盛線が正しく書式設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-816">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-817">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-817">Project</span></span>

- <span data-ttu-id="63b96-818">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-818">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="63b96-819">ベースラインのリセットまたは更新により、時間単位の予算コスト/作業リソースが変更され、ベースラインが誤った予算値を反映する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-819">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-820">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-820">Word</span></span>

- <span data-ttu-id="63b96-821">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式設定をクリアする機能が動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-821">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="63b96-822">ルーラーが表示されていないときにテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションが点滅し始める問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-822">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="63b96-823">共同編集モードで、コメントの返信がコメント ウィンドウに表示されず、変更履歴ウィンドウに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-823">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="63b96-824">Wordに 50 を超える頻繁に開かれる文書のリストがある場合、文書を保存して開いた後、その文書に変更が加えられていなくても、変更履歴が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-824">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-05"></a><span data-ttu-id="63b96-826">バージョン 2006: 6 月 5 日</span><span class="sxs-lookup"><span data-stu-id="63b96-826">Version 2006: June 05</span></span>
<span data-ttu-id="63b96-827">*バージョン 2006 (ビルド 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-827">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-829">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-829">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-830">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-830">Excel</span></span>

- <span data-ttu-id="63b96-831">**Excel での共同作業中の並べ替え/フィルター処理:** Excel ファイルの並べ替えとフィルター処理を他のユーザーと行うことができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-831">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="63b96-832">この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="63b96-832">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="63b96-833">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-833">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="63b96-834">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-834">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="63b96-835">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="63b96-835">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="63b96-836">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-836">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="63b96-837">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-837">Outlook</span></span>

- <span data-ttu-id="63b96-838">**以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-838">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="63b96-839">Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="63b96-839">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="63b96-840">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="63b96-840">This feature is on by default.</span></span> <span data-ttu-id="63b96-841">オフにするには、[オプション] > [一般] > [開始オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="63b96-841">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-844">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-844">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-845">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-845">Excel</span></span>

- <span data-ttu-id="63b96-846">グラフの軸にカスタム値が正しく適用されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-846">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="63b96-847">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-847">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-848">Outlook</span></span>

- <span data-ttu-id="63b96-849">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-849">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="63b96-850">新しいメール メッセージの作成時にテンプレートを表示するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-850">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="63b96-851">Outlook バージョン1911以降、ユーザーが Exchange 2010のパブリック フォルダーを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-851">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="63b96-852">Office リボンのグループ予定表の [分類] ボタンが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-852">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="63b96-853">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-853">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="63b96-854">高 DPI のモニターを使用しているユーザーに対して、フォルダー プロパティの [オンライン アーカイブ] ドロップダウンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-854">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="63b96-855">テキスト形式のメールでハイパーリンクを使用して作業しているときに、Outlook でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-855">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="63b96-856">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-856">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="63b96-857">スクリーン リーダーを使用すると、Outlook ユーザーに断続的なハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-857">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-858">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-858">PowerPoint</span></span>

- <span data-ttu-id="63b96-859">サーバ構成のファイルをフォームベースの認証で開くときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-859">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="63b96-860">グラフまたはブックが埋め込まれた PowerPoint ファイルの保存時にエラーが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-860">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="63b96-861">ユーザーによって終了されたコメント ウィンドウが自動的に再起動する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-861">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="63b96-862">1つのスライドからのスライド エディタが次のスライドに重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-862">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-863">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-863">Project</span></span>

- <span data-ttu-id="63b96-864">親計画が削除された後、孤立したタスクの削除や再割り当てができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-864">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-865">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-865">Word</span></span>

- <span data-ttu-id="63b96-866">コメント ウィンドウのタイムスタンプがシステム ロケールの時間に基づいていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-866">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="63b96-867">Web アプリとデスクトップ アプリケーションの間のコメントが同期していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-867">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2006-may-29"></a><span data-ttu-id="63b96-869">バージョン 2006: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="63b96-869">Version 2006: May 29</span></span>
<span data-ttu-id="63b96-870">*バージョン 2006 (ビルド 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-870">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="63b96-871">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-871">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-872">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-872">Outlook</span></span>

- <span data-ttu-id="63b96-873">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-873">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-874">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-874">PowerPoint</span></span>

- <span data-ttu-id="63b96-875">**PowerPoint でのストリーム ビデオのパフォーマンス向上:** ビデオの読み込み時間を最小限に抑え快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-875">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="63b96-876">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="63b96-876">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-879">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-879">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-880">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-880">Excel</span></span>

- <span data-ttu-id="63b96-881">OneDrive を起動すると Excel がシャットダウンすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-881">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="63b96-882">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-882">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="63b96-883">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-883">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="63b96-884">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押してスクロールした後、Excel が応答しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-884">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-885">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-885">PowerPoint</span></span>

- <span data-ttu-id="63b96-886">マウス ホイールを使用して拡大した後、スライドが中央に配置されていない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-886">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-887">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-887">Word</span></span>

- <span data-ttu-id="63b96-888">テキストのコピーと貼り付けがコメント ウィンドウに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-888">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="63b96-889">100% ズームでコメント ヒントの吹き出しがぼやけて見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-889">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="63b96-890">ポリシー Word 2007 以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集で失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-890">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="63b96-891">長いパス名 (32K を超える) のファイルが開かず、適切なエラー メッセージが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-891">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2006-may-22"></a><span data-ttu-id="63b96-893">バージョン 2006: 5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="63b96-893">Version 2006: May 22</span></span>
<span data-ttu-id="63b96-894">*バージョン 2006 (ビルド 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-894">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-896">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-896">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-897">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-897">Excel</span></span>

- <span data-ttu-id="63b96-898">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="63b96-898">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="63b96-899">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="63b96-899">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="63b96-900">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="63b96-900">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="63b96-901">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-901">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="63b96-902">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-902">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-903">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-903">PowerPoint</span></span>

- <span data-ttu-id="63b96-904">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="63b96-904">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="63b96-905">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="63b96-905">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="63b96-906">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="63b96-906">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="63b96-907">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-907">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="63b96-908">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-908">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="63b96-909">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-909">Word</span></span>

- <span data-ttu-id="63b96-910">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="63b96-910">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="63b96-911">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="63b96-911">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="63b96-912">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="63b96-912">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="63b96-913">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-913">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="63b96-914">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="63b96-914">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-917">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-917">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-918">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-918">Excel</span></span>

- <span data-ttu-id="63b96-919">アドインは、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-919">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="63b96-920">Excelとサード パーティの支援技術アプリケーションの一部との間でフォントを管理する際にメモリが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-920">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="63b96-921">選択ロックがない図形を含むワークシート上で、アドインがホスト アイテムを要求すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-921">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-922">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-922">Outlook</span></span>

- <span data-ttu-id="63b96-923">ユーザーがフォルダー間でアイテムを移動したときに、Folder.BeforeItemMove イベントが正常に起動しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-923">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="63b96-924">予定表のアイテムが午前 0 時のしきい値にまたがっていると、終日イベントとして表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-924">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="63b96-925">2 つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-925">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="63b96-926">ユーザーが予定表をゲスト ユーザーと共有できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-926">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-927">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-927">PowerPoint</span></span>

- <span data-ttu-id="63b96-928">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-928">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-929">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-929">Project</span></span>

- <span data-ttu-id="63b96-930">オプションをクリックすると Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-930">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-931">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-931">Word</span></span>

- <span data-ttu-id="63b96-932">コメント内のハイパーリンクが機能しなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-932">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="63b96-933">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-933">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="63b96-934">予定表用の WordMail に HTML を貼り付けできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-934">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="63b96-935">共同編集セッションのコメントに返信すると、Word がフリーズすることがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-935">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-15"></a><span data-ttu-id="63b96-937">バージョン 2006: 5 月 15 日</span><span class="sxs-lookup"><span data-stu-id="63b96-937">Version 2006: May 15</span></span>
<span data-ttu-id="63b96-938">*バージョン 2006 (ビルド 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-938">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-940">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-940">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-941">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-941">Excel</span></span>

- <span data-ttu-id="63b96-942">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="63b96-942">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="63b96-943">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-943">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

- <span data-ttu-id="63b96-944">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-944">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-945">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-945">Outlook</span></span>

- <span data-ttu-id="63b96-946">**必要なものだけを見つける:** フォルダー、送信者、日付、添付ファイル情報などのオプションで検索を絞り込みます。</span><span class="sxs-lookup"><span data-stu-id="63b96-946">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-947">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-947">PowerPoint</span></span>

- <span data-ttu-id="63b96-948">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="63b96-948">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="63b96-949">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="63b96-949">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="63b96-950">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="63b96-950">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="63b96-951">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-951">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="63b96-952">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-952">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-953">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-953">Word</span></span>

- <span data-ttu-id="63b96-954">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-954">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-957">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-957">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-958">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-958">Excel</span></span>
- <span data-ttu-id="63b96-959">ユーザーがマージされた列を削除したときのパフォーマンス時間が向上する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-959">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="63b96-960">使用可能なプリンターのリストでプリンター名が重複する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-960">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="63b96-961">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-961">PowerPoint</span></span>
- <span data-ttu-id="63b96-962">英語スイス (QWERTZ) キーボードを使用すると、キーボード ショートカットとスペル チェックが期待どおりに機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-962">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-963">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-963">Word</span></span>
- <span data-ttu-id="63b96-964">空白のドキュメントに新しいコメントを追加しても何も発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-964">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="63b96-965">100 個を超えるエントリを含むドキュメントにインデックスを挿入または更新すると、アプリケーションがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-965">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="63b96-966">カスタム xml 値を含むファイルを開くのが非常に遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-966">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-967">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-967">Office Suite</span></span>
- <span data-ttu-id="63b96-968">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-968">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-08"></a><span data-ttu-id="63b96-971">バージョン 2006: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="63b96-971">Version 2006: May 08</span></span>
<span data-ttu-id="63b96-972">*バージョン 2006 (ビルド 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-972">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-974">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-974">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-975">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-975">Excel</span></span>

- <span data-ttu-id="63b96-976">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-976">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-977">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-977">Outlook</span></span>

- <span data-ttu-id="63b96-978">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-978">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="63b96-979">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-979">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="63b96-980">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-980">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-981">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-981">PowerPoint</span></span>

- <span data-ttu-id="63b96-982">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-982">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="63b96-983">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-983">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="63b96-984">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-984">Word</span></span>

- <span data-ttu-id="63b96-985">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-985">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-988">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-988">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="63b96-989">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-989">Office Suite</span></span>

- <span data-ttu-id="63b96-990">OS のシャットダウン後、InTune を介した Office 365 ProPlus の展開が停止する問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-990">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-01"></a><span data-ttu-id="63b96-992">バージョン 2005: 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="63b96-992">Version 2005: May 01</span></span>
<span data-ttu-id="63b96-993">*バージョン 2005 (ビルド 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="63b96-993">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-995">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-995">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-996">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-996">Outlook</span></span>

- <span data-ttu-id="63b96-997">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="63b96-997">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="63b96-998">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="63b96-998">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="63b96-999">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-999">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1002">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1002">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-1003">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1003">Excel</span></span>

- <span data-ttu-id="63b96-1004">グラフのデータ テーブルの日付軸の値が正しく表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1004">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="63b96-1005">[ページ レイアウト] または [改ページ プレビュー] に移動した後に、改ページを無効にできなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1005">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="63b96-1006">系列のデータを含む列を非表示にしてから非表示を解除すると、グラフの線のスタイルが失われる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1006">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="63b96-1007">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1007">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="63b96-1008">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1008">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="63b96-1009">[Invert if negative]\(負の値を反転する\) オプションが有効になっていると、ピボット グラフのカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1009">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="63b96-1010">[Invert if negative]\(負の値を反転する\) オプションが選択されていると、ピボット グラフの単一のデータ ポイントに対するカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1010">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="63b96-1011">この変更により、CSV ファイルで "@" 文字をアップロードすると、その "@" 文字以降の文字列が数式に変換される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1011">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="63b96-1012">SEQUENCE 関数で小数点以下が正しく四捨五入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1012">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1013">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1013">Outlook</span></span>

- <span data-ttu-id="63b96-1014">Outlook デスクトップ クライアントで、ユーザーがクリックした非常に長いセーフリンクが、切り捨てにより読み込みに失敗する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1014">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="63b96-1015">DBCS (2 バイト文字セット) 文字を含む名前が付けられた Outlook フォルダーが、サーバーと同期するときに断続的に表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1015">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="63b96-1016">この問題が発生する場合は、Outlook を IMAP アカウントを使用して構成し、ロケールが日本語に設定されたシステム上で実行する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1016">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1017">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1017">PowerPoint</span></span>

- <span data-ttu-id="63b96-1018">ユーザーがコメントを作成したのに投稿せずにそのコメント ウィンドウを閉じ、新しいウィンドウを開いて、複数のスライドを移動してからそのウィンドウを閉じ、最後に、元のプレゼンテーションでコメント ウィンドウをもう一度開くと、下書きのコメントが利用できなくなっている問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1018">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-1019">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-1019">Project</span></span>

- <span data-ttu-id="63b96-1020">Project が Project Web App に接続されていて、小数点の記号がカンマの場合、タイム ラグを追加する際に TaskDependencies Add メソッドが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1020">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1021">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1021">Word</span></span>

- <span data-ttu-id="63b96-1022">コラボレーション モードのドキュメントにコメントを挿入しても正常に動作しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1022">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="63b96-1023">この変更により、@メンションがクリックされると連絡先カードが点滅する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1023">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="63b96-1024">下書きのコメントを含むドキュメントを閉じようとすると、その下書きのコメントを保存せずにドキュメントを閉じてもよいかユーザーに確認を求める問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1024">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="63b96-1025">このプロンプトをキャンセルすると、ドキュメントが開いたままになるのではなく、閉じられていました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1025">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="63b96-1026">投稿されたコメントを翻訳しようとすると、"Inserting translated text failed" (翻訳されたテキストの挿入に失敗しました) エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1026">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="63b96-1027">Web ビュー/イマーシブ リーダーでヒントをクリックすると、ヒントが既に表示されている場合でも一番上までスクロールしていました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1027">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="63b96-1028">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1028">This has been fixed.</span></span>
- <span data-ttu-id="63b96-1029">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても WRO0004.docx というファイル名で保存されるため、そのドキュメントを使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1029">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-24"></a><span data-ttu-id="63b96-1031">バージョン 2005: 4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1031">Version 2005: April 24</span></span>
<span data-ttu-id="63b96-1032">*バージョン 2005 (ビルド 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1032">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1034">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1034">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-1035">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1035">Excel</span></span>
- <span data-ttu-id="63b96-1036">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1036">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="63b96-1037">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1037">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1038">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1038">Outlook</span></span>
- <span data-ttu-id="63b96-1039">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1039">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="63b96-1040">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1040">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1041">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1041">PowerPoint</span></span>
- <span data-ttu-id="63b96-1042">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1042">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1043">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1043">Word</span></span>
- <span data-ttu-id="63b96-1044">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="63b96-1044">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="63b96-1045">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1045">This has been fixed.</span></span>
- <span data-ttu-id="63b96-1046">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1046">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-17"></a><span data-ttu-id="63b96-1048">バージョン 2005: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1048">Version 2005: April 17</span></span>
<span data-ttu-id="63b96-1049">*バージョン 2005 (ビルド 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1049">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1051">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1051">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-1052">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1052">Excel</span></span>
- <span data-ttu-id="63b96-1053">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="63b96-1053">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="63b96-1054">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="63b96-1054">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="63b96-1055">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1055">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="63b96-1056">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1056">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="63b96-1057">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1057">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="63b96-1058">OneNote</span><span class="sxs-lookup"><span data-stu-id="63b96-1058">OneNote</span></span>
- <span data-ttu-id="63b96-1059">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1059">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1060">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1060">Outlook</span></span>
- <span data-ttu-id="63b96-1061">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1061">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="63b96-1062">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1062">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="63b96-1063">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1063">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="63b96-1064">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="63b96-1064">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="63b96-1065">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1065">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="63b96-1066">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1066">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-1067">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-1067">Project</span></span>
- <span data-ttu-id="63b96-1068">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1068">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="63b96-1069">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1069">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="63b96-1070">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1070">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2004-april-10"></a><span data-ttu-id="63b96-1072">バージョン 2004: 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1072">Version 2004: April 10</span></span>
<span data-ttu-id="63b96-1073">*バージョン 2004 (ビルド 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1073">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-1075">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-1075">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="63b96-1076">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-1076">Access</span></span>

- <span data-ttu-id="63b96-1077">**[テーブルの表示] ダイアログ ボックスをバイパスし、作業ウィンドウに直接移動して、テーブルを効率よくリレーションシップやクエリに追加します。:** 4 つのタブをクリックして、名前を複数選択して、テキストで検索し、作業中に開いたままの作業ウィンドウからドラッグして、テーブルやクエリを追加 ます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1077">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-1078">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1078">Excel</span></span>

- <span data-ttu-id="63b96-1079">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="63b96-1079">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="63b96-1080">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="63b96-1080">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1081">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1081">Outlook</span></span>

- <span data-ttu-id="63b96-1082">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="63b96-1082">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="63b96-1083">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="63b96-1083">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="63b96-1084">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1084">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1085">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1085">PowerPoint</span></span>

- <span data-ttu-id="63b96-1086">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="63b96-1086">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="63b96-1087">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="63b96-1087">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="63b96-1088">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1088">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1089">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1089">Word</span></span>

- <span data-ttu-id="63b96-1090">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="63b96-1090">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="63b96-1091">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="63b96-1091">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="63b96-1092">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1092">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="63b96-1093">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1093">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1096">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1096">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-1097">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-1097">Access</span></span>

- <span data-ttu-id="63b96-1098">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1098">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-1099">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1099">Excel</span></span>

- <span data-ttu-id="63b96-1100">シートのセル範囲を選択すると、1 つのセルが選択されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1100">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="63b96-1101">X 軸の範囲に合わせてグラフのサイズを小さくすると、Excel が応答を停止する可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1101">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="63b96-1102">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1102">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="63b96-1103">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1103">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="63b96-1104">R1C1 セルの参照が有効になっている Excel シートが共同編集/共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動すると、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1104">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1105">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1105">Outlook</span></span>

- <span data-ttu-id="63b96-1106">メール メッセージからカテゴリが消えることがあるという問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1106">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="63b96-1107">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1107">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="63b96-1108">ユーザーが組織フォームのプロパティを表示とするときにクラッシュするという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1108">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="63b96-1109">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが発生しないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1109">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1110">PowerPoint</span></span>

- <span data-ttu-id="63b96-1111">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1111">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="63b96-1112">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1112">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="63b96-1113">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1113">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-1114">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-1114">Project</span></span>

- <span data-ttu-id="63b96-1115">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1115">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1116">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1116">Word</span></span>

- <span data-ttu-id="63b96-1117">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1117">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="63b96-1118">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1118">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="63b96-1119">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1119">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="63b96-1120">この変更により、コメントを作成するとき、コメント アンカーが表示されない場合があるという 2 ページ表示の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1120">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="63b96-1121">スタイルがリストにリンクされている祖先のスタイルである段落の場合、そのリストの番号が失われる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1121">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-27"></a><span data-ttu-id="63b96-1123">バージョン 2004: 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1123">Version 2004: March 27</span></span>
<span data-ttu-id="63b96-1124">*バージョン 2004 (ビルド 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1124">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-1126">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-1126">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-1127">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1127">Outlook</span></span>

- <span data-ttu-id="63b96-1128">**メール作成時の @ メンションの候補表示を無効にするオプションが追加されました。** メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="63b96-1128">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="63b96-1129">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1129">Now you can turn it off if you prefer.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1132">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1132">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-1133">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1133">Outlook</span></span>
- <span data-ttu-id="63b96-1134">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1134">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="63b96-1135">ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1135">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="63b96-1136">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1136">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1137">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1137">PowerPoint</span></span>
- <span data-ttu-id="63b96-1138">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1138">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-1139">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-1139">Project</span></span>
- <span data-ttu-id="63b96-1140">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1140">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1141">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1141">Word</span></span>
- <span data-ttu-id="63b96-1142">この変更により、 [表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1142">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-20"></a><span data-ttu-id="63b96-1144">バージョン 2004: 3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1144">Version 2004: March 20</span></span>
<span data-ttu-id="63b96-1145">*バージョン 2004 (ビルド 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1145">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-1147">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-1147">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-1148">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1148">Outlook</span></span>

- <span data-ttu-id="63b96-1149">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="63b96-1149">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="63b96-1150">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1150">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="63b96-1151">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1151">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1152">PowerPoint</span></span>

- <span data-ttu-id="63b96-1153">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1153">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1156">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1156">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-1157">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1157">Excel</span></span>

- <span data-ttu-id="63b96-1158">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1158">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1159">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1159">Outlook</span></span>

- <span data-ttu-id="63b96-1160">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1160">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="63b96-1161">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1161">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="63b96-1162">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1162">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="63b96-1163">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1163">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="63b96-1164">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1164">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-1165">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-1165">Project</span></span>

- <span data-ttu-id="63b96-1166">ユーザーがスケジュール グループ内の [タスク] リボンにある「無効化」ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Applications (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1166">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="63b96-1167">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1167">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="63b96-1168">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="63b96-1168">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="63b96-1169">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1169">This behavior has been fixed.</span></span>

- <span data-ttu-id="63b96-1170">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1170">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="63b96-1171">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1171">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="63b96-1172">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1172">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="63b96-1173">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1173">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="63b96-1174">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1174">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1175">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1175">Word</span></span>

- <span data-ttu-id="63b96-1176">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1176">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="63b96-1177">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1177">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="63b96-1178">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1178">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="63b96-1179">この変更により、文書に記載されていない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1179">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="63b96-1180">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1180">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-13"></a><span data-ttu-id="63b96-1182">バージョン 2004: 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1182">Version 2004: March 13</span></span>
<span data-ttu-id="63b96-1183">*バージョン 2004 (ビルド 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1183">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-1185">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-1185">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1186">Excel</span></span>
- <span data-ttu-id="63b96-1187">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1187">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="63b96-1188">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-1188">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a><span data-ttu-id="63b96-1189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1189">PowerPoint</span></span>
- <span data-ttu-id="63b96-1190">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1190">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="63b96-1191">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-1191">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a><span data-ttu-id="63b96-1192">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1192">Word</span></span>
- <span data-ttu-id="63b96-1193">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1193">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="63b96-1194">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-1194">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1197">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1197">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="63b96-1198">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-1198">Access</span></span>
- <span data-ttu-id="63b96-1199">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1199">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-1200">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1200">Excel</span></span>
- <span data-ttu-id="63b96-1201">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1201">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="63b96-1202">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1202">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1203">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1203">Outlook</span></span>
- <span data-ttu-id="63b96-1204">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1204">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="63b96-1205">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1205">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="63b96-1206">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1206">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="63b96-1207">Project</span><span class="sxs-lookup"><span data-stu-id="63b96-1207">Project</span></span>
- <span data-ttu-id="63b96-1208">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1208">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="63b96-1209">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1209">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1210">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1210">Word</span></span>
- <span data-ttu-id="63b96-1211">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1211">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="63b96-1212">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1212">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="63b96-1213">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1213">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="63b96-1214">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1214">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-06"></a><span data-ttu-id="63b96-1216">バージョン 2003: 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1216">Version 2003: March 06</span></span>
<span data-ttu-id="63b96-1217">*バージョン 2003 (ビルド 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1217">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1219">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1219">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-1220">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1220">Outlook</span></span>

- <span data-ttu-id="63b96-1221">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1221">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="63b96-1222">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1222">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="63b96-1223">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1223">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1224">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1224">PowerPoint</span></span>

- <span data-ttu-id="63b96-1225">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1225">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="63b96-1226">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="63b96-1226">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1227">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1227">Word</span></span>

- <span data-ttu-id="63b96-1228">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1228">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-1229">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-1229">Office Suite</span></span>

- <span data-ttu-id="63b96-1230">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1230">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="63b96-1231">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1231">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2003-february-28"></a><span data-ttu-id="63b96-1234">バージョン 2003: 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1234">Version 2003: February 28</span></span>
<span data-ttu-id="63b96-1235">*バージョン 2003 (ビルド 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1235">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-1237">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-1237">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-1238">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1238">Outlook</span></span>

- <span data-ttu-id="63b96-1239">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1239">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="63b96-1240">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-1240">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="63b96-1241">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1241">PowerPoint</span></span>

- <span data-ttu-id="63b96-1242">**インクを図形に変換する作図エクスペリエンスの向上:** より良い図を描いて変換し、Office オブジェクトを操作できるようにします。[詳細情報](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="63b96-1242">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1245">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1245">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="63b96-1246">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1246">Excel</span></span>

- <span data-ttu-id="63b96-1247">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1247">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1248">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1248">Outlook</span></span>

- <span data-ttu-id="63b96-1249">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1249">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1250">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1250">Word</span></span>

- <span data-ttu-id="63b96-1251">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1251">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="63b96-1252">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1252">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="63b96-1253">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1253">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-1254">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-1254">Office Suite</span></span>

- <span data-ttu-id="63b96-1255">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1255">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-21"></a><span data-ttu-id="63b96-1257">バージョン 2003: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1257">Version 2003: February 21</span></span>
<span data-ttu-id="63b96-1258">*バージョン 2003 (ビルド 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1258">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-1260">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-1260">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="63b96-1261">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-1261">Office Suite</span></span>

- <span data-ttu-id="63b96-1262">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキスト ハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1262">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1265">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1265">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-1266">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1266">Excel</span></span>
- <span data-ttu-id="63b96-1267">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1267">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="63b96-1268">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1268">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="63b96-1269">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1269">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="63b96-1270">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1270">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="63b96-1271">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1271">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1272">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1272">Outlook</span></span>
- <span data-ttu-id="63b96-1273">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1273">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="63b96-1274">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1274">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="63b96-1275">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1275">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1276">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1276">Word</span></span>
- <span data-ttu-id="63b96-1277">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1277">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="63b96-1278">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="63b96-1278">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="63b96-1279">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="63b96-1279">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-1280">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-1280">Office Suite</span></span>
- <span data-ttu-id="63b96-1281">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1281">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="63b96-1282">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="63b96-1282">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="63b96-1283">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1283">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-14"></a><span data-ttu-id="63b96-1285">バージョン 2003: 2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1285">Version 2003: February 14</span></span>
<span data-ttu-id="63b96-1286">*バージョン 2003 (ビルド 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1286">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-1288">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-1288">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-1289">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1289">Outlook</span></span>

- <span data-ttu-id="63b96-1290">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="63b96-1290">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="63b96-1291">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1291">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1292">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1292">Word</span></span>

- <span data-ttu-id="63b96-1293">**描画ツールボックスでインク エディターを見つける**: [描画] を選択し、[インク エディター] ペンを選択して、指またはデジタル ペンでドキュメントを編集します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1293">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="63b96-1294">詳細情報</span><span class="sxs-lookup"><span data-stu-id="63b96-1294">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="63b96-1295">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-1295">Office Suite</span></span>

- <span data-ttu-id="63b96-1296">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました</span><span class="sxs-lookup"><span data-stu-id="63b96-1296">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1299">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1299">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="63b96-1300">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1300">Outlook</span></span>

- <span data-ttu-id="63b96-1301">ユーザーが「空き時間情報オプション」予定表のアクセス許可ダイアログにアクセスできなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1301">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="63b96-1302">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「申し訳ございません、このアイテムを開くことができません」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1302">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="63b96-1303">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1303">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="63b96-1304">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1304">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1305">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1305">PowerPoint</span></span>

- <span data-ttu-id="63b96-1306">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1306">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1307">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1307">Word</span></span>

- <span data-ttu-id="63b96-1308">ドキュメントを PDF にエクスポートすると、画像の透明性が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1308">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-07"></a><span data-ttu-id="63b96-1310">バージョン 2002: 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="63b96-1310">Version 2002: February 07</span></span>
<span data-ttu-id="63b96-1311">*バージョン 2002 (ビルド 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="63b96-1311">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="63b96-1313">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="63b96-1313">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="63b96-1314">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-1314">Access</span></span>

- <span data-ttu-id="63b96-1315">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="63b96-1315">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="63b96-1316">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1316">Search and replace text in SQL View.</span></span> <span data-ttu-id="63b96-1317">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1317">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="63b96-1320">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="63b96-1320">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="63b96-1321">Access</span><span class="sxs-lookup"><span data-stu-id="63b96-1321">Access</span></span>

- <span data-ttu-id="63b96-1322">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1322">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="63b96-1323">VB コードのレコーダー オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="63b96-1323">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="63b96-1324">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1324">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="63b96-1325">Excel</span><span class="sxs-lookup"><span data-stu-id="63b96-1325">Excel</span></span>

- <span data-ttu-id="63b96-1326">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1326">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="63b96-1327">Outlook</span><span class="sxs-lookup"><span data-stu-id="63b96-1327">Outlook</span></span>

- <span data-ttu-id="63b96-1328">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1328">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="63b96-1329">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1329">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="63b96-1330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="63b96-1330">PowerPoint</span></span>

- <span data-ttu-id="63b96-1331">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1331">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="63b96-1332">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1332">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="63b96-1333">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="63b96-1333">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="63b96-1334">Word</span><span class="sxs-lookup"><span data-stu-id="63b96-1334">Word</span></span>

- <span data-ttu-id="63b96-1335">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="63b96-1335">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="63b96-1336">ドキュメントが共同編集されている場合、ルート コメントのドラフト バージョンが保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1336">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="63b96-1337">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1337">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="63b96-1338">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1338">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="63b96-1339">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="63b96-1339">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="63b96-1340">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="63b96-1340">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="63b96-1341">Office スイート</span><span class="sxs-lookup"><span data-stu-id="63b96-1341">Office Suite</span></span>

- <span data-ttu-id="63b96-1342">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="63b96-1342">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|DevMain|Insiders| |16.0.13617.20002|version-2101-december-25|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13610.20002|version-2101-december-18|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13604.20000|version-2101-december-11|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13530.20000|version-2012-december-04|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13519.20000|version-2012-november-27|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13512.20000|version-2012-november-20|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13510.20004|version-2012-november-13|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13430.20000|version-2012-november-06|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13426.20004|version-2011-october-30|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13415.20002|version-2011-october-23|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
