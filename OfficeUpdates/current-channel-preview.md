---
title: リリース ノートの最新チャネル (プレビュー)
ms.author: anankani
author: v-lislo
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Slow の対象ユーザーに新機能、修正プログラム、または既知の問題の最新リストを提供します
ms.openlocfilehash: 64fa879f8279057f7e768c6743568516cb8046dc
ms.sourcegitcommit: d7b61837c922993e563c83df547d865c6715517b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/12/2021
ms.locfileid: "50741640"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="2f120-103">Office 向けリリース ノートの最新チャネル (プレビュー)</span><span class="sxs-lookup"><span data-stu-id="2f120-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="2f120-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project、Teams の最新チャネル (プレビュー版) ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="2f120-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="2f120-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="2f120-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="2f120-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって最新チャネル (プレビュー) に展開されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="2f120-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="2f120-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="2f120-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="2f120-109">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="2f120-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="2f120-110">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2f120-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="2f120-111">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-111">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="2f120-112">Microsoft Teams の機能は、リリース頻度が高いため、最新チャネル プレビュー版とは異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-112">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (削除しないでください)

## <a name="version-2103-march-11"></a><span data-ttu-id="2f120-114">バージョン 2103: 3 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2f120-114">Version 2103: March 11</span></span>
<span data-ttu-id="2f120-115">*バージョン 2103 (ビルド 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="2f120-115">*Version 2103 (Build 13901.20148)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-117">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-117">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-118">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-118">Excel</span></span>

- <span data-ttu-id="2f120-119">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="2f120-119">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="2f120-120">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-120">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="2f120-121">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="2f120-121">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-122">Outlook</span></span>

- <span data-ttu-id="2f120-123">**会議室とワークスペースの新しい予約機能:** 会議室の予約機能が更新され、個々のワークスペースをスケジュールできる機能が追加されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-123">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-124">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-124">PowerPoint</span></span>

- <span data-ttu-id="2f120-125">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="2f120-125">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="2f120-126">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-126">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="2f120-127">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="2f120-127">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="visio"></a><span data-ttu-id="2f120-128">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-128">Visio</span></span>

- <span data-ttu-id="2f120-129">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、製品のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="2f120-129">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="2f120-130">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-130">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="2f120-131">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-131">Word</span></span>

- <span data-ttu-id="2f120-132">**Word 文書のダーク モード:** ダーク モードは、ドキュメントでの作業中に目の疲れを軽減し、光感受性に対応するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2f120-132">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="2f120-133">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="2f120-133">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="2f120-134">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-134">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="2f120-135">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="2f120-135">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-138">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-138">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-139">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-139">Access</span></span>

- <span data-ttu-id="2f120-140">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-140">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2f120-141">外部アプリケーションがアクセシビリティ インターフェイスを要求した場合、そのインターフェイスが参照を解放するまでシャットダウンできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-141">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="2f120-142">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-142">Excel</span></span>

- <span data-ttu-id="2f120-143">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-143">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2f120-144">画像を取得できないためにデータ型カードを表示しようとすると、Excel が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-144">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="2f120-145">日本語フォントで乗算または除算記号を使用すると、フォントが予期せず変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-145">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="2f120-146">文字をサポートしている場合は、引き続き同じフォントを使用します。</span><span class="sxs-lookup"><span data-stu-id="2f120-146">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="2f120-147">ユーザーが Excel ブックを PDF にエクスポートできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-147">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="2f120-148">[リンクされた画像を貼り付け] オプションを使用すると、画像が予想よりも小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-148">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="2f120-149">共同編集中にシートをコピーした際、一部の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-149">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="2f120-150">ブックを開いたときに予期せずメモが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-150">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="2f120-151">.xls または .xlt 形式で保存するときに、一部のピボットテーブル形式でブックが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-151">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-152">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-152">Outlook</span></span>

- <span data-ttu-id="2f120-153">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-153">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2f120-154">新しいグループを作成した後、重複する予定表のグループが表示される原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-154">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="2f120-155">改善された共有カレンダーのユーザーが、カレンダーの色を黄色または茶色に設定できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-155">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="2f120-156">Outlook を再起動するまで、新しく追加された予定表がナビゲーション ウィンドウに表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-156">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="2f120-157">CSV にエクスポートするときに非 ASCII 文字が正しくエクスポートされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-157">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="2f120-158">一部のユーザーがセカンダリ メール アカウントに関連付けられた署名にアクセスできなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-158">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="2f120-159">新しいデバイスで Outlook を構成した後、クラウド設定機能のユーザーにカスタマイズされた設定が既定の設定で上書きされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-159">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="2f120-160">Unicode コンテンツを含む署名が破損するのをユーザーに表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-160">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="2f120-161">インライン翻訳のユーザーがフィードバックを送信できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-161">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="2f120-162">DRM 保護を削除すると、添付ファイルが重複するる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-162">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="2f120-163">メールを作成するときに、ユーザーが [名前の確認] で連絡先グループを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-163">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-164">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-164">PowerPoint</span></span>

- <span data-ttu-id="2f120-165">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-165">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2f120-166">PowerPoint スライドショー モードで折れ線グラフの矢印が期待どおりに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-166">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="2f120-167">アニメーションおよびオーディオ ブックマークのループの問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="2f120-167">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-168">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-168">Project</span></span>

- <span data-ttu-id="2f120-169">終了時に Visio が動作を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-169">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="2f120-170">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-170">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2f120-171">100% 完了したタスクが 99% 完了に戻る問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-171">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="2f120-172">JAWS を実行しているときにタスク情報ダイアログに移動すると、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-172">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="2f120-173">インジケーター列が最初の列スポットにない場合、「サマリー タスクを切り取ると、サブタスクも削除されます」という警告が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-173">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="2f120-174">ユーザーがタイムシートで [タスクに自分自身を追加] 機能を選択した場合に、作成された割り当てで適切なリソース利用可能時間の単位が使用されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-174">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="2f120-175">Project Web App からローカル ファイルにプロジェクトを保存するときに、タスクの分割が誤って作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-175">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="2f120-176">これは、非標準の作業時間のタスク カレンダーが使用されていた場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="2f120-176">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="2f120-177">Publisher</span><span class="sxs-lookup"><span data-stu-id="2f120-177">Publisher</span></span>

- <span data-ttu-id="2f120-178">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-178">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="2f120-179">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-179">Visio</span></span>

- <span data-ttu-id="2f120-180">終了時に Visio が動作を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-180">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="2f120-181">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-181">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-182">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-182">Word</span></span>

- <span data-ttu-id="2f120-183">Microsoft Information Protection (MIP) ラベルで保護されたファイルを開くとき、MIP で保護されたラベルにアクセスできる ID にユーザーがサインインしていない場合、無期限にハングする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-183">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="2f120-184">ユーザーは、サインイン プロンプトを表示するためにオープンをキャンセルする必要があり、オープンはその時点以降にのみ成功します。</span><span class="sxs-lookup"><span data-stu-id="2f120-184">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="2f120-185">開く/ダウンロード中にサインイン プロンプトを表示できるようにすることで、この問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-185">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="2f120-186">外部ドライブを取り外すときに予期せずアプリが閉じる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-186">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="2f120-187">新しい単語コメントでディクテーションを使用する際の問題を修正しました。コメント カードのディクテーション ボタンが正しくオンとオフを切り替えるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-187">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="2f120-188">ドキュメントの共同編集時に、コメント順序が変更されてもアクティブな下書きがクリアされません。</span><span class="sxs-lookup"><span data-stu-id="2f120-188">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="2f120-189">ユーザーがドキュメントにディクテーションしたときに単語の間にスペースが挿入されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-189">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="2f120-190">スクロールまたはズーム アニメーションを含むスクロール レイヤーに関連するレンダリング パイプラインの問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-190">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="2f120-191">3D 効果のあるアイコンと SVG グラフィックに適用される色の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-191">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="2f120-192">自動保存の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-192">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="2f120-193">脚注の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-193">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="2f120-194">RTL で入力された複数行のコメントを投稿すると、2 行目以降が右ではなく左に配置される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-194">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="2f120-195">複数のコメントの配置に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-195">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="2f120-196">[音声読み上げ] 作業ウィンドウの、キーボード ショートカットの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-196">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="2f120-197">段落をスキップする可能性があるナレーターの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-197">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="2f120-198">スペル チェックが 2 つの異なるスペル修正コンテキスト メニュー間で切り替わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-198">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="2f120-199">リッチ テキスト コンテンツ コントロールの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-199">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="2f120-200">非表示の段落の最後に入力すると、アプリケーションがハングする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-200">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="2f120-201">列のテキストが重複する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-201">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="2f120-202">ブックマークに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-202">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="2f120-203">共同編集中の競合を解決する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-203">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-204">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-204">Office Suite</span></span>

- <span data-ttu-id="2f120-205">OneDrive の場所は、グループ ポリシー設定に応じて適切にフィルター処理されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-205">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="2f120-206">数式を含むテキスト内でナレーターを使用すると発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-206">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="2f120-207">セッション 0 で実行されている Office アプリのサポートに関連する信頼性の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-207">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="2f120-208">セッション 0 で実行されている Office アプリのサポートに関連する信頼性の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-208">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="2f120-209">EMF 画像の読み込み時に発生する可能性がある無応答に関連した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-209">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-march-03"></a><span data-ttu-id="2f120-211">バージョン 2102: 3 月 3 日</span><span class="sxs-lookup"><span data-stu-id="2f120-211">Version 2102: March 03</span></span>
<span data-ttu-id="2f120-212">*バージョン 2102 (ビルド 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="2f120-212">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-214">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-214">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="2f120-215">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-215">Word</span></span>

- <span data-ttu-id="2f120-216">アイコンと SVG グラフィックに適用されるテーマ情報の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-216">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-march-01"></a><span data-ttu-id="2f120-218">バージョン 2102: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2f120-218">Version 2102: March 01</span></span>
<span data-ttu-id="2f120-219">*バージョン 2102 (ビルド 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="2f120-219">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-221">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-221">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-222">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-222">Outlook</span></span>

- <span data-ttu-id="2f120-223">**Teams で共有:** Outlook からのメッセージを Teams 内のユーザーまたはチャネルと共有します。</span><span class="sxs-lookup"><span data-stu-id="2f120-223">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-226">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-226">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-227">Outlook</span></span>

- <span data-ttu-id="2f120-228">新しいグループを作成した後、重複する予定表のグループが表示される原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-228">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="2f120-229">改善された共有カレンダーのユーザーが、カレンダーの色を黄色または茶色に設定できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-229">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="2f120-230">一部のユーザーがメッセージ ウィンドウを閉じるときにアプリがシャットダウンする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-230">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="2f120-231">Unicode コンテンツを含む署名が破損するのをユーザーに表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-231">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="2f120-232">インライン翻訳のユーザーがフィードバックを送信できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-232">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-february-21"></a><span data-ttu-id="2f120-234">バージョン 2102: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2f120-234">Version 2102: February 21</span></span>
<span data-ttu-id="2f120-235">*バージョン 2102 (ビルド 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="2f120-235">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-237">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-237">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-238">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-238">Outlook</span></span>

- <span data-ttu-id="2f120-239">**音声でメッセージの下書きを作成する:** 新しいディクテーション ツールバー、音声コマンド、自動句読点などを使用してメッセージを作成します。</span><span class="sxs-lookup"><span data-stu-id="2f120-239">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-240">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-240">Word</span></span>

- <span data-ttu-id="2f120-241">**音声で文書の下書きを作成する:** 新しいディクテーション ツールバー、音声コマンド、自動句読点を使用して文書の下書きを作成します。</span><span class="sxs-lookup"><span data-stu-id="2f120-241">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-244">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-244">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-245">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-245">Excel</span></span>

- <span data-ttu-id="2f120-246">[リンク画像を貼り付け] オプションを使用すると、画像が思っていたよりも小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-246">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-february-16"></a><span data-ttu-id="2f120-248">バージョン 2102: 2 月 16 日</span><span class="sxs-lookup"><span data-stu-id="2f120-248">Version 2102: February 16</span></span>
<span data-ttu-id="2f120-249">*バージョン 2102 (ビルド 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="2f120-249">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="2f120-250">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-250">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="2f120-251">バージョン 2102: 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2f120-251">Version 2102: February 15</span></span>
<span data-ttu-id="2f120-252">*バージョン 2102 (ビルド 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="2f120-252">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-254">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-254">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-255">Outlook</span></span>

- <span data-ttu-id="2f120-256">**ディクテーションはより多くの言語で利用できます:** ディクテーションは 7 つの新しい言語をサポートするようになりました: ヒンディー語、ロシア語、ポーランド語、ポルトガル語 (ポルトガル)、韓国語、タイ語、中国語 (台湾)</span><span class="sxs-lookup"><span data-stu-id="2f120-256">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="2f120-257">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-257">Word</span></span>

- <span data-ttu-id="2f120-258">**ディクテーションはより多くの言語で利用できます:** ディクテーションは 7 つの新しい言語をサポートするようになりました: ヒンディー語、ロシア語、ポーランド語、ポルトガル語 (ポルトガル)、韓国語、タイ語、中国語 (台湾)</span><span class="sxs-lookup"><span data-stu-id="2f120-258">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-261">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-261">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-262">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-262">Excel</span></span>

- <span data-ttu-id="2f120-263">ユーザーが Excel ブックを PDF にエクスポートできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-263">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-264">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-264">Word</span></span>

- <span data-ttu-id="2f120-265">共同編集中の競合を解決する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-265">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2102-february-11"></a><span data-ttu-id="2f120-267">バージョン 2102: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2f120-267">Version 2102: February 11</span></span>
<span data-ttu-id="2f120-268">*バージョン 2102 (ビルド 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="2f120-268">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-270">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-270">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2f120-271">Teams</span><span class="sxs-lookup"><span data-stu-id="2f120-271">Teams</span></span>

- <span data-ttu-id="2f120-272">**Windows および Mac の Edge および Chrome ブラウザーの 2x2 ビデオ** ユーザーは、Windows および Mac の Edge および Chrome ブラウザーでのチーム会議において、最大 4 人の参加者のビデオを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-272">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="2f120-273">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-273">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="2f120-275">バージョン 2102: 2 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2f120-275">Version 2102: February 08</span></span>
<span data-ttu-id="2f120-276">*バージョン 2102 (ビルド 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="2f120-276">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-278">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-278">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-279">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-279">Outlook</span></span>

- <span data-ttu-id="2f120-280">**Microsoft Search を利用した作成 (To\CC\BCC) の提案:** To\CC 行へのユーザーの追加は、Microsoft Search を利用するようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-280">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-283">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-283">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-284">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-284">Access</span></span>

- <span data-ttu-id="2f120-285">Access で選択したタブがよりはっきりと表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-285">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="2f120-286">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-286">Excel</span></span>

- <span data-ttu-id="2f120-287">ファイルを再度開いたときに、セルの連続していない範囲を使用する特定のグラフが読み込まれない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-287">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="2f120-288">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-288">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="2f120-289">グラフでデータ系列を選択した後に Excel が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-289">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="2f120-290">[名前の定義] ダイアログで名前を追加したときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-290">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="2f120-291">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-291">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-292">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-292">Outlook</span></span>

- <span data-ttu-id="2f120-293">デジタル署名のオプションのチェックを外した後も、メールがデジタル署名されたものとして送信される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-293">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="2f120-294">[暗号化のみ] オプションを使用して送信されたメールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-294">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-295">PowerPoint</span></span>

- <span data-ttu-id="2f120-296">色付きの絵文字を表示すると発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-296">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="2f120-297">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-297">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="2f120-298">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-298">Visio</span></span>

- <span data-ttu-id="2f120-299">CAD ステンシルからの形状レンダリングに関するこの問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-299">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="2f120-300">ユーザーには、最新のビルドで解決された問題が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-300">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-301">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-301">Word</span></span>

- <span data-ttu-id="2f120-302">これにより、インターネット接続が一定期間失われた後、リアルタイム入力とプレゼンスが復元されない問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-302">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="2f120-303">ユーザーがコメント内のテキストを選択すると、Word は他のコメント内の選択されたテキストの選択を解除するようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-303">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="2f120-304">Word でコメント テキストを Excel にコピーできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-304">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="2f120-305">VBA マクロ実行中に ExportAsFixedFormat2 が、"プレゼンテーション (不明のメンバー) の不正な値" というエラーを表示して失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-305">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="2f120-306">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-306">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="2f120-307">コメントがリンクで切り捨てられる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-307">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="2f120-308">SharePoint Online に保存する際に発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2f120-308">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="2f120-309">Word 文書を PDF にエクスポートする際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-309">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="2f120-310">自動バックアップの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-310">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="2f120-311">DRM で保護されたファイルを共同編集する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-311">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-312">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-312">Office Suite</span></span>

- <span data-ttu-id="2f120-313">画像として箇条書きを挿入すると箇条書きが消える PowerPoint のバグを修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-313">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="2f120-314">この修正により、レンダリングの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="2f120-314">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="2f120-315">あるサインイン アカウントの機密ラベルを表示する必要があるときに、特定の状況で Office が別のサインイン アカウントの機密ラベルを表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-315">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-february-03"></a><span data-ttu-id="2f120-317">バージョン 2101: 2 月 3 日</span><span class="sxs-lookup"><span data-stu-id="2f120-317">Version 2101: February 03</span></span>
<span data-ttu-id="2f120-318">*バージョン 2101 (ビルド 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="2f120-318">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-320">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-320">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-321">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-321">Outlook</span></span>

- <span data-ttu-id="2f120-322">OWA に既定の正しい署名が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-322">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="2f120-323">[暗号化のみ] オプションを使用して送信されたメールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-323">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-february-02"></a><span data-ttu-id="2f120-325">バージョン 2101: 2 月 2 日</span><span class="sxs-lookup"><span data-stu-id="2f120-325">Version 2101: February 02</span></span>
<span data-ttu-id="2f120-326">*バージョン 2101 (ビルド 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="2f120-326">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-328">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-328">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-329">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-329">Outlook</span></span>

- <span data-ttu-id="2f120-330">クラウド設定のユーザーが設定を更新するときにハングする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-330">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-25"></a><span data-ttu-id="2f120-332">バージョン 2101: 1 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2f120-332">Version 2101: January 25</span></span>
<span data-ttu-id="2f120-333">*バージョン 2101 (ビルド 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="2f120-333">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-335">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-335">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-336">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-336">Excel</span></span>

- <span data-ttu-id="2f120-337">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-337">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="2f120-338">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-338">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="2f120-339">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-339">Outlook</span></span>

- <span data-ttu-id="2f120-340">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-340">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="2f120-341">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-341">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="2f120-342">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-342">PowerPoint</span></span>

- <span data-ttu-id="2f120-343">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-343">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="2f120-344">[詳細情報](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2f120-344">[Learn more](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="2f120-345">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-345">Word</span></span>

- <span data-ttu-id="2f120-346">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-346">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="2f120-347">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-347">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="2f120-348">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-348">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-349">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-349">Outlook</span></span>

- <span data-ttu-id="2f120-350">プロファイルに大きな階層がある共有メールボックスまたは代理メールボックスを持つユーザーがハングする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-350">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



## <a name="version-2101-january-18"></a><span data-ttu-id="2f120-352">バージョン 2101: 1 月 18 日</span><span class="sxs-lookup"><span data-stu-id="2f120-352">Version 2101: January 18</span></span>
<span data-ttu-id="2f120-353">*バージョン 2101 (ビルド 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="2f120-353">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-357">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-357">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2f120-358">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-358">Project</span></span>

- <span data-ttu-id="2f120-359">チーム プランナー ビューのタスクに枠が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-359">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="2f120-360">チーム プランナー ビューのタスクでドラッグ アンド ドロップが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-360">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-13"></a><span data-ttu-id="2f120-362">バージョン 2101: 1 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2f120-362">Version 2101: January 13</span></span>
<span data-ttu-id="2f120-363">*バージョン 2101 (ビルド 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="2f120-363">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
### <a name="feature-updates"></a><span data-ttu-id="2f120-365">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-365">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="2f120-366">Teams</span><span class="sxs-lookup"><span data-stu-id="2f120-366">Teams</span></span>
- <span data-ttu-id="2f120-367">**その他のテーマ:** デスクトップと Web クライアントで新しいテーマを利用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-367">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="2f120-368">**PPT 共有:** Teams の発表者ツール Teams の共有トレイから PowerPoint ファイルを選択すると、発表者ツールが自動的に開きます。</span><span class="sxs-lookup"><span data-stu-id="2f120-368">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="2f120-369">簡単なアドホック スライド ナビゲーションのために、デッキ内すべてのスライドの現在のスライド、スライド ノート、サムネイル ストリップを表示できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-369">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="2f120-370">このビューは完全に背後で動作し、制御している発表者のみに表示されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-370">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="2f120-371">オーディエンスには、現在のスライド (大きな赤いボックスで強調表示)、またはオーディエンスが選択した移動先のスライド (オーディエンスのナビゲーションがお客様によってロックされていない場合) しか表示されません。</span><span class="sxs-lookup"><span data-stu-id="2f120-371">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="2f120-372">**Mac でデスクトップまたはウィンドウを共有する際に、コンピュータのサウンドを含める** Mac の Teams からデスクトップまたはウィンドウを共有するときに、コンピューターのサウンドを含めることができるようになりました。これにより、会議の参加者は、コンピューターから再生されるオーディオを聞くことができます。 </span><span class="sxs-lookup"><span data-stu-id="2f120-372">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="2f120-374">バージョン 2101: 1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2f120-374">Version 2101: January 09</span></span>
<span data-ttu-id="2f120-375">*バージョン 2101 (ビルド 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="2f120-375">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-377">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-377">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-378">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-378">Outlook</span></span>

- <span data-ttu-id="2f120-379">**ワンクリック ライティング候補:** ワンクリックでライティング候補を適用します。</span><span class="sxs-lookup"><span data-stu-id="2f120-379">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="2f120-380">編集機能では、スペルチェックと文章校正を行い、ユーザーに文章を洗練されたものにするアイデアを提供します。</span><span class="sxs-lookup"><span data-stu-id="2f120-380">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="2f120-381">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-381">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="2f120-382">[ブログの投稿](https://insider.office.com/ja-JP/blog/microsoft-editor-gets-an-upgrade)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-382">See details in [blog post](https://insider.office.com/ja-JP/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-385">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-385">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-386">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-386">Outlook</span></span>

- <span data-ttu-id="2f120-387">特定の検索シナリオで Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-387">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-07"></a><span data-ttu-id="2f120-389">バージョン 2101: 1 月 7 日</span><span class="sxs-lookup"><span data-stu-id="2f120-389">Version 2101: January 07</span></span>
<span data-ttu-id="2f120-390">*バージョン 2101 (ビルド 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="2f120-390">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-392">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-392">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-393">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-393">Excel</span></span>

- <span data-ttu-id="2f120-394">**複数のシートを同時に再表示する:** 一度に再表示できるのが、1枚のシートだけではなくなりました。一度に複数の非表示シートを表示します。</span><span class="sxs-lookup"><span data-stu-id="2f120-394">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="2f120-395">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-395">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="2f120-396">**改善された条件付き書式ダイアログ**: 条件付き書式ダイアログのサイズが変更可能になり、シングルクリックでルールを複製できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-396">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="2f120-397">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-397">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-400">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-400">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-401">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-401">Excel</span></span>

- <span data-ttu-id="2f120-402">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-402">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="2f120-403">Selection.Parent.Copy コールの後に区切り文字の切り替えに関連する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-403">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="2f120-404">ピボット テーブルに書式設定スタイルを適用するときのパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-404">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="2f120-405">Excel 4.0 マクロを含む Excel アドイン ファイルを開いたときにプロンプトが表示されずにマクロが無効のままになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-405">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="2f120-406">Excel からグラフをコピーして Word に貼り付けるときに、10 進数と桁区切りの記号の設定を継承するように更新しました</span><span class="sxs-lookup"><span data-stu-id="2f120-406">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="2f120-407">無効なファイル属性 (作成時刻、修正時刻など) を持つ UNC ファイルを開くと、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-407">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="2f120-408">STOCKHISTORY 関数を使用するときに、"リソース不足" のアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-408">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="2f120-409">PQ dll リストに FuzzyClustering dll を追加しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-409">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="2f120-410">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-410">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="2f120-411">PowerPoint での埋め込まれた Excel の範囲のプレビューでサイズが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-411">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="2f120-412">OneNote</span><span class="sxs-lookup"><span data-stu-id="2f120-412">OneNote</span></span>

- <span data-ttu-id="2f120-413">この変更により、OneNote に影響を与えるレンダリングの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-413">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-414">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-414">Outlook</span></span>

- <span data-ttu-id="2f120-415">Word から差し込み印刷を開始するときに、ユーザーがアクセスを許可する時間の長さを指定できず、ユーザーに対して余分なプロンプトが表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-415">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="2f120-416">この変更により、エンド ユーザーに対して Exchange Online アーカイブ メールボックスを表示しないようにする Exchange サーバーの設定を Outlook で利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2f120-416">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="2f120-417">引き換えベースのアドインのユーザーの Outlook が予期せず終了してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-417">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="2f120-418">ユーザーが検索対象のカテゴリを複数選ぶことができなかった原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-418">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="2f120-419">イベントが別の予定からコピーされたときに、一部の予定表アイテムの開始時刻が予期せず変更される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-419">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="2f120-420">送信時にプレーン テキストの S/MIME メッセージが正しく表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-420">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-421">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-421">PowerPoint</span></span>

- <span data-ttu-id="2f120-422">この変更により、図形の結合がテキストを操作するときに発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-422">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="2f120-423">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-423">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="2f120-424">この変更により、スライドショーでバックグラウンドビデオ再生がループする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-424">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="2f120-425">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-425">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-426">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-426">Project</span></span>

- <span data-ttu-id="2f120-427">リソースの最大単位数が、最新の最大単位数の更新を常に反映していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-427">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="2f120-428">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-428">Visio</span></span>

- <span data-ttu-id="2f120-429">最近の回帰を原因とする問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-429">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="2f120-430">この問題は解決されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-430">We have resolved the issue.</span></span> <span data-ttu-id="2f120-431">"Web ページとして保存" ダイアログは、ユーザーの入力に従って正しく生成されたフィールドを持つようになり、ユーザーはシームレスにファイルを Web ページとして保存することができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-431">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="2f120-432">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="2f120-432">This issue has been fixed.</span></span> <span data-ttu-id="2f120-433">PowerPoint や Word などの他の Office アプリケーションに Visio ファイルをオブジェクトとして埋め込み、これらのアプリケーション内からシームレスにアクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-433">You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-434">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-434">Word</span></span>

- <span data-ttu-id="2f120-435">sha512 以外のハッシュ設定を使用して共同作業セッションを開始すると、カスタム ハッシュ設定を持つコンピューターに問題が発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-435">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="2f120-436">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-436">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="2f120-437">@Mention を含むコメント投稿を編集するときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-437">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="2f120-438">最新のコメントをより信頼性の高いものにするために、問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-438">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="2f120-439">編集不可とマークされているコンテンツ コントロールでの最新のコメントの削除に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-439">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="2f120-440">コメント カードの下部に入力するときのアニメーションを修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-440">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="2f120-441">コメント カードの返信ボックスが画面に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-441">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="2f120-442">ページの上部にコメント カードが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-442">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="2f120-443">テキストが画面外にスクロールしてしまうことがあるコメントでのバグを修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-443">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="2f120-444">コメント ウィンドウ内のネストされたスクロール バーに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-444">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="2f120-445">新しい Word インスタンスを作成すると、コメントの下書きが消えます。</span><span class="sxs-lookup"><span data-stu-id="2f120-445">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="2f120-446">文書を隠し文字で PDF に保存する際に、Word が固まる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-446">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-january-04"></a><span data-ttu-id="2f120-448">バージョン 2012: 1 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2f120-448">Version 2012: January 04</span></span>
<span data-ttu-id="2f120-449">*バージョン 2012 (ビルド 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="2f120-449">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="2f120-450">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-450">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-452">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-452">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-453">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-453">Excel</span></span>

- <span data-ttu-id="2f120-454">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-454">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-455">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-455">PowerPoint</span></span>

- <span data-ttu-id="2f120-456">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-456">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-457">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-457">Word</span></span>

- <span data-ttu-id="2f120-458">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-458">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-28"></a><span data-ttu-id="2f120-460">バージョン 2012: 12 月 28 日</span><span class="sxs-lookup"><span data-stu-id="2f120-460">Version 2012: December 28</span></span>
<span data-ttu-id="2f120-461">*バージョン 2012 (ビルド 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="2f120-461">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-463">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-463">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-464">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-464">Outlook</span></span>

- <span data-ttu-id="2f120-465">一部のお客様の環境で、予定表の読み込み中にハングアップする原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-465">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-21"></a><span data-ttu-id="2f120-467">バージョン 2012: 12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2f120-467">Version 2012: December 21</span></span>
<span data-ttu-id="2f120-468">*バージョン 2012 (ビルド 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="2f120-468">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-470">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-470">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-471">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-471">Excel</span></span>

- <span data-ttu-id="2f120-472">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="2f120-472">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="2f120-473">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="2f120-473">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-474">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-474">Outlook</span></span>

- <span data-ttu-id="2f120-475">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分遅く会議を開始するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-475">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="2f120-476">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-476">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="2f120-477">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="2f120-477">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="2f120-478">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="2f120-478">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-479">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-479">PowerPoint</span></span>

- <span data-ttu-id="2f120-480">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="2f120-480">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="2f120-481">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="2f120-481">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-482">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-482">Word</span></span>

- <span data-ttu-id="2f120-483">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="2f120-483">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="2f120-484">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="2f120-484">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-487">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-487">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2f120-488">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-488">PowerPoint</span></span>

- <span data-ttu-id="2f120-489">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-489">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-14"></a><span data-ttu-id="2f120-491">バージョン 2012: 12 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2f120-491">Version 2012: December 14</span></span>
<span data-ttu-id="2f120-492">*バージョン 2012 (ビルド 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="2f120-492">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-494">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-494">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-495">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-495">Outlook</span></span>

- <span data-ttu-id="2f120-496">**クラウドでの Outlook の設定** [自動応答]、[優先受信トレイ]、[プライバシー] などの Outlook for Windows の設定を選択し、任意の PC でアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="2f120-496">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-499">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-499">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2f120-500">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-500">Office Suite</span></span>

- <span data-ttu-id="2f120-501">最適化されたバイナリ サイズ。</span><span class="sxs-lookup"><span data-stu-id="2f120-501">Optimized binary size.</span></span>


- <span data-ttu-id="2f120-502">Anaheim WebView は、Windows 情報保護 (WIP) をまだサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="2f120-502">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="2f120-503">この修正プログラムを適用すると、Office addin プラットフォームが、WIP が有効な環境でダウンレベルの WebView に戻ります。</span><span class="sxs-lookup"><span data-stu-id="2f120-503">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="2f120-504">お客様のコンピューター環境に応じて、Edge Spartan WebView または Trident WebView のいずれかになります。</span><span class="sxs-lookup"><span data-stu-id="2f120-504">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="2f120-505">ダウンレベル WebViews は、両方とも WIP をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="2f120-505">Both down level WebViews support WIP.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-07"></a><span data-ttu-id="2f120-507">バージョン 2012: 12 月 7 日</span><span class="sxs-lookup"><span data-stu-id="2f120-507">Version 2012: December 07</span></span>
<span data-ttu-id="2f120-508">*バージョン 2012 (ビルド 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="2f120-508">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-510">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-510">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="2f120-511">Teams</span><span class="sxs-lookup"><span data-stu-id="2f120-511">Teams</span></span>

- <span data-ttu-id="2f120-512">**Teams で Windows ネイティブ通知をサポート:** ユーザーはバナーに組み込まれた Teams、または Windows のネイティブ バナーのいずれかを使用して、通知配信の優先手段を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-512">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="2f120-513">**Citrix および VMWare VDI の Teams 会議 2X2 ギャラリー ビュー:** Teams の VDI 2x2 ギャラリー ビュー機能を使用すると、Teams クライアントが VDI 最適化モードの場合、Citrix、VMWare から VDI クライアントの 2x2 ギャラリー ビューで最大 4 人の参加者のビデオを表示できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-513">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="2f120-514">**会議の反応:**  会議の反応は、会議を操作するための新しい方法です。</span><span class="sxs-lookup"><span data-stu-id="2f120-514">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="2f120-515">参加者は、共有されているコンテンツにストリームとして表示される反応を送信できます。また、会議ステージに表示されている場合は、その反応を送信した人物に対しても送信できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-515">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="2f120-516">**Web 会議の Together モードとラージ ギャラリー** ラージ ギャラリーでは、同時に最大 49 の他のユーザーのビデオを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-516">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="2f120-517">このオプションは、少なくとも 10 人のユーザーがカメラをオンにしている場合に使用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-517">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="2f120-518">Together モードを使用すると、会議のすべてのユーザーと同じ共有スペースを使用しているかのように感じられます。</span><span class="sxs-lookup"><span data-stu-id="2f120-518">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="2f120-519">会議に少なくとも 5 人のユーザーがいる場合に、Together モードを使用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-519">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="2f120-520">**コール マージ** コール マージを使用すると、ユーザーは新しい通話または新しい着信を 1-1 またはグループ呼び出しに結合できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-520">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="2f120-521">これは、Teams の VOIP 通話と PSTN 通話に適用されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-521">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="2f120-522">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-522">Visio</span></span>

- <span data-ttu-id="2f120-523">**新しい Azure ステンシルと図形:** 最新の Azure 図を作成するために、多くのステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-523">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="2f120-524">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-524">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-527">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-527">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-528">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-528">Excel</span></span>

- <span data-ttu-id="2f120-529">一部のリボン要素が簡体字中国語でローカライズされていないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-529">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="2f120-530">更新時に Excel が予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-530">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="2f120-531">OneDrive のローカル同期フォルダーからファイルを挿入する際に、「オブジェクトの挿入」コマンドにおいて正しいアイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-531">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="2f120-532">上書きモードで、IME の使用が必要な言語で編集を行うと、パフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-532">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="2f120-533">共同編集時に、一部のユーザーに対して、新しいバージョンのファイルを通知するメッセージ バーが誤って表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-533">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="2f120-534">数式ビューでデータをコピーして貼り付けるときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-534">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="2f120-535">自動保存が無効になった場合に、通知のヘルプ記事へのハイパーリンクが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-535">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="2f120-536">Excel を特定の言語で実行しているときにデータを入力すると、Excel が動作しなくなるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-536">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="2f120-537">この変更により、数式内にフォントが正しく表示されないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-537">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="2f120-538">これにより、Power Pivot がタブ区切りのテキストファイルを正しくインポートできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-538">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-539">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-539">Outlook</span></span>

- <span data-ttu-id="2f120-540">タスク進捗レポートの [宛先] フィールドが空白になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-540">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="2f120-541">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-541">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="2f120-542">Outlook 以外のアプリケーションから Outlook メールを送信するときに問題が発生する原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-542">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="2f120-543">下書きに保存すると、SmartLinks が書式設定を失うという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-543">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="2f120-544">Zip ファイルから開いたメッセージに添付ファイルを追加するときに問題が発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-544">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-545">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-545">PowerPoint</span></span>

- <span data-ttu-id="2f120-546">Word から PowerPoint への数式のコピーと貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-546">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="2f120-547">この変更により、インク分析中のタイムアウトに関連する問題が解決します。</span><span class="sxs-lookup"><span data-stu-id="2f120-547">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="2f120-548">この変更は、アニメーション GIF ユーザー インターフェイスの作成に関する文法エラーに対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-548">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="2f120-549">この変更により、特定のジオメトリで図形の結合操作を適用するときの軌跡の塗りつぶしに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-549">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="2f120-550">この変更により、数式内にフォントが正しく表示されないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-550">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="2f120-551">この変更により、ビデオの読み込み中に発生する可能性のあるエラーの処理に関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-551">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="2f120-552">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (MPG-1、Mpeg-2) でクラッシュする VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-552">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="2f120-553">共同編集者の詳細情報が利用可能な場合、不明だった共同編集者のプレゼンス インジケーターが完全に更新されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-553">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="2f120-554">ルーラーがオンの状態でスライド表示のサイズが変更されるときに、null ポインターが逆に参照されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-554">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="2f120-555">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-555">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-556">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-556">Project</span></span>

- <span data-ttu-id="2f120-557">更新された情報が保存されているはずのプロジェクトをユーザーが開いた際に、更新された情報が見つからないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-557">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="2f120-558">成果物が関連付けられていた SharePoint サイトが存在しなくなった場合に、成果物の依存関係を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-558">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="2f120-559">多くのリソースを持つプロジェクトを開くのに時間がかかるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-559">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="2f120-560">タスクに関連付して、割り当てられていない割り当てが複数存在するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-560">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="2f120-561">大規模なプロジェクトでは、タスク名の入力に非常に時間がかかることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-561">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="2f120-562">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-562">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-563">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-563">Word</span></span>

- <span data-ttu-id="2f120-564">リッチ テキストとして貼り付けるより、通常のテキストとして貼り付けることが推奨されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-564">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="2f120-565">このコンテキスト メニューの修正プログラムでは、テキストとして貼り付けることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-565">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="2f120-566">それ以外の場合、ユーザーはメモ帳などのプレーンテキスト エディターにコピーして、メモ帳から目的のターゲット アプリにコピーする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-566">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="2f120-567">Word から PowerPoint への数式のコピーと貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-567">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="2f120-568">この変更により、ドキュメントを編集するときのカーソルに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-568">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="2f120-569">ズーム中に写真がぼやけてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-569">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="2f120-570">長いハイパーリンクが一部省略されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-570">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-571">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-571">Office Suite</span></span>

- <span data-ttu-id="2f120-572">Office スイートでは、新しいバージョンの Office を特定の古いバージョンの Office の上からインストールすると、レジストリ エントリが存在していないために機能が低下する(Power Query を使用できないなど) という問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-572">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-december-01"></a><span data-ttu-id="2f120-574">バージョン 2011: 12 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2f120-574">Version 2011: December 01</span></span>
<span data-ttu-id="2f120-575">*バージョン 2011 (ビルド 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="2f120-575">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-577">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-577">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-578">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-578">Outlook</span></span>

- <span data-ttu-id="2f120-579">**会議はすべてオンラインで:** 新しい設定により、オンライン会議のスケジュールを簡単に立てれるため、既定ですべての会議をオンラインにできます。</span><span class="sxs-lookup"><span data-stu-id="2f120-579">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-582">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-583">Outlook</span></span>

- <span data-ttu-id="2f120-584">他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-584">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="2f120-585">1 つ以上の署名が構成されているにもかかわらず、ユーザーの署名が署名ドロップダウンに表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-585">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-586">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-586">Project</span></span>

- <span data-ttu-id="2f120-587">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-587">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-24"></a><span data-ttu-id="2f120-589">バージョン 2011: 11 月 24 日</span><span class="sxs-lookup"><span data-stu-id="2f120-589">Version 2011: November 24</span></span>
<span data-ttu-id="2f120-590">*バージョン 2011 (ビルド 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="2f120-590">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-592">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-592">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2f120-593">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-593">Office Suite</span></span>

- <span data-ttu-id="2f120-594">Word から PowerPoint への数式のコピーと貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-594">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-21"></a><span data-ttu-id="2f120-596">バージョン 2011: 11 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2f120-596">Version 2011: November 21</span></span>
<span data-ttu-id="2f120-597">*バージョン 2011 (ビルド 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="2f120-597">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-599">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-599">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2f120-600">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-600">PowerPoint</span></span>

- <span data-ttu-id="2f120-601">**ビデオ ライブラリ:** アプリ内で利用可能な、質の良い無料のビデオ フッテージのライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="2f120-601">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-604">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-604">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-605">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-605">Outlook</span></span>

- <span data-ttu-id="2f120-606">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="2f120-606">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="2f120-607">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-607">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="2f120-608">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="2f120-608">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="2f120-609">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="2f120-609">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="2f120-610">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-610">0 = filetimes are excluded.</span></span> <span data-ttu-id="2f120-611">1 = (既定) filetimes が含まれています</span><span class="sxs-lookup"><span data-stu-id="2f120-611">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="2f120-612">Azure Information Protection の保護ラベルを使用してメッセージに返信すると、インライン画像が表示されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-612">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-18"></a><span data-ttu-id="2f120-614">バージョン 2011: 11 月 18 日</span><span class="sxs-lookup"><span data-stu-id="2f120-614">Version 2011: November 18</span></span>
<span data-ttu-id="2f120-615">*バージョン 2011 (ビルド 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="2f120-615">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="2f120-616">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-616">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="2f120-617">バージョン 2011: 11 月 16 日</span><span class="sxs-lookup"><span data-stu-id="2f120-617">Version 2011: November 16</span></span>
<span data-ttu-id="2f120-618">*バージョン 2011 (ビルド 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="2f120-618">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-620">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-620">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-621">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-621">Outlook</span></span>

- <span data-ttu-id="2f120-622">**同じ署名、すべてのデバイス:** 署名をクラウドに保存し ます。</span><span class="sxs-lookup"><span data-stu-id="2f120-622">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="2f120-623">一度作成して、Outlook を使用するすべての場所で使用します。</span><span class="sxs-lookup"><span data-stu-id="2f120-623">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-626">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-626">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-627">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-627">Outlook</span></span>

- <span data-ttu-id="2f120-628">タスクに対する進捗レポートの送信時に、[宛先] フィールドが空白になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-628">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-629">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-629">PowerPoint</span></span>

- <span data-ttu-id="2f120-630">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (MPG-1、Mpeg-2) でクラッシュする VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-630">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-09"></a><span data-ttu-id="2f120-632">バージョン 2011: 11 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2f120-632">Version 2011: November 09</span></span>
<span data-ttu-id="2f120-633">*バージョン 2011 (ビルド 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="2f120-633">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-635">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-635">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-636">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-636">Excel</span></span>

- <span data-ttu-id="2f120-637">**クエリから Powe rPlatform データフローを作成する**: 新しい Powe rPlatform データフローの作成に使用できる Power Query テンプレートにクエリをエクスポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-637">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-640">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-640">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-641">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-641">Access</span></span>

- <span data-ttu-id="2f120-642">同期済みの OneDrive フォルダーからクエリをエクスポートしようとしたときに、一部のユーザーに "システム リソースの超過" というエラーが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-642">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="2f120-643">フォーム ウィンドウ間で別のフォームに切り替える場合の「自動」切り替えの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-643">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="2f120-644">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-644">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="2f120-645">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-645">Excel</span></span>

- <span data-ttu-id="2f120-646">COM アドインを有効にして SaveAs 操作を行った後、ファイル名が変更されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-646">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="2f120-647">Oracle データベースへの接続を使用する際の Power Pivot の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-647">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="2f120-648">Excel データモデルに不適切なメジャー定義がある場合に、自動保存が誤った、または誤解を招くエラーメッセージを表示して失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-648">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="2f120-649">MTR 計算およびグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) のプロセスがトリガーされたときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-649">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="2f120-650">ユーザーが SharePoint から .atomsvc (UTF8 + BOM) ファイルを直接開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-650">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="2f120-651">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-651">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="2f120-652">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-652">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-653">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-653">Outlook</span></span>

- <span data-ttu-id="2f120-654">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-654">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="2f120-655">画像の添付ファイルをクイック印刷すると、以下のエラーが発生する問題を修正しました。「Windows がこの画像を見つけることができません。</span><span class="sxs-lookup"><span data-stu-id="2f120-655">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="2f120-656">場所を確認してから、もう一度お試しください」。</span><span class="sxs-lookup"><span data-stu-id="2f120-656">Check the location, and then try again".</span></span>


- <span data-ttu-id="2f120-657">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-657">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="2f120-658">会議の場所からコピーした URL をブラウザーなどの別の場所に貼り付けると、URL の末尾にセミコロンが含まれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-658">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="2f120-659">ユーザーが基本認証で Microsoft 365 グループの予定表の予定を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-659">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="2f120-660">ニックネーム キャッシュの読み込み中に Outlook の起動に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-660">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="2f120-661">オプションがグレー表示され、メールボックスの所有者が自分のカレンダーの共有権限を管理できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-661">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="2f120-662">Outlook が制限付きのアクセス許可でメッセージを作成できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-662">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="2f120-663">メールテンプレートを .OFT として保存すると、中国語の文字が疑問符に変わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-663">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-664">PowerPoint</span></span>

- <span data-ttu-id="2f120-665">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-665">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="2f120-666">画像の横のコンテンツ プレースホルダー アイコンにツールヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-666">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="2f120-667">pptsx ファイルで表示されるスライド ショーの保護されたビューで、IRM で保護されたドキュメントの画面キャプチャが許可される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-667">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="2f120-668">デザインウィンドウを閉じるときにグリッド線がスライドからずれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-668">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="2f120-669">スライドショーを 2 台目のモニターに複製する場合、そのスライドショーが他のウィンドウの背面で非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-669">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="2f120-670">選択ウィンドウを開いた状態で画面の記録を停止した後、スライドのスクロールバーが自動的に調整を開始する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-670">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-671">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-671">Project</span></span>

- <span data-ttu-id="2f120-672">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-672">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="2f120-673">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-673">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="2f120-674">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-674">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="2f120-675">リソースエンゲージメントが GUID ではなく名前でリソースを検索する問題を修正しました。同じ名前のリソースが複数ある場合に問題が発生していました。</span><span class="sxs-lookup"><span data-stu-id="2f120-675">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="2f120-676">プロジェクトサイトにタスクリストがあり、タスクリストをグループ化すると、タスクリストをすばやく編集できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-676">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="2f120-677">CSOM を介してエンタープライズリソースを更新すると、リソースの最大単位数が失われることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-677">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-678">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-678">Word</span></span>

- <span data-ttu-id="2f120-679">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-679">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="2f120-680">コメントヒントをクリックしてもズームアウトしてコメントカードが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-680">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="2f120-681">列間の線がずれている場合があるレイアウトの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-681">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="2f120-682">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-682">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="2f120-683">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-683">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="2f120-684">機密度ラベルに透かしが適用される場合がある印刷の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-684">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-685">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-685">Office Suite</span></span>

- <span data-ttu-id="2f120-686">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-686">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="2f120-687">SSO API インタラクティブ サインインがエラー コードを返す問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-687">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-06"></a><span data-ttu-id="2f120-689">バージョン 2010: 11 月 6 日</span><span class="sxs-lookup"><span data-stu-id="2f120-689">Version 2010: November 06</span></span>
<span data-ttu-id="2f120-690">*バージョン 2010 (ビルド 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="2f120-690">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="2f120-691">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-691">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-04"></a><span data-ttu-id="2f120-694">バージョン 2010: 11 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2f120-694">Version 2010: November 04</span></span>
<span data-ttu-id="2f120-695">*バージョン 2010 (ビルド 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="2f120-695">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-697">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-697">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-698">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-698">Excel</span></span>

- <span data-ttu-id="2f120-699">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-699">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="2f120-700">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-700">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="2f120-701">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-701">Outlook</span></span>

- <span data-ttu-id="2f120-702">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-702">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="2f120-703">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-703">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="2f120-704">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-704">PowerPoint</span></span>

- <span data-ttu-id="2f120-705">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-705">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="2f120-706">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-706">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="2f120-707">[ブログの投稿](https://insider.office.com/ja-JP/blog/svg-content-office-third-party-apps)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-707">See details in [blog post](https://insider.office.com/ja-JP/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="2f120-708">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-708">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="2f120-709">[ブログ記事](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-709">See details in [blog post](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="2f120-710">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します</span><span class="sxs-lookup"><span data-stu-id="2f120-710">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="2f120-711">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-711">Word</span></span>

- <span data-ttu-id="2f120-712">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-712">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="2f120-713">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-713">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-716">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-716">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-717">Outlook</span></span>

- <span data-ttu-id="2f120-718">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-718">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-719">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-719">Office Suite</span></span>

- <span data-ttu-id="2f120-720">同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-720">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-27"></a><span data-ttu-id="2f120-722">バージョン 2010: 10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="2f120-722">Version 2010: October 27</span></span>
<span data-ttu-id="2f120-723">*バージョン 2010 (ビルド 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="2f120-723">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-727">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-727">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-728">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-728">Outlook</span></span>

- <span data-ttu-id="2f120-729">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-729">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="2f120-730">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-730">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-24"></a><span data-ttu-id="2f120-732">バージョン 2010: 10 月 24 日</span><span class="sxs-lookup"><span data-stu-id="2f120-732">Version 2010: October 24</span></span>
<span data-ttu-id="2f120-733">*バージョン 2010 (ビルド 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="2f120-733">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-737">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-737">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-738">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-738">Outlook</span></span>

- <span data-ttu-id="2f120-739">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-739">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="2f120-740">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-740">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-741">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-741">Project</span></span>

- <span data-ttu-id="2f120-742">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-742">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="2f120-743">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-743">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-19"></a><span data-ttu-id="2f120-745">バージョン 2010 : 10 月 19 日</span><span class="sxs-lookup"><span data-stu-id="2f120-745">Version 2010: October 19</span></span>
<span data-ttu-id="2f120-746">*バージョン 2010 (ビルド 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="2f120-746">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-748">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-748">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-749">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-749">Outlook</span></span>

- <span data-ttu-id="2f120-750">**メッセージの作成にかかる時間を節約:** Outlook は、メッセージをすばやく作成するのに役立つ提案を作成することを示します。</span><span class="sxs-lookup"><span data-stu-id="2f120-750">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="2f120-751">提案を受け入れるには、Tab キーを使用するだけです。</span><span class="sxs-lookup"><span data-stu-id="2f120-751">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="2f120-752">[ブログ記事](https://insider.office.com/ja-JP/blog/text-predictions-in-word-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-752">See details in [blog post](https://insider.office.com/ja-JP/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="2f120-753">**組み込みの翻訳機能を使用して、言語の壁を取り除く:** 翻訳用のアドインは必要なくなりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-753">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="2f120-754">メッセージを右クリックすると、特定の単語、語句、またはメッセージ全体を翻訳できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-754">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="2f120-755">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-755">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="2f120-756">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新</span><span class="sxs-lookup"><span data-stu-id="2f120-756">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-757">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-757">PowerPoint</span></span>

- <span data-ttu-id="2f120-758">**発表者のコーチでプレゼンテーションを練習する:** 話す速度、特定の単語を使いすぎていないか、ボディーランゲージなど、聴衆の関心を引きつけておくのに役立つ内容についてコーチングを受けます。</span><span class="sxs-lookup"><span data-stu-id="2f120-758">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="2f120-759">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-759">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="2f120-760">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-760">Word</span></span>

- <span data-ttu-id="2f120-761">**Microsoft エディター ウィンドウにデスクトップ用の Word の更新が表示される:** デスクトップ クライアント用の Word エディター ウィンドウの現在のエクスペリエンスをアップグレードしました。</span><span class="sxs-lookup"><span data-stu-id="2f120-761">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="2f120-762">**ワンクリック ライティング候補:** ワンクリックでライティング候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-762">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="2f120-763">更新されたエディターウィンドウを使って、候補間を簡単に移動できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-763">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-766">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-766">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2f120-767">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-767">PowerPoint</span></span>

- <span data-ttu-id="2f120-768">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="2f120-768">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-11"></a><span data-ttu-id="2f120-770">バージョン 2010: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2f120-770">Version 2010: October 11</span></span>
<span data-ttu-id="2f120-771">*バージョン 2010 (ビルド13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="2f120-771">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-773">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-773">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-774">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-774">Excel</span></span>

- <span data-ttu-id="2f120-775">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-775">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="2f120-776">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-776">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="2f120-777">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-777">PowerPoint</span></span>

- <span data-ttu-id="2f120-778">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-778">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="2f120-779">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-779">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="2f120-780">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-780">Word</span></span>

- <span data-ttu-id="2f120-781">**データを悪意のあるファイルから保護する:** Application Guard を使用すると、隔離されたコンテナーで Office ファイルを閲覧、印刷、保存できるようになり、マルウェアからユーザーを保護できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-781">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="2f120-782">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-782">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-785">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-785">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-786">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-786">Access</span></span>

- <span data-ttu-id="2f120-787">スクロール中に保存されたクエリ/リレーションシップ ウィンドウを読み込むときに、スクロールバーの位置が正しく設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-787">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="2f120-788">[テーブルを追加する] 作業ウィンドウに「&」を含む名前が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-788">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="2f120-789">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-789">Excel</span></span>

- <span data-ttu-id="2f120-790">マルチレベル カテゴリの手動間隔がグラフで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-790">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="2f120-791">VBA を使用した、シリーズの最大値、中間値、最小値の色の設定が機能しないという 2D マップ グラフの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-791">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="2f120-792">Excel で 1 つまたは複数の数式を計算しようとする際に発生する、Excelはリソース不足になりましたというエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-792">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="2f120-793">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-793">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="2f120-794">[改ページ プレビュー] が有効になっているときに、大量のデータが含まれているワークシート間を切り替える際に顕著な遅延が発生する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-794">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="2f120-795">データ検証に使用されるテーブルに追加しても、ブック内のすべてのシートのオプションが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-795">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="2f120-796">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-796">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="2f120-797">数式バーに数式を入力したときに、ChartSheet がクラッシュする場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-797">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="2f120-798">デバイスへの接続が失われると (リモート セッションが接続されたり接続が解除されたり、モニターでの変更があった場合など) Excel の関数バーが完全に描画されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-798">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="2f120-799">OneNote</span><span class="sxs-lookup"><span data-stu-id="2f120-799">OneNote</span></span>

- <span data-ttu-id="2f120-800">ユーザーが OutSpace で [ファイル]、[情報] に移動してテキスト ボックスからノートブックの URL を選択してコピーできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-800">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="2f120-801">ノートブックのカラー セレクターで緑色にカーソルを合わせると、ポップアップに「赤チョーク」と表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-801">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="2f120-802">OneNote がカスタム テーマのキャンバスのハイ コントラスト カラーを尊重しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-802">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-803">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-803">Outlook</span></span>

- <span data-ttu-id="2f120-804">件名が空白の場合、自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-804">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="2f120-805">間違ったフォルダー GUID がフォルダーにキャッシュされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-805">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="2f120-806">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2f120-806">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="2f120-807">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-807">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="2f120-808">オンライン共有フォルダーが親フォルダー名を返さない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-808">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="2f120-809">失敗する代わりに、プライマリ アカウントに誤って送信された空のパスを返しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-809">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="2f120-810">[名前を付けて保存] オプションが従来の添付ファイルで使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-810">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="2f120-811">ポリシーを上書きするときに正当化テキストをカスタマイズする方法をユーザーに提供する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-811">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="2f120-812">読み取り専のプレビュー ウィンドウから下書きを再開した後、トラックの変更がオンになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-812">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="2f120-813">優先受信トレイをオフにして並べ替えを行った後に、メールが非表示になるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-813">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="2f120-814">クラウド設定を有効にしているユーザーに対して、2つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-814">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-815">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-815">PowerPoint</span></span>

- <span data-ttu-id="2f120-816">PDF へのエクスポート中に PowerPoint が長方形の箇条書きをエクスポートしなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-816">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="2f120-817">エディターとスライド ショーで GIF のアニメーションが1 回だけしか再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-817">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="2f120-818">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-818">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="2f120-819">最後のスライドを表示していて、[セッションの終了] を押した後、概要が表示される前に次のスライドにスワイプすると、[セッションの終了] ダイアログ ボックスが概要ページにも表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-819">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-820">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-820">Project</span></span>

- <span data-ttu-id="2f120-821">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-821">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="2f120-822">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-822">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="2f120-823">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-823">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="2f120-824">数式を使用してカスタム フィールドを作成し、取得した値を使用している場合、表示の切り替えやプロジェクト/タスクの詳細を開く際にパフォーマンスの遅延が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-824">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="2f120-825">リソース配分状況ビューまたはシート ビューにグループ化を適用してから列を挿入すると、Project がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-825">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-826">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-826">Word</span></span>

- <span data-ttu-id="2f120-827">ワークフロー対応ファイルへのリンクが期待どおりに開かない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-827">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="2f120-828">変更履歴 (挿入/削除) をユーザーがタップすると、コメントがポップアップ表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-828">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="2f120-829">Word でコメントの吹き出しを削除するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-829">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="2f120-830">Outlook でメッセージが [転送不可] に設定される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-830">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="2f120-831">引用と数式を含む Word 文書を保存するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-831">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="2f120-832">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-832">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-833">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-833">Office Suite</span></span>

- <span data-ttu-id="2f120-834">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-834">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="2f120-835">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-835">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-07"></a><span data-ttu-id="2f120-837">バージョン 2009: 10 月 7 日</span><span class="sxs-lookup"><span data-stu-id="2f120-837">Version 2009: October 07</span></span>
<span data-ttu-id="2f120-838">*バージョン 2009 (ビルド 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="2f120-838">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-840">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-840">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-841">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-841">Excel</span></span>

- <span data-ttu-id="2f120-842">**Power Query を使用してデータ型を作成する: Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します**</span><span class="sxs-lookup"><span data-stu-id="2f120-842">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-843">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-843">Outlook</span></span>

- <span data-ttu-id="2f120-844">**文章校正による支援:** Outlook では、入力中に文章校正のエラーが表示されます。シングル クリックで候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-844">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="2f120-845">[ブログの投稿](https://insider.office.com/ja-JP/blog/grammar-and-style-suggestions-available-in-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-845">See details in [blog post](https://insider.office.com/ja-JP/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-848">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-848">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-849">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-849">Outlook</span></span>

- <span data-ttu-id="2f120-850">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-850">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="2f120-851">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-851">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="2f120-852">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-852">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-853">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-853">PowerPoint</span></span>

- <span data-ttu-id="2f120-854">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-854">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-855">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-855">Office Suite</span></span>

- <span data-ttu-id="2f120-856">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-856">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="2f120-857">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-857">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-26"></a><span data-ttu-id="2f120-859">バージョン 2009: 9 月 26　日</span><span class="sxs-lookup"><span data-stu-id="2f120-859">Version 2009: September 26</span></span>
<span data-ttu-id="2f120-860">*バージョン 2009 (ビルド13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="2f120-860">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-862">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-862">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-863">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-863">Outlook</span></span>

- <span data-ttu-id="2f120-864">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-864">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-865">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-865">Project</span></span>

- <span data-ttu-id="2f120-866">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-866">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-21"></a><span data-ttu-id="2f120-868">バージョン 2009: 9 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2f120-868">Version 2009: September 21</span></span>
<span data-ttu-id="2f120-869">*バージョン 2009 (ビルド 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="2f120-869">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-871">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-871">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2f120-872">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-872">Access</span></span>

- <span data-ttu-id="2f120-873">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-873">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-874">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-874">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-875">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-875">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="2f120-876">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-876">Excel</span></span>

- <span data-ttu-id="2f120-877">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-877">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2f120-878">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-878">No conversion required.</span></span><br /><span data-ttu-id="2f120-879">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-879">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2f120-880">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-880">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-881">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-881">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-882">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-882">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="2f120-883">OneNote</span><span class="sxs-lookup"><span data-stu-id="2f120-883">OneNote</span></span>

- <span data-ttu-id="2f120-884">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-884">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-885">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-885">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-886">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-886">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="2f120-887">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-887">Outlook</span></span>

- <span data-ttu-id="2f120-888">**メッセージの所有者として会話を削除する:** この機能を使用すると、メッセージの所有者による会話を削除できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-888">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="2f120-889">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-889">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2f120-890">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-890">No conversion required.</span></span><br /><span data-ttu-id="2f120-891">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-891">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2f120-892">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-892">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-893">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-893">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-894">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-894">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="2f120-895">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-895">PowerPoint</span></span>

- <span data-ttu-id="2f120-896">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-896">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2f120-897">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-897">No conversion required.</span></span><br /><span data-ttu-id="2f120-898">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-898">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2f120-899">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-899">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-900">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-900">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-901">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-901">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="2f120-902">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-902">Project</span></span>

- <span data-ttu-id="2f120-903">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-903">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-904">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-904">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-905">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-905">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="2f120-906">発行者</span><span class="sxs-lookup"><span data-stu-id="2f120-906">Publisher</span></span>

- <span data-ttu-id="2f120-907">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-907">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-908">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-908">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-909">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-909">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="2f120-910">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-910">Visio</span></span>

- <span data-ttu-id="2f120-911">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-911">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-912">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-912">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-913">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-913">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="2f120-914">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-914">Word</span></span>

- <span data-ttu-id="2f120-915">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-915">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2f120-916">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-916">No conversion required.</span></span><br /><span data-ttu-id="2f120-917">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-917">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2f120-918">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-918">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="2f120-919">[ファイル] > [オプション] に移動し、[Office テーマ] の横の [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-919">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="2f120-920">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-920">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-923">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-923">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2f120-924">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-924">PowerPoint</span></span>

- <span data-ttu-id="2f120-925">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-925">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-14"></a><span data-ttu-id="2f120-927">バージョン 2009: 9 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2f120-927">Version 2009: September 14</span></span>
<span data-ttu-id="2f120-928">*バージョン 2009 (ビルド 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="2f120-928">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="2f120-929">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-929">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-10"></a><span data-ttu-id="2f120-932">バージョン 2009: 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2f120-932">Version 2009: September 10</span></span>
<span data-ttu-id="2f120-933">*バージョン 2009 (ビルド 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="2f120-933">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-935">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-935">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-936">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-936">Access</span></span>

- <span data-ttu-id="2f120-937">この問題は解決されましたので、クラッシュが発生しなくなったはずです。</span><span class="sxs-lookup"><span data-stu-id="2f120-937">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="2f120-938">ODBC データベースへの接続がサードパーティ製アプリケーションで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-938">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="2f120-939">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-939">Excel</span></span>

- <span data-ttu-id="2f120-940">LET 関数が含まれているファイルを開くと、以下の警告が表示される問題が修正されました: "ファイル名.xlsx" のコンテンツに問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-940">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="2f120-941">できるだけ多くの内容の復元を試みますか?</span><span class="sxs-lookup"><span data-stu-id="2f120-941">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="2f120-942">このブックの発行元が信頼できる場合は、[はい] をクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="2f120-942">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="2f120-943">ユーザーがかっこを含む数式名を入力し、F1 を介してヘルプを呼び出した場合、その数式に固有のヘルプ トピックが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-943">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="2f120-944">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="2f120-944">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="2f120-945">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-945">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="2f120-946">XLAM アドイン参照と名前付き範囲に関係するクラッシュが修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-946">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="2f120-947">ユーザーが動的配列にカスタム スタイルを適用すると、"配列の一部を変更することはできません" というエラーが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-947">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="2f120-948">これは以前に存在していた制約でしたが、現在は削除されています。</span><span class="sxs-lookup"><span data-stu-id="2f120-948">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="2f120-949">古いバージョンのファイルを復元した後、ボタンに割り当てられたマクロが壊れる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-949">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="2f120-950">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-950">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-951">Outlook</span></span>

- <span data-ttu-id="2f120-952">問題が修正され、グループ ポリシー経由で既定のログ記録オプションを有効または無効にするための柔軟性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-952">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="2f120-953">アシスタントのアクセス許可があるメールボックスと管理者のアクセス許可があるメールボックスの間でメールの下書きを移動した後も、メール送信者の従来のドメイン名が維持されて表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-953">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="2f120-954">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-954">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="2f120-955">1 行リボン (SLR) を有効にした後に VBA コード ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") を実行すると実行時エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-955">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="2f120-956">高解像度 (1750 x 1920 など) と大きなテキストサイズ (175% など) が同時に使用された場合に、[自動応答] ダイアログの [OK] ボタンと [キャンセル] ボタンが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-956">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="2f120-957">会議出席依頼を空の連絡先グループから別の連絡先グループに送信するとクラッシュする状態が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-957">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="2f120-958">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-958">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="2f120-959">アドインが常に有効になっていることがグループ ポリシーで要求される場合に、ユーザーがアドインを無効にすることを防ぐためにアドインの監視が使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-959">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="2f120-960">1 つ以上のメッセージを選択した場合に、OneNote に "転送不可" ポリシーが適用されているメール コンテンツを送信することができるようになっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-960">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="2f120-961">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-961">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="2f120-962">Active Directory の "otherTelephone" および "otherHomePhone" のユーザー アカウント属性が、対応する Outlook LDAP 属性にマッピングされていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-962">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="2f120-963">この変更により、ユーザーがタブを会議ページからスケジュール アシスタント ページに切り替えた後も会議ページが引き続き表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-963">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-964">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-964">PowerPoint</span></span>

- <span data-ttu-id="2f120-965">特定の条件下でリボンまたはタイトル バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-965">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="2f120-966">PowerPoint を起動後にスライドを挿入してコメント ウィンドウを開いて閉じると、縮小版ウィンドウ内のスライドが重なって表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-966">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="2f120-967">ビデオを挿入する機能が無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-967">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="2f120-968">ビデオがスライドショーで自動的に再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-968">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-969">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-969">Project</span></span>

- <span data-ttu-id="2f120-970">リソースに複数のコスト単価テーブルが含まれている場合、残りのコストが正確に計算されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-970">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="2f120-971">SharePoint タスク リストに接続されているプロジェクトのプロジェクト終了日が更新されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-971">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="2f120-972">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-972">Visio</span></span>

- <span data-ttu-id="2f120-973">テキストを配置するとリアルタイムのプレビューがクラッシュする問題がお客様から報告されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-973">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="2f120-974">7 月のフォークで最も多く報告されているクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="2f120-974">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-975">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-975">Word</span></span>

- <span data-ttu-id="2f120-976">ユーザーがコメントをクリックした場合に、コメント カードでコメントのテキストの周囲に枠線が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-976">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="2f120-977">箇条書きのアイコンが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-977">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="2f120-978">コメントの選択時に、ヘッダー/フッターを閉じることができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-978">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="2f120-979">コメントが削除された後に Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-979">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="2f120-980">ユーザーがコメントの下書きを作成して、解決済みのコメントが既に含まれている行にアンカーすると、サイドトラックでは解決済みのコメントに対して正しくない順番で下書きが並べ替えられる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-980">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="2f120-981">ドキュメントの拡大率が 160% より大きく設定され、コメント ウィンドウが表示されていない場合に、フォーカスがコメント ウィンドウに移動しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-981">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="2f120-982">サイドトラックのスクロールが機能しないため、サイドトラックの境界を超えたコメントのスレッドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-982">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="2f120-983">サイドトラック ウィンドウで解決済みのコメントを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-983">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="2f120-984">開いている複数のドキュメントの間で切り替えを行うと、あるドキュメントのコメントが、開かれている別のドキュメントに表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-984">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="2f120-985">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-985">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="2f120-986">メールで箇条書きが正しく表示されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-986">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="2f120-987">AutoOpen が AutoExec. より前に実行されるというマクロの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-987">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-988">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-988">Office Suite</span></span>

- <span data-ttu-id="2f120-989">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-989">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="2f120-990">[図の圧縮] ダイアログで、ユーザーが選択した一部の DPI 設定が保持されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-990">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="2f120-991">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-991">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-september-04"></a><span data-ttu-id="2f120-993">バージョン 2008: 9 月 04 日</span><span class="sxs-lookup"><span data-stu-id="2f120-993">Version 2008: September 04</span></span>
<span data-ttu-id="2f120-994">*バージョン 2008 (ビルド 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="2f120-994">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-996">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-996">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2f120-997">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-997">Office Suite</span></span>

- <span data-ttu-id="2f120-998">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-998">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-september-02"></a><span data-ttu-id="2f120-1000">バージョン 2008: 9 月 02 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1000">Version 2008: September 02</span></span>
<span data-ttu-id="2f120-1001">*バージョン 2008 (ビルド 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1001">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1003">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1003">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1004">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1004">Excel</span></span>

- <span data-ttu-id="2f120-1005">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1005">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="2f120-1006">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1006">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2f120-1007">**Excelペンを使用してすばやく編集する:** ペン ツールを使用すると、データを手書きしてすばやく編集できます</span><span class="sxs-lookup"><span data-stu-id="2f120-1007">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1010">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1010">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1011">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1011">Excel</span></span>

- <span data-ttu-id="2f120-1012">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1012">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-1013">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1013">Word</span></span>

- <span data-ttu-id="2f120-1014">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1014">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-august-27"></a><span data-ttu-id="2f120-1016">バージョン 2008: 8 月 27 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1016">Version 2008: August 27</span></span>
<span data-ttu-id="2f120-1017">*バージョン 2008 (ビルド 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1017">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1021">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1021">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1022">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1022">Outlook</span></span>

- <span data-ttu-id="2f120-1023">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1023">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="2f120-1024">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1024">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="2f120-1025">クラウドの添付ファイルを操作しているときに不定期にクラッシュする場合があった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1025">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="2f120-1026">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1026">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="2f120-1027">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1027">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1028">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1028">Word</span></span>

- <span data-ttu-id="2f120-1029">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレントな保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1029">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="2f120-1030">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1030">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-25"></a><span data-ttu-id="2f120-1032">バージョン 2008: 8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1032">Version 2008: August 25</span></span>
<span data-ttu-id="2f120-1033">*バージョン 2008 (ビルド 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1033">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1035">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1035">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1036">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1036">Outlook</span></span>

- <span data-ttu-id="2f120-1037">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、候補に表示される最も関連性の高いメールが届きます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1037">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1040">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1040">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1041">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1041">Outlook</span></span>

- <span data-ttu-id="2f120-1042">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-1042">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="2f120-1043">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="2f120-1043">Do you want to download them anyway?</span></span> <span data-ttu-id="2f120-1044">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="2f120-1044">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="2f120-1045">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1045">Project</span></span>

- <span data-ttu-id="2f120-1046">リソースに複数のコスト単価表が定義されている場合、残りのコストが常に正しく計算されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1046">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-1047">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1047">Word</span></span>

- <span data-ttu-id="2f120-1048">新しいメールに返信または作成するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1048">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-17"></a><span data-ttu-id="2f120-1050">バージョン 2008: 8 月 17 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1050">Version 2008: August 17</span></span>
<span data-ttu-id="2f120-1051">*バージョン 2008 (ビルド 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1051">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1053">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1053">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1054">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1054">Outlook</span></span>

- <span data-ttu-id="2f120-1055">特定の状況において、代理人が会議を辞退したときに、上司の予定表から削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1055">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="2f120-1056">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1056">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="2f120-1057">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1057">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="2f120-1058">右クリックのコンテキスト メニューが検索コントロールに表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1058">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-11"></a><span data-ttu-id="2f120-1060">バージョン 2008: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1060">Version 2008: August 11</span></span>
<span data-ttu-id="2f120-1061">*バージョン 2008 (ビルド 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1061">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="2f120-1062">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2f120-1062">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1064">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1064">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1065">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1065">Access</span></span>

- <span data-ttu-id="2f120-1066">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="2f120-1066">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="2f120-1067">Office 365 がインストールされている場合、Office エコシステム外に ACE を公開するために、ACE の再頒布可能エンジンをインストールする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-1067">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="2f120-1068">そのため、Office 365 を使用している場合は、ACE の再頒布可能エンジンが不要になったため、結果的にこの問題が発生することはありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-1068">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="2f120-1069">この問題は解決されました。これで、Office のクイック実行アプリケーション以外の ODBC ドライバーを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1069">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="2f120-1070">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1070">Excel</span></span>

- <span data-ttu-id="2f120-1071">グラフ系列の順序を変更した場合、系列に並んだチェックボックスが系列に沿って並び替えられない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1071">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="2f120-1072">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1072">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="2f120-1073">ブックの VBA を介して「ForceFullCalculation」が有効になっていると、グラフが期待どおりに更新されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1073">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="2f120-1074">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1074">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="2f120-1075">OneNote</span><span class="sxs-lookup"><span data-stu-id="2f120-1075">OneNote</span></span>

- <span data-ttu-id="2f120-1076">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="2f120-1076">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1077">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1077">Outlook</span></span>

- <span data-ttu-id="2f120-1078">Outlook で同じメール ドメインから複数のプロファイルを作成することに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1078">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="2f120-1079">共有された予定表の機能強化を利用できないユーザーが、新しく追加した共有予定表を表示できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1079">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="2f120-1080">S/MIME 暗号化メッセージのヘッダーにロック アイコンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1080">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="2f120-1081">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1081">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="2f120-1082">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1082">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="2f120-1083">ユーザーが適切な印刷権限を持っていても、印刷ボタンが無効な状態で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1083">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="2f120-1084">暗号化されずに送信されたときに添付ファイルが S/MIME メッセージから削除される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1084">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="2f120-1085">送信時にプレーン テキストの S/MIME メッセージが文字化けする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1085">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="2f120-1086">暗号化されていない S/MIME メールを送信すると添付ファイルが破損する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1086">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="2f120-1087">送信者から名前を付けて保存のアクセス許可が付与されている場合でも、受信者が権利保護されたメッセージを保存できなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1087">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="2f120-1088">この修正プログラムでは、ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1088">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="2f120-1089">この修正プログラムでは、Outlook のMarkdown コンテンツでは改行が正常に表示されない問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="2f120-1089">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="2f120-1090">一部の言語で一部の高度な検索のオプションのラベルが切り捨てられる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1090">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1091">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1091">PowerPoint</span></span>

- <span data-ttu-id="2f120-1092">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1092">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="2f120-1093">Office ストアへのアクセスが許可されていない場合に、PowerPoint の [フォーム] ボタンでフォームを作成できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1093">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="2f120-1094">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1094">Project</span></span>

- <span data-ttu-id="2f120-1095">[タスク ボード] ビューに一覧表示されているタスクが [リソースの割り当て] ダイアログのタスクと同期していない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1095">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="2f120-1096">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存しようとしても、何も起こらない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1096">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="2f120-1097">複数の依存関係があるタスクをコピーして貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1097">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="2f120-1098">SharePoint のタスク リストで、2番目のタブにあるリボン ボタンが無効になる場合がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1098">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="2f120-1099">Skype</span><span class="sxs-lookup"><span data-stu-id="2f120-1099">Skype</span></span>

- <span data-ttu-id="2f120-1100">ダンス絵文字のスキントーンが中間色に変更されました</span><span class="sxs-lookup"><span data-stu-id="2f120-1100">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="2f120-1101">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-1101">Visio</span></span>

- <span data-ttu-id="2f120-1102">この修正プログラムを適用すると、ユーザーがいずれかのメカニズム (この場合はアドインを使用) によって delete コマンドの実行を停止した場合、メモリがリークすることはなく、コンピューター全体への影響もありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-1102">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1103">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1103">Word</span></span>

- <span data-ttu-id="2f120-1104">テキストとの画像をコメントボックスに貼り付けると Word が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1104">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="2f120-1105">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1105">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="2f120-1106">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="2f120-1106">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="2f120-1107">変更を追跡するコメントが追加された場合に、[変更履歴] ウィンドウが予期せず開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1107">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="2f120-1108">フォーカスがコメント テキスト ボックスにあるときに「エディター」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1108">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="2f120-1109">フォーカスがコメント テキスト ボックスにあるときに「変更履歴と​​コメントの表示」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1109">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="2f120-1110">最後のコメントを削除すると [新しいコメント] ボタンが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1110">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="2f120-1111">変更履歴の記録の[特定のユーザー]オプションが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1111">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="2f120-1112">[挿入]、[リンク] ドロップダウンを通して、ドキュメントへのリンクがコメントボックスに挿入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1112">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="2f120-1113">HTML ファイルを開くときに、時々切断される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1113">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="2f120-1114">ドキュメントを開くとコメントの状態が失われる可能性があるカスタム XML の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1114">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="2f120-1115">ハイパーリンクを含む画像を追加した後に、VBA のハイパーリンク コレクションにあるハイパーリンク数が正しく指定されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1115">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="2f120-1116">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1116">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="2f120-1117">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1117">This is now fixed.</span></span>

- <span data-ttu-id="2f120-1118">ユーザーがタスクバーから新しいアプリ ウィンドウを開いて新しい空白のドキュメントを作成した後、追加のファイルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1118">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="2f120-1119">ユーザーがドキュメントを編集していて権限を失っていた場合、再認証が必要であることをユーザーに通知しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1119">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-05"></a><span data-ttu-id="2f120-1121">バージョン 2007: 8 月 5 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1121">Version 2007: August 05</span></span>
<span data-ttu-id="2f120-1122">*バージョン 2007 (ビルド 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1122">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1126">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1126">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1127">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1127">Outlook</span></span>

- <span data-ttu-id="2f120-1128">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1128">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="2f120-1129">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1129">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-1130">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1130">Project</span></span>

- <span data-ttu-id="2f120-1131">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1131">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-29"></a><span data-ttu-id="2f120-1133">バージョン 2007: 7 月 29 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1133">Version 2007: July 29</span></span>
<span data-ttu-id="2f120-1134">*バージョン 2007 (ビルド 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1134">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1136">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1136">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1137">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1137">Excel</span></span>

- <span data-ttu-id="2f120-1138">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1138">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="2f120-1139">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="2f120-1139">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="2f120-1140">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1140">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="2f120-1141">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1141">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="2f120-1142">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-1142">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1143">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1143">Outlook</span></span>

- <span data-ttu-id="2f120-1144">**検索する場所を選択する:** 新しい検索範囲のドロップ ダウン リストを使用すると、検索結果を簡単に変更したり、現在のフォルダーと現在のメールボックスを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1144">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="2f120-1145">新しい検索についてフィードバックを提供してくれた皆さんに感謝します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1145">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="2f120-1146">このデザインと更新プログラムは、お客様のフィードバックを反映しています。</span><span class="sxs-lookup"><span data-stu-id="2f120-1146">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1147">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1147">Word</span></span>

- <span data-ttu-id="2f120-1148">**最新のコメントによる共同作業の向上:** オブジェクトにコメントを追加したり、同僚に @mention したり、コメント スレッドを解決して共同作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1148">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="2f120-1149">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1149">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1152">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1152">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1153">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1153">Outlook</span></span>

- <span data-ttu-id="2f120-1154">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1154">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="2f120-1155">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1155">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="2f120-1156">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1156">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-27"></a><span data-ttu-id="2f120-1158">バージョン 2007: 7 月 27 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1158">Version 2007: July 27</span></span>
<span data-ttu-id="2f120-1159">*バージョン 2007 (ビルド 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1159">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="2f120-1160">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-1160">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="2f120-1161">バージョン 2007: 7 月 20 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1161">Version 2007: July 20</span></span>
<span data-ttu-id="2f120-1162">*バージョン 2007 (ビルド 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1162">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="2f120-1163">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-1163">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="2f120-1164">バージョン 2007: 7 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1164">Version 2007: July 15</span></span>
<span data-ttu-id="2f120-1165">*バージョン 2007 (ビルド 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1165">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1167">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1167">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1168">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1168">Excel</span></span>

- <span data-ttu-id="2f120-1169">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1169">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="2f120-1170">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1170">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1173">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1173">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1174">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1174">Access</span></span>

- <span data-ttu-id="2f120-1175">リンクされた SQL テーブルが更新された場合、リンクされたテーブル マネージャーが主キーを要求する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1175">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="2f120-1176">クエリ エディターのクエリがスクロールして表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1176">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="2f120-1177">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1177">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="2f120-1178">Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できず、行が削除されたと誤って報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1178">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="2f120-1179">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1179">Excel</span></span>

- <span data-ttu-id="2f120-1180">http または https ベースではない URL が最近使用したリストに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1180">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="2f120-1181">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1181">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="2f120-1182">テーブルに関連付けられたクエリが編集されていない場合でも、特定のバージョンの Excel で作成したデータ モデル テーブルが [テーブル プレビュー] に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1182">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="2f120-1183">[名前の定義] \ [名前の適用] ダイアログの [相対/絶対参照を区別しない] 参照が原因で、数式が機能しなくなります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1183">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="2f120-1184">SharePoint/OneDriveにブックを保存すると、ユーザー設定のリボンタブの CustomUI XML が削除される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1184">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="2f120-1185">ファイルが読み取り専用である場合にのみ、ブックが読み取り専用であった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1185">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="2f120-1186">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1186">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="2f120-1187">レーダー チャートの主要な目盛線が正しく書式設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1187">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="2f120-1188">高度なデータ フィルターをクリアするとテーブルの書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1188">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="2f120-1189">埋め込まれた PDF 文書のフル パスがファイル名だけでなく文書の標題に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1189">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="2f120-1190">Wolfram クラウド コネクターを無効にしてから、Excel ブックを保存してもう一度開くとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1190">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="2f120-1191">ソルバー アドインを有効にして Excel を起動するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1191">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-1192">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1192">Outlook</span></span>

- <span data-ttu-id="2f120-1193">「To」行に 130 人を超える受信者がいる場合に Outlook がハングする問題を修正し、テキストのレンダリングのパフォーマンスも改善しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1193">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="2f120-1194">解像度の異なる複数のモニターを使用している場合に、Input Method Editor (IME) ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1194">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="2f120-1195">2 日を超えるイベントはそれ以降のすべての日に同じ終了時刻を表示するという「To Do バー」の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1195">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="2f120-1196">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501 年 1 月 1 日に設定される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1196">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="2f120-1197">ユーザーが配布リストの「送信者を指定して送信」または「代理送信」ができなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1197">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="2f120-1198">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1198">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="2f120-1199">以前に保存した予定を閉じると、次のエラーが表示される問題を修正しました。「別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。</span><span class="sxs-lookup"><span data-stu-id="2f120-1199">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="2f120-1200">アイテムの既定のフォルダーにコピーしますか?」</span><span class="sxs-lookup"><span data-stu-id="2f120-1200">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="2f120-1201">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1201">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="2f120-1202">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1202">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="2f120-1203">Outlook のユーザーが共有の予定表を使用した後、メッセージ一覧の更新が数分間停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1203">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="2f120-1204">予定表のリマインダーで、1 週間以内に行われる会議の正確な時刻が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1204">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="2f120-1205">メッセージに画像をインラインで挿入し、メッセージを下書きとして保存すると画像のサイズが変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1205">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="2f120-1206">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1206">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="2f120-1207">日本のユーザーに対してミニ カレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1207">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-1208">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1208">PowerPoint</span></span>

- <span data-ttu-id="2f120-1209">ライブの共同編集セッション中に共同編集ギャラリーでユーザーのプレゼンス カラー インジケーターが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1209">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="2f120-1210">スライドのテキスト領域に HTML を貼り付けると、代わりにスライドの上部に作成されたテキスト ボックスに貼り付けられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1210">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="2f120-1211">発表者ビューですべてのスライドを選択し、Alt + Tabを使用して発表者ビューを終了し、スライド ショーに戻って [ショーの終了] をクリックすると、未処理の例外が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1211">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-1212">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1212">Project</span></span>

- <span data-ttu-id="2f120-1213">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1213">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="2f120-1214">URL の末尾が「.com」の場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1214">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="2f120-1215">特定の XML ファイルを開くと、Project がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1215">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="2f120-1216">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1216">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="2f120-1217">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1217">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="2f120-1218">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1218">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="2f120-1219">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1219">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="2f120-1220">固定期間タスクが 100% 完了しているが、実際の完了が指定されていない場合、タスク完了率が 100% 未満として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1220">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="2f120-1221">ベースラインのリセットまたは更新により、時間単位の予算コスト/作業リソースが変更され、ベースラインが誤った予算値を反映する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1221">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="2f120-1222">Government Community Cloud 環境でプロジェクト プランナのリンクが無効になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1222">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="2f120-1223">ライブラリがモダン モードの場合、SharePoint ドキュメント ライブラリから Project ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1223">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-1224">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1224">Word</span></span>

- <span data-ttu-id="2f120-1225">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式設定をクリアする機能が動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1225">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="2f120-1226">スケーラブル ベクター グラフィックス （SVG）に挿入されたテキストを、Word、Excel、または PowerPoint ファイルに挿入し、ファイルを保存して閉じ、再度開いた後、判読できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1226">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="2f120-1227">ルーラーが表示されていないときにテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションが点滅し始める問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1227">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="2f120-1228">共同編集モードで、コメントの返信がコメント ウィンドウに表示されず、変更履歴ウィンドウに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1228">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="2f120-1229">マージの競合があり、ユーザーが既に変更を破棄することを選択している場合の共同編集モード中の問題を修正し、変更を保存または破棄するオプションを表示しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1229">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="2f120-1230">HTML ハイパーリンクの色が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1230">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="2f120-1231">Wordに 50 を超える頻繁に開かれる文書のリストがある場合、文書を保存して開いた後、その文書に変更が加えられていなくても、変更履歴が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1231">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="2f120-1232">共同編集中の自動保存に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1232">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="2f120-1233">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても「WRO0004.docx」というファイル名で保存されるため、その文書を使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1233">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-1234">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1234">Office Suite</span></span>

- <span data-ttu-id="2f120-1235">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります</span><span class="sxs-lookup"><span data-stu-id="2f120-1235">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="2f120-1236">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1236">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="2f120-1237">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1237">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2006-july-09"></a><span data-ttu-id="2f120-1239">バージョン 2006: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1239">Version 2006: July 09</span></span>
<span data-ttu-id="2f120-1240">*バージョン 2006 (ビルド 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1240">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1242">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1242">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1243">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1243">Excel</span></span>

- <span data-ttu-id="2f120-1244">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1244">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="2f120-1245">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1245">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="2f120-1246">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1246">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="2f120-1247">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1247">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="2f120-1248">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1248">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="2f120-1249">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-1249">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="2f120-1250">**Excel のショートカットキー:** 更新された Excel のショートカットキー</span><span class="sxs-lookup"><span data-stu-id="2f120-1250">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1251">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1251">Outlook</span></span>

- <span data-ttu-id="2f120-1252">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="2f120-1252">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="2f120-1253">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1253">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1256">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1256">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1257">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1257">Access</span></span>

- <span data-ttu-id="2f120-1258">この問題は解決されており、ID (オートナンバーなど) フィールドを含むリンクされた SQL テーブルを Access に正常に挿入できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1258">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="2f120-1259">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1259">Excel</span></span>

- <span data-ttu-id="2f120-1260">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1260">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1261">Outlook</span></span>

- <span data-ttu-id="2f120-1262">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1262">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2f120-1263">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1263">Office Suite</span></span>

- <span data-ttu-id="2f120-1264">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="2f120-1264">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="2f120-1265">レジストリ TabProcGrowth の値がREG_SZ型で値 "0" でアドインがアクティブ化されているときに、Windows の Office ホストがクラッシュしていました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1265">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="2f120-1266">このレジストリ ボックスには、4つのパスのいずれかを使用できます。 HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main。この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1266">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-25"></a><span data-ttu-id="2f120-1268">バージョン 2006: 6月 25 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1268">Version 2006: June 25</span></span>
<span data-ttu-id="2f120-1269">*バージョン 2006 (ビルド 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1269">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1271">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1271">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="2f120-1272">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-1272">Visio</span></span>

- <span data-ttu-id="2f120-1273">**Excel で洗練された Visio 図を作成する:** ワークシートのデータに基づいて、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1273">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1276">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1276">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1277">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1277">Access</span></span>

- <span data-ttu-id="2f120-1278">この問題は解決されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1278">This problem is now resolved.</span></span> <span data-ttu-id="2f120-1279">このプロセスでさらに問題が発生した場合は、チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="2f120-1279">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1280">Outlook</span></span>

- <span data-ttu-id="2f120-1281"><span style="display:inline !important;">ドラッグ アンド ドロップによってファイル システムにコピーされた添付<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">ファイルの作成日&nbsp; が、&nbsp;4501年1月1日に設定された問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="2f120-1281"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="2f120-1282"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span></span><span class="sxs-lookup"><span data-stu-id="2f120-1282"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="2f120-1283"><span style="display:inline !important;">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="2f120-1283"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="2f120-1284"><span style="display:inline !important;">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span></span><span class="sxs-lookup"><span data-stu-id="2f120-1284"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-18"></a><span data-ttu-id="2f120-1286">バージョン 2006: 6 月 18 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1286">Version 2006: June 18</span></span>
<span data-ttu-id="2f120-1287">*バージョン 2006 (ビルド 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1287">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1289">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1289">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1290">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1290">Excel</span></span>



- <span data-ttu-id="2f120-1291">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1291">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2f120-1292">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1292">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2f120-1293">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1293">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="2f120-1294">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-1294">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1295">PowerPoint</span></span>

- <span data-ttu-id="2f120-1296">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1296">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2f120-1297">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1297">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2f120-1298">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1298">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="2f120-1299">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-1299">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1300">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1300">Word</span></span>

- <span data-ttu-id="2f120-1301">**ピン留めされたフォルダーに保存**: フォルダーをピン留めすると、Office ファイルの保存が簡単になります。新しいファイルを保存したときに利用できるフォルダーをもっと制御したいというユーザーのフィードバックをいただきました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1301">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2f120-1302">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1302">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2f120-1303">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1303">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="2f120-1304">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-1304">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1307">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1307">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1308">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1308">Excel</span></span>

- <span data-ttu-id="2f120-1309">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1309">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1310">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1310">Outlook</span></span>

- <span data-ttu-id="2f120-1311">クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1311">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="2f120-1312">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1312">Project</span></span>

- <span data-ttu-id="2f120-1313">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1313">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-11"></a><span data-ttu-id="2f120-1315">バージョン 2006: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1315">Version 2006: June 11</span></span>
<span data-ttu-id="2f120-1316">*バージョン 2006 (ビルド 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1316">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1318">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1318">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2f120-1319">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1319">PowerPoint</span></span>

- <span data-ttu-id="2f120-1320">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1320">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="2f120-1321">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1321">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1322">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1322">Word</span></span>

- <span data-ttu-id="2f120-1323">**テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1323">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1326">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1326">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1327">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1327">Excel</span></span>

- <span data-ttu-id="2f120-1328">OneDrive を起動すると Excel がシャットダウンすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1328">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="2f120-1329">グラフの軸にカスタム値が正しく適用されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1329">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="2f120-1330">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1330">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="2f120-1331">使用可能なプリンターのリストでプリンター名が重複する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1331">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="2f120-1332">ユーザーがマージされた列を削除したときのパフォーマンス時間が向上する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1332">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="2f120-1333">アドインは、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」 というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1333">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="2f120-1334">Excelとサード パーティの支援技術アプリケーションの一部との間でフォントを管理する際にメモリが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1334">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="2f120-1335">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1335">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2f120-1336">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1336">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="2f120-1337">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1337">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="2f120-1338">選択ロックがない図形を含むワークシート上で、アドインがホスト アイテムを要求すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1338">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="2f120-1339">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1339">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1340">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1340">Outlook</span></span>

- <span data-ttu-id="2f120-1341">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1341">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="2f120-1342">新しいメール メッセージの作成時にテンプレートを表示するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1342">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="2f120-1343">Outlook バージョン1911以降、ユーザーが Exchange 2010のパブリック フォルダーを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1343">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="2f120-1344">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1344">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="2f120-1345">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1345">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="2f120-1346">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1346">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="2f120-1347">ユーザーが予定表をゲストユーザーと共有できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1347">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="2f120-1348">予定表のアイテムが真夜中にまたがっていると、終日イベントとして表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1348">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="2f120-1349">高 DPI のモニターを使用しているユーザーに対して、フォルダー プロパティの [オンライン アーカイブ] ドロップダウンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1349">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="2f120-1350">ユーザーがフォルダー間でアイテムを移動したときに、「BeforeItemMove」 イベントが正常に起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1350">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="2f120-1351">2つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1351">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="2f120-1352">テキスト形式のメールでハイパーリンクを使用して作業しているときに、Outlook でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1352">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="2f120-1353">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1353">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="2f120-1354">スクリーン リーダーを使用すると、Outlook ユーザーの断続的なハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1354">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="2f120-1355">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1355">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1356">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1356">PowerPoint</span></span>

- <span data-ttu-id="2f120-1357">サーバ構成のファイルをフォームベースの認証で開くときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1357">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="2f120-1358">グラフまたはブックが埋め込まれた PowerPoint ファイルの保存時にエラーが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1358">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="2f120-1359">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1359">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="2f120-1360">マウス ホイールを使用して拡大した後、スライドが中央に配置されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1360">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="2f120-1361">英語スイス (QWERTZ) キーボードを使用すると、キーボード ショートカットとスペル チェックが期待どおりに機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1361">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="2f120-1362">ユーザーによって終了されたコメント ウィンドウが自動的に再起動するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1362">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="2f120-1363">1つのスライドからのスライド エディタが次のスライドに重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1363">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="2f120-1364">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1364">Project</span></span>

- <span data-ttu-id="2f120-1365">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1365">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="2f120-1366">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1366">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="2f120-1367">オプションをクリックするとプロジェクトがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1367">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="2f120-1368">親計画が削除された後、孤立したタスクの削除や再割り当てができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1368">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="2f120-1369">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-1369">Visio</span></span>

- <span data-ttu-id="2f120-1370">依存コードに回帰がありましたが、これは修正されています。</span><span class="sxs-lookup"><span data-stu-id="2f120-1370">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="2f120-1371">これで、SharePoint Onprem で実行されている Visio services の画像が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1371">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1372">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1372">Word</span></span>

- <span data-ttu-id="2f120-1373">コメント ウィンドウのタイムスタンプがシステム ロケールの時間に基づいていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1373">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="2f120-1374">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1374">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="2f120-1375">テキストのコピーと貼り付けがコメント ウィンドウに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1375">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="2f120-1376">コメント内のハイパーリンクが機能しなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1376">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="2f120-1377">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1377">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="2f120-1378">Web アプリとデスクトップ アプリケーションの間のコメントが同期していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1378">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="2f120-1379">100% ズームでコメント ヒントの泡がぼやけて見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1379">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="2f120-1380">空白のドキュメントに新しいコメントを追加しても何も発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1380">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="2f120-1381">予定表用の WordMail に HTML を貼り付けできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1381">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="2f120-1382">共同編集セッションのコメントに返信すると、Word がフリーズすることがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1382">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="2f120-1383">100 個を超えるエントリを含むドキュメントにインデックスを挿入または更新すると、アプリケーションがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1383">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="2f120-1384">ポリシー Word 2007以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集で失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1384">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="2f120-1385">カスタム xml 値を含むファイルを開くのが非常に遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1385">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="2f120-1386">長いパス名 (32K を超える) のファイルが開かず、適切なエラー メッセージが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1386">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2f120-1387">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1387">Office Suite</span></span>

- <span data-ttu-id="2f120-1388">OS のシャットダウン後、InTune を介した Office 365 ProPlus の展開が停止する問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1388">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="2f120-1389">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1389">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2f120-1390">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1390">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-08"></a><span data-ttu-id="2f120-1392">バージョン 2005: 6月 8 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1392">Version 2005: June 08</span></span>
<span data-ttu-id="2f120-1393">*バージョン 2005 (ビルド 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1393">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1395">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1395">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2f120-1396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1396">PowerPoint</span></span>

- <span data-ttu-id="2f120-1397">[フォントの置換] ダイアログボックスで、[フォントの置換] ドロップダウンリストには、システムにインストールされているフォントの代わりにプレゼンテーション内のフォントしか表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1397">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-04"></a><span data-ttu-id="2f120-1399">バージョン 2005: 6月 4 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1399">Version 2005: June 04</span></span>
<span data-ttu-id="2f120-1400">*バージョン 2005 (ビルド 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1400">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1402">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1402">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1403">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1403">Access</span></span>

- <span data-ttu-id="2f120-1404">**時代に追いつきましょう! 日付/時刻の拡張データ型では、より精度が高くなります。:** 改良されたデータ型をご紹介します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1404">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="2f120-1405">SQL との構文の互換性を高め、日付と時刻を含むレコードの精度と詳細レベルを向上させるため、Access に DateTime2 データ型を実装しています。</span><span class="sxs-lookup"><span data-stu-id="2f120-1405">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="2f120-1406">この追加の日付および時間のデータ型には、より大きい日付範囲 (0001-01-01 ～ 9999-12-31) が含まれます。これにより、指定された時間の精度 (秒単位ではなくナノ秒) で提供され、計算を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1406">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="2f120-1407">有効にするには、[新しいフィールド] > [日付と時間の拡張] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1407">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="2f120-1408">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1408">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="2f120-1409">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1409">Excel</span></span>

- <span data-ttu-id="2f120-1410">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1410">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="2f120-1411">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1411">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="2f120-1412">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="2f120-1412">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1413">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1413">Outlook</span></span>

- <span data-ttu-id="2f120-1414">**以前の Outlook セッションからアイテムを素早く再開するオプション:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1414">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1417">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1417">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2f120-1418">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1418">PowerPoint</span></span>

- <span data-ttu-id="2f120-1419">これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1419">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-1420">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1420">Office Suite</span></span>

- <span data-ttu-id="2f120-1421">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1421">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-29"></a><span data-ttu-id="2f120-1423">バージョン 2005: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1423">Version 2005: May 29</span></span>
<span data-ttu-id="2f120-1424">*バージョン 2005 (ビルド 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1424">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1426">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1426">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="2f120-1427">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1427">Excel</span></span>

- <span data-ttu-id="2f120-1428">**シート ビュー:** Excel デスクトップで他のユーザーとの共同作業を行っているときに、並べ替えまたはフィルタリングを行います。</span><span class="sxs-lookup"><span data-stu-id="2f120-1428">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1429">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1429">Outlook</span></span>

- <span data-ttu-id="2f120-1430">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1430">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1433">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1433">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="2f120-1434">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1434">Outlook</span></span>

- <span data-ttu-id="2f120-1435">Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効です」という警告が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1435">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="2f120-1436">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="2f120-1436">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2f120-1437">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1437">Office Suite</span></span>

- <span data-ttu-id="2f120-1438">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1438">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2f120-1439">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1439">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-21"></a><span data-ttu-id="2f120-1441">バージョン 2005: 5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1441">Version 2005: May 21</span></span>
<span data-ttu-id="2f120-1442">*バージョン 2005 (ビルド 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1442">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1446">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1446">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1447">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1447">Excel</span></span>

- <span data-ttu-id="2f120-1448">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1448">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="2f120-1449">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1449">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="2f120-1450">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1450">Outlook</span></span>

- <span data-ttu-id="2f120-1451">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1451">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="2f120-1452">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1452">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-14"></a><span data-ttu-id="2f120-1454">バージョン 2005: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1454">Version 2005: May 14</span></span>
<span data-ttu-id="2f120-1455">*バージョン 2005 (ビルド 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1455">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1457">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1457">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1458">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1458">Excel</span></span>

- <span data-ttu-id="2f120-1459">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1459">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1460">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1460">PowerPoint</span></span>

- <span data-ttu-id="2f120-1461">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1461">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="2f120-1462">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1462">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="2f120-1463">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="2f120-1463">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="2f120-1464">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1464">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="2f120-1465">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1465">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1466">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1466">Word</span></span>

- <span data-ttu-id="2f120-1467">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1467">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1470">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1470">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2f120-1471">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1471">Excel</span></span>

- <span data-ttu-id="2f120-1472">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1472">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="2f120-1473">グラフのデータ テーブルの日付軸の値が正しく表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1473">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="2f120-1474">[ページ レイアウト] または [改ページ プレビュー] に移動した後に、改ページを無効にできなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1474">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="2f120-1475">系列のデータを含む列を非表示にしてから非表示を解除すると、グラフの線のスタイルが失われる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1475">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="2f120-1476">フィルタリングされたリストに列を挿入すると、通常よりも時間がかかってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1476">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="2f120-1477">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1477">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2f120-1478">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1478">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="2f120-1479">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1479">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2f120-1480">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1480">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2f120-1481">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1481">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2f120-1482">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1482">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="2f120-1483">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1483">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="2f120-1484">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1484">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="2f120-1485">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1485">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="2f120-1486">[Invert if negative]\(負の値を反転する\) オプションが有効になっていると、ピボット グラフのカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1486">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="2f120-1487">[Invert if negative]\(負の値を反転する\) オプションが選択されていると、ピボット グラフの単一のデータ ポイントに対するカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1487">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="2f120-1488">この変更により、CSV ファイルで "@" 文字をアップロードすると、その "@" 文字以降の文字列が数式に変換される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1488">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="2f120-1489">SEQUENCE 関数で小数点以下が正しく四捨五入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1489">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="2f120-1490">OneNote</span><span class="sxs-lookup"><span data-stu-id="2f120-1490">OneNote</span></span>

- <span data-ttu-id="2f120-1491">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1491">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1492">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1492">Outlook</span></span>

- <span data-ttu-id="2f120-1493">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1493">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="2f120-1494">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1494">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="2f120-1495">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1495">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="2f120-1496">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1496">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="2f120-1497">Outlook デスクトップ クライアントで、ユーザーがクリックした非常に長いセーフリンクが、切り捨てにより読み込みに失敗する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1497">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="2f120-1498">DBCS (2 バイト文字セット) 文字を含む名前が付けられた Outlook フォルダーが、サーバーと同期するときに断続的に表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1498">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="2f120-1499">この問題が発生する場合は、Outlook を IMAP アカウントを使用して構成し、ロケールが日本語に設定されたシステム上で実行する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1499">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="2f120-1500">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1500">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="2f120-1501">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1501">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="2f120-1502">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1502">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="2f120-1503">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1503">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2f120-1504">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="2f120-1504">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1505">PowerPoint</span></span>

- <span data-ttu-id="2f120-1506">ユーザーがコメントを作成したのに投稿せずにそのコメント ウィンドウを閉じ、新しいウィンドウを開いて、複数のスライドを移動してからそのウィンドウを閉じ、最後に、元のプレゼンテーションでコメント ウィンドウをもう一度開くと、下書きのコメントが利用できなくなっている問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1506">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="2f120-1507">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1507">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="2f120-1508">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1508">Project</span></span>

- <span data-ttu-id="2f120-1509">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1509">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="2f120-1510">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1510">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="2f120-1511">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1511">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2f120-1512">Project が Project Web App に接続されていて、小数点の記号がカンマの場合、タイム ラグを追加する際に TaskDependencies Add メソッドが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1512">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-1513">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1513">Word</span></span>

- <span data-ttu-id="2f120-1514">コラボレーション モードのドキュメントにコメントを挿入しても正常に動作しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1514">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="2f120-1515">この変更により、@メンションがクリックされると連絡先カードが点滅する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1515">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="2f120-1516">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="2f120-1516">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="2f120-1517">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1517">This has been fixed.</span></span>

- <span data-ttu-id="2f120-1518">下書きのコメントを含むドキュメントを閉じようとすると、その下書きのコメントを保存せずにドキュメントを閉じてもよいかユーザーに確認を求める問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1518">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="2f120-1519">このプロンプトをキャンセルすると、ドキュメントが開いたままになるのではなく、閉じられていました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1519">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="2f120-1520">見出しをコピー & ペーストする際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1520">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="2f120-1521">投稿されたコメントを翻訳しようとすると、"Inserting translated text failed" (翻訳されたテキストの挿入に失敗しました) エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1521">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="2f120-1522">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1522">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="2f120-1523">Web ビュー/イマーシブ リーダーでヒントをクリックすると、ヒントが既に表示されている場合でも一番上までスクロールしていました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1523">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="2f120-1524">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1524">This has been fixed.</span></span>

- <span data-ttu-id="2f120-1525">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても WRO0004.docx というファイル名で保存されるため、そのドキュメントを使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1525">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2f120-1526">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1526">Office Suite</span></span>

- <span data-ttu-id="2f120-1527">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1527">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="2f120-1528">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1528">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="2f120-1529">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-1529">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="2f120-1530">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1530">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2f120-1531">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1531">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-11"></a><span data-ttu-id="2f120-1533">バージョン 2004: 5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1533">Version 2004: May 11</span></span>
<span data-ttu-id="2f120-1534">*バージョン 2004 (ビルド 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1534">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1536">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1536">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1537">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1537">Excel</span></span>

- <span data-ttu-id="2f120-1538">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1538">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1539">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1539">Outlook</span></span>

- <span data-ttu-id="2f120-1540">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1540">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="2f120-1541">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1541">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="2f120-1542">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1542">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="2f120-1543">[ブログの投稿](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2f120-1543">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="2f120-1544">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1544">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1545">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1545">PowerPoint</span></span>

- <span data-ttu-id="2f120-1546">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1546">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="2f120-1547">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1547">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="2f120-1548">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1548">Word</span></span>

- <span data-ttu-id="2f120-1549">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1549">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1552">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1552">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1553">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1553">Outlook</span></span>

- <span data-ttu-id="2f120-1554">ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1554">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-04"></a><span data-ttu-id="2f120-1556">バージョン 2004: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1556">Version 2004: May 04</span></span>
<span data-ttu-id="2f120-1557">*バージョン 2004 (ビルド 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1557">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1559">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1559">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1560">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1560">Outlook</span></span>

- <span data-ttu-id="2f120-1561">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1561">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="2f120-1562">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1562">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="2f120-1563">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1563">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="2f120-1564">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1564">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1567">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1567">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2f120-1568">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1568">Office Suite</span></span>

- <span data-ttu-id="2f120-1569">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1569">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-29"></a><span data-ttu-id="2f120-1571">バージョン 2004: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1571">Version 2004: April 29</span></span>
<span data-ttu-id="2f120-1572">*バージョン 2004 (ビルド 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1572">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1574">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1574">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1575">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1575">Outlook</span></span>

- <span data-ttu-id="2f120-1576">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1576">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1579">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1579">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1580">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1580">Outlook</span></span>

- <span data-ttu-id="2f120-1581">Windows の一部のビルドで Outlook がクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1581">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2004-april-25"></a><span data-ttu-id="2f120-1583">バージョン 2004: 4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1583">Version 2004: April 25</span></span>
<span data-ttu-id="2f120-1584">*バージョン 2004 (ビルド 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1584">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1586">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1586">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1587">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1587">Outlook</span></span>

- <span data-ttu-id="2f120-1588">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1588">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="2f120-1589">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1589">Project</span></span>

- <span data-ttu-id="2f120-1590">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1590">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-1591">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1591">Office Suite</span></span>

- <span data-ttu-id="2f120-1592">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1592">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-21"></a><span data-ttu-id="2f120-1594">バージョン 2004: 4 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1594">Version 2004: April 21</span></span>
<span data-ttu-id="2f120-1595">*バージョン 2004 (ビルド 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1595">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1597">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1597">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1598">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1598">Outlook</span></span>

- <span data-ttu-id="2f120-1599">フォルダー ウィンドウの幅が予期せず変更される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1599">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="2f120-1600">Outlook の終了中にユーザーが応答停止を経験する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1600">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-15"></a><span data-ttu-id="2f120-1602">バージョン 2004: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1602">Version 2004: April 15</span></span>
<span data-ttu-id="2f120-1603">*バージョン 2004 (ビルド 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1603">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1605">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1605">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1606">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1606">Excel</span></span>

- <span data-ttu-id="2f120-1607">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1607">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1608">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1608">Outlook</span></span>

- <span data-ttu-id="2f120-1609">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="2f120-1609">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="2f120-1610">望むなら、オフにすることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1610">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1611">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1611">PowerPoint</span></span>

- <span data-ttu-id="2f120-1612">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1612">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1613">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1613">Word</span></span>

- <span data-ttu-id="2f120-1614">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成できます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1614">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="2f120-1615">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1615">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1618">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1618">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1619">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1619">Access</span></span>

- <span data-ttu-id="2f120-1620">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1620">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="2f120-1621">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1621">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="2f120-1622">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1622">Excel</span></span>

- <span data-ttu-id="2f120-1623">シートのセル範囲を選択しているのに、単一セルの選択になってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1623">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="2f120-1624">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1624">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2f120-1625">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1625">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2f120-1626">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1626">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2f120-1627">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1627">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="2f120-1628">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1628">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="2f120-1629">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1629">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="2f120-1630">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1630">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="2f120-1631">X 軸の範囲によっては、グラフのサイズを小さくすると、Excel が応答を停止する場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1631">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="2f120-1632">R1C1 セルの参照が有効になっている Excel シートが共同編集 / 共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動しても、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1632">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="2f120-1633">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1633">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1634">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1634">Outlook</span></span>

- <span data-ttu-id="2f120-1635">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1635">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="2f120-1636">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1636">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="2f120-1637">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1637">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="2f120-1638">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1638">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="2f120-1639">メール メッセージからカテゴリが消えることがあるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1639">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="2f120-1640">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1640">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="2f120-1641">ユーザーが組織フォームのプロパティを表示しようとするとクラッシュするという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1641">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="2f120-1642">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1642">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="2f120-1643">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1643">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2f120-1644">返信の対象のメッセージに対してユーザーが所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1644">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="2f120-1645">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1645">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="2f120-1646">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1646">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="2f120-1647">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1647">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="2f120-1648">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1648">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="2f120-1649">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1649">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-1650">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1650">PowerPoint</span></span>

- <span data-ttu-id="2f120-1651">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1651">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="2f120-1652">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1652">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="2f120-1653">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1653">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="2f120-1654">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1654">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="2f120-1655">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1655">Project</span></span>

- <span data-ttu-id="2f120-1656">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1656">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="2f120-1657">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1657">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2f120-1658">ユーザーがスケジュール グループ内の [タスク] リボンにある [無効化] ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Application (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1658">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="2f120-1659">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1659">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="2f120-1660">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="2f120-1660">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="2f120-1661">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1661">This behavior has been fixed.</span></span>

- <span data-ttu-id="2f120-1662">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1662">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="2f120-1663">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1663">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="2f120-1664">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1664">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="2f120-1665">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1665">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="2f120-1666">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1666">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="2f120-1667">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1667">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="2f120-1668">[フォーム] ビュー内で先行処理 / 後続処理データを編集すると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1668">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="2f120-1669">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1669">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1670">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1670">Word</span></span>

- <span data-ttu-id="2f120-1671">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1671">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="2f120-1672">この変更により、[表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1672">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="2f120-1673">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1673">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="2f120-1674">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1674">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="2f120-1675">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1675">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="2f120-1676">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1676">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="2f120-1677">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1677">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="2f120-1678">この変更により、2 ページ表示で、コメントを作成するとき、コメント アンカーが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1678">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="2f120-1679">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1679">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="2f120-1680">スタイルがリストにリンクされているスタイルの祖先である段落の場合、そのリストの番号が失われる場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1680">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="2f120-1681">この変更により、文書に存在しない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1681">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="2f120-1682">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1682">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="2f120-1683">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1683">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2f120-1684">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1684">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="2f120-1685">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1685">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-14"></a><span data-ttu-id="2f120-1687">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1687">Version 2003: April 14</span></span>
<span data-ttu-id="2f120-1688">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1688">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="2f120-1689">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2f120-1689">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

- <span data-ttu-id="2f120-1691">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-1691">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-09"></a><span data-ttu-id="2f120-1693">バージョン 2003: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1693">Version 2003: April 09</span></span>
<span data-ttu-id="2f120-1694">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1694">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1696">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1696">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1697">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1697">Excel</span></span>

- <span data-ttu-id="2f120-1698">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="2f120-1698">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2f120-1699">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2f120-1699">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1700">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1700">Outlook</span></span>

- <span data-ttu-id="2f120-1701">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="2f120-1701">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2f120-1702">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2f120-1702">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1703">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1703">PowerPoint</span></span>

- <span data-ttu-id="2f120-1704">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="2f120-1704">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2f120-1705">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2f120-1705">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1706">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1706">Word</span></span>

- <span data-ttu-id="2f120-1707">**M365 プレミアム コンテンツ ピッカー:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="2f120-1707">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="2f120-1708">1000 点のロイヤリティ フリーのストック画像、アイコン、ステッカーをご覧ください [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="2f120-1708">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-03"></a><span data-ttu-id="2f120-1712">バージョン 2003: 4 月 3 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1712">Version 2003: April 03</span></span>
<span data-ttu-id="2f120-1713">*バージョン 2003 (ビルド 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1713">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1715">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1715">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1716">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1716">Excel</span></span>

- <span data-ttu-id="2f120-1717">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1717">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1718">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1718">Outlook</span></span>

- <span data-ttu-id="2f120-1719">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1719">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="2f120-1720">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1720">Project</span></span>

- <span data-ttu-id="2f120-1721">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChangeevent が発生します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1721">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1722">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1722">Word</span></span>

- <span data-ttu-id="2f120-1723">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1723">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="2f120-1725">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1725">Version 2003: March 31</span></span>
<span data-ttu-id="2f120-1726">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1726">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1728">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1728">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1729">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1729">Access</span></span>

- <span data-ttu-id="2f120-1730">**[テーブルの追加] 作業ウィンドウ:** Access の新しい [テーブルの追加] 作業ウィンドウを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1730">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="2f120-1731">この機能を使用すると、クエリやリレーションシップ ビューのために [テーブルの表示] ダイアログボックスに移動することなく、クエリ ウィンドウに追加またはそこから削除する 1 つ以上のテーブルを簡単に選択することができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1731">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="2f120-1732">この機能には、リンク テーブルを表示するための新しい [リンク] タブ、現在のリストをフィルター処理するための検索ボックス、"ドラッグ アンド ドロップ" による操作なども含まれます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1732">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1735">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1735">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2f120-1736">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="2f120-1736">Project</span></span>

- <span data-ttu-id="2f120-1737"><span style="display:inline !important;">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="2f120-1737"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="2f120-1739">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1739">Version 2003: March 25</span></span>
<span data-ttu-id="2f120-1740">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1740">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="2f120-1741">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-1741">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="2f120-1742">バージョン 2003: 3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1742">Version 2003: March 23</span></span>
<span data-ttu-id="2f120-1743">*バージョン 2003 (ビルド 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1743">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="2f120-1744">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-1744">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="2f120-1745">バージョン 2003: 3 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1745">Version 2003: March 21</span></span>
<span data-ttu-id="2f120-1746">*バージョン 2003 (ビルド 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1746">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1748">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1748">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1749">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1749">Outlook</span></span>

- <span data-ttu-id="2f120-1750">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="2f120-1750">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="2f120-1751">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1751">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="2f120-1752">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="2f120-1752">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="2f120-1753">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1753">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1754">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1754">PowerPoint</span></span>

- <span data-ttu-id="2f120-1755">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1755">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-16"></a><span data-ttu-id="2f120-1757">Version 2003: March 16</span><span class="sxs-lookup"><span data-stu-id="2f120-1757">Version 2003: March 16</span></span>
<span data-ttu-id="2f120-1758">*バージョン 2003 (ビルド 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1758">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1760">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1760">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1761">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1761">Excel</span></span>

- <span data-ttu-id="2f120-1762">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1762">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1763">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1763">Outlook</span></span>

- <span data-ttu-id="2f120-1764">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1764">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1765">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1765">PowerPoint</span></span>

- <span data-ttu-id="2f120-1766">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1766">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1767">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1767">Word</span></span>

- <span data-ttu-id="2f120-1768">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1768">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2f120-1769">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1769">Office Suite</span></span>

- <span data-ttu-id="2f120-1770">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1770">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="2f120-1771">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1771">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1774">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1774">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1775">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1775">Excel</span></span>

- <span data-ttu-id="2f120-1776">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1776">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1777">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1777">Outlook</span></span>

- <span data-ttu-id="2f120-1778">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1778">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-10"></a><span data-ttu-id="2f120-1780">バージョン 2003: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1780">Version 2003: March 10</span></span>
<span data-ttu-id="2f120-1781">*バージョン 2003 (ビルド 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1781">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="2f120-1782">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2f120-1782">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)
### <a name="feature-updates"></a><span data-ttu-id="2f120-1784">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1784">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1785">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1785">Excel</span></span>
- <span data-ttu-id="2f120-1786">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1786">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2f120-1787">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1787">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a><span data-ttu-id="2f120-1788">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1788">PowerPoint</span></span>
- <span data-ttu-id="2f120-1789">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1789">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2f120-1790">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1790">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a><span data-ttu-id="2f120-1791">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1791">Word</span></span>
- <span data-ttu-id="2f120-1792">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1792">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="2f120-1793">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2f120-1793">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1794">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1794">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1795">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1795">Excel</span></span>

- <span data-ttu-id="2f120-1796">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1796">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2f120-1797">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1797">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="2f120-1798">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1798">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="2f120-1799">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1799">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2f120-1800">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1800">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="2f120-1801">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1801">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="2f120-1802">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1802">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="2f120-1803">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1803">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="2f120-1804">この変更では、アドインによって noSelect ロックがある図形を含むドキュメントまたはワークシートのホスト アイテムが求められるときに、オブジェクト モデルでランタイム エラーが発生する問題および App (Excel、Word) がクラッシュする可能性がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1804">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="2f120-1805">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1805">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="2f120-1806">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1806">Outlook</span></span>

- <span data-ttu-id="2f120-1807">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1807">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="2f120-1808">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1808">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="2f120-1809">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1809">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="2f120-1810">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1810">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="2f120-1811">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1811">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="2f120-1812">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1812">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="2f120-1813">ユーザーが「&quot;空き時間情報オプション&quot;」予定表のアクセス許可ダイアログにアクセスできなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1813">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="2f120-1814">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「&quot;申し訳ございません、このアイテムを開くことができません&quot;」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1814">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="2f120-1815">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1815">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="2f120-1816">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1816">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="2f120-1817">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1817">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="2f120-1818">Outlook ユーザーが設定を同期するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1818">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2f120-1819">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1819">PowerPoint</span></span>

- <span data-ttu-id="2f120-1820">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1820">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="2f120-1821">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1821">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="2f120-1822">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1822">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2f120-1823">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1823">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="2f120-1824">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1824">Project</span></span>

- <span data-ttu-id="2f120-1825">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1825">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="2f120-1826">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1826">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2f120-1827">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1827">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="2f120-1828">Visio</span><span class="sxs-lookup"><span data-stu-id="2f120-1828">Visio</span></span>

- <span data-ttu-id="2f120-1829">Visio デスクトップで開いたファイルに関して、[図形情報] ウィンドウの [図形データ] セクションに矛盾した詳細が表示されていました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1829">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="2f120-1830">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1830">It has now been fixed.</span></span>

- <span data-ttu-id="2f120-1831">何らかのセキュリティ チェックが原因で、2016 より前のバージョンでインポートされたビットマップは表示されていませんでした。</span><span class="sxs-lookup"><span data-stu-id="2f120-1831">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="2f120-1832">この問題は Visio サブスクリプションで修正されました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1832">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1833">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1833">Word</span></span>

- <span data-ttu-id="2f120-1834">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1834">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="2f120-1835">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1835">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="2f120-1836">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1836">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="2f120-1837">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1837">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="2f120-1838">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="2f120-1838">This issue has been fixed.</span></span>

- <span data-ttu-id="2f120-1839">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1839">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="2f120-1840">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1840">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="2f120-1841">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1841">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="2f120-1842">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1842">Office Suite</span></span>

- <span data-ttu-id="2f120-1843">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1843">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="2f120-1844">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="2f120-1844">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="2f120-1845">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1845">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="2f120-1846">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1846">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="2f120-1847">同じ SharePoint ライブラリから Word、Excel、PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1847">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-05"></a><span data-ttu-id="2f120-1849">バージョン 2002: 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1849">Version 2002: March 05</span></span>
<span data-ttu-id="2f120-1850">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1850">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="2f120-1851">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-1851">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="2f120-1852">バージョン 2002: 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1852">Version 2002: March 04</span></span>
<span data-ttu-id="2f120-1853">*バージョン 2002 (ビルド 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1853">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1855">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1855">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="2f120-1856">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1856">Project</span></span>
- <span data-ttu-id="2f120-1857">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1857">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-1858">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1858">Office Suite</span></span>
- <span data-ttu-id="2f120-1859">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1859">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-01"></a><span data-ttu-id="2f120-1861">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1861">Version 2002: March 01</span></span>
<span data-ttu-id="2f120-1862">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1862">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1863">解決した問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1863">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1864">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1864">Outlook</span></span>

- <span data-ttu-id="2f120-1865">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1865">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-24"></a><span data-ttu-id="2f120-1867">バージョン 2002: 2 月 24 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1867">Version 2002: February 24</span></span>
<span data-ttu-id="2f120-1868">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1868">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="2f120-1869">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-1869">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="2f120-1870">バージョン 2002: 2 月 22 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1870">Version 2002: February 22</span></span>
<span data-ttu-id="2f120-1871">*バージョン 2002 (ビルド 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1871">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="2f120-1872">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2f120-1872">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="2f120-1873">バージョン 2002: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1873">Version 2002: February 21</span></span>
<span data-ttu-id="2f120-1874">*バージョン 2002 (ビルド 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1874">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1876">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1876">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1877">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1877">Access</span></span>

- <span data-ttu-id="2f120-1878">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="2f120-1878">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="2f120-1879">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1879">Search and replace text in SQL View.</span></span> <span data-ttu-id="2f120-1880">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1880">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1881">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1881">Outlook</span></span>

- <span data-ttu-id="2f120-1882">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="2f120-1882">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="2f120-1883">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1883">Outlook now detects this and helps you get connected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1886">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1886">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2f120-1887">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1887">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="2f120-1888">CUBEVALUE 関数が間違った結果を返すことがある問題を修正しました。&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="2f120-1888">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="2f120-1889">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1889">Outlook</span></span>

- <span data-ttu-id="2f120-1890">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1890">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="2f120-1891">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1891">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="2f120-1892">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="2f120-1892">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="2f120-1893">黒のテーマを持つユーザーが [&quot;差出人&quot;] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1893">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="2f120-1894"><span style="display:inline !important;">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span></span><span class="sxs-lookup"><span data-stu-id="2f120-1894"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-18"></a><span data-ttu-id="2f120-1896">バージョン 2002: 2 月 18 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1896">Version 2002: February 18</span></span>
<span data-ttu-id="2f120-1897">*バージョン 2002 (ビルド 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1897">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="2f120-1898">バージョン 2002: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2f120-1898">Version 2002: February 11</span></span>
<span data-ttu-id="2f120-1899">*バージョン 2002 (ビルド 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="2f120-1899">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="2f120-1900">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2f120-1900">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2f120-1902">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2f120-1902">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="2f120-1903">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1903">Outlook</span></span>

- <span data-ttu-id="2f120-1904">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="2f120-1904">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="2f120-1905">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1905">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="2f120-1906">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1906">Word</span></span>

- <span data-ttu-id="2f120-1907">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1907">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2f120-1908">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1908">Office Suite</span></span>

- <span data-ttu-id="2f120-1909">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1909">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2f120-1912">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2f120-1912">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2f120-1913">Access</span><span class="sxs-lookup"><span data-stu-id="2f120-1913">Access</span></span>

- <span data-ttu-id="2f120-1914">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1914">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2f120-1915">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1915">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="2f120-1916">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1916">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2f120-1917">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1917">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2f120-1918">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1918">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="2f120-1919">Excel</span><span class="sxs-lookup"><span data-stu-id="2f120-1919">Excel</span></span>

- <span data-ttu-id="2f120-1920">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1920">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="2f120-1921">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1921">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="2f120-1922">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1922">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="2f120-1923">Outlook</span><span class="sxs-lookup"><span data-stu-id="2f120-1923">Outlook</span></span>

- <span data-ttu-id="2f120-1924">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1924">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="2f120-1925">左側のナビゲーション ウィンドウで [お気に入り] に保存したフォルダーが断続的に表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1925">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="2f120-1926">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1926">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="2f120-1927">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1927">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2f120-1928">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1928">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="2f120-1929">アイテム保持ポリシーに基づいて期限切れになるメールに 2 つのラベルが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1929">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="2f120-1930">メールが 1 日で期限切れになることを示すものと、2 日で期限切れになることを示すものです。</span><span class="sxs-lookup"><span data-stu-id="2f120-1930">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="2f120-1931">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1931">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2f120-1932">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2f120-1932">PowerPoint</span></span>

- <span data-ttu-id="2f120-1933">インクが PowerPoint のインク アニメーションで使用すると完全にレンダリングされない、またはスキップされることがある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1933">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="2f120-1934">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1934">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="2f120-1935">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1935">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="2f120-1936">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="2f120-1936">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="2f120-1937">Project</span><span class="sxs-lookup"><span data-stu-id="2f120-1937">Project</span></span>

- <span data-ttu-id="2f120-1938">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1938">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="2f120-1939">Word</span><span class="sxs-lookup"><span data-stu-id="2f120-1939">Word</span></span>

- <span data-ttu-id="2f120-1940">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1940">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="2f120-1941">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1941">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="2f120-1942">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1942">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="2f120-1943">コメントを編集し、テキストをイタリック体にし、それを投稿すると、その後にイタリック体の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1943">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="2f120-1944">反転したページ色を使用する読み取りモードでコメントのヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1944">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="2f120-1945">ドキュメントが共同編集されている場合、ルート コメントの下書き版が保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1945">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="2f120-1946">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="2f120-1946">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="2f120-1947">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1947">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="2f120-1948">コメント コンテキスト メニューのコメント コマンド (コメントの編集、コメントへの返信、コメントの削除、コメントの解決) が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2f120-1948">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2f120-1949">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2f120-1949">Office Suite</span></span>

- <span data-ttu-id="2f120-1950">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1950">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="2f120-1951">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2f120-1951">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

