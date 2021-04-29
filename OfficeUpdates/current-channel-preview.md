---
title: リリース ノートの最新チャネル (プレビュー)
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Slow の対象ユーザーに新機能、修正プログラム、または既知の問題の最新リストを提供します
ms.openlocfilehash: 81b0fd214752a3218809f860db9ad97f34d3ad0c
ms.sourcegitcommit: 6a6a10d50664c552f2aea560d521265d2b0677d2
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/27/2021
ms.locfileid: "52058741"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="5dd8e-103">Office 向けリリース ノートの最新チャネル (プレビュー)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="5dd8e-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project、Teams の最新チャネル (プレビュー版) ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="5dd8e-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="5dd8e-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって最新チャネル (プレビュー) に展開されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="5dd8e-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="5dd8e-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="5dd8e-109">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="5dd8e-110">詳細については、[こちらの記事](/DeployOffice/update-channels-changes)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-110">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>

> [!NOTE]
> - <span data-ttu-id="5dd8e-111">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-111">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="5dd8e-112">Microsoft Teams の機能は、リリース頻度が高いため、最新チャネル プレビュー版とは異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-112">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (削除しないでください)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2104-april-26"></a><span data-ttu-id="5dd8e-115">バージョン 2104: 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-115">Version 2104: April 26</span></span>
<span data-ttu-id="5dd8e-116">*バージョン 2104 (ビルド 13929.20254)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-116">*Version 2104 (Build 13929.20254)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-118">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-118">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-119">Outlook</span></span>

- <span data-ttu-id="5dd8e-120">**共有カレンダーの更新を有効にする**: Office 365 の共有カレンダーの場合、Outlook では REST API を使用してこれらのカレンダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-120">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="5dd8e-121">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-121">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-124">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-124">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-125">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-125">Excel</span></span>

- <span data-ttu-id="5dd8e-126">一部のファイルが保護されたビューで開かない可能性があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="5dd8e-126">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-127">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-127">Outlook</span></span>

- <span data-ttu-id="5dd8e-128">Outlook が OWA で構成された優先受信トレイの設定を上書きする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-128">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2104-april-19"></a><span data-ttu-id="5dd8e-130">バージョン 2104: 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-130">Version 2104: April 19</span></span>
<span data-ttu-id="5dd8e-131">*バージョン 2104 (ビルド 13929.20216)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-131">*Version 2104 (Build 13929.20216)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-133">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-133">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-134">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-134">Excel</span></span>

- <span data-ttu-id="5dd8e-135">**動的配列からのデータのインポート:** 現在のブックの動的配列からデータをインポート、整形、更新できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-135">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="5dd8e-136">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-136">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)

### <a name="outlook"></a><span data-ttu-id="5dd8e-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-137">Outlook</span></span>

- <span data-ttu-id="5dd8e-138">**改善された予定表の検索:** 予定表の検索が改善されました。最大のものは、検索結果でシリーズの次の出現をより簡単に見つける機能です。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-138">**Improved Calendar Search:** Improvements have been made to Calendar search, largest of which is the ability to more easily find the next occurence of a series in search results.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-141">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-141">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-142">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-142">Access</span></span>

- <span data-ttu-id="5dd8e-143">SQL Server パススルー クエリを実行すると、"無効なカーソル状態" があったことを示すエラー メッセージが表示されることがある問題がこの変更により修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-143">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


- <span data-ttu-id="5dd8e-144">外部アプリケーションがアクセシビリティ インターフェイスを要求した場合、そのインターフェイスが参照を解放するまでシャットダウンできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-144">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="5dd8e-145">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-145">Excel</span></span>

- <span data-ttu-id="5dd8e-146">保護されたシートに数式として貼り付けることができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-146">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


- <span data-ttu-id="5dd8e-147">ファイルを PDF ドキュメントとして保存すると、HYPERLINK 関数を使用して作成したハイパーリンクが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-147">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


- <span data-ttu-id="5dd8e-148">空の範囲を参照して暗黙の演算子 (@) 記号が数式に追加され、誤った結果が得られる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-148">We fixed an issue where an implicit operator (@) symbol would be added to the formula with a reference to an empty range and potentially give the incorrect result.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-149">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-149">Outlook</span></span>

- <span data-ttu-id="5dd8e-150">フォルダー階層の変更を同期するときに、Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-150">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="5dd8e-151">予定表を追加すると、ユーザーに "これにはしばらく時間がかかる場合があります" というメッセージが誤って表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-151">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="5dd8e-152">新しく追加した予定表で作成された会議の開催者として代理人が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-152">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="5dd8e-153">この状態の会議は、プリンシパルの予定表に表示されません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-153">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="5dd8e-154">ユーザーが検索時にクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-154">We fixed an issue that caused users to experience a crash when searching.</span></span>


- <span data-ttu-id="5dd8e-155">検索関連のクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-155">We fixed a search related crash.</span></span>


- <span data-ttu-id="5dd8e-156">署名の予期しない消去が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-156">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="5dd8e-157">作成中のメッセージが UI フォーカスを失ってしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-157">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="5dd8e-158">Outlook が OWA で構成された優先受信トレイの設定を上書きする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-158">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="5dd8e-159">新しいデバイスで Outlook を構成した後、クラウド設定機能のユーザーにカスタマイズされた設定が既定の設定で上書きされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-159">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="5dd8e-160">一部のユーザーがセカンダリ メール アカウントに関連付けられた署名にアクセスできなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-160">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="5dd8e-161">別のユーザーに代わって送信し、グローバル アドレス一覧ではないアドレス ブックに対して解決すると、名前解決が失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-161">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="5dd8e-162">別のユーザーに代わって送信し、グローバル アドレス一覧ではないアドレス ブックに対して解決すると、名前解決が失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-162">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-163">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-163">Project</span></span>

- <span data-ttu-id="5dd8e-164">日付の形式が W4/4 の場合、日付の選択に間違った日と年が表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-164">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="visio"></a><span data-ttu-id="5dd8e-165">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-165">Visio</span></span>

- <span data-ttu-id="5dd8e-166">終了時に Visio が動作を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-166">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="5dd8e-167">すべての結果を表示するように "図形の検索" 機能を修正しました</span><span class="sxs-lookup"><span data-stu-id="5dd8e-167">Fixed "Search Shape" feature to display all the results</span></span>



### <a name="word"></a><span data-ttu-id="5dd8e-168">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-168">Word</span></span>

- <span data-ttu-id="5dd8e-169">このバグでは、特定のポリシーは Office によって適用されません (テンプレートのグループが無効になっているはずのホーム ページに表示されています)。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-169">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled).</span></span> <span data-ttu-id="5dd8e-170">この修正により、ポリシーが適用されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-170">With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="5dd8e-171">ドキュメントの共同編集時に、コメント順序が変更されてもアクティブな下書きがクリアされません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-171">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="5dd8e-172">一部の国際言語で句読点と数字が間違った側に表示される Modern Commenting のバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-172">Fixed bug in Modern Commenting where punctuation and numbers would show up on the wrong side for some international languages.</span></span>


- <span data-ttu-id="5dd8e-173">'B' と ')' の組み合わせが自動的にサングラスをかけた絵文字に変わり、個々のキャラクターとして残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="5dd8e-173">Fixed an issue where the combination of 'B' and ')' would automatically turn into the sunglass wearing emoji and now remain as the individual characters</span></span>


- <span data-ttu-id="5dd8e-174">ローカルに保存されたファイルの自動保存の吹き出しのテキストを更新します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-174">Updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="5dd8e-175">共同編集中のコメントの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-175">We fixed an issue with comments during coauthoring.</span></span>


- <span data-ttu-id="5dd8e-176">コメント アイコンに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-176">We fixed an issue relating to comment icon.</span></span>


- <span data-ttu-id="5dd8e-177">貼り付けたテキストで、コピーと貼り付けのスタイルが同じにならない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-177">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


- <span data-ttu-id="5dd8e-178">提供されるテキスト予測の条件を最適化します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-178">Optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="5dd8e-179">ハイパーリンクに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-179">We fixed an issue relating to hyperlink.</span></span>


- <span data-ttu-id="5dd8e-180">読み取りモードでダークモード テーマを使用すると、一部の選択テキストは表示されません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-180">Some select text not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="5dd8e-181">自動保存の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-181">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="5dd8e-182">Application.OnTime で修正を行いましたが、正しくトリガーされない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-182">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-183">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-183">Office Suite</span></span>

- <span data-ttu-id="5dd8e-184">テキストの反復に関連するパフォーマンスの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-184">Fixed a performance issue related to iteration of text.</span></span>


- <span data-ttu-id="5dd8e-185">Office での GDI + LineJoinMiterClipped のサポートに関する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-185">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>


