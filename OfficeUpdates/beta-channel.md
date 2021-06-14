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
ms.openlocfilehash: 6ca376f15c7915675ac0bbc1eeb44f4479402ebe
ms.sourcegitcommit: e04eca2da568e5b00330db8441a5a74646233bcd
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/11/2021
ms.locfileid: "52899917"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="d08ce-103">ベータ チャネルのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="d08ce-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="d08ce-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project のベータ チャネル ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="d08ce-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="d08ce-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたってベータ チャネルにロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="d08ce-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="d08ce-108">以下に示すものが表示されない場合でも、最終的には入手できますのでご安心ください。</span><span class="sxs-lookup"><span data-stu-id="d08ce-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="d08ce-109">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="d08ce-110">詳細については、[こちらの記事](/DeployOffice/update-channels-changes)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="d08ce-110">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>

> [!NOTE]
> - <span data-ttu-id="d08ce-111">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="d08ce-112">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (削除しないでください)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2107-june-11"></a><span data-ttu-id="d08ce-115">バージョン 2107: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-115">Version 2107: June 11</span></span>
<span data-ttu-id="d08ce-116">*バージョン 2107 (ビルド 14204.20006)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-116">*Version 2107 (Build 14204.20006)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-118">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-119">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-119">Excel</span></span>

- <span data-ttu-id="d08ce-120">一部のユーザーの Excel アドイン一覧に追加のエントリが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-120">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="d08ce-121">SPO ドキュメント ライブラリに保存するときに、保存したブックが最近使用したブックの一覧の上部に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-121">We fixed an issue where a saved workbook would appear at the top of the Recent list when saving to an SPO document library.</span></span>


### <a name="onenote"></a><span data-ttu-id="d08ce-122">OneNote</span><span class="sxs-lookup"><span data-stu-id="d08ce-122">OneNote</span></span>

- <span data-ttu-id="d08ce-123">段落へのリンクをコピーすると、必ずしも正しいページにリダイレクトされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-123">We fixed an issue where copying a link to a paragraph did not always redirect to the correct page.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-124">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-124">Word</span></span>

- <span data-ttu-id="d08ce-125">Microsoft Word Manuscript Paper アドインの使用時に四角形が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-125">We fixed an issue in which squares appeared when using the Microsoft Word Manuscript Paper Add-in.</span></span>


- <span data-ttu-id="d08ce-126">印刷プレビューの一部のページが空白になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-126">We fixed an issue in which some pages in print preview were blank.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。)

## <a name="version-2106-june-04"></a><span data-ttu-id="d08ce-128">バージョン 2106: 6 月 4 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-128">Version 2106: June 04</span></span>
<span data-ttu-id="d08ce-129">*バージョン 2106 (ビルド 14131.20008)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-129">*Version 2106 (Build 14131.20008)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-131">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-131">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-132">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-132">Excel</span></span>

- <span data-ttu-id="d08ce-133">**データ型の検出の設定:** Excel の Power Query を使用して、非構造化ソースからのデータのインポート中にデータ型の検出動作を構成する</span><span class="sxs-lookup"><span data-stu-id="d08ce-133">**Data type detection settings:** Configure the data type detection behavior when importing data from unstructured sources with Power Query in Excel</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-136">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-136">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="d08ce-137">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-137">PowerPoint</span></span>

- <span data-ttu-id="d08ce-138">バス バーの '保存の再試行' ボタンを使用して保存されたファイルを確認すると、最近のリストに追加されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-138">We fixed an issue that ensures a file saved using the 'Retry Save' button on the bus bar is added to the Recent List.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-139">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-139">Word</span></span>

- <span data-ttu-id="d08ce-140">特定のフォントで文字を 90 度回転させると、文字間隔が広くなるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-140">We fixed an issue where character spacing increases for specific fonts when rotating them 90 degrees.</span></span>


- <span data-ttu-id="d08ce-141">複数のユーザーと共同編集中に、コメントの返信に失敗する場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-141">We fixed an issue where comment replies were sometimes lost when coauthoring with multiple users.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-142">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-142">Office Suite</span></span>

- <span data-ttu-id="d08ce-143">以前に、SyncBacked ファイル (OneDrive で同期されるファイル) に自発的に保存されてしまう原因になった CLP 機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-143">We fixed an issue where the CLP feature previously caused unprompted saves to the SyncBacked file (File synced by OneDrive).</span></span>


- <span data-ttu-id="d08ce-144">オンプレミス サーバーに保存されたファイルをユーザーが編集できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-144">We fixed an issue where user is unable to edit files stored in OnPrem servers.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2106-may-28"></a><span data-ttu-id="d08ce-146">バージョン 2106: 5 月 28 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-146">Version 2106: May 28</span></span>
<span data-ttu-id="d08ce-147">*バージョン 2106 (ビルド 14122.20004)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-147">*Version 2106 (Build 14122.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-149">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-149">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-150">Outlook</span></span>

- <span data-ttu-id="d08ce-151">**Org Explorer:** 組織図を表示してナビゲートします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-151">**Org Explorer:** View and navigate the organization chart.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-154">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-154">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-155">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-155">Outlook</span></span>

- <span data-ttu-id="d08ce-156">"ビジネス以外" のライセンスの Outlook バージョンで、ユーザーがフォルダー間でアイテムを移動できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-156">We fixed an issue where users were unable to move items across folders in "non-business" licensed Outlook versions.</span></span>


- <span data-ttu-id="d08ce-157">このレジストリ キーは、新しい [会議室​​の検索] 機能 (Outlook for Web と同じ機能) を無効にして、従来の時間の候補を含む [会議室​​の検索] 機能を有効にします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-157">This registry key disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with suggested times.</span></span>

  <span data-ttu-id="d08ce-158">レジストリ キー:</span><span class="sxs-lookup"><span data-stu-id="d08ce-158">Registry Key:</span></span>
  
  > <span data-ttu-id="d08ce-159">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="d08ce-159">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
  > <span data-ttu-id="d08ce-160">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="d08ce-160">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
  > <span data-ttu-id="d08ce-161">0 (既定) - ユーザーが [会議室の検索] ボタンをクリックして利用可能な会議室を検索する際、Outlook は会議室の新しい検索機能 “OWA Powered eXperience” を使用します</span><span class="sxs-lookup"><span data-stu-id="d08ce-161">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
  > <span data-ttu-id="d08ce-162">1 - Outlook は従来の会議室検索ユーザーインタフェースを使用して、利用可能な会議室を検索します</span><span class="sxs-lookup"><span data-stu-id="d08ce-162">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span></br>


### <a name="project"></a><span data-ttu-id="d08ce-163">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-163">Project</span></span>

- <span data-ttu-id="d08ce-164">手動で時刻設定したタスクの割り当てが不正な日付に移動する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-164">We fixed an issue where assignments on manually scheduled tasks could be moved to an incorrect date.</span></span>


- <span data-ttu-id="d08ce-165">リソース共有元が応答せず、開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-165">We fixed an issue where the resource pool was unresponsive and couldn't be opened.</span></span>


- <span data-ttu-id="d08ce-166">特定の日付または時刻パラメーターで ProjectDate */ProjectDur* 関数を使用するカスタム フィールドの数式を作成した場合にエラーが生成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-166">We fixed an issue where an error was generated if you created a custom field formula that used the ProjectDate */ProjectDur* functions with specific date or time parameters.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-167">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-167">Word</span></span>

- <span data-ttu-id="d08ce-168">ドキュメントを PDF にエクスポートするときに一部のコメントが保存されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-168">We fixed an issue where some comments were not saved when exporting a document to PDF.</span></span>


- <span data-ttu-id="d08ce-169">制限付き編集が適用されている場合に、ドキュメントの保護されていない領域で新しいコメントを編集できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-169">We fixed an issue that prevented the editing of a new comment in an unprotected area of a document when Restricted Editing is applied.</span></span>


- <span data-ttu-id="d08ce-170">不要なスクロール アニメーションに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-170">We fixed an issue related to unneeded scrolling animation.</span></span>


- <span data-ttu-id="d08ce-171">コメント ウィンドウが予期せず閉じてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-171">We fixed an issue causing comments pane closed unexpectedly.</span></span>


- <span data-ttu-id="d08ce-172">エディター ウィンドウのテーマとシステム テーマの間で不一致が発生していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-172">We fixed an issue that was causing a mismatch between the Editor pane theme and the system theme.</span></span>