- <span data-ttu-id="5dd8e-186">このリリースでは、キーワードがドキュメントの最初の行にある場合の、行にまたがる機密コンテンツの処理が改善されています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-186">This release improves handling of line-spanning sensitive content when the keyword is on the first line of a document.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-april-13"></a><span data-ttu-id="5dd8e-188">バージョン 2103: 4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-188">Version 2103: April 13</span></span>
<span data-ttu-id="5dd8e-189">*バージョン 2103 (ビルド 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-189">*Version 2103 (Build 13901.20400)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-190">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-190">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="5dd8e-191">Teams</span><span class="sxs-lookup"><span data-stu-id="5dd8e-191">Teams</span></span>

- <span data-ttu-id="5dd8e-192">**動的なビュー** 動的なビューでは、Teams 会議で共有コンテンツとビデオ参加者を自動的に最適化します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-192">**Dynamic view** Dynamic view automatically optimizes shared content and video participants in Teams meetings.</span></span> <span data-ttu-id="5dd8e-193">新しいコントロールでは、共有コンテンツと特定の参加者を並べて表示する機能など、好みに合わせてビューをカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-193">New controls let you personalize the view to suit your preferences and needs, such as the ability to show shared content and specific participants side-by-side.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-april-10"></a><span data-ttu-id="5dd8e-195">バージョン 2103: 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-195">Version 2103: April 10</span></span>
<span data-ttu-id="5dd8e-196">*バージョン 2103 (ビルド 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-196">*Version 2103 (Build 13901.20400)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-198">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-199">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-199">Excel</span></span>

- <span data-ttu-id="5dd8e-200">画像を描画するときに、単語内のリソース競合の可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-200">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-201">Outlook</span></span>

- <span data-ttu-id="5dd8e-202">予定表を追加すると、ユーザーに "これにはしばらく時間がかかる場合があります" というメッセージが誤って表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-202">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>

- <span data-ttu-id="5dd8e-203">新しく追加した予定表で作成された会議の開催者として代理人が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-203">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="5dd8e-204">この状態の会議は、プリンシパルの予定表に表示されません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-204">Meetings in this state did not appear on the principal's calendar.</span></span>

- <span data-ttu-id="5dd8e-205">画像を描画するときに、単語内のリソース競合の可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-205">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-206">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-206">Powerpoint</span></span>

- <span data-ttu-id="5dd8e-207">画像を描画するときに、単語内のリソース競合の可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-207">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-208">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-208">Word</span></span>

- <span data-ttu-id="5dd8e-209">画像を描画するときに、単語内のリソース競合の可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-209">Fixed a potential resource contention issue in word when drawing an image.</span></span>

- <span data-ttu-id="5dd8e-210">印刷プレビュー中に応答がない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-210">Fixed a non-responsive issue while in Print preview.</span></span>

- <span data-ttu-id="5dd8e-211">ローカルに保存されたファイルの自動保存の吹き出しのテキストを更新します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-211">Updates text on autosave callout for files saved locally.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5dd8e-212">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-212">Office Suite</span></span>

- <span data-ttu-id="5dd8e-213">SyncBacked ファイルをオフラインで開いてから、ファイルを保存する前にアプリでファイルの名前を変更した際にエラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-213">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-april-02"></a><span data-ttu-id="5dd8e-215">バージョン 2103: 4 月 2 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-215">Version 2103: April 02</span></span>
<span data-ttu-id="5dd8e-216">*バージョン 2103 (ビルド 13901.20336)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-216">*Version 2103 (Build 13901.20336)*</span></span>
* <span data-ttu-id="5dd8e-217">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-217">Various bugs and performance fixes.</span></span>

## <a name="version-2103-april-1"></a><span data-ttu-id="5dd8e-218">バージョン 2103: 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-218">Version 2103: April 1</span></span>
<span data-ttu-id="5dd8e-219">*バージョン 2103 (ビルド 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-219">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-220">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-220">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="5dd8e-221">Teams</span><span class="sxs-lookup"><span data-stu-id="5dd8e-221">Teams</span></span>

- <span data-ttu-id="5dd8e-222">**日付/時刻形式** この更新により、Teams の日付/時刻形式は Mac および Windows オペレーティング システムの地域設定と一致します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-222">**Date/Time format** With this update, the date/time formats in Teams will match the Mac and Windows operating system regional settings.</span></span> <span data-ttu-id="5dd8e-223">以前は、Teams はアプリケーションの言語に対応する形式でのみ日付/時刻を表示していました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-223">Previously, Teams would only show date/time in the format corresponding to the application's language.</span></span> <span data-ttu-id="5dd8e-224">オペレーティング システムの予定表の設定に関係なく、グレゴリオ暦のみがサポートされていることに注意することが重要です。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-224">It's important to note that only the Gregorian calendar is supported regardless of the operating system's calendar setting.</span></span> 

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-march-30"></a><span data-ttu-id="5dd8e-226">バージョン 2103: 3 月 30 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-226">Version 2103: March 30</span></span>
<span data-ttu-id="5dd8e-227">*バージョン 2103 (ビルド 13901.20312)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-227">*Version 2103 (Build 13901.20312)*</span></span>
* <span data-ttu-id="5dd8e-228">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-228">Various bugs and performance fixes.</span></span>

## <a name="version-2103-march-28"></a><span data-ttu-id="5dd8e-229">バージョン 2103: 3 月 28 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-229">Version 2103: March 28</span></span>
<span data-ttu-id="5dd8e-230">*バージョン 2103 (ビルド 13901.20306)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-230">*Version 2103 (Build 13901.20306)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-232">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-232">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-233">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-233">Outlook</span></span>

- <span data-ttu-id="5dd8e-234">フォルダー階層の変更を同期するときに、Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-234">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="5dd8e-235">一部のユーザーがナビゲーション ウィンドウで予定表のプライマリとセカンダリ カレンダーの切り替え場所を表示する原因となる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-235">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください)

## <a name="version-2103-march-22"></a><span data-ttu-id="5dd8e-237">バージョン 2103: 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-237">Version 2103: March 22</span></span>
<span data-ttu-id="5dd8e-238">*バージョン 2103 (ビルド 13901.20230)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-238">*Version 2103 (Build 13901.20230)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-240">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-240">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-241">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-241">Outlook</span></span>

- <span data-ttu-id="5dd8e-242">ユーザーに予想よりも多くの署名が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-242">We fixed an issue that caused users to see more signatures than expected.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-march-15"></a><span data-ttu-id="5dd8e-244">バージョン 2103: 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-244">Version 2103: March 15</span></span>
<span data-ttu-id="5dd8e-245">*バージョン 2103 (ビルド 13901.20170)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-245">*Version 2103 (Build 13901.20170)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-247">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-247">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="5dd8e-248">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-248">Project</span></span>

- <span data-ttu-id="5dd8e-249">終了時に Visio が動作を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-249">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="5dd8e-250">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-250">Visio</span></span>

- <span data-ttu-id="5dd8e-251">終了時に Visio が動作を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-251">Fixed an issue where Visio could stop working during close.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
## <a name="version-2103-march-11"></a><span data-ttu-id="5dd8e-254">バージョン 2103: 3 月 11 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-254">Version 2103: March 11</span></span>
<span data-ttu-id="5dd8e-255">*バージョン 2103 (ビルド 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-255">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-256">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-257">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-257">Excel</span></span>

- <span data-ttu-id="5dd8e-258">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-258">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="5dd8e-259">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-259">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="5dd8e-260">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-260">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-261">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-261">Outlook</span></span>

- <span data-ttu-id="5dd8e-262">**会議室とワークスペースの新しい予約機能:** 会議室の予約機能が更新され、個々のワークスペースをスケジュールできる機能が追加されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-262">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-263">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-264">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-264">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="5dd8e-265">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-265">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="5dd8e-266">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-266">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="teams"></a><span data-ttu-id="5dd8e-267">Teams</span><span class="sxs-lookup"><span data-stu-id="5dd8e-267">Teams</span></span>

- <span data-ttu-id="5dd8e-268">**外出中の状態** 勤務時間外や休暇中のため、チャット メッセージに返信できないことを他のユーザーに知らせるメッセージを設定します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-268">**Out of Office status** Set up a message to let others know you're not working or on vacation so you're not available to reply when they send a chat message to you.</span></span> <span data-ttu-id="5dd8e-269">"外出中の状態"は、Outlook カレンダーの自動応答とも同期されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-269">Your Out of Office status will also sync with Automatic Replies in your Outlook calendar.</span></span>

### <a name="visio"></a><span data-ttu-id="5dd8e-270">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-270">Visio</span></span>

- <span data-ttu-id="5dd8e-271">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、製品のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-271">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="5dd8e-272">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-272">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="5dd8e-273">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-273">Word</span></span>

- <span data-ttu-id="5dd8e-274">**Word 文書のダーク モード:** ダーク モードは、ドキュメントでの作業中に目の疲れを軽減し、光感受性に対応するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-274">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="5dd8e-275">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-275">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="5dd8e-276">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-276">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="5dd8e-277">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-277">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-280">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-280">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-281">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-281">Access</span></span>

- <span data-ttu-id="5dd8e-282">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-282">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="5dd8e-283">外部アプリケーションがアクセシビリティ インターフェイスを要求した場合、そのインターフェイスが参照を解放するまでシャットダウンできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-283">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="5dd8e-284">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-284">Excel</span></span>

- <span data-ttu-id="5dd8e-285">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-285">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="5dd8e-286">画像を取得できないためにデータ型カードを表示しようとすると、Excel が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-286">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="5dd8e-287">日本語フォントで乗算または除算記号を使用すると、フォントが予期せず変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-287">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="5dd8e-288">文字をサポートしている場合は、引き続き同じフォントを使用します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-288">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="5dd8e-289">ユーザーが Excel ブックを PDF にエクスポートできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-289">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="5dd8e-290">[リンクされた画像を貼り付け] オプションを使用すると、画像が予想よりも小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-290">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="5dd8e-291">共同編集中にシートをコピーした際、一部の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-291">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="5dd8e-292">ブックを開いたときに予期せずメモが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-292">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="5dd8e-293">.xls または .xlt 形式で保存するときに、一部のピボットテーブル形式でブックが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-293">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-294">Outlook</span></span>

- <span data-ttu-id="5dd8e-295">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-295">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="5dd8e-296">新しいグループを作成した後、重複する予定表のグループが表示される原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-296">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="5dd8e-297">改善された共有カレンダーのユーザーが、カレンダーの色を黄色または茶色に設定できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-297">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="5dd8e-298">Outlook を再起動するまで、新しく追加された予定表がナビゲーション ウィンドウに表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-298">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="5dd8e-299">CSV にエクスポートするときに非 ASCII 文字が正しくエクスポートされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-299">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="5dd8e-300">一部のユーザーがセカンダリ メール アカウントに関連付けられた署名にアクセスできなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-300">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="5dd8e-301">新しいデバイスで Outlook を構成した後、クラウド設定機能のユーザーにカスタマイズされた設定が既定の設定で上書きされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-301">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="5dd8e-302">Unicode コンテンツを含む署名が破損するのをユーザーに表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-302">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="5dd8e-303">インライン翻訳のユーザーがフィードバックを送信できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-303">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="5dd8e-304">DRM 保護を削除すると、添付ファイルが重複するる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-304">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="5dd8e-305">メールを作成するときに、ユーザーが [名前の確認] で連絡先グループを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-305">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-306">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-306">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-307">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-307">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="5dd8e-308">PowerPoint スライドショー モードで折れ線グラフの矢印が期待どおりに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-308">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="5dd8e-309">アニメーションおよびオーディオ ブックマークのループの問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-309">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-310">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-310">Project</span></span>

- <span data-ttu-id="5dd8e-311">終了時に Visio が動作を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-311">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="5dd8e-312">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-312">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="5dd8e-313">100% 完了したタスクが 99% 完了に戻る問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-313">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="5dd8e-314">JAWS を実行しているときにタスク情報ダイアログに移動すると、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-314">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="5dd8e-315">インジケーター列が最初の列スポットにない場合、「サマリー タスクを切り取ると、サブタスクも削除されます」という警告が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-315">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="5dd8e-316">ユーザーがタイムシートで [タスクに自分自身を追加] 機能を選択した場合に、作成された割り当てで適切なリソース利用可能時間の単位が使用されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-316">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="5dd8e-317">Project Web App からローカル ファイルにプロジェクトを保存するときに、タスクの分割が誤って作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-317">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="5dd8e-318">これは、非標準の作業時間のタスク カレンダーが使用されていた場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-318">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="5dd8e-319">Publisher</span><span class="sxs-lookup"><span data-stu-id="5dd8e-319">Publisher</span></span>

- <span data-ttu-id="5dd8e-320">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-320">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="5dd8e-321">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-321">Visio</span></span>

- <span data-ttu-id="5dd8e-322">終了時に Visio が動作を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-322">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="5dd8e-323">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-323">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-324">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-324">Word</span></span>

- <span data-ttu-id="5dd8e-325">Microsoft Information Protection (MIP) ラベルで保護されたファイルを開くとき、MIP で保護されたラベルにアクセスできる ID にユーザーがサインインしていない場合、無期限にハングする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-325">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="5dd8e-326">ユーザーは、サインイン プロンプトを表示するためにオープンをキャンセルする必要があり、オープンはその時点以降にのみ成功します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-326">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="5dd8e-327">開く/ダウンロード中にサインイン プロンプトを表示できるようにすることで、この問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-327">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="5dd8e-328">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-328">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="5dd8e-329">新しい単語コメントでディクテーションを使用する際の問題を修正しました。コメント カードのディクテーション ボタンが正しくオンとオフを切り替えるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-329">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="5dd8e-330">ドキュメントの共同編集時に、コメント順序が変更されてもアクティブな下書きがクリアされません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-330">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="5dd8e-331">ユーザーがドキュメントにディクテーションしたときに単語の間にスペースが挿入されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-331">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="5dd8e-332">スクロールまたはズーム アニメーションを含むスクロール レイヤーに関連するレンダリング パイプラインの問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-332">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="5dd8e-333">3D 効果のあるアイコンと SVG グラフィックに適用される色の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-333">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="5dd8e-334">自動保存の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-334">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="5dd8e-335">脚注の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-335">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="5dd8e-336">RTL で入力された複数行のコメントを投稿すると、2 行目以降が右ではなく左に配置される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-336">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="5dd8e-337">複数のコメントの配置に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-337">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="5dd8e-338">[音声読み上げ] 作業ウィンドウの、キーボード ショートカットの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-338">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="5dd8e-339">段落をスキップする可能性があるナレーターの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-339">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="5dd8e-340">スペル チェックが 2 つの異なるスペル修正コンテキスト メニュー間で切り替わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-340">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="5dd8e-341">リッチ テキスト コンテンツ コントロールの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-341">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="5dd8e-342">非表示の段落の最後に入力すると、アプリケーションがハングする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-342">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="5dd8e-343">列のテキストが重複する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-343">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="5dd8e-344">ブックマークに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-344">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="5dd8e-345">共同編集中の競合を解決する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-345">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-346">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-346">Office Suite</span></span>

- <span data-ttu-id="5dd8e-347">OneDrive の場所は、グループ ポリシー設定に応じて適切にフィルター処理されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-347">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="5dd8e-348">数式を含むテキスト内でナレーターを使用すると発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-348">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="5dd8e-349">セッション 0 で実行されている Office アプリのサポートに関連する信頼性の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-349">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="5dd8e-350">セッション 0 で実行されている Office アプリのサポートに関連する信頼性の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-350">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="5dd8e-351">EMF 画像の読み込み時に発生する可能性がある無応答に関連した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-351">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-march-03"></a><span data-ttu-id="5dd8e-353">バージョン 2102: 3 月 3 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-353">Version 2102: March 03</span></span>
<span data-ttu-id="5dd8e-354">*バージョン 2102 (ビルド 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-354">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-356">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-356">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="5dd8e-357">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-357">Word</span></span>

- <span data-ttu-id="5dd8e-358">アイコンと SVG グラフィックに適用されるテーマ情報の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-358">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-march-01"></a><span data-ttu-id="5dd8e-360">バージョン 2102: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-360">Version 2102: March 01</span></span>
<span data-ttu-id="5dd8e-361">*バージョン 2102 (ビルド 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-361">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-363">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-363">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-364">Outlook</span></span>

- <span data-ttu-id="5dd8e-365">**Teams で共有:** Outlook からのメッセージを Teams 内のユーザーまたはチャネルと共有します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-365">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-368">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-368">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-369">Outlook</span></span>

- <span data-ttu-id="5dd8e-370">新しいグループを作成した後、重複する予定表のグループが表示される原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-370">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="5dd8e-371">改善された共有カレンダーのユーザーが、カレンダーの色を黄色または茶色に設定できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-371">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="5dd8e-372">一部のユーザーがメッセージ ウィンドウを閉じるときにアプリがシャットダウンする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-372">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="5dd8e-373">Unicode コンテンツを含む署名が破損するのをユーザーに表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-373">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="5dd8e-374">インライン翻訳のユーザーがフィードバックを送信できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-374">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-february-21"></a><span data-ttu-id="5dd8e-376">バージョン 2102: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-376">Version 2102: February 21</span></span>
<span data-ttu-id="5dd8e-377">*バージョン 2102 (ビルド 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-377">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-379">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-379">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-380">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-380">Outlook</span></span>

- <span data-ttu-id="5dd8e-381">**音声でメッセージの下書きを作成する:** 新しいディクテーション ツールバー、音声コマンド、自動句読点などを使用してメッセージを作成します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-381">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-382">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-382">Word</span></span>

- <span data-ttu-id="5dd8e-383">**音声で文書の下書きを作成する:** 新しいディクテーション ツールバー、音声コマンド、自動句読点を使用して文書の下書きを作成します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-383">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-386">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-386">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-387">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-387">Excel</span></span>

- <span data-ttu-id="5dd8e-388">[リンク画像を貼り付け] オプションを使用すると、画像が思っていたよりも小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-388">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-february-16"></a><span data-ttu-id="5dd8e-390">バージョン 2102: 2 月 16 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-390">Version 2102: February 16</span></span>
<span data-ttu-id="5dd8e-391">*バージョン 2102 (ビルド 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-391">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="5dd8e-392">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-392">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="5dd8e-393">バージョン 2102: 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-393">Version 2102: February 15</span></span>
<span data-ttu-id="5dd8e-394">*バージョン 2102 (ビルド 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-394">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-396">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-396">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-397">Outlook</span></span>

- <span data-ttu-id="5dd8e-398">**ディクテーションはより多くの言語で利用できます:** ディクテーションは 7 つの新しい言語をサポートするようになりました: ヒンディー語、ロシア語、ポーランド語、ポルトガル語 (ポルトガル)、韓国語、タイ語、中国語 (台湾)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-398">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-399">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-399">Word</span></span>

- <span data-ttu-id="5dd8e-400">**ディクテーションはより多くの言語で利用できます:** ディクテーションは 7 つの新しい言語をサポートするようになりました: ヒンディー語、ロシア語、ポーランド語、ポルトガル語 (ポルトガル)、韓国語、タイ語、中国語 (台湾)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-400">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-403">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-403">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-404">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-404">Excel</span></span>

- <span data-ttu-id="5dd8e-405">ユーザーが Excel ブックを PDF にエクスポートできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-405">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-406">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-406">Word</span></span>

- <span data-ttu-id="5dd8e-407">共同編集中の競合を解決する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-407">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2102-february-11"></a><span data-ttu-id="5dd8e-409">バージョン 2102: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-409">Version 2102: February 11</span></span>
<span data-ttu-id="5dd8e-410">*バージョン 2102 (ビルド 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-410">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-412">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-412">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="5dd8e-413">Teams</span><span class="sxs-lookup"><span data-stu-id="5dd8e-413">Teams</span></span>

- <span data-ttu-id="5dd8e-414">**Windows および Mac の Edge および Chrome ブラウザーの 2x2 ビデオ** ユーザーは、Windows および Mac の Edge および Chrome ブラウザーでのチーム会議において、最大 4 人の参加者のビデオを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-414">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="5dd8e-415">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-415">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="5dd8e-417">バージョン 2102: 2 月 8 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-417">Version 2102: February 08</span></span>
<span data-ttu-id="5dd8e-418">*バージョン 2102 (ビルド 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-418">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-420">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-420">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-421">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-421">Outlook</span></span>

- <span data-ttu-id="5dd8e-422">**Microsoft Search を利用した作成 (To\CC\BCC) の提案:** To\CC 行へのユーザーの追加は、Microsoft Search を利用するようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-422">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-425">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-425">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-426">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-426">Access</span></span>

- <span data-ttu-id="5dd8e-427">Access で選択したタブがよりはっきりと表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-427">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="5dd8e-428">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-428">Excel</span></span>

- <span data-ttu-id="5dd8e-429">ファイルを再度開いたときに、セルの連続していない範囲を使用する特定のグラフが読み込まれない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-429">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="5dd8e-430">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-430">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="5dd8e-431">グラフでデータ系列を選択した後に Excel が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-431">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="5dd8e-432">[名前の定義] ダイアログで名前を追加したときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-432">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="5dd8e-433">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-433">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-434">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-434">Outlook</span></span>

- <span data-ttu-id="5dd8e-435">デジタル署名のオプションのチェックを外した後も、メールがデジタル署名されたものとして送信される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-435">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="5dd8e-436">[暗号化のみ] オプションを使用して送信されたメールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-436">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-437">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-438">色付きの絵文字を表示すると発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-438">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="5dd8e-439">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-439">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="5dd8e-440">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-440">Visio</span></span>

- <span data-ttu-id="5dd8e-441">CAD ステンシルからの形状レンダリングに関するこの問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-441">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="5dd8e-442">ユーザーには、最新のビルドで解決された問題が表示されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-442">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-443">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-443">Word</span></span>

- <span data-ttu-id="5dd8e-444">これにより、インターネット接続が一定期間失われた後、リアルタイム入力とプレゼンスが復元されない問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-444">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="5dd8e-445">ユーザーがコメント内のテキストを選択すると、Word は他のコメント内の選択されたテキストの選択を解除するようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-445">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="5dd8e-446">Word でコメント テキストを Excel にコピーできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-446">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="5dd8e-447">VBA マクロ実行中に ExportAsFixedFormat2 が、"プレゼンテーション (不明のメンバー) の不正な値" というエラーを表示して失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-447">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="5dd8e-448">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-448">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="5dd8e-449">コメントがリンクで切り捨てられる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-449">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="5dd8e-450">SharePoint Online に保存する際に発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="5dd8e-450">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="5dd8e-451">Word 文書を PDF にエクスポートする際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-451">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="5dd8e-452">自動バックアップの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-452">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="5dd8e-453">DRM で保護されたファイルを共同編集する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-453">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-454">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-454">Office Suite</span></span>

- <span data-ttu-id="5dd8e-455">画像として箇条書きを挿入すると箇条書きが消える PowerPoint のバグを修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-455">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="5dd8e-456">この修正により、レンダリングの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-456">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="5dd8e-457">あるサインイン アカウントの機密ラベルを表示する必要があるときに、特定の状況で Office が別のサインイン アカウントの機密ラベルを表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-457">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-february-03"></a><span data-ttu-id="5dd8e-459">バージョン 2101: 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-459">Version 2101: February 03</span></span>
<span data-ttu-id="5dd8e-460">*バージョン 2101 (ビルド 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-460">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-462">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-462">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-463">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-463">Outlook</span></span>

- <span data-ttu-id="5dd8e-464">OWA に既定の正しい署名が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-464">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="5dd8e-465">[暗号化のみ] オプションを使用して送信されたメールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-465">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-february-02"></a><span data-ttu-id="5dd8e-467">バージョン 2101: 2 月 2 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-467">Version 2101: February 02</span></span>
<span data-ttu-id="5dd8e-468">*バージョン 2101 (ビルド 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-468">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-470">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-470">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-471">Outlook</span></span>

- <span data-ttu-id="5dd8e-472">クラウド設定のユーザーが設定を更新するときにハングする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-472">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-25"></a><span data-ttu-id="5dd8e-474">バージョン 2101: 1 月 25 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-474">Version 2101: January 25</span></span>
<span data-ttu-id="5dd8e-475">*バージョン 2101 (ビルド 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-475">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-477">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-477">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-478">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-478">Excel</span></span>

- <span data-ttu-id="5dd8e-479">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-479">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="5dd8e-480">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-480">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="5dd8e-481">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-481">Outlook</span></span>

- <span data-ttu-id="5dd8e-482">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-482">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="5dd8e-483">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-483">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-484">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-485">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-485">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="5dd8e-486">[詳細情報](/microsoft-365/compliance/sensitivity-labels) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-486">[Learn more](/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-487">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-487">Word</span></span>

- <span data-ttu-id="5dd8e-488">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-488">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="5dd8e-489">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-489">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-490">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-490">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-491">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-491">Outlook</span></span>

- <span data-ttu-id="5dd8e-492">プロファイルに大きな階層がある共有メールボックスまたは代理メールボックスを持つユーザーがハングする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-492">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



## <a name="version-2101-january-18"></a><span data-ttu-id="5dd8e-494">バージョン 2101: 1 月 18 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-494">Version 2101: January 18</span></span>
<span data-ttu-id="5dd8e-495">*バージョン 2101 (ビルド 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-495">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-499">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-499">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="5dd8e-500">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-500">Project</span></span>

- <span data-ttu-id="5dd8e-501">チーム プランナー ビューのタスクに枠が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-501">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="5dd8e-502">チーム プランナー ビューのタスクでドラッグ アンド ドロップが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-502">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-13"></a><span data-ttu-id="5dd8e-504">バージョン 2101: 1 月 13 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-504">Version 2101: January 13</span></span>
<span data-ttu-id="5dd8e-505">*バージョン 2101 (ビルド 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-505">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
### <a name="feature-updates"></a><span data-ttu-id="5dd8e-507">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-507">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="5dd8e-508">Teams</span><span class="sxs-lookup"><span data-stu-id="5dd8e-508">Teams</span></span>
- <span data-ttu-id="5dd8e-509">**その他のテーマ:** デスクトップと Web クライアントで新しいテーマを利用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-509">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="5dd8e-510">**PPT 共有:** Teams の発表者ツール Teams の共有トレイから PowerPoint ファイルを選択すると、発表者ツールが自動的に開きます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-510">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="5dd8e-511">簡単なアドホック スライド ナビゲーションのために、デッキ内すべてのスライドの現在のスライド、スライド ノート、サムネイル ストリップを表示できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-511">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="5dd8e-512">このビューは完全に背後で動作し、制御している発表者のみに表示されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-512">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="5dd8e-513">オーディエンスには、現在のスライド (大きな赤いボックスで強調表示)、またはオーディエンスが選択した移動先のスライド (オーディエンスのナビゲーションがお客様によってロックされていない場合) しか表示されません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-513">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="5dd8e-514">**Mac でデスクトップまたはウィンドウを共有する際に、コンピュータのサウンドを含める** Mac の Teams からデスクトップまたはウィンドウを共有するときに、コンピューターのサウンドを含めることができるようになりました。これにより、会議の参加者は、コンピューターから再生されるオーディオを聞くことができます。 </span><span class="sxs-lookup"><span data-stu-id="5dd8e-514">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="5dd8e-516">バージョン 2101: 1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-516">Version 2101: January 09</span></span>
<span data-ttu-id="5dd8e-517">*バージョン 2101 (ビルド 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-517">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-519">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-519">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-520">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-520">Outlook</span></span>

- <span data-ttu-id="5dd8e-521">**ワンクリック ライティング候補:** ワンクリックでライティング候補を適用します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-521">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="5dd8e-522">編集機能では、スペルチェックと文章校正を行い、ユーザーに文章を洗練されたものにするアイデアを提供します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-522">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="5dd8e-523">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-523">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="5dd8e-524">[ブログの投稿](https://insider.office.com/ja-JP/blog/microsoft-editor-gets-an-upgrade)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-524">See details in [blog post](https://insider.office.com/ja-JP/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-527">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-527">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-528">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-528">Outlook</span></span>

- <span data-ttu-id="5dd8e-529">特定の検索シナリオで Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-529">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-07"></a><span data-ttu-id="5dd8e-531">バージョン 2101: 1 月 7 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-531">Version 2101: January 07</span></span>
<span data-ttu-id="5dd8e-532">*バージョン 2101 (ビルド 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-532">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-534">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-534">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-535">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-535">Excel</span></span>

- <span data-ttu-id="5dd8e-536">**複数のシートを同時に再表示する:** 一度に再表示できるのが、1枚のシートだけではなくなりました。一度に複数の非表示シートを表示します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-536">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="5dd8e-537">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-537">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="5dd8e-538">**改善された条件付き書式ダイアログ**: 条件付き書式ダイアログのサイズが変更可能になり、シングルクリックでルールを複製できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-538">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="5dd8e-539">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-539">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-542">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-542">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-543">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-543">Excel</span></span>

- <span data-ttu-id="5dd8e-544">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-544">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="5dd8e-545">Selection.Parent.Copy コールの後に区切り文字の切り替えに関連する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-545">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="5dd8e-546">ピボット テーブルに書式設定スタイルを適用するときのパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-546">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="5dd8e-547">Excel 4.0 マクロを含む Excel アドイン ファイルを開いたときにプロンプトが表示されずにマクロが無効のままになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-547">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="5dd8e-548">Excel からグラフをコピーして Word に貼り付けるときに、10 進数と桁区切りの記号の設定を継承するように更新しました</span><span class="sxs-lookup"><span data-stu-id="5dd8e-548">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="5dd8e-549">無効なファイル属性 (作成時刻、修正時刻など) を持つ UNC ファイルを開くと、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-549">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="5dd8e-550">STOCKHISTORY 関数を使用するときに、"リソース不足" のアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-550">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="5dd8e-551">PQ dll リストに FuzzyClustering dll を追加しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-551">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="5dd8e-552">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-552">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="5dd8e-553">PowerPoint での埋め込まれた Excel の範囲のプレビューでサイズが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-553">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="5dd8e-554">OneNote</span><span class="sxs-lookup"><span data-stu-id="5dd8e-554">OneNote</span></span>

- <span data-ttu-id="5dd8e-555">この変更により、OneNote に影響を与えるレンダリングの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-555">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-556">Outlook</span></span>

- <span data-ttu-id="5dd8e-557">Word から差し込み印刷を開始するときに、ユーザーがアクセスを許可する時間の長さを指定できず、ユーザーに対して余分なプロンプトが表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-557">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="5dd8e-558">この変更により、エンド ユーザーに対して Exchange Online アーカイブ メールボックスを表示しないようにする Exchange サーバーの設定を Outlook で利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-558">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="5dd8e-559">引き換えベースのアドインのユーザーの Outlook が予期せず終了してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-559">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="5dd8e-560">ユーザーが検索対象のカテゴリを複数選ぶことができなかった原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-560">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="5dd8e-561">イベントが別の予定からコピーされたときに、一部の予定表アイテムの開始時刻が予期せず変更される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-561">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="5dd8e-562">送信時にプレーン テキストの S/MIME メッセージが正しく表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-562">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-563">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-563">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-564">この変更により、図形の結合がテキストを操作するときに発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-564">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="5dd8e-565">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-565">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="5dd8e-566">この変更により、スライドショーでバックグラウンドビデオ再生がループする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-566">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="5dd8e-567">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-567">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-568">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-568">Project</span></span>

- <span data-ttu-id="5dd8e-569">リソースの最大単位数が、最新の最大単位数の更新を常に反映していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-569">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="5dd8e-570">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-570">Visio</span></span>

- <span data-ttu-id="5dd8e-571">最近の回帰を原因とする問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-571">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="5dd8e-572">この問題は解決されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-572">We have resolved the issue.</span></span> <span data-ttu-id="5dd8e-573">"Web ページとして保存" ダイアログは、ユーザーの入力に従って正しく生成されたフィールドを持つようになり、ユーザーはシームレスにファイルを Web ページとして保存することができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-573">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="5dd8e-574">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-574">This issue has been fixed.</span></span> <span data-ttu-id="5dd8e-575">PowerPoint や Word などの他の Office アプリケーションに Visio ファイルをオブジェクトとして埋め込み、これらのアプリケーション内からシームレスにアクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-575">You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-576">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-576">Word</span></span>

- <span data-ttu-id="5dd8e-577">sha512 以外のハッシュ設定を使用して共同作業セッションを開始すると、カスタム ハッシュ設定を持つコンピューターに問題が発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-577">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="5dd8e-578">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-578">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="5dd8e-579">@Mention を含むコメント投稿を編集するときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-579">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="5dd8e-580">最新のコメントをより信頼性の高いものにするために、問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-580">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="5dd8e-581">編集不可とマークされているコンテンツ コントロールでの最新のコメントの削除に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-581">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="5dd8e-582">コメント カードの下部に入力するときのアニメーションを修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-582">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="5dd8e-583">コメント カードの返信ボックスが画面に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-583">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="5dd8e-584">ページの上部にコメント カードが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-584">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="5dd8e-585">テキストが画面外にスクロールしてしまうことがあるコメントでのバグを修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-585">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="5dd8e-586">コメント ウィンドウ内のネストされたスクロール バーに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-586">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="5dd8e-587">新しい Word インスタンスを作成すると、コメントの下書きが消えます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-587">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="5dd8e-588">文書を隠し文字で PDF に保存する際に、Word が固まる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-588">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-january-04"></a><span data-ttu-id="5dd8e-590">バージョン 2012: 1 月 4 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-590">Version 2012: January 04</span></span>
<span data-ttu-id="5dd8e-591">*バージョン 2012 (ビルド 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-591">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="5dd8e-592">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-592">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-594">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-594">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-595">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-595">Excel</span></span>

- <span data-ttu-id="5dd8e-596">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-596">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-597">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-597">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-598">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-598">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-599">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-599">Word</span></span>

- <span data-ttu-id="5dd8e-600">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-600">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-28"></a><span data-ttu-id="5dd8e-602">バージョン 2012: 12 月 28 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-602">Version 2012: December 28</span></span>
<span data-ttu-id="5dd8e-603">*バージョン 2012 (ビルド 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-603">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-605">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-605">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-606">Outlook</span></span>

- <span data-ttu-id="5dd8e-607">一部のお客様の環境で、予定表の読み込み中にハングアップする原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-607">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-21"></a><span data-ttu-id="5dd8e-609">バージョン 2012: 12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-609">Version 2012: December 21</span></span>
<span data-ttu-id="5dd8e-610">*バージョン 2012 (ビルド 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-610">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-612">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-612">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-613">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-613">Excel</span></span>

- <span data-ttu-id="5dd8e-614">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-614">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="5dd8e-615">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-615">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-616">Outlook</span></span>

- <span data-ttu-id="5dd8e-617">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分遅く会議を開始するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-617">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="5dd8e-618">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-618">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="5dd8e-619">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-619">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="5dd8e-620">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-620">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-621">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-621">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-622">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-622">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="5dd8e-623">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-623">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-624">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-624">Word</span></span>

- <span data-ttu-id="5dd8e-625">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-625">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="5dd8e-626">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-626">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-629">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-629">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="5dd8e-630">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-630">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-631">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-631">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-14"></a><span data-ttu-id="5dd8e-633">バージョン 2012: 12 月 14 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-633">Version 2012: December 14</span></span>
<span data-ttu-id="5dd8e-634">*バージョン 2012 (ビルド 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-634">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-636">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-636">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-637">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-637">Outlook</span></span>

- <span data-ttu-id="5dd8e-638">**クラウドでの Outlook の設定** [自動応答]、[優先受信トレイ]、[プライバシー] などの Outlook for Windows の設定を選択し、任意の PC でアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-638">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-641">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-641">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="5dd8e-642">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-642">Office Suite</span></span>

- <span data-ttu-id="5dd8e-643">最適化されたバイナリ サイズ。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-643">Optimized binary size.</span></span>


- <span data-ttu-id="5dd8e-644">Anaheim WebView は、Windows 情報保護 (WIP) をまだサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-644">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="5dd8e-645">この修正プログラムを適用すると、Office addin プラットフォームが、WIP が有効な環境でダウンレベルの WebView に戻ります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-645">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="5dd8e-646">お客様のコンピューター環境に応じて、Edge Spartan WebView または Trident WebView のいずれかになります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-646">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="5dd8e-647">ダウンレベル WebViews は、両方とも WIP をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-647">Both down level WebViews support WIP.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-07"></a><span data-ttu-id="5dd8e-649">バージョン 2012: 12 月 7 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-649">Version 2012: December 07</span></span>
<span data-ttu-id="5dd8e-650">*バージョン 2012 (ビルド 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-650">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-652">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-652">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="5dd8e-653">Teams</span><span class="sxs-lookup"><span data-stu-id="5dd8e-653">Teams</span></span>

- <span data-ttu-id="5dd8e-654">**Teams で Windows ネイティブ通知をサポート:** ユーザーはバナーに組み込まれた Teams、または Windows のネイティブ バナーのいずれかを使用して、通知配信の優先手段を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-654">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="5dd8e-655">**Citrix および VMWare VDI の Teams 会議 2X2 ギャラリー ビュー:** Teams の VDI 2x2 ギャラリー ビュー機能を使用すると、Teams クライアントが VDI 最適化モードの場合、Citrix、VMWare から VDI クライアントの 2x2 ギャラリー ビューで最大 4 人の参加者のビデオを表示できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-655">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="5dd8e-656">**会議の反応:**  会議の反応は、会議を操作するための新しい方法です。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-656">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="5dd8e-657">参加者は、共有されているコンテンツにストリームとして表示される反応を送信できます。また、会議ステージに表示されている場合は、その反応を送信した人物に対しても送信できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-657">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="5dd8e-658">**Web 会議の Together モードとラージ ギャラリー** ラージ ギャラリーでは、同時に最大 49 の他のユーザーのビデオを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-658">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="5dd8e-659">このオプションは、少なくとも 10 人のユーザーがカメラをオンにしている場合に使用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-659">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="5dd8e-660">Together モードを使用すると、会議のすべてのユーザーと同じ共有スペースを使用しているかのように感じられます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-660">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="5dd8e-661">会議に少なくとも 5 人のユーザーがいる場合に、Together モードを使用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-661">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="5dd8e-662">**コール マージ** コール マージを使用すると、ユーザーは新しい通話または新しい着信を 1-1 またはグループ呼び出しに結合できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-662">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="5dd8e-663">これは、Teams の VOIP 通話と PSTN 通話に適用されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-663">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="5dd8e-664">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-664">Visio</span></span>

- <span data-ttu-id="5dd8e-665">**新しい Azure ステンシルと図形:** 最新の Azure 図を作成するために、多くのステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-665">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="5dd8e-666">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-666">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-669">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-669">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-670">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-670">Excel</span></span>

- <span data-ttu-id="5dd8e-671">一部のリボン要素が簡体字中国語でローカライズされていないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-671">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="5dd8e-672">更新時に Excel が予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-672">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="5dd8e-673">OneDrive のローカル同期フォルダーからファイルを挿入する際に、「オブジェクトの挿入」コマンドにおいて正しいアイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-673">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="5dd8e-674">上書きモードで、IME の使用が必要な言語で編集を行うと、パフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-674">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="5dd8e-675">共同編集時に、一部のユーザーに対して、新しいバージョンのファイルを通知するメッセージ バーが誤って表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-675">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="5dd8e-676">数式ビューでデータをコピーして貼り付けるときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-676">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="5dd8e-677">自動保存が無効になった場合に、通知のヘルプ記事へのハイパーリンクが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-677">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="5dd8e-678">Excel を特定の言語で実行しているときにデータを入力すると、Excel が動作しなくなるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-678">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="5dd8e-679">この変更により、数式内にフォントが正しく表示されないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-679">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="5dd8e-680">これにより、Power Pivot がタブ区切りのテキストファイルを正しくインポートできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-680">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-681">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-681">Outlook</span></span>

- <span data-ttu-id="5dd8e-682">タスク進捗レポートの [宛先] フィールドが空白になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-682">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="5dd8e-683">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-683">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="5dd8e-684">Outlook 以外のアプリケーションから Outlook メールを送信するときに問題が発生する原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-684">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="5dd8e-685">下書きに保存すると、SmartLinks が書式設定を失うという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-685">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="5dd8e-686">Zip ファイルから開いたメッセージに添付ファイルを追加するときに問題が発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-686">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-687">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-687">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-688">Word から PowerPoint への数式のコピーと貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-688">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="5dd8e-689">この変更により、インク分析中のタイムアウトに関連する問題が解決します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-689">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="5dd8e-690">この変更は、アニメーション GIF ユーザー インターフェイスの作成に関する文法エラーに対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-690">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="5dd8e-691">この変更により、特定のジオメトリで図形の結合操作を適用するときの軌跡の塗りつぶしに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-691">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="5dd8e-692">この変更により、数式内にフォントが正しく表示されないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-692">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="5dd8e-693">この変更により、ビデオの読み込み中に発生する可能性のあるエラーの処理に関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-693">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="5dd8e-694">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (MPG-1、Mpeg-2) でクラッシュする VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-694">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="5dd8e-695">共同編集者の詳細情報が利用可能な場合、不明だった共同編集者のプレゼンス インジケーターが完全に更新されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-695">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="5dd8e-696">ルーラーがオンの状態でスライド表示のサイズが変更されるときに、null ポインターが逆に参照されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-696">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="5dd8e-697">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-697">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-698">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-698">Project</span></span>

- <span data-ttu-id="5dd8e-699">更新された情報が保存されているはずのプロジェクトをユーザーが開いた際に、更新された情報が見つからないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-699">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="5dd8e-700">成果物が関連付けられていた SharePoint サイトが存在しなくなった場合に、成果物の依存関係を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-700">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="5dd8e-701">多くのリソースを持つプロジェクトを開くのに時間がかかるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-701">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="5dd8e-702">タスクに関連付して、割り当てられていない割り当てが複数存在するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-702">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="5dd8e-703">大規模なプロジェクトでは、タスク名の入力に非常に時間がかかることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-703">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="5dd8e-704">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-704">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-705">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-705">Word</span></span>

- <span data-ttu-id="5dd8e-706">リッチ テキストとして貼り付けるより、通常のテキストとして貼り付けることが推奨されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-706">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="5dd8e-707">このコンテキスト メニューの修正プログラムでは、テキストとして貼り付けることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-707">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="5dd8e-708">それ以外の場合、ユーザーはメモ帳などのプレーンテキスト エディターにコピーして、メモ帳から目的のターゲット アプリにコピーする必要があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-708">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="5dd8e-709">Word から PowerPoint への数式のコピーと貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-709">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="5dd8e-710">この変更により、ドキュメントを編集するときのカーソルに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-710">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="5dd8e-711">ズーム中に写真がぼやけてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-711">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="5dd8e-712">長いハイパーリンクが一部省略されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-712">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-713">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-713">Office Suite</span></span>

- <span data-ttu-id="5dd8e-714">Office スイートでは、新しいバージョンの Office を特定の古いバージョンの Office の上からインストールすると、レジストリ エントリが存在していないために機能が低下する(Power Query を使用できないなど) という問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-714">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-december-01"></a><span data-ttu-id="5dd8e-716">バージョン 2011: 12 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-716">Version 2011: December 01</span></span>
<span data-ttu-id="5dd8e-717">*バージョン 2011 (ビルド 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-717">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-719">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-719">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-720">Outlook</span></span>

- <span data-ttu-id="5dd8e-721">**会議はすべてオンラインで:** 新しい設定により、オンライン会議のスケジュールを簡単に立てれるため、既定ですべての会議をオンラインにできます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-721">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-724">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-724">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-725">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-725">Outlook</span></span>

- <span data-ttu-id="5dd8e-726">他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-726">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="5dd8e-727">1 つ以上の署名が構成されているにもかかわらず、ユーザーの署名が署名ドロップダウンに表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-727">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-728">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-728">Project</span></span>

- <span data-ttu-id="5dd8e-729">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-729">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-24"></a><span data-ttu-id="5dd8e-731">バージョン 2011: 11 月 24 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-731">Version 2011: November 24</span></span>
<span data-ttu-id="5dd8e-732">*バージョン 2011 (ビルド 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-732">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-734">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-734">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="5dd8e-735">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-735">Office Suite</span></span>

- <span data-ttu-id="5dd8e-736">Word から PowerPoint への数式のコピーと貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-736">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-21"></a><span data-ttu-id="5dd8e-738">バージョン 2011: 11 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-738">Version 2011: November 21</span></span>
<span data-ttu-id="5dd8e-739">*バージョン 2011 (ビルド 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-739">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-741">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-741">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="5dd8e-742">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-742">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-743">**ビデオ ライブラリ:** アプリ内で利用可能な、質の良い無料のビデオ フッテージのライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-743">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-746">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-746">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-747">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-747">Outlook</span></span>

- <span data-ttu-id="5dd8e-748">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="5dd8e-748">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="5dd8e-749">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-749">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="5dd8e-750">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="5dd8e-750">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="5dd8e-751">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="5dd8e-751">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="5dd8e-752">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-752">0 = filetimes are excluded.</span></span> <span data-ttu-id="5dd8e-753">1 = (既定) filetimes が含まれています</span><span class="sxs-lookup"><span data-stu-id="5dd8e-753">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="5dd8e-754">Azure Information Protection の保護ラベルを使用してメッセージに返信すると、インライン画像が表示されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-754">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-18"></a><span data-ttu-id="5dd8e-756">バージョン 2011: 11 月 18 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-756">Version 2011: November 18</span></span>
<span data-ttu-id="5dd8e-757">*バージョン 2011 (ビルド 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-757">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="5dd8e-758">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-758">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="5dd8e-759">バージョン 2011: 11 月 16 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-759">Version 2011: November 16</span></span>
<span data-ttu-id="5dd8e-760">*バージョン 2011 (ビルド 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-760">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-762">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-762">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-763">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-763">Outlook</span></span>

- <span data-ttu-id="5dd8e-764">**同じ署名、すべてのデバイス:** 署名をクラウドに保存し ます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-764">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="5dd8e-765">一度作成して、Outlook を使用するすべての場所で使用します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-765">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-768">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-768">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-769">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-769">Outlook</span></span>

- <span data-ttu-id="5dd8e-770">タスクに対する進捗レポートの送信時に、[宛先] フィールドが空白になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-770">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-771">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-771">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-772">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (MPG-1、Mpeg-2) でクラッシュする VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-772">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-09"></a><span data-ttu-id="5dd8e-774">バージョン 2011: 11 月 9 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-774">Version 2011: November 09</span></span>
<span data-ttu-id="5dd8e-775">*バージョン 2011 (ビルド 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-775">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-777">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-777">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-778">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-778">Excel</span></span>

- <span data-ttu-id="5dd8e-779">**クエリから Powe rPlatform データフローを作成する**: 新しい Powe rPlatform データフローの作成に使用できる Power Query テンプレートにクエリをエクスポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-779">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-782">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-782">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-783">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-783">Access</span></span>

- <span data-ttu-id="5dd8e-784">同期済みの OneDrive フォルダーからクエリをエクスポートしようとしたときに、一部のユーザーに "システム リソースの超過" というエラーが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-784">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="5dd8e-785">フォーム ウィンドウ間で別のフォームに切り替える場合の「自動」切り替えの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-785">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="5dd8e-786">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-786">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="5dd8e-787">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-787">Excel</span></span>

- <span data-ttu-id="5dd8e-788">COM アドインを有効にして SaveAs 操作を行った後、ファイル名が変更されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-788">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="5dd8e-789">Oracle データベースへの接続を使用する際の Power Pivot の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-789">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="5dd8e-790">Excel データモデルに不適切なメジャー定義がある場合に、自動保存が誤った、または誤解を招くエラーメッセージを表示して失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-790">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="5dd8e-791">MTR 計算およびグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) のプロセスがトリガーされたときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-791">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="5dd8e-792">ユーザーが SharePoint から .atomsvc (UTF8 + BOM) ファイルを直接開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-792">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="5dd8e-793">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-793">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="5dd8e-794">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-794">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-795">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-795">Outlook</span></span>

- <span data-ttu-id="5dd8e-796">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-796">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="5dd8e-797">画像の添付ファイルをクイック印刷すると、以下のエラーが発生する問題を修正しました。「Windows がこの画像を見つけることができません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-797">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="5dd8e-798">場所を確認してから、もう一度お試しください」。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-798">Check the location, and then try again".</span></span>


- <span data-ttu-id="5dd8e-799">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-799">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="5dd8e-800">会議の場所からコピーした URL をブラウザーなどの別の場所に貼り付けると、URL の末尾にセミコロンが含まれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-800">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="5dd8e-801">ユーザーが基本認証で Microsoft 365 グループの予定表の予定を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-801">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="5dd8e-802">ニックネーム キャッシュの読み込み中に Outlook の起動に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-802">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="5dd8e-803">オプションがグレー表示され、メールボックスの所有者が自分のカレンダーの共有権限を管理できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-803">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="5dd8e-804">Outlook が制限付きのアクセス許可でメッセージを作成できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-804">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="5dd8e-805">メールテンプレートを .OFT として保存すると、中国語の文字が疑問符に変わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-805">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-806">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-806">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-807">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-807">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="5dd8e-808">画像の横のコンテンツ プレースホルダー アイコンにツールヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-808">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="5dd8e-809">pptsx ファイルで表示されるスライド ショーの保護されたビューで、IRM で保護されたドキュメントの画面キャプチャが許可される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-809">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="5dd8e-810">デザインウィンドウを閉じるときにグリッド線がスライドからずれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-810">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="5dd8e-811">スライドショーを 2 台目のモニターに複製する場合、そのスライドショーが他のウィンドウの背面で非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-811">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="5dd8e-812">選択ウィンドウを開いた状態で画面の記録を停止した後、スライドのスクロールバーが自動的に調整を開始する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-812">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-813">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-813">Project</span></span>

- <span data-ttu-id="5dd8e-814">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-814">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="5dd8e-815">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-815">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="5dd8e-816">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-816">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="5dd8e-817">リソースエンゲージメントが GUID ではなく名前でリソースを検索する問題を修正しました。同じ名前のリソースが複数ある場合に問題が発生していました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-817">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="5dd8e-818">プロジェクトサイトにタスクリストがあり、タスクリストをグループ化すると、タスクリストをすばやく編集できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-818">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="5dd8e-819">CSOM を介してエンタープライズリソースを更新すると、リソースの最大単位数が失われることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-819">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-820">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-820">Word</span></span>

- <span data-ttu-id="5dd8e-821">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-821">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="5dd8e-822">コメントヒントをクリックしてもズームアウトしてコメントカードが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-822">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="5dd8e-823">列間の線がずれている場合があるレイアウトの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-823">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="5dd8e-824">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-824">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="5dd8e-825">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-825">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="5dd8e-826">機密度ラベルに透かしが適用される場合がある印刷の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-826">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-827">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-827">Office Suite</span></span>

- <span data-ttu-id="5dd8e-828">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-828">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="5dd8e-829">SSO API インタラクティブ サインインがエラー コードを返す問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-829">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-06"></a><span data-ttu-id="5dd8e-831">バージョン 2010: 11 月 6 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-831">Version 2010: November 06</span></span>
<span data-ttu-id="5dd8e-832">*バージョン 2010 (ビルド 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-832">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="5dd8e-833">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-833">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-04"></a><span data-ttu-id="5dd8e-836">バージョン 2010: 11 月 4 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-836">Version 2010: November 04</span></span>
<span data-ttu-id="5dd8e-837">*バージョン 2010 (ビルド 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-837">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-839">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-839">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-840">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-840">Excel</span></span>

- <span data-ttu-id="5dd8e-841">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-841">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="5dd8e-842">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-842">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="5dd8e-843">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-843">Outlook</span></span>

- <span data-ttu-id="5dd8e-844">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-844">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="5dd8e-845">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-845">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-846">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-846">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-847">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-847">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="5dd8e-848">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-848">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="5dd8e-849">[ブログの投稿](https://insider.office.com/ja-JP/blog/svg-content-office-third-party-apps)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-849">See details in [blog post](https://insider.office.com/ja-JP/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="5dd8e-850">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-850">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="5dd8e-851">[ブログ記事](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-851">See details in [blog post](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="5dd8e-852">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します</span><span class="sxs-lookup"><span data-stu-id="5dd8e-852">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-853">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-853">Word</span></span>

- <span data-ttu-id="5dd8e-854">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-854">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="5dd8e-855">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-855">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-858">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-858">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-859">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-859">Outlook</span></span>

- <span data-ttu-id="5dd8e-860">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-860">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-861">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-861">Office Suite</span></span>

- <span data-ttu-id="5dd8e-862">同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-862">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-27"></a><span data-ttu-id="5dd8e-864">バージョン 2010: 10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-864">Version 2010: October 27</span></span>
<span data-ttu-id="5dd8e-865">*バージョン 2010 (ビルド 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-865">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-869">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-869">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-870">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-870">Outlook</span></span>

- <span data-ttu-id="5dd8e-871">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-871">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="5dd8e-872">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-872">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-24"></a><span data-ttu-id="5dd8e-874">バージョン 2010: 10 月 24 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-874">Version 2010: October 24</span></span>
<span data-ttu-id="5dd8e-875">*バージョン 2010 (ビルド 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-875">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-879">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-879">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-880">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-880">Outlook</span></span>

- <span data-ttu-id="5dd8e-881">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-881">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="5dd8e-882">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-882">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-883">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-883">Project</span></span>

- <span data-ttu-id="5dd8e-884">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-884">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="5dd8e-885">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-885">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-19"></a><span data-ttu-id="5dd8e-887">バージョン 2010 : 10 月 19 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-887">Version 2010: October 19</span></span>
<span data-ttu-id="5dd8e-888">*バージョン 2010 (ビルド 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-888">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-890">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-890">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-891">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-891">Outlook</span></span>

- <span data-ttu-id="5dd8e-892">**メッセージの作成にかかる時間を節約:** Outlook は、メッセージをすばやく作成するのに役立つ提案を作成することを示します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-892">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="5dd8e-893">提案を受け入れるには、Tab キーを使用するだけです。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-893">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="5dd8e-894">[ブログ記事](https://insider.office.com/ja-JP/blog/text-predictions-in-word-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-894">See details in [blog post](https://insider.office.com/ja-JP/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="5dd8e-895">**組み込みの翻訳機能を使用して、言語の壁を取り除く:** 翻訳用のアドインは必要なくなりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-895">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="5dd8e-896">メッセージを右クリックすると、特定の単語、語句、またはメッセージ全体を翻訳できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-896">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="5dd8e-897">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-897">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="5dd8e-898">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新</span><span class="sxs-lookup"><span data-stu-id="5dd8e-898">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-899">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-899">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-900">**発表者のコーチでプレゼンテーションを練習する:** 話す速度、特定の単語を使いすぎていないか、ボディーランゲージなど、聴衆の関心を引きつけておくのに役立つ内容についてコーチングを受けます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-900">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="5dd8e-901">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-901">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="5dd8e-902">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-902">Word</span></span>

- <span data-ttu-id="5dd8e-903">**Microsoft エディター ウィンドウにデスクトップ用の Word の更新が表示される:** デスクトップ クライアント用の Word エディター ウィンドウの現在のエクスペリエンスをアップグレードしました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-903">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="5dd8e-904">**ワンクリック ライティング候補:** ワンクリックでライティング候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-904">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="5dd8e-905">更新されたエディターウィンドウを使って、候補間を簡単に移動できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-905">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-908">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-908">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="5dd8e-909">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-909">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-910">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-910">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-11"></a><span data-ttu-id="5dd8e-912">バージョン 2010: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-912">Version 2010: October 11</span></span>
<span data-ttu-id="5dd8e-913">*バージョン 2010 (ビルド13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-913">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-915">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-915">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-916">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-916">Excel</span></span>

- <span data-ttu-id="5dd8e-917">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-917">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="5dd8e-918">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-918">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-919">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-919">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-920">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-920">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="5dd8e-921">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-921">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="5dd8e-922">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-922">Word</span></span>

- <span data-ttu-id="5dd8e-923">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-923">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="5dd8e-924">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-924">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-927">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-927">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-928">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-928">Access</span></span>

- <span data-ttu-id="5dd8e-929">スクロール中に保存されたクエリ/リレーションシップ ウィンドウを読み込むときに、スクロールバーの位置が正しく設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-929">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="5dd8e-930">[テーブルを追加する] 作業ウィンドウに「&」を含む名前が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-930">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="5dd8e-931">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-931">Excel</span></span>

- <span data-ttu-id="5dd8e-932">マルチレベル カテゴリの手動間隔がグラフで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-932">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="5dd8e-933">VBA を使用した、シリーズの最大値、中間値、最小値の色の設定が機能しないという 2D マップ グラフの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-933">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="5dd8e-934">Excel で 1 つまたは複数の数式を計算しようとする際に発生する、Excelはリソース不足になりましたというエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-934">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="5dd8e-935">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-935">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="5dd8e-936">[改ページ プレビュー] が有効になっているときに、大量のデータが含まれているワークシート間を切り替える際に顕著な遅延が発生する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-936">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="5dd8e-937">データ検証に使用されるテーブルに追加しても、ブック内のすべてのシートのオプションが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-937">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="5dd8e-938">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-938">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="5dd8e-939">数式バーに数式を入力したときに、ChartSheet がクラッシュする場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-939">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="5dd8e-940">デバイスへの接続が失われると (リモート セッションが接続されたり接続が解除されたり、モニターでの変更があった場合など) Excel の関数バーが完全に描画されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-940">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="5dd8e-941">OneNote</span><span class="sxs-lookup"><span data-stu-id="5dd8e-941">OneNote</span></span>

- <span data-ttu-id="5dd8e-942">ユーザーが OutSpace で [ファイル]、[情報] に移動してテキスト ボックスからノートブックの URL を選択してコピーできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-942">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="5dd8e-943">ノートブックのカラー セレクターで緑色にカーソルを合わせると、ポップアップに「赤チョーク」と表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-943">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="5dd8e-944">OneNote がカスタム テーマのキャンバスのハイ コントラスト カラーを尊重しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-944">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-945">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-945">Outlook</span></span>

- <span data-ttu-id="5dd8e-946">件名が空白の場合、自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-946">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="5dd8e-947">間違ったフォルダー GUID がフォルダーにキャッシュされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-947">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="5dd8e-948">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-948">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="5dd8e-949">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-949">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="5dd8e-950">オンライン共有フォルダーが親フォルダー名を返さない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-950">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="5dd8e-951">失敗する代わりに、プライマリ アカウントに誤って送信された空のパスを返しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-951">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="5dd8e-952">[名前を付けて保存] オプションが従来の添付ファイルで使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-952">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="5dd8e-953">ポリシーを上書きするときに正当化テキストをカスタマイズする方法をユーザーに提供する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-953">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="5dd8e-954">読み取り専のプレビュー ウィンドウから下書きを再開した後、トラックの変更がオンになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-954">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="5dd8e-955">優先受信トレイをオフにして並べ替えを行った後に、メールが非表示になるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-955">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="5dd8e-956">クラウド設定を有効にしているユーザーに対して、2つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-956">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-957">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-958">PDF へのエクスポート中に PowerPoint が長方形の箇条書きをエクスポートしなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-958">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="5dd8e-959">エディターとスライド ショーで GIF のアニメーションが1 回だけしか再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-959">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="5dd8e-960">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-960">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="5dd8e-961">最後のスライドを表示していて、[セッションの終了] を押した後、概要が表示される前に次のスライドにスワイプすると、[セッションの終了] ダイアログ ボックスが概要ページにも表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-961">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-962">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-962">Project</span></span>

- <span data-ttu-id="5dd8e-963">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-963">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="5dd8e-964">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-964">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="5dd8e-965">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-965">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="5dd8e-966">数式を使用してカスタム フィールドを作成し、取得した値を使用している場合、表示の切り替えやプロジェクト/タスクの詳細を開く際にパフォーマンスの遅延が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-966">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="5dd8e-967">リソース配分状況ビューまたはシート ビューにグループ化を適用してから列を挿入すると、Project がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-967">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-968">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-968">Word</span></span>

- <span data-ttu-id="5dd8e-969">ワークフロー対応ファイルへのリンクが期待どおりに開かない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-969">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="5dd8e-970">変更履歴 (挿入/削除) をユーザーがタップすると、コメントがポップアップ表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-970">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="5dd8e-971">Word でコメントの吹き出しを削除するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-971">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="5dd8e-972">Outlook でメッセージが [転送不可] に設定される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-972">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="5dd8e-973">引用と数式を含む Word 文書を保存するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-973">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="5dd8e-974">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-974">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-975">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-975">Office Suite</span></span>

- <span data-ttu-id="5dd8e-976">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-976">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="5dd8e-977">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-977">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-07"></a><span data-ttu-id="5dd8e-979">バージョン 2009: 10 月 7 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-979">Version 2009: October 07</span></span>
<span data-ttu-id="5dd8e-980">*バージョン 2009 (ビルド 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-980">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-982">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-982">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-983">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-983">Excel</span></span>

- <span data-ttu-id="5dd8e-984">**Power Query を使用してデータ型を作成する: Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します**</span><span class="sxs-lookup"><span data-stu-id="5dd8e-984">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-985">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-985">Outlook</span></span>

- <span data-ttu-id="5dd8e-986">**文章校正による支援:** Outlook では、入力中に文章校正のエラーが表示されます。シングル クリックで候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-986">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="5dd8e-987">[ブログの投稿](https://insider.office.com/ja-JP/blog/grammar-and-style-suggestions-available-in-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-987">See details in [blog post](https://insider.office.com/ja-JP/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-990">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-990">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-991">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-991">Outlook</span></span>

- <span data-ttu-id="5dd8e-992">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-992">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="5dd8e-993">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-993">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="5dd8e-994">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-994">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-995">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-995">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-996">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-996">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-997">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-997">Office Suite</span></span>

- <span data-ttu-id="5dd8e-998">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-998">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="5dd8e-999">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-999">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-26"></a><span data-ttu-id="5dd8e-1001">バージョン 2009: 9 月 26　日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1001">Version 2009: September 26</span></span>
<span data-ttu-id="5dd8e-1002">*バージョン 2009 (ビルド13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1002">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1004">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1004">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1005">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1005">Outlook</span></span>

- <span data-ttu-id="5dd8e-1006">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1006">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-1007">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1007">Project</span></span>

- <span data-ttu-id="5dd8e-1008">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1008">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-21"></a><span data-ttu-id="5dd8e-1010">バージョン 2009: 9 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1010">Version 2009: September 21</span></span>
<span data-ttu-id="5dd8e-1011">*バージョン 2009 (ビルド 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1011">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1013">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1013">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1014">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1014">Access</span></span>

- <span data-ttu-id="5dd8e-1015">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1015">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1016">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1016">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1017">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1017">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="5dd8e-1018">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1018">Excel</span></span>

- <span data-ttu-id="5dd8e-1019">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1019">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="5dd8e-1020">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1020">No conversion required.</span></span><br /><span data-ttu-id="5dd8e-1021">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1021">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="5dd8e-1022">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1022">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1023">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1023">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1024">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1024">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="5dd8e-1025">OneNote</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1025">OneNote</span></span>

- <span data-ttu-id="5dd8e-1026">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1026">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1027">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1027">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1028">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1028">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="5dd8e-1029">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1029">Outlook</span></span>

- <span data-ttu-id="5dd8e-1030">**メッセージの所有者として会話を削除する:** この機能を使用すると、メッセージの所有者による会話を削除できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1030">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="5dd8e-1031">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1031">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="5dd8e-1032">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1032">No conversion required.</span></span><br /><span data-ttu-id="5dd8e-1033">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1033">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="5dd8e-1034">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1034">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1035">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1035">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1036">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1036">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1037">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1037">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1038">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1038">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="5dd8e-1039">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1039">No conversion required.</span></span><br /><span data-ttu-id="5dd8e-1040">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1040">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="5dd8e-1041">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1041">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1042">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1042">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1043">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1043">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="5dd8e-1044">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1044">Project</span></span>

- <span data-ttu-id="5dd8e-1045">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1045">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1046">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1046">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1047">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1047">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="5dd8e-1048">発行者</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1048">Publisher</span></span>

- <span data-ttu-id="5dd8e-1049">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1049">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1050">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1050">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1051">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1051">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="5dd8e-1052">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1052">Visio</span></span>

- <span data-ttu-id="5dd8e-1053">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1053">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1054">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1054">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1055">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1055">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="5dd8e-1056">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1056">Word</span></span>

- <span data-ttu-id="5dd8e-1057">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1057">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="5dd8e-1058">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1058">No conversion required.</span></span><br /><span data-ttu-id="5dd8e-1059">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1059">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="5dd8e-1060">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1060">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="5dd8e-1061">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1061">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="5dd8e-1062">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1062">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1065">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1065">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1066">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1066">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1067">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1067">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-14"></a><span data-ttu-id="5dd8e-1069">バージョン 2009: 9 月 14 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1069">Version 2009: September 14</span></span>
<span data-ttu-id="5dd8e-1070">*バージョン 2009 (ビルド 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1070">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="5dd8e-1071">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1071">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-10"></a><span data-ttu-id="5dd8e-1074">バージョン 2009: 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1074">Version 2009: September 10</span></span>
<span data-ttu-id="5dd8e-1075">*バージョン 2009 (ビルド 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1075">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1077">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1077">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1078">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1078">Access</span></span>

- <span data-ttu-id="5dd8e-1079">この問題は解決されましたので、クラッシュが発生しなくなったはずです。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1079">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="5dd8e-1080">ODBC データベースへの接続がサードパーティ製アプリケーションで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1080">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="5dd8e-1081">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1081">Excel</span></span>

- <span data-ttu-id="5dd8e-1082">LET 関数が含まれているファイルを開くと、以下の警告が表示される問題が修正されました: "ファイル名.xlsx" のコンテンツに問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1082">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="5dd8e-1083">できるだけ多くの内容の復元を試みますか?</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1083">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="5dd8e-1084">このブックの発行元が信頼できる場合は、[はい] をクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1084">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="5dd8e-1085">ユーザーがかっこを含む数式名を入力し、F1 を介してヘルプを呼び出した場合、その数式に固有のヘルプ トピックが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1085">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="5dd8e-1086">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1086">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="5dd8e-1087">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1087">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="5dd8e-1088">XLAM アドイン参照と名前付き範囲に関係するクラッシュが修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1088">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="5dd8e-1089">ユーザーが動的配列にカスタム スタイルを適用すると、"配列の一部を変更することはできません" というエラーが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1089">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="5dd8e-1090">これは以前に存在していた制約でしたが、現在は削除されています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1090">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="5dd8e-1091">古いバージョンのファイルを復元した後、ボタンに割り当てられたマクロが壊れる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1091">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="5dd8e-1092">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1092">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-1093">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1093">Outlook</span></span>

- <span data-ttu-id="5dd8e-1094">問題が修正され、グループ ポリシー経由で既定のログ記録オプションを有効または無効にするための柔軟性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1094">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="5dd8e-1095">アシスタントのアクセス許可があるメールボックスと管理者のアクセス許可があるメールボックスの間でメールの下書きを移動した後も、メール送信者の従来のドメイン名が維持されて表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1095">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="5dd8e-1096">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1096">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="5dd8e-1097">1 行リボン (SLR) を有効にした後に VBA コード ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") を実行すると実行時エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1097">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="5dd8e-1098">高解像度 (1750 x 1920 など) と大きなテキストサイズ (175% など) が同時に使用された場合に、[自動応答] ダイアログの [OK] ボタンと [キャンセル] ボタンが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1098">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="5dd8e-1099">会議出席依頼を空の連絡先グループから別の連絡先グループに送信するとクラッシュする状態が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1099">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="5dd8e-1100">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1100">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="5dd8e-1101">アドインが常に有効になっていることがグループ ポリシーで要求される場合に、ユーザーがアドインを無効にすることを防ぐためにアドインの監視が使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1101">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="5dd8e-1102">1 つ以上のメッセージを選択した場合に、OneNote に "転送不可" ポリシーが適用されているメール コンテンツを送信することができるようになっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1102">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="5dd8e-1103">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1103">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="5dd8e-1104">Active Directory の "otherTelephone" および "otherHomePhone" のユーザー アカウント属性が、対応する Outlook LDAP 属性にマッピングされていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1104">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="5dd8e-1105">この変更により、ユーザーがタブを会議ページからスケジュール アシスタント ページに切り替えた後も会議ページが引き続き表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1105">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1106">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1106">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1107">特定の条件下でリボンまたはタイトル バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1107">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="5dd8e-1108">PowerPoint を起動後にスライドを挿入してコメント ウィンドウを開いて閉じると、縮小版ウィンドウ内のスライドが重なって表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1108">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="5dd8e-1109">ビデオを挿入する機能が無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1109">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="5dd8e-1110">ビデオがスライドショーで自動的に再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1110">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-1111">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1111">Project</span></span>

- <span data-ttu-id="5dd8e-1112">リソースに複数のコスト単価テーブルが含まれている場合、残りのコストが正確に計算されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1112">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="5dd8e-1113">SharePoint タスク リストに接続されているプロジェクトのプロジェクト終了日が更新されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1113">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="5dd8e-1114">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1114">Visio</span></span>

- <span data-ttu-id="5dd8e-1115">テキストを配置するとリアルタイムのプレビューがクラッシュする問題がお客様から報告されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1115">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="5dd8e-1116">7 月のフォークで最も多く報告されているクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1116">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-1117">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1117">Word</span></span>

- <span data-ttu-id="5dd8e-1118">ユーザーがコメントをクリックした場合に、コメント カードでコメントのテキストの周囲に枠線が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1118">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="5dd8e-1119">箇条書きのアイコンが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1119">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="5dd8e-1120">コメントの選択時に、ヘッダー/フッターを閉じることができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1120">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="5dd8e-1121">コメントが削除された後に Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1121">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="5dd8e-1122">ユーザーがコメントの下書きを作成して、解決済みのコメントが既に含まれている行にアンカーすると、サイドトラックでは解決済みのコメントに対して正しくない順番で下書きが並べ替えられる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1122">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="5dd8e-1123">ドキュメントの拡大率が 160% より大きく設定され、コメント ウィンドウが表示されていない場合に、フォーカスがコメント ウィンドウに移動しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1123">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="5dd8e-1124">サイドトラックのスクロールが機能しないため、サイドトラックの境界を超えたコメントのスレッドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1124">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="5dd8e-1125">サイドトラック ウィンドウで解決済みのコメントを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1125">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="5dd8e-1126">開いている複数のドキュメントの間で切り替えを行うと、あるドキュメントのコメントが、開かれている別のドキュメントに表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1126">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="5dd8e-1127">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1127">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="5dd8e-1128">メールで箇条書きが正しく表示されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1128">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="5dd8e-1129">AutoOpen が AutoExec. より前に実行されるというマクロの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1129">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-1130">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1130">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1131">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1131">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="5dd8e-1132">[図の圧縮] ダイアログで、ユーザーが選択した一部の DPI 設定が保持されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1132">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="5dd8e-1133">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1133">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-september-04"></a><span data-ttu-id="5dd8e-1135">バージョン 2008: 9 月 04 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1135">Version 2008: September 04</span></span>
<span data-ttu-id="5dd8e-1136">*バージョン 2008 (ビルド 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1136">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1138">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1138">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="5dd8e-1139">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1139">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1140">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1140">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-september-02"></a><span data-ttu-id="5dd8e-1142">バージョン 2008: 9 月 02 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1142">Version 2008: September 02</span></span>
<span data-ttu-id="5dd8e-1143">*バージョン 2008 (ビルド 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1143">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1145">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1145">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1146">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1146">Excel</span></span>

- <span data-ttu-id="5dd8e-1147">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1147">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="5dd8e-1148">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1148">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="5dd8e-1149">**Excelペンを使用してすばやく編集する:** ペン ツールを使用すると、データを手書きしてすばやく編集できます</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1149">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1152">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1152">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1153">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1153">Excel</span></span>

- <span data-ttu-id="5dd8e-1154">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1154">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-1155">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1155">Word</span></span>

- <span data-ttu-id="5dd8e-1156">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1156">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-august-27"></a><span data-ttu-id="5dd8e-1158">バージョン 2008: 8 月 27 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1158">Version 2008: August 27</span></span>
<span data-ttu-id="5dd8e-1159">*バージョン 2008 (ビルド 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1159">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1163">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1163">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1164">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1164">Outlook</span></span>

- <span data-ttu-id="5dd8e-1165">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1165">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="5dd8e-1166">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1166">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="5dd8e-1167">クラウドの添付ファイルを操作しているときに不定期にクラッシュする場合があった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1167">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="5dd8e-1168">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1168">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="5dd8e-1169">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1169">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1170">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1170">Word</span></span>

- <span data-ttu-id="5dd8e-1171">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレントな保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1171">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="5dd8e-1172">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1172">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-25"></a><span data-ttu-id="5dd8e-1174">バージョン 2008: 8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1174">Version 2008: August 25</span></span>
<span data-ttu-id="5dd8e-1175">*バージョン 2008 (ビルド 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1175">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1177">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1177">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1178">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1178">Outlook</span></span>

- <span data-ttu-id="5dd8e-1179">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、候補に表示される最も関連性の高いメールが届きます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1179">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1182">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1182">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1183">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1183">Outlook</span></span>

- <span data-ttu-id="5dd8e-1184">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1184">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="5dd8e-1185">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="5dd8e-1185">Do you want to download them anyway?</span></span> <span data-ttu-id="5dd8e-1186">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1186">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-1187">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1187">Project</span></span>

- <span data-ttu-id="5dd8e-1188">リソースに複数のコスト単価表が定義されている場合、残りのコストが常に正しく計算されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1188">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-1189">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1189">Word</span></span>

- <span data-ttu-id="5dd8e-1190">新しいメールに返信または作成するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1190">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-17"></a><span data-ttu-id="5dd8e-1192">バージョン 2008: 8 月 17 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1192">Version 2008: August 17</span></span>
<span data-ttu-id="5dd8e-1193">*バージョン 2008 (ビルド 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1193">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1195">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1195">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1196">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1196">Outlook</span></span>

- <span data-ttu-id="5dd8e-1197">特定の状況において、代理人が会議を辞退したときに、上司の予定表から削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1197">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="5dd8e-1198">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1198">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="5dd8e-1199">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1199">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="5dd8e-1200">右クリックのコンテキスト メニューが検索コントロールに表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1200">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-11"></a><span data-ttu-id="5dd8e-1202">バージョン 2008: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1202">Version 2008: August 11</span></span>
<span data-ttu-id="5dd8e-1203">*バージョン 2008 (ビルド 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1203">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="5dd8e-1204">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1204">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1206">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1206">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1207">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1207">Access</span></span>

- <span data-ttu-id="5dd8e-1208">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1208">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="5dd8e-1209">Office 365 がインストールされている場合、Office エコシステム外に ACE を公開するために、ACE の再頒布可能エンジンをインストールする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1209">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="5dd8e-1210">そのため、Office 365 を使用している場合は、ACE の再頒布可能エンジンが不要になったため、結果的にこの問題が発生することはありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1210">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="5dd8e-1211">この問題は解決されました。これで、Office のクイック実行アプリケーション以外の ODBC ドライバーを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1211">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="5dd8e-1212">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1212">Excel</span></span>

- <span data-ttu-id="5dd8e-1213">グラフ系列の順序を変更した場合、系列に並んだチェックボックスが系列に沿って並び替えられない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1213">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="5dd8e-1214">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1214">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="5dd8e-1215">ブックの VBA を介して「ForceFullCalculation」が有効になっていると、グラフが期待どおりに更新されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1215">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="5dd8e-1216">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1216">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="5dd8e-1217">OneNote</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1217">OneNote</span></span>

- <span data-ttu-id="5dd8e-1218">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1218">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1219">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1219">Outlook</span></span>

- <span data-ttu-id="5dd8e-1220">Outlook で同じメール ドメインから複数のプロファイルを作成することに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1220">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="5dd8e-1221">共有された予定表の機能強化を利用できないユーザーが、新しく追加した共有予定表を表示できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1221">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="5dd8e-1222">S/MIME 暗号化メッセージのヘッダーにロック アイコンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1222">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="5dd8e-1223">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1223">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="5dd8e-1224">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1224">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="5dd8e-1225">ユーザーが適切な印刷権限を持っていても、印刷ボタンが無効な状態で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1225">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="5dd8e-1226">暗号化されずに送信されたときに添付ファイルが S/MIME メッセージから削除される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1226">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="5dd8e-1227">送信時にプレーン テキストの S/MIME メッセージが文字化けする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1227">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="5dd8e-1228">暗号化されていない S/MIME メールを送信すると添付ファイルが破損する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1228">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="5dd8e-1229">送信者から名前を付けて保存のアクセス許可が付与されている場合でも、受信者が権利保護されたメッセージを保存できなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1229">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="5dd8e-1230">この修正プログラムでは、ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1230">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="5dd8e-1231">この修正プログラムでは、Outlook のMarkdown コンテンツでは改行が正常に表示されない問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1231">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="5dd8e-1232">一部の言語で一部の高度な検索のオプションのラベルが切り捨てられる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1232">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1233">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1233">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1234">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1234">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="5dd8e-1235">Office ストアへのアクセスが許可されていない場合に、PowerPoint の [フォーム] ボタンでフォームを作成できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1235">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="5dd8e-1236">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1236">Project</span></span>

- <span data-ttu-id="5dd8e-1237">[タスク ボード] ビューに一覧表示されているタスクが [リソースの割り当て] ダイアログのタスクと同期していない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1237">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="5dd8e-1238">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存しようとしても、何も起こらない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1238">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="5dd8e-1239">複数の依存関係があるタスクをコピーして貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1239">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="5dd8e-1240">SharePoint のタスク リストで、2番目のタブにあるリボン ボタンが無効になる場合がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1240">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="5dd8e-1241">Skype</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1241">Skype</span></span>

- <span data-ttu-id="5dd8e-1242">ダンス絵文字のスキントーンが中間色に変更されました</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1242">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="5dd8e-1243">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1243">Visio</span></span>

- <span data-ttu-id="5dd8e-1244">この修正プログラムを適用すると、ユーザーがいずれかのメカニズム (この場合はアドインを使用) によって delete コマンドの実行を停止した場合、メモリがリークすることはなく、コンピューター全体への影響もありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1244">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1245">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1245">Word</span></span>

- <span data-ttu-id="5dd8e-1246">テキストとの画像をコメントボックスに貼り付けると Word が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1246">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="5dd8e-1247">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1247">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="5dd8e-1248">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1248">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="5dd8e-1249">変更を追跡するコメントが追加された場合に、[変更履歴] ウィンドウが予期せず開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1249">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="5dd8e-1250">フォーカスがコメント テキスト ボックスにあるときに「エディター」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1250">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="5dd8e-1251">フォーカスがコメント テキスト ボックスにあるときに「変更履歴と​​コメントの表示」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1251">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="5dd8e-1252">最後のコメントを削除すると [新しいコメント] ボタンが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1252">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="5dd8e-1253">変更履歴の記録の[特定のユーザー]オプションが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1253">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="5dd8e-1254">[挿入]、[リンク] ドロップダウンを通して、ドキュメントへのリンクがコメントボックスに挿入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1254">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="5dd8e-1255">HTML ファイルを開くときに、時々切断される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1255">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="5dd8e-1256">ドキュメントを開くとコメントの状態が失われる可能性があるカスタム XML の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1256">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="5dd8e-1257">ハイパーリンクを含む画像を追加した後に、VBA のハイパーリンク コレクションにあるハイパーリンク数が正しく指定されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1257">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="5dd8e-1258">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1258">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="5dd8e-1259">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1259">This is now fixed.</span></span>

- <span data-ttu-id="5dd8e-1260">ユーザーがタスクバーから新しいアプリ ウィンドウを開いて新しい空白のドキュメントを作成した後、追加のファイルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1260">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="5dd8e-1261">ユーザーがドキュメントを編集していて権限を失っていた場合、再認証が必要であることをユーザーに通知しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1261">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-05"></a><span data-ttu-id="5dd8e-1263">バージョン 2007: 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1263">Version 2007: August 05</span></span>
<span data-ttu-id="5dd8e-1264">*バージョン 2007 (ビルド 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1264">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1268">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1268">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1269">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1269">Outlook</span></span>

- <span data-ttu-id="5dd8e-1270">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1270">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="5dd8e-1271">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1271">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-1272">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1272">Project</span></span>

- <span data-ttu-id="5dd8e-1273">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1273">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-29"></a><span data-ttu-id="5dd8e-1275">バージョン 2007: 7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1275">Version 2007: July 29</span></span>
<span data-ttu-id="5dd8e-1276">*バージョン 2007 (ビルド 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1276">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1278">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1278">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1279">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1279">Excel</span></span>

- <span data-ttu-id="5dd8e-1280">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1280">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="5dd8e-1281">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1281">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="5dd8e-1282">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1282">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="5dd8e-1283">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1283">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="5dd8e-1284">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1284">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1285">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1285">Outlook</span></span>

- <span data-ttu-id="5dd8e-1286">**検索する場所を選択する:** 新しい検索範囲のドロップ ダウン リストを使用すると、検索結果を簡単に変更したり、現在のフォルダーと現在のメールボックスを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1286">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="5dd8e-1287">新しい検索についてフィードバックを提供してくれた皆さんに感謝します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1287">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="5dd8e-1288">このデザインと更新プログラムは、お客様のフィードバックを反映しています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1288">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1289">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1289">Word</span></span>

- <span data-ttu-id="5dd8e-1290">**最新のコメントによる共同作業の向上:** オブジェクトにコメントを追加したり、同僚に @mention したり、コメント スレッドを解決して共同作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1290">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="5dd8e-1291">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1291">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1294">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1294">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1295">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1295">Outlook</span></span>

- <span data-ttu-id="5dd8e-1296">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1296">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="5dd8e-1297">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1297">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="5dd8e-1298">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1298">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-27"></a><span data-ttu-id="5dd8e-1300">バージョン 2007: 7 月 27 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1300">Version 2007: July 27</span></span>
<span data-ttu-id="5dd8e-1301">*バージョン 2007 (ビルド 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1301">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="5dd8e-1302">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1302">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="5dd8e-1303">バージョン 2007: 7 月 20 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1303">Version 2007: July 20</span></span>
<span data-ttu-id="5dd8e-1304">*バージョン 2007 (ビルド 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1304">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="5dd8e-1305">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1305">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="5dd8e-1306">バージョン 2007: 7 月 15 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1306">Version 2007: July 15</span></span>
<span data-ttu-id="5dd8e-1307">*バージョン 2007 (ビルド 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1307">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1309">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1309">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1310">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1310">Excel</span></span>

- <span data-ttu-id="5dd8e-1311">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1311">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="5dd8e-1312">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1312">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1315">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1315">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1316">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1316">Access</span></span>

- <span data-ttu-id="5dd8e-1317">リンクされた SQL テーブルが更新された場合、リンクされたテーブル マネージャーが主キーを要求する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1317">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="5dd8e-1318">クエリ エディターのクエリがスクロールして表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1318">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="5dd8e-1319">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1319">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="5dd8e-1320">Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できず、行が削除されたと誤って報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1320">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="5dd8e-1321">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1321">Excel</span></span>

- <span data-ttu-id="5dd8e-1322">http または https ベースではない URL が最近使用したリストに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1322">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="5dd8e-1323">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1323">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="5dd8e-1324">テーブルに関連付けられたクエリが編集されていない場合でも、特定のバージョンの Excel で作成したデータ モデル テーブルが [テーブル プレビュー] に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1324">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="5dd8e-1325">[名前の定義] \ [名前の適用] ダイアログの [相対/絶対参照を区別しない] 参照が原因で、数式が機能しなくなります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1325">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="5dd8e-1326">SharePoint/OneDriveにブックを保存すると、ユーザー設定のリボンタブの CustomUI XML が削除される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1326">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="5dd8e-1327">ファイルが読み取り専用である場合にのみ、ブックが読み取り専用であった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1327">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="5dd8e-1328">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1328">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="5dd8e-1329">レーダー チャートの主要な目盛線が正しく書式設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1329">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="5dd8e-1330">高度なデータ フィルターをクリアするとテーブルの書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1330">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="5dd8e-1331">埋め込まれた PDF 文書のフル パスがファイル名だけでなく文書の標題に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1331">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="5dd8e-1332">Wolfram クラウド コネクターを無効にしてから、Excel ブックを保存してもう一度開くとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1332">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="5dd8e-1333">ソルバー アドインを有効にして Excel を起動するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1333">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-1334">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1334">Outlook</span></span>

- <span data-ttu-id="5dd8e-1335">「To」行に 130 人を超える受信者がいる場合に Outlook がハングする問題を修正し、テキストのレンダリングのパフォーマンスも改善しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1335">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="5dd8e-1336">解像度の異なる複数のモニターを使用している場合に、Input Method Editor (IME) ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1336">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="5dd8e-1337">2 日を超えるイベントはそれ以降のすべての日に同じ終了時刻を表示するという「To Do バー」の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1337">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="5dd8e-1338">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501 年 1 月 1 日に設定される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1338">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="5dd8e-1339">ユーザーが配布リストの「送信者を指定して送信」または「代理送信」ができなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1339">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="5dd8e-1340">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1340">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="5dd8e-1341">以前に保存した予定を閉じると、次のエラーが表示される問題を修正しました。「別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1341">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="5dd8e-1342">アイテムの既定のフォルダーにコピーしますか?」</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1342">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="5dd8e-1343">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1343">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="5dd8e-1344">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1344">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="5dd8e-1345">Outlook のユーザーが共有の予定表を使用した後、メッセージ一覧の更新が数分間停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1345">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="5dd8e-1346">予定表のリマインダーで、1 週間以内に行われる会議の正確な時刻が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1346">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="5dd8e-1347">メッセージに画像をインラインで挿入し、メッセージを下書きとして保存すると画像のサイズが変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1347">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="5dd8e-1348">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1348">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="5dd8e-1349">日本のユーザーに対してミニ カレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1349">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1350">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1351">ライブの共同編集セッション中に共同編集ギャラリーでユーザーのプレゼンス カラー インジケーターが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1351">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="5dd8e-1352">スライドのテキスト領域に HTML を貼り付けると、代わりにスライドの上部に作成されたテキスト ボックスに貼り付けられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1352">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="5dd8e-1353">発表者ビューですべてのスライドを選択し、Alt + Tabを使用して発表者ビューを終了し、スライド ショーに戻って [ショーの終了] をクリックすると、未処理の例外が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1353">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-1354">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1354">Project</span></span>

- <span data-ttu-id="5dd8e-1355">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1355">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="5dd8e-1356">URL の末尾が「.com」の場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1356">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="5dd8e-1357">特定の XML ファイルを開くと、Project がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1357">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="5dd8e-1358">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1358">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="5dd8e-1359">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1359">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="5dd8e-1360">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1360">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="5dd8e-1361">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1361">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="5dd8e-1362">固定期間タスクが 100% 完了しているが、実際の完了が指定されていない場合、タスク完了率が 100% 未満として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1362">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="5dd8e-1363">ベースラインのリセットまたは更新により、時間単位の予算コスト/作業リソースが変更され、ベースラインが誤った予算値を反映する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1363">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="5dd8e-1364">Government Community Cloud 環境でプロジェクト プランナのリンクが無効になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1364">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="5dd8e-1365">ライブラリがモダン モードの場合、SharePoint ドキュメント ライブラリから Project ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1365">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-1366">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1366">Word</span></span>

- <span data-ttu-id="5dd8e-1367">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式設定をクリアする機能が動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1367">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="5dd8e-1368">スケーラブル ベクター グラフィックス （SVG）に挿入されたテキストを、Word、Excel、または PowerPoint ファイルに挿入し、ファイルを保存して閉じ、再度開いた後、判読できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1368">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="5dd8e-1369">ルーラーが表示されていないときにテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションが点滅し始める問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1369">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="5dd8e-1370">共同編集モードで、コメントの返信がコメント ウィンドウに表示されず、変更履歴ウィンドウに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1370">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="5dd8e-1371">マージの競合があり、ユーザーが既に変更を破棄することを選択している場合の共同編集モード中の問題を修正し、変更を保存または破棄するオプションを表示しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1371">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="5dd8e-1372">HTML ハイパーリンクの色が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1372">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="5dd8e-1373">Wordに 50 を超える頻繁に開かれる文書のリストがある場合、文書を保存して開いた後、その文書に変更が加えられていなくても、変更履歴が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1373">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="5dd8e-1374">共同編集中の自動保存に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1374">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="5dd8e-1375">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても「WRO0004.docx」というファイル名で保存されるため、その文書を使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1375">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-1376">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1376">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1377">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1377">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="5dd8e-1378">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1378">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="5dd8e-1379">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1379">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2006-july-09"></a><span data-ttu-id="5dd8e-1381">バージョン 2006: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1381">Version 2006: July 09</span></span>
<span data-ttu-id="5dd8e-1382">*バージョン 2006 (ビルド 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1382">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1384">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1384">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1385">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1385">Excel</span></span>

- <span data-ttu-id="5dd8e-1386">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1386">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="5dd8e-1387">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1387">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="5dd8e-1388">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1388">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="5dd8e-1389">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1389">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="5dd8e-1390">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1390">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="5dd8e-1391">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1391">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="5dd8e-1392">**Excel のショートカットキー:** 更新された Excel のショートカットキー</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1392">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1393">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1393">Outlook</span></span>

- <span data-ttu-id="5dd8e-1394">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1394">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="5dd8e-1395">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1395">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1398">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1398">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1399">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1399">Access</span></span>

- <span data-ttu-id="5dd8e-1400">この問題は解決されており、ID (オートナンバーなど) フィールドを含むリンクされた SQL テーブルを Access に正常に挿入できるようになります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1400">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="5dd8e-1401">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1401">Excel</span></span>

- <span data-ttu-id="5dd8e-1402">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1402">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1403">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1403">Outlook</span></span>

- <span data-ttu-id="5dd8e-1404">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1404">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5dd8e-1405">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1405">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1406">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1406">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="5dd8e-1407">レジストリ TabProcGrowth の値がREG_SZ型で値 "0" でアドインがアクティブ化されているときに、Windows の Office ホストがクラッシュしていました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1407">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="5dd8e-1408">このレジストリ ボックスには、4つのパスのいずれかを使用できます。 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main。この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1408">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-25"></a><span data-ttu-id="5dd8e-1410">バージョン 2006: 6月 25 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1410">Version 2006: June 25</span></span>
<span data-ttu-id="5dd8e-1411">*バージョン 2006 (ビルド 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1411">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1413">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1413">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="5dd8e-1414">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1414">Visio</span></span>

- <span data-ttu-id="5dd8e-1415">**Excel で洗練された Visio 図を作成する:** ワークシートのデータに基づいて、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1415">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1418">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1418">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1419">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1419">Access</span></span>

- <span data-ttu-id="5dd8e-1420">この問題は解決されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1420">This problem is now resolved.</span></span> <span data-ttu-id="5dd8e-1421">このプロセスでさらに問題が発生した場合は、チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1421">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-1422">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1422">Outlook</span></span>

- <span data-ttu-id="5dd8e-1423"><span style="display:inline !important;">ドラッグ アンド ドロップによってファイル システムにコピーされた添付<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">ファイルの作成日&nbsp; が、&nbsp;4501年1月1日に設定された問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="5dd8e-1423"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="5dd8e-1424"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span></span><span class="sxs-lookup"><span data-stu-id="5dd8e-1424"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="5dd8e-1425"><span style="display:inline !important;">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="5dd8e-1425"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="5dd8e-1426"><span style="display:inline !important;">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="5dd8e-1426"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-18"></a><span data-ttu-id="5dd8e-1428">バージョン 2006: 6 月 18 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1428">Version 2006: June 18</span></span>
<span data-ttu-id="5dd8e-1429">*バージョン 2006 (ビルド 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1429">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1431">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1431">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1432">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1432">Excel</span></span>



- <span data-ttu-id="5dd8e-1433">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1433">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="5dd8e-1434">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1434">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="5dd8e-1435">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1435">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="5dd8e-1436">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1436">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1437">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1438">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1438">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="5dd8e-1439">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1439">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="5dd8e-1440">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1440">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="5dd8e-1441">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1441">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1442">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1442">Word</span></span>

- <span data-ttu-id="5dd8e-1443">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1443">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="5dd8e-1444">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1444">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="5dd8e-1445">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1445">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="5dd8e-1446">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1446">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1449">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1449">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1450">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1450">Excel</span></span>

- <span data-ttu-id="5dd8e-1451">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1451">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1452">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1452">Outlook</span></span>

- <span data-ttu-id="5dd8e-1453">クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1453">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="5dd8e-1454">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1454">Project</span></span>

- <span data-ttu-id="5dd8e-1455">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1455">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-11"></a><span data-ttu-id="5dd8e-1457">バージョン 2006: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1457">Version 2006: June 11</span></span>
<span data-ttu-id="5dd8e-1458">*バージョン 2006 (ビルド 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1458">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1460">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1460">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1461">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1462">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1462">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="5dd8e-1463">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1463">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1464">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1464">Word</span></span>

- <span data-ttu-id="5dd8e-1465">**テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1465">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1468">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1468">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1469">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1469">Excel</span></span>

- <span data-ttu-id="5dd8e-1470">OneDrive を起動すると Excel がシャットダウンすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1470">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="5dd8e-1471">グラフの軸にカスタム値が正しく適用されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1471">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="5dd8e-1472">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1472">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="5dd8e-1473">使用可能なプリンターのリストでプリンター名が重複する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1473">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="5dd8e-1474">ユーザーがマージされた列を削除したときのパフォーマンス時間が向上する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1474">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="5dd8e-1475">アドインは、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」 というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1475">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="5dd8e-1476">Excelとサード パーティの支援技術アプリケーションの一部との間でフォントを管理する際にメモリが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1476">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="5dd8e-1477">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1477">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="5dd8e-1478">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1478">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="5dd8e-1479">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1479">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="5dd8e-1480">選択ロックがない図形を含むワークシート上で、アドインがホスト アイテムを要求すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1480">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="5dd8e-1481">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1481">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1482">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1482">Outlook</span></span>

- <span data-ttu-id="5dd8e-1483">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1483">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="5dd8e-1484">新しいメール メッセージの作成時にテンプレートを表示するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1484">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="5dd8e-1485">Outlook バージョン1911以降、ユーザーが Exchange 2010のパブリック フォルダーを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1485">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="5dd8e-1486">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1486">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="5dd8e-1487">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1487">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="5dd8e-1488">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1488">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="5dd8e-1489">ユーザーが予定表をゲストユーザーと共有できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1489">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="5dd8e-1490">予定表のアイテムが真夜中にまたがっていると、終日イベントとして表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1490">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="5dd8e-1491">高 DPI のモニターを使用しているユーザーに対して、フォルダー プロパティの [オンライン アーカイブ] ドロップダウンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1491">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="5dd8e-1492">ユーザーがフォルダー間でアイテムを移動したときに、「BeforeItemMove」 イベントが正常に起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1492">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="5dd8e-1493">2つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1493">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="5dd8e-1494">テキスト形式のメールでハイパーリンクを使用して作業しているときに、Outlook でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1494">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="5dd8e-1495">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1495">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="5dd8e-1496">スクリーン リーダーを使用すると、Outlook ユーザーの断続的なハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1496">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="5dd8e-1497">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1497">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1498">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1498">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1499">サーバ構成のファイルをフォームベースの認証で開くときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1499">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="5dd8e-1500">グラフまたはブックが埋め込まれた PowerPoint ファイルの保存時にエラーが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1500">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="5dd8e-1501">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1501">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="5dd8e-1502">マウス ホイールを使用して拡大した後、スライドが中央に配置されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1502">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="5dd8e-1503">英語スイス (QWERTZ) キーボードを使用すると、キーボード ショートカットとスペル チェックが期待どおりに機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1503">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="5dd8e-1504">ユーザーによって終了されたコメント ウィンドウが自動的に再起動するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1504">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="5dd8e-1505">1つのスライドからのスライド エディタが次のスライドに重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1505">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="5dd8e-1506">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1506">Project</span></span>

- <span data-ttu-id="5dd8e-1507">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1507">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="5dd8e-1508">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1508">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="5dd8e-1509">オプションをクリックするとプロジェクトがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1509">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="5dd8e-1510">親計画が削除された後、孤立したタスクの削除や再割り当てができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1510">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="5dd8e-1511">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1511">Visio</span></span>

- <span data-ttu-id="5dd8e-1512">依存コードに回帰がありましたが、これは修正されています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1512">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="5dd8e-1513">これで、SharePoint Onprem で実行されている Visio services の画像が表示されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1513">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1514">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1514">Word</span></span>

- <span data-ttu-id="5dd8e-1515">コメント ウィンドウのタイムスタンプがシステム ロケールの時間に基づいていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1515">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="5dd8e-1516">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1516">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="5dd8e-1517">テキストのコピーと貼り付けがコメント ウィンドウに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1517">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="5dd8e-1518">コメント内のハイパーリンクが機能しなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1518">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="5dd8e-1519">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1519">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="5dd8e-1520">Web アプリとデスクトップ アプリケーションの間のコメントが同期していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1520">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="5dd8e-1521">100% ズームでコメント ヒントの泡がぼやけて見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1521">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="5dd8e-1522">空白のドキュメントに新しいコメントを追加しても何も発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1522">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="5dd8e-1523">予定表用の WordMail に HTML を貼り付けできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1523">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="5dd8e-1524">共同編集セッションのコメントに返信すると、Word がフリーズすることがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1524">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="5dd8e-1525">100 個を超えるエントリを含むドキュメントにインデックスを挿入または更新すると、アプリケーションがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1525">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="5dd8e-1526">ポリシー Word 2007以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集で失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1526">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="5dd8e-1527">カスタム xml 値を含むファイルを開くのが非常に遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1527">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="5dd8e-1528">長いパス名 (32K を超える) のファイルが開かず、適切なエラー メッセージが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1528">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5dd8e-1529">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1529">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1530">OS のシャットダウン後、InTune を介した Office 365 ProPlus の展開が停止する問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1530">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="5dd8e-1531">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1531">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="5dd8e-1532">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1532">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-08"></a><span data-ttu-id="5dd8e-1534">バージョン 2005: 6月 8 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1534">Version 2005: June 08</span></span>
<span data-ttu-id="5dd8e-1535">*バージョン 2005 (ビルド 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1535">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1537">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1537">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1538">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1539">[フォントの置換] ダイアログボックスで、[フォントの置換] ドロップダウンリストには、システムにインストールされているフォントの代わりにプレゼンテーション内のフォントしか表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1539">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-04"></a><span data-ttu-id="5dd8e-1541">バージョン 2005: 6月 4 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1541">Version 2005: June 04</span></span>
<span data-ttu-id="5dd8e-1542">*バージョン 2005 (ビルド 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1542">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1544">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1544">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1545">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1545">Access</span></span>

- <span data-ttu-id="5dd8e-1546">**時代に追いつきましょう! 日付/時刻の拡張データ型では、より精度が高くなります。:** 改良されたデータ型をご紹介します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1546">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="5dd8e-1547">SQL との構文の互換性を高め、日付と時刻を含むレコードの精度と詳細レベルを向上させるため、Access に DateTime2 データ型を実装しています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1547">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="5dd8e-1548">この追加の日付および時間のデータ型には、より大きい日付範囲 (0001-01-01 ～ 9999-12-31) が含まれます。これにより、指定された時間の精度 (秒単位ではなくナノ秒) で提供され、計算を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1548">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="5dd8e-1549">有効にするには、[新しいフィールド] > [日付と時間の拡張] を選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1549">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="5dd8e-1550">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1550">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="5dd8e-1551">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1551">Excel</span></span>

- <span data-ttu-id="5dd8e-1552">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1552">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="5dd8e-1553">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1553">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="5dd8e-1554">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1554">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1555">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1555">Outlook</span></span>

- <span data-ttu-id="5dd8e-1556">**以前の Outlook セッションからアイテムを素早く再開するオプション:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1556">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1559">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1559">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1560">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1560">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1561">これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1561">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-1562">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1562">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1563">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1563">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-29"></a><span data-ttu-id="5dd8e-1565">バージョン 2005: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1565">Version 2005: May 29</span></span>
<span data-ttu-id="5dd8e-1566">*バージョン 2005 (ビルド 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1566">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1568">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1568">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="5dd8e-1569">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1569">Excel</span></span>

- <span data-ttu-id="5dd8e-1570">**シート ビュー:** Excel デスクトップで他のユーザーとの共同作業を行っているときに、並べ替えまたはフィルタリングを行います。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1570">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1571">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1571">Outlook</span></span>

- <span data-ttu-id="5dd8e-1572">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1572">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1575">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1575">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="5dd8e-1576">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1576">Outlook</span></span>

- <span data-ttu-id="5dd8e-1577">Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効です」という警告が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1577">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="5dd8e-1578">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1578">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5dd8e-1579">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1579">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1580">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1580">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="5dd8e-1581">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1581">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-21"></a><span data-ttu-id="5dd8e-1583">バージョン 2005: 5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1583">Version 2005: May 21</span></span>
<span data-ttu-id="5dd8e-1584">*バージョン 2005 (ビルド 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1584">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1588">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1588">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1589">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1589">Excel</span></span>

- <span data-ttu-id="5dd8e-1590">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1590">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="5dd8e-1591">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1591">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="5dd8e-1592">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1592">Outlook</span></span>

- <span data-ttu-id="5dd8e-1593">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1593">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="5dd8e-1594">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1594">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-14"></a><span data-ttu-id="5dd8e-1596">バージョン 2005: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1596">Version 2005: May 14</span></span>
<span data-ttu-id="5dd8e-1597">*バージョン 2005 (ビルド 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1597">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1599">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1599">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1600">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1600">Excel</span></span>

- <span data-ttu-id="5dd8e-1601">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1601">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1602">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1603">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1603">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="5dd8e-1604">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1604">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="5dd8e-1605">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1605">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="5dd8e-1606">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1606">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="5dd8e-1607">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1607">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1608">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1608">Word</span></span>

- <span data-ttu-id="5dd8e-1609">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1609">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1612">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1612">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="5dd8e-1613">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1613">Excel</span></span>

- <span data-ttu-id="5dd8e-1614">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1614">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="5dd8e-1615">グラフのデータ テーブルの日付軸の値が正しく表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1615">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="5dd8e-1616">[ページ レイアウト] または [改ページ プレビュー] に移動した後に、改ページを無効にできなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1616">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="5dd8e-1617">系列のデータを含む列を非表示にしてから非表示を解除すると、グラフの線のスタイルが失われる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1617">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="5dd8e-1618">フィルタリングされたリストに列を挿入すると、通常よりも時間がかかってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1618">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="5dd8e-1619">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1619">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="5dd8e-1620">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1620">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="5dd8e-1621">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1621">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="5dd8e-1622">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1622">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="5dd8e-1623">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1623">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="5dd8e-1624">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1624">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="5dd8e-1625">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1625">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="5dd8e-1626">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1626">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="5dd8e-1627">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1627">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="5dd8e-1628">[Invert if negative]\(負の値を反転する\) オプションが有効になっていると、ピボット グラフのカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1628">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="5dd8e-1629">[Invert if negative]\(負の値を反転する\) オプションが選択されていると、ピボット グラフの単一のデータ ポイントに対するカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1629">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="5dd8e-1630">この変更により、CSV ファイルで "@" 文字をアップロードすると、その "@" 文字以降の文字列が数式に変換される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1630">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="5dd8e-1631">SEQUENCE 関数で小数点以下が正しく四捨五入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1631">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="5dd8e-1632">OneNote</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1632">OneNote</span></span>

- <span data-ttu-id="5dd8e-1633">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1633">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1634">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1634">Outlook</span></span>

- <span data-ttu-id="5dd8e-1635">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1635">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="5dd8e-1636">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1636">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="5dd8e-1637">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1637">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="5dd8e-1638">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1638">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="5dd8e-1639">Outlook デスクトップ クライアントで、ユーザーがクリックした非常に長いセーフリンクが、切り捨てにより読み込みに失敗する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1639">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="5dd8e-1640">DBCS (2 バイト文字セット) 文字を含む名前が付けられた Outlook フォルダーが、サーバーと同期するときに断続的に表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1640">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="5dd8e-1641">この問題が発生する場合は、Outlook を IMAP アカウントを使用して構成し、ロケールが日本語に設定されたシステム上で実行する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1641">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="5dd8e-1642">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1642">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="5dd8e-1643">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1643">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="5dd8e-1644">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1644">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="5dd8e-1645">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1645">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="5dd8e-1646">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1646">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1647">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1648">ユーザーがコメントを作成したのに投稿せずにそのコメント ウィンドウを閉じ、新しいウィンドウを開いて、複数のスライドを移動してからそのウィンドウを閉じ、最後に、元のプレゼンテーションでコメント ウィンドウをもう一度開くと、下書きのコメントが利用できなくなっている問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1648">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="5dd8e-1649">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1649">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="5dd8e-1650">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1650">Project</span></span>

- <span data-ttu-id="5dd8e-1651">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1651">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="5dd8e-1652">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1652">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="5dd8e-1653">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1653">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="5dd8e-1654">Project が Project Web App に接続されていて、小数点の記号がカンマの場合、タイム ラグを追加する際に TaskDependencies Add メソッドが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1654">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-1655">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1655">Word</span></span>

- <span data-ttu-id="5dd8e-1656">コラボレーション モードのドキュメントにコメントを挿入しても正常に動作しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1656">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="5dd8e-1657">この変更により、@メンションがクリックされると連絡先カードが点滅する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1657">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="5dd8e-1658">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1658">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="5dd8e-1659">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1659">This has been fixed.</span></span>

- <span data-ttu-id="5dd8e-1660">下書きのコメントを含むドキュメントを閉じようとすると、その下書きのコメントを保存せずにドキュメントを閉じてもよいかユーザーに確認を求める問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1660">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="5dd8e-1661">このプロンプトをキャンセルすると、ドキュメントが開いたままになるのではなく、閉じられていました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1661">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="5dd8e-1662">見出しをコピー & ペーストする際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1662">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="5dd8e-1663">投稿されたコメントを翻訳しようとすると、"Inserting translated text failed" (翻訳されたテキストの挿入に失敗しました) エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1663">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="5dd8e-1664">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1664">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="5dd8e-1665">Web ビュー/イマーシブ リーダーでヒントをクリックすると、ヒントが既に表示されている場合でも一番上までスクロールしていました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1665">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="5dd8e-1666">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1666">This has been fixed.</span></span>

- <span data-ttu-id="5dd8e-1667">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても WRO0004.docx というファイル名で保存されるため、そのドキュメントを使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1667">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5dd8e-1668">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1668">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1669">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1669">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="5dd8e-1670">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1670">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="5dd8e-1671">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1671">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="5dd8e-1672">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1672">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="5dd8e-1673">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1673">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-11"></a><span data-ttu-id="5dd8e-1675">バージョン 2004: 5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1675">Version 2004: May 11</span></span>
<span data-ttu-id="5dd8e-1676">*バージョン 2004 (ビルド 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1676">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1678">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1678">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1679">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1679">Excel</span></span>

- <span data-ttu-id="5dd8e-1680">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1680">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1681">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1681">Outlook</span></span>

- <span data-ttu-id="5dd8e-1682">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1682">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="5dd8e-1683">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1683">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="5dd8e-1684">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1684">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="5dd8e-1685">[ブログの投稿](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1685">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="5dd8e-1686">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1686">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1687">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1687">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1688">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1688">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="5dd8e-1689">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1689">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="5dd8e-1690">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1690">Word</span></span>

- <span data-ttu-id="5dd8e-1691">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1691">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1694">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1694">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1695">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1695">Outlook</span></span>

- <span data-ttu-id="5dd8e-1696">ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1696">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-04"></a><span data-ttu-id="5dd8e-1698">バージョン 2004: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1698">Version 2004: May 04</span></span>
<span data-ttu-id="5dd8e-1699">*バージョン 2004 (ビルド 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1699">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1701">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1701">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1702">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1702">Outlook</span></span>

- <span data-ttu-id="5dd8e-1703">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1703">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="5dd8e-1704">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1704">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="5dd8e-1705">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1705">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="5dd8e-1706">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1706">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1709">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1709">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="5dd8e-1710">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1710">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1711">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1711">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-29"></a><span data-ttu-id="5dd8e-1713">バージョン 2004: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1713">Version 2004: April 29</span></span>
<span data-ttu-id="5dd8e-1714">*バージョン 2004 (ビルド 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1714">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1716">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1716">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1717">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1717">Outlook</span></span>

- <span data-ttu-id="5dd8e-1718">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1718">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1721">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1721">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1722">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1722">Outlook</span></span>

- <span data-ttu-id="5dd8e-1723">Windows の一部のビルドで Outlook がクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1723">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2004-april-25"></a><span data-ttu-id="5dd8e-1725">バージョン 2004: 4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1725">Version 2004: April 25</span></span>
<span data-ttu-id="5dd8e-1726">*バージョン 2004 (ビルド 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1726">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1728">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1728">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1729">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1729">Outlook</span></span>

- <span data-ttu-id="5dd8e-1730">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1730">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="5dd8e-1731">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1731">Project</span></span>

- <span data-ttu-id="5dd8e-1732">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1732">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-1733">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1733">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1734">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1734">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-21"></a><span data-ttu-id="5dd8e-1736">バージョン 2004: 4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1736">Version 2004: April 21</span></span>
<span data-ttu-id="5dd8e-1737">*バージョン 2004 (ビルド 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1737">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1739">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1739">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1740">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1740">Outlook</span></span>

- <span data-ttu-id="5dd8e-1741">フォルダー ウィンドウの幅が予期せず変更される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1741">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="5dd8e-1742">Outlook の終了中にユーザーが応答停止を経験する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1742">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-15"></a><span data-ttu-id="5dd8e-1744">バージョン 2004: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1744">Version 2004: April 15</span></span>
<span data-ttu-id="5dd8e-1745">*バージョン 2004 (ビルド 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1745">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1747">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1747">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1748">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1748">Excel</span></span>

- <span data-ttu-id="5dd8e-1749">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1749">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1750">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1750">Outlook</span></span>

- <span data-ttu-id="5dd8e-1751">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1751">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="5dd8e-1752">望むなら、オフにすることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1752">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1753">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1753">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1754">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1754">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1755">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1755">Word</span></span>

- <span data-ttu-id="5dd8e-1756">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成できます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1756">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="5dd8e-1757">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1757">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1760">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1760">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1761">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1761">Access</span></span>

- <span data-ttu-id="5dd8e-1762">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1762">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="5dd8e-1763">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1763">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="5dd8e-1764">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1764">Excel</span></span>

- <span data-ttu-id="5dd8e-1765">シートのセル範囲を選択しているのに、単一セルの選択になってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1765">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="5dd8e-1766">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1766">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="5dd8e-1767">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1767">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="5dd8e-1768">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1768">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="5dd8e-1769">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1769">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="5dd8e-1770">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1770">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="5dd8e-1771">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1771">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="5dd8e-1772">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1772">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="5dd8e-1773">X 軸の範囲によっては、グラフのサイズを小さくすると、Excel が応答を停止する場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1773">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="5dd8e-1774">R1C1 セルの参照が有効になっている Excel シートが共同編集 / 共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動しても、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1774">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="5dd8e-1775">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1775">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1776">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1776">Outlook</span></span>

- <span data-ttu-id="5dd8e-1777">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1777">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="5dd8e-1778">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1778">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="5dd8e-1779">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1779">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="5dd8e-1780">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1780">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="5dd8e-1781">メール メッセージからカテゴリが消えることがあるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1781">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="5dd8e-1782">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1782">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="5dd8e-1783">ユーザーが組織フォームのプロパティを表示しようとするとクラッシュするという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1783">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="5dd8e-1784">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1784">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="5dd8e-1785">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1785">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="5dd8e-1786">返信の対象のメッセージに対してユーザーが所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1786">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="5dd8e-1787">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1787">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="5dd8e-1788">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1788">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="5dd8e-1789">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1789">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="5dd8e-1790">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1790">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="5dd8e-1791">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1791">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1792">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1792">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1793">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1793">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="5dd8e-1794">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1794">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="5dd8e-1795">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1795">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="5dd8e-1796">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1796">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="5dd8e-1797">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1797">Project</span></span>

- <span data-ttu-id="5dd8e-1798">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1798">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="5dd8e-1799">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1799">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="5dd8e-1800">ユーザーがスケジュール グループ内の [タスク] リボンにある [無効化] ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Application (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1800">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="5dd8e-1801">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1801">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="5dd8e-1802">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1802">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="5dd8e-1803">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1803">This behavior has been fixed.</span></span>

- <span data-ttu-id="5dd8e-1804">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1804">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="5dd8e-1805">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1805">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="5dd8e-1806">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1806">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="5dd8e-1807">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1807">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="5dd8e-1808">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1808">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="5dd8e-1809">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1809">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="5dd8e-1810">[フォーム] ビュー内で先行処理 / 後続処理データを編集すると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1810">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="5dd8e-1811">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1811">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1812">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1812">Word</span></span>

- <span data-ttu-id="5dd8e-1813">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1813">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="5dd8e-1814">この変更により、[表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1814">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="5dd8e-1815">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1815">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="5dd8e-1816">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1816">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="5dd8e-1817">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1817">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="5dd8e-1818">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1818">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="5dd8e-1819">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1819">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="5dd8e-1820">この変更により、2 ページ表示で、コメントを作成するとき、コメント アンカーが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1820">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="5dd8e-1821">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1821">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="5dd8e-1822">スタイルがリストにリンクされているスタイルの祖先である段落の場合、そのリストの番号が失われる場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1822">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="5dd8e-1823">この変更により、文書に存在しない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1823">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="5dd8e-1824">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1824">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="5dd8e-1825">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1825">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="5dd8e-1826">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1826">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="5dd8e-1827">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1827">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-14"></a><span data-ttu-id="5dd8e-1829">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1829">Version 2003: April 14</span></span>
<span data-ttu-id="5dd8e-1830">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1830">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="5dd8e-1831">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1831">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

- <span data-ttu-id="5dd8e-1833">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1833">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-09"></a><span data-ttu-id="5dd8e-1835">バージョン 2003: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1835">Version 2003: April 09</span></span>
<span data-ttu-id="5dd8e-1836">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1836">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1838">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1838">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1839">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1839">Excel</span></span>

- <span data-ttu-id="5dd8e-1840">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1840">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="5dd8e-1841">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1841">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1842">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1842">Outlook</span></span>

- <span data-ttu-id="5dd8e-1843">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1843">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="5dd8e-1844">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1844">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1845">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1845">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1846">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1846">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="5dd8e-1847">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1847">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1848">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1848">Word</span></span>

- <span data-ttu-id="5dd8e-1849">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1849">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="5dd8e-1850">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1850">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-03"></a><span data-ttu-id="5dd8e-1854">バージョン 2003: 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1854">Version 2003: April 03</span></span>
<span data-ttu-id="5dd8e-1855">*バージョン 2003 (ビルド 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1855">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1857">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1857">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1858">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1858">Excel</span></span>

- <span data-ttu-id="5dd8e-1859">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1859">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1860">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1860">Outlook</span></span>

- <span data-ttu-id="5dd8e-1861">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1861">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="5dd8e-1862">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1862">Project</span></span>

- <span data-ttu-id="5dd8e-1863">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChangeevent が発生します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1863">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1864">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1864">Word</span></span>

- <span data-ttu-id="5dd8e-1865">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1865">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="5dd8e-1867">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1867">Version 2003: March 31</span></span>
<span data-ttu-id="5dd8e-1868">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1868">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1870">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1870">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-1871">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1871">Access</span></span>

- <span data-ttu-id="5dd8e-1872">**[テーブルの追加] 作業ウィンドウ:** Access の新しい [テーブルの追加] 作業ウィンドウを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1872">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="5dd8e-1873">この機能を使用すると、クエリやリレーションシップ ビューのために [テーブルの表示] ダイアログボックスに移動することなく、クエリ ウィンドウに追加またはそこから削除する 1 つ以上のテーブルを簡単に選択することができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1873">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="5dd8e-1874">この機能には、リンク テーブルを表示するための新しい [リンク] タブ、現在のリストをフィルター処理するための検索ボックス、"ドラッグ アンド ドロップ" による操作なども含まれます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1874">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1877">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1877">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="5dd8e-1878">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1878">Project</span></span>

- <span data-ttu-id="5dd8e-1879"><span style="display:inline !important;">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="5dd8e-1879"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="5dd8e-1881">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1881">Version 2003: March 25</span></span>
<span data-ttu-id="5dd8e-1882">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1882">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="5dd8e-1883">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1883">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="5dd8e-1884">バージョン 2003: 3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1884">Version 2003: March 23</span></span>
<span data-ttu-id="5dd8e-1885">*バージョン 2003 (ビルド 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1885">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="5dd8e-1886">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1886">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="5dd8e-1887">バージョン 2003: 3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1887">Version 2003: March 21</span></span>
<span data-ttu-id="5dd8e-1888">*バージョン 2003 (ビルド 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1888">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1890">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1890">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-1891">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1891">Outlook</span></span>

- <span data-ttu-id="5dd8e-1892">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1892">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="5dd8e-1893">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1893">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="5dd8e-1894">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1894">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="5dd8e-1895">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1895">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1896">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1896">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1897">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1897">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-16"></a><span data-ttu-id="5dd8e-1899">Version 2003: March 16</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1899">Version 2003: March 16</span></span>
<span data-ttu-id="5dd8e-1900">*バージョン 2003 (ビルド 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1900">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1902">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1902">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1903">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1903">Excel</span></span>

- <span data-ttu-id="5dd8e-1904">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1904">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1905">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1905">Outlook</span></span>

- <span data-ttu-id="5dd8e-1906">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1906">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1907">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1907">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1908">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1908">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1909">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1909">Word</span></span>

- <span data-ttu-id="5dd8e-1910">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1910">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5dd8e-1911">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1911">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1912">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1912">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="5dd8e-1913">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1913">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1916">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1916">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1917">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1917">Excel</span></span>

- <span data-ttu-id="5dd8e-1918">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1918">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-1919">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1919">Outlook</span></span>

- <span data-ttu-id="5dd8e-1920">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1920">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-10"></a><span data-ttu-id="5dd8e-1922">バージョン 2003: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1922">Version 2003: March 10</span></span>
<span data-ttu-id="5dd8e-1923">*バージョン 2003 (ビルド 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1923">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="5dd8e-1924">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1924">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)
### <a name="feature-updates"></a><span data-ttu-id="5dd8e-1926">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1926">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1927">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1927">Excel</span></span>
- <span data-ttu-id="5dd8e-1928">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1928">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="5dd8e-1929">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1929">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1930">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1930">PowerPoint</span></span>
- <span data-ttu-id="5dd8e-1931">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1931">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="5dd8e-1932">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1932">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="5dd8e-1933">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1933">Word</span></span>
- <span data-ttu-id="5dd8e-1934">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1934">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="5dd8e-1935">詳細情報</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1935">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1936">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1936">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-1937">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1937">Excel</span></span>

- <span data-ttu-id="5dd8e-1938">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1938">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="5dd8e-1939">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1939">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="5dd8e-1940">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1940">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="5dd8e-1941">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1941">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="5dd8e-1942">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1942">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="5dd8e-1943">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1943">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="5dd8e-1944">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1944">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="5dd8e-1945">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1945">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="5dd8e-1946">この変更では、アドインによって noSelect ロックがある図形を含むドキュメントまたはワークシートのホスト アイテムが求められるときに、オブジェクト モデルでランタイム エラーが発生する問題および App (Excel、Word) がクラッシュする可能性がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1946">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="5dd8e-1947">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1947">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="5dd8e-1948">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1948">Outlook</span></span>

- <span data-ttu-id="5dd8e-1949">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1949">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="5dd8e-1950">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1950">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="5dd8e-1951">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1951">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="5dd8e-1952">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1952">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="5dd8e-1953">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1953">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="5dd8e-1954">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1954">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="5dd8e-1955">ユーザーが「&quot;空き時間情報オプション&quot;」予定表のアクセス許可ダイアログにアクセスできなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1955">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="5dd8e-1956">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「&quot;申し訳ございません、このアイテムを開くことができません&quot;」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1956">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="5dd8e-1957">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1957">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="5dd8e-1958">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1958">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="5dd8e-1959">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1959">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="5dd8e-1960">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1960">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="5dd8e-1961">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1961">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-1962">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1962">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="5dd8e-1963">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1963">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="5dd8e-1964">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1964">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="5dd8e-1965">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1965">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="5dd8e-1966">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1966">Project</span></span>

- <span data-ttu-id="5dd8e-1967">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1967">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="5dd8e-1968">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1968">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="5dd8e-1969">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1969">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="5dd8e-1970">Visio</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1970">Visio</span></span>

- <span data-ttu-id="5dd8e-1971">Visio デスクトップで開いたファイルに関して、[図形情報] ウィンドウの [図形データ] セクションに矛盾した詳細が表示されていました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1971">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="5dd8e-1972">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1972">It has now been fixed.</span></span>

- <span data-ttu-id="5dd8e-1973">何らかのセキュリティ チェックが原因で、2016 より前のバージョンでインポートされたビットマップは表示されていませんでした。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1973">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="5dd8e-1974">この問題は Visio サブスクリプションで修正されました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1974">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-1975">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1975">Word</span></span>

- <span data-ttu-id="5dd8e-1976">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1976">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="5dd8e-1977">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1977">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="5dd8e-1978">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1978">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="5dd8e-1979">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1979">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="5dd8e-1980">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1980">This issue has been fixed.</span></span>

- <span data-ttu-id="5dd8e-1981">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1981">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="5dd8e-1982">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1982">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="5dd8e-1983">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1983">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="5dd8e-1984">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1984">Office Suite</span></span>

- <span data-ttu-id="5dd8e-1985">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1985">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="5dd8e-1986">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1986">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="5dd8e-1987">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1987">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="5dd8e-1988">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1988">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="5dd8e-1989">同じ SharePoint ライブラリから Word、Excel、PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1989">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-05"></a><span data-ttu-id="5dd8e-1991">バージョン 2002: 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1991">Version 2002: March 05</span></span>
<span data-ttu-id="5dd8e-1992">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1992">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="5dd8e-1993">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1993">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="5dd8e-1994">バージョン 2002: 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1994">Version 2002: March 04</span></span>
<span data-ttu-id="5dd8e-1995">*バージョン 2002 (ビルド 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1995">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-1997">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1997">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="5dd8e-1998">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1998">Project</span></span>
- <span data-ttu-id="5dd8e-1999">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-1999">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-2000">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2000">Office Suite</span></span>
- <span data-ttu-id="5dd8e-2001">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2001">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-01"></a><span data-ttu-id="5dd8e-2003">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2003">Version 2002: March 01</span></span>
<span data-ttu-id="5dd8e-2004">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2004">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-2005">解決した問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2005">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-2006">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2006">Outlook</span></span>

- <span data-ttu-id="5dd8e-2007">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2007">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-24"></a><span data-ttu-id="5dd8e-2009">バージョン 2002: 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2009">Version 2002: February 24</span></span>
<span data-ttu-id="5dd8e-2010">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2010">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="5dd8e-2011">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2011">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="5dd8e-2012">バージョン 2002: 2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2012">Version 2002: February 22</span></span>
<span data-ttu-id="5dd8e-2013">*バージョン 2002 (ビルド 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2013">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="5dd8e-2014">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2014">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="5dd8e-2015">バージョン 2002: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2015">Version 2002: February 21</span></span>
<span data-ttu-id="5dd8e-2016">*バージョン 2002 (ビルド 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2016">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-2018">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2018">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-2019">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2019">Access</span></span>

- <span data-ttu-id="5dd8e-2020">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2020">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="5dd8e-2021">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2021">Search and replace text in SQL View.</span></span> <span data-ttu-id="5dd8e-2022">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2022">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-2023">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2023">Outlook</span></span>

- <span data-ttu-id="5dd8e-2024">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2024">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="5dd8e-2025">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2025">Outlook now detects this and helps you get connected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-2028">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2028">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="5dd8e-2029">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2029">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="5dd8e-2030">CUBEVALUE 関数が間違った結果を返すことがある問題を修正しました。&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="5dd8e-2030">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="5dd8e-2031">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2031">Outlook</span></span>

- <span data-ttu-id="5dd8e-2032">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2032">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="5dd8e-2033">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2033">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="5dd8e-2034">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2034">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="5dd8e-2035">黒のテーマを持つユーザーが [&quot;差出人&quot;] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2035">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="5dd8e-2036"><span style="display:inline !important;">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span></span><span class="sxs-lookup"><span data-stu-id="5dd8e-2036"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-18"></a><span data-ttu-id="5dd8e-2038">バージョン 2002: 2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2038">Version 2002: February 18</span></span>
<span data-ttu-id="5dd8e-2039">*バージョン 2002 (ビルド 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2039">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="5dd8e-2040">バージョン 2002: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2040">Version 2002: February 11</span></span>
<span data-ttu-id="5dd8e-2041">*バージョン 2002 (ビルド 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2041">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="5dd8e-2042">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2042">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="5dd8e-2044">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2044">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="5dd8e-2045">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2045">Outlook</span></span>

- <span data-ttu-id="5dd8e-2046">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2046">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="5dd8e-2047">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2047">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="5dd8e-2048">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2048">Word</span></span>

- <span data-ttu-id="5dd8e-2049">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2049">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="5dd8e-2050">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2050">Office Suite</span></span>

- <span data-ttu-id="5dd8e-2051">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2051">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="5dd8e-2054">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2054">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="5dd8e-2055">Access</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2055">Access</span></span>

- <span data-ttu-id="5dd8e-2056">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2056">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="5dd8e-2057">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2057">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="5dd8e-2058">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2058">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="5dd8e-2059">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2059">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="5dd8e-2060">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2060">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="5dd8e-2061">Excel</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2061">Excel</span></span>

- <span data-ttu-id="5dd8e-2062">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2062">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="5dd8e-2063">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2063">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="5dd8e-2064">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2064">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="5dd8e-2065">Outlook</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2065">Outlook</span></span>

- <span data-ttu-id="5dd8e-2066">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2066">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="5dd8e-2067">左側のナビゲーション ウィンドウで [お気に入り] に保存したフォルダーが断続的に表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2067">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="5dd8e-2068">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2068">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="5dd8e-2069">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2069">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="5dd8e-2070">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2070">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="5dd8e-2071">アイテム保持ポリシーに基づいて期限切れになるメールに 2 つのラベルが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2071">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="5dd8e-2072">メールが 1 日で期限切れになることを示すものと、2 日で期限切れになることを示すものです。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2072">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="5dd8e-2073">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2073">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="5dd8e-2074">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2074">PowerPoint</span></span>

- <span data-ttu-id="5dd8e-2075">インクが PowerPoint のインク アニメーションで使用すると完全にレンダリングされない、またはスキップされることがある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2075">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="5dd8e-2076">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2076">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="5dd8e-2077">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2077">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="5dd8e-2078">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2078">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="5dd8e-2079">Project</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2079">Project</span></span>

- <span data-ttu-id="5dd8e-2080">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2080">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="5dd8e-2081">Word</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2081">Word</span></span>

- <span data-ttu-id="5dd8e-2082">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2082">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="5dd8e-2083">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2083">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="5dd8e-2084">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2084">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="5dd8e-2085">コメントを編集し、テキストをイタリック体にし、それを投稿すると、その後にイタリック体の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2085">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="5dd8e-2086">反転したページ色を使用する読み取りモードでコメントのヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2086">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="5dd8e-2087">ドキュメントが共同編集されている場合、ルート コメントの下書き版が保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2087">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="5dd8e-2088">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2088">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="5dd8e-2089">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2089">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="5dd8e-2090">コメント コンテキスト メニューのコメント コマンド (コメントの編集、コメントへの返信、コメントの削除、コメントの解決) が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2090">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="5dd8e-2091">Office スイート</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2091">Office Suite</span></span>

- <span data-ttu-id="5dd8e-2092">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2092">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="5dd8e-2093">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="5dd8e-2093">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)