- <span data-ttu-id="d08ce-173">大きなドキュメントの操作に関連するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-173">We fixed a performance issue related to working with large documents.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2106-may-21"></a><span data-ttu-id="d08ce-175">バージョン 2106: 5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-175">Version 2106: May 21</span></span>
<span data-ttu-id="d08ce-176">*バージョン 2106 (ビルド 14117.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-176">*Version 2106 (Build 14117.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-178">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-178">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-179">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-179">Outlook</span></span>

- <span data-ttu-id="d08ce-180">**最後のサインイン/不審なサインイン:** Outlook では、アカウントに最後にサインインした場合と場所が通知され、不審なサインイン アクティビティが検出された場合は警告が表示されます</span><span class="sxs-lookup"><span data-stu-id="d08ce-180">**Last Sign In / Suspicious Sign In:** Outlook now tells you when and where you last signed into your account, and alerts you if any suspicious sign-in activity is detected</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-183">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-183">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-184">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-184">Excel</span></span>

- <span data-ttu-id="d08ce-185">RealTimeData 関数が参照している場合に Dynamic Arrays がセル値を更新しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-185">We fixed an issue that caused Dynamic Arrays to not update cell values when referenced by RealTimeData functions.</span></span>


- <span data-ttu-id="d08ce-186">大量のデータを入力すると、VLOOKUP および INDEX/MATCH のパフォーマンスに影響がでるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-186">We fixed an issue that impacted the performance of VLOOKUP and INDEX/MATCH when filling a large amount of data.</span></span>


- <span data-ttu-id="d08ce-187">ウィンドウ枠の固定の使用時に 2 本指でのスクロールする必要がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-187">We fixed an issue related to two-finger scrolling when using freeze panes.</span></span>


- <span data-ttu-id="d08ce-188">大型プリンターでの印刷時にメモリ不足になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-188">We fixed an issue related to out of memory issues when printing on large-format printers.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-189">PowerPoint</span></span>

- <span data-ttu-id="d08ce-190">読み取り専用モードの場合に、発表者のノート ウィンドウからコピーができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-190">We fixed an issue that prevented copying from the speaker notes pane while in Read Only mode.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-191">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-191">Word</span></span>

- <span data-ttu-id="d08ce-192">ユーザーが変更を破棄するように選択しても、[名前を付けて保存] のエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-192">We fixed an issue where a Save As error message was displayed even after a user chose to discard changes.</span></span>


- <span data-ttu-id="d08ce-193">最新のコメントに画像が投稿されなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-193">We fixed an issue that prevented images from being posted in modern comments.</span></span>


- <span data-ttu-id="d08ce-194">[変更履歴] ウィンドウでスクロールができて、スクロールしているようなのに、選択したコメントが一致してないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-194">We fixed an issue where the Reviewing pane could scroll or appear to scroll but didn't align with selected comment.</span></span>


- <span data-ttu-id="d08ce-195">新しく作成したコメントの外側をクリックしても、文書内の選択がクリアされないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-195">We fixed an issue that caused the selection in the document to not be cleared when clicking outside a newly created comment.</span></span>


- <span data-ttu-id="d08ce-196">選択してもコメントが強調表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-196">We fixed an issue where comments aren't highlighted when selected.</span></span>


- <span data-ttu-id="d08ce-197">編集の制限を適用していると、マクロ実行中に間違ったフィールドが更新される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-197">We fixed an issue where the wrong field is getting updated when running a macro if editing restrictions are applied.</span></span>


- <span data-ttu-id="d08ce-198">ブックマークの破損で一部の Word ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-198">We fixed an issue where some Word files don't open because of corrupt bookmarks.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-199">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-199">Office Suite</span></span>

- <span data-ttu-id="d08ce-200">別のアカウントでサインインするとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-200">We fixed an issue where signing in with a different account could result in a crash.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2106-may-14"></a><span data-ttu-id="d08ce-202">バージョン 2106: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-202">Version 2106: May 14</span></span>
<span data-ttu-id="d08ce-203">*バージョン 2106 (ビルド 14107.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-203">*Version 2106 (Build 14107.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-205">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-205">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-206">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-206">Outlook</span></span>

- <span data-ttu-id="d08ce-207">「ヘッダーのみダウンロード」モードで実行した場合に、ダウンロード後に操作可能なメッセージが常に更新されたり、ヘッダーに戻ったりする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-207">We fixed an issue that caused users to see actionable messages either constantly refreshing or reverting back to headers after download when running in Download Headers Only mode.</span></span>


- <span data-ttu-id="d08ce-208">Outlook で永久ライセンスをお持ちのユーザーに、ユーザー ピッカーを下方向ではなく上方向に拡大されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-208">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


- <span data-ttu-id="d08ce-209">カスタム ドメインのユーザーがメール メッセージにリンクを貼り付ける場合に、アクセス許可に関する警告メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-209">We fixed an issue that caused users of custom domains to see a warning message about permissions when pasting a link into an email message.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-210">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-210">Word</span></span>

- <span data-ttu-id="d08ce-211">ctrl + shift + @ のようなキーの組み合わせを押しても、期待したアクセント文字 (この場合は 'å') が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-211">We fixed an issue where pressing key combinations such as ctrl + shift + @ would not produce the expected accented character( in this case, 'å').</span></span>


- <span data-ttu-id="d08ce-212">画像圧縮に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-212">We fixed an issue related to image compression.</span></span>


- <span data-ttu-id="d08ce-213">メールの添付ファイルを Word 以外のアプリケーションにコピーする場合に、ファイル名に DBCS 文字が含まれていると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-213">We fixed an issue where copying a mail attachment to an application other than Word would fail if the filename included DBCS characters.</span></span>


- <span data-ttu-id="d08ce-214">Word でテキストの周囲に本来ないはずの枠線が表示される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-214">We fixed an issue where Word sometimes displayed a border around text that should have not been there.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-215">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-215">Office Suite</span></span>

- <span data-ttu-id="d08ce-216">実際には結合の競合がないのに、OneDrive が結合エラー メッセージを表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-216">We fixed an issue where OneDrive would display a merge error message when there was indeed no merge conflict.</span></span>


- <span data-ttu-id="d08ce-217">SVG オブジェクトを図形に変換したときの Z オーダーに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-217">We fixed an issue related to z-order of SVG objects when converted to shapes.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2106-may-07"></a><span data-ttu-id="d08ce-219">バージョン 2106: 5 月 7 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-219">Version 2106: May 07</span></span>
<span data-ttu-id="d08ce-220">*バージョン 2106 (ビルド14029.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-220">*Version 2106 (Build 14029.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-222">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-222">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-223">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-223">Excel</span></span>

- <span data-ttu-id="d08ce-224">ネーム マネージャーが大量の非表示の名前を含む書籍を開かない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-224">We fixed an issue that prevented the Name Manager from opening books with a large number of hidden names.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-225">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-225">Outlook</span></span>

- <span data-ttu-id="d08ce-226">すべての送信済みアイテムのコピーがユーザーの送信トレイ フォルダーに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-226">We fixed an issue that caused users to see copies of all of their sent items appearing in their Outbox folder.</span></span>


- <span data-ttu-id="d08ce-227">Windows の他のバージョンを含む音声読み上げを使用した場合に、Outlook が予期せず閉じる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-227">We fixed an issue that caused Outlook closed unexpectedly when using read aloud with other versions of Windows.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-228">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-228">Word</span></span>

- <span data-ttu-id="d08ce-229">Windows の他のバージョンを含む音声読み上げを使用した場合に、Word が予期せず閉じる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-229">We fixed an issue that caused Word closed unexpectedly when using read aloud with other versions of Windows.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2105-april-30"></a><span data-ttu-id="d08ce-231">バージョン 2105: 4 月 30 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-231">Version 2105: April 30</span></span>
<span data-ttu-id="d08ce-232">*バージョン 2105 (ビルド 14026.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-232">*Version 2105 (Build 14026.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-234">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-234">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-235">Outlook</span></span>

- <span data-ttu-id="d08ce-236">**大規模 DL、外部ユーザーへのメール送信時のアクセシビリティ チェックの微調整:** 大勢のユーザーや外部ユーザーに向けたメールを作成する際に、アクセシビリティ違反がないかどうかをメール ヒントを通して自動的に確認できる機能を追加しました。これらの設定は、[簡単操作] にあります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-236">**Accessibility Checker nudge when sending emails to large DL, external users:** We added the functionally to get prompted automatically, through a mailtip, of an accessibility violation while composing an email to large audiences, external users, etc. These settings live in the Ease of Access</span></span>

### <a name="visio"></a><span data-ttu-id="d08ce-237">Visio</span><span class="sxs-lookup"><span data-stu-id="d08ce-237">Visio</span></span>

- <span data-ttu-id="d08ce-238">**AWS のステンシルと図形:** 図の作成に役立つ最新の AWS の図形を備えたステンシルが利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-238">**AWS stencils and shapes:** We now have stencils with the latest AWS shapes to help you create diagrams.</span></span> [<span data-ttu-id="d08ce-239">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-239">Learn more</span></span>](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)

### <a name="word"></a><span data-ttu-id="d08ce-240">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-240">Word</span></span>

- <span data-ttu-id="d08ce-241">**ライティングの目標:** WinWord のライティングの目標</span><span class="sxs-lookup"><span data-stu-id="d08ce-241">**Writing Goals:** Writing Goals for WinWord</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-244">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-244">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-245">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-245">Excel</span></span>

- <span data-ttu-id="d08ce-246">コメント ウィンドウでコメント内を移動するときに、Excel が予期せずに終了してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-246">We fixed an issue that cause Excel to close unexpectedly when moving through comments in the Comments pane.</span></span>


- <span data-ttu-id="d08ce-247">アドインを使用するときに、一部の言語で日付の書式が正しく表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-247">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="d08ce-248">特定の状況で "形式を選んでペーストする" を書式を設定して使用すると、Excel が予期せず終了してしまう可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-248">We fixed an issue which could cause Excel to close unexpectedly when using Paste Special with formats in certain situations.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-249">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-249">Project</span></span>

- <span data-ttu-id="d08ce-250">計画ウィザードで行った変更が、変更イベントにキャプチャされない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-250">We fixed an issue where changes done through Planning Wizards weren't always captured by change events.</span></span>


- <span data-ttu-id="d08ce-251">ユーザーがリソースの共有元からプロジェクトを削除できなくなってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-251">We fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-252">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-252">Word</span></span>

- <span data-ttu-id="d08ce-253">ハイパーリンクを削除してもテキストの書式が残ってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-253">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


- <span data-ttu-id="d08ce-254">ユーザーでフィルター処理を行った後にコメントが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-254">We fixed an issue where comments are not displayed after filtering by people.</span></span>


- <span data-ttu-id="d08ce-255">Word が Access データベースとの間で差し込み印刷を実行できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-255">We fixed an issue where Word was unable to perform a Mail Merge with an Access database.</span></span>


- <span data-ttu-id="d08ce-256">複数の列を含むドキュメントの余白を折り畳む機能が利用可能になってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-256">We fixed an issue that caused the ability to collapse margins in a document containing multiple columns to be available.</span></span>


- <span data-ttu-id="d08ce-257">ドキュメント内にコメントがある場合に、表のセルに一部の文字が正しく表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-257">We fixed an issue where some characters are not displayed correctly in table cells when there are comments in the document.</span></span>


- <span data-ttu-id="d08ce-258">AIP アドインを有効にしてドキュメントを保存すると、ファイル形式の変更が発生してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-258">We fixed an issue where the file format changes occurred when saving documents with the AIP add-in enabled.</span></span>


- <span data-ttu-id="d08ce-259">フィールドの編集時に Word が応答しなくなってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-259">We fixed an issue where Word would become unresponsive when editing fields.</span></span>


- <span data-ttu-id="d08ce-260">(Ctrl キー + S キーのキーボード ショートカットではなく) コマンドを使用する場合に、ドキュメントの保存を促すメッセージが表示されない可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-260">We fixed an issue where users would not be prompted to save documents when using a command (rather than the CTRL+S keyboard shortcut).</span></span>


- <span data-ttu-id="d08ce-261">SharePoint Online にファイルをアップロードした後に、Word のファイルから秘密度ラベルが消えてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-261">We fixed an issue where the sensitivity label disappears from a file in Word after uploading the file to SharePoint Online.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-262">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-262">Office Suite</span></span>

- <span data-ttu-id="d08ce-263">ドキュメントにコメントを追加する際に、[ディクテーション] ボタンの位置がずれてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-263">We fixed an issue that caused the Dictation button to be misaligned when adding comments to a document.</span></span>


- <span data-ttu-id="d08ce-264">ハイ コントラスト モードを長時間使用すると、Outlook が予期せずに終了してしまう可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-264">We fixed an issue where using High Contrast mode for extended periods of time would cause Outlook to close unexpectedly.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2105-april-23"></a><span data-ttu-id="d08ce-266">バージョン 2105: 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-266">Version 2105: April 23</span></span>
<span data-ttu-id="d08ce-267">*バージョン 2105 (ビルド 14014.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-267">*Version 2105 (Build 14014.20002)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-269">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-269">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-270">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-270">Excel</span></span>

- <span data-ttu-id="d08ce-271">**動的配列からのデータのインポート:** 現在のブックの動的配列からデータをインポート、整形、更新できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-271">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="d08ce-272">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-272">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-275">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-275">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-276">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-276">Excel</span></span>

- <span data-ttu-id="d08ce-p105">古いバージョンの Excel との下位互換性をサポートするための問題を修正しました。この問題により、Office 2007 以降の Excel に追加された IFERROR や XLOOKUP などの関数を原因として、最近のバージョンの Excel で保存されたファイルが古いバージョンの Excel で正しく読み込まれない場合があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p105">We fixed an issue to support backward compatibility with older versions of Excel. The issue may cause a file that is saved in a more recent version of Excel fail to load properly in older versions of Excel due to  functions such as IFERROR and XLOOKUP added to Excel since Office 2007.</span></span>


- <span data-ttu-id="d08ce-279">一部のファイルが保護されたビューで開かない可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-279">We fixed an issue where some files would occasionally fail to open in Protected View.</span></span>


- <span data-ttu-id="d08ce-280">一部のユーザーに対して、ステータス バーが準備完了状態を表示しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-280">We fixed an issue that caused the status bar to not indicate a Ready state for some users.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-281">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-281">Outlook</span></span>

- <span data-ttu-id="d08ce-282">別のユーザーに代わって送信し、グローバル アドレス一覧ではないアドレス ブックに対して解決すると、名前解決が失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-282">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-283">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-283">Word</span></span>

- <span data-ttu-id="d08ce-284">右から左に記述される言語を使用している場合に、コメントでプレースホルダー テキストがクリップされてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-284">We fixed a issue where placeholder text was clipped in comments when using right-to-left languages.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-285">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-285">Office Suite</span></span>

- <span data-ttu-id="d08ce-286">Outlook で右から左に記述される言語でメッセージを作成するときに、数字を含んでいるハイパーリンクが壊れてしまう可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-286">We fixed an issue where hyperlinks including digits would be broken when composing a message in Outlook in a right-to-left language.</span></span>


- <span data-ttu-id="d08ce-287">一部のスケーラベル ベクター グラフィックス (SVG) が正しくレンダリングされないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-287">We fixed an issue where some Scalable Vector Graphics (SVG) did not render correctly.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2105-april-16"></a><span data-ttu-id="d08ce-289">バージョン 2105: 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-289">Version 2105: April 16</span></span>
<span data-ttu-id="d08ce-290">*バージョン 2105 (ビルド 14007.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-290">*Version 2105 (Build 14007.20002)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-292">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-292">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-293">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-293">Excel</span></span>

- <span data-ttu-id="d08ce-294">64 ビット Windows で 32 ビットの Office を使用すると、Excel がクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-294">We fixed an issue that caused Excel to crash when using 32 bit Office on 64 bit Windows.</span></span>


- <span data-ttu-id="d08ce-295">[ページ設定] ダイアログ ボックスの [ヘッダー/フッター] タブの 2 つのボタンのプロパティが、ナレーターによって誤って読み上げられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-295">We fixed an issue that caused Narrator to incorrectly read the properties of two buttons on the Header/Footer tab in the Page Setup dialog box.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-296">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-296">PowerPoint</span></span>

- <span data-ttu-id="d08ce-297">リンクされた図に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-297">We fixed an issue related to linked pictures.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2105-april-09"></a><span data-ttu-id="d08ce-299">バージョン 2105: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-299">Version 2105: April 09</span></span>
<span data-ttu-id="d08ce-300">*バージョン 2105 (ビルド 14002.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-300">*Version 2105 (Build 14002.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-302">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-302">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-303">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-303">Excel</span></span>

- <span data-ttu-id="d08ce-304">**アクセシビリティ リボン:** アクセスできるコンテンツを作成する必要があるすべてのツールを 1 箇所で検出できるのが、アクセシビリティ リボンです。</span><span class="sxs-lookup"><span data-stu-id="d08ce-304">**Accessibility ribbon:** Find all of the tools you need to create accessible content in one place - the Accessibility ribbon!</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-305">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-305">Word</span></span>

- <span data-ttu-id="d08ce-306">**ドキュメント内で選択されたテキストに校正が使用可能:** これらの変更を使用して、選択したテキストに関するスペル、文法、その他のインテリジェントな記述の提案を確認できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-306">**Proofing is now available for selected text within the Document:** With these changes you can now review spelling, grammar and other intelligent writing suggestions for just the selected text.</span></span> <span data-ttu-id="d08ce-307">オプションで、ドキュメント全体の提案を確認することもできます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-307">Additionally you can also review suggestions for the whole document.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2104-april-02"></a><span data-ttu-id="d08ce-309">バージョン 2104: 4 月 2 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-309">Version 2104: April 02</span></span>
<span data-ttu-id="d08ce-310">*バージョン 2104 (ビルド 13929.20016)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-310">*Version 2104 (Build 13929.20016)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-312">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-312">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-313">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-313">Outlook</span></span>

- <span data-ttu-id="d08ce-314">**Outlook for Windows での自動応答の候補:** 短い返信メッセージで返信できるメール メッセージを受信した場合、Outlook は 3 つの返信を提案し、ユーザーはその中から選ぶだけでわずか数クリックで返信できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-314">**Suggested Replies in Outlook for Windows:** When you receive an email message that can be answered by a short response, Outlook can suggest three responses you can use to reply with just a couple of clicks.</span></span>

- <span data-ttu-id="d08ce-315">**共有カレンダーの更新を有効にする**: Office 365 の共有カレンダーの場合、Outlook では REST API を使用してこれらのカレンダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-315">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="d08ce-316">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-316">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-319">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-319">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-320">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-320">Access</span></span>

- <span data-ttu-id="d08ce-321">外部アプリケーションがアクセシビリティ インターフェイスを要求した場合、そのインターフェイスが参照を解放するまでシャットダウンできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-321">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-322">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-322">Word</span></span>

- <span data-ttu-id="d08ce-p108">このバグでは、特定のポリシーは Office によって適用されません (テンプレートのグループが無効になっているはずのホーム ページに表示されています)。この修正により、ポリシーが適用されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p108">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled). With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="d08ce-325">自動保存の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-325">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="d08ce-326">Application.OnTime で修正を行いましたが、正しくトリガーされない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-326">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2104-march-26"></a><span data-ttu-id="d08ce-328">バージョン 2104: 3 月 26 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-328">Version 2104: March 26</span></span>
<span data-ttu-id="d08ce-329">*バージョン 2104 (ビルド 13919.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-329">*Version 2104 (Build 13919.20002)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-331">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-331">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-332">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-332">Outlook</span></span>

- <span data-ttu-id="d08ce-333">フォルダー階層の変更を同期するときに、Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-333">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-334">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-334">Word</span></span>

- <span data-ttu-id="d08ce-335">貼り付けたテキストで、コピーと貼り付けのスタイルが同じにならない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-335">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-336">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-336">Office Suite</span></span>

- <span data-ttu-id="d08ce-337">テキストの反復に関連するパフォーマンスの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-337">Fixed a performance issue related to iteration of text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2104-march-19"></a><span data-ttu-id="d08ce-339">バージョン 2104: 3 月 19 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-339">Version 2104: March 19</span></span>
<span data-ttu-id="d08ce-340">*バージョン 2104 (ビルド 13913.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-340">*Version 2104 (Build 13913.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-342">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-342">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-343">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-343">Access</span></span>

- <span data-ttu-id="d08ce-344">SQL Server パススルー クエリを実行すると、"無効なカーソル状態" があったことを示すエラー メッセージが表示されることがある問題がこの変更により修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-344">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="d08ce-345">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-345">Excel</span></span>

- <span data-ttu-id="d08ce-346">保護されたシートに数式として貼り付けることができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-346">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-347">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-347">Project</span></span>

- <span data-ttu-id="d08ce-348">日付の形式が W4/4 の場合、日付の選択に間違った日と年が表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-348">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-349">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-349">Office Suite</span></span>

- <span data-ttu-id="d08ce-350">Office での GDI + LineJoinMiterClipped のサポートに関する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-350">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2104-march-12"></a><span data-ttu-id="d08ce-352">バージョン 2104: 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-352">Version 2104: March 12</span></span>
<span data-ttu-id="d08ce-353">*バージョン 2104 (ビルド 13906.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-353">*Version 2104 (Build 13906.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-355">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-355">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="d08ce-356">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-356">PowerPoint</span></span>

- <span data-ttu-id="d08ce-357">**PowerPoint に Flipgrid ビデオを挿入する:** PowerPoint は、スライドへの Flipgrid ビデオの挿入をサポートするようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-357">**Insert Flipgrid videos in PowerPoint:** PowerPoint will now support insertion of Flipgrid videos in slides.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-360">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-360">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-361">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-361">Excel</span></span>

- <span data-ttu-id="d08ce-362">ファイルを PDF ドキュメントとして保存すると、HYPERLINK 関数を使用して作成したハイパーリンクが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-362">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-363">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-363">Word</span></span>

- <span data-ttu-id="d08ce-364">共同編集中のコメントの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-364">We fixed an issue with comments during coauthoring.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-march-05"></a><span data-ttu-id="d08ce-366">バージョン 2103: 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-366">Version 2103: March 05</span></span>
<span data-ttu-id="d08ce-367">*バージョン 2103 (ビルド 13901.20036)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-367">*Version 2103 (Build 13901.20036)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-369">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-369">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-370">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-370">Excel</span></span>

- <span data-ttu-id="d08ce-371">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="d08ce-371">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="d08ce-372">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-372">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="d08ce-373">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="d08ce-373">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-374">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-374">PowerPoint</span></span>

- <span data-ttu-id="d08ce-375">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="d08ce-375">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="d08ce-376">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-376">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="d08ce-377">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="d08ce-377">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-378">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-378">Word</span></span>

- <span data-ttu-id="d08ce-379">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="d08ce-379">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="d08ce-380">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-380">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="d08ce-381">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="d08ce-381">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-384">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-384">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-385">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-385">Excel</span></span>

- <span data-ttu-id="d08ce-386">日本語フォントで乗算または除算記号を使用すると、フォントが予期せず変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-386">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="d08ce-387">文字をサポートしている場合は、引き続き同じフォントを使用します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-387">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="d08ce-388">.xls または .xlt 形式で保存するときに、一部のピボットテーブル形式でブックが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-388">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="d08ce-389">ブックを開いたときに予期せずメモが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-389">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-390">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-390">Outlook</span></span>

- <span data-ttu-id="d08ce-391">CSV にエクスポートするときに非 ASCII 文字が正しくエクスポートされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-391">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="d08ce-392">メールを作成するときに、ユーザーが [名前の確認] で連絡先グループを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-392">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-393">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-393">PowerPoint</span></span>

- <span data-ttu-id="d08ce-394">PowerPoint スライドショー モードで折れ線グラフの矢印が期待どおりに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-394">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-395">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-395">Word</span></span>

- <span data-ttu-id="d08ce-396">Microsoft Information Protection (MIP) ラベルで保護されたファイルを開くとき、MIP で保護されたラベルにアクセスできる ID にユーザーがサインインしていない場合、無期限にハングする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-396">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="d08ce-397">ユーザーは、サインイン プロンプトを表示するためにオープンをキャンセルする必要があり、オープンはその時点以降にのみ成功します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-397">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="d08ce-398">開く/ダウンロード中にサインイン プロンプトを表示できるようにすることで、この問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-398">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="d08ce-399">新しい単語コメントでディクテーションを使用する際の問題を修正しました。コメント カードのディクテーション ボタンが正しくオンとオフを切り替えるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-399">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="d08ce-400">ユーザーがドキュメントにディクテーションしたときに単語の間にスペースが挿入されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-400">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="d08ce-401">RTL で入力された複数行のコメントを投稿すると、2 行目以降が右ではなく左に配置される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-401">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="d08ce-402">スペル チェックが 2 つの異なるスペル修正コンテキスト メニュー間で切り替わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-402">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="d08ce-403">列のテキストが重複する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-403">We fixed an issue where columns might have overlapping text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-february-26"></a><span data-ttu-id="d08ce-405">バージョン 2103: 2 月 26 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-405">Version 2103: February 26</span></span>
<span data-ttu-id="d08ce-406">*バージョン 2103 (ビルド 13819.20006)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-406">*Version 2103 (Build 13819.20006)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-408">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-408">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-409">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-409">Excel</span></span>

- <span data-ttu-id="d08ce-410">ユーザーが Excel ブックを PDF にエクスポートできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-410">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="d08ce-411">共同編集中にシートをコピーした際、一部の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-411">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-412">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-412">Outlook</span></span>

- <span data-ttu-id="d08ce-413">DRM 保護を削除すると、添付ファイルが重複して表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-413">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-414">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="d08ce-414">Project</span></span>

- <span data-ttu-id="d08ce-415">Project Web App からローカル ファイルにプロジェクトを保存するときに、タスクの分割が誤って作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-415">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="d08ce-416">これは、非標準の作業時間のタスク カレンダーが使用されていた場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-416">This would happen if a task calendar with non-standard working times was being used.</span></span>


- <span data-ttu-id="d08ce-417">インジケーター列が最初の列スポットにない場合、「サマリー タスクを切り取ると、サブタスクも削除されます」という警告が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-417">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="d08ce-418">ユーザーがタイムシートで [タスクに自分自身を追加] 機能を選択した場合に、作成された割り当てで適切なリソース利用可能時間の単位が使用されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-418">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-419">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-419">Word</span></span>

- <span data-ttu-id="d08ce-420">複数のコメントの配置に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-420">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="d08ce-421">[音声読み上げ] 作業ウィンドウの、キーボード ショートカットの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-421">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-422">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-422">Office Suite</span></span>

- <span data-ttu-id="d08ce-423">OneDrive の場所は、グループ ポリシー設定に応じて適切にフィルター処理されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-423">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="d08ce-424">EMF 画像の読み込み時に発生する可能性がある無応答に関連した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-424">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-february-19"></a><span data-ttu-id="d08ce-426">バージョン 2103: 2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-426">Version 2103: February 19</span></span>
<span data-ttu-id="d08ce-427">*バージョン 2103 (ビルド 13811.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-427">*Version 2103 (Build 13811.20002)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-429">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-429">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-430">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-430">Outlook</span></span>

- <span data-ttu-id="d08ce-431">DRM 保護を削除すると、添付ファイルが重複して表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-431">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-432">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="d08ce-432">Project</span></span>

- <span data-ttu-id="d08ce-433">インジケーター列が最初の列スポットにない場合、「サマリー タスクを切り取ると、サブタスクも削除されます」という警告が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-433">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="d08ce-434">ユーザーがタイムシートで [タスクに自分自身を追加] 機能を選択した場合に、作成された割り当てで適切なリソース利用可能時間の単位が使用されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-434">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-435">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-435">Word</span></span>

- <span data-ttu-id="d08ce-436">[音声読み上げ] 作業ウィンドウの、キーボード ショートカットの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-436">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-february-12"></a><span data-ttu-id="d08ce-438">バージョン 2103: 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-438">Version 2103: February 12</span></span>
<span data-ttu-id="d08ce-439">*バージョン 2103 (ビルド 13806.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-439">*Version 2103 (Build 13806.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-441">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-441">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-442">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-442">Outlook</span></span>

- <span data-ttu-id="d08ce-443">**Microsoft Search を利用した作成 (To\CC\BCC) の提案:** To\CC 行へのユーザーの追加は、Microsoft Search を利用するようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-443">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>

- <span data-ttu-id="d08ce-444">**ディクテーションはより多くの言語で利用できます:** ディクテーションは 7 つの新しい言語をサポートするようになりました: ヒンディー語、ロシア語、ポーランド語、ポルトガル語 (ポルトガル)、韓国語、タイ語、中国語 (台湾)</span><span class="sxs-lookup"><span data-stu-id="d08ce-444">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-445">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-445">Word</span></span>

- <span data-ttu-id="d08ce-446">**ディクテーションはより多くの言語で利用できます:** ディクテーションは 7 つの新しい言語をサポートするようになりました: ヒンディー語、ロシア語、ポーランド語、ポルトガル語 (ポルトガル)、韓国語、タイ語、中国語 (台湾)</span><span class="sxs-lookup"><span data-stu-id="d08ce-446">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-449">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-449">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-450">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-450">Excel</span></span>

- <span data-ttu-id="d08ce-451">画像を取得できないためにデータ型カードを表示しようとすると、Excel が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-451">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-452">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-452">PowerPoint</span></span>

- <span data-ttu-id="d08ce-453">アニメーションおよびオーディオ ブックマークのループの問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-453">Fixes an issue with looping animations and audio bookmarks.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-454">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-454">Project</span></span>

- <span data-ttu-id="d08ce-455">100% 完了したタスクが 99% 完了に戻る問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-455">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>

- <span data-ttu-id="d08ce-456">JAWS を実行しているときにタスク情報ダイアログに移動すると、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-456">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-457">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-457">Word</span></span>

- <span data-ttu-id="d08ce-458">自動保存の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-458">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="d08ce-459">共同編集中の競合を解決する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-459">We fixed an issue in resolving conflicts while in coauthoring.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-february-05"></a><span data-ttu-id="d08ce-461">バージョン 2102: 2 月 5 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-461">Version 2102: February 05</span></span>
<span data-ttu-id="d08ce-462">*バージョン 2102 (ビルド 13801.20004)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-462">*Version 2102 (Build 13801.20004)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-464">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-464">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-465">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-465">Access</span></span>

- <span data-ttu-id="d08ce-466">Access で選択したタブがよりはっきりと表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-466">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="d08ce-467">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-467">Excel</span></span>

- <span data-ttu-id="d08ce-468">グラフでデータ系列を選択した後に Excel が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-468">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="d08ce-469">Android で特定のキーボードを使用して Enter キーを押すと、次のセルに移動するのではなく、新しい行が追加される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-469">We fixed an issue where pressing Enter with certain keyboards on Android would add a new line rather than moving to the next cell.</span></span>


- <span data-ttu-id="d08ce-470">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-470">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-471">Outlook</span></span>

- <span data-ttu-id="d08ce-472">デジタル署名のオプションのチェックを外した後も、メールがデジタル署名されたものとして送信される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-472">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-473">PowerPoint</span></span>

- <span data-ttu-id="d08ce-474">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-474">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-475">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-475">Word</span></span>

- <span data-ttu-id="d08ce-476">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-476">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="d08ce-477">コメントがリンクで切り捨てられる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-477">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="d08ce-478">共同編集時に競合モードになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-478">We fixed an issue with conflict mode when coauthoring.</span></span>


- <span data-ttu-id="d08ce-479">SharePoint Online に保存する際に発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="d08ce-479">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="d08ce-480">Word 文書を PDF にエクスポートする際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-480">We fixed an issue in exporting Word document to PDF.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-481">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-481">Office Suite</span></span>

- <span data-ttu-id="d08ce-482">あるサインイン アカウントの機密ラベルを表示する必要があるときに、特定の状況で Office が別のサインイン アカウントの機密ラベルを表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-482">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-january-29"></a><span data-ttu-id="d08ce-484">バージョン 2102: 1 月 29 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-484">Version 2102: January 29</span></span>
<span data-ttu-id="d08ce-485">*バージョン 2102 (ビルド 13721.20008)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-485">*Version 2102 (Build 13721.20008)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-487">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-487">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-488">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-488">Excel</span></span>

- <span data-ttu-id="d08ce-489">[名前の定義] ダイアログで名前を追加したときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-489">We fixed a problem where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-490">Outlook</span></span>

- <span data-ttu-id="d08ce-491">[暗号化のみ] オプションを使用して送信された電子メールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-491">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-492">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-492">Project</span></span>

- <span data-ttu-id="d08ce-493">キリル文字の長い名前のプロジェクトをプロジェクト センターから開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-493">Fixed an issue where projects with long Cyrillic names could not be opened through Project Center.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-january-22"></a><span data-ttu-id="d08ce-495">バージョン 2102: 1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-495">Version 2102: January 22</span></span>
<span data-ttu-id="d08ce-496">*バージョン 2102 (ビルド 13714.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-496">*Version 2102 (Build 13714.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-498">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-498">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-499">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-499">Excel</span></span>

- <span data-ttu-id="d08ce-500">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-500">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="d08ce-501">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-501">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="d08ce-502">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-502">Outlook</span></span>

- <span data-ttu-id="d08ce-503">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-503">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="d08ce-504">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-504">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="d08ce-505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-505">PowerPoint</span></span>

- <span data-ttu-id="d08ce-506">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-506">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="d08ce-507">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-507">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a><span data-ttu-id="d08ce-508">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-508">Word</span></span>

- <span data-ttu-id="d08ce-509">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-509">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="d08ce-510">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-510">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-513">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-513">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-514">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-514">Excel</span></span>

- <span data-ttu-id="d08ce-515">ファイルを再度開いたときに、セルの連続していない範囲を使用する特定のグラフが読み込まれない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-515">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="d08ce-516">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せずクラッシュしたりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-516">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-517">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-517">PowerPoint</span></span>

- <span data-ttu-id="d08ce-518">色付きの絵文字を表示すると発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-518">Fixed an issue related to displaying emojis with color.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-519">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-519">Word</span></span>


- <span data-ttu-id="d08ce-520">これにより、インターネット接続が一定期間失われた後、リアルタイムの入力とプレゼンスが復元されない問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-520">This fixes an issue that prevented real-time typing and presence from being restored after loosing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="d08ce-521">共同編集の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-521">We fixed an issue with coauthoring.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-january-15"></a><span data-ttu-id="d08ce-523">バージョン 2102: 1 月 15 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-523">Version 2102: January 15</span></span>
<span data-ttu-id="d08ce-524">*バージョン 2102 (ビルド 13707.20008)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-524">*Version 2102 (Build 13707.20008)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-526">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-526">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-527">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-527">Outlook</span></span>

- <span data-ttu-id="d08ce-528">**Teamsと共有:** Outlook からのメールや会話を Teams のユーザーまたはチャネルと共有します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-528">**Share to Teams:** Share an email or a conversation from Outlook to a person or channel in Teams.</span></span>

### <a name="visio"></a><span data-ttu-id="d08ce-529">Visio</span><span class="sxs-lookup"><span data-stu-id="d08ce-529">Visio</span></span>

- <span data-ttu-id="d08ce-530">**図に適した既製のグラフィック:** アイコン、株の写真画像、ユーザーの切り抜き、ステッカーの大きなライブラリから選び、Visio 図面に追加できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-530">**Ready-made graphics for your diagrams:** Choose from a large library of icons, stock photo images, cutout people, and stickers that you can add to your Visio drawings.</span></span> [<span data-ttu-id="d08ce-531">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-531">Learn more</span></span>](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-534">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-534">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="d08ce-535">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-535">Project</span></span>

- <span data-ttu-id="d08ce-536">コスト型リソースがマイルストーン タスクに割り当てられたとき、基準コストが正しくロールアップされないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-536">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-537">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-537">Word</span></span>

- <span data-ttu-id="d08ce-538">VBA マクロ実行中に ExportAsFixedFormat2 が、"プレゼンテーション (不明のメンバー) の不正な値" というエラーが表示され失敗する問題を修正しています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-538">Fixing a failure when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-january-08"></a><span data-ttu-id="d08ce-540">バージョン 2102: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-540">Version 2102: January 08</span></span>
<span data-ttu-id="d08ce-541">*バージョン 2102 (ビルド 13704.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-541">*Version 2102 (Build 13704.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-543">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-543">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-544">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-544">Outlook</span></span>

- <span data-ttu-id="d08ce-545">**ディクテーションが改善されました:** 新しい [ディクテーション] ツールバー、[音声コマンド]、および [自動句読点のサポート] を使用して、音声でのコンテンツ作成がさらに簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-545">**Dictation just got better:** It's now easier to create content with your voice with the new dictation toolbar, voice commands, and auto-punctuation support</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-546">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-546">Word</span></span>

- <span data-ttu-id="d08ce-547">**ディクテーションが改善されました:** 新しい [ディクテーション] ツールバー、[音声コマンド]、および [自動句読点のサポート] を使用して、音声でのコンテンツ作成がさらに簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-547">**Dictation just got better:** It's now easier to create content with your voice with the new dictation toolbar, voice commands, and auto-punctuation support</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-550">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-550">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-551">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-551">Excel</span></span>

- <span data-ttu-id="d08ce-552">PowerPoint での埋め込まれた Excel の範囲のプレビューでサイズが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-552">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-01"></a><span data-ttu-id="d08ce-554">バージョン 2101: 1 月 1 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-554">Version 2101: January 01</span></span>
<span data-ttu-id="d08ce-555">*バージョン 2101 (ビルド 13624.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-555">*Version 2101 (Build 13624.20002)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-557">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-557">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-558">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-558">Excel</span></span>

- <span data-ttu-id="d08ce-559">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-559">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-560">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-560">PowerPoint</span></span>

- <span data-ttu-id="d08ce-561">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-561">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-562">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-562">Word</span></span>

- <span data-ttu-id="d08ce-563">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-563">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-566">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-566">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="d08ce-567">OneNote</span><span class="sxs-lookup"><span data-stu-id="d08ce-567">OneNote</span></span>

- <span data-ttu-id="d08ce-568">この変更により、OneNote に影響を与えるレンダリングの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-568">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-569">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-569">Outlook</span></span>

- <span data-ttu-id="d08ce-570">この変更により、エンド ユーザーに対して Exchange Online アーカイブ メールボックスを表示しないようにする Exchange サーバーの設定を Outlook で利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-570">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-571">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-571">PowerPoint</span></span>

- <span data-ttu-id="d08ce-572">この変更により、図形の結合がテキストを操作するときに発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-572">This change addresses an issue with Merge Shapes working with text.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-573">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-573">Word</span></span>

- <span data-ttu-id="d08ce-574">最新コメントをより堅牢なものにするための修正を行いました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-574">Fix to make Modern comments more robust.</span></span>


- <span data-ttu-id="d08ce-575">@Mention を含むコメント投稿を編集するときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-575">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="d08ce-576">新しい Word インスタンスを作成すると、コメントの下書きが消えます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-576">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="d08ce-577">修正と、コメント ウィンドウ内のネストされたスクロール バーに関する問題。</span><span class="sxs-lookup"><span data-stu-id="d08ce-577">Fix and issue with nested scrollbars in the comments pane.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-december-25"></a><span data-ttu-id="d08ce-579">バージョン 2101: 12 月 25 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-579">Version 2101: December 25</span></span>
<span data-ttu-id="d08ce-580">*バージョン 2101 (ビルド 13617.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-580">*Version 2101 (Build 13617.20002)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-582">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-582">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-583">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-583">Excel</span></span>

- <span data-ttu-id="d08ce-584">Excel からグラフをコピーして Word に貼り付けるときに、10 進数と桁区切りの記号の設定を継承するように更新しました</span><span class="sxs-lookup"><span data-stu-id="d08ce-584">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="d08ce-585">無効なファイル属性 (作成時刻、修正時刻など) を持つ UNC ファイルを開くと、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-585">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="d08ce-586">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-586">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-587">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-587">Outlook</span></span>

- <span data-ttu-id="d08ce-588">Word から差し込み印刷を開始するときに、ユーザーがアクセスを許可する時間の長さを指定できず、ユーザーに対して余分なプロンプトが表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-588">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="d08ce-589">引き換えベースのアドインのユーザーの Outlook が予期せず終了してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-589">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-590">PowerPoint</span></span>

- <span data-ttu-id="d08ce-591">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-591">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-592">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-592">Word</span></span>

- <span data-ttu-id="d08ce-593">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-593">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="d08ce-594">コメント カードの返信ボックスが画面に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-594">Fixes an issue where the reply box on a comment card is off the screen.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-december-18"></a><span data-ttu-id="d08ce-596">バージョン 2101: 12 月 18 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-596">Version 2101: December 18</span></span>
<span data-ttu-id="d08ce-597">*バージョン 2101 (ビルド 13610.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-597">*Version 2101 (Build 13610.20002)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-599">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-599">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-600">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-600">Excel</span></span>

- <span data-ttu-id="d08ce-601">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-601">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="d08ce-602">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="d08ce-602">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-603">Outlook</span></span>

- <span data-ttu-id="d08ce-604">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-604">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="d08ce-605">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="d08ce-605">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-606">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-606">PowerPoint</span></span>

- <span data-ttu-id="d08ce-607">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-607">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="d08ce-608">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="d08ce-608">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-609">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-609">Word</span></span>

- <span data-ttu-id="d08ce-610">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-610">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="d08ce-611">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="d08ce-611">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-614">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-614">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-615">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-615">Excel</span></span>

- <span data-ttu-id="d08ce-616">ピボット テーブルに書式設定スタイルを適用するときのパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-616">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-617">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-617">Outlook</span></span>

- <span data-ttu-id="d08ce-618">ユーザーが検索対象のカテゴリを複数選ぶことができなかった原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-618">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="d08ce-619">イベントが別の予定からコピーされたときに、一部の予定表アイテムの開始時刻が予期せず変更される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-619">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-620">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-620">Project</span></span>

- <span data-ttu-id="d08ce-621">更新された情報が保存されているはずのプロジェクトをユーザーが開いた際に、更新された情報が見つからないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-621">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-622">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-622">Word</span></span>

- <span data-ttu-id="d08ce-623">コメント カードの下部に入力するときのアニメーションを修正します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-623">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="d08ce-624">文書を隠し文字で PDF に保存する際に、Word が固まる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-624">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-december-11"></a><span data-ttu-id="d08ce-626">バージョン 2101: 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-626">Version 2101: December 11</span></span>
<span data-ttu-id="d08ce-627">*バージョン 2101 (ビルド 13604.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-627">*Version 2101 (Build 13604.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-629">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-629">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-630">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-630">Outlook</span></span>

- <span data-ttu-id="d08ce-631">**クラウドでの Outlook の設定** [自動応答]、[優先受信トレイ]、[プライバシー] などの Outlook for Windows の設定を選択し、任意の PC でアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-631">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-632">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-632">Word</span></span>

- <span data-ttu-id="d08ce-633">**最新のコメントによる共同作業の向上:** オブジェクトにコメントを追加したり、同僚に @mention したり、コメント スレッドを解決して共同作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-633">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="d08ce-634">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-634">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br /><span data-ttu-id="d08ce-635">[ブログの投稿](https://insider.office.com/ja-JP/blog/modern-commenting-in-word)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-635">See details in [blog post](https://insider.office.com/ja-JP/blog/modern-commenting-in-word)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-638">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-638">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-639">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-639">Excel</span></span>

- <span data-ttu-id="d08ce-640">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-640">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="d08ce-641">Selection.Parent.Copy コールの後に区切り文字の切り替えに関連する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-641">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-642">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-642">Outlook</span></span>

- <span data-ttu-id="d08ce-643">送信時にプレーン テキストの S/MIME メッセージが正しく表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-643">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-644">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-644">PowerPoint</span></span>

- <span data-ttu-id="d08ce-645">この変更により、スライドショーでバックグラウンドビデオ再生がループする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-645">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="d08ce-646">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-646">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-647">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-647">Word</span></span>

- <span data-ttu-id="d08ce-648">編集不可とマークされているコンテンツ コントロールでの最新のコメントの削除に関する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-648">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>



[//]: # ( BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-04"></a><span data-ttu-id="d08ce-650">バージョン 2012: 12 月 4 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-650">Version 2012: December 04</span></span>
<span data-ttu-id="d08ce-651">*バージョン 2012 (ビルド 13530.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-651">*Version 2012 (Build 13530.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-653">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-653">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-654">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-654">Outlook</span></span>

- <span data-ttu-id="d08ce-655">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分遅く会議を開始するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-655">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="d08ce-656">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-656">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a><span data-ttu-id="d08ce-657">Visio</span><span class="sxs-lookup"><span data-stu-id="d08ce-657">Visio</span></span>

- <span data-ttu-id="d08ce-658">**新しい Azure ステンシルと図形:** 最新の Azure 図を作成するために、多くのステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-658">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="d08ce-659">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-659">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-662">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-662">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-663">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-663">Excel</span></span>

- <span data-ttu-id="d08ce-664">上書きモードでの編集時に、IME を使用する必要がある言語での編集がうまくいかない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-664">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="d08ce-665">自動保存が無効になっている場合に、通知のヘルプ記事へのハイパーリンクが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-665">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="d08ce-666">数式ビューでデータをコピーして貼り付けると、Excel が予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-666">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-667">Outlook</span></span>

- <span data-ttu-id="d08ce-668">下書きに保存したときに SmartLinks の書式設定が失われるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-668">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-669">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-669">Project</span></span>

- <span data-ttu-id="d08ce-670">沢山のリソースが付いたプロジェクトを開くのに、長い時間かかっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-670">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="d08ce-671">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-671">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-672">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-672">Word</span></span>

- <span data-ttu-id="d08ce-673">リッチ テキストとして貼り付けるより、通常のテキストとして貼り付けることが推奨されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-673">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="d08ce-674">このコンテキスト メニューの修正プログラムでは、テキストとして貼り付けることができます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-674">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="d08ce-675">それ以外の場合、ユーザーはメモ帳などのプレーンテキスト エディターにコピーして、メモ帳から目的のターゲット アプリにコピーする必要があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-675">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-november-27"></a><span data-ttu-id="d08ce-677">バージョン 2012: 11 月 27 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-677">Version 2012: November 27</span></span>
<span data-ttu-id="d08ce-678">*バージョン 2012 (ビルド 13519.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-678">*Version 2012 (Build 13519.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-680">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-680">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-681">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-681">Excel</span></span>

- <span data-ttu-id="d08ce-682">これにより、Power Pivot がタブ区切りのテキストファイルを正しくインポートできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-682">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-683">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-683">Outlook</span></span>

- <span data-ttu-id="d08ce-684">Outlook 以外のアプリケーションから Outlook メールを送信するときに、ユーザーに問題が発生しているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-684">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-685">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-685">PowerPoint</span></span>

- <span data-ttu-id="d08ce-686">この変更により、インク分析中のタイムアウトに関連する問題が解決します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-686">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="d08ce-687">この変更は、アニメーション GIF ユーザー インターフェイスの作成に関する文法エラーに対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-687">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="d08ce-688">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-688">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-689">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-689">Project</span></span>

- <span data-ttu-id="d08ce-690">タスクに関連付して、割り当てられていない割り当てが複数存在するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-690">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="d08ce-691">大規模なプロジェクトでは、タスク名の入力に非常に時間がかかることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-691">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-november-20"></a><span data-ttu-id="d08ce-693">バージョン 2012: 11 月 20 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-693">Version 2012: November 20</span></span>
<span data-ttu-id="d08ce-694">*バージョン 2012 (ビルド 13512.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-694">*Version 2012 (Build 13512.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-696">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-696">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-697">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-697">Outlook</span></span>

- <span data-ttu-id="d08ce-698">**会議はすべてオンラインで:** 新しい設定により、オンライン会議のスケジュールを簡単に立てれるため、既定ですべての会議をオンラインにできます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-698">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-699">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-699">PowerPoint</span></span>

- <span data-ttu-id="d08ce-700">**ビデオ ライブラリ:** アプリ内で利用可能な、質の良い無料のビデオ フッテージのライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-700">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-703">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-703">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="d08ce-704">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-704">PowerPoint</span></span>

- <span data-ttu-id="d08ce-705">共同編集者の詳細情報が有効になった際に、不明だった共同編集者のプレゼンス インジケーターを完全に更新できなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-705">Fixed an issue where the presence indicator for an unknown coauthor does not get completely refreshed, once more information about the coauthor is available.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-706">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-706">Word</span></span>

- <span data-ttu-id="d08ce-707">文書を隠し文字で PDF に保存する際に、Word が固まる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-707">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-november-13"></a><span data-ttu-id="d08ce-709">バージョン 2012: 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-709">Version 2012: November 13</span></span>
<span data-ttu-id="d08ce-710">*バージョン 2012 (ビルド 13510.20004)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-710">*Version 2012 (Build 13510.20004)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-712">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-712">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-713">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-713">Excel</span></span>

- <span data-ttu-id="d08ce-714">OneDrive のローカル同期フォルダーからファイルを挿入する際に、「オブジェクトの挿入」コマンドにおいて正しいアイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-714">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-715">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-715">Outlook</span></span>

- <span data-ttu-id="d08ce-716">タスク進捗レポートの [宛先] フィールドが空白になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-716">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-717">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-717">PowerPoint</span></span>

- <span data-ttu-id="d08ce-718">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-718">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-719">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-719">Project</span></span>

- <span data-ttu-id="d08ce-720">成果物が関連付けられていた SharePoint サイトが存在しなくなった場合に、成果物の依存関係を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-720">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="d08ce-721">更新された情報が保存されているはずのプロジェクトをユーザーが開いた際に、更新された情報が見つからないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-721">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-722">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-722">Word</span></span>

- <span data-ttu-id="d08ce-723">ズーム中に写真がぼやけてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-723">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="d08ce-724">長いハイパーリンクが一部省略されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-724">We fixed an issue where long hyperlinks were getting truncated.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2012-november-06"></a><span data-ttu-id="d08ce-726">バージョン 2012: 11 月 6 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-726">Version 2012: November 06</span></span>
<span data-ttu-id="d08ce-727">*バージョン 2012 (ビルド 13430.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-727">*Version 2012 (Build 13430.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-729">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-729">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-730">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-730">Excel</span></span>

- <span data-ttu-id="d08ce-731">**複数のシートを同時に再表示する:** 一度に再表示できるのが、1枚のシートだけではなくなりました。一度に複数の非表示シートを表示します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-731">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="d08ce-732">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-732">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a><span data-ttu-id="d08ce-733">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-733">Outlook</span></span>

- <span data-ttu-id="d08ce-734">**同じ署名、すべてのデバイス:** 署名をクラウドに保存し ます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-734">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="d08ce-735">一度作成して、Outlook を使用するすべての場所で使用します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-735">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-738">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-738">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-739">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-739">Excel</span></span>

- <span data-ttu-id="d08ce-740">一部のリボン要素が簡体字中国語でローカライズされていないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-740">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="d08ce-741">更新時に Excel が予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-741">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-742">Outlook</span></span>

- <span data-ttu-id="d08ce-743">Zip ファイルから開いたメッセージに添付ファイルを追加するときに問題が発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-743">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-30"></a><span data-ttu-id="d08ce-745">バージョン 2011: 10 月 30 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-745">Version 2011: October 30</span></span>
<span data-ttu-id="d08ce-746">*バージョン 2011 (ビルド 13426.20004)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-746">*Version 2011 (Build 13426.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-748">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-748">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-749">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-749">Excel</span></span>

- <span data-ttu-id="d08ce-750">**改善された条件付き書式ダイアログ**: 条件付き書式ダイアログのサイズが変更可能になり、シングルクリックでルールを複製できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-750">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="d08ce-751">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-751">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-754">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-754">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-755">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-755">Access</span></span>

- <span data-ttu-id="d08ce-756">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-756">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="d08ce-757">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-757">Excel</span></span>

- <span data-ttu-id="d08ce-758">Oracle データベースへの接続を使用する際の Power Pivot の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-758">Fixed a problem with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="d08ce-759">MTR 計算およびグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) のプロセスがトリガーされたときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-759">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="d08ce-760">この変更により、atomsvc ファイルを読み込もうとすると Excel でエラーが発生するバグが修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-760">This change fixes a bug, which causes a failure in Excel on attempt to load an atomsvc file.</span></span>


- <span data-ttu-id="d08ce-761">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-761">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-762">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-762">Outlook</span></span>

- <span data-ttu-id="d08ce-763">オプションがグレー表示され、メールボックスの所有者が自分のカレンダーの共有権限を管理できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-763">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="d08ce-764">メールテンプレートを .OFT として保存すると、中国語の文字が疑問符に変わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-764">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


- <span data-ttu-id="d08ce-765">Outlook が制限付きのアクセス許可でメッセージを作成できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-765">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="d08ce-766">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-766">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-767">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-767">PowerPoint</span></span>

- <span data-ttu-id="d08ce-768">デザインウィンドウを閉じるときにグリッド線がスライドからずれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-768">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="d08ce-769">選択ウィンドウを開いた状態で画面の記録を停止した後、スライドのスクロールバーが自動的に調整を開始する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-769">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-770">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-770">Project</span></span>

- <span data-ttu-id="d08ce-771">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-771">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="d08ce-772">リソースエンゲージメントが GUID ではなく名前でリソースを検索する問題を修正しました。同じ名前のリソースが複数ある場合に問題が発生していました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-772">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-773">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-773">Word</span></span>

- <span data-ttu-id="d08ce-774">コメントヒントをクリックしてもズームアウトしてコメントカードが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-774">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="d08ce-775">列間の線がずれている場合があるレイアウトの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-775">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="d08ce-776">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-776">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-777">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-777">Office Suite</span></span>

- <span data-ttu-id="d08ce-778">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-778">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2011-october-23"></a><span data-ttu-id="d08ce-780">バージョン 2011: 10 月 23 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-780">Version 2011: October 23</span></span>
<span data-ttu-id="d08ce-781">*バージョン 2011 (ビルド 13415.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-781">*Version 2011 (Build 13415.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-783">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-783">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="d08ce-784">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-784">PowerPoint</span></span>

- <span data-ttu-id="d08ce-785">**プレゼンター コーチでプレゼンテーションのリハーサルを行う:** 話す速度、ピッチ、つなぎ語、機微な表現など、聴衆の関心を引きつけておくのに役立つ内容についてフィードバックを受けます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-785">**Rehearse your presentation with Presenter Coach:** Get feedback on the things that help keep an audience engaged — like pacing, pitch, filler words, sensitive phrases, and more.</span></span> [<span data-ttu-id="d08ce-786">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-786">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-789">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-789">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-790">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-790">Access</span></span>

- <span data-ttu-id="d08ce-791">同期済みの OneDrive フォルダーからクエリをエクスポートしようとしたときに、一部のユーザーに "システム リソースの超過" というエラーが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-791">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>

- <span data-ttu-id="d08ce-792">フォーム ウィンドウ間で別のフォームに切り替える場合の「自動」切り替えの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-792">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-793">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-793">Outlook</span></span>

- <span data-ttu-id="d08ce-794">会議の場所からコピーした URL をブラウザーなどの別の場所に貼り付けると、URL の末尾にセミコロンが含まれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-794">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-795">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-795">PowerPoint</span></span>

- <span data-ttu-id="d08ce-796">スライドショーを 2 台目のモニターに複製する場合、そのスライドショーが他のウィンドウの背面で非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-796">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-797">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-797">Project</span></span>

- <span data-ttu-id="d08ce-798">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-798">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-799">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-799">Word</span></span>

- <span data-ttu-id="d08ce-800">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-800">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>

- <span data-ttu-id="d08ce-801">機密度ラベルに透かしが適用される場合がある印刷の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-801">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-16"></a><span data-ttu-id="d08ce-803">バージョン 2011: 10 月 16 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-803">Version 2011: October 16</span></span>
<span data-ttu-id="d08ce-804">*バージョン 2011 (ビルド 13408.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-804">*Version 2011 (Build 13408.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-806">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-806">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-807">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-807">Excel</span></span>

- <span data-ttu-id="d08ce-808">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-808">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="d08ce-809">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-809">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="d08ce-810">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-810">Outlook</span></span>

- <span data-ttu-id="d08ce-811">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-811">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="d08ce-812">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-812">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="d08ce-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-813">PowerPoint</span></span>

- <span data-ttu-id="d08ce-814">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-814">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="d08ce-815">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-815">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a><span data-ttu-id="d08ce-816">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-816">Word</span></span>

- <span data-ttu-id="d08ce-817">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-817">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="d08ce-818">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-818">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-821">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-821">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-822">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-822">Outlook</span></span>

- <span data-ttu-id="d08ce-823">ユーザーが基本認証で Microsoft 365 グループの予定表の予定を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-823">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="d08ce-824">ニックネーム キャッシュの読み込み中に Outlook の起動に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-824">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-825">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-825">PowerPoint</span></span>

- <span data-ttu-id="d08ce-826">画像の横のコンテンツ プレースホルダー アイコンにツールヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-826">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="d08ce-827">pptsx ファイルで表示されるスライド ショーの保護されたビューで、IRM で保護されたドキュメントの画面キャプチャが許可される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-827">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-09"></a><span data-ttu-id="d08ce-829">バージョン 2011: 10 月 09 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-829">Version 2011: October 09</span></span>
<span data-ttu-id="d08ce-830">*バージョン 2011 (ビルド 13406.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-830">*Version 2011 (Build 13406.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-832">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-832">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-833">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-833">Excel</span></span>

- <span data-ttu-id="d08ce-834">**クエリから Powe rPlatform データフローを作成する**: 新しい Powe rPlatform データフローの作成に使用できる Power Query テンプレートにクエリをエクスポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-834">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-835">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-835">PowerPoint</span></span>

- <span data-ttu-id="d08ce-836">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します</span><span class="sxs-lookup"><span data-stu-id="d08ce-836">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="d08ce-837">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-837">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-840">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-840">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-841">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-841">Excel</span></span>

- <span data-ttu-id="d08ce-842">COM アドインを有効にして SaveAs 操作を行った後、ファイル名が変更されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-842">We fixed an issue where  Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="d08ce-843">Excel データモデルに不適切なメジャー定義がある場合に、自動保存が誤った、または誤解を招くエラーメッセージを表示して失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-843">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="d08ce-844">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-844">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-845">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-845">Outlook</span></span>

- <span data-ttu-id="d08ce-p136">画像の添付ファイルをクイック印刷すると、以下のエラーが発生する問題を修正しました。「Windows がこの画像を見つけることができません。場所を確認してから、もう一度お試しください」。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p136">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture. Check the location, and then try again".</span></span>


- <span data-ttu-id="d08ce-848">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-848">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-849">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-849">PowerPoint</span></span>

- <span data-ttu-id="d08ce-850">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-850">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-851">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-851">Project</span></span>

- <span data-ttu-id="d08ce-852">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-852">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="d08ce-853">プロジェクトサイトにタスクリストがあり、タスクリストをグループ化すると、タスクリストをすばやく編集できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-853">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="d08ce-854">CSOM を介してエンタープライズリソースを更新すると、リソースの最大単位数が失われることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-854">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-855">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-855">Word</span></span>

- <span data-ttu-id="d08ce-856">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-856">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d08ce-857">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-857">Office Suite</span></span>

- <span data-ttu-id="d08ce-858">SSO API インタラクティブ サインインがエラー コードを返す問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-858">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-02"></a><span data-ttu-id="d08ce-860">バージョン 2010: 10 月 2 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-860">Version 2010: October 02</span></span>
<span data-ttu-id="d08ce-861">*バージョン 2010 (ビルド 13328.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-861">*Version 2010 (Build 13328.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-863">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-863">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-864">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-864">Excel</span></span>

- <span data-ttu-id="d08ce-865">**[詳細] ダイアログ ボックスを使用してデータ型を作成する:** [詳細] ダイアログ ボックスでは、作成するデータ型を組み合わせる列を手動で選択できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-865">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-868">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-868">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="d08ce-869">OneNote</span><span class="sxs-lookup"><span data-stu-id="d08ce-869">OneNote</span></span>

- <span data-ttu-id="d08ce-870">ユーザーが OutSpace で [ファイル]、[情報] に移動してテキスト ボックスからノートブックの URL を選択してコピーできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-870">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-871">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-871">Outlook</span></span>

- <span data-ttu-id="d08ce-872">件名が空白の場合、自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-872">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="d08ce-873">間違ったフォルダー GUID がフォルダーにキャッシュされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-873">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="d08ce-874">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-874">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="d08ce-875">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-875">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="d08ce-876">オンライン共有フォルダーが親フォルダー名を返さない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-876">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="d08ce-877">失敗する代わりに、プライマリ アカウントに誤って送信された空のパスを返しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-877">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="d08ce-878">読み取り専のプレビュー ウィンドウから下書きを再開した後、トラックの変更がオンになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-878">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="d08ce-879">[名前を付けて保存] オプションが従来の添付ファイルで使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-879">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="d08ce-880">ポリシーを上書きするときに正当化テキストをカスタマイズする方法をユーザーに提供する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-880">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-881">PowerPoint</span></span>

- <span data-ttu-id="d08ce-882">PDF へのエクスポート中に PowerPoint が長方形の箇条書きをエクスポートしなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-882">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="d08ce-883">最後のスライドを表示していて、[セッションの終了] を押した後、概要が表示される前に次のスライドにスワイプすると、[セッションの終了] ダイアログ ボックスが概要ページにも表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-883">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="d08ce-884">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-884">Project</span></span>

- <span data-ttu-id="d08ce-885">リソース配分状況ビューまたはシート ビューにグループ化を適用してから列を挿入すると、Project がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-885">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


- <span data-ttu-id="d08ce-886">数式を使用してカスタム フィールドを作成し、取得した値を使用している場合、表示の切り替えやプロジェクト/タスクの詳細を開く際にパフォーマンスの遅延が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-886">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="d08ce-887">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-887">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="d08ce-888">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-888">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-september-25"></a><span data-ttu-id="d08ce-890">バージョン 2010: 9 月 25 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-890">Version 2010: September 25</span></span>
<span data-ttu-id="d08ce-891">*バージョン 2010 (ビルド 13318.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-891">*Version 2010 (Build 13318.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-893">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-893">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-894">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-894">Excel</span></span>

- <span data-ttu-id="d08ce-895">**Power Query を使用してデータ型を作成する: Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します**</span><span class="sxs-lookup"><span data-stu-id="d08ce-895">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-896">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-896">Outlook</span></span>

- <span data-ttu-id="d08ce-897">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新</span><span class="sxs-lookup"><span data-stu-id="d08ce-897">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="d08ce-898">**メッセージの作成にかかる時間を節約:** Outlook は、メッセージをすばやく作成するのに役立つ提案を作成することを示します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-898">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="d08ce-899">提案を受け入れるには、Tab キーを使用するだけです。</span><span class="sxs-lookup"><span data-stu-id="d08ce-899">To accept the suggestion, just use the Tab key.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-900">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-900">Word</span></span>

- <span data-ttu-id="d08ce-901">**Microsoft エディター ウィンドウにデスクトップ用の Word の更新が表示される:** デスクトップ クライアント用の Word エディター ウィンドウの現在のエクスペリエンスをアップグレードしました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-901">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-904">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-904">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-905">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-905">Access</span></span>

- <span data-ttu-id="d08ce-906">スクロール中に保存されたクエリ/リレーションシップ ウィンドウを読み込むときに、スクロールバーの位置が正しく設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-906">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="d08ce-907">[テーブルを追加する] 作業ウィンドウに「&」を含む名前が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-907">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="d08ce-908">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-908">Excel</span></span>

- <span data-ttu-id="d08ce-909">マルチレベル カテゴリの手動間隔がグラフで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-909">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="d08ce-910">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-910">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="d08ce-911">データ検証に使用されるテーブルに追加しても、ブック内のすべてのシートのオプションが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-911">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


### <a name="onenote"></a><span data-ttu-id="d08ce-912">OneNote</span><span class="sxs-lookup"><span data-stu-id="d08ce-912">OneNote</span></span>

- <span data-ttu-id="d08ce-913">OneNote がカスタム テーマのキャンバスのハイ コントラスト カラーを尊重しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-913">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


- <span data-ttu-id="d08ce-914">ノートブックのカラー セレクターで緑色にカーソルを合わせると、ポップアップに「赤チョーク」と表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-914">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d08ce-915">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-915">PowerPoint</span></span>

- <span data-ttu-id="d08ce-916">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-916">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-917">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-917">Word</span></span>

- <span data-ttu-id="d08ce-918">ワークフロー対応ファイルへのリンクが期待どおりに開かない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-918">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-september-18"></a><span data-ttu-id="d08ce-920">バージョン 2010: 9 月 18 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-920">Version 2010: September 18</span></span>
<span data-ttu-id="d08ce-921">*バージョン 2010 (ビルド 13312.20006)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-921">*Version 2010 (Build 13312.20006)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-923">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-923">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-924">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-924">Outlook</span></span>

- <span data-ttu-id="d08ce-925">**エディターによるメッセージの校正:** Outlook 64 ビットのユーザーのメールで、文法や他のスタイル修正候補が提供されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-925">**Proofread your messages with Editor:** You can now get grammar and other style suggestions in your emails for Outlook 64-bit users.</span></span> <span data-ttu-id="d08ce-926">下線が引かれた単語には、文章を洗練させるための修正候補がエディターから提示されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-926">Look for underlined words to see Editor’s suggestions to refine your writing.</span></span>

- <span data-ttu-id="d08ce-927">**組み込みの翻訳機能を使用して、言語の壁を取り除く:** 翻訳用のアドインは必要なくなりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-927">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="d08ce-928">メッセージを右クリックすると、特定の単語、語句、またはメッセージ全体を翻訳できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-928">In a message, right-click to translate specific words, phrases, or the whole message.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-931">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-931">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-932">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-932">Excel</span></span>

- <span data-ttu-id="d08ce-933">VBA を使用した、シリーズの最大値、中間値、最小値の色の設定が機能しないという 2D マップ グラフの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-933">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="d08ce-934">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-934">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="d08ce-935">「Excel で 1 つまたは複数の数式を計算しようとする際にリソース不足になりました」というエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-935">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="d08ce-936">数式バーに数式を入力したときに、ChartSheet がクラッシュする場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-936">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


### <a name="outlook"></a><span data-ttu-id="d08ce-937">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-937">Outlook</span></span>

- <span data-ttu-id="d08ce-938">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-938">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="d08ce-939">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-939">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


### <a name="word"></a><span data-ttu-id="d08ce-940">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-940">Word</span></span>

- <span data-ttu-id="d08ce-941">変更履歴 (挿入/削除) をユーザーがタップすると、コメントがポップアップ表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-941">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="d08ce-942">Word でコメントの吹き出しを削除するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-942">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="d08ce-943">Outlook でメッセージが [転送不可] に設定される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-943">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="d08ce-944">引用と数式を含む Word 文書を保存するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-944">We fixed an issue with saving Word document that contains citation and equation.</span></span>



[//]: # (BUGDETAILS を削除しないでください 終了)

## <a name="version-2010-september-11"></a><span data-ttu-id="d08ce-946">バージョン 2010: 9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-946">Version 2010: September 11</span></span>
<span data-ttu-id="d08ce-947">*バージョン 2010 (ビルド 13304.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-947">*Version 2010 (Build 13304.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-949">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-949">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-950">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-950">Access</span></span>

- <span data-ttu-id="d08ce-951">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-951">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-952">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-952">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-953">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-953">Excel</span></span>

- <span data-ttu-id="d08ce-954">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-954">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-955">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-955">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="onenote"></a><span data-ttu-id="d08ce-956">OneNote</span><span class="sxs-lookup"><span data-stu-id="d08ce-956">OneNote</span></span>

- <span data-ttu-id="d08ce-957">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-957">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-958">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-958">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-959">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-959">Outlook</span></span>

- <span data-ttu-id="d08ce-960">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-960">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-961">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-961">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-962">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-962">PowerPoint</span></span>

- <span data-ttu-id="d08ce-963">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-963">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-964">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-964">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-965">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-965">Project</span></span>

- <span data-ttu-id="d08ce-966">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-966">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-967">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-967">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="publisher"></a><span data-ttu-id="d08ce-968">Publisher</span><span class="sxs-lookup"><span data-stu-id="d08ce-968">Publisher</span></span>

- <span data-ttu-id="d08ce-969">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-969">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-970">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-970">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="visio"></a><span data-ttu-id="d08ce-971">Visio</span><span class="sxs-lookup"><span data-stu-id="d08ce-971">Visio</span></span>

- <span data-ttu-id="d08ce-972">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-972">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-973">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-973">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-974">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-974">Word</span></span>

- <span data-ttu-id="d08ce-975">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="d08ce-975">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="d08ce-976">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-976">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-979">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-979">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-980">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-980">Excel</span></span>

- <span data-ttu-id="d08ce-981">[改ページ プレビュー] が有効になっているときに、大量のデータが含まれているワークシート間を切り替える際に顕著な遅延が発生する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-981">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-982">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-982">Outlook</span></span>

- <span data-ttu-id="d08ce-983">優先受信トレイをオフにして並べ替えを行った後に、メールが非表示になるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-983">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-984">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-984">PowerPoint</span></span>

- <span data-ttu-id="d08ce-985">エディターとスライド ショーで GIF のアニメーションが1 回だけしか再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-985">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>

[//]: # (BUGDETAILS を削除しないでください 終了)

## <a name="version-2010-september-04"></a><span data-ttu-id="d08ce-987">バージョン 2010: 9 月 4 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-987">Version 2010: September 04</span></span>
<span data-ttu-id="d08ce-988">*バージョン 2010 (ビルド 13301.20004)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-988">*Version 2010 (Build 13301.20004)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-990">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-990">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-991">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-991">Outlook</span></span>

- <span data-ttu-id="d08ce-992">**メールのピン留め:** この機能を使うことで、他のユーザーに返信する必要があるメールを追跡したり、忘れないようにそれらのメールをメッセージ一覧の一番上に固定したりできます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-992">**Pinning email:** This feature helps users keep track of mails they need to go back to you or have as a reminder by keeping them at the top of the message list.</span></span>

- <span data-ttu-id="d08ce-993">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、関連性が最も高いメールが候補に表示されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-993">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="d08ce-994">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、関連性が最も高いメールが候補に表示されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-994">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="d08ce-995">**Microsoft エディターが Word と Outlook のデスクトップ クライアント向けにアップグレードされました:** エディターのスペルチェック、文章校正、および詳細なスタイルの修正候補で、新しい、クリックによるレビュー モデルが導入されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-995">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="d08ce-996">この変更には、候補をレビューするために表示される専用のカードも含まれています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-996">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-997">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-997">Word</span></span>

- <span data-ttu-id="d08ce-998">**Microsoft エディターが Word と Outlook のデスクトップ クライアント向けにアップグレードされました:** エディターのスペルチェック、文章校正、および詳細なスタイルの修正候補で、新しい、クリックによるレビュー モデルが導入されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-998">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="d08ce-999">この変更には、候補をレビューするために表示される専用のカードも含まれています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-999">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1002">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1002">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1003">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1003">Excel</span></span>

- <span data-ttu-id="d08ce-1004">LET 関数が含まれているファイルを開くと、以下の警告が表示される問題が修正されました: "ファイル名.xlsx" のコンテンツに問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1004">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="d08ce-1005">できるだけ多くの内容の復元を試みますか?</span><span class="sxs-lookup"><span data-stu-id="d08ce-1005">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="d08ce-1006">このブックの発行元が信頼できる場合は、[はい] をクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1006">If you trust the source of this workbook, click Yes".</span></span>
- <span data-ttu-id="d08ce-1007">XLAM アドインの参照と名前付き範囲に関連するクラッシュが修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1007">We fixed a crash related to XLAM add-in references and named ranges.</span></span>
- <span data-ttu-id="d08ce-1008">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1008">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>
- <span data-ttu-id="d08ce-p155">ユーザーが動的配列にカスタム スタイルを適用すると、"配列の一部を変更することはできません" というエラーが表示される問題が修正されました。これは以前に存在していた制約でしたが、現在は削除されています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p155">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array". This was a legacy restriction that has been removed.</span></span>
- <span data-ttu-id="d08ce-1011">デバイスへの接続が失われると (リモート セッションが接続されたり接続が解除されたり、モニターでの変更があった場合など) Excel の関数バーが完全に描画されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1011">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1012">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1012">Outlook</span></span>

- <span data-ttu-id="d08ce-1013">問題が修正され、グループ ポリシー経由で既定のログ記録オプションを有効または無効にするための柔軟性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1013">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>
- <span data-ttu-id="d08ce-1014">アシスタントのアクセス許可があるメールボックスと管理者のアクセス許可があるメールボックスの間でメールの下書きを移動した後も、メール送信者の従来のドメイン名が維持されて表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1014">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>
- <span data-ttu-id="d08ce-1015">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1015">We fixed an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>
- <span data-ttu-id="d08ce-1016">1 行リボン (SLR) を有効にした後に VBA コード ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") を実行すると実行時エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1016">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>
- <span data-ttu-id="d08ce-1017">高解像度 (1750 x 1920 など) と大きなテキストサイズ (175% など) が同時に使用された場合に、[自動応答] ダイアログの [OK] ボタンと [キャンセル] ボタンが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1017">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>
- <span data-ttu-id="d08ce-1018">会議出席依頼を空の連絡先グループから別の連絡先グループに送信するとクラッシュする状態が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1018">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>
- <span data-ttu-id="d08ce-1019">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1019">We fixed an issue that caused users to experience a crash when opening certain very large emails.</span></span>
- <span data-ttu-id="d08ce-1020">アドインが常に有効になっていることがグループ ポリシーで要求される場合に、ユーザーがアドインを無効にすることを防ぐためにアドインの監視が使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1020">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1021">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1021">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1022">ビデオがスライドショーで自動的に再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1022">We fixed an issue where videos were not playing automatically in slideshows.</span></span>
- <span data-ttu-id="d08ce-1023">PowerPoint を起動後にスライドを挿入してコメント ウィンドウを開いて閉じると、縮小版ウィンドウ内のスライドが重なって表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1023">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1024">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1024">Project</span></span>

- <span data-ttu-id="d08ce-1025">リソースに複数のコスト単価テーブルが含まれている場合、残りのコストが正確に計算されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1025">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>
- <span data-ttu-id="d08ce-1026">SharePoint のタスク リストに接続されているプロジェクトでプロジェクト終了日が更新されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1026">We fixed an issue where the Project finish date wasn't getting updated for projects connected to SharePoint tasks list.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1027">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1027">Word</span></span>

- <span data-ttu-id="d08ce-1028">ユーザーがコメントをクリックした場合に、コメント カードでコメントのテキストの周囲に枠線が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1028">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>
- <span data-ttu-id="d08ce-1029">ドキュメントの拡大率が 160% より大きく設定され、コメント ウィンドウが表示されていない場合に、フォーカスがコメント ウィンドウに移動しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1029">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>
- <span data-ttu-id="d08ce-1030">開いている複数のドキュメントの間で切り替えを行うと、あるドキュメントのコメントが、開かれている別のドキュメントに表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1030">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>
- <span data-ttu-id="d08ce-1031">ユーザーがコメントの下書きを作成して、解決済みのコメントが既に含まれている行にアンカーすると、サイドトラックでは解決済みのコメントに対して正しくない順番で下書きが並べ替えられる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1031">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>
- <span data-ttu-id="d08ce-1032">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1032">We fixed an issue where long links were not being wrapped when saving a document to HTML format.</span></span>
- <span data-ttu-id="d08ce-1033">AutoOpen が AutoExec. より前に実行されるというマクロの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1033">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>

[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2009-august-28"></a><span data-ttu-id="d08ce-1035">バージョン 2009: 8 月 28 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1035">Version 2009: August 28</span></span>
<span data-ttu-id="d08ce-1036">*バージョン 2009 (ビルド 13219.20004)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1036">*Version 2009 (Build 13219.20004)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1038">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1038">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1039">Outlook</span></span>

- <span data-ttu-id="d08ce-1040">1 つ以上のメッセージを選択した場合に、OneNote に "転送不可" ポリシーが適用されているメール コンテンツを送信することができるようになっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1040">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1041">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1041">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1042">ビデオを挿入する機能が無効になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1042">We fixed an issue where the functionality to insert a video was disabled.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1043">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1043">Word</span></span>

- <span data-ttu-id="d08ce-1044">コメントの選択時に、ヘッダー/フッターを閉じることができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1044">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>
- <span data-ttu-id="d08ce-1045">サイドトラックのスクロールが機能しないため、サイドトラックの境界を超えたコメントのスレッドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1045">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>
- <span data-ttu-id="d08ce-1046">サイドトラック ウィンドウで解決済みのコメントを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1046">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1047">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1047">Office Suite</span></span>

- <span data-ttu-id="d08ce-1048">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1048">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>
- <span data-ttu-id="d08ce-1049">[図の圧縮] ダイアログで、ユーザーが選択した一部の DPI 設定が保持されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1049">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-21"></a><span data-ttu-id="d08ce-1051">バージョン 2009: 8 月 21 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1051">Version 2009: August 21</span></span>
<span data-ttu-id="d08ce-1052">*バージョン 2009 (ビルド 13212.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1052">*Version 2009 (Build 13212.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1054">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1054">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1055">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1055">Excel</span></span>

- <span data-ttu-id="d08ce-1056">**Excel のアクション ペン:** ペン ツールを使用すると、データを手書きしてすばやく編集できます</span><span class="sxs-lookup"><span data-stu-id="d08ce-1056">**Action Pen in Excel:** Pen Tool to help you handwrite and make quick edits to your data</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1057">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1057">Outlook</span></span>

- <span data-ttu-id="d08ce-1058">**メッセージの所有者として会話を削除する:** この機能を使用すると、メッセージの所有者による会話を削除できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1058">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1061">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1061">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-1062">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1062">Access</span></span>

- <span data-ttu-id="d08ce-1063">ODBC データベースへの接続がサードパーティ製アプリケーションで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1063">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1064">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1064">Excel</span></span>

- <span data-ttu-id="d08ce-1065">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1065">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>
- <span data-ttu-id="d08ce-1066">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1066">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1067">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1067">Outlook</span></span>

- <span data-ttu-id="d08ce-1068">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1068">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1069">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1069">Word</span></span>

- <span data-ttu-id="d08ce-1070">コメントが削除された後に Word がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1070">We fixed an issue where Word could crash after comments were deleted.</span></span>
- <span data-ttu-id="d08ce-1071">メールで箇条書きが正しく表示されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1071">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-14"></a><span data-ttu-id="d08ce-1073">バージョン 2009: 8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1073">Version 2009: August 14</span></span>
<span data-ttu-id="d08ce-1074">*バージョン 2009 (ビルド 13205.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1074">*Version 2009 (Build 13205.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1076">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1076">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1077">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1077">Excel</span></span>

- <span data-ttu-id="d08ce-1078">ユーザーがかっこを含む数式名を入力し、F1 を介してヘルプを呼び出した場合、その数式に固有のヘルプ トピックが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1078">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>
- <span data-ttu-id="d08ce-1079">古いバージョンのファイルを復元した後、ボタンに割り当てられたマクロが壊れる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1079">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1080">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1080">Outlook</span></span>

- <span data-ttu-id="d08ce-1081">この変更により、ユーザーがタブを会議ページからスケジュール アシスタント ページに切り替えた後も会議ページが引き続き表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1081">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1082">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1082">Word</span></span>

- <span data-ttu-id="d08ce-1083">箇条書きのアイコンが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1083">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-07"></a><span data-ttu-id="d08ce-1085">バージョン 2009: 8 月 7 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1085">Version 2009: August 07</span></span>
<span data-ttu-id="d08ce-1086">*バージョン 2009 (ビルド 13130.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1086">*Version 2009 (Build 13130.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1088">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1088">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1089">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1089">Outlook</span></span>

- <span data-ttu-id="d08ce-1090">Active Directory の "otherTelephone" および "otherHomePhone" のユーザー アカウント属性が、対応する Outlook LDAP 属性にマッピングされていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1090">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1091">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1091">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1092">特定の条件下でリボンまたはタイトル バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1092">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-31"></a><span data-ttu-id="d08ce-1094">バージョン 2008: 7 月 31 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1094">Version 2008: July 31</span></span>
<span data-ttu-id="d08ce-1095">*バージョン 2008 (ビルド 13127.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1095">*Version 2008 (Build 13127.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1097">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1097">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1098">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1098">Excel</span></span>

- <span data-ttu-id="d08ce-1099">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1099">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="d08ce-1100">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1100">No conversion required.</span></span><br /><span data-ttu-id="d08ce-1101">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-1101">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1102">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1102">Outlook</span></span>

- <span data-ttu-id="d08ce-1103">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1103">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="d08ce-1104">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1104">No conversion required.</span></span><br /><span data-ttu-id="d08ce-1105">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-1105">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1106">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1106">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1107">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1107">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="d08ce-1108">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1108">No conversion required.</span></span><br /><span data-ttu-id="d08ce-1109">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-1109">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1110">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1110">Word</span></span>

- <span data-ttu-id="d08ce-1111">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1111">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="d08ce-1112">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1112">No conversion required.</span></span><br /><span data-ttu-id="d08ce-1113">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-1113">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1116">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1116">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-1117">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1117">Access</span></span>

- <span data-ttu-id="d08ce-1118">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1118">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex.'</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1119">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1119">Excel</span></span>

- <span data-ttu-id="d08ce-1120">グラフ系列の順序を変更した場合、系列に並んだチェックボックスが系列に沿って並び替えられない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1120">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>
- <span data-ttu-id="d08ce-1121">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1121">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1122">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1122">Outlook</span></span>

- <span data-ttu-id="d08ce-1123">この修正プログラムでは、ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1123">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>
- <span data-ttu-id="d08ce-1124">この修正プログラムでは、Outlook のMarkdown コンテンツでは改行が正常に表示されない問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1124">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1125">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1126">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1126">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="d08ce-1127">Office ストアへのアクセスが許可されていない場合に、PowerPoint の [フォーム] ボタンでフォームを作成できないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1127">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to the Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1128">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1128">Project</span></span>

- <span data-ttu-id="d08ce-1129">SharePoint のタスクリストで、2番目のタブにあるリボン ボタンが無効になる場合がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1129">We fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1130">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1130">Word</span></span>

- <span data-ttu-id="d08ce-1131">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1131">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="d08ce-1132">変更を追跡するコメントが追加された場合に、[変更履歴] ウィンドウが予期せず開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1132">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>
- <span data-ttu-id="d08ce-1133">[挿入]、[リンク] ドロップダウンを通して、ドキュメントへのリンクがコメントボックスに挿入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1133">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>
- <span data-ttu-id="d08ce-1134">ハイパーリンクを含む画像を追加した後に、VBA のハイパーリンク コレクションにあるハイパーリンク数が正しく指定されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1134">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-24"></a><span data-ttu-id="d08ce-1136">バージョン 2008: 7 月 24 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1136">Version 2008: July 24</span></span>
<span data-ttu-id="d08ce-1137">*バージョン 2008 (ビルド 13117.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1137">*Version 2008 (Build 13117.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1139">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1139">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1140">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1140">Excel</span></span>

- <span data-ttu-id="d08ce-1141">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1141">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="d08ce-1142">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1142">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1145">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1145">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="d08ce-1146">OneNote</span><span class="sxs-lookup"><span data-stu-id="d08ce-1146">OneNote</span></span>

- <span data-ttu-id="d08ce-1147">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="d08ce-1147">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1148">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1148">Word</span></span>

- <span data-ttu-id="d08ce-1149">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="d08ce-1149">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>
- <span data-ttu-id="d08ce-1150">変更履歴の記録の[特定のユーザー]オプションが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1150">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>
- <span data-ttu-id="d08ce-1151">HTML ファイルを開くときに、時々切断される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1151">We fixed an occasional hang while opening HTML files.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-17"></a><span data-ttu-id="d08ce-1153">バージョン 2008: 7 月 17 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1153">Version 2008: July 17</span></span>
<span data-ttu-id="d08ce-1154">*バージョン 2008 (ビルド 13115.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1154">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1156">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1156">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1157">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1157">Excel</span></span>

- <span data-ttu-id="d08ce-1158">引き出し線が非表示のピボット グラーフが保存されて再度開かれると、引き出し線が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1158">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="d08ce-1159">ブックの VBA を介して「ForceFullCalculation」が有効になっていると、グラフが常に期待どおりに更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1159">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1160">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1160">Outlook</span></span>

- <span data-ttu-id="d08ce-1161">Outlook で同じメール ドメインから複数のプロファイルを作成することに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1161">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="d08ce-1162">S/MIME 暗号化メッセージのヘッダーにロック アイコンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1162">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="d08ce-1163">暗号化されずに送信されたときに添付ファイルが S/MIME メッセージから削除される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1163">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="d08ce-1164">送信時にプレーン テキストの S/MIME メッセージが文字化けする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1164">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="d08ce-1165">暗号化されていない S/MIME メールを送信すると添付ファイルが破損する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1165">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="d08ce-1166">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1166">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="d08ce-1167">送信者から名前を付けて保存のアクセス許可が付与されている場合でも、受信者が権利保護されたメッセージを保存できなくなる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1167">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="d08ce-1168">一部の言語で一部の高度な検索のオプションのラベルが切り捨てられる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1168">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1169">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1169">Project</span></span>

- <span data-ttu-id="d08ce-1170">[タスク ボード] ビューに一覧表示されているタスクが [リソースの割り当て] ダイアログのタスクと同期していない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1170">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="d08ce-1171">複数の依存関係があるタスクをコピーして貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1171">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1172">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1172">Word</span></span>

- <span data-ttu-id="d08ce-1173">フォーカスがコメント テキスト ボックスにあるときに「エディター」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1173">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="d08ce-1174">フォーカスがコメント テキスト ボックスにあるときに「変更履歴と​​コメントの表示」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1174">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="d08ce-1175">ドキュメントを開くとコメントの状態が失われる可能性があるカスタム XML の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1175">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1176">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1176">Office Suite</span></span>

- <span data-ttu-id="d08ce-1177">ユーザーがタスクバーから新しいアプリ ウィンドウを開いて新しい空白のドキュメントを作成した後、追加のファイルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1177">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="d08ce-1178">ユーザーがドキュメントを編集していて権限を失っていた場合、再認証が必要であることをユーザーに通知しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1178">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2008-july-10"></a><span data-ttu-id="d08ce-1180">バージョン 2008: 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1180">Version 2008: July 10</span></span>
<span data-ttu-id="d08ce-1181">*バージョン 2008 (ビルド 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1181">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1183">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1183">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1184">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1184">Outlook</span></span>

- <span data-ttu-id="d08ce-1185">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1185">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="d08ce-1186">ユーザーが適切な印刷権限を持っていても、印刷ボタンが無効な状態で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1186">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1187">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1187">Project</span></span>

- <span data-ttu-id="d08ce-1188">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存しようとしても、何も起こらない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1188">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1189">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1189">Word</span></span>

- <span data-ttu-id="d08ce-1190">テキストとの画像をコメントボックスに貼り付けると Word が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1190">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="d08ce-1191">最後のコメントを削除すると [新しいコメント] ボタンが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1191">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-03"></a><span data-ttu-id="d08ce-1193">バージョン 2007: 7 月 3 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1193">Version 2007: July 03</span></span>
<span data-ttu-id="d08ce-1194">*バージョン 2007 (ビルド 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1194">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1196">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1196">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1197">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1197">Outlook</span></span>

- <span data-ttu-id="d08ce-1198">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します [詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="d08ce-1198">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="d08ce-1199">**新しい会議室の検索機能:** これまでと違うさまざまな機能で会議室を検索できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1199">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1202">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1203">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1203">Excel</span></span>

- <span data-ttu-id="d08ce-1204">テーブルに関連付けられたクエリが編集されていない場合でも、特定のバージョンの Excel で作成したデータ モデル テーブルが [テーブル プレビュー] に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1204">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="d08ce-1205">[名前の定義] \ [名前の適用] ダイアログで [相対/絶対を無視] 参照を無効にすると数式が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1205">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="d08ce-1206">高度なデータ フィルターをクリアするとテーブルの書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1206">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="d08ce-1207">埋め込まれた PDF 文書のフル パスがファイル名だけでなく文書の標題に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1207">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="d08ce-1208">Wolfram クラウド コネクターを無効にしてから、Excel ブックを保存してもう一度開くとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1208">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="d08ce-1209">ソルバー アドインを有効にして Excel を起動するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1209">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1210">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1210">Outlook</span></span>

- <span data-ttu-id="d08ce-1211">「To」行に 130 人を超える受信者がいる場合に Outlook がハングする問題を修正し、テキストのレンダリングのパフォーマンスも改善しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1211">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="d08ce-1212">2 日を超えるイベントはそれ以降のすべての日に同じ終了時刻を表示するという「To Do バー」の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1212">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="d08ce-1213">Outlook のユーザーが共有の予定表を使用した後、メッセージ一覧の更新が数分間停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1213">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1214">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1214">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1215">スライドのテキスト領域に HTML を貼り付けると、代わりにスライドの上部に作成されたテキスト ボックスに貼り付けられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1215">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="d08ce-1216">発表者ビューですべてのスライドを選択し、Alt + Tabを使用して発表者ビューを終了し、スライド ショーに戻って [ショーの終了] をクリックすると、未処理の例外が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1216">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1217">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1217">Project</span></span>

- <span data-ttu-id="d08ce-1218">特定の XML ファイルを開くと、Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1218">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="d08ce-1219">ライブラリがモダン モードの場合、SharePoint ドキュメント ライブラリから Project ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1219">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="d08ce-1220">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1220">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1221">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1221">Word</span></span>

- <span data-ttu-id="d08ce-1222">マージの競合があり、ユーザーが既に変更を破棄することを選択している場合の共同編集モード中の問題を修正し、変更を保存または破棄するオプションを表示しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1222">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="d08ce-1223">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても「WRO0004.docx」というファイル名で保存されるため、その文書を使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1223">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-26"></a><span data-ttu-id="d08ce-1225">バージョン 2007: 6月 26 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1225">Version 2007: June 26</span></span>
<span data-ttu-id="d08ce-1226">*バージョン 2007 (ビルド 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1226">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1228">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1228">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-1229">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1229">Access</span></span>

- <span data-ttu-id="d08ce-1230">リンクされた SQL テーブルが更新された場合、リンクされたテーブル マネージャーが主キーを要求する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1230">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="d08ce-1231">クエリ エディターのクエリがスクロールして表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1231">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="d08ce-1232">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1232">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1233">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1233">Outlook</span></span>

- <span data-ttu-id="d08ce-1234">ユーザーが配布リストの「送信」または「代理送信」ができなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1234">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="d08ce-1235">メッセージに画像をインラインで挿入し、メッセージを下書きとして保存すると画像のサイズが変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1235">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="d08ce-1236">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1236">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1237">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1237">Project</span></span>

- <span data-ttu-id="d08ce-1238">政府機関向けコミュニティのクラウド環境でプロジェクト プランナのリンクが無効になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1238">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1239">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1239">Office Suite</span></span>

- <span data-ttu-id="d08ce-1240">スケーラブル ベクター グラフィックス （SVG）に挿入されたテキストを、Word、Excel、または PowerPoint ファイルに挿入し、ファイルを保存して閉じ、再度開いた後、判読できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1240">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-19"></a><span data-ttu-id="d08ce-1242">バージョン 2007: 6月 19 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1242">Version 2007: June 19</span></span>
<span data-ttu-id="d08ce-1243">*バージョン 2007 (ビルド 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1243">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1245">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1245">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1246">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1246">Excel</span></span>

- <span data-ttu-id="d08ce-1247">SharePoint/OneDriveにブックを保存すると、ユーザー設定のリボンタブの CustomUI XML が削除される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1247">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="d08ce-1248">ファイルが読み取り専用である場合にのみ、ブックが読み取り専用であった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1248">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1249">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1249">Outlook</span></span>

- <span data-ttu-id="d08ce-1250">解像度の異なる複数のモニターを使用している場合に、Input Method Editor (IME) ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1250">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="d08ce-p161">以前に保存した予定を閉じると、次のエラーが表示されてしまうという問題を修正しました。「別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。アイテムの既定のフォルダーにコピーしますか? 」</span><span class="sxs-lookup"><span data-stu-id="d08ce-p161">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window. Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="d08ce-1253">日本のユーザーに対してミニ カレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1253">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="d08ce-1254">予定表のリマインダーで、1 週間以内に行われる会議の正確な時刻が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1254">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1255">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1255">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1256">ライブの共同編集セッション中に共同編集ギャラリーでユーザーのプレゼンス カラー インジケーターが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1256">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1257">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1257">Project</span></span>

- <span data-ttu-id="d08ce-1258">固定期間タスクが 100% 完了しているが、実際の完了が指定されていない場合、タスク完了率が 100% 未満として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1258">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1259">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1259">Word</span></span>

- <span data-ttu-id="d08ce-1260">HTML ハイパーリンクの色が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1260">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1261">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1261">Office Suite</span></span>

- <span data-ttu-id="d08ce-1262">http または https ベースではない URL が最近使用したリストに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1262">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-12"></a><span data-ttu-id="d08ce-1264">バージョン 2007: 6月 12 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1264">Version 2007: June 12</span></span>
<span data-ttu-id="d08ce-1265">*バージョン 2007 (ビルド 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1265">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1267">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1267">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1268">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1268">Excel</span></span>

- <span data-ttu-id="d08ce-1269">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1269">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="d08ce-1270">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1270">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="d08ce-1271">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1271">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="d08ce-1272">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1272">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="d08ce-1273">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-1273">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1276">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1276">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-1277">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1277">Access</span></span>

- <span data-ttu-id="d08ce-1278">Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できず、行が削除されたと誤って報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1278">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1279">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1279">Excel</span></span>

- <span data-ttu-id="d08ce-1280">レーダーチャートの主要な目盛線が正しく書式設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1280">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1281">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1281">Project</span></span>

- <span data-ttu-id="d08ce-1282">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1282">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="d08ce-1283">ベースラインのリセットまたは更新により、時間単位の予算コスト/作業リソースが変更され、ベースラインが誤った予算値を反映する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1283">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1284">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1284">Word</span></span>

- <span data-ttu-id="d08ce-1285">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式設定をクリアする機能が動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1285">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="d08ce-1286">ルーラーが表示されていないときにテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションが点滅し始める問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1286">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="d08ce-1287">共同編集モードで、コメントの返信がコメント ウィンドウに表示されず、変更履歴ウィンドウに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1287">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="d08ce-1288">Wordに 50 を超える頻繁に開かれる文書のリストがある場合、文書を保存して開いた後、その文書に変更が加えられていなくても、変更履歴が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1288">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-05"></a><span data-ttu-id="d08ce-1290">バージョン 2006: 6 月 5 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1290">Version 2006: June 05</span></span>
<span data-ttu-id="d08ce-1291">*バージョン 2006 (ビルド 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1291">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1293">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1293">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1294">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1294">Excel</span></span>

- <span data-ttu-id="d08ce-1295">**Excel での共同作業中の並べ替え/フィルター処理:** Excel ファイルの並べ替えとフィルター処理を他のユーザーと行うことができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1295">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="d08ce-1296">この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1296">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="d08ce-1297">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1297">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="d08ce-1298">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1298">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="d08ce-1299">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1299">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="d08ce-1300">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1300">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="d08ce-1301">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1301">Outlook</span></span>

- <span data-ttu-id="d08ce-1302">**以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1302">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="d08ce-1303">Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1303">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="d08ce-1304">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1304">This feature is on by default.</span></span> <span data-ttu-id="d08ce-1305">オフにするには、[オプション] > [一般] > [開始オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1305">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1308">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1308">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1309">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1309">Excel</span></span>

- <span data-ttu-id="d08ce-1310">グラフの軸にカスタム値が正しく適用されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1310">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="d08ce-1311">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1311">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1312">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1312">Outlook</span></span>

- <span data-ttu-id="d08ce-1313">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1313">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="d08ce-1314">新しいメール メッセージの作成時にテンプレートを表示するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1314">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="d08ce-1315">Outlook バージョン1911以降、ユーザーが Exchange 2010のパブリック フォルダーを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1315">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="d08ce-1316">Office リボンのグループ予定表の [分類] ボタンが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1316">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="d08ce-1317">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1317">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="d08ce-1318">高 DPI のモニターを使用しているユーザーに対して、フォルダー プロパティの [オンライン アーカイブ] ドロップダウンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1318">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="d08ce-1319">テキスト形式のメールでハイパーリンクを使用して作業しているときに、Outlook でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1319">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="d08ce-1320">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1320">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="d08ce-1321">スクリーン リーダーを使用すると、Outlook ユーザーに断続的なハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1321">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1322">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1322">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1323">サーバ構成のファイルをフォームベースの認証で開くときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1323">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="d08ce-1324">グラフまたはブックが埋め込まれた PowerPoint ファイルの保存時にエラーが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1324">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="d08ce-1325">ユーザーによって終了されたコメント ウィンドウが自動的に再起動する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1325">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="d08ce-1326">1つのスライドからのスライド エディタが次のスライドに重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1326">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1327">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1327">Project</span></span>

- <span data-ttu-id="d08ce-1328">親計画が削除された後、孤立したタスクの削除や再割り当てができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1328">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1329">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1329">Word</span></span>

- <span data-ttu-id="d08ce-1330">コメント ウィンドウのタイムスタンプがシステム ロケールの時間に基づいていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1330">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="d08ce-1331">Web アプリとデスクトップ アプリケーションの間のコメントが同期していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1331">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2006-may-29"></a><span data-ttu-id="d08ce-1333">バージョン 2006: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1333">Version 2006: May 29</span></span>
<span data-ttu-id="d08ce-1334">*バージョン 2006 (ビルド 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1334">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1335">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1335">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1336">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1336">Outlook</span></span>

- <span data-ttu-id="d08ce-1337">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1337">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1338">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1339">**PowerPoint でのストリーム ビデオのパフォーマンス向上:** ビデオの読み込み時間を最小限に抑え快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1339">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="d08ce-1340">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1340">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1343">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1343">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1344">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1344">Excel</span></span>

- <span data-ttu-id="d08ce-1345">OneDrive を起動すると Excel がシャットダウンすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1345">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="d08ce-1346">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1346">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="d08ce-1347">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1347">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="d08ce-1348">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押してスクロールした後、Excel が応答しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1348">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1349">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1349">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1350">マウス ホイールを使用して拡大した後、スライドが中央に配置されていない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1350">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1351">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1351">Word</span></span>

- <span data-ttu-id="d08ce-1352">テキストのコピーと貼り付けがコメント ウィンドウに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1352">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="d08ce-1353">100% ズームでコメント ヒントの吹き出しがぼやけて見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1353">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="d08ce-1354">ポリシー Word 2007 以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集で失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1354">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="d08ce-1355">長いパス名 (32K を超える) のファイルが開かず、適切なエラー メッセージが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1355">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2006-may-22"></a><span data-ttu-id="d08ce-1357">バージョン 2006: 5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1357">Version 2006: May 22</span></span>
<span data-ttu-id="d08ce-1358">*バージョン 2006 (ビルド 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1358">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1360">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1360">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1361">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1361">Excel</span></span>

- <span data-ttu-id="d08ce-1362">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1362">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="d08ce-1363">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1363">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d08ce-1364">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1364">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d08ce-1365">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1365">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="d08ce-1366">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-1366">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1367">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1367">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1368">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1368">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="d08ce-1369">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1369">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d08ce-1370">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1370">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d08ce-1371">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1371">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="d08ce-1372">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-1372">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1373">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1373">Word</span></span>

- <span data-ttu-id="d08ce-1374">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1374">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="d08ce-1375">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1375">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d08ce-1376">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1376">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d08ce-1377">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1377">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="d08ce-1378">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d08ce-1378">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1381">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1381">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1382">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1382">Excel</span></span>

- <span data-ttu-id="d08ce-1383">アドインは、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1383">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="d08ce-1384">Excelとサード パーティの支援技術アプリケーションの一部との間でフォントを管理する際にメモリが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1384">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="d08ce-1385">選択ロックがない図形を含むワークシート上で、アドインがホスト アイテムを要求すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1385">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1386">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1386">Outlook</span></span>

- <span data-ttu-id="d08ce-1387">ユーザーがフォルダー間でアイテムを移動したときに、Folder.BeforeItemMove イベントが正常に起動しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1387">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="d08ce-1388">予定表のアイテムが午前 0 時のしきい値にまたがっていると、終日イベントとして表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1388">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="d08ce-1389">2 つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1389">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="d08ce-1390">ユーザーが予定表をゲスト ユーザーと共有できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1390">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1391">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1391">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1392">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1392">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1393">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1393">Project</span></span>

- <span data-ttu-id="d08ce-1394">オプションをクリックすると Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1394">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1395">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1395">Word</span></span>

- <span data-ttu-id="d08ce-1396">コメント内のハイパーリンクが機能しなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1396">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="d08ce-1397">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1397">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="d08ce-1398">予定表用の WordMail に HTML を貼り付けできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1398">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="d08ce-1399">共同編集セッションのコメントに返信すると、Word がフリーズすることがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1399">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-15"></a><span data-ttu-id="d08ce-1401">バージョン 2006: 5 月 15 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1401">Version 2006: May 15</span></span>
<span data-ttu-id="d08ce-1402">*バージョン 2006 (ビルド 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1402">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1404">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1404">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1405">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1405">Excel</span></span>

- <span data-ttu-id="d08ce-1406">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1406">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="d08ce-1407">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1407">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

- <span data-ttu-id="d08ce-1408">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1408">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1409">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1409">Outlook</span></span>

- <span data-ttu-id="d08ce-1410">**必要なものだけを見つける:** フォルダー、送信者、日付、添付ファイル情報などのオプションで検索を絞り込みます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1410">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1411">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1411">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1412">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1412">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="d08ce-1413">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1413">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="d08ce-1414">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1414">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="d08ce-1415">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1415">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="d08ce-1416">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1416">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1417">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1417">Word</span></span>

- <span data-ttu-id="d08ce-1418">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1418">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1421">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1421">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1422">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1422">Excel</span></span>
- <span data-ttu-id="d08ce-1423">ユーザーがマージされた列を削除したときのパフォーマンス時間が向上する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1423">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="d08ce-1424">使用可能なプリンターのリストでプリンター名が重複する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1424">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1425">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1425">PowerPoint</span></span>
- <span data-ttu-id="d08ce-1426">英語スイス (QWERTZ) キーボードを使用すると、キーボード ショートカットとスペル チェックが期待どおりに機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1426">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1427">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1427">Word</span></span>
- <span data-ttu-id="d08ce-1428">空白のドキュメントに新しいコメントを追加しても何も発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1428">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="d08ce-1429">100 個を超えるエントリを含むドキュメントにインデックスを挿入または更新すると、アプリケーションがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1429">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="d08ce-1430">カスタム xml 値を含むファイルを開くのが非常に遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1430">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1431">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1431">Office Suite</span></span>
- <span data-ttu-id="d08ce-1432">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1432">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-08"></a><span data-ttu-id="d08ce-1435">バージョン 2006: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1435">Version 2006: May 08</span></span>
<span data-ttu-id="d08ce-1436">*バージョン 2006 (ビルド 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1436">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1438">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1438">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1439">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1439">Excel</span></span>

- <span data-ttu-id="d08ce-1440">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1440">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1441">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1441">Outlook</span></span>

- <span data-ttu-id="d08ce-1442">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1442">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="d08ce-1443">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1443">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="d08ce-1444">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1444">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1445">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1445">PowerPoint</span></span>

- <span data-ttu-id="d08ce-p173">**アニメーション GIF を使用してストーリーを伝える:** Office エディターでアニメーション GIF がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになります。[詳細については、こちらを参照してください](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="d08ce-p173">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier. [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1448">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1448">Word</span></span>

- <span data-ttu-id="d08ce-1449">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1449">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1452">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1452">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="d08ce-1453">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1453">Office Suite</span></span>

- <span data-ttu-id="d08ce-1454">OS のシャットダウン後、InTune を介した Office 365 ProPlus の展開が停止する問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1454">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-01"></a><span data-ttu-id="d08ce-1456">バージョン 2005: 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1456">Version 2005: May 01</span></span>
<span data-ttu-id="d08ce-1457">*バージョン 2005 (ビルド 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1457">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1459">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1459">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1460">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1460">Outlook</span></span>

- <span data-ttu-id="d08ce-1461">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1461">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="d08ce-1462">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1462">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="d08ce-1463">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1463">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1466">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1466">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1467">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1467">Excel</span></span>

- <span data-ttu-id="d08ce-1468">グラフのデータ テーブルの日付軸の値が正しく表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1468">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="d08ce-1469">[ページ レイアウト] または [改ページ プレビュー] に移動した後に、改ページを無効にできなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1469">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="d08ce-1470">系列のデータを含む列を非表示にしてから非表示を解除すると、グラフの線のスタイルが失われる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1470">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="d08ce-1471">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1471">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="d08ce-1472">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1472">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="d08ce-1473">[Invert if negative]\(負の値を反転する\) オプションが有効になっていると、ピボット グラフのカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1473">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="d08ce-1474">[Invert if negative]\(負の値を反転する\) オプションが選択されていると、ピボット グラフの単一のデータ ポイントに対するカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1474">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="d08ce-1475">この変更により、CSV ファイルで "@" 文字をアップロードすると、その "@" 文字以降の文字列が数式に変換される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1475">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="d08ce-1476">SEQUENCE 関数で小数点以下が正しく四捨五入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1476">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1477">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1477">Outlook</span></span>

- <span data-ttu-id="d08ce-1478">Outlook デスクトップ クライアントで、ユーザーがクリックした非常に長いセーフリンクが、切り捨てにより読み込みに失敗する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1478">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="d08ce-1479">DBCS (2 バイト文字セット) 文字を含む名前が付けられた Outlook フォルダーが、サーバーと同期するときに断続的に表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1479">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="d08ce-1480">この問題が発生する場合は、Outlook を IMAP アカウントを使用して構成し、ロケールが日本語に設定されたシステム上で実行する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1480">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1481">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1482">ユーザーがコメントを作成したのに投稿せずにそのコメント ウィンドウを閉じ、新しいウィンドウを開いて、複数のスライドを移動してからそのウィンドウを閉じ、最後に、元のプレゼンテーションでコメント ウィンドウをもう一度開くと、下書きのコメントが利用できなくなっている問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1482">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1483">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1483">Project</span></span>

- <span data-ttu-id="d08ce-1484">Project が Project Web App に接続されていて、小数点の記号がカンマの場合、タイム ラグを追加する際に TaskDependencies Add メソッドが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1484">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1485">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1485">Word</span></span>

- <span data-ttu-id="d08ce-1486">コラボレーション モードのドキュメントにコメントを挿入しても正常に動作しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1486">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="d08ce-1487">この変更により、@メンションがクリックされると連絡先カードが点滅する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1487">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="d08ce-p176">下書きのコメントを含むドキュメントを閉じようとすると、その下書きのコメントを保存せずにドキュメントを閉じてもよいかユーザーに確認を求める問題が修正されました。このプロンプトをキャンセルすると、ドキュメントが開いたままになるのではなく、閉じられていました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p176">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments. Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="d08ce-1490">投稿されたコメントを翻訳しようとすると、"Inserting translated text failed" (翻訳されたテキストの挿入に失敗しました) エラーが発生してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1490">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="d08ce-p177">Web ビュー/イマーシブ リーダーでヒントをクリックすると、ヒントが既に表示されている場合でも一番上までスクロールしていました。この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p177">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view. This has been fixed.</span></span>
- <span data-ttu-id="d08ce-1493">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても WRO0004.docx というファイル名で保存されるため、そのドキュメントを使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1493">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-24"></a><span data-ttu-id="d08ce-1495">バージョン 2005: 4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1495">Version 2005: April 24</span></span>
<span data-ttu-id="d08ce-1496">*バージョン 2005 (ビルド 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1496">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1498">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1498">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1499">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1499">Excel</span></span>
- <span data-ttu-id="d08ce-1500">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1500">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="d08ce-1501">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1501">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1502">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1502">Outlook</span></span>
- <span data-ttu-id="d08ce-1503">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1503">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="d08ce-1504">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1504">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1505">PowerPoint</span></span>
- <span data-ttu-id="d08ce-1506">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1506">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1507">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1507">Word</span></span>
- <span data-ttu-id="d08ce-p178">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p178">Enabling the option "Show bookmarks" would not display bookmarks. This has been fixed.</span></span>
- <span data-ttu-id="d08ce-1510">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1510">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-17"></a><span data-ttu-id="d08ce-1512">バージョン 2005: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1512">Version 2005: April 17</span></span>
<span data-ttu-id="d08ce-1513">*バージョン 2005 (ビルド 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1513">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1515">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1515">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1516">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1516">Excel</span></span>
- <span data-ttu-id="d08ce-1517">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1517">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="d08ce-1518">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1518">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="d08ce-1519">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1519">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="d08ce-1520">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1520">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="d08ce-1521">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1521">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="d08ce-1522">OneNote</span><span class="sxs-lookup"><span data-stu-id="d08ce-1522">OneNote</span></span>
- <span data-ttu-id="d08ce-1523">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1523">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1524">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1524">Outlook</span></span>
- <span data-ttu-id="d08ce-1525">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1525">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="d08ce-1526">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1526">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="d08ce-1527">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1527">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="d08ce-1528">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1528">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="d08ce-1529">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1529">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="d08ce-1530">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1530">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1531">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1531">Project</span></span>
- <span data-ttu-id="d08ce-1532">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1532">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="d08ce-1533">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1533">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="d08ce-1534">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1534">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2004-april-10"></a><span data-ttu-id="d08ce-1536">バージョン 2004: 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1536">Version 2004: April 10</span></span>
<span data-ttu-id="d08ce-1537">*バージョン 2004 (ビルド 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1537">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1539">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1539">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-1540">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1540">Access</span></span>

- <span data-ttu-id="d08ce-1541">**[テーブルの表示] ダイアログ ボックスをバイパスし、作業ウィンドウに直接移動して、テーブルを効率よくリレーションシップやクエリに追加します。:** 4 つのタブをクリックして、名前を複数選択して、テキストで検索し、作業中に開いたままの作業ウィンドウからドラッグして、テーブルやクエリを追加 ます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1541">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1542">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1542">Excel</span></span>

- <span data-ttu-id="d08ce-1543">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1543">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="d08ce-1544">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="d08ce-1544">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1545">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1545">Outlook</span></span>

- <span data-ttu-id="d08ce-1546">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1546">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="d08ce-1547">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="d08ce-1547">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="d08ce-1548">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1548">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1549">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1549">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1550">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1550">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="d08ce-1551">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="d08ce-1551">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="d08ce-1552">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1552">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1553">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1553">Word</span></span>

- <span data-ttu-id="d08ce-1554">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1554">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="d08ce-1555">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="d08ce-1555">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="d08ce-1556">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1556">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="d08ce-1557">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1557">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1560">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1560">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-1561">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1561">Access</span></span>

- <span data-ttu-id="d08ce-1562">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1562">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1563">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1563">Excel</span></span>

- <span data-ttu-id="d08ce-1564">シートのセル範囲を選択すると、1 つのセルが選択されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1564">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="d08ce-1565">X 軸の範囲に合わせてグラフのサイズを小さくすると、Excel が応答を停止する可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1565">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="d08ce-1566">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1566">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="d08ce-1567">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1567">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="d08ce-1568">R1C1 セルの参照が有効になっている Excel シートが共同編集/共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動すると、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1568">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1569">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1569">Outlook</span></span>

- <span data-ttu-id="d08ce-1570">メール メッセージからカテゴリが消えることがあるという問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1570">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="d08ce-1571">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1571">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="d08ce-1572">ユーザーが組織フォームのプロパティを表示とするときにクラッシュするという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1572">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="d08ce-1573">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが発生しないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1573">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1574">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1574">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1575">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1575">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="d08ce-1576">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1576">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="d08ce-1577">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1577">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1578">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1578">Project</span></span>

- <span data-ttu-id="d08ce-1579">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1579">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1580">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1580">Word</span></span>

- <span data-ttu-id="d08ce-1581">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1581">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="d08ce-1582">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1582">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="d08ce-1583">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1583">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="d08ce-1584">この変更により、コメントを作成するとき、コメント アンカーが表示されない場合があるという 2 ページ表示の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1584">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="d08ce-1585">スタイルがリストにリンクされている祖先のスタイルである段落の場合、そのリストの番号が失われる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1585">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-27"></a><span data-ttu-id="d08ce-1587">バージョン 2004: 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1587">Version 2004: March 27</span></span>
<span data-ttu-id="d08ce-1588">*バージョン 2004 (ビルド 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1588">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1590">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1590">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1591">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1591">Outlook</span></span>

- <span data-ttu-id="d08ce-1592">**メール作成時の @ メンションの候補表示を無効にするオプションが追加されました。** メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="d08ce-1592">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="d08ce-1593">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1593">Now you can turn it off if you prefer.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1596">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1596">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1597">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1597">Outlook</span></span>
- <span data-ttu-id="d08ce-1598">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1598">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="d08ce-1599">ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1599">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="d08ce-1600">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1600">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1601">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1601">PowerPoint</span></span>
- <span data-ttu-id="d08ce-1602">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1602">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1603">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1603">Project</span></span>
- <span data-ttu-id="d08ce-1604">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1604">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1605">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1605">Word</span></span>
- <span data-ttu-id="d08ce-1606">この変更により、 [表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1606">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-20"></a><span data-ttu-id="d08ce-1608">バージョン 2004: 3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1608">Version 2004: March 20</span></span>
<span data-ttu-id="d08ce-1609">*バージョン 2004 (ビルド 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1609">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1611">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1611">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1612">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1612">Outlook</span></span>

- <span data-ttu-id="d08ce-1613">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="d08ce-1613">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="d08ce-1614">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1614">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="d08ce-1615">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1615">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1616">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1616">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1617">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1617">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1620">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1620">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1621">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1621">Excel</span></span>

- <span data-ttu-id="d08ce-1622">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1622">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1623">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1623">Outlook</span></span>

- <span data-ttu-id="d08ce-1624">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1624">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="d08ce-1625">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1625">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="d08ce-1626">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1626">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="d08ce-1627">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1627">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="d08ce-1628">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1628">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1629">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1629">Project</span></span>

- <span data-ttu-id="d08ce-1630">ユーザーがスケジュール グループ内の [タスク] リボンにある「無効化」ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Applications (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1630">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="d08ce-1631">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1631">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="d08ce-1632">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1632">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="d08ce-1633">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1633">This behavior has been fixed.</span></span>

- <span data-ttu-id="d08ce-1634">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1634">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="d08ce-1635">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1635">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="d08ce-1636">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1636">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="d08ce-1637">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1637">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="d08ce-1638">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1638">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1639">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1639">Word</span></span>

- <span data-ttu-id="d08ce-1640">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1640">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="d08ce-1641">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1641">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="d08ce-1642">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1642">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="d08ce-1643">この変更により、文書に記載されていない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1643">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="d08ce-1644">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1644">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-13"></a><span data-ttu-id="d08ce-1646">バージョン 2004: 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1646">Version 2004: March 13</span></span>
<span data-ttu-id="d08ce-1647">*バージョン 2004 (ビルド 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1647">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1649">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1649">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1650">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1650">Excel</span></span>
- <span data-ttu-id="d08ce-1651">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1651">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="d08ce-1652">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1652">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1653">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1653">PowerPoint</span></span>
- <span data-ttu-id="d08ce-1654">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1654">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="d08ce-1655">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1655">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="d08ce-1656">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1656">Word</span></span>
- <span data-ttu-id="d08ce-1657">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1657">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="d08ce-1658">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1658">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1661">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1661">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="d08ce-1662">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1662">Access</span></span>
- <span data-ttu-id="d08ce-1663">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1663">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1664">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1664">Excel</span></span>
- <span data-ttu-id="d08ce-1665">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1665">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="d08ce-1666">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1666">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1667">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1667">Outlook</span></span>
- <span data-ttu-id="d08ce-1668">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1668">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="d08ce-1669">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1669">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="d08ce-1670">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1670">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="d08ce-1671">Project</span><span class="sxs-lookup"><span data-stu-id="d08ce-1671">Project</span></span>
- <span data-ttu-id="d08ce-1672">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1672">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="d08ce-1673">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1673">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1674">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1674">Word</span></span>
- <span data-ttu-id="d08ce-1675">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1675">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="d08ce-1676">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1676">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="d08ce-1677">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1677">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="d08ce-1678">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1678">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-06"></a><span data-ttu-id="d08ce-1680">バージョン 2003: 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1680">Version 2003: March 06</span></span>
<span data-ttu-id="d08ce-1681">*バージョン 2003 (ビルド 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1681">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1683">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1683">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1684">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1684">Outlook</span></span>

- <span data-ttu-id="d08ce-1685">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1685">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="d08ce-1686">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1686">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="d08ce-1687">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1687">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1688">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1688">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1689">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1689">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="d08ce-1690">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1690">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1691">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1691">Word</span></span>

- <span data-ttu-id="d08ce-1692">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1692">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1693">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1693">Office Suite</span></span>

- <span data-ttu-id="d08ce-1694">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1694">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="d08ce-1695">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1695">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2003-february-28"></a><span data-ttu-id="d08ce-1698">バージョン 2003: 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1698">Version 2003: February 28</span></span>
<span data-ttu-id="d08ce-1699">*バージョン 2003 (ビルド 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1699">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1701">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1701">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1702">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1702">Outlook</span></span>

- <span data-ttu-id="d08ce-1703">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1703">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="d08ce-1704">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1704">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1705">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1705">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1706">**インクを図形に変換する作図エクスペリエンスの向上:** より良い図を描いて変換し、Office オブジェクトを操作できるようにします。[詳細情報](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="d08ce-1706">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1709">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1709">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d08ce-1710">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1710">Excel</span></span>

- <span data-ttu-id="d08ce-1711">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1711">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1712">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1712">Outlook</span></span>

- <span data-ttu-id="d08ce-1713">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1713">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1714">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1714">Word</span></span>

- <span data-ttu-id="d08ce-1715">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1715">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="d08ce-1716">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1716">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="d08ce-1717">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1717">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1718">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1718">Office Suite</span></span>

- <span data-ttu-id="d08ce-1719">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1719">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-21"></a><span data-ttu-id="d08ce-1721">バージョン 2003: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1721">Version 2003: February 21</span></span>
<span data-ttu-id="d08ce-1722">*バージョン 2003 (ビルド 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1722">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1724">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1724">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="d08ce-1725">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1725">Office Suite</span></span>

- <span data-ttu-id="d08ce-1726">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキスト ハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1726">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1729">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1729">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1730">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1730">Excel</span></span>
- <span data-ttu-id="d08ce-1731">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1731">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="d08ce-1732">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1732">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="d08ce-1733">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1733">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="d08ce-1734">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1734">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="d08ce-1735">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1735">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1736">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1736">Outlook</span></span>
- <span data-ttu-id="d08ce-1737">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1737">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="d08ce-1738">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1738">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="d08ce-1739">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1739">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1740">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1740">Word</span></span>
- <span data-ttu-id="d08ce-1741">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1741">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="d08ce-p192">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p192">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag. This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1744">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1744">Office Suite</span></span>
- <span data-ttu-id="d08ce-1745">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1745">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="d08ce-1746">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1746">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="d08ce-1747">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1747">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-14"></a><span data-ttu-id="d08ce-1749">バージョン 2003: 2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1749">Version 2003: February 14</span></span>
<span data-ttu-id="d08ce-1750">*バージョン 2003 (ビルド 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1750">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1752">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1752">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1753">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1753">Outlook</span></span>

- <span data-ttu-id="d08ce-1754">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="d08ce-1754">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="d08ce-1755">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1755">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1756">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1756">Word</span></span>

- <span data-ttu-id="d08ce-1757">**描画ツールボックスでインク エディターを見つける**: [描画] を選択し、[インク エディター] ペンを選択して、指またはデジタル ペンでドキュメントを編集します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1757">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="d08ce-1758">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d08ce-1758">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="d08ce-1759">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1759">Office Suite</span></span>

- <span data-ttu-id="d08ce-1760">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました</span><span class="sxs-lookup"><span data-stu-id="d08ce-1760">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1763">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1763">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="d08ce-1764">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1764">Outlook</span></span>

- <span data-ttu-id="d08ce-1765">ユーザーが「空き時間情報オプション」予定表のアクセス許可ダイアログにアクセスできなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1765">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="d08ce-1766">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「申し訳ございません、このアイテムを開くことができません」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1766">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="d08ce-1767">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1767">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="d08ce-1768">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1768">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1769">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1769">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1770">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1770">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1771">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1771">Word</span></span>

- <span data-ttu-id="d08ce-1772">ドキュメントを PDF にエクスポートすると、画像の透明性が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1772">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-07"></a><span data-ttu-id="d08ce-1774">バージョン 2002: 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="d08ce-1774">Version 2002: February 07</span></span>
<span data-ttu-id="d08ce-1775">*バージョン 2002 (ビルド 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="d08ce-1775">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d08ce-1777">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d08ce-1777">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-1778">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1778">Access</span></span>

- <span data-ttu-id="d08ce-1779">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1779">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="d08ce-1780">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1780">Search and replace text in SQL View.</span></span> <span data-ttu-id="d08ce-1781">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1781">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d08ce-1784">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d08ce-1784">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d08ce-1785">Access</span><span class="sxs-lookup"><span data-stu-id="d08ce-1785">Access</span></span>

- <span data-ttu-id="d08ce-p197">この更新は、ADODB を使用する問題を修正します。 VB コードのレコーダー オブジェクトでエラーが誤って報告される場合があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-p197">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="d08ce-1788">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1788">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="d08ce-1789">Excel</span><span class="sxs-lookup"><span data-stu-id="d08ce-1789">Excel</span></span>

- <span data-ttu-id="d08ce-1790">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1790">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="d08ce-1791">Outlook</span><span class="sxs-lookup"><span data-stu-id="d08ce-1791">Outlook</span></span>

- <span data-ttu-id="d08ce-1792">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1792">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="d08ce-1793">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1793">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d08ce-1794">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d08ce-1794">PowerPoint</span></span>

- <span data-ttu-id="d08ce-1795">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1795">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="d08ce-1796">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1796">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="d08ce-1797">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1797">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="d08ce-1798">Word</span><span class="sxs-lookup"><span data-stu-id="d08ce-1798">Word</span></span>

- <span data-ttu-id="d08ce-1799">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1799">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="d08ce-1800">ドキュメントが共同編集されている場合、ルート コメントのドラフト バージョンが保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1800">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="d08ce-1801">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1801">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="d08ce-1802">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1802">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="d08ce-1803">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1803">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="d08ce-1804">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1804">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="d08ce-1805">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d08ce-1805">Office Suite</span></span>

- <span data-ttu-id="d08ce-1806">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="d08ce-1806">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|DevMain|Insiders| |16.0.14204.20006|version-2107-june-11|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14131.20008|version-2106-june-04|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14122.20004|version-2106-may-28|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14117.20000|version-2106-may-21|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14107.20000|version-2106-may-14|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14029.20000|version-2106-may-07|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14026.20000|version-2105-april-30|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14014.20002|version-2105-april-23|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14007.20002|version-2105-april-16|)
[//]: # (|Win32|DevMain|Insiders| |16.0.14002.20000|version-2105-april-09|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
